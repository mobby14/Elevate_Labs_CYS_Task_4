# Firewall and its functions
Configuring the firewall to add rules to allow and block traffic.

## What is firewall?
- Firewall as its name implies it blocks the malicious traffic which could harm your system and prevent from hackers that target your data.

## How to add rules in firewall?
- Open Windows Firewall or realted software in its respective OS.
- Then you can see following window:
  ![Window from Windows Firewall](https://github.com/mobby14/Elevate_Labs_CYS_Task_4/blob/main/EL_LABS_FIREWALL.PNG)
- There will be two types of rules:
  - Inbound Rules
  - Outbound Rules  
- There you see Add Rule button, click to add rule for your firewall.
  - You need to Rule type which you need to implement.[For example, I want to create rule to block inbound for telent in port 23 so I choose Port.]
  - The, You find the correspinding submenu for that menu. [In my case , I got protocols and port]
  - Next you need to find Action, there you need to choose whether Allow , Allow if it is secured , Block [I choose Block].
  - Then you need to choose profile ie Public, Private or Domain. [I choose all]
  - Then you need to name the rule.Click Finish.

## Verification:

To check whether my rule is working properly,
Before that check whether you enabled Telnet Client in your system.
- You can activate by running optionalfeatures.exe in Run and check the TelentClient.
    - Open CMD
    - Type, telnet <Your ip> 23
### Results
- If you got blank screen then the connection is successful but the rule you placed is failed to block this conenction,
- If you got this following message then the connection is failed and the rule is working properly.
 ![CMD output](path/to/image.jpg)
  
