# **FASE 3: OPERACIÓN Y MONITOREO CONTINUO**

## **Objetivo General**
Mantener la infraestructura de redes y seguridad del cliente operando de manera óptima, cumplir con los SLA comprometidos, detectar y resolver incidentes de forma proactiva, ejecutar mantenimientos preventivos y proporcionar visibilidad constante al cliente sobre el estado de sus servicios. Esta es la fase más larga y donde el proveedor demuestra su valor real día a día.

---

## **1. Desglose Detallado de Tareas**

### **Sección 3.1: Operación Diaria**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.1.1 Revisión matutina de dashboards | Verificar estado general de red, seguridad y servicios al iniciar el día | Ingeniero de Redes | Reporte de estado matutino en Slack | Diaria |
| 3.1.2 Revisión de alertas nocturnas | Analizar y clasificar alertas generadas durante la noche/madrugada | Ingeniero de Redes | Alertas clasificadas y documentadas | Diaria |
| 3.1.3 Verificar estado de backups | Confirmar que los backups automáticos de configuraciones se ejecutaron correctamente | Ingeniero de Redes | Confirmación de backups en log | Diaria |
| 3.1.4 Revisión de logs de seguridad | Analizar logs del SIEM en busca de anomalías, intentos de intrusión o comportamientos sospechosos | Analista de Seguridad | Registro de hallazgos de seguridad | Diaria |
| 3.1.5 Stand-up interno del equipo | Reunión breve para coordinar tareas del día, compartir bloqueos y prioridades | Líder Técnico | Minuta breve de stand-up | Diaria |
| 3.1.6 Atención de tickets e incidencias | Gestionar tickets abiertos, resolver incidencias según prioridad y SLA | Equipo de Soporte | Tickets actualizados/resueltos | Continua |
| 3.1.7 Monitoreo proactivo de capacidad | Verificar uso de CPU, RAM, ancho de banda y storage en equipos críticos | Ingeniero de Redes | Alertas de capacidad si se detectan umbrales | Diaria |
| 3.1.8 Verificar estado de enlaces | Confirmar disponibilidad y rendimiento de enlaces WAN, VPN e internet | Ingeniero de Redes | Estado de enlaces documentado | Diaria |
| 3.1.9 Actualizar bitácora de operaciones | Registrar eventos relevantes del día (cambios, incidentes, observaciones) | Ingeniero de Redes | Bitácora actualizada | Diaria |

---

### **Sección 3.2: Gestión de Incidentes**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.2.1 Recibir y registrar incidentes | Documentar cada incidente reportado por el cliente o detectado por monitoreo | Equipo de Soporte | Ticket de incidente creado | Según ocurra |
| 3.2.2 Clasificar y priorizar incidentes | Asignar severidad (Crítico/Alto/Medio/Bajo) y categoría según matriz de clasificación | Líder Técnico | Incidente clasificado | Según ocurra |
| 3.2.3 Asignar incidente al técnico apropiado | Dirigir el incidente al ingeniero con las competencias adecuadas | Líder Técnico | Incidente asignado | Según ocurra |
| 3.2.4 Diagnosticar causa raíz | Investigar y determinar la causa del incidente | Ingeniero asignado | Diagnóstico documentado | Según SLA |
| 3.2.5 Implementar solución | Ejecutar la corrección o workaround para restaurar el servicio | Ingeniero asignado | Servicio restaurado | Según SLA |
| 3.2.6 Verificar resolución | Confirmar que el servicio funciona correctamente después de la corrección | Ingeniero asignado | Verificación documentada | Según SLA |
| 3.2.7 Comunicar resolución al cliente | Informar al cliente sobre la resolución, causa y acciones tomadas | Gerente de Cuenta | Comunicación enviada | Post-resolución |
| 3.2.8 Documentar incidente completo | Registrar timeline, causa raíz, acciones, lecciones aprendidas | Ingeniero asignado | Ticket cerrado con documentación completa | Post-resolución |
| 3.2.9 Ejecutar post-mortem (incidentes mayores) | Análisis profundo de incidentes críticos para prevenir recurrencia | Líder Técnico | Informe post-mortem | Dentro de 48h del cierre |
| 3.2.10 Implementar acciones preventivas | Ejecutar las mejoras identificadas en el post-mortem | Equipo Técnico | Acciones implementadas y verificadas | Según plan |

---

### **Sección 3.3: Gestión de Cambios**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.3.1 Recibir solicitud de cambio | Registrar solicitudes de cambio del cliente o del equipo interno | Gerente de Proyecto | RFC (Request for Change) registrado | Según ocurra |
| 3.3.2 Evaluar impacto del cambio | Analizar riesgos, servicios afectados, downtime y recursos necesarios | Líder Técnico | Análisis de impacto documentado | Según ocurra |
| 3.3.3 Preparar plan de implementación del cambio | Documentar pasos de ejecución, rollback y verificación | Ingeniero asignado | Plan de cambio completo | Según ocurra |
| 3.3.4 Obtener aprobaciones | Enviar el cambio a aprobación según matriz de autorización | Gerente de Proyecto | Aprobaciones obtenidas | Según ocurra |
| 3.3.5 Programar ventana de mantenimiento | Coordinar fecha y hora para ejecutar el cambio | Gerente de Proyecto | Ventana programada y comunicada | Según ocurra |
| 3.3.6 Ejecutar cambio | Implementar el cambio según el plan aprobado | Ingeniero asignado | Cambio ejecutado | Según ventana |
| 3.3.7 Verificar post-cambio | Confirmar que todo funciona correctamente después del cambio | Ingeniero asignado | Verificación documentada | Post-cambio |
| 3.3.8 Actualizar documentación | Modificar wiki, AS-BUILT, inventario y diagramas según el cambio | Ingeniero asignado | Documentación actualizada | Post-cambio |
| 3.3.9 Cerrar RFC | Documentar resultado final y cerrar la solicitud de cambio | Gerente de Proyecto | RFC cerrado | Post-verificación |

---

### **Sección 3.4: Mantenimiento Preventivo**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.4.1 Aplicar parches de seguridad | Actualizar firmware y software de equipos de red y seguridad | Administrador de Sistemas | Informe de parcheo | Mensual |
| 3.4.2 Revisar reglas de firewall | Auditar y optimizar reglas de firewall, eliminar reglas obsoletas | Analista de Seguridad | Informe de auditoría de reglas | Trimestral |
| 3.4.3 Renovar certificados SSL/TLS | Verificar y renovar certificados antes de su expiración | Administrador de Sistemas | Certificados renovados | Según vencimiento |
| 3.4.4 Limpiar logs antiguos | Archivar o eliminar logs según política de retención | Administrador de Sistemas | Espacio liberado documentado | Mensual |
| 3.4.5 Verificar integridad de backups | Realizar pruebas de restauración de configuraciones de backup | Ingeniero de Redes | Informe de prueba de restore | Mensual |
| 3.4.6 Ejecutar escaneo de vulnerabilidades | Realizar escaneos programados con OpenVAS para detectar nuevas vulnerabilidades | Analista de Seguridad | Informe de vulnerabilidades | Mensual |
| 3.4.7 Revisar políticas de acceso | Auditar cuentas de usuario, permisos y accesos activos | Analista de Seguridad | Informe de auditoría de accesos | Trimestral |
| 3.4.8 Verificar redundancia y failover | Probar mecanismos de alta disponibilidad y conmutación automática | Ingeniero de Redes | Informe de pruebas de failover | Trimestral |
| 3.4.9 Optimizar rendimiento de red | Analizar tráfico, identificar cuellos de botella y optimizar configuraciones | Ingeniero de Redes | Informe de optimización | Trimestral |
| 3.4.10 Revisar capacidad y crecimiento | Analizar tendencias de uso y proyectar necesidades futuras de capacidad | Arquitecto de Redes | Informe de capacity planning | Semestral |
| 3.4.11 Actualizar documentación técnica | Revisar y actualizar wiki, diagramas y procedimientos operativos | Líder Técnico | Documentación revisada | Trimestral |
| 3.4.12 Ejecutar simulacro de DR | Probar el plan de recuperación ante desastres en ambiente controlado | Líder Técnico | Informe de simulacro DR | Semestral |

---

### **Sección 3.5: Gestión de Seguridad Continua**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.5.1 Monitoreo de amenazas | Supervisar feeds de inteligencia de amenazas y correlacionar con la infraestructura del cliente | Analista de Seguridad | Boletín de amenazas relevantes | Diaria |
| 3.5.2 Análisis de eventos de seguridad | Investigar eventos sospechosos detectados por el SIEM | Analista de Seguridad | Eventos analizados y clasificados | Diaria |
| 3.5.3 Gestión de vulnerabilidades | Dar seguimiento a la remediación de vulnerabilidades detectadas en escaneos | Analista de Seguridad | Tracker de vulnerabilidades actualizado | Semanal |
| 3.5.4 Actualizar reglas IDS/IPS | Mantener actualizadas las firmas y reglas de detección de intrusos | Analista de Seguridad | Reglas actualizadas | Semanal |
| 3.5.5 Revisar indicadores de compromiso (IoC) | Buscar IoCs conocidos en los sistemas del cliente | Analista de Seguridad | Informe de búsqueda de IoCs | Semanal |
| 3.5.6 Gestión de incidentes de seguridad | Responder a incidentes de seguridad siguiendo el plan de respuesta | Analista de Seguridad | Informe de incidente de seguridad | Según ocurra |
| 3.5.7 Auditoría de compliance | Verificar cumplimiento continuo con frameworks requeridos (ISO, NIST, PCI-DSS) | CISO | Informe de compliance | Trimestral |
| 3.5.8 Ejecutar pruebas de phishing (si aplica) | Realizar campañas de concientización de seguridad para usuarios del cliente | Analista de Seguridad | Informe de campaña de phishing | Trimestral |
| 3.5.9 Revisar y actualizar políticas de seguridad | Actualizar políticas según nuevas amenazas o cambios regulatorios | CISO | Políticas actualizadas | Semestral |
| 3.5.10 Ejecutar pentesting periódico | Pruebas de penetración programadas para validar postura de seguridad | Analista de Seguridad | Informe de pentesting | Semestral |

