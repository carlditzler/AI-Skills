# Tauri deployment best practices for macOS, Windows, and Linux
macOS
- Review bundle configuration, app icon, identifier, signing, and distribution path.
- Prefer release flows that fit normal macOS user expectations.

Windows
- Review EXE/MSI packaging, WebView2 assumptions, code signing, and updater/distribution path.
- Be explicit if Microsoft Store distribution changes packaging requirements.

Linux
- Review AppImage and .deb packaging expectations, runtime dependency assumptions, and signing strategy.
- Remember Linux distribution behavior varies; do not assume one environment equals all.

General
- Keep build and release configuration under source control where practical.
- Treat packaging config as product behavior, not a one-time afterthought.
- Validate installer/bundle behavior on the target platform, not just in development.
