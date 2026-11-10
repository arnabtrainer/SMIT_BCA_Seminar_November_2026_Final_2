# 🎬 Module 03 — AI Can Help Me Create

> **AI in Action: Learn • Create • Build**  
> **Theme:** Take a real product from a creative brief to a cinematic AI-assisted advertisement—story, images, moving video, voice, music and editing.

![Module 3 — Create with AI](https://github.com/user-attachments/assets/b12841ad-5444-4a1b-9668-aa9702293191)

[🏠 Main programme](../README.md) · [⬅️ Learn with AI](../Module_02_LEARN_LIVE/README.md) · [➡️ Build with AI](../Module_04_BUILD_LIVE/README.md)

## 🎥 Full cinematic production guide

[📘 **Create a Real-Movement AI Product Advertisement — Step-by-Step Runbook**](04_Cinematic_Production_Runbook.md)

This companion guide contains a real-product creative brief, three scene-specific JSON examples, visual-consistency instructions, image-to-video motion prompts, natural-narration direction, instrumental music prompts and final video checks. It follows the Chengmari-inspired methodology while using a different everyday product for learning.

**Transparency:** The runbook is an end-to-end production plan. It does not include or claim a finished Google Vids/Veo-generated advertisement.

## 🌟 Overview

A polished promotional film is **not** simply a slideshow with transitions. It communicates one idea through composition, meaningful action, realistic camera movement, expressive narration, sound and careful editing. In this module, those pieces come together through an end-to-end, AI-assisted creative workflow.

**Demonstration brief:** Create an original educational advertising concept for the **Milton Atlantis Thermosteel Water Bottle (black, 750 ml)**. The product is real, but this workshop advertisement is **not an official Milton campaign or endorsement**.

**Creative concept:** *Every Journey Begins with a Moment.*  
**Planned deliverable:** A short cinematic MP4 with moving footage, spoken narration, instrumental music and a clear product finish.

The production approach adapts the earlier Chengmari Tea creative methodology—**brief → storyline → structured scene prompts → consistent images → genuine video motion → voice and music → edit and review**—to a different everyday product.

## 🎯 Learning objectives

After exploring this module, you should be able to:

- Turn a product brief into a clear creative concept and visual story.
- Write scene descriptions that control subject, action, framing, camera, lighting and continuity.
- Generate **reference images** and use them to guide moving-video generation.
- Distinguish genuine subject/camera motion from a still-image slideshow with a zoom effect.
- Produce and combine AI narration, an instrumental track and suitable ambient sounds.
- Review factual claims, visual consistency, licensing and audio quality before export.

## 🧰 Tools and reference sources

| Tool/source | Role | Link |
|---|---|---|
| 🛍️ Milton website | Research the actual product and verify details | [Milton Atlantis product page](https://www.milton.in/products/atlantis-thermosteel-water-bottle) |
| 💬 ChatGPT | Creative brief, story, narration, prompts and visual references | [chatgpt.com](https://chatgpt.com/) |
| 🎞️ Google Vids | Image-to-video generation and timeline editing, if enabled in your account | [Google Vids](https://workspace.google.com/products/vids/) |
| 🎙️ MiniMax Speech | Audition and produce spoken AI narration | [MiniMax](https://www.minimax.io/) |
| 🎼 MiniMax Music | Generate instrumental background music, where supported | [MiniMax Music](https://www.minimax.io/audio/music) |

The exact tools and model names can change. If a listed capability is unavailable under your account, another tool with the same function can be substituted **without changing the production principles**.

## 🎯 The creative brief

| Brief element | Working specification |
|---|---|
| Product | Milton Atlantis Thermosteel bottle, black, 750 ml |
| Audience | Adults who carry a reusable bottle for daily activities |
| Core message | A dependable everyday companion for different moments of the day |
| Film style | Hyper-realistic, warm, cinematic lifestyle advertisement |
| Format | Landscape 16:9; short finished commercial |
| Human action | Natural daily preparation and outdoor movement |
| Audio | One natural spoken voiceover plus instrumental music |
| Brand identity | Exact product appearance and approved lettering added in editing |
| Restrictions | No invented claims, false endorsement, altered logo or misleading product geometry |

For a real campaign, obtain the necessary permissions to reuse manufacturer photography, brand graphics and third-party assets; verify all claims against the approved brief. Generated concept images should **not** be passed off as actual product photographs.

## 🎞️ The story — Three visual beats

| Scene | Story moment | Moving footage to generate | Approximate finished edit |
|---|---|---|---|
| **S01 — A New Day** | An adult prepares to leave home with the bottle | Hand reaches toward the bottle; natural movement; gentle tracking camera | 8 s |
| **S02 — On the Move** | The same person moves through an attractive outdoor location | Walking, backpack movement, changing background perspective; smooth following shot | 8 s |
| **S03 — Product Reveal** | The bottle becomes the visual hero | Controlled close-up or product movement; clean typography added afterward | 4 s |

The source clips may be longer than the finished edit and can be trimmed as necessary.

![Illustrative video-production visual from the repository](https://github.com/user-attachments/assets/96cbde5c-1005-4a36-b072-fa20f7b53dec)

## 🧪 Make the advertisement — Start to finish

### Step 1 — Read the real product information

Open the official Milton product page. Note the exact **model, colour, capacity, lid design, materials and any verified features**. Choose one approved product photo if you have permission to use it as a reference. Write the client's single key message in one sentence.

### Step 2 — Generate a story and narration

Paste the verified facts into ChatGPT alongside this prompt:

```text
Act as an experienced advertising creative director and visual storyteller.
Create an original, premium short-form brand-film concept for the Milton
Atlantis Thermosteel bottle (black, 750 ml).

VERIFIED PRODUCT FACTS:
[Paste a small factual summary from the manufacturer's official page.]

Aim for a concise cinematic story with a beginning, middle and end.
Use one adult lead character. Include natural actions and real camera movement.
There should be one expressive, natural-sounding voiceover, but no spoken
on-camera conversation. Style: photorealistic, warm, restrained and premium.

Return: concept title, one-sentence premise, three visual beats,
a short voiceover, a closing message and important visual consistency rules.
Do not invent specifications or imply an official endorsement.
```

Read the concept and choose **one clear story**, rather than combining several unrelated advertising ideas.

### Step 3 — Create scene-by-scene structured prompts

```text
Convert the approved film concept into exactly three independent scene plans
for AI image and image-to-video generation.

For every scene, return a JSON object with:
scene_id, purpose, subject_and_identity, environment, primary_action,
shot_size, camera_movement, lighting, colour_grade, ambience,
narration_segment, duration_target, continuity, and negative_constraints.

Repeat all essential continuity information INSIDE EACH scene object:
the same adult identity, wardrobe, exact bottle design, environment style,
lighting direction and cinematic treatment. Each shot should contain
one primary action. Avoid dialogue, face morphing, extra limbs,
text generation, altered packaging and sudden camera changes.

Also provide a compact three-row shot list and the complete narration.
```

**Why structure prompts?** A scene plan helps maintain consistency and makes it easier to revise one shot at a time. JSON is a convenient production record, **not** a mandatory syntax for every video generator.

### Step 4 — Generate visual frames

Start with an authorised real product reference if available. Create one key image per scene using ChatGPT Images or another image generator.

```text
Create one photorealistic 16:9 cinematic storyboard frame for Scene [S01/S02/S03]
using the approved scene JSON and the product reference image.

Preserve the exact product silhouette, lid, colour and proportions.
Maintain the same adult character identity and wardrobe wherever present.
Respect the scene's lens, lighting direction and colour grade.
Compose the shot to support the planned action and camera movement.
Do not generate lettering, logos, captions or new people.
```

Review the image carefully. Does the bottle match the official reference? Are hands, proportions and perspective believable? Approve a frame **before** using it for moving-video generation.

### Step 5 — Animate each reference frame into genuine video

In Google Vids, use an available **image-to-video / animate image** capability (for example, a Veo-based feature where enabled). Upload the approved scene frame and paste its motion-specific instructions.

```text
Create a cinematic, photorealistic moving shot from the supplied image.
Keep the approved character and bottle visually consistent.

SCENE ACTION: [Insert the scene's single primary physical action.]
CAMERA: [Insert slow tracking, gentle push-in or restrained close-up motion.]
LIGHTING: [Repeat the approved direction and warm premium grade.]
AMBIENCE: [Describe subtle natural location sound only, if supported.]

The subject must actually move naturally; do not only zoom into a still image.
No dialogue, no new props or characters, no altered label, no face morphing,
no sudden cuts and no generated captions. Landscape 16:9.
```

Repeat for the other approved frames. Generate alternatives when the action looks artificial, the bottle changes shape, or movement is unstable. **Only selected video outputs** should enter the final editing timeline.

### Step 6 — Produce AI narration separately

A short illustrative script is:

> “Every day begins with a new journey. From familiar mornings to new adventures, carry what matters. Milton Atlantis. For life's everyday journeys.”

Use a speech-generation service such as MiniMax Speech. In its voice instructions, request **warm, natural, clear Indian English**, confident but conversational delivery, believable pauses and correct pronunciation of the product name. Compare several voices and listen to the complete audio before choosing one. Avoid robotic pacing, excessive dramatic emphasis and music inside the narration track.

### Step 7 — Create the instrumental music

Use a music-generation tool, appropriately licensed music library or an available Google Vids music feature. A sample instrumental direction is:

```text
Create an original instrumental score for a short premium lifestyle advert.
Warm piano, soft ambient textures and restrained uplifting strings.
Start gently, rise subtly during the outdoor journey, then resolve cleanly
for the product reveal. No singing, lyrics or spoken words.
Avoid aggressive drums, busy melodies and abrupt endings.
```

**Keep narration and music separate.** Do not paste ordinary spoken narration into a music generator's lyrics field unless the product explicitly offers spoken narration and you intend to use it that way.

### Step 8 — Edit and export

1. Put the selected moving clips in scene order on the Google Vids timeline.
2. Trim each clip and choose restrained transitions.
3. Add the approved narration as its own track.
4. Add background music at a lower level so every spoken word remains clear.
5. Optionally preserve subtle ambience from the original generated clips.
6. Overlay the accurate product name and any approved logo/text in the editor.
7. Check how the final frame looks when the film ends.
8. Export the final MP4 and watch it from start to finish with headphones.

### Step 9 — Review the finished result

| Quality dimension | What to inspect |
|---|---|
| 🎥 Motion | People genuinely move; camera motion looks controlled; no obvious still-image slideshow |
| 👤 Continuity | Consistent face, outfit, hands and scene geography |
| 🧴 Product | Correct bottle shape, lid, colour and scale; no invented branding |
| 🎙️ Narration | Human-like pacing, clear speech, correct name pronunciation |
| 🎵 Music | Properly licensed, no unwanted vocals, audible but not overpowering |
| 📝 Text | Legible and accurate in the exported film |
| 🛡️ Claims & rights | No unsupported claims, false endorsements or unapproved assets |
| 📺 Export | Correct aspect ratio and playable MP4 with picture and sound |

![Creative production reference from the repository](https://github.com/user-attachments/assets/da9de753-d194-4cd9-bab4-336f8bba9f6a)

## 📂 Available module resources

| Resource | How to use it |
|---|---|
| [🎨 Clean audience slides](03_AUDIENCE_SLIDES_CLEAN.pptx) | Follow the visual production concepts and workflow. |
| This README | Repeat the practical creation process with copy-ready prompts and checks. |

**Production status:** The repository includes the workflow and presentations, **not a verified final cinematic Veo advertisement**. The moving clips, natural voice and licensed soundtrack must be created and reviewed in the applications used. Do not describe a static storyboard preview as genuine AI-generated video footage.

## 🔄 Adapt the workflow to another product

Try a notebook, desk lamp, backpack, reusable coffee cup or fictional household brand. Keep the steps unchanged but replace the verified product facts, visual references, creative style and approved closing message. For an actual client project, obtain relevant content and commercial-use permissions.

## 🌱 Key takeaway

> **A convincing AI advertisement is made through creative direction, real motion, careful audio and quality control—not one prompt alone.**

[⬅️ Module 02](../Module_02_LEARN_LIVE/README.md) · [🏠 Main programme](../README.md) · [➡️ Module 04](../Module_04_BUILD_LIVE/README.md)
