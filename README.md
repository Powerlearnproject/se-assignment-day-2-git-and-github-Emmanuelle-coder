[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15861590&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?

Answer
Version Control is a tool used to track chages in computer operations for example when a file is deleted it helps you know who deleted the files and when. GitHub helps track the commands initiated by different users on different file system.Git is an example of a version control system

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?

Answer
Step 1: Download Git from the GIt website and Install, then check the version of Gitbash through a command git --version control
Step 2: Create a github account and log into the account
Step 3: Navigate the Github account to the green button "New" to create a new respository. Assign the respository a name that is available and give it a shhort description
Step 4: Is to specify if the respository will be public or private( this will depend on the project your working on
Step 5: To initialize the respository i would check the box of "ADD a README file". This will give an opportunity to use a text file to describe the contents of my respository
Step 6: I will add a gitignore for files or templates i may not want to track
Step 7: Select a lincence for my git and the respository examples of such licence is the MIT
Step 8: i would click "create respository" button 

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?

Answer
README file is the place where i will communicate the contents and resources of my respository. its a text file. Its also used to initiate a respository

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

Answer
A respository can be public if one want to share it with everyone, anyone can see and maybe collaborate while private respository are those that we may not want to share with anyone
A private respository maybe a special respository with private project in which if it has to be shared, one have to share the log ins with other people


## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

Answer
Step 1: Configure Git using Git config --global user.name "my username on repor"
Step 2: Configuer Git email using Git config -- global user.email "my email on repo"
Step 3: Initialize git using Git Init to help git start tracking the repo
Step 4: Check the status of the local respository through git status to see any files that are not tracked but are on the local machine
Step 5: Use git add to add any file that are not accessible to remote Repo. If they are many files i will use the command Git add .
Step 6: Recheck the status to ascertain that all files are added, staged and are ready for transfer from local respository to the remote respository (Commit)
Step 7: To commit, i use command Git Commit -m"My message" . The message will explain why i decided to commit.it will help me and other developers understand the code
Step 8: Check status if there is anything pending to commit
Number of commits made can be seen through Git logs


## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

Answer
In the repo, once you begin editing and make a change, there is need to commit changes in the code. Once we graphically commit chages, there will be a commit box asking me to input the "commit message" followed by a large chatbox which allows for an extended description
Branching works like a sub/Small respository that one can work on and once the coding is done, we can transfer the changes to the main respository for example one may be working by a version 1 of an application which is fully functioning and realises that the version may need more features. So the developer will use a sub/Small respository (Branch) then Merge/update the features on the  main respository for upgrade. 
To create a branch, click/Check the "create a new branch for for this commit and start pull erquest" and assign the branch a name of your choice, Then click on the propose chages green button to save changes
The git will display a green message indicating word " able to merge" to the main/Original repo that was created


## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

Answer
Pull requests help one save changes from the sub/ brached repo to work on the main repo. They kind of help pull requests as the name suggests from the branch repo to the main repo
Step 1: I ould create a pull request by clicking the "create pull request button"
Step 2: The request wil check the ability for automatic merger between the main and the branch respository just incase there are any conflicts
Step 3: Once the check is done and everything okay, click on the merge pull request  and confirm merge
Step 4: Delete the brach request once the merger is success


## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

Answer
Cloning is done when the remote respository is cloned/Copied to a local respository through Git clone and then the link of remote respository is pasted. The link of the remote respository can be obtained from code and copying the HTTPS link while Forking is the opposite which is staging the trasfer from a local repository to a remote repository. Forking therfore means merging what  you have done on the local repo onto the remote repo


## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

Answer
Issues  and project boards help Plan and track my work on github, it shows which kind of work is in progress. one can track issues in another big issues that are related

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
Answer
Some common pitfalls is failing to git commit, that is copyng someones work
