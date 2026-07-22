# expo54-app

A native mobile app built on [Expo SDK 54](https://expo.dev) with
[expo-router](https://docs.expo.dev/router/introduction/) and TypeScript.

## Getting started

```bash
npm install
npx expo start
```

Then:

- Press `a` to open on an Android emulator, or `i` for the iOS simulator
- Or scan the QR code with the [Expo Go](https://expo.dev/go) app on your phone

## Project structure

- `app/_layout.tsx` — root stack navigator
- `app/index.tsx` — Home screen
- `app/about.tsx` — About screen

Add a new screen by creating a file in `app/` — the route is derived from the
file name (file-based routing).

## Native builds

To produce installable binaries, use [EAS Build](https://docs.expo.dev/build/introduction/):

```bash
npm install -g eas-cli
eas build --platform android   # or ios
```
