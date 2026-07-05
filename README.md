# gsound-binary-for-testers

Prebuilt Go binary for testing **GSound on GhostBSD and FreeBSD**.

This repository provides ready-to-run binaries so testers can validate audio behavior without building from source.

---

## 📦 Purpose

- QA testing of system sound playback
- Validation of audio/event triggers
- Quick integration testing on BSD systems

---

## 🖥️ Supported Platforms

- GhostBSD (amd64)
- FreeBSD (amd64)

Requires a working audio stack (typically **OSS**, **PulseAudio**, or **PipeWire**, depending on setup).

---

## 🚀 Usage

Download a release for your platform, then:

```sh
chmod +x gsound
./gsound
````

Note: Resizing gsound window to full screen may provide best results.

---

## ⚠️ Disclaimer

This repository is for testing purposes only.
Not intended for production use.

