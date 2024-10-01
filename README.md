# Chain Length and Scope Calculator

This Python application calculates the chain length, scope compared to water depth, and moving direction. It gathers data from an ESP32 development board, hall effect sensors, and optocoupler sensors. The data is shared with a SignalK server hosted on a Raspberry Pi.

## Features

- Calculate chain length
- Calculate scope compared to water depth
- Determine moving direction
- Integration with ESP32 dev board
- Data collection from hall effect and optocoupler sensors
- Data sharing with SignalK server

## Requirements

- Python 3.9
- ESP32 development board
- Hall effect sensors
- Optocoupler sensors
- SignalK server hosted on a Raspberry Pi

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/chain-length-calculator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd chain-length-calculator
    ```
3. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Connect the ESP32 development board, hall effect sensors, and optocoupler sensors as per the wiring diagram.
2. Ensure the SignalK server is running on the Raspberry Pi.
3. Run the application:
    ```sh
    python main.py
    ```

## Configuration

Update the `config.json` file with the appropriate settings for your setup.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- [SignalK](https://signalk.org/)
- [ESP32](https://www.espressif.com/en/products/socs/esp32)
