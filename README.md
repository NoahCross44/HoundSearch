# HoundSniffer
<img width="570" alt="Screenshot 2024-12-09 at 12 01 10 AM" src="https://github.com/user-attachments/assets/605a8c83-1c9a-4e13-9f98-716615db6c42">


# Overview
HoundSniffer is a username reconnaissance and OSINT (Open-Source Intelligence) toolkit that helps locate a given username across unlimited platforms and services. It leverages customizable platforms and dorking queries to produce comprehensive HTML reports, making it easier to visualize and analyze results.

# Types of searches
* Platform Search: searches for usernames on platforms defined in platforms.txt.
* Dorking search:  Perform search engine queries on platforms like Google, Bing, and DuckDuckGo.

# Features
* Multi-threading: Quickly scans multiple platforms using threads for better performance.
* Advanced Dorking: utilizes dorking to search intxt and inurl
* Customizable User-Agent Headers: Rotates through user agents to avoid detection or rate limiting.
* Customizable Platform searches with .txt file
* Professional HTML Reports
 <img width="1440" alt="Screenshot 2024-12-09 at 12 04 22 AM" src="https://github.com/user-attachments/assets/f1c495c5-1375-46e7-93ee-c7bcb515033e">


# Prerequisites
pip install -r requirements.txt
* Python 3.6 or higher
* requests
* Colorama

# Customization:
* To add/remove platforms open the platforms.txt file. Each line should define a platform and its URL format:
e.x:
  - GitHub,https://github.com/{username}
  - Twitter,https://twitter.com/{username}
  - Reddit,https://www.reddit.com/user/{username}

# How To Run the script
Run the tool by executing the following command:
1. navigate to HoundSniffer.py directory
2. run 'python3 HoundSniffer.py'
3. Follow the on-screen prompts

# License
This tool is licensed under the MIT License. See the LICENSE file for details.

# Legal
HoundSniffer is for legal and ethical use only. It is the responsibility of the user to ensure compliance with all applicable laws and regulations. Misuse of this tool for illegal activities is strictly prohibited.
