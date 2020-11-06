# Requirements

## Introduction and Context:

This requirements page details the development of an app that focuses on alerting the user to potentially forgotten bluetooth capable devices.  Emphasis has been placed on mobile devices that run Android and iOS software including phones and smartwatches as well as a Tile device.  These devices will notify the user via push notification if bluetooth has been broken.  

### 1. Users and their goals:
- **1.1:** User
    - **1.1.1:** Easily manage settings from within the app
    - **1.1.2:** Be alerted when a secondary bluetooth device breaks connection.
        - **1.1.2.1:** Have the secondary bluetooth device also send a push notification when bluetooth connection is broken.

### 2. Functional Requirements:
- **2.1:** Easily manage secondary bluetooth devices in the settings page of the primary device
    - **2.1.1:** Be able to add & remove a secondary bluetooth device from within a settings page within the app installed on the primary device.
    - **2.1.2:** Display secondary bluetooth device information such as the bluetooth address and other meta data
    - **2.1.3:** Allow user to edit secondary bluetooth 'nicknames' such as 'Keys', 'John's Smartwatch', etc.
    - **2.1.4:** Allow user to organize secondary bluetooth devices on the homescreen acccording to user preference.
        - **2.1.4.1:** Be able to organize secondary bluetooth devices according to alphabetical order.
        - **2.1.4.2:** Be able to organize secondary bluetooth devices according to the order that they were added.
        - **2.1.4.3:** Be able to organize secondary bluetooth devices according to a user set priority number.
    - **2.1.5:** Allow user to set a notification setting.
        - **2.1.5.1:** Be able to set notification setting to an alarm that must be silenced.
        - **2.1.5.2:** Be able to set notification setting to a notification that alerts once.
        - **2.1.5.3:** Be able to set notification setting to silent, only showing changes within the app.
- **2.2:** When a secondary bluetooth device breaks bluetooth connection, a push notification will be sent, if possible, to both the primary and secondary devices.
     - **2.2.1:** The notification will need to be able to be silenced or turned off.
- **2.3:** When a secondary bluetooth device reconnects to the primary device, push notifications need to confirm reconnectivity with each other.
- **2.4:** If a user has no connected devices, a special homescreen will help them set up a secondary bluetooth device.
- **2.5:** If a user has one or more secondary bluetooth devices, the normal homescreen will appear showing a summary of their devices.

### 3. Non-Functional Requirements:
- **3.1:** Weekly developer-client meetings.
- **3.2:** Toolset:
    - **3.2.1:** [Xamarin.Forms](https://dotnet.microsoft.com/apps/xamarin/xamarin-forms)
    - **3.2.3:** [GitHub](https://github.com/Septimis)
    - **3.2.4:** [Git](https://git-scm.com/)
    - **3.2.5:** [draw.io](https://app.diagrams.net/)

### 4. Future Features:
- **4.1:** Implement use for other bluetooth devices other than phone such as headphones, rice cookers, televisions, etc.
- **4.2:** Implement a log that shows when different bluetooth devices have connected and disconnected.
- **4.3:** Implement a GIF tutorial on first time set up
- **4.4:** Implement a signal strength meter on the home page.
    - **4.4.1** Be able to adjust when a bluetooth device goes out of range based on signal strength.  
    - **4.4.2** Allow User to 'train' their devices signal strength.
- **4.5:** Implement a GPS location to be saved when a secondary bluetooth device goes out of range.

### 5. Glossary:
- **5.1:** *Primary Device*: The device the user uses to track other bluetooth devices (e.g. Phone or Smartwatch)
- **5.2:** *Secondary Device*: Other devices being tracked by the primary device. (e.g. Bluetooth Tile, Phone, Smartwatch)