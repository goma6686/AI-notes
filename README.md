# ==Models==

## [DreamShaper] (https://civitai.com/models/4384/dreamshaper)

<img src="https://shorturl.at/cNTV7" width="300"/>
<img src="https://shorturl.at/qrCN5" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ SDE Karras
       - Model: DreamShaper8_pruned
       - Seed: 2067885436
       - Clip skip 2
       - CFG Scale: 8
       - Steps: 20
  2. TXT2IMG prompt:
     - **Positive**: (anime coloring, anime screencap, ghibli, mappa, anime style), 1girl, hatsune miku, white gown, angel, angel wings, golden halo, dark background, upper body, (closed mouth:1.2), looking at viewer, arms behind back, blue theme, stars, starry night
     - **Negative**: BadDream, FastNegativeV2

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: DPM++ SDE Karras
       - Model: DreamShaper8_pruned
       - Seed: 3091544718
       - Clip skip 2
       - CFG Scale: 12
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: (masterpiece), (extremely intricate), fantasy, (((realistic portrait of an evil hermit, male, villain, anti hero, evil face, masculine face, medium hair, Maroon hair, wicked, cruel, sinister, malicious, ruthless, masculine, athletic))), (((dark bloody clothing, intricate details on clothing))), (perfect composition:1.4), aspect ratio 1:1, beach, deviantart hd, artstation hd, concept art, detailed face and body, award-winning photography, margins, detailed face, professional oil painting by Ed Blinkey, Atey Ghailan, Jeremy Mann, Greg Manchess, Alex Gray, trending on ArtStation, trending on CGSociety, intricate, high detail, sharp focus, dramatic, award winning matte drawing cinematic lighting octane render unreal engine volumetrics dtx
     - **Negative**: UnrealisticDream, (BadDream)

</details>

**Suggested settings**:
- **CLIP skip 2**
- ENSD set to 31337
- highres.fix or img2img at higher resolution. Some even have ADetailer. Careful with that tho, as it tends to make all faces look the same.
- **don't use "restore faces".**

**For old versions**:
- Versions >4 require no LoRA for anime style. For version 3 I suggest to use one of these LoRA networks at 0.35 weight:
-- https://civitai.com/models/4219 (the girls with glasses or if it says wanostyle)
-- https://huggingface.co/closertodeath/dpepmkmp/blob/main/last.pt (if it says mksk style)
-- https://civitai.com/models/4982/anime-screencap-style-lora (not used for any example but works great).

**NOTES**:
- **Version 5** is the best at **photorealism** and has noise offset.
- **Version 4** is much better with **anime** (can do them with no LoRA) and **booru tags**. IT might be harder to control if you're used to caption style, so you might still want to use version 3.31.

## [ReV Animated] (https://civitai.com/models/7371)

<img src="https://shorturl.at/fqE38" width="300"/>
<img src="https://shorturl.at/uFOYZ" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: rev_1.2.2
       - Seed: 387766904
       - Clip skip 2
       - CFG Scale: 8.5
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: ((best quality)), ((masterpiece)), (detailed), (realistic), male warrior, muscular physique, tribal attire, face paint, wielding spear, (jungle:1.3), dense foliage, exotic plants, dappled sunlight, (hyperrealistic:1.2), oil painting, (Frank Frazetta:1.1), DeviantArt influence, dynamic action pose, (intense expression:1.2), (portrait shot:1.1), 8k resolution
     - **Negative**: 3d, cartoon, anime, sketches, (worst quality, bad quality, child, cropped:1.4) ((monochrome)), ((grayscale)),  (bad-hands-5:1.0), (badhandv4:1.0), (easynegative:0.8),  (bad-artist-anime:0.8), (bad-artist:0.8), (bad_prompt:0.8), (bad-picture-chill-75v:0.8), (bad_prompt_version2:0.8),  (bad_quality:0.8)

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: rev_1.2.2
       - Seed: 2474129942
       - Clip skip 2
       - CFG Scale: 8.5
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: ((best quality)), ((masterpiece)), (detailed), close-up, person wearing costume, (Behance contest winner:1.2), fantasy art, crown of giant rubies, 3D goddess portrait, style of Ross Tran, captivating lighting, 8k resolution, striking facial expression, (elaborate costume details:1.3), vibrant colors, powerful presence, (ethereal glow:1.1)
     - **Negative**: 3d, cartoon, anime, sketches, (worst quality, bad quality, child, cropped:1.4) ((monochrome)), ((grayscale)),  (bad-hands-5:1.0), (badhandv4:1.0), (easynegative:0.8),  (bad-artist-anime:0.8), (bad-artist:0.8), (bad_prompt:0.8), (bad-picture-chill-75v:0.8), (bad_prompt_version2:0.8),  (bad_quality:0.8)

