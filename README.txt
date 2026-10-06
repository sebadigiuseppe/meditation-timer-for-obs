Meditation Timer for OBS

Upload this folder to GitHub and enable GitHub Pages.

OBS Browser Source (timer):
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/?mode=obs

OBS Custom Browser Dock (controls):
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/control.html

In OBS: View -> Docks -> Custom Browser Docks. Add a dock named Meditation Timer and paste the control URL.

The dock sends commands to the Browser Source using BroadcastChannel. The Browser Source owns audio playback, so bowl sounds are part of the OBS source. Configuration is persisted in localStorage.

Suggested Browser Source size: 760 x 260, 10 FPS.
