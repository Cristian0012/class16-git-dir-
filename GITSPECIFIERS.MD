
Log: Displays the commit history.
	git log: Shows the commit history with details.
	git log --oneline: Displays a condensed version of the commit history.

Show: Shows information about a specific commit or reference.
	git show <commit_hash>: Displays detailed information about the commit.
	git show <branch_name>: Shows information about the latest commit on the branch.

Diff: Shows changes between commits, branches, or other references.
	git diff <commit_hash> <commit_hash>: Shows differences between two commits.
	git diff <branch_name> <branch_name>: Displays differences between two branches

Commit Hash:
	3a2b9c8: Refers to a specific commit identified by its unique hash.

Branch Name:
	master: Refers to the branch named "master".
	feature/xyz: Refers to the branch named "feature/xyz".

Tag:
	v1.0.0: Refers to the tag named "v1.0.0".
	mytag: Refers to the tag named "mytag".
Relative References:

	HEAD: Refers to the current commit on the current branch.
	HEAD~2: Refers to the commit that is two parents behind the current commit.
	HEAD^: Refers to the commit's parent (same as HEAD~1).
	master~3: Refers to the commit that is three parents behind the "master" branch's current commit.
