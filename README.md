# flightinfomock
This is used to share the javascript to simulate the flights information with Logic App on Azure. This script will be invoked by Recurrence to produce the content which will be sent to Event Hub or Eventstream.

The whole steps in Logic App (with stateful workflow) are:

![flightinfomock flow](https://github.com/xujxu/flightinfomock/assets/68268054/df818630-0cb7-443f-84c0-bc8bea8e6ed9)

- Recurrence
- Execute JavaScript Code (copy the script content to this step)
- Send Event (Event Hub connector In-App)
  - Add the EH connection:
    ![EH connection](https://github.com/xujxu/flightinfomock/assets/68268054/3d4529a5-cde9-4012-bbe3-241315518767)
  - Configure the EH step:
    ![EH configuration](https://github.com/xujxu/flightinfomock/assets/68268054/d79f983f-4d3d-40e3-a615-387f762958aa)

    


