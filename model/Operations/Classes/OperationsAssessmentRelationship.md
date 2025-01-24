SPDX-License-Identifier: Community-Spec-1.0

# OperationsAssessmentRelationship

## Summary

Abstract ancestor class for all operations assessments

*duplicate of Security/VulnAssessmentRelationship*

## Description

OperationsAssessmentRelationship is the ancestor class common to all operations
assessment relationships. It factors out the common properties shared by them.

## Metadata

- name: OperationsAssessmentRelationship
- SubclassOf: /Core/Relationship
- Instantiability: Abstract

## Properties

- assessedElement
  - type: /Core/Element
  - minCount: 0
  - maxCount: 1
- publishedTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- /Core/suppliedBy
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- modifiedTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- withdrawnTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
