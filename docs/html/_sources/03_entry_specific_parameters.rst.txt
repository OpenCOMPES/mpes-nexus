==========================
Entry specific parameters
==========================


An entry is meant to be relative to a single “measurement” i.e. it contains data and metadata relative to an acquisition of a specific observable.

Some of the parameters in the original list are present in the NeXus hierarchy, but much deeper in the tree. If it is decided that these parameters are necessary at this point in the hierarchy, they could be still saved in positions following the NX standard, but cross-linked in a freeform general field called ``NXentry:notes``.