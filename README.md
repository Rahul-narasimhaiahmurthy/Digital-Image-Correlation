# Digital-Image-Correlation

TurboTrans - Digital Image Correlation to Detect Crack Propagation using Python

## Note: Information provided is confidential and limited since the project is undergoing.

## Overview
The study uses digital image correlation to evaluate crack propagation and deformation from the images captured several intervals and at defined loading intervals. The main objective is to analyse fatigue loading and failure of the material under mixed loading conditions. The crack propagation is estimated using strain field, identifying crack positions, and evaluating crack growth sequence. 

## Objective
- Estimate strain fields from images captured on front and rear side of the specimen.
- Identify crack position at different loading intervals.
- Determine crack-length evolution and propagation direction.
- Study the influence of DIC parameter selection such as subset, step size, search radius on the analysis result.
- Support mixed-mode crack-propagation assessment.

## Work flow
```text
Input images at loading intervals
            ↓
Image pre-processing and region-of-interest selection
            ↓
Digital Image Correlation analysis
            ↓
Displacement and strain-field estimation
            ↓
Crack-position extraction
            ↓
Crack-length and propagation-direction analysis
            ↓
Parameter sensitivity comparison
```
