
<a name="sec2"></a>

<div class="breaker"></div>

## 2 <a name="PCTF"></a>THE PAN-CANADIAN TRUST FRAMEWORK


### 2.1 Overview

#### 2.1.1 Background

The identity management ecosystem in Canada is comprised of multiple identity providers relying on authoritative source registries that span provincial/territorial and federal jurisdictions. Consequently, the Canadian ecosystem employs a federated identity model. 

The Pan-Canadian Trust Framework (PCTF) is an outcome of the Pan-Canadian approach for federating identities which is an agreement on the principles and standards to be used when developing identity solutions<sup id="fnr-identityAssurance">[fn-number](#fn-identityAssurance)</sup>. This approach, embodied in the PCTF, is intended to facilitate the transition to a digital ecosystem which will enable transformative digital service delivery solutions for citizens and residents of Canada.

#### 2.1.2 What is the PCTF?

The PCTF is a model that consists of a set of agreed-on concepts, definitions, processes, conformance criteria, and an assessment approach. It is not a “standard” as such, but is, instead, a framework that relates and applies existing standards, policies, guidelines, and practices, and where such standards and policies do not exist, specifies additional criteria. The role of the PCTF is to complement existing standards and policies such as those concerned with security, privacy, and service delivery.

The PCTF facilitates a common approach between the public sector and the private sector. Use of the PCTF ensures alignment, interoperability, and confidence of digital identity solutions that are intended to work across organizational, sectoral, and jurisdictional boundaries. In addition, the PCTF supplements existing legislation, regulations, and policies.

The PCTF supports the acceptance and mutual recognition of:
* Digital identities of entities such as persons and organizations; and
* Digital relationships between entities.

The PCTF defines a set of discrete process patterns (called atomic processes) that can be mapped to business processes. This mapping makes possible a structured assessment and evaluation of a digital identity solution and identifies any dependencies on external organizations and providers.

The PCTF is technology-agnostic and is defined in a way that encourages innovation and participation in the digital ecosystem. It allows for the interoperability of different platforms, services, architectures, and technologies. Furthermore, the PCTF is designed to take into consideration international digital identity frameworks, such as:
* The Electronic Identification, Authentication, and Trust Services (eIDAS);
* The Financial Action Task Force (FATF); and
* The United Nations Commission on International Trade Law (UNCITRAL).

Finally, it should be noted that the Public Sector Profile of the PCTF, in itself, is not a *governance* framework. Instead, it is a tool to help assess a digital identity program or service.

#### 2.1.3 Scope of the PCTF

Currently, the scope of the Pan-Canadian Trust Framework is:
* Persons in Canada: all citizens and residents of Canada (including deceased persons) for whom an identity has been established in Canada;
* Organizations in Canada: all organizations registered in Canada (including inactive organizations) for which an identity has been established in Canada; and
* Relationships in Canada: of persons to persons, organizations to organizations, and persons to organizations.




### 2.2 The PCTF Model

The PCTF Model, as shown in Figure 1, is a high-level overview of the PCTF in diagram form.

![Figure 1: The Pan-Canadian Trust Framework Model](/images/PCTF-V1_1_FINAL.png)

The PCTF model consists of four main components:
1. A **Normative Core** component that encapsulates the key concepts of the PCTF;
2. A **Mutual Recognition** component that outlines the current methodology that is used to assess and certify actors in the digital ecosystem;
3. A **Supporting Infrastructure** component that describes the set of operational and technical policies, rules, and standards that serve as the primary enablers of a digital ecosystem; and
4. A **Digital Ecosystem Roles and Information Flows** component that defines the roles and information flows within the digital ecosystem.

All items in the "Normative Core" component are prescriptive. The section on the "Mutual Recognition" component describes a recommended methodology but it is not mandatory that the methodology be followed. The sections on the “Supporting Infrastructure” and "Digital Ecosystem Roles and Information Flows" components are descriptive only and not prescriptive.

The four components of the PCTF are described in more detail in the subsequent four sections of this document (Sections 2.3 to 2.6 inclusive).




### 2.3 Normative Core

#### 2.3.1 Identity Domains

The PCTF draws a clear distinction between *foundational identity* and *contextual identity*:
* A **Foundational Identity** is an identity that has been established or changed as a result of a foundational event (e.g., birth, person legal name change, immigration, legal residency, naturalized citizenship, death, organization legal name registration, organization legal name change, or bankruptcy).
* A **Contextual Identity** is an identity that is used for a specific purpose within a specific identity context<sup id="fnr-specificIdentityContext">[fn-number](#fn-specificIdentityContext)</sup> (e.g., banking, business permits, health services, drivers licensing, or social media). Depending on the identity context, a contextual identity may be tied to a foundational identity (e.g., a drivers licence) or may not be tied to a foundational identity (e.g., a social media profile).

The establishment and maintenance of foundational identities is the exclusive domain of the public sector; specifically:
* The Vital Statistics Organizations (VSOs) of the Provinces and Territories;
* The Business Registries of the Provinces and Territories;
* Immigration, Refugees, and Citizenship Canada (IRCC); and
* The Federal Corporate Registry of Corporations Canada.

The establishment and maintenance of contextual identities is the domain of both the public and private sectors.

#### 2.3.2 Digital Representations

A digital representation is an electronic representation of an entity or an electronic representation of the relationship between two entities. Digital representations are intended to model real-world actors, such as persons, organizations, and devices.

Currently, the PCTF recognizes two types of digital representations:
* **Digital Identity**: An electronic representation of an entity, used exclusively by that same entity, to access valued services and to carry out transactions with trust and confidence.
* **Digital Relationship**: An electronic representation of the relationship of one entity to another entity.

A digital representation is the final output of a set of processes and therefore can be conceptualized as a set of state transitions (see Section 2.3.3).

As the PCTF evolves these digital representations will be extended to include other types of entities such as digital assets and smart contracts. It is also anticipated that in the future the PCTF will be used to facilitate the mutual recognition of digital representations between countries.

#### 2.3.3 Atomic and Compound Processes

The PCTF defines a set of atomic processes that can be separately assessed and certified
to interoperate with one another in a digital ecosystem. An atomic process is a set of<sup id="fnr-stateTransition">[fn-number](#fn-stateTransition)</sup>logically related activities that results in a state transition . The PCTF recognizes that in practice a business process is often a collection of atomic processes that results in a set of state transitions. These collections of atomic processes are referred to as compound processes.

All of the atomic processes have been defined in a way that they can be implemented as modular services and be separately assessed for certification. Once an atomic process has been certified, it can be relied on or “trusted” and integrated into other digital ecosystem platforms. This digital ecosystem is intended to interoperate seamlessly across different organizations, sectors, and jurisdictions, and to be interoperable with other trust frameworks.

It should be noted that two atomic processes -- *Identity Information Determination* and *Identity Evidence Determination* – are carried out only once for a program/service.

##### 2.3.3.1 Atomic Processes

An atomic process is a set of logically related activities that results in the state transition of an object. The object’s output state can be relied on by other atomic processes. Figure 2 illustrates the atomic process model.

![Figure 2: Atomic Process Model]()

Atomic processes are crucial building blocks to ensuring the overall integrity of the digital identity supply chain and therefore, the integrity of digital services. The integrity of an atomic process is paramount because the output of an atomic process is relied upon by many participants – across jurisdictional and public and private sector boundaries, and over the short term and the long term. The PCTF ensures the integrity of an atomic process through agreed upon and well-defined conformance criteria that support an impartial, transparent, and evidence-based assessment and certification process.

The conformance criteria associated with an atomic process specify what is required to transform an object’s input state into an output state. The conformance criteria ensure that the atomic process is carried out with integrity. For example, an atomic process may involve assigning an identifier to a person or organization. The conformance criteria may specify that any party responsible for carrying out the atomic process must ensure that the identifier assigned to the person or organization is unique for a specified population.

The atomic processes are detailed in Section 2.7.

Figure 3 illustrates some model diagrams of three atomic processes.

![Figure 3: Examples of Atomic Processes (Modeled)]()

##### 2.3.3.2 Compound Processes

The primary function of the PCTF is to assess and certify existing business processes. When analyzed, these business processes are often composed of several atomic processes. A set of atomic processes grouped together form a compound process that results in a set of state transitions. It may also be the case that a compound process is composed of a set of other compound processes which in turn can be decomposed into a set of atomic processes.

For example, a business process that one party refers to as *Identity Confirmation* may in fact turn out to be a compound process consisting of 5 atomic processes as shown in Figure 4.

![Figure 4: Example of a Compound Process (Modeled)]()

**note:** Any ordering of the atomic processes should not be inferred from the diagram.

#### 2.3.4 Dependencies

The PCTF model recognizes two types of dependencies. The first type is those dependencies that exist between atomic processes. Although each atomic process is functionally discrete, to produce an acceptable output an atomic process may require the successful prior execution of another atomic process. For example, although *Identity Establishment* of a person or organization can be performed independently at any time, it is logically correct to do so only after *Identity Resolution* for that person or organization has been achieved. This type of dependency is specified in the conformance criteria (see Section 2.3.5).

The second type is dependencies on external organizations for the provision of atomic process outputs (e.g., a commercial service provider or a credential authentication service). This type of dependency is identified and noted in the assessment process (see Section 2.4.3).


#### 2.3.5 Conformance Criteria

Conformance criteria are a set of requirement statements that define what is necessary to ensure the integrity of an atomic process. Conformance criteria are used to support an impartial, transparent, and evidence-based assessment and certification process.

For example, the *Identity Resolution* atomic process may involve assigning an identifier to a person or organization. The conformance criteria specify that the atomic process must ensure that the identifier that is assigned to the person or organization is unique for a specific population or context.

The conformance criteria are maintained in a separate document. Currently, the conformance criteria are consolidated in an assessment worksheet. In future versions the conformance criteria may be embedded in an automated assessment tool.

#### 2.3.6 Qualifiers

Qualifiers may be applied to conformance criteria. Qualifiers are intended to map similar or same conformance criteria from different trust frameworks to jurisdictional policy or regulatory requirements. For example, PCTF Level 1 conformance criteria for the *Identity Verification* atomic process can be mapped to Identity Assurance Level 1 as defined in the *Standard on Identity and Credential Assurance issued* by the Treasury Board of the Government of Canada.

Qualifiers help to further indicate a level of confidence, stringency required, or a specific requirement, in relation to another trust framework, an identity domain requirement, or a specific policy or regulatory requirement. Qualifiers can be used to select the applicable conformance criteria to be used in an assessment process. Qualifiers can also be used to facilitate mapping conformance criteria equivalencies across different trust frameworks.

Conformance criteria may have no qualifiers (applicable in all cases), a single qualifier (applicable in certain cases), or several qualifiers (applicable in many cases). Consult the assessment worksheet for examples of how qualifiers are used for assessment and how they may be mapped to other frameworks.

Jurisdictions may wish to use the qualifiers that are already defined in the PCTF. They may also define new qualifiers to reflect their specific requirements and add new conformance criteria if required. New qualifiers may be incorporated back into the normative core component of the PCTF; however, these changes should be subject to a formal governance process or change management process. It should also be noted that if new qualifiers and conformance criteria are introduced into the PCTF, these will need to be mapped to and vetted against the existing conformance criteria. See Section 2.8 for more information on qualifiers.


### 2.4 Normative Core

#### 2.4.1 Process Mapping

#### 2.4.2 Alignment to Other Frameworks

#### 2.4.3 Assessment

#### 2.4.4 Acceptance




### 2.5 Supporting Infrastructure

#### 2.5.1 Methods

#### 2.5.2 Conveyance Mechanisms




### 2.6 Digital Ecosystem and Information Flows

#### 2.6.1 Roles

#### 2.6.2 Information Flows




### 2.7 Atomic Processes in Detail




### 2.8 Qualifiers in Detail

#### 2.8.1 Identity Domain Qualifiers

To reflect the shared responsibility of identity across jurisdictions within the Pan- Canadian context, two identity domain qualifiers have been defined:
* **Foundational Identity Domain**: Conformance criteria that are tied to a specific foundational event (e.g., birth, person legal name change, immigration, legal residency, naturalized citizenship, death, organization legal name registration, organization legal name change, or bankruptcy). Foundational identities are the exclusive domain of the public sector (specifically, the Vital Statistics Organizations [VSOs] and Business Registries of the Provinces and Territories; Immigration, Refugees, and Citizenship Canada [IRCC]; and the Federal Corporate Registry of Corporations Canada).
* **Contextual Identity Domain**: Conformance criteria that are specific to an identity context (e.g., banking, business permits, health services, drivers licensing, or social media). Depending on the context, a contextual identity may be tied to a foundational identity (e.g., a drivers licence) or may not be tied to a foundational identity (e.g., a social media profile). Contextual identities are the domain of both the public and private sectors.

#### 2.8.2 Pan-Canadian Levels of Assurance (LOA) Qualifiers

The current version of the PCTF conformance criteria uses the four Pan-Canadian Levels of Assurance (LOA):
* **Level 1**: Little or no confidence required.
* **Level 2**: Some confidence required.
* **Level 3**: High confidence required.
* **Level 4**: Very high confidence required.

#### 2.8.3 Secure Electronic Signature Qualifiers

Part 2 of the Federal *Personal Information Protection and Electronic Documents Act 7 (PIPEDA)*, defines an electronic signature as “a signature that consists of one or more letters, characters, numbers, or other symbols in digital form incorporated in, attached to, or associated with an electronic document”.

There are a number of cases where PIPEDA Part 2 is technology specific and requires the use of a particular class of electronic signatures (referred to as a _**secure electronic signature**_ defined in its *annexed Secure Electronic Signature [SES] Regulations*). Secure electronic signatures may be used as qualifiers.

#### 2.8.4 Other Trust Frameworks Qualifiers

Qualifiers may be based on the three levels of assurance defined by the European Regulation No 910/2014 on electronic identification and trust services for electronic transactions:
* **Low**: Low degree of confidence.
* **Substantial**: Substantial degree of confidence.
* **High**: High degree of confidence.

Qualifiers may be based on levels of assurance defined in the NIST *Special Publication 800-63 Digital Identity Guidelines*:
* **Identity Assurance Level (IAL)**: Refers to the identity proofing level.
* **Authenticator Assurance Level (AAL)**: Refers to the authentication process.
* **Federation Assurance Level (FAL)**: Refers to the strength of an assertion in a federated environment, used to communicate authentication and attribute information (if applicable) to a relying party.


---
**Footnotes**
  
<a name="fn-identityAssurance">[fn-number](#fnr-identityAssurance)</a> 
See: *Guideline on Identity Assurance* [TBS d., 2017].

<a name="fn-specificIdentityContext">[fn-number](#fnr-specificIdentityContext)</a> 
In delivering their programs and services, program/service providers operate within a certain environment or set of circumstances, which in the domain of identity management is referred to as the identity context. Identity context is determined by factors such as mandate, target population (i.e., clients, customer base), and other responsibilities prescribed by legislation or agreements. For more information on identity and identity management concepts, see Appendix B.

<a name="fn-stateTransition">[fn-number](#fnr-stateTransition)</a> 
A state transition is the transformation of an object input state to an output state.
