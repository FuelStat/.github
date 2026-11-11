# FuelStat

**FuelStat** is a multi-platform application ecosystem designed to track, manage, and analyze vehicle fuel consumption and charging sessions with absolute data privacy and cross-platform parity.

---

## 🏗️ The Ecosystem

The project is split into decoupled, dedicated repositories to ensure clean separation of concerns and automated, agentic development:

| Repository | Tech Stack | Description |
| :--- | :--- | :--- |
| **[fuelstat/fuelstat](https://github.com/FuelStat/fuelstat)** | PHP, Node.js, PostgreSQL | **Core Server & Web Frontend:** Central API, database schema, and browser client. |
| **[fuelstat/fuelstat-ios](https://github.com/FuelStat/fuelstat-ios)** | Swift, SwiftUI | **iOS Application:** Native mobile client optimized for Apple platforms. |
| **[fuelstat/fuelstat-android](https://github.com/FuelStat/fuelstat-android)** | Kotlin, Jetpack Compose | **Android Application:** Native mobile client built with modern Compose UI. |

---

## 📐 Architecture & Standards

To maintain absolute design and functional parity across Web, iOS, Android, and PWA, the ecosystem relies on strict, shared standards:

* **API-First Design:** All communication is bound to a centralized OpenAPI specification (`docs/openapi.1.0.0.yaml` in the main repo).
* **Unified Design System:** Shared tokens, color palettes, and platform-native UI guardrails are enforced via `docs/DESIGN.md`.
* **Autonomous Development:** The repositories are optimized for automated, multi-agent CI/CD workflows and AI-driven issue resolution.

---
