# ESP32_Waveshare42V2
Working Waveshare 4.2 Inch V2 Module E-Paper Display Configuration on ESP32-WROOM-32D/32U

## Display Panel Config: 

#define GxEPD2_DISPLAY_CLASS GxEPD2_BW

#define GxEPD2_DRIVER_CLASS GxEPD2_420_GDEY042T81 // GDEY042T81 400x300, SSD1683 (no inking)

## Wiring:
BUSY -> 4, RST -> 16, DC -> 17, CS -> SS(5), CLK -> SCK(18), DIN -> MOSI(23), GND -> GND, 3.3V -> 3.3V

Example:

![Image](/doc_assets/example_pins.jpg)

![Image](/doc_assets/esp32_devkit.jpg)
