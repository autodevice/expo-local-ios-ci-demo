# ExpoLocalIOSDemo

Expo iOS simulator app built via **EAS Build `--local`** and uploaded to [AutoDevice](https://autodevice.io).

## Build Method

- **Platform**: iOS (simulator .app)
- **Build**: EAS Build `--local` — builds run on the CI runner itself
- **CI Runner**: `macos-15`
- **Profile**: `simulator` (produces iOS simulator build)
- **Requirements**: macOS + Xcode (available on `macos-15`)

## Required Secrets

| Secret | Description |
|--------|-------------|
| `EXPO_TOKEN` | Expo access token for EAS Build authentication |
| `AUTODEVICE_API_KEY` | AutoDevice API key for uploading builds |

## Local Development

```bash
npm install
npx expo start
```
