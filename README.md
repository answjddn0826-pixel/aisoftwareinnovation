# TypeTuner — Font Pairing & Typography Preview

## 프로젝트 소개
디자인 과제/브랜딩 작업에서 **제목·본문·캡션** 서체 조합을 빠르게 시험하고,  
**가독성/대비 체크 → CSS 스니펫 Export**까지 수행하는 경량 웹 도구입니다.  
비전공자도 쉽게 쓸 수 있도록 **Vanilla HTML/CSS/JS**로 제작했습니다.

## 구현한 기능
- 폰트 슬롯 선택(Title / Body / Caption) + 실시간 프리뷰
- 타이포 컨트롤: font-size, line-height, letter-spacing, 본문 열폭(max-width)
- 가독성/대비 경고 배지(라이트 규칙, WCAG 근사)
- 프리셋 관리: 저장/불러오기/삭제 (localStorage)
- Export: CSS 스니펫 복사(Google Fonts import 포함)
- 추가 기능: 다크/라이트 테마 토글, 폰트 페어링 추천(룰/유사도), Variable 축(wght/wdth/slnt), 레이아웃 프리셋

## 실행 방법
1. 저장소를 클론하거나 ZIP을 다운로드/압축해제합니다.  
2. 브라우저로 `index.html`을 엽니다. (로컬에서 바로 실행 가능)  
3. 폰트를 선택하고 프리뷰/컨트롤을 조절한 뒤, 필요하면 프리셋 저장 및 **Export**로 CSS를 복사합니다.

## 사용한 기술스택
- HTML5, CSS3, JavaScript(바닐라)
- Google Fonts (웹폰트 로딩)
- localStorage (프리셋 데이터 저장)

## 기타 참고사항
- **클립보드 권한**: Export 시 브라우저의 클립보드 권한이 필요할 수 있습니다.
- **브라우저 권장**: 최신 Chrome/Edge 권장. iOS Safari 일부 환경에서 variable 축·클립보드 제한 가능.
- **폰트 라이선스**: Google Fonts 사용(상용 폰트는 별도 라이선스 확인 필요).
- **접근성**: `:focus-visible` 포커스 링 및 대비 경고 제공(라이트 규칙).



