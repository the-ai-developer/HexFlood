# URL-DDOS Tool
**Coded By**: @princetheprogrammer
**GitHub**: [github.com/the-ai-developer](https://github.com/the-ai-developer)

## About
**URL-DDOS** is a Python-based tool designed for educational purposes only, aimed at simulating Denial of Service (DoS) attacks using three different attack modes: UDP, TCP, and HTTP. This tool can be used to understand how DDoS attacks work, and to test the resilience of a network, server, or website under simulated traffic conditions.

> **NOTE**: This tool is intended for legal and ethical use only. Do not use this tool to attack any unauthorized systems. Use it only on systems you have explicit permission to test.

## Features

### Attack Modes:
- **UDP Flood**: Sends continuous UDP packets to the target.
- **TCP Flood**: Opens TCP connections and sends data to the target.
- **HTTP Flood**: Simulates HTTP requests to overwhelm the target.

### Additional Features:
- **Domain Resolution**: Automatically resolves domain names to IP addresses.
- **Target Validation**: Verifies if the URL or IP is live before launching the attack.
- **Threaded Execution**: Supports multi-threaded attacks for faster and more impactful results.
- **Customizable Parameters**: Configure the target IP/URL, port, attack duration, number of threads, and attack mode.

## Installation

### Prerequisites
Before running the tool, you must have Python installed (preferably Python 3.6 or later). You will also need the `requests` library for URL checks.

- Install Python 3 from the [official Python website](https://www.python.org/).
- Install the required dependencies using pip:

```bash
pip install requests
```

## Usage

### Running the Tool
To run the **HexFlood** tool, follow the steps below:

1. Clone the repository or download the script:

    ```bash
    git clone https://github.com/the-ai-developer/HexFlood.git
    cd HexFlood
    ```

2. Run the script using Python:

    ```bash
    python HexFlood.py
    ```

3. Follow the on-screen prompts to configure the attack parameters:

- **Enter Target (IP or URL)**: Provide the target's IP address or URL.
- **Enter Target Port (e.g., 80)**: Specify the port to attack (common ports: 80 for HTTP, 443 for HTTPS).
- **Enter Number of Threads (e.g., 10)**: Specify how many threads to use for the attack.
- **Enter Duration of Attack in Seconds**: Set how long the attack should run.
- **Choose Attack Mode (UDP / TCP / HTTP)**: Select the type of attack to simulate.

### Example

This will start a TCP flood attack on example.com on port 80 for 30 seconds using 50 threads.

## Important Notes

- **Educational Purpose Only**: The tool is built to simulate network traffic for educational and testing purposes. Do not use it for illegal activities.
- **Use Responsibly**: Only use this tool on networks or systems you own or have explicit permission to test.
- **Legality**: Ensure that you have the proper permissions and that your actions do not violate any laws or terms of service.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This tool is for educational purposes only. The creator and contributors are not responsible for any misuse of this tool. Please use it responsibly, and always ensure that you have the necessary permissions before performing any tests.
