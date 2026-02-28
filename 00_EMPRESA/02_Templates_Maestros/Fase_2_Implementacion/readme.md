# **FASE 2: IMPLEMENTACIÓN Y MIGRACIÓN**

## **Objetivo General**
Ejecutar la configuración técnica de la infraestructura de redes y seguridad del cliente, migrar los servicios desde la operación interna (o proveedor anterior) hacia el proveedor actual, realizar pruebas exhaustivas y garantizar que todo funcione según los SLA acordados antes de pasar a operación continua.

---

## **1. Desglose Detallado de Tareas**

### **Sección 2.1: Planificación de la Implementación**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.1.1 Revisar hallazgos de la Fase 1 | Analizar el gap analysis, assessment de seguridad y documentación recopilada para definir prioridades | Líder Técnico | Documento de prioridades técnicas | 2 días |
| 2.1.2 Diseñar arquitectura objetivo (TO-BE) | Crear el diseño de la arquitectura de red y seguridad deseada según requisitos del cliente | Arquitecto de Redes | Diagrama de arquitectura TO-BE | 5 días |
| 2.1.3 Elaborar plan de implementación detallado | Definir orden de ejecución, dependencias, recursos y tiempos para cada componente | Gerente de Proyecto | Plan de implementación aprobado | 3 días |
| 2.1.4 Definir plan de rollback | Documentar procedimientos de reversión en caso de fallo durante la implementación | Líder Técnico | Documento de rollback por componente | 2 días |
| 2.1.5 Crear plan de pruebas | Definir casos de prueba, criterios de aceptación y responsables de validación | Líder Técnico + Analista de Seguridad | Plan de pruebas detallado | 3 días |
| 2.1.6 Definir ventanas de mantenimiento | Coordinar con el cliente los horarios autorizados para realizar cambios con impacto | Gerente de Cuenta | Calendario de ventanas aprobado | 1 día |
| 2.1.7 Preparar inventario de licencias y recursos | Verificar disponibilidad de licencias, hardware, software y recursos necesarios | Administrador de Sistemas | Inventario validado | 2 días |
| 2.1.8 Reunión de aprobación del plan | Presentar el plan completo al cliente para obtener aprobación formal antes de ejecutar | Gerente de Cuenta + Líder Técnico | Acta de aprobación firmada | 1 día |

---

### **Sección 2.2: Configuración de Infraestructura de Red**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.2.1 Configurar segmentación de red (VLANs) | Implementar VLANs según diseño TO-BE para segmentar tráfico por departamento/función | Ingeniero de Redes | VLANs configuradas + documentación | 3 días |
| 2.2.2 Configurar routing y switching | Implementar protocolos de enrutamiento (OSPF, BGP, etc.) y configuración de switches | Ingeniero de Redes | Configuración de routing documentada | 4 días |
| 2.2.3 Configurar QoS (Quality of Service) | Implementar políticas de calidad de servicio para priorizar tráfico crítico | Ingeniero de Redes | Políticas QoS implementadas | 2 días |
| 2.2.4 Configurar redundancia de enlaces | Implementar alta disponibilidad en enlaces WAN/LAN (failover, load balancing) | Ingeniero de Redes | Redundancia configurada y probada | 3 días |
| 2.2.5 Configurar DNS y DHCP | Implementar o migrar servicios DNS y DHCP según diseño | Ingeniero de Redes | Servicios DNS/DHCP operativos | 2 días |
| 2.2.6 Configurar red inalámbrica | Implementar o reconfigurar infraestructura Wi-Fi (SSIDs, seguridad, roaming) | Ingeniero de Redes | Wi-Fi configurado y documentado | 3 días |
| 2.2.7 Configurar gestión de ancho de banda | Implementar control de tráfico y limitación de ancho de banda por servicio/usuario | Ingeniero de Redes | Políticas de bandwidth implementadas | 2 días |
| 2.2.8 Documentar configuraciones de red | Registrar todas las configuraciones en la wiki del cliente y hacer backup | Ingeniero de Redes | Wiki actualizada + backups en Oxidized | 2 días |

---

### **Sección 2.3: Configuración de Seguridad Perimetral**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.3.1 Configurar firewall perimetral | Implementar reglas de firewall según políticas de seguridad del cliente | Analista de Seguridad | Reglas de firewall documentadas | 5 días |
| 2.3.2 Configurar zonas de seguridad (DMZ) | Diseñar e implementar zona desmilitarizada para servicios expuestos | Analista de Seguridad | DMZ configurada y documentada | 3 días |
| 2.3.3 Implementar VPN site-to-site | Configurar túneles VPN entre sedes del cliente | Ingeniero de Redes | VPN S2S operativas y documentadas | 3 días |
| 2.3.4 Implementar VPN de acceso remoto | Configurar VPN para usuarios remotos con políticas de acceso | Ingeniero de Redes | VPN RA operativa y documentada | 2 días |
| 2.3.5 Configurar IDS/IPS | Desplegar sistema de detección/prevención de intrusos (ej: Suricata, Snort) | Analista de Seguridad | IDS/IPS operativo con reglas configuradas | 4 días |
| 2.3.6 Implementar filtrado web | Configurar proxy o filtrado de contenido web según políticas del cliente | Analista de Seguridad | Filtrado web operativo | 2 días |
| 2.3.7 Configurar protección anti-DDoS | Implementar medidas de mitigación contra ataques de denegación de servicio | Analista de Seguridad | Protección anti-DDoS configurada | 2 días |
| 2.3.8 Configurar NAT y port forwarding | Implementar traducciones de dirección y publicación de servicios | Ingeniero de Redes | NAT configurado y documentado | 1 día |
| 2.3.9 Hardening de dispositivos perimetrales | Aplicar guías de hardening a firewalls, routers y switches de borde | Analista de Seguridad | Checklist de hardening completado | 3 días |

---

### **Sección 2.4: Configuración de Seguridad Interna**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.4.1 Implementar autenticación multifactor (MFA) | Configurar MFA para accesos administrativos y críticos | Administrador de Sistemas | MFA habilitado en sistemas críticos | 3 días |
| 2.4.2 Configurar NAC (Network Access Control) | Implementar control de acceso a la red por dispositivo/usuario | Analista de Seguridad | NAC operativo | 4 días |
| 2.4.3 Implementar SIEM | Desplegar solución SIEM (ej: Wazuh) para correlación de eventos | Analista de Seguridad | SIEM operativo con fuentes configuradas | 5 días |
| 2.4.4 Configurar centralización de logs | Implementar recolección centralizada de logs de todos los dispositivos | Analista de Seguridad | Logs centralizados y accesibles | 3 días |
| 2.4.5 Implementar políticas de contraseñas | Configurar políticas de complejidad, rotación y bloqueo de contraseñas | Administrador de Sistemas | Políticas implementadas | 1 día |
| 2.4.6 Configurar segmentación de acceso (Zero Trust) | Implementar principio de mínimo privilegio en accesos a redes y sistemas | Analista de Seguridad | Políticas de acceso implementadas | 4 días |
| 2.4.7 Implementar cifrado de comunicaciones | Configurar TLS/SSL en servicios internos y protocolos seguros | Analista de Seguridad | Cifrado implementado y verificado | 2 días |
| 2.4.8 Configurar protección de endpoints (si aplica) | Implementar o verificar solución EDR/antivirus en endpoints | Analista de Seguridad | Endpoints protegidos | 3 días |

---

### **Sección 2.5: Implementación de Monitoreo y Alertas**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.5.1 Configurar monitoreo de disponibilidad | Implementar checks de uptime para todos los servicios críticos (Uptime Kuma/Zabbix) | Ingeniero de Redes | Monitoreo de uptime operativo | 2 días |
| 2.5.2 Configurar monitoreo de performance | Implementar métricas de rendimiento (CPU, RAM, ancho de banda, latencia) | Ingeniero de Redes | Dashboard de performance en Grafana | 3 días |
| 2.5.3 Configurar monitoreo de seguridad | Implementar alertas de seguridad (intentos de intrusión, malware, anomalías) | Analista de Seguridad | Alertas de seguridad operativas | 3 días |
| 2.5.4 Configurar dashboards operativos | Crear dashboards en Grafana con métricas clave de red y seguridad | Ingeniero de Redes | Dashboards publicados y accesibles | 3 días |
| 2.5.5 Configurar alertas y notificaciones | Definir umbrales y canales de notificación (Slack, email, SMS) para cada tipo de alerta | Ingeniero de Redes | Matriz de alertas configurada | 2 días |
| 2.5.6 Configurar monitoreo de SLA | Implementar medición automática de métricas de SLA (disponibilidad, tiempo de respuesta) | Ingeniero de Redes | Dashboard de SLA en Grafana | 2 días |
| 2.5.7 Documentar playbooks de respuesta | Crear guías paso a paso para responder a cada tipo de alerta | Líder Técnico | Playbooks documentados en wiki | 5 días |
| 2.5.8 Validar sistema de monitoreo end-to-end | Probar el flujo completo: generación de alerta → notificación → registro de ticket | Líder Técnico | Informe de validación de monitoreo | 2 días |

---

