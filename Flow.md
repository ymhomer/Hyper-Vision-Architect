# Visual Generation System Flow

## STEP 0 — Input Handling
The system supports:
- Single-image input (default)
- Multi-image input, each analyzed independently with optional fusion modes (A/B/C/custom)
- Text-only prompt creation, enhanced using all analytical frameworks

User intent determines prompt mode selection:
- Requests for "simple", "clean", "MJ-style", or minimal wording → SPM (Simple Prompt Mode)
- Requests for "accurate", "match lighting/angle", "replicate", "high fidelity", "SDXL/Flux/ComfyUI" → UDPM (Ultra-Detail Prompt Mode)

If unclear, the system may politely ask which mode the user prefers.

---

## STEP 1 — Image Analysis (Required)
Use Image_Analysis_Framework.md to perform full-spectrum analysis:

- Apply all 24 analytical dimensions
- Output structured Chinese analysis
- Identify composition, perspective geometry, pose micro-structure, camera distance, lighting physics, color theory, materials, micro-textures, style mechanics, environmental cues, cultural signatures, and consistency markers
- This analysis becomes the **authoritative data source** for prompt construction and safety handling

No identity inference is ever performed.

---

## STEP 2 — Safety Validation (Required)
Use Safety_Protocols.md to evaluate safety conditions:

- Determine risk level (0–4)
- Distinguish allowed / moderated / prohibited content
- Apply adult stylization when age is visually ambiguous
- Prevent misclassification of stylized or CJK features
- Validate perspective & distance to avoid angle-related false positives
- Validate scene continuity to avoid misinterpretation of lighting, furniture, or environment
- Apply content-adjusted substitution logic when necessary
- If Level 2–3 → present the Correction Menu and apply only the user-selected option

Safety adjustments must preserve:
- Pose
- Lighting
- Style
- Composition
- Overall artistic intent

---

## STEP 3 — Prompt Generation
Use Prompt_Structure_Template.md to create English prompts.

### SPM — Simple Prompt Mode
Used when:
- User requests compact, readable prompts  
- Midjourney, Niji, or general lightweight generation  
- High realism or reconstruction is **not** required  

Behavior:
- Summarize key analytical findings  
- Maintain pose, lighting, and stylistic cues  
- Output a concise but faithful prompt  

### UDPM — Ultra-Detail Prompt Mode
Used when:
- The user requests maximal fidelity or reconstruction accuracy  
- The target engine is SDXL/Flux/ComfyUI/A1111  
- The user emphasizes angle, lighting, geometry, or texture accuracy  

Behavior:
- Convert **all 24 analytical dimensions** into structured prompt blocks  
- Use Camera Geometry, Pose Geometry, Material Micro-texture, Style Mechanics, and Distance & Perspective blocks  
- Produce a dense, high-precision prompt representing the full scene  
- Integrate safety-adjusted substitutions when applicable  

Both modes must remain faithful to the analytical output of Step 1.

---

## STEP 4 — Interactive Refinement
Offer refinement options after prompt generation:

- Detail or micro-texture enhancement  
- Lighting reinterpretation or stylization shifts  
- Tone, color, or palette adjustments  
- Multi-image consistency tuning for style unification  
- Controlled variants or partial reworks  
- Optional rebalancing between realism and stylization  

The refinement phase is always user-driven; no changes occur without confirmation.

---

## STEP 5 — Export Feedback (/export)
Upon user request, the system can export:

- Full analytical breakdown  
- All safety decisions and applied corrections  
- SPM and/or UDPM prompt outputs  
- Any refinement history  
- Complete session in Markdown or JSON format  

This allows the user to preserve the generation workflow for reference or iteration.

# End of Document
