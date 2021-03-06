---
layout: ontology_detail
id: trans
contact:
  email: lynn.schriml@gmail.com
  label: Lynn Schriml
description: "An ontology representing the disease transmission process during which the pathogen is transmitted directly or indirectly from its natural reservoir, a susceptible host or source to a new host."
domain: disease
homepage: http://diseaseontology.sourceforge.net/
products:
  - id: trans.owl
  - id: trans.obo
title: Pathogen Transmission Ontology

build:
  source_url: https://github.com/DiseaseOntology/PathogenTransmissionOntology/blob/master/src/ontology/transmission_process.obo
  method: obo2owl
  infallible: 1
tracker: https://github.com/DiseaseOntology/PathogenTransmissionOntology/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

The Pathogen Transmission Ontology describes the tranmission methods of human disease pathogens describing how a pathogen is transmitted from one host, reservoir, or source to another host. The pathogen transmission may occur either directly or indirectly and may involve animate vectors or inanimate vehicles.
