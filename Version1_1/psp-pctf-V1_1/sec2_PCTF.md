
<a name="sec2"></a>

<div class="breaker"></div>

## 2 <a name="PCTF"></a>THE PAN-CANADIAN TRUST FRAMEWORK


### 2.1 Overview

#### 2.1.1 Background

The identity management ecosystem in Canada is comprised of multiple identity providers relying on authoritative source registries that span provincial/territorial and federal jurisdictions. Consequently, the Canadian ecosystem employs a federated identity model. 

The Pan-Canadian Trust Framework (PCTF) is an outcome of the Pan-Canadian approach for federating identities which is an agreement on the principles and standards to be used when developing identity solutions<sup id="fnr-identityAssurance"><a href="#fn-identityAssurance" class="fnote"></a></sup>. This approach, embodied in the PCTF, is intended to facilitate the transition to a digital ecosystem which will enable transformative digital service delivery solutions for citizens and residents of Canada.

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
* A **Contextual Identity** is an identity that is used for a specific purpose within a specific identity context<sup id="fnr-specificIdentityContext"><a href="#fn-specificIdentityContext" class="fnote"></a></sup> (e.g., banking, business permits, health services, drivers licensing, or social media). Depending on the identity context, a contextual identity may be tied to a foundational identity (e.g., a drivers licence) or may not be tied to a foundational identity (e.g., a social media profile).

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
to interoperate with one another in a digital ecosystem. An atomic process is a set of<sup id="fnr-stateTransition"><a href="#fn-stateTransition" class="fnote"></a></sup> logically related activities that results in a state transition . The PCTF recognizes that in practice a business process is often a collection of atomic processes that results in a set of state transitions. These collections of atomic processes are referred to as compound processes.

All of the atomic processes have been defined in a way that they can be implemented as modular services and be separately assessed for certification. Once an atomic process has been certified, it can be relied on or “trusted” and integrated into other digital ecosystem platforms. This digital ecosystem is intended to interoperate seamlessly across different organizations, sectors, and jurisdictions, and to be interoperable with other trust frameworks.

It should be noted that two atomic processes -- *Identity Information Determination* and *Identity Evidence Determination* – are carried out only once for a program/service.

##### 2.3.3.1 Atomic Processes

An atomic process is a set of logically related activities that results in the state transition of an object. The object’s output state can be relied on by other atomic processes. Figure 2 illustrates the atomic process model.

![Figure 2: Atomic Process Model](/images/Figure%20-%20Atomic%20Process%20Model.png)

Atomic processes are crucial building blocks to ensuring the overall integrity of the digital identity supply chain and therefore, the integrity of digital services. The integrity of an atomic process is paramount because the output of an atomic process is relied upon by many participants – across jurisdictional and public and private sector boundaries, and over the short term and the long term. The PCTF ensures the integrity of an atomic process through agreed upon and well-defined conformance criteria that support an impartial, transparent, and evidence-based assessment and certification process.

The conformance criteria associated with an atomic process specify what is required to transform an object’s input state into an output state. The conformance criteria ensure that the atomic process is carried out with integrity. For example, an atomic process may involve assigning an identifier to a person or organization. The conformance criteria may specify that any party responsible for carrying out the atomic process must ensure that the identifier assigned to the person or organization is unique for a specified population.

The atomic processes are detailed in Section 2.7.

Figure 3 illustrates some model diagrams of three atomic processes.

![Figure 3: Examples of Atomic Processes (Modeled)](/images/Figure%20-%20Examples%20of%20Atomic%20Processes.png)

##### 2.3.3.2 Compound Processes

The primary function of the PCTF is to assess and certify existing business processes. When analyzed, these business processes are often composed of several atomic processes. A set of atomic processes grouped together form a compound process that results in a set of state transitions. It may also be the case that a compound process is composed of a set of other compound processes which in turn can be decomposed into a set of atomic processes.

