# Contributing to JCoSS AI Governance

Thank you for helping to improve JCoSS's AI governance policies. This guide explains how to propose additions or amendments.

---

## Who Can Contribute?

Anyone with a GitHub account may propose changes. All proposed changes are reviewed and approved by the JCoSS IT / Governance team before being merged.

---

## How to Propose a Change

### Option A — Edit directly on GitHub (easiest)

1. Navigate to the file you want to edit in the `policies/` folder.
2. Click the **pencil ✏️ icon** (top-right of the file view).
3. Make your edits in the online editor.
4. Scroll down to **"Propose changes"**, add a short description of what you changed and why, then click **"Propose changes"**.
5. On the next page, click **"Create pull request"** and fill in the checklist that appears.
6. Submit the pull request. The governance team will review it.

### Option B — Fork and clone (for larger changes)

1. **Fork** this repository (click "Fork" at the top-right of the repo page).
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/JCoSS-AI-Governance.git
   cd JCoSS-AI-Governance
   ```
3. Create a new branch for your change:
   ```bash
   git checkout -b propose/my-policy-change
   ```
4. Make your edits to the relevant `.md` files in `policies/`, or add a new file using `templates/policy-template.md`.
5. Commit and push your branch:
   ```bash
   git add .
   git commit -m "Brief description of change"
   git push origin propose/my-policy-change
   ```
6. Open a **Pull Request** against the `main` branch of this repository.

---

## Adding a New Policy

1. Copy `templates/policy-template.md` to `policies/your-policy-name.md`.
2. Fill in all sections of the template.
3. Add an entry to the **Repository Structure** table in `README.md`.
4. Open a Pull Request as above.

---

## Writing Style

- Write in plain, jargon-free English.
- Use headings, bullet points, and tables to keep policies easy to scan.
- Keep sentences short and direct.
- Avoid unexplained acronyms — define them on first use.

---

## Review Process

| Step | Who | Timeframe |
|------|-----|-----------|
| PR opened | Contributor | — |
| Initial review | Head of IT | Within 5 school days |
| Policy approval | SLT / Governance team | Within 10 school days |
| Merge and Word document generation | Head of IT | On approval |

---

## Questions?

Contact the JCoSS IT office or open a [GitHub Discussion](../../discussions) if you have questions before submitting a change.