---

### **Sección 3.6: Reportería y Comunicación con el Cliente**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.6.1 Enviar reporte diario de estado | Resumen breve del estado de la infraestructura al contacto técnico | Ingeniero de Redes | Reporte diario en Slack | Diaria |
| 3.6.2 Realizar reunión operativa semanal | Revisión de incidentes, cambios pendientes, métricas operativas | Líder Técnico | Minuta de reunión semanal | Semanal |
| 3.6.3 Generar informe semanal de incidentes | Compilar estadísticas de incidentes, tiempos de resolución y tendencias | Líder Técnico | Informe semanal PDF | Semanal |
| 3.6.4 Generar informe mensual de SLA | Reporte completo de cumplimiento de SLA con métricas detalladas | Gerente de Cuenta | Informe mensual de SLA | Mensual |
| 3.6.5 Realizar comité ejecutivo mensual | Presentación al sponsor del cliente con resultados, mejoras y roadmap | Gerente de Cuenta | Presentación ejecutiva PPT | Mensual |
| 3.6.6 Generar informe mensual de seguridad | Reporte de eventos de seguridad, vulnerabilidades y cumplimiento | Analista de Seguridad | Informe de seguridad PDF | Mensual |
| 3.6.7 Generar informe trimestral ejecutivo | Análisis de tendencias, recomendaciones estratégicas y planificación | Gerente de Cuenta | Informe trimestral PPT/PDF | Trimestral |
| 3.6.8 Encuesta de satisfacción del cliente | Recopilar feedback del cliente sobre la calidad del servicio | Gerente de Cuenta | Resultados de encuesta | Trimestral |
| 3.6.9 Actualizar roadmap de mejoras | Revisar y actualizar el plan de mejoras continuas con el cliente | Gerente de Cuenta | Roadmap actualizado | Trimestral |

---

### **Sección 3.7: Gestión del Conocimiento**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Frecuencia** |
|-----------|--------------------------|-----------------|----------------|----------------|
| 3.7.1 Actualizar base de conocimiento | Documentar soluciones a problemas frecuentes en la wiki del cliente | Equipo Técnico | Artículos KB creados/actualizados | Continua |
| 3.7.2 Revisar y mejorar playbooks | Actualizar playbooks de respuesta basado en incidentes reales | Líder Técnico | Playbooks actualizados | Mensual |
| 3.7.3 Documentar workarounds conocidos | Registrar soluciones temporales para problemas recurrentes | Equipo Técnico | Workarounds documentados | Continua |
| 3.7.4 Capacitación continua del equipo | Sesiones de formación sobre nuevas tecnologías, amenazas o herramientas | Líder Técnico | Registro de capacitación | Mensual |
| 3.7.5 Compartir lecciones aprendidas | Difundir aprendizajes de incidentes o proyectos al equipo | Líder Técnico | Sesión de lecciones aprendidas | Mensual |

---

## **2. Templates Detallados para la Fase 3**

### **Template 1: Reporte Diario de Operación**

```markdown
# 📊 REPORTE DIARIO DE OPERACIÓN
## Cliente: [Nombre] | Fecha: [DD/MM/YYYY]
## Turno: [Matutino/Vespertino/Nocturno]
## Operador: [Nombre]

---

### ESTADO GENERAL: 🟢 Normal / 🟡 Degradado / 🔴 Crítico

### 1. RESUMEN DE INFRAESTRUCTURA
| Componente | Estado | Disponibilidad | Notas |
|-----------|:------:|:--------------:|-------|
| Red LAN | 🟢/🟡/🔴 | 100% | |
| Red WAN / Internet | 🟢/🟡/🔴 | 100% | |
| Firewall | 🟢/🟡/🔴 | 100% | |
| VPN Site-to-Site | 🟢/🟡/🔴 | 100% | |
| VPN Remote Access | 🟢/🟡/🔴 | 100% | |
| Wi-Fi | 🟢/🟡/🔴 | 100% | |
| IDS/IPS | 🟢/🟡/🔴 | 100% | |
| SIEM | 🟢/🟡/🔴 | 100% | |
| Monitoreo | 🟢/🟡/🔴 | 100% | |

### 2. INCIDENTES DEL DÍA
| # | Ticket | Severidad | Descripción | Estado | Tiempo Resolución |
|---|--------|:---------:|-------------|:------:|:-----------------:|
| 1 | INC-XXX | 🔴/🟠/🟡/🔵 | | Abierto/Resuelto | HH:MM |

**Total incidentes:** [X] | **Resueltos:** [X] | **Pendientes:** [X]

### 3. ALERTAS RELEVANTES
| Hora | Alerta | Severidad | Dispositivo | Acción Tomada |
|------|--------|:---------:|-------------|---------------|
| HH:MM | | | | |

**Total alertas:** [X] | **Críticas:** [X] | **Falsas positivas:** [X]

### 4. CAMBIOS EJECUTADOS
| # | RFC | Descripción | Resultado | Ejecutado por |
|---|-----|-------------|:---------:|---------------|
| 1 | CHG-XXX | | ✅/❌ | |

### 5. MÉTRICAS DE RENDIMIENTO
| Métrica | Valor Actual | Umbral | Estado |
|---------|:------------:|:------:|:------:|
| Uso CPU Firewall | % | <80% | 🟢/🟡/🔴 |
| Uso RAM Firewall | % | <85% | 🟢/🟡/🔴 |
| Ancho de Banda WAN | Mbps | | 🟢/🟡/🔴 |
| Latencia WAN | ms | <50ms | 🟢/🟡/🔴 |
| Sesiones activas FW | | | 🟢/🟡/🔴 |

### 6. BACKUPS
| Sistema | Hora Ejecución | Resultado | Tamaño |
|---------|:--------------:|:---------:|:------:|
| Oxidized (configs) | HH:MM | ✅/❌ | |
| Wazuh (logs) | HH:MM | ✅/❌ | |

### 7. TAREAS PENDIENTES PARA MAÑANA
| # | Tarea | Prioridad | Asignado a |
|---|-------|:---------:|------------|
| 1 | | | |

### 8. OBSERVACIONES
> [Cualquier observación relevante del día]

---
**Elaborado por:** [Nombre] | **Hora:** [HH:MM]
**Siguiente turno:** [Nombre del operador]
```

---

### **Template 2: Ticket de Incidente**

```markdown
# 🚨 TICKET DE INCIDENTE
## ID: INC-[YYYY]-[NNNN]
## Cliente: [Nombre] | Proyecto: [Código]

---

### INFORMACIÓN DEL INCIDENTE
| Campo | Detalle |
|-------|---------|
| **Fecha/Hora de detección** | [DD/MM/YYYY HH:MM] |
| **Reportado por** | [ ] Monitoreo automático [ ] Cliente [ ] Equipo interno |
| **Nombre del reportante** | [Nombre] |
| **Canal de reporte** | [ ] Slack [ ] Email [ ] Teléfono [ ] Ticket [ ] Monitoreo |
| **Severidad** | [ ] 🔴 Crítica [ ] 🟠 Alta [ ] 🟡 Media [ ] 🔵 Baja |
| **Categoría** | [ ] Red [ ] Seguridad [ ] VPN [ ] Wi-Fi [ ] Firewall [ ] Otro |
| **Servicio afectado** | [Nombre del servicio] |
| **Impacto** | [ ] Total [ ] Parcial [ ] Mínimo |
| **Usuarios afectados** | [Número / Departamento] |
| **Asignado a** | [Nombre del técnico] |

### SLA APLICABLE
| Métrica | Objetivo | Tiempo Transcurrido | Estado |
|---------|:--------:|:-------------------:|:------:|
| Tiempo de respuesta | [X min/h] | | 🟢/🟡/🔴 |
| Tiempo de resolución | [X h] | | 🟢/🟡/🔴 |

### DESCRIPCIÓN DEL INCIDENTE
> [Descripción detallada de lo que está ocurriendo.
> Incluir mensajes de error, comportamiento observado,
> y cualquier información relevante]

### SISTEMAS/EQUIPOS AFECTADOS
| Equipo | IP | Tipo | Ubicación | Estado |
|--------|----|----|-----------|:------:|
| | | | | 🔴 Down / 🟡 Degradado |

### TIMELINE DEL INCIDENTE
| Fecha/Hora | Acción | Responsable | Resultado |
|:----------:|--------|-------------|-----------|
| DD/MM HH:MM | Incidente detectado | [Sistema/Persona] | |
| DD/MM HH:MM | Primer diagnóstico | [Nombre] | |
| DD/MM HH:MM | Escalamiento a Nivel 2 | [Nombre] | |
| DD/MM HH:MM | Solución implementada | [Nombre] | |
| DD/MM HH:MM | Servicio restaurado | [Nombre] | |
| DD/MM HH:MM | Verificación completada | [Nombre] | |
| DD/MM HH:MM | Cliente notificado | [Nombre] | |
| DD/MM HH:MM | Ticket cerrado | [Nombre] | |

### DIAGNÓSTICO
> [Análisis técnico del problema]
> 
> **Causa raíz identificada:**
> [Descripción de la causa raíz]
> 
> **Evidencia:**
> [Logs, screenshots, outputs de comandos]

### SOLUCIÓN APLICADA
> [Descripción detallada de la solución implementada]
> 
> **Tipo de solución:**
> [ ] Definitiva [ ] Workaround temporal
> 
> **Comandos/Configuraciones aplicadas:**
> ```
> [Incluir comandos o cambios realizados]
> ```

### VERIFICACIÓN POST-RESOLUCIÓN
| Verificación | Resultado | Hora |
|-------------|:---------:|:----:|
| Servicio accesible | ✅/❌ | |
| Performance normal | ✅/❌ | |
| Sin alertas en monitoreo | ✅/❌ | |
| Sin efectos colaterales | ✅/❌ | |
| Cliente confirma resolución | ✅/❌ | |

### COMUNICACIÓN AL CLIENTE
> **Mensaje enviado:**
> "[Hora] Estimado [Cliente], le informamos que el incidente 
> [INC-XXX] ha sido resuelto. 
> 
> Causa: [Resumen breve]
> Solución: [Resumen breve]
> Duración total: [HH:MM]
> 
> Si experimenta algún problema adicional, no dude en contactarnos."

### ACCIONES PREVENTIVAS
| # | Acción | Responsable | Fecha Límite | Estado |
|---|--------|-------------|:------------:|:------:|
| 1 | | | | ⬜ Pendiente |
| 2 | | | | ⬜ Pendiente |

### CLASIFICACIÓN FINAL
| Campo | Valor |
|-------|-------|
| **Causa raíz categoría** | [ ] Hardware [ ] Software [ ] Configuración [ ] Red [ ] Seguridad [ ] Externo [ ] Humano |
| **Recurrente** | [ ] Sí [ ] No | 
| **Requiere post-mortem** | [ ] Sí [ ] No |
| **Requiere cambio en KB** | [ ] Sí [ ] No |

### MÉTRICAS FINALES
| Métrica | Valor | Dentro de SLA |
|---------|:-----:|:-------------:|
| Tiempo de detección | HH:MM | ✅/❌ |
| Tiempo de respuesta | HH:MM | ✅/❌ |
| Tiempo de resolución | HH:MM | ✅/❌ |
| Tiempo total de afectación | HH:MM | |

---
**Cerrado por:** [Nombre] | **Fecha de cierre:** [DD/MM/YYYY HH:MM]
**Revisado por:** [Líder Técnico] | **Fecha:** [DD/MM/YYYY]
```

