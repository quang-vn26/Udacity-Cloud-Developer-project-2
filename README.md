# Full Stack Apps on AWS Project

You have been hired as a software engineer to develop an application that will help the FBI find missing people.  The application will upload images to the FBI cloud database hosted in AWS. This will allow the FBI to run facial recognition software on the images to detect a match. You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk. 
You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

## Getting Started

You can clone this repo to run the project locally, or navigate to the workspace in the Udacity course.

- Run Npm i for install dependence, 
- Run aws configure
- go to C:\Users\user___\.aws\* update file config
- eb init and PassPhase: alanq_q
- update paxkage.json:  "build": "npm run clean && tsc && cp package.json www/package.json && mkdir www/tmp/ && cd www && zip -r Archive.zip . && cd ..", "clean": "rm -rf www/ || true",
- 

## Project Instructions

To complete this project, you will need to:

* Set up node environment
* Create a new endpoint in the server.js file
* Deploying your system

## Testing

Successful URL responses should have a 200 code. Ensure that you include error codes for the scenario that someone uploads something other than an image and for other common errors.

## License

[License](LICENSE.txt)
