How to use Git
==============

What is Git?
------------
What happens when you are working on a project, but you want to make regular backups in case you need to recover a past version of the project? Maybe you save all the files into a folder called `My-Project-Backup-1`, then `My-Project-Backup-2` and so on. This can become tedious, and isn't much help if you are trying to find a specific version of your project where you changed a particular feature.

Also, what happens if you want to collaborate on a project? Do you change some features, then send them your edited version over email, and vice-versa? What happens if your collaborator edits the same file as you? Do you just copy and paste their changes into your files? 

**The solution is git**.

*Git* allows you to make changes to files, and then take a snapshot of the project's current state while adding a caption for its current state, such as "Changed introduction of research section".

Git solves the mentioned problems:
1. If you make a mistake, or need to see a previous version, you can look through your previous snapshots (usually known as 'commits') and find the relevant caption/commit message, and then look at the files there.
2. Collaborating on projects is made easy, since Git figures out what has been changed, and then tries to merge these changes automatically. If there are any clashes, Git will ask you to fix these manually, but usually there are no problems.

How to use Git
--------------
1. [Create a GitHub account](https://github.com/join).
2. Fork the repository you wish to edit by clicking the `Fork` button at the top right of the repository page.
   ![Forking](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
3. Download [GitHub Desktop](https://desktop.github.com).
4. Sign into GitHub Desktop.
5. Clone the repository you wish to edit to your computer.
   `Put image here`
6. Create a new branch called `my-changes`.
   `Put image here`
7. Make the changes to the files on your computer (make sure you are on the `my-changes` branch).
8. Create a pull request
	1. Click on the rightmost circle in GitHub Desktop.
	2. Write a summary for your changes (and a description if you wish).
	3. Click `Commit to my-changes`.
	4. Click the `Pull-request` button, then click `Send pull request`.
	5. Wait for the pull request to be accepted, and your changes will be public.
	
After you have done this for the first time, you can follow these steps:
1. Click the sync button.
2. Create a new branch (with any name that it not shown in the list of branches (e.g. `my-changes-2`)).
3. Make your changes
4. Create a pull request.
	1. Click on the rightmost circle in GitHub Desktop.
	2. Write a summary for your changes (and a description if you wish).
	3. Click `Commit to my-changes`.
	4. Click the `Pull-request` button, then click `Send pull request`.
	5. Wait for the pull request to be accepted, and your changes will be public.