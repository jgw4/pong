# About This Project

This repository contains an in-progress cleanroom reverse-engineering of the PCB for the original "PONG" arcade game released in 1972. A series of schematics is being created natively in KiCad based on a schematic created previously by "Dan" (see [PongSchematic.pdf](./doc/PongSchematic.pdf)), which itself was based off an original single-page released schematic from years ago. This schematic is then linked to a pcb file, which is ultimately intended to closely replicate the original Pong revision E circuit board, ideally as a 1:1 replacement.

The hope is that this can serve as:
1) a teaching tool for others who want to learn TTL logic
2) a diagnostic tool for those with existing pong boards
3) hobbyists that maybe want to create or modify the original board for themselves
4) a source for history and/or preservationist-minded people to appreciate the pong board digitally within a modern EDA, as PONG is considered a historically significant video game, and an impressive example of analog computing. With PONG games becoming rarer, older, and more in disrepair with each passing year, knowledge and information about the boards tend to become lost.

There are a few very useful documentation pieces out there, such as a 106-page dissection of the game by Dr. H. Holder, which I have mirrored within /doc/ in this repository.

# Status

This project is in very early stages. I have been working on this board on and off as other projects in my life come and go. If you have interest in this project, such as contributing information about the board, furthering the project, or whatever else, feel free to submit a PR or reach out.

## Schematic

The schematic is not yet complete, although all used chip symbols are placed on the root sheet

## PCB

TTL chips are roughly aligned in their final grid, although all other elements of the board are yet to be drawn or determined