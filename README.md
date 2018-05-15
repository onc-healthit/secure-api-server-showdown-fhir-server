# Winner of the Secure API Server Showdown Challenge
The Department of Health and Humans Services Office of the National Coordinator for Health Information Technology (ONC) has selected [Asymmetrik](https://www.asymmetrik.com/) as the Stage 1 winner of the Secure API Server Showdown Challenge. They will deploy and maintain their FHIR server in a test environment provided by ONC throughout the duration of Stage 2’s Server Track and will be eligible to receive $10,000 at the conclusion of the Challenge. The goal of Stage 2 is to further harden the open source FHIR server by enabling dedicated testing of the security components by the participants.

[See this repository for the winning code](https://github.com/Asymmetrik/node-fhir-server-core)

The [Asymmetrik](https://asymmetrik.com/healthcare) Extensible Server Framework for Healthcare allows organizations to build secure, interoperable solutions that can aggregate and expose healthcare resources via a common [HL7 FHIR](https://www.hl7.org/fhir/)-compatible REST API.

![](https://www.asymmetrik.com/wp-content/uploads/2018/01/FHIR-Server-Architecture_Update.png)

The framework defines a core server, which handles authenticated FHIR-compliant requests; and an extensible data source integration protocol, which allows developers to map any relevant healthcare data source, allowing that data to be used for a variety of healthcare IT solutions.

Using the Asymmetrik Framework, a developer could, for instance, aggregate patient data from multiple EHR systems, or build a server that allows data from legacy health record systems to be accessed using FHIR.

**Quick Start**

1.  Install latest Node.js LTS version.
2.  Install Node packages using either npm or yarn as follows:
> \# npm
>
> npm install @asymmetrik/node-fhir-server-core --save
> 
> \# yarn
> yarn add @asymmetrik/node-fhir-server-core

For full server documentation and implementation details, see:
[*https://github.com/Asymmetrik/node-fhir-server-core*](https://github.com/Asymmetrik/node-fhir-server-core)

**Background**

This server framework was first built as a response to the ONC's Secure API Server Showdown Challenge, which invited interested stakeholders to build a secure FHIR server using current industry best practices. The competition consisted of two stages: a Server Build Stage (Stage 1), and a Vulnerability Discovery Stage (Stage 2).

In early 2018, [*ONC announced Asymmetrik the winner of the Phase 1 Competition*](https://www.challenge.gov/challenge/secure-api-server-showdown-challenge/), and released the server as an open-source reference implementation in May 2018.

**Technical Details**

Asymmetrik's solution to the [*Secure API Server Showdown Challenge*](https://www.challenge.gov/challenge/secure-api-server-showdown-challenge/) consists of two MIT-licensed node.js projects on GitHub:

1.  Node FHIR Server Core: [*@asymmetrik/node-fhir-server-core*](https://github.com/Asymmetrik/node-fhir-server-core)

2.  Node FHIR@ Server Reference Implementation (MongoDB): [*@asymmetrik/node-fhir-server-mongo*](https://github.com/Asymmetrik/node-fhir-server-mongo)

Connecting the FHIR Server Core to an existing data source is designed to be simple and secure, using pluggable configuration and profile extensions.

The core library (node-fhir-server-core) provides support for conformance, authentication, authorization, input sanitization, endpoint security, and validation of data against the FHIRÂ® specification. Using an extensible plugin architecture, developers can easily map backend data sources into FHIR-compliant resources.

For a fully-built example using MongoDB as a backend, see:\
[*https://github.com/Asymmetrik/node-fhir-server-mongo*](https://github.com/Asymmetrik/node-fhir-server-mongo)


**How to Contribute**

Asymmetrik's solution paves the way for simplified access to health record information.

We envision a day where moving medical records between healthcare providers, accessing them using mobile apps, and sharing them with insurance companies, caretakers, and loved ones is a seamless experience.

Please see [*CONTRIBUTING.md*](https://github.com/Asymmetrik/node-fhir-server-core/blob/master/.github/CONTRIBUTING.md) for more details regarding contributing issues or code, or [*contact Asymmetrik directly*](https://www.asymmetrik.com/about/contact-us/) to learn more about how Asymmetrik can help implement FHIR-based interoperability solutions for your organization.


**About Asymmetrik**

[*Asymmetrik Ltd*](https://www.asymmetrik.com). is a Maryland-based company specializing in software development and data analytics. For over a decade, weâ€™ve helped government and healthcare organizations cut through bureaucracy and increase efficiency. Using vetted open-source components to build tailored enterprise solutions, Asymmetrik bypasses the high cost and extended time of custom development. Our team development approach is precise and efficient, attacking complex challenges with an arsenal of technical expertise and deep-dive analytics.


**References**

Core Repo: [*github.com/Asymmetrik/node-fhir-server-core*](https://github.com/Asymmetrik/node-fhir-server-core)

Mongo Repo: [*github.com/Asymmetrik/node-fhir-server-mongo*](https://github.com/Asymmetrik/node-fhir-server-mongo)

Asymmetrik Healthcare: [*healthcare.asymmetrik.com*](https://www.asymmetrik.com/solutions/healthcare/) | [*fhir.health*](http://fhir.health)

Asymmetrik Blog & Podcast: [*asymmetrik.com/blog*](http://www.asymmetrik.com/blog)

ONC: [*www.healthit.gov/topic/about-onc*
