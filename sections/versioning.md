# Versioning
Distinguish dataset versioning (the Data Center responsability) and metadata versioning (automated versioning done by DataCite at each metadata update)

A good practice consists to follow a versioning mechanism for each data update. DataCite (version 4.5) recommends to create a new DOI for each major version and to stipulate the version number with the "Version" term. 
It is recommended to adopt a version number folowing the pattern ```major_version.minor_version ```


Different mechanisms exist:
- [Zenodo](https://zenodo.org/): makes a DOI collection of versions. Each version has its own DOI which are linked (related identifier)with the DOI collection.
- Make 1 DOI for version, link the DOI version together using related identifier 'isNewVersionOf', 'isPreviousVersionOf'


# Evolving datasets
Versioning is well adapted for data subject to planified update, such as survey releases for instance. Versioning that includes a new DOI creation is preferable for reproducibility, 
However,there are other datasets that evolves regularly and for which versioning is inapropriate. For instance a database like NED or Simbad evolves every days.


For those type of datasets, se suggest to add in the DOI description the evolving nature of the datasets and to modify the "Update" date at each modification.
In a tight flow context, one have to consider too the "resourceType" as to be a "Service"
