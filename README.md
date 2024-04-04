# Flight_control_controller_V1.2
Hardware files for universal flight controller for small UAV's. 

![image](https://github.com/Himanshukohale22/Flight_control_controller_V1.2/assets/114358863/12f31b0a-7cc5-4ecb-81cb-66affb741de1)

### BOARD SPECIFICATION.
---

* STM32f7 cortex M4 based on board microcontroller for precision and fligt data simulation.
  * Core: Arm® 32-bit Cortex®-M7 CPU with FPU
  * Six-stage dual-issue pipeline
  • Dynamic branch prediction
  • Harvard caches (8 Kbytes of I-cache and 8 Kbytes of D-cache)
  • 64-bit AXI4 interface
  • 64-bit ITCM interface
  • 2x32-bit DTCM interfaces 
* sensors
  * MPU9250.(IMU)
    *  9-axis of freedom. (6 are used).
    * accerelometer an gyroscopic values
    * Higher calibration precision.
    * for statbility and orientation of board/vehicle.
    * configured with SPI1.
  * BMP280 .(Barometer)
    * configured with I2C .
    * barometer for altitude calculations . helps to hover the flight.
    * absolutely accurate p = 950 -- 1100 hPa.
  * NRF module
    * nrf module for communication upto 1km.
    * configured with SPI2.
  * BLE
  * WIFI
  * Servo motors
  * GPS support
  * Perhipherals
    * UART X2
    * I2C  X1
    * SPI  X1
    * CAN  X1
  * Power 
    * 3V3 sensor support
    * 5V support
    * usbB mini for testing testing.
    * jst connector i/p from 12v to 27v .
  * OSD (On screen display)
  * SD card support
  * for programme the ,board include four pins ckl , io , pwr , gnd as in 1.27mm pins(SWD). use ST-LINK.


Top Layer
---

![image](https://github.com/Himanshukohale22/Flight_control_controller_V1.2/assets/114358863/21d47a12-9952-4f71-b3aa-9ab9d2a3119d)

Bottom Layer 
---
![image](https://github.com/Himanshukohale22/Flight_control_controller_V1.2/assets/114358863/2708bd42-c3c5-4f01-875b-15fd231d8984)



