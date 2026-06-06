# Root Detection Apps for Android

> A meticulously organized collection of Android applications for detecting root, Xposed, custom ROMs, bootloader unlock, SafetyNet, Play Integrity, and other system modifications.

## 📋 Table of Contents

- [Root / Xposed / ROM / Bootloader / SafetyNet / Play Integrity](#-root--xposed--rom--bootloader--safetynet--play-integrity)
- [Miscellaneous](#-miscellaneous)
- [How to Contribute](#-how-to-contribute)
- [Download Notes](#-download-notes)

---

## 🔍 Root / Xposed / ROM / Bootloader / SafetyNet / Play Integrity

| # | App Name | Aliases | Package Name | Official Links | Open Source | Category | Latest Version | Last Updated | Detections |
|---|----------|---------|--------------|----------------|-------------|----------|----------------|---------------|-------------|
| 1 | **Android Key Attestation Sample App** | - | `io.github.vvb2060.keyattestation` | [GitHub](https://github.com/vvb2060/KeyAttestation), [Play Store](https://play.google.com/store/apps/details?id=io.github.vvb2060.keyattestation) | ✅ Yes | Bootloader Attestation | v1.8.4 | Jan 16, 2025 | Bootloader Status, Key Attestation |
| 2 | **Android Key Attestation (Fork)** | - | (Same as original) | [GitHub](https://github.com/VisionR1/KeyAttestation) | ✅ Yes | Bootloader Attestation | v2.0.2 (247) | May 2026 | Bootloader Status, Key Attestation, RKP |
| 3 | **Checker** | - | (Not on Play Store) | [GitHub](https://github.com/AkaneTan/Checker) | ✅ Yes | ROM Detection | - | - | Custom ROM Detection |
| 4 | **Hunter** | - | `com.zhenxi.hunter` | [GitHub](https://github.com/w296488320/HunterUpdate) | ✅ Yes | Root, ROM Detection | v6.0.3 | 2025 | Root, Magisk, Xposed, Malware Scan |
| 5 | **Memory Detector** | - | (Open source) | [GitHub](https://github.com/rushiranpise/detection) | ✅ Yes | Memory-level Root Detection | v2.1 | Jan 2026 | Memory Root/Magisk traces, Xposed, Virtualization |
| 6 | **Momo** | - | (Not on Play Store) | [Telegram](https://t.me/magiskalpha/529) | ✅ Yes | Root, ROM Detection | v4.4.1 | 2025 | Root, Magisk, Zygisk, LSPosed, Code Injection |
| 7 | **Native Detector** | - | (Open source) | [GitHub](https://github.com/reveny/Android-Native-Root-Detector), [Telegram](https://t.me/reveny1) | ✅ Yes | Root Detection | v7.7.0 | Apr 12, 2026 | Root, Zygisk, Shamiko, Custom ROM, TrickyStore |
| 8 | **Native Test** | 牛头检测 | (On Play Store) | [Telegram](https://t.me/nullptr_dev) | ❌ Closed Source | Root Detection | v7.6.1 | Jan 28, 2026 | Root, Magisk/KSU/APatch detection |
| 9 | **Ruru** | - | (Open source) | [GitHub](https://github.com/byxiaorun/Ruru) | ✅ Yes | Root, Xposed Detection | v1.1.0 | 2025 | Root, Xposed/LSPosed, Magisk modules |
| 10 | **Securify** | - | (Open source) | [GitHub](https://github.com/RabahX/Securify/) | ✅ Yes | Root Detection | - | - | Root detection |
| 11 | **TB Checker** | TB Checker - Play Integrity | `krypton.tbsafetychecker` | [Play Store](https://play.google.com/store/apps/details?id=krypton.tbsafetychecker) | ❌ Closed Source | Root, Xposed, Play Integrity, SafetyNet | 2.8.5.r386.a1911d1 | Mar 4, 2026 | Root, Xposed, SafetyNet, Play Integrity, Custom ROM |
| 12 | **Play Integrity API Checker** | - | `gr.nikolasspyr.integritycheck` | [Play Store](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck) | ❌ Closed Source | Play Integrity | v2.2 | Aug 17, 2025 | Play Integrity, Root, Unlocked Bootloader |
| 13 | **SPIC** (Simple Play Integrity Checker) | - | `com.henrikherzig.playintegritychecker` | [Play Store](https://play.google.com/store/apps/details?id=com.henrikherzig.playintegritychecker) | ✅ Yes | Play Integrity | v1.4.0 | Jan 13, 2025 | Play Integrity API, SafetyNet |
| 14 | **Android-Native-Root-Detector** | - | (Open source) | [GitHub](https://github.com/reveny/Android-Native-Root-Detector), [Telegram](https://t.me/reveny1) | ✅ Yes | Root Detection | v7.7.0 | Apr 12, 2026 | Root, Zygisk, Shamiko, Custom ROM, TrickyStore |
| 15 | **Termone Plus** | Terminal Emulator | `com.termoneplus` | [Play Store](https://play.google.com/store/apps/details?id=com.termoneplus), [F-Droid](https://apt.izzysoft.de/fdroid/index/apk/com.termoneplus) | ✅ Yes | Terminal Emulator | v5.7.0 | May 10, 2026 | - |
| 16 | **Duck Detector** | DuckDetector | (Open source) | [GitHub](https://github.com/eltavine/Duck-Detector-Refactoring) | ✅ Yes | Root, Hook, Bootloader, SELinux, Virtualization | Active development | May 2026 | Root, Magisk, KernelSU, APatch, LSPosed, Bootloader, SELinux, Virtualization |
| 17 | **Luna** | Luna环境检测工具 | - | [Website](https://www.54nb.com/luna/luna.html) | ❌ Closed Source | Hardware Info, Root Detection | v1.4.1.6 | 2025 | Root, Bootloader, Simulator, Virtual Machine, Hardware Info |
| 18 | **FOSS Root Checker** | FOSS Root Checker | `foss.chillastro.root.checker` (offline: `foss.chillastro.root.checker.offline`) | [GitHub](https://github.com/Chill-Astro/FOSS-Root-Checker) | ✅ Yes | Root Checker | v36.23.1.0 | Mar 26, 2026 | Root access verification |
| 19 | **GarudaDefender** | - | (Open source) | [GitHub](https://github.com/kikyps/GarudaDefender) | ✅ Yes | RASP, Root Detection | v4.5.x / v5.x (in development) | 2026 | Root, Shamiko, ZygiskNext, Frida, Tampering |
| 20 | **Demo** | - | (Open source) | [GitHub](https://github.com/JingMatrix/Demo) | ✅ Yes | Root Detection | v1.11.0 | Feb 2026 | Magisk, KSU, APatch |
| 21 | **DetectZygisk** | - | (Open source) | [GitHub](https://github.com/apkunpacker/DetectZygisk) | ✅ Yes | Zygisk Detection | - | - | Zygisk detection |
| 22 | **Kknd_Root_Detector** | kknd Detector | `com.juanma0511.rootdetector` | [GitHub](https://github.com/juanma0511/Kknd_Root_Detector) | ✅ Yes | Root Detection | v2.0 | 2026 | Root, su binary, Root management apps |
| 23 | **Disclosure** | - | (On Play Store) | [Telegram](https://t.me/disclosureofroot) | ❌ Closed Source | Root Detection | v1.2.1 | 2026 | Root, detection loopholes |
| 24 | **APTest** | - | (APK only) | [GitHub](https://github.com/apkunpacker/MagiskDetection) | ✅ Yes | Root/Magisk Detection | - | - | Magisk detection |
| 25 | **DirtySepolicy** | - | `org.lsposed.dirtysepolicy` | [GitHub](https://github.com/LSPosed/DirtySepolicy) | ✅ Yes | SELinux Policy Detection | - | May 2026 | Userspace su solutions (unbypassable method) |
| 26 | **Holmes** | - | (APK only) | [GitHub](https://github.com/apkunpacker/MagiskDetection) | ✅ Yes | Root Detection | v1.5.1 | - | Root, Magisk |

---

## 🔧 Miscellaneous

| # | App Name | Aliases | Package Name | Official Links | Open Source | Category | Latest Version | Last Updated | Detections |
|---|----------|---------|--------------|----------------|-------------|----------|----------------|---------------|-------------|
| 27 | **DRM Info** | - | `com.androidfung.drminfo` | [Play Store](https://play.google.com/store/apps/details?id=com.androidfung.drminfo) | ❌ Closed Source | DRM Information | 1.1.18-260326 beta | Mar 31, 2026 | DRM module info, MediaDrm API |
| 28 | **DrHowdyDoo** | Developer account | Various (Display Info, MemInfo, DiskInfo, Layout Inspector) | [Play Store](https://play.google.com/store/apps/developer?id=DrHowdyDoo) | ❌ Closed Source | System Info Tools | Varies | Varies | Device info, memory, disk, layout |
| 29 | **M-Kavach 2** | - | `org.cdac.updatemkavach` | [Play Store](https://play.google.com/store/apps/details?id=org.cdac.updatemkavach) | ❌ Closed Source | Mobile Security | v7.4.3 | Apr 2026 | Mobile device security threats |
| 30 | **Smali Detector** | - | `com.godevelopers.SmaliDetector` | [Play Store](https://play.google.com/store/apps/details?id=com.godevelopers.SmaliDetector) | ❌ Closed Source | Smali Code Detection | v1.3 | 2021 | Smali patch detection |
| 31 | **Xposed Detector** | XposedChecker | `com.godevelopers.XposedChecker` | [Play Store](https://play.google.com/store/apps/details?id=com.godevelopers.XposedChecker) | ✅ Yes | Xposed Framework Detection | v1.1 | 2021 | Xposed framework detection |

---

## 🤝 How to Contribute

Pull Requests are always welcomed! If you know of any other root detection apps or have updated information about existing apps, please:

1. Fork this repository
2. Add your app information following the format above
3. Submit a pull request

**Contribution Guidelines:**
- Verify the app is still actively maintained or relevant
- Include accurate package names and official links
- Specify detection capabilities
- Update version information if newer versions exist

---

## 📥 Download Notes

- **GitHub Releases**: Check the "Releases" section of each GitHub repository for the latest APK downloads
- **Play Store**: Some apps are available on Google Play for easy installation
- **Telegram Channels**: Some developers distribute their apps exclusively through Telegram channels
- **Open Source**: Apps marked as "✅ Yes" have their source code publicly available for review and contribution
- **API Level Requirements**: Always check the minimum Android version required for each app

---

*Last updated: May 2026*
