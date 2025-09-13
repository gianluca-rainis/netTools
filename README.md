# netTools 
A network analizer tool that can send personalized packets, scan the LAN with ARP to found for all IPs the MAC and the DNS, simulate a DDoS sending packets to a host with random public source IP and scan the ports in a given range of a host to search which are open.
## Libraries
- tkinter
- pathlib
- socket
- threading
- random
- scapy
- ipaddress
## Installation
To install the tool first you need to download the source code from github, then download and intall python on your PC (https://www.python.org/downloads/), then you need to install the libraries, to install the libraries run the following commands:

```bash
pip install pathlib
```
```bash
pip install socket.py
```
```bash
pip install random2
```
```bash
pip install scapy
```
```bash
pip install ipaddress
```

The other libraries can be installed when you install python. The commands to install the libraries may be different for other OS.
The tool was written for Windows, but it may work also for linux.

To run the tool open the terminal in the project folder and run
```bash
python main.py
```
