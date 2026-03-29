# Sistema de Gestión de Red Sísmica

Proyecto desarrollado en equipo en el marco de la materia Diseño de Sistemas de Información (UTN).

## Descripción

Este sistema simula la gestión y procesamiento de información proveniente de una red sísmica. Permite registrar, modelar y analizar datos relacionados con eventos sísmicos, estaciones de monitoreo y su comportamiento.

El proyecto representa un entorno real de trabajo, aplicando conceptos de diseño de sistemas, arquitectura en capas y desarrollo backend.

## Funcionalidades

- Gestión de estaciones sísmicas
- Registro y procesamiento de eventos sísmicos
- Persistencia de datos en base de datos
- Separación por capas (presentación, lógica de negocio, persistencia)
- Inicialización de base de datos

## Tecnologías utilizadas

- Java
- Spring Boot
- Maven
- MySQL
- JUnit (tests)
- Git (control de versiones)

## Arquitectura

El proyecto sigue una estructura por capas:

- **presentation** → interacción con el usuario
- **gestores** → lógica de negocio
- **domain** → entidades del sistema
- **persistence** → acceso a datos
- **config** → configuración e inicialización

## Mi participación

- Desarrollo de funcionalidades del sistema
- Implementación de lógica de negocio
- Trabajo sobre la estructura del sistema
- Uso de Git para trabajo colaborativo

## Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Configurar la base de datos MySQL
3. Ejecutar el proyecto con Maven:

```bash
mvn spring-boot:run
