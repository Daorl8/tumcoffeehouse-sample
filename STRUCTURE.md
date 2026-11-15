# STRUCTURE · tumcoffeehouse-sample (v0.1 · 배포 예정 tumcoffeehouse-sample.lgt3232.workers.dev · 레포 이름은 다올이 정함)

```
tumcoffeehouse-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = tumcoffeehouse-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ tm-pretendard.woff2        글꼴 하나 (Pretendard 400–700, 페이지 글자 + 영문 · 숫자 전체, 공백 포함)
├─ tm-logo.svg                사장님 손그림 로고 (잉크 #1E1E1E, potrace 벡터)
├─ tm-hero.webp               히어로 · 입구 통창 (4:3)
├─ tm-bar · tm-flower .webp   01 소개
├─ tm-panini · tm-cappuccino · tm-ube · tm-pastry · tm-yogurt .webp   02 메뉴 (4:5)
├─ tm-garden · tm-window · tm-house .webp   03 공간
├─ tm-terumi1 · 2 · 3 .webp   04 터미
├─ favicon.png · og-tm.jpg
├─ img/                       다올 제공 원본 76장 + _인스타_원문.md (배포 제외 · 연예인 · 다른 브랜드 · 캐릭터 이미지 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로 → `#about`(회색) → `#menu` → `#space`(민트 띠) → `#terumi` → `#visit`(회색) → 푸터(회색) + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 플레이스 `https://m.place.naver.com/restaurant/2036517829/home`: 헤더 · 히어로 · 메뉴 안내 · 오시는 길 · 푸터 · 하단 바
- 인스타그램 `https://www.instagram.com/tumcoffeehouse/`(휴무 공지): 히어로 · 메뉴 안내 · 오시는 길 공지 상자 · 푸터 · 하단 바
- 전화 `tel:050713675808`(0507-1367-5808): 히어로 · 오시는 길 · 푸터 · 하단 바
- 네이버 길찾기 `https://map.naver.com/p/entry/place/2036517829`

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 원본 = `fonts/Pretendard-1.3.9/public/variable/PretendardVariable.ttf`를 wght 400–700으로 고정 후 서브셋.
