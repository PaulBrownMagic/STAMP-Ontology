# STAMP Ontology
[![DOI](https://zenodo.org/badge/485740035.svg)](https://zenodo.org/badge/latestdoi/485740035)

This repository contains the OWL files for the STAMP Ontology.

The STAMP Ontology was created as part of PhD research undertaken entitled:
*"Ontology Supported Scaffolding for System Safety Analysis"*

This ontology was authored by Paul S. Brown under the supervision of Prof. Vania Dimitrova, Prof. Anthony G. Cohn, and Glen Hart. This research was supported by the UKRI and DSTL.

## Contents

- **tinytop**: a small top ontology module in the interest of atomicity. If you subscribe to a particular top ontology, replace this and make the necessary adaptations.
- **situation**: contains sufficient terms to capture enough information about situations and actions such that the information could be used with a Situation Calculus reasoner, like [SitCalc](https://github.com/PaulBrownMagic/SitCalc), which is available from [woolpack](https://github.com/PaulBrownMagic/woolpack).
- **controlsystem**: a partial control systems ontology with the caveat that it's authored from the perspective of STAMP with little regard for other perspectives.
- **stamp**: contains the STAMP specific terms for a user to extend in their STPA or CAST analysis
- **interlock**: the simple example analysis from "Engineering a Safer World" by Leveson as an example of using this ontology
- **traindoor**: the example used by Thomas in his thesis as another example of using this ontology
