---
layout: default
title: Pixel Cluster
parent: Actions
nav_order: 12
---

# Pixel Cluster
This tool uses NumPy to check the values of every single pixel in every file in the selected folder. It may take a little bit of time, but since it is using multiprocessing, it should be quicker than expected.

## Potential Uses
### Tier 2 QC Automation:
- This action only targets U Files, so redundancy is avoided.
- Run Pixel Cluster on your finished output folder of TIF files
    - Select how large of a pixel cluster size will fail the file
    - Default is 3x3, but this is very strict. 5x5 or 9x9 may be better depending
- The final generated HTML report that opens in Chrome will have a Toggle Overlay button in the top right
    - Use this toggle button to show or hide the clipped areas, highlights being red and shadows being blue
    - Determine if the areas are significant enough to revisit the file

### QC Validation
- Use the same steps as above, just to validate manual QC
- Crosscheck with the sampled files that were manually QC'ed