# Before the World Fades

An atmospheric, 3D interactive web experience exploring the themes of cognitive decline, memory erosion, and terminal lucidity. Heavily inspired by the liminal aesthetic of the Backrooms and the sonic progression of The Caretaker’s *Everywhere at the End of Time*.

This project is built to run entirely in the web browser using **Three.js** and the **Web Audio API**.

---

## 🌌 The Concept

*Before the World Fades* is designed as a slow-burn, 30-minute progression. The game begins in a warm, nostalgic, and structurally stable environment. As time passes, the physical space, gravity, and audio degrade through six stages, mimicking the tragic and disorienting progression of dementia and Alzheimer's disease.

### The Six Stages
1. **Clear Reverie (0:00 – 5:00):** A warm, pristine hotel corridor. Cozy furniture, familiar melodies, and stable physics.
2. **The First Hesitation (5:00 – 10:00):** Subtle misalignments in the walls. The melody begins to loop awkwardly; space begins to stretch.
3. **Entangled Realities (10:00 – 15:00):** Peelings walls and concrete. The geometry shifts like tectonic plates, and gravity smoothly rotates.
4. **Post-Awareness Static (15:00 – 20:00):** Monochrome, shattered geometry floating in a dark void. Teleporting doorways and deep static.
5. **The Great Confusion (20:00 – 25:00):** Colossal, abstract monoliths. Chaotic gravity, distorted brass drones, and unrecognizable surroundings.
6. **Terminal Silence (25:00 – 30:00):** An infinite grey void containing only a single armchair and a handless grandfather clock. A quiet transition into a clean, peaceful melody, ending in complete silence.

---

## 🎮 Controls
* **Movement:** `W`, `A`, `S`, `D` (or Arrow Keys)
* **Look Around:** Mouse (Pointer Lock)
* **Interact:** Click or `E` (when approaching glowing focal points)

---

## 📂 Repository Structure

To run the game, your repository should be structured as follows:

```text
before-the-world-fades/
├── index.html          # Contains the HTML, CSS, and Three.js logic
└── audio/              # Store your optimized audio tracks here
    ├── stage1.mp3      # Cut from "A1 - It's just a burning memory"
    ├── stage2.mp3      # Cut from "C1 - A losing battle is raging"
    ├── stage3.mp3      # Cut from "E1 - Back there Benjamin"
    ├── stage4.mp3      # Cut from "G1 - Stage 4 Post-Awareness Confusions" (first 5m)
    ├── stage5.mp3      # Cut from "K1 - Stage 5 Advanced plaque entanglements" (first 5m)
    └── stage6.mp3      # Cut from "R1 - Stage 6 Place in the world fades away" (13:00 to 18:00)
```

---

## 🎵 Audio Preparation Guide

Because this game runs in the browser, using raw, full-length tracks from *Everywhere at the End of Time* will make the page load very slowly. It is highly recommended to compress and trim your audio files using a tool like Audacity before uploading:

* **Format:** MP3 (128kbps or 192kbps is recommended for web performance).
* **`stage1.mp3`**: Smoothly loop the original track (~3:32).
* **`stage2.mp3`**: Smoothly loop the original track (~4:37).
* **`stage3.mp3`**: Smoothly loop the original track (~4:14).
* **`stage4.mp3`**: Export only the first 5 minutes (0:00 to 5:00).
* **`stage5.mp3`**: Export only the first 5 minutes (0:00 to 5:00).
* **`stage6.mp3`**: Export a 5-minute clip from **13:00 to 18:00** of the original 22-minute track. This ensures you capture the empty drone transition followed by the clean organ/choir finale.

---

## 🚀 Deployment (GitHub Pages)

To host this project for free using GitHub Pages:

1. Push your `index.html` and the `audio/` folder containing the prepped tracks to your repository.
2. Go to your repository on GitHub.
3. Click on **Settings** (gear icon at the top).
4. Scroll down to the **Pages** section on the left sidebar.
5. Under **Build and deployment**, set the source to **Deploy from a branch**.
6. Select your branch (usually `main` or `master`) and folder (usually `/ (root)`), then click **Save**.
7. Wait a few minutes. GitHub will provide a live link (e.g., `https://your-username.github.io/before-the-world-fades/`).

---

## 📝 Disclaimer & Inspiration

This project is an artistic, abstract representation of cognitive decline. It is not a clinical study or a precise medical simulation, but rather a psychological and spatial exploration of forgetting, detachment, and acceptance.

* **Inspiration:** Leyland Kirby (The Caretaker), specifically the album cycle *Everywhere at the End of Time*.
* **Visuals:** The liminal space community and the Backrooms mythos.
* **Technology:** Built with Three.js (WebGL) and the Web Audio API.

```
