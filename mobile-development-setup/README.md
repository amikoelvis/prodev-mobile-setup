# Mobile Development Environment Setup

This document outlines the setup and testing process for the mobile development environment using **Expo Framework** with React Native.

---

## Objective

Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we are using the **Expo Framework** for React Native, which simplifies mobile app development and testing.

---

## Prerequisites

Before starting, ensure you have the following installed:

- [Node.js LTS](https://nodejs.org/en/) ✅
- [VS Code](https://code.visualstudio.com/) ✅
- A compatible OS (macOS, Linux, or Windows) ✅
- A physical device (Android or iOS) ✅

---

## Why Expo Go?

Traditional mobile app testing requires emulators that mimic various devices (e.g., iPhone 16 Pro Max, Samsung Galaxy S23). Running such emulators demands high hardware resources.  
**Expo Go** provides a lightweight and cost-effective solution by allowing you to run React Native apps directly on your physical device.

---

## Steps to Install Expo Go

1. Visit the [Expo Go homepage](https://expo.dev/go).
2. Select the latest SDK version.
3. Install the Expo Go app for your device:
   - **Android**: [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - **iOS**: [Apple App Store](https://apps.apple.com/app/expo-go/id982107779)
4. Open the **Expo Go** app on your device.
5. Create a new Expo account or log in if you already have one.

---

## Testing the Setup

- Open **Expo Go** on your phone.
- Run the following command in your project folder (after creating a React Native project with Expo):
  ```bash
  npx create-expo-app my-app
  cd my-app
  npx expo start
  ```
