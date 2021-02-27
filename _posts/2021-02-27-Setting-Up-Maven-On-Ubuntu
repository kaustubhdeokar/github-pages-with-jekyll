---
title: "Setting-Up-Maven-On-Ubuntu"
date: 2021-02-27
---
Setting Up Maven On Ubuntu

check - java installed. 
install .tar.gz file from apache.org.
unzip file by the command tar -xzf <folder-name> (use sudo if permission failure)

check java_home path is already setup. 
	if not then navigate to the home directory (cd ~) & type the following commands in the terminal.
	1.nano .bash_profile (or use any editor of your choice)
	2.export JAVA_HOME='/usr/lib/jvm/java-11-openjdk-amd64/bin/java'
	3.export CATALINA='/opt/tomcat' (it's the upper directory of the tomcat installation)
	4.export PATH=$PATH:$CATALINA_HOME:$JAVA_HOME
	
reopen the terminal or type the command <source .bash_profile>

now to open the tomcat -> 
	go to /opt/tomcat
	run the command-> sudo bin/startup.sh
	stop tomcat    -> sudo bin/shutdown.sh
	
	
