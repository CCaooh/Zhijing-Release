# Zhijing

Zhijing is a Windows utility for screenshots, annotations, scrolling capture, OCR, translation, and screen recording.

This repository distributes official binaries and signed update manifests only. The proprietary Zhijing source code is not published here.

## Highlights

- Multi-monitor and high-DPI region capture
- Vector annotations, text, mosaic, blur, and highlighter
- Automatic and manual vertical/horizontal scrolling capture
- Pin-to-screen, history, and non-destructive re-editing
- Local and online OCR/translation
- MP4/GIF region and window recording
- Live annotations during recording

## Download

1. Open Releases and download `zhijing-1.0.0-windows-x64.zip`.
2. Extract it to a writable folder.
3. Run `织境.exe`.

Version 1.0.0 is currently distributed without a commercial Authenticode certificate. Windows may show an unknown-publisher warning on first launch. Download only from the official Release and verify the SHA-256 value.

## SHA-256

```text
3E10347B17B4327AAE56026E71D93A2769E7140BCEDBFEB07F17B5643FC1BF31  zhijing-1.0.0-windows-x64.zip
```

The built-in updater also validates an ECDSA-signed manifest, file size, and SHA-256 before installation.

## Requirements

- 64-bit Windows 10 or Windows 11
- Online OCR/translation providers require user-supplied service credentials

## Open-source dependencies

Zhijing itself remains proprietary. The official Release includes a separate corresponding-source archive for the distributed Qt/FFmpeg components and third-party license notices. It does not contain Zhijing source code.

## Feedback

Please use Issues for reproducible bug reports. Never post API keys, access tokens, private screenshots, OCR content, or logs containing personal information.

