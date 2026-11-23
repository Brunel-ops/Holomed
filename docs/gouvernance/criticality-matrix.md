# Criticality Matrix

## Purpose

This document defines the criticality assessment framework used by HOLOMED to prioritize incidents, vulnerabilities, obsolescence risks and component failures.

---

## Evaluation Criteria

Each component is evaluated according to:

### Business Impact

- Low
- Medium
- High
- Critical

### Probability

- Rare
- Unlikely
- Likely
- Frequent

---

## Risk Matrix

| Impact \ Probability | Rare | Unlikely | Likely | Frequent |
|----------|----------|----------|----------|----------|
| Critical | Medium | High | Critical | Critical |
| High | Medium | High | High | Critical |
| Medium | Low | Medium | High | High |
| Low | Low | Low | Medium | Medium |

---

## Classification

### Critical

Examples:

- PostgreSQL unavailable
- Data corruption
- Scientific source unavailable globally

Target Response Time:

```text
< 24 hours
```

---

### High

Examples:

- n8n workflow failure
- AI summarization unavailable
- Discord notification failure

Target Response Time:

```text
< 72 hours
```

---

### Medium

Examples:

- Dashboard visualization issue
- API latency problem

Target Response Time:

```text
< 7 days
```

---

### Low

Examples:

- Documentation inconsistency
- UI visual adjustment

Target Response Time:

```text
Best effort
```

---

## Review

Criticality assessments must be reviewed during quarterly reviews.
