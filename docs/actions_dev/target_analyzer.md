---
layout: default
title: Target Analyzer
parent: Actions for Devs
nav_order: 13
---

# Target Analyzer
This tool uses a combination of Computer Vision  and OCR to "read" the Golden Thread ISO Object-Level Target by Don Williams used in the DIS workflow. It checks for white point, neutrality, and optionally black point.

## Potential Uses
### Tier 2 QC Automation:
- Use DT NExus to create variants that are cropped to target
- Export into a subfolder in default output with the U File recipe
- Run Target Analyzer on the created folder

### QC Validation
- Use the same steps as above, just to validate manual QC
- Crosscheck with the sampled files that were manually QC'ed