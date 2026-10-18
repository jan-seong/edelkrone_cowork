# edelkrone shot cues

Motion cues for edelkrone camera motion gear, built with the [edelkrone Python SDK](https://pypi.org/project/edelkrone/) for the edelkrone MCP Challenge 2026.

| App | What it does | Status |
|---|---|---|
| `product-sequence/` | Repeats a slide + pan + focus product shot and triggers the camera at each step | in progress |
| `onair-bridge/` | Moves the rig to a stored shot when a live-switcher scene changes (over the local network) | in progress |

## Requirements

- Python 3.11 or newer, Bluetooth LE on the computer
- A supported edelkrone unit (tested with HeadPLUS V3, SliderPLUS V6, JibPLUS)
- `pip install -U edelkrone`

## Safety

These programs move equipment. Keep the motion path clear of people, cables and objects, start at a low speed, and stop with Ctrl+C or the stop button on the device. Every program stops the device before it disconnects.

## License

MIT — see [LICENSE](LICENSE).