---

### **Template 3: Informe Mensual de SLA**

```markdown
# 📈 INFORME MENSUAL DE SLA
## Cliente: [Nombre] | Proyecto: [Código]
## Período: [Mes YYYY]
## Fecha de emisión: [DD/MM/YYYY]

---

### RESUMEN EJECUTIVO
> [Resumen de 1 párrafo sobre el cumplimiento general del mes]

### 1. CUMPLIMIENTO DE SLA

#### 1.1 Disponibilidad de Servicios
| Servicio | SLA Objetivo | Disponibilidad Real | Downtime | Cumplimiento |
|----------|:------------:|:-------------------:|:--------:|:------------:|
| Red LAN | 99.9% | % | HH:MM | ✅/❌ |
| Red WAN | 99.9% | % | HH:MM | ✅/❌ |
| Firewall | 99.99% | % | HH:MM | ✅/❌ |
| VPN S2S | 99.9% | % | HH:MM | ✅/❌ |
| VPN RA | 99.5% | % | HH:MM | ✅/❌ |
| Wi-Fi | 99.5% | % | HH:MM | ✅/❌ |
| Internet | 99.9% | % | HH:MM | ✅/❌ |
| **PROMEDIO** | **99.9%** | **%** | | |

> 📊 **Gráfico:** [Insertar gráfico de barras de disponibilidad por servicio]
> 📈 **Tendencia:** [Insertar línea de tendencia últimos 6 meses]

#### 1.2 Tiempo de Respuesta a Incidentes
| Severidad | SLA Objetivo | Promedio Real | Mejor | Peor | Cumplimiento |
|:---------:|:------------:|:-------------:|:-----:|:----:|:------------:|
| 🔴 Crítica | 15 min | min | min | min | ✅/❌ ([X]/[X]) |
| 🟠 Alta | 1 hora | min | min | min | ✅/❌ ([X]/[X]) |
| 🟡 Media | 4 horas | h | h | h | ✅/❌ ([X]/[X]) |
| 🔵 Baja | 8 horas | h | h | h | ✅/❌ ([X]/[X]) |

#### 1.3 Tiempo de Resolución de Incidentes
| Severidad | SLA Objetivo | Promedio Real | Mejor | Peor | Cumplimiento |
|:---------:|:------------:|:-------------:|:-----:|:----:|:------------:|
| 🔴 Crítica | 4 horas | h | h | h | ✅/❌ ([X]/[X]) |
| 🟠 Alta | 8 horas | h | h | h | ✅/❌ ([X]/[X]) |
| 🟡 Media | 24 horas | h | h | h | ✅/❌ ([X]/[X]) |
| 🔵 Baja | 48 horas | h | h | h | ✅/❌ ([X]/[X]) |

### 2. ESTADÍSTICAS DE INCIDENTES

#### 2.1 Resumen General
| Métrica | Valor | vs Mes Anterior | Tendencia |
|---------|:-----:|:---------------:|:---------:|
| Total de incidentes | | +/-X | 📈/📉 |
| Incidentes críticos | | +/-X | 📈/📉 |
| Incidentes resueltos | | +/-X | 📈/📉 |
| Incidentes pendientes | | +/-X | 📈/📉 |
| Tiempo medio de resolución (MTTR) | h | +/-X | 📈/📉 |
| Tiempo medio entre fallas (MTBF) | h | +/-X | 📈/📉 |

#### 2.2 Incidentes por Categoría
| Categoría | Cantidad | Porcentaje | vs Mes Anterior |
|-----------|:--------:|:----------:|:---------------:|
| Red | | % | |
| Seguridad | | % | |
| Firewall | | % | |
| VPN | | % | |
| Wi-Fi | | % | |
| Hardware | | % | |
| Software | | % | |
| Externo (ISP) | | % | |
| **Total** | | **100%** | |

> 📊 **Gráfico:** [Pie chart de distribución por categoría]

#### 2.3 Incidentes por Causa Raíz
| Causa Raíz | Cantidad | Acciones Tomadas |
|------------|:--------:|------------------|
| Fallo de hardware | | |
| Error de configuración | | |
| Ataque de seguridad | | |
| Fallo de ISP | | |
| Capacidad insuficiente | | |
| Bug de software | | |
| Error humano | | |

#### 2.4 Top 5 Incidentes del Mes
| # | ID | Severidad | Descripción | Causa Raíz | Duración | Impacto |
|---|-----|:---------:|-------------|------------|:--------:|---------|
| 1 | INC-XXX | 🔴 | | | HH:MM | |
| 2 | INC-XXX | 🟠 | | | HH:MM | |

### 3. CAMBIOS REALIZADOS
| # | RFC | Descripción | Tipo | Resultado | Fecha |
|---|-----|-------------|:----:|:---------:|:-----:|
| 1 | CHG-XXX | | Estándar/Normal/Emergencia | ✅/❌ | DD/MM |

**Total cambios:** [X] | **Exitosos:** [X] | **Fallidos:** [X] | **Tasa éxito:** [X]%

### 4. SEGURIDAD

#### 4.1 Eventos de Seguridad
| Métrica | Valor | vs Mes Anterior |
|---------|:-----:|:---------------:|
| Eventos totales procesados por SIEM | | |
| Alertas de seguridad generadas | | |
| Intentos de intrusión bloqueados | | |
| Malware detectado y neutralizado | | |
| Intentos de phishing detectados | | |
| Vulnerabilidades nuevas detectadas | | |
| Vulnerabilidades remediadas | | |
| Vulnerabilidades pendientes | | |

#### 4.2 Estado de Vulnerabilidades
| Severidad | Nuevas | Remediadas | Pendientes | Edad Promedio |
|:---------:|:------:|:----------:|:----------:|:-------------:|
| Crítica | | | | días |
| Alta | | | | días |
| Media | | | | días |
| Baja | | | | días |

### 5. MANTENIMIENTO PREVENTIVO
| Actividad | Programada | Ejecutada | Resultado | Próxima |
|-----------|:----------:|:---------:|:---------:|:-------:|
| Parches de seguridad | DD/MM | DD/MM | ✅/❌ | DD/MM |
| Escaneo vulnerabilidades | DD/MM | DD/MM | ✅/❌ | DD/MM |
| Prueba de backups | DD/MM | DD/MM | ✅/❌ | DD/MM |
| Revisión de reglas FW | DD/MM | DD/MM | ✅/❌ | DD/MM |
| Prueba de failover | DD/MM | DD/MM | ✅/❌ | DD/MM |

### 6. MÉTRICAS DE RENDIMIENTO
| Métrica | Promedio | Máximo | Mínimo | Tendencia |
|---------|:--------:|:------:|:------:|:---------:|
| Uso CPU Firewall | % | % | % | 📈/📉 |
| Uso RAM Firewall | % | % | % | 📈/📉 |
| Ancho de banda WAN (pico) | Mbps | Mbps | Mbps | 📈/📉 |
| Latencia WAN promedio | ms | ms | ms | 📈/📉 |
| Throughput LAN | Gbps | Gbps | Gbps | 📈/📉 |
| Sesiones concurrentes FW | | | | 📈/📉 |

> 📊 **Gráficos:** [Insertar gráficos de tendencia de rendimiento]

### 7. CUMPLIMIENTO GENERAL DE SLA
| SLA | Objetivo | Real | Estado |
|-----|:--------:|:----:|:------:|
| Disponibilidad general | 99.9% | % | ✅/❌ |
| Tiempo de respuesta (promedio) | Según severidad | | ✅/❌ |
| Tiempo de resolución (promedio) | Según severidad | | ✅/❌ |
| Tasa de resolución en primer contacto | 70% | % | ✅/❌ |
| Satisfacción del cliente | ≥ 4/5 | /5 | ✅/❌ |

### CUMPLIMIENTO GLOBAL DEL MES: [X]% ✅

### 8. RECOMENDACIONES
| # | Recomendación | Prioridad | Impacto Esperado | Esfuerzo |
|---|---------------|:---------:|------------------|:--------:|
| 1 | | | | |

### 9. PLAN PARA EL PRÓXIMO MES
| # | Actividad | Responsable | Fecha |
|---|-----------|-------------|:-----:|
| 1 | | | |

---
**Elaborado por:** [Nombre] | [Cargo]
**Revisado por:** [Nombre] | [Cargo]
**Presentado en comité ejecutivo:** [DD/MM/YYYY]
```

