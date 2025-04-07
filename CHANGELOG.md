# 📦 CHANGELOG

All notable changes to **BananaWRT** will be documented in this file.

---

## [2025-04-07]

### 🧩 Additional Packages

- ➕ Added condition to remove the log file if it exists on every `sysupgrade` execution by @SuperKali  
- 🔼 Bumped `banana-utils` to **v1.05** by @SuperKali  
- 🛠️ Fixed unsupported parameter usage in `sh` scripts by @SuperKali  
- ℹ️ Added more detailed information on package restore process by @SuperKali  
- ⏱️ Reverted sleep time to **10 seconds** in relevant scripts by @SuperKali  
- 🐛 Fixed issue during package installation by @SuperKali  
- 🛠️ Fixed unknown options and enabled service start at boot by @SuperKali  
- ♻️ Initial support for automatic restoration of overlay packages by @SuperKali  
- 📄 Updated `README` documentation for better clarity by @SuperKali  
- 🔄 Created a separate package to handle functionalities previously bundled with `linkup-optimization` by @SuperKali  
- 🔧 Bumped `modemband` and `linkup-optimization`; added **caching** and **overheat protection** on fan control by @SuperKali  
- 🔁 Bumped `linkup-optimization`: introduced support to update packages via `banana-update` by @SuperKali  
- 📝 Adjusted default configuration for `3g-info` utility by @SuperKali  

### 🍌 BananaWRT Core

- 🛠️ Fixed self-hosted (manual) workflow failures by @SuperKali  
- 🔧 Updated **stable** and **nightly** build configurations by @SuperKali  
- ➕ Added support in `userscript` to update `additional_pack` from repository without updating the entire board by @SuperKali  
- 📦 Bumped `actions/upload-artifact` from `4.6.1` to `4.6.2` (#29) by @dependabot[bot]  
- 🔄 Updated GitHub worker list from `README` by @SuperKali  
- 🧹 Added cleanup input to `self-hosted` workflow by @SuperKali  
- ➕ Re-added x86 worker to the workflow list by @SuperKali  
- 🗑️ Removed deprecated runner info from documentation by @SuperKali  
- 🛠️ Fixed missing functions in update script and added `--reset` flag to restore full configuration by @SuperKali  
- 📢 Added more detailed explanations in feature section by @SuperKali  


---
🛠️ Maintained with ❤️ by [BananaWRT](https://github.com/BananaWRT)  
📅 Release date: **April 7, 2025**
