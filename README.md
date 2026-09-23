# Organization Community Health & Templates (.github)

This repository contains organization-wide community health files and standard Pull Request templates for all repositories in the organization.

## Structure

```text
.github/
├── pull_request_template.md        # Default PR template
└── PULL_REQUEST_TEMPLATE/
    ├── feature.md                  # New feature / Epic template
    ├── bugfix.md                   # Bug fix & Root Cause template
    ├── hotfix.md                   # Hotfix & Production incident template
    ├── refactor.md                 # Refactor & Tech Debt template
    └── backend_api.md              # Backend, Database & API Contract template
```

## How to use

1. Create a repository named `.github` in your GitHub Organization (set visibility to **Public** or **Internal**).
2. Push the contents of this repository to `main`.
3. Any repository in the organization without its own PR template will automatically inherit these templates.
