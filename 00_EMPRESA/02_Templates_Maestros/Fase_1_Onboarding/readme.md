# **FASE 1: ONBOARDING Y ALINEACIÓN CON EL CLIENTE**

## **Objetivo General**
Establecer las bases del proyecto, entender al cliente en profundidad, configurar los accesos necesarios y garantizar que ambas partes estén completamente alineadas antes de iniciar cualquier trabajo técnico.

---

## **1. Desglose Detallado de Tareas**

### **Sección 1.1: Recepción del Proyecto**

| **Tarea**                                  | **Descripción Detallada**                                                                                             | **Responsable**       | **Entregable**                                   | **Duración** |
|-----------                                 |--------------------------                                                                                             |-----------------      |----------------                                  |-------|
| 1.1.1 Recibir documentación del cliente    | Recopilar contrato firmado, RFP, diagramas de red existentes, inventario de activos, políticas de seguridad vigentes  | Gerente de Cuenta     | Carpeta de documentación organizada              | 1 día |
| 1.1.2 Verificar completitud de documentos  | Revisar que toda la documentación necesaria esté completa y sea legible                                               | Gerente de Proyecto   | Checklist de documentos verificados              | 1 día |
| 1.1.3 Crear carpeta del cliente            | Organizar toda la documentación en Google Drive/SharePoint con estructura estandarizada                               | Asistente de Proyecto | Carpeta estructurada con permisos configurados   | 1 día |
| 1.1.4 Registrar cliente en CRM             | Documentar datos del cliente, contactos clave, información de facturación                                             | Gerente de Cuenta     | Registro en CRM actualizado                      | 1 día |
| 1.1.5 Asignar código de proyecto           | Generar un código único para tracking interno (ej: OUT-REDES-2024-001)                                                | Gerente de Proyecto   | Código asignado y comunicado                     | 1 día |

---

### **Sección 1.2: Análisis y Entendimiento del Cliente**

| **Tarea**                                           | **Descripción Detallada**                                                                                 | **Responsable**                   | **Entregable**                    | **Duración** |
|-----------                                          |--------------------------                                                                                 |-----------------                  |----------------                   |--------------|
| 1.2.1 Realizar reunión de descubrimiento            | Sesión profunda con el cliente para entender su negocio, procesos críticos, pain points y expectativas    | Gerente de Cuenta + Líder Técnico | Minuta de reunión + grabación     | 2 horas   |
| 1.2.2 Mapear stakeholders del cliente               | Identificar todos los contactos clave del cliente (técnicos, gerenciales, ejecutivos) y sus roles         | Gerente de Cuenta                 | Matriz de stakeholders            | 1 día     |
| 1.2.3 Documentar arquitectura actual                | Analizar y documentar la infraestructura de redes y seguridad existente del cliente                       | Arquitecto de Redes               | Diagrama de arquitectura AS-IS    | 3 días    |
| 1.2.4 Realizar assessment de seguridad              | Evaluación inicial del estado de seguridad del cliente (vulnerabilidades, compliance, gaps)               | Analista de Seguridad             | Informe de assessment inicial     | 5 días    |
| 1.2.5 Identificar sistemas críticos                 | Clasificar los sistemas del cliente por nivel de criticidad (Tier 1, 2, 3)                                | Líder Técnico                     | Matriz de criticidad de sistemas  | 2 días    |
| 1.2.6 Documentar procesos actuales del cliente      | Entender cómo el cliente gestiona actualmente sus redes y seguridad (procesos, herramientas, equipo)      | Gerente de Proyecto               | Documento de procesos AS-IS       | 3 días    |
| 1.2.7 Realizar análisis de brechas (Gap Analysis)   | Comparar el estado actual con el estado deseado/requisitos del contrato                                   | Líder Técnico + CISO              | Informe de Gap Analysis           | 3 días    |

---

### **Sección 1.3: Definición del Marco de Trabajo**

| **Tarea**                                     | **Descripción Detallada**                                                                  | **Responsable**                   | **Entregable**                       | **Duración** |
|-----------                                    |--------------------------                                                                  |-----------------                  |----------------                      |--------------|
| 1.3.1 Definir matriz RACI                     | Establecer quién es Responsable, Aprobador, Consultado e Informado para cada actividad     | Gerente de Proyecto               | Matriz RACI firmada por ambas partes | 2 días |
| 1.3.2 Definir canales de comunicación         | Establecer herramientas y protocolos de comunicación (Slack, email, teléfono, reuniones)   | Gerente de Proyecto               | Plan de comunicación                 | 1 día  |
| 1.3.3 Configurar SLA operativos               | Traducir los SLA contractuales en métricas operativas medibles                             | Gerente de Cuenta + Líder Técnico | Documento de SLA operativo           | 3 días |
| 1.3.4 Definir procedimiento de escalamiento   | Crear cadena de escalamiento para incidentes según severidad                               | Gerente de Operaciones            | Matriz de escalamiento               | 2 días |
| 1.3.5 Establecer calendario de reuniones      | Definir reuniones recurrentes (diarias, semanales, mensuales) con el cliente               | Gerente de Proyecto               | Calendario compartido configurado    | 1 día  |
| 1.3.6 Definir métricas y reporteo             | Acordar qué métricas se reportarán, con qué frecuencia y en qué formato                    | Gerente de Cuenta                 | Plantilla de reporteo aprobada       | 2 días |
| 1.3.7 Crear plan de gestión de cambios        | Definir cómo se gestionarán los cambios en la infraestructura (Change Management)          | Líder Técnico                     | Procedimiento de gestión de cambios  | 2 días |

---

### **Sección 1.4: Configuración de Herramientas y Accesos**

