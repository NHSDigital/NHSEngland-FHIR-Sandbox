# NHS-England-FHIR-Examples
This repository is maintained by [Interoperability Team](https://nhsd-confluence.digital.nhs.uk/pages/viewpage.action?spaceKey=IOPS&title=Interoperability+Standards). Any queries contact us via [email](interoperabilityteam@nhs.net).

This repository will be used as an internal development environment (sandpit) for trialing ideas for FHIR Resources, IG layouts, validation issues, and first of types for the Interoperability Standards Team.   
**This reposibitory does <ins>not</ins> contain any resources that can be implemented in any way.**  
The associated Simplifier Project can be found at https://simplifier.net/r4-sand-box.


## CapabilityStatement
The CapabilityStatement is used by the validation tool to check which profile to validate against. If no Profile is stated then the base FHIR resource will be used.

## FHIR Validation

This repo uses the customised HAPI FHIR Validation to ensure all assets and examples are valida FHIR, including any codes held within the ontoology server.  

More information on FHIR validation can be found on the Interoperability Standards team [Confluence page](https://nhsd-confluence.digital.nhs.uk/display/IOPS/FHIR+Conformance+and+Testing)  
More information on the FHIR validation service can be found within the Interoperability Standards team [IOPS-Test-Scripts](https://github.com/NHSDigital/IOPS-FHIR-Test-Scripts) repository.  

To set up the validation service within a fork add the following secrets:
- ONTO_CLIENT_ID
- ONTO_CLIENT_SECRET

