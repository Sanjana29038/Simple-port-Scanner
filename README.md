 Simple-port-Scanner
 
 This is a simple Python script for scanning ports on a target machine. It utilizes threading to improve performance by scanning multiple ports simultaneously.
 
 python3 Scanner.py TARGET START_PORT END_PORT
 
TARGET: The IP address or hostname of the target machine.
START_PORT: The starting port number of the port range to scan.
END_PORT: The ending port number of the port range to scan.

EXAMPLE
python3 Scanner.py 192.168.1.1 1 100

Description
This script uses the socket module in Python to create socket connections to the specified ports on the target machine. It utilizes threading to scan multiple ports concurrently, improving the efficiency of the scanning process.

Features
Scans a range of ports on a target machine.
Detects open ports and prints the results.

Installation
Clone the repository:
git clone https://github.com/your_username/simple-port-scanner.git

Navigate to the project directory:
cd simple-port-scanner

Run the script with appropriate arguments:
python3 Scanner.py TARGET START_PORT END_PORT

License
This project is licensed under the MIT License - see the LICENSE file for details.

This README file provides a brief overview, usage instructions, and installation steps for your port scanner. You can customize it further based on your preferences and project details. Let me know if you need further assistance or if you have any questions!

