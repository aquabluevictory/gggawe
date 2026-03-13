# PARK ROCHE SEOUL ONE — Blue Spring Edition 2026

> 파크로쉬 서울원 공식 분양 안내 랜딩페이지 · 싱글 페이지 어플리케이션

---

## 미리보기

서울 노원구 광운대역 도보 5분 · GTX-C 예정 정차역 · 지상 49층 · 총 342세대

---

## 기술 스택

- 순수 HTML + CSS + Vanilla JS (외부 라이브러리 없음)
- Google Fonts: Noto Serif KR · Noto Sans KR · IBM Plex Mono
- 단일 `index.html` + `img/` 폴더

---

## 파일 구조

```
park-roche-seoul-one/
├── index.html          # 메인 SPA (109KB)
└── img/                # 프로젝트 실사 이미지
    ├── hero-main.jpg       # 메인 투시도 (히어로 배경)
    ├── photo-night.jpg     # 야간 단지 전경
    ├── photo-garden.jpg    # 단지 조경 · 벚꽃
    ├── photo-fitness.jpg   # 피트니스 · 웰니스
    ├── photo-spa.jpg       # 스파 · 럭셔리
    ├── photo-arch.jpg      # 건축 외관 CG
    ├── photo-indoor.jpg    # 실내 아트리움
    ├── brand-exterior.jpg  # 브랜드 외관 비주얼
    ├── tower-arch.png      # 타워 건축 단면
    ├── landscape-plan.jpg  # 조경 마스터플랜
    ├── gtx-transport.jpg   # GTX-C 교통 인포그래픽
    ├── loc-map.jpg         # 위치도
    ├── loc-img1~3.jpg      # 입지 현장 사진 3종
    ├── banner-brand.jpg    # 브랜드 페이지 배너
    ├── banner-land.jpg     # 조경 페이지 배너
    └── banner-well.jpg     # 웰니스 페이지 배너
```

---

## 주요 기능

| 기능 | 설명 |
|------|------|
| 시네마틱 로더 | 퍼센트 카운터 + 프로그레스 바 |
| 커스텀 커서 | 데스크톱 전용 블루 닷 + 링 |
| 스크롤 진행 바 | 상단 파란 그라디언트 선 |
| 7개 페이지 SPA | 홈·브랜드·건축·조경·웰니스·프리미엄·상담 |
| 건축 서브탭 | 개요·평면도·단지배치·외관설계 탭 전환 |
| 이미지 라이트박스 | 포토스트립 클릭 확대 |
| 무한 티커 | 프로젝트 정보 스크롤 |
| 스크롤 리빌 | `.SR` `.SRL` `.SRR` 애니메이션 |
| 카운터 애니메이션 | `data-target` 숫자 카운트업 |
| 자석 3D 틸트 | 카드 마우스무브 원근 효과 |
| 텍스트 스크램블 | 네비 버튼 호버 시 글자 섞임 |
| 모바일 햄버거 메뉴 | 풀스크린 드로어 |
| 플로팅 전화 버튼 | 모바일 전용 📞 |
| 반응형 | 960px · 640px 브레이크포인트 |

---

## 로컬 실행

```bash
# 단순히 index.html을 브라우저에서 열기
open index.html

# 또는 로컬 서버 실행 (권장)
python3 -m http.server 8080
# → http://localhost:8080
```

> ⚠️ `file://` 프로토콜에서도 동작하지만 일부 브라우저에서는 로컬 서버를 권장합니다.

---

## 팔레트

```css
--navy:      #091a42   /* 주 배경 */
--deep-blue: #1a4fa0   /* 강조 */
--blue:      #3b8fd9   /* 액센트 */
--sky:       #87ceeb   /* 라이트 */
--sakura:    #f7bcd4   /* 봄 포인트 */
```

---

## 크레딧

- 조경 설계: 야마구치 타케시 (Yamaguchi Takeshi) — TOWNSCAPE Associates, Tokyo
- 시공: HDC 현대산업개발
- 입주 예정: 2028년
