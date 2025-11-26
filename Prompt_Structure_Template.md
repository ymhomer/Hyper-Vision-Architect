# Professional Prompt Generation Template

## 1. Output Philosophy
The system generates prompts using three complementary modes:

- **SPM — Simple Prompt Mode**  
  Compact, readable, ideal for Midjourney, Niji, or simplified SD.

- **UDPM — Ultra-Detail Prompt Mode**  
  Full 24-dimension technical mapping, designed for SDXL, Flux, and ComfyUI-style workflows.

- **Declarative Prompt Mode**  
  A complete natural-language prompt expressing all analytical dimensions  
  using cinematic, illustrative, and photographic narration.

Prompts must remain technically precise, composition-aware, style-consistent,  
and fully safety-compliant.

---

# 2. Template System Overview
Each mode corresponds to different output needs:

| Mode | Style | Use Case | Engines |
|------|--------|-----------|----------|
| **SPM** | concise keywords | general creativity / MJ | Midjourney / MJ Niji / light SD |
| **UDPM** | technical blocks | reconstruction / high accuracy | SDXL / Flux / ComfyUI / A1111 |
| **Declarative** | full paragraph | anime-realism / painterly realism / cinematic | All LLM-based converters + SD engines |

---

# 3. Simple Prompt Mode (SPM)

## 3.1 SPM Structure Overview
1. Subject & Key Features  
2. Attire & Accessories  
3. Pose & Expression  
4. Environment  
5. Lighting  
6. Camera & Lens  
7. Style / Aesthetic

## 3.2 SPM Template
```
[Subject], [distinct visual traits], 
wearing [attire] with [accessories], 
in [environment], under [lighting], 
captured with [camera settings], 
styled in [render/aesthetic].
```

## 3.3 SPM Example
```
A silver-haired woman with warm skin tone,
wearing a metallic satin jacket and leather harness,
standing in a neon alley with reflective pavement,
lit by magenta-blue rim light,
captured with an 85mm lens and shallow depth of field,
in a cinematic cyberpunk aesthetic.
```

---

# 4. Ultra-Detail Prompt Mode (UDPM)

## 4.1 Purpose
To generate maximum-fidelity prompts by mapping all 24 analytical dimensions into structured keyword blocks.

## 4.2 UDPM Structure Order (1:1 with Image Analysis Framework)
1. Composition & Framing  
2. Camera & Perspective  
3. Lighting & Shadows  
4. Materials & Texture  
5. Color & Tone  
6. Facial Features & Anatomy  
7. Body & Pose  
8. Clothing & Accessories  
9. Environment & Structure  
10. Art Style & Render Engine  
11. Lens Characteristics & Imperfections  
12. Spatial Relationships  
13. Mood & Atmosphere  
14. Rendering & Digital Artifacts  
15. Cultural & Regional Localization  
16. Precision & Error-Correction Guidelines  
17. Style Bias Neutralization  
18. Output Fidelity & Consistency Enforcement  
19. Perspective Geometry  
20. Pose Micro-Analysis  
21. Camera–Subject Distance  
22. Material Micro-Texture  
23. Style Mechanics  
24. Background & Spatial Coherence

## 4.3 UDPM Prompt Template
```
[1 • Composition & Framing: rule of thirds, deep staging, leading lines],
[2 • Camera & Perspective: low-angle, wide-angle exaggeration],
[19 • Perspective Geometry: camera placed below chest level, upward tilt, 28mm distortion],
[21 • Camera–Subject Distance: extreme close-up (40–60cm), foreground exaggeration],

[7 • Body & Pose: asymmetrical shoulder drop, natural weight distribution],
[20 • Pose Micro-Analysis: slight forward lean, relaxed finger curvature],

[6 • Facial Features: soft blush gradient, reflective eyes],
[22 • Material Micro-Texture: embroidered lace with high thread count, specular micro-sheen nylon],
[4 • Materials & Texture: porous matte skin scattering, velvet microfibers],

[3 • Lighting & Shadows: warm indoor rim light, soft falloff, volumetric haze],
[23 • Style Mechanics: painterly highlight edges, controlled subsurface scattering],

[9 • Environment & Structure: interior layout with aligned perspective lines],
[24 • Background & Spatial Coherence: window backlight from right, geometric continuity],

[10 • Art Style & Render Engine: photoreal shader, Octane-style reflections],
[11 • Lens Characteristics & Imperfections: 85mm bokeh falloff, slight chromatic fringe],

[13 • Mood & Atmosphere: tender, cinematic tone],
[17 • Style Bias Neutralization: balanced facial topology],
[15 • Cultural & Regional Localization: localized lighting softness, proportional cues],

[18 • Output Fidelity & Consistency Enforcement: maintain palette coherence],
[14 • Rendering & Digital Artifacts: fine film grain, controlled bloom],
```

