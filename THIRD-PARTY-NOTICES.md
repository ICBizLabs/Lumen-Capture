# Third-party notices

Lumen Capture includes the following third-party software.

## FFmpeg (live streaming)

Live streaming uses an unmodified build of **FFmpeg** (<https://ffmpeg.org>). It ships as separate
files in the `ffmpeg\` folder next to `LumenCapture.exe` and runs as a separate process.

- **Version:** FFmpeg n8.1.3, the LGPL "shared" Windows build from
  [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds), release `autobuild-2026-10-03-18-14`.
- **License:** GNU Lesser General Public License v3. The full text is in
  [FFMPEG-LICENSE.txt](FFMPEG-LICENSE.txt), and is also included as `ffmpeg\LICENSE.txt` in every
  download.
- **Source code:** FFmpeg's source is at <https://ffmpeg.org/download.html> and
  <https://git.ffmpeg.org/ffmpeg.git> (tag `n8.1.3`). The build scripts for this exact build are at
  <https://github.com/BtbN/FFmpeg-Builds>.
- **Replacing the DLLs:** FFmpeg is dynamically linked, so you can swap in your own compatible build
  of `ffmpeg.exe` and its DLLs in the `ffmpeg\` folder.

## Other components

| Component | License |
| --- | --- |
| .NET runtime | MIT |
| Windows App SDK / WinUI 3 | Microsoft Software License Terms (Windows App SDK) |
| NAudio | MIT |
| Vortice.Windows (Direct3D11, Direct2D1, DXGI, MediaFoundation) | MIT |
| SharpGen.Runtime | MIT |
| CommunityToolkit.Mvvm | MIT |
| Microsoft.Extensions.DependencyInjection | MIT |
| Serilog, Serilog.Sinks.File, Serilog.Sinks.Debug | Apache-2.0 |