</details>

- VAE:
  - orangemix
  - kl-f8-anime2
  - Blessed2

- Prompting
  - **Order matters** - words near the front of your prompt are weighted more heavily than the things in the back of your prompt.
  - **Prompt order** - content type > description > style > composition
  - **This model likes**: ((best quality)), ((masterpiece)), (detailed) in beginning of prompt **if you want anime-2.5D type**
  - This model does great on **PORTRAITS**

## [GhostMix] (https://civitai.com/models/36520)

<img src="https://shorturl.at/awxOT" width="300"/>
<img src="https://shorturl.at/cfkqG" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: GhostMix-V2.0-fp16-BakedVAE
       - Seed: 1015468391
       - Clip skip 2
       - CFG Scale: 6
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: (masterpiece, top quality, best quality, official art, beautiful and aesthetic:1.2), (1girl), extreme detailed,(fractal art:1.3),colorful,highest detailed
     - **Negative**: (worst quality, low quality:2), monochrome, zombie,overexposure, watermark,text,bad anatomy,bad hand,extra hands,extra fingers,too many fingers,fused fingers,bad arm,distorted arm,extra arms,fused arms,extra legs,missing leg,disembodied leg,extra nipples, detached arm, liquid hand,inverted hand,disembodied limb, small breasts, loli, oversized head,extra body,completely nude, extra navel,easynegative,(hair between eyes),sketch, duplicate, ugly, huge eyes, text, logo, worst face, (bad and mutated hands:1.3),  (blurry:2.0), horror, geometry, bad_prompt, (bad hands), (missing fingers), multiple limbs, bad anatomy, (interlocked fingers:1.2), Ugly Fingers, (extra digit and hands and fingers and legs and arms:1.4), ((2girl)), (deformed fingers:1.2), (long fingers:1.2),(bad-artist-anime), bad-artist, bad hand, extra legs ,(ng_deepnegative_v1_75t)

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: GhostMix_ghostmix_v20Bakedvae
       - Seed: 1313959311
       - Clip skip 2
       - CFG Scale: 6
       - Steps: 25
  2. TXT2IMG prompt:
     - **Positive**: abstract art, (style of Yuko Shimizu:1.3), (white theme:1.1), gold theme, golden butterflies, dark stars, 1girl, field of white flowers, <lora:add_detail:1>, facing viewer
     - **Negative**: (worst quality, low quality:2), NSFW, monochrome, zombie, overexposure, watermark, text, bad anatomy, bad hand,((extra hands)),extra fingers, too many fingers, fused fingers, bad arm, distorted arm, extra arms, fused arms, extra legs, missing leg,disembodied leg,extra nipples, detached arm, liquid hand, inverted hand, disembodied limb, oversized head, extra body, extra navel, (hair between eyes),sketch, duplicate, ugly, huge eyes, text, logo, worst face, (bad and mutated hands:1.3), (blurry:2.0), horror, geometry, bad_prompt, (bad hands), (missing fingers), multiple limbs, bad anatomy, (interlocked fingers:1.2), Ugly Fingers, (extra digit and hands and fingers and legs and arms:1.4), (deformed fingers:1.2), (long fingers:1.2), bad hand, extra legs ,ng_deepnegative_v1_75t, badhandv4, verybadimagenegative_v1.3, By bad artist -neg, easynegative

