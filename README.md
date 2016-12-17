# alfred-volume
Alfred workflow for controlling system volume

This workflow allows for control of the system volume. It broadly emulates the keystrokes of F10/F11/F12 - this is usually simulated by `tell application "System Events" to key code [73/74/75]`, however this has been broken for some time (it works for most keys, but not for 73/74/75).

It is useable from both the standard Alfred interface (keyword `Volume`, arguments `up`,`down`,`nudge up`,`nudge down`,`mute`) or through Alfred Remote.

There are 16 standard volume 'steps' from 0 to 100. Using alt+shift+(F10/F11) allows this to be extended to 64 steps. A press of volume up/down will set the volume to the next step up/down, and likewise with the nudge up/down. The value of the 'steps' are in the scripts. When using mute, the volume setting is saved (this replicates normal macOS behaviour). For those interested, Audio Midi Setup.app allows you to view a decimal view of current volume.

The main icon is the macOS Sound.prefpane icon. The individual button icons in the Remote view are slightly modified (white + centred) versions of the macOS taskbar volume icons.
