# TPMS Monitor Plugin for Flipper Zero

This is a plugin for the [Flipper Zero](https://flipperzero.one/) multi-tool device that allows you to monitor the Tire Pressure Monitoring System (TPMS) of Ford vehicles.

## Features

- Monitors the TPMS of Ford vehicles.
- Displays tire pressure data on the Flipper Zero screen.
- Supports Ford vehicles from model year 2003 onwards.

## Installation

1. Clone this repository to your local machine using `git clone https://github.com/yourusername/tpms_monitor.git`
2. Navigate to the directory containing the plugin and `.fam` file.
3. Use the Flipper Zero build system to compile the plugin. Run `make` in the terminal.
4. After building the plugin, a compiled file will be generated.
5. Connect your Flipper Zero device to your computer.
6. Copy the compiled plugin file to the Flipper Zero's internal storage.

## Usage

1. Disconnect your Flipper Zero from your computer.
2. Navigate to the TPMS Monitor plugin on your Flipper Zero device using the device's buttons.
3. Once you've opened the TPMS Monitor plugin, you'll see a screen displaying the current tire pressure data.
4. The plugin will automatically update the tire pressure data as new TPMS signals are received.

## Troubleshooting

If you encounter any issues while using the TPMS Monitor plugin, try the following steps:

1. Ensure that your Flipper Zero device is running the latest firmware.
2. Check that the TPMS Monitor plugin was built and installed correctly.
3. Make sure that the TPMS system in your Ford vehicle is functioning properly.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
