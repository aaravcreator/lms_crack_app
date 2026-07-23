# Course Chapter Explorer

A lightweight web app for exploring course content by pasting a course URL and loading the available chapters, sub-chapters, and downloadable assets.

## Features

- Paste a course URL and fetch the course structure
- Browse chapters and sub-chapters in a collapsible view
- Preview videos directly in the app
- Download course files when available
- Clean dark-themed interface with a glowing hero section

## How to Run

Open the project in a browser directly from the workspace file, or serve it locally with a simple web server:

```bash
cd /Users/aaravcreator/Downloads/lms_app
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/index.html
```

## Notes

- This page is a front-end interface and depends on the course URL and API details you provide.
- Some course data may require valid session credentials or bearer tokens depending on the platform.
