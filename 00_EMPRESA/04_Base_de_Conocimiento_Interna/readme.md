# ESTRUCTURA DE GOOGLE DRIVE PARA OUTSOURCING DE REDES Y SEGURIDAD

## **Filosofía de Organización**

La estructura sigue estos principios:

1. **Jerárquica**: De lo general a lo específico
2. **Consistente**: Misma nomenclatura en todos los proyectos
3. **Versionada**: Control de versiones en documentos clave
4. **Accesible**: Permisos diferenciados por rol y por carpeta
5. **Escalable**: Funciona igual con 1 cliente o con 50

---

## **Nivel 0: Raíz del Proveedor**

```
📁 [NOMBRE_DEL_PROVEEDOR]
│
├── 📁 00_EMPRESA
│   ├── 📁 01_Identidad_Corporativa
│   ├── 📁 02_Templates_Maestros
│   ├── 📁 03_Procesos_y_Procedimientos
│   ├── 📁 04_Base_de_Conocimiento_Interna
│   ├── 📁 05_Herramientas_y_Scripts
│   └── 📁 06_Capacitacion_Interna
│
├── 📁 01_CLIENTES_ACTIVOS
│   ├── 📁 [CÓDIGO]_[NOMBRE_CLIENTE_1]
│   ├── 📁 [CÓDIGO]_[NOMBRE_CLIENTE_2]
│   └── 📁 [CÓDIGO]_[NOMBRE_CLIENTE_N]
│
├── 📁 02_CLIENTES_ARCHIVO
│   ├── 📁 [CÓDIGO]_[NOMBRE_CLIENTE_CERRADO_1]
│   └── 📁 [CÓDIGO]_[NOMBRE_CLIENTE_CERRADO_N]
│
├── 📁 03_PROSPECTOS
│   ├── 📁 [PROSPECTO_1]
│   └── 📁 [PROSPECTO_N]
│
└── 📁 04_MARKETING
    ├── 📁 Casos_de_Estudio
    ├── 📁 Presentaciones_Comerciales
    └── 📁 Material_Promocional
```

---

## **Nivel 1: Carpeta de la Empresa (00_EMPRESA)**

