# ISPIC
This project provides multiple Docker containers integrated with in situ frameworks. More information on how to run the containers can be found in the respective submodules.

## Source Code structure
This repository is intended as a hub. 
The actual codes are organized in submodules as follows:
.
    ├── README.md               # the file you are currently reading
    ├── paraview_catalyst       # directory for the ParaView Catalyst workflows
    │   ├── cam                 # submodule for the Community Atmosphere Model
    │   ├── catalyst            # submodule for the Catalyst examples
    │   ├── flecsale            # submodule for FleCSALE
    │   └── vpic                # submodule for VPIC
    └── ascent                  # directory for the Ascent workflows
        ├── clover              # submodule for CloverLeaf3D
        └── nyx                 # submodule for Nyx
