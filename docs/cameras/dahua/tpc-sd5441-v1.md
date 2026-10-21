# Dahua TPC-SD5441-V1

*Also known as: DHI-TPC-SD5441-V1, DHI-TPC-SD5441-B13Z45-DC-S24, DHI-TPC-SD5441-B19Z45-DC-S24, DHI-TPC-SD5441-B25Z45-DC-S24, DHI-TPC-SD5441-B35Z45-DC-S24, DHI-TPC-SD5441-B50Z45-DC-S24*

| Field | Spec |
|-------|------|
| Brand | Dahua |
| Model | TPC-SD5441-V1 |
| Type | ptz |
| Connectivity | ethernet |
| Resolution | 400x300 (thermal) (0.12MP, 400×300) |
| Sensor | Thermal: vanadium oxide uncooled focal plane detector, 400x300, 12 um pixel pitch, 8-14 um, NETD < 35 mK; optical: 1/2.8in 4MP CMOS |
| Lens | 2× 13 / 19 / 25 / 35 / 50 (thermal, fixed, per variant); 3.95-177.75 (visible, 45x)mm |
| Field of view | Thermal 13 mm H: 21.24, V: 15.94; 19 mm H: 14.5, V: 10.9; 25 mm H: 11, V: 8.2; 35 mm H: 7.85, V: 5.89; 50 mm H: 5.5, V: 4.12° |
| Night vision | ir (100m), 0.001 lux, 0.01 lux color |
| Power | 36 VDC +/-50% / Hi-PoE |
| Storage | microSD ≤ 512GB |
| Protocols | onvif, rtsp |
| IP rating | IP66 |
| Two-way audio | Yes |
| Operating temp | -30 to 60°C |

## Streams

| Stream | Resolution | FPS | Codec |
|--------|-----------|-----|-------|
| main | 2688x1520 | 60 | H.265 |
| sub | 1920x1080 | 30 | H.265 |
| thermal main | 1280x1024 | 30 | H.265 |
| thermal sub | 400x300 | 30 | H.265 |

## Features

- V1 revision of the Pro-series thermal hybrid speed dome (datasheet DHI-TPC-SD5441_V1) (thermal + 4MP visible)
- uncooled VOx thermal detector (400x300); fixed-focal thermal lens 13 / 19 / 25 / 35 / 50 mm per ordering variant
- visible 45x optical zoom (3.95-177.75 mm); IR illumination distance 100 m
- AI: boat detection, smoke detection (up to 4,000 m), heat detection, tripwire, intrusion, human/vehicle classification, cold/hot spot trace
- heat detection distance up to 780 m (13 mm) to 3,000 m (50 mm)
- pan 0-360 endless, tilt -10 to +90; 300 presets, 8 tours, 5 patterns
- electronic image stabilization (EIS) on thermal and visible channels
- alarm 7 in / 2 out; audio 1 in / 1 out; RS-485; CVBS output
- 6 kV surge protection

## Sources

- https://www.dahuasecurity.com/products/thermal-products/thermal-cameras/pro-series/tpc-5-series/tpc-sd5441-v1=v1
- https://materialfile.dahuasecurity.com/uploads/cpq/86592/datasheet/DHI-TPC-SD5441_V1_datasheet_20260227.pdf

---
*Auto-generated from dahua-tpc-sd5441-v1.json — do not edit by hand.*
