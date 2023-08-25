### C++ script to get module offsets and dimensions for active LAr volumes in near detector prototype geometries

To extract module offsets and dimensions:

`python3 get_module_offsets.py <input file>`

The input file can be either an edep-sim ROOT file or a GDML geometry. If it can't find the active volumes, you may need to add the active volume names in `get_module_offsets.cpp`.
