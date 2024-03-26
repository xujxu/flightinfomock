# flightinfomock
This is used to share the javascript to simulate the flights information with Logic App on Azure. This script will be invoked by Recurrence to produce the content which will be sent to Event Hub or Eventstream.

The whole steps in Logic App are:
- Recurrence
- Execute JavaScript Code
- Send Event (Event Hub connector In-App)
