# 🐠 물 고리 던지기

추억의 물 고리 걸기 장난감을 폰 브라우저에서 즐기는 게임이에요.

- 버튼 2개로 물살을 만들어 고리를 띄우고
- 폰을 기울이면 고리가 물속에서 천천히 움직이고
- 폰을 흔들면 물이 출렁여요
- 고리 6개를 물고기 뿔에 모두 걸면 클리어! (최단 기록은 폰에 저장)

## GitHub Pages로 올리는 방법 (아이폰 센서는 https가 필요해요)

1. GitHub에서 새 저장소(Repository)를 만든다. 이름 예: `water-ring-game`, Public
2. `index.html`을 저장소 맨 위(루트)에 업로드한다 (Add file → Upload files)
3. Settings → Pages → Branch를 `main`, 폴더를 `/ (root)`로 선택 → Save
4. 1~2분 뒤 `https://skadnrwhd-web.github.io/water-ring-game/` 주소가 생긴다
5. 아이폰 Safari로 접속 → "시작하기" → 센서 허용 창에서 "허용"

## 팁

- 센서 허용을 실수로 거부했다면: Safari를 완전히 닫고 다시 접속해서 시작 버튼을 다시 누르세요.
- 아이폰 세로 방향 잠금(화면 회전 잠금)을 켜두면 편해요.
- 기울이기가 이상하면 주소 끝에 `#debug`를 붙이면 센서 값이 화면에 보여요.
- PC에서는 방향키(기울이기), Z / X 키(물살)로 테스트할 수 있어요.

## 게임 느낌 조절 (index.html 위쪽 숫자)

| 이름 | 뜻 |
|---|---|
| `GRAV` | 클수록 고리가 빨리 가라앉음 |
| `DRAG` | 클수록 물이 끈적해서 느려짐 |
| `JET` | 물살 세기 |
| `N_RINGS` | 고리 개수 |
| `PEG_CAP` | 막대 하나에 걸 수 있는 개수 |

## 후원

https://buymeacoffee.com/ujnam80
