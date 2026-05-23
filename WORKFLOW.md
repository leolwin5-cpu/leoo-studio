# 🎬 Myanmar Ancient Kingdom Battle Series
## AI Video Production Workflow

> **Style:** Cinema Realistic | **Video Tool:** Veo (8sec per clip)
> **Image Tool:** Flo / Gemini | **Series Format:** Episode-by-episode (Ep1 max ~2 min)
> **Dialogue:** မြန်မာ (minimal) | **Subtitles:** English

---

## ✅ PRODUCTION CHECKLIST

```
[ ] STEP 0  — Story outline confirmed
[ ] PHASE 1 — Characters approved (image prompts)
[ ] PHASE 2 — Environments approved (image prompts)
[ ] PHASE 3 — Scene compositions approved (character + environment combined)
[ ] PHASE 4 — Script locked (dialogue + camera directions)
[ ] PHASE 5 — Video prompts generated (Veo)
[ ] PHASE 6 — Metadata + English subtitles (.SRT)
```

---

## ⚡ VEO 8-SEC CLIP RULES

> ဒီ rule တွေကို Phase 4 Script နဲ့ Phase 5 Video Prompts တွင် အမြဲသတိထားရမည်။

```
CLIP DURATION     : 8 seconds per Veo generation (fixed)
SCENE GROUPING    : ဆက်စပ်နေသော action တွေကို တစ်ခု 8sec အဖြစ် ပေါင်းရမည်
CONTINUITY RULE   : ရိုက်ကူးချိတ်ဆက်မှု ပြတ်တောင်းပြတ်တောင်း မဖြစ်ရ
                    → scene တစ်ခုနဲ့တစ်ခု motion flow ဆက်နေရမည်
                    → cut မလုပ်ခင် action တစ်ခု ပြီးစီးအောင်ပြရမည်
BATTLE SCENES     : battle clip တစ်ခုထဲတွင် action sequence တစ်ခုလုံး ပါရမည်
                    (ဥပမာ — မြင်းပြေး + လှံထိုး + ရန်သူကျ = clip တစ်ခုတည်း)
SHORT SCENES      : 3-4 sec သာလိုသော scene → နောက် scene နဲ့ ပေါင်းပြီး 8sec ဖြည့်
```

---

## STEP 0 — STORY OUTLINE & SETTINGS CONFIRMATION



```
SERIES TITLE      : [ဇာတ်လမ်းအမည်]
EPISODE           : Episode [N] — [ခေါင်းစဥ်]
SETTING ERA       : မြန်မာ့ရှေးဟောင်းဘုရင်ခေတ်
BATTLE TYPE       : စီးချင်းထိုးတိုက်ပွဲ (Cavalry Battle)
EPISODE RUNTIME   : Max ~2 minutes (Episode 1)
DIALOGUE LANGUAGE : မြန်မာ (minimal — action-focused)
SUBTITLE LANGUAGE : English
IMAGE TOOL        : Flo / Gemini
VIDEO TOOL        : Veo (8sec per clip)
STYLE             : Cinema Realistic — photorealistic, no animation
```

Once confirmed → **proceed to Phase 1**

---

## PHASE 1 — CHARACTER DESIGN

> 🎯 Goal: Lock character visuals before anything else.
> ✅ Approve → generate → confirm → move to Phase 2
> ❌ Do NOT proceed until characters are approved.

### 1A. Character Definition

```
CHARACTER ID      : CHAR_[Name]
NAME              : [ဇာတ်ကောင်အမည်]
ROLE              : Hero / Antagonist / Ally / Elder / Ruler
AGE               : [အသက်]
BUILD             : [ကိုယ်ခန္ဓာပုံစံ]
FACE              : [မျက်နှာပုံစံ — မျက်လုံးရောင်၊ မုတ်ဆိတ် ရှိ/မရှိ]
OUTFIT            : [အဝတ်အစားအသေးစိတ် — မြန်မာ့ဘုရင်ခေတ်ဝတ်စုံ]
WEAPON / PROP     : [လက်နက်]
REFERENCE IMAGE   : [link or "none — describe only"]
PERSONALITY       : [စိတ်သဘောထား ၂-၃ လုံး]
```