```
📁 00_EMPRESA
│
├── 📁 01_Identidad_Corporativa
│   ├── 📄 Logo_Principal.png
│   ├── 📄 Logo_Horizontal.png
│   ├── 📄 Logo_Blanco.png
│   ├── 📄 Logo_Favicon.png
│   ├── 📄 Manual_de_Marca.pdf
│   ├── 📄 Paleta_de_Colores.pdf
│   ├── 📄 Tipografias/
│   ├── 📄 Plantilla_Presentacion_Corporativa.pptx
│   ├── 📄 Plantilla_Documento_Corporativo.docx
│   ├── 📄 Plantilla_Hoja_Membretada.docx
│   ├── 📄 Firma_de_Email_Template.html
│   └── 📄 Plantilla_Factura.xlsx
│
├── 📁 02_Templates_Maestros
│   │
│   ├── 📁 Fase_1_Onboarding
│   │   ├── 📄 TPL_Checklist_Documentacion_Cliente.md
│   │   ├── 📄 TPL_Acta_Reunion_Descubrimiento.md
│   │   ├── 📄 TPL_Matriz_Stakeholders.xlsx
│   │   ├── 📄 TPL_Matriz_RACI.xlsx
│   │   ├── 📄 TPL_Plan_Comunicacion.md
│   │   ├── 📄 TPL_Assessment_Seguridad.md
│   │   ├── 📄 TPL_Gap_Analysis.md
│   │   └── 📄 TPL_Acta_Kickoff.md
│   │
│   ├── 📁 Fase_2_Implementacion
│   │   ├── 📄 TPL_Plan_Implementacion.md
│   │   ├── 📄 TPL_Documento_AS_BUILT.md
│   │   ├── 📄 TPL_Checklist_Validacion_Migracion.md
│   │   ├── 📄 TPL_Informe_Pentesting.md
│   │   ├── 📄 TPL_Playbook_Respuesta_Alertas.md
│   │   ├── 📄 TPL_Control_Cambios.md
│   │   └── 📄 TPL_Informe_Avance_Semanal.md
│   │
│   ├── 📁 Fase_3_Operacion
│   │   ├── 📄 TPL_Reporte_Diario_Operacion.md
│   │   ├── 📄 TPL_Ticket_Incidente.md
│   │   ├── 📄 TPL_Informe_Mensual_SLA.md
│   │   ├── 📄 TPL_Informe_PostMortem.md
│   │   ├── 📄 TPL_Calendario_Mantenimiento_Preventivo.xlsx
│   │   ├── 📄 TPL_Encuesta_Satisfaccion.md
│   │   ├── 📄 TPL_Bitacora_Operaciones.md
│   │   └── 📄 TPL_Informe_Vulnerabilidades_Mensual.md
│   │
│   ├── 📁 Fase_4_Mejora_Continua
│   │   ├── 📄 TPL_QBR_Presentacion.pptx
│   │   ├── 📄 TPL_Propuesta_Mejora.md
│   │   ├── 📄 TPL_Informe_Capacity_Planning.md
│   │   ├── 📄 TPL_Informe_Valor_Entregado.md
│   │   ├── 📄 TPL_Roadmap_Evolucion.md
│   │   └── 📄 TPL_Evaluacion_Riesgo_Churn.md
│   │
│   ├── 📁 Fase_5_Cierre_Renovacion
│   │   ├── 📄 TPL_Informe_Final_Evaluacion.md
│   │   ├── 📄 TPL_Propuesta_Renovacion.md
│   │   ├── 📄 TPL_Plan_Transicion.md
│   │   ├── 📄 TPL_Acta_Cierre_Formal.md
│   │   ├── 📄 TPL_Certificado_Destruccion_Datos.md
│   │   └── 📄 TPL_Lecciones_Aprendidas.md
│   │
│   └── 📁 Generales
│       ├── 📄 TPL_Acta_Reunion_General.md
│       ├── 📄 TPL_Email_Bienvenida_Cliente.md
│       ├── 📄 TPL_Email_Agradecimiento_Cierre.md
│       ├── 📄 TPL_Caso_de_Estudio.md
│       ├── 📄 TPL_NDA.docx
│       ├── 📄 TPL_Contrato_Servicios.docx
│       └── 📄 TPL_SLA_Estandar.docx
│
├── 📁 03_Procesos_y_Procedimientos
│   │
│   ├── 📁 Procesos_Operativos
│   │   ├── 📄 PROC_Gestion_de_Incidentes.md
│   │   ├── 📄 PROC_Gestion_de_Cambios.md
│   │   ├── 📄 PROC_Gestion_de_Problemas.md
│   │   ├── 📄 PROC_Escalamiento.md
│   │   ├── 📄 PROC_Monitoreo_y_Alertas.md
│   │   ├── 📄 PROC_Backup_y_Restore.md
│   │   ├── 📄 PROC_Parcheo_de_Seguridad.md
│   │   ├── 📄 PROC_Mantenimiento_Preventivo.md
│   │   └── 📄 PROC_Respuesta_a_Incidentes_Seguridad.md
│   │
│   ├── 📁 Procesos_Comerciales
│   │   ├── 📄 PROC_Onboarding_Nuevo_Cliente.md
│   │   ├── 📄 PROC_Evaluacion_de_Oportunidades.md
│   │   ├── 📄 PROC_Renovacion_de_Contrato.md
│   │   ├── 📄 PROC_Cierre_de_Contrato.md
│   │   └── 📄 PROC_Gestion_de_Quejas.md
│   │
│   ├── 📁 Procesos_de_Seguridad
│   │   ├── 📄 PROC_Escaneo_Vulnerabilidades.md
│   │   ├── 📄 PROC_Pruebas_Penetracion.md
│   │   ├── 📄 PROC_Threat_Intelligence.md
│   │   ├── 📄 PROC_Gestion_Vulnerabilidades.md
│   │   ├── 📄 PROC_Respuesta_Incidentes_Seguridad.md
│   │   └── 📄 PROC_Auditoria_de_Compliance.md
│   │
│   └── 📁 Politicas
│       ├── 📄 POL_Seguridad_de_la_Informacion.md
│       ├── 📄 POL_Uso_Aceptable.md
│       ├── 📄 POL_Gestion_de_Contraseñas.md
│       ├── 📄 POL_Clasificacion_de_Informacion.md
│       ├── 📄 POL_Retencion_de_Datos.md
│       ├── 📄 POL_Destruccion_de_Datos.md
│       └── 📄 POL_Acceso_Remoto.md
│
├── 📁 04_Base_de_Conocimiento_Interna
│   │
│   ├── 📁 Tecnologias
│   │   ├── 📁 Firewalls
│   │   │   ├── 📁 Fortinet
│   │   │   │   ├── 📄 KB_FortiGate_Configuracion_Basica.md
│   │   │   │   ├── 📄 KB_FortiGate_VPN_IPSec.md
│   │   │   │   ├── 📄 KB_FortiGate_HA_Cluster.md
│   │   │   │   ├── 📄 KB_FortiGate_Troubleshooting.md
│   │   │   │   └── 📄 KB_FortiGate_CLI_Cheatsheet.md
│   │   │   ├── 📁 PfSense
│   │   │   │   ├── 📄 KB_PfSense_Instalacion.md
│   │   │   │   ├── 📄 KB_PfSense_VPN.md
│   │   │   │   └── 📄 KB_PfSense_Troubleshooting.md
│   │   │   └── 📁 OPNsense
│   │   │       └── 📄 ...
│   │   │
│   │   ├── 📁 Switches
│   │   │   ├── 📁 Cisco
│   │   │   ├── 📁 HP_Aruba
│   │   │   └── 📁 MikroTik
│   │   │
│   │   ├── 📁 Routers
│   │   │   ├── 📁 Cisco
│   │   │   ├── 📁 MikroTik
│   │   │   └── 📁 Ubiquiti
│   │   │
│   │   ├── 📁 Wireless
│   │   │   ├── 📁 Ubiquiti_UniFi
│   │   │   ├── 📁 Aruba
│   │   │   └── 📁 Ruckus
│   │   │
│   │   ├── 📁 SIEM
│   │   │   ├── 📁 Wazuh
│   │   │   │   ├── 📄 KB_Wazuh_Instalacion.md
│   │   │   │   ├── 📄 KB_Wazuh_Configuracion_Agentes.md
│   │   │   │   ├── 📄 KB_Wazuh_Reglas_Custom.md
│   │   │   │   └── 📄 KB_Wazuh_Integracion_Slack.md
│   │   │   └── 📁 ELK_Stack
│   │   │
│   │   ├── 📁 IDS_IPS
│   │   │   ├── 📁 Suricata
│   │   │   └── 📁 Snort
│   │   │
│   │   ├── 📁 Monitoreo
│   │   │   ├── 📁 Zabbix
│   │   │   │   ├── 📄 KB_Zabbix_Instalacion.md
│   │   │   │   ├── 📄 KB_Zabbix_Templates.md
│   │   │   │   ├── 📄 KB_Zabbix_SNMP.md
│   │   │   │   └── 📄 KB_Zabbix_Alertas.md
│   │   │   ├── 📁 Grafana
│   │   │   │   ├── 📄 KB_Grafana_Instalacion.md
│   │   │   │   ├── 📄 KB_Grafana_Dashboards.md
│   │   │   │   └── 📄 KB_Grafana_Datasources.md
│   │   │   └── 📁 Uptime_Kuma
│   │   │
│   │   ├── 📁 VPN
│   │   │   ├── 📄 KB_VPN_IPSec_Conceptos.md
│   │   │   ├── 📄 KB_VPN_OpenVPN.md
│   │   │   ├── 📄 KB_VPN_WireGuard.md
│   │   │   └── 📄 KB_VPN_Troubleshooting.md
│   │   │
│   │   ├── 📁 Backup_Configs
│   │   │   ├── 📁 Oxidized
│   │   │   └── 📁 RANCID
│   │   │
│   │   └── 📁 Automatizacion
│   │       ├── 📁 n8n
│   │       │   ├── 📄 KB_n8n_Instalacion.md
│   │       │   ├── 📄 KB_n8n_Integracion_Asana.md
│   │       │   ├── 📄 KB_n8n_Integracion_Slack.md
│   │       │   ├── 📄 KB_n8n_Integracion_Zabbix.md
│   │       │   └── 📁 Workflows_Exportados/
│   │       │       ├── 📄 WF_Nuevo_Cliente.json
│   │       │       ├── 📄 WF_Reporte_Diario.json
│   │       │       ├── 📄 WF_Gestion_Incidentes.json
│   │       │       ├── 📄 WF_Informe_SLA_Mensual.json
│   │       │       ├── 📄 WF_Mantenimiento_Preventivo.json
│   │       │       ├── 📄 WF_Threat_Intelligence.json
│   │       │       ├── 📄 WF_Capacity_Planning.json
│   │       │       ├── 📄 WF_Alerta_Vencimiento_Contrato.json
│   │       │       └── 📄 WF_[Otros].json
│   │       └── 📁 Scripts
│   │           ├── 📄 script_backup_configs.sh
│   │           ├── 📄 script_check_ssl_certs.sh
│   │           ├── 📄 script_network_audit.py
│   │           └── 📄 script_log_rotation.sh
│   │
│   ├── 📁 Troubleshooting
│   │   ├── 📄 TS_Red_Sin_Conectividad.md
│   │   ├── 📄 TS_VPN_No_Conecta.md
│   │   ├── 📄 TS_Firewall_No_Responde.md
│   │   ├── 📄 TS_DHCP_No_Asigna_IP.md
│   │   ├── 📄 TS_DNS_No_Resuelve.md
│   │   ├── 📄 TS_WiFi_Sin_Conexion.md
│   │   ├── 📄 TS_Alto_Consumo_Bandwidth.md
│   │   ├── 📄 TS_Lentitud_de_Red.md
│   │   └── 📄 TS_SIEM_No_Recibe_Logs.md
│   │
│   └── 📁 Cheatsheets
│       ├── 📄 CS_Comandos_Cisco_IOS.pdf
│       ├── 📄 CS_Comandos_FortiOS.pdf
│       ├── 📄 CS_Comandos_Linux_Networking.pdf
│       ├── 📄 CS_Comandos_MikroTik.pdf
│       ├── 📄 CS_Subnetting.pdf
│       ├── 📄 CS_Puertos_Comunes.pdf
│       ├── 📄 CS_Wireshark_Filters.pdf
│       └── 📄 CS_Nmap_Cheatsheet.pdf
│
├── 📁 05_Herramientas_y_Scripts
│   │
│   ├── 📁 Instaladores
│   │   ├── 📄 docker-compose_zabbix.yml
│   │   ├── 📄 docker-compose_grafana.yml
│   │   ├── 📄 docker-compose_wazuh.yml
│   │   ├── 📄 docker-compose_n8n.yml
│   │   ├── 📄 docker-compose_uptime-kuma.yml
│   │   ├── 📄 docker-compose_oxidized.yml
│   │   ├── 📄 docker-compose_bookstack.yml
│   │   ├── 📄 docker-compose_vaultwarden.yml
│   │   └── 📄 docker-compose_zammad.yml
│   │
│   ├── 📁 Configuraciones_Base
│   │   ├── 📄 zabbix_template_network.xml
│   │   ├── 📄 grafana_dashboard_network.json
│   │   ├── 📄 grafana_dashboard_security.json
│   │   ├── 📄 grafana_dashboard_sla.json
│   │   ├── 📄 wazuh_custom_rules.xml
│   │   ├── 📄 suricata_custom_rules.rules
│   │   ├── 📄 oxidized_config.yml
│   │   └── 📄 uptime-kuma_config.json
│   │
│   ├── 📁 Scripts_Operativos
│   │   ├── 📄 health_check_network.sh
│   │   ├── 📄 backup_verification.sh
│   │   ├── 📄 ssl_cert_checker.sh
│   │   ├── 📄 firewall_rule_audit.py
│   │   ├── 📄 bandwidth_report.py
│   │   ├── 📄 user_access_audit.sh
│   │   ├── 📄 log_analyzer.py
│   │   └── 📄 automated_pentest_scan.sh
│   │
│   └── 📁 Diagramas_Base
│       ├── 📄 Diagrama_Red_Template.drawio
│       ├── 📄 Diagrama_Seguridad_Template.drawio
│       ├── 📄 Diagrama_Flujo_Incidentes.drawio
│       ├── 📄 Diagrama_Flujo_Cambios.drawio
│       └── 📄 Iconos_Red_Seguridad.drawio
│
└── 📁 06_Capacitacion_Interna
    ├── 📁 Onboarding_Nuevos_Empleados
    │   ├── 📄 Guia_Bienvenida.pdf
    │   ├── 📄 Manual_Herramientas.pdf
    │   ├── 📄 Manual_Procesos.pdf
    │   ├── 📄 Checklist_Onboarding_Empleado.xlsx
    │   └── 📄 Video_Introduccion.mp4
    │
    ├── 📁 Certificaciones
    │   ├── 📄 Plan_Certificaciones_Equipo.xlsx
    │   ├── 📁 Material_CCNA/
    │   ├── 📁 Material_NSE/
    │   ├── 📁 Material_CompTIA_Security+/
    │   └── 📁 Material_CEH/
    │
    └── 📁 Webinars_y_Sesiones
        ├── 📁 [YYYY-MM]_[Tema]/
        │   ├── 📄 Presentacion.pptx
        │   ├── 📄 Grabacion.mp4
        │   └── 📄 Notas.md
        └── 📄 Registro_Capacitaciones.xlsx
```

---

## **Nivel 2: Carpeta del Cliente (Estructura Completa)**

Esta es la estructura que se crea automáticamente para cada nuevo cliente:

