## Introduction

This tutorial will ramp up the attendee very quickly on the Microsoft Bot Framework, providing sample code upon which to base a bot experience.  It will help attendees decide if they want to make a bot to solve a repetitive task they have encountered or they know might be useful to others.  User experience will be heavily emphasized to create the best bot experiences.  Components will be laid out for the attendee.

## Duration

Approximately 90 minutes

## Prerequisites for hands-on-labs

Please bring a laptop with internet connectivity.

1. **Node.js** with **npm** installed locally (get the latest [here](https://nodejs.org/en/download/)) - if you are new to Node, here's a good video tutorial series: [check it out](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBMdkKFn3HasZnnAqVjzHn_)
2. Unix **command terminal** access or, if on Windows, [PowerShell](https://github.com/PowerShell/PowerShell#get-powershell) or [MobaXterm](http://mobaxterm.mobatek.net/) work nicely - if you are new to the command terminal, here's a good unix tutorial: http://linuxcommand.org.
4. **Visual Studio Code** (get [here](https://code.visualstudio.com/download)) or equivalent code editing and debugging environment with IntelliSense.  Learn about debugging bots with VSCode in [these](https://docs.botframework.com/en-us/node/builder/guides/debug-locally-with-vscode/) docs.
5. **Command Line Emulator** - install instructions [here](https://docs.botframework.com/en-us/tools/bot-framework-emulator/#mac-and-linux-support-using-command-line-emulator) (Note:  this is a large install)
8.  **Git** - https://git-scm.com/downloads

## Recommended Reading/Watching

* The Bot Framework Command Line Emulator (for local testing):
  - https://docs.botframework.com/en-us/tools/bot-framework-emulator/#mac-and-linux-support-using-command-line-emulator
* Useful to know for how we will debug locally:
  - https://code.visualstudio.com/docs/editor/debugging#_launch-configurations
  - https://code.visualstudio.com/docs/editor/debugging#_attaching-vs-code-to-nodejs
* Useful to learn about testing a cloud deployed bot
  - https://docs.botframework.com/en-us/tools/bot-framework-emulator/#using-the-emulator-with-ngrok-to-interact-with-your-bot-in-the-cloud
* Computer Vision API (part of Microsoft's Cognitive Services):  https://www.microsoft.com/cognitive-services/en-us/computer-vision-api
* Language Understanding Intelligent Service (LUIS) video here:  https://www.luis.ai/Help#Video (part of Microsoft's Cognitive Services)
* Useful to know for deploying a bot to Azure (Microsoft's cloud):
  - https://docs.botframework.com/en-us/node/builder/guides/deploying-to-azure

## Outline for Conference Bot Framework Delivery

1. Introduction and goals
 * Syllabus
 * Learning objectives
1. Bot Framework Overview
  1. What a bot is and is not
  1. What types of bots people are making
  * The major components of the Bot Framework
  * Introductory knowledge of intelligent bots
  * What types of bot data there are
  * Getting the best user experience through thoughtful design
  4. Deploying and working with channels
2.  Cognitive services overview
  1. What are Cognitive APIs
  * Models behind Cognitive APIs
  * Types of Cognitive APIs
  * Cognitive APIs Demo (Vision and Text)
3.  Developer's Introduction and Building an intelligent bot with Bot Builder Node.js SDK
  1. Toolbox - Go over prereqs
  * Setup project in VSCode (and set up debugger)
  * Get code from course website
  * Update with Vision API key
  * Test with emulator
4.  Summary