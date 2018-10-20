# readme


### 참고 글
- [hooks](https://git-scm.com/book/ko/v2/Git%EB%A7%9E%EC%B6%A4-Git-Hooks) <br>
- [husky로 손쉽게 이슈 관리하기](https://www.huskyhoochu.com/npm-husky-the-git-hook-manager)
- [나중에 참고할 글](https://gist.github.com/pgilad/5d7e4db725a906bd7aa7)

### 설명

git에 hooks 기능을 상황에 맞게 작성하고 있습니다.
일단 `hooks/prepare-conmmit-msg` 는 브랜치 명을 "이슈넘버-이슈내용"으로 만들면 후에 그 브랜치의 커밋이 자동으로 "[#이슈넘버] ~ 어쩌구"로 작성되게 변환해줍니다.

### 사용방법

각 git project에서 .git/hooks 안에다가 `prepare-commit-msg`를 추가해주시면 됩니다.
