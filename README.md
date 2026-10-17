# Clipvelle: Video to Audio

<img src="docs/assets/icon.png" width="112" alt="Clipvelle film-to-sound icon">

**Your video. Just the audio.** A focused native iPhone and iPad utility that extracts a chosen audio track from your own local video, lets you listen and trim one segment, then exports a named M4A or WAV file.

**Status · October 16, 2026:** V1 implemented; native extraction/UI and local StoreKit QA passed on iOS 17.0 and 26.2. Apple validated the signed archive; build 1.0 (1) is uploaded, processed and selected in App Store Connect. Premium iPhone and iPad campaigns are saved. Physical device/sandbox checks and owner privacy publication remain open. **Not submitted or released.** Commercial source is maintained separately in a private repository.

## Campaign

Distinct iPhone and iPad art direction around authentic final app UI. Original chime media and decorative film-to-sound artwork; no fabricated controls or output data.

<img src="docs/assets/iphone-campaign.png" width="1100" alt="iPhone campaign: outcome, trim workflow, export, Pro and local privacy">

<img src="docs/assets/ipad-campaign.png" width="1100" alt="Dedicated iPad campaign showing the source list and export inspector">

[Full iPhone frames](docs/assets/iPhone) · [Full iPad frames](docs/assets/iPad)

## Product

- Photos and Files import; original media remains untouched.
- Explicit selection when a video has multiple audio tracks.
- Preview and inspectable start/end times.
- Compact AAC/M4A and uncompressed PCM/WAV export with actual duration and file size.
- Dedicated iPad source list and inspector.
- Free single-video exports; Lifetime Pro adds batch extraction and reusable export presets. No subscription.

## Engineering

Swift, SwiftUI, AVFoundation, PhotosUI, UniformTypeIdentifiers and StoreKit 2. Universal iPhone/iPad with an iOS 15 deployment target and availability fallbacks. Streaming reader/writer conversion, coordinated security-scoped imports, cancellation cleanup, durable source/export ownership and verified StoreKit entitlements. XCTest covers decoded audio, trimming, invalid media, collisions, cancellation and persistence. No third-party runtime dependencies.

## Privacy

On-device media processing, no account, ads, tracking SDK or media upload service. Local event totals never leave the device. Apple provides purchases; sharing and Files destinations are chosen by the user.

[Privacy](https://sepidehdalir.github.io/clipvelle/privacy.html) · [Support](https://sepidehdalir.github.io/clipvelle/support.html)

Designed and engineered by **Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com) · hello@arvinify.com
