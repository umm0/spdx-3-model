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
  - minCount: 0
  - maxCount: 1
- cryptoDetail
  - type: xsd:string
  - minCount: 0
- externalServerCommunication
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- includesArtificialIntelligence
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- operationsComment
  - type: ComplexComment
  - minCount: 0