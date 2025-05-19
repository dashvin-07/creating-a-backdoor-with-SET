```
NAME : DASHVIN S
REG NO : 212224100008
DEPT : CYBER SECURITY

```


# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

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

## OUTPUT :

![image](https://github.com/user-attachments/assets/f2a4f3e3-faf6-4ec7-82a3-c0e25921d180)

### The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT :

![image](https://github.com/user-attachments/assets/400e321c-a51d-4802-b8b7-4818ed4b693d)


### It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT :


![image](https://github.com/user-attachments/assets/646de069-ff89-4ca5-9487-b9f39a6111f6)


### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/607fd7db-d3cf-43c1-a933-59e342098c63)


### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT :
![image](https://github.com/user-attachments/assets/ab4148ce-d531-4616-8794-120e7a913bcf)

### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT :

![image](https://github.com/user-attachments/assets/d19e4c33-bcf3-4921-a4a3-47be0bda29ee)


### It shows the following screen in which the option Google can be selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/76869338-b77b-47fc-8ac2-b9f562e39d8b)


### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT :

![image](https://github.com/user-attachments/assets/67ff7353-8ec2-4e77-a5af-fcefdf6da934)


### In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT :

![Screenshot 2025-05-09 185233](https://github.com/user-attachments/assets/3961ec97-c9a2-49e9-9ec8-099355564d38)



### SET logs the information regarding the Google credentials:
## OUTPUT :
![image](https://github.com/user-attachments/assets/a205b897-1451-46fa-96fb-370d66177549)

### SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/e4185655-a22b-4b48-bb6c-3276cfdc635f)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
