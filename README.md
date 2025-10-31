#ESP32 Projects:

- DIY IR Smart Remote
- Bluetooth to wi-Fi Proxy 
- More soon to be...



# DIY IR Transmitter Remote

A custom IR transmitter remote currently designed to toggle power for a Seville Classics gray tower fan. This device uses a physical button and an LED indicator to show when a signal is being transmitted. Future updates will integrate it fully with Home Assistant for automated control.

---

## Current Features

- **Physical button control:** Press the button to toggle the fan's power.  
- **LED indicator:** Lights up when the IR signal is being transmitted.  
- **IR transmission:** Sends a pre-programmed power toggle code for the Seville Classics tower fan.  
- Fully functional as a standalone remote without Home Assistant.

---

## Hardware Used

- IR LED for transmitting the signal.  
- Microcontroller (e.g., ESP32 or Arduino).  
- Push button for manual input.  
- LED for transmission feedback.  

---

## Usage

1. Press the button to toggle the tower fan on or off.  
2. Observe the LED light up when the IR signal is sent.  

---

## Future Plans

- Add Home Assistant integration to send commands from automations and dashboards.  
- Support additional IR codes for other devices.  
- Enable control via MQTT or ESPHome for remote and automated management.  

---

## Notes

- Currently only supports the Seville Classics gray tower fan.  
- Code is toggle-based: pressing the button switches the fan between on and off states.  

---
## BlueTooth to WiFi Proxy for devices
"An ESP32 Bluetooth proxy acts as a bridge between Bluetooth and Wi-Fi for Home Assistant. It extends the range of Bluetooth devices (like thermometers, smart locks, or presence sensors) by scanning for their signals and forwarding that data over Wi-Fi to your Home Assistant server. This lets Home Assistant read Bluetooth devices that are far away or in other rooms, improving reliability and coverage."

---

#Hardware Used

- ESP32-Wroom.

# Code 

- The Code is currently unavailable as it is off-site.
- ~~The firmware File is availage which will be listed in the Project Folder.~~ Edit: Firmware file contain sensitive infomation, it is not available.
      Will be availabe soon.
## License

MIT License
