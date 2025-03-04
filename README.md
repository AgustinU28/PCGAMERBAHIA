# 🎮 PCGamerBahia 💻

## 🚀 Descripción del Proyecto

PCGamerBahia es una plataforma de comercio electrónico especializada en computadoras y componentes para gamers, desarrollada con tecnologías modernas para ofrecer una experiencia de compra fluida y segura.



## ✨ Características Principales

- 🔐 **Autenticación de Usuarios**
  - Registro de nuevos usuarios
  - Inicio de sesión seguro
  - Gestión de perfiles

- 🛒 **Carrito de Compras**
  - Añadir y eliminar productos
  - Gestión de cantidades
  - Resumen de compra

- 💳 **Pasarela de Pago**
  - Integración de métodos de pago
  - Procesamiento seguro de transacciones
  - Confirmación de pedidos

- 💾 **Catálogo de Productos**
  - Computadoras para gaming
  - Componentes de PC
  - Detalles técnicos completos

## 🛠️ Tecnologías Utilizadas

- **Backend**: Node.js
- **Framework**: Express.js
- **Base de Datos**: MongoDB
- **Autenticación**: JSON Web Tokens (JWT)
- **Pagos**: Pasarela de pago integrada

## 📦 Instalación

### Requisitos Previos

- Node.js (v14 o superior)
- MongoDB
- npm

### Pasos de Instalación

1. Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/pcgamerbahia.git
cd pcgamerbahia
```

2. Instalar dependencias
```bash
npm install
```

3. Configurar variables de entorno
- Crear un archivo `.env`
- Configurar:
  - `MONGODB_URI`
  - `JWT_SECRET`
  - Credenciales de pasarela de pago

4. Iniciar el servidor
```bash
npm start
```

## 🔐 Variables de Entorno

- `PORT`: Puerto del servidor
- `MONGODB_URI`: Cadena de conexión de MongoDB
- `JWT_SECRET`: Clave secreta para tokens
- `PAYMENT_API_KEY`: Clave de la pasarela de pago

## 🚧 Próximas Mejoras

- [ ] Implementar sistema de reseñas
- [ ] Añadir recomendaciones personalizadas
- [ ] Optimizar rendimiento de base de datos

## 📄 Licencia

Distribuido bajo la Licencia MIT. Consultar `LICENSE` para más información.

---

🎮 Desarrollado con ❤️ para la comunidad gamer 🖥️

## 🔑 Solicitud de Configuración .env

**IMPORTANTE**: 
Por razones de seguridad, el archivo `.env` no se incluye en el repositorio. 
Para configurar tu entorno, crea un archivo `.env` en la raíz del proyecto con las siguientes variables:

```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/pcgamerbahia
JWT_SECRET=tu_secreto_muy_largo_y_seguro
PAYMENT_API_KEY=tu_clave_de_pasarela_de_pago
```

**Nota**: Reemplaza los valores con tus credenciales y claves reales. 
Nunca compartas públicamente tus credenciales sensibles.