> ⚠️ **CHARACTER LOCK RULE — မပြောင်းရသောအရာများ (ဇာတ်တွဲတိုင်းတွင်):**
> မျက်နှာပုံစံ / အဝတ်အစားအသေးစိတ် / လက်နက် / ကိုယ်ခန္ဓာအချိုး
>
> 🎲 **Minor characters** (တစ်ကြိမ်သာပါ) → random generation OK၊ consistency မလို

### 1B. Character Image Prompt

```
[CHAR_Name] — CHARACTER REFERENCE PROMPT

"Cinematic photorealistic full body reference sheet,
ancient Myanmar kingdom era warrior,
[age]-year-old [build] [gender],
[face: skin tone, eye shape, facial hair],
wearing [detailed Myanmar period-accurate outfit],
holding [weapon/prop],
[expression: calm / fierce / determined],
neutral standing pose, studio lighting,
film grain, 8K, no animation, strictly realistic human proportions,
white or dark background"
```

> 🔁 ကြိုက်ရင် ✅ Lock | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ



---

## PHASE 2 — ENVIRONMENT / LOCATION DESIGN

> 🎯 Goal: Lock all locations used in this episode.
> ❌ Do NOT combine with characters yet.

### 2A. Environment Definition

```
ENV ID            : ENV_[LocationName]
LOCATION NAME     : [နေရာအမည်]
APPEARS IN CLIPS  : [e.g. Clip 1, 3, 5]
TIME OF DAY       : [မိုးခြိမ်းနေ့ / နေဝင်ချိန် / ညဦး]
WEATHER / MOOD    : [မြူဆိုင်း / ဖုန်ထ / မိုးရွာ]
KEY ELEMENTS      : [နေရာ၏ အဓိကဒြပ်စင်များ]
```

### 2B. Environment Image Prompt

```
[ENV_LocationName] — BACKGROUND PROMPT

"Cinematic photorealistic wide establishing shot,
ancient Myanmar kingdom era [location type],
[time of day and weather],
[key details — architecture, terrain, props],
[Myanmar cultural elements — pagodas, teak structures, war elephants in distance],
dramatic cinematic lighting, atmospheric haze, film grain,
anamorphic widescreen, no characters in frame,
pure background plate, 8K, ultra detail"
```

> 🔁 ကြိုက်ရင် ✅ Lock | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ

---

## PHASE 3 — SCENE COMPOSITION (Character + Environment)

> 🎯 Goal: Locked characters → locked environments ထဲ ထည့်မည်။
> ✅ Approve visuals ဖြစ်မှ Phase 4 သို့သွားမည်။

### Scene Composition Prompt

```
[SCENE_N] — COMPOSITION PROMPT

CHARACTER(S)      : [CHAR_Name1, CHAR_Name2]
ENVIRONMENT       : [ENV_LocationName]
SHOT TYPE         : [Wide / Medium / Close-up / Drone / Rotate / POV]
CAMERA MOVE       : [Static / Slow push-in / Drone descend / 360 rotate / Tracking]
ACTION            : [ဘာလုပ်နေသလဲ]
EXPRESSION        : [မျက်နှာအမူအရာ]
LIGHTING          : [harsh battle sun / torchlight / golden dusk]

IMAGE PROMPT:
"Cinematic photorealistic scene, ancient Myanmar kingdom,
[SHOT TYPE] shot,
[CHAR_Name1 — exact outfit from Phase 1, action, expression],
[CHAR_Name2 if present — same],
[ENV environment details],
[lighting and mood],
film grain, anamorphic lens, 8K, no animation, strictly realistic"
```

> 🔁 ကြိုက်ရင် ✅ | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ



---

## PHASE 4 — SCRIPT (Dialogue + Camera Directions)

