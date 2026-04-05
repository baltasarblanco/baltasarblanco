<!-- Badges dinámicos -->
<p align="center">
  <img src="https://img.shields.io/badge/Rust-1.85+-orange?logo=rust" />
  <img src="https://img.shields.io/badge/Python-3.12+-blue?logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-0.115+-teal?logo=fastapi" />
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

> *"Producto en Python. Poder en Rust."*

| Capa | Tecnologías | Propósito |
|------|-------------|-----------|
| **Táctica (L7)** | Python, FastAPI, SQLite, Pytest | Entregar valor comercial rápido, seguro y testeable. |
| **Estratégica (L3/L4)** | Rust, io_uring, zero‑copy IPC | Construir sistemas de ultra‑baja latencia y control total del hardware. |

---

## ⚙️ Portafolio – Lo que ya funciona

### 🦀 Vanguard Infrastructure Suite (Rust bare‑metal)

| Proyecto | Estado | Descripción | Métrica Clave |
|----------|--------|-------------|---------------|
| **[aegis-proxy](https://github.com/baltasarblanco/aegis-proxy)** | ✅ Completado | Proxy L4 TCP con io_uring, thread‑per‑core y zero‑alloc hot‑path. | **+8.4k RPS** · P99 <1ms |
| **[chronos_lsm](https://github.com/baltasarblanco/chronos_lsm)** | ✅ Completado | Motor Key‑Value LSM‑Tree con WAL, bloom filters y compactación. | **~15k reads/s · ~10.5k writes/s** |
| **[celer_mock](https://github.com/baltasarblanco/celer_mock)** | 🟡 En debugging | CEP engine zero‑copy con memfd_create + SCM_RIGHTS. | Pérdida <0.001% · Ring buffer en análisis |
| **[vanguard-infrastructure](https://github.com/baltasarblanco/vanguard-infrastructure)** | 🟡 En integración | Dashboard RYŪ + telemetría L7. | Visualización en tiempo real (backend pendiente) |

### 🐍 Bifrost (Python API – en construcción activa)

**Progreso real (semana 1 de 10):**  
██░░░░░░░░░░░░░░░░░░░░ 10%

| Hito | Estado | Detalle |
|------|--------|---------|
| CLI resiliente con httpx | ✅ | Manejo de excepciones, logs, timeouts. |
| FastAPI + Pydantic + Swagger | ⏳ | Siguiente paso (semana 2) |
| Persistencia SQLite | ⏳ | Semana 3 |
| PostgreSQL + SQLAlchemy + Alembic | ⏳ | Semana 4 |
| Autenticación JWT + bcrypt | ⏳ | Semana 5 |
| Pytest asíncrono + cobertura >70% | ⏳ | Semana 6 |
| Docker + docker‑compose + Makefile | ⏳ | Semana 7 |
| Reservas + timezone awareness | ⏳ | Semanas 8-9 |
| `SELECT FOR UPDATE` (bloqueo pesimista) | ⏳ | Semana 10 (final boss) |

> 🔥 **Próximo hito inmediato:** Subir el script CLI funcional y empezar FastAPI.

---

## 🛠️ Tecnologías que domino

**Lenguajes:**  
`Rust` · `Python` · `SQL`

**Backend / Sistemas (Python):**  
`FastAPI` · `Pydantic` · `SQLAlchemy` · `SQLite` · `Pytest` · `httpx`

**Bajo nivel / Rendimiento (Rust):**  
`io_uring` · `tokio‑uring` · `memfd_create` · `SCM_RIGHTS` · `mmap` · `thread‑per‑core` · `lock‑free structures` · `LSM‑Tree` · `WAL`

**DevOps / Calidad:**  
`Git` · `Ruff` (próximamente)

---

## 📫 Contacto

- **Email:** baltablanco9008@gmail.com  
- **Instagram:** [@baltasar_blanco](https://instagram.com/baltasar_blanco)  
- **GitHub:** [baltasarblanco](https://github.com/baltasarblanco)

---

## 🎯 Filosofía de ingeniería (en mis palabras)

> *"Aprendí Rust porque quiero seguridad extra. Construir un motor de almacenamiento o un compilador DSL me motiva más que una API comercial. Pero cuando hago producto, priorizo el MVP: algo sólido y usable lo antes posible. Prefiero **entender la máquina** que dominarla. La memoria importa: eso lo aprendí en Rust, y muchos que no lo usan no la tienen en cuenta."*

---

<p align="center">
  <i>“Sin humo. Código que funciona, métricas que respaldan.”</i>
</p>
