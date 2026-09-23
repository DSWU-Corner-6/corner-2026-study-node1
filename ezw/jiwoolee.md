깃 최초 설정

git config --global user.name "username"
git config --global user.email "username@gmail.com"

현재 폴더를 Git으로 버전 관리할 수 있는 로컬 저장소(Repository)로 초기화(Initialize)하는 명령어
git init

현재 git 저장소와 작업 트리를 보여주는 명령어
git status

브랜치 생성
git branch name

브랜치 목록 확인
git branch

다른 브랜치로 이동
git switch (신규 브랜치 명)

브랜치 생성과 이동을 동시에 하기
git switch -c (신규 브랜치 명)
git checkout -b <새로_만들_브랜치명>


로컬의 git 저장소에 원격 저장소로의 연결 추가
git remote add origin (원격 저장소 주소)


로컬 저장소의 커밋 내역을 원격으로 push (업로드). origin의 main branch로 push
git push -u origin main

로컬에 쌓인 커밋을 GitHub으로 올려서 팀원과 공유합니다.
git push

GitHub에 올라온 최신 변경사항(다른 팀원이 올린 것 포함)을 내 컴퓨터로 받아옵니다.
git pull

clone - branch 생성 - 파일 생성 후 add/ commit - push - pr 생성

git add . 
git commit -m "<커밋 메시지>"
git push origin <작업브랜치명>