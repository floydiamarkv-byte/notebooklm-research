<div align="center">

# 🔬 notebooklm-research

[![CI](https://github.com/floydiamarkv-byte/notebooklm-research/actions/workflows/ci.yml/badge.svg)](https://github.com/floydiamarkv-byte/notebooklm-research/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
### **Autonomous Deep Research Engine & Knowledge Vault Compiler**

[![Floydia Project](https://img.shields.io/badge/Powered%20By-Floydia-10D2AD.svg?style=for-the-badge&logo=crystal&logoColor=white&labelColor=0B111C)](https://floydia.site)
[![MCP](https://img.shields.io/badge/Protocol-NotebookLM%20MCP-4285F4?style=for-the-badge&logo=google&logoColor=white&labelColor=0B111C)](https://notebooklm.google.com)
[![Agentic AI](https://img.shields.io/badge/Agentic%20Engine-Antigravity%20%2F%20Claude%20Code-10D6BD?style=for-the-badge&logo=openai&logoColor=white&labelColor=0B111C)](https://floydia.site)
[![License: MIT](https://img.shields.io/badge/License-MIT-70CBAC?style=for-the-badge&labelColor=0B111C)](LICENSE)

<br/>

> **"Transform raw queries into rigorous, multi-perspective knowledge vaults. Built on NotebookLM MCP and the MIT Research Method to eliminate hallucinations."**

[🚀 Quick Start](#-quick-start) • [🏛️ Research Architecture](#-research-architecture) • [📦 Deliverables](#-structured-deliverables) • [🛠️ MCP Tools](#-mcp-tools-matrix) • [🤝 Support](#-author--support)

</div>

---

## 📌 Overview

**notebooklm-research** is an autonomous AI agent skill built for **Google Antigravity, OpenCode, Claude Code, and Cursor**. It orchestrates the official **Google NotebookLM MCP Server** to conduct exhaustive, multi-source investigations on any technical, scientific, or market domain.

Unlike simple web-search prompts that hallucinate summaries from top Google snippets, `notebooklm-research`:
1. **Curates 50 to 100+ Verified Sources**: Imports full papers, technical docs, and articles directly into private NotebookLM notebooks.
2. **Applies the MIT Deep Research Method**: Stress-tests findings across 5 Mental Models (First Principles, Second-Order Thinking, Inversion, Pareto, Red Teaming) and 3 Expert Debates.
3. **Compiles Complete Obsidian Knowledge Vaults (MOC)**: Delivers structured Markdown archives with inline grounding citations `[Source N]`, interactive mindmaps, audio overviews, and open inquiry matrices.

---

## 🏗️ Research Architecture

```mermaid
flowchart TD
    subgraph Phase 1: Intake & Exploration
        A[🎯 Research Topic & Intent] --> B[📋 Scope & Depth Framing]
        B --> C[🔍 NotebookLM MCP `research_start`]
    end

    subgraph Phase 2: Knowledge Ingestion
        C --> D[📥 Multi-Source Discovery & Curation]
        D -->|50-100+ Sources| E[📚 Dedicated Notebook Vault]
    end

    subgraph Phase 3: MIT Multi-Perspective Synthesis
        E --> F[🧠 5 Mental Models Analysis]
        E --> G[⚔️ 3-Way Expert Debates & Inversion]
        F & G --> H[📊 Grounded Insights & Citations]
    end

    subgraph Phase 4: Deliverables Matrix
        H --> I[📄 Executive Brief 500-800w]
        H --> J[📑 Technical Deep-Dive Report]
        H --> K[🗺️ Mermaid Mindmap & MOC]
        H --> L[🎙️ NotebookLM Audio / Slides]
    end

    style A fill:#0B111C,stroke:#10D2AD,color:#fff
    style B fill:#152638,stroke:#10D6BD,color:#fff
    style C fill:#10D2AD,stroke:#0B111C,color:#0B111C
    style D fill:#152638,stroke:#70CBAC,color:#fff
    style E fill:#0B111C,stroke:#10D2AD,color:#fff
    style F fill:#152638,stroke:#10D6BD,color:#fff
    style G fill:#152638,stroke:#10D6BD,color:#fff
    style H fill:#10D2AD,stroke:#0B111C,color:#0B111C
    style I fill:#152638,stroke:#70CBAC,color:#fff
    style J fill:#152638,stroke:#70CBAC,color:#fff
    style K fill:#152638,stroke:#70CBAC,color:#fff
    style L fill:#152638,stroke:#70CBAC,color:#fff
```

---

## 📦 Structured Deliverables

For every research task, the engine generates an isolated, publication-ready directory:

```
INVESTIGACION_{PROJECT_SLUG}/
├── README.md               ← Master Table of Contents with relational links
├── resumen_ejecutivo.md     ← High-impact 500-800 word executive briefing
├── informe_detallado.md     ← Exhaustive thesis with inline citations [Source N]
├── mapa_mental.md           ← Complete Mermaid mindmap hierarchy
├── fuentes.md               ← Verified source audit: URL, Date, Relevance score
└── preguntas_abiertas.md    ← Unresolved questions & future inquiry roadmap
```

---

## 🚀 Quick Start

### 1. Install Skill in Your Agent Environment

```bash
# For Google Antigravity / OpenCode / Claude Code
mkdir -p ~/.gemini/antigravity/skills/notebooklm-research
git clone https://github.com/floydiamarkv-byte/notebooklm-research.git ~/.gemini/antigravity/skills/notebooklm-research
```

### 2. Prerequisites
- Configured and running **NotebookLM MCP Server**
- Authenticated Google account with access to [NotebookLM](https://notebooklm.google.com)

### 3. Usage Examples

Just ask your AI agent naturally:
- *"Realiza una investigación profunda sobre arquitecturas de memoria vectorial para agentes autónomos."*
- *"Deep-dive research on Post-Quantum Cryptography standards for enterprise Linux."*
- *"Compila un dossier técnico sobre microservicios vs arquitecturas modulares en 2026."*

---

## 🛠️ MCP Tools Matrix

| Tool | Capability |
|------|------------|
| `notebook_create` | Initializes dedicated research workspace |
| `notebook_add_url/text` | Ingests URLs, PDFs, whitepapers & local files |
| `research_start` | Dispatches autonomous web & Drive deep searches |
| `research_poll` ➔ `research_import` | Evaluates and imports discovered citations |
| `notebook_query` | Grounded cross-querying without LLM hallucination |
| `report_create` | Formats comprehensive multi-chapter reports |
| `mind_map_generate` | Produces visual conceptual trees |
| `audio/video_overview_create` | Generates deep conversational podcast overviews |

---

## 👤 Author & Support

Developed by **[Floydia](https://floydia.site)** — Led by **Eliú Hurtado** (+25 years in IT systems, applied AI & automation).

* 🌐 **Website**: [https://floydia.site](https://floydia.site)
* 💼 **LinkedIn**: [Eliú Hurtado](https://linkedin.com/in/eliutec)
* 🐛 **Issues & Feedback**: [Open a GitHub Issue](https://github.com/floydiamarkv-byte/notebooklm-research/issues)

---

<div align="center">

Distributed under the [MIT License](LICENSE) • **Desde la infraestructura, todo.**

</div>
