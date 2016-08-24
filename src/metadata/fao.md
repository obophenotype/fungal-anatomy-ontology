---
layout: ontology_detail
id: fao
title: Fungal Anatomy Ontology
jobs:
  - id: https://travis-ci.org/obophenotype/fungal-anatomy-ontology
    type: travis-ci
build:
  checkout: git clone https://github.com/obophenotype/fungal-anatomy-ontology.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: Fungal Anatomy Ontology is an ontology...
domain: stuff
homepage: https://github.com/obophenotype/fungal-anatomy-ontology
products:
  - id: fao.owl
  - id: fao.obo
dependencies:
 - id: caro
 - id: ro
tracker: https://github.com/obophenotype/fungal-anatomy-ontology/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
