# Pioneer

> **Open Astrophotography Workspace**

Pioneer is an open-source, mobile-first workspace for controlling INDI-based astrophotography systems.

Instead of replacing existing backends such as INDI, Ekos or Astroberry, Pioneer focuses on providing a modern, intuitive and efficient user experience designed specifically for smartphones and tablets.

The goal is simple:

> Keep the astrophotographer focused on the sky, not on the software.

---

# Why Pioneer?

Current astrophotography solutions are extremely powerful, but most of them were originally designed for desktop computers.

When accessed from smartphones through VNC or remote desktop applications, the experience becomes slow, crowded and difficult to use during field operation.

Pioneer aims to solve this problem by creating a native mobile workspace that communicates with the existing INDI ecosystem.

No hardware drivers are replaced.

No imaging engine is recreated.

Only the user experience is reinvented.

---

# Project Goals

- Mobile-first interface
- Session-oriented workflow
- One-hand operation
- Minimal cognitive load
- Contextual workspaces
- Fast access to critical controls
- Modern FITS image visualization
- Open-source architecture
- Native integration with INDI

---

# Planned Features

- Equipment Dashboard
- Camera Control
- Capture Plan
- Telescope Control
- Plate Solving
- Manual & Auto Focus
- Guiding Monitor
- FITS Image Viewer
- Session Dashboard
- Notifications
- Adaptive Layouts

---

# Architecture

```
Flutter / PWA
        │
        ▼
Optional Middleware
(FastAPI)
        │
        ▼
INDI Server
(Astroberry / Stellarmate / Native INDI)
        │
        ▼
Astronomical Equipment
```

Pioneer does not replace INDI.

Instead, it builds a modern workspace on top of the existing ecosystem.

---

# Current Status

Current Phase

> Product Definition

Current Focus

> Designing the Home Workspace

---

# Documentation

Project documentation is located under the `/docs` directory.

---

# Contributing

The project is currently under active design and architecture definition.

Contributions will be welcome once the first public milestone is available.

---

# License

MIT License