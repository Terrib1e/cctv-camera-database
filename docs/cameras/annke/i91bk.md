# Annke I91BK

*Also known as: Mini Dome PTZ, 4X Optical Zoom Mini PTZ*

| Field | Spec |
|-------|------|
| Brand | Annke |
| Model | I91BK |
| Type | ptz |
| Connectivity | ethernet |
| Resolution | 3K (3072x1728) (5MP, 3072×1728) |
| Sensor | 1/2.8" Progressive Scan CMOS |
| Lens | 1× 2.8-12 (4x optical zoom, 16x digital)mm |
| Field of view | 96.7-31.6 horizontal (115.1-36.3 diagonal)° |
| Night vision | ir (20m), 0.001 lux, 0.005 lux color |
| Power | PoE (802.3af) / DC 12V (max 9.2W) |
| Storage | microSD ≤ 256GB, NVR |
| Protocols | rtsp, onvif |
| IP rating | IP66 |
| IK rating | IK10 |
| Two-way audio | No |
| Operating temp | -20 to 60°C |

## Streams

| Stream | Resolution | FPS | Codec |
|--------|-----------|-----|-------|
| main | 3072x1728 | 15 | H.265 |

## Features

- Mini dome PTZ
- 4x optical zoom (2.8-12mm), 16x digital zoom
- IR night vision up to 20m
- IK10 vandal-resistant
- TVS 4000V lightning/surge protection
- built-in mic + 1-ch audio in/out
- H.265+
- RTSP/ONVIF (Profile S/G/T)

## Sources

- https://cdn.shopify.com/s/files/1/0110/6385/3156/files/I91BK-en.pdf
- https://www.annkecctv.com/products/i91bk

## Community notes (unverified)

*Reported by users. Not from the datasheet, not verified by the project.*

- After a PTZ move command, ONVIF GetStatus reports MoveStatus IDLE for about 0.1 s before switching to MOVING. A client that polls right after the command treats the move as finished, so Frigate autotracking (0.18.2) ends every move at once. Manual PTZ from Frigate works.
  
  onvif · firmware V5.7.1 build 250227 · reported by nikosch86 · 2026-10-21 · [source](https://github.com/ch-bas/cctv-camera-database/issues/409)
- ONVIF AbsoluteMove zoom only moves in whole steps of the 4x optical zoom (1x, 2x, 3x, 4x); zoom positions between two steps cannot be reached.
  
  ptz · firmware V5.7.1 build 250227 · reported by nikosch86 · 2026-10-21 · [source](https://github.com/ch-bas/cctv-camera-database/issues/410)

---
*Auto-generated from annke-i91bk.json — do not edit by hand.*
