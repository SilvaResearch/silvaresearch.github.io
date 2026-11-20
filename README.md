# Canopy Gap
### Android Application for Forest Canopy-Gap Measurement

**Canopy Gap** is an Android application developed by **SilvaResearch** for field measurement of forest canopy-gap geometry and topographic characteristics using smartphone technology.

The application combines camera-based measurements, smartphone orientation sensors, and GPS positioning to help researchers and forestry students measure and document forest canopy gaps.

**Official Website:**  
https://silvaresearch.github.io/

---

## Application Overview

Canopy Gap is designed to support field measurements of forest canopy gaps from a fixed observation point near the center of a gap.

Using smartphone sensors and camera-based measurements, the application estimates the geometric characteristics of canopy gaps and records relevant topographic and geographic information.

It provides a practical tool for researchers working in forest ecology, forest structure, and canopy-gap studies.

## Main Features

- **Gap Area:** Estimation of forest canopy-gap area.
- **Gap Dimensions:** Measurement of maximum gap length and width.
- **Perimeter:** Calculation of canopy-gap perimeter.
- **Slope Measurement:** Recording directional ground slope using smartphone orientation sensors.
- **Aspect Measurement:** Estimation of slope aspect.
- **GPS Positioning:** Recording geographic coordinates.
- **Elevation:** Recording GPS-based elevation above sea level.
- **GPS Accuracy:** Recording horizontal positioning accuracy.
- **Multiple Measurement Modes:** Free, four-direction, and eight-direction measurement modes.
- **Direction Alignment:** Visual azimuth alignment guidance in four-direction and eight-direction modes.
- **3D Visualization:** Three-dimensional visualization of measured canopy-gap geometry.
- **Measurement Reports:** Automatic saving of measurement results.
- **Map Export:** Saving the three-dimensional measurement visualization.

## Device Requirements and Permissions

Canopy Gap requires an Android smartphone with the following components and permissions:

### Hardware Requirements

- A working camera.
- A working accelerometer.
- A working magnetic-field sensor (compass).

Both orientation sensors are essential for determining slope and azimuth.

Devices without either the accelerometer or magnetic-field sensor cannot perform the required orientation measurements.

### Application Permissions

- **Camera Permission:** Required to display the live camera preview.
- **Location Permission:** Required to obtain and record geographic information.

GPS/Location should be enabled when collecting geographic information and completing measurements.

**Important:** The application checks the availability of the required permissions, camera preview, and orientation sensors before enabling the Start button.

## Application Screenshots

### Canopy Gap Application Interface

![Canopy Gap Android Application](images/canopy-gap-app.png)

### Three-Dimensional Measurement Output

![Canopy Gap Measurement Output](images/gap-3d-output.png)

## Measurement Workflow

1. Stand at a fixed measurement point near the center of the forest canopy gap.
2. Select the preferred measurement mode.
3. Configure the measurement settings.
4. Measure the canopy-gap boundaries in the selected directions.
5. Follow the measurement positions displayed by the application.
6. Review the calculated geometric and topographic results.
7. Save the measurement report and, when required, the three-dimensional map.

## Measurement Modes

Canopy Gap provides three measurement modes:

### 4 Directions

Measures the canopy-gap boundary in four directions, using approximately 90° angular intervals.

### 8 Directions

Measures the canopy-gap boundary in eight directions, using approximately 45° angular intervals.

### Unlimited (Free Mode)

Allows users to record a flexible number of measurement directions.

At least three complete directions are required to calculate the canopy-gap geometry.

## Measurement Settings

The application provides additional settings for field measurements:

### Camera Height

The camera height is used to estimate the horizontal distance between the observation point and the canopy-gap boundary.

The actual camera height should be entered in meters and kept constant throughout the measurement.

### Flat Ground

When enabled, the application assumes that the terrain is approximately level and skips the Eye Level measurement.

Only the Bottom measurement is required for each direction.

When the terrain is sloping or noticeably uneven, Flat Ground should be disabled.

### Separate Azimuth

When enabled, an additional Azimuth measurement stage is performed for each direction.

This allows azimuth to be recorded while the phone is held upright and its viewing direction is horizontal.

## Download

