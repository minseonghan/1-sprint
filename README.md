## 제출해야하는 내용

- 코랩에서 작업한 파일
- 주차별 README.md 에 채워야 하는 실험 보고서

## 제출 방법

1. 자신의 깃허브 아이디로 브랜치 만든 다음에 개인 폴더 만들어주세요.
2. 작업 하시고 커밋 후 오리진으로 푸시해주시면 됩니다.
3. main 으로 풀리퀘 날려주시면 됩니다. merge 는 하시면 안돼요! 풀리퀘 제목 : 1주차 "이름" 과제 제출합니다.

### 예시

```bash
git clone git@github.com:minseonghan/1-sprint.git  # 클론
cd 1-sprint # 프로젝트 루트로 이동
git checkout -b minseongh # 브랜치 생성 (본인의 브랜치, 폴더 등 생성)
mkdir minseongh # 개인 폴더 만들기
cd minseongh # 개인 폴더로 이동
git add . # 작업 후 add
git commit -m "[feat] ~~" # 커밋, sprint 과제 같은 경우는 [docs]로 올리시면 됩니다.
git push origin minseongh # 오리진에 푸시
```

### 폴더구조

```bash
.
├── README.md # 프로젝트 설명 리드미 (수정X)
└── minseongh #(개인 폴더)
    └── week1 # 주차별 요약 정리
      ├── README.md # 주차별 요약 정리
```

## 커밋 컨벤션

feat: 새로운 기능 추가  
fix: 버그 수정  
docs: 문서 수정  
style: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우  
refactor: 코드 리팩토링  
test: 테스트 코드, 리팩토링 테스트 코드 추가  
chore: 빌드 업무 수정, 패키지 매니저 수정, production code와 무관한 부분들 (.gitignore, build.gradle 같은)  
comment: 주석 추가 및 변경  
remove: 파일, 폴더 삭제  
rename: 파일, 폴더명 수정