</details>

- **Highres-Fix is A Must!** Highres-Fix: 2x, denoising:0.4-0.5 or 1.5x, denoising:0.5-0.65.
- Clip skip 1/2
- **Sampler Suggest** : DPM++ series , Steps: 20-30, CFG:5-7(7 is best)
- **THIS IS NOT A 3D MODEL**
- Some prompt recommendations:
  - **Fractal Art**:
  (masterpiece, top quality, best quality, official art, beautiful and aesthetic:1.2), (1girl:1.3), (fractal art:1.3),
  - **Color art**:
  (flat color:1.3),(colorful:1.3),(masterpiece:1.2), best quality, masterpiece, original, extremely detailed wallpaper, looking at viewer,1girl,solo,floating colorful water
- **VAE**:
  -  kl-f8-anime2
  -  vae-ft-mse-840000-ema-pruned



## [Bloody Mary] (https://civitai.com/models/113969)

<img src="https://shorturl.at/rAXY9" width="300"/>

<details>
<summary>details</summary>

  1. Settings 
       - Sampler: DPM++ SDE Karras
       - Model: bloody_mary_Final
       - Seed: 351159
       - CFG Scale: 5
       - Steps: 50
  2. TXT2IMG prompt:
     - **Positive**: An ultra hd detailed painting of many different types of flowers by android jones, earnst haeckel, james jean. behance contest winner, generative art, baroque, intricate patterns, fractalism, movie still, photorealistic,Portrait of a beautiful woman surrounded by fire, portrait of beautiful young maiden, warhammer, some red water, the middle ages, highly detailed, artstation, illustration, sylvari portrait, 8 k quality, art by partick woodroof
     - **Negative**: 3d, cartoon, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, young, loli, elf, 3d, illustration

</details>

----------------
# ==Loras==

## [3D render style] (https://civitai.com/models/73756?modelVersionId=107366)

<img src="https://shorturl.at/aewX9" width="300"/>
<img src="https://shorturl.at/lrtwO" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: animesh_FullV15
       - Seed: 2136366136
       - Clip skip 2
       - CFG Scale: 20
       - Steps: 25
  2. TXT2IMG prompt:
     - **Positive**: (realistic:1.3), finely detailed, (masterpiece:1.2), (photorealistic:1.2), (best quality), (intricate details), <lora:3DMM_V12:0.6>, <lora:add_detail:1>, <lora:stylesqueeze_v1b:0.5>, 1girl, adult (elven:0.7) woman, freckles, coral eyes, light blonde twin drills hair, portrait, looking down, solo, (full body:0.6), detailed background, detailed face, (<lora:AntimatterTech-20:0.5>, antitech, antimatter theme:1.1), inventor, safety-goggles, lab coat, innovation, advanced technology, fantastical science lab in background, biology, microscope, biohazard, virology, surgical mask,    test chamber, <lora:granblue2:0.5>
     - **Negative**: EasyNegative, drawn by bad-artist, sketch by bad-artist-anime, (bad_prompt:0.8), (artist name, signature, watermark:1.4), (ugly:1.2), (worst quality, poor details:1.4), bad-hands-5, badhandv4, blurry, deformed feet, deformed hands

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: lemonTeaMixPainterly2_v1
       - Seed: 1702809180
       - Clip skip 2
       - CFG Scale: 20
       - Steps: 25
  2. TXT2IMG prompt:
     - **Positive**: (masterpiece, best quality), photorealistic rendering,   colorful paint style, <lora:add_detail_v5:1>, <lora:anime3d:0.75>, <lora:3DMM_V12:0.25>, 3DMM, 1girl, adult british woman, freckles, light blue eyes, blonde ponytail,portrait, looking at viewer, solo, (full body:0.6), detailed background, detailed face, (<lora:ChronomancyAI:0.5>, ChronomancyAI, chronomancy theme:1.1) evil sorcerer, tattered dark brown magical robes, sinister smirk, scarlet color scheme, dark crimson light, study room, bookshelves,  evil book, dark atmosphere, shadows, realistic lighting, floating particles, sparks, surrounded by yellow lightning <lora:LightingVFX:0.1>,  summoning,  blue arcane symbols, corrupted by eldritch power, power-hungry eyes, bloom
     - **Negative**: (abstract paint), (3d, realistic:1.3), (low quality, worst quality:1.4), (bad anatomy), extra digit, fewer digits, (extra arms:1.2), bad hands, by (bad-artist:0.6), bad-image-v2-39000, Asian-Less-Neg

