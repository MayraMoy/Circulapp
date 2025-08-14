# 🤝 Circulapp

Plataforma de economía colaborativa que conecta a personas para compartir productos de forma segura, eficiente y confiable. Fomenta el acceso a herramientas, electrodomésticos, muebles y más, mediante donaciones de los usuarios.

---

## 📍 Diseño y Desarrollo
- <a href="https://www.figma.com/proto/Qc2f8GJf8JQju95wWrchJv/Circulapp?node-id=1-6&p=f&t=TKgtgjCcaOUaU2sh-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1" target="_blank">Circulapp Diseño Movil</a>
- <a href="https://github.com/MayraMoy/circulappFront.git">Desarrollo Frontend Repo</a>

## 🚀 Funcionalidades principales

- ✅ Registro e inicio de sesión de usuarios (email, redes sociales)
- 📦 Publicación de productos con imágenes, descripción y ubicación
- 🔍 Búsqueda y filtrado por categoría, ubicación y disponibilidad
- 💬 Chat en tiempo real entre ofertantes y demandantes
- ⭐ Sistema de calificaciones y reseñas
- 🛠 Panel de administración (gestión de usuarios y publicaciones)
- 📍 Geolocalización integrada con Google Maps
- 🔐 Seguridad con JWT y cifrado de contraseñas

---

## 🧱 Tecnologías utilizadas

| Parte        | Stack / Herramienta         |
|--------------|-----------------------------|
| Frontend     | React / React Native        |
| Backend      | FastAPI / Node.js (opcional)|
| Base de datos| PostgreSQL / MongoDB        |
| Autenticación| JWT + Firebase OAuth        |
| Almacenamiento de imágenes | Cloudinary     |
| Geolocalización | Google Maps API          |
| Chat         | Firebase Realtime / WebSocket |

---

## 🛠 Instalación local

### Requisitos previos

- Node.js / Python 3.10+
- PostgreSQL o MongoDB
- Cuenta en Firebase y Cloudinary
- API Keys para Google Maps y Stripe/MercadoPago

### Backend

```bash
cd backend/
# Instalar dependencias
pip install -r requirements.txt
# Iniciar el servidor
uvicorn main:app --reload
````

### Frontend (Web)

```bash
cd frontend/
npm install
npm run dev
```

### Frontend (Móvil)

```bash
cd mobile/
npm install
npx expo start
```

---

## 📁 Estructura del proyecto

```
Circulapp/
│
├── backend/               # API y lógica de negocio (FastAPI)
├── frontend/              # Interfaz web (React)
├── mobile/                # App móvil (React Native)
├── docs/                  # Documentación (SRS, diagramas, etc.)
└── README.md
```

---

## 📌 Estado del proyecto

🚧 En desarrollo (MVP funcional en progreso)
🧪 Etapa de validación con primeros usuarios
🔄 Planeando escalado e integración de IA para recomendaciones

---

## 🧑‍💻 Contribuciones

¡Contribuciones, ideas y sugerencias son bienvenidas!
Abrí un issue o hacé un pull request.

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT.
© 2025 Circulapp. Todos los derechos reservados.

---

## 🌍 Autora

**Mayra Moyano - Marilen Cornejo**