> 🎯 Scene compositions approve ပြီးမှသာ script ရေးမည်။
> Dialogue minimal — visual/action storytelling ဦးစားပေး။

### ⚡ Script Rules (Veo 8sec)

```
CLIP DURATION     : တစ်ခု = 8sec (Veo fixed output)
SCENE GROUPING    : ဆက်နေသော action တွေ → clip တစ်ခုတည်းဖြစ်အောင် ပေါင်း
SHORT MOMENTS     : 3-4sec သာလိုသော dialogue/reaction → ဆက်နေသော scene နဲ့ clip တစ်ခုဖြစ်အောင် ပေါင်း
BATTLE CONTINUITY : မြင်းပြေး → လှံထိုး → ကျဆုံး = clip တစ်ခုတည်း (ပြတ်တောင်းပြတ်တောင်းမဖြစ်ရ)
FLOW CHECK        : clip တိုင်းသည် ရှေ့ clip ၏ last frame နဲ့ ဆက်နေသလို ဖြစ်ရမည်
```

### Script Format

```
=== EPISODE [N] | [ခေါင်းစဥ်] ===
TOTAL CLIPS  : [N]
EST. RUNTIME : ~[X] min [Y] sec

--- CLIP [N] ---
SCENES COMBINED : [e.g. Scene 3 + 4 merged / or Scene 5 standalone]
LOCATION        : [ENV_LocationName]
CHARACTERS      : [CHAR_Name1, CHAR_Name2]
SHOT            : [Wide / Medium / Close-up / Drone / Rotate]
CAMERA MOVE     : [Static / Push-in / Orbit / Tracking / Drone descend]
ACTION SEQUENCE : [ဘာဖြစ်နေသလဲ — ဆက်တိုက် action ဖော်ပြ]
DURATION        : 8sec

DIALOGUE (if any):
[CHAR_Name]: "[မြန်မာဘာသာ]"

FLOW NOTE       : [ရှေ့ clip နဲ့ ဘယ်လို ဆက်သလဲ / နောက် clip ဘာဖြင့် သွားမည်]
SOUND CUE       : [တပ်တောင်းသံ / ငြိမ်သက် / မြင်းသံ / တံပိုး]
---
```

---

## PHASE 5 — VIDEO PROMPTS (Veo 8sec)

> 🎯 Phase 3 images + Phase 4 script → Veo prompts

### ⚡ Continuity Prompt Rules

```
- clip တိုင်း၏ ပထမ frame သည် ရှေ့ clip ၏ နောက်ဆုံး frame နဲ့ ဆက်နေရမည်
- battle clips တွင် action တစ်ခုလုံး clip တစ်ခုထဲ ပြီးစီးရမည်
- camera motion သည် smooth ဖြစ်ရမည် — abrupt cut မသုံးရ
- CONTINUE FROM နဲ့ LEADS INTO field သည် continuity စစ်ဆေးရန် မဖြစ်မနေ ဖြည့်ရမည်
```

### Video Prompt Format

```
--- VIDEO CLIP [N] ---
SOURCE IMAGE    : Scene_[N]_image
DURATION        : 8sec (Veo fixed)
CAMERA MOTION   : [slow drone descend / static hold / gentle push-in / 360 orbit / tracking shot]
CONTINUE FROM   : [ရှေ့ clip ၏ ending action — e.g. "horse at full gallop approaching"]
LEADS INTO      : [နောက် clip ၏ starting action — e.g. "spear already raised for strike"]

VIDEO PROMPT:
"Cinematic photorealistic 8-second video clip, ancient Myanmar kingdom era,
[CAMERA MOTION] — [describe motion path clearly],
ENVIRONMENT: [ENV_LocationName — ambient: dust rising / flags waving / fire flickering],
ACTION SEQUENCE: [full action from start to end within 8sec — no cuts],
[CHAR_Name1 — exact outfit, motion, expression],
[CHAR_Name2 if present — reaction or counter-action],
DIALOGUE (if any): [CHAR_Name — mouth sync] '[မြန်မာဘာသာ]',
SOUND: [ambient: horses / battle cries / wind / silence],
MUSIC: [BGM cue],
mood: [tense / triumphant / sorrowful / fierce],
seamless continuation from previous clip,
film grain, anamorphic, no animation, ultra realistic, 8K"

[TRANSITION: 0.3s crossfade] ← normal scenes
[TRANSITION: hard cut]        ← impact / battle hit moments
[TRANSITION: fade to black]   ← episode ending
```

