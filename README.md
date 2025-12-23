<div align="center">

# LogicFrame

**Ingeniería de software + productos digitales**  
Plataformas web, automatización y sistemas serverless con foco en calidad, seguridad y experiencia de usuario.

<br/>

<!-- Reemplaza SOLO estos links si quieres que los badges apunten a algo real -->
<a href="logicframe.cl">
  <img alt="Website" src="https://img.shields.io/badge/Web-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white">
</a>
<a href="{LINK_DISCORD}">
  <img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</a>
<a href="mailto:contacto@logicframe.cl">
  <img alt="Email" src="https://img.shields.io/badge/Contacto-555?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<br/><br/>

</div>

---

## ✨ Quiénes somos

En **LogicFrame** construimos sistemas y productos digitales orientados a operaciones y comunidades:  
desde **plataformas D&D con módulos VTT**, hasta **e-commerce**, **bots para Discord** y **sistemas de gestión operativa** con control de acceso, auditoría y reporting.

**Enfoque:**
- ✅ Arquitectura mantenible (separación por módulos, tipado, contratos claros)
- ✅ Iteración rápida (metodologías adaptativas tipo Crystal Clear)
- ✅ Seguridad por defecto (roles, reglas de acceso, secretos, auditoría)

---

## 🧩 Qué hacemos

### Productos / Proyectos principales
- **DnD Nexus (Plataforma D&D)**  
  Creación y gestión de contenido (razas, clases, dotes, hechizos), campañas single-player guiadas y paneles internos.
- **VTT (Virtual Tabletop) + sesiones en tiempo real**  
  Sesiones, mensajes, iniciativa/combate, tokens, condiciones, pings y eventos (incluye broadcasting de eventos como tiradas/sonidos).
- **Danu’s Vault (operación/venta en Discord)**  
  Flujos de venta digital, roles, cupones/boletas y automatizaciones con bots y workers.
- **E-commerce**  
  Tienda web con stack Django/MySQL y estructura orientada a catálogo, ventas y administración.
- **Sistema de gestión operativa**  
  Roles (admin/rangos/usuario), inventario, reportes/estadísticas, mantención y manuales.

---

## 🧱 Stack tecnológico (lo que realmente hemos usado)

- **Frontend:** React + TypeScript + Vite, Astro (UI interna / vistas), TailwindCSS
- **Backend / Serverless:** Firebase (Auth, Firestore, RTDB, Storage), Cloud Functions/Serverless patterns
- **Automatización / Bots:** Discord slash commands, Cloudflare Workers / Deno Deploy (según el proyecto)
- **Bases de datos:** Firestore (principal), MySQL (e-commerce), modelos tipo DWH/ETL en entregables académicos
- **Calidad:** ESLint/Prettier, reglas de seguridad, validaciones, templates y documentación

---

## ✅ Forma de trabajar (estándar interno)

### Ramas
- `main`: estable (producción)
- `develop`: integración (si aplica)
- `feature/*`: nuevas funcionalidades
- `fix/*`: correcciones
- `hotfix/*`: parches urgentes

### Commits (Conventional Commits)
- `feat:` nueva funcionalidad
- `fix:` bugfix
- `docs:` documentación
- `refactor:` refactor sin cambio funcional
- `chore:` tareas internas / tooling

### Pull Requests
- Descripción clara (qué / por qué)
- Screenshots o GIF si hay UI
- Checklist mínimo: lint OK, build OK, reglas/roles revisados si toca permisos

---

## 🔐 Seguridad (principios no negociables)

- **Nunca** subir API keys/credenciales al repositorio (usar secrets/variables de entorno)
- Reglas de acceso por rol (por ejemplo: IAM interno, permisos por usuario/rol)
- Auditoría y logging de acciones relevantes
- Revisión de cuotas y límites (por ejemplo: Firestore y operaciones masivas)

📩 Reporte de vulnerabilidades: **soporte@logicframe.cl** *(o usa el mismo correo de contacto)*

---

## 🚀 Onboarding rápido (para nuevos contributors)

### Requisitos típicos
- Node.js LTS
- Cuenta Firebase (si el repo lo requiere) y variables `.env.local`
- Git + GitHub (PR workflow)

### Comandos típicos
- Instalar: `npm i`
- Correr: `npm run dev`
- Build: `npm run build`
- Lint: `npm run lint`

> Cada repositorio debería tener su propia sección “Setup” con sus `.env` necesarios y pasos exactos.

---

## 📌 Repositorios destacados (según lo que hemos construido)

| Repo | Qué contiene | Stack | Estado |
|---|---|---|---|
| **dnd-nexus** | Plataforma D&D (contenido + campañas + panel) | React/TS/Firebase | 🟢 Activo |
| **vtt-module** | Virtual Tabletop (sesiones, tokens, combate, eventos) | React/TS/Firebase/RTDB | 🟢 Activo |
| **danu-vault-bot** | Bot + automatización para Discord (ventas/roles/cupones) | Workers/Deno/TS | 🟡 Iterando |
| **jrbstore2** | E-commerce (catálogo/ventas/admin) | Django/MySQL | 🟡 Mantención |
| **ops-inventory** | Gestión operativa (inventario/partes/reportes/roles) | Web + BD | 🟢 Activo |

> Si tus repos tienen otros nombres reales, cambia solo la columna “Repo” y listo.

---

## 📚 Documentación

- Manuales: **Usuario / Instalación / Mantención**
- Metodología: **Crystal Clear** (entrega por iteraciones + comunicación)
- Diagramas: flujo front→backend, infraestructura (Hosting → Firebase Auth/DB/Storage)

---

## 📣 Contacto

- Web: https://logicframe.cl
- Discord: {LINK_DISCORD}
- Correo: **contacto@logicframe.cl**

---

<div align="center">

**© 2025 LogicFrame**  
Construimos productos con foco en experiencia, seguridad y mantenibilidad.

</div>
