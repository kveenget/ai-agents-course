# AI Agents Course

Ejercicios y laboratorios de ingeniería de agentes de IA: OpenAI Agents SDK, CrewAI, LangGraph, AutoGen y MCP.

## Stack

- Python `>=3.12` (gestionado con `uv`)
- OpenAI, Anthropic, LangChain / LangGraph, CrewAI, AutoGen, MCP
- Gradio para interfaces, Playwright para automatización web

## Estructura

```
1_foundations/   Fundamentos de agentes
2_openai/        OpenAI Agents SDK
3_crew/          CrewAI
4_langgraph/     LangGraph
5_autogen/       AutoGen
6_mcp/           Model Context Protocol
guides/          Guías de referencia
setup/           Instrucciones de instalación por SO
```

## Setup

```bash
uv sync
cp .env.example .env   # añade tus API keys
```

Guías detalladas por SO en [`setup/`](setup/).

## Uso

Abrir los notebooks (`.ipynb`) en orden por carpeta. Para proyectos de CrewAI:

```bash
uv tool install crewai
crewai run
```

## Variables de entorno

Necesitarás claves para los proveedores que uses (`OPENAI_API_KEY`, `ANTHROPIC_API_KEY`, etc.) en el archivo `.env`.
