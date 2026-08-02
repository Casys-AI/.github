<div align="center">

<img src="logo.png" alt="Casys AI" width="96" />

# Casys AI

**Independent R&D studio — open source first**

MCP servers that connect AI agents to the systems holding engineering and
business data: SysML models, CAD, FEA, simulation, ERP, e-invoicing. Plus the
extraction toolkits that get data out of platforms with no API.
TypeScript and Deno, MIT.

<a href="https://casys.ai">casys.ai</a> ·
<a href="https://www.linkedin.com/showcase/casys-ai">LinkedIn</a> ·
<a href="mailto:hello@casys.ai">hello@casys.ai</a> ·
Taiwan

<br />
<br />

<a href="https://casys.ai">
  <img alt="casys.ai status" src="https://img.shields.io/website?url=https%3A%2F%2Fcasys.ai&amp;label=casys.ai&amp;style=flat-square" />
</a>
<img alt="Model Context Protocol" src="https://img.shields.io/badge/MCP-Model_Context_Protocol-6E56CF?style=flat-square" />
<img alt="Deno" src="https://img.shields.io/badge/Deno-000000?logo=deno&amp;logoColor=white&amp;style=flat-square" />
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&amp;logoColor=white&amp;style=flat-square" />

</div>

---

## Engineering chain

Model-to-physics tooling. Each server runs standalone; `engineering-toolchain`
bundles three of them into one image with the native solvers already installed.

| Repository | Scope | Signals |
| --- | --- | --- |
| [mcp-syson](https://github.com/Casys-AI/mcp-syson) | SysML v2 MBSE through SysON — 29 tools, AQL queries, requirements tracing, 4 UI viewers, docker-compose included. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-syson?style=flat-square) |
| [mcp-build123d](https://github.com/Casys-AI/mcp-build123d) | Parametric CAD as code (Python/OCCT) — exact mass properties, STEP/STL/GLTF export. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-build123d?style=flat-square) |
| [mcp-calculix](https://github.com/Casys-AI/mcp-calculix) | FEA — Gmsh meshing plus CalculiX linear static solve on STEP files. Faces designated by bounding box, mm/N/MPa. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-calculix?style=flat-square) |
| [mcp-modelica](https://github.com/Casys-AI/mcp-modelica) | OpenModelica system-level multiphysics simulation, reproducible runs. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-modelica?style=flat-square) |
| [mcp-onshape](https://github.com/Casys-AI/mcp-onshape) | Onshape CAD/PDM — 100 tools across 14 categories, 4 UI viewers. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-onshape?style=flat-square) |
| [constraint-solver](https://github.com/Casys-AI/constraint-solver) | Parametric constraints with units treated as part of the value — 2.5 kg against a 4 lb limit fails. Source-agnostic: SysML, FEA, cost models. | ![stars](https://img.shields.io/github/stars/Casys-AI/constraint-solver?style=flat-square) |
| [engineering-toolchain](https://github.com/Casys-AI/engineering-toolchain) | One Docker image: mcp-syson + mcp-build123d + mcp-calculix, with z3, Python/OCCT, Gmsh and CalculiX bundled. No native installs. | ![stars](https://img.shields.io/github/stars/Casys-AI/engineering-toolchain?style=flat-square) |

## Business systems

| Repository | Scope | Signals |
| --- | --- | --- |
| [mcp-erpnext](https://github.com/Casys-AI/mcp-erpnext) | ERPNext / Frappe — 120 tools across 14 categories, 7 interactive UI viewers. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-erpnext?style=flat-square) |
| [mcp-erp](https://github.com/Casys-AI/mcp-erp) | ERP-agnostic adapter layer — drop-in adapters for ERPNext, Dolibarr and more, meant to be embedded in a multi-tenant server. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-erp?style=flat-square) |
| [mcp-einvoice](https://github.com/Casys-AI/mcp-einvoice) | French e-invoicing — CII / UBL / Factur-X, PA-agnostic adapter pattern. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-einvoice?style=flat-square) |

## Framework

| Repository | Scope | Signals |
| --- | --- | --- |
| [mcp-server](https://github.com/Casys-AI/mcp-server) | Casys MCP Platform — middleware pipeline, OAuth2, concurrency control, backpressure, observability, interactive UIs. Published on JSR and npm. | ![stars](https://img.shields.io/github/stars/Casys-AI/mcp-server?style=flat-square) |

## Extraction toolkits

| Repository | Scope | Signals |
| --- | --- | --- |
| [ecommerce-platform-scraper](https://github.com/Casys-AI/ecommerce-platform-scraper) | Deno scraping toolkit for e-commerce storefronts, organised by platform — SHOPLINE / Cyberbiz / BV SHOP adapters, multimodal LLM + OCR extraction. Domain-agnostic. | ![stars](https://img.shields.io/github/stars/Casys-AI/ecommerce-platform-scraper?style=flat-square) |
| [formation-platform-scraper](https://github.com/Casys-AI/formation-platform-scraper) | Teachizy-hosted course platforms — dual auth, content extraction, Whisper transcription, link qualification, pedagogical knowledge graph. MCP Playwright embedded, nothing tenant-hardcoded. | ![stars](https://img.shields.io/github/stars/Casys-AI/formation-platform-scraper?style=flat-square) |

## Side project

| Repository | Scope | Signals |
| --- | --- | --- |
| [DenoClaw](https://github.com/Casys-AI/DenoClaw) | Deno-native AI agent framework — Subhosting + Sandbox + A2A protocol, zero Node.js deps. | ![stars](https://img.shields.io/github/stars/Casys-AI/DenoClaw?style=flat-square) |

---

<div align="center">
<sub>MIT unless the repository states otherwise · <a href="mailto:hello@casys.ai">hello@casys.ai</a></sub>
</div>
