# GhostLayer Android Client

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Build Status](https://github.com/poepulse/ghostlayer-client-android/actions/workflows/build.yml/badge.svg)](https://github.com/poepulse/ghostlayer-client-android/actions)
[![Latest Release](https://img.shields.io/github/v/release/poepulse/ghostlayer-client-android)](https://github.com/poepulse/ghostlayer-client-android/releases)

**Privacy-focused VPN client for Android with native VpnService integration and WireGuard tunnel.**

---

## 🌟 Features

- ✅ **WireGuard Protocol** — Fast, modern VPN protocol with state-of-the-art cryptography
- ✅ **Token-Based Authentication** — No username/password, secure token + HWID binding
- ✅ **Zero-Trust Security** — Tailscale-inspired security model
- ✅ **DPI Circumvention** — QUIC/443 traffic masking to bypass deep packet inspection
- ✅ **Kill Switch** — Automatic traffic block on connection drop
- ✅ **Always-On VPN** — System-level VPN enforcement
- ✅ **Material Design 3** — Modern UI following Android design guidelines
- ✅ **Battery Optimized** — Efficient background operation

---

## 📥 Installation

### Option 1: Google Play Store

Coming soon.

### Option 2: Download APK

1. Go to [Releases](https://github.com/poepulse/ghostlayer-client-android/releases)
2. Download latest `.apk` file
3. Enable "Install from Unknown Sources" in Android settings
4. Install APK and launch GhostLayer

### Option 3: Build from Source

**Requirements:**
- Android Studio Hedgehog+
- JDK 17+
- Android SDK 33+
- Gradle 8+

**Build Steps:**
```bash
# Clone repository
git clone https://github.com/poepulse/ghostlayer-client-android.git
cd ghostlayer-client-android

# Build debug APK
./gradlew assembleDebug

# Build release APK (requires signing)
./gradlew assembleRelease
```

---

## 🔧 Configuration

### Minimum Requirements

- Android 10 (API 29) or higher
- 50 MB free storage
- Internet connection

### Permissions

- **INTERNET** — Network connectivity
- **FOREGROUND_SERVICE** — Persistent VPN connection
- **RECEIVE_BOOT_COMPLETED** — Auto-start on device boot

---

## 🔐 Security

- **Token + HWID Binding** — One token = one device
- **No-Logs Policy** — Zero activity or connection logs
- **End-to-End Encryption** — WireGuard with ChaCha20-Poly1305
- **Forensic Resistance** — No sensitive data stored on device

---

## 🏗️ Architecture

- **Language**: Kotlin
- **VPN Tunnel**: WireGuard Android library
- **UI**: Jetpack Compose + Material Design 3
- **Backend**: Native VpnService API

---

## 📄 License

**AGPL-3.0** — Open Source

You are free to use, modify, and distribute this software under the terms of the GNU Affero General Public License v3.0.

See [LICENSE](LICENSE.md) for full license text.

---

## 🙋 Support

- **Documentation**: https://github.com/poepulse/ghostlayer-docs
- **Issues**: https://github.com/poepulse/ghostlayer-client-android/issues
- **Website**: https://poepulse.com

---

**Built with ❤️ by PoePulse**
