# StickerSmash App

StickerSmash is a React Native application that allows users to select photos, add emoji stickers, and save their creations. This app supports both mobile devices (iOS and Android) and web platforms.

## Features

- Select photos from device gallery
- Add emoji stickers to photos
- Resize stickers with double-tap gesture
- Drag and position stickers freely
- Save edited images to device gallery (on mobile)
- Download edited images (on web)

## Technologies Used

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Router](https://docs.expo.dev/router/introduction/)
- [React Native Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/)
- [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/)
- [Expo Image Picker](https://docs.expo.dev/versions/latest/sdk/imagepicker/)
- [Expo Media Library](https://docs.expo.dev/versions/latest/sdk/media-library/)
- [react-native-view-shot](https://github.com/gre/react-native-view-shot)
- [dom-to-image](https://github.com/tsayen/dom-to-image) (for web)

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Expo CLI

### Installation

1. Clone this repository:
```
git clone https://github.com/SuzanZeytcioglu/StickerSmash.git
cd sticker-smash
```

2. Install dependencies:
```
npm install
```
or
```
yarn install
```

3. Start the development server:
```
npx expo start
```

## Usage

1. Launch the app on your device or emulator
2. Tap "Choose a photo" to select an image from your gallery
3. Tap "Use this photo" to proceed to the editing screen
4. Use the circular button to add emoji stickers
5. Drag stickers to position them on the image
6. Double-tap on a sticker to resize it
7. Tap "Save" to save your creation to your device
8. Tap "Reset" to start over


## Acknowledgments

- This project was built following the [Expo tutorial](https://docs.expo.dev/tutorial/introduction/).
