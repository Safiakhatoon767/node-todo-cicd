# node-todo-cicd

sudo apt install nodejs
sudo apt install npm
npm install
node app.js

step 1 : Fork The Repo
step 2 : Open Jenkins
step 3 : Click on create a job
step4 :  Enter name and click on freestyle project and finally click on ok.
step5 : Provide github url.
step6 : Click on Build Steps and select Execute Shell.
step7 : Click on Save button and the job will appear on dashboard screen.
step8 : Click on job->configure and select “GitHub hook trigger for GITScm pollling”.
step9 :  Add a webhook. To add it , follow the section given below.
step10 : Make any change in github repo and edit any header file. Job will run automatically and changes will be made.
step11: Adding Jenkins Webhook in Github
step12: Open Github repository.
step13 : Go to “settings” and then to “hooks”.
step14 : Click the “Add webhook” button. Enter “<Jenkins url>//github-webhook/” Payload URL. Click on Add webhook.
step15 : In the Execute shell, run the application using Docker compose.
Give docker commands in the execute shell(Project should be integrated with github repo and jenkins). Click on save.

  
  step16 : Click on build now. Job will run successfully.
  step17 : Open the particular IP on which it is hosted. It will be up and running.


                                                         Thank you for reading this blog. Hope it helps.

                                                         — Safia Khatoon
