# Proyecto Bases de Datos Taxis

## Contexto

Este proyecto forma parte de una simulación realista para evaluar y mejorar una aplicación de taxis en la ciudad de Chicago. La empresa responsable del sistema ha recibido reportes de problemas operativos, como insuficiencia de taxis disponibles y discrepancias en los datos de viajes y ganancias.  

Para contribuir a la resolución de estos problemas, se nos ha encomendado analizar dos áreas clave:  
- La información de logs del servidor para identificar solicitudes y errores específicos en un periodo crítico.  
- La base de datos que almacena información sobre viajes, taxis, compañías y condiciones meteorológicas para detectar posibles errores y obtener datos relevantes para la toma de decisiones.

El objetivo es realizar un análisis detallado que permita al equipo de desarrollo corregir fallos y mejorar la fiabilidad del sistema.

## Descripción del proyecto

Este proyecto consta de dos partes principales:  

1. **Análisis y extracción de logs en servidor remoto**  
   - Se trabajó con archivos de logs ubicados en un servidor remoto para identificar solicitudes específicas de una IP, y para clasificar errores HTTP en archivos separados.  
   - Se usaron comandos de consola para filtrar, guardar y organizar los logs según instrucciones.

2. **Consultas y análisis en base de datos PostgreSQL de viajes en taxi en Chicago**  
   - Se realizaron consultas SQL para analizar información relevante sobre la cantidad de taxis disponibles, distribución por compañía, y análisis del clima relacionado con viajes.  
   - Se detectaron posibles inconsistencias y se entregó información útil para mejorar el sistema.

## Objetivos

- Practicar la gestión y análisis de logs en sistemas Unix/Linux.  
- Aplicar consultas avanzadas SQL con funciones agregadas, operadores CASE, joins y filtrados específicos.  
- Generar información crítica para la toma de decisiones operativas en una aplicación de taxis.  

## Contenido del repositorio

- Scripts y comandos usados para extracción y clasificación de logs.  
- Consultas SQL utilizadas para responder las preguntas planteadas.  
- Resultados y archivos generados con la información requerida.

## Comandos usados en los logs

Se utilizaron comandos para:  
- Buscar solicitudes que comienzan con la IP `233.201`.  
- Filtrar logs por fechas y tipos de error (400, 500).  
- Crear directorios y organizar archivos de logs separados según el tipo de error.

## Consultas SQL realizadas

Las consultas principales incluyeron:  

- Conteo total de taxis en la base de datos.  
- Listado de compañías con menos de 100 automóviles.  
- Clasificación de condiciones meteorológicas y agrupación por estados “Bad” o “Good”.  
- Conteo de viajes por compañía para fechas específicas.

## Resultados

Los resultados obtenidos permitieron identificar:  

- La cantidad real de taxis disponibles y las compañías con menor presencia.  
- Horas con condiciones climáticas adversas que pueden afectar la operación.  
- Posibles discrepancias en los datos de viajes reportados.

## Conclusiones

Este proyecto permitió profundizar en el manejo de datos de diferentes fuentes: tanto registros de sistema (logs) como bases de datos relacionales.  

Se identificaron áreas donde la información puede presentar errores o inconsistencias, lo cual es crítico para asegurar un buen funcionamiento del sistema de taxis.  

Además, trabajar con la base de datos PostgreSQL y realizar consultas específicas ayudó a entender mejor la estructura de los datos y cómo extraer información relevante para el negocio.  

En resumen, la experiencia de analizar logs y realizar consultas detalladas es fundamental para mantener la calidad y confiabilidad de aplicaciones complejas como esta.

