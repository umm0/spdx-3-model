SPDX-License-Identifier: Community-Spec-1.0

# ExportControlAssessmentRelationship

## Summary

Assessment for export control puposes

## Description


## Metadata

- name: ExportControlAssessmentRelationship
- SubclassOf: OperationsAssessmentRelationship
- Instantiability: Concrete

## Properties


- notRequired
  - type: Boolean
  - minCount: 0
  - maxCount: 1
- purpose: 
  - type: String
  - minCount: 0
  - maxCount: 1
- countryOfOrigin:
  - type: Country
  - minCount: 0
  - maxCount: n
- manufacturer: 
  - type: Organization
  - minCount: 0
  - maxCount: n
- Classification: 
  - type: ExportControlClassification
  - minCount: 1
  - maxCount: n
- SpecialTechnology: 
  - type:SpecialTechnology
  - mincount: 0
  - maxcount: 1
- ExportControlQandA:
  - type: QandA
  - mincount: 0
  - maxcount: n