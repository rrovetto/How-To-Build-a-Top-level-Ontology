# Problems and Limitations of Top-level Ontologies

This folder describes some limitations and problems with using top-level ontologies. To see the Pros & Cons of ontologies and other knowledge-organization or semantic systems (such as Property Graphs, Semantic technology in general, taxonomies, Knowledge Graphs, etc.), [Donate $50 here for a copy](https://tinyurl.com/yyoo6z96 ) or [use this Paypal link](https://tinyurl.com/donateViaPayPalrr) of my [Catalog of Pros & Cons of Knowledge organization systems](https://docs.google.com/spreadsheets/d/1tJigcoOFIfppHZdf8WB0upgrtA6bSP7bxZcCCErKUsU/edit?skip_itp2_check=true#gid=0) website 

These sorts of ontologies are typically intended to be the most general, and as such are often intended to subsume others. This introduces both technical and ethical concerns and potential consequences. As a most-generic conceptual model, they can represent the risk of being a one-to-rule-them-all product, i.e., monopolization. Their high degree of abstractness also make them subject to philosophical speculation and theory.

"designing ontology is not a simple matter of putting the metaphysical categories on top and letting specific disciplines and domains add descendants." 
(source: p136, Ontological Semantics Sergei Nirenburg and Victor Raskin The MIT Press 2004, Cambridge, Massachusetts, London, England ISBN 0-262-14086-1)

The high degree of abstractness and generality of these types of ontology--and the categories they encode--are inherently subject various conceptualizations. There can be various possible interpretations. Such high-level categories are by their character, underspecified; that is the purpose of generic categories. Trying to specify a very specific meaning to an inherently vague and generic concept excludes other intepretations/senses, and is in contrast to the inherently broadness that we can consider the purpose of the category.

"It is best to allow for a diversity of knowledge representations instead of committing to a single one. This is true even in the field of ontology engineering. What we need are different ontologies you can play with, rather than choosing the one ontology which enforces you to subordinate your thoughts and the world.”
(p.38, "Actually, What Does “Ontology” Mean?", Johannes Bussel)

The mixing of philosophical and technical motivations may be a source of confusion and other problems, and may be potentially dangerous. When engaging in the most abstract concepts, it will be important to clearly distiinguish between any philosophical (e.g. metaphysical) views, assumptions, and claims from the technical (computational, data-centric, practical or goal-focused) choices, goals and motivations. If you are building a computational ontology that is also philosophically laden, then you should be transparent by explicitly stating the assumed ontological commitments in a metaphyiscal sense, and any adoped ideology (methodological or otherwise, e.g., ((non)reductionist, etc.). If you are trying to make metaphysical claims about the world, then you should be doing philosphy, not computational ontology; such abstract accounts or assumptions of the world should not be assumed on the data or domain that the ontology is potentially appplied to, not least because such abstract accounts are unverified, arguably unverifiable, and numerous in their variations. 

## Some problems
- Not all concepts or categories can necessarily be grouped or subsumed under a more generic concept or category.
- Some concepts may be irreducible (actually so, or desired for the model), such that they cannot be classified/subsumed under, or defined/characterized in terms of a broader concept or set of concepts.
  - Consider how some theories of a given concept, category or phenomena, consider the concept to be irreducible to others. In an ontology, then, it is not necessarily subsumable.  
- The intended meaning of some concepts may be lost by subsuming the concept under a broader.

- High learning-curve: they are difficult to understand for non-specialists (non-philosophers, non-computer-scientists, etc.)

## Technical 
- For the more complex and logically formalized ontologies... 
  - They increase the 'path' between data elements, i.e., to access or otherwise perform some action on data
- As with all ontology, quantitative evidence for their utility is lacking or not readily available. If there is such evidence, it may be behind NDAs in enterprises. 
- (For all ontologies) "ontologies may have undesirable entailments." "Problem arises in several areas...
Databases: New entry inconsistent with database.
Robotics: Sensor information inconsistent with plans.
Diagnosis: Device behavior inconsistent with device description.
Ontologies: New axioms added/retracted." (In 'Belief Revision and Ontology Repair' by Renata Wassermann, September 2021 Reasoning Web Summer School)
 
Consider also 
"Science and society are in constant flux. Meaning is an emerging and
evolving property of (human) cognition both on the individual and
societal level. Put differently, meaning is in our heads, not in the
world. Meaning cannot be fixed in ontologies. Instead, ontologies aim at
restricting the interpretation of domain terminology towards their
intended meaning. Such restriction aims to maximize semantic
interoperability, i.e., to minimize cases where parties exchange
information that seems valid on a syntactic level but where the expected
semantics of the target does not match the semantics of the source.

Once we leave the ground of concrete domains and their tasks, we lose
the context that helps restrict a domain's terminology and a sense for
the required quality of this restriction, e.g., the choice of axioms. As
a result, top-level ontology becomes metaphysics - useful, but not
easily ground-able. One top-level ontology may declare that there are
two disjoint kinds: objects and events. A second such ontology may
declare that 'objects are just very slowly evolving events'. You can
select the one you prefer, but none of them is wrong. It is also often
unclear when and why one would have to restrict the interpretation of
terminology for a certain, concrete task, e.g., data retrieval, by going
all the way up the abstraction hierarchy.

Personally, I often search for measurement types and face the semantic
interoperability challenge that two different measurement procedures go
by the same name. I rarely search for things that are 'substances',
'occurrences', or 'forms'. All that said, I fully understand the
intellectual joy of designing and studying these top-level ontologies,
but I see their use in providing us with answers to the big questions of
what can be said and which distinctions make sense and less on the level
of actionable theories."
([Krzysztof Janowicz](https://lists.w3.org/Archives/Public/semantic-web/2021Jan/0034.html))

## Copyright
© 2023, Robert John Rovetto. All right reserved.
Not authorized for commercial use unless explicitly negotiated with the author. Citation/attribution required.
No warranty. Presented "AS IS". Author and copyright holder is not liable. All content, work and products are subject to revision. No claims to completeness or complete accuracy.