```
📁 OUT-RS-2024-001_EMPRESA_ACME
│
├── 📁 00_GENERAL
│   │
│   ├── 📁 01_Contrato
│   │   ├── 📄 Contrato_Servicios_v1.0.pdf
│   │   ├── 📄 Contrato_Servicios_v1.0_FIRMADO.pdf
│   │   ├── 📄 Anexo_A_Alcance_Tecnico.pdf
│   │   ├── 📄 Anexo_B_SLA.pdf
│   │   ├── 📄 Anexo_C_Precios.pdf
│   │   ├── 📄 NDA_FIRMADO.pdf
│   │   ├── 📄 Adendum_01_[Descripcion].pdf
│   │   └── 📁 Renovaciones/
│   │       ├── 📄 Propuesta_Renovacion_2025.pdf
│   │       └── 📄 Contrato_Renovacion_2025_FIRMADO.pdf
│   │
│   ├── 📁 02_Contactos_y_Stakeholders
│   │   ├── 📄 Matriz_Stakeholders.xlsx
│   │   ├── 📄 Matriz_RACI.xlsx
│   │   ├── 📄 Directorio_Contactos_Cliente.xlsx
│   │   ├── 📄 Directorio_Equipo_Proveedor.xlsx
│   │   └── 📄 Matriz_Escalamiento.xlsx
│   │
│   ├── 📁 03_Plan_de_Comunicacion
│   │   ├── 📄 Plan_Comunicacion_v1.0.md
│   │   ├── 📄 Calendario_Reuniones.xlsx
│   │   └── 📄 Protocolo_Emergencias.md
│   │
│   ├── 📁 04_Facturacion
│   │   ├── 📁 2024/
│   │   │   ├── 📄 Factura_2024_01_Enero.pdf
│   │   │   ├── 📄 Factura_2024_02_Febrero.pdf
│   │   │   └── 📄 ...
│   │   ├── 📁 2025/
│   │   └── 📄 Control_Facturacion.xlsx
│   │
│   └── 📁 05_Presentaciones
│       ├── 📄 Presentacion_Kickoff.pptx
│       ├── 📄 Presentacion_Resultados_Q1.pptx
│       └── 📄 ...
│
├── 📁 01_FASE_1_ONBOARDING
│   │
│   ├── 📁 01_Documentacion_Recibida
│   │   │
│   │   ├── 📁 Contractual
│   │   │   ├── 📄 RFP_Original.pdf
│   │   │   ├── 📄 Propuesta_Tecnica_Enviada.pdf
│   │   │   └── 📄 Propuesta_Economica_Enviada.pdf
│   │   │
│   │   ├── 📁 Tecnica
│   │   │   ├── 📄 Diagrama_Red_Actual_Cliente.pdf
│   │   │   ├── 📄 Diagrama_Red_Actual_Cliente.drawio
│   │   │   ├── 📄 Inventario_Equipos_Cliente.xlsx
│   │   │   ├── 📄 Configuraciones_Actuales/
│   │   │   │   ├── 📄 Firewall_Config_[Fecha].txt
│   │   │   │   ├── 📄 Switch_Core_Config_[Fecha].txt
│   │   │   │   ├── 📄 Router_Config_[Fecha].txt
│   │   │   │   └── 📄 ...
│   │   │   ├── 📄 Plan_Direccionamiento_IP.xlsx
│   │   │   ├── 📄 Lista_VLANs.xlsx
│   │   │   └── 📄 Licencias_Software.xlsx
│   │   │
│   │   ├── 📁 Seguridad
│   │   │   ├── 📄 Politica_Seguridad_Cliente.pdf
│   │   │   ├── 📄 Reglas_Firewall_Actuales.xlsx
│   │   │   ├── 📄 Ultima_Auditoria_Seguridad.pdf
│   │   │   ├── 📄 Ultimo_Pentesting.pdf
│   │   │   ├── 📄 Plan_Continuidad_Negocio.pdf
│   │   │   ├── 📄 Plan_Recuperacion_Desastres.pdf
│   │   │   └── 📄 Certificaciones_Compliance.pdf
│   │   │
│   │   ├── 📁 Operativa
│   │   │   ├── 📄 Horarios_Operacion.pdf
│   │   │   ├── 📄 Ventanas_Mantenimiento.pdf
│   │   │   ├── 📄 Proveedores_ISP.xlsx
│   │   │   └── 📄 Procedimientos_Actuales.pdf
│   │   │
│   │   └── 📄 Checklist_Documentacion_v1.0.xlsx
│   │       [✅ Lista de todos los documentos 
│   │        recibidos/pendientes con fechas]
│   │
│   ├── 📁 02_Assessment_Inicial
│   │   ├── 📄 Informe_Assessment_Seguridad_v1.0.pdf
│   │   ├── 📄 Escaneo_Vulnerabilidades_Inicial.pdf
│   │   ├── 📄 Informe_Gap_Analysis_v1.0.pdf
│   │   ├── 📄 Matriz_Riesgos_Inicial.xlsx
│   │   ├── 📄 Clasificacion_Criticidad_Sistemas.xlsx
│   │   └── 📁 Evidencias/
│   │       ├── 📄 Nmap_Scan_Results.xml
│   │       ├── 📄 OpenVAS_Report.html
│   │       └── 📄 Screenshots/
│   │
│   ├── 📁 03_Diseno
│   │   ├── 📄 Arquitectura_AS_IS.drawio
│   │   ├── 📄 Arquitectura_AS_IS.png
│   │   ├── 📄 Arquitectura_TO_BE.drawio
│   │   ├── 📄 Arquitectura_TO_BE.png
│   │   ├── 📄 Plan_Direccionamiento_IP_Nuevo.xlsx
│   │   └── 📄 Diseño_VLANs.xlsx
│   │
│   ├── 📁 04_SLA_y_Gobernanza
│   │   ├── 📄 SLA_Operativos_v1.0.pdf
│   │   ├── 📄 Procedimiento_Gestion_Cambios.pdf
│   │   ├── 📄 Matriz_Escalamiento.xlsx
│   │   └── 📄 Plantilla_Reporteo_Aprobada.xlsx
│   │
│   ├── 📁 05_Actas_y_Minutas
│   │   ├── 📄 Acta_Reunion_Descubrimiento_[Fecha].pdf
│   │   ├── 📄 Acta_Kickoff_Interno_[Fecha].pdf
│   │   ├── 📄 Acta_Kickoff_Cliente_[Fecha].pdf
│   │   ├── 📄 Acta_Aprobacion_Inicio_FIRMADA.pdf
│   │   └── 📄 ...
│   │
│   └── 📁 06_Capacitacion
│       ├── 📄 Material_Capacitacion_Cliente.pptx
│       ├── 📄 Guia_Rapida_Reportar_Incidencias.pdf
│       ├── 📄 Guia_Rapida_Solicitar_Cambios.pdf
│       ├── 📄 Registro_Asistencia_Capacitacion.xlsx
│       └── 📄 Material_Capacitacion_Equipo_Interno.pptx
│
├── 📁 02_FASE_2_IMPLEMENTACION
│   │
│   ├── 📁 01_Plan
│   │   ├── 📄 Plan_Implementacion_v1.0.pdf
│   │   ├── 📄 Plan_Implementacion_v1.0_APROBADO.pdf
│   │   ├── 📄 Plan_Rollback.pdf
│   │   ├── 📄 Plan_Pruebas.pdf
│   │   ├── 📄 Cronograma_Implementacion.xlsx
│   │   ├── 📄 Inventario_Licencias_Recursos.xlsx
│   │   └── 📄 Calendario_Ventanas_Mantenimiento.xlsx
│   │
│   ├── 📁 02_Configuraciones
│   │   │
│   │   ├── 📁 Red
│   │   │   ├── 📄 Config_VLANs.txt
│   │   │   ├── 📄 Config_Routing.txt
│   │   │   ├── 📄 Config_QoS.txt
│   │   │   ├── 📄 Config_Redundancia.txt
│   │   │   ├── 📄 Config_DNS.txt
│   │   │   ├── 📄 Config_DHCP.txt
│   │   │   ├── 📄 Config_WiFi.txt
│   │   │   └── 📄 Config_Bandwidth_Management.txt
│   │   │
│   │   ├── 📁 Seguridad_Perimetral
│   │   │   ├── 📄 Config_Firewall.txt
│   │   │   ├── 📄 Reglas_Firewall_Detalle.xlsx
│   │   │   ├── 📄 Config_DMZ.txt
│   │   │   ├── 📄 Config_VPN_S2S.txt
│   │   │   ├── 📄 Config_VPN_RA.txt
│   │   │   ├── 📄 Config_IDS_IPS.txt
│   │   │   ├── 📄 Config_Filtrado_Web.txt
│   │   │   ├── 📄 Config_NAT.txt
│   │   │   └── 📄 Checklist_Hardening.xlsx
│   │   │
│   │   ├── 📁 Seguridad_Interna
│   │   │   ├── 📄 Config_MFA.txt
│   │   │   ├── 📄 Config_NAC.txt
│   │   │   ├── 📄 Config_SIEM.txt
│   │   │   ├── 📄 Config_Centralizacion_Logs.txt
│   │   │   ├── 📄 Config_Politicas_Contraseñas.txt
│   │   │   ├── 📄 Config_Zero_Trust.txt
│   │   │   └── 📄 Config_Cifrado.txt
│   │   │
│   │   └── 📁 Monitoreo
│   │       ├── 📄 Config_Zabbix_Hosts.xml
│   │       ├── 📄 Config_Zabbix_Templates.xml
│   │       ├── 📄 Config_Grafana_Dashboards.json
│   │       ├── 📄 Config_Uptime_Kuma.json
│   │       ├── 📄 Config_Alertas.xlsx
│   │       └── 📄 Config_Wazuh_Rules.xml
│   │
│   ├── 📁 03_Migracion
│   │   ├── 📁 Pre_Migracion
│   │   │   ├── 📄 Backup_Pre_Migracion_[Fecha].zip
│   │   │   └── 📄 Verificacion_Backup.pdf
│   │   │
│   │   ├── 📁 Piloto
│   │   │   ├── 📄 Informe_Migracion_Piloto.pdf
│   │   │   ├── 📄 Checklist_Validacion_Piloto.xlsx
│   │   │   └── 📄 Lecciones_Piloto.md
│   │   │
│   │   ├── 📁 Fase_A
│   │   │   ├── 📄 Log_Migracion_Fase_A.md
│   │   │   ├── 📄 Checklist_Validacion_Fase_A.xlsx
│   │   │   └── 📄 Comunicacion_Ventana_Fase_A.pdf
│   │   │
│   │   ├── 📁 Fase_B
│   │   │   ├── 📄 Log_Migracion_Fase_B.md
│   │   │   ├── 📄 Checklist_Validacion_Fase_B.xlsx
│   │   │   └── 📄 Comunicacion_Ventana_Fase_B.pdf
│   │   │
│   │   ├── 📁 Fase_C
│   │   │   ├── 📄 Log_Migracion_Fase_C.md
│   │   │   └── 📄 Checklist_Validacion_Fase_C.xlsx
│   │   │
│   │   └── 📁 Post_Migracion
│   │       ├── 📄 Backup_Post_Migracion_[Fecha].zip
│   │       ├── 📄 Checklist_Validacion_Completa.xlsx
│   │       └── 📄 Verificacion_Backup_Post.pdf
│   │
│   ├── 📁 04_Pruebas
│   │   │
│   │   ├── 📁 Conectividad
│   │   │   ├── 📄 Informe_Pruebas_Conectividad.pdf
│   │   │   └── 📄 Evidencias_Conectividad/
│   │   │       ├── 📄 Ping_VLANs.png
│   │   │       ├── 📄 Traceroute_Results.txt
│   │   │       └── 📄 DNS_Tests.txt
│   │   │
│   │   ├── 📁 Rendimiento
│   │   │   ├── 📄 Informe_Pruebas_Performance.pdf
│   │   │   └── 📄 Evidencias_Performance/
│   │   │       ├── 📄 iPerf_Results.txt
│   │   │       ├── 📄 Latency_Tests.png
│   │   │       └── 📄 QoS_Validation.png
│   │   │
│   │   ├── 📁 Failover
│   │   │   ├── 📄 Informe_Pruebas_Failover.pdf
│   │   │   └── 📄 Evidencias_Failover/
│   │   │
│   │   ├── 📁 Seguridad
│   │   │   ├── 📄 Informe_Pentesting.pdf
│   │   │   ├── 📄 Informe_Escaneo_Vulnerabilidades.pdf
│   │   │   ├── 📄 Informe_Validacion_Firewall.pdf
│   │   │   └── 📄 Evidencias_Seguridad/
│   │   │       ├── 📄 OpenVAS_Full_Report.html
│   │   │       ├── 📄 Nmap_Results.xml
│   │   │       └── 📄 Screenshots/
│   │   │
│   │   ├── 📁 Monitoreo
│   │   │   ├── 📄 Informe_Validacion_Monitoreo.pdf
│   │   │   └── 📄 Evidencias_Monitoreo/
│   │   │
│   │   ├── 📁 Backup_Restore
│   │   │   ├── 📄 Informe_Pruebas_Restore.pdf
│   │   │   └── 📄 Evidencias_Restore/
│   │   │
│   │   ├── 📁 Usuario_Final
│   │   │   ├── 📄 Formulario_Validacion_Usuarios.xlsx
│   │   │   └── 📄 Feedback_Usuarios.xlsx
│   │   │
│   │   └── 📁 Remediacion
│   │       ├── 📄 Log_Remediacion.xlsx
│   │       ├── 📄 Informe_Retest.pdf
│   │       └── 📄 Evidencias_Retest/
│   │
│   ├── 📁 05_Documentacion_Final
│   │   ├── 📄 Documento_AS_BUILT_v1.0.pdf
│   │   ├── 📄 Documento_AS_BUILT_v1.0.md
│   │   ├── 📄 Diagrama_Red_Implementado.drawio
│   │   ├── 📄 Diagrama_Red_Implementado.png
│   │   ├── 📄 Diagrama_Seguridad_Implementado.drawio
│   │   ├── 📄 Diagrama_Seguridad_Implementado.png
│   │   ├── 📄 Inventario_Activos_Final.xlsx
│   │   └── 📄 Matriz_Alertas_Configuradas.xlsx
│   │
│   ├── 📁 06_Playbooks
│   │   ├── 📄 PB_001_Host_Down.md
│   │   ├── 📄 PB_002_High_CPU.md
│   │   ├── 📄 PB_003_Link_Down.md
│   │   ├── 📄 PB_004_Security_Alert.md
│   │   ├── 📄 PB_005_Disk_Full.md
│   │   ├── 📄 PB_006_Backup_Failed.md
│   │   ├── 📄 PB_007_Brute_Force.md
│   │   ├── 📄 PB_008_Malware.md
│   │   └── 📄 PB_Indice_Playbooks.xlsx
│   │
│   ├── 📁 07_Capacitacion_Operaciones
│   │   ├── 📄 Material_Capacitacion_Ops.pptx
│   │   ├── 📄 Registro_Capacitacion_Ops.xlsx
│   │   └── 📄 Evaluacion_Conocimiento.xlsx
│   │
│   └── 📁 08_Aceptacion
│       ├── 📄 Acta_Aceptacion_FIRMADA.pdf
│       ├── 📄 Informe_Implementacion_Final.pdf
│       ├── 📄 Retrospectiva_Implementacion.md
│       └── 📄 Acta_Transicion_Operacion.pdf
│
├── 📁 03_FASE_3_OPERACION
│   │
│   ├── 📁 01_Reportes_Diarios
│   │   ├── 📁 2024/
│   │   │   ├── 📁 01_Enero/
│   │   │   │   ├── 📄 Reporte_Diario_2024-01-02.md
│   │   │   │   ├── 📄 Reporte_Diario_2024-01-03.md
│   │   │   │   └── 📄 ...
│   │   │   ├── 📁 02_Febrero/
│   │   │   └── 📁 .../
│   │   └── 📁 2025/
│   │
│   ├── 📁 02_Incidentes
│   │   ├── 📁 2024/
│   │   │   ├── 📁 01_Enero/
│   │   │   │   ├── 📁 INC-2024-0001/
│   │   │   │   │   ├── 📄 Ticket_INC-2024-0001.md
│   │   │   │   │   ├── 📄 Evidencias/
│   │   │   │   │   │   ├── 📄 screenshot_error.png
│   │   │   │   │   │   ├── 📄 log_extract.txt
│   │   │   │   │   │   └── 📄 wireshark_capture.pcap
│   │   │   │   │   └── 📄 Comunicacion_Cliente.pdf
│   │   │   │   ├── 📁 INC-2024-0002/
│   │   │   │   └── 📄 ...
│   │   │   └── 📁 .../
│   │   ├── 📁 2025/
│   │   ├── 📄 Registro_Incidentes_Maestro.xlsx
│   │   └── 📁 Post_Mortems/
│   │       ├── 📄 PM_INC-2024-0015.md
│   │       ├── 📄 PM_INC-2024-0042.md
│   │       └── 📄 ...
│   │
│   ├── 📁 03_Cambios
│   │   ├── 📁 2024/
│   │   │   ├── 📁 CHG-2024-001/
│   │   │   │   ├── 📄 RFC_CHG-2024-001.md
│   │   │   │   ├── 📄 Plan_Implementacion.md
│   │   │   │   ├── 📄 Plan_Rollback.md
│   │   │   │   ├── 📄 Evidencia_Pre_Cambio.png
│   │   │   │   ├── 📄 Evidencia_Post_Cambio.png
│   │   │   │   └── 📄 Verificacion_Post_Cambio.md
│   │   │   └── 📄 ...
│   │   ├── 📁 2025/
│   │   └── 📄 Registro_Cambios_Maestro.xlsx
│   │
│   ├── 📁 04_Informes_Mensuales
│   │   ├── 📁 2024/
│   │   │   ├── 📄 Informe_SLA_2024_01_Enero.pdf
│   │   │   ├── 📄 Informe_SLA_2024_02_Febrero.pdf
│   │   │   ├── 📄 Informe_Seguridad_2024_01_Enero.pdf
│   │   │   ├── 📄 Informe_Seguridad_2024_02_Febrero.pdf
│   │   │   └── 📄 ...
│   │   └── 📁 2025/
│   │
│   ├── 📁 05_Informes_Semanales
│   │   ├── 📁 2024/
│   │   │   ├── 📄 Informe_Semanal_2024_S01.pdf
│   │   │   ├── 📄 Informe_Semanal_2024_S02.pdf
│   │   │   └── 📄 ...
│   │   └── 📁 2025/
│   │
│   ├── 📁 06_Seguridad
│   │   │
│   │   ├── 📁 Escaneos_Vulnerabilidades
│   │   │   ├── 📁 2024/
│   │   │   │   ├── 📁 2024_01_Enero/
│   │   │   │   │   ├── 📄 Informe_Vulnerabilidades_2024_01.pdf
│   │   │   │   │   ├── 📄 OpenVAS_Full_Report.html
│   │   │   │   │   └── 📄 Tracker_Remediacion.xlsx
│   │   │   │   └── 📄 ...
│   │   │   └── 📁 2025/
│   │   │
│   │   ├── 📁 Pentesting
│   │   │   ├── 📁 2024_H1/
│   │   │   │   ├── 📄 Informe_Pentesting_2024_H1.pdf
│   │   │   │   ├── 📄 Evidencias/
│   │   │   │   └── 📄 Plan_Remediacion.xlsx
│   │   │   └── 📁 2024_H2/
│   │   │
│   │   ├── 📁 Threat_Intelligence
│   │   │   ├── 📁 2024/
│   │   │   │   ├── 📄 Boletin_Amenazas_2024_01.pdf
│   │   │   │   └── 📄 ...
│   │   │   └── 📄 IoCs_Detectados.xlsx
│   │   │
│   │   ├── 📁 Compliance
│   │   │   ├── 📄 Auditoria_Compliance_Q1_2024.pdf
│   │   │   ├── 📄 Auditoria_Compliance_Q2_2024.pdf
│   │   │   └── 📄 ...
│   │   │
│   │   └── 📁 Awareness
│   │       ├── 📁 Campaña_Phishing_Q1_2024/
│   │       │   ├── 📄 Informe_Campaña.pdf
│   │       │   └── 📄 Resultados.xlsx
│   │       └── 📄 ...
│   │
│   ├── 📁 07_Mantenimiento_Preventivo
│   │   ├── 📄 Calendario_Mantenimiento_2024.xlsx
│   │   ├── 📄 Calendario_Mantenimiento_2025.xlsx
│   │   ├── 📁 Registros/
│   │   │   ├── 📁 Parcheo/
│   │   │   │   ├── 📄 Parcheo_2024_01.md
│   │   │   │   └── 📄 ...
│   │   │   ├── 📁 Pruebas_Backup/
│   │   │   │   ├── 📄 Prueba_Restore_2024_01.md
│   │   │   │   └── 📄 ...
│   │   │   ├── 📁 Pruebas_Failover/
│   │   │   │   ├── 📄 Prueba_Failover_Q1_2024.md
│   │   │   │   └── 📄 ...
│   │   │   ├── 📁 Auditorias_Firewall/
│   │   │   │   ├── 📄 Auditoria_Reglas_Q1_2024.pdf
│   │   │   │   └── 📄 ...
│   │   │   ├── 📁 Revisiones_Acceso/
│   │   │   │   ├── 📄 Revision_Accesos_Q1_2024.pdf
│   │   │   │   └── 📄 ...
│   │   │   └── 📁 Simulacros_DR/
│   │   │       ├── 📄 Simulacro_DR_H1_2024.pdf
│   │   │       └── 📄 ...
│   │   └── 📄 Registro_Mantenimientos_Maestro.xlsx
│   │
│   ├── 📁 08_Backups_Configuraciones
│   │   ├── 📁 Automaticos_Oxidized/
│   │   │   └── [Gestionado por Oxidized - referencia]
│   │   ├── 📁 Manuales/
│   │   │   ├── 📁 2024_01_15_Pre_Cambio_CHG001/
│   │   │   │   ├── 📄 firewall_config.txt
│   │   │   │   ├── 📄 switch_core_config.txt
│   │   │   │   └── 📄 router_config.txt
│   │   │   └── 📄 ...
│   │   └── 📄 Registro_Backups.xlsx
│   │
│   ├── 📁 09_Bitacora_Operaciones
│   │   ├── 📁 2024/
│   │   │   ├── 📄 Bitacora_2024_01_Enero.md
│   │   │   ├── 📄 Bitacora_2024_02_Febrero.md
│   │   │   └── 📄 ...
│   │   └── 📁 2025/
│   │
│   ├── 📁 10_Reuniones
│   │   ├── 📁 Semanales/
│   │   │   ├── 📄 Minuta_Semanal_2024-01-09.md
│   │   │   ├── 📄 Minuta_Semanal_2024-01-16.md
│   │   │   └── 📄 ...
│   │   ├── 📁 Mensuales/
│   │   │   ├── 📄 Minuta_Comite_Ejecutivo_2024_01.md
│   │   │   └── 📄 ...
│   │   └── 📁 Extraordinarias/
│   │       └── 📄 ...
│   │
│   └── 📁 11_Satisfaccion_Cliente
│       ├── 📄 Encuesta_Q1_2024_Resultados.xlsx
│       ├── 📄 Encuesta_Q2_2024_Resultados.xlsx
│       ├── 📄 Encuesta_Q3_2024_Resultados.xlsx
│       ├── 📄 Encuesta_Q4_2024_Resultados.xlsx
│       └── 📄 Historico_Satisfaccion.xlsx
│
├── 📁 04_FASE_4_MEJORA_CONTINUA
│   │
│   ├── 📁 01_QBRs
│   │   ├── 📁 QBR_Q1_2024/
│   │   │   ├── 📄 Presentacion_QBR_Q1_2024.pptx
│   │   │   ├── 📄 Presentacion_QBR_Q1_2024.pdf
│   │   │   ├── 📄 Datos_Soporte_QBR_Q1_2024.xlsx
│   │   │   └── 📄 Minuta_QBR_Q1_2024.md
│   │   ├── 📁 QBR_Q2_2024/
│   │   ├── 📁 QBR_Q3_2024/
│   │   └── 📁 QBR_Q4_2024/
│   │
│   ├── 📁 02_Analisis_Tendencias
│   │   ├── 📄 Analisis_Tendencias_Q1_2024.pdf
│   │   ├── 📄 Analisis_Tendencias_Q2_2024.pdf
│   │   ├── 📄 Analisis_Tendencias_Q3_2024.pdf
│   │   ├── 📄 Analisis_Tendencias_Q4_2024.pdf
│   │   └── 📄 Datos_Historicos_Tendencias.xlsx
│   │
│   ├── 📁 03_Capacity_Planning
│   │   ├── 📄 Informe_Capacity_H1_2024.pdf
│   │   ├── 📄 Informe_Capacity_H2_2024.pdf
│   │   └── 📄 Datos_Capacity_Historico.xlsx
│   │
│   ├── 📁 04_Propuestas_Mejora
│   │   │
│   │   ├── 📁 IMP-2024-001_Optimizar_QoS/
│   │   │   ├── 📄 Propuesta_IMP-2024-001.pdf
│   │   │   ├── 📄 Analisis_Costo_Beneficio.xlsx
│   │   │   ├── 📄 Plan_Implementacion.pdf
│   │   │   ├── 📄 Informe_Resultados.pdf
│   │   │   └── 📄 Medicion_Impacto_30d.pdf
│   │   │
│   │   ├── 📁 IMP-2024-002_Implementar_ZTNA/
│   │   │   ├── 📄 Propuesta_IMP-2024-002.pdf
│   │   │   ├── 📄 POC_Resultados.pdf
│   │   │   └── 📄 Estado_RECHAZADA.md
│   │   │
│   │   ├── 📁 IMP-2024-003_SD_WAN/
│   │   │   └── 📄 ...
│   │   │
│   │   └── 📄 Backlog_Mejoras_Maestro.xlsx
│   │
│   ├── 📁 05_Valor_Entregado
│   │   ├── 📄 Informe_Valor_H1_2024.pdf
│   │   ├── 📄 Informe_Valor_H2_2024.pdf
│   │   └── 📄 Calculo_ROI_Historico.xlsx
│   │
│   ├── 📁 06_Roadmap
│   │   ├── 📄 Roadmap_Evolucion_v1.0.pdf
│   │   ├── 📄 Roadmap_Evolucion_v1.0.pptx
│   │   ├── 📄 Roadmap_Evolucion_v2.0.pdf [Actualizado]
│   │   └── 📄 Historico_Versiones_Roadmap.md
│   │
│   ├── 📁 07_Evaluaciones_Madurez
│   │   ├── 📄 Evaluacion_Madurez_Seguridad_H1_2024.pdf
│   │   ├── 📄 Evaluacion_Madurez_Seguridad_H2_2024.pdf
│   │   └── 📄 Historico_Madurez.xlsx
│   │
│   └── 📁 08_EOL_EOS
│       ├── 📄 Inventario_EOL_EOS.xlsx
│       ├── 📄 Alerta_EOL_[Equipo]_[Fecha].pdf
│       └── 📄 Plan_Renovacion_Tecnologica.pdf
│
├── 📁 05_FASE_5_CIERRE_RENOVACION
│   │
│   ├── 📁 01_Evaluacion_Final
│   │   ├── 📄 Informe_Final_Evaluacion_Servicio.pdf
│   │   ├── 📄 Informe_SLA_Acumulado.pdf
│   │   ├── 📄 Informe_Valor_Total_Entregado.pdf
│   │   ├── 📄 Informe_Cumplimiento_Objetivos.pdf
│   │   ├── 📄 Encuesta_Satisfaccion_Final.xlsx
│   │   ├── 📄 Presentacion_Resultados_Finales.pptx
│   │   ├── 📄 Auditoria_Tecnica_Final.pdf
│   │   └── 📄 Escaneo_Vulnerabilidades_Final.pdf
│   │
│   ├── 📁 02_Renovacion [Si aplica]
│   │   ├── 📄 Propuesta_Renovacion_v1.0.pdf
│   │   ├── 📄 Comparativa_Alcance_Actual_vs_Nuevo.xlsx
│   │   ├── 📄 Roadmap_Nuevo_Periodo.pdf
│   │   ├── 📄 Negociacion_Terminos.md
│   │   ├── 📄 Contrato_Renovacion_FIRMADO.pdf
│   │   └── 📄 Plan_Primer_Trimestre_Nuevo.pdf
│   │
│   ├── 📁 03_Transicion [Si aplica]
│   │   ├── 📄 Plan_Transicion_v1.0.pdf
│   │   ├── 📄 Plan_Transicion_v1.0_APROBADO.pdf
│   │   ├── 📄 Cronograma_Transicion.xlsx
│   │   │
│   │   ├── 📁 Documentacion_Entregada/
│   │   │   ├── 📄 Paquete_Documentacion_Tecnica.zip
│   │   │   ├── 📄 AS_BUILT_Final.pdf
│   │   │   ├── 📄 Configuraciones_Export.zip
│   │   │   ├── 📄 Playbooks_Export.zip
│   │   │   ├── 📄 KB_Export.zip
│   │   │   ├── 📄 Historial_Incidentes_Export.xlsx
│   │   │   ├── 📄 Historial_Cambios_Export.xlsx
│   │   │   ├── 📄 Informes_SLA_Historicos.zip
│   │   │   ├── 📄 Monitoreo_Export.zip
│   │   │   ├── 📄 SIEM_Export.zip
│   │   │   └── 📄 Checklist_Entregables.xlsx
│   │   │
│   │   ├── 📁 Capacitacion_Receptor/
│   │   │   ├── 📄 Sesion_01_Arquitectura_Red.pptx
│   │   │   ├── 📄 Sesion_02_Seguridad_Perimetral.pptx
│   │   │   ├── 📄 Sesion_03_Seguridad_Interna.pptx
│   │   │   ├── 📄 Sesion_04_Monitoreo.pptx
│   │   │   ├── 📄 Sesion_05_Gestion_Incidentes.pptx
│   │   │   ├── 📄 Sesion_06_Gestion_Cambios.pptx
│   │   │   ├── 📄 Sesion_07_Backups_DR.pptx
│   │   │   ├── 📄 Sesion_08_WiFi.pptx
│   │   │   ├── 📄 Sesion_09_Operacion_Diaria.pptx
│   │   │   ├── 📄 Sesion_10_QA_General.pptx
│   │   │   ├── 📄 Grabaciones/ [Si aplica]
│   │   │   └── 📄 Registro_Asistencia.xlsx
│   │   │
│   │   ├── 📁 Operacion_Paralela/
│   │   │   ├── 📄 Informe_Shadowing_Semana_1.md
│   │   │   ├── 📄 Informe_Supervisada_Semana_2.md
│   │   │   └── 📄 Informe_Independiente_Semana_3.md
│   │   │
│   │   ├── 📁 Revocacion_Accesos/
│   │   │   ├── 📄 Lista_Accesos_Revocados.xlsx
│   │   │   └── 📄 Verificacion_Accesos_Revocados.pdf
│   │   │
│   │   └── 📁 Destruccion_Datos/
│   │       ├── 📄 Inventario_Datos_a_Destruir.xlsx
│   │       ├── 📄 Log_Destruccion.md
│   │       └── 📄 Certificado_Destruccion_Datos_FIRMADO.pdf
│   │
│   ├── 📁 04_Cierre_Administrativo
│   │   ├── 📄 Checklist_Obligaciones_Cumplidas.xlsx
│   │   ├── 📄 Estado_Cuenta_Final.pdf
│   │   ├── 📄 Factura_Final.pdf
│   │   ├── 📄 Acta_Devolucion_Activos.pdf
│   │   ├── 📄 NDA_Post_Contractual.pdf
│   │   └── 📄 Resolución_Penalizaciones.pdf [Si aplica]
│   │
│   ├── 📁 05_Lecciones_Aprendidas
│   │   ├── 📄 Retrospectiva_Interna.md
│   │   ├── 📄 Documento_Lecciones_Aprendidas.pdf
│   │   ├── 📄 Acciones_Mejora_Organizacion.xlsx
│   │   └── 📄 Caso_de_Estudio.pdf [Si aplica]
│   │
│   └── 📁 06_Cierre_Formal
│       ├── 📄 Acta_Cierre_Formal_FIRMADA.pdf
│       ├── 📄 Carta_Agradecimiento.pdf
│       ├── 📄 Carta_Referencia_Cliente.pdf [Si aplica]
│       └── 📄 Plan_Contacto_Post_Cierre.md
│
├── 📁 06_DOCUMENTACION_TECNICA_VIGENTE
│   │
│   │   [Esta carpeta contiene SIEMPRE la versión más
│   │    actualizada de cada documento técnico.
│   │    Es la "fuente de verdad" para el equipo operativo.]
│   │
│   ├── 📄 AS_BUILT_VIGENTE.md
│   ├── 📄 AS_BUILT_VIGENTE.pdf
│   ├── 📄 Diagrama_Red_VIGENTE.drawio
│   ├── 📄 Diagrama_Red_VIGENTE.png
│   ├── 📄 Diagrama_Seguridad_VIGENTE.drawio
│   ├── 📄 Diagrama_Seguridad_VIGENTE.png
│   ├── 📄 Inventario_Equipos_VIGENTE.xlsx
│   ├── 📄 Plan_Direccionamiento_IP_VIGENTE.xlsx
│   ├── 📄 Reglas_Firewall_VIGENTE.xlsx
│   ├── 📄 Configuracion_VPN_VIGENTE.md
│   ├── 📄 Configuracion_WiFi_VIGENTE.md
│   ├── 📄 Politicas_Seguridad_VIGENTE.pdf
│   ├── 📄 Matriz_RACI_VIGENTE.xlsx
│   ├── 📄 Plan_Comunicacion_VIGENTE.md
│   ├── 📄 Matriz_Escalamiento_VIGENTE.xlsx
│   ├── 📄 SLA_Operativos_VIGENTE.pdf
│   ├── 📄 Matriz_Alertas_VIGENTE.xlsx
│   ├── 📄 Calendario_Mantenimiento_VIGENTE.xlsx
│   ├── 📄 Inventario_Licencias_VIGENTE.xlsx
│   ├── 📄 Inventario_Certificados_VIGENTE.xlsx
│   ├── 📄 Contactos_ISP_Proveedores_VIGENTE.xlsx
│   │
│   ├── 📁 Playbooks_VIGENTES/
│   │   ├── 📄 PB_001_Host_Down.md
│   │   ├── 📄 PB_002_High_CPU.md
│   │   ├── 📄 PB_003_Link_Down.md
│   │   ├── 📄 PB_004_Security_Alert.md
│   │   ├── 📄 PB_005_Disk_Full.md
│   │   ├── 📄 PB_006_Backup_Failed.md
│   │   ├── 📄 PB_007_Brute_Force.md
│   │   ├── 📄 PB_008_Malware.md
│   │   └── 📄 Indice_Playbooks.md
│   │
│   ├── 📁 Procedimientos_VIGENTES/
│   │   ├── 📄 Procedimiento_Gestion_Incidentes.md
│   │   ├── 📄 Procedimiento_Gestion_Cambios.md
│   │   ├── 📄 Procedimiento_Escalamiento.md
│   │   ├── 📄 Procedimiento_Backup_Restore.md
│   │   ├── 📄 Procedimiento_Parcheo.md
│   │   └── 📄 Procedimiento_Respuesta_Incidentes_Seg.md
│   │
│   └── 📄 _CHANGELOG.md
│       [Registro de cada cambio realizado 
│        en la documentación vigente con fecha,
│        descripción y responsable]
│
└── 📁 07_METRICAS_Y_DATOS
    │
    │   [Hojas de cálculo maestras que alimentan 
    │    dashboards, automatizaciones e informes]
    │
    ├── 📄 Metricas_SLA_Maestro.xlsx
    │   [Sheets: Disponibilidad, MTTR, MTBF, 
    │    Cumplimiento SLA, Tendencias]
    │
    ├── 📄 Registro_Incidentes_Maestro.xlsx
    │   [Sheets: Todos los incidentes, Por Severidad,
    │    Por Categoría, Por Causa Raíz, Tendencias]
    │
    ├── 📄 Registro_Cambios_Maestro.xlsx
    │   [Sheets: Todos los cambios, Por Tipo,
    │    Tasa de Éxito, Tendencias]
    │
    ├── 📄 Registro_Vulnerabilidades_Maestro.xlsx
    │   [Sheets: Todas las vulns, Aging, Remediación,
    │    Tendencias, Por Severidad]
    │
    ├── 📄 Registro_Mantenimientos_Maestro.xlsx
    │   [Sheets: Todos los mantenimientos, Cumplimiento,
    │    Por Tipo, Tendencias]
    │
    ├── 📄 Registro_Backups_Maestro.xlsx
    │   [Sheets: Todos los backups, Pruebas Restore,
    │    Éxitos/Fallos]
    │
    ├── 📄 Metricas_Satisfaccion_Maestro.xlsx
    │   [Sheets: Todas las encuestas, Por Categoría,
    │    NPS, Tendencias, Comentarios]
    │
    ├── 📄 Metricas_Capacity_Maestro.xlsx
    │   [Sheets: CPU, RAM, Bandwidth, Storage, Sesiones,
    │    Proyecciones, Alertas]
    │
    ├── 📄 Registro_Mejoras_Maestro.xlsx
    │   [Sheets: Todas las propuestas, Estado, ROI,
    │    Aprobadas, Rechazadas, Implementadas]
    │
    ├── 📄 Calculo_Valor_Entregado_Maestro.xlsx
    │   [Sheets: Ahorro Disponibilidad, Ahorro Eficiencia,
    │    Ahorro Seguridad, ROI Acumulado]
    │
    ├── 📄 Inventario_Certificados_Licencias.xlsx
    │   [Sheets: Certificados SSL, Licencias SW,
    │    Vencimientos, Alertas]
    │
    └── 📄 Evaluacion_Churn_Historico.xlsx
        [Sheets: Evaluaciones trimestrales, Score,
         Tendencia, Acciones tomadas]
```

