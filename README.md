# AR-Measure-App
Final Project for CS8395: AR Measure App

## Introduction
The AR Measure App is an augmented reality application exclusively for iOS that utilizes Apple's ARKit through Unity's AR Foundation to let users measure real-world objects with their iPhone.

## Features
- Measure distances in augmented reality.
- User-friendly interface for seamless interaction.
- Support for various measurement units.

## Prerequisites
- Unity Version: (Specify the version of Unity suitable for ARKit integration)
- Xcode with the latest iOS SDK
- iOS device with ARKit support

## Getting Started
These instructions will guide you through the setup process to get the AR Measure app running on your iOS device.

### Clone the Repository
Clone this repository to your local machine using your preferred Git client.

### Open the Project in Unity
Navigate to the Unity Hub, add the cloned project directory by clicking on the `Add` button, and then open the project.

### Configuring for iOS
1. Open the project in Unity.
2. Go to `File` → `Build Settings`, select `iOS` as the platform, and click `Switch Platform`.
3. With your iOS device connected to your computer, enable it as a trusted device.

### AR Support
Ensure ARKit XR Plugin is installed:

1. Go to `Window` → `Package Manager`.
2. Look for the ARKit XR Plugin and make sure it is added to the project.

### Build and Run
1. With your iOS device connected and Unity in iOS Build mode, go to `File` → `Build & Run`.
2. Unity will compile the app and prompt you to open Xcode.
3. In Xcode, sign the project with your Apple developer account and run it on your device.

### Permissions
The first time you run the application on your device, you'll be prompted to grant camera permissions.

## Usage
- Launch the app on your iOS device.
- Point your device's camera towards a flat surface to detect the plane.
- Tap on the screen to place anchor points and measure the distance between them.

## Troubleshooting
- Ensure the iOS device supports ARKit.
- Confirm that the device is running the latest version of iOS.
- Check Unity and Xcode for any compilation or build errors.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Ensure to update any tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
