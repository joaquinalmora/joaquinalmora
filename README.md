# Joaquin Almora

I build full-stack systems, developer tooling, automation, and small shipped products.

<p align="center">
  <a href="mailto:joaquin.almora@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-374151?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/jalmora">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-374151?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</p>
<p align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-1f2937?style=flat-square&logo=openjdk&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1f2937?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Postgres" src="https://img.shields.io/badge/Postgres-1f2937?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-1f2937?style=flat-square&logo=docker&logoColor=white" />
</p>

---

## Selected work

### 🧩 [Wordoku](https://apps.apple.com/ca/app/wordoku/id6762939318)
SwiftUI letter-sudoku puzzle app released on the iOS App Store.

- Built letter-based 9x9 Sudoku with hidden-word reveals and solver-backed puzzle generation
- Added Daily Challenge, streaks, undo/redo, and local-only progress with no accounts or tracking
- **Stack:** Swift

### 🧰 [DevFolio](https://github.com/COSC-499-W2025/capstone-project-team-7)
Desktop app for turning local repositories into structured portfolio and resume material.

- Analyzes source code, commit history, and project artifacts instead of relying on manual summaries
- Built around a pipeline that extracts engineering signals and turns them into reusable project data
- **Stack:** Next.js, TypeScript, FastAPI, Python, Supabase, Electron

### ⚙️ [CommitGen](https://github.com/joaquinalmora/commitgen)
CLI for generating structured commit messages directly from git diffs.

- Integrates with git hooks so the workflow stays lightweight and consistent
- Focused on practical enforcement rather than adding another manual step
- **Stack:** Go, Git hooks

### 🌐 [Course Hover Info](https://github.com/joaquinalmora/hover-course)
Chrome extension that adds course context directly into university pages.

- Injects grade distribution and professor rating data without changing the original site
- Built to surface useful information in-place instead of sending users somewhere else
- **Stack:** JavaScript, Chrome Extensions

---

## Other engineering work

### 📦 Contract system
**WhatsApp receipt processing pipeline**

- Processed receipt images through OpenAI Vision and returned structured confirmations over WhatsApp
- Added retry queues, dead-letter handling, stale-confirmation suppression, and deployment validation safeguards
- Reached **~0.78s median end-to-end latency**

### 🔧 Open source
- **[Kubetail](https://github.com/kubetail-org/kubetail):** auth caching, RBAC log access support, CI expansion for more Ubuntu architectures
- **[Nautobot](https://github.com/nautobot/nautobot):** clearer runtime error handling for config issues
- **[Grafana k6](https://github.com/grafana/k6):** reliability fix for missing-configuration edge cases
- **[go-fast-cdn](https://github.com/kevinanielsen/go-fast-cdn):** proposed Redis bloom-filter approach for leaner metadata lookups

---

## Now

- Building Python tooling and automation for parking operations at UBC
- Maintaining Wordoku, a released iOS word puzzle game
