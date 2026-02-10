# EP.01 "당신의 온도" — 풀 영상 프롬프트 (B+D 방식 / 극사실)

> **방식**: 나노바나나프로에서 이미지 생성 → 구글 플로우에서 영상 클립으로 변환 → 브루에서 슬로우모션
> **스타일**: 극사실(포토리얼리스틱) — 실제 한국 드라마처럼 보이는 영상
> **총 클립 수**: 18개

---

## 작업 순서

```
STEP 1: 나노바나나프로에서 극사실 이미지 18장 생성 (아래 프롬프트 복붙)
STEP 2: 생성된 이미지를 구글 플로우에 넣고 영상 클립으로 변환 (아래 지시문 복붙)
STEP 3: 브루에서 대본 입력 → 성우 생성 → 영상 클립 배치 → 슬로우모션 적용
```

---

## 스타일 통일 키워드 (극사실)

### 나노바나나프로 이미지용 (모든 프롬프트 끝에 이미 포함됨)
```
photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 구글 플로우 영상용 (모든 영상 프롬프트 끝에 이미 포함됨)
```
photorealistic, hyperrealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p
```

---

## 캐릭터 외모 통일 키워드

프롬프트마다 캐릭터가 등장할 때 아래 외모 설명을 동일하게 넣어주세요.

**김민재 (57세 남자)**:
```
a 57-year-old Korean man with salt-and-pepper hair neatly combed back, gentle tired eyes with crow's feet, weathered skin with natural wrinkles, wearing a plain dark navy jacket over a white collared shirt
```

**윤정희 (55세 여자)**:
```
a 55-year-old Korean woman with shoulder-length black hair with natural gray streaks, warm crescent-moon eyes when smiling, minimal makeup, wearing a beige knit cardigan over a cream blouse and a faded green canvas apron
```

**정태호 (58세 남자)**:
```
a 58-year-old Korean man with half-gray hair swept back, a round weathered friendly face, deep laugh lines, wearing a worn brown linen apron over a red-and-navy checkered flannel shirt
```

---

## STEP 1: 나노바나나프로 이미지 프롬프트 (18장)

> 그대로 복사해서 나노바나나프로에 붙여넣으세요.

---

### 이미지 01: 타이틀 — 손 클로즈업
```
Extreme close-up photograph of a 57-year-old Korean man's weathered hands resting on his knees. Visible age spots, dry skin, fine wrinkles on knuckles. Autumn sunlight streams through a window casting warm golden rays on his hands. Dust particles float in the light beam. Shallow depth of field, blurred background of a simple Korean apartment living room. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 02: 아침 — 아파트 벤치
```
A 57-year-old Korean man with salt-and-pepper hair neatly combed back, gentle tired eyes with crow's feet, wearing a plain dark navy jacket over a white collared shirt, sitting alone on a concrete bench near a typical Korean apartment complex in early morning. He holds a triangle kimbap from a convenience store. Fallen autumn leaves on the ground. Gray apartment buildings behind him. Overcast morning sky. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 03: 아침 — 산책로 낙엽길
```
A 57-year-old Korean man with salt-and-pepper hair, wearing a dark navy jacket, walking alone on a paved path lined with ginkgo trees in a Korean residential neighborhood. Ground covered with golden fallen leaves. Morning light filtering through branches creating dappled shadows. His left hand is slightly clenched in his jacket pocket. Shot from behind at a slight angle. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 04: 회상 — 병실에서 아내 곁
```
A Korean man in his early 50s with dark hair, sitting in a plastic hospital chair, holding his sick wife's thin hand. She lies in a hospital bed with an IV drip. Dim fluorescent lighting mixed with a warm bedside lamp. His hand has a very faint warm glow where it touches hers. The room has typical Korean hospital details — green curtain divider, patient monitor. Slightly hazy like a faded memory. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 05: 회상 — 홀로 남은 빈 병실
```
An empty Korean hospital bed with rumpled white sheets. A single wilted flower in a cheap glass vase on the metal nightstand. Pale morning light through venetian blinds casting striped shadows. A man's dark jacket is draped over the visitor chair. The room feels hollow and silent. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 06: 꽃집 외관 — 정희네 꽃방
```
A small Korean neighborhood flower shop on a quiet street corner in Seoul. A hand-painted wooden sign hangs above the door. Chrysanthemum pots and seasonal flowers arranged outside the open glass door on the sidewalk. Autumn afternoon golden light. A 57-year-old Korean man with salt-and-pepper hair in a navy jacket stands several meters away on the sidewalk, looking toward the shop. Real Korean street with utility poles, parked car, low-rise buildings. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 07: 재회 — 꽃집 안에서 눈 마주침
```
Inside a small flower shop, a 57-year-old Korean man with salt-and-pepper hair and a 55-year-old Korean woman with shoulder-length black hair with gray streaks, facing each other with expressions of stunned recognition. Surrounded by buckets of fresh flowers, gardening tools, soil bags. Warm natural light from the glass door behind the man. Her green apron is slightly dirty from work. His eyes are wide. Her hand covers her mouth in surprise. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 08: 꽃집 대화 — 커피 마시며
```
Inside a small Korean flower shop, a 57-year-old Korean man in a navy jacket and a 55-year-old Korean woman in a beige cardigan and green apron, sitting across each other at a cluttered wooden work table. They drink instant coffee from mismatched ceramic mugs. Small bandages on the woman's fingers. Half-trimmed roses and pruning scissors on the table. Warm afternoon light through the window. They look at each other with shy, nostalgic smiles. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 09: 매일 지나치는 — 꽃집 유리문 너머
```
View from outside a flower shop through a slightly foggy glass door. Inside, a 55-year-old Korean woman in a green apron is arranging a bouquet at her work table, concentrating. The faint reflection of a man in a navy jacket can be seen in the glass. Autumn street and fallen leaves reflected in the door. Voyeuristic, tender feeling. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 10: 태호네 다방 — 카페 전경
```
Interior of a real traditional Korean hanok building converted into a small cafe. A 58-year-old Korean man with half-gray hair, wearing a worn brown linen apron over a red-and-navy checkered flannel shirt, stands behind a dark wooden counter carefully pouring hot water over a hand-drip coffee filter. Steam rises. Warm dim lighting from paper lanterns. Wooden beams, stone floor, old wooden shelves with coffee cups. A small radio plays in the corner. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 11: 태호네 다방 — 대화 장면
```
Inside a traditional Korean hanok cafe. A 57-year-old Korean man in a navy jacket sits at a low wooden table looking down at his coffee cup with a troubled, conflicted expression. A 58-year-old man in a brown apron leans against the counter across from him, listening with a knowing, gentle expression. Two ceramic coffee cups between them. Steam rises. Intimate, warm, confessional atmosphere. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 12: 위기 — 꽃방 바닥에 쓰러진 정희
```
Inside a flower shop, a 55-year-old Korean woman with shoulder-length hair sits on the tiled floor, clutching her lower back with both hands, face twisted in pain. Cold sweat on her forehead. A broken terracotta flower pot lies beside her, soil and a crushed plant spilled across the floor. Water from a knocked-over bucket spreads on the tiles. Dramatic side lighting. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 13: 치유 — 등에 손을 대는 민재
```
Inside a flower shop, a 57-year-old Korean man kneels on the tiled floor beside a woman sitting in pain. His right hand is placed gently on her lower back. A soft warm golden light radiates from his palm where it touches her back. The woman's face shows the transition from pain to gradual relief, eyes half-closed. Close-up framing from the side. Emotional, dramatic warm lighting. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 14: 발각 — 피가 나는 손가락
```
Extreme close-up of two hands held palm-up. The woman's right index finger is clean and healed where a cut used to be. The man's right index finger has a fresh cut, a drop of blood forming. Both people's faces are visible in soft focus background, looking down at the hands with shock. Flower shop interior blurred behind them. Tense, dramatic atmosphere. photorealistic, hyperrealistic, shot on Sony A7IV with 85mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 15: 단절 — 닫힌 꽃집 셔터
```
A Korean flower shop with its gray metal rolling shutter closed. No flowers outside. Autumn morning, overcast sky. A 57-year-old Korean man in a navy jacket stands alone in front of it, looking at the closed shutter. His shoulders are slumped, hands deep in pockets. Fallen leaves on the sidewalk. A lonely, quiet residential street. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 16: 화해 — 현관 앞 국화와 메모
```
A small bouquet of yellow and white chrysanthemums wrapped in brown kraft paper, placed on the doormat of a Korean apartment front door. A small handwritten note on white paper is tucked between the flowers. Warm hallway fluorescent light. The apartment door is painted gray-green, typical Korean style. Close-up shot, hopeful and tender mood. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 17: 한강 산책 — 나란히 걷는 두 사람
```
A 57-year-old Korean man in a dark navy jacket and a 55-year-old Korean woman in a beige knit cardigan walking side by side along the paved Hangang river walkway in Seoul. Golden hour sunset. The Han River sparkles with orange and gold reflections. Autumn trees with red and yellow leaves line the path. They walk very close but are not holding hands. Wind gently lifts the woman's hair. Shot from behind at a low angle. Real Yeouido or Banpo riverside scenery. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

