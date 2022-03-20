# Art 277 section 4
Art 277 Assignment #1 section 4 march 20, 2022

1 Explain in your own words the terms Git and Github.
 Git is the most pooular version control system which allows you to record changes to your files over time or allows for different people to work on the same project at the same time. While Github is cloud based service which allows developers to stored and manage their code and projects.

2. Explain the steps to download, install, and configure, Git on your PC.

* Open browser.
* Enter URL https//git.com in the internet browser address bar.
* Click the download link to download git.
* Once downloaded, start the installation from the browser on the download folder.
* In select components windows, leave all default option checked and check any other additional components your want installed.
* Open the command line.
* say tour username: git config... global-username "FIRST-NAME - LAST-NAME".
* Set your email "MY-NAME@example.com"

3. Discuss the process to create and intialize a project in git.

* The first file to create and add and commit is probably a ReadMe file, either as plain text or with markdown, descrbing the project.

4. Explain the steps to pull and Push from a local repository to a remote repository.

* Git remote add origin - after you created a repository on a service in a above case github, you need add it as a target remote repository.
* Git branch m master- in. This case,if i want to push my current master branch which was called main instead master, and the repository at the remote has a branch you want to do force rename of the local master branch.
* Git push u origin master- push the branch to the remote... The u option will automatically set the upstream branch for you.

5. In your own words, explain the terms, push, pull, commit, stage,and branches in Git.

* The push command is used to transfer the commit, which is made on local branch in your computer to a remote repository.
* The git pull command is used to fetch and download content from a remote repository and update the local the local repository to match that content.
* The git commit command capture a snapshot of the project currently staged changes.
* The git stage allows you to continue making changes to the working directory.
* In git, branches are a part of your everyday development process.
