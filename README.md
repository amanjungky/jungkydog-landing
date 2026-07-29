# 정키독 JUNGKYDOG RE:FORM · 공식 홈페이지

> 프리미엄 반려동물 하네스 아틀리에 · 리폼 / 업사이클링 / 핸드메이드 클래스

꿈마루 창업가 랜딩페이지 프로젝트 · 정훈숙 대표

## 프로젝트 개요

- **브랜드**: 정키독 (JUNGKYDOG RE:FORM)
- **브랜드 정의**: "우리는 하네스를 만드는 브랜드가 아닙니다. 우리는 우리 아이와 함께하는 시간을 디자인합니다."
- **핵심 가치**: RE:FORM · HANDCRAFT · COMFORT · SAFETY
- **미션**: Protect Memories. Protect Pets. Protect Earth.
- **주력 서비스**: 맞춤 리폼 의뢰 · 업사이클링(폐방화복) · 시그니처 하네스 · 핸드메이드 클래스

## 카테고리 구성

`홈페이지카테고리` 시안의 7개 카테고리를 그대로 반영한 원페이지 구조입니다.

| 순서 | 카테고리 | 앵커 | 내용 |
|---|---|---|---|
| — | Hero | `#home` | 브랜드 선언 + 핵심 가치 4종 |
| 1 | **ABOUT** | `#about` | 01 브랜드 소개 · 02 철학 · 03 미션 · 04 대표 이야기 |
| 2 | **COLLECTION** | `#collection` | 시그니처/시즌/제품상세 + 시그니처 하네스 4종 |
| 3 | **RE:FORM** | `#reform` | 맞춤 리폼 의뢰 · 제작 과정 · Before&After · 상담 신청 |
| 4 | **UPCYCLING** | `#upcycling` | 소방복 프로젝트 · 업사이클링 철학 · 소재 이야기 · 환경 가치 + 실제 작업 현장 |
| 5 | **CLASS** | `#class` | 원데이 클래스 · 정규 클래스 · 예약 |
| 6 | **STORY** | `#story` | 고객 후기 · 제작 일기 · 봉사활동 · 브랜드 뉴스 |
| 7 | **CONTACT** | `#contact` | 카카오 상담 · 위치 · 운영시간 · 문의 |

## 이미지 자산

```
images/
├─ favicon.png          파비콘
├─ logo.png             로고 (예비)
├─ logo-mark.jpg        로고 마크 (예비)
├─ products/            시그니처 하네스 실제 제품 사진
│  └─ rocket.jpg / superman.jpg / minions.jpg / set.jpg
├─ craft/               실제 공방·봉사 사진
│  ├─ design.jpg        원단 선정과 디자인 설계
│  ├─ workshop.jpg      폐방화복 업사이클링 공방
│  ├─ sewing.jpg        봉제 작업 현장
│  ├─ result.jpg        완성 하네스 착용
│  └─ rescue.jpg        유기견 봉사 활동
└─ cat/                 카테고리 시안(PNG)에서 잘라낸 카드 사진
   ├─ about-hero.jpg / about-philosophy.jpg / about-founder.jpg
   ├─ mission-1~3.jpg
   ├─ col-1~3.jpg / reform-1~4.jpg / upcycle-1~4.jpg
   └─ class-1~3.jpg / story-1~4.jpg / contact-1~4.jpg
```

`images/cat/`은 원본 시안 PNG(약 2MB/장)에서 사진 영역만 잘라 웹용 JPEG로 변환한 것입니다.
시안에 글자가 박혀 있던 부분은 이미지로 넣지 않고 전부 HTML 텍스트로 다시 작성했습니다.

## 컬러 시스템 (시안 기준)

| 역할 | 변수 | 값 |
|---|---|---|
| 배경 (아이보리) | `--ivory` | `#F5F2ED` |
| 배경 교차 | `--ivory-2` | `#EFEAE2` |
| 카드 | `--card` | `#FBFAF8` |
| 제목·네비 | `--navy` | `#1B2B4B` |
| 아이콘·번호 | `--gold` | `#A8916C` |
| 버튼 (브라운) | `--brown` | `#8C7454` |
| 본문 | `--ink` / `--muted` | `#1E1C1A` / `#77706A` |

## 폰트

- **본문/제목**: Pretendard Variable (CDN)
- **넘버링·영문 디스플레이**: Georgia (serif)

## ⚠️ 대표님 확인 필요

1. **CONTACT 위치** — 시안(CONTACT.png)에 적힌 주소는 예시입니다.
   실제 주소를 알려주시면 `index.html`의 `<!-- 실제 주소를 확인 후 ... -->` 주석 부분을 교체합니다.
2. **운영시간** — 현재 "월–토 10:00–19:00 (일·공휴일 휴무)"로 표기했습니다. 실제와 다르면 알려주세요.
3. **카드 사진** — 시안 사진 다수가 AI 생성 컨셉 이미지입니다.
   실제 촬영본이 준비되는 대로 `images/cat/` 파일만 같은 이름으로 교체하면 됩니다.

## 연결된 채널

- 스마트스토어: https://smartstore.naver.com/jungkydog
- 카카오 채널: https://pf.kakao.com/_pyexfX
- 인스타그램: https://www.instagram.com/amanjungky
- 이메일: swelljung@gmail.com

## 로컬 확인

```bash
start index.html
```

## 다음 작업

- [x] 실제 주소 반영 (시흥시 신천동) / [ ] 운영시간 반영
- [ ] AI 컨셉 이미지를 실제 촬영본으로 순차 교체
- [ ] 고객 후기 / 제작 일기 실제 콘텐츠 연결
- [x] GitHub 리포 + Netlify 배포
