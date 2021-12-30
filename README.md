# VPS_COFFIN
### Create an unlimited private vps for free!
## You are not allowed to modify the project.
> ## [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/c9ffin/vps/blob/main/.github/workflows/c9ffin.yml)
***
### Machine Specification:
- OS : Ubuntu 20.04 SSH Tunnel
- 2-core vCPU
- 7 GB RAM
***

## Setting up:
1. Fork this project
2. Go to your peoject page, click `Settings` and go to `Secrets`, and then click `New Secret` to add these secrets below:

Secrets Name | Uses | Notes
----- | ----- | -----
`NGROK_AUTH_TOKEN` | For **ngrok** tunnel uses | Go to website, and copy Your Authtoken from https://dashboard.ngrok.com/auth/your-authtoken
`LINUX_USERNAME` | For VPS username `root` | Type any name you want
`LINUX_USER_PASSWORD` | For VPS `root password` | Type any password you want
`LINUX_MACHINE_NAME` | For VPS System `Computer` name | Type any name you want
`CHROME_HEADLESS_CODE` | For remoting linux desktop using google remote | Copy Codes from [here](https://remotedesktop.google.com/headless) and login with your google account, and then copy the code below `Debian Linux` blank. :warning: Each code can only be used for once, generate another code when u have used that one.
***
## How To Run
    
1. go to `Actions` Tab and select one of system workflow.

2. Click `Run Workflow` button on the left of `This workflow has a workflow_dispatch event trigger` line.

3. Wait until a few minutes.

4. Go to https://dashboard.ngrok.com/endpoints/status and check if theres a one online tunnel running.

5. Copy the link(**without tcp://**) and go to **PuTTY** (Or Any Software that supports SSH Connection),

6. Fill in those login info, within username from `LINUX_USERNAME`and password from `LINUX_USER_PASSWORD` you typed.

7. Enjoy!

***
> If you have any questions, contact me in Discord:
> https://discord.gg/fgsK9wqWhQ
## Original Repositor :
> https://github.com/c9ffin/vps
***
