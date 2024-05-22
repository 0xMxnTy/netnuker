🚀 netnuker
---
v1.1

![image](https://github.com/mxntysec/netnuker/assets/166342298/fe41f33a-f628-4d7f-94aa-1bd8663ca781)

netnuker is an all-in-one attack tool that performs TCP Syn Flood Attacks, Nmap scans, and Sub Directory Brute Forcing.

netnuker leverages nmap and a custom tool named subdestroyer for comprehensive reconnaissance.

![image](https://github.com/mxntysec/netnuker/assets/166342298/95166b4b-4497-4a48-98a0-34a5064fd5a8)
---
✨ Features

    TCP Syn Flood Attack (DDoS)
    Nmap Scans:
        Standard scans with service/version detection.
        Most popular 100 UDP ports scan.
    Subdirectory Brute Forcing with subdestroyer.

📋 Prerequisites
---
Ensure you have the following installed:

    nmap
    Python 3
---
Install the dependencies via the requirements.txt file:

`pip install -r requirements.txt`

🔧 Installation
---
Clone this repository:
---
```
git clone https://github.com/mxntysec/netnuker.git
cd netnuker
```
---
Install dependencies:

    `pip install -r requirements.txt`
---
🚀 Usage

Run netnuker with the following command:

`python3 netnuker.py`
---
Available Options:

    TCP Syn Flood Attack (DDoS)
    Nmap Scan (-sC -sV -p- --open)
    Subdirectory Scan (subdestroyer)
    Nmap Scan for Most Popular UDP Ports
---
Note:

    The default subdirectory wordlist is located at /usr/share/seclists/Discovery/Web-Content/raft-medium-directories.txt. You can change this by editing the script on line 144 and modifying the wordlist = line.

⚠️ Disclaimer

This tool is intended for educational purposes only and should only be used on networks and systems for which you have explicit permission to conduct security testing. Unauthorized use of this tool is illegal and unethical, and can result in severe legal consequences.
---
🧪 Testing

This tool is still in testing. If it doesn't work or has bugs, improvements are in progress. Enhancements to the efficiency of the TCP Syn Flood attack are ongoing.
---
🛡️ Ethical Disclaimer
---
This tool is intended for educational purposes only and should only be used on networks and systems for which you have explicit permission to conduct security testing. Unauthorized use of this tool is illegal and unethical, and can result in severe legal consequences.

Feel free to contribute to this project or raise any issues you encounter.
