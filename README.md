# Vehicle Livery 2D Template Rules

This repository defines placement and orientation rules for AI-generated
vehicle livery designs based on flat 2D templates.

## Purpose

The templates represent a top-down flattened layout of a vehicle.
They are NOT 3D renders.

AI must only place flat design elements (logos, text, stripes)
within allowed areas.

## Template Color Rules

- White areas = valid design zones
- Black areas = no design allowed
- Transparent areas = glass / roof / no graphics

The template is a placement reference ONLY.

## Orientation Rules (Critical)

The template is 2D, but the vehicle exists in 3D.
Text orientation must be adjusted to appear correct in real-world view.

### Hood / Front Section
- Text must face forward
- When viewed from above, text reads normally

### Left Side Panels
- Text must be horizontal in 2D
- This will appear vertical when applied to the real car

### Right Side Panels
- Text must mirror the left side orientation

### Front Bumper
- Text must face forward

### Rear Bumper
- Text must face backward

## Style Rules

- Flat vector style only
- No shadows, lighting, or perspective
- No panel outlines
- No invented shapes
- Wallpaper-style layout

## Output Requirements

- Resolution: 1024x1024
- Background: pure white
- No mockups or vehicle drawings

## Final Notes

The AI should behave as a layout assistant, not a vehicle designer.
Final masking and alignment will be done manually in Photoshop.
