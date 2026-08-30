# Adaptive Traction Hub Dashboard 🛞

## Overview

The **Adaptive Traction Hub Dashboard** is a vehicle-mounted dashboard interface designed for the **Smart Adaptive Traction-Hub** project.

The dashboard provides the driver with real-time visual information such as vehicle speed, tyre pressure, traction demand, wheel-slip condition, and surface condition. When excessive wheel slip is detected, the driver can choose to deploy the mechanical traction lugs for temporary recovery and improved grip.

## Project Concept

The Smart Adaptive Traction-Hub is a **low-speed traction-assistance concept** for selected:

* Heavy utility vehicles
* Emergency vehicles
* Hill-transport vehicles
* Off-road vehicles

During normal paved-road driving, the traction lugs remain retracted. When excessive wheel slip is detected on surfaces such as **mud, slush, loose soil, or compacted snow**, the driver can activate the traction-assist mechanism.

## Dashboard Features

### 🚗 Vehicle Speed

Displays the current vehicle speed in **km/h**.

### 🛞 Tyre Pressure

Displays individual tyre-pressure readings for:

* Front Left (FL)
* Front Right (FR)
* Rear Left (RL)
* Rear Right (RR)

### 📊 Traction Demand

A visual traction-demand bar indicates how much traction assistance is currently required.

### ⚠️ High Wheel Slip Alert

The dashboard displays an alert when excessive wheel slip is detected.

### ⚙️ Traction Lug Deployment

The driver can activate the traction system using the large:

**DEPLOY TRACTION LUGS**

button.

The dashboard then changes the system state and visually deploys the traction lugs.

### 🛞 3D Wheel Animation

The centre of the dashboard contains an animated wheel representing the traction-hub mechanism.

The wheel includes **four traction-lug deployment points** positioned around the wheel.

When the system is activated, the four lugs visually deploy from different sections of the wheel.

### 🌧️ Surface Condition

Displays the detected/selected terrain condition, such as:

**MUD / SLUSH**

### 📈 Traction Monitor

Displays the current wheel-slip ratio along with a visual slip graph.

## User Interface Flow

```text
Normal Driving
      ↓
Wheel Slip Detected
      ↓
HIGH WHEEL SLIP ALERT
      ↓
Driver Decision
   ↙          ↘
 NO          DEPLOY
 ↓             ↓
Continue     Traction
Driving      Lugs Deploy
                 ↓
          Improved Traction
```

## Technologies Used

* **HTML5** – Dashboard structure
* **CSS3** – Styling, animations and responsive layout
* **CSS Animations** – Wheel rotation and traction-lug deployment
* **SVG** – Traction monitoring graph

## Project Structure

The dashboard is provided as a single HTML file:

```text
adaptive-traction-hub-final-v2.html
```

The HTML file contains both the **HTML structure and CSS styling**, so no additional stylesheet is required.

## How to Run

1. Download the HTML file.
2. Open it using a modern web browser such as **Google Chrome, Microsoft Edge, or Firefox**.
3. The dashboard will load directly in the browser.
4. Use the **DEPLOY TRACTION LUGS** button to demonstrate the lug deployment animation.

## Demonstration

The dashboard can be used as a **UI prototype/demo** for the Adaptive Traction Hub project.

It demonstrates how a driver could:

1. Monitor vehicle speed.
2. Check tyre pressure.
3. Observe traction demand.
4. Receive a high wheel-slip warning.
5. Decide whether traction assistance is required.
6. Deploy the traction lugs.
7. Observe the four-point lug deployment on the wheel.

## Important Note

This dashboard is a **visual and functional prototype**. The displayed vehicle data, tyre pressures, traction demand, and wheel-slip values are simulated for demonstration purposes and are not connected to an actual vehicle sensor or actuator system.

## Future Improvements

Possible future development includes:

* Real wheel-speed sensor integration
* Real tyre-pressure monitoring
* CAN bus integration
* Automatic wheel-slip detection
* Real-time vehicle-speed data
* Hardware actuator control
* Terrain/surface detection
* Fault and safety monitoring
* Deployment confirmation sensors
* Data logging and trip history

## License

This project is intended for **educational, prototype, and demonstration purposes**.
