# Ocadox

**The local AI of the future. Your fans stop screaming.**

A desktop app that runs a coding agent, bots, and a full creative studio on your own PC, with Ollama and other local models. It watches the heat while it works, pacing the work and holding the power down so the fans stay at normal speed. No cloud, no account, no subscription.

**Website:** https://ocadox.com · **Help:** https://ocadox.com/help.html · **What's new:** https://ocadox.com/whats-new.html

## Download

Get the [latest release](https://github.com/kennethyork/ocadox-releases/releases/latest). Ocadox updates itself from here.

| Platform | File |
|---|---|
| Windows 10/11 | `_x64-setup.exe` (or `.msi`) |
| Mac (Apple Silicon) | `_aarch64.dmg` |
| Linux (64-bit) | `.AppImage`, `.deb` or `.rpm` |
| Android 8+ | `_android.apk`: your bots on the go, paired with your PC |

Works with NVIDIA, AMD and Intel graphics, or no graphics card at all (CPU mode).

## What's in it

**Code and automate**
- **Chat and a full coding agent** that reads and edits files, runs commands with your approval, uses git, and browses the web if you allow it. Folder locks and approvals keep it in bounds.
- **Fan guard, power cap and quiet pacing** on everything that uses the graphics card.
- **Bots** with their own chat, folder, model and instructions, which keep working with the window closed.
- **A board for each project** (Trello-style): hand a card to the agent with *Do it*.
- **Git panel:** changes, commits, push and pull, branches, clone and GitHub pull requests.
- **Models your way:** Ollama, LM Studio, llama.cpp and other local servers; or, if you want them, your own Codex or Claude Code, Sign in with OpenRouter, or your own API key.

**Create, on your PC**
- **Images** (Z-Image Turbo), **video** up to 2 minutes (Wan 2.2), and **speech in your own voice** (Qwen3-TTS) with voice-overs.
- **Make music:** songs or background tracks from a description, instrumental or with lyrics, fast or in best quality (ACE-Step 1.5).
- **Edit by transcript**, like Descript: cut words, ums and pauses, captions, studio sound, and overdub in your voice.
- **Long video to Shorts:** the best moments, vertical, with big captions and titles.
- **Dub videos into 10 languages** in your voice.
- **Edit pictures by asking**, remove backgrounds, and upscale 4x.
- **Record websites** or Ocadox itself as videos.
- **AI influencers:** characters with a face that stays the same, a voice, and labelled posts.

**Everyday**
- **Voice dictation** with Whisper, and **dictate anywhere**: a hotkey that types what you say into any app.
- **Meeting notes:** record or drop in a recording; you get a summary, decisions and action items.
- **The Poster:** schedule posts, pictures and videos to Bluesky, Mastodon, Discord and Slack.

## Ocadox Pro

$79 once (launch price, going up to $99 later), lifetime, up to 3 computers. It adds bot routines on a schedule, always-on mode, using an always-on PC's bots from your laptop or phone, checkpoints and undo, agent branches, bots that work through your board, more characters and brands, and more. Try it free for 7 days in the app.

**Buy:** https://kennethyork.gumroad.com/l/wggyib

## About this repository

This repository holds the installers and the website (`docs/`, served at ocadox.com). Releases named `engine-…` are builds of the open-source engines Ocadox downloads (for example acestep.cpp, MIT, for music); the app checks each download against a pinned SHA-256.

Bugs and ideas: [open an issue](https://github.com/kennethyork/ocadox-releases/issues/new). Terms, privacy and licences are on the website.

Ocadox was called Hush before version 0.2.0.
