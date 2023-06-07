---
layout: page
title: Modulo IV
permalink: moduloIV
---
# MODULO IV

## 🌀 PROCESO - MODELO ESPIRAL

## 💬 COMUNICACIÓN

## 📋 REQUISITOS

### ❗️ CONCEPCIÓN
El cliente necesita que exista un control de personal, buses, rutas y aspectos económicos de una terminal de buses.

### ❓ INDAGACIÓN
Se tomará en cuenta los siguientes requisitos:

- Facilidad de uso para el personal de administración.
- Interfaz amigable para el usuario.
- Capacidad para administrar y programar horarios de los buses.
- Registro y seguimiento de los tiempos de llegada y salida de los buses.
- Registro y seguimiento de los conductores de los buses y sus horarios de trabajo.
- Administración de reservas y compras de boletos.
- Capacidad para procesar pagos electrónicos.
- Notificación de cancelaciones de viajes o cambios de horarios a los clientes.
- Registro de información de los clientes y sus boletos.
- Información en tiempo real sobre la disponibilidad de asientos.
- Capacidad para imprimir boletos y facturas.
- Capacidad de reprogramación y/o cancelación de boletos.
- Generación de reportes de ventas y estadísticas de uso.
- Capacidad para gestionar múltiples empresas de autobuses.
- Seguimiento y comunicación con los conductores de los buses.
- Control de inventario de boletos y materiales.
- Capacidad para enviar mensajes de texto o correo electrónico a los clientes.
- Sincronización con sistemas de reservas en línea.
- Capacidad de categorizar los boletos por comodidad de viaje.
- Opciones de personalización para la presentación de la información.
- Alertas de sobreventa de boletos.
- Capacidad para administrar paquetes y envíos.
- Registro y seguimiento de paquetes y envíos.
- Capacidad para administrar precios de boletos.
- Capacidad para escanear códigos QR y generar códigos QR de boletos.
- Registro de información de pasajeros frecuentes.
- Capacidad para mostrar información de llegadas y salidas de buses en la terminal.
- Capacidades multilingües para dar soporte a clientes internacionales.
- Soporte técnico confiable y rápido.
- Capacidad de asignación de plataformas de embarque y desembarque para los buses.

### 📝 ELABORACIÓN
Procedemos a la depuración de requisitos y analizamos dentro del contexto que es un Software para una terminal de buses.

- Capacidad para administrar y programar horarios de los buses.
- Registro y seguimiento de los tiempos de llegada y salida de los buses.
- Administración de reservas y compras de boletos.
- Capacidad para procesar pagos electrónicos.
- Notificación de cancelaciones de viajes o cambios de horarios a los clientes.
- Registro de información de los clientes y sus boletos.
- Seguimiento y comunicación con los conductores de los buses.
- Control de inventario de boletos y materiales.
- Sincronización con sistemas de reservas en línea.
- Capacidades multilingües para dar soporte a clientes internacionales.
- Soporte técnico confiable y rápido.
- Capacidad de asignación de plataformas de embarque y desembarque para los buses.

### 💼 NEGOCIACIÓN
Se ve la conformidad del cliente en cuanto a los requisitos llegando a estar de

 acuerdo por ambas partes. Procedemos a la jerarquización según el nivel de importancia para el producto final.

| NIVEL | PRODUCTO          | DESCRIPCIÓN                                                         |
|-------|-------------------|---------------------------------------------------------------------|
| 1     | 🎟️ BOLETOS        | Consta de los requisitos referidos a la relación con los clientes, entrada y salida de información. De mayor prioridad.                            |
| 2     | 🚌 BUSES          | Trata a la información de los buses, conductores y demás empleados relacionados a los buses, es de prioridad media. |
| 3     | 🔧 SOPORTE TÉCNICO | Contiene los datos en cuanto soporte técnico, trabajadores e información dirigida al mantenimiento de operaciones. De prioridad media.                                      |

> Agrupación y Jerarquización de los requisitos.

#### 🔝 ORDEN DE LOS REQUISITOS SEGÚN SU PRIORIDAD

- 🎟️ Administración de reservas y compras de boletos.
- 🎟️ Capacidad para procesar pagos electrónicos.
- 🎟️ Notificación de cancelaciones de viajes o cambios de horarios a los clientes.
- 🎟️ Registro de información de los clientes y sus boletos.
- 🎟️ Sincronización con sistemas de reservas en línea.
- 🎟️ Control de inventario de boletos y materiales.
- 🚌 Capacidad para administrar y programar horarios de los buses.
- 🚌 Registro y seguimiento de los tiempos de llegada y salida de los buses.
- 🚌 Capacidad de asignación de plataformas de embarque y desembarque para los buses.
- 🚌 Seguimiento y comunicación con los conductores de los buses.
- 🔧 Capacidades multilingües para dar soporte a clientes internacionales.
- 🔧 Soporte técnico confiable y rápido.

## 📦 ENTREGAS DE PRODUCTOS O PROTOTIPOS

El cliente acordó recibir el software en tres entregas de niveles progresivos. La primera entrega tiene prioridad, ya que es el inicio del sistema y resuelve la vulnerabilidad de los datos de los empleados.

