# 🧭 Governance

This document describes how the **Atriva Community** and its open projects are governed.

---

## ⚙️ Governance Model

Atriva follows a **community-driven but maintainer-led** governance model.

- **Community-driven** → anyone can propose ideas, file issues, or submit pull requests.
- **Maintainer-led** → trusted maintainers review and approve changes, ensuring technical and strategic alignment.

All decisions favor **transparency**, **technical merit**, and **respectful collaboration**.

---

## 👥 Roles & Responsibilities

### 🧩 Contributors
Anyone who opens issues, discusses ideas, or submits pull requests.  
Contributors:
- Follow the [Code of Conduct](CODE_OF_CONDUCT.md)
- Submit PRs aligned with the project’s goals
- Participate in discussions and reviews

### 🛠️ Maintainers
Trusted contributors with merge permissions.  
Maintainers:
- Review and merge PRs
- Maintain CI/CD, testing, and release processes
- Guide contributors and enforce standards
- Approve or reject feature proposals and architectural changes

Maintainers are appointed by the current maintainers or project founder(s).

### 🧭 Project Lead(s)
Project leads define long-term direction and priorities.  
They:
- Coordinate between maintainers across projects (e.g., `platform-api`, `video-pipeline`)
- Approve major roadmap or licensing changes
- Represent the project in external collaborations or events

---

## 🔄 Decision-Making

1. **Minor changes** (bug fixes, documentation updates)  
   → Approved by at least **one maintainer** via PR review.

2. **Moderate changes** (new features, refactoring, CI updates)  
   → Require **two maintainer approvals** or a short **discussion thread** in Issues or Discussions.

3. **Major changes** (API design, architecture, governance, or licensing)  
   → Discussed openly in [Discussions](https://github.com/Atriva-AI-Community/community/discussions).  
   → Approved by a **majority of maintainers** and at least one **project lead**.

---

## 🧩 Subprojects

Each subproject under the `Atriva` organization (e.g., `platform-api`, `video-pipeline`, `ai-api`) follows this governance unless otherwise documented.

Subprojects may have:
- Their own maintainers  
- Their own `ROADMAP.md`  
- Independent release cycles  

All subprojects align with the **core community standards** defined here.

---

## 🧱 Transparency

All governance decisions are made publicly via:
- GitHub Issues and Discussions
- Pull request history
- Public roadmap (`community/ROADMAP.md`)

No private decision-making for technical or directional matters.

---

## 🌱 Adding or Removing Maintainers

- New maintainers are proposed by existing maintainers or leads.  
- The nomination is discussed publicly and requires consensus approval.  
- Inactive maintainers (6+ months inactivity) may be rotated out by consensus.

---

## 📅 Releases

Each project follows [Semantic Versioning](https://semver.org/):  
`MAJOR.MINOR.PATCH` → (breaking / feature / fix)

Releases are approved by maintainers and documented in the changelog.

---

## ⚖️ Licensing and Intellectual Property

All community contributions are made under the project’s open-source license (Apache 2.0).  
Contributors agree that:
- Their contributions are freely redistributable under this license.
- The Atriva maintainers may manage releases and official distributions.

---

## 💬 Amendments

This document can evolve.  
Any changes require:
1. Public proposal via PR  
2. Review and approval by maintainers and leads  
3. Update of version/date at the bottom of the file

---

_Last updated: October 2025_
