# Auth-Micro API
A microapi to allow easy integration of authentication into your service

## Usage 
[Go to support website](auth.microapi.dev) 🎈

## Contributions
https://docs.google.com/spreadsheets/d/1aNd-d2mQIOHOYnCLvG1wHn7pYS2XqHnmDSzABABQTBI/edit?usp=sharing

## Features
- [x] Register to use Auth Service
- [x] Get API key after Email Verification
- [x] Register/Login your App users with API key
- [x] Email Verification for your App users on Registration 
- [ ] Social Authentication
- [ ] Get all your app users 
- [ ] Get all active/online users 

## Prerequisites:
- Node v~12.16.0
- npm v~6.14.5
- MongoDB Atlas URI
- Sendgrid APIKEY
- Clone repo

## Setup:
- `cd auth-microapi`
- `cp sample.env .env`
- `add MongoDB URI, and Sengrid APIkey in .env`
- `npm install`
- `npm run dev`

## Contribution Guide:
Please always follow the right format before making pull request

* Fork this repository into your remote repository
* Clone the code from your remote repository into your local machine `git clone <url>`
* Create a branch with the feature name you wish to work on `git checkout -b <name_of_feature>`
* Add any changes
* Add tests with jest and make sure they pass `npm run test`
* Create an upstream on your local machine to pull the latest code from the develop branch of this repository `git remote add upstream develop` and `git pull upstream develop`
* Push to the remote branch which you forked `git add .` | `git commit -m "cool feature"` | `git push origin <name_of_feature>`
* Make a pull request to the develop branch of this repository