# awsomeEngSci
Curated list of awsome Free and Open Source Software for engineering and science



There are many reasons one may want to use Free and Open Source CAD software. For example if you are a scientist and you want to be sure about the reproducibility of your work. You are a teacher and you follow certain ethics to do not promote a specific comercial package over the others. Or you are a startup and you don't have the resources to pay for expensive licensing fees, or you care about your privacy and don't want to use freemium/shareware/spyware proprietary software which nobody know what information they collect about you. Or maybe you are a big company which is suffering from huge licensing fees imposed by the companies. Or you are an student and you want to work on your own computer rather than the college/University computers. Or you are just normal sane person who is using a non-Windows operating system like macOS or GNU/Linux, who finds the whole concept of running a virtual machine just for your CAD insane!

I have searched the internet and I have found some of the open source 3D and 2D CAD packages. Please share your experience. If there are good books, examples, demos, tutorials ... please share. Or if you know other options not listed here please add to the comments.

# 3D CAD:
   1. FreeCAD
   2. [solveSpace](http://solvespace.com/index.pl)
   3. NaroCAD
   4. BRL-CAD
   5. HeeksCAD
   6. [Antimony](http://www.mattkeeter.com/projects/antimony/3/) → visual programing
   7. [VARKON](http://varkon.sourceforge.net/)
   8. [JS.Sketcher](https://github.com/xibyte/jsketcher) → web based self hosted
   9. [SALOME](http://www.salome-platform.org/)

# 2D CAD:

   1. LibreCAD
   2. LibreDWG
   3. OpenDWG
   4. [Archimedes](https://sourceforge.net/projects/arquimedes/)
   5. [QCAD](http://www.qcad.org/en/qcad-screenshots)
   6. SAMoCAD
   7. SagCAD
   8. Piglet Drawing Editor
   9. DESI-III

# Sculpting:

   1. Blender
   2. EQUINOX-3D
   3. K-3D
   4. Wings 3D
   5. DeleD CE
   6. Structure Synth
   7. Moonlight|3D
   8. OpenFX
   9. Fragmentarium


[Here](https://www.reddit.com/r/CNC/comments/aizatc/free_and_open_source_camcnc_software/) I have also listed all the Free and Open source CAM/CNC software I could find. and if you care about indirect code based CAD (aka generative, programmatic design) I have made a list [here](https://github.com/openscad/openscad/issues/2299) as well.


**3D:** 
- OpenCASCADE 
   * [pythonOCC](http://www.pythonocc.org/) / [aocutils](https://pypi.org/project/aocutils/)
   * [occmodel](https://github.com/tenko/occmodel)
   * [declaracad](https://github.com/codelv/declaracad), enaml
   * FreeCAD python scripting
   * [pyOCCT](https://github.com/LaughlinResearch/pyOCCT)
- [ImplicitCAD](https://github.com/colah/ImplicitCAD), haskell
- [CadQuery](https://github.com/dcowden/cadquery)
-  Blender Python macros
-  Initial Graphics Exchange Specification (IGES) .iges/.igs
- [X3D](https://en.wikipedia.org/wiki/X3D)
- [ACIS](https://en.wikipedia.org/wiki/ACIS) .sat
- [Parasolid ](https://en.wikipedia.org/wiki/Parasolid) .x_t
- Virtual Reality Modeling Language (VRML) .wrl
- [Wavefront ](https://en.wikipedia.org/wiki/Wavefront_.obj_file).obj
- [libfive ](https://libfive.com/)([Ao](https://www.mattkeeter.com/projects/ao/))
- [HyperFun](http://hyperfun.org)
- [CScheme](http://www.dia.uniroma3.it/~scorzell/cscheme/index.htm)
- [PLaSM](http://www.plasm.net/) (Programming Language of Solid Modeling)
- OpenJSCAD
- [RapCAD](https://github.com/GilesBathgate/RapCAD)
- [CoffeeSCAD](https://github.com/kaosat-dev/CoffeeSCad)
- [SchemeCad](http://www.omnigia.com/SchemeCad/)
- [Curv](https://github.com/doug-moen/curv)

**Mesh:**
- [Gmsh ](http://gmsh.info/) .geo  ([pygmsh](https://github.com/nschloe/pygmsh) python wrapper)
- [NetGen ](https://ngsolve.org/) .in2d
- [OpenFOAM blockMeshDict](https://cfd.direct/openfoam/user-guide/blockmesh/)
- [Elmergrid ](ftp://nic.funet.fi/index/elmer/doc/ElmerGridManual.pdf) .grd --> [Elmer](https://www.csc.fi/web/elmer)
- Medit mesh file format .mesh
- Geomview polyhedral file format .off 
- Polyhedral file format .ply

**2D/vector graphics :**
- PostScript
- LaTeX based graphics: Tikz/PGF, asymptote, pstricks
- MetaPost
- xml/svg
- [diagrams](https://archives.haskell.org/projects.haskell.org/diagrams/)
- UML Unified Modeling Language
- CGM Computer Graphics Metafile

**CAM:** 
- G-code
- OpenSBP
- HPLG or HPGL (Hewlett-Packard Graphics Language)

**Plotting and data visualisation:**
- GnuPlot
- Mathplotlib
- GeoGebra
- ggplot
- D3


PDE solver (FEM, CFD...) (list1)
Preprocessor: Gmsh, Netgen, tetgen, ElmerGrid (Quickmesh), GetDDM, METIS, pdnMesh, EasyMesh, libmesh, tetlib, nglib, OpenFOAM blockMesh, gCAD3D, Larosterna, enGrid
 solver: ELMER, Impact, OpenFOAM, SALOME Meca, ONELAB, GetDP KRATOS, MOOSE, CalculiX, Code_Aster, Code_Saturne, FEniCS-Oasis, FreeFem++, SU2, Vortexje, Caedium, NASA NASTRAN, cast3m, R-desolve, z88, OOFEM, CMISS (list1, list2, list3), NGSolve, tochnog, NiftySim, MFEM/GLVis,  Finite Element ToolKit (FETK), deal.II, GetFEM++, DUNE, Gerris Flow Solver, SfePy , HiFlow3,Agros2D, Hermes Project, oomph-lib, FeatFlow, futureye , OpenFVM, coolfluid3, MBDyn, OpenSees, Dedalus, MuPIF, AixVipMap, CHEOPS, CouPE , Advanced Simulation Library (ASL)  , ALBERTA , The FEBio software suite ...?
postprocessors:ParaView, OpenDX, Wings 3D, VisIt, libmesh, tetgen
mesh edit: MeshLab, GLC_Player, CloudCompare, blender, meshfix, ReMESH, Openmesh, open3mod



Sadly the world of CAM/CNC is dominated by proprietary software which costs hobbyists and students a lot. Besides for scientists and researchers they do not provide much freedom to tinker around. I have previously listed all the available CAD options [here](https://www.reddit.com/r/cad/comments/8dmtc8/please_share_your_experience_with_the_available/) or if you are interested in indirect code based design [here](https://github.com/openscad/openscad/issues/2299). I'm going to just list everything I have found and then maybe you guys can share others:

# Machine languages:

These are the languages most of CNC/NC controllers can read:

* G-code
* OpenSBP
* HPGL (Hewlett-Packard Graphics Language)
* [Cutter Location (CL) Data](https://en.wikipedia.org/wiki/Cutter_location), [APT](https://en.wikipedia.org/wiki/APT_(programming_language))

some software can directly read 2D formats like SVG and DXF too.

# Nesting:

* [SVGnest](https://svgnest.com) A browser-based vector nesting tool
* [Deepnest](https://deepnest.io/)

# CAM and slicer software:

These are the software which take the CAD file and then generate the tool-path in machine language.

* [PyCAM](http://pycam.sourceforge.net/): reads STL (binary/ascii), DXF, SVG, PS/EPS and generates G-code, license GPL v3, cross-platform Windows/macOS/Linux, it also has the simulation
* [dxf2gcode](https://sourceforge.net/projects/dxf2gcode/) or [here](https://github.com/workflo/dxf2gcode) the grbl compatible: reads 2D drawings dxf, pdf/ps and generates G-code, license GPL v3, cross-platform, it includes visual simulation
* [dmap2gcode](http://www.scorchworks.com/Dmap2gcode/dmap2gcode.html): converts depth maps to G-Code using [image-to-gcode](http://www.linuxcnc.org/docs/2.4/html/gui_image-to-gcode.html), license GPL v3, is written in Python and Windows executables are provided
* [OpenSCAD2CNC](https://bitbucket.org/kosme/openscad2cnc) which directly converts [OpenSCAD](http://www.openscad.org/) scripts to toolpath. It is only a CLI tool written in C# so most probably only for Windows
* [CNC Code Generator](http://cnccodegen.sourceforge.net/) converts DXF to NC code (G&M), license GPL v2, it is a Java program so most probably is cross-platform
* [Ace Converter](http://www.dakeng.com/ace.html) converts DXF to G-code, license GNU GPL, written in Borland C++ and Windows binaries are provided
* [gCncCam GNU Cam Processor](http://gcnccam.sourceforge.net/): converts DXF and GERBER NC-Files (Drill-Files) to G-code (RS-274), it includes a GUI, GPLv2
* [HeeksCNC](https://sites.google.com/site/heekscad/) which is OS but you have to pay for the binaries! Import solid models from STEP and IGES files or DXF drawings. I'm not sure how it is related to [HeeksCAM](https://github.com/danheeks/HeeksCAM), [Area](https://code.google.com/archive/p/libarea/) and PyCAM projects.
* [CollabCAD](https://collabcad.gov.in/) seems to be a complete CAD/CAM suit written in Java (the GUI) available for Linux and Windows. It reads XML, STEP, IGES, and VRML
* [CncSimple](https://cncsimple.wordpress.com/) not much information available for this one. it has been deprecated into a podiatry software. old code can be downloaded from [here](https://archive.codeplex.com/?p=cncsimple)
* [Inkscape Laser Plug-In](http://jtechphotonics.com/?page_id=2012)
* [Inkscape Gcodetools plug-in](http://www.cnc-club.ru/forum/viewtopic.php?f=33&t=35)
* [Generic CAM](http://genericcam.sourceforge.net/) multi-axis, reads STL, GTS and DXF, GPLv3, is cross-platform
* [F-Engrave](http://www.scorchworks.com/Fengrave/fengrave.html) converts text or image to g-code, for Engraving and V-Carving, is written in Python, reads DXF and bitmap images
* [Blender CAM](http://blendercam.blogspot.com/) description [here](http://blendercam.blogspot.com/p/blender-cam-description.html) and [this presentation](https://download.blender.org/documentation/bc2014/Vilem_Novak-BlenderCAM.pdf)
* [SFACT](https://github.com/ahmetcemturan/SFACT) or SF-ACT formerly [Skeinforge](https://reprap.org/wiki/Skeinforge), written in Python, converts 3D to G-code
* [PathCAM](https://github.com/xenovacivus/PathCAM), 2.5D toolpath generator, for Windows and Ubuntu
* [OpenCAMLib](https://github.com/aewallin/opencamlib) written in C++ with Python bindings for 3D tool path generation
* [OpenCAM](http://opencam.sourceforge.net/) to generate G-code and HPGL, Linux,
* [FreeCAD Path Workbench](https://www.freecadweb.org/wiki/Path_Workbench)
* [CNC Toolkit](http://cnc-toolkit.com/) 3D Studio Max's plugin
* [Simple2D CAD/CAM](http://simple2dcadcam.sourceforge.net/)
* [Hugomatic](https://github.com/hugomatic/hugomatic) and [cnconline](https://github.com/hugomatic/cncOnline) written in Python
* [CP1](http://wiki.linuxcnc.org/cgi-bin/wiki.pl?Cp1) conversational machining to G-code
* [gDrill](http://www.derekhugger.com/tools.html) Python script vconverting list of X Y points to tool path G-code
* [g-code-generators](https://github.com/twforeman/g-code-generators/) Perl scripts for G-code
* [GCAM - GNU Computer Aided Manufacturing ](https://github.com/bubbapizza/GCAM)
* [PartKAM](https://github.com/Jack000/PartKAM) and it's fork makercam which uses flash: web-based 2.5D
* [gcode-tools](https://github.com/reox/gcode-tools)
* [Reprap host software](https://reprap.org/wiki/Reprap_host_software)
* [cl-mill](https://code.google.com/archive/p/cl-mill/) written in Common Lisb, BSD license
* [gcodeplot](https://github.com/arpruss/gcodeplot)
* [SolveSpace](http://solvespace.com/index.pl)
* [GtkCAD](http://www.nongnu.org/gtkcad/)
* [cam-occ](https://code.google.com/archive/p/cam-occ/)
* [monocam](https://code.google.com/archive/p/monocam/)
* [camvox](https://sourceforge.net/projects/camvox/)
* \[\]

## PCB:

* [visolate](https://sourceforge.net/projects/visolate/) mill PCBs using voronoi-regions
* [pcb2gcode](https://github.com/pcb2gcode/pcb2gcode) a CLI tool for isolation, routing and drilling of PCBs, reads [Gerber files](https://en.wikipedia.org/wiki/Gerber_format), there is also [pcb2gcodeGUI](https://github.com/pcb2gcode/pcb2gcodeGUI), it is cross-platform.
* [FlatCAM](http://flatcam.org/) for PCB milling, reads Gerber and Excellon , witten in Python,
* [cirQWizard](http://cirqwizard.org/) Gerber to GCode converter for PCB milling

## 3D printing:

* [Slic3r](https://slic3r.org)
* Cura
* Repetier
* ReplicatorG
* [SuperSkein](https://github.com/MaskedRetriever/SuperSkein/)
* SmoothieControl

# Simulation and Post-processors:

If you have the machine code, you need to simulate the process to be sure it is what you intended and sometimes you have to modify the code manually and simulate it again.

* [CAMotics](https://camotics.org/) formerly (OpenSCAM), reads 3-axis G-code, is cross-platform, is GPL v2+ licensed

# Machine controller:

These are the software which read the tool-path and control the CNC/NC machine directly:

* [LinuxCNC](http://linuxcnc.org/) which works on [RTAI](https://www.rtai.org/) Linux, has a GNU GPLv2 license
* [Grbl](https://github.com/grbl/grbl): parallel-port-based motion control, GPLv3 license, Arduino
* [Jedicut](https://www.jedicut.com/en/): controlling 4 axis CNC machines to make hot wire cuttings,
* [PyCNC](https://github.com/Nikolay-Kha/PyCNC) G-code interpreter and CNC/3D-printer controller
* [Inkcut](https://codelv.com/projects/inkcut/)
* [Universal Gcode Sender (UGS)](http://winder.github.io/ugs_website/)
* TinyG, Chilipepper, TgFX
* Smoothie
* LaserGRBL
* bCNC

more firmwares listed [here](https://reprap.org/wiki/List_of_Firmware), grbl interfaces listed [here](https://github.com/grbl/grbl/wiki/Using-Grbl).

# Other:

There are other lists also at [wiki.shapeoko](https://wiki.shapeoko.com/index.php/CAM), [wiki.linuxcnc](http://wiki.linuxcnc.org/cgi-bin/wiki.pl?Cam), [freebyte](http://www.freebyte.com/cad/cadcam.htm), [GroundControl](https://github.com/MaslowCNC/GroundControl/wiki/CAM-(G-code-generation)-programs), [fablab](http://wiki.fablab.is/wiki/Portal:Software), [maker-works](https://www.maker-works.com/cadcam-toolchain/). Also [here](https://github.com/linuxcnc/simple-gcode-generators) a list of Python G-code generator scripts. I have also posted this question [here in hobycnc sub](https://www.reddit.com/r/hobbycnc/comments/aj0hu8/list_of_free_and_open_source_camcnc_software/)





Following my former lists of awesome [CAD](https://www.reddit.com/r/cad/comments/8dmtc8/please_share_your_experience_with_the_available/) and [CAM/CNC](https://www.reddit.com/r/CNC/comments/aizatc/free_and_open_source_camcnc_software/) FOSS for mechanical engineering, I decided to create also a similar list for electrical engineering too. However it turned out to be way more complicated than what I expected, taking two weeks of my free time to research.

I'm not gonna lecture you about the importance of FOSS, and I think most professionals are aware of the advantages. From software licensing costs, privacy, cross platform experience, customizability and most importantly vendor lock down. Just imaging Autodesk decides to triple its fees all of a sudden. Your designs are basically ransom! Or if you are a scientist and want to implement your own auto routing method or improved compiling algorithm, or you are a student you want to do something on your mac or Linux computer without loosing your sanity over virtualization...

The way I categorize these software will be based on the conventional workflow I use for my own work (Robotics). I will start with conceptual design including a circuit schematics and a breadboard implementation. Following by programing the Microcontroller and then merging the circuit and MCU in a prototype or simulation. Next step the PCB should be designed and send for manufacturing. I hope this list will stimulate FOSS adoption and help the community to better know of their alternatives.

# EDA suits:

These are the family of the products which try to integrate most of the PCB Design process in one place. They usually include the schematic capture and CAD parts, and sometimes even the simulation and auto routing.

* **KiCAD:** Is probably the most famous and stable of all FOSS EDA suits. It does not require introduction; if you haven't heard of it you have probably living under a stone :) what makes it unique is the fact it is used and supported by the folks at CERN. In the latest version it has some simulation (using Ngspice?) and some auto routing plugins.
* **Fritzing:** In my humble opinion is the most hobbyist friendly of all EDA suits. I have read a lot of criticism on the forums about it though. What makes it unique is the virtual breadboard where you can place parts and connections similar to the way you could do it on a real one. It is great for beginners like me as well as documentation and publication.
* **gEDA** Is a combination of several other packages including gschem, pcb and Gerbv. It is the classic gold standard of EDA suits world. It's community is comparable to KiCAD and Fritzing, if not bigger.
* [**LibrePCB**](https://github.com/LibrePCB/LibrePCB)**:** Is an ambitious attempt to develop an EDA suit from scratch which outperforms KiCAD in terms of usability and extendability. Extensive libraries and version control are some of the key features. Reading from the forums this project has a bright future.
* [**Horizon**](https://github.com/carrotIndustries/horizon)**:** similar to the LibrePCB, is another attempt to make a better FOSS EDA and very appreciated by the community.

TinyCAD, FreePCB, BSch3V MINIMAL PCB EDITOR, MeowCAD, [PCB Elegance](http://www.pcbelegance.org), [Caneda](https://github.com/Caneda/Caneda), [diy-layout-creator](https://code.google.com/archive/p/diy-layout-creator/), [BlackBoard Circuit Designer](https://github.com/mpue/blackboard), [eSim](https://esim.fossee.in/home) formerly Oscad  FreeEDA, [myNetPCB](https://sourceforge.net/projects/mynetpcb/), [FidoCadJ](https://sourceforge.net/projects/fidocadj/)) are also some of the available options for those who enjoy investigating. Also if you care about programatic (aka code based indirect CAD), there are attempts like [aeCAD](https://github.com/aktos-io/aecad) and [SKiDL](https://github.com/xesscorp/skidl) to look into. Immediate advantages of indirect CAD are version control and object oriented programing, but it requires its own essay. If you have a design with lots of components and layers, manual placement and routing (PnR) can be cumbersome. There are some automatic PnR tools available which are either an standalone GUI/CLI and/or as plugins to above EDA suits:

* [**FreeRouting**](https://freerouting.org)**:**, on [GitHub](https://github.com/Engidea/FreeRoutingNew) or [this website](https://freerouting.mihosoft.eu)
* [VeroRoute](https://sourceforge.net/projects/veroroute/)
* [C-PCB](https://github.com/vygr/C-PCB)
* MUCS-PCB
* qautorouter
* [Graywolf](https://github.com/rubund/graywolf) formerly TimberWolf
* [Fairly Good Router FGR](http://vlsicad.eecs.umich.edu/BK/FGR/) and more has been listed in [this eevblog forum post](https://www.eevblog.com/forum/kicad/open-source-high-quality-autorouting-is-it-possible/)

# Circuit diagram:

These are the software for schematics capture. Some might use these as a conceptual design platform, But I personally prefer to use pen and paper first. Then using these software is necessary for documentation of the final design. Some of them can also export different flavors of netlist (SPICE, Spectre, CDL...) to be imported to EDA suits, auto-routing or simulation software:

* XCircuit
* [YCircuit](https://siddharthshekar.bitbucket.io/public/ycircuit/) which is an attempt to improve XCircuit
* [Circuit Diagram](https://www.circuit-diagram.org)
* [QElectroTech](https://qelectrotech.org/)
* AACircuit

There also more general purpose software like Dia diagram editor, InkScape, LibreOffice (LibreSymbols) for design and documentation of discute boards. If you prefer non-WYSWYG way of design then TikZ CircuiTikz, METAPOST MakeCirc, [PSTricks pst-circ](http://pstcirc.free.fr/index.html), [Circuit\_macros](https://ece.uwaterloo.ca/~aplevich/Circuit_macros/) , [Cirkuit](http://wwwu.uni-klu.ac.at/magostin/cirkuit.html) , [lcapy](http://lcapy.elec.canterbury.ac.nz), might be your cup of tee.

# Simulation:

Now some people might argue that thanks to the cheap development boards like Arduino and Raspberry pi, simulation is unnecessary, which I strongly disagree. For me personally simulation is important to reduce risks of damage on the hardware or even novice students, documentation, long distance collaboration...

The most well-known software commercial software in this category is the infamous [Proteus VSM](https://alternativeto.net/software/proteus-vsm/?license=opensource) which not only is very expensive for hobbyists and students, but is also only on Windows! Unfortunately there is not much in the FOSS world coming close to Proteus VSM in terms of stability and features. Mosts of the FOSS are either for analogue or logic circuits simulation or for MCU emulation, not much available for integrated virtual prototyping. However, it does not mean FOSS community has done nothing. There are amazing attempts:

## Integrated MCU-analogue:

* **KTechLab:** is probably the most amazing and in some ways peculiar of all in this section. It is primarily an KDE tool for RCL, logic and PIC MCU (using gpsim) simulation. However it has a unique visual programing environment where one can develop the MCU workflow by flowcharts. Then it is translated into Microbe or MicroBASIC, another peculiar high level language of KTechLab. It also an IDE for C, assembly and MicroBASIC development and compiling (using SDCC?). It is unfortunate that KTechLab is still very unstable full of bugs. Another long requested feature is the AVR integration. There have been requests since 2006 to use SimulAVR, yet this feature to be seen :(
* **SimulIDE:** is all KTechLab wished to be. It has both PIC and AVR integration. However it is also not yet stable, more to be considered as a prototype.
* [**Emulare**](http://emulare.sourceforge.net/)**:** for ATMega line of MCUs
* [simuino](https://code.google.com/archive/p/simuino/) an Arduino UNO/MEGA Pin Simulator
* [gpsim](https://en.m.wikipedia.org/wiki/Gpsim) used in both KTechLab and SimulIDE
* PICsim PICsimLab
* [SimulAVR](http://www.nongnu.org/simulavr/) which also includes simulavr-disp a TCL-TK GUI. It used in SimulIDE and is the gold standard FOSS AVR simulation.
* [simavr](https://github.com/buserror/simavr) is the newer AVR simulation which according to the forums is a very promising alternative to SimulAVR.
* [PIC-Simulator](https://github.com/PalatinCoder/PIC-Simulator)
* GNUSim8085
* [MCUSim](https://trac.mcusim.org)
* Ardulator
* [Arduino Simulator](https://sourceforge.net/projects/arduinosim/)
* [emulino](https://github.com/ghewgill/emulino)
* [HAPSIM](http://www.helmix.at/hapsim/)

## General purpose:

There are softwares which are not specifically for EE simulation:

* Modelica Language and its FOSS implementations such as OpenModelica and jModelica are a great option for simulation of multi physics systems. The OM software has libraries for analogue, digital and logic electronic components. You have the option to use the GUI to connect the components or code your system in Modelica Language using continuous and discrete algebraic differential equations. The language has also been adopted by Wolfram Mathematica's produces, Maple and many more. It is just a shame that it is not already an industry standard!
* Scilab's Xcos or ScicosLab's SciCos are somehow attempts to replicate MATLAB's SIMULINK. They are indeed not as powerful but still great for students, teachers and even easy industrial simulation. Especially if you want to prototype a system and do not want to spend much time to code it, the visual programing environment can be a great help.
* MyOpenLab is also a great platform for visual physical system simulation. It can be considered an alternative to NI's LabVIEW.

## Analogue:

These are the software which can only simulate the RCL and logical circuits. They import netlist files mostly:

* [**SPICE**](https://ptolemy.berkeley.edu/projects/embedded/pubs/downloads/spice/) (Simulation Program with Integrated Circuit Emphasis) which has been around since the beginning of time, is just for analogue simulation.
* Quite Universal Circuit Simulator (QUCS), and its SPICE compatible version Qucs-S have one of the largest user bases. Qucsstudio is also another derivative.
* Ngspice which is a combination of three FOSS projects Spice3f5, Cider1b1 and Xspice, is "a mixed-level/mixed-signal circuit simulator". It is the simulation backend of most EDAs above KiCAD, Fritzing and gEDA.
* Xyce is also an SPICE compatible simulator for "extremely large circuit problems by supporting large-scale parallel computing platforms"
* Circuit Simulator\]([https://github.com/pfalstad/circuitjs1](https://github.com/pfalstad/circuitjs1)) Java and web based
* [BrainBox](https://freegroup.github.io/brainbox/circuit/) web based
* PySpice
* [SpiceOpus](http://spiceopus.si)
* QSapecNG
* oregano
* gSpiceUI
* [GNU Circuit Analysis Package (Gnucap)](https://en.wikipedia.org/wiki/GNU_Circuit_Analysis_Package)
* [linNet](https://sourceforge.net/projects/linnet-svn/) symbolically
* [LCSIM - Laboratory Circuit Simulator](https://sourceforge.net/projects/lcsim/files/latest/download))

# IC design and simulation programing:

Software for logic, FPGA, IC ...

* [Electric](https://staticfreesoft.com)
* Alliance CAD
* [Icarus Verilog](http://iverilog.icarus.com)
* Verilator
* TkGate
* KSimus
* KLogic
* GHDL
* FidoCadJ
* myNetPCB
* JSchem
* BSch3V
* IRSIM
* FreeHDL
* Chisel with Scala
* MyHDL and Migen with Python
* Bluespec and Lava with Haskell
* PSHDL
* [CEDAR Logic Simulator](https://sourceforge.net/projects/cedarlogic/)
* Logisim and the fork [Logisim-Evolution](https://github.com/reds-heig/logisim-evolution)
* gLogic
* [Logic Gate Simulator](https://sourceforge.net/projects/gatesim/)
* Qfsm
* Yosys, netlistsvg
* [Qflow](http://opencircuitdesign.com/qflow/welcome.html)
* [Netgen](http://opencircuitdesign.com/netgen/)
* [IceStorm](http://www.clifford.at/icestorm/)
* gwave
* GTKWave VCD

# Microcontroller programing:

## Operating Systems:

List of real-time operating systems or firmware [here](https://www.osrtos.com)

## Compilers:

* [avr-gcc](https://www.nongnu.org/avr/)
* [avra](https://sourceforge.net/projects/avra/)
* SDCC Small Device C Compiler
* GPUTILS, gpasm, gpdasm, gplink, and gplib
* [gnupic](http://www.gnupic.org) spasm, gypsum
* cpik
* MSPgcc --> TI
* [MIPS GCC](https://www.linux-mips.org/wiki/Toolchains)
* [MPIDE](http://chipkit.net/wpcproduct/mpide/)
* OpenOCD - Open On-Chip Debugger
* PicCBuilder
* pic32 microchip compiler
* [Newlib](http://sourceware.org/newlib/)
* [Picprog](http://hyvatti.iki.fi/~jaakko/pic/picprog.html)
* [Hex2bin](https://sourceforge.net/projects/hex2bin/)

## High level languages:

* [Jal (not?) Just Another Language](http://jal.sourceforge.net)
* [PicPas](https://github.com/t-edson/PicPas)
* Microbe/MicroBASIC --> KTechLab
* MicroPython
* CircuitPython
* Zerynth

more at [fedoraproject](https://fedoraproject.org/wiki/Packages_For_Embedded_Development) and [piclist](http://www.piclist.com/tecHREF/microchip/languages.htm)

## Editors and IDE:

* CodeBlocks Arduino IDE
* Arduino
* Pinguino
* Piklab
* Wiring [http://wiring.org.co/](http://wiring.org.co/)
* Embitz
* Code::Blocks
* Eclipse CDT
* Code Composer Essentials (CCEssentials) TI
* ChipVault
* Ardiuno debugger
* MCU 8051 IDE

burner, programmer, downloader, inhibitor...: avrdude avrgal pic32prog ardupic32 PonyProg prog84

# other lists:

* [opencircuitdesign](http://opencircuitdesign.com)
* [vlsiacademy](http://www.vlsiacademy.org/open-source-cad-tools.html)
* [opencircuits](http://www.opencircuits.com/Software_tool)
* [semiwiki](https://www.semiwiki.com/forum/f119/eda-open-source-tools-wiki-314.html)
* [semiwiki](https://www.semiwiki.com/forum/showwiki.php?title=Semi-Wiki:EDA-Open-Source-Tools-Wiki)
* [fritzing](http://fritzing.org/about/comparison)
* [wiki.archlinux](https://wiki.archlinux.org/index.php/List_of_applications/Science#Electronics) [wikipedia HDL simulators](https://en.m.wikipedia.org/wiki/List_of_HDL_simulators)
* [wikipedia List free electronics circuit simulators](https://en.wikipedia.org/wiki/List_of_free_electronics_circuit_simulators)
* [wikipedia Electronic circuit simulation](https://en.wikipedia.org/wiki/Electronic_circuit_simulation)
* [m-thu](https://github.com/m-thu/sandbox/blob/master/URLs.md#eda)
* [awesome-electronics](https://github.com/kitspace/awesome-electronics/blob/master/README.md)
* [Awesome-Embedded](https://github.com/nhivp/Awesome-Embedded)
* [awesome-iot-1](https://github.com/kuzzleio/awesome-iot-1)
* [awesome-c](https://github.com/uhub/awesome-c)
* [fedoraproject](https://fedoraproject.org/wiki/User:Jjmcd/Drafts/Packages/Embedded)
* [gnupic](http://www.gnupic.dds.nl/index.html)
* [webring](http://www.webring.org/l/rd?ring=picmicro;id=26;url=http%3A%2F%2Fpicemulator%2Ecom%2Flinks%2Ehtml)
* [microchip](https://www.microchip.com/forums/m/tm.aspx?m=235424&p=1)



**P.S.** This as far as I could go. There are probably a lot of mistakes here. Please help me complete and improve this list.

1. symbolic mathematical analysis alternatives to Mathematica, Maple and MATLAB symbolic toolbox (formerly MuPAD)
    1. Maxima Language using WxMaxima or Jupyter
    2. Python-Sympy using Jupyter
    3. SageMath which uses Sympy, Maxima, Giac
    4. Yacas
    5. PanAxiom ( [Axiom](http://axiom-developer.org/), FriCAS,  OpenAxiom )
    6. [FORM](https://www.nikhef.nl/~form/)
    7. [Macaulay2](https://faculty.math.illinois.edu/Macaulay2/)
    8. [Magnus](https://en.wikipedia.org/wiki/Magnus_(computer_algebra_system))
    9. [Mathomatic](https://en.wikipedia.org/wiki/Mathomatic)
    10. [REDUCE](http://www.reduce-algebra.com/)
    11. Euler Math Toolbox (EMT)
    12. [Mathics](http://mathics.github.io/)
    13. [Cantor](https://edu.kde.org/cantor/)
    14. MathAction
    15. SymbolicC++
    16. SymEngine
    17. [GiNaC](https://www.ginac.de/)
    18. [Piranha](https://github.com/bluescarni/piranha)
    
    
CAS: Cadabra, Singular, Giac/Xcas, CoCoA, GAP, Erable/ALGB, Aldor
Numerical: (R, Python, Julia, gnuplot, CERN/ROOT, Fortran, GNU Octave, Scilab/Scicoslab, Modelica, ASCEND, bc, PDL Perl Data Language, IDL interactive data language )
Plotting: gnuplot, Matplotlib, TikZ/PGFplot, Qtiplot, SciDAVis, LabPlot, List
simulation: Modelica language


CAS/symbolic : WxMaxima (Euler Math Toolbox (EMT), Mathics, Cantor, MathAction)
Numerical: (GNU Ocatve, scilab, scicoslab, FreeMat, EngLab ,ASCEND, PyDSTool, Reinteract , MathPiper )
Ket, Mirai Math, PARI/GP, Calc, Euler Math Toolbox, GSL Shell, Genius, spyder, python(x,y),   (list)
Ploting:
gnuplot
Matplotlib
Ptplot
Data analysis
Orange, Fityk, Simfit, QtiPlot, PyModelFit,  other 


