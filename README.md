# Intro to Command Prompt

## Shortcut Commands
* Windows + R 
	* opens the command runner

* Ctrl+C
	* copies highlighted text
* Ctrl+V
	* pastes the copied text   

## Basic Commands
* `cmd`
	* opens the command prompt 
* `cd the-specified-directory`
	* changes the directory to `the-specified-directory`
* `cd .`
	* changes to current directory
* `explorer .`
	* opens current directory 
* `dir`
 	* lists all files in the current directory
* `mkdir`
	* create a folder in the current directory  




# Creating a Repository
## Create a Repository on the Web
1. Navigate to Github.com
2. click on your icon at the top right and select "repositories"
3. click "new" button at the top left of browser



## Create a Repository on your local machine
1. Navigate to the root folder of the project you would like to become a repository.
2. `git init` - tells this directory that it is a repository
3. `git add .` - adds all _changes_ in this directory to the repository
4. `git commit -m 'my update message'` - commits these changes to be pushed onto the web
5. `git push -u origin master` - _pushes_ the changes onto the web, making them accessible through the _cloud_