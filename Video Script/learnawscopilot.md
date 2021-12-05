# Learn AWS Copilot

## Script

> Title Slide

Hi Everyone. This is Julian Frank

For quite some time I've been blogging my experiments on julianfrank.wordpress.com but this time I wanted to move to video blog...so here we are...

I recently tried out the Amazon Container Service and the copilot cli which is the companion cli to help with this solution. 

Lets go about this today but first a quick background on why I'm interested in this?

Back in 2016 I had blogged about Hobby stack that could be built by individuals to build their own web places You can see the link in the description. 

So what is Hobby stack?

> Hobby Stack Slide

Its a stack that I beleive can be used by the not so normal developers to build their own place without any regard for the "Enterprise" model and norms. 

Focus has to be on Cool Features, almost zero cost, cloud independent and multi-cloud resilient. 

Most of these would would have low traffic volume and not have commercial value but focus would be on not-so-normal architecture design patterns and user experiences

Over the years the option available have increased making this a very interesting "Hobby" for me.

Off late I've been playing around with functions provided by different clouds and slowly and steadily I'm seeing "container as Functions" slowly becoming more and more mature every year. 

This is not a new solution ...Its been around for more than 5 years! Also Copilot is also not new ...It went GA last ...novemebr 2020

but I ahppen to try it recently and wanted to share my experiences so here we go...

> Baseline Application
>> Show Sample Hobby App

OK so this is a base app to show both one way and two way APIs in action. 

You can find the link to this repo in the description

This is a technical demo app with the front end being a simple HTML5 Page but on the backend there is a REST API Server providing Add and Subtract Services
There is also a WebSocker Socket server which provides the Clock Service which is sending the server clock info to the client on a periodic basis

The Web page also has the option to access the Add and Sub service using the WebSocket APIs

So Reasonably complex as the backend for the webpage, REST and webSocket are all separate. 

Try to make them work together... Its fun... You'll a lot about web technologies

> About amazon Container Service
>> Show Topics Diagram
OK back to our topic

This is basically the outline of wha we are going to see today

Dont worry its not as complicated as it looks 

> One Step back
>> Show Pre-Requisites diagram

You need to understand some cloud basics before we go deeper into this solution. 

The main purpose of ECS is to run Containers and hence I beilve you understand what containers are, what container repository mean and how they work together

I'm also assuming that you understnad code repositories. I'm sure you should be well versed with git and the multiple git repositories like github, gitlab, bitbucket and superscaler provided git repositories provided in azure devops, aws codestar etc

Cloud Logs is another important aspect that gets missed out but is super important when you app gets super complicated

CICD for automated testing, integration and deployment from code repo to builders to container repository to container runtimes

Cloud State manageent is a enterprise concept but I already see the benefit esp when the app spans multiple clouds

Cloud Builders take the code in the repo and build the impages and load them into container repositories

This is a minimum you should have a fair understanding of for the rest of this video to make sense for you

> Amazon Container Service
>> show aws cloud services picture
Amazon Container Service is the service that brings the benefits of Container based workloads with serveless paradigms

U see Containers let you write your code in any language you want and keeps you code ready to be run in any container runtime provided by the different cloud providers

Functions let you run the code in an environment where you get infrastructure like compute and memory in response to user requests and events and when the response is provided, they are removed and not billed!

This makes running app with spikey usage to be very cost effective. And Cost effectiveness is very important for Hobby Stack

Container Runtimes like the various Kubernetes and in house engines need compute and memory to be reserved and hence you end up paying for your app even if you are the only user and you end up uding only during weekends!
That is very innefecient and hence I had been staying away from containers. 

Then came FARGATE and changed the game. It changed the ECS to be used only when triggered and promised to bring the utility model of functions available with App working in containers

thats cool but then in practise that meant writing a lot of shell scripts or complex cicd to make it work

This is where aws brought co-pilot to help you out

>copilot
>> show copilot picture

From their homepage they claim to help with managing multiple app architectures, continous delivery and even operations!

well we could get into a lot of theory but lets get practical... So lets jump to the terminal and clone the samplehobbyapp repo to get us started

For this repo we'll need aws configured along with nodejs and Npm

