# netconv This version v0.2.0 is for macOS and Windows.
This project enables netlist export from the most popular schematic design tools for use in Veroboard/stripboard layout applications.

**TinyCAD**[https://www.tinycad.net/](https://www.tinycad.net/) 

You won't need netconv. TinyCAD can export a file which can be imported directly by DIY Layout Creator or VeroRoute. There are some glitches when moving wires, but otherwise it's a user-friendly app which fits well with DIY Layout Creator. To create a netlist suitable for import into DIYLC,  Tools \> Generate Netlist \> Protel You can import a list of valid components or Right-click on a component, find "Package", click "Show" and enter a valid package type, for example RESISTOR. If you copy this item you won't need to do it for each item.

**Qucs-S**[https://ra3xdh.github.io/](https://ra3xdh.github.io/)

**KiCad** [https://www.kicad.org/](https://www.kicad.org/)

Both can export a file for netconv which exports a file suitable for DIY Layout Creator or VeroRoute.

Currently these applications only import the components. For progress on importing nets, see: [https://github.com/bancika/diy-layout-creator/issues/1026](https://github.com/bancika/diy-layout-creator/issues/1026) [https://sourceforge.net/p/veroroute/discussion/general/thread/e1e88b422f/?limit=25\#d83f](https://sourceforge.net/p/veroroute/discussion/general/thread/e1e88b422f/?limit=25#d83f)

**Installation**

Download the netconv.zip file. Unzip it into a convenient folder.

**Running it**
Open a command line window, go into that folder then type: 

python3 netconv.py

(To remove it just delete the files.)
