## 4주차

### GitHub Repository 구성

프로젝트의 작업 영역을 구분하기 위해 GitHub Organization 내 Repository를 구성하였다.

- **Frontend**  
  To.U 프론트엔드 개발을 위한 Repository
- **Project**  
  문서 작성, 프로젝트 관리 등 과제 제출을 제외한 전반적인 작업을 위한 Repository
- **Backend**  
  회원가입, 로그인 등 추후 백엔드 기능 개발을 위한 Repository  
  현재 Private 상태로 미공개

---

### GitHub 협업 규칙 설정

#### Branch 규칙

브랜치 이름은 다음 형식으로 통일하였다.

```text
이름-페이지명
```

#### Label 생성

Issue와 PR의 작업 유형을 쉽게 구분할 수 있도록 다음 Label을 생성하였다.

| Label | 용도 |
| --- | --- |
| ✨ `feature` | 기능 및 페이지 생성 |
| 🚧 `prototype` | 프로토타입 작업 |
| 🔧 `fix` | 오류 수정 |
| 🛠️ `refactor` | 기존 기능 보완 및 개선 |
| 🎨 `style` | CSS 및 스타일 관련 작업 |

---

### Issue Template 생성

Issue 작성 형식을 통일하기 위해 다음 Template을 생성하였다.

```md
## 📌 기능 설명
<!-- 구현할 기능에 대해 간단하게 작성해주세요. -->

## ✅ 작업 내용
- [ ]
- [ ]
- [ ]

## 💡 참고 사항
<!-- 디자인, API, 관련 이슈 등 참고할 내용이 있다면 작성해주세요. -->
```

## 5주차

### Pull Request Template 생성

PR 작성 시 관련 Issue와 작업 내용을 명확하게 확인할 수 있도록 다음 Template을 생성하였다.

```md
## 🔗 관련 이슈

Closed

## 📌 작업 내용

## 📸 스크린샷
```

---

### Git Rulesets 생성

`main` 브랜치를 보호하기 위해 **Protect main branch** Ruleset을 생성하였다.

- `main` 브랜치에 직접 Push하지 않고 다른 브랜치에서 작업 후 PR을 통해 병합
- PR을 통한 변경 사항 검토 절차 적용
- Force Push 차단

---

### Manyfast를 활용한 서비스 기획 및 설계

프로토타입 제작에 앞서 **Manyfast**를 활용하여 서비스의 기획 및 설계에 필요한 산출물을 생성하였다.

#### PRD (Product Requirements Document) 작성

- 서비스의 목적과 핵심 기능을 정의하기 위한 PRD 생성
- 서비스 요구사항 및 개발 방향 구체화

#### 기능 명세서 작성

- 서비스에서 제공할 주요 기능 정리
- 각 기능의 역할과 동작 방식 구체화

#### User Flow 설계

- 사용자의 서비스 이용 과정을 단계별로 시각화
- 페이지 간 이동 흐름 및 사용자 행동 구조 정리

#### Wireframe 제작

- 주요 페이지의 화면 구성 및 레이아웃 설계
- 기능별 UI 요소 배치 및 사용자 인터페이스 구조 구체화

---

### 프로토타입 제작

서비스의 주요 화면에 대한 프론트엔드 프로토타입을 제작하였다.

#### 후보 목록 페이지 제작

PR: https://github.com/UXD-ToU/Frontend/pull/6

#### 후보 상세 정보 페이지 제작
PR: https://github.com/UXD-ToU/Frontend/pull/7

#### 후보 최종 확인 페이지 제작
PR: https://github.com/UXD-ToU/Frontend/pull/10