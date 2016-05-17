# OntoFuhSen Vocabulary

This repository contains the OntoFuhSen vocabulary. The permanent URI of the ontology is: <https://w3id.org/eis/vocabs/fuhsen#>

The online documentation is here: <http://lidakra.github.io/Ontology/>

The OntoFuhSen vocabulary is one of the key components in the Federated Hybrid Search Engine (FuhSen). 
<https://github.com/LiDaKrA/FuhSen-reactive>

It allows for the description of user search activities, data sources, and entities in the federation. The vocabulary is divided into the following three modules:

1. Search engine metadata: comprises classes modeling a user search activity (e.g.,
fs:Search, fs:SearchableEntity). 
2. Data sources metadata: contains classes describing data sources API services and access points (e.g., fs:API, fs:Parameter, fs:Operation). These classes model the APIs and services from which the data is extracted (e.g., Facebook or Twitter).
3. Domain specific metadata: includes classes for describing the results collected from FuhSen during keyword query processing. For the crime domain concepts include: gr:ProductOrService and org:Organization.

![OntoFuhSen overview image](https://cloud.githubusercontent.com/assets/4923203/15324039/bd4efac4-1c12-11e6-9410-884da5c9236e.png)


