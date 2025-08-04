# nodejs-app
Elevate Labs DevOps Internship Task 1

Objective: Set up a CI/CD pipeline to build and deploy a web app. 
Tools: GitHub, GitHub Actions, Node.js, Docker
Deliverables: GitHub repo with .yml CI/CD workflow

Implementation:-
    --Downloaded Git.
    --Created ssh keys, to connect local to github repository.
    --Installed node.js, to run the sample API-based web application in local host using "npm-start".
      Checked test cases locally using "npm-test".
    --Created Dockerfile, to set working app directory and copied application folder and package json files.
      Used docker-compose to test the app in port 3000, to check container build locally.
    --Inititated CI/CD Pipeline to run multiple jobs containing test, build, deployment.
    --Pushed the code to Git Repository to run CI/CD pipeline for docker image build.
    --Once build pipeline successful, the application was further deployed to Render Cloud Application Platform (Free Tier) 

