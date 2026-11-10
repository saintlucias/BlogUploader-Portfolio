# 화면 안내

[프로젝트 소개로 돌아가기](../README.md)

v0.1.31 앱의 화면이며 기본 예시 원고·사진과 시연용 매장 정보를 사용함. 외부 플랫폼은 로그인 전 상태임.

## 01. 대시보드

매장 컨텍스트, 초기 설정 안내와 4개 플랫폼 연결 상태를 한 화면에서 확인함. 채널을 실제로 연결하기 전의 상태가 표시됨.

![대시보드](../assets/screenshots/01-dashboard.png)

## 02. 매장 관리

매장 프로필, 공식 정보, 메뉴·가격과 플랫폼 계정 주소를 관리함. 캡처의 주소·영업시간은 시연용이며 실제 매장 안내 정보가 아님.

![매장 관리](../assets/screenshots/02-store-management.png)

## 03. 콘텐츠 작성

초안 선택·복제·보관·버전 복원과 플랫폼별 원고 편집을 지원함. 오른쪽 이미지 보관함에서 플랫폼별 사진을 배정함. GPT 작성 요청 문구를 입력한 상태임.

![콘텐츠 작성](../assets/screenshots/03-content-editor.png)

## 04. Instagram 원고 편집

같은 초안에서 Instagram 탭으로 전환한 화면임. 플랫폼마다 다른 원고와 이미지 선택을 유지할 수 있음.

![Instagram 원고 편집](../assets/screenshots/04-instagram-editor.png)

## 05. 게시 미리보기

플랫폼별 원고·사진을 확인하고 작업 대상을 선택함. 계정 연결 상태와 게시 전 자동 점검 결과를 함께 표시함.

![게시 미리보기](../assets/screenshots/05-publish-preview.png)

## 06. 작업 이력

작업별 진행 결과를 확인하는 화면임. 작업 이력이 없는 초기 상태를 표시함.

![작업 이력 빈 상태](../assets/screenshots/06-job-history.png)

## 07. 설정

플랫폼 사용 여부, 저장소 상태, 이미지 자산과 로컬 백업·복원을 관리함. 캡처에서는 4개 플랫폼을 활성화한 상태임.

![설정](../assets/screenshots/07-settings.png)

## 캡처 정보

| 항목 | 값 |
| --- | --- |
| 캡처일 | 2026-11-10, Asia/Seoul |
| 원본 | BlogUploader v0.1.31 / `58573ae` |
| 실행 환경 | Windows, Node.js 24.11.1, Next.js 개발 서버, Google Chrome headless |
| 브라우저 뷰포트 | 1600 × 1100 CSS px / device scale factor 1 |
| 이미지 범위 | 일반 화면은 전체 페이지, 게시 미리보기는 뷰포트 캡처. 모달 내부 스크롤 아래 내용은 이미지에 모두 담기지 않음 |
| 데이터 | 별도 SQLite DB, 기본 예시 원고·사진, 시연용 매장 프로필 |
| 외부 작업 | 계정 로그인·GPT 호출·외부 게시 없음 |
