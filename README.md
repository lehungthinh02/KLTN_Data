# Bảng dữ liệu thiết kế

| Cảm biến                           | Điện áp nguồn | Dòng điện              | Giao tiếp                           |
|------------------------------------|---------------|------------------------|------------------------------------|
| GPS (SL871)                        | 3.3v          | <10mA, <25 mA, <30 mA | UART (chính), I2C (phụ)           |
| Nhiệt độ-độ ẩm (HPP845E034R5)     | 3.8v          | 0.65 mA                | I2C                                |
| Áp suất (BM1383AGLV)              | 3.3v          | -                      | I2C                                |
| Cảm biến bụi (GP2Y1010AU0F)       | 5v            | 11 mA                  | Analog                             |
| Cảm biến hướng gió (AS5600)       | 3.3v          | 1.5 mA                 | I2C                                |
| Cảm biến tốc độ gió (Hall A3144)  | 4.5v-24v      | -                      | Analog                             |
| Cảm biến mưa (SG90/MG90S servo)   | 4.8v-6v       | 2.7 mA - 70 mA         | PWM                                |
| Cảm biến mưa (loadcell 100g + HX711) | 2.6 ~ 5.5v   | 1.6 mA                 | Pin_Clock, Pin_Data, ...           |

&nbsp;

| Module (NB-IOT ME310G1)            |               | 
|------------------------------------|---------------|
| Điện áp nguồn                      | 3.8v          |
| Dòng điện                          | 700 mA        |
| Giao tiếp                          | UART, SPI, LTE Cat-M1/Cat-NB1, DCS/PCS, GSM |

&nbsp;

| MCU(PIC32MM0256GPM064)             |               | 
|------------------------------------|---------------|
| Điện áp nguồn                      | 2.0v đến 3.6v |
| Dòng điện                          | 0.65 μA đến 5 μA  |
| Giao tiếp                          | SPI, I2C, UART, USB-OTG, CAN, LIN  |

# Nguồn tài liệu
[Do tốc độ gió](https://hackaday.io/project/191652-long-range-weather-station-65/log/220690-weather-station-anemometer)
[Do hướng gió](https://hackaday.io/project/191652-long-range-weather-station-65/log/220476-the-wind-direction-sensor)
[Do lượng mưa](https://hackaday.io/project/191652-long-range-weather-station-65/log/220475-the-rain-gauge)