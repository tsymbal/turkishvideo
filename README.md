**[English](README.md)** | **[Русский](README.ru.md)** 

# Turkish Video Player

> A flexible HTML5/JS video player for simultaneous playback of multiple videos in a customizable grid with a marquee and logo.

## Overview

**Turkish Video Player** is a flexible **HTML5/JS video player** designed for simultaneous playback of multiple video files in a customizable grid (multi-video grid). The player is controlled via a simple **JSON config**, allowing for easy modification of the layout, appearance, and behavior without editing the code. The project is ideal for local execution directly from a folder in a browser and can be easily adapted for websites and online installations.

## Use Cases

This project is useful for anyone looking for a flexible and customizable solution to display multiple videos simultaneously, for example, for:
*   **Interactive Installations:** Demonstrating various video materials in exhibition spaces.
*   **Digital Signage:** Displaying promotional or informational videos on a single screen.
*   **Educational Purposes:** Playing educational videos in parallel.
*   **Entertainment Platforms:** Creating unique video collages or multi-screen presentations.
*   **Testing and Debugging Video Content:** Viewing multiple versions of a video at the same time.

## Features

### 🎥 Flexible Video Grid

*   **Multiple Layouts:** Support for various grid configurations (e.g., 2x2, 3x1) for simultaneous playback of multiple video streams.
*   **Visual Customization:**
    *   Adjustable `gap` between video elements.
    *   Customizable corner `radius` for each video.
    *   Option to use a background color (`bgColor`) for the entire video grid.
    *   Optional borders (`borderWidth`, `borderColor`) for video elements.
*   **Playlist Management:** Easily define a list of video files (`playlistFileNames`) for playback.

### 🖼️ Dynamic Logo

*   **Optional Display:** Ability to enable or disable a custom logo (image).
*   **Full Customization:**
    *   Adjust size (`size`), padding (`padding`), and corner radius (`radius`).
    *   Flexible positioning (`position`) of the logo (e.g., center, corner).
    *   Adjustable outer margins (`margin`).
    *   Customizable logo background with adjustable opacity (`bgOpacity`) and blur effect (`blur`).

### 📜 Marquee (Scrolling Text)

*   **Enable/Disable:** Ability to activate or deactivate the marquee feature.
*   **Custom Text:** Fully editable text content (`text`) for messages.
*   **Rich Styling Options:**
    *   Selection of cross-platform font sets (`fontFamily`), with support for bold (`bold`) and italic (`italic`) text.
    *   Adjustable font size (`fontSize`) and text color (`fontColor`).
*   **Motion Control:**
    *   Set scroll speed (`speed`) and character spacing (`spacing`).
    *   Position the marquee (`position`) at the top or bottom.
*   **Background Effects:**
    *   Customizable marquee background with corner radius (`radius`), blur (`blur`), color (`bgColor`), and opacity (`bgOpacity`).
    *   Adjustable horizontal (`marginX`) and vertical (`marginY`) margins.

## Tech Stack

The project is built on standard web technologies, requiring no external libraries or frameworks.

*   **HTML5:** For structure and video embedding (`<video>`).
*   **CSS3:** For styling the grid, logo, marquee, and creating a responsive design.
*   **JavaScript (Vanilla JS):** For player logic, configuration loading, and dynamic style application.
*   **JSON:** For storing all player settings and configurations.

## Quick Start

1.  **Gather Files:** Place all the files you plan to use (videos, logo) in the same folder as `index.html` (or `index.ru.html` if you are Russian).
2.  **Run the Player:** Open the `index.html` file in a modern web browser (e.g., Chrome, Firefox, Safari).
3.  **Configure:** Select files and customize the player's styles. Settings can be saved to a `settings.json` file for quick restoration later.

## Configuration Examples

The repository includes examples of video and image files, as well as JSON configuration files (`settings.json`, `bw_landscape.json`, `blue_rounded_grid.json`), demonstrating various preset styles and settings. Use the "Load Settings" button to quickly switch between saved configurations.

## Contact

For questions and suggestions, you can contact the author:
*   **Website:** tsymbal.su
*   **Email:** a@tsymbal.su

`video player, multi-video player, video grid, HTML5 video, JavaScript player, JSON config, customizable player, digital signage, video wall, marquee, local player, offline player, Vanilla JS, open source`