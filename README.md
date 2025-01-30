# Diseño y arquitectura de dominio

## Estructura del Proyecto
- `src/main`: Contiene el código fuente del proyecto.
- `cml/`: Contiene los archivos CML (Context Mapper Language) que definen los contextos acotados y los subdominios.
  - `as-is.cml`: Describe el estado actual del sistema. Contiene el dominio, los subdominios y contextos acotados.
  - `to-be.cml`: Describe el estado futuro deseado del sistema. Contiene el dominios, los subdominios y contextos acotados.
- `src-gen/`: Contiene las imágenes generadas a partir de los archivos CML.
  - `as-is_ContextMap.png`: Imagen generada del estado actual del sistema.
  - `to-be_ContextMap.png`: Imagen generada del estado futuro deseado del sistema.
- `event-storming/`: Contiene las imágenes generadas del Event Storming.
  - `event-storming_as-is.png`: Imagen del Event Storming del estado actual.
  - `event-storming_to-be.png`: Imagen del Event Storming del futuro deseado del sistema.

## Generación de Imágenes de Context Mapper
Para generar las imágenes de Context Mapper a partir de los archivos CML, sigue estos pasos:
1. Abre el archivo CML correspondiente (`as-is.cml` o `to-be.cml`) en el editor.
2. Haz clic derecho en el archivo abierto y selecciona la opción **Generate Graphical Context Map**.
3. Las imágenes generadas se guardarán en el directorio `src-gen/`.