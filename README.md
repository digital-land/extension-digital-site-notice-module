# Digital Site Notice Module (Extension to Planning Application Data Specification)

This repository contains an example **extension module** for the [Planning Application Data Specification](https://github.com/digital-land/planning-application-data-specification).

The module defines a **Digital Site Notice** — a structured summary of key development details intended for public display (e.g. online, on-site, or as part of digital engagement tools).

> 🧪 **This is a demonstrator** — it is **not part of the core specification**, but shows how extension modules _could_ be authored, shared, and integrated.

---

## 🔍 What this module includes

- A module definition (`digital-site-notice.md`)
- Conditional logic (`applies-if`) to apply the module only when a planning application is submitted to **Camden** (`local-authority:CMD`)
- A list of required fields such as:
  - Name of development
  - Construction period
  - Affordable housing percentage
  - Estimated jobs created
  - and more

See [`digital-site-notice.md`](./specification/module/digital-site-notice.md) for the full definition.

---

## 🌐 Relationship to the Core Specification

This module is:
- **Not part of the core specification**
- Designed to be **used alongside** standard application types and modules
- Written in the same structure and style for compatibility (currently experimenting with a more structured approach to defining modules)

It’s intended to show how third parties — such as local authorities, software providers, or policy groups — how they might define **optional or locally required modules**.

---

## 🚧 Open Questions and Next Steps

This repo helps us start the conversation about how extension modules should work.

We still need to explore:
- ✅ How and where extension modules are registered
- ✅ How they are discovered and loaded by validators or form builders
- ✅ How versioning and naming are managed
- ✅ How to reference shared structures (e.g. `document`, `person`) without duplication
- ✅ How to modules can be used across projects and ultimately hoisted into the core specification if there is community consensus

---

## 💬 Contributing / Discussion

We welcome issues, questions, and feedback! Please open a [GitHub Issue](https://github.com/your-org/digital-site-notice-module/issues) if you'd like to:

- Suggest improvements
- Propose a better way to structure extension modules
- Ask about reuse, registration, or tooling
