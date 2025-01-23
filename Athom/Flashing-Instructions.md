### Instructions for Flashing Athom Smart Plug V2:
1. Copy and paste base configuration file to ESPHome.
2. Change the values of *static_ip*, *use_address*, *api_key*, and *device_id*. 
3. OTA flash the device with *athom-smart-plug-v2-super-minimal.yaml* (no need to edit anything under packages).
4. OTA flash the device with *athom-smart-plug-v2-minimal.yaml* (uncomment the corresponding line under packages and comment the line containing *athom-smart-plug-v2-super-minimal.yaml*).
5. OTA flash the device with *athom-smart-plug-v2.yaml* (uncomment the corresponding line under packages and comment the line containing *athom-smart-plug-v2-minimal.yaml*).
