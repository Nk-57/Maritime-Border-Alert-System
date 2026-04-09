# Maritime Border Alert System for Fishermen Safety

## Overview

This project is an embedded safety system designed to alert fishermen when they approach restricted maritime borders. It uses GPS-based geofencing to detect boundary crossing and generate alerts.

## Problem Statement

Fishermen sometimes unknowingly cross maritime borders due to lack of awareness, which can lead to legal consequences and safety risks.

## Proposed Solution

This system continuously tracks the boat's GPS location and compares it with predefined maritime boundary coordinates. When the boat approaches or crosses the boundary, a buzzer alert is triggered to warn the fishermen.

## Components Used

* ESP32 Microcontroller
* GPS Module
* Buzzer
* Power Supply

## Working Principle

1. GPS module collects real-time location data.
2. ESP32 reads latitude and longitude values.
3. Coordinates are compared with predefined border limits.
4. If the boundary is crossed:

   * Buzzer alert is activated
   * Location data is logged to cloud (optional)

## Features

* GPS-based geofencing
* Real-time boundary detection
* Audio alert using buzzer
* Optional cloud monitoring

## Applications

* Maritime safety
* Fishermen navigation support
* Border monitoring systems

## Future Improvements

* Add GSM alert to send SMS notifications
* Add display to show distance from border
* Improve accuracy using multiple GPS corrections
