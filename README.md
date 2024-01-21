# Metroid Prime Fan Hacks

A growing collection of fan hacks for Metroid Prime 1 (GC).

*Inspired by randomizer; Evolved from plandomizer*

## Requirements
- *Windows 10+
- Metroid Prime (GC) in ISO format

## How to play

1. Browse the [hacks](./hacks/) directory and decide which fan hack you want to play

2. Read the readme, and download the fan hack installer

3. Extract the contents of the fan hack into a folder

4. Double click `patch.bat` and select your Metroid Prime ISO when prompted

5. Drag and drop the freshly generated rom file into Dolphin's main window, or load onto storage media and open with Nintendont

## Features

Fan hack authors have access to a large variety of features which includes (but is not limited to) the following:

- Custom Items/Locations
- Custom Elevators
- Custom Doors
- Custom Blast Shields
- Place custom objects such as water, platforms, boxes, grapple points
- Remove objects
- Edit in-game text
- Quality of Life improvements and bugfixes

## Frequently asked questions

### Do I need to have the original North American NTSC 0-00 Release?

If it ran on the GameCube it's supported. Scan dashing is added back in to later releases, among other things.

### I want to make my own fan hack, where can I get started?

Start by reading the [Creator's Guide](./doc/readme.md).

### Where's the community at?

http://discord.gg/WWGcay6

### I don't use Windows!

Use the py-randomprime distributed via `python -m pip install --upgrade py-randomprime` to patch your ISO.

### How does it work?

[randomprime](https://github.com/randovania/randomprime), the open source patcher used by [Randovania](https://github.com/randovania/randovania), includes a bunch of optional features not utilized by randomizer. Fan hacks use the same patcher API to create their own custom layout descriptions. The patcher copies the contents of the end user's ROM into a new one, making modifications at specific file addresses as it does. This means that *there is zero copyright protected content being shared and you should take care to do the same.* 
