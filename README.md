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
| 01 | [LED Blink Circuit](./01-Led-Blink-Circuit) | Current-limited LED driver circuit with calculated resistor values for two different LED forward voltages. |
| 02 | [ATtiny85 Microcontroller Board](./02-ATtiny85-Microcontroller) | Minimal ATtiny85 breakout with a proper reset circuit, decoupling, and a ground plane, on a 2-layer board. |
| 03 | [AMS1117 Power Supply](./03-AMS1117-Power-Supply) | 5V-to-3.3V regulated power supply with proper input/output decoupling, built on a 4-layer stackup with dedicated GND/power planes. |
| 04 | [BME280 I2C Sensor Board](./04-BME280-I2C-Sensor) | Self-contained sensor module with onboard 5V-to-3.3V regulation, an ATtiny85, and a BME280 environmental sensor over I2C. |
| 05 | [USB-C Power Board](./05-USB-C-Power-Board) | USB-C input with ESD protection, CC detection, differential pair routing, and 3.3V regulation. |
| 06 | [IoT Environmental Monitor (Capstone)](./06-IoT-Environmental-Monitor) | Full system: USB-C input with ESD protection, onboard power regulation, an ATtiny85, and a BME280 sensor. Designed, fabricated, and assembled. |

Tools

- KiCad (schematic capture, PCB layout, DRC/ERC)

About this repository

Each project folder contains:
- A README with the design brief, schematic, PCB layout, and key decisions
- Schematic and PCB screenshots
- KiCad source files
