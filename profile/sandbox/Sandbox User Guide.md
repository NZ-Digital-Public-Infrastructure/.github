# Digital Public Infrastructure Sandbox Testing Ecosystem
This page describes the sandbox versions of the New Zealand government [Digital Public Infrastructure (DPI)](https://github.com/NZ-Digital-Public-Infrastructure/.github/blob/main/profile/README.md) products managed by the Government Digital Delivery Agency (GDDA).

## Overview

To assist government agencies and other organisations with development and testing of digital credentials for New Zealanders, test versions of DPI products are available in a sandbox environment. 

* [All of Government Digital Credential Issuance Platform (DCIP)](https://github.com/NZ-Digital-Public-Infrastructure/nz-digital-credential-issuance-platform)
* [Govt.nz app digital wallet](https://github.com/NZ-Digital-Public-Infrastructure/govt-nz-app-wallet)
* [NZ Verify app](https://github.com/NZ-Digital-Public-Infrastructure/nz-verify)

The sandbox version of the Govt.nz app can accept credential offers and issuance into its wallet from the sandbox DCIP tenants, or from the test environments of non-government organisations.

The sandbox version of the NZ Verify app will verify credentials from the sandbox Govt.nz app wallet, or other test credentials as arranged with the DPI team.

## Conditions of use

Access to the sandbox environment will be granted to organisations involved with the production or verification of [Digital Identify Services Trust Framework (DISTF)](https://www.publicservice.govt.nz/about-the-commission/government-digital-delivery-agency/trust-framework-for-digital-identity/about-digital-identity-services/trust-framework-legislation) accredited digital credentials.

Full conditions of use of the sandbox environment are provided in the [Sandbox access request form](DPI%20Sandbox%20Access%20Form%202026-04-15.pdf). Two main points to note: 

* No Personal Identifiable Information (PII) can be added into the sandbox environment without the prior content of the data subjects.
* Credentials listed in the Govt.nz app wallet will be visible to all sandbox participants. Organisations are required to sign a Non-Disclosure Agreement to prevent disclosure of any information seen in sandbox before it has been publicised by the credential providers.

## Requesting access

Government agencies and other organisations can use the [Sandbox access request form](DPI%20Sandbox%20Access%20Form%202026-04-15.pdf) to provide the DPI team with details of the products they require, and any configurations necessary for adding their own credentials into the sandbox ecosystem.

## Version management

New sandbox versions of the Govt.nz and NZ Verify apps will be released from time to time, typically on a monthly cycle following internal testing by the DPI team. Production release will usually occur one week after sandbox.

Users should set their devices to automatically update the test apps when new versions are available.  

## Testing credentials in the wallet

Test credentials are available to assist relying parties with testing of verification products and their compatibility with the Govt.nz app wallet. Issuers can test their own credentials after details have been provided to the DPI team. 

To claim a credential:
1.	Set up the wallet in the app. 
2.	Tap the ‘+’ button at the top of the wallet screen.

    ![Wallet screenshot](/profile/sandbox/assets/Govt.nz%20app%20wallet%20add%20credential.png "Wallet screenshot")

3. Choose either to scan a QR code, or initiate an authorisation for a credential listed in the app.

### Selecting a credential from the list

The wallet provides a list of credentials that use the authorisation code flow which can be initiated from within the wallet. Issuers can add their credential to the list during the platform onboarding process.

These issuers can be used for general testing of the wallet and relying party products:
*	Montcliff DMV Driver Licence - enter any test details
*	Testopia driver licence or photo ID - use details from one of the Test Credentials provided below.

### Scanning a QR code

[MATTR Labs](https://tools.mattrlabs.com/issue-credential) may be used to generate pre-authorised driver licence and photo ID credentials that can be added to the wallet. The tool can be used to generate credentials that are revoked, expired, or pending activation.

The Test Credentials section provides three IDs with QR codes that can be scanned. Once scanned, you will be sent to the Testopia site where you can claim the credential by entering details as displayed on the ID card.

### Test credentials

**Photo ID for 16 year old**

<img src="/profile/sandbox/assets/testopia-photo-id-661717.png" alt="Photo ID 661717" width="70%">

**Photo ID for 26 year old**

<img src="/profile/sandbox/assets/testopia-photo-id-130926.png" alt="Photo ID 130926" width="70%">

**Driver licence for 26 year old**

<img src="/profile/sandbox/assets/testopia-driver-license-130926.png" alt="Driver licence 130926" width="70%">
