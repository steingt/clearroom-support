# ClearRoom support

ClearRoom is a free native iPhone toolkit for inspecting possible hidden-camera clues. All features are free, with no ads, account, analytics, subscriptions or in-app purchases. Requires iOS 17 or later.

## Build 8 guide

**Start a check.** Connect to Wi-Fi you are allowed to inspect and tap **Start check**. ClearRoom looks for devices that may stream video. A progress bar and percentage show completed device checks, followed by a short result. A stopped or partial check is marked incomplete. **Wi-Fi details** holds device responses and technical information.

**Follow the next step.** If a streaming clue is found, tap **Review finding** and compare it with devices you recognize. Ask the property owner about anything unfamiliar. Ordinary devices are not labeled as cameras; a streaming response alone does not establish that a camera is hidden.

**Try the optional light check.** Tap **Check for infrared light**. The front / selfie camera is selected initially because it can make infrared easier to see on some iPhones; the rear camera is also available. The drawing shows which side to face toward the room. Tap **Open camera**, then **Record for 12 seconds**. Darken the room, face the screen toward the area and move slowly. A countdown, dim screen and start/end vibrations help you record without watching.

**Review the clip.** Turn the screen back toward you. Pause, scrub or enlarge a frame to inspect a small light. Clips are deleted when you leave or background the check. Use **Save or share clip** to keep a copy. No microphone or photo-library access is requested.

Build 8 uses Apple’s device-specific orientation handling for the preview and capture. If the camera looks sideways, confirm that TestFlight has updated to build 8 and reopen it.

Infrared visibility varies by camera. The optional **Test with a TV remote** instructions help you check a known working IR remote up close. That does not establish room-distance performance or sensitivity to other wavelengths. A light can come from ordinary equipment, and many cameras emit no infrared.

**More** contains Where to look, All tools, Room checklist, Saved notes and Privacy. Existing notes are preserved. Every feature is free. Public App Store availability remains subject to Apple review.

## Troubleshooting

- Camera unavailable: allow Camera in iPhone Settings, close other camera activity, and restart the selected camera. Physical camera capture needs an iPhone.
- No network results: check Wi-Fi and Local Network permission. Direct discovery covers six common ports on the connected IPv4 subnet, up to 1,022 host addresses. IPv6, other ports, guest-network isolation, offline devices and other networks can be missed. Limited coverage is shown explicitly.
- Infrared sensitivity varies by camera; no software removes its hardware filter. Seeing no light cannot rule out cameras or audio recorders. See [Sony’s camera-and-remote guidance](https://www.sony.com/electronics/support/televisions-projectors-lcd-tvs/klv-21sr2/articles/00223964).
- Magnetic readings: remove magnetic accessories before establishing a baseline. Changes cannot identify cameras or measure Wi-Fi radio signals.
- Saved notes remain inside ClearRoom and are excluded from backups. Export what you want to keep before deleting the app.

## Help and privacy

Email [contato@terosmk.com.br](mailto:contato@terosmk.com.br) for support from TMK Consultoria LTDA.

[Open a support issue](https://github.com/steingt/clearroom-support/issues/new) with your iPhone model, iOS/app version and steps to reproduce the problem. Issues are public and hosted by GitHub. Do not post private room addresses, inspection notes or sensitive photos.

[Read the privacy policy](PRIVACY.md).

ClearRoom is an inspection aid. No app result or completed checklist can establish that a room is free of cameras. No measured detection accuracy is claimed.

Provided by TMK Consultoria LTDA.
