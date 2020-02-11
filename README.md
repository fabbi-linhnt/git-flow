# git-flow

1. Init git flow: git flow init
  - Release branch: master
  - Develop branch: develop
  - Feature/task branch: feature(or task)/[feature/task name]
2. Develop feature/task:
  - git checkout develop
  - git pull
  - git checkout -b [branch name]
  - git add .
  - git commit -m [message]
  - git checkout develop
  - git pull
  - git checkout [branch name]
  - git rebase develop
  - git push origin [branch name]
3. Create pull request to develop branch

## Rules:
1. One commit per pull request. if more than one, you have to merge commits.
2. Rebase with develop branch before create pull request

