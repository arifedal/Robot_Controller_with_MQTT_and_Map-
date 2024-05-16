
# Life Saving Robot Remote Control Application

This is a Flutter/Dart application for remotely controlling a life-saving robot. The application allows users to log in, retrieve real-time data from the robot, view its live location on a map, and control its movements using on-screen buttons.

## Features

- **Login Page**: Users can log in securely to access the robot control interface.
- **Real-time Data Retrieval**: Instant retrieval of data from the robot and display to the user.
- **Live Location Tracking**: View and track the live location of the robot on the map.
- **Remote Control**: Control the robot's movements using on-screen buttons to turn left, right, forward, and backward.

## Dependencies

The following dependencies were used in this project:

- **flutter_polyline_point**: For working with polylines on the map.
- **google_maps_flutter**: For integrating Google Maps into the application.
- **location**: For retrieving device location data.
- **mqtt_client**: For establishing a remote connection with the robot using MQTT protocol.
- **provider**: For state management within the application.
- **sqflite**: For local database storage.
- **path_provider**: For accessing device directories.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `flutter pub get` to install the dependencies.
4. Ensure you have a Google Maps API key and replace `YOUR_API_KEY` in `android/app/src/main/AndroidManifest.xml` and `ios/Runner/AppDelegate.swift` with your API key.
5. Run the project using `flutter run`.

## Usage

To use the application:

1. Launch the application on your device.
2. Log in with your credentials.
3. View real-time data from the robot.
4. Track its live location on the map.
5. Control the robot's movements using the on-screen buttons.


## Contributors

- [Arife Dal]([GitHub profile](https://github.com/arifedal/))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## NOTE:For privacy reasons, codes or screenshots are added as private. The project exists as private.



