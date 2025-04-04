SPDX-License-Identifier: Community-Spec-1.0

# ExportControlClassification

## Summary

Export control classification entry

## Description

Export control classification entry

## Metadata

- name: ExportControlClassification
- Instantiability: Concrete

## Properties

- classificationSystem
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- classificationValue
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- classificationComment
  - type: /Core/comment
  - minCount: 0
  - maxCount: n
