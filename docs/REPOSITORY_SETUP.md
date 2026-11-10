# 새 소개용 저장소 만들기

이 폴더의 내용을 새 GitHub 저장소의 루트에 올리면 됩니다. 원본 앱 소스와 Git 이력은 포함하지 않습니다.

## 저장소 정보

- 권장 이름: `BlogUploader-Portfolio`
- 설명: `매장별 콘텐츠 작성과 4개 플랫폼 게시 준비를 지원하는 Windows 앱 — 기능, 화면, 기술 설계 포트폴리오`
- 권장 토픽: `portfolio`, `electron`, `nextjs`, `typescript`, `playwright`, `sqlite`, `content-management`

소개용 저장소: [saintlucias/BlogUploader-Portfolio](https://github.com/saintlucias/BlogUploader-Portfolio)

## GitHub 웹에서 업로드

1. [GitHub 새 저장소 만들기](https://github.com/new)를 엽니다.
2. 이름과 설명을 입력하고 공개 범위를 직접 선택합니다.
3. 이 폴더의 `README.md`, `.gitignore`, `assets/`, `docs/`를 새 저장소 루트에 업로드합니다. ZIP을 사용한다면 먼저 압축을 풉니다.
4. 첫 커밋 후 README 이미지와 문서 링크가 표시되는지 확인합니다.

예상 구조:

```text
BlogUploader-Portfolio/
├── README.md
├── .gitignore
├── assets/
│   └── screenshots/          # 실제 앱 캡처 7장
└── docs/
    ├── SCREENS.md
    ├── FEATURES.md
    ├── ARCHITECTURE.md
    ├── SOURCE.md
    └── REPOSITORY_SETUP.md
```

## Git으로 등록

원본 체크아웃 안에서 `git init`이나 origin 변경을 실행하지 말고, 이 자료를 별도 폴더로 복사한 후 진행합니다. 아래 폴더는 예시이며 ZIP을 푼 실제 위치에 맞게 수정합니다. GitHub에는 같은 이름의 빈 저장소를 먼저 만듭니다.

```powershell
cd C:\Projects\BlogUploader-Portfolio
git init -b main
git add README.md .gitignore assets docs
git commit -m "docs: introduce BlogUploader portfolio"
git remote add origin https://github.com/saintlucias/BlogUploader-Portfolio.git
git push -u origin main
```

## 이후 보완할 정보

개발 기간, 팀 구성, 본인이 맡은 범위와 측정된 개선 결과가 확인되면 README에 추가합니다. 현재 문서는 소스에서 확인할 수 있는 기능과 설계만 소개합니다.
