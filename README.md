# Lector/Extracción de contenido PDF con n8n

Automatización de un proceso de gestión de facturas mediante **n8n**, integrando Gmail, procesamiento con OpenAI y Google Drive.

El flujo permite recibir facturas en formato PDF por correo electrónico, extraer y estructurar la información relevante del documento, validar los datos obtenidos y almacenar automáticamente los archivos procesados.

## Objetivo

Reducir las tareas manuales asociadas al procesamiento de facturas, automatizando la extracción, validación y organización de la información.

### Proceso manual

```text
Recibir factura
      ↓
Descargar PDF
      ↓
Revisar información
      ↓
Extraer datos manualmente
      ↓
Validar información
      ↓
Guardar archivo
