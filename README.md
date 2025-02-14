FFUF-Automation
FFUF-Automation is a Python script designed to automate FFUF (Fast web FUzzer) for fast and efficient web fuzzing. This tool helps penetration testers, bug bounty hunters, and security researchers discover hidden directories, files, subdomains, and parameters in web applications.

🚀 Features
Directory and file enumeration – Discover hidden paths efficiently
Subdomain fuzzing – Identify live subdomains easily
Virtual host detection – Uncover virtual hosts using HTTP headers
Parameter fuzzing – Find hidden GET and POST parameters
Custom wordlist support – Works with SecLists and other lists
Advanced filtering – Exclude responses by status codes, content length, or regex
Automation ready – JSON output for easy integration
🛠 Requirements
Python 3
FFUF Installed (go install github.com/ffuf/ffuf@latest)
Required Python libraries (pip install -r requirements.txt)
🔥 Usage
Run the script with a target URL and wordlist:

sh
Copy
Edit
python ffuf_automation.py -u https://target.com/FUZZ -w wordlist.txt
📜 License
This project is open-source. Contributions are welcome! 🚀
