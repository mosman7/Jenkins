## What is CI, CD & CDE
#### What is CICD
- Continuous Integration and Continuous Deliviery is considered as the backbone of DevOps practices and automation, it plays a vital role in DevOps culture.
- CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deploymen
- A CI/CD pipeline is all about automation: Intialising the code builds, automated testing, and automated deployment to staging or production enviroments. This saves the teams a lot of time as they don't have to create the tests and this process is incredibly fast.

#### Continuous Integration - CI
- Is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where the builds and tests are then run.
- Developers merge/commit code to the main branch multiple times a day, full automated build and test processes which gives them feedback within a few minutes, by doing this, you are effectively avoiding the integration mayhem that happens when developers wait for the release day to merge all their changes into the release branch.

#### Continuous Delivery - CD
- It's an extension of continuous integration to make sure that you can release new changes to your customers quicker in a much more sustainable method. So on top of your continuous integration, you also automated your release process and can deploy you application at any point of time by clicking a button. Deployment will have to be done manually but that can also be done automatically

#### Continuous Deployment - CDE
- This goes futher than Continuous Delivery by deploying the actually application online automatically, so each change that passes all the stages of your production pipeline is released to your customers, there is no human interaction so this lowers the chance for human error, and even one failed test will prevent the new change being deployed to production.

### What is the diff between Continuous deliver - deployment
- The main difference is that on continuous delivery, you would have to deploy the application manually whereas continuous deployment is an extension of continuous delivery and deploys the application automatically as well as testing the application too.

What is a webhook

![](https://miro.medium.com/max/612/0*DVSYJfjOJrCTzqUB.png)

#### Jenkins

- Jenkins is an open-source continuous integration server written in Java.
- It helps developers in building and testing software continuously. It increases the scale of automation and is quickly gaining popularity in DevOps circles

#### Stages
![](https://cloudaffaire.com/wp-content/uploads/2022/01/word-image-45.png)
A piece of code that is ready to be deployed needs to go through each of these stages before it is released to a live production. It is a thorough check at each stage and must pass.

#### How does it work

#### Benefits of using Jenkins
- Issues are detected and resolved almost right away which keeps the software in a state where it can be released at any time safely.
- Most of the integration work is automated. Hence fewer integration issues. This saves both time and money over the lifespan of a project.
- 

#### Who is using Jenkins
- Jenkins has been adopted by the likes of Facebook, Netflix and Ebay because of it's incredible advantages. Jenkins is an open source automation server in which the central build and the continuous integration take place. It works on Windows, macOs, and Linux. It has a user-friendly interface, easy installation, extensible with a ton of plugin resource, and easy environment configuration.

what other tools are available as automation servedr
