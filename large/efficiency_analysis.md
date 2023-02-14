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
4. If the software is not to be highly performant, what combination of technologies produces a working prototype fastest?
5. What are the breakeven points for investing in more infrastructure? For example, how many manual deploys would you have to do before it costs less to set up Terraform deployments? 

## Method: 
Here is the method I plan to use: 

### Compare Competing Technologies
For example, compare TailwindCSS to Bootstrap to raw css.  
Then, compare python/django to java/springBoot to rust/actix. 
Then, compare Postgres to MongoDB to Postgres+Reddis. 


Categories could be: 
- Databases
- Frontend frameworks
- CSS Frameworks
- backend frameworks
- CI/CD Technologies
- Scaling Technologies
- Development Techniques (TDD vs code then test vs augment with AI, etc.)

Criteria could be: 
- development time (time writing, time reading documentation)
- bugs encountered
- performance (load times, query times, requests per second, etc.)
- Code Maintainability
- Security


## Future Work: 
Finalize lists of criteria and categories
Create list of technolgoies to compare


## Final Thoughts
More is still to come, this is just the brainstorming of a project I would like to work on. 
