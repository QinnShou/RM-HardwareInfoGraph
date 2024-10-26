# QS Hardware Info Graph Rainmeter Skin

![Rainmeter HardwareInfoGraph Screenshot](https://github.com/QinnShou/RM-HardwareInfoGraph/blob/main/Screenshot.png) 
![Rainmeter HardwareInfoGraph Screenshot2](https://github.com/QinnShou/RM-HardwareInfoGraph/blob/main/Screenshot%202.png)

## Overview
The QS Hardware Info Graph is a Rainmeter skin designed to display real-time hardware information in a grid format. This skin is perfect for users who want to keep a close eye on their system's performance with a sleek and informative display.

## Features
- Real-time hardware information display
- Highly customizable (Color, Size, Padding, etc.)
- Grid auto-scaling based on size and padding.
- High temperature warning
- Clean and minimalist design

## Requirements
- Rainmeter 4.0 or higher.
- HWiNFO64 for hardware data.

## Installation
1. Download and install Rainmeter from [Rainmeter's official website](https://www.rainmeter.net/).
2. Download and install [HWiNFO64](https://www.hwinfo.com/download/).
3. Config HWiNFO64 to enable memory sharing and Gadget report. [Rainmeter tutorial](https://docs.rainmeter.net/tips/hwinfo/).
![Rainmeter-HWiNFO64 Data Pull How-to](https://github.com/QinnShou/RM-HardwareInfoGraph/blob/main/Screenshot%20Sensor%20Howto.png)
5. Run Windows CMD: reg query HKEY_CURRENT_USER\SOFTWARE\HWiNFO64\VSB
7. Download and install the QS Hardware Info Graph skin.
8. Modify the ini file for the correct report ID.
10. Load the skin via the Rainmeter Manage window.

## Customization
You can customize various aspects of the skin, such as graph width, height, and other visual elements etc., by editing the `.ini` file [Variables] section.

  ```ini
[Variables]
MeterType=Line
LineWidthValue=1
;Try out Line or Histogram!

AntiAliasValue=1
; Graph Width, Height
GraphW=80
GraphH=80

; Graph Padding
GraphWPad=4
GraphHPad=4

; Text Labels
TextPadX=4
TextPadY=0
FontFaceValue=OCR A
FontSizeValue=12
FontWrapSpace=8
FontAntiAlias=1
FontColorValue=255,255,255,160
FontColorValue2=255,255,255,200
StringAlignValue=LeftTop
InlineSetting1=Shadow |0|2|2|0,0,0,200
InlineSetting2=Shadow |0|2|2|0,0,0,200

; Container Round Edge
ShapeValue=Rectangle 0, 0, #GraphW#, #GraphH#, 5, 5
...
  ```

## Authors
- QinnShou (author of script)
- YeyeBBC (author of several function)
- ChatGPT by OpenAI (assisting with basic script structure, rainmeter Q&A, writting this readme.md)

This work is licensed under the Creative Commons Attribution-Non-Commercial-Share Alike 3.0.
