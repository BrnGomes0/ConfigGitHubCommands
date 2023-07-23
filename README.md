#Basic commands to work with GitHub How to use GitHub - Step by Step


Creating the first commit in a new repository. on the first machine


First Step → Create the repository on GitHub

Give the repository a name, configure whether it will be private or public, choose whether it will contain a Readme.md file.


Second Step → Open VisualStudioCode with the files open, and create a new terminal using GitBash.

Third Step → Follow series of git commands in order

	If you are on your personal computer, the first two commands are only needed once. If it is on the BOSCH computer or one that is not yours, put it every time you commit.

<code>git config --global user.name "BrnGomes0"</code>
<code>git config -global user.email "brunownog05@gmail.com"</code>
<code>git init</code>
<code>git status</code>
<code>git add .</code>
<code>git commit -m "nameCommit" </code>
<code>git branch -M main</code>
<code>git remote add origin <link> (Uma única vez)</code>
<code>git push -u origin main</code>


Your first commit has been performed. Your repository will contain your committed files. 

If you change any other files and want to commit in the same repository using the SAME MACHINE, just follow the codes below: 


clear
git add .
git commit -m "SecondCommit"
git push 




ACCESSING THE REPOSITORY FILES ON A DIFFERENT MACHINE



First Step → Open the terminal in Visual Studio Code and issue the following commands
cd <nameFile> 


Second Step  → Inside the selected folder, put the following code:
git clone <LinkRepositoryAlreadyCreated>


Third step → Open the folder inside the folder created in the first step:
cd <nameFile>


Fourth step → To view the status of files in the folder
git status

 
Fifth step → Change branch from master to main
git branch -M main


Sixth step → Add all changed files
git add .


Seventh step → After adding all the files, commit to upload the new files with the necessary changes on github
git commit -m "nameChosen"


Eighth Step→ Push the files to the repository
git push


