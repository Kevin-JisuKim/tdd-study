# 테스트 주도 개발 스터디
- `Test-Driven Development: By Example` 의 내용을 참고하여 간단하게 마크다운으로 정리
- 해당 장에 속한 설명대로 코드를 작성하고 테스트 주도 개발을 익힌다.



#### 방식

- 해당 챕터의 폴더에 들어가 (없다면 만든다) 자신의 `github` 계정의 디렉터리를 만든 뒤 마크다운 파일 하나와 관련 소스를 첨부한다.
- 소스명 혹은 마크다운 파일의 이름은 원하는대로 정해도 무관하다.
- 마크다운의 내용은 해당 챕터의 내용을 간단하게 요약하는 정도로 너무 신경 안써도 된다. 
  - 해당 내용을 복기하는데 의의가 있음.
- **구현 언어는 뭐가 되었든 상관 없다.**
- `.idea`나 `.vscode`와 같은 사용자 설정 파일은 `.gitignore`에 추가해서 커밋되지 않도록 한다.
- 아래와 같이 구성 되도록 **지향**

```
tdd-study/
├── README.md
└── ch1
    └── yojkim
        ├── ch1
        │   └── dollar.go
        │   └── dollar_test.go
        └── ch1.md
```

- 브랜치를 나눠서 작성하거나, 작성 전 반드시 `git pull` 작업을 통해 충돌이 나지 않도록 주의하기