---

### **Template 4: Informe Post-Mortem de Incidente Mayor**

```markdown
# 🔍 INFORME POST-MORTEM
## Incidente: INC-[YYYY]-[NNNN]
## Cliente: [Nombre] | Proyecto: [Código]
## Fecha del incidente: [DD/MM/YYYY]
## Fecha del post-mortem: [DD/MM/YYYY]
## Clasificación: CONFIDENCIAL

---

### RESUMEN EJECUTIVO
> [Resumen de 1 párrafo: qué pasó, cuánto duró, 
> qué se afectó y cómo se resolvió]

### 1. DATOS DEL INCIDENTE
| Campo | Valor |
|-------|-------|
| **ID del Incidente** | INC-YYYY-NNNN |
| **Severidad** | 🔴 Crítica |
| **Fecha/Hora de inicio** | DD/MM/YYYY HH:MM |
| **Fecha/Hora de detección** | DD/MM/YYYY HH:MM |
| **Fecha/Hora de resolución** | DD/MM/YYYY HH:MM |
| **Duración total** | HH:MM |
| **Tiempo de detección** | HH:MM |
| **Tiempo de respuesta** | HH:MM |
| **Tiempo de resolución** | HH:MM |
| **SLA cumplido** | ✅ Sí / ❌ No |
| **Servicios afectados** | [Lista] |
| **Usuarios afectados** | [Número] |
| **Impacto en negocio** | [Descripción del impacto] |

### 2. TIMELINE DETALLADO
| Hora (UTC) | Evento | Acción | Responsable |
|:----------:|--------|--------|-------------|
| HH:MM | Inicio del incidente | - | - |
| HH:MM | Alerta detectada por [sistema] | Verificar alerta | [Nombre] |
| HH:MM | Confirmación de incidente | Iniciar diagnóstico | [Nombre] |
| HH:MM | Notificación al cliente | Comunicar vía Slack | [Nombre] |
| HH:MM | Escalamiento a Nivel 2 | Involucrar a [Nombre] | [Nombre] |
| HH:MM | Causa raíz identificada | - | [Nombre] |
| HH:MM | Solución implementada | [Acción] | [Nombre] |
| HH:MM | Servicio restaurado | Verificar funcionalidad | [Nombre] |
| HH:MM | Monitoreo post-resolución | Observación activa | [Nombre] |
| HH:MM | Confirmación de estabilidad | - | [Nombre] |
| HH:MM | Cliente notificado de resolución | Comunicar vía Slack + Email | [Nombre] |
| HH:MM | Ticket cerrado | Documentación completa | [Nombre] |

### 3. CAUSA RAÍZ
> **Causa raíz técnica:**
> [Descripción técnica detallada de qué causó el incidente]
>
> **Causa raíz subyacente:**
> [¿Por qué existía esa condición? ¿Qué proceso o control falló?]

### 4. ANÁLISIS DE LOS 5 POR QUÉ
```
¿Por qué se cayó el servicio?
→ Porque [...]

  ¿Por qué [...]?
  → Porque [...]

    ¿Por qué [...]?
    → Porque [...]

      ¿Por qué [...]?
      → Porque [...]

        ¿Por qué [...]?
        → Porque [...] ← CAUSA RAÍZ
```

### 5. QUÉ FUNCIONÓ BIEN
| # | Aspecto | Detalle |
|---|---------|---------|
| 1 | | |
| 2 | | |
| 3 | | |

### 6. QUÉ NO FUNCIONÓ BIEN
| # | Aspecto | Detalle | Impacto |
|---|---------|---------|---------|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### 7. DÓNDE TUVIMOS SUERTE
| # | Aspecto | Qué pudo haber sido peor |
|---|---------|-------------------------|
| 1 | | |

### 8. ACCIONES CORRECTIVAS Y PREVENTIVAS
| # | Acción | Tipo | Prioridad | Responsable | Fecha Límite | Estado |
|---|--------|:----:|:---------:|-------------|:------------:|:------:|
| 1 | | Correctiva | 🔴 Alta | | DD/MM/YYYY | ⬜ Pendiente |
| 2 | | Preventiva | 🟠 Media | | DD/MM/YYYY | ⬜ Pendiente |
| 3 | | Mejora proceso | 🟡 Baja | | DD/MM/YYYY | ⬜ Pendiente |

### 9. IMPACTO EN SLA
| Métrica | Antes del Incidente | Después del Incidente | Impacto |
|---------|:-------------------:|:---------------------:|:-------:|
| Disponibilidad mensual | 99.98% | 99.85% | -0.13% |
| MTTR | Xh | Xh | |
| MTBF | Xh | Xh | |

### 10. LECCIONES APRENDIDAS
| # | Lección | Aplicación |
|---|---------|------------|
| 1 | | |
| 2 | | |

### 11. PARTICIPANTES DEL POST-MORTEM
| Nombre | Cargo | Rol en el Incidente |
|--------|-------|---------------------|
| | | |

---
**Elaborado por:** [Nombre]
**Revisado por:** [Nombre]
**Fecha de revisión:** [DD/MM/YYYY]
**Próxima revisión de acciones:** [DD/MM/YYYY]
```

---

### **Template 5: Calendario de Mantenimiento Preventivo**

```markdown
# 📅 CALENDARIO DE MANTENIMIENTO PREVENTIVO
## Cliente: [Nombre] | Proyecto: [Código]
## Año: [YYYY]
## Última actualización: [DD/MM/YYYY]

---

### ACTIVIDADES DIARIAS
| Actividad | Hora | Responsable | Automatizado |
|-----------|:----:|-------------|:------------:|
| Revisión de dashboards | 08:00 | Ing. Redes | No |
| Revisión de alertas nocturnas | 08:30 | Ing. Redes | No |
| Verificación de backups | 09:00 | Ing. Redes | Parcial |
| Revisión de logs de seguridad | 09:30 | Analista Seg. | Parcial |
| Verificación de estado de enlaces | 10:00 | Ing. Redes | Sí |

### ACTIVIDADES SEMANALES
| Actividad | Día | Hora | Responsable | Semana 1 | Semana 2 | Semana 3 | Semana 4 |
|-----------|:---:|:----:|-------------|:--------:|:--------:|:--------:|:--------:|
| Revisión de performance | Lun | 10:00 | Ing. Redes | ⬜ | ⬜ | ⬜ | ⬜ |
| Actualización de reglas IDS/IPS | Mar | 14:00 | Analista Seg. | ⬜ | ⬜ | ⬜ | ⬜ |
| Búsqueda de IoCs | Mie | 10:00 | Analista Seg. | ⬜ | ⬜ | ⬜ | ⬜ |
| Seguimiento de vulnerabilidades | Jue | 14:00 | Analista Seg. | ⬜ | ⬜ | ⬜ | ⬜ |
| Actualización de KB | Vie | 16:00 | Equipo | ⬜ | ⬜ | ⬜ | ⬜ |

### ACTIVIDADES MENSUALES
| Actividad | Semana | Responsable | Ene | Feb | Mar | Abr | May | Jun | Jul | Ago | Sep | Oct | Nov | Dic |
|-----------|:------:|-------------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Parches de seguridad | 2 | Admin. Sys. | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| Escaneo vulnerabilidades | 3 | Analista | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| Prueba de restore | 4 | Ing. Redes | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| Limpieza de logs | 4 | Admin. Sys. | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| Informe mensual SLA | 1 (sig) | Ger. Cuenta | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| Revisión de playbooks | 1 | Líder Téc. | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

### ACTIVIDADES TRIMESTRALES
| Actividad | Q1 | Q2 | Q3 | Q4 | Responsable |
|-----------|:--:|:--:|:--:|:--:|-------------|
| Auditoría de reglas firewall | ⬜ | ⬜ | ⬜ | ⬜ | Analista Seg. |
| Prueba de failover | ⬜ | ⬜ | ⬜ | ⬜ | Ing. Redes |
| Revisión de accesos | ⬜ | ⬜ | ⬜ | ⬜ | Analista Seg. |
| Optimización de rendimiento | ⬜ | ⬜ | ⬜ | ⬜ | Ing. Redes |
| Auditoría de compliance | ⬜ | ⬜ | ⬜ | ⬜ | CISO |
| Encuesta de satisfacción | ⬜ | ⬜ | ⬜ | ⬜ | Ger. Cuenta |
| Informe ejecutivo trimestral | ⬜ | ⬜ | ⬜ | ⬜ | Ger. Cuenta |
| Revisión de documentación | ⬜ | ⬜ | ⬜ | ⬜ | Líder Téc. |
| Campaña de phishing | ⬜ | ⬜ | ⬜ | ⬜ | Analista Seg. |

### ACTIVIDADES SEMESTRALES
| Actividad | H1 | H2 | Responsable |
|-----------|:--:|:--:|-------------|
| Capacity planning | ⬜ | ⬜ | Arq. Redes |
| Simulacro de DR | ⬜ | ⬜ | Líder Téc. |
| Pentesting | ⬜ | ⬜ | Analista Seg. |
| Revisión de políticas de seguridad | ⬜ | ⬜ | CISO |

### ACTIVIDADES ANUALES
| Actividad | Mes Planificado | Responsable | Estado |
|-----------|:---------------:|-------------|:------:|
| Renovación de certificados SSL | [Mes] | Admin. Sys. | ⬜ |
| Revisión de contrato y SLA | [Mes] | Ger. Cuenta | ⬜ |
| Auditoría externa (si aplica) | [Mes] | CISO | ⬜ |
| Actualización mayor de firmware | [Mes] | Ing. Redes | ⬜ |

---
**Aprobado por Proveedor:** _____________ Fecha: _________
**Aprobado por Cliente:** _______________ Fecha: _________
```

