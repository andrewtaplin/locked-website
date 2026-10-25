LOCKED WEBSITE - LOCAL TEST

Option 1 (simplest):
1. Open the locked-website folder.
2. Double-click index.html.

Option 2 (recommended local server):
Windows PowerShell:
  cd path\to\locked-website
  py -m http.server 8000
Then open http://localhost:8000

The site is self-contained except for optional Google fonts. If offline, it falls back to system fonts.
The interactive prototype supports mood selection, task completion, progress tracking, and adding tasks during the current session.
