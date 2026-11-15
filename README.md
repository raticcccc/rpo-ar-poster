# Ready Player One – WebAR Poster (MC3101 Module 05)

Mind-AR + A-Frame image-tracking experience. Point a phone camera at the poster:
- low-poly Jade Key and Copper Key float off the poster and spin
- tap the glowing rings for info panels (Parzival, Iron Giant, release info)
- collect both keys to unlock Halliday's Easter Egg (gold glow + particle burst + fanfare)
- neon scan-line sweeps over the poster; synthwave loop plays while the poster is tracked

## Publish on GitHub Pages
1. Create a new public repo (e.g. `rpo-ar-poster`) on github.com.
2. Upload ALL files and folders in this directory (index.html, assets/, vendor/) to the repo root.
3. Repo > Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` > Save.
4. After ~1 min your URL is https://<your-username>.github.io/rpo-ar-poster/  (HTTPS, as the brief requires).
5. Open it on your phone, tap "Enter the OASIS", allow the camera, aim at the poster.

## Customising
- Text, hotspot positions and colours: the HOTSPOTS array near the top of the script in index.html
  (px/py are pixel positions on assets/poster.jpg, 741x1145).
- Tracking image: assets/poster.mind was compiled from assets/poster.jpg. If you swap the poster, recompile
  at https://hiukim.github.io/mind-ar-js-doc/tools/compile and replace poster.mind, then update IMG_W/IMG_H.
- Audio: assets/loop.mp3 (synthesised, copyright-free).

## Tips for demoing
- Good, even light and no glare on the print; fill most of the camera view with the poster.
- Tracking is the target image only, so the same poster image printed or on a screen also works.
