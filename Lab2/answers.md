Answers for Lab 2 (1/22/2025)

1. ```2.46.2```
2. ```
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    user.name=CollinInMySternum
    user.email=projectunkowngame@gmail.com
    core.repositoryformatversion=0
    core.filemode=true
    core.bare=false
    core.logallrefupdates=true
    lfs.repositoryformatversion=0
    remote.origin.url=https://github.com/CollinInMySternum/CS2400-Spring2025.git
    remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
    branch.main.remote=origin
    branch.main.merge=refs/heads/main
    [collinblumenauer@archlinux CS2400-Spring2025]$
    ```

3.  ```Lists all possible commands for git ```
4. ```
    On branch main
    Your branch is up to date with 'origin/main'

    Changes to be committed
    ...

    Untracked files:
    answers.md, README.md
    ```

5. ```
    On branch main
    Your branch is up to date with 'origin/main'

    Changes to be committed
    README.md

    Untracked files:
    answers.md
    ```

6. ```
    On branch main
    Your branch is up to date with 'origin/main'

    Changes to be committed
    README.md, answers.md

    Untracked files:
    ...
    ```

7. ```
    On branch main
    Your branch is up to date with 'origin/main'.

    Untracked files:
    ...
    ```

8. ```
    (HEAD -> main, origin/main, origin/HEAD)
    Author: CollinInMySternum <projectunkowngame@gmail.com>
    Date:   Wed Jan 22 18:49:46 2025 -0500

        Initial Commit #3

    ...
    ```

9. ```
    On branch main
    Your branch is up to date with 'origin/main'.

    nothing to commit, working tree clean

    ```

10. ```
    No, the local repo will not reflect the most recent version. You would need to pull origin.
    ```
11. ```
    The push command pushes files from the local repository to the remote repo, making it available on web.
12. ```
    Yes, the changes made online are reflected in the local copy, because of git pull.

    The git pull gets the most recent version of the repository from the remote repository.
    ```

13. ```
    .  ..  .git  .gitignore  README.md
    ```