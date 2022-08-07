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

	// If your git branch has no upstream branch then use 
	git push --set-upstream origin add-information
# git checkout
With checkout you can switch to other branches or creating them.
#### Commands
	git checkout <branch-name> // switch to the other branch
	git checkout -b <branch-name> // create a branch and switch to them
# git branch
You can create, delete or list all branches.
#### Commands
	git branch <branch-name> // create a new branch
	git branch // list all branches
	git branch -d <branch-name> // delete a branch

	// Provides more information about all your branches
	// By default will only show locak branches
	// Flag -a : Remote branches will includes in the list
	// Flag -v : Make command more "verbose" (add hash and last commit message)
	git branch -a -v

	// To show all branches that not been merged into your current HEAD branch
	git branch --no-merged