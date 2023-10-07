# There is a storage xss vulnerability in the zentao OA
##[CVE ID]

CVE-2023-44826

##[PRODUCT]

zentao OA Open source version 18.6

##[VERSION]

Open source version 18.6

##[PROBLEM TYPE]

Cross Site Scripting (XSS)

##[DESCRIPTION]

There is a stored XSS vulnerability in the background of zentao OA, which can steal user cookies or perform watering hole attacks

Location of vulnerability：http://127.0.0.1:81/zentao/project-browse-0-all.html

Create the project and insert the XSS script at the username

![image](https://github.com/jacyyang52/chandaoxss/assets/147254524/22a175ea-f482-45fe-a532-44d28c1ebc43)

Click Save to save the project in the background

![image](https://github.com/jacyyang52/chandaoxss/assets/147254524/803051ca-8015-4cdd-851b-3aea8e7fffb7)

View the created project and trigger a pop-up window

![image](https://github.com/jacyyang52/chandaoxss/assets/147254524/d1f1bcb3-370e-4c3a-84cd-26a712be301b)
