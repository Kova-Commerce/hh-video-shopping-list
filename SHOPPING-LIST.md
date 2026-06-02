# Hyde & Hare - Missing Video Shopping List
Generated 5 Apr 2026 from 24-month Meta pull

## How to use this list
1. Find these videos in the H&H Google Drive
2. Download them to your laptop/phone
3. SCP to Mac Mini: `scp video.mp4 casey@<mac-mini>:~/casey-brain/tools/video-analyzer/incoming/`
4. Tell Claude which file is which (or name them with the ad number, e.g. "ad1.mp4", "ad63.mp4")
5. Claude will rename and move them into videos/, then run the Gemini analysis

## Priority 1: Must-haves (£22k spend, 1,059 conversions)

### #1 - Ad 1: UGC Video with voiceover (Free Delivery)
- **What it is:** UGC voiceover, free delivery hook, softest sheepskin messaging
- **Total:** £9,709 spend / 526 conv across 5 ad runs
- **Save as any of:** 120211533148000530.mp4, 120223650372470530.mp4, 120211219958820530.mp4, 120204543192850530.mp4, 120212885369180530.mp4

### #2 - Ad 63: Ways to style with sheepskin rugs
- **What it is:** Multi-room sheepskin rug styling video
- **Total:** £8,787 spend / 344 conv across 2 ad runs
- **Save as any of:** 120232948743250530.mp4, 120223643642290530.mp4

### #3 - Ad 191: White Company testimonial b-roll
- **What it is:** B-roll with testimonial text overlay comparing to The White Company
- **Total:** £1,715 spend / 69 conv across 3 ad runs
- **Save as any of:** 120240380887470530.mp4, 120238847617070530.mp4, 120239795717910530.mp4

### #4 - Ad 172: Home of Hygge b-roll (with text overlay)
- **What it is:** Hygge-themed b-roll with detailed text overlay
- **Total:** £1,052 spend / 33 conv across 2 ad runs
- **Save as any of:** 120240774622060530.mp4, 120239795717760530.mp4

### #5 - Ad 192: BFCM Joey styling (20% off)
- **What it is:** Joey ways to style sheepskin, BFCM 20% off offer
- **Total:** £803 spend / 50 conv
- **Save as:** 120238204006030530.mp4

## Priority 2: Nice-to-haves (£3k spend, 122 conversions)

### #6 - Ad 157: Slow motion unboxing (hot water bottle offer)
- £573 / 15 conv - Save as: 120234450107770530.mp4

### #7 - Ad 180: Flora - 5 Ways to Style Sheepskin Rug
- £553 / 22 conv - Save as: 120238071114200530.mp4 or 120239795717810530.mp4

### #8 - Ad 155: Joey voiceover features & benefits (hot water bottle offer)
- £363 / 17 conv - Save as: 120239801462670530.mp4

### #9 - Ad 113: UGC Heidi 2 quality of materials
- £354 / 11 conv - Save as: 120223649380670530.mp4

### #10 - Ad 178: Bedroom b-roll, cosy products text overlay
- £354 / 20 conv - Save as: 120239795717890530.mp4

### #11 - Ad 177: Charlie tips on luxury living room styling
- £338 / 12 conv - Save as: 120239795717770530.mp4

### #12 - Ad 182: Lianna creating a cosy corner
- £319 / 17 conv - Save as: 120240774589480530.mp4 or 120239795717730530.mp4

## Priority 3: Skip unless easy to grab

### #13-33: All under £320 spend each
- Ad 154: Family hot water bottles (£314 / 9 conv)
- Ad 190: Cultiver slideshow (£268 / 7 conv)
- Ad 193: BFCM Jojo moonlight (£234 / 6 conv)
- Ad 110: UGC Justyna 1 unboxing (£225 / 5 conv)
- Ad 165: UGC sheepskin rugs cosy season (£224 / 5 conv)
- Ad 183-210 and others: all under £200

## Transfer cheat sheet (from any device)
```bash
# SCP a single file
scp "Ad 1 UGC.mp4" casey@<mac-mini-ip>:~/casey-brain/tools/video-analyzer/incoming/

# SCP a whole folder
scp *.mp4 casey@<mac-mini-ip>:~/casey-brain/tools/video-analyzer/incoming/
```

Then SSH in, start a Claude session, and say:
"I've uploaded the missing H&H videos to incoming/. Here's what's what:
- ad1-ugc.mp4 is Ad 1 (UGC voiceover)
- styling-video.mp4 is Ad 63 (ways to style)
- ..."

Claude will rename them and run the analysis.
