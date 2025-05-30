# Weather Display — Color-Based Weather Visualizer for LILYGO T-Display

This project displays live weather data using a color-coded interface on a **LILYGO ESP32 T-Display Module**. It pulls current weather conditions from the **OpenWeatherMap API** and maps them to specific colors that represent different atmospheric states such as rain, snow, clear skies, or thunderstorms.

# Hardware
- LILYGO ESP32 T-Display Module for Arduino  
  (TTGO LCD Wi-Fi BLE, CH9102F Chip)

# Weather to Color Mapping
| Weather Condition | Color            |
|-------------------|------------------|
| Clear             | Yellow           |
| Clouds (light)    | Slate Blue/Grey  |
| Overcast          | Deep Grey        |
| Rain              | Blue             |
| Drizzle           | Light Grey-Blue  |
| Thunderstorm      | Purple           |
| Snow              | White            |
| Fog/Mist/etc.     | Beige            |


# Getting Started
1. Upload the sketch to your LILYGO ESP32 T-Display using the Arduino IDE.
2. Replace placeholder values in the code:
   - Your Wi-Fi name and password
   - Your OpenWeatherMap API key
   - Your target city and country code
3. Power the device and watch the weather appear as ambient color.

# License
MIT License — feel free to remix, reuse, or adapt with credit.
