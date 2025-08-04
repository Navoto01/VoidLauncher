# VoidLauncher: A Modern, Minimalist Android Experience

> **Please Note:** This project is currently under active development and is not yet available for public release. The features and designs described here are subject to change.

Welcome to **VoidLauncher**, a custom Android homescreen experience built from the ground up for users who value aesthetics, performance, and deep customization. Inspired by the clean and fluid designs of HarmonyOS and iOS, VoidLauncher aims to provide a beautiful, minimalist, and highly animated interface for your Android device.

---

### ✨ Key Features

* **Elegant, Animated Interface:** Every interaction is designed to be visually satisfying. From the custom "push effect" on buttons to the fluid transitions when entering Edit Mode, the entire experience is smooth and responsive.
* **Guided Onboarding Experience:** First-time users are greeted with a multi-step setup process that introduces the launcher with a custom video animation and allows them to personalize key settings before they even reach the homescreen.
* **Deep Homescreen Customization (Edit Mode):** A long press on the homescreen activates a powerful Edit Mode. Rearrange your apps across multiple pages, and access controls for planned features like custom wallpapers, themes, and icon packs.
* **Dynamic Icon & Label Sizing:** During setup, you can precisely control the size of your app icons and choose whether to display app labels, with a real-time preview of your changes.
* **Smart, Animated Search:** The launcher features an iOS-style search bar that intelligently animates above the keyboard when active, providing a seamless search experience without disrupting the UI.
* **Planned AI Integration:** A built-in **AnonAI** feature is planned, allowing you to interact with an AI chatbot directly from your homescreen, complete with personality modes and quick actions.

---

### In-Depth Look at Features

#### The Onboarding Experience

VoidLauncher ensures a perfect setup from the very first launch.
1.  **Video Intro:** A beautiful, full-screen video animation greets you, which you activate with a simple swipe-up gesture.
2.  **Live Customization:** You are then guided to a screen where you can adjust icon size and toggle app labels, seeing the results instantly in a live preview area.
3.  **Animated Welcome:** Finally, a stunning, animated welcome screen confirms your setup is complete before launching you into the main homescreen.

#### The Homescreen

The core of the launcher is clean, organized, and functional.
* **Paginated App Grid:** Your apps are organized across multiple pages using a smooth `ViewPager2`, which you can swipe through.
* **iOS-Style Dock & Search:** A persistent, floating dock at the bottom provides quick access to your essential apps, while a sleek search bar sits just above it.
* **Page Indicators:** Small dots clearly indicate which homescreen page you are currently viewing.

#### Powerful Edit Mode

This is where true personalization happens.
* **Activation:** Long-press anywhere on the homescreen to enter Edit Mode.
* **Visual Transformation:** The entire UI animates into a new state: your app grid scales down, and new control buttons for **Wallpapers, Themes, Icons, and Settings** elegantly slide into view at the bottom.
* **App Organization:** Drag and drop your app icons to rearrange them on the page or move them to different pages.
* **Widget Adding Mode:** An "Add" button in Edit Mode reveals a planned interface for adding widgets to your homescreen, featuring a smooth, full-screen expansion animation.

#### AnonAI Integration

Based on the `anonai.xml` layout, a powerful AI assistant is a core planned feature.
* **Direct Access:** Launch a full-screen AI chat interface directly from your homescreen.
* **Quick Actions:** Use preset buttons for common tasks like "Write me a code" or "Tell the latest news".
* **Personalities:** Just like the standalone app, you'll be able to choose from different AI personalities to tailor your conversation.

---

### 💻 Tech Stack

* **Language:** **Kotlin**
* **UI:** **Android XML Layouts**
* **Animations:** **Lottie** for complex vector animations (like the loading screen) and Android's native **`AnimatorSet`** and **`ObjectAnimator`** for all UI transitions.
* **Core Components:** `ViewPager2`, `RecyclerView`, `ConstraintLayout`.

---

### 🚀 Project Status

**VoidLauncher is currently a work-in-progress and is not yet available for public download.**

The features listed here are actively being developed and polished. The goal is to create a uniquely fluid and visually appealing launcher that stands out from the rest. Follow this repository for updates on our progress!

---

### Credits

* **Lead Developer & Designer:** Navoto01
* **Project:** AnonLab
* **Testing & Feedback**: Special thanks to the testers who helped improve the application:

    * Maxi
    * N0TThat
    * Vale
