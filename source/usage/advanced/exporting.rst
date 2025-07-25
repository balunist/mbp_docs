.. _exporting-label:

Exporting the created map
=========================

There are several alternative :ref:`map_type-label` options that will export
the created map in one step finishing without leaving the map in the model.
This includes DXF file, SVG files or Report Output.  You may however wish to
keep the map in order to use it in the Fusion's manufacturing workspace to
create toolpaths to produce your model.  The same exports can be done after
a map with component bodies has been created.  Performing exports post-mapping
provides a way to rearranged the map before an export is performed.

There are a number of post-mapping tasks that can be performed on the created
map object.  It is  ` more efficient and recommended to create the map first
then execute tasks on that map.  The tasks available include labeling, exports
of SVG, DXF, Cutlist, Report and the recently added Manufacturing Model.  A
description of the tasks can be found here
:ref:`Post-Mapping Tasks <tasks-label>`.
Be sure to try the Report task which will create an html file that includes a
view of the map, cut-list, required materials and the MBP options selected to
create the map.  Report also provides an output type Print which allows the
report to be saved as a PDF or even rotate boards for better viewing.

There are a number of options available in the Options tab. See
:ref:`Options <options-label>`

Notes:
    - The creating of a map arrangement accounts for the amount of
      **component spacing** and **trim on board** specified in the options.
      It is suggested that you minimize their size for tighter arrangements.
    - You can move components within or between boards in the resulting
      arranged map.  :ref:`Rearranging Map <rearrange_map-label>`
    - Rearranged maps can be relabeled using the
      :ref:`Label Map <labelmap-label>` task or exported using the
      Post-Mapping tasks

|
