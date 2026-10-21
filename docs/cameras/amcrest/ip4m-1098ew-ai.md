# Amcrest IP4M-1098EW-AI

*Also known as: Amcrest IP4M-1098EW-AI*

| Field | Spec |
|-------|------|
| Brand | Amcrest |
| Model | IP4M-1098EW-AI |
| Type | ptz |
| Connectivity | ethernet |
| Resolution | 4MP (4MP, 2560×1440) |
| Sensor | 1/2.8" Starvis CMOS |
| Lens | 1× 2.7-13.5mm F1.6 |
| Field of view | 34.6-112.3° |
| Night vision | hybrid (50m), 0.005 lux color |
| Power | PoE+ (802.3at) / DC 24V |
| Storage | microSD ≤ 512GB, NVR |
| Protocols | rtsp, onvif |
| IP rating | IP66 |
| Two-way audio | Yes |
| Operating temp | -30 to 60°C |

## Features

- 5x optical zoom
- 360 pan
- 90 tilt
- auto-tracking
- dual-light fusion (IR + white light)
- human detection
- vehicle detection
- face detection
- tripwire
- intrusion detection
- 120dB WDR

## Sources

- https://support.amcrest.com/hc/en-us/articles/23967384150157-Technical-Specifications-IP4M-1098EW-AI

## Community notes (unverified)

*Reported by users. Not from the datasheet, not verified by the project.*

- With focus set to Auto, the camera refocuses after every PTZ move and ONVIF GetStatus reports MOVING until the refocus finishes, so each move appears to take several seconds and Frigate autotracking reacts slowly. Setting focus to Manual removes the delay.
  
  ptz · firmware 2.821.00AC002.0.R · reported by nikosch86 · 2026-10-21 · [source](https://github.com/ch-bas/cctv-camera-database/issues/411)

---
*Auto-generated from amcrest-ip4m-1098ew-ai.json — do not edit by hand.*
