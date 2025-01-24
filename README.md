# test-conflict
**Use merge in shared/team branches (e.g., main or dev) to keep the full history.
Use rebase in your private branches to tidy up history before merging.






Use merge in shared/team branches (e.g., main or dev) to keep the full history.
Use rebase in your private branches to tidy up history before merging.





## git rebase
**

**
Think of it as replaying commits from one branch onto another.
It rewrites history by moving the commits from your branch to the tip of the branch you’re rebasing onto.
This creates a cleaner, linear history.
When to use?
When you want a clean and linear history, as if all changes happened one after the other without any branching.**


### git merge
**
Think of it as combining branches while keeping their histories intact.
It creates a new merge commit that ties the histories of both branches together.
The original commits in both branches remain unchanged.
When to use?
When you want to preserve the history of both branches, showing how and when branches diverged and came back together.**