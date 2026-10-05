**Disclaimer
This is an independent portfolio project using synthetic data.
It is not an official product and is not connected to production health systems.**

# HauoraConnect NZ

A New Zealand digital health portfolio project exploring HL7 FHIR, shared care, interoperability, privacy, and equitable healthcare.

## Project Overview

HauoraConnect NZ is a conceptual clinician-facing shared care application designed to demonstrate how health information could be brought together using HL7 FHIR in an Aotearoa New Zealand context.

The project uses synthetic data only and is not connected to any live Health New Zealand systems.

## Why I Built This

The goal of this project is to demonstrate practical understanding of:

- HL7 FHIR and healthcare interoperability
- New Zealand digital health concepts
- NHI and HPI
- Shared care and patient summary workflows
- Clinical safety and privacy
- Health equity and Te Tiriti-informed design
- Product thinking and user-centred design

## Example User Journey

1. Clinician signs in
2. Selects reason for accessing the record
3. Searches for a patient
4. Opens the patient summary
5. Reviews allergies
6. Reviews conditions
7. Reviews medications
8. Reviews observations
9. Reviews immunisations
10. Reviews care gaps and equity considerations

## FHIR Resources Used

This project will model data using common FHIR resources including:

- Patient
- Practitioner
- Organization
- Location
- AllergyIntolerance
- Condition
- Observation
- MedicationRequest
- Immunization
- Encounter
- ServiceRequest
- CarePlan

## New Zealand Context

The project is designed around concepts relevant to digital health in Aotearoa New Zealand, including:

- National Health Index (NHI)
- Health Provider Index (HPI)
- NZ Base FHIR profiles
- SNOMED CT New Zealand Edition
- New Zealand Medicines Terminology
- Aotearoa Immunisation Register concepts
- Shared care and interoperability
- Health information privacy and auditability

## Health Equity

The project also explores how digital health systems can support equity by considering:

- Māori participation in service design
- Tino rangatiratanga and self-determination
- Equity of health outcomes
- Whānau involvement
- Cultural and language needs
- Access barriers
- Care gaps
- Data-informed service improvement

## Project Structure

```text
hauora-connect-nz-fhir
│
├── README.md
│
├── docs
│   ├── architecture.md
│   ├── nz-fhir-overview.md
│   ├── equity-and-te-tiriti.md
│   └── user-journey.md
│
├── fhir-samples
│   ├── patient.json
│   ├── allergy-intolerance.json
│   ├── condition.json
│   ├── observation.json
│   ├── medication-request.json
│   └── immunization.json
│
└── mockups


That closes the code block.

Then leave a blank line and keep your dashboard section like this:

```markdown
## Dashboard Mockup

![HauoraConnect NZ Patient Summary](mockups/Patient%20Summary.png)
