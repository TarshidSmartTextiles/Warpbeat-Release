# Warpbeat-Release: Elevate Your Experience!


<img src="https://github.com/TarshidSmartTextiles/Warpbeat-Release/blob/main/warpbeaticon.svg" alt="Warpbeat Icon" width="200"/>

### **Key Features**
- **Bluetooth Integration**: Effortlessly connect and manage your Bluetooth-enabled devices.
- **Real-Time Data Visualization**: Dive into interactive charts for comprehensive data tracking and analysis.
- **Customizable UI Components**: Enjoy a modern interface with Bottom Sheets, Chips, and Expanders.
- **Calendar Integration**: Organize your schedules and events with ease.
- **Notifications**: Stay informed with real-time alerts and reminders.
- **Location Tracking**: Utilize advanced GPS tracking for precise distance and route monitoring.

#### **Getting Started**

**Prerequisites**
- Android 5+

**Installation**
Head to the release to download the latest version.
# **Permisions**

**Warpbeat Permissions Explained**

To give you the best fitness tracking experience, Warpbeat needs access to certain features and data on your device. We only ask for permissions essential for the app to work correctly. Here’s what we need and why:

**1. Bluetooth (Essential for Sensors)**

*   **Permissions:** `Nearby devices` (includes Scanning & Connecting)
*   **Why:** This is crucial for finding and connecting to your Bluetooth Low Energy (BLE) heart rate monitors, foot pods, or other fitness sensors. Without this, the app can't get real-time data like your heart rate during workouts.
    *   *(Technical Note: On newer Android versions, this requires separate `BLUETOOTH_SCAN` and `BLUETOOTH_CONNECT` permissions. Older versions might just ask for general Bluetooth access.)*

**2. Location (Essential for GPS Tracking & Sensor Discovery)**

*   **Permissions:** `Precise location` (GPS), potentially `Approximate location`
*   **Why:**
    *   **Workout Routes:** To accurately track your distance, speed, and map your route for activities like running, cycling, or walking using GPS.
    *   **Finding Bluetooth Sensors:** Android requires Location access to scan for nearby Bluetooth Low Energy devices. **Even if you don't need a GPS map for your workout type, this permission is often necessary just to find your sensors.**
*   **Recommendation:** Choose "**Allow only while using the app**" for the best balance of functionality and privacy.

**3. Foreground Service & Background Operation (Essential for Continuous Tracking)**

*   **Permissions:** `Physical activity` / `Health data`, `Connected devices`, `Location` (for background use notifications)
*   **Why:** When you start a workout and then switch apps or turn off your screen, Warpbeat needs to keep running in the background to continuously record your sensor data (heart rate, etc.) and location (if applicable). The "Foreground Service" permission allows this, usually showing a persistent notification so you know it's active and Android doesn't shut it down prematurely. The specific types (`connectedDevice`, `health`, `location`) tell Android exactly *why* the service is running.

**4. Body Sensors (Optional - Depending on App Features)**

*   **Permissions:** `Body sensors` / `Health data`
*   **Why:** This permission is for accessing sensors *built directly into your phone or smartwatch* (like a built-in heart rate monitor on a watch). If Warpbeat only connects to *external* Bluetooth sensors, you might not need to grant this specific permission unless the app also utilizes on-device sensors.
*   **Background Sensors:** The `BODY_SENSORS_BACKGROUND` permission would be needed if the app accesses these *on-device* sensors while running in the background.

**5. Network Access**

*   **Permissions:** `Network access` / `Internet`
*   **Why:** Allows Warpbeat to potentially sync your workout data with an online account, check for updates, or download other necessary information. This is usually granted automatically.

**How Permissions Are Requested:**

Android will ask for your permission via pop-up dialogs the first time Warpbeat needs to use a specific feature (like starting Bluetooth scanning or accessing location).

**Managing Your Permissions:**

You can review and change the permissions granted to Warpbeat at any time in your device's settings:

*   Go to `Settings` > `Apps` > `Warpbeat` > `Permissions`.

**Our Commitment:**

We only request permissions that are necessary for Warpbeat's features to function correctly. We value your privacy and data security.



#### **Support**

For support or inquiries, reach out to your designated contact or use the in-app support feature.

---




## Roadmap

| **Milestone** | **Description**                                                | **Status**         | **Target Completion** |
|---------------|----------------------------------------------------------------|--------------------|-----------------------|
| **v1.0.0**    | Initial release with core features like Bluetooth integration and charts. | 🚀 Released       | **April 25, 2025**    |
| **v1.1.0**    | Add advanced calendar features and notification system.        | 🚧 In Progress     | **June 30, 2025**     |
| **v1.2.0**    | UI upgrade to align with Fluent UI and implement location tracking. | ⏳ Planned         | **October 1, 2025**   |
| **v2.0.0**    | Major release with AI-powered insights, intelligent analyses of metrics, and more health parameters. | ⏳ Planned         | **February 15, 2026** |
| **v2.1.0**    | Introduce more sharing options and provide access to both analyzed and raw data. | ⏳ Planned         | **June 1, 2026**      |
| **v2.2.0**    | Launch iOS version with feature parity to the existing platform. | ⏳ Planned         | **September 30, 2026**|


---

### **Privacy and Security**

WarpBeat is committed to safeguarding your data. All personal information are saved locally and accessible only to the user.

---


