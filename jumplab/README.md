# JumpLab V3

JumpLab V3 is a video-based jump-analysis workflow for CMJ, SJ, and DJ review. It combines video playback, frame-level event marking, estimated performance metrics, AI-assisted event suggestions, and on-device pose overlays to support teaching and coach review.

## Demo screenshots

### Countermovement and lowest position

![JumpLab V3 countermovement frame with hip and knee angles](../assets/jumplab/jumplab-crouch.jpg)

The frame-by-frame view overlays estimated body landmarks and displays hip and knee angles to support review of the countermovement position. These are single-camera 2D estimates and require coach interpretation.

### Take-off and flight phase

![JumpLab V3 take-off frame with pose overlay and estimated jump height](../assets/jumplab/jumplab-takeoff.jpg)

The take-off marker and AI-estimated floor-contact line support manual verification of the first fully airborne frame. Flight time and jump height are calculated from the reviewed take-off and landing events.

### Landing review

![JumpLab V3 landing frame with floor contact line and pose overlay](../assets/jumplab/jumplab-landing.jpg)

The landing frame helps the reviewer identify the first renewed floor contact and inspect posture around landing. The event marker remains editable so the user can correct an AI suggestion frame by frame.

## What it demonstrates

- Local video import and original-aspect-ratio playback
- Frame-by-frame review at the selected video frame rate
- Take-off and landing event marking for CMJ and SJ
- Contact, take-off, and landing event marking for DJ
- Estimated flight time, jump height, contact time, and RSI
- On-device pose overlay and coach-facing report workflow
- Manual verification of AI-suggested event points

## Project links

- [Open JumpLab V3 demo](https://jumplab-tehta.web.app/v3)
- [Source repository](https://github.com/skyfu218/jumplab-motion-analysis)

## Measurement boundary

Jump height may be estimated from flight time, and event timing depends on the source video's true frame rate and the reviewer-selected frames. Pose landmarks and floor contact are 2D image estimates. Results should be interpreted as teaching and coach-support information, not as force-plate validation, medical diagnosis, or an official performance standard.

[Back to Video Motion Analysis](../README.md)