For example, a business process that one party refers to as *Identity Confirmation* may in fact turn out to be a compound process consisting of 5 atomic processes as shown in Figure 4.

![Figure 4: Example of a Compound Process (Modeled)](/images/Figure%20-%20Example%20of%20a%20Compound%20Process.png)

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


### 2.4 Mutual Recognition

Mutual recognition is an agreement wherein two or more parties agree to recognize the results of a conformance assessment. Depending on the context, the mutual recognition may be formalized through the issuance of a letter of acceptance or be part of a broader agreement.

Prior to commencing the PCTF mutual recognition process, it is recommended that a planning and engagement process be undertaken with the key participants in order to develop a formalized work arrangement.

At this time, the mutual recognition process is still in its early stages. The following sections outline mutual recognition at a high level. Detailed guidance will follow in subsequent deliverables.

#### 2.4.1 Process Mapping

Process mapping consists of the set of activities to map program activities, business processes, and technical capabilities to the atomic processes defined in the PCTF.

In most cases, this mapping is applied to an existing program currently in operation. The table below illustrates some examples of mapping to existing business processes.

| Atomic Process                  | Existing Business Process Examples |
| ------------------------------- | ---------------------------------- |
| Identity Resolution             | A service enrolment process that attempts to uniquely identify a person based on the person’s name and date of birth<br>A business registry process that attempts to uniquely identify an organization based on the organization’s legal name, date of creation, address, and identification number/name on an authoritative record |
| Identity Establishment          | A birth registration process that creates an authoritative birth record<br>A business registry process that create an authoritative business record |
| Identity Information Validation | A driver’s license application process that confirms identity information as presented on physical documents or by means of an electronic validation service<br>A cannabis licensing process that confirms identity information as presented about a business by means of an electronic validation with the applicable business registry |
| Identity Verification           | Asking questions of the person presenting the identity information – the answers to which (in theory, at least) only they and the interrogator would know (e.g., financial information, credit history, shared secret, mailed-out access code, password, personal identification number, assigned identifier)<br>A passport application process that compares biological characteristics recorded on a document (e.g., facial photograph, eye colour, height) to ensure it is the right applicant<br>Performing an on-site audit of a business |
| Identity Maintenance            | An identity information notification service<br>An identity information retrieval service |
| Credential Issuance             | Issuing an authoritative document such as a birth certificate or driver’s licence<br>Issuing an authoritative document such as a certificate of existence or compliance<br>Issuing a verifiable credential |

#### 2.4.2 Alignment to Other Frameworks

Alignment of processes, systems, and solutions assists in mutual recognition across an international context where multiple frameworks may be in use.

For example, someone who accesses Canadian digital services may also need to access digital services in other countries. Recognizing this evolution toward the international context, the PCTF is being designed to be applied in conjunction with established and emerging global frameworks, such as:
* The Electronic Identification, Authentication, and Trust Services (eIDAS)
* The Financial Action Task Force (FATF) – *Guidance on Digital Identity*
* The United Nations Commission on International Trade Law (UNCITRAL) – *Draft Provisions on the Cross-border Recognition of Identity Management and Trust Services*

International mutual recognition is still in its early phases. Consideration should be given to aligning to these frameworks before commencing the assessment process.


#### 2.4.3 Assessment

The PCTF defines a normative set of atomic processes and accompanying conformance criteria<sup id="fnr-conformanceCriteria2"><a href="#fn-conformanceCriteria2" class="fnote"></a></sup>. Once the existing business processes have been mapped to the atomic processes, they can be assessed and a determination made against each of the related atomic process conformance criteria.

A detailed assessment worksheet has been developed to assist in the PCTF assessment process. This worksheet consolidates the atomic processes and accompanying conformance criteria into a single spreadsheet to aid in the mapping of existing business processes and assist the assessment team in cross-referencing data for assessment analysis. The conformance criteria are also mapped to qualifiers to assist in the selection of the conformance criteria that are applicable to the assessment process.

