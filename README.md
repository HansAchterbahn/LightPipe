# LightPipe

LightPipes are colorful lighting pipes that can be combined to create complex and interesting geometries. The LightPipe project is based on the easily addressable APA102 RGB LEDs. Each LED in a LightPipe geometry can be addressed individually.

The LightPipe project uses one PCB with a slightly modified assembly as input and output PCB. On the input side, it simply accepts data from a 3.5 jack and power from an XT30 connector. On the output side, the data is send to the next LightPipe via the same jack and XT30 power connector.

An additional 3.5 female connector is used to tunnel the data from the output PCB back to the input PCB. With this arrangement it is possible to realize a complete tree structure therefore to create arbitrary geometries.

In this main repository you will find links to all repositories related to the LightPipe Project.

*Fork me and have fun!*

![LightPipe first Prototyep @ Neotopia Hackspace in Göttingen](https://wiki.cccgoe.de/data/images/0/03/LightPipe--Lichteffekt1.jpg)
**LightPipe - First Prototyep in 2020 @ Neotopia Hackspace in Göttingen**




## Submodules

## Hardware

| Type                               | URL                                                |
| ---------------------------------- | -------------------------------------------------- |
| Input/Output PCB (made with KiCad) | https://github.com/HansAchterbahn/LightPipe-Kicad  |
| Spacer (made with FreeCad)         | https://github.com/HansAchterbahn/LightPipe-Spacer |
| EndCap (made with FreeCad)         | https://github.com/HansAchterbahn/LightPipe-EndCap |

### Software

| Type                               | URL                                                |
| ---------------------------------- | -------------------------------------------------- |
| Driver                             | https://git.cccgoe.de/lightpipe/driver             |
| Effects Library                    | https://git.cccgoe.de/lightpipe/effects            |
