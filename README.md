# CI/CD
# What is CI/CD CDE ![Alt text](../Images/CI-CD.png)
- It stands for continous integration,  continuous delivery and eployment 
- It is considered the back bone of DevOps. Most companies now are releasing softwear with the help of CI/CD practices. 
## Continous Integration 
- In CI developers mareg/commit code to the master branch multiple times a day. Performing releases this way elimanates the need for companies wating for days to then merge their branch into the release branch. 
## Continuos delivery (CD)
- This is an extension of CI to make sure that you can release new changes to the customer much quicker, and more sustainbaly. With this you will have to automate your testing and also, have to automate your release process release process and you can deploy yourn application at any point of the day at the click of a button. CD the delivery is compleated manually. 
## continous Deployment (CDE)
- This Goes one step further than CD as all stages of production pipeline are released withou human interventio nand only when their is a failed test will it prevent a new change going through to production.

## examples of when CI/CD CDE is used 
- Services like amazon, netflix, facebook all use this pipline as they need there services to be constantly running and able to perform updates in the background. 
## What is Jenkins 
- Jenkins is an open source automation server in whihc the centrle build and CI processes take place. It is java program with packages for windows, macOS and linux. 
## Why jenkins?
- It is such a good program to use as it is ope source and has an amazing range of plugins avaliable. Jenkins supports building, deployment and automatiuon for SD (softwear developer) projects. Has easy instilation simple UI (user interface). 

## Other automation services avaliable are 
- circleci
- TeamCity
- Bamboo
- GitLab

This image illustrates what the differnece between these services are. 
![](../Images/Other-automation-services.webp)
## git workflow 
- Git workflow is a recomendation for how to use Git to accomplish work in a consistent and porductive manner. They encourage Developers and DevOps teams to leverage Git effectively and consistently.
## Jenkins work flow
- Configure jenkins. Set up the jenkins server and configure with the necesary plugins
- create a job to automate specific tasks 
- Trigger the job
- Build the code 
- Run tests
- deploy changes 
- monitor the job.
## SDLC workflow ![Alt text](../Images/SDLC-WORKflow.png)
- Planning 
- Analysis 
- Design 
- Implement 
- Testing 
- DEployment 
- Maintanence 

