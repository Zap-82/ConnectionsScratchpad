
# Connections Scratchpad

Connections Scratchpad is a lightweight iOS app designed as a companion tool for the New York Times "Connections" game. It allows users to manually or visually import today's puzzle words and organize them into categories using a flexible 4x4 tile grid.

Unlike the official game, this app does **not check for correctness** — it’s meant as a creative scratchpad to help players organize their thinking before submitting real answers.

---

## Features

- **Touch-friendly 4x4 tile grid** with tap-to-swap sorting
- **Import words manually** or from a **screenshot using OCR**
- **Supports multi-word tiles** (e.g. "polar bear" or "baby powder")
- **Sketchpad aesthetic** with handwritten-style UI
- Built entirely with **SwiftUI** and runs on **iPad**

---

## How It Works

1. Launch the app and tap **"Import or Type Words"**
2. Choose to:
   - Type in today's words (one per line)
   - Import a screenshot of the puzzle
3. Words appear as movable tiles in a 4x4 grid
4. Tap to select and tap again to swap tiles
5. Organize them by categories — your way

---

## Limitations

- This app does **not connect** to the NYT puzzle backend
- It is intended only for **personal organization**, not validation
- OCR accuracy may vary depending on screenshot quality

---

## Development

Built with:
- SwiftUI
- Vision Framework (for OCR)
- Compatible with Swift Playgrounds and Xcode

---

## License

MIT License — see [LICENSE](LICENSE) file for details.
