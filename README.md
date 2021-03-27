# rogue

The beginnings of a browser based adventure game. Keyboard required.

Dig tunnels on the screen with the mouse and run around in them with the keyboard for now.
Hold shift to run fast.

Currently the project is one file "index.html" self contained, and is working.

TODO:
- This code is very old, needs to be structured better and separated into modules.
- The digging and exploring mechanisms should be two separate interfaces, one for creating maps and one for playing.
- A server interface is required to serve levels, a portal system for using doors like links.
- An api should track the strokes when drawing a level, instead of saving as a bitmap.
- Alternately the levels are two monochrome images and may be compressed as .png effectively.