### **Sección 2.6: Migración de Servicios**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.6.1 Realizar backup pre-migración | Hacer respaldo completo de todas las configuraciones antes de iniciar la migración | Ingeniero de Redes | Backup verificado y almacenado | 1 día |
| 2.6.2 Ejecutar migración piloto | Migrar un servicio o segmento no crítico como prueba de concepto | Ingeniero de Redes | Informe de migración piloto | 3 días |
| 2.6.3 Validar migración piloto | Verificar funcionalidad completa del servicio migrado | Líder Técnico + Cliente | Checklist de validación firmado | 2 días |
| 2.6.4 Ajustar plan según resultados piloto | Modificar el plan de migración basado en lecciones de la prueba piloto | Gerente de Proyecto | Plan de migración actualizado | 1 día |
| 2.6.5 Comunicar ventana de migración | Notificar a todos los stakeholders sobre la ventana de migración productiva | Gerente de Cuenta | Comunicación enviada y confirmada | 1 día |
| 2.6.6 Ejecutar migración productiva Fase A | Migrar servicios de prioridad alta según el plan (ej: firewalls, core network) | Ingeniero de Redes + Analista | Servicios Fase A migrados | 3-5 días |
| 2.6.7 Validar migración Fase A | Verificar funcionalidad de servicios migrados en Fase A | Líder Técnico + Cliente | Checklist de validación Fase A | 2 días |
| 2.6.8 Ejecutar migración productiva Fase B | Migrar servicios de prioridad media (ej: Wi-Fi, VPN, accesos remotos) | Ingeniero de Redes + Analista | Servicios Fase B migrados | 3-5 días |
| 2.6.9 Validar migración Fase B | Verificar funcionalidad de servicios migrados en Fase B | Líder Técnico + Cliente | Checklist de validación Fase B | 2 días |
| 2.6.10 Ejecutar migración productiva Fase C | Migrar servicios de prioridad baja (ej: monitoreo, reportería, optimizaciones) | Ingeniero de Redes | Servicios Fase C migrados | 2-3 días |
| 2.6.11 Validar migración completa | Verificación integral de TODOS los servicios migrados | Líder Técnico + Cliente | Checklist de validación completa | 3 días |
| 2.6.12 Realizar backup post-migración | Hacer respaldo completo de las nuevas configuraciones | Ingeniero de Redes | Backup post-migración verificado | 1 día |

---

### **Sección 2.7: Pruebas y Validación**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.7.1 Ejecutar pruebas de conectividad | Verificar conectividad entre todos los segmentos de red, sedes y servicios externos | Ingeniero de Redes | Informe de pruebas de conectividad | 2 días |
| 2.7.2 Ejecutar pruebas de rendimiento | Medir throughput, latencia y jitter en enlaces críticos | Ingeniero de Redes | Informe de pruebas de performance | 2 días |
| 2.7.3 Ejecutar pruebas de failover | Simular caídas de enlaces y verificar que la redundancia funcione correctamente | Ingeniero de Redes | Informe de pruebas de failover | 2 días |
| 2.7.4 Ejecutar pruebas de penetración | Realizar pentesting interno y externo para validar la postura de seguridad | Analista de Seguridad | Informe de pentesting | 5 días |
| 2.7.5 Ejecutar escaneo de vulnerabilidades | Realizar escaneo completo con OpenVAS/Nessus y documentar hallazgos | Analista de Seguridad | Informe de vulnerabilidades | 3 días |
| 2.7.6 Ejecutar pruebas de VPN | Verificar conexiones VPN S2S y RA desde diferentes ubicaciones | Ingeniero de Redes | Informe de pruebas VPN | 1 día |
| 2.7.7 Ejecutar pruebas de firewall | Verificar que las reglas de firewall permitan solo tráfico autorizado | Analista de Seguridad | Informe de validación de reglas | 2 días |
| 2.7.8 Ejecutar pruebas de monitoreo | Simular incidentes para verificar que las alertas y notificaciones funcionen | Ingeniero de Redes | Informe de validación de monitoreo | 1 día |
| 2.7.9 Ejecutar pruebas de restauración | Verificar que los backups de configuración se pueden restaurar exitosamente | Ingeniero de Redes | Informe de pruebas de restore | 2 días |
| 2.7.10 Ejecutar pruebas de usuario final | Coordinar con usuarios del cliente para validar acceso a servicios y aplicaciones | Gerente de Proyecto | Formulario de validación de usuarios | 2 días |
| 2.7.11 Remediar hallazgos de pruebas | Corregir todos los problemas encontrados durante las pruebas | Equipo Técnico | Log de remediación | 3-5 días |
| 2.7.12 Re-ejecutar pruebas fallidas | Repetir las pruebas que fallaron después de la remediación | Equipo Técnico | Informe de re-test | 2 días |

---

### **Sección 2.8: Aceptación y Cierre de Fase**

| **Tarea** | **Descripción Detallada** | **Responsable** | **Entregable** | **Duración** |
|-----------|--------------------------|-----------------|----------------|--------------|
| 2.8.1 Compilar documentación técnica final | Reunir toda la documentación generada durante la implementación | Líder Técnico | Paquete de documentación técnica | 3 días |
| 2.8.2 Crear documento AS-BUILT | Documentar la arquitectura implementada exactamente como quedó configurada | Arquitecto de Redes | Documento AS-BUILT completo | 3 días |
| 2.8.3 Actualizar inventario de activos | Registrar todos los equipos, licencias y configuraciones en el inventario | Administrador de Sistemas | Inventario actualizado | 2 días |
| 2.8.4 Capacitar al equipo de operaciones | Transferir conocimiento al equipo que operará el servicio día a día | Líder Técnico | Registro de capacitación + material | 3 días |
| 2.8.5 Realizar reunión de aceptación con cliente | Presentar resultados de implementación y pruebas para obtener aprobación | Gerente de Cuenta + Líder Técnico | Acta de aceptación firmada | 1 día |
| 2.8.6 Obtener sign-off del cliente | Firma formal del cliente aceptando la implementación | Gerente de Cuenta | Documento de aceptación firmado | 1 día |
| 2.8.7 Realizar retrospectiva de implementación | Sesión interna para identificar lecciones aprendidas | Gerente de Proyecto | Documento de lecciones aprendidas | 1 día |
| 2.8.8 Transicionar a operación continua | Handoff formal al equipo de operaciones e inicio de la Fase 3 | Gerente de Proyecto | Acta de transición a operación | 1 día |

---

## **2. Templates Detallados para la Fase 2**

### **Template 1: Plan de Implementación**