---

### **Template 6: Encuesta de Satisfacción del Cliente**

```markdown
# ⭐ ENCUESTA DE SATISFACCIÓN DEL SERVICIO
## Cliente: [Nombre] | Proyecto: [Código]
## Período evaluado: [Trimestre/Año]
## Fecha: [DD/MM/YYYY]
## Respondido por: [Nombre] | [Cargo]

---

### INSTRUCCIONES
Califique cada aspecto del servicio en una escala de 1 a 5:
1 = Muy insatisfecho | 2 = Insatisfecho | 3 = Neutral | 
4 = Satisfecho | 5 = Muy satisfecho

---

### 1. DISPONIBILIDAD DEL SERVICIO
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Disponibilidad de la red | | |
| Disponibilidad del acceso a internet | | |
| Disponibilidad de VPN | | |
| Estabilidad general de los servicios | | |

### 2. GESTIÓN DE INCIDENTES
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Velocidad de respuesta ante incidentes | | |
| Calidad de la resolución | | |
| Comunicación durante el incidente | | |
| Seguimiento post-resolución | | |

### 3. SOPORTE TÉCNICO
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Conocimiento técnico del equipo | | |
| Disponibilidad del equipo de soporte | | |
| Amabilidad y profesionalismo | | |
| Proactividad en identificar problemas | | |

### 4. COMUNICACIÓN Y REPORTERÍA
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Calidad de los informes mensuales | | |
| Utilidad de los dashboards | | |
| Frecuencia de comunicación | | |
| Claridad en las explicaciones técnicas | | |

### 5. SEGURIDAD
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Confianza en la protección de seguridad | | |
| Gestión de vulnerabilidades | | |
| Respuesta ante amenazas | | |
| Recomendaciones de mejora de seguridad | | |

### 6. GESTIÓN DE CAMBIOS
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Proceso de solicitud de cambios | | |
| Tiempo de implementación | | |
| Comunicación sobre el impacto | | |
| Calidad de la ejecución | | |

### 7. VALORACIÓN GENERAL
| Aspecto | Calificación (1-5) | Comentarios |
|---------|:------------------:|-------------|
| Satisfacción general con el servicio | | |
| Relación calidad-precio | | |
| Recomendaría el servicio a otros | | |

### 8. PREGUNTAS ABIERTAS
**¿Qué es lo que más valora de nuestro servicio?**
> [Respuesta]

**¿En qué áreas cree que debemos mejorar?**
> [Respuesta]

**¿Hay algún servicio adicional que le gustaría recibir?**
> [Respuesta]

**¿Tiene algún comentario adicional?**
> [Respuesta]

### RESUMEN DE CALIFICACIONES
| Categoría | Promedio |
|-----------|:--------:|
| Disponibilidad | /5 |
| Gestión de Incidentes | /5 |
| Soporte Técnico | /5 |
| Comunicación | /5 |
| Seguridad | /5 |
| Gestión de Cambios | /5 |
| General | /5 |
| **PROMEDIO GLOBAL** | **/5** |

### NET PROMOTER SCORE (NPS)
**En una escala de 0 a 10, ¿qué tan probable es que 
recomiende nuestro servicio a un colega?**
Calificación: [0-10]

---
**Encuesta procesada por:** [Nombre] | Fecha: [DD/MM/YYYY]
```

---

### **Template 7: Bitácora de Operaciones**

```markdown
# 📝 BITÁCORA DE OPERACIONES
## Cliente: [Nombre] | Mes: [Mes YYYY]

---

### [DD/MM/YYYY] - [Día de la semana]
**Operador de turno:** [Nombre]

| Hora | Tipo | Descripción | Acción | Estado |
|:----:|:----:|-------------|--------|:------:|
| 08:00 | 🟢 Inicio | Inicio de turno. Revisión de dashboards. Todo normal. | - | OK |
| 08:15 | 🔵 Info | Backup nocturno completado exitosamente | Verificado | OK |
| 09:30 | 🟡 Alerta | CPU del firewall al 78% | Monitorear | Observación |
| 10:15 | 🟠 Incidente | Usuario reporta lentitud en VPN. Ticket INC-XXX | Diagnosticando | En progreso |
| 11:00 | 🟢 Resolución | INC-XXX resuelto. Causa: MTU incorrecto en túnel | MTU ajustado | Cerrado |
| 14:00 | 🔄 Cambio | CHG-XXX: Actualización de regla de firewall para nuevo servidor | Implementado | Exitoso |
| 14:30 | 🔵 Info | Verificación post-cambio CHG-XXX completada | Todo OK | Cerrado |
| 17:00 | 🟢 Fin | Fin de turno. Sin incidentes pendientes. | Handoff a [Nombre] | OK |

**Resumen del día:**
- Incidentes: [X] abiertos / [X] cerrados
- Cambios: [X] ejecutados
- Alertas: [X] procesadas
- Observaciones: [Notas relevantes]

---

### [DD/MM/YYYY] - [Día de la semana]
[Mismo formato...]
```

---

### **Template 8: Informe de Escaneo de Vulnerabilidades Mensual**

```markdown
# 🛡️ INFORME DE ESCANEO DE VULNERABILIDADES
## Cliente: [Nombre] | Proyecto: [Código]
## Período: [Mes YYYY]
## Fecha de escaneo: [DD/MM/YYYY]
## Herramienta: OpenVAS/Greenbone [Versión]

---

### RESUMEN EJECUTIVO
> [Resumen breve del estado de vulnerabilidades]

### 1. ALCANCE DEL ESCANEO
| Parámetro | Valor |
|-----------|-------|
| Redes escaneadas | [Lista de subredes] |
| Hosts descubiertos | [Número] |
| Hosts escaneados | [Número] |
| Puertos evaluados | [Rango] |
| Perfil de escaneo | [Nombre del perfil] |
| Duración del escaneo | [HH:MM] |

### 2. RESUMEN DE HALLAZGOS
| Severidad | Este Mes | Mes Anterior | Variación | Tendencia |
|:---------:|:--------:|:------------:|:---------:|:---------:|
| 🔴 Crítica | | | +/-X | 📈/📉 |
| 🟠 Alta | | | +/-X | 📈/📉 |
| 🟡 Media | | | +/-X | 📈/📉 |
| 🔵 Baja | | | +/-X | 📈/📉 |
| **Total** | | | | |

> 📊 **Gráfico:** [Tendencia de vulnerabilidades últimos 6 meses]

### 3. VULNERABILIDADES NUEVAS
| # | CVE | Severidad | CVSS | Host(s) Afectado(s) | Descripción | Remediación |
|---|-----|:---------:|:----:|---------------------|-------------|-------------|
| 1 | CVE-YYYY-XXXX | 🔴 | 9.8 | | | |

### 4. VULNERABILIDADES REMEDIADAS ESTE MES
| # | CVE | Severidad | Host(s) | Fecha Remediación | Verificado |
|---|-----|:---------:|---------|:-----------------:|:----------:|
| 1 | | | | DD/MM | ✅/❌ |

### 5. VULNERABILIDADES PENDIENTES (AGING)
| # | CVE | Severidad | Días Abierta | Host(s) | Plan de Remediación | Fecha Objetivo |
|---|-----|:---------:|:------------:|---------|---------------------|:--------------:|
| 1 | | 🔴 | XX días | | | DD/MM |

### 6. TOP 10 HOSTS MÁS VULNERABLES
| # | Host | IP | Críticas | Altas | Medias | Bajas | Total | Score |
|---|------|----|:--------:|:-----:|:------:|:-----:|:-----:|:-----:|
| 1 | | | | | | | | |

### 7. MÉTRICAS DE GESTIÓN DE VULNERABILIDADES
| Métrica | Valor | Objetivo | Estado |
|---------|:-----:|:--------:|:------:|
| Tiempo medio de remediación (Críticas) | días | 7 días | ✅/❌ |
| Tiempo medio de remediación (Altas) | días | 30 días | ✅/❌ |
| % vulnerabilidades remediadas este mes | % | 80% | ✅/❌ |
| Vulnerabilidades pendientes > 90 días | | 0 | ✅/❌ |

### 8. RECOMENDACIONES
| # | Recomendación | Prioridad | Impacto |
|---|---------------|:---------:|---------|
| 1 | | | |

---
**Elaborado por:** [Nombre] | [Cargo]
**Revisado por:** [Nombre] | [Cargo]
```

---

## **3. Automatizaciones con n8n para la Fase 3**

### **Automatización 1: Reporte Diario Automático de Operación**

