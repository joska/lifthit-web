# lifthit-web

Static site for the LiftHit iOS app — landing page, support contact, and privacy policy.

Lives at https://lifthit.sekava.dev.

## Layout

- `index.html` — landing / support page (Tailwind via Play CDN)
- `content/` — app icon, screenshots, marketing copy
- `files/` — externally linked legal docs (privacy policy)

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.
