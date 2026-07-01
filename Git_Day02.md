# Git/GitHub 2일차

Favorite: No
Archive: No
Notebook: Web Development (https://app.notion.com/p/Web-Development-38b233603e278082b9a5df03ef673f92?pvs=21)
Edited: July 1, 2026 4:03 PM
Created: July 1, 2026 3:28 PM

## **GitHub란?**

- Remote Repository
- 코드 공유
- 백업
- 협업

## **Repository 생성**

- Public / Private
- Repository Description
- README.md
- .gitignore
- License

### **Remote Repository 연결**

Local vs Remote Repository

내 컴퓨터
(Local)

↓

GitHub
(Remote)

### Push

git push 

내코드 → GitHub 업로드 

### Pull ( = fetch + merge)

git pull 

GitHub 최신 코드 → 내 컴퓨터

### Clone

git clone 

처음 프로젝트를 복제

### Pull vs. Clone

| **Clone** | **Pull** |
| --- | --- |
| 처음 복사 | 이후 동기화 |
| Git 저장소 없음 | Git 저장소 있음 |

# **GitHub 협업 Workflow**

## **Issue**

### **왜 필요한가?**

- 작업 중복 방지
- 버그 추적
- 작업 관리

### **기능**

- Issue 생성
- Assignee 지정
- Label 지정
- Open / Closed 상태

## Pull Request (PR)

작업이 끝났으니 작업 branch 를 main 에 넣어달라는 요청

---

# **GitHub 추가 기능**

## **Git Log -oneline**

Commit 기록 간단히 보기

## **Git Show**

특정 commit 보기 

## **Git Blame**

누가 수정했는지 추적

# **HTML 기초**

## **HTML이란?**

**HyperText Markup Language**

역할:

- 웹 페이지 구조 정의
- 제목
- 문단
- 이미지
- 링크
- 화면 뼈대 구성

---

## **웹 동작 구조**

## HTML 기본 구조

```
<!DOCTYPE html>

<html>

<head>
</head>

<body>
</body>

</html>
```

## Head vs Body

|  Head  | Body |
| --- | --- |
| 사용자에게 안보임 | 실제로 보이는 영역 |

## HTML Tag

| <h1> | 제목 |
| --- | --- |
| <p> | 문단 |
| <br> | 줄바꿈  |
| <hr> | 가로선 |

```
<body>

<h1>제목</h1>

<p>본문</p>

</body>
```

=

```
body
 ├─ h1
 └─ p
```

## **HTML → 브라우저 Rendering**

서버: HTML 전달 → 브라우저: HTML 해석 → 화면 생성