Evidence collected to support the analysis and substantiate the determination should be collected and recorded in a manner that can be easily cross-referenced to the applicable conformance criteria.

It should be noted, that by design, the PCTF does not assume that a single provider is solely responsible for all of the atomic processes. Therefore, several bodies might be involved in the PCTF assessment process, focusing on different atomic processes, or different aspects (e.g., security, privacy, service delivery). Consideration must be given as to how to coordinate several bodies that might need to work together to yield an overall PCTF assessment. The organization being assessed is accountable for all parties within the scope of the assessment. The organization may decide that this is not feasible, nonetheless the organization remains accountable. Such cases will be noted in the assessment.

As the PCTF assessment process evolves, consideration will be given to determine which bodies and/or standards are best suited to meet stakeholder requirements and best applied in relation to the PCTF.

#### 2.4.4 Acceptance

Acceptance is the process of formally approving the outcome of the assessment process. The acceptance process is dependent on governance and takes into account the applicable mandates, legislation, regulations, and policies.

Eventually, the PCTF acceptance process may include standard processes defined by the International Standards Organization (ISO)<sup id="fnr-ISO"><a href="#fn-ISO" class="fnote"></a></sup> as follows:
* **Certification**: The provision by an independent body of written assurance (a certificate) that the product, service, or system in question meets specific requirements.
* **Accreditation**: The formal recognition by an independent body (generally known as an accreditation body) that a certification body operates according to international standards.

Formalized certification and accreditation programs are currently being developed. It is anticipated that once formalized, independent third parties will be enabled to conduct PCTF assessments. There are several domestic and international standards bodies that have recognized conformity assessment standards and programs. For example, the Standards Council of Canada has the mandate to promote voluntary standardization in Canada, where standardization is not expressly provided for by law.



### 2.5 Supporting Infrastructure

The Supporting Infrastructure is the set of operational and technical policies, rules, and standards that serve as the primary enablers of a digital ecosystem. The various elements of the Supporting Infrastructure have established rules that are outside the scope of the PCTF. The PCTF does not make recommendations in respect to the composition of the Supporting Infrastructure.

Figure 5 illustrates some elements (with examples) of what could constitute a Supporting Infrastructure.

![Figure 5: Supporting Infrastructure](/images/Figure%20-%20Supporting%20Infrastructure.png)

The following sections provide details on two elements of the Supporting Infrastructure that can assist in relating legacy implementations to newer technologies and standards.

#### 2.5.1 Methods

Methods encompass the sets of rules that govern such things as data models, communications protocols, cryptographic algorithms, databases, distributed ledgers, verifiable data registries, and similar schemes; and combinations of these. Methods also include systems that are isolated or have intermittent connectivity. Within the context of the digital ecosystem, Methods enable actors to interact directly or indirectly with one another without either party being bound to a particular solution or technology.

#### 2.5.2 Conveyance Mechanisms

Conveyance mechanisms are the various methods by which the output of one atomic process is made available for use as the input to another atomic process. As can be seen in Figure 6, the conveyance mechanisms are situated between the parties producing and consuming the output states of atomic processes.

![Figure 6: Conveying Output States between Parties](/images/Figure%20-%20Conveying%20Output%20States%20between%20Parties.png)

The PCTF does not constrain the possibility of several competing providers and it is anticipated that many providers will coexist to serve the conveyance mechanism needs of different communities across the public and private sector.


### 2.6 Digital Ecosystem and Information Flows

Figure 7 illustrates a conceptual model of the digital ecosystem roles and information flows. (Note that “Methods” in the diagram is discussed in Section 2.5.1.)

![Figure 7: Digital Ecosystem Roles and Information Flows](/images/Figure%20-%20Digital%20Ecosystem%20Roles%20and%20Information%20Flows.png)

#### 2.6.1 Roles

