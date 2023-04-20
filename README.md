# esphome-projects

Personal collection of esphome projects. See `README.md` in each project directory for more information.

- bt-proxy - Bluetooth / BLE proxy devices
- hvac-detector - Detects HVAC is running by monitoring vibrations
- pan-world-7rc04 - Monte Carlo Maverick fan remote hack
- pool-ezo - Monitors pH / ORP probes in pool plumbing
- rf-bridge - 433 MHz bridge using the you-called-it...Sonoff RF Bridge

## Setup

Get the code:

```bash
git clone https://github.com/robert-alfaro/esphome-projects.git
```

Create Python3 virtual environment and install esphome:

```bash
python -m venv venv
. venv/bin/activate
pip install esphome
```

Create `secrets.yaml` in the root of the repo, fill with credentials:

```yaml
wifi_ssid: <your ssid>
wifi_pass: <your pass>
```

## Build & Run on device

```bash
esphome run <proj_name>/<proj_name>.yaml --device=<serial or hostname>
```

