# Bảng dữ liệu thiết kế

Thông tin chi tiết về các cảm biến và module được sử dụng trong thiết kế:

## Cảm biến

| Cảm biến                                  | Điện áp nguồn | Dòng điện   | Giao tiếp |
|-------------------------------------------|---------------|-------------|-----------|
| Nhiệt độ-độ ẩm (HPP845E034R5)             | 3.8V          | 0.65 mA     | I2C       |
| Áp suất (BM1383AGLV)                      | 3.3V          | -           | I2C       |
| Cảm biến bụi (GP2Y1010AU0F)               | 5V            | 11 mA       | Analog    |
| Cảm biến hướng gió (AS5600)               | 3.3V          | 1.5 mA      | I2C       |
| Cảm biến tốc độ gió (Hall A3144)          | 4.5V-24V      | -           | Analog    |
| Cảm biến từ trường đo lượng mưa (HMC5883L)| 2.16V-3.6V    | 100μA       | I2C       |

## Module (NB-IOT ME310G1)

| Thuộc tính    | Giá trị         |
|---------------|-----------------|
| Điện áp nguồn | 3.8V            |
| Dòng điện     | 700 mA          |
| Giao tiếp     | UART, SPI, LTE  |

## MCU (PIC32MM0256GPM064)

| Thuộc tính    | Giá trị                |
|---------------|------------------------|
| Điện áp nguồn | 2.0V đến 3.6V          |
| Dòng điện     | 0.65 μA đến 5 μA       |
| Giao tiếp     | SPI, I2C, UART, USB-OTG|

# Nguồn tài liệu


- [File 3D và danh sách bom](https://www.thingiverse.com/thing:6439737)

# Sơ đồ thiết kế

Mô tả quy trình hoạt động:

![flowchart](https://github.com/lehungthinh02/KLTN_Data/blob/main/Flowchart/KLTN_DATA_DIAGRAM1.drawio.png)

# Case of Board

Mô tả về case bảo vệ board:

![Case of Board](https://github.com/lehungthinh02/KLTN_Data/blob/main/Case%20of%20board/case.png)
