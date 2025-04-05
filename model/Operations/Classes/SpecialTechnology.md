SPDX-License-Identifier: Community-Spec-1.0

# SpecialTechnology

## Summary

Special technology information

## Description

Informatin on any included special technology (e.g. export control relevant crypto)

## Metadata

- name: SpecialTechnology
- Instantiability: Concrete

## Properties

- includesCrypto
  - type: xsd:boolean
  - minCount: 1
  - maxCount: 1
- cryptoDetail
  - type: xsd:string
  - minCount: 1
- externalServerCommunication
  - type: xsd:boolean
  - minCount: 0
- includesArtificialIntelligence
  - type: xsd:boolean
  - minCount: 0
- operationsComment
  - type: ComplexComment
  - minCount: 0