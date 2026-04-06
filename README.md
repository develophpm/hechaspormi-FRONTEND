# Hechaspormi Frontend

Aplicación web desarrollada en React para la visualización de productos, carrito de compra y flujo de checkout del sistema Hechaspormi.cl

---

## 🧱 Tecnologías

- React
- Vite / Create React App
- Axios
- React Router
- CSS 

---

## 🚀 Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/<org>/hechaspormi-frontend.git
cd hechaspormi-frontend
```

2. Instalar dependencias:

```bash
npm install
```

3. Configurar variables de entorno:
```bash
Crear archivo .env:
VITE_API_URL=http://localhost:8080
```

4. Ejecutar servidor:

```bash
npm run dev
```

---

## 📁 Estructura del proyecto

```bash
src/
├── components/
├── pages/
├── services/
├── hooks/
├── routes/
└── assets/
```

---

## 🔗 Comunicación con backend
El frontend consume la API REST expuesta por el backend (Ruby on Rails).
Ejemplo:
```bash
GET /products
POST /orders
```

---

## 🚀 Despliegue
El frontend se despliega en Firebase Hosting

---

## 👥 Flujo de desarrollo
1. Crear rama desde feature/development
2. Nombre: feature/nombre-feature
3. Crear Pull Request
4. Requiere aprobación antes de merge

---

## 📌 Notas
1. No subir .env
2. Mantener componentes reutilizables
