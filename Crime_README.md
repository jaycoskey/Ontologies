## Towards a Crime Ontology
**Note:** This is for personal interest only. It is not meant to be practical.

Project Phases (can be overlapping)
### **Phase 1:** Planning
  * List types of crimes/use cases to be inferred from activities modeled
    * Accounting fraud, money laundering, murder, terrorism
    * It might make sense to treat each of these categories separately, and have a separate crime ontology reference all of them.
  * Requirements
    * Means of checking both business and personal relationships between people
    * Identification of outliers/suspects
    * Minimize duplication of ontology with already-established base ontologies 
  * Prior work (not including base ontologies) 
    * Engineering an Ontology of Financial Securities Fraud: [https://www.researchgate.net/profile/John_Kingston2/publication/220831102_Engineering_an_Ontology_of_Financial_Securities_Fraud/links/0fcfd51063affeb744000000/Engineering-an-Ontology-of-Financial-Securities-Fraud.pdf link]
    * Finance Ontology and Semantic Technologies: [http://www.fadyart.com/financeV4.owl link]
    * Good use case scenario in section 1.2 of the 2005 paper "Building a Terrorism Ontology"
    * METHONTOLOGY: From Ontological Art Towards Ontological Engineering [http://oa.upm.es/5484/1/METHONTOLOGY_.pdf link]
    * Ontological Constructs to Create Money Laundering Schemes [https://pdfs.semanticscholar.org/4954/5197a2900299fb6cd30a5dcf05134e76c730.pdf link]
    * "The Semantic Web," Tim Berners-Lee, et. al., Scientific American, 2001
    * Towards a Financial Fraud Ontology: A Legal Modelling Approach: [http://www.leibnizcenter.org/~winkels/LegOnt2003/Leary.pdf link]
    * Towards Ontology-based E-mail Fraud Detection:
        [https://pdfs.semanticscholar.org/20da/4d5230f87b1c188e0b54f6c9a7edead032af.pdf link1]
        [https://doctiktak.com/towards-ontology-based-e-mail-fraud-detection.html link2]
  * Ontological engineering resources
    * Protégé (ontology modeling tool)
    * Data on 9/11 or other real-world terrorism events
    * The Ontology Definition Metamodel Specification, by the Object Management Group
  * Out of scope
    * Query performance
### **Phase 2:** Rough outline
  * Create categorized tables of Things, Predicates, and properties, with associated source ontologies
  * Example categories: Bio, Business, Evidence, Finance, Geo, Law, Terrorism, Travel
  * Establish relationships between Things and Predicates (sequence diagrams, etc.) (Use rdfs?)
### **Phase 3:** Create ontology doc (OWL format?)
### **Phase 4:** Populate ontology
  * Populate ontology with real-world or mock data. Real world can come from terrorist events (e.g., 9/11)
### **Phase 5:** Ontology queries
  * Create queries (in SPARQL?), both for constraint-checking and information-gathering
  * Queries to find outliers (e.g., 3σ or Benford's Law), violations of applicable laws, or near-violations
  * The writing of these queries would (of course) be initiated during earlier phases
  * Modify output from earlier phases as needed


## Appendix: Glossary

Term        | Definition
----------- | ----------
AKEM        | Application Knowledge Engineering Methodology (uses RUP=Rational Unified Process)
BN          | Bayesian Networks
CLG         | Conditional Linear Gaussian BNs
DOGMA       | Developing Ontology-Guided Mediation for Agents
FF-POIROT   | Financial Fraud Prevention-Oriented Information Resources using Ontology Technology
GTD         | Global Terrorism Database
ID          | Intrusion Detection
LBP         | Loopy  Belief Propagation
MEBN/PR-OWL | Multi-Entity Bayesian Networks
MFrag       | MEBN Fragment (influences among clusters of related random variables)
MSBN        | Multiply-Sanctioned Bayesian Networks
OOBN        | Object-Oriented Bayesian Networks
OWL 2 / Full| If you are unconcerned about performance of automated reasoning
OWL 2 / EL  | Optimized for inference of relationships (polynomial time)
OWL 2 / QL  | Optimized for quantity of instance data, & for running atop a relational DB
OWL 2 / RL  | Optimized for running on a traditional business rules engine
OWL-DL      | A decidable subset of OWL based on Description Logics
P-SHOQ(D)   | A probabilistic extension of SHOQ(D)
SHOQ(D)     | A descriptive logic comparable with OWL
SSBN        | Situation-specific Bayesian network

