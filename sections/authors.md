# Authors
```
The good usage consists to add all authors and not only the first author. 
```
All authors are indeed asked by journals for citations.

We encourage also to add the authors [ORCID](https://orcid.org/) with their affiliations.
When possible inform the [RoR](https://ror.org/).


Example of a unique author.
```
  "creators": [
    {
      "name": "Ochsenbein, Francois",
      "nameType": "Personal",
      "givenName": "Francois",
      "familyName": "Ochsenbein",
      "affiliation": [
        {
          "name": "Observatoire astronomique de Strasbourg",
          "schemeUri": "https://ror.org",
          "affiliationIdentifier": "https://ror.org/04xsj2p07",
          "affiliationIdentifierScheme": "ROR"
        }
      ],
      "nameIdentifiers": [
        {
          "schemeUri": "https://orcid.org/",
          "nameIdentifier": "0000-0003-4667-015X",
          "nameIdentifierScheme": "ORCID"
        }
      ]
    }
   ]
```
    
## Creators and contributors
DataCite distinguishes creators and contributors. The authors are conceptually the same that the Datacite term "creator" (issues #26).

- The "creator" can be a Person or an Organization.
- Contributors are persons or organizations that contributed to the development of the resources (sic DataCite Schema 4.5).  
A contributor has a role (eg: 'Editor', 'Supervisor', etc.) taken in a controled vocubulary
(see 'contributorType' term and the complete list in [DataCite Schema](https://datacite-metadata-schema.readthedocs.io/_/downloads/en/4.5/pdf/)).

In a way "Contributors" are an alternative of "Creators". For instance, [Zenodo](https://zenodo.org) provides a way to add a role to creators in its upload form.
However, DOI created by Zeonodo used only Creator term.

The usage of Contributor in citation has not been evaluated today.

