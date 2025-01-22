# what is jenkins?

Jenkins is an open-source automation server widely used for continuous integration (CI) and continuous delivery/deployment (CD) in software development. It helps developers automate tasks related to building, testing, and deploying applications, enabling faster and more reliable delivery of software.

# features of jenkins:
1. Open-Source: Free to use with an active and supportive community.
2. Extensibility: Supports a wide range of plugins for different tools and technologies.
3. Cross-Platform: Runs on multiple platforms, including Windows, macOS, and Linux.
4. Easy Installation: Simple to set up and configure.
5. Scalability: Can be scaled using master-slave architecture to distribute workloads.
6. Customization: Supports scripting for custom workflows using Groovy or other languages.

Step by step process of installing jenkins on AWSInstance
. AWS EC2 Instance

 ->Go to AWS Console

 ->Instances(running)
 
 ->Launch instances

![Screenshot (29)](https://github.com/user-attachments/assets/e71a3dfb-79cc-44c3-9cd7-8e5da0e4315f)

![Screenshot (30)](https://github.com/user-attachments/assets/b1917589-2192-4ad9-91d6-14d9d6f45c14)

![Screenshot (31)](https://github.com/user-attachments/assets/08ae1a4e-e392-4c27-b4f8-c0e1ea693dc5)

![image](https://github.com/user-attachments/assets/94732256-f48c-4544-90e5-6c2613766e03)

Go to security groups and Edit inbound rules

![image](https://github.com/user-attachments/assets/b4aa70e3-a275-4324-add0-11eaf607f55b)

![image](https://github.com/user-attachments/assets/8eab7198-117d-4862-9cd9-fe67ee2fb364)

![image](https://github.com/user-attachments/assets/6ce5dad5-829d-41ee-a665-fc220aaf5ea6)

click on save changes

![image](https://github.com/user-attachments/assets/94732256-f48c-4544-90e5-6c2613766e03)

select the instance and click on connect

![image](https://github.com/user-attachments/assets/5216ed73-a182-4983-a664-aa269ffcc007)

 To install jenkins and java
https://www.jenkins.io/doc/book/installing/linux/#debianubuntu

![WhatsApp Image 2025-01-22 at 12 43 52 PM](https://github.com/user-attachments/assets/2c221bc5-1417-4091-8e55-9d1b8d4c20fd)

![WhatsApp Image 2025-01-22 at 12 42 42 PM](https://github.com/user-attachments/assets/649c309b-14c3-412f-b2b8-0de47a6bf716)

![WhatsApp Image 2025-01-22 at 1 00 27 PM](https://github.com/user-attachments/assets/0e792492-ce33-49dc-8c2c-047df83fee38) 

![image](https://github.com/user-attachments/assets/5216ed73-a182-4983-a664-aa269ffcc007)

copy the publiIP and paste it in new tab with port number 8080 (ex:34.238.118.90:8080)

![image](https://github.com/user-attachments/assets/23abfd1f-5c93-4293-b4b0-c6df5fb5ef97)

copy the permission(/var/lib/jenkins/secrets/initialAdminPassword) and paste it in teminal with the command sudo cat permission(/var/lib/jenkins/secrets/initialAdminPassword)
then we will get a password copy it and paste it.


![image](https://github.com/user-attachments/assets/68e2b6dc-275e-4853-912f-b3a40e027243)

![image](https://github.com/user-attachments/assets/4f5dce2f-7574-4ba8-ad9a-8eafdf1c645b)

![image](https://github.com/user-attachments/assets/9a86f028-a4e2-4b13-a354-010d0d755cea)

![image](https://github.com/user-attachments/assets/813080bf-cee7-4dce-8680-4d6fe20b59fa)

fill the details click on save and continue 

![image](https://github.com/user-attachments/assets/17a640f6-806b-4dc0-975b-39f95f50a484)

![image](https://github.com/user-attachments/assets/78c263ba-7681-4ff6-ac86-06e5789f78a5)

![image](https://github.com/user-attachments/assets/9d46666e-dd5d-493e-ae08-c9d1302a5508)














