# 표지 지시문 — 00 초보자도 쉽게 따라하는 DB 환경 설치

지금 페이지에는 CSS로 만든 대체 표지(서버 선반 세 개 + 캐릭터 팩 그림 네 장)가 들어 있다. 아래 그림을 받으면 `index.html`의 `<!-- lab-cover -->` 블록에 반영한다.

| 항목 | 값 |
|---|---|
| 키 | `cover_00` |
| 크기 | 1600×900 (16:9), WebP |
| 등장 | 박사 · 조수(하루) · 초파리 연구원 · 주판봇 |
| 장면 | 밤의 연구실, 서버 선반 세 개(초록 · 파랑 · 노랑 불빛) 앞에 선 네 식구 |
| 글자 | 넣지 않는다 (제목은 HTML이 얹는다). 왼쪽 위 1/3은 비워 둔다 |
| 참고 그림 | `fruitfly-lab-expressions`의 네 캐릭터 기본 그림(E13)과 단체 사진 |

## 한국어 지시

밤의 연구실에 서버 선반 세 개가 나란히 서 있다. 첫째는 초록, 둘째는 파랑, 셋째는 노랑 불빛이다. 박사가 선반을 가리키고, 조수는 비밀번호를 적은 종이를 들고, 초파리 연구원은 클립보드에 확인 표시를 하고, 주판봇은 주판을 들고 있다. 키 순서는 박사 ≥ 조수 > 주판봇 > 초파리. 글자·숫자·로고는 그리지 않는다.

## 영어 프롬프트 (그대로 붙여 넣기)

```
16:9 pixel-art illustration, night laboratory with fluorescent-microscope color accents on a dark navy background (#13141f). Three chunky server cabinets stand in a row with small status lights: the first glows green, the second blue, the third amber. In front of them, four chibi lab characters: a confident scientist with thin teal rectangular glasses, black hair with one white streak and a short ponytail, white lab coat over black vest and tie, gesturing toward the cabinets; a female assistant with long pink hair in two round buns and a navy streak, white lab coat over a lavender hoodie, jeans, holding a paper note; a small fruit-fly researcher with red compound eyes, blue helmet with a gold stripe and pink and blue wires, white coat over black vest, holding a clipboard; a beige box-shaped retro CRT computer robot with a dark green screen showing mint pixel eyes and mouth, a short antenna tipped with an abacus bead, grey segmented arms, two caterpillar tracks, holding a wooden abacus. Height order: scientist tallest, assistant slightly shorter, robot shorter, fruit fly smallest. Leave the upper-left third empty for a title. No text, no letters, no numbers, no logos.
```

## 받은 뒤

1. 1600×900 WebP로 저장한다.
2. `index.html`의 표지 블록 배경으로 넣고, `cover_manifest.json`의 `status`를 `ok`로 바꾼다.
3. 공유 미리보기(og:image)용으로 1200×630을 잘라 `assets/og.webp`로 둔다.
