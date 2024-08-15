# ESPHome Water softener blocksalt level detector (esphome.salt.level)

Inspired by 'Water Softener Salt Level Monitor' https://www.instructables.com/Water-Softener-Salt-Level-Monitor/.


![image](VL53L0X.png)

![image](circuit.png)


# ESP32 WROOM

| ESP32 Pin | Name    | VL53L0X Left | VL53L0X Right |
| --------- | ------- | ------------ | ------------- |
| 19        | Vin 5v  |              |               |
| 38        | GND     |              |               |
| -         |         |              |               |
| 1         | 3.3v    | VIN          |               |
|           |         | GND          |               |
| 36        | GPIO22  | SCL          |               |
| 33        | GPIO21  | SDA          |               |
|           | -       | GPIO1        |               |
| 31        | GPIO19  | XSHUT        |               |
| -         |         |              |               |
| 1         | 3.3v    |              | VIN           |
|           |         |              | GND           |
| 36        | GPIO22  |              | SCL           |
| 33        | GPIO21  |              | SDA           |
|           | -       |              | GPIO1         |
| 30        | GPIO18  |              | XSHUT         |

# ESP32-S3 Mini

![image](ESP32-S3-Mini.png)

| ESP32-S3 Mini Pin | Name    | VL53L0X Left | VL53L0X Right |
| --------- | ------- | ------------ | ------------- |
| 1         | Vin 5v  |              |               |
| 2         | GND     |              |               |
| -         |         |              |               |
| 3         | 3.3v    | VIN          |               |
|           |         | GND          |               |
| 6         | GPIO22  | SCL          |               |
| 5         | GPIO21  | SDA          |               |
|           | -       | GPIO1        |               |
| 7         | GPIO19  | XSHUT        |               |
| -         |         |              |               |
| 3         | 3.3v    |              | VIN           |
|           |         |              | GND           |
| 6         | GPIO22  |              | SCL           |
| 5         | GPIO21  |              | SDA           |
|           | -       |              | GPIO1         |
| 4         | GPIO18  |              | XSHUT         |
