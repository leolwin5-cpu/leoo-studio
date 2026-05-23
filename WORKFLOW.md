# 🎬 Myanmar Ancient Kingdom Battle Series
## AI Video Production Workflow

> **Style:** Cinema Realistic | **Video Tool:** Veo | **Image Tool:** Flo / Gemini
> **Series Format:** Episode-by-episode (Ep1 max ~2 min) | **Dialogue:** မြန်မာ | **Subtitles:** English

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

## STEP 0 — STORY OUTLINE & SETTINGS CONFIRMATION

Before any phase begins, confirm the following:

```
SERIES TITLE      : [ဇာတ်လမ်းအမည်]
EPISODE           : Episode [N] — [ခေါင်းစဥ်]
SETTING ERA       : မြန်မာ့ရှေးဟောင်းဘုရင်ခေတ်
BATTLE TYPE       : စီးချင်းထိုးတိုက်ပွဲ (Cavalry Battle)
EPISODE RUNTIME   : Max ~2 minutes (Episode 1)
DIALOGUE LANGUAGE : မြန်မာ (minimal — action-focused)
SUBTITLE LANGUAGE : English
IMAGE TOOL        : Flo / Gemini
VIDEO TOOL        : Veo
STYLE             : Cinema Realistic — photorealistic, no animation
```

Once confirmed → **proceed to Phase 1**

---

## PHASE 1 — CHARACTER DESIGN

> 🎯 Goal: Lock character visuals before anything else.
> ✅ Approve character image prompts → generate → confirm → move to Phase 2
> ❌ Do NOT proceed to environments until characters are approved.

### 1A. Character Definition

For each **main / recurring character**, fill in:

```
CHARACTER ID      : CHAR_[Name]          ← used in all future prompts
NAME              : [ဇာတ်ကောင်အမည်]
ROLE              : Hero / Antagonist / Ally / Elder / Ruler
AGE               : [အသက်]
BUILD             : [ကိုယ်ခန္ဓာပုံစံ — e.g. ကြံ့ခိုင်သော၊ ပိန်လျသော]
FACE              : [မျက်နှာပုံစံ — မျက်လုံးရောင်၊ မုတ်ဆိတ် ရှိ/မရှိ]
OUTFIT            : [အဝတ်အစားအသေးစိတ် — မြန်မာ့ဘုရင်ခေတ်ဝတ်စုံ]
WEAPON / PROP     : [လက်နက် သို့မဟုတ် ကိုင်ဆောင်ပစ္စည်း]
REFERENCE IMAGE   : [link or "none — describe only"]
PERSONALITY       : [စိတ်သဘောထား ၂-၃ လုံး]
```

> ⚠️ **CHARACTER LOCK RULE:**
> Once approved, the following must NEVER change across all episodes:
> - မျက်နှာပုံစံ / အရောင်
> - အဝတ်အစား (အသေးစိတ်အပါအဝင်)
> - လက်နက် / ကိုင်ဆောင်ပစ္စည်း
> - ကိုယ်ခန္ဓာအချိုး

> 🎲 **Minor / background characters** (တစ်ကြိမ်သာပါသောဇာတ်ကောင်) — random generation လုပ်နိုင်သည်၊ consistency မလိုအပ်။

---

### 1B. Character Image Prompt Format

တစ်ကောင်စီအတွက် prompt ထုတ်ပေးမည်—

```
[CHAR_Name] — CHARACTER REFERENCE PROMPT

"Cinematic photorealistic portrait, ancient Myanmar kingdom era warrior,
[age]-year-old [build] [gender] man/woman,
[face description — skin tone, eye shape, eye color, facial hair if any],
wearing [detailed Myanmar period-accurate outfit],
holding [weapon/prop],
[expression — calm / fierce / determined / sorrowful],
golden hour / torchlight / overcast battle-day lighting,
shallow depth of field, film grain, anamorphic lens,
ultra high detail, 8K resolution, no animation, no cartoon,
strictly realistic human proportions,
full body reference sheet, neutral pose, white/dark background"
```

> 🔁 After generating: **ကြိုက်ရင် ✅ Lock | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ**

---

## PHASE 2 — ENVIRONMENT / LOCATION DESIGN

> 🎯 Goal: Lock all locations used in this episode.
> ✅ Approve environment image prompts → generate → confirm → move to Phase 3
> ❌ Do NOT combine with characters yet.

### 2A. Environment Definition

