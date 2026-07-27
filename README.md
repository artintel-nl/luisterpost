# Luisterpost

*A listening post in a Utrecht city garden.*

One house near the centre of Utrecht, listening to its environment across four physical
media — **sound, radio, light and gamma radiation**. Microphones, antennas, particle
detectors and weather instruments, all reporting into one small MQTT broker.

**Website: [luisterpost.io](https://luisterpost.io)**

## Channels

| CH | Instrument | Medium | Status |
|----|-----------|--------|--------|
| 01 | Birds — BirdNET acoustic species detection | Sound 2–10 kHz | Live |
| 02 | Weather — greenhouse station + AS3935 lightning | Mixed · RF 500 kHz | Live |
| 03 | Air quality — CO₂ / PM2.5 / temp / RH | Particle count | Live |
| 04 | Aircraft — from-scratch ADS-B decoder | Radio 1090 MHz | Live |
| 05 | Drones — EU/ASTM Remote ID receiver | Radio 2.4 GHz | Live |
| 06 | Power — station telemetry (INA219 DC) | Telemetry | Live |
| 07 | Aerosol lidar — 905 nm backscatter | Light 905 nm | Planned |
| 08 | Radiation — RadiaCode 110 gamma monitor | Gamma 0.05–3 MeV | Live |

## Status

The repository is being filled one instrument at a time: firmware, hardware notes,
housing builds, data formats, then data releases. Watch this space.

## Licensing

- **Code**: MIT
- **Data & docs**: CC BY 4.0
- Station location is published at city precision (52.09° N, 5.12° E).
