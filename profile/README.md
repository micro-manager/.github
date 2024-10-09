# Micro-Manager

Micro-Manager started out as an application to control microscope hardware, 
such as cameras, xy-stages, filter wheels, etc. It includes a hardware abstraction layer written in C++ that is now used in several projects including the original user interface written in Java that is distributed as an ImageJ plugin.

**Go to [micro-manager.org](https://micro-manager.org) for documentation and
binary downloads.**

**For support, see [Micro-Manager
Community](https://micro-manager.org/Micro-Manager_Community).**

**The Micro-Manager community welcomes you!  For our governance structures, 
go [here](https://github.com/micro-manager/micro-manager/tree/main/governance)**


## Repositories

** [mmCoreAndDevices](https://github.com/micro-manager/mmCoreAndDevices) contains the hardware abstraction layer (MMCore) and device adapters (modules that translate between the actual hardware and MMCode.  These are all written in C++. Also containe the code to export MMCore to Java (MMCoreJ).

** [micro-manager](https://github.com/micro-manager/micro-manager). The source code to the Java user interface.  

** [pymmcore](https://github.com/micro-manager/pymmcore). Exports MMCore to Python

** [micro-manager.github.io](https://github.com/micro-manager.github.io). Source code for the [micro-manager website](https://micro-manager.org)


## Python compatility
Several projects provide access to Micro-Manager code from Python. [Pycro-manager](https://github.com/micro-manager/pycro-manager) creates an interprocess bridge between the "classical" Micro-Manger running in a Java Virtual Machine and Python.  [Pymmcore](https://github.com/micro-manager/pymmcore) exports the MMCore interface directly to Python.  Pymmcore is used by various Python packages such as [mmpycorex](https://github.com/micro-manager/mmpycores) and [pymmcore-plus](https://github.com/pymmcore-plus/pymmcore-plus), an organization that contains several User Interfaces witten in Python to interface with MMCore ([pymmcore-widgets](https://github.com/pymmcore-plus/pymmcore-widgets), [napari-micro-manager](https://github.com/pymmcore-plus/napari-micromanager). 

## Contributing

Start [here](https://micro-manager.org/Building_and_debugging_Micro-Manager_source_code).
