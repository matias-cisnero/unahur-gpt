# 🤖 UNAHUR-GPT

UNAHUR-GPT es un proyecto que permite montar un sistema tipo *ChatGPT* con **modelos locales**, accesible desde una interfaz web amigable.  
Todo se ejecuta en contenedores **Docker**, integrando:

- **Ollama** → motor de modelos de lenguaje locales (Llama 3, Mistral, Gemma, etc.).  
- **Open WebUI (versión propia)** → interfaz gráfica web para interactuar con los modelos.  
- **PostgreSQL** → base de datos para gestionar usuarios y sesiones.  
- **n8n** → herramienta de automatización y orquestación de agentes.  

---

## 🚀 Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/matias-cisnero/unahur-gpt
   cd unahur-gpt
   ```

2. Levantar los contenedores:
   ```bash
   docker compose up -d --build
   ```

---

## 📌 Objetivo

Este proyecto busca brindar a la comunidad académica de la **UNAHUR** un entorno de inteligencia artificial local, privado y extensible, evitando depender de servicios externos.

---
