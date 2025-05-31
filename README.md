# About
CWXTR is a ambient interface that translates live weather data into color, offering a sensory alternative to traditional forecasting. It operates using the OpenWeatherMap API, fetching live weather data for a user-defined location. This data is parsed and categorized into simplified weather conditions, each mapped to a specific hue based on emotional associations with weather and color psychology.

In a world increasingly defined by the accumulation of ones and zeros, data is delivered in ways that are often overwhelmingly quantitative, optimized for precision but detached from anything personal. CWXTR goal is to provoke thought around alternative mode of engagement, modes that bypasses linguistic and numerical interpretation in favor of mood and feeling. While this sentiment applies broadly to how we engage with information, weather offers a uniquely fertile ground for exploration. It is a universally shared phenomenon, intimately tied to our moods, behaviors, and mental health.

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