The model consists of four roles:
1. **Subject**: An entity<sup id="fnr-entity"><a href="#fn-entity" class="fnote"></a></sup> about which **_Claims_** are asserted by an **_Issuer_**.
2. **Issuer**: An entity that asserts one or more **_Claims_** about one or more **_Subjects_**, creates a **_Credential_** from these Claims, and assigns the Credential to a **_Holder_**.
3. **Holder**: An entity that controls one or more **_Credentials_** from which a **_Presentation_** can be expressed to a **_Verifier_**. A Holder is usually, but not always, the **_Subject_** of a Credential<sup id="fnr-credentialHolder"><a href="#fn-credentialHolder" class="fnote"></a></sup>.
4. **Verifier**: An entity that accepts a **_Presentation_** from a **_Holder_** for the purposes of delivering services or administering programs.

The digital ecosystem roles are carried out by many different entities that perform specific roles under a variety of labels. These specific roles can be categorized into the digital ecosystem roles as shown in the following table.

| Role      | Example |
| --------- | ------- | 
| Issuer    | Authoritative Party, Identity Assurance Provider, Identity Proofing Service Provider, Identity Provider, Credential Assurance Provider, Credential Service Provider, Credential Provider, Authenticator Provider, Digital Identity Provider, Delegated Service Provider |
| Subject   | Person, Organization, Device |
| Holder    | Digital Identity Owner, Card Holder |
| Verifier  | Relying Party, Credential Verification Service Provider, Credential Authentication Service Provider, Authentication Service Provider, Digital Identity Consumer, Delegated Service Provider |

Given the variety of business, service, and technology models that exist within the digital ecosystem, roles may be performed by multiple different actors in a given context, or one actor may perform several roles (e.g., an actor may be both a relying party and a credential provider).

In addition to the four roles outlined above, digital ecosystem actors include Supporting Infrastructure providers such as Network Operators.

#### 2.6.2 Information Flows

The model also consists of five information flows:
1. **Claim**: A statement about a **_Subject_**.
2. **Credential**: A set of one or more **_Claims_** asserted about one or more **_Subjects_**<sup id="fnr-multipleSubjects"><a href="#fn-multipleSubjects" class="fnote"></a></sup>.
3. **Presentation**: Information derived from one or more **_Credentials_**. The data in a Presentation is often about the same **_Subject_**, but the Credentials might have been issued by different **_Issuers_**.
4. **Credential Registration**: An indication<sup id="fnr-indication"><a href="#fn-indication" class="fnote"></a></sup> of the existence of a credential.
5. **Correctness Confirmation**<sup id="fnr-correctnessConfirmation"><a href="#fn-correctnessConfirmation" class="fnote"></a></sup>: An indication of the correctness of the **_Presentation_** itself and the correctness of the information associated with the **_Presentation_**.


### 2.7 Atomic Processes in Detail

#### 2.7.1 Identity Information Determination

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Information Determination is the process of determining the
      identity context<sup id="fnr-section_4_3"><a href="#fn-section_4_3" class="fnote"></a></sup>, the identity information requirements<sup id="fnr-section_4_4"><a href="#fn-section_4_4" class="fnote"></a></sup>, and the identifier<sup id="fnr-section_4_4_1"><a href="#fn-section_4_4_1" class="fnote"></a></sup>.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Determination Made</b>: The identity context, the identity information requirements, and the identifier have not been determined</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Determination Made</b>: The identity context, the identity information requirements, and the identifier have been determined</td>
  </tr>
</table>

#### 2.7.2 Identity Evidence Determination

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Evidence Determination is the process of determining the acceptable evidence of identity (whether physical or electronic).</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Determination Made</b>: The acceptable evidence of identity has not been determined</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Determination Made</b>: The acceptable evidence of identity has been determined</td>
  </tr>
</table>


