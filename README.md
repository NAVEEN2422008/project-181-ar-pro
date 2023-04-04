# c181

A React Native (Expo) face-detection app using the live camera.

## Features
- Requests camera permission via `expo-permissions`
- Live camera feed from `expo-camera`
- Real-time face detection with `expo-face-detector`
- Overlays detected-face data on the screen ("Look Me" UI)
- Responsive styling for iOS and Android safe areas

## Tech Stack
- Expo SDK 45, React Native 0.68, React 17
- `expo-camera`, `expo-permissions`, `expo-face-detector`, `react-native-responsive-fontsize`

## Project Structure
```
App.js            # entry point — renders Main screen
screens/Main.js   # camera + face detection logic and UI
app.json          # expo config (name C-181)
package.json      # dependencies
assets/           # icons, splash
```

## Installation
```
npm install
```

## Usage
```
npm start          # then scan QR with Expo Go, or run android/ios
```
Grant camera access on the device; faces in view are detected and reported live.