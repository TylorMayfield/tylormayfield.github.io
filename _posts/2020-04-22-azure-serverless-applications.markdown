---
layout: post
author: Ty
title:  "Azure Serverless Applications"
date:   2020-04-22 
image: https://images.unsplash.com/photo-1564457461758-8ff96e439e83?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1489&q=80
categories: [Topics]
---


Azure Functions, EventHub and WebHook focus on specific, short tasks. Azure Functions allows developers to execute code without explicitly deploying and managing infrastructure. Written on the WebJobs SDK, it is the logical successor to Webjobs and allows the developer to run the code in the cloud without explicitly making rules and managing the infrastructure, or even using a third-party server. 

With server-less computing, there is no longer any limit on how much CPU resources are required to execute a function. You write the feature, publish it in the cloud, run it, and only pay for it at every launch. Serverless enables developers to focus on the code rather than the platform, and in many cases even eliminates the need to manage dependencies. If your code is running, you will not be billed for the server-less architecture, as you only pay to keep the underlying server resources reserved and available. 

A function that runs successfully locally can be scaled to potentially handle billions of events in the cloud, and a function code hosted on multiple underlying servers is able to potentially host several of them. This allows a server-less platform such as Azure Functions to automatically scale to the maximum. To meet your application needs, your functions automatically scale up and down to meet the application's needs. 

