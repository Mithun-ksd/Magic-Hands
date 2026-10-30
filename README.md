# Magic Hands

> Draw in the air using a simple pinch gesture.

Magic Hands turns your hand into an on-screen drawing tool. Pinch your thumb and index finger together to draw, then open them to lift the virtual pen. No physical pen, mouse, or touch screen is required.

## Download

**Windows executable:** [Download the latest release](../../releases/latest)

1. Open the latest release.
2. Download the `Magic Hands.exe` file from the **Assets** section.
3. Run the downloaded file on a compatible Windows computer.

Only download releases published from this repository. Windows may display a SmartScreen or antivirus warning for an unsigned or less widely downloaded application. Do not bypass a warning unless you trust the publisher and have independently verified the file.

## How to use

1. Hold one hand up so the camera can see your fingers clearly.
2. Pinch your thumb and index finger together to begin drawing.
3. Move your hand while pinching to draw a line.
4. Open your fingers to lift the virtual pen.
5. Press 1 to 5 to select a colour. Use Plus or Minus to change brush size.
6. Press E to erase, Z to undo, C to clear the canvas, or S to save your picture.
7. Press Q or Esc to quit.

## Features

- Draw by pinching your thumb and index finger
- Five selectable colours
- Adjustable brush size
- Eraser, undo, and clear controls
- Save drawings with a transparent background
- Smoothed drawing strokes
- Designed to support use at different distances from the camera

## Keyboard controls

| Key | Action |
|---|---|
| 1–5 | Select a colour |
| + / - | Increase / decrease brush size |
| E | Eraser |
| Z | Undo |
| C | Clear the drawing |
| S | Save the drawing |
| Q / Esc | Quit |

## How it works

1. MediaPipe Hands detects a hand and estimates 21 landmarks on it.
2. The application measures the distance between the thumb tip and index fingertip.
3. A small distance is interpreted as pen-down; a larger distance is interpreted as pen-up.
4. The application draws the tracked fingertip path over the camera view.

## Camera and privacy

The application uses your camera to track hand movement. Use it only in a setting where people being recorded by the camera have agreed to its use. The application saves an image when you press S; review the save location and handle exported drawings carefully. The publisher has not made a claim here about network traffic; consult the application's behavior and your firewall/network monitor if offline operation is important.

The application may display or process camera imagery. Obtain consent before using a camera where other people may be visible. Avoid capturing or sharing images of people without their permission.

## System requirements

- A Windows computer.
- A working camera.
- Sufficient lighting for reliable camera detection.
- A keyboard for the controls listed above.

The publisher should add the tested Windows versions, minimum hardware requirements, and any known limitations here after testing the release on a clean Windows installation.

## Troubleshooting

- **Camera not available:** Close other applications that may be using the camera and check Windows camera permissions.
- **Detection is unstable:** Improve lighting, keep the relevant hand or face in view, and avoid blocking it.
- **Application does not start:** Confirm that you downloaded the latest release from this repository. If the issue continues, report it using the repository's Issues page and include your Windows version and the exact error message. Do not attach private images or personal data.

## Security

See [SECURITY.md](SECURITY.md) for how to report a security concern.

## Third-party components

See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for the direct dependencies declared for this app. The final executable may contain additional transitive or bundled components; their notices must also be reviewed and included as required.

## License

Copyright (c) 2026 Mithun C. All rights reserved. See [LICENSE](LICENSE).

This repository distributes the compiled application only. The application's source code is not included.
