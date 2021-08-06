## 지역저장소를 원격저장소와 연결하기

### git remote add  <이름> <원격저장소 주소>

- 원격 저장소와 지역 저장소를 연결하는 명령어
- 하나의 지역 저장소를 여러개의 원격 저장소와 연결할 수 있기 때문에 구별할 수 있도록 이름을 붙혀준다.
- 보통 기본적인 원격저장소는 origin을 사용한다.

### git remote [-v]

- 지역 저장소와 연결된 원격 저장소 목록 확인
- -v 옵션 사용시 원격 저장소의 주소도 출력해준다.

## git push - 원격 저장소에 업로드하기

### git push <저장소명> <브랜치명>

- git push origin master : origin 원격 저장소의 master 브랜치에 업로드한다.

### git push

- git push -u <저장소명> <브랜치명> 명령어를 입력하면 이후부터는 git push만 타이핑해도 지정한 저장소의 브랜치에 업로드가 된다.
- 예를 들어 git push -u origin master 명령어를 입력하면 이후부터는 git push 명령어만 입력해도 git push origin master와 같은 기능을 하는 것이다.

## git clone - 원격저장소로부터 지역 저장소 만들기

- git clone <원격 저장소 주소>

## git pull - 원격저장소의 버전을 지역저장소로 불러오기

- git pull <저장소명> <브랜치명>