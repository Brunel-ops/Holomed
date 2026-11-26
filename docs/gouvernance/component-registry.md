# Component Registry

## Purpose

This registry provides an inventory of all critical components used within HOLOMED.

---

## Software Components

| Component | Role | Owner | Criticality | Status |
|------------|------------|------------|------------|------------|
| Next.js | Frontend Application | Project Team | High | Planned |
| PostgreSQL | Data Storage | Project Team | Critical | Planned |
| n8n | Workflow Automation | Project Team | High | Planned |
| Docker | Deployment | Project Team | High | Planned |
| Ollama | AI Processing | Project Team | Medium | Planned |
| OpenAI API | AI Processing | Project Team | Medium | Planned |

---

## Data Sources

| Source | Type | Criticality | Status |
|----------|----------|----------|----------|
| PubMed | Scientific | Critical | Active |
| IEEE Xplore | Scientific | High | Active |
| Nature | Scientific | High | Active |
| Springer | Scientific | Medium | Active |
| ScienceDirect | Scientific | Medium | Active |
| arXiv | Scientific | Medium | Active |
| Microsoft Research | Research Organization | Medium | Active |
| NVIDIA Research | Research Organization | Medium | Active |

---

## Lifecycle Status

Possible values:

```text
Planned
Active
Under Review
Deprecated
Retired
```

---

## Ownership

Every component must have an assigned owner responsible for:

- Monitoring
- Maintenance
- Upgrade planning
- Obsolescence review