# Beeframe-scan
BeeFrame Scan — Prototype PWA for camera-guided beehive frame inspection. Limited test build. Not a diagnostic tool.
# BeeFrame Scan — Tester Instruction Card
**Prototype v0.1.2 · Limited Test Build · Not a Diagnostic Tool**
---
## What this is:
BeeFrame Scan is a **prototype inspection aid** for beekeepers. It uses your phone camera to help you:

- Frame and light a pulled hive frame consistently
- Get real-time image quality coaching (sharpness, brightness)
- Capture and log inspection notes with a small thumbnail
- See a rough heuristic flag for possible dark reddish specks that *may* warrant closer manual inspection

It is **not** a varroa counter, diagnostic device, treatment recommendation engine, or scientific instrument.
---
## What this is NOT:
**Do not** use this app to decide whether to:
- Treat, medicate, or apply oxalic acid or any miticide to a hive
- Destroy, combine, requeen, or sell a colony
- Declare a hive healthy or diseased
- Skip standard confirmation methods

**Always confirm with standard beekeeper methods:**
Alcohol wash · Sugar roll · Sticky board count · Drone brood check · Experienced manual inspection
---
## How to install on your phone:
1. Open the link you were given in **Safari (iPhone)** or **Chrome (Android)**
2. **iPhone:** tap the Share icon → "Add to Home Screen"
3. **Android:** tap the browser menu → "Add to Home Screen" or "Install app"
4. The app works offline once installed

Camera access requires the HTTPS link — it will not work over plain HTTP.
---
## How to use it:
1. Pull a frame from the hive
2. Open BeeFrame Scan and enter a Hive ID and frame number/side
3. Tap **Start camera** and point the rear camera at the frame
4. Watch the coaching bar:
   - *Too dark* — add light or angle the frame toward daylight
   - *Too blurry* — move slowly and brace your hand
   - *Too bright* — reduce direct glare on capped cells
   - *Possible pest candidates* — something in the image triggered the heuristic; capture and look carefully
5. Tap **Capture frame** when the image looks good
6. Add notes, then tap **Save inspection**
7. Use **Export metadata JSON** to send your session data
---
## Feedback categories — please use these exactly;
When reporting what you saw, label each observation as one of:

| Label | When to use |
|---|---|
| **image quality** | Feedback about lighting, blur, framing, or camera coaching |
| **suspected pest flagging** | The app flagged something; you haven't confirmed yet |
| **confirmed pest observation** | You independently confirmed (alcohol wash, manual count, etc.) |
| **false flag** | The app flagged something; you confirmed it was not a pest |
| **uncertain result** | You cannot determine whether the flag was correct |

Please include: Hive ID, frame number, date, your experience level (new / hobbyist / experienced / professional), and any notes on lighting conditions.
---
## Privacy:
All inspection data stays **on your device only**. Nothing is uploaded to any server. The exported JSON file contains only metadata and a small thumbnail — not full-size images.
---
## Known limitations of this prototype
- The pest heuristic is a simple color-range filter. It will produce false positives on dark wax, propolis, shadow edges, and other reddish-brown organic matter.
- No AI model has been trained. No labeled dataset exists yet. The flag is a workflow scaffold, not a detection system.
- Storage uses your browser's local storage. Clearing your browser data will erase the inspection log.
- The app logs up to 100 inspections locally. Older entries are dropped when the limit is reached.
---
## Questions or problems:
Contact: admin@spiralqit.org
*BeeFrame Scan Prototype v0.1.2 — SpiralQIT · Limited test build authorized by Michael E. Fletcher · Not for production, clinical, commercial, or treatment-decision use.*
