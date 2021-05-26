# Github

## 1. fork한 레포지토리는 커밋을 해도 잔디가 안 심어집니다
- 해결방법으로는 새로운 레포지토리를 만들어서 거기에 다시 커밋을 진행하는 거밖에 없다고 합니다...

## 2. branch에서는 커밋을 해도 잔디가 안 심어집니다.
- 해결방법으로는 master로 merge를 시키면 자신이 해왔던 커밋들이 잔디로 심어진 것을 볼 수 있습니다.

## 3. error: Your local changes to the following files would be overwritten by merge:
- 해결방법 1 : git stash
- 현재 디렉토리의 파일을 임시로 백업하고 깨끗한 상태로 돌린다.
- 버전관리 되는 대상 파일들을 임시저장 해둔다고 보면 된다.

- 해결방법 2 : git add 

## 4. gitignore
- .gitignore이란?
- Project에 원하지 않는 Backup File이나 Log File, 혹은 컴파일 된 파일들을 Git에서 제외시킬수 있는 설정 File이다

### 사용법
1) .gitignore 작성한다.
2) git bash창 실행
3) git rm -r --cached .
4) git add .
5) git commit -m "cache clear"
6) git push origin branch명
