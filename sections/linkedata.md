# Linked Data

DataCite provides a list of controled vocabulary that allows to specify the role existing betwen a resource and an external resource.
These relations may use DOI or other sustainable identifier (eg: bibcode).

```
The relatsionship vocabulary is precise. Too often, providers give their own interpretation of the term.
In case of doubts on a vacubulary meaning, it is better to put no relations that a misunderstood relation type.
```

See relation vocabulary and their definition in the [DataCite Schema](https://datacite-metadata-schema.readthedocs.io/_/downloads/en/4.5/pdf/), section 12)

## Link resources within a DataCenter
Datancenter may provides resources in different granularity. For instance Chandra provides a catalogue of observations. Each observation is a Product that has his own DOI.
Then the product is linked to the catalogue which has a DOI too.

example: TODO

## Link data from outside
There are many reason to link a resource with external products, we give just few examples:

- link datasets used to create a product 
- link other copy (term isIdenticalTo)
- for a derived product, link the original data(qualifed terms such as isVariantFormOf,  isDerivedFrom, ...)
- cite a resource (term cites)
- etc.

Example:


### Linking Dataset with its original resource
We distinguish between a mirror copy and resource derived from an orginal resource.

Both can have their own DOI. We encourage derived resource as wel as copy mirror to link the original resource using DataCite relations.

There are lots of reason why a DataCenter that provides a derived resource want to provide a DOI. 
Often, the derived product is the result of a curation that provides added values.

Before creating a DOI, we encourgae the DataCenter to contact the original archive and explain his plan to assign a DOI.
Some metadata from the original resources should be copyed as metadata of the derived product. But the derived metadata can also be competed by information.

- Authors: the full authors (creators and contributors) list should be copyed in the derived metadata. The list can be completed with contributors involved in the derived product curation.
- Dates: the creation and the modification dates are the dates of the DataCenter that provide the derived product
- Abstract: it is not needed to duplicate the original abstract, But the DataCenter curation could be explained
- relations: add link to the original product. 
  You can Cite (relation type "Cites") the original resource that you can complete with a relation explaining the relationship between the original and the derived product.

  Please : refer to the DataCite relationType vocabulary and do not extrapolate the semantic.



- 
