# AWS cloud-server

## To create a new user:

-go to AWS: "IAM"

-once at the dashboard go to users on right hand toolbar

- click create user

-follow prompts to create user

- for permissions select attach policies directly

- Select Administrator Access

- Create User

- Go to the created user and select Create Access key

- copy/paste info for later use

## Create a new application:

- Go to Elastic Beanstalk in AWS

- click on create application

- name the application and save

- Go to environment

- create a web server environment

- in platform choose node.js or other system file

- upload the zipped code file

- enter version number and continue

- select server access

- select next and then continue with defaults until Submit

- Application will be created

## Terminal upload

- in terminal go to file you want created

- enter "eb init"

- select default options or change the options

- say no for codecommit and SSH

- enter 'eb create (environment file name)'

- once completed write "eb deploy" to deploy application

![screenshot](/Screenshot%202023-08-23%20at%208.37.04%20PM.png)

![screenshot](/Screenshot%202023-08-23%20at%208.37.22%20PM.png)