</details>


- **Trigger word**: 3DMM
- 
  **Positive prompt**:
   1girl,Look straight ahead, long hair, Straight hair, a dark room with lights, close-up shot, Street Background, masterpiece, best quality,**3dmm style**,3d,realistic, high-quality, 3D realistic works, ultra-high details, 4k, real skin materials,simple background
  **Negative prompt**:
  tattooing,lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry,braid hair

## [Khrone] (https://civitai.com/models/109647/khorne)
<img src="https://shorturl.at/esCGN" width="300"/>
<img src="https://shorturl.at/bAJKT" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: GhostMix_ghostmix_v20Bakedvae
       - Seed: 1367881045
       - Clip skip 2
       - CFG Scale: 7
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: (masterpiece, top quality, best quality, official art, beautiful and aesthetic:1.2), extremely detailed, very detailed, absurd quality, intricate detail, volumetric light, cg illustration, trending on artstation, award-winning illustration, dark fantasy, gothic art, dark art, digital painting, dark souls style, 1girl, priestess, upper body, (closeup view on face:1.1), standing, blindfold, long hair, white hair, (messy hair:1.3), wavy hair, black robes, golden accents, (ornate1.3), abandoned temple, front view, <lora:add_detail:1>, <lora:khorne:1>
     - **Negative**: (worst quality, low quality:2), NSFW, monochrome, zombie, overexposure, watermark, text, bad anatomy, bad hand,((extra hands)),extra fingers, too many fingers, fused fingers, bad arm, distorted arm, extra arms, fused arms, extra legs, missing leg,disembodied leg,extra nipples, detached arm, liquid hand, inverted hand, disembodied limb, oversized head, extra body, extra navel, easynegative,(hair between eyes),sketch, duplicate, ugly, huge eyes, text, logo, worst face, (bad and mutated hands:1.3), (blurry:2.0), horror, geometry, bad_prompt, (bad hands), (missing fingers), multiple limbs, bad anatomy, (interlocked fingers:1.2), Ugly Fingers, (extra digit and hands and fingers and legs and arms:1.4), (deformed fingers:1.2), (long fingers:1.2), bad hand, extra legs ,(ng_deepnegative_v1_75t),((hands on head)),  badhandv4,  verybadimagenegative_v1.3,  By bad artist -neg

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: Euler a
       - Model: sakushimixHentai_sakushiV20
       - Seed: 1032435244
       - Clip skip 2
       - CFG Scale: 6.5
       - Steps: 30
  2. TXT2IMG prompt:
     - **Positive**: (solo, 1girl, crazy, yelling, blood on face, blood on clothes) (digital) ( in detailed construction site,  (armor)) , best quality, <lora:boldline:0.2>  <lora:hairdetailer:0.2> khorne, skull, <lora:khorne:0.7>
     - **Negative**: (worst quality, low quality:1.4) bad-artist bad-hands-5 bad-image-v2-39000 badhandv4 verybadimagenegative_v1.3 EasyNegative, 3d

</details>

- **Clip skip 2**
- **Trigger words**: khorne, armor, skull
- **Additional**: blood on face, blood on clothes, spiked armor, chain

## [Anime 3D Converter] (https://civitai.com/models/108813)
*will convert your anime model to a 3D style and bring new life to all of your old checkpoints.*

<img src="https://shorturl.at/nDGK1" height="400"/>

## [Anime realism control] (https://civitai.com/models/99619/anime-realism-control-lora)
*This LoRA will make your model either 2D/anime <-> 3D/photorealistic depending on how to use it.*

