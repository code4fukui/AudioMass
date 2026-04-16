# AudioMass

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

AudioMass is a free, open-source, web-based audio and waveform editor. It runs entirely in your browser, with no backend or plugins required!

## Live Demo

You can try it out here: **[https://audiomass.co](https://audiomass.co)**

## Features

-   **Waveform Editing:** Cut, copy, paste, trim, and delete selections of audio.
-   **Audio Effects:** Apply a wide range of effects, including:
    -   Gain / Volume adjustment
    -   Fade In & Fade Out
    -   Compressor
    -   Normalize
    -   Reverb
    -   Distortion
    -   Pitch Shift & Speed Change
    -   Parametric EQ
    -   Invert / Reverse
-   **Recording:** Record audio directly from your microphone.
-   **File Formats:** Supports loading MP3, WAV, FLAC, OGG, and AIFF. Export your work as MP3 or WAV.
-   **Visualization:** A responsive, fullscreen waveform editor.
-   **Undo/Redo:** Full undo/redo history for all actions.
-   **Browser-Based:** Runs 100% in the browser. No server-side processing.
-   **Offline Support:** Works offline as a Progressive Web App (PWA).
-   **Session Management:** Save and load sessions locally using IndexedDB.

## Getting Started

To run AudioMass locally, you just need to serve the `src` directory with a local web server.

1.  Clone or download this repository.
2.  Navigate to the `src` directory in your terminal:
    ```sh
    cd AudioMass/src
    ```
3.  Start a local server. You can use the provided Go or Python servers, or any other static file server.

    *   **Using Go:**
        ```sh
        go run audiomass-server.go
        ```
    *   **Or using Python:**
        ```sh
        python audiomass-server.py
        ```
4.  Open your browser and navigate to [http://localhost:5055/](http://localhost:5055/).

## License

MIT License — see [LICENSE](LICENSE).