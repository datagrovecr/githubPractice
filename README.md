# Git/GitHub Practice Repo
This repo was created for Datagrove Costa Rica developers to practice making commits, creating branches, and making pull requests.

## About These Instructions
* Items `highlighted in gray` indicate buttons or specific text 
* Items in a code block will be entered into a terminal
    
    For example, you can copy and paste this text into a terminal:

        open index.html

* Text in <angle brackets> should be customized to your project - do not type the angle brackets themselves

    For example, if the instructions say:

        git checkout -b <branchName>
    
    You would actually type:

        git checkout -b featureBranch

## Copying This Repo to Your Machine
1. In your terminal, naviagte to the location where you would like to save the code.
2. Create a new directory for your code: 

        mkdir <newDirectoryName>

3. Navigate into the new directory: 

        cd <newDirectoryName>

4. In your computer terminal, open the directory in Visual Studio Code:

        code .

5. Open a terminal in Visual Studio Code (Terminal > New Terminal)
6. In GitHub, click the green `code` button in the Practice Repo and copy the repo path
7. In the VS Code terminal, type: 

        git clone <paste code location that you copied from GitHub>

8. The files in your GitHub repo should appear in VS Code 

## Contributing to This Repo
1. In the VS Code terminal, create a new branch: 

        git checkout -b <newBranchName>

2. Make desired changes in VS Code on your local Machine
3. In the VS Code terminal, **Track** all changes in git: 

        git add .

4. In the VS Code terminal, **Commit** the changes in git: 

        git commit -m "Add a message about the changes" 

5. In the VS Code terminal, push the changes to GitHub: 

        git push

6. Open the repo in Github and click the `Pull requests` tab
7. Click the `New pull request` button - make sure that the main branch is on the left and your new branch is on the right
8. Click the `Create pull request` button
9. An adminstrator will be notified that you have created a pull request - they will either approve or deny it  
10. After your branch is merged with main you can usually delete your branch