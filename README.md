Git Basics

=========
**TERMINAL BASICS**

cd - change directory
cd.. - will go up one folder in the directory
ls - will list all the items inside the working directory Always start by typing this out first

=========

Git Repository for current git testing folder

https://github.com/soujohn/gitTest01.git

	•	**git clone** ‘URL’
		⁃	This will clone a copy of any repository using its URL to your working directory
	•	**git status**
		⁃	This will show us what’s different from the working directory and the repository on gitHub online
			⁃	new files
			⁃	modified files
	•	**git add**
		⁃	This will add changes(stage files) to be committed to the repository
	•	**git commit -m** “message”
		⁃	GIT COMMIT This will commit your changes to the repository, but it still only exists on your machine. The change still hasn’t been synced up to github.com
		⁃	-M This indicates that you are adding a messages/description to this file when it gets committed to the repository
		⁃	“MESSAGE” This is the message/description you include to document changes you’re making. You’re message must be within quotation marks
	•	**git commit** (sans -m) full commit
		⁃	commits changes and expects a multiline message to be typed in
		⁃	to escape from a full commit ESC :WQ
			⁃	This will still commit your change even if you don’t enter a message
	•	**git push**
		⁃	This will take whatever is on your machine and sync it up to github.com
	•	**git pull**
		⁃	This will pull down whatever you have in your repository on github.com into your working directory
	•	**git add .**, **git add -A**
		⁃	This will add everything that is in your working directory