## 4.4 UDPM Full Example
```
rule-of-thirds composition with deep framing and soft leading lines,
low-angle perspective with subtle wide-angle 28mm distortion,
camera positioned below chest level shooting upward,
extreme close-up distance (40–60cm) exaggerating foreground proportions,

asymmetrical shoulder drop with a natural forward lean,
relaxed finger curvature and balanced torso articulation,

soft gradient blush and reflective irises,
dense embroidered lace overlays with high thread count,
porous matte skin scattering under warm indoor rim light,
velvet microfibers absorbing side light along fabric folds,

volumetric haze with warm–cool contrast,
painterly rim highlights and controlled subsurface scattering,
aligned interior perspective lines with right-side window backlight,

photorealistic shader with Octane-like reflections,
85mm shallow bokeh falloff with slight chromatic fringe,

cinematic intimate atmosphere,
balanced facial topology and localized lighting softness,

consistent color palette across the frame,
fine film grain and controlled bloom artifacts.
```

---

# 5. Declarative Prompt Mode

## 5.1 Purpose
A cinematic natural-language prompt form that expresses all analytical dimensions in fluent descriptive paragraphs instead of keyword blocks.

## 5.2 Declarative Prompt Structure
A complete declarative prompt is typically 3–6 paragraphs, following:

1. Scene objective and general setting  
2. Camera geometry and framing logic  
3. Subject anatomy and pose geometry  
4. Facial detail and hair rendering  
5. Clothing materials and texture behavior  
6. Lighting model and atmospheric behavior  
7. Environment depth, defocus, and spatial coherence  
8. Art style, shading logic, and rendering methodology  
9. Explicit constraints (for example, “not frontal”, “preserve angle”)  

## 5.3 Declarative Prompt Template
```
Create a detailed [style] illustration of [subject] within [environment].

Use a [camera angle] with [tilt direction], placing the camera at [distance] 
and capturing [lens distortion], ensuring [framing placement] and 
[perspective cues such as ceiling or wall visibility].

Describe the subject’s body with precise geometric behavior: [torso rotation],
[shoulder alignment], [weight distribution], [head tilt], [gaze direction],
and [hand positioning with micro-articulation details].

Render the face with [expression], [eye lighting and gradient], [lash detail], 
[skin shading], and [highlight structure]. Reconstruct hair with 
[length], [material properties], [strand behavior], and [light interaction].

Depict clothing using accurate material physics: [fabric type], [transparency], 
[stitch patterns], [lace or embroidery detail], [reflective or gloss behavior], 
and [deformation according to pose].

Use a [lighting type] that produces [shadow character], [rim or fill light], 
[volumetric effects], and [atmospheric mood].  
Ensure background elements maintain [depth], [defocus logic], 
and [structural coherence].

Follow a [rendering style] characterized by [line weight], [texture handling], 
[shading model], [color dynamics], and [overall tone].  
Preserve all pose, perspective, and stylistic constraints from the analysis.
```

## 5.4 Declarative Prompt Example
```
Create a detailed anime-realistic illustration of a white-haired cat-girl 
standing in a bright sunlit living room.

Use a cinematic low-angle upward shot from below the waist, with the camera 
positioned extremely close (40–60 cm), producing mild wide-angle distortion 
around 28–35mm. The face should appear in the upper third of the frame, with the 
ceiling visible to reinforce the upward geometry.

Her torso leans subtly forward with natural shoulder asymmetry. Her left eye 
remains visible with a soft gradient red tone, long lashes, and a calm gaze. 
Her silky white bob has semi-transparent strands catching luminous sunlight.

She wears a cream floral lingerie top with embroidered pastel flowers and lace 
trim, paired with loose cream nylon pants with subtle gloss and realistic wrinkle 
behavior. Sunlight from large windows creates warm rim lighting, soft abdominal 
shadows, and an airy atmosphere.

Background elements such as curtains, plants, and furniture appear slightly 
defocused, maintaining depth and spatial coherence. Render in anime-realism with 
soft skin scattering, luminous hair lighting, and realistic fabric physics.
```

---

# 6. Stable Diffusion Template
Designed for SD 1.5, SDXL, and similar pipelines.

## 6.1 SD Prompt Template
```
(masterpiece, best quality:1.4), ultra-detailed, hyperrealistic,
[Subject tags], [Quantity], [Gender], [Distinct physical features],
(Attire: ...), (Accessories: ...),
(Pose and Expression: ...),
(Environment: ...),
(Lighting: ...),
(Camera: lens mm, aperture, depth of field),
(Render style or engine),
(Realism effects),
```

## 6.2 SD Negative Prompt
```
(lowres, bad anatomy, bad hands, extra limbs, blurry, watermark)
```

---

# 7. Midjourney Template
Optimized for MJ v5, v6, and Niji.

## 7.1 MJ Prompt Template
```
[Subject and key features], ultra-detailed, cinematic realism,
wearing [attire], with [accessories],
in [environment], under [lighting],
captured with [camera settings] and [lens],
art style of [style] --ar 3:4 --v 6 --style raw
```

## 7.2 Common MJ Parameters
- `--ar` — aspect ratio  
- `--v` — model version  
- `--style` — style intensity  
- `--q` — quality  
- `--s` — prompt strength  

---

# 8. Syntax Notes
- SPM and UDPM favor comma-separated fragments for SD-style engines.  
- Declarative mode uses full sentences and paragraph structure.  
- SD can benefit from weight syntax `(keyword:1.2)`, while MJ and declarative prompts should remain weight-free.  
- All modes must stay consistent with Image Analysis and Safety Protocol outputs.

---

# End of Document
