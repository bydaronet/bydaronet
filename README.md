<h1 align="center">Hola, soy Darío 👋</h1>
<p align="center"><strong>Español</strong> · <a href="#english">English</a></p>

<p align="center">
Fundador de <strong>UpTech</strong> 🇦🇷 — construyo y vendo software a medida para
empresas reales: plataformas para ISPs, sistemas de gestión, <strong>IA conversacional</strong>
y automatización que eliminan trabajo manual.
</p>

---

### 🧭 Sobre mí
- 👷 Fundador de **UpTech**: convierto problemas operativos en productos que se usan todos los días.
- 🧰 Full-stack pragmático: **Go** en el backend, **React** en el front, **PostgreSQL** y **Docker** en producción.
- 🤖 **IA conversacional + RAG**: pipelines con LLMs (Claude / Ollama), índices vectoriales, intent parsing, scope-guard anti-jailbreak y agentes autónomos.
- 🧗 +46, autodidacta y en aprendizaje continuo. Mi fórmula: **claridad, disciplina y mejora continua.**
- 📍 Argentina
- 🔒 Mis productos son comerciales — el código es privado, pero acá te muestro **qué resuelven**.

### 🛠️ Stack
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
<br />
![Anthropic Claude](https://img.shields.io/badge/Anthropic%20Claude-D97757?logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate%20%2F%20pgvector-1B1F3B?logo=weaviate&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-7C3AED)

### 🚀 Productos destacados
| Producto | Qué resuelve |
|----------|--------------|
| **Upico4** | Plataforma para ISPs que cierra la brecha entre la **administración comercial** y el **aprovisionamiento técnico**: facturación recurrente automática, integración con pasarelas de pago, gestión de ancho de banda/aprovisionamiento por API y **ticketing (helpdesk)** integrado. |
| **Portal de Clientes V4** | Portal de autogestión para clientes de ISP: pagos con **conciliación automática** (OCR + webhooks), estado de cuenta y soporte. |
| **UpFlow** | Plataforma de gestión **multi-rubro** con 5 verticales: **VetFlow** (veterinarias), **BarberFlow** (barberías), **BeautyFlow** (spa & estética), **DentistFlow** (odontología) y **ComercialFlow** (asesores comerciales). |
| **Zearch** | Buscador inmobiliario **conversacional** multi-agencia: consultas en lenguaje natural con **RAG** sobre índice vectorial y scraping autónomo multi-fuente. *(detalle abajo 👇)* |

### 🔎 En foco: Zearch
**Buscador inmobiliario conversacional multi-agencia con IA, RAG y scraping autónomo.** Indexa el contenido público de varias inmobiliarias (web, Instagram, TikTok, YouTube, APIs Xintel/Tokko y medios editoriales) y deja consultarlo en **lenguaje natural** con un pipeline de IA de punta a punta:

- 🧠 **RAG sobre índice vectorial** (Weaviate · pgvector) — recuperación semántica + BM25 sobre el catálogo indexado.
- 💬 **Pipeline conversacional**: *intent parser* con LLM (operación, tipo, zona, presupuesto y características, con **contexto histórico** y fallback a regex) → retrieval estructurado → *synthesizer* que responde **citando propiedades** y evita alucinaciones, en **streaming (SSE)**.
- 🔀 **LLM pluggable** tras una sola interfaz: **Anthropic Claude** (cloud) u **Ollama** (Qwen3, server propio), incluido **modelo de visión** (Qwen3-VL) que enriquece las imágenes scrapeadas.
- 🛡️ **Scope guard + hardening**: clasificador LLM pre-retrieval que rechaza consultas fuera del rubro y system prompt blindado contra jailbreaks.
- 🤖 **Scraping autónomo** multi-fuente (Go + Colly) con scheduler cada 6 h y reindexado en paralelo.

<sub>Stack: Go (Gin) · React + Tailwind · Weaviate/pgvector · SQLite/Postgres · Anthropic/Ollama · Docker.</sub>

### 💼 ¿Necesitás software a medida?
Construyo soluciones para ISPs, comercios, pymes e inmobiliarias — incluyendo **IA conversacional** sobre tus propios datos. Hablemos:
- ✉️ **bydaro@gmail.com**

> _"La disciplina es el puente entre las metas y los logros."_

---

<h3 id="english">🇬🇧 English</h3>

Founder of **UpTech** 🇦🇷 — I build and sell custom software for real businesses:
ISP platforms, management systems, **conversational AI**, and automation that kills
manual work. Pragmatic full-stack builder (**Go · React · PostgreSQL · Docker**) with
deep work in **LLM pipelines & RAG** (Claude / Ollama, vector search, intent parsing,
anti-jailbreak scope guards). 46, self-taught and always learning.

My products are commercial (the code is private), but here is **what they solve**:

- **Upico4** — ISP platform bridging **commercial administration** and **technical provisioning**: automated recurring billing, payment-gateway integration, API-driven bandwidth/provisioning, and integrated **ticketing (helpdesk)**.
- **Portal de Clientes V4** — ISP customer self-service portal: payments with **automatic reconciliation** (OCR + webhooks), account status, and support.
- **UpFlow** — **multi-vertical** management platform: VetFlow (vets), BarberFlow (barbershops), BeautyFlow (spa & beauty), DentistFlow (dentists), ComercialFlow (sales reps).
- **Zearch** — multi-agency **conversational real-estate search engine**. End-to-end AI pipeline: **RAG** over a vector index (Weaviate / pgvector), LLM **intent parser** with conversation context, an answer **synthesizer** that cites listings and avoids hallucinations (streaming SSE), a **pluggable LLM** layer (Anthropic Claude / Ollama Qwen3 + Qwen3-VL vision), an LLM **scope guard** against off-domain queries & jailbreaks, and **autonomous multi-source scraping** (Go + Colly).

Need custom software — or conversational AI over your own data? → **bydaro@gmail.com**
