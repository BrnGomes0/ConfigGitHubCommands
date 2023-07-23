# Basic commands to work with GitHub How to use GitHub - Step by Step

## Creating the first commit in a new repository. On the first machine

<strong>First Step</strong> → Create the repository on GitHub

Give the repository a name, configure whether it will be private or public, choose whether it will contain a Readme.md file.
<strong>Second Step</strong> → Open VisualStudioCode with the files open, and create a new terminal using GitBash.

<strong>Third Step</strong> → Follow series of git commands in order

If you are on your personal computer, the first two commands are only needed once. If it is on the BOSCH computer or one that is not yours, put it every time you commit.

<code>git config --global user.name "BrnGomes0"</code>
<br>
<code>git config -global user.email "brunownog05@gmail.com"</code>
<br>
<code>git init</code>
<br>
<code>git status</code>
<br>
<code>git add .</code>
<br>
<code>git commit -m "nameCommit" </code>
<br>
<code>git branch -M main</code>
<br>
<code>git remote add origin <link> (Uma única vez)</code>
<br>
<code>git push -u origin main</code>
<br>
Your first commit has been performed. Your repository will contain your committed files. 

### If you change any other files and want to commit in the same repository using the SAME MACHINE, just follow the codes below:

<code>clear</code>
<code>git add .</code>
<code>git commit -m "SecondCommit"</code>
<code>git push</code> 

## ACCESSING THE REPOSITORY FILES ON A DIFFERENT MACHINE

<strong>First Step</strong> → Open the terminal in Visual Studio Code and issue the following commands
<code>cd <nameFile> </code>

<strong>Second Step</strong>  → Inside the selected folder, put the following code:
<code>git clone <LinkRepositoryAlreadyCreated></code>

<strong>Third step</strong> → Open the folder inside the folder created in the first step:
<code>cd <nameFile></code>

<strong>Fourth step</strong> → To view the status of files in the folder
<code>git status</code>

<strong>Fifth step</strong> → Change branch from master to main
<code>git branch -M main</code>

<strong>Sixth step → Add all changed files</strong>
<code>git add .</code>

<strong>Seventh step</strong> → After adding all the files, commit to upload the new files with the necessary changes on github
<code>git commit -m "nameChosen"</code>

<strong>Eighth Step</strong> → Push the files to the repository
<code>git push</code>
