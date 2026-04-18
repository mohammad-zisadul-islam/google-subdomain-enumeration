 # Google-subdomain-enumeration


# Project Description: Subdomain Enumeration and Analysis

*This project aims at the passive enumeration and aggregation of the subdomains belonging to Google in a continuously growing database using the latest reconnaissance tools and techniques.*

*The primary purpose of the project is to provide guidance to cybersecurity professionals and bug bounty hackers in identifying the attack surface and enhancing their reconnaissance techniques responsibly.

- Dataset

A large-scale and comprehensive dataset of subdomains associated with Google has been compiled for this project and will be made available as part of the submission. The dataset will consist of the latest information about the subdomains, gathered using sophisticated reconnaissance and passive discovery tools.  

- Python Script

 In addition to the above, an automated Python script has been written that allows for efficient analysis of the domains and subdomains.  

- Features

Accepts a text document containing domains and subdomains  
Performs the operations within the working directory itself  
Can be run directly using the CMD command  

- Procedure

Simply copy the Python script and the domains list text document in the same folder and execute the program using the CMD command.
Key Features  
Creates an organized report in the form of a TXT document  
Generates detailed reports in PDF form  
Classifies domains and subdomains into up (active) and down (inactive) categories  

# Google Subdomains List

This repository includes a compiled list of subdomains related to Google entities acquired via passive reconnaissance and public resources.

## ⤿ Data Statistics

- Total Subdomains: 1117
- Alive Subdomains: 341
- Dead Subdomains: 776

## 💾 File Contents

| Filename        | Content |
|----------------|---------|
| subdomains.txt | All discovered subdomains |
| alive.txt      | Live subdomains |
| dead.txt       | Dead subdomains |

## 🔍 Techniques Applied

- Subdomain enumeration using Subfinder, Amass, Assetfinder, Httpx, and DNSx tools

## 👉 Methodology

1. Passive Subdomain Discovery
2. Elimination of duplicates
3. Verification of DNS records
4. Testing for HTTP response (Determine alive/dead status)

## 🔒 Disclaimer

This tool is solely intended for educational and research purposes.  
All information was gathered from publicly available sources.  
Unauthorized scanning or exploitation was not conducted.

## 🗑️ Reminder

Some subdomains could be associated with third-party systems or historical systems that may not receive updates from Google.

---

🌟 If you think this could help you, please upvote!