### 이미지 18: 엔딩 — 태호네 다방 창밖 저녁
```
View from inside a traditional Korean hanok cafe looking out through the wooden-framed window at dusk. A steaming ceramic coffee cup sits on a dark wooden table in the foreground. Outside the window, a narrow Ikseon-dong alley in Seoul with warm yellow street lights just turned on, stone walls, and a few passing silhouettes. A 57-year-old man is seen from behind, his reflection faintly visible in the glass, with a peaceful expression. photorealistic, hyperrealistic, shot on Sony A7IV with 35mm lens, natural skin texture, real location in Seoul, cinematic color grading, warm tones, shallow depth of field, no text, no watermark
```

---

## STEP 2: 구글 플로우 변환 지시문

> 나노바나나프로에서 만든 이미지를 구글 플로우에 업로드한 뒤, 아래 지시문을 붙여넣으세요.

### 클립 01 (이미지 01 사용): 손끝의 빛
```
Animate this photo into a realistic cinematic video. The man's fingers slowly curl slightly. A faint warm golden glow pulses gently from his fingertips. Dust particles drift slowly in the sunlight. Very slow, subtle movement only. Camera very slowly dollies back. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 8 seconds.
```

### 클립 02 (이미지 02 사용): 벤치에 앉은 아침
```
Animate this photo into a realistic cinematic video. The man slowly chews and looks around the empty apartment courtyard. Autumn leaves drift gently past in the wind. He exhales and his breath is slightly visible in the cold air. Very slow, realistic movement. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 03 (이미지 03 사용): 낙엽길 산책
```
Animate this photo into a realistic cinematic video. The man walks slowly forward along the leaf-covered path. Leaves rustle underfoot. His left hand in his pocket clenches slightly. Camera follows from behind in a steady tracking shot. Wind moves the tree branches. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 04 (이미지 04 사용): 병실 회상
```
Animate this photo into a realistic cinematic video. The man's thumb gently strokes his wife's hand. A faint warm glow pulses where their hands touch. The IV drip slowly drops. Her chest rises and falls weakly. Very slow, dreamlike movement. Slightly soft focus like a memory. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 05 (이미지 05 사용): 빈 병실
```
Animate this photo into a realistic cinematic video. Camera slowly pans right across the empty hospital room. The curtain sways gently in a breeze from the cracked window. Sunlight slowly shifts across the empty bed. Still and quiet. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 5 seconds.
```

### 클립 06 (이미지 06 사용): 꽃집 발견
```
Animate this photo into a realistic cinematic video. The man walks slowly toward the flower shop. He stops when he hears a woman's voice from inside. He tilts his head and takes a step closer. Camera slowly pushes forward past him toward the shop door. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 7 seconds.
```

### 클립 07 (이미지 07 사용): 재회 눈 마주침
```
Animate this photo into a realistic cinematic video. Both people freeze, staring at each other. The woman slowly lowers the flowers in her hand. The man's lips part slightly as if about to speak. Time feels suspended. Very slow movement. Camera slowly zooms in. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 08 (이미지 08 사용): 커피 마시며 대화
```
Animate this photo into a realistic cinematic video. The woman laughs and her eyes become crescents. The man looks down shyly and smiles. She lifts her coffee mug. Steam rises between them. Natural, warm conversation. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 7 seconds.
```

