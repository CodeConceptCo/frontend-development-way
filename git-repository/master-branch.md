## 1. Master branch 

Keep your **master** branch protected and use it only for the production-ready version of your application.

Merge code to master branch with pull request from develop with **Squash**. Squash merging is a merge option that allows you to condense the Git history of topic branches when you complete a pull request. Instead of each commit on the topic branch being added to the history of the default branch, a squash merge takes all the file changes and adds them to a single new commit on the default branch. A simple way to think about this is that squash merge gives you just the file changes, and a regular merge gives you the file changes and the commit history. This allows having a completely new version of application just in one commit.

Benefits

-   One commit — one release
-   Have a history of all releases in the commit history
-   Allow rolling back to any other version in case of emergency in seconds