---

## **3. Permisos y Control de Acceso**

### **Matriz de Permisos por Carpeta**

```markdown
## PERMISOS GOOGLE DRIVE

### LEYENDA
- 👁️ = Solo lectura
- ✏️ = Lectura + Edición
- 🔧 = Lectura + Edición + Administración
- ❌ = Sin acceso

### EQUIPO INTERNO DEL PROVEEDOR

| Carpeta | Director | Ger. Cuenta | Ger. Proyecto | Líder Técnico | Ing. Redes | Analista Seg. | Admin. Sys. |
|---------|:--------:|:-----------:|:-------------:|:-------------:|:----------:|:-------------:|:-----------:|
| 00_EMPRESA | 🔧 | ✏️ | ✏️ | ✏️ | 👁️ | 👁️ | 👁️ |
| 00_General/Contrato | 🔧 | ✏️ | 👁️ | 👁️ | ❌ | ❌ | ❌ |
| 00_General/Facturacion | 🔧 | ✏️ | 👁️ | ❌ | ❌ | ❌ | ❌ |
| 01_Fase_1 | 🔧 | ✏️ | ✏️ | ✏️ | ✏️ | ✏️ | ✏️ |
| 02_Fase_2 | 👁️ | 👁️ | ✏️ | ✏️ | ✏️ | ✏️ | ✏️ |
| 03_Fase_3 | 👁️ | 👁️ | ✏️ | ✏️ | ✏️ | ✏️ | ✏️ |
| 04_Fase_4 | 👁️ | ✏️ | ✏️ | ✏️ | 👁️ | 👁️ | ❌ |
| 05_Fase_5 | 🔧 | ✏️ | ✏️ | 👁️ | ❌ | ❌ | ❌ |
| 06_Doc_Técnica_Vigente | 👁️ | 👁️ | 👁️ | ✏️ | ✏️ | ✏️ | ✏️ |
| 07_Metricas_Datos | 👁️ | 👁️ | ✏️ | ✏️ | ✏️ | ✏️ | ✏️ |

### EQUIPO DEL CLIENTE (Compartido vía Google Drive Sharing)

| Carpeta | Sponsor | Ger. TI | Contacto Téc. | Help Desk |
|---------|:-------:|:-------:|:-------------:|:---------:|
| 00_General (parcial) | 👁️ | 👁️ | 👁️ | ❌ |
| 01_Fase_1/05_Actas | 👁️ | 👁️ | 👁️ | ❌ |
| 03_Fase_3/04_Informes_Mensuales | 👁️ | 👁️ | 👁️ | ❌ |
| 03_Fase_3/06_Seguridad (parcial) | 👁️ | 👁️ | 👁️ | ❌ |
| 04_Fase_4/01_QBRs | 👁️ | 👁️ | 👁️ | ❌ |
| 06_Doc_Técnica_Vigente | ❌ | 👁️ | 👁️ | 👁️ |
| Dashboards Grafana (link) | 👁️ | 👁️ | 👁️ | 👁️ |
```

