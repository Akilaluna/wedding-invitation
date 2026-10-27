# Akila ♥ Vinod – Online Wedding Invitation

Swipeable wedding invitation (English / தமிழ்) with soft music, countdown, map links and QR codes.

## Files
| File | What it is |
|---|---|
| `index.html` | The whole website |
| `assets/couple.jpg` | Bride & groom photo (replace with any photo, same name) |
| `assets/qr-chennai.png` | QR → KM Palace, Kundrathur |
| `assets/qr-coimbatore.png` | QR → Jothimani Ponnaiyah Marriage Hall, Coimbatore |
| `assets/music.mp3` | Background song (add it yourself – see below). If it is missing, the music button is hidden. |

## Host on GitHub Pages
1. Create a new **public** repository on GitHub, e.g. `akila-vinod`.
2. Upload everything in this folder (`index.html`, `assets/`, `README.md`) → **Commit changes**.
3. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → **Save**.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/akila-vinod/`.

## For a nice WhatsApp link preview
In `index.html`, change
`<meta property="og:image" content="assets/couple.jpg">`
to the full URL, e.g. `https://<your-username>.github.io/akila-vinod/assets/couple.jpg`.

## Using your own music
Save your song (e.g. an "Ummachi Ummachi" instrumental) as exactly `assets/music.mp3` — lowercase, GitHub Pages is case-sensitive. Keep it small (2–5 MB). It fades in when the guest taps "Open Invitation" and loops at low volume.
