# **Nmap Vulnerability Scanner**

A simple vulnerability scanning script built on Kali Linux using Nmap to identify open ports and known vulnerabilities on a target system.

## **📖 Project Overview**
This project automates basic network scanning tasks, combining service detection and vulnerability script scanning (`nmap --script vuln`) to help identify potential security risks in target machines or networks.

It is designed to:

- Perform full TCP scans.
- Detect services and their versions.
- Run vulnerability detection scripts from Nmap's NSE library.
- Output the results into an organized report format.

## **🛠 Technologies Used**
1. Kali Linux
2. Nmap (Network Mapper)
3. Bash / Linux Terminal

## **🚀 How to Use**
1. Clone or download the repository.
2. Ensure you have Nmap installed by running:
   ```bash
   sudo apt update
   sudo apt install nmap
## 🚀 How to Use

Run the scanner script or manually execute:

```bash
nmap -sV --script vuln <target-ip>

## **PROJECT STRUCTURE**
nmap-vuln-scanner/
├── scan.sh           # (optional) Bash script to automate the scan
├── output/           # Directory to store scan results
├── screenshots/      # Screenshots of the tool in action
└── README.md         # Project documentation (this file)
🎯 Features
Automated vulnerability scans using Nmap's built-in scripts.

Customizable scanning options for different targets and ports.

Organized output files for easy analysis.

Beginner-friendly project ideal for those learning penetration testing and reconnaissance.

⚠️ Legal Disclaimer
This project is intended ONLY for educational purposes or authorized penetration testing. Unauthorized scanning of networks that you do not own or have explicit permission to test is illegal and unethical.

🤝 Contribution
Pull requests are welcome!
If you have ideas for improvements, feel free to fork the project and submit a PR.

📧 Contact
Created with 💻 by Maureen Rita Muriuki
Feel free to reach out for collaboration or feedback!

⭐️ Show Your Support
If you found this project helpful, give it a ⭐️ on GitHub! It helps others find it too!


