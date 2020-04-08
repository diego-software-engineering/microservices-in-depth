# Micro services challenges

based on [this](https://www.youtube.com/watch?v=aQLv4F1PpTY&t=1382s) talk from nubank team

Main questions:

* how to ensure well designed domains, subdomains and entities?
* how to handle state accross components in a distributed system?
* which are the main issues between components communication?
* which events may compose a transaction?
* how to handle inconsistent state?


(1) solution architecture ( domain )

(2) application architecture ( sub-domain )

(3) entities ( schemas )

State flow

* microservices in containers ( stateless )
* database persistence ( stateful )
* message queue ( stateful )
* handling over inconsistencies

concepts:

* eventual consistency
* deadletter queue
* event sourcing 
