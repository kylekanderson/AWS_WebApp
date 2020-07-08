## Description

For this assignment, you have been asked by your boss to roll out a new web application using an EC2 instance in AWS. This instance will be running an updated web application that has been modified by you. You will need to download the helloworld.js and helloworld.conf files (located below). Once downloaded, you will modify the helloworld.js file to display a different message other than "Hello World" when customers visit your website. Like in our demo, you will need to create a security group that allows you to SSH into the machine and you will need to configure a specified port to allow access to your web server.  Below are all the requirements for this assignment.

### Requirements

**[90 pts] Build your own custom web application**

- [x] [10 pts] Download both of the files [helloworld.js ](https://maryville.instructure.com/courses/46481/files/7969028/download?wrap=1)and [helloworld.conf](https://maryville.instructure.com/courses/46481/files/8104598/download?wrap=1)

- [x] Modify the helloworld.js file to display a new message.

- HINT: The text that you will modify in the JS file is located on line 11 ('Hello World\n'), like in python the \n indicates to go to the next line.

- [ ] Create a new Github repository and upload the two updated helloworld files.

- [ ] You will turn in the link to your Github repository.

- [ ] [5 pts] Find the AMI instance type ID.

- Requirements:

  - Amazon Linux AMI
  - x86_64 bit
  - Virtaulize Type HVM
  - Has GP2 support

  - [ ] Save the instance type ID, you will turn this in.

- [ ] [5 pts] Find the ID of your Default VPC.

- [ ] You will submit the ID of your VPC as part of your homework assignment.

- [ ] [10 pts] Create a Security Group for your EC2 instance and your VPC.

- [ ] I want you to name your Security Group "Week2HW" and give it a description of "Week 2 Homework"

- [ ] I want the following ports to be open in the new Security Group

- Port 22 - SSH
- Port 3333 - Web Application

- [ ] [5 pts] Create an SSH Key Pair for your EC2 instance.

- This SSH Key Pair will be submitted as part of the assignment.

- [ ] [10 pts] Create the EC2 instance.

- - You will submit the instance ID of your new EC2 instance.

- [ ] [5 pts] Find the public DNS or IP address for your new EC2 instance.

- You will submit either one as part of the assignment.
  - [ ] Connect to your new EC2 instance and install all of the OS updates.

- [ ] [10 pts] Install Node.js.

- [ ] [10 pts] Using your own Github repository, upload your new web application.js file.

- [ ] [10 pts] Configure Node.js to run as a service, so your web application can run all of the time.

- [ ] [10 pts] Answer the questions in the turn-in section when you submit your assignment.

### Turn in

1. Web address for your Github repository containing the modified helloworld.js file
2. AMI instance ID
3. VPC ID
4. Security Group ID
5. Attach your SSH Key Pair to your assignment submission (Do not store this in your Github account)
6. The instance ID for your new EC2 web server
7. Public DNS or IP address of your new EC2 web server.
8. Answers to the following questions:
   1. How many hours do you estimate that you used in completing this assignment?
   2. What was the most straightforward part of any task for you?
   3. Describe the most frustrating technical challenge you encountered, and how you overcame it.
   4. What one part, of the technologies used in this task, would you like to learn more about?
   5. If you could have one magic piece of documentation that would make this assignment easier, what would it tell you how to do?