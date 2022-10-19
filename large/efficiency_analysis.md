# Efficiency Analysis Project

The goal of this project is to examine what technologies and procedures are the most efficient at producing web applications. 
The outline is simple: produce the same web application with several technologies and methods to see 
what is the most cost-effective way to create a web app. All development time for the web app will be recorded for each case. 

These web app implementations would then be subject to analysis of several key metrics to see what the quality of the final product is. 
Recorded metrics include: 
1. Performance testing (requests successfully served per second, percentage of successful requests, etc.) 
2. Security Testing
3. Rate of faults introduced
4. ... and so much more!

Technology combinations to be tested include: 
1. Python + Django + Postgres
2. Python + Django + Postgres + Kubernetes
3. Python + Django + Postgres + AWS Scaling
4. Rust + Actix + Postgres

The goal is basically to find out the answers to a few very important questions: 
1. Is it more efficient to build in efficient technologies like rust, or is it more efficient to build in less efficient technologies like python and then apply a scaling technology to it. 
2. If the software is safety critical, what combination produces software that is most safe (defined as least failures and most secure from attackers)
3. If the software is to be highly performant, what combination of technologies produces the most performant web app? 


More is still to come, this is just an initial brainstorming of a project I would like to work on. 
