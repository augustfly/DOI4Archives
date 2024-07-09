# Titles
Title is an important metadata, it describes the resource and is often exploited by search engine (such as ADS or VO-registry) in a text search process.

```
Assigning a title is specific to each dataset. 
It is a short and unique sentence that contains the most relevant aspects of the dataset.
```


For datasets derived or attached to a reference article, it is better to create a new description  that describes the dataset.

Example :
- Reference article:  ApJ (Draper Z.H, 2000), https://doi.org?10.1088/0004-637X/786/2/120

    "Disk-loss and disk-renewal phases in classical Be stars. II. Contrasting with stable and variable disks"
- Dataset Title : VizieR, https://doi.org? 10.26093/cds/vizier.17860120

    "Spectropolarimetric survey of classical Be stars"


Making a good title is of course specific to the dataset. For instance, we can name the object or type studied, the facility used, the release version, or the  measurement methods if it is spectropscopy or photometry, etc.

<!--- An observation dataset of a peculiar astronomical object must contains the object name in the title.
- A study of a particular type of object must be in the title. 
- For observations, the wave band or the facility can complete the title
- In some case, the observation methods are important
- For catalogues providing a media, indicated the type of data (for example catalogue of spectra)
- If the dataset is the final product of a suvey, then the survey name must be in the title with its version release.
-->

example of title: TODO

# Description

The description completes the title. Generaly, the description is not exploited by search process.
However, like the title, the description describes the data and not its reference, even when the data comes from an original resource. 

Datacite provides a description qualifier (```Abstract```, ```Methods```, ...) which depends of the resource.

## Description for data derived from external resource

When the data derived from an external resource is not a simple copy, it is recommended to adapt the original description.
For example, in the case of data attached to a published article, rather than reproducing the abstract of the reference article (which may also be subject to the same license as the article), the description may focused on the dataset content with added information such as thoses usefull to produce the datasets.

An other good practice consist to add in the description a reference to the data origin.

Example : VizieR DOI description example -

   "VizieR online Data Catalogue associated with article published in journal 
    Monthly Notices of the Royal Astronomical Society with title ... "
