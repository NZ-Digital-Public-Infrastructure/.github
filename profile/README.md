![Government Digital Delivery Agency logo](GDDA-banner.png)
# New Zealand Government Digital Public Infrastructure
The Digital Public Infrastructure (DPI) is a suite of trusted, reusable digital platforms that supports government agencies to deliver high-quality public services more efficiently. By adopting these ready-made capabilities, agencies can reduce costs, streamline delivery, and focus their efforts on creating value for New Zealanders, rather than independently procuring and building components from scratch.

## Background
The DPI is a key component of the [Digital Government Target State](https://www.digital.govt.nz/digital-government/digitising-government-programme-dgp/digital-target-state).
<p align="center" width="100%">
  <img  alt="Digital Government Target State diagram" src="https://www.digital.govt.nz/assets/Images/Digital-government/Digitisation-Government-Programme/img-digital-target-state-720.png" /></p>

The DPI is managed and operated by the [Government Digital Delivery Agency (GDDA)](https://www.publicservice.govt.nz/about-te-kawa-mataaho/government-digital-delivery-agency). 

## DPI Products
The current DPI products are focussed on delivery of identity and credential services. Further products will be added over time to support notifications and secure messaging, payments management, and other core infrastructure capabilities.

Access the product technical details and descriptions, along with guidance on how to request access and get started:: 
* [All of Government Digital Credential Issuance Platform (DCIP)](https://github.com/NZ-Digital-Public-Infrastructure/nz-digital-credential-issuance-platform)
* [Govt.nz app digital wallet](https://github.com/NZ-Digital-Public-Infrastructure/govt-nz-app-wallet)
* [NZ Verify app](https://github.com/NZ-Digital-Public-Infrastructure/nz-verify)
* [Digital Trust Service](https://github.com/NZ-Digital-Public-Infrastructure/digital-trust-service)

## Digital Credential Overview
A description of digital identity in New Zealand can be found [here](https://github.com/nz-trust-framework/DISTF-reference-architecture/blob/main/OVERVIEW.md) and is summarised in the diagram below.
<p align="center" width="100%">
<img alt="Digital Identity Infrastructure " src="https://github.com/nz-trust-framework/DISTF-reference-architecture/blob/main/media/ecosystem-diagram.png" /></p>

The digital credentials ecosystem allows users to securely store digital credentials in a digital wallet, and present these online or in-person to share their information securely and selectively: 
* An organisation issues the credential to a user after they have passed the relevant identity checks and proof of eligibility to hold the credential. New Zealand government agencies must use the All of Government Digital Credential Issuance Platform to produce the credential.
* The user accepts the credential into their digital wallet. The Govt.nz app digital wallet can accept credentials from any issuer that has been appropriately accredited under the [Digital Identity Services Trust Framework (DISTF)](https://www.publicservice.govt.nz/about-the-commission/government-digital-delivery-agency/trust-framework-for-digital-identity/about-digital-identity-services/trust-framework-legislation).
* The user presents their wallet to a relying party, either online or in-person, who verifies that they hold a trusted credential that proves they meet a requested requirement, e.g. proof of age or qualification. The NZ Verify app is provided as an in-person verification tool for certain use cases. Other relying parties may access the Digital Trust Service to receive details of credential issuers that have achieved DISTF accreditation.