---

## **4. Nomenclatura y Convenciones**

### **Template de Nomenclatura de Archivos**

```markdown
## CONVENCIONES DE NOMENCLATURA

### FORMATO GENERAL
[TIPO]_[DESCRIPCION]_[VERSION/FECHA].[EXTENSION]

### TIPOS DE DOCUMENTO (Prefijos)
- TPL_    → Template / Plantilla
- PROC_   → Procedimiento
- POL_    → Política
- KB_     → Knowledge Base / Base de Conocimiento
- TS_     → Troubleshooting
- CS_     → Cheatsheet
- PB_     → Playbook
- WF_     → Workflow (n8n)

### INFORMES Y REPORTES
Informe_[TIPO]_[YYYY]_[MM]_[MES].pdf
Ejemplo: Informe_SLA_2024_01_Enero.pdf

### INCIDENTES
INC-[YYYY]-[NNNN]
Ejemplo: INC-2024-0042

### CAMBIOS
CHG-[YYYY]-[NNN]
Ejemplo: CHG-2024-015

### MEJORAS
IMP-[YYYY]-[NNN]
Ejemplo: IMP-2024-003

### PROYECTOS DE CLIENTE
OUT-RS-[YYYY]-[NNN]_[NOMBRE_CLIENTE]
Ejemplo: OUT-RS-2024-001_EMPRESA_ACME

### VERSIONES DE DOCUMENTOS
_v[MAJOR].[MINOR]
Ejemplo: Plan_Implementacion_v1.0.pdf
         Plan_Implementacion_v1.1.pdf (revisión menor)
         Plan_Implementacion_v2.0.pdf (cambio mayor)

### DOCUMENTOS FIRMADOS
Agregar _FIRMADO antes de la extensión
Ejemplo: Contrato_Servicios_v1.0_FIRMADO.pdf

### DOCUMENTOS VIGENTES
Agregar _VIGENTE para la versión activa
Ejemplo: AS_BUILT_VIGENTE.pdf

### FECHAS EN NOMBRES DE ARCHIVOS
Formato: YYYY-MM-DD
Ejemplo: Backup_Config_2024-03-15.zip

### REGLAS GENERALES
1. NO usar espacios → usar guión bajo (_)
2. NO usar caracteres especiales (ñ, acentos, &, %, etc.)
3. NO usar nombres genéricos ("Documento1", "Final_v2_FINAL")
4. Mantener nombres descriptivos pero concisos
5. Máximo 80 caracteres en nombre de archivo
6. Todo en español (o idioma acordado)
```

