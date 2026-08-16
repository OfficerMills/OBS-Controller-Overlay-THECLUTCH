<p align="center">
  <a href="https://theclutch.net" target="_blank" rel="noopener noreferrer">
    <img 
      src="EXAMPLE%20IMAGES/THECLUTCH_Banner.png" 
      alt="The Clutch — Visit THECLUTCH.NET"
      width="100%"
    >
  </a>
</p>

<p align="center">
  <a href="https://theclutch.net">
    <img src="https://img.shields.io/badge/The%20Clutch-THECLUTCH.NET-5865F2?style=flat&logo=googlechrome&logoColor=white" alt="The Clutch Website">
  </a>
  <a href="https://discord.gg/BQkXttTR4n">
    <img src="https://img.shields.io/badge/Discord-Join%20The%20Clutch-5865F2?style=flat&logo=discord&logoColor=white" alt="Join The Clutch Discord">
  </a>
  <a href="https://x.com/TheClutch_USA">
    <img src="https://img.shields.io/badge/TheClutch_USA-000000?style=flat&logo=x&logoColor=white" alt="GregTheClutch on X">
  </a>
  <a href="https://www.instagram.com/greghatchette/">
    <img src="https://img.shields.io/badge/Instagram-%40GregHatchette-E4405F?style=flat&logo=instagram&logoColor=white" alt="GregHatchette on Instagram">
  </a>
  <a href="https://www.tiktok.com/@thisistheclutch">
    <img src="https://img.shields.io/badge/TikTok-%40ThisIsTheClutch-000000?style=flat&logo=tiktok&logoColor=white" alt="This Is The Clutch on TikTok">
  </a>
  <a href="https://www.twitch.tv/gregtheclutch">
    <img src="https://img.shields.io/badge/Twitch-GregTheClutch-9146FF?style=flat&logo=twitch&logoColor=white" alt="GregTheClutch on Twitch">
  </a>
</p>

<p align="center">
  <a href="https://github.com/OfficerMills/OBS-Controller-Overlay-THECLUTCH/releases/latest">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/officermills/OBS-Controller-Overlay-THECLUTCH?style=plastic&logo=Github&logoSize=auto&label=Download%20Size&color=%23FFFF00">
  </a>
  <a href="https://github.com/OfficerMills/OBS-Controller-Overlay-THECLUTCH/releases">
    <img alt="GitHub Release" src="https://img.shields.io/github/v/release/officermills/OBS-Controller-Overlay-THECLUTCH?include_prereleases&style=plastic&logo=github&logoSize=auto&label=Latest%20Release&color=%23FFFF00">
  </a>
  <a href="https://github.com/OfficerMills/OBS-Controller-Overlay-THECLUTCH/stargazers">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/officermills/OBS-Controller-Overlay-THECLUTCH?style=plastic&logo=Github&label=Stars&color=%23FFFF00">
  </a>
</p>


# 🎮 The Clutch — Input-Overlay Controller Overlay

