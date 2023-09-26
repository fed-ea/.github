# Motivations

To some extent, every single architecture initiative that is based on an Enterprise Architecture model starts from scratch, and typically locked to an software tool or service. Through the selected tool, an architecture metamodel is defined (or adopted from standards like Archimate®), architecture domains are identified, template diagrams are developed, and architecture data to be used is identified, activities that become as time consuming as the architecture initiative itself, before the actual work starts.

It feels like a significant amount of effort even before the first architecture artifact is captured. The metaphor I to use is that "the construction of road that takes us to the to-be built facility is bigger than the facility itself". 

As a result, business organizations developed a "traumatic disorder" in respect to architecture initiatives, perceiving the benefits being small than the effort and costs. Often enterprise architecture teams are assembled and disassembled due to their perceived cost/benefit, and organizations unknowingly (or accepting it) loose tacit and coded knowledge of their business, information and technnology architectures.

# Purpose

The purpose of this experiment is to evaluate the acceleration of Enterprise Architecture modeling value delivery through federation with already existing architecture-knowledege, which is managed in a de-centralized form by different teams and organizations. It would allow the reuse of architecture as "building blocks" to enriched and expanded to address the need of a given organization. Same examples:

* Business Capability Models: ACORD, APQC, ISACA COBIT, The Open Group IT4IT
* Technology Services: Amazon AWS, Microsoft Azure, Google Cloud
* Implementation: PMI PMBok
* Applications: ServiceNow CMDB

Check list of [frameworks](frameworks.md) and [data sources](data-sources.md) considered to be represented by Fed-EA and federated into enteprise architecure modeling.

# How

## This experiment has as small set of architectural guiding principles:

* Develop a set of best practices, specifications and proof-of-concept implementations
* It will not re-invent the wheel - leverage existing standards and approaches
* Leverage Archimate® modeling language - it is the most prevalent across EA practitioner community
* Decoupled from existing commercial product - based on Open Source technologies to allow unrestricted usage

## Proof-of-Concept Implementations

* Federation file format (FFF), supporting federated architecture information (TypeScript Types, JSON Schema)
* Library for basic architecture modeling functions (TypeScript Base Class)
* Library for import of ArchiMate® Exchange File Format into FFF (TypeScript)
* Reference implementation for visualization of federated ArchiMate® Views (TypeScript React Function)
* Reference implementation for in-memory architecture model storage (TypeScript Factory/Class)

<!--
using the following technologies 

* Typescript and JSON Schema, for typings

* OpenAPI, for remote access
-->

# Contribution guidelines

Still being developed, it will address how can the community get involved.

* [Guide to Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Useful resources

Still being developed, it will cover topics such as where can the community find your docs or anything else the community should know.

# Licenses, Copyrights, Registered Trademarks

* [ArchiMate® is a registered trademark of The Open Group.](https://www.opengroup.org/archimate-forum/archimate-overview)



