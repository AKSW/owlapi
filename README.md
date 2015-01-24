owlapi
======

OWL API main repository

The OWL API is a Java API for creating, manipulating and serialising OWL Ontologies. 
The latest version of the API supports OWL 2.

It is available under Open Source licenses (LGPL and Apache).

The following components are included:

An API for OWL 2 and an efficient in-memory reference implementation
RDF/XML parser and writer
OWL/XML parser and writer
OWL Functional Syntax parser and writer
Turtle parser and writer
KRSS parser
OBO Flat file format parser
Reasoner interfaces for working with reasoners such as FaCT++, HermiT, Pellet, Racer, JFact and Chainsaw.


DL-Learner modifications
=====

Allow for class expressions containing (A AND A) and (A OR A)

* OWLNaryBooleanClassExpressionImpl
* OWLObjectUnionOfImpl
* OWLObjectIntersectionOfImpl
* OWLDataFactory
* OWLDataFactoryImpl
* SimpleRenderer
