# AI-generated design renderings — Study 1 AI image Generation

Supporting images for the manuscript *AI-generated Images in Design Education: Performance,
Perception, and Cognitive and Visual Mechanisms*.

The prompts are in **`Study 1 AI Image Generation/Prompts.docx`**, the same appendix that appears in
the manuscript, and every file in this repository is named so that it maps directly onto a row of it.

## Contents

| Folder | Tool | Files |
|---|---|---|
| `Study 1 AI Image Generation/01_source_model/` | 3D model viewport captures, one per camera view | 15 |
| `Study 1 AI Image Generation/03_sketchup_diffusion/` | SketchUp Diffusion (Appendix C.1) | 75 |
| `Study 1 AI Image Generation/04_midjourney/` | Midjourney (Appendix C.2) | 75 |
| `Study 1 AI Image Generation/05_stable_diffusion/` | Stable Diffusion (Appendix C.3) | 75 |
| `Study 1 AI Image Generation/06_lora/` | Stable Diffusion with a fine-tuned LoRA model (Appendix C.4) | 75 |
| `Study 1 AI Image Generation/07_gpt4o/` | GPT-4o (Appendix C.5) | 75 |

Total: **375** AI-generated images.

## Filenames

    <theme>_<tool>_<camera>_<output>.jpg      e.g.  wetland-park_SUD_1_1.jpg
    <theme>_camera_<n>.jpg                    for the source models

The five themes are the five site briefs used in Study 1, and they are the same labels used in
Appendix 3:

| Folder prefix | Appendix C theme |
|---|---|
| `wetland-park` | Wetland park |
| `urban-riverfront` | Urban riverfront district |
| `prairie-equestrian` | Prairie equestrian site |
| `residential-neighborhood` | Residential neighborhood |
| `sports-complex` | Sports complex and creek |

## Coverage

The Study 1 design is 5 themes x 3 camera views x 5 outputs x 5 tools = **375** AI-generated
images. Every other tool folder is complete at 15 images per theme, 75 per tool. Raw generation batches,
alternates, and exploratory outputs present in the working folders are not published; only the
images belonging to the documented design are included.

## Image processing

JPEG, quality 92, 4:4:4 chroma, longest side capped at 1920 px; smaller originals were not
upscaled. `manifest.csv` records the theme, tool, appendix image ID, original filename, and both
original and published pixel dimensions for every file. These are derived files for browsing and
reference; lossless originals are not in this repository.

