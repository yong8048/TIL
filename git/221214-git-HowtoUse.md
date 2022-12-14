How to Make branch and Use, I learned Today
1. What is Branch?
 - Branch란 분기점을 생성하여 독립적으로 코드를 변경할 수 있도록 도와주는 모델
2. Branching Models
 a. git flow : (hotfix) - master - (release) - develop - feature
   - 장점: 가장 많이 사용, 각 단계가 명확이 구분.
   - 단점: 복잡함.
 b. github flow : master - feature
   - 장점: Branch모델의 단순화, master의 모든 커밋은 deployable
   - 단점: CI의존성이 높고, 팀원 중 한명이라도 실수하면...
 c. gitlab flow : production - pre-production - master - feature
   - 장점: deploy, issue에 대한 대응이 가능하도록 보완.
   - 단점: git flow와 반대.
3. Commands
 a. Rename
   - Worst : mv server,py main.py  -> 삭제 후, 파일을 새로 생성
   - Best : git mv server.py main,py -> renamed
 b. Undoing
   - git checkout --
 c. Unstaging
   - git reset HEAD {filename} : reset은이력이 남지않아 권고하지않음.
   - git revert --no-commit HEAD~{갯수} : 이력이 남는다.
 - git branch : 현재 생성되어있는 Branch를 볼 수 있음.
 - git branch -m "바꿀이름" : 현재 위치해있는 Branch의 이름을 변경


