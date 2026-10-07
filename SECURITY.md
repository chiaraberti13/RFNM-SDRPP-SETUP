# Security Policy

<p align="center"><a href="#english">🇬🇧 English</a> · <a href="#italiano">🇮🇹 Italiano</a></p>

## English
### Supported versions
Security fixes target the latest revision of the default branch unless otherwise documented.

### Scope
The setup/reset scripts, downloaded upstream source, build/install paths, sudo operations and SDR++/RFNM configuration.

### Reporting
Do not open a public issue for an unpatched vulnerability. Use GitHub private vulnerability reporting / Security Advisories when available. Include affected commit/version, impact, reproducible steps, minimal proof of concept and mitigations. Remove unrelated sensitive data.

### Responsible and legal use
Use the project only with devices, systems and signals you own or are explicitly authorized to receive, analyze or modify. Applicable radio, privacy and communications law takes precedence over project documentation.

### Security requirements
Never commit secrets or private captures. Treat device input, paths, package sources, downloaded archives and configuration as untrusted. Verify upstream sources where practical, use least privilege, and review commands that install system packages, udev rules, kernel modules or services. Treat installation scripts as privileged code: avoid curl-pipe-shell patterns, unexpected destructive cleanup and unpinned/unexplained source changes.

## Italiano
### Versioni supportate
Le correzioni riguardano la revisione più recente del branch predefinito salvo diversa indicazione.

### Ambito
The setup/reset scripts, downloaded upstream source, build/install paths, sudo operations and SDR++/RFNM configuration.

### Segnalazione
Non aprire issue pubbliche per vulnerabilità non corrette. Usa la segnalazione privata / Security Advisories quando disponibile. Indica commit/versione, impatto, passaggi riproducibili, PoC minimo e mitigazioni, rimuovendo dati sensibili non necessari.

### Uso responsabile e legale
Usa il progetto solo con dispositivi, sistemi e segnali che possiedi o che sei esplicitamente autorizzato a ricevere, analizzare o modificare. Le norme applicabili in materia radio, privacy e comunicazioni prevalgono sulla documentazione del progetto.

### Requisiti di sicurezza
Non committare segreti o acquisizioni private. Considera non fidati input dei dispositivi, percorsi, sorgenti pacchetti, archivi scaricati e configurazione. Verifica le fonti upstream quando possibile, usa privilegi minimi e controlla i comandi che installano pacchetti, regole udev, moduli kernel o servizi. Treat installation scripts as privileged code: avoid curl-pipe-shell patterns, unexpected destructive cleanup and unpinned/unexplained source changes.
