# Ruta
Rutas de cursos que vi en internet y se usaran como base para el aprendizaje de GO en este repositorio
--------------------------------------------------------------------------------
## Temario y recursos del Curso de Golang:

### Hola mundo en Go

Introducción al Curso de Golang

¿Qué es, por qué y quienes utilizan Go?

Instalar Go en Linux

Instalar Go en Mac

Instalar Go en Windows

Nuestras primeras líneas de código con Go


### Variables, funciones y documentación

Variables, constantes y zero values

Operadores aritméticos

Tipos de datos primitivos

Paquete fmt: algo más que imprimir en consola

Uso de funciones

Go doc: La forma de ver documentación


### Estructuras de control de flujo y condicionales

El poder de los ciclos en Golang: for, for while y for forever

Operadores lógicos y de comparación

El condicional if

Múltiple condiciones anidadas con Switch

El uso de los keywords defer, break y continue


### Estructuras de datos básicas

Arrays y Slices

Recorrido de Slices con Range

Llave valor con Maps

Structs: La forma de hacer clases en Go

Modificadores de acceso en funciones y Structs


### Métodos e interfaces

Structs y Punteros

Stringers: personalizar el output de Structs

Interfaces y listas de interfaces


### Concurrencia y Channels

¿Qué es la concurrencia?

Primer contacto con las Goroutines

Channels: La forma de organizar las goroutines

Range, Close y Select en channels


### Manejo de paquetes y Go Modules

Go get: El manejador de paquetes

Go modules: Ir más allá del GoPath con Echo

Modificando módulos con Go


### Bonus

Cheat Sheet Go

Librerías para desarrollo web con Go

Data Science con Go

---------------------------------------------------------------------------------------------------------------------

## Temario y recursos del Curso de Go Intermedio

### Introducción

Características esenciales de Go

Qué aprenderás y qué necesitas saber

Repaso general: variables, condicionales, slices y map

Repaso general: GoRoutines y apuntadores


### Programación orientada a objetos

¿Es Go orientado a objetos?

Structs vs. clases

Métodos y funciones

Constructores

Herencia

Interfaces

Aplicando interfaces con Abstract Factory

Implementación final de Abstract Factory

Funciones anónimas

Funciones variadicas y retornos con nombre


### Go Modules

Cómo utilizar los Go modules

Creando nuestro módulo


### Testing

Testing

Code coverage

Profiling

Testing usando Mocks

Implementando Mocks


### Concurrencia

Unbuffered channels y buffered channels

Waitgroup

Buffered channels como semáforos

Definiendo channels de lectura y escritura

Worker pools

Multiplexación con Select y Case


### Proyecto: servidor con worker pools

Definiendo workers, jobs y dispatchers

Creando web server para procesar jobs


---------------------------------------------------------------------------------------------------------------------------------------------------------------
## Temario y recursos del Curso de Go Avanzado

### Introducción

Cómo aprender Go avanzado: concurrencia, patrones de diseño y net

### Concurrencia

Race condition: el problema de depositar y retirar

Sync Mutex: Lock y Unlock

Mutex de lectura y escritura


Sistema de caché sin concurrencia

Sistema de caché con concurrencia

Reutilización de computación intensiva


### Patrones de diseño

¿Qué son los patrones de diseño?

Factory

Singleton

Adapter

Observer

Strategy


### Net

Escaneador de puertos sin concurrencia

Escaneador de puertos con concurrencia

Netcat

Servidor de chat en Go con net

Terminando el chat

### Conclusión

Resumen del curso de Go avanzado

-----------------------------------------------------------------------------------------------------------------------------------------------------
## Temario y recursos del Curso de Go Avanzado: REST y WebSockets

### Introducción

Introducción al curso

¿Qué estaremos construyendo?

HTTP y REST

CRUD


### REST

Inicialización de módulo e instalación de dependencias

Struct Server

Nuestro primer endpoint

Definiendo el modelo de usuarios

Patrón repository

Registro de usuarios

Implementando el registro

Probando los registros

Autenticación de usuarios

Probando el login

Middleware de validación de autenticación

Implementando el middleware

Modelo Posts

CRUD para Posts

Paginación para Posts


### WebSockets

Websockets

Upgrader y Endpoint para Websocket

Struct de Hub para conexiones

Implementando el Broadcast


### Cierre

Ejemplo de implementación frontend

Docker file para producción

Siguientes pasos y mejoras

----------------------------------------------------------------------------------------------------------------------------------------------

## Temario y recursos del Curso de Go Avanzado: Protobuffers y gRPC

### Introducción

Introducción al curso

¿Qué construiremos?

ProtoBuffers

Creando y compilando nuestro primer Proto

Arquitectura de microservicios

### gRPC

RPC y gRPC

ProtoBuffers vs. JSON

Definición del Servicio Students

Create y Read para Students

Implementando GetStudent y SetStudent

Testing de GetStudent y SetStudent

Definición del Servicio Test

Create y Read para Test

Implementando streaming del lado del cliente

Definiendo servicios de streaming del lado del servidor

Implementando EnrollStudents y GetStudentsPer Test

Implementando Streaming Bidireccional

Probando Streaming Bidireccional

Implementación de clientes a nivel de código: Unary y ClientStreaming

Implementación de clientes a nivel de código: ServerStreaming y BidirectionalStreaming


### Conclusión

Limitaciones de gRPC y creación de Proxy REST

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Temario y recursos del Curso de Arquitectura de Eventos y CQRS con Go

### Introducción

¿Qué estaremos construyendo en el curso?

Microservicios y arquitecturas basadas en eventos

CQRS: Command Query Responsibility Segregation


### Modelos y repositorios

Creando modelos y repositorios

Implementando repositorio


### Mensajes y eventos

Agregando NATS

Definiendo mensajes y eventos

Implementado interfaces para mensajes y eventos

Reaccionando a eventos


### Indexación mediante Elastic Search

Agregando indexación

Implementando indexación mediante Elastic Search

Búsqueda mediante Elastic Search

Serialización de resultados de Elastic Search

### Feed Service

Creando Feed Service

Creando Handlers para Feed Service

Agregando Feed Service como Command


### Query Service y Pusher

Creando Query Service

Creando Handlers para Query Service

Creando el Servicio Pusher


### Últimos pasos

Agregando NGINX

Probando nuestra aplicación de Feeds

Conclusiones

