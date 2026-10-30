DoricTrack Pro PWA deployment

1. Upload ALL files and folders in this package to the ROOT of your GitHub Pages repository.
2. Keep the filename exactly index.html. Keep manifest.webmanifest, sw.js, and icons/ alongside it.
3. In GitHub: Settings > Pages > Deploy from branch > main > /(root), then Save.
4. Open the HTTPS GitHub Pages URL in Chrome/Edge.
5. Install: Chrome/Edge menu > Install app (or the install icon in the address bar).
   Android Chrome: menu > Install app / Add to Home screen.
   iPhone Safari: Share > Add to Home Screen.
6. Sign in with the same Supabase email/password on each device.

Important: PWA offline caching stores only the app shell. Supabase login and cloud data require an internet connection. This package does not migrate or delete existing local records. Test with a backup and one harmless sample record first.
