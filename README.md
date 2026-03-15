# idol-light-sticks-config

Remote configuration for the [Idol Light Sticks](https://github.com/waadrarii/idol-light-sticks-app) app, served via GitHub Pages.

> **Note:** This repo must remain public so GitHub Pages can serve the JSON on the free plan.
> The content is non-sensitive — ad unit IDs are already embedded in the compiled app binary.

## Files

### `admob.json`

Controls AdMob ad unit IDs and interstitial frequency without requiring an app update.

| Key | Description |
|-----|-------------|
| `banner_id` | AdMob ad unit ID for banner ads |
| `interstitial_id` | AdMob ad unit ID for interstitial ads |
| `interstitial_every_n` | Show interstitial every N band changes |

**To update:** Edit `admob.json` directly on GitHub and commit. Changes take effect on next app launch after the 1-hour cache TTL expires.

### `config.json`

General app configuration served remotely to avoid requiring an app update.

| Key | Description |
|-----|-------------|
| `request_url` | URL opened when users tap "Request a Light Stick" — set to `null` or remove to hide the button |

**To update:** Edit `config.json` directly on GitHub and commit. Changes take effect on next app launch after the 1-hour cache TTL expires.

## URLs

```
https://waadrarii.github.io/idol-light-sticks-config/admob.json
https://waadrarii.github.io/idol-light-sticks-config/config.json
```
