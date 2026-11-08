# QR video page

A public GitHub Pages video page. The repository contains only the page and the
video approved for public sharing.

- `index.html`: responsive player with muted autoplay and a play-with-sound button.
- `video.mp4`: the published video.
- `.nojekyll`: publish the static files without Jekyll processing.

Enable GitHub Pages from the `main` branch, at the repository root. Point the QR
code at the Pages URL rather than the repository or the raw video file.

Autoplay is subject to browser policy. Sound requires a user gesture in most
mobile browsers. If playback fails, use the native player controls or the direct
video link.

To replace the video while keeping the same QR code, replace `video.mp4` and
push the change to `main`. Visitors may briefly see a cached version.

Do not add API keys, internal documents, or private videos to this repository.
The page and video are public.
