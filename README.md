## Supporting Virtual Links with the Extended Vocabulary of Interlinked Datasets (VoIDext)

This RDF schema vocabulary (TBox) is documented and available in the [VoIDext Vocabulary Specification Draft](https://biosoda.github.io/voidext/). 
VoIDext is also accesible via the [SPARQL endpoint here](http://biosoda.expasy.org:8890/sparql).

## PURL VoIDext RDFS schema vocabulary: [http://purl.org/query/voidext](http://purl.org/query/voidext)

## VoIDext Supplementary Material 
The [Supplementary_Material_VoIDext.pdf](Supplementary_Material_VoIDext.pdf) file describes in more details the development of VoIDext based on [SAMOD: an agile methodology for the development of ontologies](http://essepuntato.github.io/samod/) methodology.

## Exemplar datasets (ABox)
The assertion box (ABox1) used to build the VoIDext is available in [ABox_examplar_data](ABox_examplar_data).
Both  "ABox_doc_examples.ttl" and "ABox_application.ttl" files were considered during the VoIDext development. "ABox_application.ttl" file contains metadata for describing the virtual link sets in the Bioquery project (see [bioquery](https://github.com/biosoda/bioquery/) github repository). 
These files include all virtual link sets among MusicBraiz, DBpedia, DrugBank, LINDAS e-government platform, EBI RDF platform and so on considered during the VoIDext development.

## Virtual links for OMA-UniProt-Bgee RDF datasets  
The assertion box (ABox) according to VoIDext for a SIB Swiss Institute of Bioinformatics application is available in [ABox_examplar_data](ABox_examplar_data).

The Beta-version of the application "[BioQuery](http://biosoda.expasy.org)" with query templates based on the federated SPARQL queries in the [Queries folder](https://github.com/biosoda/bioquery/tree/master/Queries) is available at http://biosoda.expasy.org/ . 
These SPARQL federated queries were defined according to the virtual link set metadata in [ABox_application.ttl](ABox_examplar_data) file. 

## The set of SPARQL queries (SQ) along with the competency questions (CQ)
The formal set of queries to answer the informal competency questions during the development of VoIDext is available in
 [SQ_set_of_queries](SQ_set_of_queries). 
 
These queries can be executed on the [SPARQL endpoint here](http://biosoda.expasy.org:8890/sparql) where bioquery-related virtual link sets are in the named graph "http://purl.org/query/voidext" along with VoIDext and other virtual link sets (based on non-life-sciences link sets) are part of the named graph "http://example.org/voidext".
 
Exception: "[SQ_5.txt](https://github.com/biosoda/voidext/blob/master/SQ_set_of_queries/SQ_5.txt)" that should be executed at https://www.ebi.ac.uk/rdf/services/sparql ). "[SQ_5.txt](https://github.com/biosoda/voidext/blob/master/SQ_set_of_queries/SQ_5.txt)" is actually a federated query to test a mapping function that solves heterogeneities at the ABox level.

The [queries_supplementary_examples.txt](ABox_examplar_data/queries_supplementary_examples.txt) file describes additional queries written during the development of the virtual link sets in "ABox_doc_examples.ttl" and complementary information about some link sets performance.

## Additional Information
The [voidext_with_import.ttl](https://github.com/biosoda/voidext/blob/master/voidext_with_import.ttl) file is the VoIDext RDF Turtle serialisation including imported ontologies.
