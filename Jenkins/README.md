# Jenkins


- From the Home page of Jenkins select New Item
- Enter the name of the item you want to create. 
- Select Freestyle project
- Click Okay

![](../images/Screenshot%202022-09-01%20155713.png)

![](../images/Screenshot%202022-09-01%20155728.png)

- As the screenshots show, fill in the relevant sections as neccesary 
- Enter the details of the project you want to test.



![](../images/Screenshot%202022-09-01%20155850.png)


![](../images/Screenshot%202022-09-01%20155901.png)

- Under Source Code Management, Enter your repository URL. We have a test repository located at
- It is also possible for you to use a local repository.
- If your GitHub repository is private, Jenkins will first validate your login credentials with GitHub and only then pull the source code from your GitHub repository.


![](../images/Screenshot%202022-09-01%20155915.png)

- Now that you have provided all the details, it’s time to build the code. Tweak the settings under the build section to build the code at the time you want. You can even schedule the build to happen periodically, at set times.

- Click on “Add build step”
-  Click on “Execute shell” and add the commands you want to execute during the build process.


![](../images/Screenshot%202022-09-01%20155931.png)

![](../images/Screenshot%202022-09-01%20155944.png)

![](../images/Screenshot%202022-09-01%20155954.png)

- Once you have entered all the data, ensure to save the project





