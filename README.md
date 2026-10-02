# Greenhouse Climate Node Long-Range Telemetry

Build a smart agriculture prototype that uses EC sensor, flow sensor to report field measurements over long distances. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 104 |
| Category | Smart Agriculture |
| Platform | STM32 |
| Difficulty | Advanced |
| Estimated build time | 52 hours |
| Connectivity | Wi-Fi |
| Core components | EC sensor, flow sensor |
| Control mode | telemetry |

## Repository layout

- `firmware/greenhouse-climate-node-long-range-telemetry/greenhouse-climate-node-long-range-telemetry.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/greenhouse-climate-node-long-range-telemetry/greenhouse-climate-node-long-range-telemetry.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **STM32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Long-Range Telemetry demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
