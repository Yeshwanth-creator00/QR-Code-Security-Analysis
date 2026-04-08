#  QR Code Security Analysis

# Project Overview

This project focuses on analyzing the security risks associated with QR codes using Kali Linux tools. QR codes are widely used for payments, login systems, and websites, but they can also contain malicious links or hidden data.

# Objective

* Detect malicious links inside QR codes
* Extract hidden data using steganography techniques
* Analyze website vulnerabilities from extracted links
* Classify QR codes based on risk level

# Tools Used

* **ZBar** – For scanning and extracting QR code data
* **Steghide** – For detecting hidden data inside images
* **Nikto** – For web vulnerability scanning
* **Jok3r** – For automated web application analysis

# Methodology

1. Scan QR code using ZBar
2. Extract hidden data using Steghide
3. Analyze extracted links using Nikto and Jok3r
4. Perform risk classification (Safe / Suspicious / High Risk)

# Results

* Successfully extracted visible and hidden data from QR codes
* Identified malicious and suspicious URLs
* Performed vulnerability analysis on extracted links

# Project Structure

* `README.md` → Project documentation
* `report.pdf` → Detailed project report
* `screenshots/` → Tool outputs and results
* `samples/` → Sample QR codes

# Conclusion

This project demonstrates how QR codes can be exploited for cyber attacks and how security tools can be used to detect and analyze such threats effectively.



 Developed as part of Cybersecurity Project using Kali Linux
