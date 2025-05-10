# Sistema de Control de Inventario 📦

Este es un proyecto fullstack que permite gestionar el inventario y las ventas de una tienda. Incluye una aplicación **backend con Node.js y MySQL** y un **frontend moderno construido con Vite + React + TailwindCSS**. Diseñado como una solución local, esta app permite agregar productos, controlar stock y simular ventas de manera rápida y sencilla.

## 🧠 Contenido

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Repositorios Originales](#repositorios-originales)
- [Licencia](#licencia)

## 🚀 Características

- **Gestión de Productos:** Crear, editar y eliminar productos del inventario.
- **Registro de Ventas:** Gestiona y registra las ventas.
- **Interfaz Intuitiva:** Interfaz gráfica moderna y fácil de usar.
- **Persistencia con MySQL:** Los datos se guardan en una base de datos relacional.
- **Estado local de ventas:** Se utiliza `localStorage` para guardar temporalmente los datos de venta.

## 🛠️ Tecnologías Utilizadas

### Backend:
- **Node.js**
- **Express.js**
- **Sequelize** (ORM)
- **MySQL**

### Frontend:
- **React**
- **Vite**
- **TailwindCSS**
- **JavaScript**

## 📁 Estructura del Proyecto

```
fullstack-inventory-management/
├── server/        # API REST con Express + Sequelize
├── client/       # Interfaz gráfica con React + TailwindCSS
└── README.md       # Este archivo
```

## ⚙️ Instalación

1. **Clonar el repositorio unificado**:

```bash
git clone https://github.com/TU_USUARIO/fullstack-inventory-management
cd fullstack-inventory-management
```

2. **Configurar el backend**:

```bash
cd server
touch .env
npm install
npm start
```

Ejemplo de `.env`:

```env
DB_NAME=tu_base_de_datos
DB_USER=tu_usuario
DB_PASS=tu_contraseña
DB_HOST=localhost
DB_DIALECT=mysql
PORT=3000
```

3. **Configurar el frontend**:

```bash
cd ../client
npm install
npm run dev
```

## 🧪 Uso

1. Asegúrate de tener tu base de datos MySQL corriendo 💾.
2. Inicia primero el backend (`localhost:3000` por defecto).
3. Luego, inicia el frontend (`localhost:5173` por defecto con Vite).
4. Abre el navegador en `http://localhost:5173` y comienza a usar la app 🎉.

## 🔗 Repositorios Originales

Este repositorio unificado fue creado para fines de portafolio. El desarrollo inicial del proyecto fue dividido en dos repositorios independientes:

- 🔙 **Backend original:** [inventory-management-system](https://github.com/Draekk/inventory-management-system)
- 🎨 **Frontend original:** [ims-front-test](https://github.com/Draekk/ims-front-test)

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.