<img src="https://shorturl.at/nzJO4" height="400"/>

- \<lora:realistic:-1.0> (negative values) will strengthen the 2D style and \<lora:realistic:1.0> (positive values) will strengthen the photo style
- Potential uses:

    - Adjust the style of your model slightly to make it look more original

    - Make a realistic model more realistic (such as when the skin is too smooth/plastic)

    - Make a 2D/anime model more stylised by making it more 2D

    - Combined with the detail LoRA (linked in the resources) you can reduce details in your anime model and make it look more 2D to create a unique cell shaded style

## [Pentagram harness] (https://civitai.com/models/108718/pentagram-harness)

<img src="https://shorturl.at/cyGK8" height="300"/>

- Works with realistic and anime/comic models
- **Trigger word**: pentagram_harness
- **hres fix enabled**

## [Colored Skin] (https://civitai.com/models/19695/colored-skin-loha)

==Lora/LoHa==
==Loha is way better at multi-concepts==
- **Trigger word**: <lora:ColoredSkinv309:0.7>(gray skin, woman)
- You might want to add some negatives to counter color bleeding if necessary, for example: (purple background, purple eyes, purple clothes, purple hair)

## [Tattoos] (https://civitai.com/models/65050/tattooloralora)

<img src="https://shorturl.at/hCPU6" height="300"/>

- **Trigger words**: 1girl, tattoo
- Doesn't work well with kimono
- Used to enchance the effect of word tattoo

## [Valkyrie] (https://civitai.com/models/64422/valkyrie)

<img src="https://shorturl.at/chxGJ" height="400"/>

- **Trigger words**: walkure, wearing walkure, armor, helmet, chainmail armor,wings
- Don't expect perfect wings all the time

## [Beautiful armor] (https://civitai.com/models/65353/cm-beautifularmor)

<img src="https://shorturl.at/muBTU" height="300"/>

- <lora:CM-Beautiful_armor:0.8>CM-Beautiful_armor,armor
- **Trigger words** - CM-Beautiful_armor,armor,   shield, shoulder_armor,crown，weapon，sword

## [Line Tweaker] (https://civitai.com/models/78118)

<img src="https://shorturl.at/ghUX6" height="250"/>

- Increase weight, increase the thickness of the tick marks, reduce weight, and reduce the tick marks, with a maximum/minimum of 2/-2!
- When using larger weights, there may be significant changes in the image

## [Detail tweaker] (https://civitai.com/models/77203)

<img src="https://shorturl.at/fjtDJ" height="200"/>

- Increase weight to increase details, reduce weight to reduce details, up to a maximum/minimum of 3/-3!
- When using larger weights, there may be significant changes in the image
- Use negative weights to reduce details!

## [Detail Maker] (https://civitai.com/models/62687)

<img src="https://shorturl.at/gjGIM" height="250"/>

- Positive weights can still increase the details of the image, making it particularly suitable for creating things out of thin air. 
- Negative weights can reduce details.
- The weight range is from - 6 to 3, and both the real style model and the anime animation style model are competent.
-------------------
# ==Wildcards==

## [Full feature character fantasy prompts] (https://civitai.com/models/45448/full-feature-character-prompts-fantasy?modelVersionId=112170)

<img src="https://shorturl.at/dikzR" width="300"/>
<img src="https://shorturl.at/efkKZ" width="300"/>

<details>
<summary>1st image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: brickMortar_v20
       - Seed: 751028130
       - Clip skip 2
       - CFG Scale: 20
       - Steps: 25
  2. TXT2IMG prompt:
     - **Positive**: (best quality, masterpiece:1.2), photorealistic, thick outlines, strong shadows, <lora:add_detail:0.75>,(1man, wrinkled face, old  male:1.2), wise,  dark brown eyes, graying hair, short hair, portrait, solo, upper body, looking down, detailed background, detailed face, (<lyco:DecorationBundlev2:0.3>, GemstoneAI, gemstone theme:1.1)  (master of time and space:1.1), eternity, weightless, infinite landscape, swirling patterns, (style-swirlmagic:0.8),  clockwork, clock gears,  energy, standing still,  clock-face in background, ethereal atmosphere,
     - **Negative**: (worst quality, low quality:1.4), logo, watermark, signature, text, EasyNegative, (verybadimagenegative_v1.3:0.75),

