# Wireless Breathing Monitor (ESP-NOW)

A non-invasive clinical device designed to monitor patient breathing patterns and transmit respiratory waveforms wirelessly between ESP32 nodes with ultra-low latency.

## Hardware & Components
- Microcontroller: 2x ESP32 (Transmitter & Receiver nodes)
- Sensor: CO2 sensor, MQ135, DHT11
- Display: OLED Display 

## Tech Stack & Communication
- Firmware: Embedded C 
- Protocol: ESP-NOW Protocol (MAC Address-based peer-to-peer wireless link)
- Network Architecture: Router-less direct Wi-Fi packet transmission

## Key Features
- High-speed, low-latency transmission using target hardware MAC address binding.
- Zero-Wi-Fi router dependency (functions in standalone hospital wards and ambulances).
- Continuous real-time respiration waveform synchronization and shallow-breathing detection.
