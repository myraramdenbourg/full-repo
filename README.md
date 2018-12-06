
# full-repo

Goals:

1. Remove the last two commits from `develop` branch and push to remote

2. Create a PR against `master` and resolve conflicts

3. This one is a three parter

    a. Create and switch to a new branch based of off `develop` called `experimental`, remove file2 and push `experimental` to `full-repo`.

     b. Next, create a new repo called `partial-repo` and push `full-repo/experimental` to `partial-repo/master`.

    c. Now make another change on `experimental` and commit, then push only that commit to `partial-repo/experimental`

4. Make changes on `develop`, make the these changes reflect on both `full-repo/experimental` as well as on `partial-repo/experimental`.
