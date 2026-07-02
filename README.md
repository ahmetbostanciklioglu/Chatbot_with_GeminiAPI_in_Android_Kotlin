<div align="center">

# 🤖 Gemini AI Chatbot

**A conversational Android chatbot powered by the Google Gemini API, built with Kotlin & Jetpack Compose.**

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.0.0-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Material 3](https://img.shields.io/badge/Material%203-Design-6E48AA?style=flat-square&logo=materialdesign&logoColor=white)](https://m3.material.io)
[![Gemini API](https://img.shields.io/badge/Google-Gemini%20API-4776E6?style=flat-square&logo=google&logoColor=white)](https://ai.google.dev)
[![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/Chatbot_with_GeminiAPI_in_Android_Kotlin?style=flat-square&color=6E48AA)](https://github.com/ahmetbostanciklioglu/Chatbot_with_GeminiAPI_in_Android_Kotlin/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Chatbot_with_GeminiAPI_in_Android_Kotlin?style=flat-square&color=4776E6)](https://github.com/ahmetbostanciklioglu/Chatbot_with_GeminiAPI_in_Android_Kotlin/commits)

</div>

## 📖 Overview

Gemini AI Chatbot is a native Android app that lets you have a free-form conversation with Google's Gemini model. It is built entirely with Jetpack Compose and Material 3, and follows an MVVM structure where a `ChatViewModel` talks to the Google Generative AI SDK and drives a reactive chat UI. The conversation keeps its full history, so each new question is answered with the context of everything said before.

## ✨ Features

- 💬 Multi-turn conversations with the Gemini model, preserving chat history for contextual replies.
- ⚡ Reactive Compose UI driven by an observable message list in `ChatViewModel` (MVVM).
- ⏳ A "Typing..." placeholder shown while a response is being generated, then swapped for the answer.
- 🗨️ Distinct chat bubbles for user and model messages, with selectable (copyable) text.
- 🧭 Friendly "Ask me anything" empty state before the first message is sent.
- 🛡️ Built-in error handling that surfaces API failures as an in-chat message.

## 📸 Preview

<div align="center">

<img width="1712" alt="Gemini AI Chatbot screenshot 1" src="https://github.com/user-attachments/assets/f09208ff-e6cd-4c10-8f85-864c827b6dac" />

<img alt="Gemini AI Chatbot screenshot 2" src="https://github.com/user-attachments/assets/8554050b-5052-4dd2-a9c2-9042613089c8" />

<img alt="Gemini AI Chatbot screenshot 3" src="https://github.com/user-attachments/assets/d109adf8-f67c-401a-a98a-5c08f7de4ef0" />

</div>

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Chatbot_with_GeminiAPI_in_Android_Kotlin.git
cd Chatbot_with_GeminiAPI_in_Android_Kotlin
```

1. Open the project in **Android Studio**.
2. Let **Gradle sync** finish downloading the dependencies.
3. Get a Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey) and set it in `app/src/main/java/com/gemini_androidkotlin/utils/Constants.kt` (replace the `API_KEY` value).
4. Select an emulator or a connected device and press **Run** ▶️.

## 📋 Requirements

- Android Studio (Ladybug or newer recommended)
- Android Gradle Plugin 8.8.0 · Kotlin 2.0.0
- JDK 11
- Android SDK: `minSdk 24`, `compileSdk` / `targetSdk 35`
- A valid Google Gemini API key

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
