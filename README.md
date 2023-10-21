# MasterTracker-1541-Drive-Enhancement

The MasterTracker is a 1541 drive enhancement that is built into the 1541 disk drive.  It is a semi-distructive installation, as some material from the case (plastic behind the original 1541 badge must be removed).  It is however reversable, as the original badge (if removed nicely) can be placed back on the drive, disguising the removed material if glued back in place.  At it's core, the digital track display is a step counting circuit design, capable of counting whole and half tracks.  Unlike "ram reader" style trackers, the circuit used in the Mastertracker (© WJW 1989) cannot be defeated by any software or acceleration/speeder enhancement applied to the 1541.

![rs640_IMG_2400](https://github.com/COREi64/MasterTracker-1541-Drive-Enhancement/assets/37495485/8c898975-dd9f-4e99-8e9f-433dabef69a9)

The MasterTracker device was a collaboration between three individuals from the Commodore community.
- Wes256 provided the use of the design schematics for the DTD (digital track display) and the DLD (density level display).
- As a paid contractor and team collaboration member, DDI provided all the PCB design/layup work as well as providing circuits for the other functional elements contained in the MasterTracker design (outside of the DTD and DLD).  Development and test boards were created in eCAD by DDI.
- COREi64 100 percent funded, built and tested in collaboration with the other above noted contributors.  Captive pin UC2 tap was designed by COREi64.
- Creative input is shared between DDI and COREi64 on the MasterTracker project.  Acceptance of the final design was executed by COREi64.

COREi64 is the project owner and retains the sole rights of distribution with respect to the completed Mastertracker device.

The MasterTracker contains the following functional elements in it's design.
- Illuminated left-side logo (DDI)
- Rolling light bars on write signal (DDI)
- Drive reset button (DDI)
- Digital Track Display (Wes256 © WJW 1989)
- Density Level Display (Wes256 © WJW 1989)
- Audio Soundtrack/Sync mark audio circuit (Wes256 © WJW 1989)
- Digital Track Display Sync (Wes256 © WJW 1989)
- Drive ID changer, display and button to cycle (DDI)
- Drive ROM changer, multicolor display and button to cycle (DDI)
- 1541 Illuminated write protect indicator (DDI)
- Optional step LED (in place of the stock power LED) (DDI)

This is NOT an open source device.  Gerbers, design files and schematics will not be shared with the community.  The track display and density display circuits are © WJW 1989 and protected by US Copyright law.  The MasterTracker device and project is owned by COREi64, and was designed in collaboration with Wes256 (WJW), and DDI.  Track Display (DTD) and Density Level Display (DLD) remain under the sole ownership of WJW © 1989.  Although a valued and key contributor to the MasterTracker project, DDI retains no ownership or residuals in this project.

The device itself will be available through https://COREi64.com in TWO versions.

1. A very limited number of completed assembled and tested units will be made available.  These will be made available for a limited time.
2. The MasterTracker will be offered as a PCB kit.

MasterTracker Assembled Units.
Initially, there will be a number of assembled units available through COREi64.  This will only be for a limited time, as they are quite time consuming to build, and are not cost effective for me to build.

MasterTracker PCB kits.
This is the reason you're seeing this Github.  A PCBkit for the MasterTracker will be made available, which is THE MOST COST EFFECTIVE way you can get a MasterTracker for your drive.  It will contain the following items.
- 1 Stencil PCB (for use in removing the correct amount of material from your drive for installation, and for locating the four screw holes)
- 1 PCB Bezel
- 1 PCB Display board will all SMD parts included and pre-soldered on the board
- 1 PCB MasterTracker main logic board with all SMD parts included and pre-soldered on the board
- 1 PCB UC2 tap board
- 1 PCB ROM switcher board with all SMD parts included and pre-soldered on the board

No additional components will be provided in the PCB kit.  This is, save for the SMD work that is pre-done for you, and entirely "thru-hole" soldering project.  It is easily completed by most Commodore enthusiasts that are handy with a soldering iron.  The purchase of parts are the responsibility of the kit builder.  Mouser part number, and part descriptions will be provided in the various BOM lists.  BOM lists will be found on this github pertaining to each circuit board.

An announcement will be made on social media when this kit becomes available, and this Github will be updated accordingly.
