VSE_CA1
---

## SECTION 1 : PROJECT TITLE
Project Title

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
In this assignment, we attempted to efficiently detect objects in an image while simultaneously generating a high-quality segmentation mask for each instance. 
The method adopted is the Mask R-CNN. It is a deep neural network aimed to solve semantic segmentation problem in machine learning or computer vision. There are two stages of Mask RCNN. 
First, it generates proposals about the regions where there might be an object based on the input image. Second, it predicts the class of the object, refines the bounding box and generates a mask in pixel level of the object based on the first stage proposal.  

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | 
| :------------ |:---------------:| 
| IAN TAN ENG KIONG | A0120534W | 
| KHOO WEE BENG | A0195308Y | 



---
## SECTION 4 : USE CASE DEMO

[![AMAB](https://i9.ytimg.com/vi/lwk6KzagxJo/mq1.jpg?sqp=CLTkxOcF&rs=AOn4CLAwjj2kbTRT1l9Hwnkfjqn4s7e_1Q)](https://youtu.be/lwk6KzagxJo "AMAB")

---
## SECTION 5 : USER GUIDE
### [ 1 ] To run the system using iss-vm

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> open terminal in iss-vm

> $ git clone https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB.git

### as there is an existing npm of lower version, upgrade npm with the following instructions

> open terminal in iss-vm

> $ sudo npm cache clean -f

> $ sudo npm install -g n

> $ sudo n stable

### find folder installed for new npm
### usually during mkdir e.g. “/usr/local/n/versions/node/10.16.0/bin”
### symlink nodejs to /usr/bin/node

> ln -s /usr/local/n/versions/node/10.16.0/bin /usr/bin/node

### if link exists, 'unlink /usr/bin/node' first than execute the command above

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> unzip dialogflow-web-v2.zip into dialogflow-web-v2 folder

> go to terminal

> $ cd IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/dialogflow-web-v2/

> $ npm install

> $ npm run dev

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> **open iss.html in Chrome

### [ 2 ] To run the system in other/local machine:
### Install npm, get latest nodejs n npm

> $ sudo apt-get update

> $ sudo apt-get install npm 

> $ git clone https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB.git

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> unzip dialogflow-web-v2.zip into dialogflow-web-v2 folder

> go to terminal

> $ cd IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/dialogflow-web-v2/

> $ npm install

> $ npm run dev

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> **open iss.html in Chrome

---
## SECTION 6 : PROJECT REPORT / PAPER

amab.pdf
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/ProjectReport/amab.pdf>

---
## SECTION 7 : MISCELLANEOUS

ChatBot.xlsx
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/Miscellaneous/ChatBot.xlsx>

---
