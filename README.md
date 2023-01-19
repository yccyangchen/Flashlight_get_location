# Flashlight_get_location
## Introduction:
This app is a flashlight application with location API provided by google play service which can request the last known location of the user's device.

**MainActivity.java:**
Handling the toggle button widget to toggle ON or OFF inside this file and get the last known location.

**activity_main.xml:**
This layout contains a simple TextView, View, and one ToggleButton to toggle the Flashlight unit.
<!-- The following output UI is produced: -->
<!-- ![Flashlight](https://ibb.co/v48kvKQ) -->

This application needs to be tested under a physical android device.

**What can be improved:**
This app only makes a single request for the location of a device using the getLastLocation() method in the fused location provider. Extra functions such as get device id, get camera access, get audio permission can be added.
