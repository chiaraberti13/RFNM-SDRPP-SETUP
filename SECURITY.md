# Security Policy

## Supported versions
Security fixes target the latest revision of the default branch unless otherwise documented.

## Scope
The setup/reset scripts, downloaded upstream source, build/install paths, sudo operations and SDR++/RFNM configuration.

## Reporting
Do not open a public issue for an unpatched vulnerability. Use GitHub private vulnerability reporting / Security Advisories when available. Include affected commit/version, impact, reproducible steps, minimal proof of concept and mitigations. Remove unrelated sensitive data.

## Responsible and legal use
Use the project only with devices, systems and signals you own or are explicitly authorized to receive, analyze or modify. Applicable radio, privacy and communications law takes precedence over project documentation.

## Security requirements
Never commit secrets or private captures. Treat device input, paths, package sources, downloaded archives and configuration as untrusted. Verify upstream sources where practical, use least privilege, and review commands that install system packages, udev rules, kernel modules or services. Treat installation scripts as privileged code: avoid curl-pipe-shell patterns, unexpected destructive cleanup and unpinned/unexplained source changes.

## Private reporting process

Use **Report a vulnerability** in the repository Security tab if private reporting is available. Otherwise use a verified private contact published by the repository owner. If no private contact is available, open a public issue asking only for a private contact, without vulnerability details. Do not publish exploit details, credentials, personal data or sensitive logs in public issues.

Include the affected revision, environment, impact and minimal synthetic reproduction. Coordinate disclosure with the maintainer. Acknowledgement and remediation depend on availability and severity; no fixed response deadline is guaranteed.
