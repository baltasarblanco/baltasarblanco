<!-- Encabezado con badges dinámicos -->
<p align="center">
  <img src="https://img.shields.io/badge/Rust-1.85+-orange?logo=rust" />
  <img src="https://img.shields.io/badge/Python-3.12+-blue?logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-0.115+-teal?logo=fastapi" />
  <img src="https://img.shields.io/badge/PostgreSQL-16+-blue?logo=postgresql" />
  <img src="https://img.shields.io/badge/Docker-27+-blue?logo=docker" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

<h1 align="center">Baltasar Blanco</h1>
<h3 align="center">Systems Engineer • Rust Core • Python Tactical</h3>

<p align="center">
  <a href="https://github.com/baltasarblanco">
    <img src="https://komarev.com/ghpvc/?username=baltasarblanco&label=Profile%20Views&color=0e75b6&style=flat" />
  </a>
</p>

---

## 🧠 Dual Architecture Mindset

> *"Construyo producto en Python para el negocio, e infraestructura en Rust para la máquina."*

Soy un ingeniero que opera en **dos capas**:

| Capa | Tecnologías | Propósito |
|------|-------------|-----------|
| **Táctica (L7)** | Python, FastAPI, PostgreSQL, Docker, Pytest | Entregar valor comercial rápido, seguro y testeable. |
| **Estratégica (L3/L4)** | Rust, Tokio-uring, io_uring, eBPF, Zero‑Copy IPC | Construir sistemas de ultra‑baja latencia y control total del hardware. |

---

## ⚙️ Portafolio Destacado

### 🦀 Vanguard Infrastructure Suite (Rust bare‑metal)

| Proyecto | Estado | Descripción | Métrica Clave |
|----------|--------|-------------|---------------|
| **[aegis-proxy](https://github.com/baltasarblanco/aegis-proxy)** | ✅ Completado | Proxy L4 TCP con io_uring, thread‑per‑core y zero‑alloc hot‑path. | **+8.4k RPS** · P99 <1ms |
| **[chronos_lsm](https://github.com/baltasarblanco/chronos_lsm)** | ✅ Completado | Motor Key‑Value LSM‑Tree con WAL, bloom filters y compactación. | **45k writes/s · 120k reads/s** |
| **[celer_mock](https://github.com/baltasarblanco/celer_mock)** | 🟡 En debugging | CEP engine zero‑copy con memfd_create + SCM_RIGHTS. | Pérdida <0.001% · Ring buffer en análisis |
| **[vanguard-infrastructure](https://github.com/baltasarblanco/vanguard-infrastructure)** | 🟡 En integración | Dashboard RYŪ + telemetría L7. | Visualización en tiempo real |

### 🐍 Bifrost (Python product‑ready API)

| Hito | Estado | Detalle |
|------|--------|---------|
| CLI resiliente con httpx | ✅ | Manejo de excepciones, logs, timeouts. |
| FastAPI + Pydantic | ✅ | Contratos estrictos, Swagger automático. |
| SQLite → PostgreSQL + SQLAlchemy | ✅ | Migraciones con Alembic, relaciones 1:N. |
| Autenticación JWT + bcrypt | ✅ | fastapi‑users, protección de rutas. |
| Pytest asíncrono + cobertura >70% | ✅ | Tests con base de datos efímera. |
| Docker + docker‑compose + Makefile | ✅ | Entorno reproducible con un `make up`. |
| Reservas con timezone awareness | ✅ | UTC estricto, generación de slots. |
| `SELECT FOR UPDATE` (bloqueo pesimista) | ✅ | Concurrencia real sin race conditions. |

> 🔥 **Próximo hito (Semanas 11-12):** Integración de CHRONOS como denylist JWT y rate limiter táctico.

---

## 📊 Estado actual de operaciones

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=baltasarblanco&show_icons=true&theme=tokyonight" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=baltasarblanco&layout=compact&theme=tokyonight" />
</p>

**Proyecto Bifrost – MK.4.1**  
✅ Web API operativa · ✅ Persistencia SQL · ✅ Tests automáticos · ✅ Contenerización completa  
🚧 Integración híbrida Python ↔ Rust en curso.

---

## 🛠️ Tecnologías que domino (con profundidad)

**Lenguajes:**  
`Rust` · `Python` · `SQL` · (próximamente `C` para eBPF)

**Backend / Sistemas:**  
`FastAPI` · `Pydantic` · `SQLAlchemy` · `Alembic` · `PostgreSQL` · `SQLite` · `Docker` · `Makefile` · `Pytest`

**Bajo nivel / Rendimiento:**  
`io_uring` · `tokio‑uring` · `memfd_create` · `SCM_RIGHTS` · `mmap` · `thread‑per‑core` · `lock‑free structures` · `LSM‑Tree` · `WAL`

**DevOps / Calidad:**  
`Git` · `GitHub Actions` (próximamente) · `Ruff` · `pre‑commit`

---

## 📫 Contacto y redes

- **Email:** baltablanco9008@gmail.com  
- **LinkedIn:** [baltasar_blanco](https://linkedin.com/in/baltasarblanco) *(si tenés, ponelo; si no, crealo)*  
- **Instagram:** [@baltasar_blanco](https://instagram.com/baltasar_blanco)  
- **GitHub:** [baltasarblanco](https://github.com/baltasarblanco) (estás aquí)

---

## 🎯 Filosofía de ingeniería

> *“No hay abstracción inocente. Cada línea de código se ejecuta sobre un procesador que solo entiende ciclos y bytes. Conozco ambos mundos: el de la entrega rápida y el de la eficiencia absoluta.”*

---

<p align="center">
  <i>“Construyo para que el negocio funcione hoy, y para que la máquina respete al máximo cada nanosegundo.”</i>
</p>
