## Interpreting de novo Variation in Human Disease Using denovolyzeR.
Curr Protoc Hum Genet. 2015 Oct 6;87:7.25.1-15. doi: [10.1002/0471142905.hg0725s87](http://dx.doi.org/10.1002/0471142905.hg0725s87).

This repo contains source code to produce the above methods paper, which describes the **denovolyzeR** software package, and its application for the analysis of *de novo* variants identified in human exome sequencing.

**denovolyzeR** is an `R` package, avaiable from [CRAN](https://cran.r-project.org/web/packages/denovolyzeR/index.html).

The published manuscript is available through the [journal webpage](http://onlinelibrary.wiley.com/doi/10.1002/0471142905.hg0725s87/abstract "Curr Protoc Hum Genet."), [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/26439716), or [PubMed Central](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4606471/) (from Oct 6, 2016).  If you don't have access, then [click here](mailto:j.ware@imperial.ac.uk?subject=denovolyzeR cphg reprint request&body=I think denovolyzeR is the best thing since sliced bread.  Please send me a copy of your manuscript.) to request a pre-print from the authors.

Further information on the **denovolyzeR** software is located at <http://denovolyzer.org>.

The manuscript is authored in `rmarkdown`, compiled using `knitr`, and output as a word .docx file  
- template.docx is a template for document formatting  
- denovolyzerManuscriptReferences is an endnote library containing necessary references to format the bibliography in word after it is compiled by R.  

(in subsequent manuscripts authored in `R` we have moved to the `knitcitations` package: an open source and more readily reproducible option. This also uses flat file formats that play more nicely with git version control)
