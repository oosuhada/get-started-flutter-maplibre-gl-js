# Get started with Flutter and MapLibre GL JS

A quick way to start a mobile native map application with MapLibre GL JS using Flutter.

This simple mobile fullscreen map application is an example of how to use MapTiler maps together with Flutter and MapLibre GL JS for your native app.

We have made this app using the [VS Code Flutter extension](https://docs.flutter.dev/get-started/editor?tab=vscode) and the plugin
[flutter-maplibre-gl](https://github.com/maplibre/flutter-maplibre-gl/tree/main).

## Installation and setting up

1. [Install Flutter](https://docs.flutter.dev/get-started/install)

2. Clone the [Get started with Flutter and MapLibre GL JS](https://github.com/maptiler/get-started-flutter-maplibre-gl-js) repo
  ```sh
    git clone https://github.com/maptiler/get-started-flutter-maplibre-gl-js.git my-flutter-map
  ```

3. Navigate to the newly created project folder **my-flutter-map**
  ```sh
    cd my-flutter-map
  ```

4. Install dependencies
  ```sh
    flutter pub get
  ```

5. :warning: Open the lib/map.dart file and replace **YOUR_MAPTILER_API_KEY_HERE** with your actual [MapTiler API key](https://cloud.maptiler.com/account/keys/).

  :information_source: If you don't have an API KEY you can create it for **FREE** at https://www.maptiler.com/cloud/

6. Build your project
  ```sh
    flutter run
  ```

7. You will find your app on your virtual device (Emulator) or physical device.

## Resources

Here are a few resources to get you started if this is your first Flutter project:

- [Install Flutter](https://docs.flutter.dev/get-started/install)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

For help with [Flutter MapLibre](https://github.com/maplibre/flutter-maplibre-gl/) view the online documentation.

## Architecture & Topics / 아키텍처 및 주제

**Architecture / 아키텍처**<br>
[`platform-channel`](https://github.com/topics/platform-channel) · [`native-bridge`](https://github.com/topics/native-bridge) · [`plugin-architecture`](https://github.com/topics/plugin-architecture) · [`declarative-ui`](https://github.com/topics/declarative-ui) · [`client-side-rendering`](https://github.com/topics/client-side-rendering) · [`map-rendering-pipeline`](https://github.com/topics/map-rendering-pipeline) · [`adapter-pattern`](https://github.com/topics/adapter-pattern)

**Core technologies / 핵심 기술**<br>
[`maplibre`](https://github.com/topics/maplibre) · [`maptiler`](https://github.com/topics/maptiler)

**Project context / 프로젝트 맥락**<br>
[`cross-platform`](https://github.com/topics/cross-platform) · [`flutter-development`](https://github.com/topics/flutter-development) · [`flutter-map`](https://github.com/topics/flutter-map) · [`geolocation`](https://github.com/topics/geolocation) · [`geospatial`](https://github.com/topics/geospatial) · [`map`](https://github.com/topics/map) · [`map-sdk`](https://github.com/topics/map-sdk) · [`mapping`](https://github.com/topics/mapping) · [`maps`](https://github.com/topics/maps) · [`mobile-app`](https://github.com/topics/mobile-app) · [`openstreetmap`](https://github.com/topics/openstreetmap)

**Implementation stack / 구현 스택**<br>
[`dart`](https://github.com/topics/dart) · [`flutter`](https://github.com/topics/flutter)
