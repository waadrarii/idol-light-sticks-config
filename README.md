# idol-light-sticks-config

Remote configuration for the [Idol Light Sticks](https://github.com/hamzaboularbah/idol-light-sticks-app) app, served via GitHub Pages.

## Files

### `admob.json`

Controls AdMob ad unit IDs and interstitial frequency without requiring an app update.

| Key | Description |
|-----|-------------|
| `banner_id` | AdMob ad unit ID for banner ads |
| `interstitial_id` | AdMob ad unit ID for interstitial ads |
| `interstitial_every_n` | Show interstitial every N band changes |

**To update:** Edit `admob.json` directly on GitHub and commit. Changes take effect on next app launch after the 1-hour cache TTL expires.

## URL

```
https://hamzaboularbah.github.io/idol-light-sticks-config/admob.json
```
