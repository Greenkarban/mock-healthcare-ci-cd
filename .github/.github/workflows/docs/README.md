# Mock Healthcare App CI/CD Showcase

This repository demonstrates how a Product Manager / Business Analyst can collaborate with engineering and DevOps teams by structuring product documentation, workflows, and CI/CD pipelines in GitHub.

It includes:
- **Documentation**: Product requirements, workflow diagrams, and supporting artifacts.
- **CI/CD Pipeline**: A sample GitHub Actions workflow for build → test → deploy.
- **Collaboration Tools**: Pull request template and changelog for structured releases.

---

## 🚀 CI/CD Workflow
The pipeline (`.github/workflows/ci-cd-pipeline.yml`) covers:

1. **Commit / Push** – Developer pushes code.
2. **Build & Test** – Automated build and unit tests run.
3. **Deploy to Staging** – Code deployed to a staging environment.
4. **Manual Approval** – PM/QA sign-off.
5. **Deploy to Production** – Release pushed to production.

![CI/CD Diagram](docs/ci_cd_workflow.png)

---

## 📂 Repo Contents
- `docs/` → Product requirements, diagrams, showcase PDF
- `.github/` → GitHub templates and workflows
- `src/` → Placeholder application source
- `tests/` → Placeholder test scripts
- `CHANGELOG.md` → Release notes

---

## 📌 Context
This repo is a **work product showcase** to illustrate my ability as a Product Manager / BA to:
- Document workflows and requirements
- Collaborate using GitHub & DevOps practices
- Bridge communication between Product, Engineering, and Business teams
