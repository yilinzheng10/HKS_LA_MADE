# Laguna CNC Router

Reference configuration: SmartShop 3 Excel 5x10 / 61" x 121" working area.

## Overview

This folder documents safe startup, basic machine setup, posted-code workflow, example jobs, and onboarding for the shop's Laguna 5x10 CNC router.

## Specification snapshot

- Working area: 61" x 121"
- Footprint: 115" W x 158" L
- Gantry clearance: 12"
- Spindle: 12 HP HSD ATC ES951 spindle
- Spindle speed: 5,000-24,000 RPM
- Rapid travel: up to 3,000 IPM
- Maximum cutting speed: 1,200 IPM
- Tool capacity: 12-position rotary tool changer
- Vacuum table: 6 zones, pod-ready
- Dust port: 6"
- Power: CNC motion is 220V / 3-phase / 30A; total electrical requirement depends on the installed vacuum package

## Recommended design and CAM formats

- Preferred design interchange: DXF
- Preferred unit interchange: inches
- 3D component import: STL
- CAM platforms supported by Laguna resources/posts: Fusion 360, RhinoCAM / VisualCAM, VCarve, Aspire
- Machine execution format: posted NC / G-code for the Laguna SmartShop 3 + Fanuc control