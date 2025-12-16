# Basic Design (High-Level Design)

## Purpose
This folder defines **how the system is structured** at a high level, based on the approved requirements.
It should be detailed enough to align stakeholders and guide detailed design, but not so detailed that it becomes code.

## What belongs here (and what doesn’t)
### ✅ Included
- System overview and boundaries
- Architecture decisions (components, responsibilities, environments)
- High-level data model (entities and relationships)
- API list (endpoint catalog, auth approach, error format)
- Screen list / feature list (not per-screen specs)
- Error handling & logging policy
- Diagrams: deployment, overview sequence, overview ER

### ❌ Not included
- Full DB schema (column-by-column) → goes to **Detailed Design**
- Full API schemas and request/response examples → **Detailed Design**
- Per-screen behavior and validations → **Detailed Design**
- Unit test cases → **Unit Testing**

---

## Contents
- [`01_system_overview.md`](./01_system_overview.md)  
  What we are building, scope boundary, major assumptions.

- [`02_architecture.md`](./02_architecture.md)  
  Component responsibilities, integration points, key design decisions.

- [`03_data_model_overview.md`](./03_data_model_overview.md)  
  Entity overview and relationships (conceptual level).

- [`04_api_overview.md`](./04_api_overview.md)  
  Endpoint catalog, auth strategy, common headers, common error format.

- [`05_screen_list.md`](./05_screen_list.md)  
  Screen list (IDs + names) or feature list for UI apps.

- [`06_error_handling_policy.md`](./06_error_handling_policy.md)  
  Error codes, error response format, logging levels, retry policy.

---

## Diagrams
All diagrams are stored as `.drawio` source files.

- `diagrams/deployment.drawio`  
  Infrastructure view (environments, networks, major components)

- `diagrams/sequence_overview.drawio`  
  High-level request flow across components

- `diagrams/er_overview.drawio`  
  Conceptual ER (entities, relations, no full columns)

---

## Definition of Done (for Basic Design)
- Requirements are traceable to basic design elements (at least via references/links)
- All major components and responsibilities are explained
- “Happy path” and key error flows are documented at a high level
- Diagram set exists and matches the text
- Open decisions are captured in the project decision log (`docs/00_project/99_decision_log.md`)
