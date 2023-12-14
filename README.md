# MasterTracker-1541-Drive-Enhancement

The MasterTracker is a 1541 visual drive enhancement that is built into the 1541 disk drive.  It is a semi-destructive installation, as some material from the case (plastic behind the original 1541 badge must be removed).  It is however reversable, as the original badge (if removed nicely) can be placed back on the drive, disguising the removed material if glued back in place.  At it's core, the digital track display is a step counting circuit design, capable of counting whole and half tracks.  Unlike "ram reader" style trackers, the circuit used in the Mastertracker cannot be defeated by any software or acceleration/speeder enhancement applied to the 1541.  It will accurately display head movement and positional information as fast as the drive head can move, with no delay or lag.

This github exists to provide support documentation those who decide to build a MasterTracker for their 1541.

![IMG_2400](https://github.com/COREi64/MasterTracker-1541-Drive-Enhancement/assets/37495485/f1bec15d-2ff6-4713-a599-a5400386d66e)

The MasterTracker device was a collaboration between three individuals from the Commodore community.
- Wes256 provided the use of the design schematics for the DTD (digital track display) and the DLD (density level display).
- As a paid contractor and team collaboration member, DDI provided all the PCB design/layup work as well as providing circuits for the other functional elements contained in the MasterTracker design (outside of the DTD and DLD).  Development and test boards were created in eCAD by DDI.
- COREi64 100 percent funded, built and tested in collaboration with the other above noted contributors.  Captive pin UC2 tap was designed by COREi64.
- Creative input was shared between DDI and COREi64 on the MasterTracker project until October 2023.
- The photo provided is of the first functional prototype.  The look and function will continue to evolve until the project is announced complete.  DDI's creative input, and complete involvement in this project as well as any spin-off projects ceased in October 2023, however development has not yet been completed.  All of the boards, appearance and function are subject to change without notice.  These changes will move forward and align with the creative vision of Wes256 and COREi64. 

The MasterTracker, when completed, contains the following functional elements in it's design, element author noted in brackets.
- Illuminated left-side logo (DDI)
- Rolling light bars on write signal (Designed by DDI, functionally revised by Wes256)
- Drive reset button (DDI)
- Digital Track Display (Wes256)
- Density Level Display (Wes256)
- Audio Soundtrack/Sync mark audio circuit (Wes256)
- Digital Track Display Sync (Wes256)
- Drive ID changer, display and button to cycle (DDI)
- Drive ROM changer, multicolor display and button to cycle (DDI)
- 1541 Illuminated write protect indicator (DDI)
- Optional step LED (in place of the stock power LED) (DDI)

This is NOT an open source device.  **It is however a "Build it Yourself" project, where you purchase the board set from COREi64.com.**  You may then order the parts based on the BOM lists found on this github.

The track display and density display circuits are © WJW 1989 and protected by US Copyright law.  The MasterTracker device and project is owned by COREi64, and was designed in collaboration with Wes256 (WJW), and DDI.  Track Display (DTD) and Density Level Display (DLD) remain under the sole ownership of Wes256.  Although a valued and key contributor to the MasterTracker project, DDI has withdrawn from this project.  His contributions to this project will not be forgotten.

The only difficult to source component is the 7496 5-bit Shift Register IC.  This is the only electronics component that you may optionally purchase along with the PCB set from the COREi64.com site.

The PCB package will include the following:

- 1 x MasterTracker Display Board and Bezel
- 1 x MasterTracker Main PCB (your choice of SMD main board or through hole main board)
- 1 x UC2 Tap Board
- 1 x Drive ROM Adapter Board
- 1 x Cut Stencil (used to cut the opening in the face of the drive)
