# About

This script provides an online toolbar that...

- monitors subject physiology
    - It automatically updates every 15 minutes (can be changed) and is also capable of manual recording.
    - The recorded values are written to the log.
- provides some buttons to change the width of the main view window
- creates predefined textmarks for TB and W stims as well as pentobarbital supplements

# How to use

1. Update global variable to their corresponding channels.
    - etChan = End-tidal CO2
    - bpChan = Continuous Blood Pressure
    - textMarkChan = TextMark (30 is spike8 default)
    - tChan = Temperature/Homeothermic Blanket
    - O2Chan = Oxygen
2. Run the script or add it to the script bar
3. Use buttons or hotkeys to perform actions
    - Hotkeys:
        - Quit: NumPad -
        - Take Stats: NumPad +
        - TB Stim ON: F9
        - TB Stim OFF: F10
        - Cannula In Mouth: F11
        - Water Stim ON: F12
        - Display Change: NumPad *
            - 1 Minute: NumPad 1
            - 5 Minutes: NumPad 5
