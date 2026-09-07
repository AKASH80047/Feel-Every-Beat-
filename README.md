# 🎵 Feel Every Beat — Production-Grade Audio & Music Streaming Mobile App

<div align="center">

  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Riverpod_2.x-2C3E50?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Clean_Architecture-4A154B?style=for-the-badge&logo=blueprint&logoColor=white" />
  <img src="https://img.shields.io/badge/iOS_%26_Android-000000?style=for-the-badge&logo=apple&logoColor=white" />

  <br/><br/>

  <!-- QUICK HIRE CTA -->
  <a href="https://www.fiverr.com/akashpandey318" target="_blank">
    <img src="https://img.shields.io/badge/Hire_Me_on_Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white" height="36" />
  </a>
  &nbsp;
  <a href="https://www.upwork.com/freelancers/~01e0a297e6e580e0c0" target="_blank">
    <img src="https://img.shields.io/badge/Hire_on_Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white" height="36" />
  </a>
  &nbsp;
  <a href="https://akp991892-portfolio.web.app" target="_blank">
    <img src="https://img.shields.io/badge/Live_Portfolio-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" height="36" />
  </a>

</div>

---

## 📱 About the Project

**Feel Every Beat** is a production-ready, full-featured music & podcast streaming mobile application built with **Flutter, Dart, and Clean Architecture**. It delivers a Spotify-grade listening experience with background playback, notification controls, smooth audio seek waveforms, and offline caching.

---

## ⚡ Key Features

- 🎧 **Background Audio & Lock-Screen Controls**: Powered by `audio_service` and `just_audio` with full OS-level notification controls and hardware media button listeners.
- ⚡ **60 FPS Smooth Audio Visualizers**: Real-time waveform visualizers, dynamic color palette extraction from album art.
- 📂 **Offline Caching & Smart Playlists**: Hive NoSQL database integration for instant offline playback and customized user queues.
- 🌐 **Robust REST API Integration**: Dio client with JWT token bearer refresh, caching layers, and network connectivity stream handlers.
- 🎨 **Material 3 Glassmorphic UI**: Ultra-clean dark mode UI with micro-animations and intuitive gesture navigation.

---

## 🏗️ Architecture & Engineering Design

```
lib/
├── core/               # Constants, themes, network clients, error handlers
├── features/           # Feature-first modular organization
│   ├── player/         # Player UI, state notifiers, audio service handlers
│   ├── playlist/       # Playlist management, offline caching
│   ├── search/         # Debounced API search, filter chips
│   └── home/           # Dynamic carousels, trending tracks
└── main.dart           # App entry point & dependency initialization
```

- **Architecture**: Clean Architecture (Presentation, Domain, Data layers)
- **State Management**: Riverpod 2.x (StateNotifierProvider & AutoDispose)
- **Audio Engine**: `just_audio` + `audio_service`
- **Network Engine**: Dio + PrettyDioLogger + ConnectivityPlus
- **Local Persistence**: Hive + Shared Preferences

---

## 💼 Want a Custom Audio, Streaming, or Media App Built?

I am available for **freelance mobile app development**, custom audio player engineering, and full-stack Flutter builds.

- 🎯 **Order on Fiverr**: [fiverr.com/akashpandey318](https://www.fiverr.com/akashpandey318)
- 💼 **Hire on Upwork**: [Upwork Profile](https://www.upwork.com/freelancers/~01e0a297e6e580e0c0)
- 🌐 **Portfolio**: [akp991892-portfolio.web.app](https://akp991892-portfolio.web.app)
- 📧 **Direct Email**: [akp991892@gmail.com](mailto:akp991892@gmail.com)
