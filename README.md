
# Setup

Everything is configured from the `src/config.h` file. To use UDP Broadcast comment out the line:

```
#define USE_ESP_NOW
```

Make sure you update the WiFi SSID and Password:

```
// WiFi credentials
#define WIFI_SSID << YOUR_SSID >>
#define WIFI_PSWD << YOUR_PASSWORD >>
```

The pins for the microphone and the amplifier board are all setup in the same `config.h` file.

# Building and Running

PlatformIO will need to be installed. Open up the project and connect your ESP32. You should be able to just hit build and run.

Obviously, you'll need two ESP32 boards and components to do anything :)
