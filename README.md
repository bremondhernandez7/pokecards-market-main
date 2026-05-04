# 🎴 PokéCards Market

> 🛒 Tienda interactiva de cartas Pokémon con pagos simulados en tiempo real

Aplicación web construida con React + Vite que consume datos desde PokéAPI y permite comprar cartas usando PayPal Sandbox.

---

## 🚀 Demo (opcional)
👉 Puedes agregar aquí tu link si lo subes a Vercel o Netlify

---

## ✨ Características principales

- 🎴 30 cartas dinámicas cargadas en tiempo real  
- 💰 Sistema de precios inteligente según rareza (tipo Pokémon)  
- 🔎 Filtros en vivo por tipo  
- 💳 Pagos con PayPal Sandbox (flujo real)  
- ✅ Validación de compra (`COMPLETED`)  
- 📦 Mi colección con resumen de inversión  
- 💾 Persistencia local con `localStorage`  
- 🔔 Notificaciones animadas con ID de transacción  
- 📱 Diseño responsive (móvil + desktop)

---

## 🧠 Lógica interesante del proyecto

### 💎 Sistema de rareza
Los precios se calculan dinámicamente:
- 🔥 Dragón → más caro  
- ⚡ Eléctrico / Fuego → medio  
- 🍃 Normal → más barato  

Esto simula un mercado real dentro del juego.

---

## 🛠️ Instalación

### Requisitos
- Node.js 18+
- npm 9+

### Pasos

```bash
git clone https://github.com/bremondhernandez7/pokecards-market.git
cd pokecards-market
npm install
npm run dev