## 💰 COSTO DEL SOFTWARE

Se estimó el tamaño del software utilizando el método COSMIC, que utiliza los Puntos de Función Cosmic para estimar el tamaño del software basándose en los requisitos funcionales del proyecto. Al tener el tamaño estimado se puede utilizar este dato para estimar el costo del software como se muestra a continuación:


| Evaluación de Puntos Función Cosmic (PFC) | |
|---|---|
| Procesos Funcionales | PFC |
| Ingreso al sistema de control de personal de buses | 3 |
| Registro de boleteros | 3 |
| Asignación de Área de trabajo y cargo | 2 |
| Asignación de Turno y Horario de buses | 2 |
| Control de Asistencia, horario de entrada y salida | 4 |
| Listado de empleados en cada área de trabajo | 4 |
| Listado de turnos y horarios de cada empleado | 4 |
| Carga horaria y cálculo de sueldo | 9 |
| Asignación de Permisos | 4 |
| Reporte de Faltas y Permisos | 5 |
| Reporte de Retrasos | 5 |
| Reporte Diario de Asistencia | 4 |
| Registro de Horas extra | 5 |
| Evaluación Diaria | 5 |
| Registro de observaciones y quejas | 3 |
| Historial de Rendimiento de Soporte Tecnico | 5 |
| Reporte Mensual/Semanal de la Carga Horaria | 5 |
| **TOTAL** | **80** |

>Evaluación de puntos de función COSMIC (PCF)
Ahora tenemos el tamaño del software utilizando procesos funcionales, ahora se calcula el costo utilizando un costo medio por cada PFC.

|-----------------|-------------------|
| COSTO MEDIO POR PFC (EN Bs) | 412,5 |
| TOTAL PUNTOS FUNCIÓN COSMIC (PFC) | 80 |
| TOTAL | Bs. 33.000,00 |

>Evaluación de costo COSMIC

A continuación se presenta el texto convertido a Markdown con emojis relacionados en cada título:
## 📝 ESPECIFICACIÓN

Al obtener los requisitos se recibe la dirección hacia el producto final, a continuación tomamos los requisitos y los mostramos con la ayuda de flujogramas que consiste en un diagrama que utilizamos para ilustrar el proceso de los productos deseados.

- Administración de reservas y compras de boletos.
- Capacidad para procesar pagos electrónicos.
- Notificación de cancelaciones de viajes o cambios de horarios a los clientes.
- Registro de información de los clientes y sus boletos.
- Sincronización con sistemas de reservas en línea.
- Control de inventario de boletos y materiales.

## ✅ VALIDACIÓN

Los requisitos presentados en la primera iteración se han analizado, y negociado con el cliente (gerente de la empresa), y se ha concluido que cada requisito está validado por ambas partes tanto como equipo de trabajo de software como el cliente, dejando en claro que no hay ambigüedades ni inconsistencias, dando a lugar a la validación de los requisitos presentados, así mismo se procederá a firmar esta sección a forma de conformidad con la primera iteración presentada a la fecha. 

## 📋 ADMINISTRACIÓN DE LOS REQUISITOS

Los requisitos han sido observados anteriormente y se manejan bajo la organización. Siendo enfáticos en la jerarquización que se realizó en la etapa de negociación manejamos los requisitos por niveles y los resolvemos bajo un calendario programado y observamos que se cumplió cada etapa de la comunicación con buenos resultados.	

## 📅 PLANEACIÓN 

En cuanto a una buena apreciación del funcionamiento del Software de una terminal de buses, manejamos una agenda con la que realizamos y evaluamos el sistema para la primera parte

## 🖼️ MODELADO 


## 💻 CONSTRUCCIÓN - LENGUAJE
El lenguaje de programación que se utilizara es “PYTHON” y para el manejo de la base de datos se utilizara la herramienta de “SQL”.
Python es un lenguaje de programación multipropósito, la estructura del código en este lenguaje es muy práctico para el proyecto en cuestión, ayuda bastante en la estructuración de datos ya que el lenguaje permite hacer los procesos de manera muy directa sin necesidad de ahondar en excesivas líneas de código, además que existe la posibilidad de enlazar este trabajo con muchos otros lenguajes y herramientas, ya que se cuenta con un soporte que da compatibilidad con muchas funcionalidades, herramientas y lenguajes.

## 💻🔧 HARDWARE Y SOFTWARE 

El equipo informático de la terminal de buses debe tener las siguientes características para el buen funcionamiento del producto software:

Espero que esto te sea útil. ¡Si tienes alguna otra pregunta, no dudes en preguntar!

A continuación se muestra el texto convertido a Markdown con un emoji relacionado en cada título:

## 🚀 DESPLIEGUE
Llegamos a la etapa de la primera entrega, realizamos una evaluación con el cliente que en este caso es el Gerente de la terminal de buses X,  que a su vez tenemos la ventaja de que también es el primer usuario del producto, y como segundo usuario tenemos al Administrador General de operaciones. Para los cuales se presentó un manual de usuario donde se especifican los requisitos resueltos el cual en su conjunto denominamos primera entrega.