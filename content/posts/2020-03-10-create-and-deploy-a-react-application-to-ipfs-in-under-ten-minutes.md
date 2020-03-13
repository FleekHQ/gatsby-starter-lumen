---
template: post
title: Create and Deploy a React Application to IPFS in Under Ten Minutes
slug: terminal-create-react-app
draft: false
date: 2020-03-10T02:38:34.993Z
description: >-
  A React application can be bootstrapped in a matter of minutes with
  create-react-app. Terminal allows apps to be deployed to IPFS in a matter of
  minutes. These two go together like peanut butter and jelly, allowing for
  development and deployment to be complete in a flash.
category: Tutorial
socialImage: /media/CreateReactAppSocialimage.png
tags:
  - Tutorial
  - Guide
---
![](/media/CreateReactAppSocialimage.png)

A React application can be bootstrapped in a matter of minutes with create-react-app. Terminal allows apps to be deployed to IPFS in a matter of minutes. These two go together like peanut butter and jelly, allowing for development and deployment to be complete in a flash.

We will do it in two steps which are: 1. Creating a react application with create-react-app 2. Deploying our app to IPFS with terminal. This process takes less than ten minutes. Let’s go!

### Step 1: Creating a React application with create-react-app

Create-react-app requires npm => 5.6 and node >= 8.10, so make sure they are installed at the correct version.\
\
We will start by running the following commands to create and preview the react application.

`npx create-react-app my-app`

`cd my-app`

`npm start`

Go to <http://localhost:3000> in your browser and you will see the default create-react-app application.

![](/media/1-localhost.png)

Now, it’s time to develop the app if you wish to do so, or simply use the default application. For this tutorial, I made some slight modifications to the default react app.

![](/media/2createreactapp.png)

Terminal will grab the application from your github repo, so the next thing to do is to create a github repository with our app in it.This is the repo for the app above: <https://github.com/SamueleA/create-react-app-ipfs-deploy>Feel free to fork it.Let’s deploy it now!

### Step 2: Deploying the App Through Terminal

Upon first signing up on Terminal, we are asked to add a new site.

![](/media/3-add-site.png)

Next, we input additional information such as the repo branch, the build commands and the build directory. Luckily for us, the default values will work perfectly so there is no need to change anything. Clicking the “Deploy Site” button at the bottom will commence the deployment.

![](/media/4reactapp.png)

The deployment is in progress! In a few minutes, we’ll have access to our deployed app. The deploy log at the bottom of the page tracks the progress of the deployment.

![](/media/5reactapp.png)

Success! The deployment worked and the yellow indicator at the top turned blue and a clickable url ending in .tmnl.co appeared. This url is provided by Terminal and it points to the IPFS deployment.

![](/media/6-og-success.png)

Here is the link to see the result: <https://orange-disk-4090.tmnl.co/> You can also click on the “Verify on IPFS” link which will lead you to an IPFS gateway using the IPFS hash, where the app can be admired in all its distributed, uncensorable glory. Creating the default react app and deploying it to IPFS literally takes less than 10 minutes, so I invite you to create and deploy your own application by participating in the [Terminal Beta](https://terminalbeta.typeform.com/to/kionHH).

**\
Documentation** 

**[Create-React-App](https://reactjs.org/docs/create-a-new-react-app.html)**

**[Terminal Docs](https://docs.terminal.co/)**