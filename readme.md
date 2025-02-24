VTK Large Data Directory
----------------------

This directory contains data and baseline images for VTK regression testing
and other VTK examples. Normally these are located in the VTKData repository.
However, that repository is restricted to smaller files to avoid long cvs
checkout times. This repository is where larger files can be committed when
it is not possible to create a reasonable test without them.

The VTKLargeData/Data directory are data files of various types. This includes
polygonal data, images, volumes, structured grids, rectilinear grids,
and multi-variate data.

The VTKLargeData/Baseline are the testing images. These are used in testing to
compare a valid image against a generated image. If a difference between the
two images is found, then the test is considered to have failed.

-------

Refer to
https://www.vtk.org/Wiki/VTK_Datasets


```.sh
git clone git://vtk.org/VTKLargeData.git VTKLargeData
```

See also https://github.com/csukuangfj/VTKData
