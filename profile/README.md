<div align="center">

<img src="logo.png" alt="" width="104" />

# Casys AI

**Evidence-led infrastructure for engineering agents.**

Open-source [MCP](https://modelcontextprotocol.io/) servers and supporting tools
for system models, simulation, manufacturing checks, and operational workflows.

[Website](https://casys.ai) ·
[Repositories](https://github.com/orgs/Casys-AI/repositories) ·
[LinkedIn](https://www.linkedin.com/showcase/casys-ai) ·
[Contact](mailto:hello@casys.ai)

</div>

---

Casys is an independent R&D studio based in Taiwan. We build focused, composable
infrastructure around engineering and business systems.

Our products favour explicit contracts, reproducible execution, and structured
results that can move across models, solvers, agents, and teams.

## From model to evidence

`system architecture → geometry → physics → measured checks → reviewable evidence`

That chain runs end to end in
**[casys-digital-thread](https://github.com/Casys-AI/casys-digital-thread)**,
where one project holds the brief, the artifacts, and the evidence behind each
answer.

### Architecture and geometry

- **[mcp-syson](https://github.com/Casys-AI/mcp-syson)** — SysON-backed SysML v2
  modelling, queries, diagrams, requirements tracing, and constraint workflows.
- **[mcp-build123d](https://github.com/Casys-AI/mcp-build123d)** — parametric
  CAD with OCCT measurements and verifiable STEP, STL, and GLB exports.
- **[mcp-onshape](https://github.com/Casys-AI/mcp-onshape)** — access to Onshape
  CAD and PDM workflows.

### Simulation and mechanics

- **[mcp-calculix](https://github.com/Casys-AI/mcp-calculix)** — STEP-based
  finite-element analysis with Gmsh and CalculiX.
- **[mcp-modelica](https://github.com/Casys-AI/mcp-modelica)** — OpenModelica
  execution of qualified simulation kits.
- **[mcp-spice](https://github.com/Casys-AI/mcp-spice)** — ngspice
  operating-point and transient observations from content-addressed circuit
  netlists.
- **[mcp-chrono](https://github.com/Casys-AI/mcp-chrono)** — prescribed
  rigid-body kinematics with Project Chrono and recorded run evidence.

### Manufacturing and engineering checks

- **[mcp-dfm](https://github.com/Casys-AI/mcp-dfm)** — measured DFM checks on
  STEP geometry against caller-declared limits.
- **[mcp-prusaslicer](https://github.com/Casys-AI/mcp-prusaslicer)** — time and
  material statistics from exact STL and caller-owned PrusaSlicer profiles.
- **[mcp-tolerance](https://github.com/Casys-AI/mcp-tolerance)** — deterministic
  ISO 286-1 fits and one-dimensional tolerance stacks.
- **[constraint-solver](https://github.com/Casys-AI/constraint-solver)** —
  unit-aware constraint evaluation, satisfiability, and optimisation.

## Build and operate

- **[mcp-server](https://github.com/Casys-AI/mcp-server)** — a TypeScript
  framework for MCP middleware, OAuth integration, concurrency, observability,
  and MCP Apps.
- **[mcp-erpnext](https://github.com/Casys-AI/mcp-erpnext)** — ERPNext/Frappe
  documents, workflows, and interactive MCP App viewers.
- **[mcp-einvoice](https://github.com/Casys-AI/mcp-einvoice)** — French
  e-invoicing workflows and structured invoice formats through configurable
  provider adapters.

## More open-source work

Casys also maintains **[acpx](https://github.com/Casys-AI/acpx)**, a headless
client for stateful ACP sessions.

Our extraction toolkits cover
[e-commerce storefronts](https://github.com/Casys-AI/ecommerce-platform-scraper)
and
[learning platforms](https://github.com/Casys-AI/formation-platform-scraper).
[Browse all public repositories](https://github.com/orgs/Casys-AI/repositories).

## Built to compose

Start with one capability, then connect others as the workflow grows. Follow
each repository for its setup and examples.

---

<div align="center">
<sub>Independent R&D studio · Taiwan · <a href="mailto:hello@casys.ai">hello@casys.ai</a></sub>
</div>
