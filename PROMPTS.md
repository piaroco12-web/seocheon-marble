# 그림 프롬프트 — 「다 같이 돌자, 서천 한 바퀴」(서천탐험대)

> 각 프롬프트는 공통 스타일 문장까지 들어 있는 완성본입니다. 코드 블록 오른쪽 위 복사 버튼으로 복사해 ChatGPT에 그대로 붙여 넣으세요.
> 저장 위치: `public/regions/seocheon/art/` · 파일 이름을 그대로 쓰면 게임에 바로 들어갑니다.

그림 **47장** + 앱 아이콘 1장 (⬜ 필요 · ✅ 완료)

## 목차

- [0. 기준 이미지 — 가장 먼저](#base)
- [1. 지도 바탕](#map)
- [2. 장소 건물 12](#bld)
- [3. 안내 캐릭터 — 서아 · 천이](#char)
- [4. 플레이어 말 4](#piece)
- [5. 미니게임 그림 10](#mg)
- [6. 화면(UI) 그림 9](#ui)
- [7. 앱 아이콘 2](#icon)

## 체크리스트

| 상태 | 파일 | 그림 |
|---|---|---|
| ⬜ | `style-anchor.png` | 기준 이미지: 한산모시관 |
| ⬜ | `map-base.png` | 지도 바탕 (건물 없이) |
| ⬜ | `bld-ramie.png` | 한산모시관 (= 기준 이미지) |
| ⬜ | `bld-moonheon.png` | 문헌서원 |
| ⬜ | `bld-leesangjae.png` | 이상재 선생 생가지 |
| ⬜ | `bld-reed.png` | 신성리 갈대밭 |
| ⬜ | `bld-birds.png` | 금강하구 조류생태전시관 |
| ⬜ | `bld-tidal.png` | 서천갯벌 유부도 |
| ⬜ | `bld-ecology.png` | 국립생태원 에코리움 |
| ⬜ | `bld-skywalk.png` | 장항스카이워크 |
| ⬜ | `bld-port.png` | 홍원항 |
| ⬜ | `bld-camellia.png` | 마량리 동백나무숲 |
| ⬜ | `bld-start.png` | 출발: 한산모시문화제 마당 |
| ⬜ | `bld-rest.png` | 쉼터: 춘장대 솔밭 쉼터 |
| ⬜ | `bld-chance.png` | 찬스: 모시 실꾸리 바구니 |
| ⬜ | `char-seoa-normal.png` | 서아 기본 |
| ⬜ | `char-seoa-think.png` | 서아 생각 |
| ⬜ | `char-seoa-happy.png` | 서아 정답 |
| ⬜ | `char-seoa-sad.png` | 서아 오답 |
| ⬜ | `char-seoa-surprised.png` | 서아 시간 초과 |
| ⬜ | `char-cheoni-normal.png` | 천이 기본 |
| ⬜ | `char-cheoni-think.png` | 천이 생각 |
| ⬜ | `char-cheoni-happy.png` | 천이 정답 |
| ⬜ | `char-cheoni-sad.png` | 천이 오답 |
| ⬜ | `char-cheoni-surprised.png` | 천이 시간 초과 |
| ⬜ | `piece-ramie.png` | 말: 모시 요정 |
| ⬜ | `piece-camellia.png` | 말: 동백이 |
| ⬜ | `piece-bird.png` | 말: 검은머리물떼새 |
| ⬜ | `piece-octopus.png` | 말: 주꾸미 |
| ⬜ | `mg-ramie-loom.png` | 모시 올 뽑기: 베틀 배경 |
| ⬜ | `mg-ramie-thread.png` | 모시 올 뽑기: 모시 실꾸리 |
| ⬜ | `mg-card-back.png` | 짝 맞추기: 카드 뒷면 |
| ⬜ | `mg-card-1.png` | 짝 맞추기: 모시풀 |
| ⬜ | `mg-card-2.png` | 짝 맞추기: 동백꽃 |
| ⬜ | `mg-card-3.png` | 짝 맞추기: 검은머리물떼새 |
| ⬜ | `mg-card-4.png` | 짝 맞추기: 주꾸미 |
| ⬜ | `mg-nest.png` | 철새 길 안내: 갈대밭 둥지 (출발점) |
| ⬜ | `mg-mudflat.png` | 철새 길 안내: 갯벌 먹이터 (도착점) |
| ⬜ | `mg-pylon.png` | 철새 길 안내: 전봇대 장애물 |
| ⬜ | `ui-title-bg.png` | 첫 화면 배경 |
| ⬜ | `ui-bus.png` | 서천 버스 아이콘 |
| ⬜ | `ui-heart.png` | 하트 (가득) |
| ⬜ | `ui-heart-empty.png` | 하트 (빈칸) |
| ⬜ | `ui-score.png` | 점수 아이콘 |
| ⬜ | `ui-hint.png` | 힌트 아이콘 |
| ⬜ | `ui-stamp.png` | 도장 자국 |
| ⬜ | `ui-trophy.png` | 완주 트로피 |
| ⬜ | `ui-paper.png` | 카드 바탕 종이 (반복 무늬) |

## 공통 스타일 문장

ChatGPT가 스타일을 잊은 것 같을 때 따로 붙여 넣으세요. (아래 프롬프트에는 이미 들어 있습니다.)

```text
[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="base"></a>

## 0. 기준 이미지 — 가장 먼저

1. **한 대화창에서 끝까지** 만드세요. 새 대화를 열면 스타일이 달라집니다.
1. 기준 이미지(`style-anchor.png`)를 확정한 뒤, 이후 모든 요청에 **그 그림을 첨부**합니다.
1. 투명 배경이 안 나오면 "make the background pure white #FFFFFF"로 다시 요청하고 배경은 정리 도구로 지웁니다.
1. 이미 있는 그림도 더 좋게 다시 만들고 싶으면 같은 프롬프트로 다시 요청해 같은 이름으로 덮어쓰면 됩니다.

### ⬜ 기준 이미지: 한산모시관 — `style-anchor.png` + `bld-ramie.png`

1024×1024 · 투명 배경

```text
A single miniature diorama building piece: a small traditional Korean craft museum about ramie cloth weaving inspired by the Hansan Ramie Hall in Seocheon, Korea — a tiled-roof hanok hall with wooden lattice doors and a stone step, an open side room showing a wooden floor loom with pale ivory ramie thread stretched on it, a small patch of tall green ramie plants beside the building, and a bamboo tray of thin ivory thread bundles at the entrance. The building sits on a round grassy base disc, like a board-game tile piece. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

→ 마음에 들 때까지 다시 만들고, 확정한 그림을 `style-anchor.png`와 `bld-ramie.png` 두 이름으로 저장합니다.

---

<a id="map"></a>

## 1. 지도 바탕

### ⬜ 지도 바탕 — `map-base.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide isometric miniature diorama landscape of a Korean west-coast county on a tabletop: a wide blue sea along the LEFT (west) side with a long pale sandy beach and a small rocky headland, a broad river estuary with a barrage sweeping across the BOTTOM (south) edge and a flat island of mud flats where the river meets the sea, golden reed beds along the river bank, a tall dark-green pine windbreak forest near the coast, low green hills with small rice paddies and patches of tall green ramie plants in the middle. Leave plenty of empty open flat ground spread across the land where game pieces will be placed later. NO buildings, no text. Wide landscape format, the land fills the frame like an island board on a table.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

건물이 그려져 나오면 "remove all buildings"로 다시 요청하세요.

---

<a id="bld"></a>

## 2. 장소 건물 12

모든 건물 프롬프트는 아래 **공통 앞부분**으로 시작합니다. 프롬프트 블록에 이미 들어 있습니다.

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.
```

### ⬜ 문헌서원 — `bld-moonheon.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small traditional Korean Confucian academy (seowon): a walled compound with a wooden entrance gate, two tiled-roof halls facing each other across a tidy courtyard, a low stone terrace, a tall old zelkova tree at the side, and a small lotus pond in front. Dignified and calm, nothing written anywhere. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 이상재 선생 생가지 — `bld-leesangjae.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A modest old Korean countryside house: a small thatched-roof hanok with earthen walls and paper-screen doors, a low wooden veranda, a packed-earth yard with a large clay jar and a wooden water bucket, a short stone wall, a persimmon tree with a few orange fruits, and a simple stone marker with no writing on it beside the gate. Warm and humble. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 신성리 갈대밭 — `bld-reed.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A riverside reed field scene: a dense field of tall golden reeds with feathery plumes leaning in the wind, a narrow wooden boardwalk path winding through them to a small viewing deck, a strip of calm blue river water at the edge, and two small birds flying up out of the reeds. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 금강하구 조류생태전시관 — `bld-birds.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small bird-watching exhibition hall by a river: a gently curved modern building with a wing-shaped roof and a round glass observation window, a tall slim observation tower with a telescope platform beside it, reeds and shallow water in front, and a small flock of ducks and geese resting on the water and flying overhead. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 서천갯벌 유부도 — `bld-tidal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A tidal flat island scene at low tide: a flat sandy-grey mud flat with shallow winding water channels and ripple patterns, scattered shells, two tiny crabs and a mudskipper, a small low green island with a few bushes at the back, and a group of small black-and-white wading birds with long orange bills feeding on the flat. The whole scene sits on a round base disc, half mud flat and half blue sea. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 국립생태원 에코리움 — `bld-ecology.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A cluster of connected glass greenhouse domes of different heights, like an ecology museum: a tall glass dome with palm trees visible inside, a smaller dome with pine and snow inside, joined by a low glass corridor, surrounded by a small garden pond with water lilies and a wooden walkway. Bright and inviting. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 장항스카이워크 — `bld-skywalk.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A high walkway through a pine forest: a long straight elevated wooden deck on slim steel posts, rising above the tops of tall dark-green pine trees, with a glass-floor section and simple railings, a small round viewing platform at the far end facing a strip of blue sea and pale sand. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 홍원항 — `bld-port.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small busy fishing harbour: a curved concrete breakwater with a tiny red beacon at its tip, two colorful wooden fishing boats moored at a short pier, stacked blue nets and round orange floats, a low harbour shed with an open front, flat racks of drying seaweed sheets, and shallow baskets of silvery fish and small octopuses. The whole scene sits on a round base disc, half stone quay and half blue sea. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 마량리 동백나무숲 — `bld-camellia.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small seaside grove of old camellia trees on a low coastal hill: gnarled low trunks with dense glossy dark-green leaves and many bright red camellia flowers, fallen red petals on the ground, a short stone path through the grove, and a small tiled-roof Korean pavilion at the top of the hill looking out to blue sea. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 출발: 한산모시문화제 마당 — `bld-start.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부 · **다른 건물보다 살짝 크게**

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base, but slightly larger than the other pieces.

A festive traditional craft festival plaza: a small outdoor stage with a tiled-roof canopy, long lines of pale ivory ramie cloth hung out to dry on wooden racks and fluttering in the wind, a hands-on weaving tent with a small loom, food stalls with striped awnings, round paper lanterns on a string, and a big cute mascot statue of a smiling ramie-thread spool (original design). The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 쉼터: 춘장대 솔밭 쉼터 — `bld-rest.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A restful pine grove by the beach: a small traditional Korean pavilion (jeongja) with a tiled roof among tall slim pine trees, a wooden bench and a straw mat on the sandy ground, a little table holding a steaming plate of grilled fish and two bowls, and a glimpse of pale sand and calm blue sea at the edge. The whole scene sits on a round base disc, half grass and half beach sand. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 찬스: 모시 실꾸리 바구니 — `bld-chance.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A cute woven bamboo basket overflowing with soft ivory ramie thread spools and loose shining threads, a few bright red camellia flowers and green ramie leaves tucked in, and one small wooden shuttle resting on the rim, all on the same round base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="char"></a>

## 3. 안내 캐릭터 — 서아 · 천이

먼저 **기본(normal)** 1장을 만들고, 그 그림을 첨부해 표정 4장을 뽑습니다. 같은 옷·같은 자세를 유지하는 것이 중요합니다.

### ⬜ 서아 기본 — `char-seoa-normal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a cute chibi child explorer character as a small painted toy figure: a girl with a short bob and a red camellia flower pin in her hair, wearing a pale ivory ramie-cloth summer jacket over a white tee, wide cropped trousers, cloth sneakers, carrying a small cloth shoulder bag and a tiny wooden thread spool in one hand. Full body, standing, facing slightly to the left, friendly smile. Centered, the whole figure visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 천이 기본 — `char-cheoni-normal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a cute chibi child explorer character as a small painted toy figure: a boy with short hair under a green bucket hat shaped like a reed leaf, wearing a sand-colored field vest with many small pockets over a blue tee, shorts, little hiking shoes, with binoculars hanging from his neck and a small notebook in one hand. Full body, standing, facing slightly to the left, bright cheerful smile. Centered, the whole figure visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 표정 4장씩 — 기본 그림을 첨부하고 `<표정>`만 바꿔 8장

1024×1024 · 투명 배경 · 📎 **그 캐릭터의 기본 그림** 첨부

```text
Same character as the attached image, same pose, same outfit, same camera angle and lighting. Only change the facial expression to: <표정>. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No text, no letters, no logos, no watermark.
```

| 서아 | 천이 | `<표정>`에 넣을 영어 | 게임에서 쓰는 곳 |
|---|---|---|---|
| `char-seoa-think.png` | `char-cheoni-think.png` | `thinking with a finger on the chin, eyes looking up` | 문제를 낼 때 |
| `char-seoa-happy.png` | `char-cheoni-happy.png` | `happy and cheering with both arms up` | 정답 |
| `char-seoa-sad.png` | `char-cheoni-sad.png` | `a little sad, downturned mouth` | 오답 |
| `char-seoa-surprised.png` | `char-cheoni-surprised.png` | `surprised, wide open eyes and round mouth` | 시간 초과 |

---

<a id="piece"></a>

## 4. 플레이어 말 4

네 개 모두 **같은 크기의 작은 둥근 받침** 위에 세웁니다. 받침 색은 동백 붉은빛 `#C62B2B`입니다.

### ⬜ 모시 요정 — `piece-ramie.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute ramie-plant fairy character, a slim ivory thread spool body wrapped in soft pale thread, with two big green ramie leaves as arms, tiny legs, a little thread tuft on its head and big round friendly eyes. It stands on a small round red (#C62B2B) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 동백이 — `piece-camellia.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute camellia flower character, a round bright red flower with layered petals as its head and a glossy dark-green leaf collar, short stem body with tiny arms and legs, big round eyes and rosy cheeks. It stands on a small round red (#C62B2B) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 검은머리물떼새 — `piece-bird.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute chubby wading bird character standing upright — black head and back, white belly, a long straight bright orange bill, orange legs, round red-ringed eyes, little wings tucked at its sides. It stands on a small round red (#C62B2B) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 주꾸미 — `piece-octopus.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute small webfoot octopus character, a round soft pinkish-beige head with big round eyes and a happy smile, eight short curly tentacles, two of them waving cheerfully. It stands on a small round red (#C62B2B) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="mg"></a>

## 5. 미니게임 그림 10

| 미니게임 | 쓰는 그림 |
|---|---|
| 모시 올 뽑기 (타이밍) | `mg-ramie-loom.png`, `mg-ramie-thread.png` |
| 서천 생태 짝 맞추기 | `mg-card-back.png`, `mg-card-1~4.png` |
| 철새 길 안내 (순차 명령) | `mg-nest.png`, `mg-mudflat.png`, `mg-pylon.png` |

### ⬜ 베틀 배경 — `mg-ramie-loom.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide front-view background of the inside of a traditional Korean weaving room: a wooden floor loom across the middle with many fine pale ivory ramie threads stretched tight from left to right, a woven bamboo basket of thread spools and a wooden shuttle on the straw-mat floor, warm wooden walls and a paper-screen window letting in soft light at the back. No characters, no text. Wide landscape format, viewed straight from the front.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 모시 실꾸리 — `mg-ramie-thread.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single ball of ramie thread, front view, slightly tilted: a soft round spool of fine pale ivory thread with a few loose strands trailing from it and one small green ramie leaf tucked at the side. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 카드 뒷면 — `mg-card-back.png`

768×1024 · 불투명 배경

```text
Create a flat playing-card back design, front view, no 3D perspective: a vertical card filled with a traditional Korean pattern of woven linen weave texture and small camellia flower shapes on a soft ivory ground, with a thin double border frame and a small circular flower emblem in the center. Symmetrical, evenly repeating, calm and clean. No letters, no numbers, no logos, no watermark.
```

### ⬜ 짝 맞추기 카드 그림 4장 — `mg-card-1.png` ~ `mg-card-4.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부 · 한 장씩 만드세요

```text
Using the attached image as the style reference, create a single centered object in the same toy-diorama style, simple and bold so it reads clearly at small size: <아래 표의 설명>. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

| 파일 | `<설명>`에 넣을 영어 |
|---|---|
| `mg-card-1.png` | `a small bundle of tall green ramie plants with broad heart-shaped leaves` |
| `mg-card-2.png` | `a single bright red camellia flower with two glossy dark-green leaves` |
| `mg-card-3.png` | `a black-and-white wading bird with a long orange bill, standing in profile` |
| `mg-card-4.png` | `a small pinkish-beige webfoot octopus with curly tentacles` |

### ⬜ 갈대밭 둥지 (출발점) — `mg-nest.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single small bird nest among reeds, simple and bold so it reads clearly at small size: a round woven nest of dry golden reed stems holding two pale speckled eggs, resting low between a few tall golden reed stalks with feathery plumes. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 갯벌 먹이터 (도착점) — `mg-mudflat.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single small round patch of tidal mud flat, simple and bold so it reads clearly at small size: a low disc of soft grey-brown mud with ripple patterns, a shallow puddle reflecting the sky, two small shells, one tiny crab and a few little worm holes, with a thin ring of shallow blue water around the edge. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 전봇대 장애물 — `mg-pylon.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single chunky obstacle, simple and bold so it reads clearly at small size: a short grey concrete utility pole with two small crossarms and a few sagging wires cut off at the edges, a small insulator cap on top, standing on a tiny square base. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="ui"></a>

## 6. 화면(UI) 그림 9

아이콘은 화면에서 작게(64px) 보입니다. **단순하고 굵게** 나오는지 확인하세요. 파일이 없으면 지금처럼 이모지로 보이고, 넣으면 바로 바뀝니다.

### ⬜ 첫 화면 배경 — `ui-title-bg.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide key-art background for the title screen of a board game: the Seocheon miniature island board seen from a low angle along the bottom of the frame — golden reed beds, a river estuary with mud flats, a pine windbreak forest, a small fishing harbour and a glass greenhouse dome — with a soft warm morning sky above, fluffy clouds, a loose flock of migratory birds flying across and a few drifting reed seeds. Keep the CENTER and upper middle of the image calm and empty (soft sky) for the title text. No characters, no text.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 서천 버스 아이콘 — `ui-bus.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute chunky little country bus, ivory and forest-green colors with a golden reed-leaf stripe along the side, round headlights, three-quarter front view. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 하트 (가득) — `ui-heart.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A glossy plump red heart shaped like a camellia bud, with layered petal lines and a tiny glossy green leaf on top. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 하트 (빈칸) — `ui-heart-empty.png`

512×512 · 투명 배경 · 📎 `ui-heart.png` 첨부

```text
The same plump heart shape as the attached image but empty: pale ivory translucent with a soft outline, like an empty slot, no shine. Same size, same angle, same position. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No text, no letters, no logos, no watermark.
```

### ⬜ 점수 아이콘 — `ui-score.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A shiny golden coin with an embossed camellia flower on its face (no letters), slightly tilted. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 힌트 아이콘 — `ui-hint.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute pair of binoculars with a wooden-and-brass body and a small glowing reed leaf reflected in one lens. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 도장 자국 — `ui-stamp.png`

512×512 · 투명 배경

```text
Create a flat game UI element, front view, no 3D perspective: a round red ink seal stamp impression like a traditional Korean seal, slightly rough ink texture at the edges, with a simple camellia flower symbol in the center and a double ring border. No letters. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No logos, no watermark.
```

### ⬜ 완주 트로피 — `ui-trophy.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute golden trophy cup with two handles on a small base, a red camellia flower set in the front of the cup and a thin woven linen pattern around the rim, a few sparkles around it. No letters. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 카드 바탕 종이 — `ui-paper.png`

768×768 · 불투명 배경 · **이어 붙여도 자연스럽게(seamless)**

```text
Create a flat seamless tileable paper texture, front view, no 3D perspective: warm ivory handmade Korean paper (hanji) with soft visible fibers and a very faint woven linen weave pattern spread evenly, slightly uneven tone. Very low contrast so dark text stays readable on top. Seamless on all four edges. No letters, no numbers, no logos, no watermark.
```

---

## 사진 준비 (선택)

사진 퀴즈(`questions.json`의 문항에 `"image": "photos/파일명.jpg"`를 더하면 문제 위에 사진이 나옵니다)를 쓰려면 아래 사진을 모아 `public/regions/seocheon/photos/`에 넣고 출처 표를 함께 주세요.

| 분류 | 사진 |
|---|---|
| 장소 | 한산모시관과 베틀, 문헌서원, 이상재 선생 생가, 신성리 갈대밭, 금강하구 철새 떼, 유부도 갯벌, 국립생태원 에코리움, 장항스카이워크, 홍원항, 마량리 동백나무숲 |
| 특산물·음식 | 모시옷·모시 원단, 김, 전어, 주꾸미, 꽃게 |
| 인물·유물 | 목은 이색 영정, 월남 이상재 선생 사진 |

- 가로 4:3, 가로 1200px 이상, 간판·이름이 보이지 않는 사진이 퀴즈용으로 좋습니다.
- 파일 이름은 영문 소문자 (예: `hansan-ramie.jpg`, `sinseongri-reed.jpg`).
- **직접 촬영**, **공공누리 제1유형**, **기관 허락 사진**만 씁니다. 블로그·뉴스 사진은 허락 없이 쓰지 않습니다.

---

<a id="icon"></a>

## 7. 앱 아이콘 — `public/icons/`

바탕화면에 "앱 설치"로 둘 때 쓰는 아이콘입니다. 지금은 **금산판 아이콘이 그대로 들어 있어** 반드시 다시 만들어 덮어써야 합니다.
한 장(1024×1024)을 만들고 **512×512**와 **192×192**로 줄여 저장하세요. 저장 위치는 `public/icons/`이고 파일 이름은 `icon-512.png`, `icon-192.png`입니다.

### ⬜ 앱 아이콘 — `icon-512.png` + `icon-192.png`

1024×1024 · **불투명 배경** (아이콘은 배경이 꽉 차야 합니다) · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a square mobile app icon, front view, centered, simple and bold so it reads clearly at 64px: a soft ivory spool of ramie thread with one bright red camellia flower tucked beside it and a few golden reed plumes behind, sitting on a pine-green rounded-square background with a soft radial glow. Fill the whole square edge to edge with the background, leave a small safe margin around the subject, no rounded corner cut out. No text, no letters, no numbers, no logos, no watermark.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: ramie linen ivory #E8E3D3, reed gold #C9A24A,
camellia red #C62B2B, Geumgang river blue #3A7FA6, pine forest green #35704A.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

> 아이콘은 `public/icons/`에 들어가며 `art/` 폴더가 아닙니다. 파일 이름을 바꾸면 `public/manifest.webmanifest`도 함께 고쳐야 합니다.