#### 2.7.3 Identity Resolution

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Resolution is the process of establishing the uniqueness of a Subject within a program/service population through the use of identity information. A program or service defines its identity resolution requirements in terms of identity attributes; that is, it specifies the set of identity attributes that is required to achieve identity resolution within its population.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Identity Information</b>: The identity information may or may not be unique to one and only one Subject</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Unique Identity Information</b>: The identity information is unique to one and only one Subject</td>
  </tr>
</table>

#### 2.7.4 Identity Establishment

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Establishment is the process of creating a record of identity of a Subject within a program/service population that may be relied on by others for subsequent programs, services, and activities.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Record of Identity</b>: No record of identity exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Record of Identity</b>: A record of identity exists</td>
  </tr>
</table>

#### 2.7.5 Identity Information Validation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Information Validation is the process of confirming the accuracy of identity information about a Subject as established by the Issuer.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Unconfirmed Identity Information</b>: The identity information has not been confirmed with the Issuer</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Confirmed Identity Information</b>: The identity information has been confirmed with the Issuer</td>
  </tr>
</table>

#### 2.7.6 Identity Verification

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Verification is the process of confirming that the identity information is under the control of the Subject. It should be noted that this process may use personal information or organizational information that is not related to identity.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Unverified Control</b>: The identity information has not been verified as being under the control of the Subject</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Verified Control</b>: The identity information has been verified as being under the control of the Subject</td>
  </tr>
</table>

#### 2.7.7 Identity Evidence Validation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Evidence Validation is the process of confirming that the evidence of identity presented (whether physical or electronic) is acceptable.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Unconfirmed Identity Evidence</b>: The evidence of identity has not been confirmed as being acceptable</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Confirmed Identity Evidence</b>: The evidence of identity has been confirmed as being acceptable</td>
  </tr>
</table>

#### 2.7.8 Identity Continuity

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Continuity is the process of dynamically confirming that the Subject has a continuous existence over time (i.e., “genuine presence”). This process can be used to ensure that there is no malicious or fraudulent activity (past or present) and to address identity spoofing concerns.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Periodic Presence</b>: The identity exists sporadically and often only in association with a vital event or a business event (e.g., birth, death, bankruptcy)</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Continuous Presence</b>: The identity exists continuously over time in association with many transactions
</td>
  </tr>
</table>

#### 2.7.9 Identity Maintenance

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Maintenance is the process of ensuring that a Subject’s identity information is accurate, complete, and up-to-date.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Identity Information</b>: The identity information is not up-to-date</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Identity Information</b>: The identity information is up-to-
date</td>
  </tr>
</table>

#### 2.7.10 Identity Linking

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Identity Linking is the process of mapping two or more identifiers to the same Subject.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Unlinked Identifier</b>: The identifier is not associated with another identifier of the same Subject</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Linked Identifier</b>: The identifier is associated with one or more other identifiers of the same Subject</td>
  </tr>
</table>

#### 2.7.11 Credential-Identity Binding

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential-Identity Binding is the process of asserting one or more Claims about one or more Subjects.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Claim</b>: No claim exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Asserted Claim</b>: One or more asserted claims has been associated
with one or more Subjects</td>
  </tr>
</table>

#### 2.7.12 Credential Issuance

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Issuance is the process of creating a Credential from a set of Claims and assigning the Credential to a Holder.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Asserted Claim</b>: One or more asserted claims has been associated with one or more Subjects
</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Issued Credential</b>: A credential has been assigned to a Holder</td>
  </tr>
</table>

#### 2.7.13 Credential-Authenticator Binding

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential-Authenticator Binding is the process of associating a credential issued to a Holder with one or more authenticators. This process also includes authenticator life-cycle activities such as suspending authenticators (caused by a forgotten password or a lockout due to successive failed authentications, inactivity, or suspicious activity), removing authenticators, binding new authenticators, and updating authenticators (e.g., changing a password, updating security questions and answers, having a new facial photo taken).</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Issued Credential</b>: A credential has been assigned to a Holder</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Authenticator Bound Credential</b>: An issued credential has been
associated with one or more authenticators</td>
  </tr>
