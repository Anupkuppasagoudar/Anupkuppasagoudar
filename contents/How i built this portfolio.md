# Building a Dynamic Portfolio with Angular 21 & GitHub API

This portfolio isn't just a static resume—it's a real-time integration of modern web technologies, designed to demonstrate autonomous execution and technical ownership.

## 🏗️ The Architecture
The application is built on **Angular 21**, leveraging the latest "Zoneless" capabilities for peak performance. Instead of a traditional backend, I use **GitHub as a Headless CMS**.

### Core Tech Stack
* **Frontend:** Angular 21 (Zoneless, Signals)
* **UI Framework:** Angular Material
* **Data Source:** GitHub REST API
* **Styling:** SCSS with Unified Material Design tokens
* **Rendering:** `ngx-markdown` for dynamic article injection

## 🚀 Key Features

### 1. GitHub-as-CMS Flow
To keep the portfolio updated without redeploying code, I built a dynamic fetch engine.
* **Discovery:** The app hits the GitHub Content API to list `.md` files in a specific repo folder.
* **Lazy Loading:** Article content is only fetched when a user expands the accordion, saving bandwidth and improving initial load speed.
* **Automated Formatting:** Custom Angular Pipes handle filename-to-title translation and date calculations.

### 2. Unified UI/UX
The design follows a "Blueprint" philosophy, ensuring that technical specs and personal identity share a cohesive visual language. 

## 🔗 Project Links
* **Source Code:** [GitHub Repository](https://github.com/Anupkuppasagoudar/Anupkuppasagoudar)
* **LinkedIn:** [Anup Kuppasagoudar](https://www.linkedin.com/in/anup-kuppasagoudar/)
* **Live Portfolio:** [Your Hosted URL Here]

---
*Created by Anup Kuppasagoudar | Fullstack Software Engineer*
