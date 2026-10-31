# Security policy

## Reporting a vulnerability

Please report security problems in UnkiSocialManager, its update process or its license service privately by email to **ya.madam.bez.prav@gmail.com** with the subject "Security". Do not open a public issue.

Include what you found, the app version (Settings → About) and steps to reproduce. We will confirm receipt within a few working days and keep you informed.

Please do not access other people's accounts or data, degrade the service, or publish details before a fix is available.

## Verifying releases

Releases are published only on this repository. Each release contains `SHA256SUMS.txt` and an `update-manifest.json` signed by UnkiSoftware; the app refuses updates whose signature or hashes do not match.
