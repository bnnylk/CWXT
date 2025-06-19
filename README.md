# About
CWXT (Color Weather Translator) is a ambient interface that translates live weather data into color, offering a sensory alternative to traditional forecasting. It operates using the OpenWeatherMap API, fetching live weather data for a user-defined location. This data is parsed and categorized into simplified weather conditions, each mapped to a specific hue based on emotional associations with weather and color psychology.

In a world increasingly defined by the accumulation of ones and zeros, data is delivered in ways that are often overwhelmingly quantitative, optimized for precision but detached from anything personal. The CWXT goal is to provoke thought around alternative mode of engagement, modes that bypasses linguistic and numerical interpretation in favor of mood and feeling. While this sentiment applies broadly to how we engage with information, weather offers a uniquely fertile ground for exploration. It is a universally shared phenomenon, intimately tied to our moods, behaviors, and mental health.

# Hardware
- LILYGO ESP32 T-Display Module for Arduino  
  (TTGO LCD Wi-Fi BLE, CH9102F Chip)
  
  Purchase here - 
  https://www.alibaba.com/product-detail/p_1601377916687.html?mark=google_shopping&src=sem_ggl&field=UG&from=sem_ggl&cmpgn=22635874527&adgrp=177485315221&fditm=&tgt=pla-2412849993011&locintrst=&locphyscl=1023416&mtchtyp=&ntwrk=g&device=c&dvcmdl=&creative=756472634791&plcmnt=&plcmntcat=&aceid=&position=&gad_source=1&gad_campaignid=22635874527&gbraid=0AAAAAD8m77rCZDcMwJQW7Mt9voO65YnEj&gclid=CjwKCAjw6s7CBhACEiwAuHQckpe0o9m6kuqALRBNKNBJAGxG4iTpDd8sGFV0hwFLXQ-N0WrnInv11xoC3NIQAvD_BwE
  
- 3.7 LiPo Battery

# Weather to Color Mapping
| Weather Condition | Color            |
|-------------------|------------------|
| Clear             | Yellow           |
| Clouds (light)    | Slate Blue/Grey  |
| Overcast          | Deep Grey        |
| Rain              | Blue             |
| Drizzle           | Light Grey-Blue  |
| Thunderstorm      | Red              |
| Snow              | White            |
| Fog/Mist/etc.     | Beige            |


# Getting Started
1. Upload the sketch to your LILYGO ESP32 T-Display using the Arduino IDE.
2. Replace placeholder values in the code:
   - Your Wi-Fi name and password
   - Your OpenWeatherMap API key
   - Your target city and country code
3. Power the device with battery or USB-C and watch the weather appear as ambient color.
