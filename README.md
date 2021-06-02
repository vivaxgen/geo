# vivaxgen-geo
SNP-based geographic barcode platform for *Plasmodium vivax*

This repository provide information about the software and the instalation procedure for
[vivagen-geo](http://geo.vivaxgen.org) as described in this preprint [manuscript](https://www.biorxiv.org/content/10.1101/776781v1).

The classifier software, which also provides the web interface, can be found at https://github.com/trmznt/lkc-bisnp. Basically, the software uses modified Bernoulli Naive Bayes classifier with some modification to allow for bi-allelic data set (reference allele, alternate allele and heterozygote allele) instead of just boolean data.

The data preparation, filtering and processing are performed using https://github.com/trmznt/pys and
https://github.com/trmznt/seqpy which provide tools and library for processing WGS data, respectively.

