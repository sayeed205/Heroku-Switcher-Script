# Heroku Switcher Script

### Individual script for <a href="https://hs.hitarashi.in">Heroku Switcher</a>

## Description

#### This is individual script separated from <a href="https://github.com/sayeed205/Heroku-Switcher">Heroku Switcher</a>. You don't have to sign up for <a href="https://hs.hitarashi.in">Heroku Switcher</a> to run your Heroku apps without worrying about dyno hours.

## How it works

- First of all you need two of Heroku accounts ( yeah, need two accounts to make this work).
- This script will transfer your heroku apps from one account to another on 1st and 15th day of every month.
- Although this script will check every 4 hour if its 1st or 15th day of the month.

## Alternative

You can use <a href="https://hs.hitarashi.in">Heroku Switcher</a> to do the same thinhg and you don't have to use this scrpit.

## Preparation for Deployment

- Create two Heroku accounts
- Deploy your app on one heroku account only. We will call this your main account.
- Leave the second account as it is.
- Get API Keys from both the accounts.
- Make a github gist as herokuData.json
- Fill that gist as shown below.
  <br>
  <img src="https://raw.githubusercontent.com/sayeed205/Assets/main/Screenshot%202022-08-25%20164633.png" alt="gist example" />
  <br>
- Add your Heroku API key of the main account as aHerokuApi.
- bHerokuApi for the second account.
- And last appName for the heroku app name.
- You can add as many apps as you want separated by comma as json format.
- Now get the raw link of the gist without commit id.

## Deployment

### WIP
