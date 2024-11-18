# Age Progression: 10 to 40 Years

<img src="images/age-transition-10-to-40-full.jpeg" alt="Age Progression 10 to 40 Years">

## Overview
The Age Progression tool generates a visual sequence that simulates the aging process from childhood (10 years) to adulthood (40 years). This workflow utilizes face analysis, image-to-image transformations, and frame interpolation for a smooth, realistic aging transition.

## Features
- **Face Analysis** using 1019-Face-Analyzer to determine facial features.
- **Image Transformation** with Flux Img-to-Img and Stable Diffusion models to age the face realistically.
- **Frame Interpolation** to generate a continuous transition across different ages.

## Inputs

### 1. image
- **Type:** File 
- **Description:** The initial image of the person to be used as a basis for age progression.

### 2. child_gender_boy_or_girl
- **Type:** Text 
- **Description:** Gender of the child in the input image. Options are "boy" or "girl."

## Example

### Input
- **Image:** 

<img src="https://storage.googleapis.com/magicpoint/models/women.png" alt="Age Progression Input" width="300">

- **child_gender_boy_or_girl:** girl

### Output
[Output Video](https://storage.googleapis.com/magicpoint/github-outputs/age-progression-10-to-40-output.mp4)

If you encounter an error, you can join our <b><a href="https://discord.com/invite/yzZD4ZxBPt" target="_blank">Discord</a></b> server.
