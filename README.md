# Lemon
A macOS speedrunning timer.

There aren't really any good speedrunning timers available on macOS, so I decided to make one. The aim of this project is to make a fully functional speedrunning timer for macOS which is similar to LiveSplit. Some of the features that it will have are:
<ul>
  <li>a timer</li>
  <li>a variety of timing options (real time, in game time, etc.)</li>
  <li>global hotkeys</li>
  <li>an autosplitter</li>
  <li>a variety of customisability options</li>
</ul>

This project will hopefully make speedrunning more accessible to macOS users. However, this project is still in development and unstable, so use it with care.

## Features
As of current, Lemon contains the following features:
<ul>
  <li>a timer</li>
  <li>a window that always shows on top, even on fullscreen apps</li>
  <li>a customisable global hotkey</li>
  <li>some customisability options</li>
</ul>

## How to use
When you first open Lemon, you will find a small window with a timer on it and nothing else. With the app selected, you can scroll down and across with a trackpad or mouse or adjust the window size to view some basic settings and controls.

### Start Button
The start button will start the timer. It will also resume the timer if it has been paused previously.

![Start Button GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/startBtn.gif)

### Stop Button
The stop button will pause the timer. It can then be resumed again by pressing the start button.

![Stop Button GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/stopBtn.gif)

### Reset Button
The reset button will stop the timer and reset it.

![Reset Button GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/resetBtn.gif)

### Moving and Resizing the Window
The window can be resized by dragging its corners and edges. To move the window around the screen, you need to drag the square in the top left of the window.

![Moving and Resizing GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/moveAndResize.gif)

## Options
The app features a variety of options underneath the control buttons, all of which provide customisability to the app.

### Timer Decimal Format
This setting allows you to pick from four options:
<ul>
  <li>seconds (0 decimal places)</li>
  <li>tenths (1 decimal place)</li>
  <li>hundredths (2 decimal places)</li>
  <li>miliseconds (3 decimal places) (default)</li>
</ul>

Depending on the selected option, a different number of decimal places will appear behind the seconds on the timer, affecting the accuracy of the time displayed on the screen.

![Timer Decimal Format Option GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/timerDecimalFormat.gif)

### Text Align
This setting allows you to pick from two options:
<ul>
  <li>right (defualt)</li>
  <li>left</li>
</ul>

Depending on which option you select, the timer will align to either side of the window.

![Text Align Option GIF](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/textAlign.gif)

### Start/Stop Hotkey
This setting allows you to set the global hotkey that starts and stops the timer. By default this is the space bar. When this hotkey is pressed, no matter what application is selected, the timer will either start or stop.

Type the preferred keybind into the text box then click 'Apply' and your hotkey will be updated. The 'Reset' button will set the contents of the text box to the current hotkey, the 'Reset to default' will reset the hotkey back to space bar, and the 'Help' button will provide more information about hotkeys.

![Start and Stop Hotkey Picture](https://github.com/kris-stockenstroom/lemon/blob/main/readme-images/startStopHotkey.png)

## Support
If you find any issues with the application, need help with using it or think that there's something missing, use the Issues page on this GitHub page. Check if you issue has already been discussed and if it hasn't, create a new one!

<br>
© 2022 Kristoffer Stockenstroom. All rights reserved.

# Patch Notes:
