# fnxio-vocabularies
This repository contains list of controlled vocabularies being universal but used as a FNXIO *controlled* input both in production and in progress (with prototypes).
Vocaublaries are divided by an Operation:

- **Authority tables/Named Authority Lists (NAL)** - used to harmonise and standardise the codes and associated labels used in various execution environments and views in facilitating data exchanges.

  currencies:   https://github.com/finamatix/fnxio-vocabularies/tree/main/NAL/Currency
  
  regions: https://github.com/finamatix/fnxio-vocabularies/tree/main/NAL/Regions
  
- **Codelists (CL)** - key-value pairs which are **ordered, mutable, and do not allow duplicates**
  
- **Thesaurus** - controlled and structured vocabularies with concepts represented by labels with a hierarchical structure of broader and narrower terms. A thesaurus *may* represent a multilingual equivalent of this approach, with the same concept in each of the supported languages represented by a single preferred label.
  
- **Alignments** - common in database interoperability projects and tasks. It is in the nature of controlled vocabularies that a given concept from one vocabulary can have a level of correspondence with a concept in a different vocabulary, no matter if these controlled vocabularies comply with the same or different ontologies.
  
- **Taxonomies** is a controlled vocabulary in which all the terms belong to a single hierarchical structure and have parent/child or broader/narrower relationships to other terms. The structure is sometimes referred to as a ‘tree’. The addition of non-preferred terms/synonyms may or may not be part of a taxonomy.
