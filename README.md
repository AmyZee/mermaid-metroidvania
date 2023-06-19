# mermaid-metroidvania

A game in the style of the late Aquaria, or the water levels of Rayman Legends.

You control a mermaid who swims through a maze of water rooms, encountering obstacles like streams and walls, and unbreathable air and toxic water; all while slowly increasing your power through permanent power-ups which control the water.

The target platforms are mobile and possibly iPad Mini. Device orientation is assumed to be portrait.

## Controls

The game's primary control system uses the accelerometer (through `window.addEventListener("deviceorientation", function(){})`), with Touch as a secondary input for activated power-ups.

I chose the accelerometer so fingers on the screen don't hide potential obstacles and one can see the entire screen.
