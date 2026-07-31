# Security Ops merge-gate POC

Disposable public repository for validating GitHub server-side merge safety.
It contains no production code, credentials, or private data.

The protected `main` branch requires the GitHub Actions check named
`security-ops/merge-gate`. The workflow does not check out or execute pull
request code.
