# Setting up a Windows 2022 Server machine

## Outline

In this guide, I will be showing you how to set up a Windows Server 2022 machine in Virtual Box. This is a machine I have been using a lot in my home labs recently, and has allowed me to experiment with and learn technologies, such as DNS and DHCP servers. Following along with this guide will show you how to set up a Windows Server 2022 machine in the Virtual Box environment. If you follow these installation instructions, you will also be able to install this software on a physical machine. 

This guide is intended for beginners, or those with a low technical knowledge, so they can install these machines as the need arises.

### Before you begin

There are some prerequisites before you create this virtual machine. you will need to have the following items:

* Oracle Virtual Box 7.1.12 installed on your machine (*This is the version I am using*)
* Virtualization enabled on your host machines (the computer you are running Virtual Box on) BIOS (*You can do this by pressing ESC, DEL, F2 or F10 when you turn on your computer, refer to your manafacturers documentation to find which key you require*)
* At least 10GB of space on your host machines hard drive

Lets get started with the first step, downloading the software to be installed.

### Downloading Windows Server 2022

* First search Windows Server 2022 in your search engine
![search for software](/screenshots/1.png)
* Locate the download link on the page
![locate the link](/screenshots/2.png)
* Complete the form to register
![complete the form](/screenshots/3.png)
* Select the format you would like your download in (*in this case you require the ISO*) and language
![selected format](/screenshots/4.png)
* Your download will begin (*make sure to take note of where the system is saving this file*)
![download begins](/screenshots/5.png)

This file is very large, and will take a while to download, while this download is completing, lets set up the virtual machine. 

### Setting up the Virtual Box Machine

* Select the machine option in the navigation bar, in the top left corner
* Select the option 'New' to start the new machine creation wizard
![create new machine](/screenshots/6.png)
* Name the new machine
* Select the type and version of the machine you are creating
![name the machine](/screenshots/7.png)
* Select the amount of RAM to assign to the virtual machine
* Select the number of CPU cores to assign to the virtual machine
![selecting virtual components](/screenshots/8.png)
* Create the virtual hard disk for the system

Now we have created the virtual machine, we will begin to install the software we downloaded, on our newly created virtual machine!

### Installing Windows Server 2022

![create the virtual disk](/screenshots/9.png)
* Start the virtual machine
![start the virtual machine](/screenshots/10.png)
* A pop up will appear
![pop up](/screenshots/11.png)
* Select the right hand drop down arrow, and the 'Other' option to open the file manager
![open file manager](/screenshots/12.png)
* Select the Windows Server 2022 ISO file
![select the ISO](/screenshots/13.png)
* Select mount and reboot, to reboot the system and load the Windows Server 2022 installer
![mount and reboot](/screenshots/14.png)
* Your machine should boot and display the Windows logo
![windows logo](/screenshots/15.png)
* Select your language
* Select your time and currency format
* Select your keyboard and input method language
![selecting language, region, and input](/screenshots/16.png)
* Click the 'Install now' button to begin the install
![install now](/screenshots/17.png)
* Select the version of the software you would like to install
![select the edition](/screenshots/18.png)
* Read and agree to Windows terms and conditions
![read Ts and Cs](/screenshots/19.png)
* Select the type of installation you require
![select install type](/screenshots/20.png)
* Select the drive to install the software on
![select the drive](/screenshots/21.png)
* Your software will begin to install
![software begins to install](/screenshots/22.png)
* Restart your system after the install has completed
![reboot the system](/screenshots/23.png)
* Your machine will reboot, and the software will run
![software will begin to run](/screenshots/24.png)
* Set up your local administator account, create a secure password and make note of it
![setting up local adminstrator account](/screenshots/25.png)
* Log in to your newly created local administrator account
![login with admin account](/screenshots/26.png)
* Your machine will open up server manager once you have booted it
![server manager](/screenshots/27.png)
* Your operating system has been successfully installed
![successfully installed system](/screenshots/28.png)

You have successfully installed Windows Server 2022 on your virtual machine, now you can begin assigning this server roles in order for it to complete tasks on your network.

### Frequently asked questions

*Do I need to complete the form when downloading the software?*

The software we are using in this guide is under an **evaluation license** this gives us full access to the software for educational and testing purposes for 180 days. You have to submit this data in order dor Microsoft to assign you this type of license, so you are not using this software illegally

*Why have you assigned that amount of RAM and CPUs to this system?*

On the page we found the download link for the software, we can find the recommend requires for a system running this software. Here, they recommend at least 4GBs of RAM and 2 CPU cores, so I assigned this to the virtual machine

*Why did you select the desktop version of the software to install?* 

As this guide is intended for beginners, I wanted to set up the most beginner friendly environment possible. So I selected this version of the software, as you get a desktop environment that resembles a desktop computer the most. 

*What is a local administrator account?*

A local administrator account is the account of the machine with the highest level of permissions. With this level of permission, you can do pretty much anything you want on this machine, however, you only have these permissions on the machine you have set this account up on.

*How do I know if I have a secure password?*

Having a secure password is integeral, especially if you have an account at the administrator level. You can ensure you have a strong and secure password by following these steps:

* Having a mix of uppercase and lowercase letters in your password
* Having numbers in your password
* Having symbols in your password
* Not using easily guessable number in your password, such as 1234, 0000, or your birthday
* Avoid using thing that are easily discoverable about you, such as your name, your pets names, your family names, or you favourite tv shows/films
* Avoid repeating passwords across different accounts

If you follow these guidelines, you will be able to come up with a strong a secure password for your accounts 
