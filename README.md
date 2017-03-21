[Geant4](https://cern.ch/geant4/) is a toolkit for the simulation of the passage of particles through matter developed at CERN. It is popular in nuclear and particle phyiscs.

# Synopsis

```
cmake_geant4.sh <version>
```

# Description

This script downloads and builds Geant4 from the source distribution. It installs the resulting binaries in `geant4{version}-install`. Multiple versions can be installed next to each other, and the desired version can be loaded by sourcing the file `bin/geant4.sh`.

# Examples

```
./cmake_geant4.sh 4.10.03.p01  
(current version 20th march 2017)
```

# License

This work is provided under the license described in the `LICENSE` file.
