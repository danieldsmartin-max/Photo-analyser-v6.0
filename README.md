# LumiAudit Studio — Stock Preflight v5.0
## First-Time User Guide

### What LumiAudit does
LumiAudit is a **technical screening and stock-submission preflight tool**. It measures a few image characteristics, displays diagnostic findings, reads available camera metadata, and gives you a checklist for the human checks that stock agencies expect.

**Important:** It does not certify an image, decide whether you own the rights, reliably detect every defect, or predict whether a stock agency will accept a submission. Always check the target agency's current contributor rules.

## 1. Open the app
1. Open `LumiAudit_Stock_Preflight_v5.html` in a modern browser such as Chrome or Edge.
2. The interface uses some external web libraries and fonts, so an internet connection may be needed for every interface feature to load correctly.
3. Your image is processed in the browser by the app; the app states that it does not upload the image to a server. Avoid using sensitive images on shared computers and close the tab when finished.

## 2. Load an image
You can use any of these methods:
- Click **Upload Image** and choose a JPEG, PNG, or WebP file.
- Drop a supported image into the large image area if drag-and-drop is available in your browser.
- Copy an image and press **Ctrl + V** on Windows (or **Cmd + V** on Mac) while the app page is active.
- Use **Landscape**, **Portrait**, or **Clipping Audit** sample presets to explore the interface. Presets are examples, not your own photographs or proof that a real submission will pass.

After loading, check the displayed filename and pixel dimensions. Give the image time to finish processing before interpreting the panels.

## 3. Inspect the image
Use the controls over the image to help review it:
- **Rule of Thirds** grid: check placement and balance.
- **Golden Ratio** grid: try an alternate composition guide.
- **Center Crosshair**: inspect central alignment.
- **Framing Guides**: review crop and framing.
- **Exposure Mask**: highlight areas that may be clipped in bright or dark tones. Treat these as clues; white backgrounds, lights, night scenes and silhouettes can be intentional.
- **Zoom In / Zoom Out / Reset View**: change the viewing scale. Inspect critical areas at **100%** when judging focus and defects.

Composition overlays are visual aids. They do not score artistic quality or establish stock suitability.

## 4. Understand the five tabs

### Telemetry
Shows the overall technical screening score and image measurements. The score is an app-generated screening indicator, **not an agency score, a legal check, or an acceptance prediction**. A high score does not guarantee acceptance; a low score should prompt inspection rather than automatic rejection.

### Report
Shows a summary of exposure/tone, colour-related findings, optical detail and suggested remediation. Read the explanatory text, then confirm every concern against the original image. Automated estimates can be affected by the subject, lighting, image texture, resizing and intended style.

### Metadata
Shows camera and exposure details when they are embedded in the image and can be read. Fields such as camera, lens, aperture, shutter speed, ISO or capture date may be absent. **Missing metadata does not automatically mean the image is unsuitable**, and displayed metadata does not prove ownership or authenticity.

### Export
Provides three actions:
- **Copy Report to Clipboard**: copies the diagnostic summary so you can paste it into notes or a review record.
- **Export Full JSON Audit**: downloads a structured `.json` file containing the technical results, available metadata and Stock QA review status.
- **Download Annotated PNG Snapshot**: downloads a PNG snapshot of the current image view/canvas. Check the result before using it; it is a review aid, not a replacement for the original master file.

### Stock QA
This is the most important tab for stock submissions. It combines technical screening flags with ten manual review gates. Enter the target agency/collection and notes about unresolved issues. Tick each box **only after you have actually verified that item**.

## 5. Read the technical screening flags carefully
The app currently displays these Stock QA checks:

- **Resolution**: compares pixel dimensions against a broad 4-megapixel baseline. This is only a rough baseline; agency and collection requirements vary.
- **Bright clipping proxy**: estimates the share of pixels that are near-white across all RGB channels. Some clipped highlights are intentional.
- **Dark clipping proxy**: estimates the share of pixels that are near-black. Dark scenes and silhouettes may be intentional; inspect whether important shadow detail is lost.
- **Edge-detail proxy**: a relative image-texture/sharpness estimate. It cannot tell whether the intended subject's eyes, product label or other critical detail is actually in focus.
- **Noise / artifacts**: explicitly requires manual inspection. The lightweight browser check does not reliably classify noise, banding, dust, chromatic aberration or compression defects.

Treat “NO FLAG” as “this simple check did not flag it,” not “the image is perfect.” Treat “REVIEW” as a prompt to investigate in context, not proof that the image must be rejected.

## 6. Complete the ten Stock QA gates
Review each item against the full-resolution original and the target agency's rules:

1. **Focus and detail** — inspect the important subject areas at 100%.
2. **Noise and artifacts** — check noise, banding, dust, sensor spots and compression artifacts at 100%.
3. **Retouching** — look for halos, repeated cloning patterns, oversharpening and unnatural edges.
4. **Composition** — review crop, horizon, distractions, framing and whether any claimed copy space is usable.
5. **Rights and ownership** — confirm that you own or have permission to license all relevant content. Pixel analysis cannot establish copyright.
6. **Releases** — obtain model/property releases where required, or verify that editorial-only use is appropriate and permitted.
7. **Brands and protected content** — check logos, trademarks, recognizable products, signage and copyrighted artwork against the intended submission rules.
8. **Authenticity and AI policy** — ensure edits are not misleading and follow the agency's current AI-generated/AI-edited content policy and disclosure rules.
9. **Metadata quality** — prepare an accurate title, description and relevant keywords; avoid spam and unsupported claims. The checklist does not automatically write metadata into an agency portal.
10. **Agency requirements** — verify the current file format, dimensions, colour profile, content policy and collection-specific rules.

The status updates as you check items and technical thresholds. A “checklist complete” message only means the app's gates appear complete; it is **not approval**. Confirm the agency's latest rules and resolve all notes before submitting.

## 7. Recommended workflow for every image
1. Start with the original, highest-quality file available. Keep an untouched master copy.
2. Load the image and confirm the filename and pixel dimensions.
3. Review Telemetry and Report. Write down anything flagged for review.
4. Zoom to 100% and inspect critical subject areas, edges, shadows, highlights and flat areas of sky/walls for defects.
5. Open Metadata and note any useful capture information. Do not invent missing values.
6. Open Stock QA. Enter the target agency/collection and record uncertainties in Reviewer Notes.
7. Complete all ten manual checks honestly. If a rights, release, AI-policy or quality question is unresolved, do not mark it as verified.
8. Make any necessary corrections in your editing software, export a fresh submission copy and re-run the preflight on that final file.
9. Export the JSON audit and/or copy the report if you want a review record. Keep the audit alongside the relevant image/version.
10. Check the agency's current contributor guidelines and upload portal immediately before submission.

## 8. Common questions
**Does a score of 10/10 guarantee acceptance?** No. It is only an app-generated technical screening score.

**Does the app prove I own the image?** No. Keep original files, project files and permissions/releases as appropriate.

**Why is camera information missing?** The file may not contain readable EXIF metadata, or the information may have been removed during editing/export.

**Should I reject every image with clipped highlights or shadows?** No. Decide whether the clipping harms important information or is intentional for the image.

**Can I skip a checklist item if I am unsure?** Do not tick it as verified. Record the uncertainty in Reviewer Notes and investigate first.

**Does the app check all stock agency rules automatically?** No. Agency rules differ and change; you must verify the target agency's current requirements.

## Final principle
**Use LumiAudit to find things to investigate, not to replace careful image inspection, rights documentation, release management or the agency's own submission rules.**
