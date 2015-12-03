My Experiences with Git and GitHub
==================================
1. create an account in **Github** :octocat: [GitHub](https://github.com/)
2. create a Public Repository with **default README.md** file
3. download [**Git** for windows](https://git-scm.com/downloads) and Install it

4. in your windows desktop, move to your current windows user folder
5. **Git** considers this as **root directory** 
6. GitHub Repository folders can be found here in future

7. now, open **Git Bash** from windows programs menu
8. it is a command line editor
	+ maintain email-id and Github user name in configuration file ( one time activity)  
		+ git config --global user.email "your email address mentioned in github account"  
		+ git config --global user.name "your github account user name"  
9. **Clone** your Central Repository from GitHub into your Local System  
	+ git clone https://www.github.com/<github username>/<repository name>.get  
	+ use same command to synchronize Central and Local Repositories, when repository Files are deleted
10. Then a folder with repository name will be created in Root directory**
11. move into folder from git console  
	+ cd <repository name>  
	+ use **cd ..** to come back if necessary  
12. create or modify files/folders of this repository folder from windows desktop
13. Add the files/folder to Staging area  
	+ :octocat: **git** add folder1  
	+ :octocat: **git** add folder2  
	+ :octocat: **git** add file1  
	+ :octocat: **git** add file2  
	+ :octocat: **git** add *.txt  
	+ :octocat: **git** add *.*md
14. Commit these Staged items to Local Repository  
	+ **git** commit -m "1st version :octocat:"
15. Push the Local Repository items to Central Repository  
	+ **git** push -u origin master
		
		