</table>

#### 2.7.14 Credential Validation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Validation is the process of verifying
credential is valid (e.g., not tampered with, corrupted, modified, suspended, or revoked). The validity of the issued credential can be used to generate a level of assurance.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Authenticator Bound Credential</b>: An issued credential has been associated with one or more authenticators</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Validated Credential</b>: The issued credential is valid</td>
  </tr>
</table>

#### 2.7.15 Credential Verification

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Verification is the process of verifying that a Holder has control over an issued credential. Control of an issued credential is verified by means one or more authenticators. The degree of control over the issued credential can be used to generate a level of assurance.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Authenticator Bound Credential</b>: An issued credential has been associated with one or more authenticators</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Verified Credential</b>: The Holder has proven control of the issued credential
</td>
  </tr>
</table>

#### 2.7.16 Credential Maintenance

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Maintenance is the process of updating the credential attributes (e.g., expiry date, scope of service, permissions) of an issued credential.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Issued Credential</b>: A credential has been assigned to a Holder</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Issued Credential</b>: The issued credential has been updated</td>
  </tr>
</table>

#### 2.7.17 Credential Suspension

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Suspension is the process of transforming an issued credential into a suspended credential by flagging the issued credential as temporarily unusable.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Issued Credential</b>: A credential has been assigned to a Holder</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Suspended Credential</b>: The Holder is not able to use the credential</td>
  </tr>
</table>

#### 2.7.18 Credential Recovery

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Recovery is the process of transforming a suspended credential back to a usable state (i.e., an issued credential).</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Suspended Credential</b>: The Holder is not able to use the credential</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Issued Credential</b>: The issued credential has been updated</td>
  </tr>
</table>

#### 2.7.19 Credential Revocation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Credential Revocation is the process of ensuring that an issued credential is permanently flagged as unusable.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Issued Credential</b>: A credential has been assigned to a Holder</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Revoked Credential</b>: The Holder is not able to use the credential</td>
  </tr>
</table>

#### 2.7.20 Notice Formulation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Notice Formulation is the process of producing a notice statement that describes what personal information is being, or may be, collected; with which parties the personal information is being shared and what type of personal information is being shared (as known at the time of presentation); for what purposes the personal information is being collected, used, or disclosed; the risk of harm and other consequences as a result of the collection, use, or disclosure; how the personal information will be handled and protected; the time period for which the notice statement is applicable; and under whose jurisdiction or authority the notice statement is issued. This process should be carried out in accordance with any requirements of jurisdictional legislation and regulation</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Notice Statement</b>: No notice statement exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Notice Statement</b>: A notice statement exists</td>
  </tr>
</table>

#### 2.7.21 Notice Presentation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Notice Presentation is the process of presenting a notice statement to a person.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Notice Statement</b>: A notice statement exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Presented Notice Statement</b>: A notice statement has been
presented to a person</td>
  </tr>
</table>

#### 2.7.22 Consent Request

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Request is the process of asking a person to agree to provide consent (“Yes”) or decline to provide consent (“No”) based on the contents of a presented notice statement, resulting in either a “yes” or “no” consent decision.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Presented Notice Statement</b>: A notice statement has been presented to a person</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Consent Decision</b>: A consent decision exists</td>
  </tr>
</table>

#### 2.7.23 Consent Registration

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Registration is the process of persisting a notice statement and the person’s related consent decision, to storage. In addition, information about the person, the version of the notice statement that was presented, the date and time that the notice statement was presented, and, if applicable, the expiration date for the consent decision may be stored. Once the consent information has been stored, a notification on the consent decision made is issued to the relevant parties to the consent decision.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Consent Decision</b>: A consent decision exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
</table>

#### 2.7.24 Consent Review

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Review is the process of making the details of a stored consent decision visible to the person who provided the consent.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
</table>

#### 2.7.25 Consent Renewal

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Renewal is the process of extending the validity of a “yes” consent decision by means of increasing an expiration date limit.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Consent Decision</b>: A stored consent decision has been
updated</td>
  </tr>
