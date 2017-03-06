Webfaction Deployment
By Joseph Karasek for Hello World Devs

Description

This deployment script is meant to be used with WebFaction and was built as a development tool for the Tyson Steele projects. This script handles two tasks: 1) setting up the initial configuration on Webfaction for a static site (including the webapp, domain, and website) and 2) pulling the latest version of a site if the website already exists.

This is the first python application I have ever written. Please feel free to give me feedback.

Prerequisites

You will need the following things properly installed on your computer.

Python 2.7
Installation

It is highly suggested (but not required) that you place the script in the root directory of the project you are working on.
Open the example.siteConfig.py file. Follow the instruction to create a siteConfig.py file
Note: This file will need to be in the same directory as the deploy.py script
It's suggested you add the following entries to you .gitignore file
siteConfig.py
*.pyc
How to use

Simply run... python deploy.py. This command will both initialize a project and pull in the latest version.

Features to add

Setup of DNS through Name Cheap
Better UI feedback, including prompts
Known Bugs

No known bugs at this time.

Resources

WebFaction API Docs
Support and contact details

If you have any questions, concerns, or feedback, please contact the authors through gitHub.

Technologies Used

Python
WebFaction API
License

MIT License.

Copyright (c) 2016 Joseph Karasek
