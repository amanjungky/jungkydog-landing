# 청담펫부티크 · 정키독 랜딩페이지

> 프리미엄 반려견 용품 및 업사이클링

꿈마루 창업가 랜딩페이지 프로젝트 · 정훈숙 대표

## 프로젝트 개요

- **브랜드**: 청담펫부티크 (정키독)
- **슬로건**: 프리미엄 반려견 용품 및 업사이클링
- **정의**: 사회적 가치와 내 아이의 안전을 동시에 챙기는 브랜드 — 안전·편안함·유니크한 디자인
- **주력 제품**: 반려견 하네스 (테마 자수 시리즈)
- **주요 목적**: ⭐ **잠재고객 DB 수집** (뉴스레터 구독)
- **참고 레퍼런스**: 프라이탁·파타고니아·와일드원·플리츠마마

## 섹션 구성 (8섹션 · DB 수집 최적화)

1. **Nav** — 로고 + "소식 받기" CTA 고정
2. **Hero** — 슬로건 + 대표 제품 이미지 + 뉴스레터 유도 버튼
3. **Story** — 브랜드 스토리 + 4가지 가치
4. **Products** — 시그니처 하네스 4종
5. **Values** — 3가지 약속 (안전·편안함·유니크)
6. **Craft** — 업사이클링 4단계 프로세스
7. **Newsletter** ⭐ — Google Forms 임베드 · 메인 DB 수집
8. **Contact** — 스마트스토어·블로그·이메일

## 컬러 시스템 (로고 기반)

| 역할 | 변수 | 값 | 출처 |
|---|---|---|---|
| 메인 포인트 | `--sky` | `#5FA8E0` | 로고 "정키독" 글자 |
| 강조 | `--crown-red` | `#E64545` | 로고 왕관 |
| 액센트 | `--sun` | `#F5C544` | 제품 자수 노랑 |
| 텍스트 | `--ink` | `#1A1A1A` | 로고 외곽선 |
| 배경 | `--paper` | `#FFFFFF` | 하얀색 |

## 폰트

- **본문/제목**: Pretendard Variable (모던 한글)
- **영문 포인트**: Playfair Display (italic, 소제목)
- **손글씨 액센트**: Gochi Hand (로고 정체성 반영)

## ⚠️ 대표님 조치 필요

### 1. Google Forms 생성 후 교체

`index.html` 안의 Newsletter 섹션에 **iframe src**가 `about:blank`으로 비어있어요.

**절차**:
1. [Google Forms](https://forms.google.com) 새 폼 생성
2. 받을 정보 필드: 이메일(필수) · 반려견 이름 · 관심 제품 · 기타
3. 우측 상단 **"보내기"** → `< >` 아이콘(임베드)
4. 표시되는 `<iframe src="..."`의 **src 값만** 복사
5. `index.html`에서 `id="gform"` 찾아 `src="about:blank"`을 복사한 주소로 교체

교체 전까지는 **"Google Forms 임베드 준비 완료"** 안내 박스가 대신 표시됩니다.

## 연결된 채널

- 스마트스토어: https://smartstore.naver.com/jungkydog
- 블로그: https://blog.naver.com/jungkydog
- 이메일: swelljung@gmail.com

## 로컬 확인

```bash
open index.html
```

## 다음 작업

- [ ] 대표님께 Google Forms 생성 요청 → iframe src 교체
- [ ] 추가 제품 사진 받으면 Products 섹션 확장
- [ ] GitHub Private 리포 + Cloudflare Pages 배포
