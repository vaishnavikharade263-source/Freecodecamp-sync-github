# Freecodecamp-sync-github
FreeCodeCamp → GitHub Sync Extension
A Chrome extension that automatically syncs your FreeCodeCamp project code to a GitHub repository.
This tool helps learners showcase their progress and maintain a portfolio without manual copy‑paste.

✨ Features
Sync FreeCodeCamp code directly to GitHub.

Supports automatic syncing when you run/submit code.

Saves each project as a new file (fcc_project_TIMESTAMP.js by default).

Configurable repo, commit message, and GitHub token via popup UI.

📦 Installation
Clone or download this repository.

Open Chrome and go to chrome://extensions.

Enable Developer Mode.

Click Load unpacked and select the project folder.

Pin the extension to your toolbar for easy access.

🔑 Setup
Generate a GitHub Personal Access Token (PAT) with repo scope.

Go to Settings → Developer settings → Personal access tokens → Tokens (classic).

Copy the token (you’ll need it only once).

Open the extension popup and enter:

GitHub repo name (username/repo)

Personal Access Token

Commit message

🚀 Usage
Open any FreeCodeCamp project.

Run or submit your code.

The extension will automatically sync your code to GitHub.

Check your repo — your project will appear as a new file.

⚠️ Notes & Limitations
The extension requires that at least one FreeCodeCamp project tab (with the editor open) is active.

If no project is open, the sync won’t trigger.

Keep your completed project open in the browser when syncing.

GitHub Personal Access Token must have repo scope.

FreeCodeCamp’s editor DOM may change — if syncing stops working, update the content script selector.

Automatic syncing is tied to the “Run Code” or “Submit” button; syncing on every keystroke is disabled to avoid flooding GitHub.
