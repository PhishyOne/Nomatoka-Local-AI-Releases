# Nomatoka Local AI Releases

Public release channel for the Nomatoka Local AI Android tester.

This repository intentionally contains release artifacts and signed update metadata only. Application source code is maintained separately in a private repository.

## Layout

- `stable/` — current signed update envelope and compatibility artifacts.
- `releases/` — immutable versioned release artifacts.
- Future Android APK releases will be published here with signed metadata, exact sizes, and SHA-256 hashes.

No Android signing keystore, APK signing private key, update-manifest private key, passwords, model binaries, or application source code belongs in this repository.
