# Intergrating Jenkins with AWS


- Create ec2 - create security group - allow Jenkins ip to ssh in as well as any rules required
- Create a 3rd job in Jenkins: get the code from main branch and SCP to the ec2 created above - run the script to install node with any other required dependencies (see screenshots in Jenkins folder)
- The 3rd job must only be triggered if the 2nd job was successful 
- First iteration run npm install and npm start manually (delivery)
- 4th job on Jenkins launch the app only be triggered if the 3rd job was successful 
- pm2 kill all - create a 5th job to create DB_HOST=db-ip
- npm start

hello test 