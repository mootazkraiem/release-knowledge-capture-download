# Release Knowledge Capture: download

This page is only for downloading **Release Knowledge Capture**, a small Windows app for capturing
team knowledge (Problem / Solution, Information, Procedure) before it is reviewed in RCK.

## Download

1. Open the [**latest release**](../../releases/latest) and download `ReleaseKnowledgeCapture-v1.0.0.zip`.
2. The zip is **password-protected** (AES-256). Ask the maintainer for the password.
3. Open it with **7-Zip** or **WinRAR**. The zip opener built into Windows can't open AES-encrypted zips.

## Inside the zip

| File | What it is |
|------|------------|
| `ReleaseKnowledgeCapture.exe` | The app as one file. Double-click it; nothing to install (Windows 10/11). |
| `release_knowledge_capture.py` | The same app as one Python file. Run `pip install pywebview`, then `python release_knowledge_capture.py`. |

## First launch

The app asks for your full name once, then creates the folder `RCK Entry (<your name>)` on your
Desktop. Every entry you capture is saved there as a JSON file with status *pending review*. Later
launches go straight to the home screen and reuse the same folder.

To hand your knowledge over for RCK, send the `RCK Entry (…)` folder to the maintainer.
