## 🇯🇵 日本語の案内はこちら → [README（日本語）](README.ja.md) ／ [インストール方法（日本語）](https://kadoya2005.github.io/VPT39-manual/install.html) ／ [マニュアル（日本語）](https://kadoya2005.github.io/VPT39-manual/)

# VPT39 Manual

> ### 📘 Manual: **https://kadoya2005.github.io/VPT39-manual/en/**
> ### ⬇ How to install (step by step): **https://kadoya2005.github.io/VPT39-manual/en/install.html**
> ### 💾 Download VPT39: **https://github.com/kadoya2005/VPT39** (green "Code" button → "Download ZIP")

**VPT39** is a video player made especially for projection mapping. It is designed to be easy to use for media and interactive art works that use projectors, live shows and similar events.

The control panel can be switched between Japanese and English with the 日本語 / English button in the top bar (the choice is remembered).

> VPT39 is an unofficial tool inspired by VPT (VideoProjectionTool) by HC Gilje. It is not affiliated with VPT in any way.

## Features of VPT39 (improvements over VPT8)

Note: tested on Windows 11.

1. **Any number of outputs**
   You can add as many output windows as you like. You can use as many monitors and projectors as your graphics card can connect, with a different picture and different mapping for each output.
2. **Mapping from a phone**
   You can adjust the position of the projected picture (four-corner mapping) from a phone while standing in front of the screen. No app to install: just scan a QR code.
3. **Synchronized playback on several outputs**
   One video can be shown on several outputs at the same time, perfectly in sync. Clips lined up for each song or scene can be started from the beginning on all layers at once with one button ("Play column").
4. **Window capture**
   Any window on the same PC can be used directly as media, even from apps that do not support Spout (Zoom, a browser and so on). Receiving from Spout (TouchDesigner, Processing and so on) is also supported.
   Note: window audio cannot be captured at the moment (picture only).
5. **Wide picture (virtual big monitor)**
   Connect two or more projectors or monitors to make one wide picture (e.g. 1920×2 = 3840×1080). Overlapping areas are blended smoothly, and the brightness can be matched at each seam. No splitter or other extra hardware is needed.

### Other features

- **Audio mixer**: plays the sound of the videos on all layers at the same time, with volume and mute per layer and per output. The sound also crossfades when you switch clips.
- **Capture board input**: brings in the picture and sound of another PC with low latency. Several units of the same model can be told apart.
- **Photo wall**: shows the photos in a folder automatically, newest first. You can also line up images from your media and show them in a fixed order.
- **Move photos in real time**: even during the show, you can move photos and videos with the arrow keys or a phone to adjust their position.
- **Prepare on another PC**: if you set the "Show resolution" for each output, the shapes you adjust in a small window can be used as they are in the show.
- **Setup files**: for each venue or show, save the running order, mapping, volume and outputs together and switch between them.
- **Safeguards for the show**: auto-save, output windows do not close with ×, outputs open fullscreen on the same display at the next start, BLACKOUT button.
- **Browser control panel**: tabs can be split into separate windows, and it comes with a manual whose numbers match the screen.
- **Media formats**: animated GIF, APNG and WebP, and transparent PNG can be used as they are.
- **Free, MIT license**: written in Python, so anyone can modify it.

### What it cannot do yet, compared with VPT8

- No mesh warping (fine correction for curved surfaces and so on). Mapping uses the four corners only.
- No masks (cutting out part of the picture).
- Cannot be controlled from external hardware such as OSC or MIDI controllers, LFOs or Arduino sensors.
- Cannot send video to other apps with Spout or Syphon.
- Windows only; does not run on Mac or Linux.
- Cannot capture audio from window capture.

## Manuals

| | |
|---|---|
| [Screen guide (view in the browser)](https://kadoya2005.github.io/VPT39-manual/en/) | Explains each part of the control panel |
| [Quick start (PDF, 2 A4 pages)](en/quickstart.pdf) | One sheet to keep at hand during the show |
| [How it works (PDF, 2 A4 pages)](en/concept.pdf) | How the picture gets to the screen, and the ideas behind it |
| [Detailed guide (PDF)](en/guide.pdf) | Everything from installation to the show |

This repository publishes only the manuals (the program itself is not included).
