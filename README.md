<h1 align="center">Torus</h1>

<p align="center"><b>Spring Reverb Engine</b> by <a href="https://lissajouslabs.com">Lissajous Labs</a></p>

<p align="center">
  <img src="img/torus.png" alt="The Torus plugin interface" width="560">
</p>

<p align="center">
  <b>Download:</b>
  <a href="https://lissajouslabs.com/download/torus/macos">macOS (.dmg)</a> ·
  <a href="https://lissajouslabs.com/download/torus/windows">Windows (.zip)</a> ·
  <a href="https://lissajouslabs.com/download/torus/linux">Linux (.zip)</a>
</p>

<p align="center">
  <a href="../../releases">All releases</a> ·
  <a href="https://lissajouslabs.com/faq">FAQ</a> ·
  <a href="SUPPORT.md">Support</a>
</p>

A stereo spring reverb with two engines: a physical model of the spring tank
and a lighter parametric one. Free beta for macOS, Windows and Linux.

This repository holds release builds only; the source is private.

## Formats

| Platform | File | Contains |
|---|---|---|
| macOS 11+ (universal) | `Torus-<version>-macOS.dmg` | VST3, AU, CLAP, Standalone |
| Windows 10+ (x64) | `Torus-<version>-Windows.zip` | VST3, CLAP, Standalone |
| Linux (x64) | `Torus-<version>-Linux.zip` | VST3, CLAP, Standalone |

## Installing

**macOS.** Open the DMG and drag each item onto the folder link beside it:
`Torus.vst3` to *VST3 Plug-Ins*, `Torus.component` to *AU Plug-Ins
(Components)*, `Torus.clap` to *CLAP Plug-Ins* and `Torus.app` to
*Applications*. If the CLAP folder doesn't exist yet, create it with
`sudo mkdir -p /Library/Audio/Plug-Ins/CLAP`. The beta isn't signed yet: the
DMG's `Install.txt` has the one-line command that lets macOS open it.

**Windows.** Copy `Torus.vst3` to `C:\Program Files\Common Files\VST3` and
`Torus.clap` to `C:\Program Files\Common Files\CLAP`. `Torus.exe` is the
standalone app.

**Linux.** Copy `Torus.vst3` to `~/.vst3` and `Torus.clap` to `~/.clap`.
`Torus` is the standalone app.

Rescan plug-ins in your DAW afterwards. Torus checks lissajouslabs.com for new
releases (macOS and Windows) and lights its help icon when one is out.

## Help

- Install questions and the unsigned beta: the [FAQ](https://lissajouslabs.com/faq).
- Bugs: [open an issue](../../issues/new/choose).
- Anything else: [SUPPORT.md](SUPPORT.md). Security problems: [SECURITY.md](SECURITY.md).

The beta is free to use under the [Lissajous Labs terms](https://lissajouslabs.com/terms).