```markdown
# 📋 PLAN DE IMPLEMENTACIÓN
## Proyecto: [Código] - [Nombre del Cliente]
## Versión: [X.X] | Fecha: [DD/MM/YYYY]
## Estado: [ ] Borrador [ ] En Revisión [ ] Aprobado

---

### 1. INFORMACIÓN GENERAL
- **Cliente:** [Nombre]
- **Gerente de Proyecto:** [Nombre]
- **Líder Técnico:** [Nombre]
- **Fecha inicio planificada:** [DD/MM/YYYY]
- **Fecha fin planificada:** [DD/MM/YYYY]
- **Duración total estimada:** [X] semanas

### 2. ALCANCE DE LA IMPLEMENTACIÓN
#### Incluido:
- [ ] Segmentación de red (VLANs)
- [ ] Configuración de routing/switching
- [ ] Firewall perimetral
- [ ] VPN (Site-to-Site / Remote Access)
- [ ] IDS/IPS
- [ ] SIEM
- [ ] Monitoreo y alertas
- [ ] Red inalámbrica
- [ ] NAC
- [ ] [Otros]

#### Excluido:
- [ ] [Listar explícitamente]

### 3. PREREQUISITOS
| # | Prerequisito | Responsable | Estado | Fecha Límite |
|---|-------------|-------------|--------|--------------|
| 1 | Accesos remotos configurados | Cliente | ✅/❌ | |
| 2 | Ventanas de mantenimiento aprobadas | Cliente | ✅/❌ | |
| 3 | Licencias disponibles | Proveedor | ✅/❌ | |
| 4 | Hardware en sitio | Cliente | ✅/❌ | |
| 5 | Backup de configuración actual | Proveedor | ✅/❌ | |
| 6 | Plan de rollback documentado | Proveedor | ✅/❌ | |

### 4. CRONOGRAMA DE IMPLEMENTACIÓN
| Semana | Componente | Actividades | Ventana de Mant. | Riesgo | Responsable |
|--------|-----------|-------------|-------------------|--------|-------------|
| S1 | Segmentación | VLANs, routing básico | Sáb 22:00-06:00 | Medio | Ing. Redes |
| S2 | Core Network | Routing avanzado, QoS, redundancia | Sáb 22:00-06:00 | Alto | Ing. Redes |
| S3 | Seguridad Perimetral | Firewall, DMZ, NAT | Dom 00:00-06:00 | Alto | Analista Seg. |
| S4 | VPN | S2S, Remote Access | Sáb 22:00-06:00 | Medio | Ing. Redes |
| S5 | Seguridad Interna | IDS/IPS, NAC, MFA | Sáb 22:00-06:00 | Medio | Analista Seg. |
| S6 | SIEM y Logs | Wazuh, centralización | Sin impacto | Bajo | Analista Seg. |
| S7 | Monitoreo | Zabbix, Grafana, alertas | Sin impacto | Bajo | Ing. Redes |
| S8 | Wi-Fi | SSIDs, seguridad, roaming | Dom 00:00-06:00 | Medio | Ing. Redes |
| S9 | Pruebas | Todas las pruebas | Varias | Medio | Todo equipo |
| S10 | Remediación | Corrección de hallazgos | Según necesidad | Variable | Todo equipo |

### 5. PLAN DE ROLLBACK
| Componente | Procedimiento de Rollback | Tiempo Estimado | Responsable |
|-----------|---------------------------|-----------------|-------------|
| VLANs | Restaurar configuración backup de switches | 30 min | Ing. Redes |
| Firewall | Restaurar reglas anteriores desde backup | 1 hora | Analista Seg. |
| VPN | Revertir configuración de túneles | 45 min | Ing. Redes |
| DNS/DHCP | Restaurar zonas y pools anteriores | 20 min | Ing. Redes |

### 6. MATRIZ DE RIESGOS DE IMPLEMENTACIÓN
| # | Riesgo | Probabilidad | Impacto | Mitigación | Responsable |
|---|--------|:---:|:---:|------------|-------------|
| 1 | Caída de servicio durante migración | Media | Alto | Ventana de mant. + rollback | Líder Técnico |
| 2 | Incompatibilidad de hardware | Baja | Alto | Validación previa de compatibilidad | Arq. Redes |
| 3 | Pérdida de configuraciones | Baja | Crítico | Backup previo + verificación | Ing. Redes |
| 4 | Retrasos por dependencias del cliente | Alta | Medio | Seguimiento proactivo | Ger. Proyecto |
| 5 | Vulnerabilidades post-implementación | Media | Alto | Pentesting + escaneo | Analista Seg. |

### 7. CRITERIOS DE ACEPTACIÓN
| # | Criterio | Método de Verificación | Responsable |
|---|----------|----------------------|-------------|
| 1 | Disponibilidad de red ≥ 99.9% durante pruebas | Monitoreo Uptime Kuma 72h | Ing. Redes |
| 2 | Latencia < 10ms en enlaces LAN | Pruebas con iperf/ping | Ing. Redes |
| 3 | Cero vulnerabilidades críticas abiertas | Escaneo OpenVAS | Analista Seg. |
| 4 | VPN operativas desde todas las sedes | Pruebas de conectividad | Ing. Redes |
| 5 | Alertas de monitoreo funcionando | Simulación de incidentes | Ing. Redes |
| 6 | Failover operativo en < 30 segundos | Prueba de failover | Ing. Redes |

### 8. APROBACIONES
| Rol | Nombre | Firma | Fecha |
|-----|--------|-------|-------|
| Gerente de Proyecto (Proveedor) | | | |
| Líder Técnico (Proveedor) | | | |
| Contacto Técnico (Cliente) | | | |
| Sponsor (Cliente) | | | |
```

---

### **Template 2: Documento AS-BUILT**

```markdown
# 🏗️ DOCUMENTO AS-BUILT
## Proyecto: [Código] - [Nombre del Cliente]
## Versión: [X.X] | Fecha: [DD/MM/YYYY]
## Clasificación: CONFIDENCIAL

---

### 1. INFORMACIÓN GENERAL
- **Cliente:** [Nombre]
- **Ubicación(es):** [Direcciones]
- **Fecha de implementación:** [DD/MM/YYYY]
- **Arquitecto responsable:** [Nombre]

### 2. DIAGRAMA DE ARQUITECTURA IMPLEMENTADA
> [Insertar diagrama de red actualizado - Draw.io/Lucidchart]
> 
> Incluir:
> - Topología física
> - Topología lógica
> - Flujo de tráfico
> - Zonas de seguridad

### 3. INVENTARIO DE EQUIPOS
#### 3.1 Equipos de Red
| # | Equipo | Marca/Modelo | Hostname | IP Mgmt | Ubicación | S/N | Firmware | Función |
|---|--------|-------------|----------|---------|-----------|-----|----------|---------|
| 1 | Router Core | | | | | | | |
| 2 | Switch Core | | | | | | | |
| 3 | Switch Acceso | | | | | | | |
| 4 | Access Point | | | | | | | |

#### 3.2 Equipos de Seguridad
| # | Equipo | Marca/Modelo | Hostname | IP Mgmt | Ubicación | S/N | Firmware | Función |
|---|--------|-------------|----------|---------|-----------|-----|----------|---------|
| 1 | Firewall | | | | | | | |
| 2 | IDS/IPS | | | | | | | |
| 3 | WAF | | | | | | | |

### 4. CONFIGURACIÓN DE RED
#### 4.1 VLANs
| VLAN ID | Nombre | Subred | Gateway | DHCP | Descripción |
|---------|--------|--------|---------|------|-------------|
| 10 | Servidores | 10.0.10.0/24 | 10.0.10.1 | No | Servidores de producción |
| 20 | Usuarios | 10.0.20.0/24 | 10.0.20.1 | Sí | Estaciones de trabajo |
| 30 | VoIP | 10.0.30.0/24 | 10.0.30.1 | Sí | Telefonía IP |
| 40 | IoT | 10.0.40.0/24 | 10.0.40.1 | Sí | Dispositivos IoT |
| 99 | Management | 10.0.99.0/24 | 10.0.99.1 | No | Gestión de equipos |
| 100 | DMZ | 10.0.100.0/24 | 10.0.100.1 | No | Servicios públicos |

#### 4.2 Routing
| Protocolo | Áreas/AS | Redes Anunciadas | Vecinos | Notas |
|-----------|----------|-----------------|---------|-------|
| OSPF | Area 0 | | | |
| BGP | AS XXXXX | | | |
| Estáticas | N/A | | | |

#### 4.3 DNS
| Servidor | IP | Tipo | Zonas | Notas |
|----------|----|------|-------|-------|
| DNS Primario | | Autoritativo | | |
| DNS Secundario | | Recursivo | | |
| DNS Externo | 8.8.8.8 | Forwarder | | |

#### 4.4 DHCP
| Pool | Rango | Gateway | DNS | Lease Time | Exclusiones |
|------|-------|---------|-----|------------|-------------|
| Usuarios | 10.0.20.100-254 | 10.0.20.1 | 10.0.10.5 | 8h | 10.0.20.1-99 |

### 5. CONFIGURACIÓN DE SEGURIDAD
#### 5.1 Reglas de Firewall (Resumen)
| # | Nombre | Origen | Destino | Puerto/Protocolo | Acción | Log |
|---|--------|--------|---------|-----------------|--------|-----|
| 1 | Allow-DNS | VLAN 20 | DNS Server | UDP/53 | Permit | Sí |
| 2 | Allow-Web | VLAN 20 | Any | TCP/80,443 | Permit | No |
| 3 | Block-IoT-to-Servers | VLAN 40 | VLAN 10 | Any | Deny | Sí |
| ... | Default Deny | Any | Any | Any | Deny | Sí |

> **Nota:** Archivo completo de reglas adjunto como anexo

#### 5.2 VPN
| Tipo | Nombre | Peer Local | Peer Remoto | Subred Local | Subred Remota | Cifrado | Estado |
|------|--------|-----------|-------------|-------------|---------------|---------|--------|
| S2S | Sede-A-B | x.x.x.x | y.y.y.y | 10.0.0.0/16 | 10.1.0.0/16 | AES-256 | Activa |
| RA | RemoteAccess | x.x.x.x | Pool | Pool VPN | Según perfil | AES-256 | Activa |

#### 5.3 IDS/IPS
| Parámetro | Valor |
|-----------|-------|
| Solución | Suricata [Versión] |
| Modo | IPS (inline) |
| Rulesets | ET Open + Custom |
| Actualización de reglas | Diaria automática |
| Interfaces monitoreadas | [Lista] |
| Dashboard | [URL Grafana] |

#### 5.4 SIEM
| Parámetro | Valor |
|-----------|-------|
| Solución | Wazuh [Versión] |
| Agentes instalados | [Número] |
| Fuentes de log | [Lista] |
| Retención de logs | [X] días |
| Dashboard | [URL Wazuh] |
| Alertas configuradas | [Número] |

### 6. MONITOREO
#### 6.1 Herramientas Implementadas
| Herramienta | Versión | Función | URL | Credenciales (Ref) |
|-------------|---------|---------|-----|---------------------|
| Zabbix | | Monitoreo infraestructura | | Vaultwarden #XX |
| Grafana | | Dashboards | | Vaultwarden #XX |
| Uptime Kuma | | Monitoreo disponibilidad | | Vaultwarden #XX |
| Wazuh | | SIEM | | Vaultwarden #XX |

#### 6.2 Dashboards Disponibles
| Dashboard | URL | Descripción | Refresh Rate |
|-----------|-----|-------------|:---:|
| Network Overview | | Vista general de red | 30s |
| Security Events | | Eventos de seguridad | 60s |
| SLA Metrics | | Métricas de SLA | 5min |
| Bandwidth Usage | | Consumo de ancho de banda | 30s |

#### 6.3 Alertas Configuradas
| # | Alerta | Severidad | Umbral | Notificación | Playbook |
|---|--------|-----------|--------|--------------|----------|
| 1 | Host Down | Crítica | 3 min sin respuesta | Slack + SMS | PB-001 |
| 2 | High CPU | Alta | >90% por 5 min | Slack | PB-002 |
| 3 | Link Down | Crítica | Interface down | Slack + SMS | PB-003 |
| 4 | Security Alert | Crítica | SIEM high severity | Slack + SMS + Ticket | PB-004 |
| 5 | Disk Full | Alta | >85% | Slack | PB-005 |
| 6 | Backup Failed | Alta | Fallo en backup | Slack | PB-006 |

### 7. CREDENCIALES Y ACCESOS
> ⚠️ Todas las credenciales están almacenadas en Vaultwarden
> Referencia: [URL del vault] - Carpeta: [Nombre del cliente]
> 
> NO incluir contraseñas en este documento

### 8. ANEXOS
- [ ] Anexo A: Configuración completa de firewall
- [ ] Anexo B: Configuración de switches
- [ ] Anexo C: Configuración de routers
- [ ] Anexo D: Diagramas detallados
- [ ] Anexo E: Resultados de pruebas

---
**Elaborado por:** [Nombre] | Fecha: [DD/MM/YYYY]
**Revisado por:** [Nombre] | Fecha: [DD/MM/YYYY]
**Aprobado por:** [Nombre] | Fecha: [DD/MM/YYYY]
```

