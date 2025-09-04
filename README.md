# Esp32-S2_HelloBlink_Vs_Idf

This is an example for an Esp32-S2 USB Board, shows blinking a LED an monitor output.

There were some difficulties with a monitor com port not showing up after flashing the application.
TinyUSB had to be added as a dependency:

idf.py add-dependency esp_tinyusb~1.0.0

With the sdkconfig file used here (copy sdkconfig.copy to sdkconfig) it worked as expected.
