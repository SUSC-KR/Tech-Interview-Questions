# Tech-Interview-Questions

이 레포지토리는 기술 면접을 준비하는 개발자들을 위해 만들어졌습니다. 다양한 기업의 면접 질문을 모아 효율적인 학습을 돕습니다.

## 문서 구조

```
Tech-Interview-Questions
├── README.md
└── CompanyName
    └── questions.csv
```

각 회사별 디렉토리에 해당 기업의 면접 질문이 포함된 `questions.csv` 파일이 위치합니다.

## 기여 방법
이 프로젝트에 대한 기여는 언제든 환영입니다. 문제가 있거나 추가하고 싶은 질문이 있다면 언제든지 Pull Request를 생성해주세요. 감사합니다!

### 문제 추가하기

1. 이 레포지토리를 Fork 합니다.
2. 질문의 기업명이 현재 존재하지 않는다면, 기업명을 영문으로 작성하여 새 디렉토리를 생성합니다. 만약 기업명을 밝히기 어렵거나 면접 질문만 추가하고 싶다면 `Anonymous` 폴더의 `questions.csv`에 추가해 주세요.
3. 해당 디렉토리에 `questions.csv` 파일을 생성합니다. (이미 파일이 있다면 이 과정을 뛰어넘습니다.)
4. `questions.csv` 파일에 다음 형식으로 질문을 추가합니다:
   ```csv
   id,category,question
   1,Algorithm,"퀵정렬의 시간복잡도는 무엇인가요?"
   2,Data Structure,"스택과 큐의 차이점은 무엇인가요?"
   ```
5. 변경 사항을 커밋하고 Pull Request를 생성합니다.

### 문제 수정하기

이 프로젝트의 데이터는 크롤링과 GPT 기반 전처리 파이프라인을 통해 생성되었습니다. 따라서 일부 질문이 어색하거나 정보가 누락될 수 있습니다.

1. 이 레포지토리를 Fork 합니다.
2. 수정이 필요한 `questions.csv` 파일을 찾아 내용을 업데이트합니다.
3. 변경 사항을 커밋하고 Pull Request를 생성합니다.

## 기여 시 유의사항

- 기업명은 반드시 **영문**으로 작성해주세요.
- `questions.csv` 파일 내 질문은 **한글**로 작성하는 것을 권장합니다.
- 중복된 질문이 있는지 확인 후 추가해주세요.
- 기여 전 기존 데이터의 형식을 준수하는지 검토해주세요.

