# Lumen Capture

A screen and audio recorder for Windows 11 that can also **stream live to YouTube**. It records your
screen, a window or a region to MP4/MKV using your graphics card's hardware encoder. System audio and
your microphone are mixed in, and you can stream while you record.

**[⬇ Download the latest release](https://github.com/ICBizLabs/Lumen-Capture/releases/latest)**

| Download | Use it when |
| --- | --- |
| `LumenCapture-<version>-x64-Setup.exe` | You want a normal install: Start-menu shortcut and uninstaller. |
| `LumenCapture-<version>-x64-portable.zip` | You don't want to install. Unzip it anywhere and run `LumenCapture.exe`. |

Both are code-signed by ICBizLabs and need nothing else installed; .NET and the Windows App SDK are
included.

## Features

- **Capture** a full display, a single window, or a region you draw, with or without the cursor.
- **Record** to MP4 or MKV with hardware H.264/HEVC (NVIDIA, Intel or AMD). System audio and
  microphone are mixed in. Includes pause/resume, a countdown and auto-stop.
- **Live stream** to YouTube (RTMPS) or any custom RTMP server, at the same time as a recording.
- **Overlays:** webcam picture-in-picture, watermark text, an elapsed-time clock, and a privacy blur
  region. Drag and resize them right on the live preview.
- **Screenshots** (PNG), a built-in **library** to play, open or delete recordings, and **global
  hotkeys:** Ctrl+Alt+F9 record, F10 pause, F11 screenshot.
- **View modes:** Studio, Compact, and an always-on-top Mini-bar.

## Requirements

- Windows 11 (Windows 10 version 2004 or later should also work)
- 64-bit (x64) PC
- A GPU with a hardware video encoder is recommended. A software encoder is used otherwise.

## Streaming to YouTube

1. In **YouTube Studio → Create → Go live → Stream**, copy your **stream key**. The first time,
   YouTube can take up to 24 hours to enable live streaming on your channel.
2. In Lumen Capture, open **Settings → Live streaming** and paste the key. It is stored encrypted for
   your Windows account.
3. On the **Capture** page, pick what to share and click **Go Live**.
4. Your stream shows up in YouTube Studio within about 10–20 seconds. Set the title and visibility
   there, and click *Go live* (or turn on auto-start).

## Support

Recordings are saved to `Videos\Lumen Capture` by default; you can change this in Settings.
For questions, visit [i-b.biz](http://i-b.biz).

---

Copyright © 2026 ICBizLabs. All rights reserved. Lumen Capture is distributed as binaries only.
Third-party components and their licenses are listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
