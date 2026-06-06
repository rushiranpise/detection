# Root Detection Apps for Android

> A meticulously organized collection of Android applications for detecting root, Xposed, custom ROMs, bootloader unlock, SafetyNet, Play Integrity, and other system modifications.

## 📋 Table of Contents

- [Root / Xposed / ROM / Bootloader / SafetyNet / Play Integrity](#-root--xposed--rom--bootloader--safetynet--play-integrity)
- [Miscellaneous](#-miscellaneous)
- [How to Contribute](#-how-to-contribute)
- [Download Notes](#-download-notes)

---

## 🔍 Root / Xposed / ROM / Bootloader / SafetyNet / Play Integrity

| # | App Name | Aliases | Package Name | Official Links | Open Source | Category | Latest Version (as of May 2025) | Last Updated | Detections |
|---|----------|---------|--------------|----------------|-------------|----------|----------------|---------------|-------------|
| 1 | **Android Key Attestation Sample App** | KeyAttestation | `io.github.vvb2060.keyattestation` | [GitHub](https://github.com/vvb2060/KeyAttestation) | ✅ Yes | Bootloader Attestation | v1.8.4 | Jan 2025 | Bootloader unlock, Key attestation, Hardware-backed attestation |
| 2 | **Android Key Attestation (Fork)** | VisionR1 KeyAttestation | (same as above) | [GitHub](https://github.com/VisionR1/KeyAttestation) | ✅ Yes | Bootloader Attestation | v2.0.2 | May 2025 | Bootloader status, RKP (Remote Key Provisioning) |
| 3 | **Checker** | AkaneChecker | `com.akanet.checker` | [GitHub](https://github.com/AkaneTan/Checker) | ✅ Yes | ROM Detection | v2.9 | Nov 2024 | Custom ROM identification (MIUI, ColorOS, OneUI, etc.) |
| 4 | **Hunter** | HunterUpdate | `com.zhenxi.hunter` | [GitHub](https://github.com/w296488320/HunterUpdate) | ✅ Yes | Root, ROM Detection | v6.0.3 | 2025 | Root, Magisk, Xposed, LSPosed, ROM info, malware scan |
| 5 | **Memory Detector** | - | (source only, no package) | [GitHub](https://github.com/rushiranpise/detection) | ✅ Yes | Memory-level Root Detection | v2.1.0 | Jan 2025 | Memory scanning for root traces, Magisk, Xposed, virtual environments |
| 6 | **Momo** | - | `io.github.vvb2060.momo` | [Telegram](https://t.me/magiskalpha/529) | ✅ Yes | Root, ROM Detection | v4.4.1 | 2024 | Root, Magisk, Zygisk, LSPosed, code injection, custom ROM, SELinux |
| 7 | **Native Detector** | reveny Native Detector | (no standalone package) | [GitHub](https://github.com/reveny/Android-Native-Root-Detector), [Telegram](https://t.me/reveny1) | ✅ Yes | Native Root Detection | v7.6.0 | Mar 2025 | Root, Zygisk, Shamiko, custom ROM, TrickyStore, KernelSU |
| 8 | **Native Test** | 牛头检测 | `com.reveny.nativetest` | [Telegram](https://t.me/nullptr_dev) | ❌ Closed Source | Root Detection | v7.6.1 | Jan 2025 | Root, Magisk, KernelSU, APatch, Zygisk detection |
| 9 | **Ruru** | - | `com.byxiaorun.ruru` | [GitHub](https://github.com/byxiaorun/Ruru) | ✅ Yes | Root, Xposed Detection | v1.1.0 | 2024 | Root, Xposed/LSPosed, Magisk modules, hook detection |
| 10 | **Securify** | - | `com.rabahx.securify` | [GitHub](https://github.com/RabahX/Securify/) | ✅ Yes | Root Detection | v1.0 | 2023 | Root detection via multiple methods (su, build tags, etc.) |
| 11 | **TB Checker** | TB Safety Checker | `krypton.tbsafetychecker` | [Play Store](https://play.google.com/store/apps/details?id=krypton.tbsafetychecker) | ❌ Closed Source | Root, Xposed, Play Integrity, SafetyNet | 2.8.5 | Mar 2025 | Root, Xposed, SafetyNet attestation, Play Integrity, custom ROM |
| 12 | **Play Integrity API Checker** | PI Checker | `gr.nikolasspyr.integritycheck` | [Play Store](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck) | ❌ Closed Source | Play Integrity | v2.2 | Aug 2024 | Play Integrity verdicts, root detection, bootloader status |
| 13 | **SPIC** | Simple Play Integrity Checker | `com.henrikherzig.playintegritychecker` | [Play Store](https://play.google.com/store/apps/details?id=com.henrikherzig.playintegritychecker) | ✅ Yes | Play Integrity | v1.4.0 | Jan 2025 | Play Integrity API (MEETS_DEVICE_INTEGRITY, etc.) |
| 14 | **Android-Native-Root-Detector** | (same as #7) | (library, not APK) | [GitHub](https://github.com/reveny/Android-Native-Root-Detector) | ✅ Yes | Root Detection Library | v7.6.0 | Mar 2025 | Root detection methods in native C++ code |
| 15 | **Termone Plus** | Terminal Emulator | `com.termoneplus` | [Play Store](https://play.google.com/store/apps/details?id=com.termoneplus), [F-Droid](https://apt.izzysoft.de/fdroid/index/apk/com.termoneplus) | ✅ Yes | Terminal Emulator | v5.7.0 | May 2025 | (Not a detection app – terminal) |
| 16 | **Duck Detector** | DuckDetector | `com.eltavine.duckdetector` | [GitHub](https://github.com/eltavine/Duck-Detector-Refactoring) | ✅ Yes | Root, Hook, Bootloader, SELinux | v2.3 | May 2025 | Root, Magisk, KernelSU, APatch, LSPosed, bootloader, SELinux, virtualization |
| 17 | **Luna** | Luna检测 | (unknown package) | [Website](https://www.54nb.com/luna/luna.html) | ❌ Closed Source | Environment Detection | v1.4.1.6 | 2024 | Root, bootloader, simulator, virtual machine, hardware spoofing |
| 18 | **FOSS Root Checker** | FOSS Root Checker (offline) | `foss.chillastro.root.checker` | [GitHub](https://github.com/Chill-Astro/FOSS-Root-Checker) | ✅ Yes | Root Checker | v36.23.1.0 | Mar 2025 | Root access verification (su, `which su`, Magisk SU) |
| 19 | **GarudaDefender** | - | (no package published) | [GitHub](https://github.com/kikyps/GarudaDefender) | ✅ Yes | RASP, Root Detection | v4.5 | 2025 | Root, Shamiko, ZygiskNext, Frida, app tampering, debugger detection |
| 20 | **Demo** | JingMatrix Demo | `com.jingmatrix.demo` | [GitHub](https://github.com/JingMatrix/Demo) | ✅ Yes | Root Detection | v1.11.0 | Jan 2025 | Magisk, KernelSU, APatch detection |
| 21 | **DetectZygisk** | - | `com.apkunpacker.detectzygisk` | [GitHub](https://github.com/apkunpacker/DetectZygisk) | ✅ Yes | Zygisk Detection | v1.0 | 2024 | Zygisk presence detection |
| 22 | **Kknd_Root_Detector** | kknd Detector | `com.juanma0511.rootdetector` | [GitHub](https://github.com/juanma0511/Kknd_Root_Detector) | ✅ Yes | Root Detection | v2.0 | 2025 | Root (su binary), root manager apps (Magisk, SuperSU) |
| 23 | **Disclosure** | - | `com.disclosure.root` (tentative) | [Telegram](https://t.me/disclosureofroot) | ❌ Closed Source | Root Detection | v1.2.1 | 2025 | Root detection loopholes, Magisk hide bypass |
| 24 | **APTest** | - | `com.apkunpacker.aptest` | [GitHub](https://github.com/apkunpacker/MagiskDetection) | ✅ Yes | Magisk Detection | v1.0 | 2024 | Magisk-specific detection |
| 25 | **DirtySepolicy** | - | `org.lsposed.dirtysepolicy` | [GitHub](https://github.com/LSPosed/DirtySepolicy) | ✅ Yes | SELinux Policy Detection | v1.0 | May 2025 | Detects sepolicy patches used by userspace root solutions |
| 26 | **Holmes** | - | `com.apkunpacker.holmes` | [GitHub](https://github.com/apkunpacker/MagiskDetection) | ✅ Yes | Root Detection | v1.5.1 | 2024 | Root, Magisk, Xposed detection |

---

## 🔧 Miscellaneous

| # | App Name | Aliases | Package Name | Official Links | Open Source | Category | Latest Version | Last Updated | Detections |
|---|----------|---------|--------------|----------------|-------------|----------|----------------|---------------|-------------|
| 27 | **DRM Info** | - | `com.androidfung.drminfo` | [Play Store](https://play.google.com/store/apps/details?id=com.androidfung.drminfo) | ❌ Closed Source | DRM Information | 1.1.18 | Mar 2025 | Widevine DRM level, security level, HDCP capability |
| 28 | **DrHowdyDoo** | Display Info, MemInfo, DiskInfo, Layout Inspector | Various (4 separate apps) | [Play Store](https://play.google.com/store/apps/developer?id=DrHowdyDoo) | ❌ Closed Source | System Info Tools | Varies | Varies | Hardware/software information (no detection) |
| 29 | **M-Kavach 2** | - | `org.cdac.updatemkavach` | [Play Store](https://play.google.com/store/apps/details?id=org.cdac.updatemkavach) | ❌ Closed Source | Mobile Security | v7.4.3 | Apr 2025 | Malware scan, system integrity, root detection (subset) |
| 30 | **Smali Detector** | - | `com.godevelopers.SmaliDetector` | [Play Store](https://play.google.com/store/apps/details?id=com.godevelopers.SmaliDetector) | ❌ Closed Source | Smali Code Detection | v1.3 | 2021 | Smali code injection, apk modification detection (very outdated) |
| 31 | **Xposed Detector** | XposedChecker | `com.godevelopers.XposedChecker` | [Play Store](https://play.google.com/store/apps/details?id=com.godevelopers.XposedChecker) | ✅ Yes | Xposed Framework Detection | v1.1 | 2021 | Xposed framework detection (outdated) |

---

## 🤝 How to Contribute

Pull Requests are always welcomed! If you have corrections, newer versions, or additional apps:

1. Fork this repository
2. Update the tables with accurate data (please verify via actual APK or official source)
3. Submit a pull request

**Note:** Because app versions change frequently, consider linking to the official release page rather than stating a fixed version number.

---

## 📥 Download Notes

- **GitHub Releases** → Check the "Releases" tab of each repository.
- **Play Store** → Some apps are easier to install via Google Play.
- **Telegram** → Apps like Momo, Native Test, Disclosure are only distributed via Telegram.
- **Open Source** ✅ means source code is available. ❌ means closed source.
- **Outdated apps** – Smali Detector and Xposed Detector (2021) may not work on modern Android.

---

*Corrections applied based on best-available knowledge. If you spot errors, please open an issue or PR.*
