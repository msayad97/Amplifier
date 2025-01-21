# 1kw peak RFPA | Source Files

## General

The RFPA consists of three PCBs and a casing.
The respective BOMs of these subcomponents contain all parts of amplifier in total – there is no BOM besides these.

## PCBs

The three PCBs are:

- [MRIamp](/src/MRIamp/) (=the main RFPA boarRadio-frequency power amplifierd)
	- project file: `PCB_Project_MRIamp.PrjPCB`
	- board design file: `MRIAMP.PcbDoc`
	- bill of materials: [.csv]() (see #1) TODO
- [TrafoPCB-NoGap](/src/TrafoPCB-NoGap/) (=the PCB for the back of the RF transformer)
	- board design file: `TrafoPCB-NoGap.PcbDoc`
- [TrafoPCB-WithGap](/src/TrafoPCB-WithGap/), (=PCB for the front of the RF transformer)
	- board design file: `TrafoPCB-WithGap.PcbDoc`

The `TrafoPCB-*`-boards are essentially just pieces of FR4 with some holes and one or two copper planes, so they come without BOM and schematics.

If you're looking for Gerber exports: please refer to the respective [release notes](https://gitlab.com/osii/rf-system/rf-power-amplifier/1kw-peak-rfpa/-/releases).

## Casing

The files have been created with Schaeffer's [Front Panel Designer](https://www.frontpanelexpress.com/front-panel-designer) and are available in their native proprietary file format.
The software is however (currently) available as Freeware for Windows, macOS and Linux distributions.
