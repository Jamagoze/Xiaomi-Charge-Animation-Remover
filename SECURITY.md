# Security Policy

## Supported Versions

We aim to keep **Xiaomi Charge Animation Remover** secure and safe for system deployment. Security updates and bug fixes are prioritized for the latest release versions.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < 1.0   | :x:                |

---

## Reporting a Vulnerability

Because this module operates with high-level system permissions via the Xposed/LSPosed framework and interacts directly with `com.android.systemui` or system framework packages, security and stability are critical.

If you discover a security vulnerability, system exploitation risk, or critical boot-loop trigger, **please do not report it publicly via open GitHub issues.**

### How to Report

1. **Private Disclosure:** Send an email or open a private security advisory on GitHub describing the vulnerability in detail.
2. **Details to Include:**
   - A description of the security risk or vulnerability.
   - Steps to reproduce the issue (including sample code or modified APK payload if applicable).
   - Affected device configurations (Android SDK version, MIUI/HyperOS version, Xposed framework version).
   - Potential impact (e.g., privilege escalation, denial of service / soft brick, bootloop).

### Response Expectations

- **Acknowledgement:** We will acknowledge receipt of your report within 48 hours.
- **Assessment & Fix:** We will assess the issue and attempt to release a patch or advisory as quickly as possible.
- **Public Disclosure:** Once a fix is released, we will credit security researchers in the release notes unless you prefer to remain anonymous.

Thank you for helping keep the Android modding community safe and secure!