A preconfigured **controller overlay package for OBS Studio**, powered by [Input-Overlay](https://github.com/univrsal/input-overlay).

This package includes the required Input-Overlay plugin installer, **The Clutch controller overlay**, configuration files, example videos, and installation documentation.



<p align="center">
  <strong>
    <span style="font-size: 1.15em;">
      <a href="#-installation">INSTALLATION</a>
      &nbsp;•&nbsp;
      <a href="#-configuration">CONFIGURATION</a>
      &nbsp;•&nbsp;
      <a href="#%EF%B8%8F-troubleshooting">TROUBLESHOOTING</a>
      &nbsp;•&nbsp;
      <a href="#-credits--licensing">CREDITS</a>
      &nbsp;•&nbsp;
      <a href="#-support">SUPPORT</a>
    </span>
  </strong>
</p>

<details>
<summary><strong>📑 Table of Contents</strong></summary>

<br>

- [📦 Installation](#-installation)
  - [1. Download & Extract](#1-download--extract)
  - [2. Install the Input-Overlay Plugin](#2-install-the-input-overlay-plugin)
  - [3. Install The Clutch Controller Overlay](#3-install-the-clutch-controller-overlay)

- [🎮 Configuration](#-configuration)
  - [4. Add the Overlay to OBS](#4-add-the-overlay-to-obs)
  - [5. Position & Resize](#5-position--resize)
  - [⚙️ Input-Overlay Settings](#️-input-overlay-settings)

- [🛠️ Troubleshooting](#️-troubleshooting)
  - [Overlay Doesn't Appear](#overlay-doesnt-appear)
  - [Controller Inputs Aren't Showing](#controller-inputs-arent-showing)
  - [Overlay Looks Incorrect](#overlay-looks-incorrect)

- [📁 File Structure](#-file-structure)

- [💡 Quick Reference](#-quick-reference)

- [📜 Credits & Licensing](#-credits--licensing)
  - [Input-Overlay](#input-overlay)
  - [The Clutch Controller Overlay](#-the-clutch-controller-overlay)
  - [Third-Party Software](#️-third-party-software)

- [🤝 Support](#-support)

- [🎮 Ready to Go](#-ready-to-go)

<br>

### 📂 Repository Files

- 📜 [LICENSE](LICENSE)
- 📄 [Installation Guide](INSTALLATION%20GUIDE.md)
- 🎞️ [Example Videos](EXAMPLE%20VIDEOS/)
- 🖼️ [Example Images](EXAMPLE%20IMAGES/)
- 🎮 <a href="b)%20Add%20Contents%20of%20This%20Folder%20to%20Desired%20Location/Controller%20Overlay%20TheClutch/">Controller Overlay — The Clutch</a>

</details>

---

## 📦 Installation

### 1. Download & Extract

Download the provided ZIP file and **extract the entire contents** to a location of your choice.

After extraction, you should see a structure similar to:

```text
📁 a) INSTALL CONTENTS (Run .exe to install Input-Overlay plugin to OBS)
📁 b) Add Contents of This Folder to Desired Location
   └── Controller Overlay TheClutch
📁 🎞️ EXAMPLE VIDEOS
    └── 🎞️ Clutch-OBS-Overlay.mp4
📁 🖼️ EXAMPLE IMAGES
    └── 🖼️ image.png
        🖼️ image-1.png
        🖼️ image-2.png
        🖼️ THECLUTCH_Banner.png
📄 README.md
📜 LICENSE
```

> [!NOTE]
> The names and contents of individual files may vary slightly between releases.

---

### 2. Install the Input-Overlay Plugin

Open:

```text
a) INSTALL CONTENTS
```

Locate and run the `.exe` installer contained inside the folder.

Follow the installation prompts to install **Input-Overlay** into OBS Studio.

> [!IMPORTANT]
> If OBS Studio was already running during installation, completely close and restart OBS before continuing.

---

### 3. Install The Clutch Controller Overlay

Open:

```text
b) Add Contents of This Folder to Desired Location
```

Inside this folder you'll find:

```text
Controller Overlay TheClutch
```

Copy the **entire `Controller Overlay TheClutch` folder**.

Paste it into the same location where you keep your other custom Input-Overlay configurations.

> [!WARNING]
> Do **not** separate the `.png` and `.json` files. Both files are required for the overlay to function correctly and should remain together inside the `Controller Overlay TheClutch` folder.

---

## 🎮 Configuration

### 4. Add the Overlay to OBS

Open **OBS Studio** and navigate to the scene where you want to use the controller overlay.

1. Select your desired scene.
2. Locate the **Sources** panel.
3. Click **`+`** to add a new source.
4. Select **Input Overlay**.
5. When the Input-Overlay configuration window appears, locate the **Image** field.
6. Click **Browse**.
7. Navigate to your `Controller Overlay TheClutch` folder.
8. Select the provided `.png` file.

Next, locate the **Configuration** field.

9. Click **Browse**.
10. Navigate to the same `Controller Overlay TheClutch` folder.
11. Select the provided `.json` configuration file.

Your configuration should look similar to:

<p align="center">
  <img src="EXAMPLE IMAGES/image.png" alt="Input-Overlay image configuration" width="48%">
  <img src="EXAMPLE IMAGES/image-2.png" alt="Input-Overlay JSON configuration" width="48%">
</p>

> [!IMPORTANT]
> Make sure the `.png` and `.json` files you select both come from the **same `Controller Overlay TheClutch` folder**.

---

### 5. Position & Resize

Once the overlay has been added successfully, it will appear in your OBS scene.

You can now:

* 🎮 Position the controller overlay anywhere in your scene
* 📐 Resize the overlay to fit your layout
* 🖱️ Move and position the source using OBS
* 🎥 Use the overlay during streams or recordings

---

## ⚙️ Input-Overlay Settings

Input-Overlay provides additional configuration options directly within OBS Studio.

You can access them from:

**`Tools → Input Overlay`**

![Input-Overlay Settings](EXAMPLE%20IMAGES/image-1.png)

> [!TIP]
> If you need to modify Input-Overlay's global settings or troubleshoot the plugin itself, check the **Tools → Input Overlay** menu before changing the controller configuration files.

---

## 🛠️ Troubleshooting

### Overlay Doesn't Appear

If the controller overlay doesn't appear in OBS, verify the following:

* Input-Overlay was installed successfully.
* OBS Studio was restarted after installation.
* An **Input Overlay** source was added to the correct scene.
* The correct `.png` file was selected.
* The correct `.json` configuration file was selected.
* The `.png` and `.json` files are located together inside `Controller Overlay TheClutch`.

---

### Controller Inputs Aren't Showing

Verify that:

1. Your controller is connected to your computer.
2. Windows recognizes the controller.
3. The controller is functioning correctly outside of OBS.
4. The Input-Overlay source has been added to the correct OBS scene.
5. The correct `.json` configuration file is selected.

> [!NOTE]
> If Windows itself does not recognize the controller, Input-Overlay cannot display its inputs.

---

### Overlay Looks Incorrect

If the controller graphics or input indicators don't appear correctly:

* Verify that you're using the provided `.png` file.
* Verify that you're using the corresponding `.json` file.
* Make sure both files came from `Controller Overlay TheClutch`.
* Do not mix configuration files from another Input-Overlay controller layout.

> [!WARNING]
> The `.png` and `.json` files are a matched pair. Using a configuration file from another overlay may cause incorrect positioning, missing inputs, or other visual problems.

---

## 📁 File Structure

After extracting the download, the package should generally look like:

```text
Input-Overlay Controller Overlay/
│
├── 📁 a) INSTALL CONTENTS
│   └── ⚙️ input-overlay-5.0.6-windows-x64-Installer.exe
│
├── 📁 b) Add Contents of This Folder to Desired Location
│   └── 📁 Controller Overlay TheClutch
│       ├── 🖼️ Clutch-game-pad.png
│       └── 📄 Clutch-game-pad.json
│
├── 📁 🎞️ EXAMPLE VIDEOS
│   └── 🕹️ Clutch-OBS-Overlay.mp4
│
├── 📁 🖼️ EXAMPLE IMAGES
│   ├── 🖼️ image.png
│   ├── 🖼️ image-1.png
│   ├── 🖼️ image-2.png
│   └── 🖼️ THECLUTCH_Banner.png
│
├── 📜 LICENSE
│
└── 📄 README.md
```

> [!NOTE]
> The exact filenames may change between releases. The important part is that the `.png` and `.json` files inside `Controller Overlay TheClutch` remain together.

---

## 💡 Quick Reference

|  Step  | Action                                                    |
| :----: | --------------------------------------------------------- |
|  **1** | Download and extract the ZIP                              |
|  **2** | Open `a) INSTALL CONTENTS`                                |
|  **3** | Run the Input-Overlay installer                           |
|  **4** | Open `b) Add Contents of This Folder to Desired Location` |
|  **5** | Copy `Controller Overlay TheClutch`                       |
|  **6** | Paste it with your other Input-Overlay configurations     |
|  **7** | Open OBS Studio                                           |
|  **8** | Add an **Input Overlay** source                           |
|  **9** | Select the `.png` file                                    |
| **10** | Select the `.json` file                                   |
| **11** | Position and resize the overlay                           |
| **12** | 🎮 Start using the controller overlay                     |

---

## 📜 Credits & Licensing

### Input-Overlay

This controller overlay package utilizes **Input-Overlay**, an open-source OBS Studio plugin created by **univrsal**.

**Original Project:**
[univrsal/input-overlay](https://github.com/univrsal/input-overlay)

**Original Author:**
[univrsal](https://github.com/univrsal)

**License:**
[GNU General Public License v2.0](LICENSE)

Input-Overlay is a separate third-party project and is **not owned or developed by The Clutch**.

For the original source code, documentation, releases, and complete licensing information, please visit the official repository:

<p align="center">
  <a href="https://github.com/univrsal/input-overlay">
    <img src="https://img.shields.io/badge/View_Original_Project-univrsal%2Finput--overlay-181717?style=for-the-badge&logo=github" alt="View Original Input-Overlay Project">
  </a>
</p>

---

### 🎮 The Clutch Controller Overlay

The following materials are part of **The Clutch's controller overlay package**:

* Controller overlay graphics
* Controller overlay configuration
* Installation package organization
* Installation documentation
* Example materials created for this distribution

Unless otherwise noted, these materials are created and maintained by **[@OfficerMills](https://discord.com/invite/FKDzHjCJNB)** for **[The Clutch](https://theclutch.net)** community.

> [!IMPORTANT]
> The Clutch controller overlay is an independent configuration/preset for Input-Overlay. It is **not an official Input-Overlay project, plugin, or release**.

---

### ⚖️ Third-Party Software

Third-party software included with or required by this package remains subject to its respective license terms.

Please refer to the [original project's repository](https://github.com/univrsal/input-overlay/blob/master/LICENSE) and included license information for the applicable terms governing Input-Overlay and its dependencies.

---

## 🤝 Support

Having trouble getting the overlay working?

Before requesting support, please verify that:

* OBS Studio is up to date.
* Input-Overlay was installed successfully.
* OBS Studio has been restarted after installation.
* The `.png` and `.json` files are from the same `Controller Overlay TheClutch` folder.
* Windows recognizes your controller.

If you're still having trouble, reach out to **[@OfficerMills](https://discord.com/invite/FKDzHjCJNB)** on Discord for assistance.

---

## 🎮 Ready to Go

That's it!

Once the Input-Overlay plugin and **Controller Overlay TheClutch** configuration have been installed, you're ready to add the controller overlay to OBS and start streaming or recording.

**Enjoy your new controller overlay!** 🎮
