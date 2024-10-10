# Versioning
Distinguish dataset versioning (the Data Center responsability) and metadata versioning (automated versioning done by DataCite at each metadata update)

A good practice consists to follow a versioning mechanism for each data update. DataCite (version 4.5) recommends to create a new DOI for each major version and to stipulate the version number with the ```Version``` term. 
It is recommended to adopt a version number folowing the pattern ```major_version.minor_version ```


Different mechanisms exist:
- [Zenodo](https://zenodo.org/): makes a DOI collection of versions. Each version has its own DOI which are linked (related identifier)with the DOI collection.
- Make 1 DOI for version, link the DOI version together using related identifier ```isNewVersionOf```, ```isPreviousVersionOf```


# Evolving datasets
Versioning is well adapted for data subject to planified update, such as survey releases. Versioning implying a DOI per version is preferable for reproducibility, 
However, there are datasets that evolves regularly and for which versioning is inapropriate. For instance logs of observations evolves regularly.


For those type of datasets, we suggest to add in the DOI ```Description``` the evolving nature of the datasets and to modify the "Update" date at each modification.

In a tight flow context, for instance databases such as Simbad or NED which evolves every days, it is worth considering using the ```resourceType``` as a ```Service``` (see the DataCite controled vocabulary).
