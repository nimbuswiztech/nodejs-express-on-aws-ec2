# Deploying NodeJS APP on AWS EC2 Instance

Let's get started. We need to perform the following steps:

1. Create an AWS EC2 instance
2. SSH into the instance
3. Install NodeJS and NPM
4. Clone the repository from GitHub
5. Install all the required dependencies
6. Run the application
7. Access the application in a browser

## Install NodeJS and NPM

Now we need to install nvm (node version manager) by typing the following at the command line:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

## Now you need to activate nvm by using the command:

```
. ~/.nvm/nvm.sh

## By using nvm you have to install Node.js. Put the below command in the command line:
```
nvm install node

Check the nvm and Node.js version by using the commands:
```
nvm --version

## Clone the repository from GitHub
After installing Git, now we will clone the repository of the Node.js application.

```
git clone <repository name>
cd nodejs-on-ec2

## Install all the required dependencies

To install the dependencies use the below command:
```
npm install

## Run the application
To run the application put the below command:
```
node app.js