### 클립 09 (이미지 09 사용): 유리문 너머
```
Animate this photo into a realistic cinematic video. Through the glass door, the woman inside slowly arranges flowers, moving stems from one bucket to another. The man's reflection in the glass shifts slightly as he watches from outside. A leaf blows across the glass. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 10 (이미지 10 사용): 태호네 다방 전경
```
Animate this photo into a realistic cinematic video. The barista carefully pours hot water in a circular motion over coffee grounds. Steam rises and curls. Camera slowly pans left across the hanok cafe interior, revealing wooden beams and shelves of cups. Warm, cozy atmosphere. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 7 seconds.
```

### 클립 11 (이미지 11 사용): 태호와 대화
```
Animate this photo into a realistic cinematic video. The man in the navy jacket stares into his coffee cup, then slowly looks up. The barista nods slowly and gestures gently while speaking. Coffee steam drifts between them. Intimate mood. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 12 (이미지 12 사용): 정희 쓰러짐
```
Animate this photo into a realistic cinematic video. The woman shifts on the floor in pain, wincing. She adjusts her grip on her lower back. The spilled water slowly spreads across the tile. Soil from the broken pot settles. Urgent, dramatic. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 5 seconds.
```

### 클립 13 (이미지 13 사용): 치유 장면
```
Animate this photo into a realistic cinematic video. The man's hand on her back begins to glow with warm golden light. The glow slowly intensifies, then gently fades. The woman's clenched face gradually softens with relief. Her shoulders drop as pain leaves. Very slow, emotional. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 8 seconds.
```

