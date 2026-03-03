I like building backend systems and developer tools.

## Featured Projects

### Project Analyzer (Capstone)
[Repository](https://github.com/COSC-499-W2025/capstone-project-team-7)

Desktop application that scans local software projects and converts them into structured portfolio entries and resume bullets using real code evidence.

The system analyzes source code, git history, and project artifacts to extract technologies, skills, and contributions.

**Core Features**

- **Project Scanning** – analyzes repositories for languages, file metrics, git history, media, and documents  
- **Skills Extraction** – detects frameworks, algorithms, and engineering patterns from code  
- **Contribution Analysis** – evaluates git history to estimate contributor roles and ownership  
- **Resume Generation** – produces structured resume bullets from scanned projects  
- **Portfolio Management** – organize and rank projects with custom roles and chronology  
- **Optional AI Insights** – deeper summaries using OpenAI (user-provided key)

**Architecture**

- **Frontend:** Next.js + React + TypeScript  
- **Backend:** FastAPI (Python) with modular analyzers  
- **Database:** Supabase (PostgreSQL)  
- **Desktop:** Electron wrapper for local-first workflow

**Tech Stack**

Next.js • React • TypeScript • FastAPI • Python • Supabase • PostgreSQL • Electron

---

### CommitGen
[Repository](https://github.com/joaquinalmora/commitgen)

CLI tool that generates structured commit messages from git diffs.

Built in Go with:
- git hook integration  
- configurable prompts  
- caching and fallback logic  
- CI/CD release automation

---

### Course Hover Info
[Repository](https://github.com/joaquinalmora/hover-course)

Chrome extension that surfaces grade distributions and professor ratings directly inside UBC course pages.

Built using:
- Manifest V3 architecture  
- background + content scripts  
- API aggregation  
- local preference storage
