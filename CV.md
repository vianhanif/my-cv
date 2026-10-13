# Alvian Rahman Hanif

**Backend Engineer · Tech Lead @ PasarPolis Indonesia**

📧 alvian.hanif@pasarpolis.com · 📱 +62-821-1484-0131 · 📍 Depok, West Java, Indonesia  
🔗 [linkedin.com/in/vianhanif](https://www.linkedin.com/in/vianhanif) · [github.com/vianhanif](https://github.com/vianhanif)

---

## Professional Summary

Backend engineer specializing in insurtech — 6+ years building Golang & Python microservices on AWS/GCP for large-scale partner ecosystems (Gojek, Shopee, Lazada, ~30+ partners). Experience spans dynamic product configuration, multi-year policy engines, insurer API integrations, and commission platforms. Led the policy-side of a company-wide GCP→AWS migration (~15 microservices). Lead a squad owning production reliability, platform rollouts, and AI-assisted development tooling (playbook, environment bootstrap, internal CLIs).

---

## Technical Skills

**Languages:** Go (Golang), Python  
**Frameworks & Libraries:** Django, Celery  
**Cloud & DevOps:** AWS (SNS, SQS, S3), GCP (Pub/Sub, GCS, BigQuery), Kubernetes, Docker, Airflow, CircleCI  
**Databases:** PostgreSQL, Redis, Google BigQuery  
**Tools & Platforms:** Git, Linux, Playwright

---

## Professional Experience

### **Tech Lead** | PasarPolis | Jakarta, Indonesia  
*Jan 2026 – Present (10 months)*

Team: squad of 3–5 engineers

- Leading a squad of 3–5 engineers through a company-wide GCP→AWS migration across ~15 microservices: Pub/Sub→SNS/SQS, GCS→S3.
- Drive developer-experience and AI-tooling initiatives: Kubernetes multi-pod log CLI, provider-agnostic MR review CLI, shared API test collections.
- Authored the team engineering playbook and built a one-command bootstrap for AI-assisted development setup.
- Driving the Playwright E2E test suite — FE initiated the setup, then transitioned ownership to QA.
- Maintain architecture communications and alignments between stakeholders, leveraged with AI-assisted documentation.

### **Senior Software Engineer** | PasarPolis | Indonesia  
*Aug 2021 – Dec 2025 (4 years 5 months)*

- **PPIB team** — scaled partner reporting to ~30 partners; re-architected document-gen pipeline (Celery, Redis, per-partner queues, Kubernetes autoscaling); built dynamic product configuration system replacing per-product hardcoding; partnered with the claims team on automation for Shopee VN/SG, Tiki, and Kredivo.
- **Agency team** — built the agent commission platform spanning 3 services (pay-later windows, dynamic commission engine, Tokio Marine rules, double-deduction prevention); re-architected policy callback flow (REST→Pub/Sub) and fixed production issues (Redis hang, auth-pin deadlocks).
- **AUS team** — led core policy platform refactoring: multi-year policy support, addon/rider system, dynamic premium calculation, and product import/export; integrated with the vendor-based insurance backend (CARE) used by the operational team; extended IAM/integration layer (Django); stabilized addon premium configuration UI.

### **Software Engineer** | PasarPolis | Indonesia  
*Jan 2020 – Aug 2021 (1 year 8 months)*

Team: PPIB (under a tech lead)

- Onboarded new insurance products end-to-end in the core policy service: built each product in the core codebase, shared API contracts with 3rd-party partners (or wired them through the internal bulk-upload panel), and configured the per-product reporting pipeline.
- Delivered 30+ Airflow/BigQuery reporting pipelines for Gojek, Lazada, and DANA product launches — including COVID-19 protection product reporting. (Airflow platform maintained by the data-science team.)
- Developed core APIs for the document generation service, powering policy document creation.

### **Full Stack Engineer** | AIMSIS | Jl. Batu Tulis, Jakarta Barat  
*Sep 2019 – Dec 2019 (4 months)*

Contributed to maintaining a number of products related to a school management platform.

- Helped develop the AIMSIS 1.0 prototype, as a means to revamp the then-current version that was still duplicated for each school.
- Maintained the Student Registration system (PSB – Pendaftaran Siswa Baru).
- Developed new features & maintained the E-Library platform.
- Refactored code structure for better management.
- Implemented unit testing for APIs.
- Reconstructed the API deployment process from a traditional Linux service into a Docker container.
- Implemented CircleCI jobs to automate testing and deployment.

### **Software Engineer** | PT Payfazz Teknologi Nusantara | Greater Jakarta Area, Indonesia  
*Feb 2019 – Sep 2019 (8 months)*

- Developed back-end services in various forms (APIs, workers, event-bus, etc.).
- Tech used: Golang, PostgreSQL, Redis, Google Pub/Sub.

### **Frontend Engineer** | PT. Dinamika Mitra Sukses Makmur (DMSUM) | Greater Jakarta Area, Indonesia  
*Apr 2017 – Mar 2018 (1 year)*

- Developed and maintained web applications for DMSUM products, e.g. Mentimun and Mentimun Pay (available on Play Store).

---

## Personal Projects

### **9Router** | [github.com/vianhanif/9router](https://github.com/vianhanif/9router)
AI Router & Token Saver — connects 40+ AI providers & 100+ models with RTK token optimization (save 20-40% tokens), auto-fallback, and quota management. Deployed on npm, Docker, and GHCR. Active contributor & maintainer of upstream fork.

### **9Router API** | [github.com/vianhanif/9router-api](https://github.com/vianhanif/9router-api)
Lightweight LLM API server (~100-150MB footprint) as an alternative to the full 9Router Next.js dashboard. Syncs with 9Router core releases.

### **9Router Deploy** | [github.com/vianhanif/9router-deploy](https://github.com/vianhanif/9router-deploy)
Production Docker Compose stack for self-hosting 9Router with Cloudflare Tunnel ingress and automated CI/CD deploys to Tencent Cloud VPS.

### **git-review-cli** | [github.com/vianhanif/git-review-cli](https://github.com/vianhanif/git-review-cli)
Provider-agnostic MR/PR review CLI for GitLab, GitHub, and Gitea. Integrated into internal development workflows. Available on PyPI.

### **kubectl-multi-logs** | [github.com/vianhanif/kubectl-multi-logs](https://github.com/vianhanif/kubectl-multi-logs)
Tail logs from multiple Kubernetes pods simultaneously with real-time streaming and Homebrew-style progress display. Used internally for platform debugging.

### **opencode-tree** | [github.com/vianhanif/opencode-tree](https://github.com/vianhanif/opencode-tree)
Isolated development environments via git worktree + tmux for OpenCode agent sessions — clean context switching without stashing or branch conflicts.

### **opencode-session-viewer** | [github.com/vianhanif/opencode-session-viewer](https://github.com/vianhanif/opencode-session-viewer)
CLI tool to inspect OpenCode session metadata from the local SQLite database. Built in Go.

### **local-tunnel** | [github.com/vianhanif/local-tunnel](https://github.com/vianhanif/local-tunnel)
Production-grade HTTPS tunnel for local AI model servers — expose your local models to the internet securely.

### **mac-cleanup-go** | [github.com/vianhanif/mac-cleanup-go](https://github.com/vianhanif/mac-cleanup-go)
macOS maintenance tool in Go for identifying performance bottlenecks and safely cleaning long-lived system cruft.

---

## Education

**SARMAG (Sarjana & Magister), Computer Science** | Universitas Gunadarma | Indonesia  
*2012 – 2017*

- Recipient of the SarMag (Sarjana & Magister) Scholarship.

**Science** | SMA Lazuardi GIS | Indonesia  
*2009 – 2012*

**SMPN 4 Depok** | Indonesia  
*2006 – 2009*

**SD Yaspen Tugu Ibu Depok** | Indonesia  
*2000 – 2006*

---

## Honors & Awards

- **SarMag (Sarjana & Magister) Scholarship**

---

## Languages

- **Indonesian:** Native or Bilingual
- **English:** Professional Working
- **Korean:** Elementary
