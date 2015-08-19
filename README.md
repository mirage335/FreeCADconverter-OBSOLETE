Converts generic 3D models (STEP, IGES, etc) to FreeCAD documents (FCSTD).

#Usage
./freecadBatch <inFile> <outFile>

export PATH="$PATH:$PWD"
find . -type f -name '*.step' -exec freecadBatch {} {}.fcstd \;

#Cavets
Converted parts visibilty defaults to false.


#Reference
forum.freecadweb.org/viewtopic.php?t=3332