---

### **Template 3: Checklist de Validación de Migración**

```markdown
# ✅ CHECKLIST DE VALIDACIÓN DE MIGRACIÓN
## Proyecto: [Código] - [Nombre del Cliente]
## Fase de Migración: [ ] Piloto [ ] Fase A [ ] Fase B [ ] Fase C [ ] Completa
## Fecha: [DD/MM/YYYY]
## Ejecutado por: [Nombre]

---

### 1. CONECTIVIDAD
| # | Prueba | Resultado | Evidencia | Notas |
|---|--------|:---------:|-----------|-------|
| 1.1 | Ping entre todas las VLANs | ✅/❌ | [Screenshot] | |
| 1.2 | Ping a gateway de cada VLAN | ✅/❌ | | |
| 1.3 | Resolución DNS interna | ✅/❌ | | |
| 1.4 | Resolución DNS externa | ✅/❌ | | |
| 1.5 | Acceso a internet desde cada VLAN | ✅/❌ | | |
| 1.6 | Conectividad entre sedes (VPN S2S) | ✅/❌ | | |
| 1.7 | VPN de acceso remoto | ✅/❌ | | |
| 1.8 | Acceso a servidores críticos | ✅/❌ | | |
| 1.9 | Conectividad Wi-Fi (todos los SSIDs) | ✅/❌ | | |
| 1.10 | Traceroute path correcto | ✅/❌ | | |

### 2. RENDIMIENTO
| # | Prueba | Valor Esperado | Valor Obtenido | Resultado | Notas |
|---|--------|:-:|:-:|:---------:|-------|
| 2.1 | Throughput LAN | ≥ 1 Gbps | | ✅/❌ | |
| 2.2 | Throughput WAN | ≥ [X] Mbps | | ✅/❌ | |
| 2.3 | Latencia LAN | < 1 ms | | ✅/❌ | |
| 2.4 | Latencia WAN | < [X] ms | | ✅/❌ | |
| 2.5 | Jitter VoIP | < 30 ms | | ✅/❌ | |
| 2.6 | Packet loss | 0% | | ✅/❌ | |

### 3. SEGURIDAD
| # | Prueba | Resultado | Evidencia | Notas |
|---|--------|:---------:|-----------|-------|
| 3.1 | Reglas de firewall permiten tráfico autorizado | ✅/❌ | | |
| 3.2 | Reglas de firewall bloquean tráfico no autorizado | ✅/❌ | | |
| 3.3 | IDS/IPS detectando amenazas de prueba | ✅/❌ | | |
| 3.4 | SIEM recibiendo logs de todas las fuentes | ✅/❌ | | |
| 3.5 | MFA funcionando en accesos críticos | ✅/❌ | | |
| 3.6 | Certificados SSL/TLS válidos | ✅/❌ | | |
| 3.7 | Segmentación de red funcionando (VLAN isolation) | ✅/❌ | | |
| 3.8 | NAC bloqueando dispositivos no autorizados | ✅/❌ | | |

### 4. SERVICIOS
| # | Servicio | Estado Pre-Migración | Estado Post-Migración | Resultado | Notas |
|---|---------|:---:|:---:|:---------:|-------|
| 4.1 | Email | Operativo | | ✅/❌ | |
| 4.2 | ERP | Operativo | | ✅/❌ | |
| 4.3 | CRM | Operativo | | ✅/❌ | |
| 4.4 | Telefonía IP | Operativo | | ✅/❌ | |
| 4.5 | [Servicio X] | Operativo | | ✅/❌ | |

### 5. MONITOREO Y ALERTAS
| # | Prueba | Resultado | Evidencia | Notas |
|---|--------|:---------:|-----------|-------|
| 5.1 | Dashboard de red visible y actualizado | ✅/❌ | | |
| 5.2 | Alertas de host down funcionando | ✅/❌ | | |
| 5.3 | Alertas de seguridad funcionando | ✅/❌ | | |
| 5.4 | Notificaciones en Slack llegando | ✅/❌ | | |
| 5.5 | Tickets se crean automáticamente | ✅/❌ | | |

### 6. BACKUPS
| # | Prueba | Resultado | Evidencia | Notas |
|---|--------|:---------:|-----------|-------|
| 6.1 | Backup de configuración actual almacenado | ✅/❌ | | |
| 6.2 | Backup verificado (restore test) | ✅/❌ | | |
| 6.3 | Oxidized/RANCID recopilando configs | ✅/❌ | | |

### 7. RESUMEN
| Categoría | Total Pruebas | Aprobadas | Fallidas | % Éxito |
|-----------|:---:|:---:|:---:|:---:|
| Conectividad | | | | |
| Rendimiento | | | | |
| Seguridad | | | | |
| Servicios | | | | |
| Monitoreo | | | | |
| Backups | | | | |
| **TOTAL** | | | | |

### 8. HALLAZGOS Y REMEDIACIÓN
| # | Hallazgo | Severidad | Acción Correctiva | Responsable | Fecha Límite | Estado |
|---|----------|-----------|-------------------|-------------|:---:|:---:|
| 1 | | | | | | |

### 9. DECISIÓN
- [ ] ✅ APROBADO: Todos los criterios cumplidos
- [ ] ⚠️ APROBADO CON CONDICIONES: Hallazgos menores pendientes
- [ ] ❌ RECHAZADO: Hallazgos críticos que requieren remediación

### FIRMAS
| Proveedor | Cliente |
|-----------|---------|
| Nombre: __________ | Nombre: __________ |
| Cargo: ___________ | Cargo: ___________ |
| Firma: ____________ | Firma: ____________ |
| Fecha: ____________ | Fecha: ____________ |
```

---

### **Template 4: Informe de Pruebas de Penetración**

```markdown
# 🔐 INFORME DE PRUEBAS DE PENETRACIÓN
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY]
## Clasificación: ESTRICTAMENTE CONFIDENCIAL

---

### RESUMEN EJECUTIVO
> [Resumen ejecutivo de 1 página para audiencia no técnica]

### 1. ALCANCE
- **Tipo de prueba:** [ ] Black Box [ ] Grey Box [ ] White Box
- **Pruebas realizadas:** [ ] Externa [ ] Interna [ ] Wi-Fi [ ] Social Engineering
- **Redes evaluadas:** [Lista de subredes]
- **Sistemas evaluados:** [Lista de sistemas]
- **Exclusiones:** [Lo que NO se probó]
- **Período:** [Fecha inicio] - [Fecha fin]

### 2. METODOLOGÍA
- **Framework utilizado:** OWASP / PTES / NIST
- **Herramientas:**
  - Reconocimiento: Nmap, Shodan, Maltego
  - Escaneo: OpenVAS, Nikto
  - Explotación: Metasploit, Burp Suite CE
  - Post-explotación: [Herramientas]
  - Inalámbrico: Aircrack-ng, Kismet

### 3. HALLAZGOS

#### Resumen de Hallazgos
| Severidad | Cantidad | Porcentaje |
|-----------|:---:|:---:|
| 🔴 Crítica | | |
| 🟠 Alta | | |
| 🟡 Media | | |
| 🔵 Baja | | |
| ⚪ Informativa | | |
| **Total** | | **100%** |

#### Hallazgo #1: [Título]
| Campo | Detalle |
|-------|---------|
| **ID** | PT-001 |
| **Severidad** | 🔴 Crítica |
| **CVSS** | [Score] |
| **Categoría** | [Ej: Configuración insegura] |
| **Sistema afectado** | [IP/Hostname] |
| **Descripción** | [Descripción detallada del hallazgo] |
| **Evidencia** | [Screenshots, logs, comandos] |
| **Impacto** | [Qué podría hacer un atacante] |
| **Recomendación** | [Pasos para remediar] |
| **Referencia** | [CVE, CWE, enlace] |

> [Repetir para cada hallazgo]

### 4. CADENA DE ATAQUE (KILL CHAIN)
```
1. Reconocimiento → [Hallazgos]
2. Escaneo → [Hallazgos]
3. Acceso Inicial → [Hallazgos]
4. Escalamiento → [Hallazgos]
5. Movimiento Lateral → [Hallazgos]
6. Exfiltración → [Hallazgos]
```

### 5. PLAN DE REMEDIACIÓN
| Prioridad | Hallazgo | Acción | Esfuerzo | Plazo Sugerido |
|:---------:|----------|--------|:--------:|:--------------:|
| 1 | PT-001 | [Acción] | [Horas] | Inmediato |
| 2 | PT-002 | [Acción] | [Horas] | 7 días |
| 3 | PT-003 | [Acción] | [Horas] | 30 días |

### 6. CONCLUSIONES
> [Conclusiones y valoración general de la postura de seguridad]

### 7. DISCLAIMER
> Este informe refleja el estado de seguridad en el momento 
> de las pruebas. Nuevas vulnerabilidades pueden aparecer 
> después de la fecha de este informe.

---
**Pentester:** [Nombre] | [Certificaciones]
**Revisado por:** [Nombre] | [Cargo]
**Entregado a:** [Nombre contacto cliente]
```

