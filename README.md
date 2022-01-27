# MIMIC-III to SNOMED

> This is a fork of https://github.com/cscihkbu/Snomed-Proprocessed

This repository contains pre-processed SNOMED relations files that connect drugs and diagnoses from MIMIC-III to SNOMED. Formulary CD and ICD code are used for represent drugs and diagnoses respectively. And Snomed ID is used for represent other medical entities like finding sites.


## Files in this repository

- `DRUG_RELATIONS.csv`: Each row is a triplet that connect a drug from MIMIC-III to a entity from SNOMED.
- `DIAGNOSIS_RELATIONS.csv`: Each row is a triplet that connect a diagnosis from MIMIC-III to a entity from SNOMED
- `SNOMED_ENTITY_RELATIONS.csv`: Each row is a triplet that connect entity relationship from SNOMED.
- `SNOMED_ID_TO_NAMES.csv`: Each row maps a SNOMED Entity ID or Relationship ID to name.



