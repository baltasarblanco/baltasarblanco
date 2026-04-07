<h1 align="center">Baltasar Blanco</h1>
<h3 align="center">Systems Engineer · Rust Core · Python Tactical</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-1.85+-orange?logo=rust" />
  <img src="https://img.shields.io/badge/Python-3.12+-blue?logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-0.115+-teal?logo=fastapi" />
  <img src="https://komarev.com/ghpvc/?username=baltasarblanco&label=Visitas&color=0e75b6&style=flat" />
</p>

---

## 🧠 Dual Mindset

> *“Producto en Python. Poder en Rust.”*

| Capa | Tecnologías | Propósito |
|------|-------------|-----------|
| Táctica (L7) | Python, FastAPI, SQLite, Pytest | Valor comercial rápido y testeable |
| Estratégica (L3/L4) | Rust, io_uring, zero‑copy IPC | Baja latencia, control del hardware |

---

## ⚙️ Proyectos destacados

### 🦀 Vanguard (Rust – completado / en debug)

- **[aegis-proxy](https://github.com/baltasarblanco/aegis-proxy)** – Proxy L4 TCP +8.4k RPS, P99 <1ms ✅  
- **[chronos_lsm](https://github.com/baltasarblanco/chronos_lsm)** – LSM‑Tree KV ~15k reads/s, ~10.5k writes/s ✅  
- **[celer_mock](https://github.com/baltasarblanco/celer_mock)** – CEP zero‑copy (debugging ring buffer) 🟡  
- **[vanguard-infrastructure](https://github.com/baltasarblanco/vanguard-infrastructure)** – Dashboard RYŪ (backend pendiente) 🟡  

### 🐍 Bifrost (Python – Motor transaccional)

**Progreso:** semana 9/10 · ██████████████████░░ 90%

| Avance | Estado |
|--------|--------|
| CLI resiliente (httpx) | ✅ |
| FastAPI + Swagger | ✅ |
| PostgreSQL + SQLAlchemy | ✅ |
| Migraciones (Alembic) | ✅ |
| Docker Compose (multi‑contenedor) | ✅ |
| Identidad (hashing Bcrypt) | ✅ |
| JWT Auth + roles (User/Admin) | ✅ |
| Reservas + timezones (UTC) | ✅ |
| Concurrencia (`SELECT FOR UPDATE`) | ✅ |
| Soft Delete + integridad referencial | ✅ |
| Paginación (offset/limit) | ✅ |
| Pytest >90% cobertura | ✅ |
| Pruebas estrés (1250 RPS) | ✅ |
| Ruff linting + format | ✅ |
| CI/CD (GitHub Actions) | ⏳ |

**🔥 Estado actual:**  
Motor de reservas con bloqueos pesimistas (sin overbooking).  
API stateless con JWT y diferenciación de roles (Usuario/Admin).  
Soft Delete implementado, paginación lista.  
Tests de integración aislados en memoria RAM.  
Rendimiento verificado: **1250 RPS** (Locust, 8 vCPUs / 16GB RAM).  
Cobertura de código: **90%** (pytest --cov).  
Calidad estática: **Ruff** (+700 reglas PEP-8).

**🚀 Próximo paso:**  
Pipeline CI/CD con GitHub Actions para validación automática en cada push.

**🛠️ Tecnologías clave:**  
![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-red?style=flat-square&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-2.5-5C2D91?style=flat-square&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-000000?style=flat-square&logo=ruff&logoColor=white)
![Locust](https://img.shields.io/badge/Locust-2.31-2E8B57?style=flat-square&logo=locust&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-3776AB?style=flat-square&logo=python&logoColor=white)
---

## 📫 Contacto

[Email](mailto:baltablanco9008@gmail.com) · [Instagram](https://instagram.com/baltasar_blanco) · [GitHub](https://github.com/baltasarblanco)

---

## 🎯 Mi filosofía

> *“Aprendí Rust por la seguridad extra. Construir un motor de almacenamiento o un compilador DSL me motiva más que una API comercial. Eso sí, cuando hago producto, priorizo el MVP: sólido y usable cuanto antes. Prefiero entender los procesos generales de un sistema que dominar un lenguaje en particular. Priorizo la velocidad. Ver nanosegundos en Rust te malacostumbra.”*