### BGM Mood Cues

```
တိုက်ပွဲပြင်ဆင်   → တပ်မတော်တံပိုး၊ နှောင်းရိုက်တောင်းသံ — တိုးလာ
စီးချင်းထိုး      → တိုးမြောက်ကြိုးတပ်သံ၊ လျင်မြန်တပ်တောင်း — peak intensity
ဇာတ်ကောင်ပေါ်   → ထိမ်းမြားတစ်ကိုယ်ရည်တေး — သီးသန့်ကြည့်ရသော
ကျဆုံး/ဝမ်းနည်း  → နှေးသောကြိုးတပ်သံ — ရပ်တန့်
နိဂုံး/အနိုင်      → ဝမ်းမြောက်တံပိုးသံ၊ ပြည့်ဝသောဂီတ
```



---

## PHASE 6 — METADATA + ENGLISH SUBTITLES

### 6A. SRT Subtitle File (English)

```srt
1
00:00:00,000 --> 00:00:08,000
[English translation — Clip 1]

2
00:00:08,000 --> 00:00:16,000
[English translation — Clip 2]
```

### 6B. YouTube Metadata

```
TITLE OPTIONS:
A: [Action hook   — e.g. "The Last Cavalry Charge | Myanmar Kingdom Battle Ep.1"]
B: [Emotion hook  — e.g. "He Rode Alone Into 1000 Enemies | Ancient Myanmar Story"]
C: [Mystery hook  — e.g. "The General Who Never Retreated | Myanmar Battle Series"]

DESCRIPTION (English):
[2-line dramatic hook]
Episode [N] of the Myanmar Ancient Kingdom Battle Series.
[Timestamps — 8sec per clip]
#MyanmarHistory #AncientBattle #CinematicVideo #MyanmarKingdom #BattleSeries

THUMBNAIL BRIEF:
Scene      : [Most dramatic clip number]
Character  : [CHAR_Name]
Expression : [fierce / determined / sorrowful]
Text       : "[Short dramatic phrase]"
Color      : High contrast — deep red / gold / dark tones
```

---

## 📋 EPISODE 1 SCRIPT — သမိန်ဗရမ်း မြင်းပွဲတော်

> **Veo 8sec clips | Est. Runtime ~2 min | 15 clips total**
> ⚡ Clips ပေါင်းထားသောနေရာများကို [MERGED] ဖြင့် မှတ်သားထားသည်

---

```
--- CLIP 01 — TITLE CARD + ESTABLISHING [MERGED] ---
SCENES COMBINED : Title card + Palace wide shot
LOCATION        : ENV_PalaceCourtyardDay
CHARACTERS      : None
SHOT            : Static title → Drone wide descend
CAMERA MOVE     : Black screen ၄sec → Drone slowly descends over palace ၄sec
ACTION SEQUENCE : Black screen တွင် title text ပေါ်လာ → fade → drone မြင်ကွင်းဝင်လာ
DURATION        : 8sec

DIALOGUE        : none

CAPTION TEXT    :
  မြန်မာ  — "သမိန်ဗရမ်း"
  English — "Thamine Baran — Hanthawaddy, 14th Century"

FLOW NOTE       : Black → palace overhead view → CLIP 02 ၏ ခန်းမတံခါးဆီ ဆင်းဆက်သွား
SOUND CUE       : ငြိမ်သက်မှု → နှောင်းသံဝင်လာ
---
```

---

