Gladys Ramotadima
Computer-Architecture & System
Assesment 2 Project

 
Introduction

The purpose of this report is to give a description of Virtualisation and the VM Virtual Box. 
Secondly it is to address the issues of configuration and deployment of the virtual machine by outlining the 
steps involved and an explanation of settings and configuration selected or used. It will continue explaining what 
a web server is and what Apache is. Furthermore the setup and configuration of Apache webserver will be taken into practice
and the steps involved will be outlined. After the completion of the project reflections will be noted.
Finally it will summarise reflections of these projects and why they can be important for the future. 

Virtualisation & VM Virtual Box Descriptive

Helmick (2016) describes virtualisation as the creation of a virtual rather than an actual version of something,
such as an operating system, a server, a storage device or network resources.Virtual Box, according to Colvin (2015), provides a platform 
for a cross-platform virtualization. He further stated that it can be installed on any of the operating systems which are used by the users and that there is a version for each of these operating systems. While Visual Machine VM, according to Oracle manual, is the special environment that Virtual Box creates for guest operating system while is running.

Configuration and Development of the Virtual Machine

Outlined below is the step followed when configuring the development of virtual Machine
	First the Ubuntu server is downloaded
-	Copy taken from the lecture, scrolled down and downloaded 32.bitPC(i386
	Boot the system from the CD-ROM drive, creating the virtual to hoist Ubuntu server
-	Name and operating system appear and the following were labelled:
-Named-Gladys
      -Type Linux
      -Ubuntu(32-bit)
Memory size given 2048mb

	Step 1 Ubuntu server is  installed, and boot section
-	The language English is chosen following the appropriate steps. Carefully selected number to detect the keyboard.
-	Hoist name for the system is  registered as : Web-server
-	Then registered name of new user as :’Gladys’ then confirmed password
- Time zone was selected as Dublin in Europe

	Step 2 Several options were considered for the hard drive layout
-	Guided partition was chosen and the volume of the entire disk. The process took 15minutes.
-	The system was installed, packages, installing security updates and standard system.
	Step 3 Then formed to next step to install Grub boots
-	While the system was running I installed guides. GitHub  Hello world to act as introduction
-	Under these I learned about creating and use repository
-	Make changes to a file and push them to GitHub as comment’s
	Step 4 The Ubuntu system is then installed
	and all other things were prepared to submitted report

Explanation of what Apache is and a Webserver

According to the virtualization report a webserver is a software that listens for requests and returns data. It stated that when typing “www.mysite.com”, the request is forwarded to a machine running web server software which returns a file back to the browser which might make  a further request based on HTML content.
Apache is described as a webserver program that comes with and is configured on most of the systems. According to Laurie B, & Laurie P, (2000) it is a program that runs under suitable multitasking operating, stating examples as Unix and windows 95/98/2000/Me and NT.

Outlining the steps involved in setting up configuration of Apache webserver
Continuation of the project process continues from the previous installation of configuration and development  virtual machine which was installation of Ubuntu.

	Step 1 Previous  password used and sudo apt-get install apache2 apache2-utils is installed
-	The process did not start straight away as I encountered problems I have to restart again
-	Settings changed to Apache 2 webserver started up at system boot 2, command below is installed sudo system enable apache 2
-	Problems arises as the current part forwarding rules were not valid, none of the host or guest part values may be at zero

	Step 2 under Host part and Gurst part I typed 80
-	Or another option I clicked back on icon Gladys Ubuntu then typed http//local host: 80 browse then new tab appeared: Webserver Ubuntu appeared on screen

	Step 3 Installing MySQL
- The following command is used : sudo-apt-get install mysgl-client mysgl server
- Followed by sudo mysql-secure-installation
-	New password created for MYSQL root then reloaded

	Step 4 PHP installed and modules
-It was stated that this is an open server side scripting language mainly used for web development, which allows web developers to create dynamic interactive websites
- Command sudo apt-get install ph7.0 ph7.mysql libapache2-mod-php7.0 php7.0 php7.0-cgi php7.0-gd installed
- After running the system PHP was tested to check if it was working
- By creating info-php file in /var/www/html director
- Then the file was created

Reflections on the virtualisation and website

I learned that creating a website was not that easy is but it was fun and takes some time. I realised that having the knowledge and IT skills can help me in the future to create my own website and thus help me promote my business or services. I can choose to be a web programmer or designer. To know that there are specific languages in a computer was a new thing to me and was quite interesting. I made some errors such as typing and wrong commands and realised that the programme cannot allow me to do what I have to do if there were errors. So I have to go back and correct that.

Reflection on virtualisation, I realise that this is an important issue in IT, especially when it comes to power consumption. I attained the skills that it provides high availability for critical operations, streamlines and application deployment. Burger (1987) stated that IT specialists are always on the lookout for the latest technologies that allow businesses to run with fewer resource’s while providing the infrastructure to meet todays future customer’s needs. 

According to the virtualisation report prepared by Bakersfield College (1987) virtualisation is immediately compelling when applied to server consolidation or server containment strategies, which they stated has shown good advantages like that of customers discovering that running virtual infrastrure can help improve services levels and availability. I found this to be a good advantage and beneficial too. Giving example that because virtual machine is encapsulated its configuration and state information can easily be captured and migrated. Virtual disks are literally files that can be backed up and restored quickly for disastrous recovery purposes. Therefore virtualisation is crucial to the future of information technology.

Conclusion

After learning about the two systems I realised that computers and IT has become so essential in our daily lives. I now cannot imagine life without a computer as they are used in businesses, homes and offices. It shows that people are focused on the future of computers. 

REFERENCES

Harry Colvin (2015)Ultimate Guide Book on Virtualisation with Virtual Box 
https://www.amazon.com/dp/B015OKXXLI/ref=rdr_kindle_ext_tmb#reader_B015OKXXLI retrieved 1/March/2017


Oracle VM Virtual Box User Manual 2004-2016 Oracle Corporation
Available: http://download.virtualbox.org/virtualbox/5.1.4/UserManual.pdf Retrieved 1/March/2017

Laurie, B and Laurie P  (2002 ) Apache: The definitive guide 3rd Edition 
Available: https://www.amazon.com/Apache-Definitive-Guide-Ben-Laurie/Accessed 25/April/2017

Jason Helmick (2016) Definition of Virtualization:  SearchServerVirtualization.com. Available : http://searchservervirtualization.techtarget.com/definition/virtualization Accessed:4/April/201

Virtualisazition Assessment  Report : Server Consolidation and Server Containment Through Virtualization : Prepared  Bakersfield College 

Thomas Burger W (1987) 
Available: https://software.intel.com/en-us/articles/the-advantages-of-using-virtualization-technology-in-the-enterprise : Accessed 25/April/2017


