# git branch 명령어 정리

- add text
- 브랜치 전환
- git checkout {branch_name}
  - `-b` : 생성하면서 전환 
- git switch {branch_name}
  - `-c` : 생성하면서 전환
- 브랜치 삭제
  - git branch -d {branch_name}

- 커밋 히스토리 확인
  - git log --oneline --graph
  - `--oneline` : 간소화해서 출력
  - `--graph` : 그래프 형태로 출력
  
- 병합
  - git merge {target-branch}
    - 현재 내가 있느 브랜치에 타겟 브랜치를 가져와서 병합
  - `--graph` : 그래프 형태로 출력
