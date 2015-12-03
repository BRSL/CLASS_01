:octocat: My Experiences with Git and GitHub :snail:
==================================
1. create an account in [**GitHub**](https://github.com/)

2. create a Public Repository with **default README.md** file

3. download [**Git** for windows](https://git-scm.com/downloads) and Install it

4. in your windows desktop, move to your current windows user folder

5. **Git** considers this as **root directory** 

6. GitHub Repository folders can be found here in future

7. now, open **Git Bash** from windows programs menu

8. it is a command line editor
	+ maintain email-id and Github user name in configuration file ( one time activity)  
		+ :octocat: **git config --global user.email** "your email address mentioned in github account"  
		+ :octocat: **git config --global user.name**  "your github account user name"  
		
9. **Clone** your Central Repository from GitHub into your Local System  
	+ :octocat: **git clone** https://www.github.com/[GitHub username]**/**[Repository name].git  
10. Then a folder with repository name will be created in Root directory**

11. move into folder from git console  
	+ :octocat: **cd** [repository name]  
	+ use **cd ..** to come back if necessary  
12. create or modify files/folders of this repository folder from windows desktop

13. Add the files/folder to **Staging area**  
	+ :octocat: **git add** folder1  
	+ :octocat: **git add** folder2  
	+ :octocat: **git add** file1  
	+ :octocat: **git add** file2  
	+ :octocat: **git add** *.txt  
	+ :octocat: **git add** *.*md
	
14. Commit these Staged items to **Local Repository**  
	+ :octocat: **git commit -m** "1st version"
	
15. Push the Local Repository items to **Central Repository**  
	+ :octocat: **git push -u origin master**
		
16. use the following command to synchronize Central and Local Repositories, when repository Files are deleted
	+ :octocat: **git pull -u origin master**