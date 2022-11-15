# When you have a Repo in your local machine

## step to add local Repo in  github

 1. Initialize git in the folder ``` git init ```
 2. Add files git add ```git add <file name || . >```
 3. Do commit using command ```git commit  -m "message goes here" ```

 4. Now Crete a repo in empty repo in github 

 5. Use command ``` git remote add origin <path of repo > ```
 
 6. The use ``` git branch -M main ```

 7. then push your code using command ``` git push -u origin main ```  

 # adding new Branch 

 1. To add new branch use command ``` git checkout -b nameOfBranch ```
 2. then push the branch to github via this command ``` git push -u origin nameOfBranch```
 3. after pushing the branch we delete the branch for this you first checkout form that branch and then 
    use command ``` git -d nameOfBranch ```
 4. to pull updates use command  ``` git pull origin nameOfBranch ```
 5. you can create new brach or work with same branch