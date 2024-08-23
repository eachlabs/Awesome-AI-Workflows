
<!-- ABOUT THE PROJECT -->



# Ai Dubbing With Lipsync

<div align="center">
    <img src="images/ai-dubbing-with-lip-sync-full.jpeg">
</div>

## Overview

The AI Dubbing with Lipsync model is designed to automatically synchronize lip movements in a video with a target language audio track. Using advanced deep learning techniques, the model provides seamless and realistic dubbing, making it an excellent tool for multilingual video production, content localization, and entertainment.

## Features
- **Seamless Language Synchronization**
- **High-Quality Output**
- **Customizable Language Options**

## Use Cases
- Film and TV dubbing
- Content localization
- Educational content

# AI Flow Execution Inputs

This document provides explanations for the execution inputs used in your AI model.

## Inputs

### 1. `video`
- **Type:** String
- **Title:** Video
- **Component:** File

**Description:** This input represents a video file that the model will process. The file should contain the video that the model will analyze and synchronize with the audio. Supported file formats include `.mp4`

### 2. `language`
- **Type:** String
- **Title:** Language
- **Component:** Input

**Description:** This input specifies the target language for dubbing. The model will use this input to select the appropriate audio track and synchronize the lip movements accordingly. The language should be entered as a standard language code (e.g., `en` for English, `es` for Spanish).

**Language Available:** `en`,`es`,`fr`,`de`,`it`,`pt`,`pl`,`tr`,`ru`,`nl`,`cs`,`ar`,`zh`,`hu`,`ko`,`hi`

## Usage

These inputs are required parameters for running the model. Providing complete and accurate inputs ensures that the model operates correctly and yields expected results.

- **Video:** Upload the video file that you wish to dub.
- **Language:** Enter the desired language code for dubbing.

When these inputs are provided, the model will process the video and synchronize the audio in the target language to match the lip movements, delivering a natural and professional dubbed video.

                                                                                                                                                                           
## Examples

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: flex;
            flex-direction: row;
            align-items: flex-start;
            margin-bottom: 20px;
            gap: 20px;
        }
        .column {
            display: flex;
            flex-direction: column;
            flex: 1;
        }
        .video-section video {
            width: 300px; 
            height: 200px; 
            margin-bottom: 10px; 
        }
        .video-section a {
            text-decoration: none;
            color: #007bff;
            margin-top: 10px;
        }
        .header {
            font-weight: bold;
            margin-bottom: 10px;
        }
        hr {
            width: 300px; 
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
            .video-section video {
                width: 100%;
                height: auto;
            }
            hr {
                width: 100%; 
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="column">
            <div class="header">Input</div>
            <hr>
            <div class="video-section">
                <h3>Video</h3>
                <video controls volume="1.0">
                    <source src="https://storage.googleapis.com/magicpoint/github_inputs/gu%CC%88thub-input-ai-dubbing-with-lipsync.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <a href="https://storage.googleapis.com/magicpoint/github_inputs/gu%CC%88thub-input-ai-dubbing-with-lipsync.mp4" target="_blank">
                    Video Input
                </a>
            </div>
            <div class="language-section">
                <h3>Language</h3>
                <p>es</p>
            </div>
        </div>
        <div class="column">
            <div class="header">Output</div>
            <hr>
            <div class="video-section">
                <h3>Video</h3>
                <video controls volume="1.0">
                    <source src="https://storage.googleapis.com/magicpoint/github-outputs/github-output-ai-dubbing-with-lipsync.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <a href="https://storage.googleapis.com/magicpoint/github-outputs/github-output-ai-dubbing-with-lipsync.mp4" target="_blank">
                    Video Output
                </a>
            </div>
        </div>
    </div>
</body>
</html>





















