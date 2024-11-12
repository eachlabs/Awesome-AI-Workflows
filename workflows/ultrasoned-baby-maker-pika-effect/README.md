# Ultrasound Baby Maker + Pika Effect

<img src="images/ultrasound-baby-maker-pika-effect-full.jpeg" alt="Ultrasound Baby Maker + Pika Effect" />

## Overview

The **Ultrasound Baby Maker + Pika Effect** flow generates a unique video representation of an unborn baby by analyzing images of the parents and an ultrasound scan. It enhances the visuals through face analysis, image enhancement, and a creative filter called the Pika Effect, providing a personalized and artistic final output.

## Features

- **Face Analysis**: Uses the `Face Analyzer` tool to analyze both the mother's and father's facial features.
- **Image Enhancement**: Improves the quality of the ultrasound image using the `Photo Enhancer` (GFPGAN).
- **Flux Dev Processing**: Processes the data for video generation with enhanced visuals.
- **Pika Art Effect**: Adds an artistic touch to the final video through the `Pika Art Community` tool.
- **Customizable Inputs**: Accepts specific images of the parents and ultrasound scan to create a personalized video output.



## Inputs

### 1. `mom_image`
- **Type**: Image File
- **Title**: Mother's Image
- **Component**: Input field

**Description**: Upload an image of the mother for facial analysis. This image contributes to the final video by analyzing her facial features.

### 2. `dad_image`
- **Type**: Image File
- **Title**: Father's Image
- **Component**: Input field

**Description**: Upload an image of the father for facial analysis. This image is used alongside the mother's image to generate a composite representation in the final video.

### 3. `ultrasound_image`
- **Type**: Image File
- **Title**: Ultrasound Image
- **Component**: Input field

**Description**: Upload the ultrasound image of the baby. This image will be enhanced and used as the primary visual component of the video.

## Outputs

### Video Output
The final output is a video that combines the parental features, enhanced ultrasound image, and the Pika Effect for an artistic touch. This video can be saved and shared as a memorable keepsake for expectant parents.

## Example

### Input
- **Mother's Image**:

<img src="https://storage.googleapis.com/magicpoint/models/women.png" alt="Woman Image" width="300">

- **Father's Image**:

 <img src="https://storage.googleapis.com/magicpoint/models/man.png" alt="Man Image" width="300">

- **Ultrasound Image**:

  <img src="https://storage.googleapis.com/magicpoint/github_inputs/ultrasoned-photo-input.webp" alt="Ultrasound Image" width="200">

### Output
- **Generated Video**:
  [Click to video](https://storage.googleapis.com/magicpoint/github-outputs/ultrasound-baby-maker-pika-effect-output.mp4)

## Conclusion

If you encounter an error, you can join our <b><a href="https://discord.com/invite/yzZD4ZxBPt" target="_blank">Discord</a></b> server.

