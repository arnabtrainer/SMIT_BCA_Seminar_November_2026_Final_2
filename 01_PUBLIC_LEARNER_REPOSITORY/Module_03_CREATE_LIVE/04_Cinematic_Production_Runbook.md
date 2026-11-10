# 🎬 Create a Cinematic Product Video: Real Movement, Realistic Audio

**Module 03 — AI Can Help Me Create** · *AI in Action: Learn • Create • Build*  
**Example product:** Milton Atlantis Thermosteel Water Bottle (Black, 750 ml)  
**Demonstration:** An original independent educational advertising concept, not an official Milton advertisement.

> **Goal:** Start with an authentic product brief and end with a short video featuring genuine AI-generated moving footage, spoken narration, background music and a precise closing title. A still-image slideshow with zoom effects is **not** a substitute for generated motion.

## 🔗 Reference and production tools

- Official product information: https://www.milton.in/products/atlantis-thermosteel-water-bottle
- ChatGPT: https://chatgpt.com/ — concept, storyboard and image prompts
- Google Vids: https://workspace.google.com/products/vids/ — animate reference images with an eligible video model and edit the timeline
- MiniMax: https://www.minimax.io/ — natural narration and instrumental music where supported

Product images, marks and claims require the appropriate permission and independent verification. Do not alter the manufacturer's product design or invent performance guarantees.

## 📋 1. Define the creative brief

| Decision | Selected direction |
|---|---|
| Product | Real insulated stainless-steel everyday-use bottle |
| Audience | Students, commuters, working adults and everyday travellers |
| Purpose | Build familiarity with the product and demonstrate AI filmmaking |
| Film treatment | Warm, premium, realistic lifestyle commercial |
| Output | Widescreen 16:9, approximately 20 seconds |
| Motion | Real human actions, active environments and purposeful camera movement |
| Audio | One consistent spoken narrator and a separate original/licensed instrumental track |
| Accuracy | No fictional temperature ratings, endorsements, prices or specifications |

## ✍️ 2. Create the concept and narration

Paste this into ChatGPT:

```text
Act as an experienced creative director for short-form commercial films.
Using the verified manufacturer information below, devise ONE original premium
20-second advertisement for a black 750 ml Milton Atlantis Thermosteel bottle.

Product facts: [PASTE VERIFIED FACTS FROM THE OFFICIAL PAGE]
Audience: adult commuters and everyday travellers.

Use the story arc Morning Routine → Journey → Product Reveal.
Show meaningful realistic human actions and moving camera shots; NO spoken dialogue
between people. Write one calm, emotionally engaging English voiceover of
approximately 30–38 words, with natural breathing space.

Return: film premise, approved product claims only, narration, three-shot storyboard,
needed product references, sound mood and final call to action.
No invented data or testimonials. Acknowledge that this is an independent educational concept.
```

**Suggested draft voiceover** (adjust after testing the actual voice):

> “Every morning begins a journey. Some paths are familiar. Others are waiting to be discovered. Wherever your day takes you, carry a little comfort along. Milton Atlantis. Ready for the journey ahead.”

## 🎞️ 3. Produce scene-specific JSON specifications

Use the following prompt once the story has been approved:

```text
Turn our approved film into three standalone scene JSON objects. For every scene,
include: scene_id, target_cut_duration, reference_identity, human_action, environment,
framing, camera_movement, lighting, colour_grade, audio_ambience, and constraints.
Repeat the SAME compact product/character continuity description inside EACH object.
Use one primary action per moving shot. No in-frame logos, subtitles or invented labels.
Do not request a separate 'master prompt'.
```

### Scene A — Morning routine

```json
{
  "scene_id": "S01",
  "target_cut_duration_seconds": 8,
  "framing": "medium close-up widening slightly",
  "reference_identity": "same adult South Asian commuter with dark hair, olive-green jacket and black backpack; same approved black insulated bottle from official reference photo",
  "human_action": "commuter reaches to the desk, grips the bottle, and places it in their backpack",
  "environment": "modern apartment workspace, sunrise through a side window",
  "camera_movement": "controlled lateral tracking shot toward the action; continuous motion",
  "lighting": "warm natural morning light from camera-left",
  "colour_grade": "warm premium cinematic, natural skin tones, realistic highlights",
  "audio_ambience": "subtle footsteps, backpack fabric, gentle room ambience; no dialogue",
  "constraints": ["do not alter product lid or silhouette", "no changing hands or extra limbs", "no generated text", "no added people", "no jump cuts"]
}
```

### Scene B — The journey

```json
{
  "scene_id": "S02",
  "target_cut_duration_seconds": 8,
  "framing": "medium tracking shot with scenic background",
  "reference_identity": "same adult South Asian commuter with dark hair, olive-green jacket and black backpack; same approved black insulated bottle",
  "human_action": "commuter walks along a calm outdoor trail, pauses and takes the bottle from the side pocket",
  "environment": "accessible scenic hillside trail, clear weather, soft vegetation moving naturally",
  "camera_movement": "smooth parallel dolly/tracking movement alongside the walking subject",
  "lighting": "golden-hour natural sunlight with balanced shadows",
  "colour_grade": "warm premium cinematic, match previous shot exposure and skin tone",
  "audio_ambience": "soft wind, natural footsteps and fabric rustle; no dialogue",
  "constraints": ["preserve subject identity and jacket", "preserve bottle geometry and lid", "no teleporting objects", "no extra fingers", "no visible text"]
}
```

### Scene C — Product close

