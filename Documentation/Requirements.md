# Requirements

## Introduction and Context:

This requirements page details the development of an app that focus' on alerting the user to potentially forgotten bluetooth capable devices.  Emphasis has been placed on mobile devices that run Android and iOS software including phones and smartwatches as well as a Tile device.  These devices will notify the user via push notification if bluetooth has been broken.  

### 1. Users and their goals:
- **1.1:** User
    - **1.1.1:** Easily manage settings from within the app
    - **1.1.2:** Be alerted when a secondary bluetooth device breaks connection.
        -**1.1.2.1:** Have the secondary bluetooth device also send a push notification when bluetooth connection is broken.


### 2. Functional Requirements:
- **2.1:** Easily manage secondary bluetooth devices in the settings page of the primary device
    - **2.1.1:** Be able to add & remove a secondary bluetooth device from within a settings page within the app installed on the primary device.
- **2.2:** When a secondary bluetooth device breaks bluetooth connection, a push notification will be sent, if possible, to both the primary and secondary devices.
     - **2.2.1:** The notification will need to be able to be silenced or turned off.
- **2.3:** When a secondary bluetooth device reconnects to the primary device, push notifications need to confirm reconnectivity with each other.

### 3. Non-Functional Requirements:
- **3.1:** Weekly developer-client meetings.
- **3.2:** Toolset:
    - **3.2.1:** Xamarin.Forms
    - **3.2.2:** Dotnet Backend
    - **3.2.3:** GitHub.com
    - **3.2.4:** Git
    - **3.2.5:** Draw.io

### 4. Future Features:
- **4.1:** Implement use for other bluetooth devices other than phone such as headphones, rice cookers, televisions, etc.

### 5. Glossary:
- **5.1:** Primary Device: The device the user uses to track other bluetooth devices
- **5.2:** Secondary Device: Other devices being tracked by the primary device.