# 🚗 IngeCarsPlus

Sistema web para la gestión de talleres mecánicos. Permite a los clientes agendar citas, consultar servicios disponibles y al personal administrativo gestionar el taller de manera eficiente.

## ✨ Características

- 🔐 **Autenticación de usuarios** — Registro e inicio de sesión seguro
- 📅 **Agendamiento de citas** — Los clientes pueden programar servicios
- 🛠️ **Catálogo de servicios** — Visualización de todos los servicios del taller
- 👤 **Panel de consultas** — Historial de citas y servicios por usuario
- 📱 **Diseño responsive** — Interfaz adaptable a dispositivos móviles

## 🛠️ Stack Tecnológico

| Tecnología | Propósito |
|------------|-----------|
| **PHP** (MVC propio) | Backend y lógica de negocio |
| **MySQL** | Base de datos |
| **HTML5 / CSS3** | Estructura y estilos |
| **JavaScript (jQuery)** | Interactividad en el frontend |
| **Bootstrap** | Diseño responsive |

## 🗂️ Estructura del Proyecto

`
IngeCarsPlus/
├── app/
│   ├── controller/        # Controladores (lógica de negocio)
│   ├── models/            # Modelos (interacción con BD)
│   └── views/             # Vistas (interfaz de usuario)
│       ├── css/           # Hojas de estilo
│       ├── js/            # Scripts JavaScript
│       ├── img/           # Imágenes del sistema
│       └── fonts/         # Tipografías
├── system/
│   ├── core/              # Núcleo del framework MVC
│   │   ├── Controller.php
│   │   ├── Model.php
│   │   ├── Router.php
│   │   ├── View.php
│   │   └── autoload.php
│   └── config.php         # Configuración de la aplicación
├── index.php              # Punto de entrada
├── sena.sql               # Esquema de la base de datos
└── .gitignore
`

## 🚀 Instalación

### Requisitos

- PHP 7.4 o superior
- MySQL 5.7 o superior
- Servidor web (Apache / Nginx)

### Pasos

1. **Clonar el repositorio**
   \\\ash
   git clone https://github.com/MoroLitZ/IngecarsPlus.git
   cd IngecarsPlus
   \\\

2. **Configurar la base de datos**
   - Crea una base de datos MySQL llamada sena
   - Importa el archivo sena.sql:
   \\\ash
   mysql -u root -p sena < sena.sql
   \\\

3. **Configurar la conexión**
   - Edita system/config.php con tus credenciales de MySQL

4. **Ejecutar**
   - Coloca el proyecto en la carpeta de tu servidor web (htdocs, www, etc.)
   - Accede a través de tu navegador: http://localhost/IngecarsPlus

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
