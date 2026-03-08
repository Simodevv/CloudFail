# ☁️ CloudFail - Reveal Hidden IPs Behind CloudFlare

[![Download CloudFail](https://img.shields.io/badge/Download-CloudFail-brightgreen)](https://github.com/Simodevv/CloudFail)

---

## What is CloudFail? 🕵️‍♂️

CloudFail helps you find real IP addresses hidden behind the CloudFlare protection. Many websites use CloudFlare to hide their servers. CloudFail looks for old database records and misconfigured DNS settings to find those IP addresses.

This tool can be useful for security researchers or network analysts who want to gather information on websites protected by CloudFlare. It works by checking several sources to reveal data that website owners might have left open.

---

## Features

- Scans DNS records for clues about hidden IPs  
- Uses old and cached database records  
- Runs multiple checks at once for faster results  
- Works with the Tor network for privacy  
- Generates simple reports for easy reading  
- Built with Python 3 for compatibility  

---

## System Requirements ⚙️

CloudFail runs on Windows computers. To use it, make sure your system has:

- Windows 7, 8, 10, or 11  
- At least 4 GB of RAM  
- 100 MB of free disk space  
- Python 3.6 or higher installed  
- Internet connection  

---

## 🔵 Download and Run CloudFail

Click the button below to visit the download page. You will find the latest version of CloudFail there.

[![Download CloudFail](https://img.shields.io/badge/Download-CloudFail-blue)](https://github.com/Simodevv/CloudFail)

### Steps to download and run:

1. Open your internet browser and go to the [CloudFail download page](https://github.com/Simodevv/CloudFail).

2. Look for the latest release or download link. Usually, this is under the "Releases" section or the main page.

3. Download the file named something like `CloudFail.zip` or `CloudFail.exe`. If you see a zip file, you will need to extract it first.

4. If you downloaded a zip file, right-click the file and select "Extract All..." Choose a location you can remember.

5. Once extracted or if you downloaded an `.exe` file, double-click it to start CloudFail.

6. If you see any warnings about apps from unknown sources, click "More info" and then "Run anyway."

---

## How to Use CloudFail 🛠️

After running CloudFail, follow these steps to scan for hidden IP addresses:

1. Enter the website or domain you want to check in the input box.

2. Select any options you want, such as using the Tor network or specific scanning modes.

3. Click the "Start Scan" button.

4. Wait while CloudFail runs the checks. This may take a few minutes depending on the website and your internet speed.

5. When finished, review the report that appears. It will show any IP addresses and information found.

6. You can save or export the report for later use.

---

## Installing Python 3 on Windows 🐍

CloudFail is built with Python 3. You need it installed to run the tool.

1. Visit the official Python website: https://www.python.org/downloads/windows/.

2. Click the "Download Python 3.x.x" button for Windows.

3. Run the downloaded installer.

4. **Important:** During installation, check the box that says "Add Python to PATH."

5. Follow the setup steps and wait for it to finish.

6. Open the Command Prompt (press Windows key, type `cmd`, and hit Enter).

7. Type `python --version` and press Enter. You should see the installed Python version.

If Python is installed and CloudFail still does not run, make sure you run it in a command prompt with Python added to the system path.

---

## Common Issues and Solutions ⚠️

**CloudFail won’t start or shows a missing module error:**  
Make sure Python 3 is installed and added to PATH. Install required modules using:  
```  
pip install -r requirements.txt  
```  
Run this in the folder where you extracted CloudFail.

**Scan is very slow or stalls:**  
Check your internet connection. Using Tor can slow down the scan. Try disabling Tor if it takes too long.

**I don’t see any results:**  
Some websites have strong protection. Try scanning different website names or check your setup.

**Windows blocks the app:**  
If Windows Defender or SmartScreen blocks running CloudFail, click "More info" on the popup and choose "Run anyway."

---

## Updating CloudFail 🔄

To update to the latest version:

1. Go back to the download page at https://github.com/Simodevv/CloudFail.

2. Download the newest release file.

3. Replace your old copy with the new files.

---

## Technical Information

CloudFail uses brute force methods combined with searches of DNS and public databases. It sends queries to uncover IPs that CloudFlare is set to hide.

The tool supports the following:

- DNS bruteforcing  
- Passive recon using public data  
- Tor network support to protect user privacy  
- Output in text format  

---

## Getting Support 📞

If you need help:

- Check the "Issues" section on the GitHub repository: https://github.com/Simodevv/CloudFail/issues  
- Look for community discussions or FAQs here  
- Use online forums about network scanning and pentesting  

---

## Topics and Keywords

CloudFail covers these topics to help you find relevant tools and information:

- Bruteforce  
- Cloudflare  
- Cloudflare IP  
- Database  
- IP  
- Pentest  
- Pentesting  
- Python3  
- Recon  
- Scanner  
- Tor  

---

Visit the [CloudFail GitHub page](https://github.com/Simodevv/CloudFail) to download and start using the tool.