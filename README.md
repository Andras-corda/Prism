# Prism – A Raycast-Inspired Productivity Launcher for Windows (WPF)

**Prism** is a fast, modern productivity launcher for Windows built with **WPF (.NET)**. Inspired by [Raycast](https://www.raycast.com/), Prism brings lightning-fast app launching, file search, extensibility, and smart developer tools into one unified, keyboard-first interface.

---

## ✨ Features

- 🔍 **Global Search**  
  Launch applications, open files, and access system settings instantly.

- 🧩 **Extension System**  
  Support for custom extensions written in C# (via plugins) – soon Python support via scripting interface.

- 📅 **Built-in Tools**  
  Clipboard manager, calendar viewer, snippet inserter, quick notes, and more.

- 🧑‍💻 **Developer Utilities**  
  REST client, UUID generator, JSON formatter, Git status commands, and more – right from the launcher.

- ⚙️ **Script Runner**  
  Execute PowerShell, CMD, or custom executables from within Prism.

- 🎨 **Modern WPF UI**  
  Beautiful dark/light themes, animations, and smooth keyboard navigation.

- 🔐 **Privacy-first**  
  No telemetry, no background sync – fully offline and secure by default.

---

## 🛠️ Built With

- [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- [WPF (Windows Presentation Foundation)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/)
- MVVM Pattern (CommunityToolkit.MVVM)
- Upcoming plugin system via MEF or .NET Assembly Loading

---

## 📦 Installation

> ⚠️ Early development phase – binaries and installer will be released soon.

For now, clone and run locally:

```bash
git clone https://github.com/your-username/PrismLauncher.git
cd PrismLauncher
dotnet build
