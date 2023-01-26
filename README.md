# Metroid Prime Fan Hacks

A growing collection of fan hacks for Metroid Prime 1 (GC) - Heavily inspired by randomizer

## How to play

### Requirements
- Windows 10+
- Metroid Prime in ISO format

1) Browse the [hacks](./hacks/) directory and decide which fan hack you want to play

2) 

## Features

Fan hack authors have access to a large variety of features which include (but is not limited to) the following:

- Custom Items/Locations
- Custom Elevators
- Custom Doors
- Custom Blast Shields
- Place custom objects such as water, platforms, boxes, grapple points
- Remove vanilla objects
- Edit in-game text
- Quality of Life improvements and bugfixes

## Frequently asked questions

### Do I need to have the original North American NTSC 0-00 Release?

If it ran on the GameCube it's supported. Scan dashing is added back in to later releases, among other things.

### I want to make my own fan hack, where can I get started?

There currently is not any good documentation on how to get started with developing against the randomprime patcher API, or how to design, test and release a fan hack. Depending on the demand, I will create materials to help people get started.

If you have programming and open source project experience, you might intuit how it's done using the [Source Code](https://github.com/toasterparty/randomprime/blob/randovania/src/patch_config.rs#L636..L658), [Release Notes](https://github.com/randovania/py-randomprime/releases), and [Looking at Examples](https://github.com/toasterparty/prime-practice-world/blob/main/prime-practice-world.json).

There's also work-in-progress [GUI Program](https://github.com/meriKatt/Plandomizer-GUI/) if that you can try your luck with.

### Where's the community at?

http://discord.gg/WWGcay6

### I don't use Windows!

That's not a question, but dm me and I'll see about updating this project to be distributable to multiple platforms.

### How does it work?

My fork of [randomprime](https://github.com/toasterparty/randomprime/tree/randovania), the Rust-powered open source patcher used by [Randovania](https://github.com/randovania/randovania), includes a bunch of optional features not utilized by randomizer. Fan hacks use the same patcher API used by randovania to create their own custom.
