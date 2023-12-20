vocabulary name: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary
getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21794f3020>

object: iSamples Material Sample Type Vocabulary

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary

getObject predicate: http://purl.org/dc/terms/modified

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21795748f0>

object: 2022-03-11

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e99d0>

object: Broad categories to specify the kind of physical thing identified as the ‘sample’.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9a90>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary

getObject predicate: http://www.w3.org/2004/02/skos/core#historyNote

length of qres: 5

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eaea0>

object: 2022-01-07 SMR Change base URI to https://w3id.org/isample/vocabulary/, setting up resolution using w3id. Make the conceptScheme and ontology. Add Dublin core imports.

object: 2022-03-11 SMR change definitions from rdfs:comment to skos:definition. Minor fixes in definitions. Add skos matches to URIs from other vocabularies.

object: 2022-09-30 SMR per https://github.com/isamplesorg/metadata/issues/109, change specimen to sample in vocabulary names and labels. Add 'Slurry biome aggregation' and 'Bundle biome aggregation' (github issue 110). Rename 'liquid or gas' sample type to 'fluid in container' (github issue 108).

object: 2023-07-27 SMR modify base specimen type vocabulary, add 'Non biologic solid object'  change broader relations in this vocab to use that as parent class where appropriate.  Intention is a specimen category for solid objects that are not biologic; this subsumes 'Fossil' and 'Artifact', but excludes living organism, their parts and products. Obviously there is some overlap with Research specimens.

object: 2023-11-06 SMR add missing inScheme on Non-biologic solid object and solid materal specimen. Update version number in URI to 1.0

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb650>

object: Physical specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb4a0>

object: Any aggregation specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb140>

object: Anthropogenic aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf350>

object: Biome aggregation sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9d30>

object: Bundle biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784ebd40>

object: Slurry biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eac90>

object: Aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bfda0>

object: Any biological specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781be2d0>

object: Biome aggregation sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf770>

object: Bundle biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bfef0>

object: Slurry biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9ca0>

object: Organism part

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21793d3a10>

object: Organism product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb050>

object: Whole organism specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf140>

object: Fluid in container

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf1d0>

object: Non biologic solid object

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4d40>

object: Artifact

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf710>

object: Fossil

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bee70>

object: Other solid object

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eacf0>

object: Research product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4980>

object: Analytical preparation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21794f3230>

object: Experiment product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eaba0>

object: Physical specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bffe0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e98e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eab40>

