```
1 git 이란 
버전 관리 도구

2 github 
온라인 저장소

3 git 명령어

초기 설정 git init

이름과 이메일 저장
git config --global user.email "email"
git config --global user.name "name"

파일 지정 git add 파일명
파일 저장 git commit -m "커밋 메세지"

상태 보기 git status

저장 내역 확인 git log

브랜치 생성
git branch 브랜치이름

브랜치 이동
git switch 브랜치이름
git checkout 브랜치이름

브랜치 정보 확인
git branch 

합치기
git merge

git stash -u -m "메세지"
add, commit 없이 브랜치 이동하려고 하면 이동 불가
이 때, 임시로 저장할 수 있는 명령어
stash 하면 변경사항안 안 보이게 된다

git stash list
스태쉬 내용 확인

git stash apply stash@{숫자}
스태쉬 내용을 적용
숫자는 스태쉬 내용을 확이 했을 때 나오는 숫자

git reset --hard 커밋 아이디
git reset --mixed 커밋 아이디
git reset --soft 커밋 아이디

리셋은 예전 커밋으로 돌아가는 것

커밋 3개 -> 리셋 후 -> 커밋 2개

git revert 커밋 아이디

과거 커밋을 다음 커밋으로 갖고 와서 사용

커밋 3개 -> 리버트 후 -> 커밋 4개

vim
i insert 입력
esc 입력 완료
:wq 나가기
:w! 강제로 나가기

github 사용하기

repository 만들기 
처음 저장소 만들 때, readme.md 파일을 같이 만들어주기 -> 초기 init과 같음

git clone 깃주소 
원격 저장소 내용 갖고 오기

git push origin 브런치이름

git pull origin 브런치이름
원격 저장소 내용이 최신 버전이면 merge 한다
충돌 일어날 확률 있음 

git fetch origin 브런치 이름
merge는 하지 않는다

.ignore 파일
git이 관리하고 싶어하지 않는 내용을 저장해둔 파일
[.ignore.io]http://ignore.io

readme.md
프로젝트 설명, 협업 방법 등을 설명해둔 파일

```