```
--- CLIP 02 — CHINESE ENVOY ENTERS ---
SCENES COMBINED : Envoy + Ga Ma Ni entrance (standalone)
LOCATION        : ENV_PalaceCourtyard
CHARACTERS      : တရုတ်သံတမန်၊ CHAR_GaMaNi
SHOT            : Wide → slow push-in
CAMERA MOVE     : Camera ဆင်ခြေဖုံးအဆင့်မှ တဖြည်းဖြည်း push-in
ACTION SEQUENCE : တရုတ်သံတမန် ဦးဆောင်ဝင်လာ → ဂါမဏီ နောက်မှလိုက် →
                  လူများ နှစ်ဖက်ဖဲ့ → ကင်းကာ ဘုရင်ထံသို့ ဦးတည်
DURATION        : 8sec

DIALOGUE        : none

FLOW NOTE       : CLIP 01 ၏ drone view မှ ဆင်းဆက် → ဂါမဏီ ကိုယ်ခန္ဓာ close-up ဖြင့် ဆုံး
SOUND CUE       : ကျောက်ခင်းပေါ် ခြေသံ — ငြိမ်သက်သောနန်းတော်
---
```

---

```
--- CLIP 03 — THE CHALLENGE ---
SCENES COMBINED : Envoy speech + King's court silence [MERGED]
LOCATION        : ENV_ThroneHall
CHARACTERS      : တရုတ်သံတမန်၊ မြန်မာဘုရင်၊ ဗိုလ်မှူးများ
SHOT            : Medium → pan across generals
CAMERA MOVE     : Envoy medium shot → slow pan မြန်မာဗိုလ်မှူးများ မျက်နှာ
ACTION SEQUENCE : သံတမန် ဘုရင်ထံ တင်ပြ → ဗိုလ်မှူးများ မျက်နှာချင်းဆိုင်ကြည့် →
                  ဘယ်သူမှ မထ → ငြိမ်သက်
DURATION        : 8sec

DIALOGUE:
တရုတ်သံတမန်: "ကျွန်တော်တို့ စစ်သည်နဲ့ ရင်ဆိုင်ပါ —
               နိုင်ရင် ပြန်သွားမည်၊ ရှုံးရင် ဤနိုင်ငံ ကျွန်တော်တို့၏..."
SUBTITLE: "Face our champion. Win — we leave. Lose — this kingdom falls."

FLOW NOTE       : ဗိုလ်မှူးများ ငြိမ်ကျသောမျက်နှာဖြင့် ဆုံး → CLIP 04 ထောင်သို့ ဆက်
SOUND CUE       : ငြိမ်သက်မှု — လေကြောင်သံ
---
```

---

```
--- CLIP 04 — PRISON + THAMINE BARAN REACTS [MERGED] ---
SCENES COMBINED : Prison close-up + decision moment
LOCATION        : ENV_PrisonCell
CHARACTERS      : CHAR_ThamineBaran
SHOT            : Extreme close-up မျက်လုံး → pull back medium
CAMERA MOVE     : မျက်လုံး extreme close-up မှ တဖြည်းဖြည်း pull back
ACTION SEQUENCE : ချည်နှောင်ထားသော လက်မောင်းများ → မျက်လုံး → ကြားသံ →
                  သမိန်ဗရမ်း ဖြည်းဖြည်း ထ → ရှေ့ကိုကြည့်
DURATION        : 8sec

DIALOGUE        : none (ဇာတ်ကောင် action သာ)

FLOW NOTE       : မျက်လုံးမှ ဖြည်းဖြည်းပြောင်း → CLIP 05 ထောင်တံခါးဆီ ဆက်
SOUND CUE       : ချင်းကန်ကြိုးသံ → ငြိမ်
---
```

---

