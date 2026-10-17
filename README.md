# Clipvelle: Video to Audio

<img src="docs/assets/icon.png" width="112" alt="Clipvelle film-to-sound icon">

**Your video. Just the audio.** A focused native iPhone and iPad utility that extracts a chosen audio track from your own local video, lets you listen and trim one segment, then exports a named M4A or WAV file.

**Status · October16,2026:** In development. Apple has accepted the name and app record. Not submitted or released. Core native extraction tests passed; production QA and StoreKit checks are ongoing. This public showcase contains product documentation and visuals. Commercial source is maintained separately in a private repository.

## Product

- Photos and Files import; original media remains untouched.
- Explicit selection when a video has multiple audio tracks.
- Preview and inspectable start/end times.
- Compact AAC/M4A and uncompressed PCM/WAV export with actual duration and file size.
- Dedicated iPad source list and inspector.
- Free single-video exports; Lifetime Pro adds batch extraction and reusable export presets. No subscription.

## Engineering

Swift, SwiftUI, AVFoundation, PhotosUI, UniformTypeIdentifiers and StoreKit2. Universal iPhone/iPad with an iOS15 deployment target and availability fallbacks. Streaming reader/writer conversion, coordinated security-scoped imports, cancellation cleanup, durable source/export ownership and verified StoreKit entitlements. XCTest covers decoded audio, trimming, invalid media, collisions, cancellation and persistence. No third-party runtime dependencies.

## Privacy

On-device media processing, no account, ads, tracking SDK or media upload service. Local event totals never leave the device. Apple provides purchases; sharing and Files destinations are chosen by the user.

[Privacy](https://sepidehdalir.github.io/clipvelle/privacy.html) · [Support](https://sepidehdalir.github.io/clipvelle/support.html)

Designed and engineered by **Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com) · hello@arvinify.com
