# Love Letter - 2026 엎드림 전도축제 초대 페이지

광음교회 엎드림 청년부 전도축제 초대 페이지입니다.

- **행사**: 2026년 11월 15일(일) 오후 1시 50분, 광음교회 지하1층 본당
- **주소**: https://updreamyouth.github.io/loveletter/

## 구성

빌드 도구 없이 HTML 파일만으로 된 정적 사이트입니다.

| 파일 | 설명 |
| --- | --- |
| `index.html` | 초대 페이지 (CSS·JS 포함) |
| `stats.html` | 방문자 통계 확인 페이지 (검색 노출 차단) |
| `images/` | 페이지에 쓰는 사진·이미지 |

페이지 순서: 헤더 → 히어로·초대장 → 프로그램 01~05 → 일정표 → Love Letter·초대 글 → 교회 사진 → 푸터(SNS·교통 안내·지도)

## 수정 방법

1. `index.html`에서 문구를 고치거나 `images/`의 사진을 같은 이름으로 바꿉니다.
2. `main` 브랜치에 push하면 GitHub Pages에 자동 배포됩니다(1~2분 소요).

디자인은 원래 아임웹 템플릿을 그대로 재현한 것이라, 색·폰트·배치는 가능하면 바꾸지 않습니다.

- 색: 갈색 `#7e1e00`, 크림 `#fff8e7`, 노랑 `#ffdf74`, 진한 노랑 `#f5c95c`
- 폰트: 레코체(제목), Montserrat(영문), Pretendard(본문)

## 방문자 통계

[GoatCounter](https://www.goatcounter.com/)로 방문 수를 집계합니다.

- 대시보드: https://yevop.goatcounter.com (관리자 로그인 필요)
- QR 코드 주소는 `https://updreamyouth.github.io/loveletter/?utm_source=qr`입니다. 이미 인쇄·배포되었으니 **바꾸지 마세요.**
- `stats.html`은 읽기 전용 API 키가 있어야 보입니다. 키는 관리자에게 받은 링크로 전달되며, 코드에 넣지 않습니다.
