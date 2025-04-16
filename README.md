# 🌍 Eratosthenes 2.5 (2025)
---

##  Objective

To replicate and modernize Eratosthenes' historical experiment by measuring the length of a shadow cast by a vertical rod in different parts of the world at the same solar event, and collect high-precision data to evaluate Earth's curvature.



##  Materials Required

Each participant must have:

- **Metal rod (exactly 100 cm)**  
- **Bubble level** (to ensure the rod is perfectly vertical)  
- **Tape measure or ruler** (with millimeter precision)  
- **Smartphone or GPS device** to collect:
  - Latitude
  - Longitude
  - Altitude above sea level  
- **Weather app or device** to record:
  - Temperature (°C)
  - Humidity (%)
  - Atmospheric pressure (hPa)
- **Clock synchronized to UTC**
- **Camera or phone** to take pictures of the setup and the shadow

---

##  Suggested Apps

To make accurate measurements and calculations:

-  **GPS Coordinates** → [GPS Coordinates App (Android/iOS)]  
-  **Solar Noon Time** → [SunCalc.net](https://www.suncalc.org/) or [TimeAndDate.com](https://www.timeanddate.com/sun/)
-  **Level Tool** → [Bubble Level App (Android/iOS)]
-  **Weather App** → AccuWeather, Weather.com, or your local meteorological source



##  Instructions for Measurement

1. **Choose a day** with clear skies around **solar noon** in your area.
2. **Place the metal rod vertically** on a flat, level surface using a bubble level.
3. Wait for the **exact moment of solar noon**.
4. Measure the **length of the shadow** (from the base of the rod to the tip of the shadow).
5. Record the following:
   - **Date** and **UTC time**
   - **City/location**
   - **Latitude & Longitude** (in decimal format)
   - **Altitude (m above sea level)**
   - **Rod length (in cm)**
   - **Shadow length (in cm)**
   - **Shadow direction** (azimuth, using compass app)
   - **Temperature, Humidity, and Pressure**
6. **Take pictures** of your setup and the shadow
7. Enter your data in the shared CSV file:  
   `/data/measurements.csv`



## Notes & Common Pitfalls

- The rod must be **perfectly vertical**. Use a **bubble level** to avoid errors.
- The surface should be **flat** and not tilted in any direction.
- Be precise with your **shadow measurement**: measure at the moment when the shadow is shortest (solar noon).
- Use **UTC time** to ensure consistency across all locations.
- Measure in **centimeters and meters**, not inches or feet.
- Record all GPS data with at least **5 decimal points** for precision.
- Avoid cloudy or hazy days, as it can **blur the shadow** or shift its position.
- Do not round measurements too early. **Use exact values** during recording.



## Where to Upload Data

- Submit your measurements by editing `measurements.csv` located in the `/data/` folder.
- Upload your photos inside the `/docs/images/` folder.
- Optionally, add your name and city as contributors in the `paper.md`.