---

### **Template 5: Playbook de Respuesta a Alertas**

```markdown
# 📖 PLAYBOOK DE RESPUESTA A ALERTAS
## Proyecto: [Código] - [Nombre del Cliente]
## Versión: [X.X] | Última actualización: [DD/MM/YYYY]

---

## PLAYBOOK PB-001: HOST DOWN (Servicio Caído)

### Información General
| Campo | Valor |
|-------|-------|
| **ID** | PB-001 |
| **Alerta** | Host Down / Service Unavailable |
| **Severidad** | 🔴 Crítica |
| **SLA de Respuesta** | 15 minutos |
| **SLA de Resolución** | 4 horas |
| **Herramienta de detección** | Zabbix / Uptime Kuma |
| **Notificación** | Slack #incidentes + SMS |

### Procedimiento Paso a Paso
```
PASO 1: VERIFICAR LA ALERTA (0-5 min)
├── 1.1 Verificar en dashboard de monitoreo si la alerta es legítima
├── 1.2 Descartar falso positivo (verificar conectividad del sensor)
├── 1.3 Si es falso positivo → Cerrar alerta + documentar
└── 1.4 Si es legítima → Continuar al Paso 2

PASO 2: DIAGNÓSTICO INICIAL (5-15 min)
├── 2.1 Verificar conectividad al host (ping, traceroute)
├── 2.2 Verificar estado de interfaces (up/down)
├── 2.3 Verificar logs del dispositivo
├── 2.4 Verificar si hay cambios recientes programados
├── 2.5 Identificar alcance del impacto (¿qué servicios afecta?)
└── 2.6 Comunicar al cliente: "[Hora] Estamos investigando 
     una alerta de disponibilidad en [servicio]. 
     Actualizaremos en [X] minutos."

PASO 3: RESOLUCIÓN (15-60 min)
├── Escenario A: Problema de conectividad de red
│   ├── Verificar estado de puertos del switch
│   ├── Verificar cables/SFPs
│   ├── Reiniciar puerto/interfaz
│   └── Si persiste → Escalar a Nivel 2
├── Escenario B: Problema de hardware
│   ├── Verificar indicadores LED del equipo
│   ├── Verificar alimentación eléctrica
│   ├── Reiniciar equipo (con aprobación)
│   └── Si persiste → Contactar soporte del fabricante
├── Escenario C: Problema de software/configuración
│   ├── Revisar logs de errores
│   ├── Verificar cambios recientes
│   ├── Restaurar configuración anterior si aplica
│   └── Si persiste → Escalar a Nivel 3
└── Escenario D: Problema de ISP/Enlace externo
    ├── Verificar estado del enlace con ISP
    ├── Abrir ticket con ISP
    ├── Activar enlace de respaldo si existe
    └── Comunicar al cliente tiempo estimado del ISP

PASO 4: VERIFICACIÓN (Post-resolución)
├── 4.1 Confirmar que el servicio está operativo
├── 4.2 Verificar que el monitoreo muestra estado normal
├── 4.3 Verificar que no hay efectos colaterales
└── 4.4 Comunicar al cliente: "[Hora] El servicio [X] ha sido 
     restaurado. Causa: [breve]. Acciones: [resumen]."

PASO 5: DOCUMENTACIÓN
├── 5.1 Actualizar ticket con toda la información
├── 5.2 Registrar timeline del incidente
├── 5.3 Documentar causa raíz
├── 5.4 Documentar acciones realizadas
├── 5.5 Identificar acciones preventivas
└── 5.6 Si fue incidente mayor → Programar post-mortem
```

### Contactos de Escalamiento
| Nivel | Tiempo | Contacto | Teléfono | Método |
|:-----:|:------:|----------|----------|--------|
| 1 | 0-30 min | [Ingeniero de turno] | | Slack |
| 2 | 30-60 min | [Líder Técnico] | | Teléfono |
| 3 | 60-120 min | [Gerente de Operaciones] | | Teléfono |
| 4 | >120 min | [Director + Cliente] | | War Room |

### Herramientas Necesarias
- [ ] Acceso SSH/Telnet al equipo
- [ ] Acceso a consola de monitoreo (Zabbix)
- [ ] Acceso a logs centralizados (Wazuh)
- [ ] Credenciales en Vaultwarden
- [ ] Contacto del ISP
- [ ] Backup de configuración (Oxidized)

---

## PLAYBOOK PB-002: HIGH CPU / MEMORY
[Estructura similar al PB-001]

## PLAYBOOK PB-003: LINK DOWN
[Estructura similar al PB-001]

## PLAYBOOK PB-004: SECURITY ALERT
[Estructura similar al PB-001]

## PLAYBOOK PB-005: DISK FULL
[Estructura similar al PB-001]

## PLAYBOOK PB-006: BACKUP FAILED
[Estructura similar al PB-001]

## PLAYBOOK PB-007: BRUTE FORCE DETECTED
[Estructura similar al PB-001]

## PLAYBOOK PB-008: MALWARE DETECTED
[Estructura similar al PB-001]
```

---

### **Template 6: Control de Cambios de Implementación**

```markdown
# 🔄 REGISTRO DE CONTROL DE CAMBIOS
## Proyecto: [Código] - [Nombre del Cliente]

---

### CAMBIO #[NÚMERO]
| Campo | Detalle |
|-------|---------|
| **ID del Cambio** | CHG-[YYYY]-[NNN] |
| **Fecha de Solicitud** | [DD/MM/YYYY] |
| **Solicitado por** | [Nombre] - [Empresa] |
| **Tipo de Cambio** | [ ] Estándar [ ] Normal [ ] Emergencia |
| **Categoría** | [ ] Red [ ] Seguridad [ ] Monitoreo [ ] Otro |
| **Prioridad** | [ ] Crítica [ ] Alta [ ] Media [ ] Baja |

### DESCRIPCIÓN DEL CAMBIO
> [Descripción detallada de qué se va a cambiar]

### JUSTIFICACIÓN
> [Por qué es necesario este cambio]

### ANÁLISIS DE IMPACTO
| Aspecto | Impacto | Detalle |
|---------|:-------:|---------|
| Disponibilidad del servicio | Alto/Medio/Bajo/Ninguno | |
| Usuarios afectados | [Número] | |
| Servicios afectados | [Lista] | |
| Riesgo de seguridad | Alto/Medio/Bajo/Ninguno | |
| Tiempo de implementación | [Horas/Minutos] | |
| Ventana de mantenimiento requerida | Sí/No | |

### PLAN DE IMPLEMENTACIÓN
| Paso | Acción | Responsable | Tiempo Est. | Verificación |
|:----:|--------|-------------|:-----------:|--------------|
| 1 | Backup de configuración actual | | | |
| 2 | [Acción específica] | | | |
| 3 | Verificar funcionalidad | | | |
| 4 | Documentar cambios | | | |

### PLAN DE ROLLBACK
| Paso | Acción | Responsable | Tiempo Est. |
|:----:|--------|-------------|:-----------:|
| 1 | Restaurar configuración backup | | |
| 2 | Verificar servicio restaurado | | |
| 3 | Notificar a stakeholders | | |

### APROBACIONES
| Rol | Nombre | Aprobación | Fecha |
|-----|--------|:----------:|-------|
| Líder Técnico (Proveedor) | | ✅/❌ | |
| Gerente de Operaciones | | ✅/❌ | |
| Contacto Técnico (Cliente) | | ✅/❌ | |
| CAB (si aplica) | | ✅/❌ | |

### POST-IMPLEMENTACIÓN
| Campo | Detalle |
|-------|---------|
| **Fecha de ejecución** | [DD/MM/YYYY HH:MM] |
| **Ejecutado por** | [Nombre] |
| **Resultado** | [ ] Exitoso [ ] Exitoso con observaciones [ ] Fallido (rollback) |
| **Verificación completada** | [ ] Sí [ ] No |
| **Documentación actualizada** | [ ] Sí [ ] No |
| **Observaciones** | |
```

