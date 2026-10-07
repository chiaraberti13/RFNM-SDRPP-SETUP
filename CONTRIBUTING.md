# Contributing to RFNM-SDRPP-SETUP

<p align="center"><a href="#english">🇬🇧 English</a> · <a href="#italiano">🇮🇹 Italiano</a></p>

## English
This repository covers shell automation that installs/builds librfnm, soapy-rfnm and SDR++ with RFNM/SoapySDR support.

### Workflow
1. Read `README.md`, `SECURITY.md` and the relevant manual/design notes.
2. Use a dedicated branch and keep each pull request focused.
3. Never commit secrets, device identifiers, private recordings, personal data or unauthorized captures.
4. Use only hardware, systems and signals you are legally entitled and explicitly authorized to work with.
5. Report vulnerabilities privately.

### Setup
```bash
git clone https://github.com/chiaraberti13/RFNM-SDRPP-SETUP.git\ncd RFNM-SDRPP-SETUP
```

### Checks
```bash
bash -n setup_rfnm_sdrpp.sh\nbash -n reset_rfnm_sdrpp.sh
```
Changes that use sudo or remove files must be narrowly scoped, documented and reversible. Keep upstream URLs and build options explicit.

### Engineering expectations
Validate configuration and external input, fail safely, preserve uninstall/rollback paths, document system-level changes, avoid destructive defaults, and add tests or reproducible manual verification for behaviour changes. Update English documentation first and keep Italian documentation semantically aligned.

### Pull requests
Describe what changed, why, supported platforms/hardware, tests performed, security/privacy impact and rollback notes. Participation follows `CODE_OF_CONDUCT.md`.

## Italiano
Questo repository riguarda shell automation that installs/builds librfnm, soapy-rfnm and SDR++ with RFNM/SoapySDR support.

### Flusso
1. Leggi `README.md`, `SECURITY.md` e manuali/note di progetto pertinenti.
2. Usa un branch dedicato e mantieni ogni pull request focalizzata.
3. Non committare segreti, identificativi di dispositivi, registrazioni private, dati personali o acquisizioni non autorizzate.
4. Usa solo hardware, sistemi e segnali per cui hai diritto legale e autorizzazione esplicita.
5. Segnala privatamente le vulnerabilità.

### Setup
```bash
git clone https://github.com/chiaraberti13/RFNM-SDRPP-SETUP.git\ncd RFNM-SDRPP-SETUP
```

### Controlli
```bash
bash -n setup_rfnm_sdrpp.sh\nbash -n reset_rfnm_sdrpp.sh
```
Changes that use sudo or remove files must be narrowly scoped, documented and reversible. Keep upstream URLs and build options explicit.

### Aspettative tecniche
Valida configurazione e input esterni, usa comportamenti fail-safe, conserva procedure di uninstall/rollback, documenta le modifiche di sistema, evita default distruttivi e aggiungi test o verifiche manuali riproducibili. Aggiorna prima la documentazione inglese e mantieni quella italiana equivalente.

### Pull request
Descrivi cosa cambia, perché, piattaforme/hardware supportati, test eseguiti, impatto sicurezza/privacy e rollback. Si applica `CODE_OF_CONDUCT.md`.
