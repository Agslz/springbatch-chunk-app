# Esta es una serie de proyecto enfocados a Spring Batch, en este repositorio se muestra en enfoque en Chunks pero tambien se encuentra disponible el enfoque en Tasklets [aquí](https://github.com/Agslz/springbatch-tasklet-app)

# Spring Batch con enfoque de chunks

Este repositorio contiene un proyecto desarrollado utilizando Spring Batch con el enfoque de chunks. A través de este repositorio, podrás construir una aplicación que procesa datos en lotes de manera eficiente.

## Contenido del proyecto

- **Introducción**: Se ofrece una visión general del tutorial y del enfoque de chunks en Spring Batch.

- **Crear nuestro Entity**: Se crea la entidad necesaria para representar los datos que serán procesados.

- **Crear nuestro DAO**: Se implementa el acceso a datos para interactuar con la base de datos.

- **Crear nuestro SERVICE**: Se desarrolla la lógica de negocio necesaria para el procesamiento de los datos.

- **Configurar application.properties**: Se configuran las propiedades de la aplicación, como la configuración de la base de datos.

- **Configurar nuestra cadena de conexión a la BD**: Se establece la conexión a la base de datos para la aplicación.

- **Crear nuestro ItemReader**: Se implementa el lector de items para leer los datos de entrada.

- **Configura el LineMapper**: Se configura el mapeo de líneas para transformar los datos leídos en objetos.

- **Crear nuestro ItemWriter**: Se desarrolla el escritor de items para escribir los datos procesados en la base de datos.

- **Crear nuestro Job**: Se crea el trabajo que orquesta el procesamiento de datos en lotes.

- **Crear la base de datos**: Se establece la estructura de la base de datos necesaria para la aplicación.

- **Levantar la aplicación con CommandLineRunner**: Se muestra cómo iniciar la aplicación utilizando CommandLineRunner.

- **Configurar los hilos que serán administrados por Spring Batch**: Se configuran los hilos para el procesamiento en paralelo de los datos.

- **Crear nuestro ItemProcessor**: Se implementa el procesador de items para aplicar transformaciones o validaciones a los datos.
