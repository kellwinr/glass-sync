# GlassSync - Generate and Export lyrics to SRT file (time-synched lyrics) 🎵

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Platform](https://img.shields.io/badge/platform-HTML-orange.svg) ![Made with](https://img.shields.io/badge/Made%20with-Vanilla%20JS-yellow.svg)

**GlassSync** is a modern, browser-based tool designed to synchronize lyrics with audio files line-by-line. Featuring a stunning **Apple-inspired Glassmorphism UI**, it allows you to create precise `.srt` subtitle files directly in your browser without installing any software.

It features a high-performance **Audio Waveform Visualizer**, a **Karaoke Preview Mode**, and sub-second precision tools for perfect timing.

## Features

* **Clean UI:** A sleek, modern interface with frosted glass effects and animations.
* **Real-Time Waveform:** Automatically analyzes your audio file and renders a dynamic, interactive waveform for visual seeking.
* **Instant Sync:** Sync lyrics line-by-line using keyboard shortcuts with zero latency.
* **Karaoke Preview:** A dedicated overlay to test your sync results in real-time before exporting.
* **Precision Editing:** Nudge timestamps by **±0.1s** or click directly on the waveform to seek.
* **SRT Export:** Instantly download industry-standard `.srt` files compatible with YouTube, VLC, and more.
* **Privacy First:** 100% Client-side. Your audio files and lyrics never leave your computer.

## Quick Start

GlassSync is a **Single-File Application**. You don't need Node.js, Python, or a server.

1.  **Download** the `index.html` file from this repository.
2.  **Open** the file in any modern web browser (Chrome, Edge, Safari, Firefox).
3.  **Start Syncing!**

## How to Use?

1.  **Upload Audio:** Click `📂 MP3` to load your audio file. The waveform will generate automatically.
2.  **Load Lyrics:** Click `📝 Lyrics`, paste your text (line-separated), and load them.
3.  **Sync:**
    * Press `Space` to play the music.
    * Press `Arrow Down` (or the **Sync Next** button) exactly when the singer sings the highlighted line.
    * The line will turn green and the focus will move to the next line.
4.  **Edit/Undo:**
    * Made a mistake? Press `Arrow Up` to undo the previous line and rewind audio automatically.
    * Need fine-tuning? Use `Left/Right Arrows` to adjust the timestamp by 0.1s.
5.  **Export:** Click `Download SRT` to save your work.

## ⌨️ Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| **Space** | Play / Pause Audio |
| **Arrow Down (↓)** | **Sync Current Line** & Move to Next |
| **Arrow Up (↑)** | **Undo Previous Line** & Rewind Audio |
| **Arrow Left (←)** | Nudge Timestamp **-0.1s** |
| **Arrow Right (→)** | Nudge Timestamp **+0.1s** |

## Technical Details

This project utilizes modern Web APIs to deliver a native-app experience:

* **Web Audio API:** Used to decode MP3 data and extract channel data for the waveform visualization.
* **HTML5 Canvas:** Renders the high-performance waveform visualizer at 60fps.
* **requestAnimationFrame:** Ensures buttery smooth animations for the scrubber and karaoke preview.
* **Flexbox/CSS Variables:** Manages the responsive glassmorphism layout.

## Contributing

Contributions are welcome! If you have ideas for new features (e.g., JSON export, LRC support, or dark mode toggles), feel free to fork the repo and submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Built with ❤️ for precise lyric timing.*
