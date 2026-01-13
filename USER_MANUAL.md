# Surtitles-in-a-box

## User Manual

**Version 1.1.0**

**by Operactive Arts**

---

# Table of Contents

1. [Introduction](#1-introduction)
2. [Getting Started](#2-getting-started)
3. [The Operator Interface](#3-the-operator-interface)
4. [Preparing Your Show](#4-preparing-your-show)
5. [Running a Performance](#5-running-a-performance)
6. [Keyboard Shortcuts](#6-keyboard-shortcuts)
7. [Presets](#7-presets)
8. [Troubleshooting](#8-troubleshooting)
9. [Quick Reference Card](#9-quick-reference-card)

---

# 1. Introduction

## What is Surtitles-in-a-box?

Surtitles-in-a-box is a professional desktop application for displaying live surtitles (supertitles) during opera and theatre performances. It allows an operator to manually advance through prepared text cues, displaying them on a fullscreen output connected to the audience-facing display.

## Key Features

- **Manual cue-by-cue navigation** - You control when each title appears
- **Background virtual screens** - Display images, videos, or solid colors behind titles
- **Multi-display support** - Operator screen and audience screen on separate monitors
- **Show-safe controls** - Blackout and freeze buttons, plus panic keyboard shortcut for emergencies
- **Automatic session recovery** - Never lose your place if the app closes unexpectedly
- **Preset system** - Save and load complete show configurations

## System Requirements

- Windows 10 or later
- Two displays recommended (operator + audience output)
- 4GB RAM minimum
- 500MB disk space

---

# 2. Getting Started

## First Launch

When you first open Surtitles-in-a-box, you'll see the **Entry Code Screen**.

### Entering Your License Key

1. Enter your license key exactly as shown in your purchase confirmation email from Lemon Squeezy
2. Check **"Remember this device"** if you want to skip this step next time
3. Click **Unlock**

> **Note:** An internet connection is required for first-time activation. After activation, the software works offline. Your Device ID is displayed at the bottom of this screen - provide this to Operactive Arts if you need support.

## Restoring a Previous Session

If the application finds a previous session, you'll see a prompt:

- Click **"Restore Session"** to continue where you left off
- Click **"Start Fresh"** to begin with a clean workspace

---

# 3. The Operator Interface

The main interface is divided into several areas:

```
+------------------------------------------------------------------+
|                          TOP BAR                                  |
|  [Load File] [Reload] | Mode: [▼] | filename.txt | Cue 1 of 42 | LIVE |
+------------------------------------------------------------------+
|                |                    |                             |
|   CUE PANEL    |   PREVIEW PANEL    |      CONTROL PANEL          |
|                |                    |                             |
|   1. Text...   |   [Live Preview]   |   Output Display: [▼]       |
|   2. Text...   |                    |   [Start Output]            |
| > 3. Current   |   [Backgrounds]    |                             |
|   4. Text...   |   [+Add] [thumb]   |   Show Controls:            |
|   5. Text...   |                    |   [Titles] [Blackout] [Freeze]|
|                |                    |                             |
|                |                    |   Layout & Style...         |
|                |                    |   Presets...                |
+------------------------------------------------------------------+
```

## Top Bar

- **Load File** - Open a surtitles text file
- **Reload** - Reload the current file (turns orange when file has changed)
- **Mode** - Switch between "Line by Line" and "Paragraph" parsing
- **Cue Counter** - Shows current position (click to jump to a specific cue)
- **LIVE/OFFLINE** - Indicates if the output window is active

## Cue Panel (Left)

Displays your surtitles as a scrollable list:
- The current cue is highlighted in cyan
- Blank cues show "(blank)" tag
- Click any cue to jump to it

## Preview Panel (Center)

Shows exactly what the audience will see:
- Live preview updates as you navigate
- Background thumbnails at the bottom
- Click **"+ Add"** to add new backgrounds

## Control Panel (Right)

All the controls for your show:
- Display selection and output control
- Show-safe buttons (Titles, Blackout, Freeze, Calibration)
- Layout settings (position, size, alignment)
- Style settings (color, legibility)
- Preset save/load

---

# 4. Preparing Your Show

## Step 1: Create Your Surtitles File

Create a plain text file (.txt) with your surtitles. Save it in UTF-8 encoding.

### Line-by-Line Mode
Each line becomes one cue. Empty lines create blank (clear screen) cues.

```
Welcome to tonight's performance.
Please silence your mobile phones.

Act One
Scene One: The Garden

JULIET: O Romeo, Romeo!
Wherefore art thou Romeo?
```

### Paragraph Mode
Consecutive lines are grouped together. Empty lines separate cues.

```
Welcome to tonight's performance.
Please silence your mobile phones.

Act One
Scene One: The Garden

JULIET: O Romeo, Romeo!
Wherefore art thou Romeo?
Deny thy father and refuse thy name.
```

### Comments
Lines starting with `#` are ignored:

```
# Act 1 - Introduction
Welcome to the performance.
# Pause for applause
(blank line here for clear screen)
```

## Step 2: Load Your File

1. Click **"Load File"** in the top bar
2. Select your .txt file
3. Choose your parsing mode (Line by Line or Paragraph)

## Step 3: Add Backgrounds (Optional)

Backgrounds appear behind your titles. You can use:
- **Images** - PNG, JPG, GIF, WebP
- **Videos** - MP4 only (H.264 codec, will loop)
- **Solid Colors** - Any color you choose

To add a background:
1. Click **"+ Add"** in the Preview Panel
2. Enter an optional label (e.g., "Act 1", "Intermission")
3. Either:
   - Click **"Select File"** for an image or video
   - Choose a color and click **"Add Blank"** for a solid color

## Step 4: Configure Layout

In the Control Panel, adjust:

- **Alignment** - Left, Center, or Right
- **Vertical Position** - Where titles appear (0% = top, 100% = bottom)
- **Font Size** - Size of the title text
- **Safe Margins** - Padding from screen edges

## Step 5: Configure Style

- **Text Color** - Click the color picker
- **Legibility Mode**:
  - **Text Shadow** - Subtle shadow behind text
  - **Background Box** - Semi-transparent box behind text
  - **None** - Plain text only
- **Box Opacity** - Adjust transparency of background box

## Step 6: Connect Your Output Display

1. Connect your projector or secondary monitor
2. Select it from the **"Output Display"** dropdown
3. Click **"Start Output"**

The output window will open fullscreen on the selected display.

## Step 7: Use Calibration (Optional)

Click the **Calibration** button to show:
- Safe area boundaries (yellow dashed lines)
- Center crosshair
- Corner markers

Use this to verify your output is properly positioned on the projection surface.

## Step 8: Save Your Preset

Once everything is configured:
1. Scroll to the **Presets** section
2. Click **"Save Current as Preset"**
3. Enter a name (e.g., "Carmen Opening Night")
4. Click **Save**

---

# 5. Running a Performance

## Before the Show

1. Load your preset or configure manually
2. Start the output window
3. Navigate to cue 1
4. Verify titles are hidden (Titles OFF) for audience entry

## During the Performance

### Advancing Cues

- Press **→** (Right Arrow) or **Space** to go to the next cue
- Press **←** (Left Arrow) or **Backspace** for the previous cue
- Click any cue in the Cue Panel to jump directly

### Show Controls

| Button | Keyboard | Purpose |
|--------|----------|---------|
| **Titles** | T or H | Show/hide titles |
| **Blackout** | B | Black screen (emergency or scene change) |
| **Freeze** | F | Pause output (changes won't show until unfrozen) |

### Understanding Freeze

The **Freeze** button is a powerful safety feature. When activated:

- The audience screen **stays exactly as it is**
- You can navigate cues, change settings, and prepare changes on the operator side
- **Nothing updates on the audience screen** until you unfreeze

**When to use Freeze:**

1. **Recovering from a mistake** - If you accidentally skip ahead, press F to freeze, navigate back to the correct cue, then unfreeze. The audience sees nothing.

2. **Preparing the next section** - Load a different background for the next act without it flashing on screen while you set it up.

3. **Handling stage delays** - If the performance pauses unexpectedly (actor issue, technical problem), freeze the current title while you wait.

4. **Checking ahead** - Need to preview a future cue? Freeze, jump ahead to check it, jump back, unfreeze - the audience never knows.

### Emergency: Panic Shortcut

There is no visible panic button - instead, press the **Escape** key to immediately:
- Activate blackout
- Hide titles

Use this keyboard shortcut if something goes wrong and you need to clear the screen instantly.

### Jumping to a Specific Cue

1. Press **G** or click the cue counter in the top bar
2. Enter the cue number
3. Press Enter or click **Go**

### If the File Changes

If someone edits the surtitles file during the show:
- An orange banner appears: "File has changed on disk"
- Click **"Reload Now"** when safe to do so
- Your current cue position is preserved

## After the Show

- Press **B** to blackout for audience exit
- Close the output window via the Control Panel
- Your session is automatically saved

---

# 6. Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **→** or **Space** | Next cue |
| **←** or **Backspace** | Previous cue |
| **T** or **H** | Toggle titles on/off |
| **B** | Toggle blackout |
| **F** | Toggle freeze |
| **Escape** | Panic (immediate blackout + hide titles) |
| **G** | Jump to cue dialog |

> **Note:** Shortcuts only work when you're not typing in a text field.

---

# 7. Presets

Presets save your complete show configuration:

- Surtitles file path
- Parsing mode
- All backgrounds
- Layout settings
- Style settings

## Saving a Preset

1. Configure your show
2. Go to **Presets** section in Control Panel
3. Click **"Save Current as Preset"**
4. Enter a name and click **Save**

## Loading a Preset

1. Select from the dropdown
2. Click **Load**
3. If the surtitles file is missing, you'll see a warning

## Preset Tips

- Create separate presets for different shows
- Include the date in preset names for revivals
- Re-save presets after making changes

---

# 8. Troubleshooting

## License Key Issues

**"Invalid license key"**
- Verify you entered the key exactly as shown in your purchase confirmation email
- Copy and paste the key to avoid typos
- Check you're using the key for the correct product

**"Unable to connect to license server"**
- Check your internet connection
- Try again in a few minutes
- Contact Operactive Arts if the problem persists

**"This license is already activated on another device"**
- Each license key works on one device only
- Contact support@operactive.co.uk to transfer your license to a new device

**"This license expired"**
- Your license period has ended
- Purchase a new license to continue using the software

## Titles Not Appearing

1. Check that **Titles** is ON (green button)
2. Verify **Blackout** is OFF
3. Ensure the current cue is not blank
4. Check that output window is open (**LIVE** indicator)

## Output on Wrong Display

1. Close the output window
2. Select the correct display from the dropdown
3. Start output again

## Video Not Playing

- Video plays when the background becomes active
- Videos must finish loading before playback is smooth
- Try smaller file sizes for faster loading

## App Won't Start

1. Check Windows Firewall isn't blocking it
2. Run as Administrator
3. Reinstall if necessary

## File Changes Not Detected

- Ensure the file is saved (not just open in editor)
- The orange banner should appear within a few seconds
- Click **Reload** manually if needed

---

# 9. Quick Reference Card

## Show Day Checklist

- [ ] Load surtitles file
- [ ] Add/verify backgrounds
- [ ] Configure layout and style
- [ ] Connect output display
- [ ] Start output
- [ ] Test calibration
- [ ] Navigate to cue 1
- [ ] Hide titles (T)
- [ ] Save preset

## Key Shortcuts

```
NEXT CUE .......... → or Space
PREV CUE .......... ← or Backspace
TITLES ............ T or H
BLACKOUT .......... B
FREEZE ............ F
PANIC ............. Escape
JUMP TO CUE ....... G
```

## Status Indicators

- **LIVE** (green, pulsing) = Output window active
- **OFFLINE** (gray) = No output
- **Titles ON** = Green button
- **Titles OFF** = Gray button
- **BLACKOUT** = Red border on button
- **FROZEN** = Yellow button

---

# Support

For technical support, please contact:

**Operactive Arts**

When contacting support, please provide:
- Your Device ID (shown on Entry Code screen)
- Description of the problem
- Screenshots if possible

---

*Surtitles-in-a-box User Manual v1.1.0*
*Copyright 2026 Operactive Arts*
*All rights reserved.*
