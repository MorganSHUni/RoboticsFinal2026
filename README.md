# PDR System
Entry for the final robotics assessment, 2026.
Due to File size issues, the associated video will be linked here:
[https://drive.google.com/drive/folders/1Vdectq-4y7cVvt1QVIeKVIytx-RqZOGm]

## Description
The "Personal Delivery Robot" is a small robot designed to deliver items between rooms in your house.
Originally designed for flats where a ward lives with, or is regularly visited by, a carer, the bot uses colour sensing to travel to various rooms depending on the user's request.

## Usage
The PDR can:
1. Identify "stations" and travel between them

## What is needed to operate the PDR?
Other than the robot itself, the other thing needed is a FAT32-formatted microSD card.

## How to use the PDR?
### Initial Setup
1. Using red to indicare routes and blue to indicate a station, determine which area is your "Base Station".
  The "Base Station" is the location your PDR will use to determine routes to other rooms, and also, where it will go to power down.
2. Mark an area completely in blue tape.
  A 10x10cm square is recommended, but please ensure it is at least 40cm away from any permanent stationary objects.
3. Repeat for all the areas you would like the PDR to visit.
4. Between the areas, using red tape, mark circuit between the stations using only straight lines (of width 6cm).
5. Turn on the PDR (with the microSD card inserted) and set it at the "Base Station" facing the direction you want it to go.
6. Click "Add Stations" and enter the number of stations set up and connected, not including the "Base Station".

### Main Menu
Everything the PDR can do is accessible through the Main Menu. 
All that is needed is to press the appropriate buttons, and for the PDR to be located at a Station.
1. Add Stations -> Press Left button
3. Toggle Lid -> Press Click button
4. Travel to Station -> Press Right button
### Add Stations
This will cause the PDR to recalibrate, so please turn the PDR off, establish stations, and connect routes **before** recalibrating the PDR.


# Development Process
**Technology Used:** VEX EXP

**Research:** Please see the Design Specification for our initial development plans

## AI Transparency Statement:
In this project we have used AI up to **AITS2** - AI was used to aid with initial research and concept development, and for suggesting alternatives.
In particular, AI was used to facilitate concepts for the Design Specification, but not used in generating code nor any other development areas.


## References
##### Source - https://stackoverflow.com/a/60982598
    # Posted by Aplet123
    # Retrieved 2026-04-13, License - CC BY-SA 4.0
    actualData = [x.decode(encoding="utf-8") for x in rawData.split(b"\x00") if len(x)]

