# FitCoach Durban — Local Preview

This folder contains a simple static landing page for FitCoach Durban.

Files:
- `gym_website.html` — main HTML file
- `styles.css` — stylesheet (moved from inline)
- `scripts.js` — JavaScript (moved from inline)

Quick preview (PowerShell):

1. Open PowerShell and change to this folder:

```powershell
Set-Location 'C:\Users\User\Desktop\Manqoba\gym'
```

2. If you have Python 3 installed, start a simple HTTP server and open the page:

```powershell
python -m http.server 8000; Start-Process 'http://localhost:8000/gym_website.html'
```

3. If you don't have Python, you can open `gym_website.html` directly in your browser by double-clicking the file.