</table>

#### 2.7.26 Consent Expiration

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Expiration is the process of suspending the validity of a “yes” consent decision as a result of exceeding an expiration date limit.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Consent Decision</b>: A stored consent decision has been
updated
</td>
  </tr>
</table>

#### 2.7.27 Consent Revocation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Consent Revocation is the process of suspending the validity of a “yes” consent decision as a result of an explicit withdrawal of consent by the person (i.e., a “yes” consent decision is converted into a “no” consent decision).</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Stored Consent Decision</b>: A stored consent decision exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Updated Consent Decision</b>: A stored consent decision has been
updated</td>
  </tr>
</table>

#### 2.7.28 Signature Creation

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Signature Creation is the process of creating a signature.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>No Signature</b>: No signature exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Signature</b>: A signature exists</td>
  </tr>
</table>

#### 2.7.29 Signature Checking

<table>
  <tr>
    <th scope="row">Process Description</th>
    <td>Signature Checking is the process of confirming that the signature is valid.</td>
  </tr>
  <tr>
    <th scope="row">Input State</th>
    <td><b>Signature</b>: A signature exists</td>
  </tr>
  <tr>
    <th scope="row">Output State</th>
    <td><b>Checked Signature</b>: The signature is valid</td>
  </tr>
</table>

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
  
<a name="fn-identityAssurance" href="#fnr-identityAssurance" class="fn"></a> 
See: *Guideline on Identity Assurance* [TBS d., 2017].

<a name="fn-specificIdentityContext" href="#fnr-specificIdentityContext" class="fn"></a> 
In delivering their programs and services, program/service providers operate within a certain environment or set of circumstances, which in the domain of identity management is referred to as the identity context. Identity context is determined by factors such as mandate, target population (i.e., clients, customer base), and other responsibilities prescribed by legislation or agreements. For more information on identity and identity management concepts, see Appendix B.

<a name="fn-stateTransition" href="#fnr-stateTransition" class="fn"></a> 
A state transition is the transformation of an object input state to an output state.

<a name="fn-conformanceCriteria2" href="#fnr-conformanceCriteria2" class="fn"></a> 
The conformance criteria are maintained in a separate document.

<a name="fn-ISO" href="#fnr-ISO" class="fn"></a> 
ISO website: https://www.iso.org/certification.html.

<a name="fn-entity" href="#fnr-entity" class="fn"></a> 
An entity is defined as a thing with a distinct and independent existence such as a person, organization, or device that can be subject to legislation, policy, or regulations within a context, and which may have certain rights, duties, and obligations. An entity can perform one or more roles in the digital ecosystem.

<a name="fn-credentialHolder" href="#fnr-credentialHolder" class="fn"></a> 
Examples of where the Holder is not the Subject of a Credential would be a parent (the holder) holding the birth certificate (the credential) of their child (the subject) or a restaurant owner (the holder) holding a permit to operate (the credential) of a business (the subject).

<a name="fn-multipleSubjects" href="#fnr-multipleSubjects" class="fn"></a> 
An example of a credential having more than one subject is a marriage certificate.

<a name="fn-indication" href="#fnr-indication" class="fn"></a>
The indication may be a credential schema or the credential itself.

<a name="fn-correctnessConfirmation" href="#fnr-correctnessConfirmation" class="fn"></a> 
Correctness confirmation is often achieved by connecting a Verifier to an Issuer through a peer-to-peer system or an intermediary system.

<a name="fn-section_4_3" href="#fnr-section_4_3" class="fn"></a> 
See Section 4.3 for more information.

<a name="fn-section_4_4" href="#fnr-section_4_4" class="fn"></a> 
See Section 4.4 for more information.

<a name="fn-section_4_4_1" href="#fnr-section_4_4_1" class="fn"></a> 
See Section 4.4.1 for more information.
