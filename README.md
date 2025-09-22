# Android Dev Environment (2025) — @clauddevio

A clear, repeatable guide for new machines.

## What you’ll install
- JDK (Temurin 17)
- Android Studio (latest)
- Android SDKs + emulator
- Platform tools (ADB)

## Steps
1. Install JDK 17
2. Install Android Studio (wizard: SDK, emulator)
3. Set ANDROID_HOME and add platform-tools to PATH (if needed)
4. Create a sample project (Compose)
5. Run emulator and build the app

## Common issues
- **Gradle sync failed** → Check JDK version matches project
- **Emulator slow** → Enable hardware virtualization in BIOS, use x86_64 images
- **ADB not found** → Ensure `platform-tools` is in your PATH
