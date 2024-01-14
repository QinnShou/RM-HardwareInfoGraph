# QS Hardware Info Graph Rainmeter Skin

![Rainmeter HardwareInfoGraph Screenshot](https://github.com/QinnShou/RM-HardwareInfoGraph/blob/main/Screenshot.png)

## Overview
The QS Hardware Info Graph is a Rainmeter skin designed to display real-time hardware information in a grid format. This skin is perfect for users who want to keep a close eye on their system's performance with a sleek and informative display.

## Features
- Real-time hardware information display.
- Highly customizable.
- Grid auto-scaling.
- Clean and minimalist design.

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
  LineWidthValue=2
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
  FontFaceValue=Fixedsys
  FontSizeValue=12
  FontWrapSpace=4
  FontAntiAlias=0
  FontColorValue=255,255,255,220
  FontColorValue2=220,220,220,160
  StringAlignValue=LeftTop

  ; Container Round Edge
  ShapeValue=Rectangle 0, 0, #GraphW#, #GraphH#, 5, 5
  ...
  ```

## Authors
- ChatGPT4 by OpenAI
- QinnShou
- YeyeBBC

This work is licensed under the Creative Commons Attribution-Non-Commercial-Share Alike 3.0.
