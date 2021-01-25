# OSAK
On-Screen ANSI Keyboard v3 (AutoHotkey)

This customizable, non-interactive keyboard for Windows only flashes what you type. It may be used to:
    Memorize the ANSI keyboard format without looking down
    Record your keystrokes (like in a game or something, although full-screen games might cover it)
    Check key functionality on a damaged keyboard
    Revel in or lament over your typing speed

Demonstration GIF of the OSAK with its default settings:
https://drive.google.com/file/d/1Z15OT6rMr47JdfS6Z5uVaKm6PUaMjboe/view

1. Download AutoHotkey from https://www.autohotkey.com
2. Save OSAK.AHK to your Windows startup folder

This is the third version of the On-Screen Keyboard in AutoHotkey's official Script Showcase.

Version 3:
/u/anonymous1184 used invisible characters (to differentiate Numpad numbers from their counterparts) and labels (to eliminate version 2's lists of manual character entries).
/u/KeronCyst added all buttons to the right of Backspace, added a Ctrl-` visibility toggle, cleaned up code descriptions, and made the keyboard click-through/non-interactive by default.
Both redditors made aesthetic improvements (symbols + name changes) and fixed various flashing problems.

Version by Lehnemann added color-flashing via progress bars:
https://autohotkey.com/board/topic/94703-another-approach-to-a-virtual-keyboard/

The original by Jon: https://www.autohotkey.com/docs/scripts/index.htm

Press Ctrl-` or double-click (or right-click) the tray icon to toggle visibility of the keyboard.

Run a search for and delete the following to make the keyboard:
 • Clickable (Escape will then close the keyboard if it's focused on):
       +E0x20
 • Draggable:
       -Caption

Run a search for "Transparency" and edit the number to make it more/less opaque.
Run a search for "BackgroundRed" and edit "Red" to change the flash color.
Usable colors: https://www.autohotkey.com/docs/commands/Progress.htm#colors
