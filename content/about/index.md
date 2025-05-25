---
title: "SafeIaC: Reliable Analysis and Automated Repair for Infrastructure as Code"
---

![SafeIaC Logo](SafeIaC-Logo300dpi.png)

In our modern world, the reliability and security of software systems are foundational to the functioning of critical infrastructure, financial systems, healthcare, and virtually every aspect of daily life. Central to the operation of these systems is the configuration and infrastructure code that defines and manages the environment in which applications run. This process of using programmable configuration files to provision and manage IT infrastructure is known as _Infrastructure as Code (IaC)_. 

Despite the many benefits provided by IaC, such as enabling more reliable and predictable deployments and supporting scalability with minimal effort, errors in these critical pieces of code are a significant source of system failures and degradation. Such mistakes lead to security vulnerabilities, application outages, and incorrect program executions, undermining the stability and reliability of essential services. 

Despite the critical role of configuration and infrastructure code in software system reliability and security, research focusing on the reliable configuration and infrastructure as code remains scarce. In this project, we aim to address this gap by developing methodologies for the reliable analysis and automated repair of software configuration and infrastructure code. This goal faces several challenges, including the diversity of IaC technologies, the complexity of IaC ecosystems, and the need for techniques that can accurately model and reason about these systems' behavior. Developing solutions that are both efficient and effective requires innovative approaches to modeling and analyzing the unique structures and semantics of infrastructure as code. 

Building upon recent developments by our research team (Saavedra and Ferreira, 2022; Saavedra et al. 2023), we propose the first technology-agnostic solution for reliable analysis and automated repair for Infrastructure as Code that provides _formal correctness guarantees_. Our envisaged solution will encompass both the versatility of technology-agnostic support across various languages and environments and the reliability of formal correctness guarantees, addressing the needs of the industry by providing a singular solution to the previously unmet challenge of polyglot automated repair and reliable IaC management. We plan to cover a wide range of errors, including code smells, configuration inconsistencies, dependency errors, and so-called configuration drifts (which happen when the state of a system deviates from what is specified in the system’s configuration file). 

## Contacts
**Principal Investigator (INESC-ID):** [João F. Ferreira](https://joaoff.com)

**Principal Investigator (INESC TEC):** [Alexandra Mendes](https://archimendes.com)

[**Meet the Team**](/people)

**Research and Academic Institutions:** 
 - [INESC-ID: Instituto de Engenharia de Sistemas e Computadores, Investigação e Desenvolvimento em Lisboa (INESC-ID)](https://inesc-id.pt)
 - [Instituto Superior Técnico, Universidade de Lisboa](https://tecnico.ulisboa.pt) 
 - [INESC TEC: Instituto de Engenharia de Sistemas e Computadores, Tecnologia e Ciência](https://www.inesctec.pt/en)
 - [Faculty of Engineering, University of Porto](https://www.up.pt/feup/en)

**Industry Partners:**
 - [Checkmarx](https://checkmarx.com)
 - [Amazon Web Services (Automated Reasoning group)](https://www.amazon.science/research-areas/automated-reasoning)

## Funding
SafeIaC is funded by Fundação para a Ciência e a Tecnologia (FCT) under the program _[MPr-12-2023 - ICDT/2023](https://www.fct.pt/en/concursos/concurso-de-projetos-de-ic-dt-em-todos-os-dominios-cientificos-2023)_. 
**Funded amount: 249.609,60 €**
