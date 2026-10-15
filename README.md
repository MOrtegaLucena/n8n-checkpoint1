# Checkpoint 1 - n8n AI Agent Workflow

Este repositorio contiene la entrega del **Checkpoint 1**, donde se implementa un workflow en n8n impulsado por un **AI Agent** (`gpt-4o`) integrado con una herramienta nativa para la automatización de comunicaciones corporativas.

---

## 🏗️ Arquitectura del Workflow

1. **Trigger (`Chat Trigger`):** Recibe la solicitud del usuario mediante la interfaz de chat de n8n.
2. **AI Agent (`gpt-4o`):** Procesa el mensaje del usuario, evalúa el contexto y determina de manera autónoma si requiere activar la herramienta de comunicación.
3. **Tool (`Send a message in Gmail`):** Herramienta conectada dinámicamente como extensión del agente para enviar propuestas y cotizaciones por correo electrónico.
4. **Observabilidad:** Registro y auditoría de la ejecución del flujo.

---

## 📄 Archivo del Proyecto

- `checkpoint1_Belen_Ortega.json`: Exportación completa del flujo en formato JSON listo para ser importado en n8n (*Import from File*).

---

**Autora:** María Belén Ortega Lucena