The Canopy Gap Android application is available through the official website.

**[Download Canopy Gap](https://silvaresearch.github.io/files/CanopyGap-v1.00.apk)**

| Application Information | Details |
|---|---|
| Application | Canopy Gap |
| Version | 1.00 |
| Platform | Android |
| File Format | APK |
| File Size | 3.02 MB |
| Release Date | November 15, 2026 |
| Developer | SilvaResearch |

## Purchase & Activation

Canopy Gap requires a valid activation code.

### Important — Verify Your Device Before Ordering

**Before placing an order, install and open the Canopy Gap Android application on the phone you intend to use.**

Grant the required camera and location permissions, then wait until the **Start** button becomes enabled.

The Start button is enabled only after the application confirms that:

- Camera permission has been granted.
- Location permission has been granted.
- The accelerometer is available.
- The magnetic-field (compass) sensor is available.
- The camera preview has initialized successfully.

This preliminary check helps confirm that your smartphone meets the application's basic device requirements.

**Tap Start only after it becomes enabled.**

On the in-app activation screen, use the purchase link to open the official Purchase & Activation page.

**Please place your order from inside the Android application only after completing this device compatibility check.**

### Purchase Procedure

1. Download and install Canopy Gap on your Android device.
2. Open the application and grant the required camera and location permissions.
3. Wait until the Start button becomes enabled.
4. Tap Start to open the in-app activation screen.
5. Select the purchase link to open the official Purchase & Activation page.
6. Follow the Litecoin payment instructions.
7. Send the required payment.
8. Submit your accessible email address and transaction ID (TXID).
9. Your payment will be checked manually.
10. After payment verification, your 24-digit activation code will be sent to your email address.
11. Return to the application and enter your activation code in the activation field.

### Payment Information

| Item | Details |
|---|---|
| Payment Method | Litecoin (LTC) |
| Required Payment | 0.05 LTC |
| Displayed Price | $2.00 USD |
| Verification | Manual |
| Activation Code | 24 digits |
| Delivery Method | Email |

**[Official Purchase & Activation Page](https://silvaresearch.github.io/purchase.html)**

**Email Reminder:** Please provide an email address that you can access. Your activation code will be sent to the email address submitted with your payment request. Incorrect email addresses may prevent you from receiving your activation code.

## Measurement Results and File Storage

The application calculates and records the following characteristics:

### Gap Geometry

- Gap area (m²).
- Maximum gap length (m).
- Maximum gap width (m).
- Gap perimeter (m).

### Slope Characteristics

- Mean absolute directional S1 slope (%).
- Best-fit plane slope (%).
- Slope aspect (°).

### Geographic Information

- Longitude.
- Latitude.
- Elevation above sea level.
- Horizontal GPS accuracy.

The application also provides a three-dimensional visualization of the measured area.

### Output Files

The application generates two types of output:

- **Measurement Report (.txt):** Saved automatically after a measurement is completed.
- **3D Map Screenshot (.png):** Saved when the Save Map option is selected.

Both files are stored in:

`Internal storage/Android/data/com.forestry.cgap/files/CanopyGap/`

Android may restrict access to this directory through some file managers.

## Magnetic Azimuth

The azimuth readings provided by the application are referenced to **magnetic north**.

They are obtained from the smartphone's magnetic-field sensor and are not corrected for magnetic declination.

Therefore, they should not be interpreted as true-north or geographic-north azimuths.

For more reliable compass readings, keep the phone away from vehicles, large metal objects, and other sources of magnetic interference.

## Official Website

For application information, screenshots, downloads, and activation:

**https://silvaresearch.github.io/**

## Developer

**SilvaResearch**

*Forest is Life.*

## Copyright & License

Copyright © 2026 SilvaResearch. All rights reserved.

Canopy Gap, including its software, design, documentation, and associated materials, is the property of SilvaResearch.

No part of this application may be reproduced, redistributed, modified, or commercially exploited without prior written permission from the copyright holder, except where expressly permitted by applicable law.

This repository provides information about the Canopy Gap application. Access to this repository does not grant permission to copy, modify, or redistribute the application.

---

**Canopy Gap – Forest Canopy-Gap Measurement App**  
**Developed by SilvaResearch**
