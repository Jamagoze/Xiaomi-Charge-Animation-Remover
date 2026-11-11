# Contributing to Xiaomi Charge Animation Remover

First off, thank you for taking the time to contribute! 🎉 Android modding projects rely heavily on community collaboration to maintain compatibility across various MIUI and HyperOS versions, device architectures, and Android SDK updates.

Please take a moment to review the guidelines below to help make your contribution process smooth and effective.

---

## Code of Conduct

By participating in this project, you agree to abide by our terms. Please treat fellow developers, contributors, and users with respect, patience, and inclusivity.

---

## How Can I Help?

- **Reporting Bugs:** Found a crash, bootloop risk, or an animation that won't disappear on a specific OS version? Open an issue.
- **Suggesting Enhancements:** Have ideas for cleaner hook execution or expanded compatibility? Let's discuss it.
- **Submitting Patches:** Fix bugs, optimize Xposed/LSPosed scopes, or improve resource handling.
- **Updating Documentation:** Improve installation guides, troubleshooting steps, or translations.

---

## Reporting Bugs

Before creating a bug report, please check existing issues to avoid duplicates. When opening a new issue, please include:

1. **Device Model:** (e.g., Xiaomi 13, Redmi Note 12 Pro, Poco F5)
2. **OS Version:** Exact MIUI or HyperOS version (e.g., `HyperOS 1.0.3.0.UMRMIXM`)
3. **Module Version:** The version of Xiaomi Charge Animation Remover you are running.
4. **Xposed Framework:** Framework type and version (e.g., LSPosed v1.9.2).
5. **Logs:** Attach relevant `logcat` snippets or LSPosed error logs if the module fails to hook or causes SystemUI crashes.

---

## Pull Request Process

1. **Fork the Repo** and create your branch from `main` or `master`:
   ```bash
   git checkout -b feature/your-feature-name
