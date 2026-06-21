PCB Design Projects

A set of PCB designs built in KiCad, covering circuit fundamentals through to a complete USB-C powered environmental sensor system. Each project includes the full schematic, PCB layout, and the design reasoning behind key decisions — component selection, power regulation, signal integrity, and manufacturability.

Skills demonstrated

- Schematic capture, ERC, and footprint assignment
- PCB layout, routing, and Design Rules Checking (DRC)
- Current-limiting and Ohm's law-based component selection
- Decoupling capacitor strategy and power supply design (LDO regulation)
- Multi-layer (4-layer) stack-ups with dedicated GND/power planes
- I2C bus design, addressing, and pull-up resistor sizing
- USB-C power delivery, ESD protection, and differential pair routing
- Copper pours, thermal relief, and controlled-impedance routing
- Design for Manufacture (DFM): trace width selection, silkscreen clearance, panelization-aware board outlines
- Gerber generation and verification for fabrication

Projects
| # | Project | Description |
|---|---------|-------------|
| 01 | [LED Blink Circuit](./01-led-blink-circuit) | Basic resistor + LED series circuit. First schematic-to-Gerber workflow. |
| 02 | [ATtiny85 Microcontroller Board](./02-attiny85-microcontroller) | Minimal MCU board with reset circuit, decoupling, and copper pour. |
| 03 | [AMS1117 Power Supply](./03-ams1117-power-supply) | 5V-to-3.3V regulated power supply with proper input/output decoupling. |
| 04 | [BME280 I2C Sensor Board](./04-bme280-i2c-sensor) | ATtiny85 + BME280 environmental sensor over I2C, on a 4-layer board. |
| 05 | [USB-C Power Board](./05-usb-c-power-board) | USB-C input with ESD protection, CC detection, and 3.3V regulation. |
| 06 | [IoT Environmental Monitor (Capstone)](./06-iot-environmental-monitor) | Full system: USB-C power, ATtiny85, BME280 sensor, DFM-reviewed and fabricated. |

Tools

- KiCad (schematic capture, PCB layout, DRC/ERC)

About this repository

Each project folder contains:
- A README with the design brief, schematic, PCB layout, and key decisions
- Schematic and PCB screenshots
- Gerber files where available
