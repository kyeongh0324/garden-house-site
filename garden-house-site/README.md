# 정원속의 집 — Garden House · Geoje

경상남도 거제시 남부면에 있는 실제 독채 펜션 「정원속의 집」을 소개하는 에디토리얼 스타일 웹사이트입니다.

## 실행
`index.html`을 브라우저에서 열면 됩니다. 외부 라이브러리 없이 HTML/CSS/JS로 동작하며 Google Fonts만 외부에서 불러옵니다.

## 사진
`images/` 폴더에는 실제 제공된 사진 약 40장이 들어 있습니다.
- `photo-01.jpg` ~ `photo-08.jpg`: 초기 제공 사진(외관/바다/거실/침실/주방).
- `1.jpg` ~ `32.jpg`: 이후 추가 제공된 사진(항공샷, 오션뷰, 수영장, 복층 거실·주방·침실, 바비큐 공간 등).

이 중 `3.jpg`/`4.jpg`, `1.jpg`/`8.jpg`는 서로 완전히 동일한 이미지라 중복분은 페이지에 별도로 노출하지 않았습니다. 사용하지 않는 파일도 추후 활용할 수 있도록 삭제하지 않고 폴더에 보존합니다.

## 정보 출처 / 정확성 원칙
- 주소, 체크인·아웃 시간, 시설, 방송 촬영 협조 이력 등은 실제 제공된 정보만 사용했습니다.
- 확인되지 않은 정확한 관광지까지의 거리·소요시간, 반려동물 정책, 가격 등은 임의로 만들지 않고 표현을 흐리게 두거나(예: "예약 전 문의") 생략했습니다.
- 해금강·외도·바람의 언덕·신선대는 숙소에서 가까운 장소처럼 표현하지 않으며, 실제 사진이 없어 텍스트 기반 카드로만 구성했습니다.

## 예약
모든 "예약하기" 버튼(헤더, 히어로, 모바일 메뉴, 모바일 하단 고정 바, 본문 CTA, Footer)은 실제 예약 페이지로 연결됩니다.
`https://nol.yanolja.com/stay/domestic/10046387`

## 위치
`경상남도 거제시 남부면 거제대로 148` — LOCATION 섹션의 주소 텍스트와 지도 버튼을 클릭하면 별도 지도 앱 설치 없이 구글 지도 검색 결과로 이동합니다.

## 포함된 인터랙션
- Hero entrance animation / subtle parallax
- Scroll reveal / clip-path reveal / stagger
- Hover image zoom
- Desktop custom cursor (모바일에서는 비활성화)
- Mobile fullscreen navigation + 하단 고정 예약 바
- Masonry gallery (26장)
- Lightbox: ESC / 좌우 이동 / 배경 클릭 닫기 / 이미지 제목
- Stay Guide accordion
- prefers-reduced-motion 지원

## 실제 배포 전 확인/교체할 것
- 반려동물 정책 등 아직 확인되지 않은 세부 규정
- SEO title/description 문구 최종 검수
- 고해상도 원본 이미지로 교체 및 압축 최적화
