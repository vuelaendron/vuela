# Open Science Drone Toolkit

Drones can be a powerful tool for research in disciplines such as agriculture and environmental sciences, allowing the capture of high-resolution aerial imaging with great speed and flexibility. For a typical use, the drone needs to be able to be reliably positioned over the studied terrain and capture images that can be later processed to get a high quality image of the surveyed area and extract useful data. Although there are already many open source hardware and software tools that can be used in each of the individual steps of this process, our question was whether it was possible to perform all these steps using open source tools. We attemped to answer this question by collecting, curating, organizing and testing a comprehensive set of open source tools for aerial data capture for research purposes. The result of these actions is the Open Science Drone Toolkit (OSDT).

![aerial images](img/aerial_data.png)

&nbsp;
## What you can do with the OSDT

The OSDT is a set of open source hardware and software tools and also guides and protocols to enable the user to perform all the necessary tasks to obtain aerial data:

![tasks](img/tasks.png)

&nbsp;
## How to use the toolkit

The toolkit documentation includes: a “usage guide”, with instructions for flying the drone, programming an autonomous mission, programming the camera, and image processing. 

&nbsp;
## Build your own toolkit

An “assembly guide” is also available, that includes a step-by-step guide for building the OVLI drone, setting up and configuring the hardware components, and installing the software. Once you have all parts, it should take you just a few days to have your open hardware / open software toolkit ready.

<h3 align="center">
Hardware
</h3>

<p align="center">
Drone (<a href="https://vuela.cc/en/ovli">OVLI drone</a>)
</p>
<p align="center"> 
Camera (Canon brand camera compatible with CHDK software)
</p>
<p align="center"> 
Radio transmitter (generic 6-channel radio transmitter)
</p>
<p align="center"> 
Batteries and charger (generic 3-cell lithium-polymer battery and balance charger)
</p>
<p align="center"> 
Computer (generic PC with Windows operating system)
</p>
<p align="center"> 
Smartphone (generic smartphone with Android operating system)
</p>
<p align="center"> 
<img src = "https://github.com/vuelaendron/vuela/raw/master/docs/img/hardware.png" alt = "Hardware">
</p>

<h3 align="center">
Software
</h3>

<p align="center">
GPS recorder (<a href="https://www.basicairdata.eu/projects/android/android-gps-logger/">GPS Logger</a>)
</p>
<p align="center">
Drone ground station (<a href="https://ardupilot.org/planner/">Mission Planner</a>)
</p>
<p align="center">
Camera control (<a href="https://chdk.fandom.com/wiki/CHDK">CHDK</a>)
</p>
<p align="center">
Drone autopilot (<a href="https://ardupilot.org/copter/">ArduCopter</a>)
</p>
<p align="center">
Image processing (<a href="https://www.opendronemap.org/">OpenDroneMap</a>)
</p>
<p align="center">
Orthomosaic processing and analysis (<a href="https://qgis.org/">QGIS</a>)
</p>
<p align="center">
Data management (<a href="https://vuela.cc/en/bitacora">Bitácora</a>)
</p>
<p align="center"> 
<img src = "https://github.com/vuelaendron/vuela/raw/master/docs/img/software.png" alt = "Software">
</p>

<h3 align="center">
Documentation
</h3>

<p align="center">
Toolkit assembly guide (<a href="https://docs-google-com.translate.goog/document/d/1tggZiuJUs4auH8q10i0Y0hu3n_9OcOXIdaILVW9r6xw/pub?_x_tr_sl=es&_x_tr_tl=en&_x_tr_hl=es&_x_tr_pto=wapp">automatic translation from Spanish version</a>)
</p>
<p align="center">
Toolkit usage guide (<a href="https://docs-google-com.translate.goog/document/d/1zovHAlRXXMFL1DGB0Gw86sgsunP2yan8vVPw85lxmn8/pub?_x_tr_sl=es&_x_tr_tl=en&_x_tr_hl=es&_x_tr_pto=wapp">automatic translation from Spanish version</a>)
</p>

&nbsp;
## Open source is ❤

The OVLI drone is open hardware, which means you are free to modify it. An easy way to make you own version of the OVLI is to modify the frame, which is assembled from MDF (Medium Density Fibreboard) cut with a laser cutter according to a design file, which can be edited to modify the drone structure (using the open source software Inkscape). It is also possible make your own version of the OVLI by changing the motors, propellers, etc. 

All the software in the toolkit is also open source. The Bitácora software was developed by us especially for this toolkit, and we would gladly welcome your contributions to it. You can find its source code [here](https://github.com/gpereyrairujo/bitacora).

Both the “usage” and “assembly” guides are openly licensed documents (using a CC-BY-SA license, which means you can use their content as long as you cite the source and share it openly again), and also as live documents (in Google Docs) open for suggestions. 


&nbsp;
## Scientific journal article

A detailed description of the OSDT, along with an example use case, was published in the scientific journal PLOS One. The article is available [here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0284184).