object: A material entity that represents an entity of interest in whole or in part (http://rs.tdwg.org/dwc/terms/MaterialSample) . Top concept in material sample type type hierarchy.  Represents any physical specimen (matrial sample).

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781be1e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781be2d0>

object: material sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf230>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bd490>

object: Any aggregation specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eaf00>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9b50>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4980>

object: Sample consists of a bunch of material fragments, not related to the same object (e.g. not a bunch of broken pot sherds that might be reassembled), but taken together representative of the sampled feature. Examples: loose soil, sediment, crushed rock,  particulate, bunches of unrelated pot sherd, human production waste, filtrates and residues. The sample requires some kind of container to keep it together. Cores of loosely consolidated material are considered 'Solid material specimen' because the internal parts have spatial relationships (e.g. upper part, lower part, sedimentary structures).

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d59a0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6660>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5970>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f217934fc50>

object: Anthropogenic aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f217934fc50>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781be150>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bdc70>

object: Aggregation consists of fragments of material produced by human activity,  not described individually, and generally not all originating from the same object.  Includes pottery in an excavation unit that gets an aggregate description, production waste, production raw-materials, or other residues (broken bits of plaster from a destroyed wall), synthetic powders.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bdc10>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9c40>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/anthropogenicaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9640>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bee40>

object: Biome aggregation sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 2

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb080>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21792fd8e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb7d0>

object: Specimen is an aggregation of whole or fragmentary parts of multiple organisms, microscopic or megascopic, representative of some site.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bee40>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bdbb0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781be120>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bffb0>

object: Bundle biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d69c0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d50d0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bdf70>

object: An aggregation of whole organisms representative of some biome

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bdbe0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21787e5c70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bee70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eadb0>

object: Slurry biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb770>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9790>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb770>

object: specimen consists of mixed organic and inorganic material, including whole organisms and organism fragments.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6e40>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9340>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e96a0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf260>

object: Aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5280>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6a80>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d41d0>

object: An aggregate specimen that is not biogenic or composed of anthropogenic material fragments.  Examples: loose soil or sediment (e.g. in a bag), rock chips, particulate filtrate or precipitate; rock powders.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7320>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4740>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/genericaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf2c0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9e20>

object: Any biological specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d73b0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5f40>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4ce0>

object: Specimen for which the sampled feature is one or more living organisms from a particular biome context, megascopic or microscopic

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d74d0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d46e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d74d0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4b00>

object: Biome aggregation sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 2

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4920>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/anyaggregation

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4f50>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6e70>

object: Specimen is an aggregation of whole or fragmentary parts of multiple organisms, microscopic or megascopic, representative of some site.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d78f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5e80>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4fe0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eaff0>

object: Bundle biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21793d2e40>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21790069f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6a50>

object: An aggregation of whole organisms representative of some biome

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d54c0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6570>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/bundlebiomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d76e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7020>

object: Slurry biome aggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5df0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biomeaggregation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d63c0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5c10>

object: specimen consists of mixed organic and inorganic material, including whole organisms and organism fragments.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d68d0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7260>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/slurrybiomeaggregation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4ef0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6f90>

object: Organism part

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d72c0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9f70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb1d0>

object: Part of an organism, e.g. a tissue sample, plant leaf, flower, bird feather. Include internal parts not composed of organic material (e.g. teeth, bone), and hard body parts that are not shed (hoof, horn, tusk, claw).  Hair is tricky, include here for now.  Does not necessarily imply existance of parent sample. Not fossilized; generally includes organism parts native to deposits of Holocene to Recent age.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4cb0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7980>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismpart

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d52e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5820>

object: Organism product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d64e0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6ba0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5640>

object: Specimen is a thing produced by some organism, generally not composed of organic material or including biological tissue, e.g. Shell, antler, egg shell, coral skeleton (organic tissue not included), fecal matter, cocoon, web.  Consider internal parts not composed of organic material (e.g. teeth, bone) and hard body parts that are not shed (hoof, horn, tusk) to be organism parts.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6720>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d57f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/organismproduct

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5af0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7f20>

object: Whole organism specimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d72c0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/biologicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6c00>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d47a0>

object: Specimen consists of the bodies of one or more entire organisms of the same species, from any kingdom. Note that these are also inherently 'solid object'

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4140>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6c60>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/wholeorganism

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6cc0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5190>

object: Fluid in container

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4a10>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4380>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5490>

object: Specimen is a container whose contents are liquid, gas, or mixed dominantly fluid phases that is the actual sample material. Fluid might include minor solid particles. Container typically human made, but also includes natural fluid container, e.g. fluid inclusion in a mineral grain.  Includes colloids, foams, gels, suspensions. The sample is the fluid substance; fluid samples collected to analyze the contained biome should be considered 'Biome Aggregation'

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7020>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4a70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fluidincontainer

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7f80>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784ebbc0>

object: Non biologic solid object

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9af0>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eaf30>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb560>

object: Individual solid object, not formed directly by or part of a living organism

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4320>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d55e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4410>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6570>

object: Artifact

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781beb70>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4ec0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4cb0>

object: An object made (manufactured, shaped, modified) by a human being, or precursor hominid. Include a set of pieces belonging originally to a single object and treated as a single specimen.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d73b0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4950>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/artifact

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5df0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6480>

object: Fossil

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784ebb30>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb980>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6090>

object: Specimen is the remains of one or more organisms preserved in rock; includes whole body, body parts (usually bone or shell), and trace fossils. An organism or organism part becomes a fossil when it has undergone some fossilization process that generally entails physical and chemical changes akin to diagenesis in a sedimentary rock. Includes trace fossils, which are manifestations of biologic activity preserved in a rock body (typically sedimentary), without included preserved body parts.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d75c0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4d10>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/fossil

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d66f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5d90>

object: Other solid object

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb530>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/nonbiologicsolidobject

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eae70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb4a0>

object: Single piece of material not one of the other types.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784ea120>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9730>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/othersolidobject

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d69f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7aa0>

object: Research product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7530>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/physicalspecimen

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5df0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d76e0>

object: Specimen is a product of some research workflow, e.g. a thin section, an XRF pellet, a grain mount, SEM stub, synthetic rock or mineral ...  In general there should be a link to a parent specimen from which this was derived.  Might be aggregation (e.g. a synthetic material powder) or a solid object.

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d73b0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d79b0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf0e0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d7650>

object: Analytical preparation

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6720>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d77a0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5310>

object: Specimen is a product of processing required for some observation procedure, e.g. thin section, XRF bead, SEM stub, rock powder. If identified separately, this should have a ‘parent’ link to the original sample

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6480>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf8f0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/analyticalpreparation

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781bf1d0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#prefLabel

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d4a70>

object: Experiment product

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#broader

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d5790>

object: https://w3id.org/isample/vocabulary/specimentype/1.0/researchproduct

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#comment

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6720>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#definition

length of qres: 1

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d70b0>

object: Specimen is product of an experimental procedure (e.g. synthetic material)

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2000/01/rdf-schema#seeAlso

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784e9f70>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://www.w3.org/2004/02/skos/core#altLabel

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21781d6ea0>

getObject prefixes: 
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>


getObject subject: https://w3id.org/isample/vocabulary/specimentype/1.0/experimentalproduct

getObject predicate: http://purl.org/dc/terms/source

length of qres: 0

qres: <rdflib.plugins.sparql.processor.SPARQLResult object at 0x7f21784eb350>

---
comment: | 
  WARNING: This file is generated. Any edits will be lost!
format:
  html:
    ascii: true
    toc: true
    toc-depth: 4
    number-sections: true
    anchor-sections: false
    number-depth: 8
execute:
  echo: false
---

[]{#iSamplesMaterialSampleTypeVocabulary}

# **Concept scheme:** iSamples Material Sample Type Vocabulary

Vocabulary last modified:  2022-03-11

subtitle: 
  Broad categories to specify the kind of physical thing identified as the ‘sample’.

Namespace: 
[`https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary`](https://w3id.org/isample/vocabulary/specimentype/1.0/specimentypevocabulary)

**History**

* 2022-01-07 SMR Change base URI to https://w3id.org/isample/vocabulary/, setting up resolution using w3id. Make the conceptScheme and ontology. Add Dublin core imports.
* 2022-03-11 SMR change definitions from rdfs:comment to skos:definition. Minor fixes in definitions. Add skos matches to URIs from other vocabularies.
* 2022-09-30 SMR per https://github.com/isamplesorg/metadata/issues/109, change specimen to sample in vocabulary names and labels. Add 'Slurry biome aggregation' and 'Bundle biome aggregation' (github issue 110). Rename 'liquid or gas' sample type to 'fluid in container' (github issue 108).
* 2023-07-27 SMR modify base specimen type vocabulary, add 'Non biologic solid object'  change broader relations in this vocab to use that as parent class where appropriate.  Intention is a specimen category for solid objects that are not biologic; this subsumes 'Fossil' and 'Artifact', but excludes living organism, their parts and products. Obviously there is some overlap with Research specimens.
* 2023-11-06 SMR add missing inScheme on Non-biologic solid object and solid materal specimen. Update version number in URI to 1.0

- [Physical specimen](#physicalspecimen)
    - [Any aggregation specimen](#anyaggregation)
        - [Anthropogenic aggregation](#anthropogenicaggregation)
        - [Biome aggregation sample](#biomeaggregation)
            - [Bundle biome aggregation](#bundlebiomeaggregation)
            - [Slurry biome aggregation](#slurrybiomeaggregation)
        - [Aggregation](#genericaggregation)
    - [Any biological specimen](#biologicalspecimen)
        - [Biome aggregation sample](#biomeaggregation)
            - [Bundle biome aggregation](#bundlebiomeaggregation)
            - [Slurry biome aggregation](#slurrybiomeaggregation)
        - [Organism part](#organismpart)
        - [Organism product](#organismproduct)
        - [Whole organism specimen](#wholeorganism)
    - [Fluid in container](#fluidincontainer)
    - [Non biologic solid object](#nonbiologicsolidobject)
        - [Artifact](#artifact)
        - [Fossil](#fossil)
        - [Other solid object](#othersolidobject)
    - [Research product](#researchproduct)
        - [Analytical preparation](#analyticalpreparation)
        - [Experiment product](#experimentalproduct)

**Concepts**

[]{#physicalspecimen}

##  Physical specimen


- A material entity that represents an entity of interest in whole or
in part (http://rs.tdwg.org/dwc/terms/MaterialSample) . Top concept in
material sample type type hierarchy.  Represents any physical specimen
(matrial sample).

- **Alternate labels:**
material sample

- Concept URI token: physicalspecimen


[]{#anyaggregation}

###  Any aggregation specimen


- Child of:
 [`physicalspecimen`](#physicalspecimen)

- Sample consists of a bunch of material fragments, not related to the
same object (e.g. not a bunch of broken pot sherds that might be
reassembled), but taken together representative of the sampled
feature. Examples: loose soil, sediment, crushed rock,  particulate,
bunches of unrelated pot sherd, human production waste, filtrates and
residues. The sample requires some kind of container to keep it
together. Cores of loosely consolidated material are considered 'Solid
material specimen' because the internal parts have spatial
relationships (e.g. upper part, lower part, sedimentary structures).
- Concept URI token: anyaggregation


[]{#anthropogenicaggregation}

####  Anthropogenic aggregation


- Child of:
 [`anyaggregation`](#anyaggregation)

- Aggregation consists of fragments of material produced by human
activity,  not described individually, and generally not all
originating from the same object.  Includes pottery in an excavation
unit that gets an aggregate description, production waste, production
raw-materials, or other residues (broken bits of plaster from a
destroyed wall), synthetic powders.
- Concept URI token: anthropogenicaggregation


[]{#biomeaggregation}

####  Biome aggregation sample


- Child of:
 [`anyaggregation`](#anyaggregation)
 [`biologicalspecimen`](#biologicalspecimen)

- Specimen is an aggregation of whole or fragmentary parts of multiple
organisms, microscopic or megascopic, representative of some site.
- Concept URI token: biomeaggregation


[]{#bundlebiomeaggregation}

#####  Bundle biome aggregation


- Child of:
 [`biomeaggregation`](#biomeaggregation)

- An aggregation of whole organisms representative of some biome
- Concept URI token: bundlebiomeaggregation


[]{#slurrybiomeaggregation}

#####  Slurry biome aggregation


- Child of:
 [`biomeaggregation`](#biomeaggregation)

- specimen consists of mixed organic and inorganic material, including
whole organisms and organism fragments.
- Concept URI token: slurrybiomeaggregation


[]{#genericaggregation}

####  Aggregation


- Child of:
 [`anyaggregation`](#anyaggregation)

- An aggregate specimen that is not biogenic or composed of
anthropogenic material fragments.  Examples: loose soil or sediment
(e.g. in a bag), rock chips, particulate filtrate or precipitate; rock
powders.
- Concept URI token: genericaggregation


[]{#biologicalspecimen}

###  Any biological specimen


- Child of:
 [`physicalspecimen`](#physicalspecimen)

- Specimen for which the sampled feature is one or more living
organisms from a particular biome context, megascopic or microscopic
- Concept URI token: biologicalspecimen


[]{#biomeaggregation}

####  Biome aggregation sample


- Child of:
 [`anyaggregation`](#anyaggregation)
 [`biologicalspecimen`](#biologicalspecimen)

- Specimen is an aggregation of whole or fragmentary parts of multiple
organisms, microscopic or megascopic, representative of some site.
- Concept URI token: biomeaggregation


[]{#bundlebiomeaggregation}

#####  Bundle biome aggregation


- Child of:
 [`biomeaggregation`](#biomeaggregation)

- An aggregation of whole organisms representative of some biome
- Concept URI token: bundlebiomeaggregation


[]{#slurrybiomeaggregation}

#####  Slurry biome aggregation


- Child of:
 [`biomeaggregation`](#biomeaggregation)

- specimen consists of mixed organic and inorganic material, including
whole organisms and organism fragments.
- Concept URI token: slurrybiomeaggregation


[]{#organismpart}

####  Organism part


- Child of:
 [`biologicalspecimen`](#biologicalspecimen)

- Part of an organism, e.g. a tissue sample, plant leaf, flower, bird
feather. Include internal parts not composed of organic material (e.g.
teeth, bone), and hard body parts that are not shed (hoof, horn, tusk,
claw).  Hair is tricky, include here for now.  Does not necessarily
imply existance of parent sample. Not fossilized; generally includes
organism parts native to deposits of Holocene to Recent age.
- Concept URI token: organismpart


[]{#organismproduct}

####  Organism product


- Child of:
 [`biologicalspecimen`](#biologicalspecimen)

- Specimen is a thing produced by some organism, generally not
composed of organic material or including biological tissue, e.g.
Shell, antler, egg shell, coral skeleton (organic tissue not
included), fecal matter, cocoon, web.  Consider internal parts not
composed of organic material (e.g. teeth, bone) and hard body parts
that are not shed (hoof, horn, tusk) to be organism parts.
- Concept URI token: organismproduct


[]{#wholeorganism}

####  Whole organism specimen


- Child of:
 [`biologicalspecimen`](#biologicalspecimen)

- Specimen consists of the bodies of one or more entire organisms of
the same species, from any kingdom. Note that these are also
inherently 'solid object'
- Concept URI token: wholeorganism


[]{#fluidincontainer}

###  Fluid in container


- Child of:
 [`physicalspecimen`](#physicalspecimen)

- Specimen is a container whose contents are liquid, gas, or mixed
dominantly fluid phases that is the actual sample material. Fluid
might include minor solid particles. Container typically human made,
but also includes natural fluid container, e.g. fluid inclusion in a
mineral grain.  Includes colloids, foams, gels, suspensions. The
sample is the fluid substance; fluid samples collected to analyze the
contained biome should be considered 'Biome Aggregation'
- Concept URI token: fluidincontainer


[]{#nonbiologicsolidobject}

###  Non biologic solid object


- Child of:
 [`physicalspecimen`](#physicalspecimen)

- Individual solid object, not formed directly by or part of a living
organism
- Concept URI token: nonbiologicsolidobject


[]{#artifact}

####  Artifact


- Child of:
 [`nonbiologicsolidobject`](#nonbiologicsolidobject)

- An object made (manufactured, shaped, modified) by a human being, or
precursor hominid. Include a set of pieces belonging originally to a
single object and treated as a single specimen.
- Concept URI token: artifact


[]{#fossil}

####  Fossil


- Child of:
 [`nonbiologicsolidobject`](#nonbiologicsolidobject)

- Specimen is the remains of one or more organisms preserved in rock;
includes whole body, body parts (usually bone or shell), and trace
fossils. An organism or organism part becomes a fossil when it has
undergone some fossilization process that generally entails physical
and chemical changes akin to diagenesis in a sedimentary rock.
Includes trace fossils, which are manifestations of biologic activity
preserved in a rock body (typically sedimentary), without included
preserved body parts.
- Concept URI token: fossil


[]{#othersolidobject}

####  Other solid object


- Child of:
 [`nonbiologicsolidobject`](#nonbiologicsolidobject)

- Single piece of material not one of the other types.
- Concept URI token: othersolidobject


[]{#researchproduct}

###  Research product


- Child of:
 [`physicalspecimen`](#physicalspecimen)

- Specimen is a product of some research workflow, e.g. a thin
section, an XRF pellet, a grain mount, SEM stub, synthetic rock or
mineral ...  In general there should be a link to a parent specimen
from which this was derived.  Might be aggregation (e.g. a synthetic
material powder) or a solid object.
- Concept URI token: researchproduct


[]{#analyticalpreparation}

####  Analytical preparation


- Child of:
 [`researchproduct`](#researchproduct)

- Specimen is a product of processing required for some observation
procedure, e.g. thin section, XRF bead, SEM stub, rock powder. If
identified separately, this should have a ‘parent’ link to the
original sample
- Concept URI token: analyticalpreparation


[]{#experimentalproduct}

####  Experiment product


- Child of:
 [`researchproduct`](#researchproduct)

- Specimen is product of an experimental procedure (e.g. synthetic
material)
- Concept URI token: experimentalproduct



