### How to set Maven Specifi Version in linux
* Create an EC2 Instance and login to that machine .
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/a9b665cd-63bc-4d22-8beb-319a8534dae7)
* Update the all packages use the command `sudo apt update`
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/f705c756-f198-48c1-8058-d2546846a771)
* Now insatll JDK Version like 11,17,21
  `sudo apt install openjdk-17-jdk -y`
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/3869d2af-07d5-445f-b7c0-f2d881cc936f)
* Now Install maven specific version
  click here - https://maven.apache.org/download.cgi
* ![image](https://github.com/Gopi0527/Notes/assets/137286069/c27f5656-1571-47d6-802c-85f27ea1f8cf)
* Copy the url and go to linux machine
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/398d0307-02e2-49c2-a243-a6f6326d1e58)
* The file downloaded in tar file now untar the file
  ` tar -xvzf apache-maven-3.9.5-bin.tar.gz`
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/e1f20cee-6f7e-4af7-89f1-ad9b5b83a80e)
* Now untar the file
   ```sudo mkdir /opt/maven/
      sudo mv apache-maven-3.9.5 /opt/maven/
      sudo vi /etc/environment
      source /etc/environment```
  
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/c2e81434-9b2f-4715-9a2a-54ee6fe236d2)
   
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/f5debe29-8921-4a2f-9399-41db5efb9a85)
   
  ![image](https://github.com/Gopi0527/Notes/assets/137286069/e3de579b-11b7-433e-9702-bacac9ffde8c)




  
