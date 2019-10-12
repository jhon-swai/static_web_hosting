# Intallation of firbase CLI
1. Install node.js
2. Intsall Firebase CLI
3. Create a project in the firebase website
### Install Firebase CLI
```
sudo npm install -g firebase-tools
```
### Create a project
Sign in with your google account and create a project of your choice. 
[Go to firebase website console](https://console.firebase.google.com/)
In my case it is firebase-demo

### Firebase login
In your local machine create a folder with a similar name as in the online project
```
mkdir firebase-demo
cd firebase-demo
```
Then login
```
firebase login
```
### Initialize 
```
firebase init
```
It will be followed by a series of selection that are easy to understand. I am going to list the options to select for our case in each step
1. Hosting: configure and deploy Firebase Hosting sites (select using the spacebar and move with the arrow keys)
2. Use an existing project
3. Select firebase-demo
4. type public
5. choose yes/no for it to create index.html
### Adding files in the folder
Copy all your website files in the public directory 
Make sure there is index.html file as the default view since firebase will look for this file first

### Deployment 
```
firebase deploy
```




