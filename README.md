# Social Media Posting Bot
This python script to automate the posting on the social media website like Facebook.

### What it does:
As it is named, this python script automatically login/logout your Facebook account and posting your text-based content on the Facebook Pages.

### How does it do or Instructions to use?
- This script requires the latest version of python to do work, also requires some of the python libraries like:
  - selenium
  - JSON if not available
- Once you install the python, sets the environment variables.
- Download Social Media Posting Bot Script, and extract it somewhere in the system
- **Required/Important:**
  - Open **credentials_load.json** in notepad, and replace **yourloginemailaddress@loginemail.com** with your Facebook login email address, and email address should come between double-quotes. Also, perform the same thing with **yourloginpassword**, put your Facebook login password there (should come between double quotes).
  - To post the desire status/text, open the **PostingContents.txt** file in notepad, and add text there (this will not come in the double quotes).
  - After performing the two above steps, then we need to open cmd in the **Social bot media posting bot extracted folder** (Open the folder and type the cmd in the file explorer path, it will be on the top).
  - After opening the cmd, type **python socialbotver1.py** in the cmd to run the script.


**My Ideology:** Whenever I saw some tech things which can be automated, and make my work quicker than I always push myself hard to automate those task. So, This is the script that I built to automate one of my current job tasks.

**Credits for chromedriver.exe:**
- Thanks **Google** for creating <a href="https://chromedriver.chromium.org/">ChromeDriver</a> to control the chrome functions.