```
📌 TRIGGER: Cron job diario a las 08:00 AM

FLUJO EN n8n:

1. [Schedule Trigger] → Todos los días a las 08:00 AM

2. [Zabbix API] → Obtener estado de todos los hosts:
   - Hosts activos vs inactivos
   - Alertas activas
   - Últimas alertas de las últimas 12 horas
   - Métricas de CPU, RAM, bandwidth de equipos críticos

3. [Uptime Kuma API] → Obtener disponibilidad:
   - Estado de cada servicio monitoreado
   - Uptime últimas 24 horas
   - Incidentes detectados

4. [Wazuh API] → Obtener resumen de seguridad:
   - Alertas de seguridad últimas 24 horas
   - Top reglas activadas
   - Agentes con problemas

5. [Asana API] → Obtener incidentes:
   - Tickets abiertos
   - Tickets resueltos ayer
   - Tickets vencidos
   - Cambios programados para hoy

6. [HTTP Request] → Verificar backups (Oxidized API):
   - Último backup exitoso por dispositivo
   - Dispositivos sin backup reciente

7. [Function] → Compilar reporte:
   - Determinar estado general (🟢/🟡/🔴)
   - Calcular disponibilidad
   - Formatear datos para Slack
   - Identificar items que requieren atención

8. [Slack] → Enviar a #cliente-[nombre]-general:
   "📊 REPORTE MATUTINO | [DD/MM/YYYY]
    Estado General: [🟢/🟡/🔴]
    
    🌐 RED
    ├── LAN: 🟢 Operativa (100%)
    ├── WAN: 🟢 Operativa (99.99%)
    ├── VPN S2S: 🟢 3/3 túneles activos
    └── Wi-Fi: 🟢 Operativa
    
    🔒 SEGURIDAD
    ├── Firewall: 🟢 Operativo (CPU: 45%, RAM: 62%)
    ├── IDS/IPS: 🟢 Activo
    ├── SIEM: 🟢 [X] eventos procesados (12h)
    └── Alertas de seguridad: [X] (0 críticas)
    
    🎫 INCIDENTES
    ├── Abiertos: [X]
    ├── Resueltos ayer: [X]
    ├── Vencidos: [X] ⚠️
    └── Cambios programados hoy: [X]
    
    💾 BACKUPS
    └── Estado: ✅ Todos exitosos
    
    [Detalles de items que requieren atención si los hay]"

9. [Slack] → Enviar a #equipo-interno:
   "[Mismo reporte + información adicional interna]
    
    📋 TAREAS DEL DÍA:
    1. [Tarea 1] - @[responsable]
    2. [Tarea 2] - @[responsable]
    3. [Cambio programado] - @[responsable]"

10. [IF] → Si hay alertas críticas activas:
    a. [Slack] → Mención especial:
       "🚨 ATENCIÓN: [X] alertas críticas activas
        requieren acción inmediata.
        @[líder_técnico]"

11. [Google Sheets] → Registrar métricas diarias
    para dashboards de tendencia
```

---

### **Automatización 2: Gestión Inteligente de Incidentes**

```
📌 TRIGGER: Alerta recibida vía webhook de Zabbix/Uptime Kuma

FLUJO EN n8n:

1. [Webhook Trigger] → Recibir alerta de monitoreo

2. [Function] → Parsear y clasificar la alerta:
   
   Clasificación automática por severidad:
   - Host Down → 🔴 Crítica
   - Service Down → 🔴 Crítica  
   - High CPU (>95%) → 🟠 Alta
   - High Memory (>90%) → 🟠 Alta
   - High Bandwidth (>85%) → 🟡 Media
   - Disk Space (>80%) → 🟡 Media
   - Interface Flapping → 🟠 Alta
   - Security Alert → 🔴 Crítica
   
   Clasificación por categoría:
   - Network, Security, Hardware, Software, External

3. [Function] → Verificar si ya existe ticket activo
   para el mismo host/servicio (deduplicación)

4. [IF] → Si NO existe ticket duplicado:

   a. [Zammad/osTicket API] → Crear ticket de incidente:
      - Título: "[SEVERIDAD] [Categoría] - [Descripción]"
      - Prioridad: Según clasificación
      - Categoría: Según clasificación
      - Cliente: [Nombre del cliente]
      - Descripción: Detalles de la alerta + datos de monitoreo
      - SLA: Según severidad
   
   b. [Asana] → Crear tarea de incidente:
      - Proyecto: [Proyecto del cliente]
      - Sección: "Incidentes Activos"
      - Custom Fields: Severidad, Categoría, SLA, Ticket ID
      - Asignación automática según RACI y categoría:
        - Network → Ingeniero de Redes
        - Security → Analista de Seguridad
        - Si es Crítico → También asignar al Líder Técnico
      - Fecha límite: Según SLA
      - Crear subtareas automáticas:
        - "Diagnóstico inicial"
        - "Implementar solución"
        - "Verificar resolución"
        - "Notificar al cliente"
        - "Documentar causa raíz"
   
   c. [Slack] → Notificar en #cliente-[nombre]-incidentes:
      "🚨 INCIDENTE DETECTADO
       
       🆔 Ticket: [ID]
       ⚡ Severidad: [🔴/🟠/🟡/🔵]
       📂 Categoría: [Categoría]
       🖥️ Servicio: [Nombre]
       📍 Host: [Hostname] ([IP])
       📝 Descripción: [Detalle]
       ⏰ Detectado: [HH:MM]
       👤 Asignado a: @[responsable]
       ⏳ SLA Respuesta: [Tiempo]
       ⏳ SLA Resolución: [Tiempo]
       
       📋 Ticket: [Link]
       📊 Monitoreo: [Link Grafana]"
   
   d. [IF] → Si severidad es CRÍTICA:
      - [Slack] → Crear hilo dedicado para war room virtual
      - [Twilio] → Enviar SMS al Líder Técnico:
        "ALERTA CRÍTICA: [Servicio] [Cliente]. 
         Ticket: [ID]. Revisar inmediatamente."
      - [Google Calendar] → Crear evento de war room
        (15 min desde ahora, invitar al equipo)

5. [IF] → Si YA existe ticket duplicado:
   a. [Asana] → Agregar comentario en ticket existente:
      "⚠️ Alerta adicional detectada: [Detalle]
       Hora: [HH:MM]. Correlacionar con incidente activo."

6. [Schedule] → Iniciar timer de SLA:
   
   MONITOREO DE SLA (cada 5 minutos):
   a. [Asana] → Verificar tickets abiertos con SLA activo
   b. [Function] → Calcular tiempo transcurrido
   c. [IF] → Si tiempo > 50% del SLA y sin respuesta:
      - [Slack] → "⚠️ ALERTA SLA: Ticket [ID] al 50% 
         del tiempo. Sin respuesta. @[responsable]"
   d. [IF] → Si tiempo > 75% del SLA:
      - [Slack] → "🔴 ESCALAMIENTO: Ticket [ID] al 75% 
         del SLA. Escalando a @[líder_técnico]"
      - [Asana] → Agregar al Líder Técnico como colaborador
   e. [IF] → Si tiempo > 90% del SLA:
      - [Slack] → "🚨 SLA EN RIESGO: Ticket [ID] al 90%. 
         Escalando a @[gerente_operaciones]"
      - [Email] → Notificar al Gerente de Operaciones
      - [Twilio] → SMS al Gerente de Operaciones
   f. [IF] → Si SLA incumplido:
      - [Slack] → "❌ SLA INCUMPLIDO: Ticket [ID].
         @[gerente_cuenta] notificar al cliente."
      - [Google Sheets] → Registrar incumplimiento
      - [Asana] → Marcar Custom Field "SLA: Incumplido"
```

---

### **Automatización 3: Cierre de Incidente y Documentación**

```
📌 TRIGGER: Tarea de incidente en Asana marcada como completada

FLUJO EN n8n:

1. [Asana Trigger] → Tarea de incidente completada

2. [Asana] → Verificar que todas las subtareas están completadas:
   - ✅ Diagnóstico inicial
   - ✅ Implementar solución
   - ✅ Verificar resolución
   - ✅ Notificar al cliente
   - ✅ Documentar causa raíz

3. [IF] → Si faltan subtareas:
   a. [Asana] → Reabrir tarea
   b. [Slack] → Notificar:
      "⚠️ No se puede cerrar el ticket [ID].
       Subtareas pendientes: [Lista]
       @[responsable]"
   c. STOP

4. [IF] → Todas las subtareas completadas:

   a. [Function] → Calcular métricas del incidente:
      - Tiempo de detección
      - Tiempo de respuesta
      - Tiempo de resolución
      - SLA cumplido (Sí/No)
      - Categoría
      - Causa raíz
   
   b. [Zammad/osTicket API] → Cerrar ticket:
      - Estado: Resuelto
      - Agregar nota de resolución
      - Registrar métricas
   
   c. [Google Sheets] → Registrar en base de datos 
      de incidentes:
      | Fecha | ID | Severidad | Categoría | Causa Raíz |
      | T. Detección | T. Respuesta | T. Resolución | 
      | SLA Cumplido | Responsable |
   
   d. [Slack] → Notificar cierre en #cliente-incidentes:
      "✅ INCIDENTE RESUELTO
       
       🆔 Ticket: [ID]
       📝 Descripción: [Resumen]
       🔍 Causa raíz: [Causa]
       🛠️ Solución: [Resumen solución]
       ⏱️ Tiempo de resolución: [HH:MM]
       ✅ SLA: [Cumplido/No cumplido]
       👤 Resuelto por: [Nombre]"
   
   e. [IF] → Si severidad fue Crítica o Alta:
      - [Asana] → Crear tarea de post-mortem:
        "🔍 Post-mortem: INC-[ID]"
        Fecha límite: +2 días hábiles
        Asignado a: Líder Técnico
        Adjuntar template de post-mortem
   
   f. [IF] → Si la causa raíz es recurrente (verificar 
      en historial de Google Sheets):
      - [Slack] → Alertar:
        "🔄 INCIDENTE RECURRENTE DETECTADO
         La causa raíz '[Causa]' se ha repetido [X] veces 
         en los últimos [Y] días.
         Se requiere acción preventiva.
         @[líder_técnico]"
      - [Asana] → Crear tarea de mejora:
        "🔧 Acción preventiva: [Causa recurrente]"
   
   g. [Function] → Verificar si se debe actualizar KB:
      - Si es una solución nueva → Crear artículo KB
      - Si es un workaround → Documentar
   
   h. [BookStack API] → Crear/actualizar artículo en wiki
      (si aplica)
```

---

### **Automatización 4: Informe Mensual de SLA Automatizado**

