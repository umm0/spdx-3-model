SPDX-License-Identifier: Community-Spec-1.0

# OperationsAssessmentRelationship

## Summary

Abstract ancestor class for all operations assessments

## Description

OperationsAssessmentRelationship is the ancestor class common to all operations
assessment relationships. It factors out the common properties shared by them.

## Metadata

- name: OperationsAssessmentRelationship
- SubclassOf: /Security/VulnAssessmentRelationship
- Instantiability: Abstract

## Properties

- operationsComment
  - type: ComplexComment
  - minCount: 0
