## Setup:
```shell
git checkout commit-on-wrong-branch && ./setup.sh
```

## The task

1. Use `git log --oneline --graph --all` to view all the branches and their commits.
2. Copy `C` onto `master` before `B` by rebasing `quickfix` on `commit-on-wrong-branch`.
3. Make a new branch (`changes-including-B`) off of our `commit-on-wrong-branch` so we can keep working on `B`.
4. Reset `commit-on-wrong-branch` back to `C`.
5. Delete the `quickfix` branch.
6. Push `commit-on-wrong-branch`.
7. You can merge the `changes-including-B` branch to `commit-on-wrong-branch` and delete `changes-including-B` or just switch to `changes-including-B` and work there.
