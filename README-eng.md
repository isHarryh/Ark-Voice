Ark-Voice
==========
Arknights Character Voice Assets  
明日方舟语音库

[🇨🇳中文](README.md) **|** **🌎English**

## Overview

This repository collected the voice files of operators from Arknights (CN server), including:

| Directory      | Content             |
| :------------: | :-----------------: |
| `voice`        | Japanese voiceovers |
| `voice_cn`     | Mandarin voiceovers |
| `voice_kr`     | Korean voiceovers   |
| `voice_en`     | English voiceovers  |
| `voice_custom` | Customized voiceovers |

Currently, FX voiceovers (voiceovers with background sound effects) and extra voiceovers (e.g., additional greetings) are not included.

> We will do updates irregularly, you are welcome to send PR to improve the repository. The tool we use to extract the voice files is [ArkUnpacker](https://github.com/isHarryh/Ark-Unpacker) v3.5.

## Download

The total size of the repo exceeds 2.8GB.

- You can browse this repo online via GitHub and selectively download the files you need.
- You can download the entire repo as a ZIP file from GitHub. However, it is recommended to do so only with a stable Internet connection.
- You can clone the repo via Git. If you are familiar with Git, we recommend using Sparse Checkout to download specific files or directories to avoid downloading the entire repo.

## Formats

Each operator's voice files in Arknights (including skin-specific voiceovers) consist of dozens of "voice clips". To facilitate storage, transmission and management, all "voice clips" of an operator are combined into a single "integrated voice file" for storage.

In this repo, voice files are categorized and stored in separate directories by language, consistent with the game's internal resource structure. The `voice_data.json` dataset file in the root directory provides detailed information about each operator's voice data, making it easy to find which languages are available for an operator and the starting timestamp of a specific "voice clip" within an "integrated voice file" for that language.

All audio files are encoded in OGG Vorbis format (mono, 44100Hz, 16bit), balancing efficient compression and fidelity to the game's original audio quality. The average size of an operator's "integrated voice file" is approximately 2.1MB.

## Breaking Changes

- Jan.2025: Repo established.

## Copyright Notice

The copyright of the resources in the repository belongs to [**HYPERGRYPH Co.,Ltd.**](https://www.hypergryph.com) Please do use the resources in a proper way.
