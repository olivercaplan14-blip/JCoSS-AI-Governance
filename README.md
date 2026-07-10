# JCoSS AI Governance

Official AI governance policies and guidelines for **JCoSS** (Jeannette Cohen School of Solihull), maintained as version-controlled Markdown files and automatically converted to Word documents for distribution.

---

## 📖 About This Repository

This repository contains all AI-related policies for JCoSS. Policies are written in Markdown (`.md`) for easy reading, editing, and version control. A GitHub Actions workflow automatically converts each policy to a **Word document (`.docx`)** whenever a change is merged into `main`.

Anyone with a GitHub account can propose a change by opening a **Pull Request**. All proposed changes are reviewed by the IT / Governance team before being merged.

---

## 📁 Repository Structure

```
JCoSS-AI-Governance/
├── policies/                        # AI governance policy documents
│   ├── ai-acceptable-use-policy.md
│   ├── ai-data-privacy-policy.md
│   └── ai-tools-guidelines.md
├── templates/
│   └── policy-template.md           # Blank template for new policies
├── .github/
│   ├── workflows/
│   │   └── convert-to-word.yml      # Auto-converts .md → .docx on merge
│   └── PULL_REQUEST_TEMPLATE.md     # Checklist shown when opening a PR
├── CONTRIBUTING.md                  # How to propose changes
└── README.md                        # This file
```

---

## 🚀 Quick Start

### Reading a policy
Browse the `policies/` folder above, or download the auto-generated Word documents from the **[Actions → Artifacts](../../actions)** section after any workflow run.

### Proposing a change
See [CONTRIBUTING.md](CONTRIBUTING.md) for a step-by-step guide. In short:

1. Fork or branch this repository.
2. Edit the relevant Markdown file in `policies/`, or add a new one using the template.
3. Open a **Pull Request** against `main`.
4. The governance team will review and merge.

---

## ⚙️ Automated Word Document Generation

When a Pull Request is merged into `main`, the GitHub Actions workflow (`.github/workflows/convert-to-word.yml`) runs **Pandoc** to convert every `.md` file in `policies/` into a `.docx` file. The resulting Word documents are uploaded as workflow artifacts and can be downloaded from the Actions tab.

---

## 📬 Contact

For questions about these policies, contact the JCoSS IT / Governance team.
