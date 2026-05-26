# Vietnam Wayfarer — Translations

Public mirror of article translations for [vietnamwayfarer.com](https://vietnamwayfarer.com).

Served via [JSDelivr CDN](https://www.jsdelivr.com) so the main application bundle doesn't have to ship ~239 MB of locale JSON to every serverless function.

## Layout

- `translations/<slug>__<locale>.json` — single article translation
- `translations-index.json` — flat list of every `{ slug, locale }` pair currently published

## CDN URL pattern

```
https://cdn.jsdelivr.net/gh/nhnam1097/vietnamwayfarer-translations@main/translations/<slug>__<locale>.json
https://cdn.jsdelivr.net/gh/nhnam1097/vietnamwayfarer-translations@main/translations-index.json
```

JSDelivr cache TTL is ~12 hours; force a refresh with `@main` → specific commit SHA, or hit the purge endpoint manually.

## Locales

`en` (default), `vi`, `ko`, `zh`, `ja`, `fr`, `de`, `es`, `ru`, `it`, `pt`, `id`, `hi`.

## License

Article content rights are held by Vietnam Wayfarer. Translations are derivative works of the English originals. See [vietnamwayfarer.com/terms](https://vietnamwayfarer.com/terms).