</details>

<details>
<summary>2nd image</summary>

  1. Settings 
       - Sampler: DPM++ 2M Karras
       - Model: comicsVision_v21
       - Seed: 3869610533
       - Clip skip 2
       - CFG Scale: 20
       - Steps: 25
  2. TXT2IMG prompt:
     - **Positive**: (inked original-art:1.2), (lineart:1.31), (fine-details:1.3), RAW-format, (depth), (movement:1.4), <lora:add_detail:0.5> 1 girl, adult swedish woman,  aquamarine eyes, dark brown twin drills hair, (style-swirlmagic:1.0), character focus, portrait, looking down, solo, upper body, detailed background, detailed face, (<lora:AngelicAI:0.5>, AngelicAI theme:1.1) holy monk, zealous fury, religious armor, green cross symbols, headdress,  praying,  church,    religious icons,   stained glass,  sacred texts, filigree, swirling lights emanating, urn,      high fantasy style, gold,  holy fire, updraft,
     - **Negative**: (easynegative), (bad-hands-5), (sketch), low-res, text, watermark, (blurried-eyes), (jpeg-artifact), missing-limbs, multiple-characters, high-contrast, strong-shadows

</details>

- **Trigger words** - \__full-prompt-fantasy__
- **Required**:
    https://github.com/adieyal/sd-dynamic-prompts (needed for wildcards to work)
    https://github.com/KohakuBlueleaf/a1111-sd-webui-lycoris (needed for LyCORIS models to work) 

**Usage**:
Add a description of the character you'd like in the generated image (feel free to use character LoRas), plus any style/quality keywords necessary for the model you're using, then add \__full-prompt-fantasy__ to the prompt.

Example:
best quality, masterpiece, 1man, russian (male:1.1), solo, aquamarine eyes, long brown beard, \__full-prompt-fantasy__

-------------------

# ==Inpainting==


## [Img2Img]
Use this for adding or changing details. Other one is better for changing whole segments like background or clothes.
## Inpaint

==Main settings to play with are **denoising strength** and **masked content**==

==ControlNet is not needed in Img2Img==

**Mask mode**:
- Inpaint masked -> paints over masked area
- Inpaint not masked -> paints over everything else
    
**Masked content**
- Original -> leave original and paint **ON** it
    [use denoising up to 0.6]
- latent noise -> fill with noise and generate over that
    [use denoising 0.8-1]
    
**Inpaint area**
- Whole picture -> usually produces wonky results
    Works better when **changing** things like e.g. face
- Only masked -> focuses on the masked area
    Works better when **adding** things like e.g. new jewelry
    ==Add tiny dots around mask for context==

## Inpaint sketch

Works the same as inpaint, but it's better for specifying colors

## [InpaintAnything]

1. Choose segmentation model. It is best to use ones with _hq_ in the name
- Outpainting can be achieved by the Padding options, configuring the scale and balance, and then clicking on the Run Padding button
2. Click on the `Run Segment Anything` button.
Use sketching to point the area you want to inpaint. You can undo and adjust the pen size.
3. Click on the `Create mask` button. The mask will appear in the selected mask image area.

**Mask Adjustment**

- `Expand mask region` -> Use this to slightly expand the area of the mask for broader coverage.
- `Trim mask by sketch` -> Clicking this will exclude the sketched area from the mask.

**Inpainting Tab**

4. Enter Prompt and Negative Prompt, then choose the Inpainting Model ID. **Dreamshaper 6** works best usually
5. Choose Sampler. Euler is usually best with 30 steps
6. Click on the `Run Inpainting `

**ControlNet Inpaint Tab**

4. use the Stable Diffusion checkpoint
5. Enter Prompt(s)
6. Use _inpaint only_ preprocessor
7. Play with Denoising Strength
-----------------------
# ==Prompting==

