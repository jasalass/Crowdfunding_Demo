# 💸 CrowdfundApp - Demo

**CrowdfundApp** es una plataforma web de financiamiento colaborativo donde los usuarios pueden explorar campañas activas y aportar, mientras que los creadores pueden gestionar sus propias iniciativas.

---

## 🎯 Funcionalidades principales

- Registro e inicio de sesión con autenticación JWT
- Diferenciación de roles: creador y aportador
- Creación, listado y eliminación de campañas
- Aportes con validación mínima de monto
- Visualización de progreso recaudado
- Exploración pública de campañas activas
- Interfaz responsiva, clara y funcional

---

## 📂 Repositorios del proyecto

| Componente | Repositorio |
|------------|-------------|
| 🌐 Frontend | [jasalass/Front_Crowdfunding](https://github.com/jasalass/Front_Crowdfunding) |
| ⚙️ Backend  | [jasalass/Backend_Crowdfunding](https://github.com/jasalass/Backend_Crowdfunding) |

---

## 🚀 Demo en línea

👉 [https://crowdfunding-demo.netlify.app](https://crowdfunding-demo.netlify.app)

Puedes acceder como visitante, registrarte como nuevo usuario o iniciar sesión como creador para probar la plataforma completa.

---

## 👤 Usuarios de prueba
Creador de campañas:
```txt
Correo:     demo@crowdfund.cl
Contraseña: 123456
```
Usuario que aporta:
```txt
Correo:     aporte@crowdfunding.com
Contraseña: 123456
```
---

## ⚙️ Instalación local

### 1. Clona el frontend

```bash
git clone https://github.com/jasalass/Front_Crowdfunding.git
cd Front_Crowdfunding
```

Luego abre `index.html` directamente o usa Live Server.

### 2. Clona y ejecuta el backend

```bash
git clone https://github.com/jasalass/Backend_Crowdfunding.git
cd Backend_Crowdfunding
npm install
npm run dev
```

Crea un archivo `.env` con lo siguiente:

```env
PORT=3000
MONGO_URI=mongodb+srv://<TU-USUARIO>:<TU-CLAVE>@<CLUSTER>/<DB>
JWT_SECRET=clave_secreta
```

---

## 📸 Capturas

![1](https://github.com/user-attachments/assets/378e60b0-1a0e-4097-b6d3-8546806c7c61)

![2](https://github.com/user-attachments/assets/1dad5b6a-50ea-4581-b966-270e40bb98b5)

![3](https://github.com/user-attachments/assets/0ca50219-2bac-4a91-92ba-718e826dc141)


---

## 🧠 Tecnologías utilizadas

- 🟩 Node.js + Express + MongoDB
- 🧾 JSON Web Tokens (JWT)
- 🎨 HTML + CSS + Bootstrap 5
- 🧠 JavaScript Vanilla
- ☁️ Deploy: Netlify (frontend) + Render (backend)

---

## 💡 Créditos

Desarrollado por [@jasalass](https://github.com/jasalass) como proyecto completo full stack.

