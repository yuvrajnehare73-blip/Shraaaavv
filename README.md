# Shravikkaa's 17th Birthday Website 🎀

A pink scrapbook-style, fixed-screen interactive birthday surprise. It has centered popups, floating balloons, confetti, an animated cake, a funny childhood-photo reveal, and a heartfelt letter.

## Files
- `index.html` — website
- `assets/shravikka-childhood.jpg` — childhood photo placeholder (replace with the photo you sent)
- `assets/music.mp3` — optional music file (you add this yourself)

## Add her childhood photo
Save the childhood photo as `shravikka-childhood.jpg` and put it inside `assets/`, replacing the placeholder file.

## Add more photos/videos
Put your media inside `assets/`. To show your own photos/videos in the final memory chapter, you can add filenames and `<img>` or `<video controls>` elements to `index.html`. Example:
```html
<img src="assets/your-photo.jpg" alt="Our memory">
<video controls playsinline src="assets/our-video.mp4"></video>
```
For audio, add a song you have permission to use as `assets/music.mp3`. The music button is ready to play it.

## Publish as a separate GitHub Pages website
1. Create a **new public repository** on GitHub, for example `shravikkaa-birthday`.
2. Upload **all contents of this ZIP** (upload `index.html`, `README.md`, and the `assets` folder; do not upload only the ZIP itself).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then Save.
6. Wait a minute or two and refresh Settings → Pages to find your website link.

Keep the `assets` folder alongside `index.html` or the photo/music paths will not work. The page works best with an internet connection for decorative fonts; it still has fallback fonts if unavailable.
