# maven

## Intro:

* Maven is a software project management and build automation tool commonly used in Java projects.
* It simplifies the process of managing a project's build, dependencies, and documentation. 
* Maven's primary goal is to make the build process easy, providing a uniform way to manage projects and their dependencies.
* Maven is highly extensible through plugins.
* It is widely adopted in the software development community for its ability to simplify and standardize the build process.
 
 ## Version:

*  Now lets try to install the latest version of maven which is apache maven 3.9.8

### Instalation steps:

* first lets try to install latest version of maven by wget command 


"wget https://dlcdn.apache.org/maven/maven-3/3.9.8/binaries/apache-maven-3.9.8-bin.tar.gz"


* Now lets extract our downloaded file by command


 sudo tar -xvzf apache-maven-3.9.8-bin.tar.gz -C /opt


### set up of environment variable

* now lets open the ".bashrc" file in our home directory to set 
up Maven`s environment variables by using command


nano ~/.bashrc

at the end of the file add the folloing line 
       export M2_HOME=/opt/maven
       export PATH=$M2_HOME/bin:$PATH

save and close the file.

* now lets apply the changes by command


source ~/.bashrc


* alt last lets verify the installation by using command 

mvn -version









