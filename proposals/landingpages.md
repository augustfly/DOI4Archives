# Landing pages
Landing page is a WEB page attached to the DOI (eg: ....)
Datacite provides a documentation about good usage (https://support.datacite.org/docs/landing-pages)

```
The landing page is primarily dedicated for Human. 
The whole DOI metadata should be visible in the web page. In particular, 
the DOI, title, authors, licences should be highlighted.
```

Additional information are often added. In particular links to services to access the data, but also any other information, specific to the data center or included in other workflows provided by the Data Center (bibtex, schema.org, DCAT, etc)

## Generate a machine-readable landing page
Search engines harvest landing page for indexation and expect some metadata serialized with a standard semantic.
For instance "schema.org" or DCAT serialized in JSON-LD are read by Google Datasets (see https://datasetsearch.research.google.com/). 

The FAIRness of the landing page can be evaluated with validators :

- FAIRchecker: https://fair-checker.france-bioinformatique.fr/
- Google: https://developers.google.com/search/docs/appearance/structured-data

## Pathologies
- https://doi.org/10.17189/1519607 (NASA/PDS): there is a title, authors, DOI, summary... but there is no direct link to the data. The "Search/Access Data" link goes to a search interface, where the user should search again with some parameter (not specified, to be guessed)
- https://doi.org/10.48322/rgf7-3h67 (HPDE): there is everything about the citation, title, doi, summary, content... but the formatting is very close to the SPASE XML record. It's ok for user fluent with SPASE, not so much for outsiders.
- https://doi.org/10.57780/esa-3xcjd4w (ESA): All required/recommended information is present, but the granuality (a single DOI for the full experience, not split with version ro processing levels...). And the data access goes to a search interface, where the user should search again for the products.
