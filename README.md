# Ayran Studio website

Zero-dependency static website for Ayran Studio and Sip&Pop. It contains English, Turkish, and Spanish landing pages and game-specific privacy policies. Sip&Pop uses `/sip-and-pop/privacy/`, with localized equivalents under `/tr/` and `/es/`.

## Preview

```bash
python3 -m http.server 4173 --directory dist
```

Then open `http://127.0.0.1:4173`.

## Before publishing

The active contact routes are `privacy@ayranstudio.com`, `contact@ayranstudio.com`, and `iletisim@ayranstudio.com`. Before publishing, verify that the Google Play Data safety form matches the current app and advertising SDK configuration.
