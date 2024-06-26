# Versioning
Distinguish dataset versioning (the Data Center responsability) and metadata versioning (automated versioning done by DataCite at each metadata update)

Different mechanisms exist:
- [Zenodo](https://zenodo.org/): makes a DOI collection of versions. Each version has its own DOI which are linked (related identifier)with the DOI collection.
- Make 1 DOI for version, link the DOI version together using related identifier 'isNewVersionOf', 'isPreviousVersionOf'
