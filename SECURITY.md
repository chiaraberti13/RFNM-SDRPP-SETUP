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

## Percorso operativo di segnalazione

1. Consulta [la sezione sicurezza del repository](https://github.com/chiaraberti13/RFNM-SDRPP-SETUP/security) e usa la funzione di segnalazione privata se disponibile. La presenza di questo documento non implica che tale funzione sia abilitata.
2. Se la funzione non è disponibile, usa un canale privato già verificato con la manutentrice. In assenza di un contatto, chiedi soltanto l'attivazione di un canale riservato in una issue, senza dettagli tecnici, nomi di soggetti coinvolti o allegati sensibili. Se le issue sono disabilitate, usa un contatto verificato già disponibile; attendi un canale riservato prima di condividere dettagli.
3. Nel canale riservato indica versione o commit, componente, impatto, prerequisiti, riproduzione minima con dati sintetici ed eventuale mitigazione.
4. Concorda la pubblicazione dei dettagli dopo la valutazione e la correzione. Restano valide le eventuali tempistiche specifiche già indicate sopra; questa integrazione non introduce nuove garanzie sui tempi.

I bug ordinari e le richieste di accessibilità possono usare i modelli delle issue. Non allegare credenziali, dati di produzione o dati personali, neppure ai report tecnici quando non necessari.
