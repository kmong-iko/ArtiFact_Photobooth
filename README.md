# 📸 ArtiFact Photobooth

A browser-based camera photobooth developed as part of **ArtiFact**, a gamified Augmented Reality system for the National Museum of Fine Arts.

The photobooth was designed for the ArtiFact thesis booth, allowing visitors and guests to capture memorable photos while exploring the project's interactive and creative experience.

## ✨ Features

- **Live Camera Preview** – Accesses the device's front-facing camera for real-time viewing.
- **Vintage Photo Filter** – Applies warm tones, enhanced colors, subtle sharpening, and a retro CRT effect.
- **Custom Photobooth Design** – Features a decorative layout with illustrated stickers and animated elements.
- **Photo Capture** – Captures the camera feed together with the complete photobooth layout.
- **Automatic Download** – Saves captured photos directly to the device in JPEG format.
- **Responsive Layout** – Adapts the photobooth composition to different screen sizes.
- **Camera Recovery** – Automatically attempts to reconnect when the camera disconnects.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- Canvas API
- MediaDevices API (`getUserMedia`)
- SVG Filters

## 📂 Project Structure

```text
photobooth/
│
├── index.html
│
└── assets/
    ├── background.jpg
    ├── doily.webp
    ├── tape.webp
    ├── camera.webp
    ├── seal.webp
    ├── art.webp
    ├── cookie.webp
    ├── apple.webp
    ├── heart.webp
    ├── ladybug.webp
    │
    └── fonts/
        └── homemade-apple.woff2
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Open the Project

Navigate to the project folder:

```bash
cd photobooth
```

### 3. Run Locally

Open the project using a local development server, such as the **VS Code Live Server** extension.

Alternatively, serve it through `localhost`.

> **Note:** Camera access requires a secure context (HTTPS or localhost). Make sure to allow camera permissions when prompted by your browser.

## 📷 How to Use

1. Open the photobooth in a supported browser.
2. Allow camera access when prompted.
3. Position yourself within the camera frame.
4. Click the camera button at the bottom-right corner to capture your photo.
5. Wait for the photo to be processed.
6. Your captured photo will automatically download as a JPEG file.

## 🎨 Customization

The photobooth's visual effects can be adjusted through the `LOOK` configuration object inside `index.html`.

Available adjustments include:

- Saturation and brightness
- Contrast and sepia
- Warm color tint
- Sharpening
- CRT scanlines
- Analog grain
- RGB color separation
- Vignette effect

The decorative assets and background can also be replaced through the `assets/` folder.

## 🎓 About the Project

This photobooth was created as a supplementary interactive experience for **ArtiFact: A Gamified Augmented Reality System Utilizing Homography, ORB, and RANSAC for Image Identification at the National Museum of Fine Arts**.

It served as part of the project's physical thesis booth, giving visitors a fun way to engage with the team's presentation and take home a small digital souvenir.

---

*Developed as part of the ArtiFact thesis project.*