**[General Structure]**
 
[STYLE OF PHOTO] photo of a [SUBJECT], [IMPORTANT FEATURE], [MORE DETAILS], [POSE OR ACTION], [FRAMING], [SETTING/BACKGROUND], [LIGHTING], [CAMERA ANGLE], [CAMERA PROPERTIES],in style of [PHOTOGRAPHER]

- Prompts should specify critical attributes like subject, style, lighting, and composition.
- You may need to add weighing to a prompt to make it more prominent this can be done by following this syntax **(prompt:1.1) to increase the weight go higher with the second number.**
- On a technical level, Stable Diffusion encodes prompts into numeric representations to capture semantic meaning. As it constructs the image, the AI refers back to these encoded prompts, paying closer attention to the most relevant terms. It prioritizes key words, ignoring less important ones.
- **Photorealistic models work better with more descriptive prompts** unlike **anime** that prefers **just tags**

**[Styles]**
- https://supagruen.github.io/StableDiffusion-CheatSheet/

**[Subject]**
- Use terms like “teenage girl”, “elderly man”, “middle aged woman” to imply age and gender
- The tag “age followed by a number” like “age 30” can further pin down age
- Describe ethnicity and skin tone if relevant. Use Lora for more specific skin tones
- include distinctive features like hairstyle (“short curly red hair”), clothing (“wearing a sundress”), expression (“smiling excitedly”), and accessories (“eyebrows pierced”). Unique details make the subject feel more like a specific individual.

<details>
<summary>Example</summary>

- a (beauty photo:1.3) of a beautiful shy young japanese woman,age 25,with long curled black hair, wearing a cute red hoodie, [POSE OR ACTION], [FRAMING], [SETTING/BACKGROUND], [LIGHTING], [CAMERA ANGLE], [CAMERA PROPERTIES], in style of
[PHOTOGRAPHER].
</details>

**[Pose/Action]**

**[Framing]**

**[Setting]**

**[Lighting]**

<details>
<summary>Examples</summary>

- bounced lighting
- candlelight
- chiaroscuro
- cinematic lighting
- soft diffused lighting
- edge lighting
- fill lighting
- flash photography
- god rays
- golden hour
- hard light
- high key lighting
- low key lighting
- natural lighting
- neon lighting
- overcast lighting
- rim lighting
- shadow play
- silhouette lighting
- soft lighting

</details>

**[Camera angle]**

<details>
<summary>Examples</summary>

- dutch angle
- from above/high angle
- from below/low angle
- eye level

</details>

https://rentry.org/hdgpromptassist
Souce: https://rentry.org/gpt-prompt-generator-230122
----------
# How To

## Seams After Inpainting:

This will generally just remove seams and infill the image without doing much else to it. This is also a useful infill technique for very small (e.g. seams, color blending) errors.

<details>
<summary>Steps</summary>

1. mask over all seams, put padding to max
2. mask blur usually 0
3. switch to DDIM
4. positive prompt empty (or just quality tags) (normal negative)
5. set CFG to minimum
6. set denoising highish like .7
7. repeatedly iterate with an empty prompt

</details>

#### Deleting existing object:

<details>
<summary>img2img Inpaint</summary>

   1. masked the choker
   2. maskblur 4 and above
   3. inpaint masked
   4. fill, because I want to keep the colours
   5. padding max for context
   6. DDIM
   7. cfg 1
   8. denoise 0.9

</details>

<details>
<summary>Inpaint Anything Cleaner</summary>

   1. Segment image and create mask
   2. Use Cleaner tab (fcf, ldm usually work well)

</details>

<details>
<summary>Inpaint Anything Inpainting</summary>

   1. Segment image and create mask
    2. Write prompts in Inpainting tab
    3. Use Euler sampler
    4. Use dreamshaper 6 model

</details>
    

#### Changing existing object:

