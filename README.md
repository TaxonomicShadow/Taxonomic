Table of Contents
=================
  * [Introduction](#introduction)
  * [Project Value](#project-value)
  * [Client Expectation](#client-expectation)
  * [Road Map and System Diagram](#road-map-and-system-diagram)
  * [User Story Map](#user-story-map)
  * [Milestones](#milestones)
  * [Schedule](#schedule)
  * [Progress](#progress)
  * [Risk Management](#risk-management)
  * [Team Member Roles and Activities in Delivery Process](#team-member-roles-and-activities-in-delivery-process)
  * [Communiaction Tools](#communication-tools)
  * [Development Environment](#development-environment)
  * [Development Tools](#development-tools)
  * [Decision Make Procedures](#decision-make-procedures)
  * [Meeting Agenda](#meeting-agenda)
  * [Other Resources](#other-resources)
## Introduction
Our project aims to automate taxonomic data capture from scientific reports, something which is currently performed manually. This information can then be uploaded to searchable databases where it can be accessed by the public. Automating this process will save our client time, effort and money which can be better spent elsewhere.
# ![Diagram](Resources/concept_diagram.jpg)
## Project Value
Our project has high academic and economic value. The project will help our clients improve their data collection efficiency, which can save a lot of time for them. Also, the project output software is working on automatic data collection. Therefore, they can reduce labor consumption and save a lot of money. In addition, this project is working for an open source academic website, the success of our project will help many people improve their data searching speed on this web site.
## Value delivered to the client
- Investigate and study on existing studies and projects of extracting information, xml tags (Golden Gate).
- Build a roadmap to show what we will deliver at each development stage.
- Extract information from tagged xml articles on ZooBank.
- Do research on extracting information from untagged articles and make a design to solve it. .
- Be able to convert untagged articles into xml format by using GoldenGate or other possible tools.
- Extract information from tagged xml articles which are transformed by GoldenGate.
- Output the information in the format of standard xml, which is convenient for integrated with clients’ datab	ases.
- Build a user interface for input and output display with human-editability function.
- Finalize the web-based APP platform.

## Client Expectation
The client expects us to achieve some sort of functionality in terms of analysing documents in pdf form and returning scientific names present. At this point the client's expectations are not entirely clear and we intend to work with them to develop a concrete idea of what we are supposed to achieve with our project over the course of this week.
## Road Map and System Diagram
# ![Diagram](Resources/roadmap.jpg)
# ![Diagram](Resources/BackEndFlow.png)
## User Story Map
# ![Diagram](Resources/usm.png)
## Milestones
- Functional webclient interface
- Enable uploading pdfs and viewing them as plain text in sub-window
- Enable customising extractable tags
- Implement automated IBRA7 region calculation
- Successfully use GoldenGate to tag pdfs
- Analyse and maximise the success rate of GoldenGate’s tagging
- Analyse and maximise the success rate of tag extraction
- Propose XML schema which will allow trivial data extraction

## Schedule
Week 6:
- Finalise higher level documentation (schedule, roles, milestones, audit ppt)
- Prepare for audit

Teaching break week 1:
- Thoroughly investigate GoldenGate
- Inquire about getting a web server set up with the ANU
- Create lower level documentation, ie. pseudocode, overall program structure, algorithms and testing plan
- Begin to design UI.

Teaching break week 2: 
- Complete development on basic interface, xml tag extraction and IBRA classification
- Complete basic UI
- Begin working on integrating GoldenGate with the server
- Prepare for audit

Week 7-8:
- Continue Work on implementing GoldenGate interpreting of PDF files server-side (backend)
- Create tools which allow the user to test the validity of output and fix it if necessary (frontend)
- Try to implement audit feedback

Week 9:
- Create project poster
- Meet with client and get feedback regarding program interface
- Work to improve efficiency and accuracy of data classification and extraction

Week 10:
- Overall system testing
- Finalise documentation
- Prepare for audit

Week 11:
- Implement audit feedback
- Prepare handover resources
## Progress
# ![Diagram](Resources/Schedule6.png)
# Risk Management
As the project is being implemented as part of a secure system, it is important that it does not present any new vulnerabilities to that system. This can be achieved by being considerate of the environment in which our project will be deployed and using appropriate programming techniques.
#### [Risk Register](https://drive.google.com/drive/folders/1VyUxQys5N7-MRKLpOc4DQ5fEEyYf8H6q?usp=sharing)
## Team Member Roles and Activities in Delivery Process:

| Team Member            | Uni ID         | Role                                                                    |
| -----------------------| ---------------| ------------------------------------------------------------------------|
| Jing Li                | u6531952       | Project Manager, Developer(Text Classification)                         |
| Biwei Cao              | u5926643       | Developer(Text Classification, Documentation,Agenda)                    |
| Jiaqi Zhang            | u6089193       | Developer(Testing)                                                      |
| Joshua Trevor          | u6405233       | Developer(Text Classification,research on GoldenGate, Spokesperson)     |
| Yanlong LI             | u5890571       | Developer(UI & full steak web)                                          |
| Yuan Yao               | u5945391       | Developer(Text Classification,UI)                                       |

We have regular meetings with clients fortnightly. In the previous meetings, we have a better understanding of the project, what we are supposed to do and what we are able to do. The whole project has different components, different team members are working on different aspects, these parts will finally put together. By group meeting, we discuss each work and to make sure there's no functional conflict.

## Quantitative Records of Progress:
According to the changes, we give more specific roles and tasks to team member. The testing and backend of information extraction are both holding a folder on google drive, which document the design of each part.

Testing Design and Implementation

https://drive.google.com/drive/folders/1q1XmrbL_dwGKlekvPOv6z-yesgUQQasN

Backend 

https://drive.google.com/drive/folders/1Y17atII6fwKeBC6eu8v6PLbdWbA9J6qr

User Interface Prototype

![Diagram](Resources/UIPrototype.jpg)

By the 'Things to Be Done' part of group meeting, tasks allocation and weekly review we track progress.
Testing and web server parts both make branches of git to develop their code, which will be integreted in the master branch in the future. 


## Communication Tools
1. Email
2. Facebook Messenger
3. Slack

## Development Environment
-  Language: 
   - Java installation is necessary for GoldenGate
   - Other languages not determined yet, most likely a combination of python, javascript and php will be used
-  Testing: 
   -  Unit test during development by black/white box
   -  A/B test for the final stage 

## Development Tools
1. PyCharm(Python IDE)
2. WebStorm(JavaScript)
4. DreamWeaver(HTML, CSS, JavaScript)
5. Tesseract(OCR)
6. Imagemagic(PDF to image)

## Decision Make Procedures
# ![Diagram](Resources/decision.jpg)
#### [Decision Making Log](https://drive.google.com/open?id=19k1Fsmo4KuVd94mFDShupvla8UwJ114F)

## Meeting Agenda
#### [Client Meeting](https://drive.google.com/drive/folders/1mm_xKNJ9t8DZAf-LZkJD0TDQlAKYAVky?usp=sharing)
#### [Group Meeting](https://drive.google.com/drive/folders/1MDCKulVX2guaDb-cfK7kPHIie3Kgz8MA?usp=sharing)

## Other Resources
#### [Google Drive](https://drive.google.com/open?id=1827uZfi0IwiuHkuLUU6tcL8gX5F0Jx0d)

