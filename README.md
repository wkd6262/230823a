## 230823 ##
### 일반 ###
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
-clone : 로컬에 저장소가 없는 경우. 저장소 자체를 복사
-pull : 로컬에 연결된 저장소 있는 경우. 저장소 안에 있는 파일 내려받기

### 충돌(rejacted,conflict)시 해결 방법 ###
1.에러 메시지 확인 후 git pull을 이용해 전 버전으로 복구한다.<br>
2.복구 후 직접 내용을 추가한 후 commit을 한다<br>
3.git push -u origin main 을 입력해 오류가 안뜨면 성공.