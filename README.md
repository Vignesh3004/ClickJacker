# ClickJacker
The Clickjacking Vulnerability Checker is a command-line tool that helps identify websites vulnerable to clickjacking attacks. It analyzes the content-security-policy and x-frame-options headers to determine if a website is susceptible to clickjacking, providing a clear vulnerability status for each website checked. Additionally, it supports checking multiple websites at once and saving the vulnerable sites to a text file for further analysis or mitigation.
<br> 
<br>
## Installation
Install the clickjacker.py file 
Make sure you have python 3.x versions installed in your computer
<br>
<br>
## Usage 
python clickjacker.py [-h] (-s SINGLE | -m MULTIPLE [MULTIPLE ...] | -f FILE) [-v SAVE]
<br>
<br>
### For a Single website URL: 
python clickjacker.py -s <website_url>
<br>
### For Multiple websites URLs:
python clickjacker.py -m <website_url1> <website_url2>
<br>
### For a text file containing list of websites:
python clickjacker.py -f <filename> -v <save_file>
<br>
The -v or --save option is used to specify a file to save the vulnerable websites to.
<br>
<br>
## Optional arguments:
| Command | Description |
| --- | --- |
| `-h or --help ` | Show this help message and exit |
| `-s or --single` | Single website URL to check for vulnerabilities |
| `-m or --multiple` | Multiple website URLs to check for vulnerabilities |
| `-f or --file` | Includes the text file containing a list of websites |
| `-v or --save` | Save vulnerable sites to a text file |
<br>

## Note: <br>
If a website URL is provided without the http:// or https:// prefix, it will be automatically added.
 
## Follow me on: <br>
https://www.linkedin.com/in/vignesh3004 <br>
https://medium.com/@vignesh3004 <br>
https://www.youtube.com/@VigneshHunts
 
## Buy me a coffee:
https://www.buymeacoffee.com/vignesh3004