```
📌 TRIGGER: Cron job el día 1 de cada mes a las 06:00 AM

FLUJO EN n8n:

1. [Schedule Trigger] → Día 1 de cada mes, 06:00 AM

2. [Function] → Definir período del mes anterior

3. [RECOPILACIÓN DE DATOS]

   a. [Uptime Kuma API] → Obtener disponibilidad por servicio:
      - Uptime % para cada monitor
      - Downtime total en minutos
      - Incidentes de disponibilidad
   
   b. [Zabbix API] → Obtener métricas de rendimiento:
      - CPU, RAM, bandwidth promedio/máximo/mínimo
      - Latencia promedio
      - Alertas generadas por tipo
   
   c. [Google Sheets] → Obtener datos de incidentes:
      - Total incidentes por severidad
      - MTTR por severidad
      - MTBF
      - Incidentes por categoría
      - Incidentes por causa raíz
      - SLA cumplido por incidente
   
   d. [Asana API] → Obtener cambios ejecutados:
      - Total de cambios
      - Exitosos vs fallidos
      - Por tipo (estándar/normal/emergencia)
   
   e. [Wazuh API] → Obtener métricas de seguridad:
      - Total eventos procesados
      - Alertas de seguridad por severidad
      - Top amenazas detectadas
      - Agentes activos
   
   f. [OpenVAS API] → Obtener resumen de vulnerabilidades:
      - Nuevas vs remediadas vs pendientes
      - Por severidad
      - Aging de vulnerabilidades

4. [Function] → Calcular métricas consolidadas:
   
   Disponibilidad:
   - Por servicio
   - Promedio general
   - Comparación con mes anterior
   - Tendencia 6 meses
   
   Incidentes:
   - Tiempo promedio de respuesta por severidad
   - Tiempo promedio de resolución por severidad
   - Tasa de cumplimiento de SLA
   - Distribución por categoría y causa raíz
   - Top 5 incidentes del mes
   
   Seguridad:
   - Resumen de eventos y alertas
   - Estado de vulnerabilidades
   - Indicadores de riesgo
   
   Cambios:
   - Tasa de éxito
   - Distribución por tipo
   
   Satisfacción (si hay encuesta del trimestre):
   - Promedio por categoría
   - NPS

5. [Google Docs] → Generar informe usando Template 3
   (Informe Mensual de SLA):
   - Reemplazar placeholders con datos calculados
   - Insertar gráficos (via Google Sheets charts)
   - Formatear profesionalmente

6. [Google Drive] → Guardar informe en carpeta del cliente:
   /04_Informes/[YYYY]/[MM]_Informe_SLA.pdf

7. [Slack] → Notificar en #equipo-interno:
   "📊 INFORME MENSUAL DE SLA GENERADO
    Cliente: [Nombre]
    Período: [Mes YYYY]
    
    📈 RESUMEN:
    ├── Disponibilidad: [X]% (Objetivo: 99.9%)
    ├── MTTR: [X]h (Objetivo: [X]h)
    ├── Incidentes: [X] ([X] críticos)
    ├── SLA cumplido: [X]%
    └── Cambios exitosos: [X]/[X] ([X]%)
    
    📄 Informe: [Link]
    ⏰ Comité ejecutivo programado: [Fecha]"

8. [Email] → Enviar informe al cliente (draft, requiere
   revisión del Gerente de Cuenta antes de enviar):
   "Estimado [Contacto],
    
    Adjunto encontrará el informe mensual de SLA 
    correspondiente al mes de [Mes YYYY].
    
    Resumen destacado:
    • Disponibilidad general: [X]%
    • Cumplimiento de SLA: [X]%
    • [Punto destacado positivo]
    
    Quedamos a su disposición para revisar el informe 
    en detalle durante nuestro próximo comité ejecutivo 
    programado para el [Fecha].
    
    Saludos cordiales,
    [Nombre]
    [Cargo]"

9. [Asana] → Crear tarea:
   "📋 Revisar y enviar informe SLA [Mes] a [Cliente]"
   Asignada a: Gerente de Cuenta
   Fecha límite: +2 días hábiles
   Adjuntar link del informe

10. [Google Calendar] → Verificar/crear evento de 
    comité ejecutivo mensual
```

---

### **Automatización 5: Mantenimiento Preventivo Programado**

```
📌 TRIGGER: Cron job diario a las 07:00 AM

FLUJO EN n8n:

1. [Schedule Trigger] → Todos los días a las 07:00 AM

2. [Google Sheets] → Leer calendario de mantenimiento 
   preventivo del cliente

3. [Function] → Verificar actividades programadas:
   - Para hoy
   - Para los próximos 7 días
   - Vencidas (no ejecutadas en fecha)

4. [FOR EACH] → Para cada actividad de HOY:
   
   a. [Asana] → Crear tarea de mantenimiento:
      - Título: "🔧 MANT PREV: [Actividad]"
      - Sección: "Mantenimiento Preventivo"
      - Custom Fields: 
        - Tipo: Preventivo
        - Frecuencia: [Diaria/Semanal/Mensual/etc.]
        - Última ejecución: [Fecha]
      - Asignada a: [Según calendario]
      - Fecha límite: Hoy
      - Crear subtareas específicas según tipo:
        
        Si es "Parches de seguridad":
        - "Verificar parches disponibles"
        - "Evaluar impacto"
        - "Solicitar ventana de mantenimiento"
        - "Aplicar parches"
        - "Verificar post-parcheo"
        - "Documentar"
        
        Si es "Escaneo de vulnerabilidades":
        - "Ejecutar escaneo OpenVAS"
        - "Analizar resultados"
        - "Clasificar hallazgos"
        - "Crear tickets de remediación"
        - "Generar informe"
        
        Si es "Prueba de backup":
        - "Seleccionar backup a probar"
        - "Ejecutar restore en ambiente de prueba"
        - "Verificar integridad"
        - "Documentar resultado"
        
        [Y así para cada tipo de mantenimiento]
   
   b. [Slack] → Recordatorio:
      "🔧 MANTENIMIENTO PREVENTIVO HOY
       
       📋 Actividad: [Nombre]
       👤 Responsable: @[nombre]
       ⏰ Ejecutar antes de las [Hora]
       📖 Procedimiento: [Link a wiki]
       📋 Tarea Asana: [Link]"

5. [FOR EACH] → Para actividades de los próximos 7 días:
   
   a. [Slack] → Resumen semanal (solo los lunes):
      "📅 MANTENIMIENTOS PREVENTIVOS ESTA SEMANA
       
       Lun: [Actividad] - @[responsable]
       Mar: [Actividad] - @[responsable]
       Mie: Ninguno programado
       Jue: [Actividad] - @[responsable]
       Vie: [Actividad] - @[responsable]"

6. [FOR EACH] → Para actividades VENCIDAS:
   
   a. [Slack] → ALERTA:
      "⚠️ MANTENIMIENTO VENCIDO
       Actividad: [Nombre]
       Fecha programada: [Fecha]
       Días de atraso: [X]
       @[responsable] @[líder_técnico]
       Reprogramar inmediatamente."
   
   b. [Asana] → Crear tarea urgente con prioridad alta

7. [Schedule] → Al completar mantenimiento (trigger Asana):
   a. [Google Sheets] → Registrar ejecución:
      | Fecha | Actividad | Resultado | Ejecutado por | 
      | Observaciones | Próxima ejecución |
   b. [Google Sheets] → Actualizar fecha de próxima ejecución
```

---

### **Automatización 6: Threat Intelligence Feed**

```
📌 TRIGGER: Cron job diario a las 07:30 AM

FLUJO EN n8n:

1. [Schedule Trigger] → Todos los días a las 07:30 AM

2. [HTTP Request] → Consultar feeds de amenazas gratuitos:
   
   a. CISA Known Exploited Vulnerabilities:
      GET https://www.cisa.gov/sites/default/files/feeds/
      known_exploited_vulnerabilities.json
   
   b. Abuse.ch URLhaus:
      GET https://urlhaus-api.abuse.ch/v1/urls/recent/
   
   c. AlienVault OTX:
      GET https://otx.alienvault.com/api/v1/pulses/subscribed
   
   d. NIST NVD (últimas vulnerabilidades):
      GET https://services.nvd.nist.gov/rest/json/cves/2.0
      ?pubStartDate=[ayer]&pubEndDate=[hoy]

3. [Function] → Filtrar y correlacionar:
   
   a. Filtrar CVEs por tecnologías del cliente:
      - Fabricantes de equipos (Fortinet, Cisco, etc.)
      - Sistemas operativos
      - Software utilizado
   
   b. Verificar si alguna IP/URL maliciosa se ha visto 
      en los logs del cliente (consultar SIEM)
   
   c. Clasificar relevancia:
      - 🔴 Directamente relevante (tecnología del cliente)
      - 🟡 Potencialmente relevante
      - 🔵 Informativo

4. [IF] → Si hay amenazas directamente relevantes:
   
   a. [Slack] → Alerta en #equipo-interno:
      "🔴 AMENAZA RELEVANTE DETECTADA
       
       📋 CVE: [CVE-YYYY-XXXX]
       📝 Descripción: [Descripción]
       ⚡ CVSS: [Score]
       🖥️ Tecnología afectada: [Fabricante/Producto]
       🔗 Referencia: [URL]
       
       ⚠️ Este cliente utiliza [Producto] [Versión].
       Verificar si es vulnerable y planificar parcheo.
       @[analista_seguridad]"
   
   b. [Asana] → Crear tarea:
      "🛡️ Evaluar amenaza: [CVE]"
      Prioridad: Alta
      Asignada a: Analista de Seguridad
      Custom Field: Tipo → Threat Intelligence
   
   c. [Wazuh API] → Buscar IoCs en logs del cliente
      (IPs, URLs, hashes conocidos)

5. [IF] → Si se detectan IoCs en los logs del cliente:
   
   a. [Slack] → ALERTA CRÍTICA:
      "🚨 IoC DETECTADO EN INFRAESTRUCTURA DEL CLIENTE
       
       ⚡ Tipo: [IP/URL/Hash]
       🔍 Valor: [IoC]
       📍 Detectado en: [Host/Log]
       📅 Fecha: [Timestamp]
       
       ACCIÓN INMEDIATA REQUERIDA
       @[analista_seguridad] @[líder_técnico]"
   
   b. [Asana] → Crear incidente de seguridad CRÍTICO
   c. [Email] → Notificar al CISO
   d. [Wazuh] → Agregar IoC a watchlist activa

6. [Slack] → Boletín diario de amenazas (resumen):
   "🛡️ BOLETÍN DIARIO DE AMENAZAS | [DD/MM/YYYY]
    
    📊 Resumen:
    ├── Nuevas CVEs relevantes: [X]
    ├── CVEs críticas (CVSS ≥ 9.0): [X]  
    ├── URLs maliciosas nuevas: [X]
    ├── IoCs verificados contra cliente: [X]
    └── Coincidencias encontradas: [X]
    
    🔴 CVEs relevantes para [Cliente]:
    1. [CVE] - [Descripción breve] - CVSS [Score]
    
    📖 Informe completo: [Link]"
```

