# This is a test repo for colab learning - branching and merging

## Please clone the repo, look at the index.html file and follow the merging rules of git-hub to get the project Master doc updated.

Clone:
    TYPE: git clone (PASTE_REPO)

After you clone - make sure you are in (master)
    
Check branch :
    TYPE : git branch

Fetches all the code from GitHub and merges to our master locally
	    TYPE: git pull origin master 

PULLING (creating) new branch
	TYPE: git checkout -b example-name <---- (create a branch name)

========= WRITE YOUR CODING =========

ADDING To Branch
	TYPE: git add .
		    git commit -m "YOUR_MESAGE"
		   
PUSHING to remote before merge  
	TYPE: git push origin example-name <---- (branch name you created above)

AFTER MERGE YOU MUST UPDATE YOUR master:
	git checkout master
	git pull origin master

And now you can repeat the steps above to create new branch