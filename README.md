# mobile-release

A [Claude Code](https://claude.com/claude-code) skill, companion to `runway`, for the Flutter
part of shipping to the App Store and Google Play: version/build-number bumps, signing without
keys ever touching the repo or the chat, obfuscated release builds, the store review checklist
(permissions, privacy manifest, data-safety form), and staged rollout.

## Install

```
/plugin marketplace add MubiZero/mobile-release
/plugin install mobile-release@mobile-release
```

## What it does

See [skills/mobile-release/SKILL.md](skills/mobile-release/SKILL.md) for the flow, and
`references/signing.md` / `references/review-checklist.md` for the detail.

## License

[MIT License](LICENSE) · Copyright (c) 2026 MubiZero
