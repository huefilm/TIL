## 오늘 한 일
- git이란 무엇인가
  - Linus Torvalds가 화나서 1주일 만에 만든 최고의 버전관리 도구
  - 장점: 분산형 저장소 지원, 비선형적 개발 가능
  - ..
- 저장소 운용할 때 잊으면 안되는 것
  - README.md
  - .gitignore
  - 컴퓨터에서 첫 git push 할 때 계정 비밀번호가 아닌 Personal Access Token 발급받아서 사용하기(보안을 위해선.. 만료일 지정해야..)
- git clone
  - clone 할 때 로컬에서 위치 dev인지 꼭 확인하기
- add, commit, push
  - add 할 때 지금 단위에 들어가야 하는 파일인지 구분해서 올리기
  - commit 할 때 conventional commit 지키기
    - prefix: 커밋의 종류(feat, fix, docs, refactor, conf, chore, style, ci, build)
    - 제목: 최대한 간단하게! 문장형으로 나열하지 않기
    - 내용: 제목으로 설명 가능하면 안써도 됨
    - ..
- branch
  - 특정한 시점으로부터 코드가 독립적으로 존재할 수 있도록 만들어 주는 모델
  - ..

## 내일 할 일

- merge conflict
- git 사용 중 발생하는 다양한 상황 해결하기
- collaboration

## 회고

- 어렵지만 conventional commit에 대해 생각해 볼 수 있어서 좋았다.
- 좋은 습관을 들이자!!( `git commit -a` 하지 않기!! 앞접시에는 작업단위 구분 해서 add하기!!)
