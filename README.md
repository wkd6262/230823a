## 230823 ##
1.로컬 저장소 생성 후 만들고 싶은 곳에 git을 실행 후 아래의 명령어를 입력한다.

`git init`<br>

2.README.md 파일생성

`touch README.md`<br>
`git status를 입력해 변동사항을 확인한다.`<br>
`git add . 추가된 모든 파일을 등록한다`<br>
`git commit -m ""  ""메시지와 함께 커밋을 한다.`<br>

3.온라인 저장소 생성

`git remote add origin https://github.com/"아이디"/로컬저장소.git`<br>

4.README.md파일 온라인 저장소에 업로드

`git push -u origin main`<br>

### github에서 내려 받기 ###
`git pull origin main`

### clone과 pull 차이 ###
