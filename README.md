# koopjm Jellyfin 12.4 Plugin Repository

Custom plugin repository for stock **Jellyfin 12.4+**.

## Adding This Repository to Jellyfin

1. Open Jellyfin and navigate to **Dashboard -> Plugins -> Repositories**.
2. Click **`+`** (Add Repository) and enter:
   - **Repository Name**: `koopjm Plugins`
   - **Repository URL**:
     ```
     https://raw.githubusercontent.com/koopjm/jellyfin-plugins/main/manifest.json
     ```
3. Open the **Catalog** tab to install any of the plugins below, then restart Jellyfin.

---

## Included Plugins

| Plugin | Source Repository | Description |
| :--- | :--- | :--- |
| **HEIC Photos** | [`koopjm/jellyfin-heic-plugin`](https://github.com/koopjm/jellyfin-heic-plugin) | Fork of `LuckyNoS7evin/jellyfin-heic-plugin` enhanced for Jellyfin 12.4 with 4K WebP fullscreen slideshow transcoding (`HeicDownloadFilter` & `HeicImageProcessor`), FFmpeg 8 tile-grid decoding, and EXIF/GPS metadata. |
| **Music Visualizer** | [`koopjm/jellyfin-plugin-musicvisualizer`](https://github.com/koopjm/jellyfin-plugin-musicvisualizer) | Fullscreen 6-mode audio visualizer (`Frequency Bars`, `Waveform`, `Circular Bars`, `3D Rotating Spectrum`, `3D Starfield`, `Rainbow Road`) with synchronized lyrics and rotating artist artwork. |
| **Voice Control** | [`koopjm/jellyfin-plugin-voicecontrol`](https://github.com/koopjm/jellyfin-plugin-voicecontrol) | Top-toolbar Microphone button with Web Speech API + self-contained server-side `Whisper.net` fallback (supports Tesla browser, Firefox, Chromium, and Chrome). |
| **Music Random** | [`koopjm/jellyfin-plugin-musicrandom`](https://github.com/koopjm/jellyfin-plugin-musicrandom) | Adds a `Random` album discovery button and dropdown view to Music libraries in both Modern and Legacy UI. |
