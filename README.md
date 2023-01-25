
# ProductKG - A product knowledge graph

ProductKG is a knowledge graph created from Web information, interlinking different ontologies designed for retail and household applications. It is based on a merged product taxonomy reflecting the product classification in grocery stores and drugstores that is linked to a product location ontology created from a robot belief state while performing stocktaking in a retail store as depicted in the following picture:<br> 
<img src="UseCaseImg/semDTCompose2.jpg" width="600" alt="semantic Digital Twin"/><br>
<small>Kümpel, M., Mueller, C.A., Beetz, M. (2021). <a href="https://link.springer.com/chapter/10.1007/978-3-030-88662-2_7"><i>Semantic Digital Twins for Retail Logistics</i></a>. In: Freitag, M., Kotzab, H., Megow, N. (eds) <b>Dynamics in Logistics</b>. Springer, Cham.</small><br>


The <b>product location ontology</b> therefore stores inventory data like stock and price of products as well as their positions relative to shelves (instead of coordinates). We use the <a href="http://knowrob.org/">KnowRob knowledge processing system</a> for creation of the location ontology. In KnowRob, a robot can access specific position information of the perceived objects. The <b>product taxonomy</b> classifies products that were recognized during stocktaking. It is linked to an <b>ingredients classification</b> based on string matching, which is connected to an <b>allergen classification</b>. Ingredients also link to <b>substitutes, diseases, symptoms</b> and treatments in form of <b>nutritients</b>. The product taxonomy is linked to further product information like name and place of production in <b>product information</b>,<b> product label, brand</b> or <b>product dimensions</b>, i.e. dimensions of product packaging as well as product weight/ filling information. Since food products play an important role in daily activities, ProductKG also includes <b>nutrition</b> information and provides a user profile and quantity ontology for personalisation.
All this can be used for daily acitivity applications on robots, mobile phones or smart glasses, for example.

# Querying the knowledge graph

The knowledge graph is publicly available here and on <a href="https://krr.triply.cc/mkumpel/ProductKG/sparql/ProductKG">triply</a>, many thanks to the <a href="https://krr.cs.vu.nl/">knowledge representation and reasoning group</a> at the Vrije Universiteit Amsterdam.

<h3><a href="http://grlc.io/api/michaelakuempel/ProductKG/SPARQLfiles/">Predefined queries</a></h3> 
<img src="UseCaseImg/grlc_logo_01.png" width="50" alt="grlc image"/>

We created some predefined queries for everyone to test all versions of ProductKG via the <a href="http://grlc.io/api/michaelakuempel/ProductKG/SPARQLfiles/">ProductKG grlc api</a>. grlc is a git repository linked data API constructor that automatically builds Web APIs using shared SPARQL queries <a href="https://github.com/CLARIAH/grlc">(grlc on github)</a>
<h3>Version 1.0</h3> <a href="https://krr.triply.cc/mkumpel/ProductKG/sparql/ProductKG">ProductKG via triply SPARQL api</a>



# Disclaimer

This ProductKG is made available under the <a href="http://opendatacommons.org/licenses/by/1.0/">Open Data Commons Attribution License</a>.


This knowledge graph has been created by the <a href="https://ai.uni-bremen.de/">Institute for Artificial Intelligence</a> at the University of Bremen. Please contact <a href="https://ai.uni-bremen.de/team/michaela_k%C3%BCmpel">Michaela Kümpel</a> for further info or collaboration: michaela(dot)kuempel(at)uni-bremen(dot)de

<img src="UseCaseImg/ai_logo.png" width="200"/><img align=right src="UseCaseImg/university_new.png" width="200"/>
