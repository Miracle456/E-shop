# Steps to follow to create a new project and setup github

## Creating a Github Repository

- Move on to new reposetory on github and then give it a name and then hit "create repository" button to to create a public repository.
 - Then copy the command to link the github repository with folder present in your pc.
 for example: 
 - ``` git remote add origin https://github.com/Miracle456/E-shop.git``` 

 ## Creating Project Folder in you laptop

 - Create a folder with project name in any location of your pc like desktop , documents.
 - Open that folder in Visual Studio Code and add index.html file in it.
 - Add some code inside index.html.
 - Then Open terminal and navigate to the folder you created.
 - To navigate to the desired folder use following command :- 
 - ```ls``` (to show all the file and folders present inside the current folder)
 - ``cd folder_name ``(this command is used to change directory[folder])

 ## Commands use to setup git folder in pc in order

 1. ```git init``` (It initializes the git in local folder)
 2. ```git add .``` (Here we bundle up all the changes)
 3. ```git commit -m "(type in a message about what you changed/did)"```
    (commit is a breakpoinnt on which we can come before)
 4. ```git push origin master``` (use to push the code to github)