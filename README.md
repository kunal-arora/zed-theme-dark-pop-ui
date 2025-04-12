# Pop UI Theme for Zed

A comfortable and visually appealing dark mode theme for [Zed](https://zed.dev). Pop UI Theme is designed with clarity and minimalism in mind, providing a striking balance between aesthetics and usability. Whether you're coding late at night or prefer a soft look during the day, this theme adapts beautifully to your environment.

## Features

- **Elegant Dark Mode:** A sleek, high-contrast color palette to reduce eye strain.
- **Soft Dark Option:** A gentler version for users who prefer a less intense display.
- **System-Aware Appearance:** Automatically switches themes based on your system's light/dark mode preferences.
- **Optimized for Clarity:** Enhance code readability and create an immersive coding environment.

## Screenshots

### Dark Mode
<img width="1918" alt="Screenshot 2025-04-12 at 5 18 07 PM" src="https://github.com/user-attachments/assets/c63c0835-f1b0-466b-8d78-92224aff9bca" />

### Soft Dark Mode
<img width="1918" alt="Screenshot 2025-04-12 at 5 18 19 PM" src="https://github.com/user-attachments/assets/1a23dd30-3a26-44f1-a9fb-4c0315597bd9" />

## Installation & Usage

To enable the Pop UI Theme in Zed, follow these simple steps:

1. **Open your user settings:**
  Locate and open the settings file at `~/.config/zed/settings.json`.

2. **Configure the theme settings:**

  ```json
  {
    "theme": "Dark Pop UI"
  }
  ```
  or for soft dark mode:
  ```json
  {
    "theme": "Soft Dark Pop UI"
  }
  ```

More settings that I recommend:
```json
{
  "theme": "Dark Pop UI",
  "indent_guides": {
    "enabled": true,
    "coloring": "indent_aware"
  },
  "buffer_font_features": {
    "calt": false,
    "liga": false
  },
  "ui_font_size": 13,
  "buffer_font_size": 12.0,
  "cursor_blink": true,
  "experimental.theme_overrides": {},
  "git": {
    "inline_blame": {
      "enabled": true,
      "min_column": 150
    }
  },
  "assistant": {
    "default_model": {
      "provider": "copilot_chat",
      "model": "claude-3-7-sonnet"
    },
    "version": "2",
    "dock": "right",
    "default_width": 180,
    "button": true
  },
  "edit_predictions": {
    "mode": "eager"
  },
  "features": {
    "edit_prediction_provider": "copilot"
  },
  "show_edit_predictions": true,
  "collaboration_panel": {
    "dock": "right"
  },
  "project_panel": {
    "indent_size": 12,
    "show_hidden_files": true,
    "show_ignored_files": true,
    "show_warnings": true,
    "show_errors": true
  },
  "terminal": {
    "cursor_shape": "bar",
    "blinking": "on",
    "shell": "system",
    "dock": "right",
    "default_width": 180
  },
  "restore_on_startup": "last_session",
  "preview_tabs": {
    "enabled": true,
    "enable_preview_from_code_navigation": true
  },
  "telemetry": {
    "metrics": false,
    "diagnostics": true
  }
}
```
