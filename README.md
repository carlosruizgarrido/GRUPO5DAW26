# GRUPO5DAW26

Repositorio del grupo 5 para el desarrollo y despliegue de la aplicación web de alimentos mediante arquitectura MVC.

**Repositorio:** [GRUPO5DAW26 – GitHub](https://github.com/carlosruizgarrido/GRUPO5DAW26)  
**URL del proyecto desplegado en el hosting:** https://joseiescamas.alwaysdata.net/

## 1. Organización del proyecto

El desarrollo se ha dividido entre dos integrantes, asignando a cada uno una parte del proyecto para facilitar el trabajo simultáneo y el control de versiones mediante Git.

Se han creado tres ramas de desarrollo, una por cada parte del patrón MVC:

- `modelo`: Gestión de datos y conexión con la base de datos.
- `vista`: Interfaz de usuario y recursos del front-end.
- `controlador`: Lógica de control, configuración y acceso a la aplicación.

La rama `main` será la rama principal y contendrá la versión integrada y definitiva del proyecto.

## 2. Estructura del repositorio

La estructura prevista del proyecto es la siguiente:

```text
GRUPO5DAW26/
│
├── app/
│   ├── Config.php
│   ├── Controller.php
│   ├── Model.php
│   │
│   └── templates/
│       └── Archivos de las vistas
│
├── web/
│   ├── index.php
│   │
│   ├── css/
│   ├── js/
│   └── images/
│
├── historico.txt
├── instalacion.txt
├── valoraciones.txt
└── README.md
```

### Distribución de responsabilidades

| Integrante | Archivos y tareas asignadas |
|---|---|
| Integrante 1 | `app/templates/`, `web/css/`, `web/js/` y `web/images/`. Administración del repositorio GitHub y recopilación de valoraciones. |
| Integrante 2 | `app/Model.php`. Creación y configuración de la base de datos MySQL y despliegue en Alwaysdata. |
| Integrante 3 | `app/Config.php`, `app/Controller.php` y `web/index.php`. Configuración de conexión, controlador y documentación del histórico. |

## 3. Organización del trabajo con Git

Cada integrante trabaja en su propia rama para evitar interferencias en el desarrollo.

Las ramas utilizadas son:

- `modelo`
- `vista`
- `controlador`

Cuando una parte está terminada, sus cambios se suben a GitHub y se solicita su incorporación a `main` mediante un Pull Request.

Este procedimiento permite revisar los cambios antes de integrarlos en la versión principal.

## 4. Despliegue y estructura final en el hosting

El proyecto se publicará en Alwaysdata.

La estructura prevista en el servidor será:

```text
proyecto/
│
├── app/              (Back-end privado)
│   ├── Config.php
│   ├── Controller.php
│   ├── Model.php
│   └── templates/
│
└── web/              (Directorio público)
    ├── index.php
    ├── css/
    ├── js/
    └── images/
```

El directorio público del hosting apuntará a `web/`, manteniendo `app/` fuera del acceso público para proteger los archivos internos del proyecto, especialmente la configuración de la base de datos.

## 5. Documentación del repositorio

El repositorio contará con tres ficheros adicionales:

- **historico.txt:** Registro cronológico de las tareas realizadas, cambios y fusiones de ramas.
- **instalacion.txt:** Comandos y procedimientos utilizados para la instalación, conexión y despliegue en Alwaysdata.
- **valoraciones.txt:** Opiniones individuales de los tres integrantes sobre la realización de la práctica.

## 6. Integrantes

- **Integrante 1:** José Antonio.
- **Integrante 2:** Carlos Ruiz.

## 7. Acceso al proyecto

- **GitHub:** https://github.com/carlosruizgarrido/GRUPO5DAW26
- **URL del proyecto desplegado:** Pendiente.
