# Scale Institutional Knowledge Using Copilot Spaces

## Main Function

This repository is a **GitHub Skills hands-on exercise** that teaches how to use [GitHub Copilot Spaces](https://docs.github.com/en/copilot/using-github-copilot/using-copilot-spaces) to scale and share institutional knowledge across a team. Using the fictional company **OctoAcme** as a case study, learners practice organizing project management documentation so that GitHub Copilot can use it as context — enabling any team member to quickly get accurate, role-aware guidance without having to track down the right person or document.

## Key Components

### 📁 `docs/` — OctoAcme Project Management Documentation

The core of the repository. Contains a set of structured Markdown files covering OctoAcme's end-to-end project management processes. These documents are the "institutional knowledge" that gets surfaced through Copilot Spaces.

| File | Description |
|---|---|
| [`docs/README.md`](docs/README.md) | Central index: methodology overview, process summary, and links to all documents. |
| [`octoacme-project-management-overview.md`](docs/octoacme-project-management-overview.md) | High-level approach, principles, roles, artifacts, and communication cadence. |
| [`octoacme-project-initiation.md`](docs/octoacme-project-initiation.md) | How to validate, authorize, and kick off new work. |
| [`octoacme-project-planning.md`](docs/octoacme-project-planning.md) | Backlog creation, release planning, and milestone mapping. |
| [`octoacme-execution-and-tracking.md`](docs/octoacme-execution-and-tracking.md) | Sprint delivery rhythm, PR workflow, quality practices, and blocker escalation. |
| [`octoacme-risks-and-communication.md`](docs/octoacme-risks-and-communication.md) | Risk Register structure, stakeholder communication templates, and escalation paths. |
| [`octoacme-release-and-deployment.md`](docs/octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, rollback playbook, and release notes template. |
| [`octoacme-retrospective-and-continuous-improvement.md`](docs/octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and converting learnings into tracked improvements. |
| [`octoacme-roles-and-personas.md`](docs/octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers. |

### ⚙️ `.github/` — Automation and Templates

- **`workflows/`** — GitHub Actions workflows that drive the step-by-step exercise progression (e.g., detecting when learners create issues or merge pull requests and advancing to the next step).
- **`ISSUE_TEMPLATE/`** — A structured issue form (`add-update-content-to-process-docs.yml`) that guides contributors in proposing additions or updates to the process documentation.
- **`steps/`** — Markdown instructions shown to the learner at each step of the exercise.
- **`images/`** — Screenshots used in the step-by-step instructions.

### 🛠️ `.devcontainer/`

Defines a development container so the exercise can be run in GitHub Codespaces or any compatible local environment with a consistent, pre-configured setup.

---

## How It Works

1. **Set up Copilot Spaces** — Learners create a Copilot Space and add this repository's `docs/` folder as a knowledge source.
2. **Ask role-based questions** — With the docs loaded as context, Copilot can answer questions like *"What steps does a Project Manager follow to kick off a new project?"* drawing directly from OctoAcme's documented processes.
3. **Contribute improvements** — Learners use the issue template and pull request workflow to propose and merge documentation updates, practicing how a real team would keep institutional knowledge current.

---

<div align="center">

### 🎉 Congratulations AdamCzyz-Atos! 🎉

<img src="https://octodex.github.com/images/welcometocat.png" height="160px" />

**You've successfully completed the exercise!**

<a href="https://twitter.com/intent/tweet?text=I%20just%20completed%20the%20%22Scale%20institutional%20knowledge%20using%20Copilot%20Spaces%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FAdamCzyz-Atos%2Fskills-scale-institutional-knowledge-using-copilot-spaces%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20X-1da1f2?style=for-the-badge&logo=x&logoColor=white" alt="Share on X" />
</a>
<a href="https://bsky.app/intent/compose?text=I%20just%20completed%20the%20%22Scale%20institutional%20knowledge%20using%20Copilot%20Spaces%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FAdamCzyz-Atos%2Fskills-scale-institutional-knowledge-using-copilot-spaces%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20Bluesky-0085ff?style=for-the-badge&logo=bluesky&logoColor=white" alt="Share on Bluesky" />
</a>
<a href="https://www.linkedin.com/feed/?shareActive=true&text=I%20just%20completed%20the%20%22Scale%20institutional%20knowledge%20using%20Copilot%20Spaces%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FAdamCzyz-Atos%2Fskills-scale-institutional-knowledge-using-copilot-spaces%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Share on LinkedIn" />
</a>

[![](https://img.shields.io/badge/Return%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/AdamCzyz-Atos/skills-scale-institutional-knowledge-using-copilot-spaces/issues/1)
[![GitHub Skills](https://img.shields.io/badge/Explore%20GitHub%20Skills-000000?style=for-the-badge&logo=github&logoColor=white)](https://learn.github.com/skills)

</div>

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

