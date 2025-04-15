# 🎨 Dark Pop UI Theme for Zed

> A clean, contrast-rich dark theme for [Zed](https://zed.dev), designed to balance aesthetics and readability — with a soft mode for those long coding sessions.

---

## 📸 Preview

### Default Dark Mode  
![Dark Pop UI](https://github.com/user-attachments/assets/c63c0835-f1b0-466b-8d78-92224aff9bca)

### Soft Dark Mode  
![Soft Dark Pop UI](https://github.com/user-attachments/assets/1a23dd30-3a26-44f1-a9fb-4c0315597bd9)

---

## ✨ Features

- 🖤 **High-contrast default** – makes your syntax pop without burning your eyes.
- 🌘 **Soft dark variant** – great for mellow environments or longer sessions.
- 📐 **Minimalist UI** – subtle styling that gets out of your way.
- 👁️ **Optimized for readability** – tested across common languages and file types.

---

## ⚙️ Installation

1. Open your Zed config:  
   `~/.config/zed/settings.json`

2. Add your preferred theme:

```json
{
  "theme": "Dark Pop UI"
}
```
Or for the soft variant:

```json
{
  "theme": "Soft Dark Pop UI"
}
```

---

## 🔧 Recommended Settings

You can pair the theme with these settings for an even better dev experience:
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

---


🛠 Contributing

If you have ideas, tweaks, or color suggestions, feel free to:
	•	Fork the repo
	•	Open a pull request
	•	Or just open an issue with feedback!

---

🧑‍🎨 Author

Made with ❤️ by kunal-arora

---

📄 License

MIT — feel free to use, remix, and share.



