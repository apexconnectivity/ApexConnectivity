## Hi there 👋

<!--
**apexconnectivity/ApexConnectivity** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Apex Connectivity Framework

Repositorio privado del framework interno de gestión para servicios de outsourcing de redes y seguridad de **Apex Connectivity**.

## 🎯 Objetivo

Estandarizar cómo Apex Connectivity diseña, ejecuta y opera proyectos y servicios gestionados de redes/seguridad, desde plantillas maestras hasta automatización con n8n y Antigravity.[cite:36]

## 🧱 Estructura del framework

Este repositorio refleja la lógica de carpetas de Google Drive y los documentos maestros en formato Markdown.

- `00_EMPRESA/`
  - `01_Identidad_Corporativa/`  
    Lineamientos de marca, identidad visual y comunicación.
  - `02_Templates_Maestros/`  
    Plantillas TPL_ por fases:
    - `Fase_1_Onboarding/`
    - `Fase_2_Implementacion/`
    - `Fase_3_Operacion/`
    - `Fase_4_Mejora_Continua/`
    - `Fase_5_Cierre_Renovacion/`
    - `Generales/` (propuestas, contratos, actas, etc.).
  - `03_Procesos_y_Procedimientos/`  
    Documentos PROC_, POL_, PB_ que definen el “cómo se hace” en la operación diaria.
  - `04_Base_de_Conocimiento_Interna/`  
    KB_, TS_ y CS_ organizados por tecnología (firewalls, switches, SIEM, monitoreo, automatización n8n, etc.).[cite:39]
  - `05_Herramientas_y_Scripts/`  
    Scripts operativos, configuraciones base y diagramas estándar.
  - `06_Capacitacion_Interna/`  
    Material de onboarding, certificaciones y sesiones internas.

> Las carpetas de clientes (01_CLIENTES_ACTIVOS, 02_CLIENTES_ARCHIVO), prospectos y marketing viven en Google Drive y NO se versionan completas aquí; solo se versionan plantillas y procesos.[cite:39]

## 📑 Convenciones de nombres

Todos los archivos siguen estas reglas:[cite:39]

- Prefijos por tipo:
  - `TPL_` Plantillas
  - `PROC_` Procedimientos
  - `POL_` Políticas
  - `KB_` Base de conocimiento
  - `TS_` Troubleshooting
  - `CS_` Cheatsheet
  - `PB_` Playbook
  - `WF_` Workflows (n8n)
- Proyectos cliente: `OUT-RS-[YYYY]-[NNN]_[NOMBRE_CLIENTE]`  
  Ejemplo: `OUT-RS-2024-001_EMPRESA_ACME`
- Versionado: sufijo `_vMAJOR.MINOR` (ej. `_v1.0`, `_v1.1`)  
- Documentos firmados: `_FIRMADO`  
- Documentos vigentes: `_VIGENTE`  
- Fechas: `YYYY-MM-DD`  
- Sin espacios ni caracteres especiales, máximo 80 caracteres.

## 🔐 Alcance y uso

- Uso interno de Apex Connectivity para estandarizar proyectos y servicios gestionados.
- El repo puede integrarse con:
  - n8n (NAS Synology) vía n8n-mcp.
  - Antigravity como asistente para generar y actualizar documentos y workflows WF_.[web:14][web:80]

> Licencia: uso interno. En caso de liberarse públicamente, se añadirá una licencia (por ejemplo MIT) en este mismo repositorio.[web:28]
