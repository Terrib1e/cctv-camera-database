# Dahua TPC-SD5641-V1

*Also known as: DHI-TPC-SD5641-V1, DHI-TPC-SD5641-B19Z45-DC-S24, DHI-TPC-SD5641-B25Z45-DC-S24, DHI-TPC-SD5641-B35Z45-DC-S24, DHI-TPC-SD5641-B50Z45-DC-S24*

| Field | Spec |
|-------|------|
| Brand | Dahua |
| Model | TPC-SD5641-V1 |
| Type | ptz |
| Connectivity | ethernet |
| Resolution | 640x512 (thermal) (0.33MP, 640×512) |
| Sensor | Thermal: vanadium oxide uncooled focal plane detector, 640x512, 12 um pixel pitch, 8-14 um, NETD <= 35 mK; optical: 1/2.8in 4MP CMOS |
| Lens | 2× 19 / 25 / 35 / 50 (thermal, fixed, per variant); 3.95-177.75 (visible, 45x)mm |
| Field of view | Thermal 19 mm H: 23.3, V: 18.6; 25 mm H: 18.6, V: 14.8; 35 mm H: 12.6, V: 10.1; 50 mm H: 9.2, V: 7.3; visible H: 67.5-1.9, V: 39.4-1.1° |
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
| main | 2688x1520 | 30 | H.265 |
| sub | 1920x1080 | 30 | H.265 |
| thermal main | 1280x1024 | 60 | H.265 |
| thermal sub | 640x512 | 30 | H.265 |

## Features

- V1 revision of the Pro-series thermal hybrid speed dome (thermal + 4MP visible)
- uncooled VOx thermal detector (640x512); fixed-focal thermal lens 19 / 25 / 35 / 50 mm per ordering variant
- visible 45x optical zoom (3.95-177.75 mm); IR illumination distance 100 m
- AI: boat detection, heat detection, tripwire, intrusion, human/vehicle classification, cold/hot spot trace; dual image fusion (visible + thermal)
- heat detection distance up to 1,140 m (19 mm) to 3,000 m (50 mm)
- pan 0-360 endless, tilt -10 to +90; 200 presets, 8 tours, 5 patterns
- electronic image stabilization (EIS) on thermal and visible channels
- alarm 7 in / 2 out; audio 1 in / 1 out; RS-485; CVBS output
- 6 kV surge protection

## Sources

- https://www.dahuasecurity.com/products/thermal-products/thermal-cameras/pro-series/tpc-5-series/tpc-sd5641-v1=v1
- https://materialfile.dahuasecurity.com/uploads/cpq/86589/datasheet/TPC-SD5641_V1_datasheet_20260227.pdf

---
*Auto-generated from dahua-tpc-sd5641-v1.json — do not edit by hand.*