```
ENV ID            : ENV_[LocationName]   ← used in all future prompts
LOCATION NAME     : [နေရာအမည်]
APPEARS IN SCENES : [e.g. Scene 1, 3, 7]
TIME OF DAY       : [e.g. မိုးခြိမ်းမိုးသောနေ့ / နေဝင်ချိန် / ညဦး]
WEATHER / MOOD    : [e.g. မြူဆိုင်း / ဖုန်ထ / မိုးရွာ]
KEY ELEMENTS      : [နေရာ၏ အဓိကဒြပ်စင်များ]
```

### 2B. Environment Image Prompt Format

```
[ENV_LocationName] — BACKGROUND PROMPT

"Cinematic photorealistic wide establishing shot,
ancient Myanmar kingdom era [location type],
[time of day and weather],
[key environmental details — architecture, terrain, props],
[cultural Myanmar elements — pagodas, teak wood structures, war elephants in distance, etc.],
dramatic cinematic lighting, atmospheric haze, film grain,
anamorphic widescreen, no characters in frame,
pure background plate, 8K, ultra detail"
```

> 🔁 After generating: **ကြိုက်ရင် ✅ Lock | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ**

---

## PHASE 3 — SCENE COMPOSITION (Character + Environment)

> 🎯 Goal: Place locked characters into locked environments.
> One prompt per scene. Approve visuals before writing full script.

### 3A. Scene Composition Prompt Format

```
[SCENE_N] — COMPOSITION PROMPT

CHARACTER(S)      : [CHAR_Name1, CHAR_Name2]
ENVIRONMENT       : [ENV_LocationName]
SHOT TYPE         : [Wide / Medium / Close-up / Drone / Rotate / POV]
CAMERA MOVE       : [Static / Slow push-in / Drone descend / 360 rotate / Tracking]
ACTION            : [ဘာလုပ်နေသလဲ]
EXPRESSION        : [မျက်နှာအမူအရာ]
LIGHTING          : [e.g. harsh battle sun / torchlight / golden dusk]

IMAGE PROMPT:
"Cinematic photorealistic scene, ancient Myanmar kingdom,
[SHOT TYPE] shot, [CAMERA MOVE],
[CHAR_Name1 — outfit from Phase 1, action, expression],
[CHAR_Name2 if present — same detail],
[ENV_LocationName environment details],
[lighting and mood],
film grain, anamorphic lens flare, 8K, ultra detail,
no animation, no cartoon, strictly realistic"
```

> 🔁 After generating: **ကြိုက်ရင် ✅ | မကြိုက်ရင် ❌ ပြင်ဆင်ချက်ပြောပါ**
> ✅ Scene composition အားလုံး approve ဖြစ်မှ Phase 4 သို့သွားမည်။

---

## PHASE 4 — SCRIPT (Dialogue + Camera Directions)

> 🎯 Goal: Scene composition approve ပြီးမှသာ script ရေးမည်။
> Dialogue minimal — action/visual storytelling ကို ဦးစားပေးမည်။

### Script Format

```
=== EPISODE [N] | [ခေါင်းစဥ်] ===
TOTAL SCENES : [N]
EST. RUNTIME : ~[X] min [Y] sec

--- SCENE [N] ---
LOCATION    : [ENV_LocationName]
CHARACTERS  : [CHAR_Name1, CHAR_Name2]
SHOT        : [Wide / Medium / Close-up / Drone / Rotate]
CAMERA MOVE : [Static / Push-in / Orbit / Tracking / Drone descend]
ACTION      : [ဘာဖြစ်နေသလဲ — မြင်ကွင်းဖော်ပြချက်]
DURATION    : ~[X] sec

DIALOGUE:
[CHAR_Name]: "[မြန်မာဘာသာ စကားပြောစာကြောင်း]"
(Action/emotion note)

[SONG / SOUND CUE]: [e.g. တပ်မတော်တံပိုးသံ / ငြိမ်သက်မှု / လှေကြိုးသံ]
---
```

> ⚠️ **Script Rules:**
> - Scene တစ်ခု max **6 seconds**
> - Dialogue minimal — မလိုအပ်ပါက မထည့်ရ
> - Camera move တိုင်းကို Veo အတွက် တိကျစွာ ဖော်ပြရမည်
> - တိုက်ပွဲ scene တွေတွင် action ကို ဦးစားပေး၊ dialogue မသုံးနှင်း

---

## PHASE 5 — VIDEO PROMPTS (Veo)

