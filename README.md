Advanced Security Scanner
Advanced Security Scanner is a Python-based tool designed to perform security scans on IP addresses or domains. The tool uses various scanning utilities such as Nmap, SQLMap, Nikto, and BurpSuite to detect open ports, vulnerabilities, and provides the option to save the scan results as an XML file. The tool comes with a simple and intuitive GUI for easy interaction and monitoring.

Features
Multiple Scanners: Use Nmap, SQLMap, Nikto, and BurpSuite to perform comprehensive security scans.
Vulnerability Testing: Tests for common vulnerabilities such as HTTP and HTTPS-based issues.
XML Output: Save the scan results in XML format for further analysis.
Simple GUI: Easy-to-use graphical interface built with Tkinter.
Progress Tracking: Real-time progress bars for scan tools.
Requirements
Before using this tool, ensure the following Python packages are installed:

requests
tkinter
Pillow
subprocess
platform
threading

Install them using pip:
pip install requests Pillow

Installation

Clone the repository to your local machine:
git clone https://github.com/yourusername/AdvancedSecurityScanner.git
cd AdvancedSecurityScanner
pip install -r requirements.txt
python noto.py

Once launched, you can:

Enter a target IP or domain to scan.
Choose scanning tools like Nmap, SQLMap, Nikto, and BurpSuite.
View the scanning progress in real-time.
Save the scan results as an XML file.

Example Command Usage
python scanner.py

Important Notes
Legal Warning: This tool is intended for educational and research purposes only. Unauthorized scanning or exploiting vulnerabilities can be illegal. Make sure to have explicit permission before running scans on networks or systems.
Responsibility: Users are solely responsible for their actions while using this tool.
