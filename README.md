## Supporting Virtual Links with the Extended Vocabulary of Interlinked Datasets (VoIDext)

This RDF schema vocabulary (TBox) is documented and available in the [VoIDext Vocabulary Specification Draft](https://biosoda.github.io/voidext/). 
In addition, the [voidext_with_import.ttl](https://github.com/biosoda/voidext/blob/master/voidext_with_import.ttl) file is the VoIDext RDF Turtle serialisation including imported ontologies.
VoIDext is also accesible via the [SPARQL endpoint here](http://biosoda.expasy.org:8890/sparql).

## PURL VoIDext: [http://purl.org/query/voidext](http://purl.org/query/voidext)

## Exemplar datasets (ABox)
The assertion box (ABox1) used to build the VoIDext is available in [ABox_examplar_data](ABox_examplar_data).
Both  "ABox_paper_examples.ttl" and "ABox_application.ttl" files were considered during the VoIDext development. "ABox_application.ttl" file contains metadata for describing the virtual links in the Bioquery project (see [bioquery](https://github.com/biosoda/bioquery/) github repository).

## Virtual links for OMA-UniProt-Bgee RDF datasets  
The real case study  assertion box (ABox) according to VoIDext is available in [ABox_examplar_data](ABox_examplar_data).

The under-development application with query templates based on the federated SPARQL queries in the [federated_queries.xlsx file](https://github.com/biosoda/bioquery/tree/master/Queries) is available at http://biosoda.expasy.org/ . 
These SPARQL federated queries were defined according to the virtual link metadata in [ABox_application.ttl](ABox_examplar_data) file. 

## The set of SPARQL queries (SQ) along with the competency questions (CQ)
The formal set of queries to answer the informal competency questions during the development of VoIDext is available in
 [SQ_set_of_queries](SQ_set_of_queries). 
These queries can be executed on the [SPARQL endpoint here](http://biosoda.expasy.org:8890/sparql). 
