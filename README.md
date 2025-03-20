# ExampleRepoForPortfolio

**ExampleRepoForPortfolio**는 **깃허브 이슈와 PR**을 효율적으로 활용하는 방법을 시연하기 위한 예시 프로젝트입니다.  
신입·주니어 개발자분들이 **협업 환경과 Issue/PR 중심의 워크플로우**를 포트폴리오에 녹여내는 예시로 사용할 수 있습니다.

---

## 목차 (Table of Contents)

1. [프로젝트 개요 (Project Overview)](#프로젝트-개요-project-overview)  
2. [기능 소개 (Features)](#기능-소개-features)  
3. [시작하기 (Getting Started)](#시작하기-getting-started)  
4. [폴더 구조 (Folder Structure)](#폴더-구조-folder-structure)  
5. [이슈 템플릿 (Issue Templates)](#이슈-템플릿-issue-templates)  
6. [PR 템플릿 (Pull Request Templates)](#pr-템플릿-pull-request-templates)  
7. [사용 방법 (How to Use)](#사용-방법-how-to-use)  
8. [기여 방법 (Contributing)](#기여-방법-contributing)  
9. [라이선스 (License)](#라이선스-license)  

---

## 프로젝트 개요 (Project Overview)

- **목적**  
  깃허브 이슈(버그, 기능, 질문, 성능개선 등)를 통해 협업할 때 어떤 양식으로 이슈를 작성하고,  
  PR(Pull Request)를 통해 리뷰와 머지 과정을 어떻게 진행하는지 보여주기 위한 **예시 프로젝트**입니다.

- **대상**  
  신입·주니어 개발자 및 학생, 깃허브 협업 과정을 처음 배우는 사람

주요 포인트:
1. **Issue & PR 템플릿**을 사용해 작업 과정을 체계적으로 기록  
2. **코드리뷰(Comment)** 과정을 통해 협업 흐름을 간단히 시연  
3. **간단한 예시 코드**(예: Hello World)로도 깃허브 협업 방식 시연이 가능  

---

## 기능 소개 (Features)

- **Issue 템플릿**  
  - 버그, 기능, 질문, 성능개선 등 목적별 이슈 템플릿  
- **Pull Request 템플릿**  
  - 작업 내용, 테스트 방법, 리뷰 요청 사항 등을 자동으로 안내  
- **코드리뷰 예시**  
  - PR에서 리뷰 코멘트를 주고받아 협업하는 과정 시연  
- **Hello World 예제 코드** (Python)  
  - 가장 기본적인 예제로도 Issue/PR 과정을 체험 가능  

---

## 시작하기 (Getting Started)

1. **레포지토리 클론**
   ```bash
   git clone https://github.com/username/ExampleRepoForPortfolio.git
   cd ExampleRepoForPortfolio
   ```
2. **(선택) 파이썬 예제 실행**
   ```bash
   python hello_world.py
   # "Hello World" 출력 확인
   ```
3. **깃허브 이슈 & PR 체험**
   - 브랜치를 만들어 파일 수정 → PR 생성  
   - 다른 사람에게 코드리뷰 요청 → 머지(Merge)

---

## 폴더 구조 (Folder Structure)

```bash
ExampleRepoForPortfolio/
├─ .github/
│  ├─ ISSUE_TEMPLATE/
│  │  ├─ bug_report.md
│  │  ├─ feature_request.md
│  │  ├─ question.md
│  │  └─ performance_improvement.md
│  └─ pull_request_template.md
├─ hello_world.py
├─ README.md
└─ (기타 파일/폴더)
```

- **`.github/ISSUE_TEMPLATE/`**: 이슈 생성 시 자동으로 불러올 수 있는 템플릿들  
- **`.github/pull_request_template.md`**: Pull Request 생성 시 자동으로 불러올 템플릿  
- **`hello_world.py`**: Python Hello World 예시 코드  
- **`README.md`**: 현재 문서  

---

## 이슈 템플릿 (Issue Templates)

이 저장소에는 다음과 같은 이슈 템플릿들이 있습니다:

1. **Bug Report** (`bug_report.md`)  
   - 버그(오류) 신고 시 사용  
   - 재현 방법, 예상 동작, 에러 로그 등을 포함  

2. **Feature Request** (`feature_request.md`)  
   - 새로운 기능 또는 개선 사항을 제안할 때 사용  
   - 구현 필요성, 작업 목록(To-do list), 완료 조건 등을 포함  

3. **Question** (`question.md`)  
   - 코드, 환경 설정, 사용 방법 등에 관한 질문을 등록할 때 사용  
   - 궁금한 점과 이미 시도해본 방법, 기대하는 답변 등을 명시  

4. **Performance Improvement** (`performance_improvement.md`)  
   - 성능 개선 제안을 올릴 때 사용  
   - 원인 분석, 개선 방안, 기대 효과 등을 포함  

이슈 생성 시, **New Issue**를 클릭하면 위 템플릿 중 하나를 선택할 수 있습니다.

---

## PR 템플릿 (Pull Request Templates)

- **`pull_request_template.md`**  
  - 변경 사항 요약, 테스트 방법, 리뷰 요청 사항 등을 자동으로 안내  
  - 기존에 작업하던 이슈번호를 연결(`Closes #이슈번호`)하여 어떤 작업인지 쉽게 파악  

Pull Request를 생성할 때, 본문에 이 템플릿이 자동으로 불러와져  
**작업 배경 및 변경 내용을 한눈에** 볼 수 있도록 도와줍니다.

---

## 사용 방법 (How to Use)

### 1) 이슈 생성

1. **깃허브 상단 탭에서** `Issues` 클릭  
2. **`New Issue`** 버튼 클릭  
3. 필요한 템플릿(예: **Bug Report**, **Feature Request**, **Question**, **Performance Improvement**) 중 하나 선택  
4. 템플릿 안내에 맞춰 **제목, 내용**을 작성 후 **Submit**  

#### 예시

```markdown
[Feature] Add Python Hello World script

## 기능 설명
- 간단히 "Hello World" 출력하는 스크립트가 필요합니다.
...
```

### 2) Pull Request 생성

1. 새로운 브랜치에서 수정 작업(예: `git checkout -b feature/add-hello-world-script`)  
2. 수정 사항을 커밋 후 푸시  
3. 깃허브 `Pull Requests` 탭에서 **`New Pull Request`** 클릭  
4. `pull_request_template.md`가 자동 불러와지므로, 작업 배경과 변경 내용을 작성  
5. **“Create Pull Request”** 버튼 클릭  

#### 예시

```markdown
[Feature] Add hello_world.py

## 관련 이슈
- Closes #2

## 변경 사항
1. hello_world.py 파일 생성
2. ...

## 테스트 방법
- python hello_world.py 실행 시 "Hello World" 출력 확인

## 리뷰 요청
- ...
```

### 3) 코드 리뷰 & 머지(Merge)

- PR 생성 후 **Reviewers**(리뷰어)를 지정  
- 리뷰어가 **코드 리뷰 코멘트**를 달면, 작성자는 해당 코멘트에 답변하거나 코드를 수정  
- 모든 리뷰가 마무리되면 **“Merge”** 버튼을 눌러 `main` 브랜치에 반영

---

## 기여 방법 (Contributing)

1. **Fork** 또는 **새로운 브랜치** 생성  
2. 작업하고자 하는 이슈를 선택, 또는 새 이슈를 생성  
3. 변경 사항 완료 후 **Pull Request** 생성  
4. 리뷰 & 머지 과정을 거쳐 작업 반영  

---

## 라이선스 (License)

이 저장소는 특별한 언급이 없는 한 [MIT License](LICENSE)를 사용한다고 가정합니다.  
자세한 내용은 [LICENSE](LICENSE) 파일에서 확인하세요.

---

# 마무리

**ExampleRepoForPortfolio**는 간단한 예시 코드를 통해 **깃허브 Issue/PR 템플릿** 기반 협업 과정을 시연하기 위한 **포트폴리오 데모** 프로젝트입니다.  
**이슈와 PR** 중심의 협업 방식을 익히고, 자유롭게 기여하면서 깃허브 협업 경험을 쌓으시길 바랍니다.

> 문의 사항이나 도움 요청은 [Issues](../../issues) 탭에서 **Question** 템플릿을 사용해 작성해주세요.  
> 감사합니다!
