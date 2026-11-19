# 🛵 seoul-delivery

서울 배달 라이더 · 1인칭 오토바이 — 브라우저에서 바로 달리는 3D 배달 게임입니다.

남산타워가 보이는 서울의 밤거리에서 1인칭 오토바이를 몰고 주문을 받아
픽업하고 배달합니다. 신호를 지키고 음식을 따뜻하게 가져다주면 별점이 올라갑니다.

## 플레이

- 웹: <https://sungjin513-dev.github.io/seoul-delivery/>
- 로컬: `index.html` 파일을 브라우저로 열면 됩니다.

## 조작

| 동작 | 모바일 | PC |
| --- | --- | --- |
| 좌우 핸들 | ◀ ▶ 버튼 | A/D, ←/→ |
| 가속 / 감속 | 악셀 / 브레이크 버튼 | W/S, ↑/↓ |
| 경적 | 빵빵 버튼 | Space |

정차하면 픽업이 됩니다.

## 구성

- `index.html` — 게임 전체가 들어 있는 단일 파일(HTML/CSS/JS, 빌드 불필요)
- `.nojekyll` — GitHub Pages에서 Jekyll 처리 없이 그대로 배포하기 위한 파일

3D 렌더링에는 [three.js](https://threejs.org/) r149를 CDN(jsDelivr → cdnjs → unpkg 순)에서
불러오므로, 플레이하려면 인터넷 연결이 필요합니다.
