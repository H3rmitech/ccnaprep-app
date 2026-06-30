# Security Policy

## Reporting a vulnerability

If you discover a security issue in this project, please report it privately —
**do not open a public issue** for security problems.

Preferred: use GitHub's private vulnerability reporting on this repository:

1. Go to the **Security** tab.
2. Click **Report a vulnerability**.
3. Describe the issue, steps to reproduce, and impact.

You can expect an initial response within a few days. Once a fix is released,
the report will be disclosed publicly with credit (unless you prefer otherwise).

## Scope

This is a static, client-side study application (Vite + React) deployed to
GitHub Pages. It has no backend, stores progress only in the browser's
`localStorage`, and handles no user accounts or personal data. Reports most
relevant to this project include:

- Cross-site scripting (XSS) or content-injection in the rendered lessons.
- Supply-chain issues in the build pipeline or dependencies.
- Misconfigurations that could expose the repository or deployment.

## Supported versions

Only the latest deployed version (the `main` branch) is supported and patched.
