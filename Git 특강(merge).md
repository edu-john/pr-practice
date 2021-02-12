## Git

- branch : 하나의 commut 라인들을 말한다. 
- git 사용전에는 파일을 FTP를 사용하여 server에 전달했는데 번거로움이 많았다. 하지만 ssh로 접속해야 하고 많은 과정이 있어서 이제는 cp로 Master에 파일이 올라오면 자동으로 처리하게 구조화 되었다. 
- 쓰는 이유 : Master에서만 코딩을 하면 문제가 발생하면 관련되지 않는 부분도 문제가 발생하는데 Branch를 사용하여 각각으로 작업할 수 있도록 하기 위해서

- commit 확인은 "git log"
- commit 의 저장을 돌리는 방법 "git 
restore [파일명]"
- git reset [파일명] : commit 전으로 복원 
-branch는 일회용이다. 즉 사용후에는 지운다.
- branch는 다른 공간으로 인식한다.
- 명령어의 시작은 "git branch"로 시작 한다.
<명령어>  
        git branch : 현재 branch 확인

        git branch [브랜치이름] : 새로운 ranch 생성
        git switch [브랜치이름]: branch 이동     
        - 
        

        git switch [브랜치이름]: branch 이동 (-c 는 만들면서 이동까지)(git checkout [브랜치이름] , -b 하면 이동하면 서 만든다.)

        git merge [브랜치이름] : 브랜치 병합(병합은 항상 Master로 변환후 사용)

        git branch -d [브랜치이름] : 브랜치 삭제(한번 사용하고 merge 한 브랜치는 지우고 사용한다.)

## Merge 시나리오 
- fast-forward branch가 '하나'일때 해당 head로 master만 이동 시키는 것 

- Auto-merge(conflict 없는 merge) : 자동으로 merge 해주는 것, 다른 파일이니 문제가 없이 merge

- Merge with conflict : 같은 파일을 건들면 문제(conflict)가 발생한다. 그걸 해결하는 법 (master, branch, 둘다 3종류로 남길 수 있다.)

## Conflict 발생(되도록이면 파일을 분리시키는게 좋은 점)
1. 이젠 conflict가 날거야. 같은 줄을 수정했으니 (master에서 작성)
##Conflict 발생
1. 이건 conflict 발생







    
        
