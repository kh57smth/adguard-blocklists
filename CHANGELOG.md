# Changelog
All notable changes to this project will be documented in this file.

This project follows **Keep a Changelog** conventions and uses **semantic versioning** (MAJOR.MINOR.PATCH).

---

## [v1.0] – 2026-02-01
### Added
- Initial production‑ready release of the DNS blocklist.
- Added `blocklist.txt` containing curated entries targeting:
  - Advertising networks
  - Tracking and analytics domains
  - Telemetry services (Windows, Apple, Android)
  - Push‑notification spam providers
  - Scam, phishing, and malware hosts
  - Crypto‑mining and browser‑based mining domains
  - Mobile tracking SDKs (Adjust, AppsFlyer, Kochava, Branch, etc.)
- Structured the list into clear category sections for readability and future expansion.

### Notes
- This release establishes the baseline version of the blocklist.
- Designed for real‑world home networks with smart devices, streaming services, and gaming platforms.
- Balanced approach: strong privacy protection with minimal risk of breaking legitimate services.

---

## [Unreleased]
### Planned
- Optional “aggressive” blocklist module for users who want deeper blocking.
- Additional category‑specific blocklists (e.g., telemetry‑only, ad‑only, malware‑only).
- Automated domain validation workflow.
- Regional CDN and ISP‑specific optimizations.
