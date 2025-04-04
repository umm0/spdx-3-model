SPDX-License-Identifier: Community-Spec-1.0

# ExportControlAssessmentRelationship

## Summary

Assessment for export control puposes

## Description

Assessment for export control puposes

## Metadata

- name: ExportControlAssessmentRelationship
- SubclassOf: /Security/VulnAssessmentRelationship
- Instantiability: Concrete

## Properties

- notRequired
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- purpose
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- countryOfOrigin
  - type: Country
  - minCount: 0
  - maxCount: n
- manufacturer
  - type: /Core/Organization
  - minCount: 0
  - maxCount: n
- classification
  - type: ExportControlClassification
  - minCount: 1
  - maxCount: n
- specialTechnology
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- exportControlQandA
  - type: QandA
  - minCount: 0
  - maxCount: n