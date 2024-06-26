# Linked Data

DataCite provides a list of controled vocabulary that allows to specify the relationship between resources.
These relations may use DOI or any other sustainable identifier (eg: bibcode).

```
The relatsionship vocabulary is precise.
Too often, providers give their own interpretation of the terms.
If there's any doubt about the meaning of the vocabulary,
it's better to put no relationship than a misunderstood relationship type.
```

See relation vocabulary and their definitions in the [DataCite Schema](https://datacite-metadata-schema.readthedocs.io/_/downloads/en/4.5/pdf/), section 12

## Link resources within a DataCenter
DataCenter may provides resources in different granularity. For instance Chandra provides catalogue of observations. Each observation is a Product that has his own DOI.
Then the products are linked to the catalogue which has a DOI too.

example: **TODO**

## Link data from outside
There are many reasons to link a resource with external products, we give just few examples:

- link the datasets that have been used to create a product 
- link other copy (term isIdenticalTo)
- for a derived product, link the original data (qualifed terms such as isVariantFormOf,  isDerivedFrom, ...)
- cite a resource (term cites)
- etc.

Example: **TODO**


### Linking Dataset with its original resource
We distinguish a mirror copy and resource derived from an orginal resource.
But, both can have their own DOI. We encourage derived resource as wel as copy mirror to link the original resource using DataCite relations.

There are lots of reasons why a DataCenter that provides a derived resource want to provide a DOI. 
Often, the derived product is the result of a curation that provides added values.

Before creating a DOI, we encourage the DataCenter to contact the original archive and explain his plan to assign a DOI.
Some metadata from the original resources should be copyed as metadata of the derived product. But the derived metadata can also be competed with information.

- Authors: the full authors (creators and contributors) list should be copyed in the derived metadata. The list can be completed with contributors involved in the derived product curation.
- Dates: the creation and the modification dates are the dates of the DataCenter that provide the derived product
- Abstract: it is not needed to duplicate the original abstract, But the DataCenter curation could be explained
- relations: add link to the original product. 
  You can Cite (relation type "Cites") the original resource that you can complete with a relation explaining the relationship between the original and the derived product.

  Please : refer to the DataCite relationType vocabulary and do not extrapolate the semantic.

  Example: **TODO**



- 
