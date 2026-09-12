# ClearRoom support

ClearRoom is a free native iPhone toolkit for inspecting possible hidden-camera clues. All features are free, with no ads, account, analytics, subscriptions or in-app purchases. Requires iOS 17 or later.

## Build 6 guide

These instructions describe the redesigned build 6, which has been uploaded to Apple. TestFlight availability and public App Store release depend on the remaining distribution and review steps. Earlier builds have a different Quick Check layout.

**Start with Quick Check.** Connect to Wi-Fi you are allowed to inspect and tap Start Quick Check. ClearRoom checks common web and streaming ports and browses advertised services. Responding devices and advertised services are separate lists, not camera counts. Open a device result to see the actual evidence and a plain-language explanation. A familiar port, a streaming response or an unfamiliar name does not establish that a camera is hidden.

**Optional infrared check.** Tap Check for infrared light on the home screen. Choose Rear camera or Front / selfie camera, then start it. If you have a known working IR remote, point its emitter close to the selected camera and hold an infrared button. Seeing a flashing point demonstrates some sensitivity; it does not establish inspection distance or coverage of every wavelength. No remote or no visible light means the check remains unverified.

**Record, then review.** Darken the room and keep the flashlight off. Tap Record 12-second sweep. After the countdown, point the screen and selfie lens toward the area you want to check, and sweep slowly from a steady position. Start/end vibrations and screen dimming support recording without watching. Turn the screen toward you afterward, pause or scrub the silent clip, and enlarge individual frames. A light can come from ordinary equipment, and many cameras emit no infrared.

Sweep clips are temporary and deleted on leaving or backgrounding the check. Save or share clip lets you explicitly export a copy. The app requests no microphone or photo-library access. Ordinary lens viewing and magnetic readings are under Individual tools. The optional checklist and saved notes remain under More.

## Troubleshooting

- Camera unavailable: allow Camera in iPhone Settings, close other camera activity, and restart the selected camera. Physical camera capture needs an iPhone.
- No network results: check Wi-Fi and Local Network permission. Direct discovery covers six common ports on the connected IPv4 subnet, up to 1,022 host addresses. IPv6, other ports, guest-network isolation, offline devices and other networks can be missed. Limited coverage is shown explicitly.
- Infrared sensitivity varies by camera; no software removes its hardware filter. Seeing no light cannot rule out cameras or audio recorders. See [Sony’s camera-and-remote guidance](https://www.sony.ca/en/electronics/support/interchangeable-lens-cameras-e-mount-body/articles/00025283?category=interchangeable-lens-cameras-e-mount-body).
- Magnetic readings: remove magnetic accessories before establishing a baseline. Changes cannot identify cameras or measure Wi-Fi radio signals.
- Saved notes remain inside ClearRoom and are excluded from backups. Export what you want to keep before deleting the app.

## Help and privacy

Email [contato@terosmk.com.br](mailto:contato@terosmk.com.br) for support from TMK Consultoria LTDA.

[Open a support issue](https://github.com/steingt/clearroom-support/issues/new) with your iPhone model, iOS/app version and steps to reproduce the problem. Issues are public and hosted by GitHub. Do not post private room addresses, inspection notes or sensitive photos.

[Read the privacy policy](PRIVACY.md).

ClearRoom is an inspection aid. No app result or completed checklist can establish that a room is free of cameras. No measured detection accuracy is claimed.

Provided by TMK Consultoria LTDA.
