---
title: A sample Research article title
author:
  - Jane E. Doe [1,*,orcid:0000-0002-0778-8115]
  - John R.S. Smith [1,2,orcid:0000-0001-0002-0003]
bibliography: bibliography.bib
link-citations: true
...


* Correspondance:
jane.e.doe@unifraneker.nl


# Abstract

**Background:** Text for this section. Research articles should include an abstract
that does not exceed 350 words.

**Methods:** Text for this section.

**Results:** Text for this section.

**Keywords:** sample; article; author

<!-- A graphical abstract can be supplied which, together with the article title,
  should provide the reader with a visual description of the type of chemistry covered
  in the article. The graphical abstract should be 920 x 300 pixels and a maximum of
  150KB jpeg, png or svg file. -->

# Introduction

This Markdown template is for a Research article in the *Journal of Cheminformatics*.
It requires pandoc 2.12 or later to be converted to a Word .docx or PDF, with the 
provided *Makefile*. See the [pandoc manual](http://pandoc.org/MANUAL.html) for more
information on pandoc.

# Methods

## Information about software and data

Reviewers and readers of a research paper must be able to use the used software and
data to reach the same Results. *Journal of Cheminformatics* will only publish research
or software that is entirely reproducible by third parties. This means that any
datasets, software and algorithms that are required to reach the conclusions stated
in the paper must be provided as supplemental materials, or be otherwise accessible
without the need for registration, login or agreement with license terms other than
Creative Commons licenses for data and text and OSI-approved Open Source Licenses
for software. For any software, the source code must be provided
@agrees_with:Guha_Willighagen_2017.

## Adding References

References are added to the content in a similar way as LaTeX and there is a
`bibliography.bib` in this folder in the BibTeX format. A citation is made
by including an *\@* followed by the BibTeX key, for example like
*\@Upper_writers_1974* for Ref. @Upper_writers_1974.

Now, the *Journal of Cheminformatics* support citation typing ontology annotations
using the CiTO @uses_method_in:Willighagen_2020.


# Results


# Discussion

# Conclusions

# List of abbreviations



### CiTO annotation

The Journal of Cheminformatics welcomes authors to participate in our pilot using
the Citation Typing Ontology (http://purl.org/spar/cito). For more information, please see here. 

#### Availability of data and materials
Text for this section.

#### Competing interests
Text for this section.

#### Funding
Text for this section.

#### Authors' contributions
Text for this section.

#### Acknowledgements
Text for this section.

#### Authors' information (optional)
Text for this section.



# References
