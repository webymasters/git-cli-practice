
Q-1 Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
A-1 You can use any git command to test if it’s git rep such as
git status
Also you can look for the presence of a folder named `.git` using ls command.

Q-2 Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
A-2 git add hello-world.txt && git commit
This will ask you to add the commit message, give the relevant message and end the file using :wq

Q-3 Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.
A-3 git diff README.md

Q-4 Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.
A-4 git show abc123

Q-5 Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.
A-5  git log --oneline -3