1. Using deleting object + inpainting
2. Using Inpaint Anything:
   <details>
    <summary>Steps</summary>

      1. Inpaint Anything Inpainting
      2. Segment image and create mask
       3. Write prompts in Inpainting tab
       4. Use Euler sampler
       5. Use dreamshaper 6 model
- If replacements clearly don't match surroundings:
-- either your denoising is too high -- or padding is too low(context))

    </details>

Source: https://rentry.org/inpainting-guide-SD
Another: https://rentry.org/drfar

### Nice images I have found

<img src="https://shorturl.at/iRSZ7" height="500"/>

<details>
<summary>Settings</summary>

- Sampler: DPM++ 2M Karras
- Model: tobiko_v10
- CFG scale: 20
- Steps: 25
- Seed: 3428623758
- Clip Skip 2
</details>

<details>
<summary>Prompt</summary>

- **Positive**: (masterpiece:1.2), (best quality:1.2), (ultra detailed:1.2), <lora:add_detail_v5:1>, <lora:sharpen-soften:-0.25>, <lora:realistic:0.3>, <lora:kittew_v0.1:0.4>, 1girl, adult (elven:0.7) woman, freckles, amber eyes, ginger half-up half-down hairstyle, solo, (full body:0.6), looking at viewer, detailed background, detailed face, (<lyco:DecorationBundlev2:0.6> EbonyGoldAI theme:1.1),  supernatural eyes, brooding, witcher, wearing heavy witcher clothes, intricate, bloodstains,  tattered cloak straps, witcher gear, glowing tattoos, supernatural abilities, ocean in background, mist, magical aura, fantasy atmosphere
- **Negative**: paintings, sketches,  (worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality,(ugly:1.331), (duplicate:1.331), (morbid:1.21), (mutilated:1.21),mutated hands, (poorly drawn hands:1.5), blurry, (bad anatomy:1.21), (bad proportions:1.331), extra limbs, (disfigured:1.331), (missing arms:1.331), (extra legs:1.331), (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331), lowers, bad hands, missing fingers, extra digit, bad hands, missing fingers, bad-hands-5, blurry background,depth of field,, sketch, duplicate, ugly, huge eyes, text, logo, monochrome, worst face, (bad and mutated hands:1.3), (worst quality:2.0), (low quality:2.0), (blurry:2.0), horror, geometry, bad_prompt, (bad hands), (missing fingers), multiple limbs, bad anatomy, (interlocked fingers:1.2), Ugly Fingers, (extra digit and hands and fingers and legs and arms:1.4),  (deformed fingers:1.2), (long fingers:1.2),(bad-artist-anime), bad-artist, bad hand, extra legs

</details>

---

<img src="https://shorturl.at/cnuKN" height="600"/>

<details>
<summary>Settings</summary>

- Sampler: DPM++ SDE Karras
- Model: revAnimated_v122
- CFG scale: 7.5
- Steps: 22
- Seed: 1812726446
- Clip Skip 2
</details>

<details>
<summary>Prompt</summary>

- **Positive**: Female Warlock wearing Golden Light Armor with Sunfire Inlay , Crimson Red Cloak with Golden Phoenix: A majestic golden phoenix is elegantly woven into the fabric, symbolizing rebirth and courage., (Star Anise,Bright Greek color background:1.3),  <lora:ArmorFusion:0.8>
- **Negative**: NSFW,deformed,large breasts,missing limbs,amputated,pants,shorts,cat ears,bad anatomy, naked, no clothes,disfigured, poorly drawn face, mutation, mutated,ugly, disgusting, blurry, watermark, watermarked, over saturated, obese, doubled face,b&w, black and white, sepia, nude, freckles, no masks,duplicate image, blur, paintings, sketches, (worst quality:2), (low quality:2), (normal quality:2), low res, normal quality, monochrome, grayscale, bad anatomy,(fat:1.2),facing away, looking away,tilted head,low res,bad anatomy,bad hands, text, error, missing fingers,extra digit, fewer digits, cropped, worst quality, low quality, normal quality,jpeg artifacts,signature, watermark, username,blurry,bad feet,cropped,worst quality,low quality,normal quality,jpeg

</details>
