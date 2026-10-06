# Day 7: DHT11 Readout

This project interfaces a DHT11 temperature and humidity sensor with an ESP32 and displays the temperature and humidity readings on the Serial Monitor every 2 seconds.

## Question

**DHT11 Readout – Interface a DHT11 sensor and display temperature and humidity readings every 2 seconds.**

## Hardware

- ESP32 DevKit v1
- DHT11 Temperature and Humidity Sensor

## Features

- Reads temperature from the DHT11 sensor
- Reads humidity from the DHT11 sensor
- Displays readings every 2 seconds
- Uses the DHT sensor library

## Connections

| DHT11 | ESP32 |
|---|---|
| VCC | 3.3V |
| DATA | GPIO 15 |
| GND | GND |

## Output

The Serial Monitor displays the temperature and humidity values every 2 seconds.

Example:

```
Temperature: 28.00 °C
Humidity: 65.00 %
```

## Project Files

- `sketch.ino` – ESP32 Arduino code
- `diagram.json` – Wokwi circuit configuration
- `libraries.txt` – Required Arduino libraries
