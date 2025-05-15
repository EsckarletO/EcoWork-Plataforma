# EcoWork - Plataforma de Gestión de Órdenes de Trabajo

EcoWork es una plataforma web y móvil para la gestión de órdenes de trabajo, con enfoque en comunicación eficiente entre clientes, técnicos y personal administrativo. 

## 🚀 Tecnologías principales
- Frontend Web: React.js / Vue.js / Angular
- Aplicación Móvil: React Native / Flutter
- Backend + API: Node.js + Express / Django / Laravel
- Base de Datos: PostgreSQL o MySQL
- Hosting: VPS (Ubuntu 22.04, Nginx, SSL)

## 📁 Estructura del Repositorio

```
/
├── backend/
├── frontend/
├── mobile/
├── docs/
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── historia_usuario.md
├── .gitignore
├── .gitlab-ci.yml (opcional)
└── README.md
```

## 🔁 Flujo de trabajo Git (basado en Git Flow)

1. `main` — rama estable de producción
2. `develop` — integración de nuevas funciones
3. `feature/nombre` — nuevas funcionalidades
4. `bugfix/nombre` — corrección de errores menores
5. `release/vX.X.X` — preparaciones para versiones estables
6. `hotfix/nombre` — corrección crítica en producción

## 🧠 Convención de commits
```
feat(#ID): descripción funcional
fix(#ID): corrección de bug
docs: cambios en la documentación
refactor: cambios internos sin afectar el comportamiento
```

## 📋 Historias de Usuario
Usamos **Issues** en GitHub para registrar historias de usuario. Cada una sigue el formato descrito en la plantilla de este repositorio.

## 📌 Tablero Ágil (GitHub Projects)
Organizado por columnas:
- Backlog
- En progreso
- En revisión
- Hecho
