# Githubsetupandwork
# *This Documention will let you know, how to setup and how to push your code from local machine to github Repo*  

Step 1:  
1) Go to Git official Website and download the Git which suits your machine  
2) Run the file downloaded, choose default options and make sure "Git from the command line" option is selected.  
3) once it is done, type "git --version" in cmd, which confirms the successfull installation of git.  

Step 2:  
1) This step is to setup your profile at git. It is like telling the remote repo, who you are!  
2) run the following:  
3) git config --global user.name "your email"  
4) git config --global user.email "your_emailaddress@domain.com"  
5) once the configuration is done, we will recheck it by typing the following: **_git confg --list_**  

Step 3:  
1) Configuration of your profile is done, now we need to initialize the git, (its like starting the Git)  
2) go to your code folder, by using cd path/to/your/folder  
3) type "git init"  

Step 4:  
1) Work realted to our local machine is done, now we need to work on github, where our code goes and stays.  
2) Got to Github and Login  
3) Create New Repo  

Step 5:
1) Now copy the link which is available with your github repo.  
2) and run the following in your local machine, _**git remote add origin https://github.com/so/and/so**_
3) This is like mentioning, this is the repo our code goes and stay. here I have used github, you can use any Repo to store your code.
4) after adding, verify it by using _**git remote -v**_

Step 6:
1) Now our remote repo is also ready. Now we need to pack our code in our local machine to go to the remote repo.  
2) git add .  
3) git commit -m "Initial Commit".

Step 7:  
1) Now our code is packed and ready in our machine, Now we need to move it to github.  
2) git branch -M main  
3) git push -u origin main (for the first time)
4) git push (from the next time)


# **Happy Gitting** 👨🏻‍💻
