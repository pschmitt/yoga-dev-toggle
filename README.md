# yoga-tools

## Installation

```bash
wget https://raw.github.com/pschmitt/yoga-dev-toggle/master/yoga-dev-toggle
chmod +x yoga-dev-toggle
```

## Usage

```bash
# Enable touchpad
yoga-dev-toggle touchpad on
# Disable touchscreen
yoga-dev-toggle touchscreen off
# Toggle Wacom digitizer
yoga-dev-toggle wacom
# Start digitzier watchdog (disable touchscreen when digitizer is detected)
yoga-dev-toggle prox
# Short arguments
# Touchpad: touchpad|tpd|tp
# Trackpoint: trackpoint|trpt|tpt|trp
# Wacom: wacom|w
# Proximity: proximit|prox|p
yoga-dev-toggle tpd on
```

## Thinblink

Go checkout my [thinkblink](https://github.com/pschmitt/thinkblink) script as well! I'm working on making the power LED behave like a notification LED (similar to what's on most Android phones and tablets).