| **Tarea**                                  | **Descripción Detallada**                                                                           | **Responsable**             | **Entregable**                       | **Duración** |
|-----------                                 |--------------------------                                                                           |-----------------            |----------------                      |--------------|
| 1.4.1 Configurar proyecto en Asana         | Crear el proyecto con todas las secciones, custom fields, reglas y plantillas                       | Gerente de Proyecto         | Proyecto Asana configurado           | 1 día  |
| 1.4.2 Configurar canal de Slack            | Crear canales compartidos con el cliente (#cliente-general, #cliente-incidentes, #cliente-cambios)  | Gerente de Proyecto         | Canales Slack creados y configurados | 1 día  |
| 1.4.3 Solicitar accesos a infraestructura  | Pedir credenciales VPN, SSH, consolas de administración, SIEM, etc.                                 | Líder Técnico               | Accesos verificados y documentados   | 3 días |
| 1.4.4 Configurar herramientas de monitoreo | Implementar o conectarse a las herramientas de monitoreo (Zabbix, Grafana, etc.)                    | Ingeniero de Redes          | Dashboard de monitoreo operativo     | 4 días |
| 1.4.5 Configurar sistema de tickets        | Implementar sistema de gestión de incidencias (osTicket, Zammad o similar gratuito)                 | Administrador de Sistemas   | Sistema de tickets operativo         | 2 días |
| 1.4.6 Realizar pruebas de conectividad     | Verificar que todos los accesos remotos funcionan correctamente                                     | Ingeniero de Redes          | Informe de pruebas de conectividad   | 1 día  |
| 1.4.7 Configurar documentación en wiki     | Crear espacio en wiki (Notion, BookStack o similar) para documentación técnica del cliente          | Administrador de Sistemas   | Wiki del cliente configurada         | 1 día  |

---

### **Sección 1.5: Transición y Arranque**

| **Tarea**                                  | **Descripción Detallada**                                                                           | **Responsable**    | **Entregable**                                      | **Duración** |
|-----------                                 |--------------------------                                                                           |-----------------   |----------------                                     |--------------|
| 1.5.1 Realizar backup de configuraciones   | Hacer respaldo completo de todas las configuraciones actuales del cliente                           | Ingeniero de Redes | Backups verificados y almacenados                   | 2 días |
| 1.5.2 Capacitar al equipo del cliente      | Entrenar al personal del cliente sobre cómo reportar incidencias, solicitar cambios y comunicarse   | Líder Técnico      | Material de capacitación + registro de asistencia   | 2 días |
| 1.5.3 Capacitar al equipo interno          | Briefing técnico al equipo del proveedor sobre la infraestructura del cliente                       | Líder Técnico      | Registro de capacitación interna                    | 2 días |
| 1.5.4 Realizar reunión de kickoff formal   | Presentación formal al cliente del equipo, plan de trabajo, SLA y canales de comunicación           | Gerente de Cuenta  | Presentación de kickoff + minuta firmada            | 1 día |
| 1.5.5 Obtener aprobación formal de inicio  | Firma del acta de inicio del servicio por ambas partes                                              | Gerente de Cuenta  | Acta de inicio firmada                              | 1 día |
| 1.5.6 Iniciar período de estabilización    | Período de 2-4 semanas donde se monitorea de cerca para detectar problemas tempranos                | Equipo Completo    | Informe de estabilización                           | 14-28 días |

---

## **2. Templates Detallados para la Fase 1**

### **Template 1: Checklist de Documentación del Cliente**

```markdown
# 📋 CHECKLIST DE DOCUMENTACIÓN DEL CLIENTE
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY]
## Responsable: [Nombre]

---

### DOCUMENTACIÓN CONTRACTUAL
- [ ] Contrato firmado
- [ ] Anexos técnicos
- [ ] SLA acordados
- [ ] NDA (Acuerdo de confidencialidad)
- [ ] Términos y condiciones
- [ ] Acuerdo de nivel de servicio (OLA interno)

### DOCUMENTACIÓN TÉCNICA
- [ ] Diagrama de red actual (topología)
- [ ] Diagrama de arquitectura de seguridad
- [ ] Inventario de equipos de red (routers, switches, APs)
- [ ] Inventario de equipos de seguridad (firewalls, IDS/IPS, WAF)
- [ ] Lista de direcciones IP y subredes
- [ ] Configuraciones de VLAN
- [ ] Políticas de firewall actuales
- [ ] Configuración de VPN
- [ ] Licencias de software vigentes
- [ ] Certificados SSL/TLS
- [ ] Documentación de Wi-Fi (SSIDs, seguridad, cobertura)

### DOCUMENTACIÓN DE SEGURIDAD
- [ ] Política de seguridad de la información
- [ ] Plan de respuesta a incidentes
- [ ] Últimas auditorías de seguridad
- [ ] Reportes de pentesting previos
- [ ] Matriz de riesgos vigente
- [ ] Plan de continuidad de negocio (BCP)
- [ ] Plan de recuperación ante desastres (DRP)
- [ ] Compliance requerido (ISO 27001, PCI-DSS, HIPAA, etc.)

### DOCUMENTACIÓN OPERATIVA
- [ ] Contactos clave del cliente (técnicos y gerenciales)
- [ ] Horarios de operación
- [ ] Ventanas de mantenimiento autorizadas
- [ ] Procedimientos de cambio existentes
- [ ] Credenciales de acceso (entregadas de forma segura)
- [ ] Proveedores de telecomunicaciones (ISP, enlaces)
- [ ] Contratos con terceros relacionados

### OBSERVACIONES
> [Notas adicionales sobre documentación faltante o incompleta]

### ESTADO
- Documentos recibidos: __/__ 
- Documentos pendientes: __/__
- Fecha estimada de completitud: [DD/MM/YYYY]

### FIRMAS
- Proveedor: _________________ Fecha: _________
- Cliente: ___________________ Fecha: _________
```

---

### **Template 2: Acta de Reunión de Descubrimiento**

```markdown
# 🔍 ACTA DE REUNIÓN DE DESCUBRIMIENTO
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY] | Hora: [HH:MM] - [HH:MM]
## Ubicación/Plataforma: [Presencial/Zoom/Teams]

---

### ASISTENTES
| Nombre | Empresa | Cargo | Email | Teléfono |
|--------|---------|-------|-------|----------|
|        |         |       |       |          |

---

### 1. INFORMACIÓN GENERAL DEL CLIENTE
- **Industria/Sector:** 
- **Número de empleados:**
- **Sedes/Ubicaciones:**
- **Horario de operación:**
- **Sistemas críticos de negocio:**

### 2. ESTADO ACTUAL DE REDES
- **Tipo de red (LAN/WAN/SD-WAN):**
- **Proveedor de internet (ISP):**
- **Ancho de banda contratado:**
- **Equipos principales (marca/modelo):**
- **Número de usuarios:**
- **Número de dispositivos:**
- **Problemas recurrentes:**

### 3. ESTADO ACTUAL DE SEGURIDAD
- **Firewalls implementados:**
- **Antivirus/EDR:**
- **SIEM:**
- **Certificaciones de seguridad:**
- **Último incidente de seguridad:**
- **Nivel de madurez de seguridad (1-5):**

### 4. EXPECTATIVAS DEL CLIENTE
- **¿Qué espera lograr con el outsourcing?**
- **¿Cuáles son sus principales preocupaciones?**
- **¿Qué ha funcionado bien con proveedores anteriores?**
- **¿Qué NO ha funcionado con proveedores anteriores?**
- **¿Cuál es su presupuesto mensual esperado?**

### 5. PAIN POINTS IDENTIFICADOS
| # | Problema | Impacto en el Negocio | Prioridad |
|---|----------|-----------------------|-----------|
| 1 |          |                       |           |
| 2 |          |                       |           |

### 6. REQUISITOS ESPECIALES
- **Compliance/Normativas:**
- **Restricciones de acceso:**
- **Ventanas de mantenimiento:**
- **Requisitos de idioma:**
- **Zonas horarias:**

### 7. PRÓXIMOS PASOS
| # | Acción | Responsable | Fecha Límite |
|---|--------|-------------|--------------|
| 1 |        |             |              |

### 8. OBSERVACIONES ADICIONALES
> [Notas relevantes]

---
**Minuta elaborada por:** [Nombre]
**Fecha de envío:** [DD/MM/YYYY]
**Aprobada por cliente:** [ ] Sí [ ] No
```

---

### **Template 3: Matriz de Stakeholders**

```markdown
# 👥 MATRIZ DE STAKEHOLDERS
## Proyecto: [Código] - [Nombre del Cliente]

---

### STAKEHOLDERS DEL CLIENTE
| Nombre | Cargo | Rol en Proyecto | Nivel de Influencia | Nivel de Interés | Estrategia de Comunicación       | Email  | Teléfono | Canal Preferido |
|--------|-------|-----------------|--------------------:|------------------:|---------------------------      |------- |----------|-----------------|
|        |       | Sponsor         | Alto                | Alto              | Informes ejecutivos mensuales   |        |          | Email           |
|        |       | Contacto Técnico| Medio               | Alto              | Reuniones semanales             |        |          | Slack           |
|        |       | Usuario Final   | Bajo                | Medio             | Notificaciones por email        |        |          | Email           |

### STAKEHOLDERS INTERNOS (PROVEEDOR)
| Nombre | Cargo                 | Rol en Proyecto       | Responsabilidades Clave           | Email  | Teléfono |
|--------|-------                |-----------------      |------------------------           |------- |----------|
|        | Gerente de Cuenta     | Relación con cliente  | Comunicación ejecutiva, SLA       |        |          |
|        | Líder Técnico         | Dirección técnica     | Arquitectura, decisiones técnicas |        |          |
|        | Ingeniero de Redes    | Operación             | Configuración, monitoreo          |        |          |
|        | Analista de Seguridad | Seguridad             | Monitoreo, incidentes             |        |          |

### MAPA DE INFLUENCIA/INTERÉS
```
         ALTO INTERÉS
              |
    MANTENER  |  GESTIONAR
   SATISFECHO | DE CERCA
              |
BAJA ---------|--------- ALTA
INFLUENCIA    |      INFLUENCIA
              |
   MONITOREAR |  MANTENER
              |  INFORMADO
              |
         BAJO INTERÉS
```

### PROTOCOLOS DE COMUNICACIÓN POR STAKEHOLDER
| Stakeholder        | Tipo de Comunicación  | Frecuencia   | Formato      | Canal  |
|-------------       |---------------------  |------------  |---------     |------- |
| Sponsor            | Informe ejecutivo     | Mensual      | PDF/PPT      | Email  |
| Contacto Técnico   | Reunión operativa     | Semanal      | Videollamada | Zoom   |
| Equipo TI          | Stand-up              | Diario       | Chat         | Slack  |
```

---

### **Template 4: Matriz RACI**

```markdown
# 📊 MATRIZ RACI
## Proyecto: [Código] - [Nombre del Cliente]
## R = Responsable | A = Aprobador | C = Consultado | I = Informado

---

| Actividad | Gerente Cuenta | Líder Técnico | Ing. Redes | Analista Seg. | Contacto Cliente | Sponsor Cliente |
|-----------|:-:|:-:|:-:|:-:|:-:|:-:|
| **GESTIÓN DEL SERVICIO** |
| Informes de SLA                | R | C | I | I | I | A |
| Reuniones semanales            | R | R | I | I | R | I |
| Reuniones mensuales ejecutivas | R | C | I | I | C | A |
| Facturación                    | R | I | - | - | I | A |
| **GESTIÓN DE INCIDENTES** |
| Detección de incidentes        | I | I | R | R | I | - |
| Clasificación y priorización   | I | R | C | C | I | - |
| Resolución Nivel 1             | I | I | R | R | I | - |
| Resolución Nivel 2             | I | R | R | R | I | - |
| Escalamiento Nivel 3           | R | A | C | C | I | I |
| Comunicación al cliente        | R | C | I | I | I | I |
| Post-mortem                    | I | R | C | C | C | I |
| **GESTIÓN DE CAMBIOS** |
| Solicitud de cambio            | I | C | C | C | R | - |
| Evaluación de impacto          | I | R | C | C | I | - |
| Aprobación de cambio           | I | A | I | I | A | I |
| Implementación                 | I | A | R | R | I | I |
| Validación post-cambio         | I | R | R | R | C | I |
| **SEGURIDAD** |
| Monitoreo de amenazas          | I | I | I | R | I | - |
| Escaneos de vulnerabilidades   | I | A | I | R | I | I |
| Respuesta a incidentes de seg. | R | A | C | R | I | I |
| Auditorías de seguridad        | I | C | I | R | C | I |
| Actualización de políticas     | I | A | C | R | C | A |
| **MANTENIMIENTO** |
| Backups de configuración       | I | I | R | I | I | - |
| Aplicación de parches          | I | A | R | C | I | I |
| Mantenimiento preventivo       | I | A | R | C | I | I |
| Actualización de firmware      | I | A | R | C | A | I |

---
**Aprobado por Proveedor:** _____________ Fecha: _________
**Aprobado por Cliente:** _______________ Fecha: _________
```

---

### **Template 5: Plan de Comunicación**

```markdown
# 📞 PLAN DE COMUNICACIÓN
## Proyecto: [Código] - [Nombre del Cliente]

---

### CANALES DE COMUNICACIÓN
| Canal                       | Uso                                              | Participantes                                 | Horario            |
|-------                      |-----                                             |---------------                                |---------           |
| Slack #cliente-general      | Comunicación diaria, consultas rápidas           | Equipo proveedor + contacto técnico cliente   | Lun-Vie 8:00-18:00 |
| Slack #cliente-incidentes   | Reporte y seguimiento de incidentes              | Equipo proveedor + equipo TI cliente          | 24/7               |
| Slack #cliente-cambios      | Solicitudes y aprobaciones de cambios            | Líder técnico + contacto técnico cliente      | Lun-Vie 8:00-18:00 |
| Email                       | Comunicaciones formales, informes, aprobaciones  | Todos los stakeholders                        | 24/7               |
| Zoom/Meet                   | Reuniones programadas | Según agenda             | Según agenda                                  |
| Teléfono                    | Emergencias y escalamientos críticos             | Gerente de cuenta + sponsor cliente           | 24/7               |
| Sistema de Tickets          | Gestión formal de incidentes y solicitudes       | Equipo proveedor + equipo TI cliente          | 24/7               |

### REUNIONES PROGRAMADAS
| Reunión                  | Frecuencia   | Día/Hora                          | Duración  | Participantes                              | Agenda                                                 |
|---------                 |------------  |----------                         |---------- |---------------                             |--------                                                |
| Stand-up operativo       | Diaria       | Lun-Vie 9:00 AM                   | 15 min    | Equipo técnico proveedor                   | Estado de incidentes, tareas del día                   |
| Reunión operativa        | Semanal      | Martes 10:00 AM                   | 1 hora    | Líder técnico + contacto técnico cliente   | Revisión de incidentes, cambios pendientes, métricas   |
| Reunión de seguimiento   | Quincenal    | Jueves 11:00 AM                   | 1 hora    | Gerente cuenta + gerente TI cliente        | Avance del proyecto, riesgos, próximos pasos           |
| Comité ejecutivo         | Mensual      | Primer viernes del mes 10:00 AM   | 1.5 horas | Gerente cuenta + sponsor cliente           | Informe de SLA, satisfacción, mejoras propuestas       |
| Revisión trimestral      | Trimestral   | Según agenda                      | 2 horas   | Todos los stakeholders                     | Evaluación general, roadmap, optimizaciones            |

### INFORMES
| Informe                           | Frecuencia   | Responsable           | Destinatarios         | Formato   | Canal de Entrega            |
|---------                          |------------  |-------------          |---------------        |---------  |------------------           |
| Reporte diario de operación       | Diario       | Ingeniero de Redes    | Contacto técnico      | Dashboard | Slack                       |  
| Informe semanal de incidentes     | Semanal      | Líder Técnico         | Gerente TI cliente    | PDF       | Email                       |
| Informe mensual de SLA            | Mensual      | Gerente de Cuenta     | Sponsor + Gerente TI  | PDF/PPT   | Email + Reunión             |
| Informe de seguridad              | Mensual      | Analista de Seguridad | CISO cliente          | PDF       | Email                       |
| Reporte ejecutivo trimestral      | Trimestral   | Gerente de Cuenta     | C-Level cliente       | PPT       | Reunión presencial/virtual  |   

### PROTOCOLOS DE ESCALAMIENTO
| Nivel | Tiempo de Respuesta | Contacto Proveedor | Contacto Cliente | Canal |
|-------|--------------------|--------------------|------------------|-------|
| Nivel 1 (Bajo) | 8 horas | Ingeniero de Redes | Help Desk cliente | Ticket |
| Nivel 2 (Medio) | 4 horas | Líder Técnico | Contacto técnico | Slack + Ticket |
| Nivel 3 (Alto) | 1 hora | Gerente de Operaciones | Gerente TI | Teléfono + Email |
| Nivel 4 (Crítico) | 15 minutos | Gerente de Cuenta + Director | Sponsor + CTO/CIO | Teléfono + War Room |

---
**Aprobado por Proveedor:** _____________ Fecha: _________
**Aprobado por Cliente:** _______________ Fecha: _________
```

---

### **Template 6: Informe de Assessment Inicial de Seguridad**

```markdown
# 🔒 INFORME DE ASSESSMENT INICIAL DE SEGURIDAD
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY]
## Clasificación: CONFIDENCIAL

---

### RESUMEN EJECUTIVO
> [Resumen de 2-3 párrafos sobre el estado general de seguridad del cliente]

### ALCANCE DEL ASSESSMENT
- **Redes evaluadas:** [LAN, WAN, Wi-Fi, DMZ, etc.]
- **Equipos evaluados:** [Firewalls, routers, switches, etc.]
- **Herramientas utilizadas:** [Nmap, OpenVAS, Wireshark, etc.]
- **Período de evaluación:** [Fecha inicio - Fecha fin]

### HALLAZGOS POR CATEGORÍA

#### 1. PERÍMETRO DE RED
| # | Hallazgo | Severidad | Riesgo | Recomendación | Prioridad |
|---|----------|-----------|--------|---------------|-----------|
| 1 |          | Crítica   |        |               | Inmediata |
| 2 |          | Alta      |        |               | 30 días   |

#### 2. RED INTERNA
| # | Hallazgo | Severidad | Riesgo | Recomendación | Prioridad |
|---|----------|-----------|--------|---------------|-----------|

#### 3. SEGURIDAD INALÁMBRICA
| # | Hallazgo | Severidad | Riesgo | Recomendación | Prioridad |
|---|----------|-----------|--------|---------------|-----------|

#### 4. GESTIÓN DE ACCESOS
| # | Hallazgo | Severidad | Riesgo | Recomendación | Prioridad |
|---|----------|-----------|--------|---------------|-----------|

#### 5. POLÍTICAS Y PROCEDIMIENTOS
| # | Hallazgo | Severidad | Riesgo | Recomendación | Prioridad |
|---|----------|-----------|--------|---------------|-----------|

### RESUMEN DE HALLAZGOS
| Severidad | Cantidad | Porcentaje |
|-----------|----------|------------|
| Crítica   |          |            |
| Alta      |          |            |
| Media     |          |            |
| Baja      |          |            |
| Info      |          |            |
| **Total** |          | **100%**   |

### NIVEL DE MADUREZ DE SEGURIDAD
| Dominio | Nivel Actual (1-5) | Nivel Objetivo | Gap |
|---------|:-:|:-:|:-:|
| Gestión de activos | | | |
| Control de acceso | | | |
| Seguridad perimetral | | | |
| Monitoreo y detección | | | |
| Respuesta a incidentes | | | |
| Gestión de vulnerabilidades | | | |
| Continuidad de negocio | | | |
| Compliance | | | |

### PLAN DE REMEDIACIÓN SUGERIDO
| Fase | Acciones | Plazo | Esfuerzo Estimado |
|------|----------|-------|-------------------|
| Inmediata (0-30 días) | | | |
| Corto plazo (1-3 meses) | | | |
| Mediano plazo (3-6 meses) | | | |
| Largo plazo (6-12 meses) | | | |

### CONCLUSIONES Y RECOMENDACIONES
> [Conclusiones finales y recomendaciones estratégicas]

---
**Elaborado por:** [Nombre] | [Cargo]
**Revisado por:** [Nombre] | [Cargo]
**Clasificación:** CONFIDENCIAL
```

---

### **Template 7: Acta de Kickoff Formal**

```markdown
# 🚀 ACTA DE KICKOFF - INICIO FORMAL DEL SERVICIO
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY] | Hora: [HH:MM]
## Ubicación: [Presencial/Virtual]

---

### ASISTENTES
| Nombre | Empresa | Cargo | Firma |
|--------|---------|-------|-------|
|        | Proveedor |     |       |
|        | Cliente   |     |       |

### 1. PRESENTACIÓN DEL EQUIPO
**Equipo Proveedor:**
- Gerente de Cuenta: [Nombre] - [Contacto]
- Líder Técnico: [Nombre] - [Contacto]
- Ingeniero de Redes: [Nombre] - [Contacto]
- Analista de Seguridad: [Nombre] - [Contacto]

**Equipo Cliente:**
- Sponsor: [Nombre] - [Contacto]
- Contacto Técnico: [Nombre] - [Contacto]
- Administrador de Red: [Nombre] - [Contacto]

### 2. ALCANCE DEL SERVICIO
**Servicios incluidos:**
- [ ] Gestión de firewalls
- [ ] Monitoreo de redes 24/7
- [ ] Gestión de VPN
- [ ] Monitoreo de seguridad (SOC)
- [ ] Gestión de parches
- [ ] Soporte técnico Nivel 1/2/3
- [ ] Respuesta a incidentes
- [ ] [Otros]

**Servicios excluidos:**
- [ ] [Listar explícitamente]

### 3. SLA COMPROMETIDOS
| Métrica | Objetivo | Medición | Penalización |
|---------|----------|----------|--------------|
| Disponibilidad de red | 99.9% | Mensual | |
| Tiempo de respuesta (Crítico) | 15 min | Por incidente | |
| Tiempo de respuesta (Alto) | 1 hora | Por incidente | |
| Tiempo de resolución (Crítico) | 4 horas | Por incidente | |
| Tiempo de resolución (Alto) | 8 horas | Por incidente | |

### 4. CANALES DE COMUNICACIÓN
[Resumen del Plan de Comunicación]

### 5. PRÓXIMOS PASOS
| # | Acción | Responsable | Fecha |
|---|--------|-------------|-------|
| 1 | Inicio de período de estabilización | Equipo proveedor | [Fecha] |
| 2 | Primera reunión operativa semanal | Ambos | [Fecha] |
| 3 | Primer informe mensual | Gerente de Cuenta | [Fecha] |

### 6. ACUERDOS
> [Lista de acuerdos tomados en la reunión]

### 7. FECHA OFICIAL DE INICIO DEL SERVICIO
**Fecha: [DD/MM/YYYY]**

---
### FIRMAS DE CONFORMIDAD
| Proveedor | Cliente |
|-----------|---------|
| Nombre: _____________ | Nombre: _____________ |
| Cargo: ______________ | Cargo: ______________ |
| Firma: _______________ | Firma: _______________ |
| Fecha: _______________ | Fecha: _______________ |
```

---

### **Template 8: Informe de Gap Analysis**

```markdown
# 📊 INFORME DE ANÁLISIS DE BRECHAS (GAP ANALYSIS)
## Proyecto: [Código] - [Nombre del Cliente]
## Fecha: [DD/MM/YYYY]

---

### RESUMEN EJECUTIVO
> [Resumen del análisis]

### METODOLOGÍA
> [Describir cómo se realizó el análisis]

### ANÁLISIS POR ÁREA

#### REDES
| Requisito/Estándar | Estado Actual | Estado Deseado | Brecha | Esfuerzo | Prioridad | Plan de Acción |
|---------------------|:---:|:---:|:---:|:---:|:---:|----------------|
| Redundancia de enlaces | No | Sí | Alta | Medio | Alta | Implementar enlace secundario |
| QoS configurado | Parcial | Sí | Media | Bajo | Media | Completar configuración |
| Segmentación de red | No | Sí | Alta | Alto | Crítica | Diseñar e implementar VLANs |

#### SEGURIDAD
| Requisito/Estándar | Estado Actual | Estado Deseado | Brecha | Esfuerzo | Prioridad | Plan de Acción |
|---------------------|:---:|:---:|:---:|:---:|:---:|----------------|
| Firewall NGFW | Sí | Sí | Ninguna | - | - | Mantener |
| IDS/IPS | No | Sí | Alta | Medio | Alta | Implementar Suricata |
| SIEM | No | Sí | Alta | Alto | Alta | Implementar Wazuh |
| MFA | Parcial | Sí | Media | Bajo | Alta | Extender a todos los accesos |

#### COMPLIANCE
| Requisito | Estado Actual | Estado Deseado | Brecha | Plan de Acción |
|-----------|:---:|:---:|:---:|----------------|

### RESUMEN DE BRECHAS
| Categoría | Críticas | Altas | Medias | Bajas | Total |
|-----------|:---:|:---:|:---:|:---:|:---:|
| Redes | | | | | |
| Seguridad | | | | | |
| Compliance | | | | | |
| Operación | | | | | |
| **Total** | | | | | |

### ROADMAP DE CIERRE DE BRECHAS
| Fase | Período | Brechas a Cerrar | Recursos Necesarios | Costo Estimado |
|------|---------|-------------------|--------------------:|---------------:|
| 1 | Mes 1-2 | Críticas | | |
| 2 | Mes 3-4 | Altas | | |
| 3 | Mes 5-6 | Medias | | |
| 4 | Mes 7-12 | Bajas | | |

---
**Elaborado por:** [Nombre]
**Revisado por:** [Nombre]
```

---

## **3. Automatizaciones con n8n, Asana, Slack y Herramientas Gratuitas**

### **Automatización 1: Nuevo Cliente → Configuración Automática del Proyecto**

```
📌 TRIGGER: Se crea un nuevo proyecto en Asana con el tag "Nuevo Cliente"

FLUJO EN n8n:
1. [Asana Trigger] → Detectar nuevo proyecto con tag "Nuevo Cliente"
2. [Asana] → Crear automáticamente todas las secciones de la Fase 1:
   - "1.1 Recepción del Proyecto"
   - "1.2 Análisis del Cliente"
   - "1.3 Marco de Trabajo"
   - "1.4 Configuración de Herramientas"
   - "1.5 Transición y Arranque"
3. [Asana] → Crear tareas predefinidas en cada sección 
   (usando los templates anteriores)
4. [Asana] → Asignar Custom Fields predeterminados
5. [Google Drive] → Crear carpeta del cliente con estructura:
   └── Cliente_[Nombre]
       ├── 01_Contrato
       ├── 02_Documentacion_Tecnica
       ├── 03_Assessment
       ├── 04_Informes
       ├── 05_Actas_Reuniones
       └── 06_Backups
6. [Slack] → Crear canales:
   - #cliente-[nombre]-general
   - #cliente-[nombre]-incidentes
   - #cliente-[nombre]-cambios
7. [Slack] → Enviar mensaje al canal #equipo-interno:
   "🆕 Nuevo proyecto de outsourcing: [Cliente]. 
    Gerente de Cuenta: [Nombre]. 
    Kickoff programado para: [Fecha].
    📁 Documentación: [Link Google Drive]
    📋 Proyecto Asana: [Link]"
8. [Google Calendar] → Crear eventos recurrentes:
   - Reunión operativa semanal
   - Comité ejecutivo mensual
9. [Email/Gmail] → Enviar email de bienvenida al cliente
   con template predefinido
```

**Herramientas utilizadas:**
- n8n (orquestador gratuito/self-hosted)
- Asana (gestión de proyecto)
- Slack (comunicación)
- Google Drive (documentación)
- Google Calendar (reuniones)
- Gmail (emails)

---

### **Automatización 2: Seguimiento de Documentación Pendiente**

```
📌 TRIGGER: Cron job diario a las 9:00 AM

FLUJO EN n8n:
1. [Schedule Trigger] → Ejecutar todos los días a las 9:00 AM
2. [Asana] → Buscar tareas en la sección "1.1 Recepción" 
   con Custom Field "Estado: Pendiente" y fecha límite < hoy
3. [IF] → Si hay documentos vencidos:
   a. [Slack] → Enviar recordatorio al Gerente de Cuenta:
      "⚠️ Documentación pendiente del cliente [Nombre]:
       - [Lista de documentos pendientes]
       - Días de retraso: [X]
       Acción requerida: Contactar al cliente"
   b. [Asana] → Agregar comentario en la tarea:
      "⏰ Recordatorio automático: Este documento tiene 
       [X] días de retraso"
   c. [IF] → Si el retraso > 5 días:
      - [Email] → Enviar email al cliente solicitando 
        la documentación pendiente
      - [Slack] → Notificar al Gerente de Operaciones
4. [IF] → Si no hay documentos vencidos:
   - No hacer nada (o log informativo)
```

---

### **Automatización 3: Generación Automática de Actas de Reunión**

```
📌 TRIGGER: Reunión de Google Calendar finalizada con tag "Cliente"

FLUJO EN n8n:
1. [Google Calendar Trigger] → Detectar evento finalizado 
   con tag "Reunión Cliente"
2. [Google Docs] → Crear documento usando el Template 
   de Acta de Reunión con:
   - Nombre del cliente (del evento)
   - Fecha y hora (del evento)
   - Asistentes (del evento)
   - Secciones predefinidas vacías para completar
3. [Google Drive] → Guardar en carpeta del cliente 
   /05_Actas_Reuniones/
4. [Asana] → Crear tarea: "Completar acta de reunión [Fecha]"
   - Asignada a: Gerente de Proyecto
   - Fecha límite: +1 día hábil
   - Adjuntar link del documento
5. [Slack] → Enviar mensaje al canal del cliente:
   "📝 Se ha generado el acta de la reunión de hoy.
    Por favor completar antes de [fecha]:
    📄 [Link al documento]"
```

---

### **Automatización 4: Onboarding Checklist Inteligente**

```
📌 TRIGGER: Tarea de Asana "1.5.5 Obtener aprobación 
formal de inicio" marcada como completada

FLUJO EN n8n:
1. [Asana Trigger] → Tarea "Aprobación formal de inicio" 
   completada
2. [Asana] → Verificar que TODAS las tareas de la Fase 1 
   estén completadas
3. [IF] → Si hay tareas incompletas:
   a. [Slack] → Alertar al Gerente de Proyecto:
      "🚨 Se intentó cerrar la Fase 1 pero hay [X] tareas 
       pendientes: [Lista]"
   b. [Asana] → Reabrir la tarea de aprobación
4. [IF] → Si todas están completadas:
   a. [Asana] → Crear automáticamente todas las tareas 
      de la FASE 2 (Implementación)
   b. [Asana] → Mover el proyecto al status 
      "Fase 2 - Implementación"
   c. [Slack] → Anunciar en #equipo-interno:
      "✅ Fase 1 completada para [Cliente]. 
       Iniciando Fase 2: Implementación.
       📋 [Link al proyecto]"
   d. [Email] → Enviar al cliente:
      "Estimado [Cliente], nos complace informarle que 
       la fase de onboarding ha sido completada exitosamente.
       A continuación iniciaremos la fase de implementación..."
   e. [Google Sheets] → Registrar en hoja de seguimiento:
      - Cliente, Fecha inicio Fase 1, Fecha fin Fase 1, 
        Duración total, Observaciones
```

---

### **Automatización 5: Dashboard de Progreso de Onboarding**

```
📌 TRIGGER: Cron job cada hora

FLUJO EN n8n:
1. [Schedule Trigger] → Cada hora
2. [Asana] → Obtener todas las tareas de la Fase 1 
   del proyecto activo
3. [Function] → Calcular métricas:
   - Total de tareas
   - Tareas completadas
   - Tareas en progreso
   - Tareas vencidas
   - % de avance
   - Días restantes para kickoff
4. [Google Sheets] → Actualizar hoja de métricas
5. [Grafana] → Actualizar dashboard (conectado a Google Sheets)
6. [IF] → Si % avance < 50% y faltan < 5 días para kickoff:
   a. [Slack] → Alerta a Gerente de Proyecto:
      "🔴 ALERTA: El onboarding de [Cliente] tiene solo 
       [X]% de avance y el kickoff es en [X] días.
       Tareas críticas pendientes: [Lista]"
```

---

### **Automatización 6: Registro Automático de Accesos Configurados**

```
📌 TRIGGER: Tarea de Asana en sección "Configuración de Accesos" 
completada

FLUJO EN n8n:
1. [Asana Trigger] → Tarea de acceso completada
2. [Function] → Extraer información:
   - Tipo de acceso (VPN, SSH, Consola, etc.)
   - Usuario configurado
   - Fecha de configuración
   - Responsable
3. [Google Sheets] → Registrar en "Inventario de Accesos":
   | Fecha | Tipo | Usuario | Configurado por | Estado |
4. [Bitwarden/Vaultwarden] → (Opcional) Crear entrada 
   en el gestor de contraseñas del equipo
5. [Slack] → Notificar en #cliente-general:
   "🔑 Acceso configurado: [Tipo] para [Usuario].
    Verificado y operativo."
6. [Asana] → Crear tarea de verificación periódica:
   "Verificar vigencia de acceso [Tipo]"
   - Recurrente cada 90 días
```

---

### **Automatización 7: Alertas de SLA durante Estabilización**

```
📌 TRIGGER: Webhook desde herramienta de monitoreo 
(Zabbix/Uptime Kuma)

FLUJO EN n8n:
1. [Webhook Trigger] → Recibir alerta de monitoreo
2. [Function] → Clasificar severidad:
   - Crítica: Servicio caído
   - Alta: Degradación de performance
   - Media: Warning de recursos
   - Baja: Informativa
3. [Asana] → Crear tarea de incidente:
   - Título: "[SEVERIDAD] - [Descripción]"
   - Custom Fields: Prioridad, Categoría, Tiempo SLA
   - Asignar según RACI
4. [Slack] → Notificar en #cliente-incidentes:
   "🚨 [SEVERIDAD] Alerta detectada:
    📍 Servicio: [Nombre]
    ⏰ Detectado: [Hora]
    👤 Asignado a: [Nombre]
    ⏳ SLA: [Tiempo de resolución]"
5. [IF] → Si es Crítica:
   a. [Twilio/Signal] → Enviar SMS al Líder Técnico
   b. [Slack] → Crear hilo dedicado para seguimiento
6. [Schedule] → Iniciar temporizador de SLA
7. [Schedule] → Si no se resuelve en 50% del tiempo SLA:
   a. [Slack] → Escalar: "⚠️ Incidente [ID] al 50% del SLA. 
      Escalar si no se resuelve en [X] minutos"
```

---

## **4. Herramientas Gratuitas Recomendadas**

| **Categoría** | **Herramienta** | **Uso** | **Costo** |
|---------------|-----------------|---------|-----------|
| **Orquestación/Automatización** | n8n (self-hosted) | Automatizar flujos de trabajo entre herramientas | Gratis |
| **Gestión de Proyecto** | Asana (Free/Premium) | Seguimiento de tareas, hitos, SLA | Free hasta 15 usuarios |
| **Comunicación** | Slack (Free) | Canales con cliente, notificaciones | Free |
| **Monitoreo de Red** | Zabbix | Monitoreo de infraestructura 24/7 | Open Source |
| **Monitoreo de Uptime** | Uptime Kuma | Verificar disponibilidad de servicios | Open Source |
| **SIEM** | Wazuh | Gestión de seguridad y compliance | Open Source |
| **Escaneo de Vulnerabilidades** | OpenVAS/Greenbone | Escaneos periódicos de vulnerabilidades | Open Source |
| **Documentación/Wiki** | BookStack o Notion | Base de conocimiento técnica del cliente | Free |
| **Dashboards** | Grafana | Visualización de métricas de red y SLA | Open Source |
| **Gestión de Contraseñas** | Vaultwarden | Almacenamiento seguro de credenciales | Open Source |
| **Tickets** | Zammad u osTicket | Gestión de incidencias | Open Source |
| **Diagramas de Red** | Draw.io (diagrams.net) | Documentación visual de arquitectura | Free |
| **Backups de Configuración** | Oxidized o RANCID | Backup automático de configs de red | Open Source |
| **Análisis de Red** | Wireshark / ntopng | Análisis de tráfico y troubleshooting | Open Source |
| **Video Reuniones** | Google Meet / Jitsi | Reuniones con el cliente | Free |
| **Hojas de Cálculo** | Google Sheets | Tracking de métricas, inventarios | Free |
| **Almacenamiento** | Google Drive | Documentación del proyecto | Free 15GB |

---

## **5. Custom Fields Recomendados en Asana para la Fase 1**

| **Campo** | **Tipo** | **Opciones** | **Uso** |
|-----------|----------|--------------|---------|
| Estado del Documento | Dropdown | Pendiente / Solicitado / Recibido / Verificado | Tracking de documentación |
| Prioridad | Dropdown | Crítica / Alta / Media / Baja | Priorización de tareas |
| Responsable Cliente | Texto | [Nombre del contacto] | Identificar quién debe entregar |
| Fecha de Solicitud | Fecha | [DD/MM/YYYY] | Control de tiempos |
| Días de Retraso | Número | Auto-calculado | Alertas de retraso |
| Fase | Dropdown | Fase 1 / Fase 2 / Fase 3 / Fase 4 / Fase 5 | Clasificación |
| Tipo de Tarea | Dropdown | Documentación / Técnica / Reunión / Aprobación | Categorización |
| Bloqueo | Dropdown | Bloqueada / Sin Bloqueo | Identificar impedimentos |
| Motivo de Bloqueo | Texto | [Descripción] | Documentar razón |

---

## **6. Criterios de Salida de la Fase 1 (Definition of Done)**

Para considerar la Fase 1 como **completada**, se deben cumplir **TODOS** estos criterios:

```
✅ Toda la documentación del cliente ha sido recibida y verificada
✅ El assessment de seguridad inicial está completo
✅ El gap analysis está documentado y compartido con el cliente
✅ La matriz RACI está firmada por ambas partes
✅ Los SLA operativos están definidos y aprobados
✅ Todos los accesos remotos están configurados y probados
✅ Las herramientas de monitoreo están operativas
✅ El sistema de tickets está configurado
✅ Los canales de comunicación están activos
✅ El equipo del cliente ha sido capacitado
✅ El equipo interno ha sido briefeado
✅ La reunión de kickoff se ha realizado
✅ El acta de inicio está firmada por ambas partes
✅ El período de estabilización ha sido planificado
✅ Los backups iniciales están completos
```

---

¿Estás listo para avanzar a la **Fase 2: Implementación y Migración**? Cuando me lo indiques, la desarrollo con el mismo nivel de detalle, templates y automatizaciones.