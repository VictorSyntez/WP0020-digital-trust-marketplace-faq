## Question: What would be a good strategy for tactically addressing digital wallets?

As governments and businesses alike beginn their digital joureny which will include the issuance and verification of
verifiable credentials, we must acknowledge the fact that citizens (users) of such wallets will demand flexibility of choice. We must also recognize that tactically, digital wallet vendors are not yet pervasive nor are they all interoperable.

The concept of a digital wallet is still rapidly evolving and emerging. This particular question implies to the Trust Over IP Foundation that the Ontario government is well aware that this early-stage technology will continue to churn and morph over the next few years.

There are a number of areas where the impact of this rapid evolution can be mitigated and even harnessed. The Trust Over IP Foundation recommends the following:

* Focus on single-use applications initially while using verifiable credentials for exchange - issuing a verifiable credential to a single-purpose application (wallet); requesting a proof of a verifiable credential (e.g. “please present your government identity card”) in simple manners.
* Prepare to adjust to the changing user experiences that will come. While the data constructs for verifiable credentials, DIDs, etc. are becoming more stable the ways that we interact are just beginning to evolve. The protocols for using a verifiable credential are not standardized, though DIDComm and Hyperledger Aries are beginning to create standard communication rituals for:

  * Establishing a secure connection.
  * Offering a Credential across the secure connection.
  * Requesting a credential from an Issuer across the secure connection.
  * Request a privacy-respecting proof from a particular Holder.
  * Sending arbitrary messages across the secure connection.

* While some API-based approaches have been proposed they tend to be simplistic and rely on web-based technologies, making other communication approaches (e.g. NFC or Bluetooth for touchless communication) difficult. The key learning at this early stage of the wallet space should be focused on the key interactions that are needed to exchange information appropriately.
* Use overlays and semantics to avoid complexity.
* Hide the complexity of the system from the person:

  * Don’t ask the user to pick attributes from multiple credentials when a single, much simpler question will help them - or help their wallet/application automatically respond with the correct type of information.
  * A predefined set of mappings for common use cases (e.g. driver’s licence to simpler presentation of proof of age for alcohol purchase, without revealing date of birth or address information) would also help users appreciate the value.

* Focus on the use of W3C Verifiable Credentials for …
* Focus on the atomic processes outlined in the PCTF - they provide leverage as they are reusable and are not dependent heavily on the underlying wallet technologies.
* Focus any digital wallet applications on a limited set of interactions and credential types. Arbitrary credentials are difficult to understand for any person - even deeply technical people. While the new pattern for using verifiable credentials are learned, more business use cases and credential types can be added. In time, a set of generic interaction patterns are likely to evolve.
Focus on the most common interactions, in environments where the government has the most control or influence.

  * Presentation of health card at registration at hospitals.
  * Presentation of driver’s license or other ID at Service Ontario locations.
  * Presentation of proof-of-age at LCBO.

* With clear public communication about the government’s commitment to open standards, pick a single wallet implementation for the early phases, while ensuring that representatives for other implementations remain engaged in the process and understand that the end goal is an open market based on finalized standards.
If a COVID-19 set of use cases are to be explored the [COVID-19 Credentials Initiative](https://www.covidcreds.com/) provides numerous guidance points.

Suggested Reading: [The Current and Future State of Digital Wallets](https://www.dropbox.com/s/8hancfpfi717kbv/The-Current-and-Future-State-of-Digital-Wallets-v1.0-FINAL.pdf?dl=0).
