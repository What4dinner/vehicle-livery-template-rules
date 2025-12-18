# Orientation & Direction Rules (Critical)

This repository uses multiple 2D mask images to represent different physical sides of the same vehicle.

These masks are NOT a top-down view.

---

## Global Orientation Rule

All masks are oriented as if the viewer is standing OUTSIDE the vehicle and looking directly at that side.

Text, symbols, and directional graphics MUST be readable from that real-world viewing position.

---

## Front Hood + Bumper Mask

File:
- front_hood+bumper_mask.png

Orientation:
- The TOP of the image is the FRONT bumper.
- The BOTTOM of the image is closer to the windshield.

Rules:
- All text and logos must face forward.
- If the car drives toward the viewer, text must be readable.
- Never rotate text to be readable from a bird’s-eye or top-down view.

This area represents:
- Front bumper
- Hood
- Partial front fenders

This area does NOT include:
- Roof
- Windshield
- Headlights
- Top surfaces

---

## Rear Mask

File:
- rear_mask.png

Orientation:
- The TOP of the image is the rear window.
- The BOTTOM of the image is closer to the rear bumper.

Rules:
- Text must be readable when standing behind the vehicle.
- Do NOT mirror front designs unless explicitly instructed.
- Rear graphics should feel visually connected but directionally correct.

---

## Left Side Mask

File:
- leftside_mask.png

Orientation:
- The viewer is standing on the LEFT side of the vehicle.
- The TOP of the image is toward the roof of the car.
- The BOTTOM of the image is toward the bottom of the car.

Rules:
- Text must read from FRONT → REAR when standing on the left side.
- Do NOT flip or mirror text for symmetry.
- Directional stripes should visually move forward.

---

## Right Side Mask

File:
- right_mask.png

Orientation:
- The viewer is standing on the RIGHT side of the vehicle.
- The TOP of the image is toward the roof of the car.
- The BOTTOM of the image is toward the bottom of the car.

Rules:
- Text must read from FRONT → REAR when standing on the right side.
- Text orientation must NOT be mirrored from the left side.
- Each side must be independently readable.

---

## Symmetry Warning (Very Important)

- Vehicle sides are mirrored in shape, but NOT in text orientation.
- Never mirror text, logos, or numbers across sides.
- Readability from real-world viewing angles has priority over visual symmetry.

---

## Final Orientation Test

Before finalizing any design, verify:

- Front text is readable when standing in front of the car.
- Rear text is readable when standing behind the car.
- Left-side text is readable when standing on the left side.
- Right-side text is readable when standing on the right side.

If any text is only readable from a top-down view, the design is incorrect.
