# 📺 YouTube Clone – Documentación

Este proyecto es un **clon de YouTube** desarrollado con **React.js** y **Material UI**, que consume la API de YouTube (vía RapidAPI) para mostrar videos, canales y resultados de búsqueda en tiempo real.

El objetivo principal del proyecto es **práctico y educativo**, enfocado en el consumo de APIs, componentes reutilizables y diseño moderno con React.

---

## 🚀 Características

- 🔍 Búsqueda de videos y canales
- 📹 Reproducción de videos de YouTube
- 📂 Feed por categorías
- 👤 Vista de canal con sus videos
- ⚡ Carga dinámica de contenido
- 📱 Diseño responsive

---

## 🛠️ Tecnologías utilizadas

- **React.js**
- **Material UI v5**
- **React Router DOM**
- **Axios**
- **RapidAPI – YouTube v3**
- **CSS**

---

## 📁 Estructura del proyecto

```
project_youtube_clone-main/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── ChannelCard.jsx
│   │   ├── ChannelDetail.jsx
│   │   ├── Feed.jsx
│   │   ├── Loader.jsx
│   │   ├── Navbar.jsx
│   │   ├── SearchBar.jsx
│   │   ├── SearchFeed.jsx
│   │   ├── Sidebar.jsx
│   │   └── VideoCard.jsx
│   │
│   ├── App.js
│   ├── index.js
│   └── index.css
│
├── .env.example
├── package.json
└── README.md
```

---

## ⚙️ Instalación y configuración

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/aledrinkswine/project_youtube_clone-main.git
cd youtube-clone
```

### 2️⃣ Instalar dependencias

```bash
npm install
```

### 3️⃣ Configurar variables de entorno

Renombra el archivo `.env.example` a `.env` y agrega tu API Key:

```env
REACT_APP_RAPID_API_KEY=tu_api_key_aqui
```

> ⚠️ Necesitas una cuenta en **RapidAPI** y suscribirte a la API de YouTube v3.

---

## ▶️ Ejecutar el proyecto

```bash
npm start
```

La aplicación se abrirá en:

```
http://localhost:3000
```

---

## 🧩 Componentes principales

- **Feed**: muestra los videos principales por categoría
- **SearchFeed**: resultados de búsqueda
- **ChannelDetail**: información del canal y sus videos
- **VideoCard / ChannelCard**: tarjetas reutilizables
- **Navbar & Sidebar**: navegación principal

---

## 📌 Buenas prácticas aplicadas

- Componentes reutilizables
- Separación de responsabilidades
- Uso de hooks (`useState`, `useEffect`)
- Manejo de loaders
- Variables de entorno

---

## 🧪 Posibles mejoras futuras

- Autenticación de usuarios
- Sistema de favoritos
- Comentarios
- Modo oscuro
- Paginación avanzada

---


---

## 👨‍💻 Autor

**Manuel Alejandro** - Desarrollador Full Stack

---
