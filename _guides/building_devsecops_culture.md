---
title: Building a DevSecOps Culture - from a Technical Perspective
category: DevOps
audiences:
  - Developers
  - Designers
  - Project Managers
---

By the end of 2016, [Gartner](http://www.gartner.com/newsroom/id/2999017) predicted that 25 percent of top global 2000 organizations would have adopted DevOps as a mainstream strategy. As one of those organizations, GSA IT continues to cultivate its own strategy. Originally we began with **DevOps** - which differs from other well-known lean approaches, like Agile, in that it focuses on improving delivery outcomes versus the process of delivery. Granted, even if the engaged software development team is not practicing an Agile approach, DevOps can still be successfully implemented in any environment. Further, it promotes a more cohesive collaboration between Development and Operations teams as they work towards continuous integration and delivery.

IMAGE
*Source: Edureka!*

*Example
* Developers develop the code and this source code is managed by Version Control System tools like Git etc.
* Developers send this code to the Git repository and any changes made in the code is  committed to this Repository.
* Jenkins pulls this code from the repository using the Git plugin and build it using tools like Ant or Maven.
* Configuration management tools like puppet deploys & provisions testing environment and then Jenkins releases this code on the test environment on which testing is done using tools like Selenium.
* Once the code is tested, Jenkins sends it for deployment on the production server (even production server is provisioned & maintained by tools like puppet).
* After deployment it is continuously monitored by tools like Nagios.
* Docker containers provides testing environment to test the build features.*

### Utilizing DevOps
DevOps is a composition of enhanced “engineering” practices that reduce lead time and increase the frequency of delivery. The primary goal of DevOps is to ensure Operations team members are engaged and collaborating with Development from the very beginning of a project / product development. As Edureka! states, “Gartner believes that rather than being a market per se, DevOps is a philosophy, a cultural shift that merges operations with development and demands a linked toolchain of technologies to facilitate collaborative change.” It requires pushing past departmental lines for more effective planning, design, and release of projects / products.

IMAGE
*Source: McKinsey&Company*

Moreover, as we continue to build upon automated delivery, we find there are opportunities to test for issues beyond typical bugs - potential security flaws, design defects, and code weaknesses. Imagine being able to identify and and fix flaws earlier in delivery process, **before** they are exposed to the public.

### DevOps + Security = DevSecOps
To this end, there’s a growing movement, called DevSecOps, to incorporate Security into the coding process. Its primary focus is to ensure loopholes and weaknesses are exposed early on through monitoring and analytics, so that remediation actions can be implemented efficiently.

IMAGE
*Source: Hypergrid*

Checkmarx quotes DevOps advocate Shannon Lietz, “The purpose and intent of DevSecOps, is to build on the mindset that ‘everyone is responsible for security’ with the goal of safely distributing security decisions at speed and scale to those who hold the highest level of context without sacrificing the safety required.” 

In GSA IT, we are actively pursuing a DevSecOps model that will not only engage Security throughout the development and operations processes, but more specifically, ensure their involvement as we align the Authority to Operate (ATO) / Lightweight Authority to Operate (LATO) process with the cloud delivery process.

#### Popular Tools
Automation is an imperative in any DevSecOps environment, at least where it makes sense. While there are a vast number of tools in the market, some of the most popular that enable automation include:

IMAGE
*Source: devops.com, Edureka!, Stackify* 

#### GSA IT-Approved Tools
GSA IT currently uses the following approved tools to support DevSecOps delivery:

IMAGE

### Measuring DevSecOps Success
When utilizing DevSecOps practices, success is often measured by the efficiency of continuous development, threat detection, and release cycles. Metrics include: 
* deployment frequency
* lead time
* detection of threats, security defects, and flaws
* mean time to repair
* and mean time to recovery.

Delivery efficiency is gained through Continuous Integration and Continuous Delivery activities that encourage and support frequent code check-in, version control, sensible test automation, continuous low-risk releases and feedback. Security issue detection gains are achieved through “threat modeling, code reviews, and red teaming.”

### Benefits of a DevSecOps Environment
DevSecOps provides a number of benefits between Development, Security, and Operations - it eliminates silos, promotes collaboration and teamwork, identifies vulnerabilities early, and provides better, faster delivery. However, be wary of creating a departmental silo from Business team members. The Business can provide valuable support by engaging DevSecOps team members upfront and ensuring Development team members’ time is accounted for and visible.

DevSecOps also contributes business value through dollars and resources saved, improved operations, diminished security threats, reduction of re-work and increased quality through automated testing, as well as the delivery of projects / products early and often with less cycle time to the customer. Additionally, as Edureka! notes, the benefits of a DevOps (or DevSecOps) environment include:

#### Technical Benefits:
* Continuous software delivery
* Less complex problems to fix
* Faster resolution of problems

#### Business Benefits:
* Faster delivery of features
* More stable operating environments
* More time available to add value (rather than fix/maintain)

### Good Reads 
These are good references for understanding DevSecOps culture and tools:
* 5 Popular Devops tools every devops should know about
* 9 Open Source DevOps Tools We Love
* 10 Deep DevOps Thoughts From Chef’s Jez Humble
* Agile Vs. DevOps: 10 Ways They're Different
* Beyond agile: Reorganizing IT for faster software delivery
* DevOps.com
* DevOps and Agile
* DevOps & The Secure SDLC: Breaking Down Barriers with DevSecOps
* DevSecOps Manifesto
* Continuous integration
* How are DevOps and Agile different?
* How are Lean, Agile, and Devops related to each other?
* HyperCloud Enables DevSecOps to Secure & Scale DevOps at Large Enterprises
* Importance of Agile in 2016
* Principles of DevSecOps
* ShiwaForce: What is DevOps?
* The 3 most crucial security behaviors in DevSecOps
* The Agile Admin: What is DevOps?
* The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations
* Top DevOps Interview Questions You Must Prepare For in 2017
* Top DevOps Tools: 50 Reliable, Secure, and Proven Tools for All Your DevOps Needs