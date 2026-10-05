# Patient Summary

## HauoraConnect NZ — Clinician Shared Care View

This screen provides an authorised clinician with a concise overview of important patient information sourced from FHIR resources.

> Demo only: All patient information in this project is synthetic.

---

## Patient

**Name:** Mere Thompson  
**NHI:** ZZZ1234  
**Date of Birth:** 14 May 1972  
**Location:** Wellington, New Zealand

---

## Clinical Summary

### Allergy

**Penicillin**

Reaction: Skin rash  
Severity: Mild  
Status: Confirmed

FHIR resource: `AllergyIntolerance`

---

### Active Conditions

**Type 2 diabetes mellitus**

Status: Active  
Recorded onset: June 2018

FHIR resource: `Condition`

---

### Current Medication

**Metformin 500 mg tablet**

Directions: One tablet twice daily with food.

FHIR resource: `MedicationRequest`

---

### Latest Observation

**HbA1c: 67 mmol/mol**

Status: Above target  
Date: 15 September 2026

FHIR resource: `Observation`

---

### Immunisations

**Influenza vaccine**

Status: Completed  
Date: 10 April 2026

FHIR resource: `Immunization`
