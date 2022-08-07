# git init
Initialize (create) a new git repository 
#### Commands
	git init

# git clone
Clone a respository from a source

    git clone <repository URL>

# git pull
Downloading changes from repository and merge it.
#### Commands
	git pull
# git add
Bookmark a file for your commit.
#### Commands
	git add <filename.ext>
	git add -all
# git commit
With the commit you create a snapshotof your project. You using commits to create versions of your projects. Commits have some meta informations:
1. Author of commit / Email Address
2. Commit-Message
3. Timestamp
4. Unique hash value
5. The previous commit
#### Commands
	git commit -m "add here a message"
#### Example
|(1)----------(2)-------------(3)------->

1. First commit of your project
2. Add new UI
3. Add calculation tax feature
# git push
Uploading your changes to the repository.
#### Commands
	git push
# git checkout
With checkout you can switch to other branches or creating them.
#### Commands
	git checkout <branch-name> // switch to the other branch
	git checkout -b <branch-name> // create a branch and switch to them