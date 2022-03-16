---
title: About
layout: default

navigation_weight: 1
---

This website host the material of the SPARQL Endpoints and Web API (SWapi) Tutorial,
which will be held in Bari (Italy) during the 2022 edition of the [International Conference on Web Engineering (ICWE)](https://icwe2022.webengineering.org/). (More info coming soon)

<!-- The videos of this tutorial are available on [YouTube](https://www.youtube.com/playlist?list=PLSsFTlM4Tf905v1-mSsm1elWXOjDcANYP). -->

# Abstract
The success of Semantic Web technology has boosted the publication of Knowledge Graphs, and several technologies to access them have become available covering different spots in the spectrum of expressivity: from the highly expressive SPARQL to the controlled access of Linked Data APIs, with GraphQL in between. Many of these technologies have reached industry-grade maturity. Finding the trade-offs between them is often difficult in the daily work of developers, interested in quick API deployment and easy data ingestion. In this tutorial, we will cover this in-between technology space, with the main goal of providing strategies and tools for publishing Web APIs that ensure the easy consumption of data coming from SPARQL endpoints. Together with an overview of state-of-art technologies, the tutorial focuses on two novel technologies: [SPARQL Transformer](https://github.com/D2KLab/sparql-transformer), which allows to get a more compact JSON structure for SPARQL results, decreasing the effort required by developers in interfacing JavaScript and Python applications; and [grlc](http://grlc.io/), an automatic way of building APIs on top of SPARQL endpoints by sharing queries on collaborative platforms. Moreover, we will present recent developments to combine the two, offering a complete resource for developers and researchers. Hands-on sessions will be proposed to internalize those concepts with practice.

# Motivation

A crucial factor in the adoption of the Web of Data consists in the possibility of obtaining access to the published resources. However, this access is not always simple, constrained by languages and templates that are sub-optimal for application development. As a consequence, recent initiatives such as [EasierRDF](https://github.com/w3c/EasierRDF) are strongly pushing the proposal of new solutions for making Semantic data on the Web developer friendly.

The goal of this tutorial is to give participants sufficient knowledge for:
understanding the landscape of mature, production-ready and industry-grade technological solutions for publishing Web APIs on top of RDF datasets;
republishing RDF data through Web API, for increasing the use and adoption of RDF datasets, even outside the Semantic Web community;
retrieving data from SPARQL endpoints in a more practical format to be used in small proofs-of-content, living software or interactive notebooks (i.e. Jupyter), minimising the effort for accessing data.

# Intended Audience

This tutorial is directed to anyone who works with RDF data and SPARQL, and in particular is interested in providing quick access to the data and/or Web APIs on top of them. We assume that most participants will be familiar with basic Semantic Web technologies (RDF, SPARQL). For the hands-on session, the participants are expected to bring a laptop with a web browser installed.

The tutorial aims to provide them a general know-how and practical information for developing Web APIs on top of SPARQL endpoints.


# Previous Edition

This tutorial has been sucessfully held at:
- [ISWC 2020](https://iswc2020.semanticweb.org/program/tutorials/)
- [TheWebConf 2021](https://www2021.thewebconf.org/program/tutorials/)
- [ESWC 2021](https://2021.eswc-conferences.org/workshops-tutorials/)


# References

1. Pasquale Lisena, Albert Meroño-Peñuela, Tobias Kuhn and Raphaël Troncy. **[Easy Web API Development with SPARQL Transformer](http://www.eurecom.fr/en/publication/5927/download/data-publi-5927.pdf).** In *18th International Semantic Web Conference (ISWC)*, Auckland, New Zealand, October 26-30, 2019. - [bib](./bib/lisena2019easyweb.bib)
1. Albert Meroño-Peñuela, Rinke Hoekstra. **[`grlc` Makes GitHub Taste Like Linked Data APIs](http://ceur-ws.org/Vol-1629/paper7.pdf).** In *The Semantic Web – ESWC 2016 Satellite Events*, Heraklion, Crete, Greece, May 29 – June 2, 2016. - [bib](./bib/merono2016grlc.bib)
