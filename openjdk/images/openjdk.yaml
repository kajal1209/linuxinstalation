# openjdk

##Intro 

 * Openjdk(open java development kit) is an open-source implementation of java platform.
 * This is a java application which provides to the developer a reliable and free way to run.

 ###Version

* now lets try to install openjdk of version 17.0.12 

## Instalation steps

* First login into ubuntu machine with the help of ip address
* Then try to update the apt by command 
---
"sudo apt-get update"
---
!![Alt text](C:\Users\HP\OneDrive\Pictures\Screenshots.png)
* then search the new version of openjdk by command
---
 "sudo apt search openjdk"
---
* Then lets get the information of opendjdk-17-jdk by command
---
  " sudo apt info openjdk-17-jdk"
---
* Now lets download the latest archieve by using the wget command
---
sudo wget https://download.java.net/java/GA/jdk17.0.2/dfd4a8d0985749f896bed50d7138ee7f/8/GPL/openjdk-17.0.2_linux-x64_bin.tar.gz

---
* then lets extract our downloaded file with command  
---
sudo tar xvf openjdk-17.0.2_linux-x64_bin.tar.gz
---
* then lets move our extracted file to the /opt directory
---
 sudo mv jdk-17.0.2 /opt/
---
### Configuring java environmental path on ubuntu 20.04

* at this point we need to configure the java 17 home path on ubuntu 
 20.04 by using command 
---
sudo tee /etc/profile.d/jdk17.sh <<EOF
export JAVA_HOME=/opt/jdk-17.0.2
export PATH=\$PATH:\$JAVA_HOME/bin
EOF
---
* now lets source our file by using command
---
source /etc/profile.d/jdk17.sh
---
* at last lest try to verify our java home path by command 
---
echo $JAVA_HOME
---
we can verify our java instalation by checking its version 
---
java -version






