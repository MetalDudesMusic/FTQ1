# F1 Live — FongMi/TV Config

Stream F1 live on Android TV using [FongMi/TV](https://github.com/FongMi/TV).

## Quick Setup

### 1. Install FongMi/TV
Download the APK from the [Telegram release channel](https://t.me/fongmi_release) and install on your Android TV or phone.

### 2. Load the config into FongMi/TV
- Open FongMi/TV
- Go to **Settings → Config**
- Paste this URL and confirm:

```
https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/config.json
```

### 3. Watch
Go to **Live** in the app — all F1 channels will be listed and ready.

---

## Channels

| Channel | Quality | Notes |
|---|---|---|
| Formula 1 TV (US) | HD | Free, permanent, ad-supported (Amagi FAST) |
| Sky Sports F1 | HD | Direct m3u8 — best quality option |
| Sky Sports F1 UHD | UHD | Try this first for best quality |
| Sky Sports F1 FHD | FHD | Backup high quality |
| Sky Sports F1 (UK) | SD | .ts stream — fallback only |

---

## Troubleshooting

- If a stream stops working, try the next one in the list
- The Formula 1 TV (US) stream is always available as a guaranteed fallback
- Update f1.m3u with fresh URLs from https://cdn.f1live.dpdns.org/channels.json when streams go down

---

## Source
Stream URLs sourced from cdn.f1live.dpdns.org/channels.json — this repo does not host any video content.
