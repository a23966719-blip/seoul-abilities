# EP.01 "당신의 온도" — 풀 영상 프롬프트 (B+D 방식)

> **방식**: 나노바나나프로에서 이미지 생성 → 구글 플로우에서 영상 클립으로 변환 → 브루에서 슬로우모션
> **장점**: 캐릭터 외모 일관성 유지 + 정지 이미지 없이 전부 움직이는 영상
> **총 클립 수**: 18개

---

## 작업 순서

```
STEP 1: 나노바나나프로에서 이미지 18장 생성 (아래 프롬프트 복붙)
STEP 2: 생성된 이미지를 구글 플로우에 넣고 영상 클립으로 변환 (아래 지시문 복붙)
STEP 3: 브루에서 대본 입력 → 성우 생성 → 영상 클립 배치 → 슬로우모션 적용
```

---

## 캐릭터 외모 통일 키워드

프롬프트마다 캐릭터가 등장할 때 아래 외모 설명을 동일하게 넣어주세요.

**김민재 (57세 남자)**:
```
a 57-year-old Korean man with salt-and-pepper hair combed back, gentle tired eyes, slight wrinkles, wearing a plain dark navy jacket over a white shirt
```

**윤정희 (55세 여자)**:
```
a 55-year-old Korean woman with shoulder-length black hair with some gray, warm crescent-moon smile, wearing a beige cardigan and a green apron
```

**정태호 (58세 남자)**:
```
a 58-year-old Korean man with half-gray hair swept back, a round friendly face, wearing a worn brown apron over a checkered shirt
```

---

## STEP 1: 나노바나나프로 이미지 프롬프트 (18장)

> 모든 프롬프트 끝에 스타일 키워드가 붙어 있습니다.
> 그대로 복사해서 나노바나나프로에 붙여넣으세요.

---

