# Surtitles-in-a-box

## User Manual

**Version 1.2.0**

**by Operactive Arts**

---

# Table of Contents

1. [Introduction](#1-introduction)
2. [Getting Started](#2-getting-started)
3. [The Operator Interface](#3-the-operator-interface)
4. [Preparing Your Show](#4-preparing-your-show)
5. [Running a Performance](#5-running-a-performance)
6. [Remote Control](#6-remote-control)
7. [Multi-Language Output](#7-multi-language-output)
8. [Cue Annotations](#8-cue-annotations)
9. [Projects](#9-projects)
10. [Keyboard Shortcuts](#10-keyboard-shortcuts)
11. [Troubleshooting](#11-troubleshooting)
12. [Quick Reference Card](#12-quick-reference-card)

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
- **Project system** - Save and load complete show configurations
- **Remote control** - Control the show from a phone or tablet via WiFi
- **Multi-language output** - Display two languages simultaneously
- **Cue annotations** - Add operator notes to any cue

## What's New in Version 1.2.0

- **Remote Control** - Control your show from any phone or tablet on the same WiFi network
- **Multi-Language Support** - Display primary and secondary languages together (stacked or side-by-side)
- **Cue Annotations** - Add operator notes to cues for timing hints and reminders
- **Project Management** - New Project menu in top bar replaces the old Presets section
- **Background Management** - Rename backgrounds with double-click and reorder by drag-and-drop

## System Requirements

- Windows 10 or later
- Two displays recommended (operator + audience output)
- 4GB RAM minimum
- 500MB disk space
- WiFi connection (for remote control feature)

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
+-------------------------------------------------------------------------+
|                              TOP BAR                                     |
| [Project v] [Load File] [Reload] | Mode: [v] | [ProjectName] file.txt | Cue 1/42 | [Remote] | LIVE |
+-------------------------------------------------------------------------+
|                |                      |                                  |
|   CUE PANEL    |   PREVIEW PANEL      |      CONTROL PANEL               |
|                |                      |                                  |
|   1. Text...   |   [Live Preview]     |   Output Display: [v]            |
|      Note:...  |                      |   [Start Output]                 |
| > 2. Current   |   [Backgrounds]      |                                  |
|      Note:...  |   [+Add] [thumb]     |   Show Controls:                 |
|   3. Text...   |   [thumb] [thumb]    |   [Titles] [Blackout] [Freeze]   |
|                |                      |                                  |
|                |   NEXT: Preview...   |   Layout & Style...              |
|                |   Note: Next note    |   Languages...                   |
+-------------------------------------------------------------------------+
```

## Top Bar

- **Project** - Dropdown menu for project management (New, Save, Open, Delete)
- **Load File** - Open a surtitles text file
- **Reload** - Reload the current file (turns orange when file has changed)
- **Mode** - Switch between "Line by Line" and "Paragraph" parsing
- **Project Name** - Shows the current project name (if saved)
- **Cue Counter** - Shows current position (click to jump to a specific cue)
- **Remote** - Toggle the remote control panel
- **LIVE/OFFLINE** - Indicates if the output window is active

## Cue Panel (Left)

Displays your surtitles as a scrollable list:
- The current cue is highlighted in cyan
- Blank cues show "(blank)" tag
- Annotations appear below cue text with a memo icon
- Click any cue to jump to it
- Press **N** to add/edit an annotation on the selected cue

## Preview Panel (Center)

Shows exactly what the audience will see:
- Live preview updates as you navigate
- Current annotation displayed prominently below the preview
- Next cue preview with its annotation
- Background thumbnails at the bottom (drag to reorder, double-click to rename)
- Click **"+ Add"** to add new backgrounds

## Control Panel (Right)

All the controls for your show:
- Display selection and output control
- Show-safe buttons (Titles, Blackout, Freeze, Calibration)
- Layout settings (position, size, alignment)
- Style settings (color, fonts, legibility)
- Languages section (secondary language loading and display mode)

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

### Managing Backgrounds

- **Rename**: Double-click a background label to edit it
- **Reorder**: Drag and drop backgrounds to rearrange them
- **Delete**: Hover over a background and click the X button

## Step 4: Configure Layout

In the Control Panel, adjust:

- **Alignment** - Left, Center, or Right
- **Vertical Position** - Where titles appear (0% = top, 100% = bottom)
- **Font Size** - Size of the title text
- **Safe Margins** - Padding from screen edges

## Step 5: Configure Style

- **Primary Text Color** - Color for primary language text
- **Secondary Text Color** - Color for secondary language text
- **Primary Font** - Font family for primary language
- **Secondary Font** - Font family for secondary language
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

## Step 8: Save Your Project

Once everything is configured:
1. Click the **Project** dropdown in the top bar
2. Click **"Save Project"** (or **"Save Project As..."** for a new name)
3. Enter a project name (e.g., "Carmen Opening Night")

---

# 5. Running a Performance

## Before the Show

1. Load your project or configure manually
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

# 6. Remote Control

The Remote Control feature lets you control the show from any phone or tablet connected to the same WiFi network.

## Starting Remote Control

1. Click the **Remote** button in the top bar
2. The Remote Control panel opens on the right side
3. Click **"Start Remote Server"**
4. A QR code and URL will appear

## Connecting a Device

### Option A: QR Code
1. Open your phone's camera
2. Scan the QR code
3. Tap the notification to open the link

### Option B: Manual URL
1. Open a web browser on your phone/tablet
2. Type the displayed URL (e.g., `http://192.168.1.50:8080`)
3. Press Enter

### Security (Optional)
- Enable the PIN option before starting the server
- Set a 4-digit PIN that users must enter to connect
- Connected devices are shown in the Remote panel
- Click "Disconnect" next to any device to remove it

## Remote Interface

The remote interface adapts to screen size:

### Phone (Simplified)
- Large PREV / NEXT buttons for one-handed operation
- Current cue display and number
- Next cue preview
- Titles and Blackout toggles
- Background tiles for quick switching

### Tablet (Enhanced)
- All phone features plus:
- Scrollable cue list (tap to jump)
- Freeze toggle
- Current annotation display

## Remote Control Best Practices

- Test the connection before the show
- Keep your phone charged
- Consider a backup operator on the main computer
- The remote shows connection status - watch for disconnections
- Background tiles show colors/labels to help identify backgrounds

---

# 7. Multi-Language Output

Display surtitles in two languages simultaneously for international audiences.

## Loading a Secondary Language

1. Load your primary surtitles file first
2. In the Control Panel, go to the **Languages** section
3. Click **"Load Secondary File"**
4. Select your secondary language file

> **Important:** Both files should have the same number of cues. A warning appears if cue counts don't match.

## Display Modes

Choose how languages are displayed:

| Mode | Description |
|------|-------------|
| **Primary only** | Show only the primary language |
| **Secondary only** | Show only the secondary language |
| **Stacked** | Both languages stacked vertically |
| **Side by side** | Languages displayed next to each other |

## Configuration Options

When using Stacked or Side-by-side modes:

- **Secondary Position** (Stacked only): Choose if secondary appears above or below primary
- **Size Ratio**: Adjust relative size of primary vs secondary text (30%-70%)

## Styling Languages

In the Style section:
- **Primary Text Color**: Color for primary language
- **Secondary Text Color**: Color for secondary language
- **Primary Font**: Font for primary language
- **Secondary Font**: Font for secondary language

## Tips for Multi-Language Shows

- Use distinct colors for each language to help audiences identify them
- Consider using different fonts (e.g., serif vs sans-serif)
- Test readability from the back of the venue
- The Preview Panel shows exactly how both languages will appear

---

# 8. Cue Annotations

Add operator notes to any cue - perfect for timing hints, conductor cues, or stage directions.

## Adding an Annotation

### Method 1: Keyboard
1. Navigate to the cue
2. Press **N**
3. Type your note
4. Press **Enter** to save (or **Escape** to cancel)

### Method 2: Mouse
1. Hover over a cue in the Cue Panel
2. Click the note icon or **[+ Add note]** link
3. Type your note
4. Click away or press Enter to save

## Viewing Annotations

Annotations appear in multiple places:

- **Cue Panel**: Below each cue's text with a memo icon
- **Preview Panel**: Current cue's annotation prominently displayed
- **Preview Panel**: Next cue's annotation shown in the "NEXT" preview
- **Remote Control**: Visible on tablet view

## Editing Annotations

1. Click on an existing annotation
2. Edit the text
3. Press Enter to save
4. To delete, clear all text and save

## Annotation Tips

- Keep notes brief - they should be glanceable
- Use consistent abbreviations (e.g., "Cond." for conductor)
- Include timing cues: "Wait for aria to finish"
- Note stage positions: "After Juliet reaches balcony"
- Mark tricky transitions: "Quick - 2 sec gap"

## Annotations and Projects

Annotations are saved with your project. When you:
- **Save Project**: All annotations are included
- **Open Project**: Annotations are restored
- **Reload File**: Annotations are preserved (warning if cue count changes)

---

# 9. Projects

Projects save your complete show configuration and replace the old Presets system.

## What's Saved in a Project

- Surtitles file path (primary)
- Secondary surtitles file path (if loaded)
- Parsing mode
- All backgrounds
- Layout settings
- Style settings
- Language display settings
- All cue annotations
- Selected output display

## Project Menu

Access project functions via the **Project** dropdown in the top bar:

| Option | Description |
|--------|-------------|
| **New Project** | Clear everything and start fresh |
| **Save Project** | Save to current project (prompts for name if new) |
| **Save Project As...** | Save with a new name |
| **Open Project...** | Open the project browser |
| **Delete Project...** | Delete a saved project |

## Creating a New Project

1. Click **Project** → **New Project**
2. If you have unsaved work, confirm you want to clear it
3. All settings, cues, and annotations are reset

## Saving Your Work

### First Time Save
1. Click **Project** → **Save Project**
2. Enter a project name
3. Click OK

### Subsequent Saves
1. Click **Project** → **Save Project**
2. Project saves immediately to the same name

### Save As New Project
1. Click **Project** → **Save Project As...**
2. Enter a new name
3. Click OK

## Opening a Project

1. Click **Project** → **Open Project...**
2. A modal shows all saved projects
3. Current project (if any) is highlighted
4. Click a project to open it
5. All settings, files, and annotations are restored

> **Note:** If surtitles files have been moved or deleted, a warning appears.

## Deleting a Project

1. Click **Project** → **Delete Project...**
2. Enter the project name to delete
3. Confirm deletion
4. Project is permanently removed

## Project Tips

- Save projects with descriptive names: "Carmen_2026_MainStage"
- Create separate projects for different venues
- Save a new project after significant changes
- The current project name appears in the top bar

---

# 10. Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **→** or **Space** | Next cue |
| **←** or **Backspace** | Previous cue |
| **T** or **H** | Toggle titles on/off |
| **B** | Toggle blackout |
| **F** | Toggle freeze |
| **Escape** | Panic (immediate blackout + hide titles) |
| **G** | Jump to cue dialog |
| **N** | Add/edit annotation on current cue |

> **Note:** Shortcuts only work when you're not typing in a text field.

---

# 11. Troubleshooting

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

## Remote Control Issues

**Can't connect to remote**
- Ensure phone/tablet is on the same WiFi network
- Check the URL is typed correctly
- Try refreshing the browser
- Restart the remote server

**Remote disconnects frequently**
- WiFi signal may be weak
- Move closer to the router
- Consider a dedicated WiFi network for the show

**Commands not working from remote**
- Check connection status indicator
- Refresh the remote page
- Restart the remote server if needed

## Multi-Language Issues

**Secondary file won't load**
- Ensure primary file is loaded first
- Check file is plain text (.txt)
- Verify file uses UTF-8 encoding

**Cue count mismatch warning**
- Both files should have equal cue counts
- Check for extra blank lines
- Review file parsing mode

## App Won't Start

1. Check Windows Firewall isn't blocking it
2. Run as Administrator
3. Reinstall if necessary

## File Changes Not Detected

- Ensure the file is saved (not just open in editor)
- The orange banner should appear within a few seconds
- Click **Reload** manually if needed

---

# 12. Quick Reference Card

## Show Day Checklist

- [ ] Open project (or load files manually)
- [ ] Verify all backgrounds are present
- [ ] Check secondary language file (if using)
- [ ] Review annotations for timing cues
- [ ] Connect output display
- [ ] Start output
- [ ] Test calibration
- [ ] Set up remote control (if using)
- [ ] Test remote connection
- [ ] Navigate to cue 1
- [ ] Hide titles (T)
- [ ] Save project

## Key Shortcuts

```
NEXT CUE .......... → or Space
PREV CUE .......... ← or Backspace
TITLES ............ T or H
BLACKOUT .......... B
FREEZE ............ F
PANIC ............. Escape
JUMP TO CUE ....... G
ADD/EDIT NOTE ..... N
```

## Status Indicators

- **LIVE** (green, pulsing) = Output window active
- **OFFLINE** (gray) = No output
- **Titles ON** = Green button
- **Titles OFF** = Gray button
- **BLACKOUT** = Red border on button
- **FROZEN** = Yellow button
- **Project Name** = Shown in top bar when project is saved

## Remote Control

1. Click **Remote** button
2. Start server
3. Scan QR or type URL
4. Control show from phone/tablet

## Multi-Language Quick Setup

1. Load primary file
2. Go to Languages section
3. Load secondary file
4. Choose display mode (Stacked/Side-by-side)
5. Adjust colors and fonts

---

# Support

For technical support, please contact:

**Operactive Arts**
Email: support@operactive.co.uk

When contacting support, please provide:
- Your Device ID (shown on Entry Code screen)
- Software version (1.2.0)
- Description of the problem
- Screenshots if possible

---

*Surtitles-in-a-box User Manual v1.2.0*
*Copyright 2026 Operactive Arts*
*All rights reserved.*
