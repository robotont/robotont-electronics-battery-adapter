# robotont-electronics-battery-adapter
The repository contains KiCAD schematics and PCB layout for the battery adapter. By connecting the data pins, Robotont is able to communicate with the battery onewire interface and monitor the battery status. The Production folder contains prepared gerbers and BOM ready to order from e.g. JLCPCB.

> [!CAUTION]
> The adapter data connector pitch is currently 2.54 mm but should be 2.50 mm to match Robotont 3 battery connector. Due to the pin alignment mismatch, the adapter does not establish proper communication with the battery. Fix in progress.

## Schematics
![Schematic](docs/robotont-electronics-adapter-sch.png)

## Layout

The following figures visualize the front side of the PCB along with the 3D model of the design.

![Front side](docs/robotont-electronics-adapter-front.png)
![3D View](docs/robotont-electronics-adapter-3d.png)