1. 깃 사용시 vscode에서 프로젝트 폴더를 최 상위로 하여 열어야 한다.
2. ctrl + j (터미널 열기-명령어 창)
3. 깃 시스템 설치 명령어를 입력 - git init
4. ('->백틱) `git config --global user.email gyqlstm@gmail.com`
`git config --global user.name hyobin-lim`
5. git bash 에서 탈출 명령어 q

--
git 시스템에서 3담계로 버전을 관리함
1. working-area: 작업중 (Untracked) 상태로 U로 표시됨
 a. 언제든지 파일의 변경이 될 수 있어 기록하지 않음.
2. stage-area: 저장 (Added) 상태로 A로 표시됨
 a. 작업 내역을 저장함
 b. git add 파일명