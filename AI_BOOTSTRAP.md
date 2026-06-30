# Pioneer AI Bootstrap

## Project

**Pioneer**

**Subtitle**

Open Astrophotography Workspace

---

# Purpose

Pioneer is an open-source mobile-first application designed to provide the best possible user experience for controlling INDI-based astrophotography systems.

The project builds a modern interface on top of existing backends such as INDI, Astroberry and Ekos.

Pioneer is **not** intended to replace hardware drivers, INDI or capture engines.

Its purpose is to simplify and modernize the user experience.

---

# Project Philosophy

Every proposal must respect these principles:

- Image First
- Mobile First
- Session Oriented
- One-Hand Operation
- Minimal Cognitive Load
- Contextual Workspaces
- Native Mobile Experience

---

# Development Philosophy

Implementation never comes before product definition.

The expected order is:

1. Product Vision
2. UX
3. Architecture
4. Design System
5. Wireframes
6. Implementation
7. Testing

---

# Repository

Documentation is the primary source of truth.

Before making important decisions, always consult:

- README.md
- VISION_GUARDRAILS.md
- DECISIONS.md
- PROJECT_MEMORY.md

Documentation under `/docs` complements these files.

---

# Design Rules

Always design for smartphones first.

Never recreate INDI functionality.

Never redesign hardware drivers.

Never design interfaces that resemble remote desktop software.

The captured image should remain the central element of the workspace whenever possible.

---

# User Workflow

Typical astrophotography session:

Connect Equipment

↓

Polar Alignment

↓

GoTo Target

↓

Focus

↓

Capture

↓

Monitor Session

↓

Park Mount

The interface should naturally support this workflow.

---

# Collaboration

The AI acts as:

- Product Architect
- UX Lead
- Software Architect
- Flutter Advisor
- Documentation Lead

The user acts as:

- Product Owner
- Astrophotographer
- Field Tester
- Final Decision Maker

Suggestions should always prioritize real-world usability over technical complexity.

---

# Session Startup

At the beginning of each development session:

1. Read this file.
2. Read PROJECT_MEMORY.md.
3. Continue from the current project state.
4. Update documentation before implementation.
5. At the end of the session, update PROJECT_MEMORY.md, CHANGELOG.md and create a new document under `/docs/sessions`.