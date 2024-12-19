# Vuo-PlayPresentation
Vuo project for the Play Presentation app

## Installation

- Build MacOS app using Vuo

## Usage

- When starting the app, choose a directory of videos to use as presentation slides
  - Videos will be sorted alphanumerically (depends on Vuo sort algorithm and may not match MacOS Finder sorting order)
  - The first video will automatically start to play
- Keyboard shortcuts:
  - `R` resets to the first video in the list
  - `F` toggles fullscreen
  - `←` navigates to the previous video in the list
  - `→` navigates to the next video in the list (when starting a presentation, this plays the first video)
- File naming:
  - videos with `loop` in the file name (case insensitive) will play on repeat until navigated away from
  - videos with `next` in the file name (case insensitive) will automatically start the next video in the list upon reaching the end of the current video