### 클립 14 (이미지 14 사용): 피가 나는 손가락
```
Animate this photo into a realistic cinematic video. A drop of blood slowly forms and grows on the man's finger. Both people slowly tilt their heads down to look at the hands. The woman's clean finger trembles slightly. She slowly pulls her hand back. Tense. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 6 seconds.
```

### 클립 15 (이미지 15 사용): 닫힌 꽃집
```
Animate this photo into a realistic cinematic video. The man stands still in front of the closed shutter. Wind blows fallen leaves across the sidewalk past his feet. He lowers his head, then slowly turns and walks away. Camera stays still as he recedes. Lonely. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 7 seconds.
```

### 클립 16 (이미지 16 사용): 국화와 메모
```
Animate this photo into a realistic cinematic video. Camera slowly zooms in on the chrysanthemum bouquet on the doorstep. The note tucked in the flowers flutters slightly from a draft in the hallway. Warm light. Hopeful. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 5 seconds.
```

### 클립 17 (이미지 17 사용): 한강 산책
```
Animate this photo into a realistic cinematic video. The man and woman walk slowly side by side along the river walkway. Golden sunset light shimmers and sparkles on the Han River water. Wind gently lifts the woman's hair. Autumn leaves drift down from the trees. They walk close but don't hold hands. Camera follows from behind in a slow, low tracking shot, then slowly rises. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 8 seconds.
```

### 클립 18 (이미지 18 사용): 카페 엔딩
```
Animate this photo into a realistic cinematic video. Steam slowly rises and curls from the coffee cup in the foreground. Outside the window, the alley street lights glow warmer as dusk deepens. A silhouette of a person walks past outside. The man's reflection in the glass shows a faint, peaceful smile. Camera slowly pushes toward the window. Photorealistic, cinematic, shot on cinema camera, natural lighting, warm color grading, Korean drama cinematography, shallow depth of field, 1080p. 7 seconds.
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
- 슬로우모션: 브루에서 클립 선택 → 속도 조절 → 0.5배속 = 원래의 2배 길이
- 루프: 같은 클립을 복사해서 이어 붙이기
- 역재생 루프: 클립 복사 → 역재생 → 원본 뒤에 붙이기 (끊김 없는 반복)
- 디졸브 전환: 클립 사이에 1~3초 디졸브 (시간도 채우고 자연스러움)
- 핵심 장면(치유, 한강)은 슬로우 강하게 (2.5배)
- 대화 장면(카페, 꽃집)은 루프로 시간 채우기
```

---

## 최종 요약

| 항목 | 수량 |
|------|------|
| 나노바나나프로 이미지 | **18장 (극사실)** |
| 구글 플로우 영상 클립 | **18개 (극사실)** |
| 브루 슬로우모션+루프 후 | **30분 풀 영상** |
| 정지 이미지 구간 | **0개** (전부 움직이는 영상) |
| 스타일 | **포토리얼리스틱 (실사 한국 드라마 느낌)** |
