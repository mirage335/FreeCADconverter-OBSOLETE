Converts generic 3D models (STEP, IGES, etc) to FreeCAD documents (FCSTD).

#Usage
./FreeCADconverter <inFile> <outFile>

export PATH="$PATH:$PWD"
find . -type f -name '*.step' -exec FreeCADconverter {} {}.fcstd \;

#Cavets
Converted parts visibilty defaults to false.


#Reference
forum.freecadweb.org/viewtopic.php?t=3332
