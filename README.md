# PingNow
This is a self made ping test project/code/tool that you can use
# PingNow

A lightweight network diagnostic tool that pings IP addresses or websites and displays network latency.

## Features

- ✓ Ping IP addresses and domain names
- ✓ Display response times (latency in ms)
- ✓ Show packet loss statistics
- ✓ Beautiful ASCII art banner
- ✓ Error handling for network failures
- ✓ Limits to 4 pings per target

## Installation

```bash
git clone https://github.com/yourusername/PingNow.git
cd PingNow
```

### Requirements

- Python 3.6+
- `pyfiglet` library

Install dependencies:
```bash
pip install pyfiglet
```

## Usage

### Interactive Mode
```bash
python3 tool.py
```
Then enter an IP address or website when prompted.

### Non-Interactive Mode
```bash
echo "google.com" | python3 tool.py
```

### Examples

Ping Google:
```bash
python3 tool.py <<< "google.com"
```

Ping Google DNS:
```bash
python3 tool.py <<< "8.8.8.8"
```

Ping GitHub:
```bash
python3 tool.py <<< "github.com"
```

## Output

The tool displays:
- ASCII art banner with "PingNow"
- Ping statistics (packets transmitted/received)
- Response times for each packet
- Minimum, average, and maximum latency
- Packet loss percentage

## Example Output

```
 ____  _             _   _               
|  _ \(_)_ __   __ _| \ | | _____      __
| |_) | | '_ \ / _` |  \| |/ _ \ \ /\ / /
|  __/| | | | | (_| | |\  | (_) \ V  V / 
|_|   |_|_| |_|\__, |_| \_|\___/ \_/\_/  
               |___|                     

Enter an IP address or website URL to ping: PING google.com (142.250.76.78) 56(84) bytes of data.
64 bytes from maa05s14-in-f14.1e100.net (142.250.76.78): icmp_seq=1 ttl=111 time=114 ms
...
--- google.com ping statistics ---
4 packets transmitted, 4 received, 0% packet loss
```

## License

MIT License - Feel free to use and modify!

## Author

Sehjot
A lightweight network diagnostic tool that pings IP addresses or websites and displays network latency.

Features
✓ Ping IP addresses and domain names
✓ Display response times (latency in ms)
✓ Show packet loss statistics
✓ Beautiful ASCII art banner
✓ Error handling for network failures
✓ Limits to 4 pings per target
Installation
git clone https://github.com/yourusername/PingNow.git
cd PingNow
Requirements
Python 3.6+
pyfiglet library
Install dependencies:

pip install pyfiglet
Usage
Interactive Mode
python3 tool.py
Then enter an IP address or website when prompted.

Non-Interactive Mode
echo "google.com" | python3 tool.py
Examples
Ping Google:

python3 tool.py <<< "google.com"
Ping Google DNS:

python3 tool.py <<< "8.8.8.8"
Ping GitHub:

python3 tool.py <<< "github.com"
Output
The tool displays:

ASCII art banner with "PingNow"
Ping statistics (packets transmitted/received)
Response times for each packet
Minimum, average, and maximum latency
Packet loss percentage
