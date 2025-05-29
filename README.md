# Creating-and-Programmatically-Remediating-Vulnerabilities-on-Windows
Running a VM scan on windows. creating vulnerabilities 

# Introduction

In this project, I set up a virtual machine in Azure and configure Nessus Essentials to perform basic & credentialed vulnerability scans against Windows 10 Hosts. During this process I follow the 6 Main Stages Of The Vulnerability Management Process (Discover, Prioritize, Assess, Report, Remediate, Verify) throughout each stage of scans. I should have a list of vulnerabilities in both basic and authenticated scan. 

Also,I disabled the firewall in the VM for the Windows 10 machine & verified connections from my host machine to make sure we get efficient results

![image](https://github.com/user-attachments/assets/f2cbefe3-99ec-40d5-8ee1-55b6b05664ff)

# Preparation

First, im going to start off with creating a VM in azure. Making sure i have the right login credentials. 

![image](https://github.com/user-attachments/assets/ee6fc12a-27f8-4643-8d2c-18132c99d891)

after the creation of the VM, i'm going to create a basic scan through nessus. 

![image](https://github.com/user-attachments/assets/c2044675-608e-402d-ab62-c7b0d09d6e83)

run a scan and see what the results are. 

![image](https://github.com/user-attachments/assets/d628614f-8a52-48d0-94a7-ca9405dffd4c)

# Rating the 1st Scan (Initial Settings)

After runnung a basic scan we can see that there are a numerous amount of vulnerabilities in the nessus portal. One of the vulnerabilities is Microsoft Windows SMB Shares Access which the The remote has one or more Windows shares that can be accessed through the network with the given credentials. Depending on the share rights, it may allow an attacker to read / write confidential data.

![image](https://github.com/user-attachments/assets/58838d10-b1f2-4ae5-9dfa-0577d8899639)

Another Vulnerability 

![image](https://github.com/user-attachments/assets/db7ae782-cc47-4875-a408-cb68da33b916)


# Ratings After 2nd Scan (Credentialed)

After running our second scan, we can definitely see an uptick in higher vulnerabilities being present in our Windows 10 network now.

![image](https://github.com/user-attachments/assets/bd354896-9d7f-41d0-94ed-4c6f80e0f0fa)


Another vulnerability is an old version of firefox is one of the highest vulnerabilities 

![image](https://github.com/user-attachments/assets/8c3c0d05-d2fe-4936-b63d-87e1fb758d0e)











