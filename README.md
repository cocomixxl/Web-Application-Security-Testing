[Coursera 4X32KUBFZ3VD.pdf](https://github.com/user-attachments/files/18875911/Coursera.4X32KUBFZ3VD.pdf)
# Web-Application-Security-Testing

## Objective

An Introduction and overview of what OWASP ZAP is and how it is important for web security professionals.  
Understand the layout of OWASP ZAP and scan a website for vulnerabilities.
Analyze the OWASP ZAP vulnerability scan results and generate a vulnerability report from those results.  
Setup and configure FoxyProxy within the Firefox browser to use ZAP as a proxy.  
Find files and directories of a web server using a dictionary list within OWASP ZAP.  
Using OWASP ZAP to crawl and spider websites to find links and URLs.  
Using OWASP ZAP as a web proxy to intercept a valid request, modify it to make it invalid, and then send it to the web server to provoke unexpected behavior from it.  

### Skills Learned
- the fundamentals of how to use OWASP Zed Attack Proxy (ZAP)


### Tools Used
- OWASP ZAP


## Steps
### Task 1
Layout and first scan
![Screenshot 2025-02-19 150345](https://github.com/user-attachments/assets/49009b25-2024-4d09-8054-313b1692912c)
![image](https://github.com/user-attachments/assets/20807762-23b5-4ffa-8429-4cfa82d33c34)
Active scan > scan policy manager > default policy
![Screenshot 2025-02-19 150626](https://github.com/user-attachments/assets/77a2938a-566c-4e5e-bc79-907a4fe5f3ff)
different types of scans
![image](https://github.com/user-attachments/assets/cf2cd771-ffd8-4b02-b7ee-b4db32039c8b)
http://127.0.0.1/mutillidae/ in the url attack, then attack
![image](https://github.com/user-attachments/assets/8fee3e25-0ea3-4ac7-bff0-a0e2c86eb42b)
MutinyDay is a free open source web application and it's deliberately vulnerable and can be used to practice web application testing
![image](https://github.com/user-attachments/assets/72284532-7a81-40c8-aa15-1196dcbcaa7e)
### Task 2
Analyzing the OWASP ZAP Scan Results and Generating a Report
![image](https://github.com/user-attachments/assets/e65d8410-ad01-45fc-b500-355d98e77c03)
copy the url and paste in the browser
![image](https://github.com/user-attachments/assets/43130deb-3d4e-4946-9fa1-66c8542f0b5c)
analyze the sql injection and make a report
![Screenshot 2025-02-19 152511](https://github.com/user-attachments/assets/77232c5d-558a-4b3b-9a5a-a2784858edc3)
generate html report
![image](https://github.com/user-attachments/assets/890b4895-c1ce-4f61-a220-062e584fdf12)
save on desktop and open it then save as pdf
![image](https://github.com/user-attachments/assets/69436bc2-8948-43f1-82f5-f87170ecf81d)

### Task 3
Setting up FoxyProxy in Firefox to use OWASP ZAP as a Proxy
download foxy proxy addon
![image](https://github.com/user-attachments/assets/0c201f67-b4a0-44fd-b3b8-ba039d40de89)
open the addon 
![image](https://github.com/user-attachments/assets/f0b4fc6c-6ee1-47d9-af1b-6af8f92aeb88)
save and enable
![image](https://github.com/user-attachments/assets/04f6081a-6b2c-409f-b4e0-47a5d7e1dca9)
go to owasp zap options and change port from 8080 to 8081
![image](https://github.com/user-attachments/assets/b12a7c48-cdc3-4e4d-9e55-56b1682c415d)
test the proxy 
![image](https://github.com/user-attachments/assets/b08e182b-ee85-4c69-b8a5-647ab576ba59)
![image](https://github.com/user-attachments/assets/23dded85-9380-46a6-a9ce-9f24e22092eb)

### Task 4
Finding Files and Folders Using a Dictionary List within OWASP ZAP
![Screenshot 2025-02-19 154338](https://github.com/user-attachments/assets/27b9788c-ae0d-4339-84c8-0b42de8f63dc)
in the Tree structure Zap is reacting to this
### Task 5
Use OWASP ZAP to Spider Crawl a website to find URLs and Links 
![image](https://github.com/user-attachments/assets/04f240e1-2c5a-4f4c-8ac5-6250dd369eef)
leave as default
![image](https://github.com/user-attachments/assets/4e8a3623-32ff-47ec-a003-af35816f0f34)
After crawling a website or directory in this way, you can use the stored request to perform some pen testing.

### Task 6
Use OWASP to View and Alter Requests

![image](https://github.com/user-attachments/assets/8f1c97ff-2359-4a4e-a8d8-21148f6dd464)
toggle security 
![image](https://github.com/user-attachments/assets/cd482cb2-6e6f-4c77-8fe7-bf34a60977a3)
sview account in using user' and password'
![image](https://github.com/user-attachments/assets/e0c97b2c-6393-4d71-9c18-10620243022d)
put a break on request
![image](https://github.com/user-attachments/assets/105d355a-1c36-4b2d-acb6-3bcdaec1e4ec)
view account details again but now without the '
![image](https://github.com/user-attachments/assets/bdd91921-9836-4e77-8585-0adb822e4676)
![image](https://github.com/user-attachments/assets/634842d3-10e5-409e-a49a-0a689f4c2121)
now type the right one but first take off the break
modify the request contents
![image](https://github.com/user-attachments/assets/d9cebca7-b9ab-4355-acf1-6dc74df929f4)
