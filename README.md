## Introduction

This project contains functions that enable pan and pinch to zoom from within the Rive file. This way you can zoom in without losing quality. 

A modified version of RiveScreen.cs is provided which also prevents button click during panning/zooming and will prevent panning/zooming during button click.

Currently only a screen overly mode is supported which draws one artboard over the entire screen. If you need to draw the artboard in a frame, additional coordinate mapping is required.

This project uses the new Unity Input system and works both with a mouse, track pad, and touch screen. In order to integrate this into your own project, you have to follow a specific workflow, described below.

The logic will not allow panning or zooming outside of the artboard boundaries, so you need to zoom in before pan is possible.

## Running locally

![Alt text](readme-png/origin%20coordinate.png?raw=true)


For the other projects be sure to select a **scene** if nothing is rendering.
