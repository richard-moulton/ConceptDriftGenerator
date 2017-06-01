This project is a complement to the Massive Online Analysis (MOA) library and aims to provide
a categorical data generator which incorporates extended concept drift with given magnitude. It has been tested for compatability with MOA 16.04.

This project is an extension the the ConceptDriftGenerator developed by:
Webb, Geoffrey I. and Hyde, Roy and Cao, Hong and Nguyen, Hai Long and Petitjean, Francois
and based on their article "Characterizing concept drift."

Webb et al. define abrupt drift as occuring between two concepts, n and n+1, when the time
between the end of concept n and the start of concept n+1 is less than or equal to delta (a natural number, > 0).

Complementarily, Webb et al. also define extended drift as occuring between two concepts, n and n+1,
when the time between the end of concept n and the start of concept n+1 is greater than delta.

Specifically, this extension allows the user to select the length of the concept drift's duration,
thus allowing for data streams with extended concept drift of an arbitrary duration to be generated
and not only those with abrupt concept drift.


When using this repository, please cite:

```
@ARTICLE{Webb2016,
  author="Webb, Geoffrey I. and Hyde, Roy and Cao, Hong and Nguyen, Hai Long and Petitjean, Francois",
  title="Characterizing concept drift",
  journal="Data Mining and Knowledge Discovery",
  year="2016",
  volume="30",
  number="4",
  pages="964--994",
  doi="10.1007/s10618-015-0448-4",
  url="http://dx.doi.org/10.1007/s10618-015-0448-4"
}
```

The paper is available for download at: https://arxiv.org/pdf/1511.03816v6.pdf

The original ConceptDriftGenerator repository is [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.35005.svg)](https://doi.org/10.5281/zenodo.35005)
It is also available at: https://github.com/fpetitjean/ConceptDriftGenerator

It requires the Apache Commons Math for random number generators.   
