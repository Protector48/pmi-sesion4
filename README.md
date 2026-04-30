<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,100:1e3a8a&height=200&section=header&text=Sistema%20CRUD%20MVC&fontSize=40&fontColor=ffffff&animation=fadeIn" />
</p>
# 🧾 Sistema CRUD MVC en PHP

Aplicación web desarrollada en PHP nativo utilizando el patrón MVC (Modelo - Vista - Controlador).  
Permite la gestión de productos y usuarios mediante operaciones CRUD.

---

## 🛠️ Tecnologías utilizadas

## 🛠️ Tecnologías utilizadas

![PHP](https://img.shields.io/badge/PHP-8.0-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=apache&logoColor=white)

---

## 🚀 Características

- 📦 Gestión de productos  
- 👤 Gestión de usuarios  
- 🔄 Operaciones CRUD completas  
- 🎯 Interfaz moderna con HTML, CSS y JavaScript  
- ⚙️ Arquitectura MVC básica  
- 🔗 Comunicación con backend mediante Fetch (AJAX)

---

## 📂 Estructura del proyecto

/proyecto
├── index.php              
├── conexion/ │
              └── conexion.php       
├── controlador/ 
                 ├── ProductoController.php 
                 └── UsuarioController.php │ 
├── modelos/ │   
             ├── Producto.php  
             └── Usuario.php │ 
├── vistas/ │   
            └── home.php           
├── database.sql 
├── .gitignore 
└── README.md

---

## ⚙️ Instalación y ejecución

1. Clonar el repositorio:
git clone https://github.com/tuusuario/tu-repo.git

2. Mover el proyecto a htdocs (XAMPP)

3. Importar la base de datos:
- Abrir phpMyAdmin  
- Crear base de datos  
- Importar database.sql

4. Configurar conexión:
- Editar conexion/conexion.php

5. Ejecutar:
http://localhost/tu-proyecto/


---

## 🧠 Arquitectura

El sistema sigue el patrón MVC:

- Modelo: Manejo de datos y base de datos  
- Vista: Interfaz de usuario (HTML + JS)  
- Controlador: Lógica de negocio  

---

## 👨‍💻 Autor

Desarrollado por Protector48