```json
{
  "scene_id": "S03",
  "target_cut_duration_seconds": 4,
  "framing": "close-up clean product hero composition",
  "reference_identity": "manufacturer-approved black Atlantis bottle reference with unchanged shape and proportions",
  "human_action": "none; bottle remains stationary while realistic reflections shift with camera movement",
  "environment": "controlled premium tabletop studio, deep navy gradient background",
  "camera_movement": "subtle 3D dolly/orbit; no artificial distortion of the bottle",
  "lighting": "soft rim highlights, grounded natural shadow",
  "colour_grade": "premium navy and warm highlights consistent with earlier shots",
  "audio_ambience": "gentle ambience and soft musical resolution",
  "constraints": ["product identity exact", "no altered logos", "no invented measurements", "no fake label lettering", "add final brand name in editor instead"]
}
```

The finished cut can use parts of longer generated clips; exact generation lengths depend on the model and subscription.

## 🖼️ 4. Create reference frames

Work with the authentic product reference **only when you have permission to use it**. The same reference must guide all three shots. Generate each scene image in sequence:

```text
Create a photorealistic cinematic storyboard frame for [SCENE ID], following the
approved scene JSON and attached product reference. Preserve exact product shape,
lid, body colour and realistic scale. Preserve the same character, hair, outfit
and backpack across relevant scenes. 16:9 composition, natural anatomy,
controlled depth of field, cinematic colour consistency. No text, no watermarks,
no invented logo or packaging claims. This is ONE still frame, not the video.
```

Review all still frames before animating. Compare lid shape, product proportions, hand anatomy, wardrobe and lighting. If any change is significant, regenerate that frame.

## 🎥 5. Animate each frame into genuine moving footage

In an eligible [Google Vids](https://workspace.google.com/products/vids/) account, create a widescreen project, open **Generate video**, attach the approved reference image(s), and enter the corresponding motion description below.

**S01 motion prompt**

```text
Animate the approved morning scene into realistic cinematic footage. The adult
commuter naturally reaches for the black insulated bottle and slips it into a
backpack; fingers grip correctly and the bottle keeps its original shape. Smooth
sideways camera tracking, subtle sunlight variation, believable fabric movement.
Use the supplied reference identity. Ambient sound: quiet footsteps, desk contact,
backpack fabric. No dialogue, no overlay text, no cuts, no object morphing. 16:9.
```

**S02 motion prompt**

```text
Animate the approved outdoor scene into realistic cinematic footage. The SAME
commuter walks along a hillside path carrying the SAME backpack and bottle.
The camera tracks parallel to the subject, with natural footsteps, moving foliage
and jacket movement. The subject pauses and reaches toward the bottle once.
Preserve product geometry, character identity and exposure; avoid deformed hands,
teleporting props, extra people and artificial camera shakes. No dialogue. 16:9.
```

**S03 motion prompt**

```text
Generate a premium cinematic product hero shot from the approved Milton Atlantis
reference. The bottle stays stationary while the camera moves in a very subtle
controlled arc. Natural highlight movement, realistic surface reflections, stable
lid and proportions. Leave clean negative space for a title that will be added
by the editor. No generated brand text or logos, no product morphing. 16:9.
```

**Quality rule:** Select only clips with actual subject and/or camera motion; a still photo with an artificial zoom does not satisfy this exercise. Regenerate unstable hands, incorrect bottle geometry or obvious face changes.

## 🎙️ 6. Generate a human-like AI narration

Use a speech-generation tool, such as [MiniMax](https://www.minimax.io/), with a natural English voice. Enter the approved narration as *speech text* (not as song lyrics).

```text
Speak the following short commercial narration in warm, measured Indian English.
Natural breaths, conversational rhythm, slight curiosity in the opening,
confident yet understated brand reveal. Do not sing, overact, or adopt a robotic
announcer cadence. Keep a consistent single narrator. Preserve product
pronunciation. Use gentle pauses at sentence breaks.

NARRATION:
Every morning begins a journey. Some paths are familiar. Others are waiting
to be discovered. Wherever your day takes you, carry a little comfort along.
Milton Atlantis. Ready for the journey ahead.
```

Listen to several voices if available; select the most realistic, intelligible take. If the narrator cannot fit the visuals naturally, shorten the script rather than unnaturally speeding up speech.

## 🎵 7. Create instrumental background music

Use [MiniMax Music](https://www.minimax.io/audio/music) or a suitably licensed instrumental track. Keep music separate from narration.

```text
Create approximately 24 seconds of instrumental cinematic music for a premium
everyday product advertisement. No lyrics, singing, spoken words or vocal chops.
Warm piano, airy soft synth textures and restrained organic percussion; gentle
build across the middle, elegant resolution near the final product reveal.
Avoid harsh drums, triumphant trailer impacts and attention-grabbing melodies.
Ensure clear space in the midrange for narration.
```

## 🎞️ 8. Assemble and export

Sequence: **S01 → S02 → S03**. Trim to the intended story; blend visual transitions subtly; place narration on one track and music on another. Mute unusable generated speech or distracting ambience; keep suitable environmental sounds quieter than the voice. Add accurate approved product naming and an educational-concept label as native editor text.

**Final checks:** actual movement, actor continuity, bottle geometry, believable hand actions, no fabricated product claims, intelligible natural voice, music underneath narration, readable titles, correct permissions and a properly playable MP4.

## ✅ Proof of completion

A finished moving advertisement is a distinct output from its storyboards, image references and prompts. This repository supplies the workflow; **a final AI-generated video has not been included or represented as complete unless a verified rendered MP4 is added**.

[⬅️ Module 02](../Module_02_LEARN_LIVE/README.md) · [🏠 Main programme](../README.md) · [➡️ Module 04](../Module_04_BUILD_LIVE/README.md)
