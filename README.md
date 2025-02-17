# FFUF-Automation
FFUF-Automation is a Python script designed to automate FFUF (Fast web FUzzer) for fast and efficient web fuzzing. This tool helps penetration testers, bug bounty hunters, and security researchers discover hidden directories, files, subdomains, and parameters in web applications.
![image](https://github.com/user-attachments/assets/127a7658-c10f-4aad-9d1b-167e8b72ed3f)

## 🚀 Features
- Directory and file enumeration – Discover hidden paths efficiently
- Subdomain fuzzing – Identify live subdomains easily
- Virtual host detection – Uncover virtual hosts using HTTP headers
- Parameter fuzzing – Find hidden GET and POST parameters
- Custom wordlist support – Works with SecLists and other lists
- Advanced filtering – Exclude responses by status codes, content length, or regex
- Automation ready – JSON output for easy integration
## 🛠 Requirements
- Python 3
- FFUF Installed (go install github.com/ffuf/ffuf@latest)
- Required Python libraries (pip install -r requirements.txt)
## 🔥 Usage
Run the script with a target URL and wordlist:
python ffuf_automation.py -u https://target.com/FUZZ -w wordlist.txt
![image](https://github.com/user-attachments/assets/2158abf1-a2da-458d-b66b-963016fdf6e4)

##📜 License
This project is open-source. Contributions are welcome! 🚀
