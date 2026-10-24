# Smart Vehicle Dead Reckoning Simulator

## Project overview
This is a beginner-friendly web prototype that demonstrates map-based vehicle position estimation using dead reckoning.

### Features
- Interactive OpenStreetMap map
- Simulated vehicle movement based on speed and heading
- Orange dashed line for dead-reckoning estimate
- Green line for simulated reference route
- Adjustable sensor/heading error to demonstrate drift
- Optional GPS correction every 10 simulated seconds
- Elapsed time, distance, and position-error metrics
- Click the map to choose a start point
- Optional browser geolocation to set the initial point

## How to run
1. Extract the ZIP file.
2. Open `index.html` in a modern browser while connected to the internet.
3. Start the simulation.
4. Turn off GPS correction and increase sensor error to observe drift.
5. Turn GPS correction back on to see the estimate move closer to the reference path.

Map tiles and Leaflet are loaded from online CDNs, so an internet connection is required.

## Technology
- HTML
- CSS
- JavaScript
- Leaflet.js
- OpenStreetMap

## Important limitations
This is an educational simulation, not a real vehicle navigation system. The vehicle route, sensor error, and GPS correction are simulated. Real dead reckoning typically uses calibrated inertial sensors, wheel odometry, and sensor fusion, and errors accumulate over time.

## Resume description (use only after you have tested and understood it)
**Map-Based Smart Vehicle Position Estimation Using Dead Reckoning**
- Developed an interactive web prototype to estimate vehicle position from speed and heading when GPS is unavailable.
- Visualized estimated and reference paths on an OpenStreetMap interface and measured position error.
- Simulated sensor drift and periodic GPS correction to demonstrate the limitations of dead-reckoning navigation.

## Suggested next improvements
- Add CSV logging and export
- Add a route replay mode
- Use real GPS traces for testing
- Explore sensor fusion (for example, a Kalman filter) after understanding the basics
