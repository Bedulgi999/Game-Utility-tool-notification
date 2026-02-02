[README_UPLOAD.md](https://github.com/user-attachments/files/25004820/README_UPLOAD.md)
# Game Utility Tool – Announcements (GitHub package)

## What to do
1) Upload the `announcements/` folder to your GitHub repository root:
   `Bedulgi999/Game-Utility-tool-notification`
2) Commit & push to `main` branch.

## URL the app will fetch
https://raw.githubusercontent.com/Bedulgi999/Game-Utility-tool-notification/main/announcements/index.json

## Add a new announcement
1) Create a new JSON file: `announcements/<id>.json`
2) Add an entry in `announcements/index.json`:
   { "id": "<id>", "file": "<id>.json" }

## Images
Put images in `announcements/images/` and reference them like:
https://raw.githubusercontent.com/Bedulgi999/Game-Utility-tool-notification/main/announcements/images/your-image.png
