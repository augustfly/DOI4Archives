# Building a dissemination worklow
DOI workflow requires metadata curation based on the DataCite schema which allows to improve the FAIRness of the datasets. Other workflows exists with their own semantic and metadata serialisation. These are multiple, they overlap and are also specific.

For instance, the IVOA framework provides a registry with a high level  of interoperability and point directly to the resources, whereas Datacite is specialized in data citation and link a human web page called 'landing page'.

```
Note: DOI implies to maintain a sustainable mechanism to provide a URL. This requirements, even if also in usage in the IVOA registry, is mandatory for DOI.
```

Datasets distributed in diverses frameworks complement each other and are likeky harvested by platforms or search engine such as ADS, EOSC, Google Dataset. These infrastructures adopt merge mechanisms, often a black box, that depends of their own strategy. Note that DOI, as unique identifier, facilitate the cross operations.

The list of metadata tends to increase, but the most popular are DataCite schema, Dublin Core (the ivoa registry was based on it), schema.org (extend Dublin Core and is used by Google), DCAT (linked catalogues, datasets and services. DCAT is a concurent of the VO registry), OpenCitation (a schema of linked citation),  etc.

```
All are specific, and we highlight the importance for Data providers to disseminate consistent metadata (for instance list the whole authors in all output).
```

In practice, it is better for implementers to think since the begining about the different output in order to provide consistent workflow.

**Note**: DataCite provides several serialisation of the metadata, in particular "schema.org".

```
Maintain the disseminations workflows togethers
```
See also the presention of H.Enke, Interop 2023, Bologna: https://wiki.ivoa.net/internal/IVOA/InterOpMay2023RegistryDCP/DOI-AIP-20230510.pdf


