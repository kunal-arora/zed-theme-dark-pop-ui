# Pop UI Theme for Zed

A comfortable and visually appealing dark mode theme for [Zed](https://zed.dev). Pop UI Theme is designed with clarity and minimalism in mind, providing a striking balance between aesthetics and usability. Whether you're coding late at night or prefer a soft look during the day, this theme adapts beautifully to your environment.

## Features

- **Elegant Dark Mode:** A sleek, high-contrast color palette to reduce eye strain.
- **Soft Dark Option:** A gentler version for users who prefer a less intense display.
- **System-Aware Appearance:** Automatically switches themes based on your system's light/dark mode preferences.
- **Optimized for Clarity:** Enhance code readability and create an immersive coding environment.

## Screenshots

### Dark Mode
*(Insert the screenshot of the dark mode here)*

### Soft Dark Mode
*(Insert the screenshot of the soft dark mode here)*

## Installation & Usage

To enable the Pop UI Theme in Zed, follow these simple steps:

1. **Open your user settings:**
   Locate and open the settings file at `~/.config/zed/settings.json`.

2. **Configure the theme settings:**
   Add (or update) the following configuration to enable auto-switching between themes based on your system appearance:

   ```json
   {
     "theme": {
       "mode": "system",
       "light": "macOS Classic Light",
       "dark": "macOS Classic Dark"
     }
   }