> 🎯 Goal: Phase 3 scene images + Phase 4 script ကို အသုံးပြု၍ Veo video prompt ထုတ်မည်။

### Video Prompt Format

```
--- VIDEO SCENE [N] ---
SOURCE IMAGE  : Scene_[N]_image
DURATION      : ~[X] sec (max 6)
CAMERA MOTION : [e.g. slow drone descend / static hold / gentle push-in / 360 orbit]

VIDEO PROMPT:
"Cinematic photorealistic video clip, ancient Myanmar kingdom era,
[CAMERA MOTION] — [describe motion path clearly for Veo],
ENVIRONMENT: [ENV_LocationName — ambient motion: dust rising / flags waving / fire flickering],
[CHAR_Name1 — outfit, action in motion, expression],
[CHAR_Name2 if present — reaction, stillness or movement],
DIALOGUE: [CHAR_Name speaks in Myanmar language — mouth moves in sync] '[စကားပြောစာကြောင်း]'
— other characters remain still and listening,
SOUND: [ambient battle sounds / wind / horses / silence],
MUSIC CUE: [BGM from list below],
mood: [tense / triumphant / sorrowful / fierce],
film grain, anamorphic, no animation, ultra realistic, 8K"

[TRANSITION: 0.5s crossfade] ← between scenes
[TRANSITION: wipe] ← at act breaks
[TRANSITION: fade to black] ← episode ending
```

### BGM Mood Cues (Myanmar-inspired)
```
တိုက်ပွဲပြင်ဆင်မှု     → တပ်မတော်တံပိုး၊ နှောင်းရိုက်တောင်းသံ
စီးချင်းထိုးတိုက်ပွဲ    → တိုးမြောက်သော ကြိုးတပ်သံ၊ လျင်မြန်သောတပ်တောင်း
ဇာတ်ကောင်ပေါ်ပေါက်   → ထိမ်းမြားသောတစ်ကိုယ်ရည်တေး
သူရဲကောင်းကျဆုံး      → နှေးကွေးသောကြိုးတပ်သံ၊ ငြိမ်သက်မှု
နိဂုံးချုပ် / အနိုင်    → ဝမ်းမြောက်သောတံပိုးသံ၊ ပြည့်ဝသောသီချင်း
```

---

## PHASE 6 — METADATA + ENGLISH SUBTITLES

### 6A. SRT Subtitle File (English)
```srt
1
00:00:00,000 --> 00:00:04,000
[English translation of Scene 1 dialogue]

2
00:00:04,000 --> 00:00:08,000
[English translation of Scene 2 dialogue]
...
```

### 6B. YouTube Metadata
```
TITLE OPTIONS:
A: [Action hook — e.g. "The Last Cavalry Charge | Myanmar Kingdom Battle Ep.1"]
B: [Emotion hook — e.g. "He Rode Alone Into 1000 Enemies | Ancient Myanmar Story"]
C: [Mystery hook — e.g. "The General Who Never Retreated | Myanmar Battle Series"]

DESCRIPTION (English):
[2-line dramatic hook]
Episode [N] of the Myanmar Ancient Kingdom Battle Series.
[Timestamps]
[Series moral / theme in 1 sentence]
#MyanmarHistory #AncientBattle #CinematicVideo #MyanmarKingdom #BattleSeries

THUMBNAIL BRIEF:
Scene     : [Most dramatic scene number]
Character : [CHAR_Name]
Expression: [fierce / determined / sorrowful]
Text      : "[Short dramatic phrase]"
Color     : High contrast — deep red / gold / dark tones
```

---

## 🔄 EPISODE FLOW SUMMARY

```
STEP 0  →  ဇာတ်လမ်းကျောရိုး confirm
PHASE 1 →  ဇာတ်ကောင် image prompts → approve → lock
PHASE 2 →  နေရာ image prompts → approve → lock
PHASE 3 →  ဇာတ်ကောင် + နေရာ ပေါင်း → scene composition → approve
PHASE 4 →  Script (dialogue + camera) → lock
PHASE 5 →  Veo video prompts → generate
PHASE 6 →  SRT subtitles + YouTube metadata
```

> ⚡ **One episode at a time.**
> Episode 1 approve ဖြစ်မှ Episode 2 စမည်။
> Phase တစ်ခုချင်းစီ approve မဖြစ်ခင် နောက် phase မသွားရ။

---

*Workflow Version 1.0 — Myanmar Ancient Kingdom Battle Series*
