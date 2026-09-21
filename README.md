# 오늘의 할 일 (Daily Tasks)

순수 HTML/CSS/JavaScript로 만든 개인용 할 일 관리 앱입니다. 별도 서버나 빌드 도구, `npm install` 없이 `index.html`을 브라우저에서 바로 열면 실행됩니다.

## 기능

- 할 일 추가/수정/삭제, 완료 체크 (취소선 표시)
- 카테고리(업무/개인/공부) 분류 및 색상 태그
- 카테고리별 필터 탭 + 항목 개수 표시
- `localStorage`(`daily-tasks` 키)에 자동 저장되어 새로고침해도 유지
- 빈 상태 안내, 모바일 반응형 레이아웃, 접근성(aria) 속성 적용

## 실행 방법

`index.html` 파일을 더블클릭해서 브라우저로 열면 바로 사용할 수 있습니다.

## 배포

`render.yaml`이 포함되어 있어 [Render](https://render.com)에서 Blueprint로 바로 배포할 수 있습니다 (New + → Blueprint → 이 저장소 선택).
