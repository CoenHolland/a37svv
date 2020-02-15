# a37svv
### Git 101
Make sure to run these in your **cmd**, once you have navigated into the SVV folder, e.g. `$cd 'C:\Users\dsmor\AE BSc\SVV'`
You can verify that you are in the repository folder by running `$git status`  

To update your local repository with the most up-to date version, do a `$git pull`  

If you change anything (locally) in your repository, do a `$git status`  
This will show you any changes that were made - untracked changes will be red  
To add these changes, you must first 'stage' them by doing `$git add 'whateverfileyouadded.txt'`  
If you do a `$git status` again, then you will see the stage files to the next commit in green

Then, you commit it to the repository using `$git commit -m "An explanatory message of what I did"`  

Now, once you commited your file, do a `$git push -u origin master`  
This command now pushes your changes onto our repository  



We are going to be breaking like all of the good git practices by just doing it this way, but it's better than nothing!


