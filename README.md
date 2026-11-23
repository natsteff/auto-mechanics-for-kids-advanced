# Automotive Tech for Kids

A mobile-first educational game for children ages 6–8. Learn about 12 car parts and tools, complete an eight-question Garage Quiz and six-question Fix-It Missions, and earn progress badges. Dad (Dillian) provides safety reminders.

## Play online
https://natsteff.github.io/auto-mechanics-for-kids-advanced/

Open the URL in Safari or Chrome. On iPhone, choose Share → Add to Home Screen. On Android Chrome, choose menu → Add to Home screen or Install app.

## Development
Static HTML, CSS and JavaScript; no dependencies or backend. Open index.html in a browser for basic local play. The service worker requires HTTPS or localhost. Learning content and activities are defined in the lessons and challenges arrays in index.html.

## Progress
Progress is stored in localStorage on each device. Settings provides JSON backup, restore, and reset. Browser storage clearing removes progress. A service worker caches app files for offline use after first online load.

## Updating
Commits to main run the GitHub Pages deployment workflow. Open GitHub Actions to inspect status. Refresh the installed app while online to retrieve updates.

## Safety and accessibility
All repair scenarios are pretend. Children must not use real vehicle jacks, touch batteries, engines or moving parts. Large controls, keyboard focus, reduced motion and text feedback are provided. Narration is intentionally not included.

## Assets and limitations
The uploaded original character and logo artwork are not yet included in the hosted release. The current online app uses emoji and a simple SVG icon. Visual device testing and real-phone installation remain to be verified.
