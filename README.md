<div align="center">

<img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logoColor=white" alt="C#">
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
<img src="https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Flask-1F1F1F?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
<br>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
<img src="https://img.shields.io/badge/ML.NET-6C3FB5?style=for-the-badge&logoColor=white" alt="ML.NET">
<img src="https://img.shields.io/badge/Semantic%20Kernel-0078D4?style=for-the-badge&logoColor=white" alt="Semantic Kernel">
<img src="https://img.shields.io/badge/Ollama-111111?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">

<h1>Viviana De Los Angeles Flores Montes</h1>

<p><b>Ingeniería de Computación y Sistemas (USMP) · Desarrollo backend e IA aplicada · Lima, Perú</b></p>

<p>
Construyo aplicaciones web y APIs con .NET y Python, y les integro modelos de machine learning y agentes con LLM.<br>
Busco prácticas en desarrollo de software, datos e IA aplicada.
</p>

<img src="https://img.shields.io/badge/Estudiante-USMP%20%C2%B7%207.%C2%BA%20ciclo-1F3A93?labelColor=3C3C3C" alt="Estudiante USMP 7.º ciclo">
<img src="https://img.shields.io/badge/Participante-IAthon%20Construye%20Per%C3%BA%202026-8E44AD?labelColor=3C3C3C" alt="Participante IAthon Construye Perú 2026">
<img src="https://img.shields.io/badge/IA%20aplicada-ML.NET%20%C2%B7%20Semantic%20Kernel%20%C2%B7%20RAG-0E7C66?labelColor=3C3C3C" alt="IA aplicada">

</div>

---

## 🚀 Hackathon

**IAthon Construye Perú** (Sheads Data), oct. 2026, con **RescuePath AI**: sistema de IA que acompaña a los alumnos de programas con clases grabadas para reducir la deserción. Estuve a cargo de dos componentes:

- **Agente Batch:** procesa la transcripción de una clase y genera un resumen persistente y un índice de capítulos con timestamps. Probado con una clase de 3 h 30 min (282 segmentos, 17 capítulos).
- **Agente Tutor:** responde preguntas sobre la clase con RAG, descarta las que no son pertinentes y cita el minuto exacto del video donde está la respuesta.
- También estimé los costos de infraestructura, tokens y mantenimiento para llevar mis componentes a producción.

`Python` `FastAPI` `SQLite` `RAG` `LLM (Kimi K3 vía NVIDIA Build)`

---

## 🛠️ Proyectos

| Proyecto | Qué hace | Pila |
|---|---|---|
| [EcoPlantas](https://github.com/wallsunu/ECOPLANTAS) | Plataforma web de reciclaje para Cieneguilla: catálogo de plantas canjeables, registro de reciclaje con sesión y APIs REST documentadas. Incluye dos modelos de ML.NET (impacto del reciclaje y recomendación de planta) y **EcoBot**, un agente con Semantic Kernel que consulta datos reales de la app y responde con Ollama u OpenAI. Con Dockerfile multi-stage para Render. | C#, ASP.NET Core MVC, EF Core, PostgreSQL, Redis, ML.NET, Semantic Kernel, Docker |
| [API Inteligente de Tareas](https://github.com/wallsunu/ApiInteligenteTareas) | API REST de tareas con CRUD, filtros combinables por estado, prioridad y fechas, validaciones propias, consumo de una API externa y análisis de sentimiento de comentarios con ML.NET. | C#, ASP.NET Core Web API, EF Core, SQLite, ML.NET, Swagger |
| [Portal de Campañas](https://github.com/wallsunu/PC01) | Portal de campañas comerciales con filtros por categoría y estado, vista de detalle y resumen por canal. Trabajado con ramas `develop` y `main`, incluida la resolución de conflictos. | C#, ASP.NET Core MVC |
| [GameGaru Registro](https://github.com/wallsunu/GameGaruRegistro) | Registro de jugadores que valida el pago de matrícula antes de completar la inscripción. | C#, ASP.NET Core MVC |
| [App de nutrición](https://github.com/wallsunu/ALGORITMOS_I) | App web de hábitos saludables: login, plan de comidas, registro de nutrientes, peso y agua, calendario, recetas y foro. Proyecto final de Algoritmos I. | Python, Flask, SQLite, HTML/CSS/JS |

---

## 💼 Experiencia

- **Desarrolladora freelance**, SACOVI · 2026 – actualidad: plataforma de facturación.

---

## 🧰 Lo que he usado

| Área | Tecnologías |
|---|---|
| Backend | C#, ASP.NET Core (MVC y Web API), Entity Framework Core con migraciones, Python con Flask y FastAPI |
| Datos | PostgreSQL, SQLite, Redis para sesiones distribuidas |
| IA y ML | ML.NET (clasificación multiclase y análisis de sentimiento), Semantic Kernel con plugins nativos, LLM local con Ollama, OpenAI, RAG con citas verificables |
| APIs | REST, Swagger/OpenAPI, consumo de APIs externas, Google Maps API |
| Despliegue | Docker multi-stage, Render, configuración por variables de entorno |
| Seguridad | Contraseñas con BCrypt, rutas protegidas con sesión |
| Forma de trabajo | Git con ramas `feature/`, `fix/` y `docs/`, más de 20 pull requests integrados y commits convencionales |

---

## 📫 Contacto

<a href="https://www.linkedin.com/in/viviana-flores-montes/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:vivianafloresmontes9@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

