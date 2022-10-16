# Admission Cell BOT

## About

### Problem Statement
To develop a BOT which can remove redundancy of admitted students and applied students from given files and append the total admitted and applied students’ available details in specific admitted and applied output files respectively. <br>
The aim of the BOT is also to remove a given mobile number from each given file as per the Admin's requirements.

### Proposed Solution
• The BOT will take input of different files namely Admitted, Application, Common, Walkin, Lead, Output Admitted and Output Applied Data Files.<br>
• It will remove redundancy of data from Application, Common, Walk-in and Lead Data Files based on Admitted Data File using mobile number and application number as      primary keys.<br>
• It will remove redundancy of data from Common, Walk-in and Lead Data Files Based on Application Data File using mobile number and application number as primary keys.<br>
• It will take input of a mobile number from admin and is capable of removing all of its occurrences from all 7 files in case the mobile number has stopped working and is uncontactable.<br>

### Modules
• Append Output and Remove Redundancy (Data)<br>
• Remove Not Required Mobile Numbers

### Flowchart
![alt text](https://i.ibb.co/bmggHGW/Picture1.png)

## Developers

#### Made with ❤️ by:
##### Dhruv Dixit : [Github](https://github.com/dhruvdixit06) [Linkedin](https://www.linkedin.com/in/dhruv-dixit/)
##### Dhreeti Kesharwani [Github](https://github.com/dhreeti414) [Linkedin](https://www.linkedin.com/in/dhreetikesharwani/)

## Instructions/Dependencies/Installation
1. Open Chrome or any other browser installed in your system. (If not, download the same)<br>
2. Goto URL : https://www.uipath.com/ <br>
3. Register yourself with the appropriate details.<br>
4. Sign-in and download UiPath Community Edition from the same.<br>
5. Run the downloaded UiPath Community Edition installation (exe) file and install with required details.<br>
6. After installation, open UiPath Community Edition.<br>
7. Click on Process given on the right side of the window.<br>
![alt text](https://i.ibb.co/nCm5XY3/1.png)<br>
8. When the dialog box for process opens, enter the name you want to give to your bot and the location you want it to work from.<br>
9. Click on Create.<br>
![alt text](https://i.ibb.co/BPJFyz6/2.png)<br>
10. Close UiPath.<br>
11. Now, open file explorer and paste all the project files in the location which contains the folder of your newly created process.<br>
![alt text](https://i.ibb.co/dLLgjDR/3.png)<br>
12. Open UiPath.<br>
13. Open the project you named (say, botathon).<br>
14. Click on Manage Packages.<br>
![alt text](https://i.ibb.co/2gvgnKs/4.png)<br>
15. Search BalaReva Excel and install both the packages as marked in the snapshot given.<br>
![alt text](https://i.ibb.co/gjvbCDL/5.png)<br>
16. Click on project panel given on the bottom-left side.<br>
![alt text](https://i.ibb.co/CVQZfYP/6.png)<br>
17. Now, click on Flowchart.xaml<br>
18. From Debug File, select Run File.<br>
![alt text](https://i.ibb.co/Y7xMXhd/7.png)<br>
19. From the panel shown select the option on which you want to work on: <br>
<b>Option 1</b>: This will remove redundancy of admitted data from all other files and append details in final output file and also for applied data from other files and append the details in final output for the same.<br>
<b>Option 2</b>: This will remove the given mobile number, if present, in any of the excel files. <br>
![alt text](https://i.ibb.co/tQdcyrQ/8.png)<br>
20. On selecting first option and clicking Ok, you have to provide all the 7 excel files one by one.<br>
![alt text](https://i.ibb.co/gVJK6PV/9.png)<br>
21. If second option is chosen, then, provide the mobile number in the window as shown below without putting +91 before any number and press Ok.<br>
![alt text](https://i.ibb.co/rddy0y8/10.png)<br>
22. Now, select all the seven files one-by-one through the selection windows like the one given below. Make sure to select the correct files which have been asked.<br>
![alt text](https://i.ibb.co/gVJK6PV/9.png)<br>
23. Now, let the bot do the work.<br>
24. After the operations have been finished check the files modified as output.

### NOTE
This project was created by TEAM DDDK (Dhruv Dixit [Leader] and Dhreeti Kesharwani) as a part of offline national level hackathon Botathon 2.0 conducted at JECRC University, Jaipur sponsored by UiPath based on Robotic Process Automation. We won 2nd prize representing our college United College of Engineering and Management, Praygraj, Uttar Pradesh among 136 teams participating from 17 states of India.
