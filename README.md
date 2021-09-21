# Weather Report Website
## Table of contents
* [General info](#general-info)
* [Process](#Process)
* [Layout](#Layout)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This is Mail Application which can handle Sent Messages,Thrash,Inbox,Draft

## Process
For Adding Message to the inbox Please follow the below format :
```
Post req URL: http://localhost:3000/mail/inbox

Body raw format :

{"username":"your_username","content":{"from":"mail ID","subject":"subject Mail","body":"body of the mail","read":"no"}}

```
## Layout
There are 5 Layouts in this Application
  * New Message
  * Inbox 
  * Sent Items
  * Draft
  * Thrash
  
  ### New Message 
  In this tab we can Compose new mail Once we compose we can either Send Or discard it
  ![New Message](build/assests/Newmessage.png)

  ### Inbox
  In this tab we can view message sent through above mentioned post format
  ![Inbox](build/assests/outlook.png)

  ### Sent_item
  In this tab we can view message sent through above mentioned post format
  ![Sent Messages](build/assests/Sent_item.png)

  ### Draft
  In this tab we can view message which was discarded from the inbox message which can sent later
  ![draft](build/assests/Draft.png)

  ### Thrash
  In this tab we can view message which was deleted from Other Tabs
  ![draft](build/assests/Thrash.png)

## Technologies
Project is created with:
* Node js :14.17.5
* Express : 4.17.1
* cors : 2.8.5
* socket.io : 4.2.0



## Setup
To install Node JS check the official website(https://nodejs.org/en/download/)
To run this project, install express , Cors and Socket.io locally using npm:

```
$ npm install express
$ npm install cors
$ npm install socket.io
$ npm start

```