* download + install + get github account.
* pencil+paper
	* constrained atomic operations
	* time limit - visible
	* (1 change -> merge )x2?
	* test beforehand
* reflect
	* what challenges did you face
	* how did you resolve conflicts
		* if one person deleted, another changed?
	* did you keep track of all changes
		* who did what?
	* **introduce terminology**
* repository
	* explain what a repo would be for pencil+paper activity
	* explain what it looks like on computer - folder w/ super powers
	* show branch graph of officer sentence
* overview of basic commands, following with sentence example (different sentence?)
	* `git init` - turn folder into repo
		* `git init newFolderName`
	* make file
	* `git status`
	* commit - general concept
	* `git add` - add some files to our codebase (add md file of sentence)
	* `git add`/`git commit` -
		* focus on getting you to understand
		* staging vs commit
		* add a file before commit
		* saving for git
		* make changes -> add files to staging area -> commit
		* `git commit -a` adds all modified files and commits in one command
	* `git branch`/`git merge`
		* `branch -b` / `checkout`
		* not strictly necesary
		* talk about best practice
		* local only - makes sense for servers too
		* (have made at least two changes before branching at this point)
		* make 2 additional changes (commits)
		* `git checkout master` before merging to show difference
		* `git merge master` while on the new branch
		* fast forward merge vs conflict
	* `git clone` - run through github new repo and groups select their MCP
		* one person in each group, create a repo, everyone else clone it.
		* server vs. local
		* *multiple* repositories, not a copy of a single repo.
	* `git push`/`pull`/`fetch`/`merge`
		* in groups, make some changes and commits locally
		* in groups, merge all your changes into the MCP's repo (remote server) `git push origin master`
		* if there is a conflict, you will need to merge **before** you push.
		* to *fetch* remote changes, and *merge* those changes, `git pull` command.
