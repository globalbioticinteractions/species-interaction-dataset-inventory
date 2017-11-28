# known-projects
This project provides a list of known projects and studies that contains interaction data, that may or may not have been made available. The goal of this is to make an inventory of datasets with their species interaction summaries.

## data elements

To make it easy to find existing interaction datasets without necessarily including all the interaction records,  one or more entries per datasets are provided to capture the nature of the interaction records. Each element includes the following elements.

element name | required | example | description
--- | --- | --- | ---
sourceTaxonName | Y | Animalia | describes a starting point of an interaction
interactionTypeId | N | RO:0002455 | a identifier for the interaction from Relations Ontology (e.g., see http://www.ontobee.org/ontology/RO?iri=http://purl.obolibrary.org/obo/RO_0002556)
interactionTypeLabel | Y | pollinates | human readable description of the interaction
targetTaxonName | Y | Plantae | describes a 
referenceCitation | Y | IABIN Pollinators Thematic Network (IABIN PTN) | citation for specific dataset	
referenceUrl | N | http://www.biocomp.org.br/iabinptn | link to dataset

The examples above describe a dataset ```IABIN Pollinators Thematic Network (IABIN PTN)``` at http://www.biocomp.org.br/iabinptn that describes Animalia pollinating plants .

For the existing list, please see [interactions.tsv](./interactions.tsv)

## contribute 
To add to this list, please do one of the following:

1. edit [interactions.tsv](./interactions.tsv), add your entries (in [tab separated values](https://en.wikipedia.org/wiki/Tab-separated_values)) and create a pull request
2. (if 1. sounds scary) [open an issue](../../issues/new) and include description of datasets containing the information elements above.
3. (if 1. and 2. sound scary) [send an email](mailto:info@globalbioticinteractions.org) containing the information elements above.

To be included in http://globalbioticinteractions.org .