---

### **Template 7: Informe de Avance de Implementación (Semanal)**

```markdown
# 📊 INFORME SEMANAL DE IMPLEMENTACIÓN
## Proyecto: [Código] - [Nombre del Cliente]
## Semana: [#] | Período: [DD/MM] al [DD/MM/YYYY]
## Estado General: 🟢 En Tiempo / 🟡 En Riesgo / 🔴 Atrasado

---

### RESUMEN EJECUTIVO
> [Resumen de 3-5 líneas sobre el avance de la semana]

### MÉTRICAS DE AVANCE
| Indicador | Planificado | Real | Desviación |
|-----------|:---:|:---:|:---:|
| % Avance General | % | % | |
| Tareas completadas esta semana | | | |
| Tareas planificadas para esta semana | | | |
| Tareas atrasadas acumuladas | | | |

### PROGRESO POR COMPONENTE
| Componente | Estado | % Avance | Inicio Plan. | Fin Plan. | Fin Estimado | Notas |
|-----------|:------:|:--------:|:------------:|:---------:|:------------:|-------|
| Segmentación de Red | 🟢/🟡/🔴 | % | | | | |
| Core Network | 🟢/🟡/🔴 | % | | | | |
| Seguridad Perimetral | 🟢/🟡/🔴 | % | | | | |
| VPN | 🟢/🟡/🔴 | % | | | | |
| Seguridad Interna | 🟢/🟡/🔴 | % | | | | |
| SIEM | 🟢/🟡/🔴 | % | | | | |
| Monitoreo | 🟢/🟡/🔴 | % | | | | |
| Wi-Fi | 🟢/🟡/🔴 | % | | | | |
| Pruebas | 🟢/🟡/🔴 | % | | | | |

### ACTIVIDADES COMPLETADAS ESTA SEMANA
| # | Actividad | Responsable | Fecha | Resultado |
|---|-----------|-------------|-------|-----------|
| 1 | | | | ✅ |
| 2 | | | | ✅ |

### ACTIVIDADES EN PROGRESO
| # | Actividad | Responsable | % Avance | Fecha Límite | Estado |
|---|-----------|-------------|:--------:|:------------:|:------:|
| 1 | | | % | | 🟢/🟡/🔴 |

### ACTIVIDADES PLANIFICADAS PRÓXIMA SEMANA
| # | Actividad | Responsable | Fecha Inicio | Fecha Fin | Prerequisitos |
|---|-----------|-------------|:------------:|:---------:|---------------|
| 1 | | | | | |

### RIESGOS Y PROBLEMAS
| # | Descripción | Tipo | Impacto | Probabilidad | Mitigación | Responsable | Estado |
|---|-------------|:----:|:-------:|:------------:|------------|-------------|:------:|
| 1 | | Riesgo/Problema | | | | | Abierto/Cerrado |

### BLOQUEOS
| # | Descripción | Bloqueado Desde | Impacto | Acción Requerida | Responsable |
|---|-------------|:---------------:|---------|------------------|-------------|
| 1 | | | | | |

### CAMBIOS EN EL PLAN
| # | Cambio | Motivo | Impacto en Cronograma | Aprobado por |
|---|--------|--------|-----------------------|--------------|
| 1 | | | | |

### DECISIONES PENDIENTES DEL CLIENTE
| # | Decisión | Solicitada | Fecha Límite | Impacto si se Retrasa |
|---|----------|:----------:|:------------:|----------------------|
| 1 | | | | |

### PRÓXIMA REUNIÓN
- **Fecha:** [DD/MM/YYYY]
- **Hora:** [HH:MM]
- **Temas a tratar:** [Lista]

---
**Elaborado por:** [Nombre] | Fecha: [DD/MM/YYYY]
```

---

## **3. Automatizaciones con n8n para la Fase 2**

### **Automatización 1: Gestión Automática de Ventanas de Mantenimiento**

```
📌 TRIGGER: Tarea de Asana con tag "Cambio con Impacto" 
movida a "Aprobado"

FLUJO EN n8n:

1. [Asana Trigger] → Tarea con tag "Cambio con Impacto" 
   cambia a estado "Aprobado"

2. [Function] → Extraer información del cambio:
   - Descripción del cambio
   - Fecha/hora de la ventana de mantenimiento
   - Servicios afectados
   - Tiempo estimado de downtime
   - Responsable de ejecución
   - Plan de rollback

3. [Google Calendar] → Crear evento de ventana de mantenimiento
   - Título: "🔧 MANT: [Descripción] - [Cliente]"
   - Duración: [Tiempo estimado + 30% buffer]
   - Descripción: Plan de implementación completo
   - Invitados: Equipo técnico + contacto cliente
   - Recordatorios: 24h antes, 2h antes, 30min antes

4. [Slack] → Notificar en #cliente-cambios:
   "🔧 VENTANA DE MANTENIMIENTO PROGRAMADA
    📅 Fecha: [Fecha]
    ⏰ Hora: [Hora inicio] - [Hora fin]
    🔄 Cambio: [Descripción]
    ⚠️ Servicios afectados: [Lista]
    ⏱️ Downtime estimado: [Tiempo]
    👤 Ejecutado por: [Nombre]
    📋 Ticket: [Link Asana]"

5. [Email/Gmail] → Enviar notificación formal al cliente:
   - Template de correo profesional con toda la info
   - Solicitar confirmación de recibido
   - CC: Gerente de Cuenta

6. [Asana] → Crear subtareas automáticas:
   - "Pre-cambio: Backup de configuración"
   - "Pre-cambio: Verificar plan de rollback"  
   - "Pre-cambio: Confirmar disponibilidad del equipo"
   - "Ejecución: Implementar cambio"
   - "Post-cambio: Verificar funcionalidad"
   - "Post-cambio: Actualizar documentación"
   - "Post-cambio: Notificar finalización"

7. [Schedule] → 24 horas antes del cambio:
   a. [Slack] → Recordatorio:
      "⏰ RECORDATORIO: Ventana de mantenimiento mañana
       [Toda la info del cambio]
       ✅ Checklist pre-cambio:
       - [ ] Backup realizado
       - [ ] Rollback verificado
       - [ ] Equipo confirmado"

8. [Schedule] → 30 minutos antes del cambio:
   a. [Slack] → Alerta:
      "🚦 INICIO DE VENTANA EN 30 MINUTOS
       @[responsable] confirmar listo para ejecutar"

9. [Webhook] → Al marcar "Post-cambio: Notificar finalización":
   a. [Slack] → Notificar resultado:
      "✅ VENTANA DE MANTENIMIENTO COMPLETADA
       Cambio: [Descripción]
       Resultado: [Exitoso/Con observaciones/Rollback]
       Hora inicio real: [HH:MM]
       Hora fin real: [HH:MM]
       📋 Detalles: [Link Asana]"
   b. [Email] → Notificar al cliente formalmente
   c. [Google Sheets] → Registrar en log de cambios
```

---

### **Automatización 2: Pipeline de Pruebas y Validación**

```
📌 TRIGGER: Sección "2.6 Migración" → Todas las tareas 
completadas

FLUJO EN n8n:

1. [Asana Trigger] → Última tarea de migración completada

2. [Asana] → Verificar que TODAS las tareas de la sección 
   de migración están en "Completada"

3. [IF] → Si todas completadas:

   a. [Asana] → Crear automáticamente suite de pruebas:
      
      Sección "Pruebas de Conectividad":
      - "Test: Ping entre VLANs" (asignar a Ing. Redes)
      - "Test: DNS interno y externo" (asignar a Ing. Redes)
      - "Test: Acceso a internet por VLAN" (asignar a Ing. Redes)
      - "Test: VPN Site-to-Site" (asignar a Ing. Redes)
      - "Test: VPN Remote Access" (asignar a Ing. Redes)
      
      Sección "Pruebas de Rendimiento":
      - "Test: Throughput LAN (iperf)" (asignar a Ing. Redes)
      - "Test: Latencia WAN" (asignar a Ing. Redes)
      - "Test: QoS VoIP" (asignar a Ing. Redes)
      
      Sección "Pruebas de Seguridad":
      - "Test: Validación reglas firewall" (asignar a Analista)
      - "Test: Escaneo vulnerabilidades" (asignar a Analista)
      - "Test: Pruebas de penetración" (asignar a Analista)
      - "Test: Verificación IDS/IPS" (asignar a Analista)
      - "Test: Verificación MFA" (asignar a Analista)
      
      Sección "Pruebas de Monitoreo":
      - "Test: Simulación host down" (asignar a Ing. Redes)
      - "Test: Simulación alerta seguridad" (asignar a Analista)
      - "Test: Verificación notificaciones" (asignar a Ing. Redes)
      
      Sección "Pruebas de Backup":
      - "Test: Restore de configuración" (asignar a Ing. Redes)

   b. [Asana] → Agregar Custom Fields a cada tarea:
      - Resultado: Pendiente/Aprobado/Fallido
      - Evidencia adjunta: Sí/No
      - Notas de ejecución: [Campo texto]

   c. [Slack] → Notificar en #equipo-interno:
      "🧪 SUITE DE PRUEBAS GENERADA AUTOMÁTICAMENTE
       Migración completada para [Cliente].
       [X] pruebas creadas en Asana.
       Fecha límite: [Fecha]
       📋 [Link al proyecto]
       
       @[Ing. Redes] @[Analista] por favor iniciar 
       ejecución de pruebas"

   d. [Google Sheets] → Crear hoja de tracking de pruebas

4. [IF] → Alguna tarea de migración NO completada:
   a. [Slack] → Alertar:
      "⚠️ No se puede iniciar fase de pruebas.
       Tareas de migración pendientes: [Lista]"
```

