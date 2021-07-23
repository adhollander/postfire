# PReP Tool for postfire restoration in chaparral landscapes

This repository contains code for the PReP tool (Post-Fire Restoration Prioritization) to help with postfire
restoration of vegetation in chaparral landscapes. This tool provides a transparent and repeatable framework for USFS resource managers to guide and
prioritize post-fire restoration efforts in shrubland, with the following objectives:

* Assess regeneration ability of landscape post-fire
* Predict areas of degradation on the landscape
* Identify priorities for restoration
* Inform species for restoration

Specifically, the tool determines the regeneration capacity of the landscape post-fire based on the relative
proportion of seeding, resprouting, and facultative seeding species, and the risk of post-fire soil erosion.
Generating this information efficiently is particularly important given the often short timeframes involved in
implementing restoration activities, such as the use of fire settlement funds or implementing urgent activities
to reduce sediment erosion post-fire.

The PReP Tool uses a Jupyter notebook framework, which allows a reproducible and interactive workflow
for conducting geospatial computations. It is well-suited to the overall objectives of the PReP Tool as it
allows revisions to be made easily and efficiently, which might be necessary when applying the tool to other
fires in southern California. In addition, it uses Python code which allows it to be integrated with a variety of
other platforms, such as GIS packages that support Python scripting. Within the PReP Tool there are options
to download the spatial data as geotiff rasters which can be viewed in GIS platforms such as ArcGIS,
allowing outputs to be viewed with other spatial datasets such as roads, trails, or project area boundaries.

To install the tool, download the [PRePTool.zip](https://github.com/adhollander/postfire/raw/master/PReP_Tool.zip) file, unpack it, and follow
the instructions in the [installation guide](https://github.com/adhollander/postfire/raw/master/Postfire_Restoration_Prioritization_Tool_Installation_Instructions.pdf). 
The [technical guide](https://github.com/adhollander/postfire/raw/master/Postfire_Restoration_Priorization_Tool_Technical_Guide.pdf) 
provides instructions on running the tool and substantial details on its background and concepts.
There is also a slide presentation illustrating use of the tool in a [case study of the Copper Fire](https://github.com/adhollander/postfire/raw/master/PReP_Tool_Copper_Fire_Case_Study.pdf).
