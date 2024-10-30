<a name="readme-top"></a>

<div align="center">

<h1 align="center">Astragale Project</h1>
*Astragale* is a scientific project for bridging Built Cultural Heritage conservation data with Civil Engineering mechanical simulation results. 

</div>

#### TOC
- [🔦 Project Summary](#-project-summary)
- [✨ Features Overview](#-repositories-overview)
- [📦 Repositories Overview](#-repositories-overview)
- [📑 References](#-references)
- [Credits](#credits)


<!-- - [👋🏻 Getting Started & Join Our Community](#-getting-started--join-our-community)
- [📦 Extension Installation](#-extension-installation)
- [✨ Feature Overview](#-feature-overview)
- [🖥 Environment Support](#-environment-support)
- [📦 Ecosystem](#-ecosystem)
- [⌨️ Local Development](#️-local-development)
- [🤝 Contributing](#-contributing)
- [🩷 Sponsor](#-sponsor)
- [🔗 Links](#-links)
  - [More Products](#more-products)
  - [Credits](#credits) -->


## 🔦 Project Summary
Ensuring the resilience of our built environment requires a comprehensive understanding of structural behavior, particularly when it comes to cultural heritage buildings. These structures are defined not only by their historical and architectural value but also by unique material compositions, specialized construction methods, and conservation challenges. *Astragale* addresses these needs by enhancing data-sharing and computational support, enabling a collaborative environment that bridges disciplines.

In line with the endeavours of the [n-Dame_Heritage](http://www.ndameheritage.map.cnrs.fr/) and the Notre-Dame de Paris Ecosystems, *Astragale* aims at facilitating knowledge exchange among civil engineers, architects, and conservation scientists. 

Central to the project is a modular, Knowledge Graph-based framework utilizing Semantic Web technologies. This approach enables structured, interoperable solutions that preserve and share knowledge on heritage buildings’ structural integrity and long-term preservation, fostering a robust foundation for interdisciplinary collaboration and innovative conservation practices.

**Project Focus**: *Astragale* focuses on bridging architectural & built conservation survey data with structural models. Extracted data from simulations will correlate visible alterations of the built material with internal weaknesses, predicted cracks and deformations, or load concentration

## ✨ Features Overview
*--- WIP ---*

## 📦 Repositories Overview
> \[!WARNING]
>
> Please be aware that Astragale is currently under active development.

+ [Kibos](https://github.com/prj-astragale/kibos): This repository contains the configurations and Docker Compose deployment scripts necessary to launch and test the knowledge system *Kibos*. *Kibos* is designed as an event-centric system, integrating a Knowledge Graph for managing building-related knowledge.
+ [Semantics](https://github.com/prj-astragale/semantics): The repository dedicated to Semantic Web resources, including ontologies, ontology design patterns (ODPs) and thesauri, which form the backbone of the Knowledge Graph.
+ [StreamGraphiti](https://github.com/prj-astragale/streamgraphiti): An RDF stream processing service tailored for continuous data ingestion. *Streamgraphiti* updates the Knowledge Graph in real-time, applying predefined templates and resource patterns to incoming data streams, thus supporting dynamic updates and maintaining the relevance and accuracy of the integrated data.
+ *Biglake* (coming soon): Serving as the primary API Gateway. *Biglake* provides unified access to services and acts as the interface for external applications to interact with the system's resources and functions.
+ *Astradash* (comming soon): A concise dashboard for summarizing building survey, models and simulation data.

## 📑 References
*--- WIP ---*


## Credits
Astragale Project is founded by the *Mission Interdisciplinaire pour les Initiatives Transverses* (MITI) from the *Centre National de la Recherche Scientifique* (CNRS). It stems from a collaborative efforts between the laboratories *Modèles et Simulations pour l'Architecture et le Patrimoine* (MAP, [UPR CNRS 2002](https://www.map.cnrs.fr/) and [URM MC](https://www.map.archi.fr/), former UMR CNRS 3495), *Laboratoire de Mécanique et de Génie Civil de Montpellier* ([LMGC, Univ. Montpellier, UMR CNRS 5508](https://lmgc.umontpellier.fr/)) and the *Laboratoire d'Ingénierie des Systèmes Physiques et Numériques* ([LISPEN, Arts&Métiers EA 7515](https://lispen.artsetmetiers.fr/)). This project is located at the frontier between the "Digital Ecosystem Workgroup" and the "Structural Evaluation Workgroup" of the scientific consortium for the Restauration of Notre-Dame de Paris Cathedral, and align with the endeavors for the existing [Notre-Dame de Paris Digital Ecosystem](https://www.notre-dame.science/) and ERC [n-Dame_Heritage](http://www.ndameheritage.map.cnrs.fr/). 


All the works referred is under [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) unless otherwise stated