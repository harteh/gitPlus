# gitPlus

## git test
+ git
  - git add .
  - git status
  - git commit -m "커밋메시지"
  - git push origin 브랜치명  
<br>  

+ git clone  
  - git clone <git_URL>  
<br>

+ git remote  
  - git remote add origin <REMOTE_URL>  
  - 원격 URL 확인 : git remote -v  
  - 원격 리포지토리 이름 변경 : git remote rename 기존이름 새로운이름  
  - [GitHub Docs](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories)  
  - [브랜치명 변경 후 로컬 업데이트](https://docs.github.com/ko/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/renaming-a-branch#updating-a-local-clone-after-a-branch-name-changes)
  ```bash
  $ git branch -m OLD-BRANCH-NAME NEW-BRANCH-NAME
  $ git fetch origin
  $ git branch -u origin/NEW-BRANCH-NAME NEW-BRANCH-NAME
  $ git remote set-head origin -a
  ```

<br>

### javascript-for-beginner  
바닐라 JS로 크롬 앱 만들기  
