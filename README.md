#  Top Software Tools Finder with Use Case (LlamaCpp + Gradio)

##  Description

A smart, interactive Gradio app that leverages a **locally-run TinyLlama model** (via `LlamaCpp`) to recommend the **top 3 software tools** tailored to your specific **software type** and **use case**.

This app uses natural language prompting to understand your requirements and suggests the best-fit tools with concise, ranked descriptions. All processing is done locally – no external API calls or rate limits.

---

## Features

 Accepts any software type (e.g., CRM, ERP, BI Tools, Helpdesk)  
 Understands **specific use cases** like "tracking leads" or "remote team collaboration"  
 Returns top 3 tools with **non-redundant, clear descriptions**  
 Built on a **local LLM** (TinyLlama 1.1B) — no API keys or cloud calls  
 Clean and fast UI using **Gradio**  
 Deduplicates similar results and filters noise  
 Lightweight & fully open-source

---

##  Tech Stack

- **[LlamaCpp](https://python.langchain.com/docs/integrations/llms/llamacpp/)** via LangChain – Local LLM backend
- **TinyLlama 1.1B Chat GGUF** model (chat-tuned, small + fast)
- **Gradio** – For web UI
- **LangChain** – For prompt chaining

---
