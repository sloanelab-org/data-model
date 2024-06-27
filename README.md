# Sloane Lab Data Model

This repository contains the Sloane Lab Data Model expressed in the [OWL](https://www.w3.org/TR/2012/REC-owl2-overview-20121211/) language using the [Turtle](https://www.w3.org/TR/turtle/) syntax. The model extends the [CIDOC CRM](https://cidoc-crm.org) reference model and imports the [CRMdig](https://cidoc-crm.org/crmdig/) ontology. A list of newly-defined classes, properties, and individuals is provided below. Their descriptions can be found in the OWL document.

## Classes
* SL1 Catalogue Item

## Properties
* SL10 has specific type
* SL11 is specifically about
* SL12 has confidence degree
* SL13 has physical description
* SL14 has curator comment
* SL15 believed to be the same as
* SL16 has object history
* SL17 has scope content
* SL18 has entry number
* SL19 has page number
* SL20 has object status
* SL21 is matched
* SL22 contains elements of

## Instances of E55 Type
* author
* Historia Plantarum dataset
* Historia Plantarum entry
* Historia Plantarum header
* Historia Plantarum footer
* Historia Plantarum marginalia
* historical catalogue
* historical catalogue entry
* historical dataset
* inscription
* library dataset
* library record
* manuscript
* material
* museum dataset
* museum record
* object type
* publication place
* technique
* species
* subject

## Instances of E3 Condition State
* ex-collection
* matched
* matched uncertain
* non-registered
* registered
* unknown
* unmatched

_Disclaimer: The Sloane Lab Data Model is a work in progress and may require changes before it is ready to be deployed in different projects. Class and property identifiers are subject to change. If you have any questions about this repository, please contact [sloanelab@ucl.ac.uk](mailto:sloanelab@ucl.ac.uk)._
