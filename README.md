# Project Documentation Template

## Purpose

This repository provides a documentation-first structure for managing
professional software projects from requirements through testing.

The goal is to keep specifications, design, and tests:

- Text-based
- Version controlled
- Easy to review and maintain

---

## Documentation Flow

This project follows a standard delivery lifecycle:

1. **Project Setup**
2. **Requirements Definition**
3. **Basic (High-Level) Design**
4. **Detailed (Low-Level) Design**
5. **Implementation**
6. **Unit Testing**
7. **Integration Testing**

Each phase has its own folder and README.

---

## Folder Guide

### `docs/00_project/`

Project-wide reference documents:

- Scope and assumptions
- Glossary
- Roles (RACI)
- Decision log
- Meeting notes

Start here when joining the project.

---

### `docs/01_requirements/`

Defines **what** the system must do and **why**.

Includes:

- Business requirements
- User stories / use cases
- Non-functional requirements
- Acceptance criteria
- Business flow diagrams

---

### `docs/02_basic_design/`

Defines **how the system is structured**.

Includes:

- System overview
- Architecture
- Data model overview
- API list
- Screen list
- Error-handling policy

---

### `docs/03_detailed_design/`

Defines **exact implementation details**.

Includes:

- Module definitions
- Database schemas
- API request/response formats
- Screen specifications
- Batch and report specs
- Detailed sequence diagrams

Developers should be able to implement without additional clarification.

---

### `docs/04_implementation/`

Defines **how code is written and merged**.

Includes:

- Coding guidelines
- Branching strategy
- Pull request rules
- Definition of Done

---

### `docs/05_unit_testing/`

Defines **how individual components are tested**.

Includes:

- Unit test policies
- Test case matrices
- Unit test case definitions

---

### `docs/06_integration_testing/`

Defines **end-to-end behavior and system validation**.

Includes:

- Integration test policy
- Test scenarios
- Environment and test data
- End-to-end test cases

---

## Diagram Rules

- Diagrams are stored as `.drawio` files
- Each diagram should be small and focused
- Avoid multiple people editing the same diagram simultaneously
- `.drawio` files are the source of truth

---

## How to Use This Template

1. Copy this repository
2. Rename folders/files as needed
3. Fill documents top-down:
   - Requirements → Design → Tests
4. Keep docs updated alongside code changes
