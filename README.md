# Diego Vega

**Desarrollador Multiplataforma (DAM) · Backend Python · Android & Flutter · IA/LLM**

<p align="left">
  <a href="mailto:diegoa.vegsil@gmail.com"><img src="https://img.shields.io/badge/Email-diegoa.vegsil%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/diego-andres-vega"><img src="https://img.shields.io/badge/LinkedIn-diego--andres--vega-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Burgos,%20España-remoto%20o%20presencial-555555?style=flat-square" alt="Burgos, España — remoto o presencial" />
</p>

Técnico Superior en Desarrollo de Aplicaciones Multiplataforma con experiencia construyendo y desplegando sistemas de IA **en producción real** durante mis prácticas en empresa: pipelines de composición de imagen, generación de renders con RAG visual, agentes autónomos e integraciones ERP–ecommerce. Fuera de las prácticas desarrollo producto propio de principio a fin — de la base de datos al móvil — como **Dividi**, mi aplicación de gastos compartidos con la API desplegada en producción y app Android en Flutter. Busco mi **primera oportunidad como desarrollador junior** (backend Python, IA/LLM o multiplataforma): un equipo del que aprender y al que aportar desde el primer día.

---

## Proyecto destacado — Dividi

Aplicación completa de gastos compartidos (estilo Tricount/Splitwise) desarrollada de principio a fin: modelo de datos, API REST, tests, despliegue y cliente móvil.

### API — [dividi-FastApi](https://github.com/DiegoAndresVega/dividi-FastApi)

`Python 3.12` `FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Pydantic v2` `Alembic` `JWT` `pytest` `Docker`

Grupos de gastos, 4 métodos de división (incluyendo porcentajes por persona configurables a nivel de grupo con override por gasto), balances netos, **simplificación automática de deudas** y registro por invitación. 86 tests entre unitarios de la lógica de negocio (redondeos, deudas circulares, importes de 1 céntimo) e integración de la API completa.

