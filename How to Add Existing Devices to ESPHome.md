### How to Add Existing Devices to ESPHome
1. Open **Home Assistant** and go to **ESPHome**.
2. Click **NEW DEVICE** then **CONTINUE**. Change Name* to *{device manufacturer}-{device name}-{device id}* e.g. *apollo-air-1-87b074*.
3. Ignore the generated API Key.
4. Click **EDIT** on the newly added device.
5. Paste the base configuration file for the device. Under substitutions, change the values of *static_ip*, *use_address*, *api_key*, and *device_id*. 
6. OTA flash the device. For Athom Smart Plug V2, check *Flashing-Instructions* in the Athom folder.
