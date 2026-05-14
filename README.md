# AudioMass

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A free, open source, web-based audio and waveform editor. It runs entirely in the browser with no backend or plugins required.

## Live Demo

[https://audiomass.co](https://audiomass.co)

## Screenshot


![AudioMass Interface](https://user-images.githubusercontent.com/127535/235270115-1135b85e-2e5a-4252-8791-d327827b21fc.jpg)

*The main editor view, showing a waveform with a floating, dockable Frequency Analyser panel.*

## Features

*   **Editing:** Fast, responsive waveform editing with cut, copy, paste, trim, and zoom.
*   **Effects:** A suite of effects including Gain, Fade In/Out, Invert, Reverse, Speed, and a parametric EQ.
*   **Automation:** Apply gradual effects over time using automation points.
*   **Format Support:** Load and export MP3, WAV, FLAC, OGG, and AIFF files.
*   **Analysis:** View a frequency spectrum analysis of your audio.
*   **Modern UI:** Features dockable panels for a flexible and customizable user interface.
*   **Session Management:** Sessions are saved in your browser's IndexedDB, using LZ4 compression for speed and efficiency.
*   **Workflow:** Drag-and-drop file loading and a robust undo/redo history.
*   **Recording:** Record audio directly from your microphone.

## Requirements

*   A modern web browser (Chrome, Firefox, Safari recommended).
*   For local development: Go (1.18+) or Python 3.

## Getting Started

1.  Clone this repository or download it as a ZIP file.
2.  Navigate into the `src` directory from your command line.
    ```sh
    cd AudioMass/src
    ```
3.  Run the local development server.
    *   **Using Go:**
        ```sh
        go run audiomass-server.go
        ```
    *   **Or, using Python:**
        ```sh
        python audiomass-server.py
        ```
4.  Open your browser and navigate to [http://localhost:5055/](http://localhost:5055/).

## License
MIT License — see [LICENSE](LICENSE).