**En producción:** desplegada en Render con PostgreSQL en Neon — [dividi-api.onrender.com/docs](https://dividi-api.onrender.com/docs)

### App Android — [dividi-app](https://github.com/DiegoAndresVega/dividi-app)

`Flutter` `Dart` `JWT` `flutter_secure_storage`

Cliente móvil de la API: autenticación JWT con refresh y token cifrado en el dispositivo, gestión de grupos y gastos, reparto por porcentajes, invitados sin cuenta y settle-up guiado por la simplificación de deudas del backend.

---

## Experiencia en producción — Prácticas de empresa (Sustain Awards)

Sistemas reales, desplegados y en uso diario por la empresa.

### Pipeline de composición de imagen con IA

`Python` `Claude API` `Pillow` `ColourThief` `PyMuPDF` `PrestaShop API`

Pipeline de 5 capas que extrae logos de clientes desde PDFs, detecta su paleta de color dominante y los composita automáticamente sobre fotografías de producto, con Claude orquestando las decisiones de composición. Integrado con PrestaShop y desplegado en producción.

### Generador de renders fotorrealistas (RAG visual)

`Python` `CLIP` `Qdrant` `Flux.1` `Replicate` `Claude API`

Generación de renders de producto guiada por estilo: ~140 imágenes de referencia indexadas con embeddings CLIP en Qdrant, construcción de prompts por material orquestada con Claude y generación con Flux.1 + IP-Adapter. Diseñado como sistema modular extensible a nuevos materiales.

### Asistente empresarial autónomo

`Docker` `VPS` `MCP` `Navegación web` `Email` `Calendario`

Agente de IA desplegado con Docker en un VPS: navegación autónoma, gestión de correo y calendario, y ejecución de tareas delegadas, sobre arquitectura compatible con MCP.

### Sincronización de stock Odoo–PrestaShop

`Python` `Odoo API` `PrestaShop API` `pandas`

Sincronización de stock entre el ERP y la tienda online para un catálogo de más de 100 productos: extracción de IDs, transformación de datos y actualización automática.

---

## Portfolio personal

### [Costura](https://github.com/DiegoAndresVega/costura) — App Android para patrones de costura (proyecto final DAM)

`Kotlin` `MVVM` `Room` `Firebase (Auth · Firestore · Storage)` `Material Design 3`

App nativa Android para calcular la tela necesaria en patrones de costura y compartirlos en comunidad. Arquitectura MVVM, persistencia local con Room, backend con Firebase y navegación con Navigation Component.

### RAG 100% local — en desarrollo

`Python` `Ollama` `Qdrant`

Sistema de retrieval-augmented generation ejecutado íntegramente en local: embeddings, indexado vectorial en Qdrant y LLM servido con Ollama, sin dependencia de APIs externas.

### Otros proyectos

- [web_de_cumple](https://github.com/DiegoAndresVega/web_de_cumple) — web de evento con módulo para compartir coche y cuestionario para invitados. JavaScript + Firebase, usada por asistentes reales.

---

## Stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" title="Python" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin" title="Kotlin" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" alt="Dart" title="Dart" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" alt="Flutter" title="Flutter" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" alt="Firebase" title="Firebase" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" title="Linux / VPS" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" alt="Android Studio" title="Android Studio" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" title="VS Code" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" height="40" />
  <br><br>
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" title="Claude API / Anthropic" height="28" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code" title="Claude Code" height="28" />
  <img src="https://img.shields.io/badge/MCP-Model_Context_Protocol-1a1a1a?style=for-the-badge" alt="MCP" title="Model Context Protocol" height="28" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge" alt="Qdrant" title="Qdrant (base de datos vectorial)" height="28" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" title="Ollama" height="28" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render" title="Render (despliegue)" height="28" />
  <img src="https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black" alt="Neon" title="Neon (PostgreSQL serverless)" height="28" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" title="pandas" height="28" />
  <img src="https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Pillow" title="Pillow" height="28" />
  <img src="https://img.shields.io/badge/PrestaShop-DF0067?style=for-the-badge&logo=prestashop&logoColor=white" alt="PrestaShop" title="PrestaShop" height="28" />
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo" title="Odoo" height="28" />
</p>

**Lenguajes:** Python · Kotlin · Dart · Java · SQL · JavaScript · HTML/CSS · XML

**Backend & datos:** FastAPI · SQLAlchemy 2.0 · Pydantic · Alembic · REST APIs · JWT · PostgreSQL · MySQL · MongoDB · Firebase (Auth, Firestore, Storage) · pandas · pytest

**Móvil & multiplataforma:** Flutter · Android nativo (Kotlin) · MVVM · Room · Material Design 3

**IA & agentes:** Claude API · Claude Code · MCP (Model Context Protocol) · Agentes autónomos · Pipelines LLM · RAG · Embeddings (CLIP) · Qdrant · Ollama · Generación de imagen (Flux.1, IP-Adapter) · Pillow · PyMuPDF

**Infraestructura & herramientas:** Docker · Linux · VPS · SSH · Render · Neon · Git · VS Code · Android Studio

---

## Cómo trabajo

- **AI-augmented development** — uso LLMs como copiloto técnico, no como sustituto del criterio propio.
- **Entrega en producción** — priorizo que funcione en el entorno real, no solo en local.
- **Tests donde importan** — la lógica delicada (dinero, redondeos, deudas) va cubierta con tests exhaustivos.
- **Adaptación de stack** — aprendo lo que necesita el proyecto, sin esperar a tener el curso perfecto.
- **Documentación útil** — README y comentarios pensados para el siguiente que lo toque (o para mí en tres meses).

---

## Ahora mismo

- Evolucionando **Dividi**: mejoras en la app Flutter y un bot de Telegram como segundo cliente de la API.
- Construyendo un **RAG 100% local** (Ollama + Qdrant), sin dependencia de APIs externas.
- Profundizando en arquitecturas de agentes y **Model Context Protocol (MCP)**.
- Automatizando flujos de desarrollo con **Claude Code**.
- **Abierto a mi primera oportunidad**: junior backend Python / IA / multiplataforma · remoto o Burgos.

---

## Formación

- **Técnico Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)** — CIFP Juan de Colonia, Burgos · 2026
- **Inglés B2** — lectura técnica fluida, documentación y trabajo con recursos en inglés sin problema

---

<sub>diegoa.vegsil@gmail.com · [linkedin.com/in/diego-andres-vega](https://linkedin.com/in/diego-andres-vega) · Burgos, España</sub>
