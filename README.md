# NutriLink Ontology

## Overview

NutriLink is an ontology that links digital receipts from loyalty cards to comprehensive nutrition details of recorded products, and further to structured dietary recommendations that are based on shopped baskets.

NutriLink was created following the [Simplified Agile Methodology for Ontology Development](doi.org/10.6084/m9.figshare.3189769), based on 3 key components: 
- digital receipts from loyalty cards; 
- food product nutrition information; 
- aggregation of information of products within a single basket. 

## Purpose

The purpose of the NutriLink Ontology is to:

- Permit evaluating food purchase quality at the basket level and across baskets
- Enable provisioning of structured dietary recommendations to users

## Integration with other established ontologies

The NutriLink ontology is linked to the following established food ontologies

- [FoodOn](https://github.com/FoodOntology/foodon): Through equivalence between foodon:FoodProduct and nl:Product
- [GoodRelations](https://purl.org/goodrelations/v1): Through gr:ProductOrServiceModel and gr:hasGTIN-14
- [AGROVOC](https://agrovoc.fao.org/browse/agrovoc/en/): Through agrovoc:Products that are instances of nl:Product
- [schema.org](https://schema.org): The integration of NutriLink with schema.org is done through integration with GoodRelations and FoodOn, which employ schema concepts.

## License

This ontology is licensed under the [Creative Commons Attribution 4.0
International License (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/legalcode.en).

You are free to use, modify, and redistribute the ontology for any purpose,
provided appropriate credit is given.