### 이미지 01: 타이틀 — 손 클로즈업
```
Extreme close-up of a 57-year-old Korean man's weathered hands resting on his knees. His fingers have age spots. Autumn sunlight streams through a window, casting warm light on his hands. Dust particles float in the air. Soft focus background. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 02: 아침 — 아파트 벤치
```
A 57-year-old Korean man with salt-and-pepper hair combed back, wearing a plain dark navy jacket over a white shirt, sitting alone on a bench near a Korean apartment complex in early morning. He is eating a triangle kimbap. Autumn leaves scattered on the ground. Quiet, lonely mood. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 03: 아침 — 산책로 낙엽길
```
A 57-year-old Korean man with salt-and-pepper hair, wearing a dark navy jacket, walking alone on a tree-lined path covered with fallen autumn leaves. Residential area in Seoul. Morning light filtering through branches. His left hand is slightly clenched in his pocket. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 04: 회상 — 병실에서 아내 곁
```
A Korean man in his early 50s with dark hair, holding his sick wife's hand in a dimly lit hospital room at night. IV drip stand in background. His hand has a very faint warm glow where it touches her hand. Melancholic, tender atmosphere. Slightly hazy like a memory. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 05: 회상 — 홀로 남은 빈 병실
```
An empty hospital bed with rumpled white sheets, a single wilted flower in a vase on the nightstand. Morning light through the window. The room feels abandoned and quiet. A man's jacket is draped over the chair. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 06: 꽃집 외관 — 정희네 꽃방
```
A small charming Korean flower shop on a quiet neighborhood street corner. Hand-painted wooden sign reading in Korean style. Chrysanthemum pots lined up outside the open glass door. Autumn afternoon light. A 57-year-old Korean man with salt-and-pepper hair stands at a distance, looking at the shop. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 07: 재회 — 꽃집 안에서 눈 마주침
```
Inside a small flower shop, a 57-year-old Korean man with salt-and-pepper hair and a 55-year-old Korean woman with shoulder-length black hair with some gray, looking at each other with shocked recognition. Flowers and gardening tools surround them. Warm natural light from the window. Time-stopped feeling. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 08: 꽃집 대화 — 커피 마시며
```
Inside a small Korean flower shop, a 57-year-old Korean man in a navy jacket and a 55-year-old Korean woman in a beige cardigan and green apron, sitting across each other at a work table drinking instant coffee from paper cups. Bandages on the woman's fingers. Roses and scissors on the table. Warm, nostalgic mood. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 09: 매일 지나치는 — 꽃집 유리문 너머
```
View from outside a flower shop glass door. A 55-year-old Korean woman in a green apron is inside arranging flowers, seen through the slightly foggy glass. The reflection of a man can be faintly seen in the glass. Autumn street behind. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 10: 태호네 다방 — 카페 전경
```
Interior of a traditional Korean hanok converted into a small cozy cafe. A 58-year-old Korean man with half-gray hair, wearing a worn brown apron over a checkered shirt, stands behind a wooden counter pouring hand-drip coffee. Steam rises. Warm dim lighting. Wooden floors. Traditional architecture mixed with modern coffee equipment. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 11: 태호네 다방 — 대화 장면
```
Inside a traditional Korean hanok cafe. A 57-year-old Korean man in a navy jacket sits at a wooden table looking down at his coffee cup with a troubled expression. Across from him, a 58-year-old man in a brown apron leans on the counter listening. Two coffee cups between them. Intimate, confessional atmosphere. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 12: 위기 — 꽃방 바닥에 쓰러진 정희
```
Inside a flower shop, a 55-year-old Korean woman with shoulder-length hair sits on the floor clutching her lower back in pain. A broken flower pot lies beside her. Soil scattered on the floor. Her face is pale with cold sweat. Dramatic lighting. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 13: 치유 — 등에 손을 대는 민재
```
Inside a flower shop, a 57-year-old Korean man kneels beside a woman sitting on the floor. His right hand is placed gently on her back. A soft warm golden light emanates from his palm. The woman's pained face is beginning to relax. Emotional, dramatic lighting. Close-up framing. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 14: 발각 — 피가 나는 손가락
```
Close-up of two hands. A woman's finger is healed, clean. The man's same finger is bleeding. Both people are looking down at the hands in shock. Flower shop background blurred. Tense, dramatic atmosphere. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 15: 단절 — 닫힌 꽃집 셔터
```
A closed flower shop with the metal shutter down. Autumn morning. A 57-year-old Korean man in a navy jacket stands in front of it, looking at the closed shutter. His posture is slumped, hands in pockets. Lonely, quiet atmosphere. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 16: 화해 — 현관 앞 국화와 메모
```
A bouquet of yellow and white chrysanthemums placed on a Korean apartment doorstep. A small handwritten note is tucked into the flowers. Soft warm evening light from the hallway. Hopeful, tender mood. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 17: 한강 산책 — 나란히 걷는 두 사람
```
A 57-year-old Korean man in a navy jacket and a 55-year-old Korean woman in a beige cardigan walking side by side along the Hangang river walkway in Seoul. Golden hour sunset. Autumn trees line the path. Golden sunlight reflects on the river. They are not holding hands but walking very close. Wind gently moves their hair. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

### 이미지 18: 엔딩 — 태호네 다방 창밖 저녁
```
View from inside a traditional Korean hanok cafe looking out through the window at dusk. A steaming coffee cup on a wooden table in the foreground. Outside, a narrow Seoul alley with warm street lights turning on. A 57-year-old man is seen from behind, looking out the window with a peaceful expression. cinematic composition, warm color palette, Korean modern drama style, soft natural lighting, emotional atmosphere, no text, photorealistic
```

---

## STEP 2: 구글 플로우 변환 지시문

> 나노바나나프로에서 만든 이미지를 구글 플로우에 업로드한 뒤, 아래 지시문을 붙여넣으세요.

### 클립 01 (이미지 01 사용): 손끝의 빛
```
Animate this image. The man's fingers slowly curl slightly. A faint warm golden glow pulses gently from his fingertips like a heartbeat. Dust particles drift slowly in the sunlight. Very slow, subtle movement. Camera very slowly pulls back. 8 seconds.
```

### 클립 02 (이미지 02 사용): 벤치에 앉은 아침
```
Animate this image. The man slowly unwraps and eats a rice ball. Autumn leaves drift gently past in the breeze. He looks up and sighs. Peaceful but lonely. Slow movement. 6 seconds.
```

### 클립 03 (이미지 03 사용): 낙엽길 산책
```
Animate this image. The man walks slowly forward along the leaf-covered path. Leaves crunch underfoot. His left hand in his pocket twitches slightly. Camera follows from behind. Slow pace. 6 seconds.
```

### 클립 04 (이미지 04 사용): 병실 회상
```
Animate this image. The man's thumb gently strokes his wife's hand. A faint warm glow pulses where their hands touch. The IV drip slowly drops. Very slow, dreamlike movement. Slightly hazy. 6 seconds.
```

### 클립 05 (이미지 05 사용): 빈 병실
```
Animate this image. Camera slowly pans across the empty hospital room. The curtain sways gently in a breeze from the window. Light slowly shifts. No people, just stillness. 5 seconds.
```

### 클립 06 (이미지 06 사용): 꽃집 발견
```
Animate this image. The man walks slowly toward the flower shop from a distance. He stops and looks at the open glass door. A woman's shadow moves inside. Camera slowly pushes forward. 7 seconds.
```

### 클립 07 (이미지 07 사용): 재회 눈 마주침
```
Animate this image. Both people stare at each other in frozen surprise. The woman slowly straightens up. The man's eyes widen. Time seems to stop. Very slow, almost still. Camera slowly zooms in on their faces. 6 seconds.
```

### 클립 08 (이미지 08 사용): 커피 마시며 대화
```
Animate this image. The man and woman sit across from each other, occasionally sipping coffee. The woman laughs and her eyes become crescent moons. The man smiles shyly. Warm, natural conversation movement. 7 seconds.
```

### 클립 09 (이미지 09 사용): 유리문 너머
```
Animate this image. Through the glass door, the woman inside moves flowers from one vase to another. The man's reflection in the glass slightly shifts as he watches. Gentle, voyeuristic feeling. 6 seconds.
```

### 클립 10 (이미지 10 사용): 태호네 다방 전경
```
Animate this image. The barista slowly pours water over coffee grounds. Steam rises gently. Camera slowly pans across the hanok cafe interior. Jazz atmosphere. Warm and cozy. 7 seconds.
```

### 클립 11 (이미지 11 사용): 태호와 대화
```
Animate this image. The younger man looks down at his coffee, then looks up. The barista nods slowly and speaks. Coffee steam rises between them. Intimate, confessional mood. 6 seconds.
```

### 클립 12 (이미지 12 사용): 정희 쓰러짐
```
Animate this image. The woman on the floor shifts in pain, grimacing. She clutches her back. Soil from the broken pot settles. Dramatic, urgent feeling. 5 seconds.
```

### 클립 13 (이미지 13 사용): 치유 장면
```
Animate this image. The man's hand on her back begins to glow with warm golden light. The glow slowly intensifies then fades. The woman's face gradually relaxes from pain to relief. Very emotional, slow movement. 8 seconds.
```

### 클립 14 (이미지 14 사용): 피가 나는 손가락
```
Animate this image. A drop of blood slowly forms on the man's finger. Both people slowly look down at their hands. The woman's hand pulls back slightly. Tense, dramatic. Close-up. 6 seconds.
```

### 클립 15 (이미지 15 사용): 닫힌 꽃집
```
Animate this image. The man stands motionless in front of the closed shutter. Wind blows autumn leaves past his feet. He slowly turns and walks away. Lonely, melancholic. 7 seconds.
```

### 클립 16 (이미지 16 사용): 국화와 메모
```
Animate this image. Camera slowly zooms in on the chrysanthemum bouquet on the doorstep. The note flutters slightly in a gentle draft from the hallway. Warm evening light. Hopeful mood. 5 seconds.
```

### 클립 17 (이미지 17 사용): 한강 산책
```
Animate this image. The man and woman walk slowly side by side along the river. Golden sunset light shimmers on the water. Wind gently moves the woman's hair. They walk close but don't hold hands. Camera follows from behind in a slow tracking shot. 8 seconds.
```

### 클립 18 (이미지 18 사용): 카페 엔딩
```
Animate this image. Steam rises slowly from the coffee cup. Outside the window, the alley lights turn on one by one. The man's reflection in the glass shows a peaceful smile. Camera slowly pushes toward the window. 7 seconds.
```

---

## STEP 3: 브루(Vrew) 슬로우모션 가이드

| 클립 | 원본 길이 | 슬로우모션 | 최종 길이 | 대본 구간 |
|------|-----------|-----------|-----------|-----------|
| 01 손끝의 빛 | 8초 | 1.5배 | ~12초 | 0:00~0:12 |
| 02 벤치 아침 | 6초 | 2.5배 | ~15초 | 0:12~1:30 |
| — *02 루프 재생* | | 반복 | ~2분30초 채움 | ~3:30까지 |
| 03 낙엽길 산책 | 6초 | 2배 | ~12초 | 3:30~5:00 |
| — *03 루프+역재생* | | 반복 | ~1분30초 채움 | |
| 04 병실 회상 | 6초 | 2배 | ~12초 | 5:00~6:00 |
| 05 빈 병실 | 5초 | 2배 | ~10초 | 6:00~7:30 |
| — *04-05 교차 디졸브* | | 전환 | 자연스럽게 채움 | |
| 06 꽃집 발견 | 7초 | 2배 | ~14초 | 7:30~8:30 |
| 07 재회 눈 마주침 | 6초 | 2.5배 | ~15초 | 8:30~10:00 |
| — *06-07 디졸브* | | 전환 | 자연스럽게 채움 | |
| 08 커피 대화 | 7초 | 2배 | ~14초 | 10:00~11:30 |
| 09 유리문 너머 | 6초 | 2배 | ~12초 | 11:30~13:00 |
| — *08-09 루프* | | 반복 | ~2분 채움 | |
| 10 태호네 다방 | 7초 | 2배 | ~14초 | 13:00~14:30 |
| 11 태호 대화 | 6초 | 2배 | ~12초 | 14:30~16:30 |
| — *10-11 교차* | | 전환 | 자연스럽게 채움 | |
| 12 정희 쓰러짐 | 5초 | 1.5배 | ~8초 | 16:30~17:00 |
| 13 치유 장면 | 8초 | 2배 | ~16초 | 17:00~19:00 |
| — *12-13 연결* | | 컷 전환 | 긴장감 유지 | |
| 14 피 나는 손가락 | 6초 | 2.5배 | ~15초 | 19:00~20:00 |
| 15 닫힌 꽃집 | 7초 | 2배 | ~14초 | 20:00~22:00 |
| — *14-15 루프* | | 반복 | ~2분 채움 | |
| 16 국화와 메모 | 5초 | 2배 | ~10초 | 22:00~22:30 |
| 17 한강 산책 ★핵심★ | 8초 | 2.5배 | ~20초 | 22:30~26:00 |
| — *17 루프+역재생* | | 반복 | ~3분30초 채움 | |
| 18 카페 엔딩 | 7초 | 2.5배 | ~18초 | 26:00~30:00 |
| — *18 루프* | | 반복 | ~4분 채움 | |

### 슬로우모션 + 루프 팁

```
- 슬로우모션 1.5~2.5배: 브루에서 클립 선택 → 속도 조절 → 0.4~0.7배속
  (0.5배속 = 원래의 2배 길이)
- 루프: 같은 클립을 복사해서 이어 붙이기
- 역재생 루프: 클립 복사 → 역재생 → 원본 뒤에 붙이기 (자연스러운 반복)
- 디졸브 전환: 클립 사이에 1~3초 디졸브 (시간도 채우고 자연스러움)
- 핵심 장면(치유, 한강)은 슬로우모션 강하게 (2.5배)
- 대화 장면(카페, 꽃집)은 루프로 시간 채우기
```

---

## 최종 요약

| 항목 | 수량 |
|------|------|
| 나노바나나프로 이미지 | **18장** |
| 구글 플로우 영상 클립 | **18개** |
| 브루 슬로우모션+루프 후 | **30분 풀 영상** |
| 정지 이미지 구간 | **0개** (전부 움직이는 영상) |
