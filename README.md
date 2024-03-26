# flightinfomock
This is used to share the javascript to simulate the flights information with Logic App on Azure. This script will be invoked by Recurrence to produce the content which will be sent to Event Hub or Eventstream.

The whole steps in Logic App are:
- Recurrence
- Execute JavaScript Code (copy the script content to this step)
- Send Event (Event Hub connector In-App)

![flightinfomock flow](https://github.com/xujxu/flightinfomock/assets/68268054/df818630-0cb7-443f-84c0-bc8bea8e6ed9)
