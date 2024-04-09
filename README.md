# Awesome Component Metadata Infrastructure (CMDI) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

> A curated list of services, tools and documentation for [CLARIN](https://www.clarin.eu)'s Component Metadata Infrastructure

## Contents <!-- omit in toc -->
- [Web pages](#web-pages)
- [CMDI services](#cmdi-services)
- [Specification Documents](#specification-documents)
- [Guides and tutorials](#guides-and-tutorials)
- [Tools](#tools)
- [Publications](#publications)
- [Contribute](#contribute)

## Web pages
Web pages about CMDI

- [CMDI home page](https://www.clarin.eu/cmdi) - An introduction to CMDI and usage description for metadata modellers, authors and repository managers.
- [FAQs](https://www.clarin.eu/faq-page/267) - Frequently asked questions about metadata in CLARIN.

## CMDI services
### Core services <!-- omit in toc -->
- [Component Registry](https://www.clarin.eu/componentregistry) - Registry and editor for  CMD components and profiles.
- [CLAVAS](https://vocabularies.clarin.eu) - CLARIN's vocabulary service used in CMDI.
- [CCR](https://concepts.clarin.eu) - CLARIN's concept registry used in CMDI.

### Central services <!-- omit in toc -->
- [VLO](https://vlo.clarin.eu) - Metadata based search and discovery for language resources and tools.
- [Curation dashboard](https://curation.clarin.eu) - Metadata quality control.

## Specification Documents
### CMDI 1.1 <!-- omit in toc -->
- XSD Schemas - Common schemas for CMDI 1.1.
  - [General component schema](https://infra.clarin.eu/cmd/general-component-schema.xsd)
  - [Minimal CMD validation](https://infra.clarin.eu/cmd/xsd/minimal-cmdi.xsd)

### CMDI 1.2 <!-- omit in toc -->
- [CMDI specification](https://www.clarin.eu/cmdi1.2-specification) - Complete specification for CMDI 1.2
  - [Summary of changes](https://office.clarin.eu/v/CE-2014-0318-CMDI_1_2-executive_summary.pdf) - Executive summary of changes in CMDI 1.2 compared to CMDI 1.1.
- ISO 24622 - Language resource management.
Component Metadata Infrastructure (CMDI)
  - [ISO 24622-1:2015](https://www.iso.org/standard/37336.html) - Part 1: The Component Metadata Model.
  - [ISO 24622-2:2019](https://www.iso.org/standard/64579.html) - Part 2: Component metadata specification language.
- [XSD Schemas](https://infra.clarin.eu/CMDI/1.2/xsd/) - Common schemas for CMDI 1.2.
  - [Schema for the component specification](https://infra.clarin.eu/CMDI/1.2/xsd/cmd-component.xsd)
  - [Schema for the record envelope](https://infra.clarin.eu/CMDI/1.2/xsd/cmd-envelop.xsd)

## Guides and tutorials
- [CMDI best practices guide](https://www.clarin.eu/content/cmdi-best-practices-guide) - PDF with best practices for both modellers and authors, and a section on common approaches and problems.
- [CMDI and granularity](https://www.clarin.eu/sites/default/files/AP3-007-CMDI_and_granularity.pdf) - PDF with guidelines with respect to metadata hierarchies and levels of description.

## Tools
### General <!-- omit in toc -->
- [CMD Toolkit](https://github.com/clarin-eric/cmdi-toolkit/) - Contains the schemata, stylesheets and scripts that form the basis of CMDI.

### Validation <!-- omit in toc -->
- [Component validator](https://github.com/clarin-eric/cmd-validate) - A library for validating CMD component specifications using XSD and Schematron ("CMDValidate").
- [Instance validator](https://github.com/clarin-eric/cmdi-instance-validator) - Java based utility for validating CMDI records.

### Editing <!-- omit in toc -->
- [COMEDI](https://clarino.uib.no/comedi/) - A web-based editor for CMDI records with storage and distribution facilities.
- [CLARIAH CMDI Forms](https://github.com/knaw-huc/clariah-cmdi-forms) - A tweakable, web based editor for CMDI records (sources, runnable via Docker).

### Conversion <!-- omit in toc -->
- [CLARIN metadata conversion stylesheets](https://github.com/clarin-eric/metadata-conversion/) - A repository with stylesheets for conversion from various metadata formats to CMDI.

### Distribution <!-- omit in toc -->
- [OAI harvest manager](https://github.com/clarin-eric/oai-harvest-manager) - Solution for harvesting a predefined set of endpoints, with support for flexible XSLT based processing pipelines and integration with the CLARIN centre registry.

### Repository systems <!-- omit in toc -->
- [CLARIN DSpace](https://github.com/ufal/clarin-dspace) - Adaptation of DSpace that supports CMDI and other CLARIN requirements and conventions, developed at the Institute of Formal and Applied Linguistics of the Charles University.
- [TLA FLAT](https://github.com/TLA-FLAT) - Repository solution based on Islandora, developed at the Max Planck Institute for Psycholinguistics.

## Publications
- [CLARIN: The infrastructure for language resources](https://www.degruyter.com/document/doi/10.1515/9783110767377/html) - Chapter "Component metadata infrastructure". 
  - _Windhouwer, M., & Goosen, T. (2022). Component metadata infrastructure. CLARIN: The infrastructure for language resources, 191-222._
  - [PDF version](https://www.degruyter.com/document/doi/10.1515/9783110767377/pdf) - free digital copy of the entire book (CC-BY)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
