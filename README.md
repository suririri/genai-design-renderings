# AI-generated design renderings — Study 1 image set

Supporting images for the manuscript *AI-generated Images in Design Education: Performance,
Perception, and Cognitive and Visual Mechanisms*.

Prompts are **not** reproduced here. They are given in full in **Appendix 3** of the manuscript,
and every file in this repository is named so that it maps directly onto a row of that appendix.

## Contents

| Folder | Tool | Files |
|---|---|---|
| `images/01_source_model/` | 3D model viewport captures, one per camera view | 15 |
| `images/03_sketchup_diffusion/` | SketchUp Diffusion (Appendix 3.1) | 75 |
| `images/04_midjourney/` | Midjourney (Appendix 3.2) | 75 |
| `images/05_stable_diffusion/` | Stable Diffusion (Appendix 3.3) | 75 |
| `images/06_lora/` | Stable Diffusion with a fine-tuned LoRA model (Appendix 3.4) | 75 |
| `images/07_gpt4o/` | GPT-4o (Appendix 3.5) | 72 |

Total: **387** images.

## Filenames

    <theme>_<tool>_<camera>_<output>.jpg      e.g.  wetland-park_SUD_1_1.jpg
    <theme>_camera_<n>.jpg                    for the source models

The five themes are the five site briefs used in Study 1, and they are the same labels used in
Appendix 3:

| Folder prefix | Appendix 3 theme |
|---|---|
| `wetland-park` | Wetland park |
| `urban-riverfront` | Urban riverfront district |
| `prairie-equestrian` | Prairie equestrian site |
| `residential-neighborhood` | Residential neighborhood |
| `sports-complex` | Sports complex and creek |

So `images/06_lora/sports-complex_LoRA_2_3.jpg` is the image listed in Appendix 3.4 under theme
"Sports complex and creek", Camera 2, image `LoRA_2_3`.

## Coverage

The Study 1 design is 5 themes x 3 camera views x 5 outputs x 5 tools = **375** AI-generated
images. This repository publishes **372**. Three files are absent from the source data and could
not be recovered:

- `07_gpt4o/wetland-park_GPT_1_1`
- `07_gpt4o/wetland-park_GPT_1_2`
- `07_gpt4o/urban-riverfront_GPT_2_4`

Every other tool folder is complete at 15 images per theme, 75 per tool. Raw generation batches,
alternates, and exploratory outputs present in the working folders are not published; only the
images belonging to the documented design are included.

## De-identification

Images are grouped by design theme, not by student. No participant name appears in any filename,
folder name, or file. **All image metadata was stripped** — the source PNGs carried EXIF/XMP
fields including an `Author` value naming the institutional account, Midjourney Job IDs, and IPTC
image GUIDs. Published files carry no metadata of any kind.

`survey/survey_responses_deidentified.csv` holds the Study 3 survey (45 respondents). The export's
`Timestamp`, `Email Address`, name, and enrolled-course columns were dropped and rows were
shuffled so that row order does not recover submission order. The years-of-experience question
was free text and several answers named the respondent's degree programme or gave dates; it has
been replaced by a numeric column, `years_since_first_design_project`; two non-numeric answers
were coded by the authors.

## Image processing

JPEG, quality 92, 4:4:4 chroma, longest side capped at 1920 px; smaller originals were not
upscaled. `manifest.csv` records the theme, tool, appendix image ID, original filename, and both
original and published pixel dimensions for every file. These are derived files for browsing and
reference; lossless originals are not in this repository.

## Human subjects

Studies 1 and 3 were approved by the Institutional Review Board and all participants gave informed
consent. The renderings are student coursework, published with the participants' agreement.
