# PetSalud

<p align="center">
  <strong>Aplicación móvil orientada a la gestión y cuidado de mascotas</strong>
</p>

<p align="center">
  Proyecto Android enfocado en facilitar la gestión de información veterinaria y promover un cuidado más organizado y consciente de las mascotas.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-Mobile-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Gradle-Kotlin%20DSL-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle"/>
  <img src="https://img.shields.io/badge/Version-1.2-blue?style=flat-square" alt="Version"/>
</p>

---

## Descripción

**PetSalud v1.2** es una aplicación móvil desarrollada con el objetivo de mejorar la gestión relacionada con la salud y el cuidado de mascotas.

El proyecto busca aprovechar las ventajas de las aplicaciones móviles y los servicios de almacenamiento digital para centralizar información relacionada con las mascotas y brindar una experiencia sencilla para sus propietarios.

PetSalud está orientado a facilitar el seguimiento de información veterinaria y contribuir a un cuidado más organizado y consciente de los animales.

---

## Objetivo

Desarrollar una solución móvil que permita gestionar de manera organizada información relacionada con las mascotas y su cuidado, proporcionando al usuario una herramienta accesible desde dispositivos Android.

Entre los principales objetivos del proyecto se encuentran:

* Centralizar información relacionada con las mascotas.
* Facilitar la gestión de información veterinaria.
* Mejorar la organización del cuidado de los animales.
* Proporcionar una experiencia accesible desde dispositivos móviles.
* Aprovechar herramientas de almacenamiento digital para mantener la información disponible.

---

## Tecnologías

El repositorio corresponde a un proyecto Android configurado mediante **Gradle con Kotlin DSL**.

| Tecnología     | Uso                                              |
| -------------- | ------------------------------------------------ |
| Android        | Plataforma de ejecución de la aplicación         |
| Gradle         | Sistema de construcción y gestión del proyecto   |
| Kotlin DSL     | Configuración de Gradle mediante archivos `.kts` |
| Android Studio | Entorno recomendado para desarrollo y ejecución  |
| Git            | Control de versiones                             |
| GitHub         | Almacenamiento y gestión del repositorio         |

---

## Estructura del proyecto

Actualmente el repositorio contiene principalmente los archivos de configuración del proyecto Android:

```text
PetSalud2/
│
├── .idea/
│
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── settings.gradle.kts
```

El proyecto está configurado para utilizar un módulo denominado:

```text
app
```

mediante:

```kotlin
include(":app")
```

> El directorio `app/` se encuentra actualmente excluido por el archivo `.gitignore`, por lo que el código fuente de la aplicación no está disponible en esta versión pública del repositorio.

---

## Configuración del proyecto

El proyecto utiliza los repositorios oficiales necesarios para el ecosistema Android:

```text
Google Maven Repository
Maven Central
Gradle Plugin Portal
```

Esto permite administrar las dependencias, plugins y componentes utilizados durante la construcción de la aplicación.

---

## Requisitos

Para trabajar con el proyecto se recomienda disponer de:

* Android Studio.
* Android SDK instalado.
* JDK compatible con la versión de Gradle utilizada.
* Git.
* Un emulador Android o dispositivo físico para las pruebas.

---

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/gabyta02/PetSalud2.git
```

Acceder al proyecto:

```bash
cd PetSalud2
```

Posteriormente, abrir la carpeta desde **Android Studio**:

```text
File → Open → PetSalud2
```

Android Studio detectará automáticamente los archivos de Gradle y realizará la sincronización de las dependencias del proyecto.

---

## Ejecución

Una vez configurado el proyecto:

1. Abrir PetSalud2 en Android Studio.
2. Esperar a que finalice la sincronización de Gradle.
3. Seleccionar un emulador o dispositivo Android.
4. Compilar el proyecto.
5. Ejecutar la aplicación desde Android Studio.

También puede utilizarse Gradle desde la terminal:

### Windows

```bash
gradlew.bat build
```

### Linux / macOS

```bash
./gradlew build
```

---

## Estado del proyecto

**Versión:** `1.2`

PetSalud representa una solución enfocada en utilizar tecnología móvil para apoyar la gestión veterinaria y facilitar el cuidado cotidiano de las mascotas.

El proyecto fue desarrollado con fines académicos y de aprendizaje, aplicando conceptos relacionados con:

* Desarrollo de aplicaciones móviles.
* Estructuración de proyectos Android.
* Gestión de información.
* Interfaces para dispositivos móviles.
* Control de versiones.
* Integración de tecnologías orientadas al almacenamiento de información.

---

## Repositorio

Código fuente y configuración disponible en:

[github.com/gabyta02/PetSalud2](https://github.com/gabyta02/PetSalud2)

---

<p align="center">
  PetSalud — Tecnología aplicada al cuidado responsable de las mascotas.
</p>
