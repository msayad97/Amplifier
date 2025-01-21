# Assembly Instructions

## Manufacture Parts

PCBs:

- `MRIamp`
- `TrafoPCB-NoGap`
- `TrafoPCB-WithGap`

Panels:

- `front panel`
- `back panel`
- `bottom panel`

The Panels have been created with Schaeffer's [Front Panel Designer](https://www.frontpanelexpress.com/front-panel-designer) and can be ordered directly from the GUI of the software (as an alternative to manufacturing them yourself)

### Transformer

TODO see pictures

- CM trafo supply (2 cores)
	- solder and isolate VDC connection strip as shown in ![](/res/img/enclosure/IMG_20180209_080222.jpg)
- trafo (4 cores)
- other trafo (1 core) (SWR coil)?

## Assembly

TODO

1. Screw the prepared panels onto the `enclosure`.

### Heat Sink

TODO

- prepare holes as defined in [](holes heatsink.pdf)
- cut out `gap pad` for the diodes
- place `TO247 thermal pad` and `TO225 thermal pad` as shown in IMG_20181004_113122.jpg
- screw `diode cooling plate` into place and place `spacer 4mm` onto holes (/res/img/heatsink/IMG_20180202_122328.jpg)
- screw everything together

### Capacitor Block

1. Mill `capacitor cup` and `capacitor cover` out of PVC and glue the pairs together.
2. Place all `decoupling capacitor` into one `capacitor cup`. Connect them to `capacitor connector plate inner` and `capacitor connector plate outer` using `hexagon screw M5×35` and `washer M5` as shown in the figure below:\
	![](/res/img/capacitor-block-open.jpg){width=30%}\
	_connected capacitors_
3. Solder wires to the connector plates, put the second `capacitor cup`-`capacitor cover`-pair on top, passing the wires through and mount the block into the `enclosure`:\
	![](/res/img/capacitor-block-mounted.jpg){width=30%}\
	_mounted capacitor block_
4. …and wire it to the `MRIamp`-PCB:\
	![](/res/img/capacitor-block-wired.jpg){width=30%}\
	_wired capacitor block_