```
--- CLIP 05 — "I WILL FIGHT" ---
SCENES COMBINED : Thamine Baran steps forward (standalone)
LOCATION        : ENV_PrisonGate → ENV_PalaceCorridor
CHARACTERS      : CHAR_ThamineBaran၊ ထောင်ထိန်းများ
SHOT            : Medium tracking shot
CAMERA MOVE     : သမိန်ဗရမ်း ရှေ့မှ tracking — camera နောက်ဆုတ်
ACTION SEQUENCE : ထောင်ထိန်းများ တံခါးဖွင့် → သမိန်ဗရမ်း တည်တည်ငြိမ်ငြိမ်ထ →
                  လမ်းလျှောက် → မှတ်တမ်းမတ်ရပ်ကာ —
DURATION        : 8sec

DIALOGUE:
CHAR_ThamineBaran: "ကျွန်တော် တိုက်ပါမည်"
SUBTITLE: "I will fight."

FLOW NOTE       : ထောင်မှ နန်းတော်ဝင်း ဆက်လမ်းလျှောက် → CLIP 06 ဘုရင်ထံ ဆက်ရောက်
SOUND CUE       : တပ်မတော်တံပိုး — တိုးမြောက်သောသံ စတင်
---
```

---

```
--- CLIP 06 — KING NODS + PREPARATION MONTAGE [MERGED] ---
SCENES COMBINED : King approves + weapon + horse mount
LOCATION        : ENV_ThroneHall → ENV_StableYard
CHARACTERS      : မြန်မာဘုရင်၊ CHAR_ThamineBaran
SHOT            : Close-up cut series — 3 quick shots within 8sec
CAMERA MOVE     : Shot 1 (3sec): ဘုရင် close-up — ခေါင်းညိတ်
                  Shot 2 (2sec): လှံကိုင်သောလက် close-up
                  Shot 3 (3sec): မြင်းပေါ်တက် — medium
ACTION SEQUENCE : ဘုရင် ခေါင်းညိတ် → လှံကိုင် → မြင်းပေါ်တက်ပြီး ရှေ့ကိုကြည့်
DURATION        : 8sec

DIALOGUE        : none

FLOW NOTE       : မြင်းပေါ်မှ မျက်နှာဖြင့် ဆုံး → CLIP 07 ပွဲကွင်း entrance ဆက်
SOUND CUE       : BGM တိုးမြင့် — တပ်တောင်းသံ ပေါင်းဝင်
---
```

---

```
--- CLIP 07 — BOTH CHAMPIONS ENTER THE ARENA ---
SCENES COMBINED : Arena wide + two champions face each other
LOCATION        : ENV_BattleArena
CHARACTERS      : CHAR_ThamineBaran၊ CHAR_GaMaNi
SHOT            : Drone wide → ground level slow push-in
CAMERA MOVE     : Drone overhead → ဆင်းလာပြီး ground level ရောက်ကာ နှစ်ဦးကြား push-in
ACTION SEQUENCE : ပြည်သူများ နှစ်ဖက်တန်း → နှစ်ဦး မြင်းပေါ်မှ ဝင်လာ →
                  ကွင်းလယ်တွင် ရပ်ကာ ရင်ဆိုင်
DURATION        : 8sec

DIALOGUE        : none

FLOW NOTE       : နှစ်ဦး မျက်နှာချင်းဆိုင် ရပ်နေချိန်ဖြင့် ဆုံး → CLIP 08 face-off ဆက်
SOUND CUE       : BGM ရပ် — ဝိုင်းသောသူများ အသံ — ပြီးနောက် ငြိမ်
---
```

---

```
--- CLIP 08 — FACE-OFF CLOSE-UPS [MERGED] ---
SCENES COMBINED : Thamine Baran close-up + Ga Ma Ni close-up
LOCATION        : ENV_BattleArena
CHARACTERS      : CHAR_ThamineBaran၊ CHAR_GaMaNi
SHOT            : Alternating close-ups — 360 slow rotate between
CAMERA MOVE     : Shot 1 (4sec): သမိန်ဗရမ်း မျက်နှာ close-up — တည်ငြိမ်
                  Shot 2 (4sec): ဂါမဏီ မျက်နှာ close-up — ကြမ်းတမ်း
ACTION SEQUENCE : သမိန်ဗရမ်း မျက်လုံးမပြောင်း → ဂါမဏီ ပြုံးကာ လှံကိုင် မြင့်တင်
DURATION        : 8sec

DIALOGUE        : none

FLOW NOTE       : ဂါမဏီ လှံမြင့်တင်ချိန်ဖြင့် ဆုံး → CLIP 09 charge ဆက်ချက်ခြင်း
SOUND CUE       : တိးတဆိတ် — ပြီးနောက် တပ်တောင်းတစ်ချက်ထိုး
---
```

