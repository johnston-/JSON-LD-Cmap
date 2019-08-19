# JSON-LD-Cmap
developing represenation of concept map using existing linked data schemas and standards.

## Term List

1. :Subject => [skos:Concept](https://www.w3.org/TR/skos-reference/#concepts)
2. :Predicate => [skos:SemanticRelation](https://www.w3.org/TR/skos-reference/#semantic-relations)
3. :Object => [skos:Concept](https://www.w3.org/TR/skos-reference/#concepts)
4. :Proposition => [skos:OrderedCollection](https://www.w3.org/TR/skos-reference/#collections) <:Subject; :Predicate; :Object>

## Link Cmap entities to RDF Resources

Using the [skos:mappingRelation](https://www.w3.org/TR/skos-reference/#mapping), links can be made from the Concepts and Relationships in the Cmap to similar or exact matches in other LD documents. This can be applied when building maps to suggest new propositions or automatically assemble a cmap; it can be used to partition a large cmap into many json documents.
