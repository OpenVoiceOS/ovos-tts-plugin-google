## Description
Mycroft TTS plugin for [gTTS](https://github.com/pndurette/gTTS)

### Disclaimer

[gTTS](https://github.com/pndurette/gTTS) is *not* affiliated with Google or Google Cloud. Breaking upstream changes *can* occur without notice. This project is leveraging the undocumented [Google Translate](https://translate.google.com) speech functionality and is *different* from [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech/).

## Install

`pip install ovos-tts-plugin-google-tx`

## Configuration

```json
  "tts": {
    "module": "ovos-tts-plugin-google-tx"
  }
 
```

### Extra options

you can override the language, otherwise system lang is used

```json
  "tts": {
    "module": "ovos-tts-plugin-google-tx",
    "ovos-tts-plugin-google-tx": {
      "lang": "es"
    }
 
```


