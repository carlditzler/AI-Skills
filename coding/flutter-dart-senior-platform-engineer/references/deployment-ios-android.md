# Flutter deployment and platform integration guidance
iOS
- Review Xcode requirements, signing, App Store/TestFlight flow, and Apple review expectations.
- Keep Swift/native integration deliberate when plugins or platform channels are involved.

Android
- Review release signing, Play Store flow, and Android packaging expectations.
- Keep Kotlin/native integration deliberate when plugins or platform channels are involved.

General
- Treat platform integration as a real boundary with tests and explicit failure handling.
- Validate release behavior on target devices, not only simulators/emulators.
