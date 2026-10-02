# 🍽️ Sistema Web Startup Cusco

## 1. Introducción

La guía consiste en desarrollar inicialmente un sistema web básico para una **startup de Cusco dedicada a la gestión de pedidos de comida local**.

Durante esta actividad se configura el entorno de desarrollo, se crea un repositorio local, se gestionan cambios mediante Git y se conecta el proyecto con un repositorio remoto en GitHub.

---

## 2. Objetivo

Configurar un entorno de desarrollo y aplicar control de versiones utilizando **Git** en un proyecto web básico para la gestión de pedidos de comida local.

---

## 3. Resultados de aprendizaje

Al finalizar la actividad se busca:

* Comprender el uso del control de versiones en proyectos de software.
* Configurar herramientas modernas para el desarrollo de software.
* Crear y gestionar un repositorio local con Git.
* Conectar un repositorio local con un repositorio remoto en GitHub.
* Registrar los cambios realizados mediante commits.
* Gestionar el código fuente de manera organizada.

---

## 4. Fundamento teórico

El **control de versiones** permite gestionar los cambios realizados en los archivos de un proyecto de software.

**Git** es un sistema de control de versiones distribuido que permite registrar modificaciones, recuperar versiones anteriores y facilitar el trabajo colaborativo entre los integrantes de un equipo.

**GitHub** es una plataforma que permite alojar repositorios Git de forma remota, facilitando el almacenamiento, colaboración y seguimiento del código fuente.

En este proyecto se utiliza Git para controlar la evolución del sistema web y GitHub como repositorio remoto.

---

## 5. Herramientas utilizadas

### Visual Studio Code

Editor de código utilizado para desarrollar y organizar los archivos del proyecto.

### Git

Sistema de control de versiones utilizado para registrar y gestionar los cambios realizados en el proyecto.

### GitHub

Plataforma utilizada para almacenar el repositorio remoto del proyecto.

---

## 6. Descripción del proyecto

Una startup ubicada en **Cusco** desea desarrollar un sistema web para gestionar pedidos de comida local.

Para iniciar el desarrollo, se crea un proyecto básico que servirá como base para implementar posteriormente las diferentes funcionalidades del sistema.

En esta primera etapa, el principal objetivo es **organizar el proyecto y aplicar Git desde el inicio del desarrollo**.

---

## 7. Configuración del proyecto

### 7.1. Crear el proyecto

Se creó una carpeta para almacenar los archivos correspondientes al sistema web.

```text
Sistema web Startup Cusco/
```

El proyecto fue abierto utilizando **Visual Studio Code**.

---

### 7.2. Inicializar Git

Desde la terminal se inicializó un repositorio Git mediante:

```bash
git init
```

Este comando permite convertir la carpeta del proyecto en un repositorio local de Git.

---

### 7.3. Verificar el estado del repositorio

Para comprobar el estado de los archivos se utilizó:

```bash
git status
```

Este comando permite identificar archivos nuevos, modificados o pendientes de agregar al área de preparación.

---

### 7.4. Agregar archivos al área de preparación

Los archivos del proyecto fueron agregados mediante:

```bash
git add .
```

El comando permite preparar los cambios para realizar un commit.

---

### 7.5. Crear el primer commit

Se registró la primera versión del proyecto mediante:

```bash
git commit -m "feat: estructura inicial del proyecto"
```

El commit permite guardar un punto de control de la versión actual del proyecto.

---

## 8. Repositorio remoto en GitHub

Se creó un repositorio remoto en GitHub con el nombre:

**Sistema-web-Startup-Cusco**

Repositorio:

`https://github.com/Diana231861/Sistema-web-Startup-Cusco`

Para conectar el repositorio local con GitHub se utilizó:

```bash
git remote add origin https://github.com/Diana231861/Sistema-web-Startup-Cusco.git
```

Para verificar la configuración del repositorio remoto:

```bash
git remote -v
```

---

## 9. Subir el proyecto a GitHub

Después de conectar el repositorio local con GitHub, se utilizó:

```bash
git branch -M main
```

Este comando establece `main` como nombre de la rama principal.

Finalmente, se subió el proyecto al repositorio remoto mediante:

```bash
git push -u origin main
```

El parámetro `-u` permite establecer la relación entre la rama local `main` y la rama remota `main`.

---

## 10. Flujo básico de trabajo con Git

El flujo utilizado durante la actividad es:

```text
Modificar archivos
       ↓
   git status
       ↓
    git add .
       ↓
git commit -m "mensaje"
       ↓
 git push origin main
       ↓
     GitHub
```

Este proceso permite mantener un registro de los cambios realizados en el proyecto.

---

## 11. Comandos principales utilizados

| Comando                 | Función                                     |
| ----------------------- | ------------------------------------------- |
| `git init`              | Inicializa un repositorio Git               |
| `git status`            | Muestra el estado del repositorio           |
| `git add .`             | Agrega los cambios al área de preparación   |
| `git commit`            | Registra los cambios                        |
| `git branch`            | Permite gestionar ramas                     |
| `git remote -v`         | Muestra los repositorios remotos            |
| `git remote add origin` | Conecta el repositorio local con GitHub     |
| `git push`              | Envía cambios al repositorio remoto         |
| `git pull`              | Obtiene cambios desde el repositorio remoto |

---

## 12. Estructura inicial

La estructura inicial del proyecto es:

```text
Sistema-web-Startup-Cusco/
│
├── README.md
└── ...
```

La estructura será ampliada conforme avance el desarrollo del sistema web.

---

## 13. Evidencias

Durante la actividad se pueden considerar como evidencias:

* Proyecto creado en Visual Studio Code.
* Repositorio Git inicializado.
* Ejecución de comandos Git.
* Primer commit realizado.
* Repositorio remoto creado en GitHub.
* Proyecto subido correctamente a GitHub.

---

## 14. Conclusiones

* Se configuró un entorno básico para el desarrollo del proyecto web.
* Se comprendió la importancia del control de versiones en proyectos de software.
* Se creó y gestionó un repositorio local utilizando Git.
* Se vinculó el repositorio local con un repositorio remoto en GitHub.
* Se realizó el registro y envío de cambios mediante commits y `git push`.
* Git permite mantener un historial de cambios y facilita la organización del código durante el desarrollo.

---

## 15. Información del proyecto

**Proyecto:** Sistema Web Startup Cusco
**Curso:** Ingeniería de Software
**Actividad:** Introducción al entorno de desarrollo y Git
**Institución:** Universidad Nacional de San Antonio Abad del Cusco (UNSAAC)
**Periodo:** 2026-II
**Repositorio:** GitHub
