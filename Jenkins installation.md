# Jenkins Installation on Ubuntu
- curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
- echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
- sudo apt-get update
- sudo apt-get install jenkins

## Jenkins Installation Error
![alt text](Jenkinserror.png)
### Follow these steps
1. curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
2. echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
3. sudo apt-get update
4. sudo apt-get install fontconfig openjdk-11-jre
5. sudo apt-get install jenkins



## **Sudo Systemctl Status Jenkins**
![alt text](sys.png)

## **Retreive Password**

![alt text](Jenkinsgui.PNG)


### Localhost:8080
