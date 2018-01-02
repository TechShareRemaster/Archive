# Techshare Study Archive 

테크쉐어 스터디 모임 기록 저장소입니다.

## 문서 업데이트

모든 문서들은 md 파일이며 `docs` 폴더 하위에 있습니다.

```bash
docs
├── README.md
├── SUMMARY.md
├── project001
│   ├── HTML51.md
│   └── README.md
├── project002
│   └── README.md
└── project003
    ├── Blockchain.md
    ├── DataScience.md
    ├── MachineLearning.md
    ├── README.md
    └── React+Cordova.md
```

원하는 위치에 문서를 생성한 후, **`docs/SUMMARY.md`에서 내비게이션 링크를 지정**해 주세요.
(내비게이션에 링크가 없는 문서는 노출되지 않습니다.)

```
yarn gitbook serve
```
위 커맨드를 실행하면 `localhost:3000`에서 로컬 문서를 확인할 수 있습니다. Hot Reload를 지원합니다.

```
yarn gitbook build
```
`_book` 폴더 하위에 `html` 파일들을 빌드합니다.


## 문서 페이지 배포

`master` 브랜치에 변경된 문서를 모두 `commit`, `push`한 후에 아래 커맨드를 실행합니다.

```
yarn publish-gitbook
```

위 커맨드를 실행하면
1. `gh-pages` 브랜치로 체크아웃한 후
1. `origin/master`의 업데이트를 반영하고 
1. `_book` 폴더 내의 빌드 결과물을 root로 옮긴 후 푸시합니다. 
