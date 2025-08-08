# 🔄 Dialogflow CX Versioning Guide

This document explains how versioning was used in the project.

---

## Why Use Versions?

- Keep stable releases separate from new experiments.
- Roll back to a working version if something breaks.
- Make changes without affecting production environments.

---

## How It Was Done

1. Finalized the working flow in Draft.
2. Created a new version snapshot (e.g., `v1.0`).
3. Assigned this version to a test environment.
4. Continued working in Draft for future improvements (e.g., `v1.1`, `v2.0`).
5. Promoted stable versions to production/staging.

---

## Best Practices

- Use semantic versioning (e.g., v1.0.0).
- Always test in a staging environment before production.
- Add notes or changelogs for each version created.

