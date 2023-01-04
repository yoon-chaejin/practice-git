# Commit Message Convention

```
작업 (브랜치명) : 부연설명
```

## Commit Message Components
### 작업
- commit, merge, pull request 등의 git 작업
- 구분
  - 단일 브랜치 작업 : commit
  - 이중 브랜치 작업 : merge, pull request
### 브랜치명
- 단일 브랜치 작업(ex. commit)인 경우, 대상 브랜치명을 작성
- 이중 브랜치 작업(ex. merge, pull request)인 경우, `source > destination` 양식으로 작성
### 부연설명
- commit 의 경우, commit 순번을 작성
- 여러 branch 에서 동시에 작업 후 병합 시 graph 에서 추적을 위함
