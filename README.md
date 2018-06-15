# README #

City4Age Project's (H2020 grant agreement number 689731) Ontology Model.

The City4Age ontology model has been developed to represent individual citizens’ data regarding personal and health profile, contextual data, performed actions and activities, behaviour, risk indicators and interventions managed by different information subsystems in the context of City4Age platform. 

The City4Age ontology model has been designed reusing as much as possible the existing ontologies and vocabularies of related domains and linking it to DBpedia, Schema.org and other Open Datasets of the LOD cloud following Linked Data principles. The following external ontologies have been directly imported in the City4Age foundational ontology as part of the network of ontologies that implement it: Semantic Sensor Network (SSN  and SOSA  core) ontology, Provenance (PROV-O) ontology, DBpedia (DBO, DBP) ontology, GeoNames (GN) ontology, DEMLAB ontology and Health and LifeSciences (HLIFESCI) ontology, an extension within schema.org. DEMLAB and HLIFESCI ontologies have been uploaded to our server with modified URIs for testing and research purposes in the context of the City4Age project, since they cannot be imported in the common and well-known ontology editor Protégé via their URI namespace. We have also integrated some ideas from different ontologies and reusing / extending some classes and creating new ones to improve the network of ontologies. Most of the external entities have been aligned and merged into the City4Age foundational ontology using “subClassOf”, “equivalentClass” or other OWL statements applying Linked Data principles in order to reuse, map and align as much resources as possible from already consolidated ontologies in related fields.

CONTENT:
========

A network of ontologies for the City4Age global model has been developed to integrate other modelling proposals generated in the context of the project in order to achieve harmonization among these models. Each model has been implemented as a single ontology, but imported together in the City4Age foundational ontology. The solution is composed by a network of ontologies available from each corresponding URL for public inspection and comment:

1. **Personal Data Ontology** includes most of the entities (personal, organic and health profile, including contextual data and performed activities) represented in the data model implemented for the Personal Data Capture subsystem.
2. **Frailty and MCI risk detection ontology** based on the data model about MCI/Frailty risk indicators for the Health Risk Detection subsystem.
3. **Intervention ontology** based on the intervention model proposed for the Intervention subsystem. This ontology also imports a _COM-B ontology_ developed to implement the COM-B model integrated in the proposed intervention model.
  
USAGE:
======


ACKNOWLEDGEMENTS
================

This work was carried out with the financial support of H2020 project City4Age, grant agreement number 689731. Thanks to the teams behind the external ontologies and vocabularies reused in the City4Age ontology model for making their work available to other researchers.