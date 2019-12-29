#HE911 - Corpus of Plenary Protocols of Hessen State Parliament, legislative periods 9-11 

This repository contains the plenary protocols of the Hessen State Parliament from the legislative periods 9 till 11. 
The files where obtained by OCRing the PDF-protocols available at [starweb.hessen.de](starweb.hessen.de) and therefore contain many scan artifacts at the current state.

This repository is an installable Package for R and can be obtained by executing
```
devtools::install_github("Studentenfutter/HE911")
```
It can be used via the `polmineR`-Package and activated with
```
use("HE911")
```

Many thanks to Andreas Blätte for providing access to his parsing tools for plenary protocols and to Christoph Leonhardt for additional guidance.
