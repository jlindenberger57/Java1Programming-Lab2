# Java1Programming-Lab2
* Question - How do you see the files changed within each commit from git log?
* Answer - Type "git show --name-only"  This shows the name of the files changed.  Also, once git has been initialized, you'll see a git pane at the top-right that shows what files have changed.
* Question - How do you see the contents of what changed within each file from the git log?
* Answer - You can click the .Modified icon, and also with a "git diff" command.  Also, the "git patch" command can be used.  In addition, you can also try "git diff --staged" to determine what changes were staged versus un-staged.
* Question - What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
* Answer - When typing "git diff HEAD", the diff compares your working tree to the HEAD commit .  This HEAD commit is the most recent commit in history.
