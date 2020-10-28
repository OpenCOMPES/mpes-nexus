# Multidimensional photoemission spectroscopy data/metadata project - based on NeXus

Repository dedicated to community-wide drafting of a data/metadata schema for ARPES experiments.

A common platform across the ARPES community is now becoming urgent. The potential of a standardized structure lies not only in the improved transparency of data publishing, but immediately and perhaps most importantly in the possibility of sharing all our tools. We could reduce drastically the time spent developing code for commonplace acquisition and analysis processes, shorten the learning curve of using different facilities, and retain the capability of processing data even long after it has been acquired. 

We now wish to initiate a discussion on the matter. We suggest an existing data format as the most appealing candidate: the NeXus format (https://www.nexusformat.org). 

NeXus has been created for neutron, muon and X-ray diffraction. To adapt to other types of ARPES experiments, using  a significant enlargement of the NeXus dictionary is required. A set of definitions might also be created to complement the current NXarpes definition.

The NeXus format is based on hdf5 file format (https://www.hdfgroup.org/solutions/hdf5/), from which it inherits a set of convenient properties: hdf5 files are self-describing, flexible and extendable, efficient but human readable, platform independent and of public domain. Data and metadata of any dimensionality can be saved in these files that allow for hierarchical classification with any degree of complexity.

NeXus supplies the two missing elements to really provide an interoperable platform for a community: a standardized hierarchy and specific definitions. This dictionary aims at standardizing the names of the entries and their position in the hierarchy. The specific definitions, instead, aim at defining the minimal set of parameters needed for a specific software to operate on the file.  

NeXus standards are formalized by the NIAC (the NeXus International Advisory Committee) and published once a community has reached sufficient consensus and reliable use of determined structures. NeXus also provides a set of tools: a GUI software that can surf the NeXus structure and plot data (http://nexpy.github.io/nexpy/pythongui.html), and a python package to interface with NeXus files (http://nexpy.github.io/nexpy/pythonshell.html). NeXus files can in general be handled by all software capable of reading hdf5 files.

The files deposited here are meant to be edited and discussed by the whole ARPES community, in order to reach an all-round structure that is easy to use and efficient for our experiments. 