---

### **Automatización 7: Encuesta de Satisfacción Automatizada**

```
📌 TRIGGER: Cron job el día 1 del mes siguiente a cada trimestre
(Abril 1, Julio 1, Octubre 1, Enero 1)

FLUJO EN n8n:

1. [Schedule Trigger] → Día 1 de Abril/Julio/Octubre/Enero

2. [Google Forms] → Generar link de encuesta personalizada
   (usando Template 6: Encuesta de Satisfacción)
   - Prellenar campos: Cliente, Período, Proyecto

3. [Email] → Enviar invitación a stakeholders del cliente:
   "Estimado [Nombre],
    
    Como parte de nuestro compromiso con la mejora continua,
    le invitamos a completar nuestra encuesta trimestral 
    de satisfacción del servicio.
    
    La encuesta toma aproximadamente 5 minutos:
    🔗 [Link a Google Forms]
    
    Su feedback es fundamental para seguir mejorando 
    la calidad de nuestro servicio.
    
    Fecha límite: [+10 días]
    
    Agradecemos su tiempo.
    [Nombre] | Gerente de Cuenta"

4. [Schedule] → Si no responde en 5 días:
   a. [Email] → Recordatorio amable:
      "Estimado [Nombre], 
       queremos recordarle nuestra encuesta de satisfacción.
       Su opinión es muy valiosa: [Link]"

5. [Schedule] → Si no responde en 8 días:
   a. [Slack] → Notificar al Gerente de Cuenta:
      "⚠️ [Nombre del stakeholder] no ha respondido 
       la encuesta de satisfacción.
       Considerar llamada telefónica o mención en próxima 
       reunión."

6. [Google Forms Trigger] → Al recibir respuesta:
   
   a. [Function] → Calcular promedios por categoría y NPS
   
   b. [Google Sheets] → Registrar respuestas:
      | Fecha | Respondente | Cat1 | Cat2 | ... | 
      | Promedio | NPS | Comentarios |
   
   c. [Slack] → Notificar al Gerente de Cuenta:
      "📊 NUEVA RESPUESTA DE ENCUESTA DE SATISFACCIÓN
       
       👤 Respondente: [Nombre] ([Cargo])
       ⭐ Promedio general: [X]/5
       📈 NPS: [Score]
       
       Categorías:
       ├── Disponibilidad: [X]/5
       ├── Gestión de incidentes: [X]/5
       ├── Soporte técnico: [X]/5
       ├── Comunicación: [X]/5
       ├── Seguridad: [X]/5
       └── Gestión de cambios: [X]/5
       
       💬 Comentarios destacados:
       '[Extracto de comentario más relevante]'"
   
   d. [IF] → Si promedio < 3/5 en alguna categoría:
      - [Slack] → ALERTA:
        "⚠️ SATISFACCIÓN BAJA en [Categoría]: [X]/5
         Requiere plan de acción inmediato.
         @[gerente_cuenta] @[gerente_operaciones]"
      - [Asana] → Crear tarea:
        "📋 Plan de acción: Mejorar [Categoría]"
        Prioridad: Alta
   
   e. [IF] → Si NPS < 7:
      - [Slack] → ALERTA:
        "⚠️ NPS BAJO: [Score]. Riesgo de pérdida de cliente.
         @[gerente_cuenta] @[director]"
      - [Asana] → Crear tarea de retención
```

---

### **Automatización 8: Control de Certificados y Licencias**

```
📌 TRIGGER: Cron job semanal (lunes a las 08:00 AM)

FLUJO EN n8n:

1. [Schedule Trigger] → Lunes 08:00 AM

2. [Google Sheets] → Leer inventario de certificados 
   y licencias del cliente:
   | Tipo | Nombre | Fecha Emisión | Fecha Vencimiento | 
   | Responsable | Proveedor | Notas |

3. [Function] → Calcular días para vencimiento:
   - Vencidos (días < 0)
   - Críticos (días ≤ 7)
   - Urgentes (días ≤ 30)
   - Atención (días ≤ 60)
   - Próximos (días ≤ 90)

4. [HTTP Request] → Verificar certificados SSL/TLS 
   en vivo (para cada dominio del cliente):
   - Conectar al dominio
   - Leer fecha de expiración del certificado
   - Comparar con inventario

5. [FOR EACH] → Según urgencia:
   
   a. VENCIDOS:
      [Slack] → "🚨 CERTIFICADO/LICENCIA VENCIDO
       ❌ [Tipo]: [Nombre]
       📅 Venció: [Fecha] ([X] días atrás)
       ⚠️ ACCIÓN INMEDIATA REQUERIDA
       @[responsable] @[líder_técnico]"
      [Asana] → Crear tarea URGENTE
      [Email] → Notificar al Gerente de Cuenta
   
   b. CRÍTICOS (≤ 7 días):
      [Slack] → "🔴 VENCIMIENTO INMINENTE
       ⏰ [Tipo]: [Nombre]
       📅 Vence: [Fecha] ([X] días)
       @[responsable]"
      [Asana] → Crear tarea prioridad Alta
   
   c. URGENTES (≤ 30 días):
      [Slack] → "🟠 VENCIMIENTO PRÓXIMO
       📋 [Tipo]: [Nombre]
       📅 Vence: [Fecha] ([X] días)
       @[responsable]"
      [Asana] → Crear tarea prioridad Media
   
   d. ATENCIÓN (≤ 60 días):
      Solo registro en log semanal

6. [Slack] → Resumen semanal de certificados/licencias:
   "📋 ESTADO DE CERTIFICADOS Y LICENCIAS
    
    ❌ Vencidos: [X]
    🔴 Vencen en < 7 días: [X]
    🟠 Vencen en < 30 días: [X]
    🟡 Vencen en < 60 días: [X]
    🟢 Vigentes (> 60 días): [X]
    
    [Detalle de los que requieren acción]"
```

---

## **4. Custom Fields Recomendados en Asana para la Fase 3**

| **Campo** | **Tipo** | **Opciones** | **Uso** |
|-----------|----------|--------------|---------|
| Tipo de Tarea | Dropdown | Incidente / Cambio / Mantenimiento / Mejora / Documentación / Reporte | Clasificación general |
| Severidad | Dropdown | 🔴 Crítica / 🟠 Alta / 🟡 Media / 🔵 Baja | Priorización |
| Categoría Técnica | Dropdown | Red / Seguridad / Firewall / VPN / Wi-Fi / SIEM / Monitoreo / Hardware | Categorización |
| Estado SLA | Dropdown | ✅ Dentro de SLA / ⚠️ En riesgo / ❌ Incumplido | Tracking de SLA |
| Ticket ID | Texto | INC-YYYY-NNNN / CHG-YYYY-NNNN | Referencia cruzada |
| Causa Raíz | Dropdown | Hardware / Software / Configuración / Red / Seguridad / Externo / Humano | Análisis |
| Recurrente | Dropdown | Sí / No | Detección de patrones |
| Requiere Post-Mortem | Dropdown | Sí / No | Seguimiento |
| Cliente Notificado | Dropdown | Sí / No / No Aplica | Comunicación |
| Frecuencia | Dropdown | Diaria / Semanal / Mensual / Trimestral / Semestral / Anual / Una vez | Tareas recurrentes |
| Ventana de Mantenimiento | Dropdown | Requerida / Programada / Completada / No Necesaria | Control de cambios |

---

## **5. Criterios de Operación Continua (KPIs Permanentes)**

```
📊 KPIs QUE SE DEBEN MANTENER PERMANENTEMENTE:

DISPONIBILIDAD
✅ Disponibilidad de red ≥ 99.9%
✅ Disponibilidad de servicios de seguridad ≥ 99.99%
✅ Uptime de VPN ≥ 99.9%

INCIDENTES
✅ Tiempo de respuesta (Crítico) ≤ 15 minutos
✅ Tiempo de respuesta (Alto) ≤ 1 hora
✅ Tiempo de resolución (Crítico) ≤ 4 horas
✅ Tiempo de resolución (Alto) ≤ 8 horas
✅ Resolución en primer contacto ≥ 70%
✅ Tasa de reapertura de tickets ≤ 5%
✅ 0 incidentes críticos por errores del proveedor

SEGURIDAD
✅ 0 brechas de seguridad por negligencia
✅ Vulnerabilidades críticas remediadas en ≤ 7 días
✅ Vulnerabilidades altas remediadas en ≤ 30 días
✅ Escaneos de vulnerabilidades ejecutados mensualmente
✅ 100% de alertas de seguridad críticas investigadas

CAMBIOS
✅ Tasa de éxito de cambios ≥ 95%
✅ 0 cambios no autorizados
✅ Documentación actualizada dentro de 24h post-cambio

MANTENIMIENTO
✅ 100% de mantenimientos preventivos ejecutados a tiempo
✅ Backups de configuración diarios exitosos al 100%
✅ Prueba de restore mensual exitosa

COMUNICACIÓN Y SATISFACCIÓN
✅ Informe mensual de SLA entregado a tiempo
✅ Satisfacción del cliente ≥ 4/5
✅ NPS ≥ 8
✅ 100% de reuniones programadas realizadas
```

---

Cuando estés listo, avanzamos a la **Fase 4: Optimización y Mejora Continua**, donde el proveedor identifica oportunidades para optimizar costos, mejorar rendimiento, fortalecer seguridad y agregar valor más allá del contrato base. Es la fase que diferencia a un proveedor promedio de uno excepcional.