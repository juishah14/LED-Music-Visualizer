# SE 101 Project- LED Music Visualizer + App

Codebase for the LED Music Visualizer project, consisting of the Arduino code and the Flutter app. The LED Strip is connected to the Arduino Uno board and the signal transmission between the board and the app is handled by the Bluetooth module. The Bluetooth-connected app provides an interface for the user to select from 3 presets and 12 colours for the LED strip to display. The reactive preset allows for the user to select from 7 audio frequency bands for the LED strip to react to based on music connected via an aux cord to the Arduino Uno.

## Main Hardware Components

- Arduino Uno
- Sparkfun Spectrum Shield
- Individually Adressable LED Strip
- Bluetooth Module

## Main Software Components

- .ino Arduino code
- Cross-platform Flutter controller app using the flutter_blue plugin (https://pub.dev/packages/flutter_blue)

## App Functionalities:

- Change the brightness of the led strip
- Change the pattern of the light
- Change the frequencies of which the led strip responds to
- Change the colour of the light

<img src="screenshots/appMainPage.png" width="400">

## Contributors:

Uzair Ahmad, Dimitar Atanassov, Hanan Au, Jui Shah, Ximing Yang
