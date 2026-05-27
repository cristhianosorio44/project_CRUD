# 🎬 Proyecto CRUD en PHP — DAW2

Este proyecto implementa un sistema **CRUD (Create, Read, Update, Delete)** utilizando **PHP**, **MySQL** y **HTML**.  
Forma parte del módulo **RA4 - PT7: Documentació del codi font, Markdown i GitHub Actions**.

---

## 📁 Estructura del proyecto

project_CRUD/
│── com/
│   ├── cls/          # Clases PHP del sistema
│   └── Database/     # Conexión y gestión de base de datos
│
│── docs/             # Documentación generada con phpDocumentor
│── vendor/           # Dependencias instaladas con Composer
│── main.php          # Página principal del CRUD
│── info.php          # Archivo de prueba PHP
│── composer.json     # Configuración de dependencias
│── phpdoc.xml        # Archivo de configuración (no usado en versión actual)
│── README.md         # Documento principal del proyecto



---

## 🧩 Funcionalidades

- Crear registros  
- Leer registros  
- Actualizar registros  
- Eliminar registros  
- Gestión de base de datos mediante clases  
- Documentación generada automáticamente con **phpDocumentor**

---

## 🛠️ Tecnologías utilizadas

- **PHP 8.2**
- **MySQL**
- **Composer**
- **phpDocumentor 3**
- **Docker**
- **HTML / CSS**

---

## 📚 Documentación del código

La documentación se generó con el siguiente comando:

```bash
docker run --rm -v C:\Users\Crist\DAW\DAW2\0613_servidor\Proyectos\06_Project_CRUD:/data phpdoc/phpdoc:3 -d /data -t /data/docs



GitHub Actions
Este proyecto incluye un workflow que valida el código PHP y genera documentación automáticamente.

Archivo del workflow:
.github/workflows/main.yml


Autor
Cristhian  
DAW2 — INS Les Salines
Asignatura: Servidor (0613)

Licencia
Proyecto académico — uso educativo.


