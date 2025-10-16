# 📘 RedBlog – Plataforma de Publicaciones Interactivas

## 📝 Descripción General
**RedBlog** es una aplicación web desarrollada con el stack **MERN (MongoDB, Express.js, React, Node.js)** inspirada en plataformas como **Reddit**.  
Su propósito es permitir a los usuarios compartir publicaciones, comentar y reaccionar a contenidos, mientras que los administradores gestionan la comunidad y los visitantes pueden explorar publicaciones de manera limitada.

---

## 🎯 Objetivos
- Implementar un sistema de publicaciones tipo blog comunitario.  
- Ofrecer diferentes experiencias según el rol: visitante, usuario registrado y administrador.  
- Practicar conceptos de **autenticación, autorización y manejo de roles** en aplicaciones web modernas.  
- Aplicar arquitectura **full-stack MERN**.

---

## 👥 Roles y Vistas

### 🔹 Visitante (no autenticado)
- Puede **navegar publicaciones públicas**.  
- Puede **ver comentarios**.  
- Puede **registrarse o iniciar sesión**.  
- Acceso limitado (no puede crear publicaciones ni comentar).

### 🔹 Usuario (autenticado)
- Puede **crear publicaciones** (texto, imágenes, links).  
- Puede **comentar y reaccionar** a publicaciones.  
- Puede **editar o eliminar sus publicaciones y comentarios**.  
- Acceso a un **perfil personal** con su información básica.

### 🔹 Administrador
- Puede **gestionar usuarios** (activar/desactivar cuentas).  
- Puede **moderar publicaciones y comentarios** (eliminarlos si infringen normas).  
- Tiene un **panel de control** para estadísticas básicas de la plataforma.

---

## ⚙️ Tecnologías
- **Frontend:** React + Tailwind CSS (o Bootstrap)  
- **Backend:** Node.js + Express.js  
- **Base de Datos:** MongoDB  
- **Autenticación:** JWT (JSON Web Tokens)  
- **Control de Roles:** Middleware en Express  

---

## 📂 Funcionalidades Clave
1. **Autenticación y autorización** con roles (usuario, administrador).  
2. **CRUD de publicaciones y comentarios**.  
3. **Reacciones a publicaciones** (likes, dislikes).  
4. **Panel de administración** para gestión de usuarios y moderación.  
5. **Interfaz diferenciada** según el rol del usuario.

---

## 🔮 Posibles Extensiones Futuras
- Sistema de notificaciones.  
- Subcomunidades temáticas (subreddits).  
- Buscador avanzado por etiquetas o categorías.  
- Soporte multimedia (videos, GIFs).
