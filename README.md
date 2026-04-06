# <img width="42" height="37" alt="image" src="https://proxy.duckduckgo.com/iu/?u=https://i.imgur.com/6okqoxi.png" /> Windows Media Player 7 Series: WebApp

<img height="360" alt="Windows Media Player Banner" src="https://github.com/user-attachments/assets/ea3b4e2f-e16a-4c37-93a8-d7637d334ad0" />

*A highly detailed, nostalgic web recreation of the classic Windows Media Player 7 Series eras.*

This is a fully functional, browser-based media player built entirely with **Vanilla JavaScript, HTML5, and CSS3**. It looks like the classic Windows Media Player andit acts like it, complete with local playback, internet radio, visualizations, custom skins, 10-band EQ, in-browser MKV remuxing and more!

No frameworks. No bloat. Just modern web APIs.

---

## ✨ Key Features

### 🎬 Playback Engine
* **Local Media Handling:** Drag and drop or browse for Audio/Video files (`.mp3`, `.mp4`, `.wav`, `.flac`, `.webm`, `.ogg`, etc.).
* **Live Network Streams:** Paste direct audio/video URLs, or load `.m3u` / `.pls` / `.m3u8` (HLS) playlists.
* **YouTube Integration:** Paste a YouTube URL to instantly stream the audio/video directly within the player interface.
* **In-Browser MKV Conversion:** Utilizes **FFmpeg.wasm** to seamlessly remux `.mkv` files into playable `.mp4` formats entirely within the browser's memory—no server required!
* **Capture Devices:** Access your webcam and microphone directly within the player.

### 🎛️ Advanced Audio & Video Processing
* **10-Band Graphic Equalizer:** Fine-tune your audio frequencies using the Web Audio API.
* **Spatial Audio (SRS WOW Simulation):** Toggle spatial audio enhancements utilizing Web Audio spatial panners.
* **Video Filters:** Real-time adjustments for Brightness, Contrast, Saturation, Hue, and Sepia.
* **Dynamic Visualizations:** Beat-synced oscilloscope, album art extraction, and atmospheric video loops that react to the music.

### 🎨 Custom Skins & UI
* **12+ Built-in Skins:** Switch between Default (Redmond), Miniplayer, Compact, BMO Console, Diamond Prism, Cyber Shield, and more.
* **Pop-out Mode:** Pop your customized player out into a standalone, chromeless browser window.
* **Aspect Ratio Controls:** Force 16:9, 4:3, 1:1, 2.35:1, or fit to window.
* **Picture-in-Picture & Fullscreen:** Native browser PiP support and a custom fullscreen UI with floating transport controls.

### 🛠️ Bonus Tools
* **Audio Recording:** Record your microphone directly from the app and download the `.webm` audio file.
* **Subtitle Support:** Load `.srt` files on the fly (auto-converts to WebVTT for native HTML5 video support).
* **Metadata Extraction:** Automatically reads ID3 tags (via `jsmediatags`) and fetches missing album art via the iTunes API.

---

## 📸 Screenshots

| Now Playing | Media Library |
| :---: | :---: |
|<img height="250" alt="Now Playing View" src="https://github.com/user-attachments/assets/55b6ea62-0b8f-424c-a165-ee72a952e276" /> |<img height="250" alt="Media Library View" src="https://github.com/user-attachments/assets/867f695e-3cd8-4280-86dd-20f188bb5db1" />
| *The classic Now Playing view with visualizations.* | *Drag-and-drop media management.* |

| Graphic Equalizer | Skin Chooser |
| :---: | :---: |
| <img height="240" alt="Graphic Equalizer" src="https://github.com/user-attachments/assets/5d70d75c-3faf-42a4-8459-9e0cbf321018" />| <img height="240" alt="Skin Chooser" src="https://github.com/user-attachments/assets/0fe68858-1409-4ca5-aa0e-273470fe8d0a" />
| *10-band EQ and video enhancements.* | *Apply custom skins on the fly.* |


---

## 🗂️ UI Views Overview

Just like the original software, this WebApp features the classic left-hand navigation bar:


1.  **Now Playing:** The main media view featuring album art, video playback, and visualizations.
2.  **Media Guide:** A nostalgic iframe view pointing to classic internet archives.
3.  **Copy from CD:** A mock UI paying homage to the classic CD ripping days.
4.  **Media Library:** Your current session's playlist and metadata grid.
5.  **Radio Tuner:** An extensive, categorized list of working internet radio streams (UK, US, Canada, Australia).
6.  **Copy to CD or Device:** A mock interface for "burning" media.
7.  **Premium Services:** A nostalgic recreation of early 2000s music subscriptions (Napster, CinemaNow, Pressplay).
8.  **Skin Chooser:** Browse, preview, and apply custom structural CSS skins.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Space` | Play / Pause |
| `S` | Stop |
| `Ctrl + S` | Stop |
| `Ctrl + P` | Play / Pause |
| `Ctrl + V` | Load stream from URL |
| `N` / `Ctrl + F` | Next Track |
| `P` / `Ctrl + B` | Previous Track |
| `M` / `F8` | Toggle Mute |
| `F9` / `F10` | Volume Down / Up |
| `F` | Toggle Fullscreen |
| `Ctrl + O` | Open File |
| `Ctrl + U` | Open Stream URL |
| `Ctrl + L` | Toggle Playlist Pane |
| `Ctrl + E` | Open Equalizer |
| `Arrow Left / Right` | Seek Backward / Forward 10s |
| `[ / ]` | Decrease / Increase Playback Speed |
| `A` | Toggle Aspect Ratio |

---

## 🚀 Installation & Usage

Because this is a Vanilla JS WebApp, no `npm install` or build steps are strictly required for basic functionality!

1. Download the repository:
2. Open index.html in any modern web browser.
---

## 🛠️ Technologies Used

* **Core:** HTML5, CSS3, Vanilla JavaScript
* **Audio/Video:** HTML5 `<video>`/`<audio>`, Web Audio API, WebVTT
* **Libraries:** * [Phosphor Icons](https://phosphoricons.com/) (UI Icons)
    * [jsmediatags](https://github.com/aadsm/jsmediatags) (ID3 Tag Extraction)
    * [hls.js](https://github.com/video-dev/hls.js/) (HLS/m3u8 Stream Playback)
    * [FFmpeg.wasm](https://ffmpegwasm.netlify.app/) (In-browser video remuxing)

---

## 📜 Disclaimer
This project is not affiliated with, endorsed by, or sponsored by Microsoft Corporation. All UI designs, references, and aesthetics are utilized under fair use for parody and historical recreation purposes.
