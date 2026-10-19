# Ancora-Education-Ucertify-Lab68
# Part I: Command Line Tools

Command line tools are powerful utilities that allow users to interact with a computer's operating system through text-based commands. In this lab session, you will explore various command line tools and learn how to use them effectively. This lab session will cover several command line tools, namely, ping, ipconfig, and tracert.

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=11]

## Lab Objective 
This lab session demonstrates the steps involved in using the ping, ipconfig, and tracert commands in Windows PowerShell. Upon completion of this lab, you will be able to:
* Understand the purpose and usage of the ping, ipconfig, and tracert commands.
* Use the ping, ipconfig, and tracert commands to troubleshoot network problems.
* Understand the output of the ping, ipconfig, and tracert commands.
* Test the network connection between two devices using the ping command.
* Display the IP address configuration of a device using the ipconfig command.
* Trace the path between two devices on a network using the tracert command. Lab/Machine Environment You are provided with the Windows virtual machine.
## PART A: Analyzing Command Line Tools
Launch Windows PowerShell, execute ping, ipconfig, and tracert commands, and then analyze their results. Windows PowerShell is a powerful command-line shell and scripting language developed by Microsoft specifically for Windows operating systems. It provides a comprehensive set of administrative tools and capabilities for managing and automating system tasks.
### STEP 1
Click the Start menu and open Windows PowerShell. 
### STEP 2
Execute the following command to use ping to ping Google.com:
```bash
ping www.google.com
```
### Note 
Here, the Windows ping command is specifying only the target_name parameter and sends four ICMP echo messages to the specified target. 
### STEP 4
Execute the following command to show that the specified target address is unreachable:
```bash
ping 172.16.43.128
```
### STEP 5 
Execute the following command to use ipconfig without any parameters:
```bash
ipconfig
```
### STEP 6 
Execute the following command to show the use of ipconfig /all command:
```bash
ipconfig /all
```
### STEP 7 
Execute the following command to use tracert and to show the path taken by a packet on an IP network from a source to a destination:
```bash
tracert www.pearsonitcertification.com
```
### STEP 8 
Close all windows. 
## Lab Summary 
This lab session provides you with a straightforward and practical understanding of the ping, ipconfig, and tracert commands in Windows PowerShell. Here's a summary of what you have learned:
* The purpose and usage of the ping, ipconfig, and tracert commands.
*  How to use the ping, ipconfig, and tracert commands to troubleshoot network problems.
*  How to interpret the output of the ping, ipconfig, and tracert commands.
*  How to test the network connection between two devices using the ping command.
*   How to display the IP address configuration of a device using the ipconfig command.
*   How to trace the path between two devices on a network using the tracert command.

Now, you are equipped with the knowledge and skills to use ping, ipconfig, and tracert commands effectively to troubleshoot network problems.
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
