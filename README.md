# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212222040067
Name: KABIL S
```
## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![1](https://github.com/user-attachments/assets/10add262-8722-4fe7-b8a0-931df7a15cdc)



sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-21 212801](https://github.com/user-attachments/assets/79402cc1-d39f-44d0-9d55-c9cdd5bfe340)




The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2025-04-21 212824](https://github.com/user-attachments/assets/e26f1f0b-a8d4-4773-8956-937f9e483447)





The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2025-04-21 212853](https://github.com/user-attachments/assets/11842ded-dffc-460d-9fc6-c6d7ace3f033)





It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2025-04-21 212922](https://github.com/user-attachments/assets/8d06d719-e41b-4774-9e32-e42d2252dc6f)




It shows the following screen in which the option Google can be selected:

![Screenshot 2025-04-21 212939](https://github.com/user-attachments/assets/0e4b4ccf-5faf-4c4d-8ae7-d1d7db24b379)





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


In windows IE, on giving the url http://192.168.89.30 , the fake Google page is displayed. The victim can enter the username and password

![VirtualBox_kali-linux-2024 4-virtualbox-amd64_21_04_2025_21_21_38](https://github.com/user-attachments/assets/8ef376eb-623f-4a25-a6bf-48a611a1049d)




SET logs the information regarding the Google credentials:

![Screenshot 2025-04-21 213015](https://github.com/user-attachments/assets/0cf48fbb-9b9f-4e4a-b761-efafad0129b3)




SET logs the information in the xml file under /root/.set directory:

![Screenshot 2025-04-21 213023](https://github.com/user-attachments/assets/db44cb21-ed4c-4d62-94b1-5139e763852d)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