---

## **5. Contenido de las Hojas de Cálculo Maestras**

### **Metricas_SLA_Maestro.xlsx**

```markdown
## ESTRUCTURA DE SHEETS

### Sheet 1: "Disponibilidad"
| Mes | Año | Servicio | SLA_Objetivo | Disponibilidad_Real | Downtime_Min | Incidentes_Downtime | Cumple_SLA |
|-----|-----|----------|:------------:|:-------------------:|:------------:|:-------------------:|:----------:|

### Sheet 2: "Tiempos_Respuesta"
| ID_Incidente | Fecha | Severidad | SLA_Respuesta_Min | Tiempo_Respuesta_Real_Min | Cumple | Responsable |
|-------------|-------|:---------:|:-----------------:|:------------------------:|:------:|-------------|

### Sheet 3: "Tiempos_Resolucion"
| ID_Incidente | Fecha | Severidad | SLA_Resolucion_Min | Tiempo_Resolucion_Real_Min | Cumple | Responsable |
|-------------|-------|:---------:|:------------------:|:--------------------------:|:------:|-------------|

### Sheet 4: "Resumen_Mensual"
| Año | Mes | Disponibilidad_Prom | MTTR_Critico | MTTR_Alto | MTTR_Medio | Cumplimiento_SLA_Pct | Total_Incidentes | Incidentes_Criticos |
|-----|-----|:-------------------:|:------------:|:---------:|:----------:|:-------------------:|:----------------:|:-------------------:|

### Sheet 5: "Dashboard_Data"
[Datos preprocesados para alimentar Grafana vía Google Sheets API]

### Sheet 6: "Configuracion"
| Parametro | Valor |
|-----------|-------|
| SLA_Disponibilidad_Red | 99.9% |
| SLA_Disponibilidad_FW | 99.99% |
| SLA_Respuesta_Critico | 15 min |
| SLA_Respuesta_Alto | 60 min |
| SLA_Resolucion_Critico | 240 min |
| SLA_Resolucion_Alto | 480 min |
| Costo_Hora_Downtime | $XXX |
```

