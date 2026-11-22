---
layout: post
title: "CaptureForge: screenshots, annotation and on-device OCR in one desktop tool"
description: "A native Qt screen-capture workflow with annotation and local Tesseract OCR on Windows and Ubuntu X11."
category: "Screen capture"
permalink: /blog/captureforge-ocr/
---
A screenshot is often just the beginning: crop the image, highlight the important section, then extract text. **[CaptureForge](https://github.com/sacuar/captureforge)** brings those steps together in an independent native Qt desktop project.

## Capture, mark and recognise

CaptureForge includes region capture, an image editor with crop, pen, rotate, flip and undo, and local OCR powered by Tesseract. This workflow can recognise text on-device rather than sending screenshots to a cloud OCR service.

Recognition accuracy depends on source image quality and installed language data. The Ubuntu 24.04 x64 port targets **X11** for region capture; Wayland screen capture remains restricted pending permission-based integration.

## Current availability

Version **1.0.2** is available for Windows and Ubuntu x64 through the [official releases](https://github.com/sacuar/captureforge/releases/tag/v1.0.2). Automated Windows and Ubuntu builds and OCR smoke tests are available, but not every desktop interaction has been manually verified. A representative, verified editor screenshot is still needed.

**Explore:** [Releases](https://github.com/sacuar/captureforge/releases) · [Source and documentation](https://github.com/sacuar/captureforge) · [Report issues](https://github.com/sacuar/captureforge/issues).
