
# Flutter Wetter App
Eine Flutter App zum Anzeigen des aktuellen Wetterstatus.
Diese App wurde von LonelyCpp entwickelt und von mir ins Deutsche übersetzt.

![android](./screenshots/android.png?raw=true 'android')
![ios](./screenshots/ios.gif?raw=true 'ios')
![ios](./screenshots/ios_chart.gif?raw=true 'ios')

## Getting Started

Create a file called `api_keys.dart` in `lib/src/api/`

Make a class called `ApiKey` with your openweathermaps API key in it. Get it [here](https://openweathermap.org/api)

eg:
  ```
  class ApiKey {
    static const OPEN_WEATHER_MAP = 'your_key';
  }
  ```