---

### **Automatización 3: Seguimiento de Hallazgos de Pruebas**

```
📌 TRIGGER: Tarea de prueba marcada con Custom Field 
"Resultado: Fallido"

FLUJO EN n8n:

1. [Asana Trigger] → Custom Field "Resultado" cambia 
   a "Fallido" en tarea de prueba

2. [Function] → Extraer información:
   - Nombre de la prueba
   - Categoría (Conectividad/Rendimiento/Seguridad/etc.)
   - Responsable
   - Descripción del fallo
   - Evidencia adjunta

3. [Asana] → Crear tarea de remediación:
   - Título: "🔧 REMEDIAR: [Nombre de prueba fallida]"
   - Sección: "Remediación"
   - Custom Fields:
     - Severidad: [Basada en categoría]
     - Origen: "Prueba [ID]"
     - Fecha límite: [Según severidad]
   - Descripción: Incluir detalles del fallo y evidencia
   - Asignada a: [Responsable según categoría]

4. [Asana] → Crear tarea de re-test:
   - Título: "🔄 RE-TEST: [Nombre de prueba]"
   - Dependencia: Tarea de remediación
   - Asignada a: [Mismo responsable de la prueba original]

5. [Slack] → Notificar en #equipo-interno:
   "❌ PRUEBA FALLIDA
    🧪 Prueba: [Nombre]
    📂 Categoría: [Categoría]
    📝 Descripción: [Detalle del fallo]
    👤 Asignado para remediar: [Nombre]
    ⏰ Fecha límite: [Fecha]
    📋 Tarea de remediación: [Link]"

6. [IF] → Si la categoría es "Seguridad" Y severidad "Crítica":
   a. [Slack] → Notificar al CISO y Gerente de Cuenta
   b. [Email] → Enviar alerta de vulnerabilidad crítica
   c. [Asana] → Cambiar prioridad a "Urgente"

7. [Google Sheets] → Registrar hallazgo en log de pruebas:
   - Fecha, Prueba, Resultado, Severidad, Responsable, 
     Estado remediación
```

---

### **Automatización 4: Dashboard de Progreso de Implementación en Tiempo Real**

```
📌 TRIGGER: Cron job cada 30 minutos

FLUJO EN n8n:

1. [Schedule Trigger] → Cada 30 minutos

2. [Asana] → Obtener todas las tareas de las secciones 
   2.1 a 2.8 del proyecto

3. [Function] → Calcular métricas por sección:
   
   Para cada sección (2.1 a 2.8):
   - Total de tareas
   - Completadas
   - En progreso
   - Atrasadas (fecha límite < hoy)
   - % de avance
   
   Cálculos adicionales:
   - % avance general del proyecto
   - Velocidad de ejecución (tareas/día)
   - Fecha estimada de finalización
   - Días de desviación vs plan
   - Índice de rendimiento (EV/PV)

4. [Google Sheets] → Actualizar hoja de métricas:
   | Fecha/Hora | Sección | Total | Completadas | 
   | En Progreso | Atrasadas | % Avance |

5. [Grafana] → Dashboard actualizado automáticamente 
   (conectado a Google Sheets vía plugin)
   
   Paneles sugeridos:
   - Gauge: % avance general
   - Bar chart: Avance por sección
   - Line chart: Tendencia de avance vs planificado
   - Table: Tareas atrasadas
   - Stat: Días para completar vs planificado
   - Heatmap: Carga por responsable

6. [IF] → Si hay tareas atrasadas > 2 días:
   a. [Slack] → Alerta diaria al Gerente de Proyecto:
      "📊 REPORTE DE IMPLEMENTACIÓN
       
       📈 Avance General: [X]%
       ✅ Completadas: [X]/[Total]
       🔄 En Progreso: [X]
       ⚠️ Atrasadas: [X]
       📅 Fecha estimada fin: [Fecha]
       📅 Fecha planificada fin: [Fecha]
       ⏱️ Desviación: [+/- X días]
       
       🔴 TAREAS ATRASADAS:
       1. [Tarea] - [Responsable] - [Días atraso]
       2. [Tarea] - [Responsable] - [Días atraso]"

7. [IF] → Si % avance < umbral esperado para la fecha:
   a. [Slack] → Alerta al Gerente de Cuenta:
      "🚨 PROYECTO EN RIESGO DE RETRASO
       Avance esperado: [X]%
       Avance real: [Y]%
       Acciones requeridas: [Sugerencias]"
```

---

### **Automatización 5: Backup Automático de Configuraciones Post-Cambio**

```
📌 TRIGGER: Tarea con tag "Cambio Implementado" completada 
en Asana

FLUJO EN n8n:

1. [Asana Trigger] → Tarea con tag "Cambio Implementado" 
   marcada como completada

2. [Function] → Extraer información:
   - Dispositivo(s) modificado(s)
   - Tipo de cambio
   - Responsable
   - ID del cambio

3. [SSH Node / HTTP Request] → Ejecutar backup de 
   configuración via Oxidized API:
   - Endpoint: POST /api/oxidized/node/[hostname]/backup
   - Para cada dispositivo modificado

4. [IF] → Backup exitoso:
   a. [Asana] → Agregar comentario en la tarea:
      "✅ Backup automático completado
       Fecha: [Timestamp]
       Dispositivos: [Lista]
       Referencia: [ID backup en Oxidized]"
   
   b. [Google Sheets] → Registrar en log de backups:
      | Fecha | Dispositivo | Motivo | ID Cambio | 
      | ID Backup | Estado |
   
   c. [Slack] → Confirmar en #equipo-interno:
      "💾 Backup post-cambio completado
       Cambio: CHG-[ID]
       Dispositivos: [Lista]"

5. [IF] → Backup fallido:
   a. [Slack] → ALERTA:
      "🚨 BACKUP POST-CAMBIO FALLIDO
       Cambio: CHG-[ID]
       Dispositivo: [Hostname]
       Error: [Mensaje de error]
       @[responsable] ejecutar backup manual INMEDIATAMENTE"
   
   b. [Asana] → Crear tarea urgente:
      "🚨 Backup manual requerido - [Dispositivo]"
      Prioridad: Crítica
      Fecha límite: Hoy

6. [Function] → Comparar configuración nueva vs anterior:
   - Si hay diferencias significativas, adjuntar diff 
     en la tarea de Asana

7. [BookStack API] → Actualizar wiki del cliente:
   - Agregar entrada en historial de cambios
   - Actualizar página de configuración del dispositivo
```

---

### **Automatización 6: Notificación Inteligente de Hitos de Implementación**

```
📌 TRIGGER: Tarea con Custom Field "Tipo: Hito" completada

FLUJO EN n8n:

1. [Asana Trigger] → Tarea con tipo "Hito" completada

2. [Function] → Identificar el hito:
   - Nombre del hito
   - Fase completada
   - Próximo hito
   - % de avance del proyecto

3. [Asana] → Obtener resumen de métricas del proyecto

4. [Slack] → Notificación celebratoria en #equipo-interno:
   "🎉 HITO ALCANZADO: [Nombre del Hito]
    
    📊 Progreso del proyecto: [X]%
    ✅ Fase completada: [Nombre de la fase]
    ➡️ Próximo hito: [Nombre]
    📅 Fecha objetivo próximo hito: [Fecha]
    
    ¡Excelente trabajo equipo! 💪"

5. [Slack] → Notificación profesional en #cliente-general:
   "📢 Actualización de Proyecto
    
    Nos complace informar que hemos completado exitosamente:
    ✅ [Nombre del Hito]
    
    Avance general: [X]%
    Próximo paso: [Descripción breve]
    
    Para más detalles, el informe completo será compartido 
    en nuestra próxima reunión de seguimiento."

6. [Email] → Enviar actualización al Sponsor del cliente:
   - Template profesional con logo de la empresa
   - Resumen del hito completado
   - Métricas de avance
   - Próximos pasos

7. [Google Sheets] → Registrar hito en timeline del proyecto

8. [IF] → Si el hito es "Implementación Completada" 
   (último hito de Fase 2):
   
   a. [Asana] → Crear tareas de cierre de Fase 2:
      - "Compilar documentación técnica final"
      - "Crear documento AS-BUILT"
      - "Capacitar equipo de operaciones"
      - "Reunión de aceptación con cliente"
      - "Obtener sign-off del cliente"
   
   b. [Slack] → Notificación especial:
      "🏆 FASE 2 COMPLETADA
       La implementación del proyecto [Cliente] 
       ha finalizado exitosamente.
       Iniciando proceso de aceptación y transición 
       a operación continua."
   
   c. [Google Calendar] → Programar reunión de aceptación
```

