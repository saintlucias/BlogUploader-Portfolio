# 원본과 실행 환경

[프로젝트 소개로 돌아가기](../README.md)

## 원본 기준

| 항목 | 값 |
| --- | --- |
| 원본 저장소 | [saintlucias/BlogUploader](https://github.com/saintlucias/BlogUploader) |
| 기준 버전 | v0.1.31 |
| 기준 커밋 | [`58573ae`](https://github.com/saintlucias/BlogUploader/commit/58573ae6854cf8dd0944eabcecfe5a03c22d60fa) |
| 화면 캡처일 | 2026-11-10, Asia/Seoul |

## 실행 환경

| 항목 | 구성 |
| --- | --- |
| 운영체제 | Windows |
| 런타임 | Node.js 24.11.1 |
| 앱 실행 | Next.js 개발 서버 |
| 화면 캡처 | Google Chrome headless, 1600 × 1100 CSS px |
| 데이터 | 운영 데이터와 분리한 SQLite DB, 기본 예시 원고·사진, 시연용 매장 프로필 |
| 외부 서비스 | 계정 로그인·GPT 호출·외부 게시 미실행 |

## 원본 코드 구성

| 영역 | 주요 내용 |
| --- | --- |
| `features/` | 화면별 UI, 초안 전환·저장, 게시 준비 흐름 |
| `app/api/` | 매장·초안·이미지·작업 이력·자동화 요청 처리 |
| `lib/server/` | SQLite, GPT 응답 처리, 계정 확인, 브라우저 자동화, 백업·복원 |
| `electron/` | 데스크톱 창과 내부 서버 생명주기 관리 |
| `tests/` | Node 테스트와 네이버 편집기 fixture |

전체 실행 코드와 개발 안내는 [원본 저장소](https://github.com/saintlucias/BlogUploader)에서 확인할 수 있음.