---

### **Registro_Incidentes_Maestro.xlsx**

```markdown
## ESTRUCTURA DE SHEETS

### Sheet 1: "Todos_Incidentes"
| ID | Fecha_Creacion | Fecha_Cierre | Severidad | Categoria | Subcategoria | Descripcion | Servicio_Afectado | Usuarios_Afectados | Reportado_Por | Canal_Reporte | Asignado_A | Tiempo_Respuesta_Min | Tiempo_Resolucion_Min | SLA_Respuesta_Cumplido | SLA_Resolucion_Cumplido | Causa_Raiz | Tipo_Solucion | Recurrente | Post_Mortem | Estado |
|----|:-------------:|:------------|:---------:|:---------:|:----------:|------------|:---------------:|:-----------------:|:----------:|:-----------:|:---------:|:-------------------:|:--------------------:|:---------------------:|:----------------------:|:---------:|:------------:|:--------:|:----------:|:-----:|

### Sheet 2: "Por_Severidad"
[Tabla pivote por severidad y mes]

### Sheet 3: "Por_Categoria"
[Tabla pivote por categoría y mes]

### Sheet 4: "Por_Causa_Raiz"
[Pareto de causas raíz]

### Sheet 5: "Recurrentes"
[Filtro de incidentes recurrentes con análisis]

### Sheet 6: "Tendencias"
[Gráficos de tendencia automáticos]
```

---

### **Registro_Vulnerabilidades_Maestro.xlsx**

```markdown
## ESTRUCTURA DE SHEETS

### Sheet 1: "Todas_Vulnerabilidades"
| ID | CVE | Fecha_Deteccion | Fecha_Remediacion | Severidad | CVSS | Host | IP | Descripcion | Remediacion | Estado | Dias_Abierta | Escaner | Responsable |
|----|-----|:--------------:|:-----------------:|:---------:|:----:|------|----|-----------:|:-----------:|:------:|:-----------:|:-------:|:-----------:|

### Sheet 2: "Aging"
[Análisis de antigüedad de vulnerabilidades abiertas]

### Sheet 3: "Por_Severidad"
[Distribución por severidad]

### Sheet 4: "Por_Host"
[Top hosts más vulnerables]

### Sheet 5: "Tendencias"
[Nuevas vs remediadas por mes]

### Sheet 6: "KPIs"
| KPI | Objetivo | Actual | Cumple |
|-----|:--------:|:------:|:------:|
| Tiempo medio remediación Críticas | ≤7 días | X días | ✅/❌ |
| Tiempo medio remediación Altas | ≤30 días | X días | ✅/❌ |
| % remediadas mensualmente | ≥80% | X% | ✅/❌ |
| Vulns pendientes >90 días | 0 | X | ✅/❌ |
```

---

## **6. Automatización de Creación de Estructura**

### **Script n8n para Crear Estructura Automáticamente**

