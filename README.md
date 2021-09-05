# JSON-LD-Cmap
developing represenation of concept map using existing linked data schemas and standards.

Design Goals
- use skos objects to model concept map {skos:Concept, skos:semanticRelation, skos:ConceptScheme}
- namespace each entity in the concept map in the space of its author.
- easily update the model {add/update/remove concept, add/update/remove relation}
- allow skos:closeMatch and skos:exactMatch to align with existing rdf resources


Design Questions
- is a concept map a skos:Collection of Triples, where a Triple is a skos:ConceptScheme?
- is a concept map a skos:ConceptScheme and Triples are implied by the domain and range of skos:semanticRelation?
