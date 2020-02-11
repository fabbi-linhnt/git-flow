# git-flow

1. Init git flow: git flow init
  - Release branch: master
  - Develop branch: develop
  - Feature/task branch: feature(or task)/[feature/task name]
2. Develop feature/task:
  - git checkout -b [branch name]
  - git add .
  - git commit -m [message]
  - git rebase develop
  - git push origin [branch name]
