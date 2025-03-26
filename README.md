# Tablas en formato Excel/CSV que hay que desglosar en campos importantes según las peticiones que se vayan a hacer a la IA.
## Carpeta "excels"
Contiene las tablas de Excel, que contienen una cantidad grande de datos, y que hay que descartar los campos importantes.
## Carpeta "csv"
Contiene las tablas de Excel en contenido legible (csv) para que la IA de DeepSeek pueda sacar los campos importantes.
## Carpeta "tablas_importantes_IA"
Archivos JSON de cada tabla que contiene el nombre de los campos importantes según ha considerado DeepSeek. Estan filtrados en 2 objetos, "all_fields" (campos que DeepSeek ve importantes mantener, sin importar las preguntas que se encuentra en el archivo "Desglose de Tablas.docx") y "important_fields" (campos que DeepSeek ve importantes mantener SOLO con las preguntas que se encuentra en el archivo "Desglose de Tablas.docx").

## Archivo "Desglose de Tablas.docx"
Archivo que contiene una pequeña descripcion de que contiene cada tabla, según la empresa (texto negro) y ChatGPT (texto rojo). Tambien contiene preguntas/consultas que se pueden hacer a la IA de la empresa (estas preguntas sirven para ver que campos pueden ser importantes).

## Archivo "Explicacion_Cliente.txt" (NO IMPORTANTE)
Archivo de texto que contiene comentarios del cliente sobre una tabla

## Archivo "tabla variedades con codigos_revamped.xlsx"
Tabla de Excel que contiene datos similares a "Gsigvaried.xlsx". Este tiene marcado en colores los valores que hay que descartar, y con que valores sustituirlos.


#### La version de DeepSeek que se usa es *DeepSeek-V3*
