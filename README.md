# 💖 Love 1.0

> A lightweight Android app — Play Store ready. Built and published by [@rayhanlimon](https://github.com/rayhanlimon).

![Platform](https://img.shields.io/badge/platform-Android-green)
![Version](https://img.shields.io/badge/version-1.0-pink)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📱 About

**Love 1.0** is an Android application (package `com.love.love}`, versionCode 100) converted from a web experience into a native installable app. It ships as both an installable APK and a Play Store App Bundle (AAB).

## ✨ Features

- 📦 Lightweight (~750 KB APK)
- 🚀 Installable on any Android device
- 🏪 Play Store ready (AAB included)
- 🔐 Signed release build

## ⬇️ Download & Install

1. Go to the [**Releases**](https://github.com/rayhanlimon/love-1.0/releases) page
2. Download `app-release.apk`
3. On your Android phone, allow *Install unknown apps* and open the APK to install

> Requires Android 5.0 (Lollipop) or above.

## 🏪 Publish to Play Store

The signed `app-release.aab` in [`releases/`](releases/) is ready to upload to the [Google Play Console](https://play.google.com/console):

1. Create a new app in Play Console
2. Upload `releases/app-release.aab`
3. Complete store listing, content rating & privacy policy
4. Roll out to production

## 📁 Project Structure

```
love-1.0/
├── README.md            ← you are here
├── LICENSE              ← MIT-style license
├── .gitignore            ← blocks secrets (*.jks, *.keystore)
├── releases/
│   ├── app-release.apk  ← installable Android package
│   └── app-release.aab  ← Play Store bundle
└── docs/
    └── readme.txt       ← original build info
```

## 🔒 Security Note

The release signing key (`*.jks` / `*.keystore`) and keystore passwords are **never** committed to this repository. They are kept privately by the maintainer — this is why a `.gitignore` blocks them. Never publish your signing key.

## 🛠 Built With

- [WebIntoApp.com](https://www.webintoapp.com) — web-to-app builder
- Android APK + AAB release toolchain

## 👨‍💻 Author

**Rayhan Limon** — Full-stack developer, passionate about clean code and open-source.

- GitHub: [@rayhanlimon](https://github.com/rayhanlimon)

## 📄 License

See [LICENSE](LICENSE) — Copyright 2026 WebIntoApp.com.