---

### **Automatización 7: Sistema de Reportería Semanal Automatizado**

```
📌 TRIGGER: Cron job cada viernes a las 14:00

FLUJO EN n8n:

1. [Schedule Trigger] → Viernes 14:00

2. [Asana] → Obtener todas las tareas del proyecto:
   - Completadas esta semana
   - En progreso
   - Atrasadas
   - Creadas esta semana

3. [Asana] → Obtener comentarios/actividad de la semana

4. [Google Sheets] → Obtener métricas de la semana anterior 
   (para comparación)

5. [Function] → Compilar informe:
   
   Sección 1: Resumen Ejecutivo
   - % avance semanal
   - Tendencia vs semana anterior
   - Estado general (🟢/🟡/🔴)
   
   Sección 2: Actividades Completadas
   - Lista de tareas completadas con responsable y fecha
   
   Sección 3: Actividades en Progreso
   - Lista con % de avance
   
   Sección 4: Tareas Atrasadas
   - Lista con días de retraso y motivo
   
   Sección 5: Bloqueos y Riesgos
   - Extraer de tareas con tag "Bloqueado" o "Riesgo"
   
   Sección 6: Plan Próxima Semana
   - Tareas planificadas para la próxima semana

6. [Google Docs] → Generar informe usando template:
   - Aplicar formato del Template 7 (Informe Semanal)
   - Insertar datos compilados
   - Guardar en carpeta del cliente

7. [Slack] → Compartir en #cliente-general:
   "📊 INFORME SEMANAL DE IMPLEMENTACIÓN
    Semana [#] | [Fecha inicio] - [Fecha fin]
    
    Estado: [🟢/🟡/🔴]
    Avance: [X]% (+[Y]% vs semana anterior)
    Completadas: [N] tareas
    Atrasadas: [N] tareas
    
    📄 Informe completo: [Link Google Docs]
    📋 Proyecto Asana: [Link]"

8. [Email] → Enviar informe al Gerente de TI del cliente:
   - Adjuntar PDF del informe
   - CC: Gerente de Cuenta

9. [Google Sheets] → Registrar métricas semanales 
   para tendencia histórica
```

---

### **Automatización 8: Validación de Prerequisites Pre-Implementación**

```
📌 TRIGGER: 48 horas antes de la fecha inicio de una 
tarea de implementación técnica

FLUJO EN n8n:

1. [Schedule Trigger] → Diario a las 8:00 AM

2. [Asana] → Buscar tareas de implementación con fecha 
   inicio en los próximos 2 días

3. [FOR EACH] → Para cada tarea encontrada:

   a. [Asana] → Verificar dependencias:
      - ¿Todas las tareas prerequisito están completadas?
      - ¿El backup pre-implementación está hecho?
      - ¿La ventana de mantenimiento está aprobada?

   b. [Function] → Verificar accesos:
      - Ping a equipos involucrados (vía n8n Execute Command)
      - Verificar VPN activa
      - Verificar credenciales válidas (test de login)

   c. [IF] → Todo OK:
      - [Slack] → Mensaje de confirmación:
        "✅ PRE-CHECK COMPLETADO para: [Tarea]
         📅 Fecha de ejecución: [Fecha]
         ✓ Dependencias completadas
         ✓ Accesos verificados
         ✓ Backup realizado
         ✓ Ventana aprobada
         
         LISTO PARA EJECUTAR ✅"

   d. [IF] → Hay problemas:
      - [Slack] → ALERTA:
        "⚠️ PRE-CHECK FALLIDO para: [Tarea]
         📅 Fecha de ejecución: [Fecha]
         
         ❌ Problemas detectados:
         - [Lista de problemas]
         
         ACCIÓN REQUERIDA antes de [Fecha/Hora]
         @[responsable]"
      
      - [Asana] → Agregar comentario en la tarea con detalles
      - [IF] → Si el problema es crítico:
        - [Email] → Notificar al Gerente de Proyecto
```

---

## **4. Herramientas Gratuitas Específicas para la Fase 2**

| **Categoría** | **Herramienta** | **Uso Específico en Fase 2** | **Tipo** |
|---------------|-----------------|------------------------------|----------|
| **Diagramas de Red** | Draw.io (diagrams.net) | Crear diagramas AS-IS y TO-BE, documentos AS-BUILT | Free |
| **Pruebas de Red** | iPerf3 | Medir throughput, latencia y jitter | Open Source |
| **Pruebas de Red** | MTR (My Traceroute) | Diagnóstico de ruta y latencia | Open Source |
| **Escaneo de Puertos** | Nmap | Verificar puertos abiertos/cerrados post-implementación | Open Source |
| **Escaneo Vulnerabilidades** | OpenVAS/Greenbone | Escaneos de vulnerabilidades post-implementación | Open Source |
| **Pentesting** | Metasploit Framework | Pruebas de penetración | Open Source |
| **Análisis de Tráfico** | Wireshark | Captura y análisis de paquetes durante pruebas | Open Source |
| **Análisis Wi-Fi** | Kismet | Auditoría de red inalámbrica | Open Source |
| **Backup de Configs** | Oxidized | Backup automático de configuraciones de red | Open Source |
| **IDS/IPS** | Suricata | Sistema de detección/prevención de intrusos | Open Source |
| **SIEM** | Wazuh | Correlación de eventos y compliance | Open Source |
| **Monitoreo** | Zabbix | Monitoreo de infraestructura | Open Source |
| **Uptime** | Uptime Kuma | Monitoreo de disponibilidad de servicios | Open Source |
| **Dashboards** | Grafana | Visualización de métricas | Open Source |
| **Wiki Técnica** | BookStack | Documentación técnica del cliente | Open Source |
| **Gestión Contraseñas** | Vaultwarden | Almacenamiento seguro de credenciales | Open Source |
| **Generador de Informes** | Pandoc | Convertir markdown a PDF/DOCX profesional | Open Source |
| **Control de Versiones** | Git (Gitea) | Versionado de configuraciones y playbooks | Open Source |

---

## **5. Custom Fields Recomendados en Asana para la Fase 2**

| **Campo** | **Tipo** | **Opciones** | **Uso** |
|-----------|----------|--------------|---------|
| Componente | Dropdown | Red / Seguridad Perimetral / Seguridad Interna / Monitoreo / VPN / Wi-Fi | Clasificación técnica |
| Estado Técnico | Dropdown | Pendiente / En Configuración / En Pruebas / Aprobado / Fallido | Tracking de implementación |
| Ventana de Mantenimiento | Dropdown | Requerida / Programada / No Necesaria | Control de cambios |
| Impacto en Servicio | Dropdown | Sin Impacto / Impacto Parcial / Downtime Total | Evaluación de riesgo |
| Rollback Documentado | Dropdown | Sí / No | Verificación de seguridad |
| Backup Pre-Cambio | Dropdown | Realizado / Pendiente / No Aplica | Control de respaldos |
| Resultado de Prueba | Dropdown | Pendiente / Aprobado / Fallido / No Aplica | Tracking de pruebas |
| Evidencia Adjunta | Dropdown | Sí / No | Documentación de pruebas |
| Tipo de Tarea | Dropdown | Configuración / Migración / Prueba / Documentación / Hito | Categorización |
| Requiere Aprobación Cliente | Dropdown | Sí / No | Flujo de aprobación |

---

## **6. Criterios de Salida de la Fase 2 (Definition of Done)**

```
✅ Toda la infraestructura de red configurada según diseño TO-BE
✅ Seguridad perimetral implementada y validada
✅ Seguridad interna implementada (MFA, NAC, SIEM, etc.)
✅ VPNs configuradas y probadas (S2S y RA)
✅ Sistema de monitoreo operativo con dashboards publicados
✅ Alertas configuradas y validadas end-to-end
✅ Playbooks de respuesta documentados
✅ Migración de todos los servicios completada
✅ Pruebas de conectividad aprobadas al 100%
✅ Pruebas de rendimiento dentro de parámetros aceptables
✅ Pruebas de seguridad completadas (pentesting + escaneo vuln.)
✅ Cero vulnerabilidades críticas o altas abiertas
✅ Pruebas de failover exitosas
✅ Pruebas de backup/restore exitosas
✅ Documento AS-BUILT completo y actualizado
✅ Wiki del cliente actualizada con toda la documentación
✅ Equipo de operaciones capacitado
✅ Backups post-implementación almacenados
✅ Sign-off del cliente obtenido
✅ Retrospectiva de implementación realizada
✅ Handoff formal a equipo de operaciones completado
```

---

Cuando estés listo, avanzamos a la **Fase 3: Operación y Monitoreo Continuo**, que es donde el proveedor demuestra su valor día a día con el cliente. Incluirá templates para informes de SLA, gestión de incidentes, reportería ejecutiva y automatizaciones de monitoreo proactivo.