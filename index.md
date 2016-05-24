---
title: "EDAM"
subtitle: "Down with ontologies, long live ontologies!"
author: "Kenneth Daily"
date: "May 24, 2016"
output: 
  ioslides_presentation: 
    highlight: monochrome
    keep_md: yes
    widescreen: yes
---

## EDAM

> EDAM is an ontology of bioinformatics types of data including identifiers, data formats, operations and topics.

![Yawn](https://media4.giphy.com/media/P0YuSLm6q4xfq/200.gif)

- http://edamontology.org/
- [@edamontology](http://twitter.com/edamontology)
- [gh: edamontology/edamontology](https://github.com/edamontology/edamontology)
- [Ontology Lookup Service](http://www.ebi.ac.uk/ols/ontologies/edam)

### Use cases (subset)

- Web services including REST and SOAP APIs
- Workflows / pipelines
- Databases
- Web portals and pages
- Resource catalogues
- Documents, such as scientific publications

[Source](http://edamontology.org/)

## EDAM { .centered }

<img src='https://raw.githubusercontent.com/edamontology/edamontology/master/web/EDAMconcepts.png' alt='EDAM' width='60%'>

[Source](https://github.com/edamontology/edamontology/blob/master/web/EDAMconcepts.png)

## EDAM Example

* **Topic** - general scientific domain the software serves, e.g. “Structural biology”
* **Operation** - the precise function of the tool, e.g. “Homology modelling”
* **Data** - the primary input and output, e.g. “Protein structure”
* **Format** - the supported format(s) of the input and output, e.g. “PDB format”

Of note: separation between 'Data' and 'Format'.

[Source](http://edamontology.org/)

## Viewing and searching EDAM

http://www.ebi.ac.uk/ols/ontologies/edam

## EDAM for us?

### Pros
- Data and format terms overlap with many of our genomic-based projects: ([BAM](http://edamontology.org/format_2572), [FASTQ](http://edamontology.org/format_1930
), [VCF](http://edamontology.org/format_3016), [RNA](http://edamontology.org/topic_0099), [RNA-Seq](http://edamontology.org/topic_3170))
- Used elsewhere (Common Workflow Language, eventually)
- Extensible
- Heavy development, buy-in from many major partners (commercial and academic)

Cons
- It's an ontology (but we could use it as a controlled vocabulary)
- Require some thought on data vs format (dataType vs fileType?)

