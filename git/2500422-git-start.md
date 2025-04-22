## 오늘 한 일

**sh(Bourne Shell)**: AT&T Bell 연구소의 Steve Bourne이 작성한 UNIX 쉘.
=> **bash(Bourne Again Shell)**: Brian Fox가 작성한 UNIX 쉘

Shell Commands:
- `ls`: 디렉토리의 파일 목록을 보여준다.
- `cd`: 디렉토리 이동
- `pwd`: 현재 작업 중인 디렉토리의 경로를 보여준다.
- `mkdir`: 디렉토리 생성
- `touch`: 파일 생성
- `rm`: 파일 삭제
- `cp`: 파일 복사
- `mv`: 파일 이동
- `cat`: 파일 내용 출력


Vim: vi 확장판
- `i`: insert mode로 전환
- `Esc`: command mode로 전환
- `:wq`: 저장 후 종료
- `:q!`: 저장하지 않고 종료
----

Git: 분산 버전 관리 시스템
- **Linus Torvalds**가 Linux 커널 관리를 위해 1주일만에 만든 버전관리 시스템
![리누즈 토발즈](https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F1519303D504B741506)
> “나는 그저 내가 쓰고 싶은 도구를 만들었을 뿐이다.” — Linus Torvalds


- 분산형: 중앙 서버에 의존하지 않고 각 사용자가 로컬 저장소를 가짐
- GitHub: Git을 기반으로 한 웹 서비스로, 원격 저장소를 제공
- GitLab, Bitbucket


git config
```
$ git config --global user.name “{username}”
$ git config --global user.email “{emailaddr}”
$ git config --global core.editor “vim”
$ git config --global core.pager “cat”
$ git config --list
```
clone 부터 push까지지
```
$ git clone {repository}
$ git status
$ git add {filename} // staging area에 추가
$ git commit : 
  Conventional Commits {type}: {description} 작업단위 축약(breaking change가 있다면 type 뒤에 !)
- feat: 기능 개발 관련
- fix: 오류 개선 혹은 버그 패치
- docs: 문서화 작업
- test: test 관련
- conf: 환경설정 관련
- build: 빌드 작업 관련
- ci: Continuous Integration 관련
- chore: 패키지 매니저, 스크립트 등
- style: 코드 포매팅 관련

$ git push origin main # 원격 저장소에 푸시 
- Personal Access Token을 사용하여 인증 
```
Branch: 분기점 생성
```
$ git branch 
$ git branch {branchname} # 브랜치 생성
$ git switch {branchname} # 브랜치 이동
$ git merge {branchname} # 브랜치 병합
```
.gitignore : 추척하지 않도록 하는 파일이나 디렉토리 명시시
```
*.java
pw.*
secrets/**

```
## 내일 할 일

merge conflict 해결하기 


## 회고

- git을 오랜시간 사용했지만 CLI 사용은 기억하기도 어려웠고, 내용을 확인하는 GUI 툴이 있어서 사용하지 않았는데 이번기회에 차근히 실습할 수 있어서 좋았다. vim도 마찬가지로 잘 사용할 일이 없었는데 CLI로 사용하니 더 익숙해질 수 있었다. 