---

```
--- CLIP 09 — THE CHARGE (BATTLE BEGINS) ---
SCENES COMBINED : Full cavalry charge — standalone 8sec
LOCATION        : ENV_BattleArena
CHARACTERS      : CHAR_ThamineBaran၊ CHAR_GaMaNi
SHOT            : Wide tracking — lateral chase camera
CAMERA MOVE     : Camera နှစ်ဦးနဲ့ အတူ lateral tracking — မြင်းပြေးနှုန်းတည့်
ACTION SEQUENCE : နှစ်ဦး မြင်းကို ဝိုင်းလိုက် → ပြေးလွင့် → ကြားနေရာ ကျဉ်းလာ →
                  လှံနှစ်ချောင်း ထိတွေ့မည့်အချိန် clip ဆုံး
DURATION        : 8sec

DIALOGUE        : none

FLOW NOTE       : လှံချင်းထိတွေ့မည့်ဘဲ့ frame ဖြင့် ဆုံး → CLIP 10 impact ဆက်ချက်ခြင်း
SOUND CUE       : မြင်းဆင်းသံ၊ ဖုန်ထ၊ BGM peak — လျင်မြန်တပ်တောင်း
---
```

---

```
--- CLIP 10 — CLIFFHANGER ENDING ---
SCENES COMBINED : Impact flash + freeze + episode end title
LOCATION        : ENV_BattleArena
CHARACTERS      : CHAR_ThamineBaran၊ CHAR_GaMaNi
SHOT            : Extreme close-up impact → freeze frame → fade black
CAMERA MOVE     : Impact ၂sec → freeze ၂sec → fade to black ၄sec
ACTION SEQUENCE : လှံချင်းဝင်မိ → dust explosion → freeze frame →
                  ဘယ်သူနိုင်မည် မသိ → ကနဦးဇာတ်ကြောင်းပြ
DURATION        : 8sec

CAPTION TEXT:
  မြန်မာ  — "Episode 2 တွင် ဆက်လက်ကြည့်ရှုပါ..."
  English — "To be continued in Episode 2..."

FLOW NOTE       : Episode 1 ပြီး
SOUND CUE       : BGM ရပ် → တပ်တောင်းတစ်ချက် → ငြိမ်သက်

[TRANSITION: fade to black — episode end]
---
```

---

```
TOTAL CLIPS   : 10
EST. RUNTIME  : ~80 sec (~1 min 20 sec)
DIALOGUE LINES: 2 lines only
BATTLE CLIPS  : Clip 09, 10 — full action continuity maintained
```

---

## 🔄 EPISODE FLOW SUMMARY

```
STEP 0  →  ဇာတ်လမ်းကျောရိုး confirm
PHASE 1 →  Character image prompts → approve → lock
PHASE 2 →  Environment image prompts → approve → lock
PHASE 3 →  Character + Environment scene compositions → approve
PHASE 4 →  Script (8sec clips, dialogue + camera) → lock
PHASE 5 →  Veo video prompts (continuity-checked) → generate
PHASE 6 →  SRT subtitles + YouTube metadata
```

> ⚡ **One episode at a time.**
> Phase တစ်ခုချင်းစီ approve မဖြစ်ခင် နောက် phase မသွားရ။
> Clip တိုင်း CONTINUE FROM / LEADS INTO စစ်ဆေးပြီးမှ Veo သို့ပို့ရမည်။

---

*Workflow Version 2.0 — Myanmar Ancient Kingdom Battle Series*
*Updated: Veo 8sec clip system + battle continuity rules*
