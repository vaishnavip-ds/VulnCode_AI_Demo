# VulnCode_AI_Demo

Controlled repository for demonstrating the VulnCode AI GitHub App.

The repository contains an intentionally vulnerable Python SQL query. A push
to `main` runs Semgrep, uploads the normalized CWE-89 finding to VulnCode AI,
and publishes an inline GitHub Check. The **Create safe fixes** action requests
a validated, draft-only remediation pull request for faculty review.

The vulnerable code is included only for a controlled security demonstration.
