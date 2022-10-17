# Git and Github 

### Task 1
- Demonstrate minimum 15 basic Git command with explanation and screenshot.

#### Git Command 1
```
git config --global user.name "Arnab Das" --replace-all
```
This Command used to set the global user name. It will tagged the name for credit when review version history
![image](https://user-images.githubusercontent.com/70307607/195248932-601ad933-dcef-48c3-8409-ebba31c92e43.png)

#### Git Command 2
```
git config --global user.email "abc@xyz.com"
```
This Command used to set the global email. It will associated with each changes.
![image](https://user-images.githubusercontent.com/70307607/195249000-69226994-dfde-464b-bd04-2f9b71aa7ac4.png)

#### Git Command 3
```
git init
```
This Command used to initialize an existing directory as a Git repository. 

![image](https://user-images.githubusercontent.com/70307607/195249816-ededb54d-3d45-4fda-8ab8-34b99dd0df6b.png)

#### Git Command 4
```
git clone https://github.com/arnab000007/gittest.git
```
This Command used to retrieve an entire repository from a github repository via URL
![image](https://user-images.githubusercontent.com/70307607/195250132-d69f9642-9ac6-43d5-949f-082522b0e6d6.png)

#### Git Command 5
```
git status
```
This Command used to get modified files in working directory, staged for your next commit.
![image](https://user-images.githubusercontent.com/70307607/195250358-8586bbf6-bfa3-42b2-90b1-497cd20c4a63.png)

#### Git Command 6
```
git add README.md
```
This command add a file as it looks now to your next commit (stage).
![image](https://user-images.githubusercontent.com/70307607/195250617-91c41460-0c16-435b-a71f-551dbb004cb7.png)

#### Git Command 7
```
git reset README.md
```
This command used to unstage a file while retaining the changes in working directory.
![image](https://user-images.githubusercontent.com/70307607/195250965-9bee069c-0fd2-43f3-9b27-6e2e058c89ea.png)


#### Git Command 8
```
git diff
```
This command used to get the difference of what is changed but not staged yet.
![image](https://user-images.githubusercontent.com/70307607/195251337-61c20228-21da-4c7a-8222-64116e281753.png)

#### Git Command 9
```
git diff --staged
```
This command used to get the difference of what is staged but not yet commited.
![image](https://user-images.githubusercontent.com/70307607/195251590-b33f6c5e-4dba-407c-b523-534550ce80a0.png)

#### Git Command 10
```
git commit -m "This is the Test Commit"
```
This command used to commit staged changes as a new commit snapshot.
![image](https://user-images.githubusercontent.com/70307607/195251933-186f7eee-871b-494c-9643-d1761a664798.png)

#### Git Command 11
```
git push origin main 
```
This command used to push the commited snapshot to the git hub repository.
![image](https://user-images.githubusercontent.com/70307607/195252329-ec0aae69-a84b-45d4-a85d-449d73e804b4.png)

#### Git Command 12
```
git branch
```
This Command used to get a list of all available branch. A * will appear next to the currently active branch.
![image](https://user-images.githubusercontent.com/70307607/195253981-2c879975-b194-4d47-9d83-f80470dafa91.png)



#### Git Command 13
```
git branch developer1 
```
This Command used to create a new branch at the current commit.

![image](https://user-images.githubusercontent.com/70307607/195254118-850dba67-7dcf-4cf3-a644-a2bc4692c514.png)

#### Git Command 14
```
git checkout developer1
```
This Command used to switch to another branch and check it out into your working directory.
![image](https://user-images.githubusercontent.com/70307607/195254958-74b326d2-edb8-4753-bc84-03b0f3adddc0.png)


#### Git Command 15
```
 git branch -d developer1
```
This Command used to delete a branch.

![image](https://user-images.githubusercontent.com/70307607/195255269-eb0eaacf-8bbf-4fa3-ae74-795329c52ec3.png)


### Task 2 
- Consider that your want to start an open-source project in your organization. Perform all the standard operation to create a repository with minimal permision for all the users. It should contain.
1. Proper open source structure 
2. Proper Readme
3. Add 2 collaborator 
4. Host GitHub Pages using settings (Designed to host your personal, organization, or project pages from a GitHub repository)

This is the Open Source project - [https://github.com/arnab000007/github-open-source](https://github.com/arnab000007/github-open-source).

Added 2 Collaborators
![image](https://user-images.githubusercontent.com/70307607/196086490-4ce796dd-a03c-4cbc-a7b6-d4167712a70c.png)

You can find the github hosted page in [https://arnab000007.github.io/github-open-source/](https://arnab000007.github.io/github-open-source/).


### Task 3 
1. Create a Issue in your github repository.
2. Raise a pull request.
3. Merge A pull request.
4. Reject a pull request with proper comments.
5. Add a Dependabot alerts in your github.(for above cases)
6. Stash changes
7. Create a release your package
8. Setup a Projects Board for your project.
