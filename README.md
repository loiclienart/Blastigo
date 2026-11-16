<div align="center">

# Blastigo

**Compose your views. Preview your animation. Export your playblast.**

A multi-camera playblast tool for Autodesk Maya, created by **Loïc Liénart**.

### [Download the latest version](https://github.com/loiclienart/Blastigo/releases/latest)

[Installation](#installation) · [Release notes](https://github.com/loiclienart/Blastigo/releases) · [Report an issue](https://github.com/loiclienart/Blastigo/issues)

**Maya 2025+ · MP4 / MOV · English / Français**

</div>

![Blastigo multi-camera composition interface](https://github.com/user-attachments/assets/e0c7076c-03c7-4d7e-94e0-eabac353c29e)

## Build your playblast in one place

- **Live Maya viewports** with timeline and playback controls.
- **Flexible compositions:** split, merge, reorder and resize camera views; adjust framing, zoom and position.
- **Composition or sequential playback**, with custom output resolutions.
- **MP4 H.264, MOV H.264 and MOV ProRes 422**, with audio, speed, repeats and final-frame hold.
- **Optional NVIDIA NVENC acceleration** for H.264 encoding, with availability detection and CPU fallback.
- **Undo/redo, saved compositions and personal defaults**, plus automatic camera rename tracking while the tool is open.
- **In-app update checks** for future releases.

## Installation

1. Open **[the latest release](https://github.com/loiclienart/Blastigo/releases/latest)** and download `Blastigo-<version>.zip`.
2. Fully extract the archive.
3. Drag **INSTALLER.mel** into a Maya viewport.
4. Choose your shelf, click **Install**, then open Blastigo using its shelf button.
5. If prompted, select the folder containing **FFmpeg and FFprobe**.

> Download the installer ZIP from **Releases**. The **Code → Download ZIP** archive is not the Blastigo installer.

If an older version was already loaded, restart Maya after installation. Future updates are available in **Preferences → Updates** and take effect after Maya restarts.

## Requirements

- **Autodesk Maya 2025 or later**, with its bundled Python, PySide6 and Viewport 2.0.
- **[FFmpeg and FFprobe](https://ffmpeg.org/download.html)** with `libx264`, `aac`, `prores_ks` and `pcm_s16le`. They are not included in the download.
- A writable output folder with enough free space for temporary captures.

**Tested native environment:** Windows with Maya 2025.3.1. Native Maya validation on macOS, Linux and other Maya versions is still pending.

NVIDIA encoding is optional and disabled by default; it requires a compatible GPU, driver and FFmpeg build. Final ProRes encoding remains on the CPU. Multi-view playback performance depends on the scene and hardware. Audio supports a single Time Slider track; Trax mixes are not supported.

<details>
<summary><strong>Français — Présentation et installation</strong></summary>

## Composez et exportez vos playblasts

Blastigo est un outil de playblast multi-caméras pour Autodesk Maya, créé par **Loïc Liénart**.

- **Viewports Maya en direct**, avec timeline et commandes de lecture.
- **Compositions personnalisées :** division, fusion, réorganisation, dimensions des vues, cadrage, zoom et position.
- **Modes Composition et À la suite**, avec résolution de sortie personnalisable.
- **Export MP4 H.264, MOV H.264 et MOV ProRes 422**, avec audio, vitesse, répétitions et maintien final.
- **Accélération NVIDIA NVENC optionnelle** pour le H.264, avec détection de disponibilité et retour sur CPU.
- **Annuler/Rétablir, compositions enregistrées et préférences personnelles**, avec suivi du renommage des caméras pendant que le tool est ouvert.
- **Vérification intégrée des prochaines mises à jour.**

### Installation

1. Ouvrez **[la dernière version](https://github.com/loiclienart/Blastigo/releases/latest)** et téléchargez `Blastigo-<version>.zip`.
2. Décompressez entièrement l’archive.
3. Glissez **INSTALLER.mel** dans un viewport Maya.
4. Choisissez votre shelf, cliquez sur **Installer**, puis ouvrez Blastigo avec son bouton de shelf.
5. Si demandé, indiquez le dossier contenant **FFmpeg et FFprobe**.

> Téléchargez le ZIP d’installation depuis **Releases**. L’archive **Code → Download ZIP** n’est pas l’installateur de Blastigo.

Si une ancienne version était déjà chargée, redémarrez Maya après installation. Les prochaines mises à jour sont accessibles dans **Préférences → Mises à jour** et prennent effet après redémarrage de Maya.

### Prérequis et compatibilité

**Maya 2025 ou ultérieur**, avec Python, PySide6 et Viewport 2.0 fournis par Maya ; **FFmpeg et FFprobe** avec les encodeurs `libx264`, `aac`, `prores_ks` et `pcm_s16le` ; un dossier de sortie accessible et suffisamment d’espace libre. FFmpeg et FFprobe ne sont pas inclus.

**Environnement natif testé :** Windows avec Maya 2025.3.1. La validation native dans Maya sur macOS, Linux et les autres versions de Maya reste à effectuer.

L’option NVIDIA est désactivée par défaut et nécessite du matériel, un pilote et une build FFmpeg compatibles. L’encodage final ProRes reste sur le processeur. La fluidité dépend de la scène et du matériel. Une piste simple du Time Slider est prise en charge ; les mixages Trax ne le sont pas.

</details>

---

Created by **Loïc Liénart** · [Downloads](https://github.com/loiclienart/Blastigo/releases/latest) · [Feedback & issues](https://github.com/loiclienart/Blastigo/issues)
