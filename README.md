# RAULSANCHEZ_PRUEBATECNICA_BG
# 📊 Banco Guayaquil - Asistente Financiero Inteligente

Bienvenido al **Asistente Financiero** desarrollado con tecnologías de IA. Esta herramienta te permite:

- 🤖 Consultar informes financieros en PDF usando un sistema inteligente de preguntas y respuestas (RAG - Retrieval-Augmented Generation).
- 💱 Realizar conversiones de moneda de forma rápida y sencilla, sin necesidad de API Key.

---

## 🚀 Funcionalidades

### 1️⃣ Consultas Inteligentes a PDFs
Sube tu informe financiero en PDF y realiza preguntas como:
- `"¿Cuál es el total de activos en 2023?"`
- `"¿Cuánto fue el pasivo corriente?"`

El sistema utiliza **LLM + Vectorstore (FAISS)** para buscar respuestas precisas dentro del documento.

---

### 2️⃣ Conversión de Moneda
Realiza conversiones escribiendo frases como:
- `150 EUR a USD`
- `1000 USD a COP`

Sin necesidad de registrarse en servicios externos.

---

## ⚙️ Tecnologías Utilizadas
- [Python](https://www.python.org/)
- [LangChain](https://www.langchain.com/) - Para la arquitectura RAG.
- [FAISS](https://github.com/facebookresearch/faiss) - Motor de búsqueda vectorial.
- [Gradio](https://gradio.app/) - Interfaz web rápida y sencilla.
- [OpenAI](https://openai.com/) - LLM para generación de respuestas.
- API pública de tipos de cambio: [open.er-api.com](https://www.exchangerate-api.com/).

---

## 📥 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
