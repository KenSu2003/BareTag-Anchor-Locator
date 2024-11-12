# BareTag Anchor Locator

**BareTag Anchor Locator** is an iOS app designed to fetch precise GPS coordinates and share them over Bluetooth Low Energy (BLE). It’s primarily intended for construction sites to help locate tools and equipment accurately, minimizing loss and theft.

---

## Features

- **GPS Location Fetching**: Retrieves the device’s current GPS location with high accuracy.
- **Bluetooth Advertising**: Broadcasts location data over Bluetooth for nearby BLE-capable devices to detect.
- **Status Updates**: Displays the current status (e.g., connecting Bluetooth, fetching GPS, sending location) on the app UI for user feedback.

---

## Requirements

- **iOS 15.0 or later**
- **Xcode 14.0 or later**
- **Swift 5.0 or later**
- **Device with Bluetooth Low Energy (BLE) capability**

---

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/BareTag_Anchor_Locator.git
   cd BareTag_Anchor_Locator

2. Open in Xcode: 

   Open the project in Xcode by double-clicking on BareTag_Anchor_Locator.xcodeproj or BareTag_Anchor_Locator.xcworkspace (if using Swift Packages).
   
4. Configure App Permissions:
   
   Ensure Info.plist includes the necessary permissions for location and Bluetooth usage.

   - \<key>NSLocationWhenInUseUsageDescription\</key> : \<string>We need your location to track the device accurately.\</string>

   - \<key>NSLocationAlwaysUsageDescription\</key> : \<string>We need your location even when the app is in the background.\</string>

   - \<key>NSBluetoothAlwaysUsageDescription\</key> : \<string>Bluetooth is required to share your location with nearby devices.\</string>
   
6. Build and Run:
  
   - Select your device as the target in Xcode (BLE and GPS features require a physical device).
   - Press Cmd + R or click Run to build and deploy the app.
9. 
