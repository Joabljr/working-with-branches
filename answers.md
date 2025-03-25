@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git branch
  add-css-file
* feature-add-player
  feature-test-branch
  test-branch

  @Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git branch test-branch
fatal: a branch named 'test-branch' already exists

3-@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git branch
  add-css-file
* feature-add-player
  feature-test-branch
  test-branch

  4-@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git switch test-branch
Switched to branch 'test-branch'

5-@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git switch test-branch
Switched to branch 'test-branch'
@Joabljr ➜ ~/.ssh/working-with-branches (test-branch) $ git status
On branch test-branch
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .answers.md.swp
        .asnwers.swp
        answers
        answers.md
        styles.css

nothing added to commit but untracked files present (use "git add" to track)
@Joabljr ➜ ~/.ssh/working-with-branches (test-branch) $ git switch feature-add-player
Switched to branch 'feature-add-player'
Your branch is up to date with 'origin/feature-add-player'.
@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ git status
On branch feature-add-player
Your branch is up to date with 'origin/feature-add-player'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .answers.md.swp
        .asnwers.swp
        answers
        answers.md
        styles.css

nothing added to commit but untracked files present (use "git add" to track)
@Joabljr ➜ ~/.ssh/working-with-branches (feature-add-player) $ 

6-It looks the same 

7-@Joabljr ➜ ~/.ssh/working-with-branches (test-branch) $ git switch feature-add-player
Switched to branch 'feature-add-player'
Your branch is up to date with 'origin/feature-add-player'.

8-same 

9-