```
📌 TRIGGER: Nuevo proyecto creado en Asana con tag 
"Nuevo Cliente"

FLUJO EN n8n:

1. [Asana Trigger] → Nuevo proyecto con tag "Nuevo Cliente"

2. [Function] → Extraer datos:
   - Nombre del cliente
   - Código del proyecto
   - Gerente de cuenta asignado

3. [Google Drive API] → Crear estructura completa:

   a. Crear carpeta raíz:
      "[CÓDIGO]_[NOMBRE_CLIENTE]"
      en /01_CLIENTES_ACTIVOS/

   b. Crear todas las subcarpetas según estructura:
      
      POST /drive/v3/files
      {
        "name": "00_GENERAL",
        "mimeType": "application/vnd.google-apps.folder",
        "parents": ["[ID_carpeta_raiz]"]
      }
      
      [Repetir para CADA carpeta y subcarpeta 
       de la estructura completa]

   c. Crear subcarpetas con año actual:
      /03_FASE_3_OPERACION/01_Reportes_Diarios/[YYYY]/
      /03_FASE_3_OPERACION/02_Incidentes/[YYYY]/
      [etc.]

4. [Google Drive API] → Copiar templates maestros:
   
   Desde: /00_EMPRESA/02_Templates_Maestros/
   Hacia: Carpetas correspondientes del cliente
   
   Ejemplo:
   - TPL_Checklist_Documentacion → 01_FASE_1/01_Documentacion/
   - TPL_AS_BUILT → 02_FASE_2/05_Documentacion_Final/
   - TPL_Calendario_Mantenimiento → 03_FASE_3/07_Mantenimiento/

5. [Google Sheets API] → Crear hojas maestras de métricas:
   
   Copiar templates desde /00_EMPRESA/ y personalizar:
   - Metricas_SLA_Maestro.xlsx (configurar SLA del cliente)
   - Registro_Incidentes_Maestro.xlsx
   - Registro_Cambios_Maestro.xlsx
   - Registro_Vulnerabilidades_Maestro.xlsx
   - Registro_Mantenimientos_Maestro.xlsx
   - Registro_Backups_Maestro.xlsx
   - Metricas_Satisfaccion_Maestro.xlsx
   - Metricas_Capacity_Maestro.xlsx
   - Registro_Mejoras_Maestro.xlsx
   - Calculo_Valor_Entregado_Maestro.xlsx
   - Inventario_Certificados_Licencias.xlsx
   - Evaluacion_Churn_Historico.xlsx

6. [Google Docs API] → Crear documentos iniciales:
   
   - _CHANGELOG.md en 06_DOCUMENTACION_TECNICA_VIGENTE
   - README.md en carpeta raíz con índice de contenido

7. [Google Drive API] → Configurar permisos:
   
   a. Carpeta raíz: Acceso al equipo interno completo
   b. Subcarpetas sensibles: Restringir según matriz de permisos
   c. Carpetas compartidas con cliente: Configurar sharing

8. [Slack] → Notificar:
   "📁 ESTRUCTURA DE GOOGLE DRIVE CREADA
    
    Cliente: [Nombre]
    Código: [Código]
    
    📂 Carpeta raíz: [Link]
    📊 Métricas: [Link a carpeta 07_METRICAS]
    📖 Documentación vigente: [Link a carpeta 06]
    
    Se han creado [X] carpetas y [Y] archivos template.
    
    @[gerente_proyecto] verificar estructura y permisos."

9. [Asana] → Agregar links en la descripción del proyecto:
   "📁 Google Drive: [Link carpeta raíz]
    📊 Métricas: [Link]
    📖 Doc Técnica: [Link]"
```

---

## **7. Documento README para la Carpeta del Cliente**

```markdown
# 📁 ÍNDICE DE DOCUMENTACIÓN
## Cliente: [Nombre] | Código: [Código]
## Última actualización: [DD/MM/YYYY]

---

### 🗂️ ESTRUCTURA DE CARPETAS

| Carpeta | Contenido | Responsable Principal |
|---------|-----------|----------------------|
| **00_GENERAL** | Contrato, contactos, plan comunicación, facturación | Gerente de Cuenta |
| **01_FASE_1_ONBOARDING** | Documentación recibida, assessment, diseño, kickoff | Gerente de Proyecto |
| **02_FASE_2_IMPLEMENTACION** | Plan, configuraciones, migración, pruebas, AS-BUILT | Líder Técnico |
| **03_FASE_3_OPERACION** | Reportes, incidentes, cambios, seguridad, mantenimiento | Equipo Operativo |
| **04_FASE_4_MEJORA_CONTINUA** | QBRs, propuestas, capacity planning, valor entregado | Gerente de Cuenta |
| **05_FASE_5_CIERRE_RENOVACION** | Evaluación final, renovación/transición, cierre | Gerente de Cuenta |
| **06_DOC_TECNICA_VIGENTE** | ⭐ Documentación técnica ACTUALIZADA (fuente de verdad) | Líder Técnico |
| **07_METRICAS_Y_DATOS** | Hojas de cálculo maestras para dashboards e informes | Gerente de Proyecto |

### ⚠️ REGLAS IMPORTANTES

1. **06_DOC_TECNICA_VIGENTE** es la FUENTE DE VERDAD
   - Siempre consultar esta carpeta para información actual
   - Actualizar dentro de 24h después de cualquier cambio
   - Registrar cada cambio en _CHANGELOG.md

2. **No duplicar archivos** entre carpetas
   - Usar shortcuts (accesos directos) de Google Drive

3. **Seguir convenciones de nomenclatura**
   - Ver sección de nomenclatura en 00_EMPRESA

4. **Versionado de documentos**
   - Documentos menores: v1.0, v1.1, v1.2
   - Cambios mayores: v2.0
   - NUNCA borrar versiones anteriores

5. **Archivos confidenciales**
   - Marcar con [CONFIDENCIAL] en el nombre
   - Verificar permisos de compartición

### 🔗 LINKS RÁPIDOS
- 📋 Proyecto Asana: [Link]
- 💬 Slack #cliente-general: [Link]
- 💬 Slack #cliente-incidentes: [Link]
- 📊 Dashboard Grafana: [Link]
- 📊 Uptime Kuma: [Link]
- 🔒 Wazuh (SIEM): [Link]
- 📡 Zabbix: [Link]
- 🔑 Vaultwarden: [Link]
- 📖 Wiki (BookStack): [Link]
- 🎫 Tickets (Zammad): [Link]

### 📞 CONTACTOS CLAVE
| Rol | Nombre | Email | Teléfono |
|-----|--------|-------|----------|
| Gerente de Cuenta | | | |
| Líder Técnico | | | |
| Ingeniero de Redes | | | |
| Analista de Seguridad | | | |
| Contacto Técnico (Cliente) | | | |
| Sponsor (Cliente) | | | |

---
**Mantenido por:** [Nombre] | **Última revisión:** [DD/MM/YYYY]
```

---

## **8. Checklist de Verificación de Estructura**

```markdown
# ✅ CHECKLIST DE VERIFICACIÓN DE ESTRUCTURA
## Cliente: [Nombre] | Fecha: [DD/MM/YYYY]

### CARPETAS CREADAS
- [ ] 00_GENERAL (con todas las subcarpetas)
- [ ] 01_FASE_1_ONBOARDING (con todas las subcarpetas)
- [ ] 02_FASE_2_IMPLEMENTACION (con todas las subcarpetas)
- [ ] 03_FASE_3_OPERACION (con todas las subcarpetas)
- [ ] 04_FASE_4_MEJORA_CONTINUA (con todas las subcarpetas)
- [ ] 05_FASE_5_CIERRE_RENOVACION (con todas las subcarpetas)
- [ ] 06_DOCUMENTACION_TECNICA_VIGENTE (con subcarpetas)
- [ ] 07_METRICAS_Y_DATOS

### TEMPLATES COPIADOS
- [ ] Templates de Fase 1 en carpeta correspondiente
- [ ] Templates de Fase 2 en carpeta correspondiente
- [ ] Templates de Fase 3 en carpeta correspondiente
- [ ] Templates de Fase 4 en carpeta correspondiente
- [ ] Templates de Fase 5 en carpeta correspondiente

### HOJAS DE CÁLCULO MAESTRAS CREADAS
- [ ] Metricas_SLA_Maestro.xlsx
- [ ] Registro_Incidentes_Maestro.xlsx
- [ ] Registro_Cambios_Maestro.xlsx
- [ ] Registro_Vulnerabilidades_Maestro.xlsx
- [ ] Registro_Mantenimientos_Maestro.xlsx
- [ ] Registro_Backups_Maestro.xlsx
- [ ] Metricas_Satisfaccion_Maestro.xlsx
- [ ] Metricas_Capacity_Maestro.xlsx
- [ ] Registro_Mejoras_Maestro.xlsx
- [ ] Calculo_Valor_Entregado_Maestro.xlsx
- [ ] Inventario_Certificados_Licencias.xlsx
- [ ] Evaluacion_Churn_Historico.xlsx

### PERMISOS CONFIGURADOS
- [ ] Equipo interno con permisos según matriz
- [ ] Carpetas sensibles (contrato, facturación) restringidas
- [ ] Carpetas compartidas con cliente configuradas
- [ ] Links de compartición verificados

### DOCUMENTOS INICIALES
- [ ] README.md creado en carpeta raíz
- [ ] _CHANGELOG.md creado en 06_DOC_TECNICA_VIGENTE
- [ ] SLA configurados en Metricas_SLA_Maestro.xlsx

### INTEGRACIONES
- [ ] Links agregados en proyecto de Asana
- [ ] Links agregados en canal de Slack
- [ ] Google Sheets conectados a Grafana (si aplica)
- [ ] Google Sheets conectados a n8n workflows

---
**Verificado por:** [Nombre] | **Fecha:** [DD/MM/YYYY]
```