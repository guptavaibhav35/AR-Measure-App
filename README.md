# AR-Measure-App
Final Project for CS8395: AR Measure App

## Introduction
AR Measure App is an augmented reality application for Android that leverages Unity's AR Foundation to let users measure real-world objects using their smartphones.

## Features
- Measure distances with AR.
- Intuitive UI for ease of use.
- Multiple measurement units support.

## Prerequisites
- Unity Version: (Specify the Unity version)
- Android SDK & NDK (Installed via Unity or Android Studio)
- ARCore Supported Android Device

## Getting Started
These instructions will guide you through the setup process to get the AR Measure app running on your Android device.

### Clone the Repository
To get started, clone this repo to your local machine using your favorite Git client.

### Open the Project in Unity
Open Unity Hub and add the cloned project directory by clicking on the `Add` button, then navigate to the root of the cloned repo.

### Configuring for Android
1. Open the project in Unity.
2. Go to `File` → `Build Settings`, select `Android` and click `Switch Platform`.
3. Connect your ARCore supported Android device to your computer.
4. Enable `Developer Mode` and `USB Debugging` on your Android device.

### AR Support
Ensure AR Foundation and ARCore XR Plugin are installed:

1. Go to `Window` → `Package Manager`.
2. Look for AR Foundation and ARCore XR Plugin and ensure they are added to the project.

### Build and Run
1. With your Android device connected and Unity in Android Build mode, go to `File` → `Build & Run`.
2. Unity will compile the app and install it directly on your device.

### Permissions
The first time you run the application on a device, you may be prompted to grant camera permissions.

## Usage
- Launch the app on your Android device.
- Point your device's camera towards a flat surface.
- Tap on the screen to place starting and end points to measure the distance.

## Troubleshooting
- Ensure the device is compatible with ARCore.
- Make sure the latest version of ARCore is installed on the device.
- Check for any compilation errors in Unity's Console window.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
