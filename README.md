# Optimización de Filas y Tiempos

Proyecto de simulación y análisis de teoría de colas aplicado al restaurante **Zarzamora**.

El objetivo es analizar el comportamiento de las filas y los tiempos de espera durante horas de alta demanda, utilizando datos observados y un modelo de colas M/M/s.

## Objetivo

Evaluar cómo cambia el desempeño del restaurante al variar el número de servidores o puntos de atención.

El proyecto busca identificar una configuración que permita:

- Reducir tiempos de espera.
- Mejorar la satisfacción de los clientes.
- Disminuir la congestión.
- Mantener una utilización adecuada del sistema.

## Datos analizados

El proyecto utiliza dos franjas de observación del restaurante.

Para cada sección se registran datos como:

- Hora.
- Número de personas que entran.
- Número de personas que salen.
- Total de movimientos.
- Duración observada.

A partir de estos datos se calculan las tasas principales del sistema.

## Modelo de teoría de colas

Se utiliza un modelo:

```text
M/M/s
