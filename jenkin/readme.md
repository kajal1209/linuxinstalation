# Jenkin

## Intro

* Jenkins is an open-source automation server that is widely used for continuous integration (CI)
and continuous delivery (CD) in software development.
* It helps automate the parts of software development related to building, testing, and deploying, facilitating a DevOps culture.
* Jenkins is highly extensible with a large ecosystem of plugins.
* Jenkins supports defining build pipelines as code using a DSL (Domain-Specific Language). 
* Jenkins can distribute build and test loads to multiple machines (called nodes), allowing for efficient resource usage and faster build times.
* Jenkins is an essential tool in modern DevOps practices, enabling teams to deliver software faster and more reliably by automating many
aspects of the development lifecycle.

### Installation steps 

* first,lets try to ensure that our system is update by command 
---
sudo apt-get update
---

* for installation of jekin java is required. Try to ensure that the java is installed 
in our machine by using command 
---
java -version
---

* now lets try to install jenkin by wget command
---
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
---

* lets try to add 
---
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
---

* lets instal the jenkin by using apt
---
sudo apt-get install jenkins
---

* enable the jenkin service to start at boot with command 
---
sudo systemctl enable jenkins
---

*  lets start the Jenkins service with the command
---
sudo systemctl start jenkins
---

* we know that Jenkins runs on port 8080 by default.
So lets try to quick check jenkin is running correctly or not .
* now first Open your web browser and go to seach bar
and search by using command 
---
http://ip address:8080


