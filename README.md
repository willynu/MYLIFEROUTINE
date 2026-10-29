# 나의 루틴 PWA

습관 개수 제한 없이 사용할 수 있는 개인용 루틴 트래커입니다.

## 기능
- 무제한 루틴 생성, 수정, 삭제
- 반복 요일/시간대 지정, 날짜별 완료 체크
- 최근 30일 달성 통계
- JSON 백업/복원
- 설치형 PWA 및 오프라인 캐시

## 배포 (Windows, GitHub Pages)
1. GitHub 새 **Public** repository를 생성합니다. 예: `my-routine`.
2. 이 폴더 안 파일 5개(`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`)를 저장소 최상위에 업로드합니다.
3. Repository **Settings → Pages → Build and deployment → Deploy from a branch**를 선택하고 `main` / `/ (root)`로 저장합니다.
4. GitHub Pages에 표시된 HTTPS 주소를 아이폰 Safari에서 엽니다.
5. Safari 공유 메뉴 → **홈 화면에 추가** → **웹 앱으로 열기** 켜기 → 추가.
6. 홈 화면 아이콘으로 앱을 실행해 루틴을 등록합니다.

## 주의
- 데이터는 웹앱의 로컬 스토리지에만 저장되며 기기별 자동 동기화는 없습니다.
- 아이폰에서 설치된 웹앱과 Safari 탭 사이에 저장 데이터가 공유되지 않을 수 있습니다. 설치된 아이콘으로 사용하세요.
- 설정 → JSON 백업을 정기적으로 실행하고 파일 앱/iCloud Drive 등에 보관하세요.
- 브라우저 저장공간 초기화나 앱 제거 시 기록이 손실될 수 있습니다.
- 알림 발송, 계정, 클라우드 동기화는 제공하지 않습니다.
- 소프트웨어는 개인용 초기 버전입니다. 주요 데이터는 별도 백업이 필요합니다.
