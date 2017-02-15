Developing and Deploying Intelligent Chat Bots 
===============================================

## Quick Links

* This page:  https://aka.ms/botedu
* Cognitive Services APIs:  https://www.microsoft.com/cognitive-services/en-us/documentation
* Cognitive Services Python labs:  https://notebooks.azure.com/library/python-cognitive
* Intelligent-Kiosk windows app:  https://www.microsoft.com/en-us/store/p/intelligent-kiosk/9nblggh5qd84
* Intelligent-Kiosk code:  https://github.com/Microsoft/Cognitive-Samples-IntelligentKiosk
* Bot Framework:  https://botframework.com
* Bot Framework resources:  https://blogs.msdn.microsoft.com/smich/2016/09/30/microsoft-bot-framework-resources/
* Microsoft privacy statement with Cognitive Services and Translator info:  https://privacy.microsoft.com/en-us/privacystatement
* Public class forum:  [![Join the chat at https://gitter.im/class-bots/Lobby](https://badges.gitter.im/class-bots/Lobby.svg)](https://gitter.im/analytics-at-ms/class-bots?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

other links will be posted as needed  

## About the Course

This 2-Day course is designed for developers and data scientists.  This course will ramp up the attendee quickly on the Microsoft Bot Framework as a development tool/portal and the Cognitive Services APIs for intelligence, linking the two in the creation of an intelligent chat bot for conversational platforms. Thoughtful design, much like in Data Science, as well as user experience will be emphasized to create the best bot experiences.

Instructor:  Micheleen Harris (michhar<at>microsoft<dot>com)

## Prerequisites

There are a few things you will need in order to take full advantage of the course:

Please bring a laptop with internet connectivity.

1.  **Git clone** or download this site to get all of the resources
  * To git clone, on the command line (must have git installed - see below) `git clone https://github.com/Azure/bot-education.git` or just download as a zip file.
1. **Node.js** with **npm** installed locally - get the latest at:
  * https://nodejs.org/en/download/
4. **Visual Studio Code** \[recommended\] or equivalent code editing and debugging environment with IntelliSense.  
  * https://code.visualstudio.com/download
5. **Bot Framework Emulator** (Windows and Unix-compatible) installed locally - information and links at
  * https://docs.botframework.com/en-us/tools/bot-framework-emulator
8.  **GitHub Account** - a code repository and collaboration tool we'll use
  * https://github.com/join
*  **Git Bash** - included in git download
  * https://git-scm.com/downloads
9.  [Recommended]**Azure account** - use the one you have, sign up for a free trial at https://azure.microsoft.com/en-us/free/, or, if you have an MSDN account and Azure as a benefit, link your Microsoft Account or Work/School Account to MSDN and activate the Azure benefit by following [this](https://www.visualstudio.com/en-us/docs/setup-admin/team-services/link-msdn-subscription-to-organizational-account-vs) guide

We will assume you have already have the following background:

1.  Basic knowledge around using and navigating in a unix-style command line or terminal (for using Git Bash) (good basic guide at http://linuxcommand.org/lc3_learning_the_shell.php)
2.  Familiarity with Git and GitHub as a tools for software development, versioning and collaboration. (great book on Git at https://git-scm.com/book/en/v2)
*  Have learned about debugging bots with VSCode in https://docs.botframework.com/en-us/node/builder/guides/debug-locally-with-vscode/ docs.
*  If you are new to Node, here's a good video tutorial series at https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBMdkKFn3HasZnnAqVjzHn_

## Agenda

Summary:  Each day is broken up into 1-2 hour Modules, where you will learn and perform labs on your own. Some material that is out of scope for hands-on labs will instead be demonstrated by instructor led labs. The modules, broken up into a general agenda are as follows. The specific modules may bleed across sessions depending on engagement of the audience.

## Day 1 Outline: 9:00 am – 4:30 pm

Section 1: 15 mins – 9:00 am

1.  Welcome
2.  Introduction (and course links)

Section 2: 90 mins – 9:15 am

1.  Motivation
1.  Cognitive Services overview
2.  Cognitive Services demo - IntelligentKiosk

Break – 15 mins 10:30 am

Section 3: 60 mins – 10:45 am

1.  Programming primer

Lunch – 11:45 am – 12:45 pm

Section 4: 90 mins – 12:45 pm

1.  Cognitive Services deep dive
2.  Instructor-led labs with python on jupyter notebooks

Break – 15 mins – 2:15 pm

Section 5: 90 mins – 2:30 pm

1.  Group exercise: a pitch

Break – 15 mins – 4:00 pm

Section 6: 15 mins – 4:15 pm

1.  Summary
2.  Q/A

End - 4:30 pm

## Day 2 Outline: 9:00 am – 4:30 pm

Section 1: 15 mins – 9:00 am

1.  Welcome
2.  Introduction

Section 2: 60 mins – 9:15 am

1.  Motivation
1.  Bot Framework overview ([Lab](https://github.com/Azure/bot-education/blob/master/Student-Resources/Labs/Node/Lab1_SetupCheck.md))
3.  OCR bot demo on Skype

Break – 15 mins – 10:15 am

Section 3: 75 mins – 10:30 am

1.  Developer's introduction and deploying an intelligent bot
2.  Deploy a sample bot end-to-end (use bot-hello and follow [Main Lab](https://github.com/michhar/Bot-Framework-HOL/blob/master/CONNECT.md#initialise-a-github-repository), other resources: [Part 1](https://docs.botframework.com/en-us/node/builder/guides/deploying-to-azure/#i-want-to-setup-continuous-integration-from-github), [Part 2](https://docs.botframework.com/en-us/node/builder/guides/deploying-to-azure/#test-your-azure-bot-with-the-bot-framework-emulator), [Part 3](https://michhar.github.io/posts/ocrbot-makes-a-connection#the-ocrbot-gets-registered-on-the-bf) with instructor)

Lunch: 11:45 am – 12:45 pm

Section 4: 90 mins 12:45 pm

1.  Deep dive into the Microsoft Bot Framework
2.  Instructor-led and hands-on labs ([Dialog Lab](https://github.com/Azure/bot-education/tree/master/Student-Resources/BOTs/Node/bot-playground), [Attachment Lab](https://github.com/Azure/bot-education/tree/master/Student-Resources/BOTs/Node/bot-cardbot), [Simple Intent Lab](https://github.com/michhar/bot-education/tree/master/Student-Resources/BOTs/Node/bot-simpleintent), [LUIS Intent Lab](https://github.com/Microsoft/BotBuilder-Samples/tree/master/Node/intelligence-LUIS), [Graph Dialog Lab](https://github.com/CatalystCode/bot-trees))

Break – 15 mins – 2:15 pm

Section 4: 90 mins 2:30 pm

1.  Group exercise:  Hackathon (Instructions at [https://aka.ms/botedu-hack](https://aka.ms/botedu-hack))

Break – 15 mins – 4:00 pm

Section 5: 15 mins – 4:15 pm

1.  Summary
2.  Q/A

End - 4:30 pm

The slide decks (as pdfs) are posted at https://github.com/michhar/bot-extras for each delivery of this course and available from the instructor as powerpoints.

## Modules

1.  Cognitive Services Overview
2.  Cognitive Services Topic Deep Dive
*  Bot Framework Overview and User Experience Best Practices
*  Developer's Introduction and Building an Intelligent Bot with Bot Builder Node.js SDK
*  Bot Framework Developer's Deep Dive

## Concepts Covered

1.  Generally grasp what the Cognitive Services APIs have to offer
*  Gain some in-depth knowledge and practical experience with some of the popular Cognitive Services APIs
*  Understand what a chat bot entails and how the Bot Framework can make the developer's life much easier
*  Grasp best practices around creating chat bots to create an attractive and positive user experience
*  Take a tour of an end-to-end chat bot creation process
*  Take an in-depth look at what makes up conversations and how to make them more intelligent

## Technologies Covered

* Microsoft Cognitive Services
* Microsoft Bot Framework

## Agenda

Summary:  Each day is broken up into 1-2 hour Modules, where you will learn and perform labs on your own. Some material that is out of scope for hands-on labs will instead be demonstrated by instructor led labs. The modules, broken up into a general agenda are as follows. The specific modules may bleed across sessions depending on engagement of the audience.

## Day 1 Outline: 9:00 am – 4:30 pm

Section 1: 15 mins – 9:00 am

1.  Welcome
2.  Introduction (and course links)

Section 2: 90 mins – 9:15 am

1.  Motivation
1.  Cognitive Services overview
2.  Cognitive Services demo - IntelligentKiosk

Break – 15 mins 10:30 am

Section 3: 60 mins – 10:45 am

1.  Programming primer

Lunch – 11:45 am – 12:45 pm

Section 4: 90 mins – 12:45 pm

1.  Cognitive Services deep dive
2.  Instructor-led labs with python on jupyter notebooks

Break – 15 mins – 2:15 pm

Section 5: 90 mins – 2:30 pm

1.  Group exercise: a pitch

Break – 15 mins – 4:00 pm

Section 6: 15 mins – 4:15 pm

1.  Summary
2.  Q/A

End - 4:30 pm

## Day 2 Outline: 9:00 am – 4:30 pm

Section 1: 15 mins – 9:00 am

1.  Welcome
2.  Introduction

Section 2: 60 mins – 9:15 am

1.  Motivation
1.  Bot Framework overview ([Lab](https://github.com/Azure/bot-education/blob/master/Student-Resources/Labs/Node/Lab1_SetupCheck.md))
3.  OCR bot demo on Skype

Break – 15 mins – 10:15 am

Section 3: 75 mins – 10:30 am

1.  Developer's introduction and deploying an intelligent bot
2.  Deploy a sample bot end-to-end (use bot-hello and follow [Main Lab](https://github.com/michhar/Bot-Framework-HOL/blob/master/CONNECT.md#initialise-a-github-repository), other resources: [Part 1](https://docs.botframework.com/en-us/node/builder/guides/deploying-to-azure/#i-want-to-setup-continuous-integration-from-github), [Part 2](https://docs.botframework.com/en-us/node/builder/guides/deploying-to-azure/#test-your-azure-bot-with-the-bot-framework-emulator), [Part 3](https://michhar.github.io/posts/ocrbot-makes-a-connection#the-ocrbot-gets-registered-on-the-bf) with instructor)

Lunch: 11:45 am – 12:45 pm

Section 4: 90 mins 12:45 pm

1.  Deep dive into the Microsoft Bot Framework
2.  Instructor-led and hands-on labs ([Dialog Lab](https://github.com/Azure/bot-education/tree/master/Student-Resources/BOTs/Node/bot-playground), [Attachment Lab](https://github.com/Azure/bot-education/tree/master/Student-Resources/BOTs/Node/bot-cardbot), [Simple Intent Lab](https://github.com/michhar/bot-education/tree/master/Student-Resources/BOTs/Node/bot-simpleintent), [LUIS Intent Lab](https://github.com/Microsoft/BotBuilder-Samples/tree/master/Node/intelligence-LUIS), [Graph Dialog Lab](https://github.com/CatalystCode/bot-trees))

Break – 15 mins – 2:15 pm

Section 4: 90 mins 2:30 pm

1.  Group exercise:  Hackathon

Break – 15 mins – 4:00 pm

Section 5: 15 mins – 4:15 pm

1.  Summary
2.  Q/A

End - 4:30 pm

The slide decks (as pdfs) are posted at https://github.com/michhar/bot-extras for each delivery of this course and available from the instructor as powerpoints.

## Training Objectives

The course is designed to help developers and data scientists create intelligent chat bots. After completion, participants will be able to:
* \[Specifics COMING SOON\]

## Detailed Outline [currently under minor revisions]

1. Cognitive Services Overview
  1. Introduction to the five API categories
  2. Demos of the APIs
  2. Intelligent Kiosk Windows app
1. Cognitive Services Topic Deep Dive
    Topics dependent on interest, but generally cover examples of Language, Knowledge and Vision APIs
  - Get your key and navigate the API reference
  - LUIS app
  - QnA Maker
  - Jupyter notebook code snippets of REST API calls and responses
2. Bot Framework Overview
  1. What a bot is and is not
  * The major components of the Bot Framework
  * Deploying and working with channels
  * Your arsenal or toolbox
  * Getting the best user experience through thoughtful design
  * Set up project in VSCode
4. Developer's Introduction and Building an Intelligent Bot with Bot Builder Node.js SDK
  * Develop
  * Deploy
  * Register
  * Publish
  * Test
5. Deep Dive into the Microsoft Bot Framework
  1. Overview refresher
  3. Basics
  4. Conversations and their features
  8. Conversation model
  5. State storage
  6. Adding intelligence