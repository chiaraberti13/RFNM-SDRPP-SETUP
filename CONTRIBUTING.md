# Contributing to RFNM-SDRPP-SETUP

This repository covers shell automation that installs/builds librfnm, soapy-rfnm and SDR++ with RFNM/SoapySDR support.

## Workflow
1. Read `README.md`, `SECURITY.md` and the relevant manual/design notes.
2. Use a dedicated branch and keep each pull request focused.
3. Never commit secrets, device identifiers, private recordings, personal data or unauthorized captures.
4. Use only hardware, systems and signals you are legally entitled and explicitly authorized to work with.
5. Report vulnerabilities privately.

## Setup
```bash
git clone https://github.com/chiaraberti13/RFNM-SDRPP-SETUP.git
cd RFNM-SDRPP-SETUP
```

## Checks
```bash
bash -n setup_rfnm_sdrpp.sh
bash -n reset_rfnm_sdrpp.sh
```
Changes that use sudo or remove files must be narrowly scoped, documented and reversible. Keep upstream URLs and build options explicit.

## Engineering expectations
Validate configuration and external input, fail safely, preserve uninstall/rollback paths, document system-level changes, avoid destructive defaults, and add tests or reproducible manual verification for behaviour changes. Write documentation in English and keep README.md and README.it.md semantically aligned.

## Pull requests
Describe what changed, why, supported platforms/hardware, tests performed, security/privacy impact and rollback notes. Participation follows `CODE_OF_CONDUCT.md`.

## Reporting and contribution checks

Use the [issue templates](https://github.com/chiaraberti13/RFNM-SDRPP-SETUP/issues/new/choose) and check for duplicates first. Useful context: Linux distribution, shell, RFNM hardware, driver versions and installation stage.

Write community and technical documentation in English; maintain equivalent English and Italian READMEs. Preserve existing application translations. Fill in the pull request template with commands, results and checks not performed, including the reason. Use synthetic examples without secrets or personal data.

See [the code of conduct](CODE_OF_CONDUCT.md), [security policy](SECURITY.md) and [accessibility statement](ACCESSIBILITY.md). Report vulnerabilities only through the security policy process.
