
<a name="sec4"></a>

<div class="breaker"></div>

## 4 <a name="APPENDIX A"></a>APPENDIX B: IDENTITY MANAGEMENT OVERVIEW

### 4.1 Identity

#### 4.1.1 Real-World Identity

> “Identity is how we recognize, remember, and ultimately respond to specific people and things...It helps us recognize friends, families, and threats; it enables remembering birthdays, preferences, and histories; it gives us the ability to respond to each individual as their own unique person.
>
> ...Our identity is bigger than our digital selves. Our identities existed before and continue to exist independent of any digital representation. Digital identities are simply tools which help organizations and individuals manage real-world identity.”
>
> – A Primer on Functional Identity by Joe Andrieu<sup id="fnr-JoeAndrieu"><a href="#fn-JoeAndrieu" class="fnote"></a></sup>

#### 4.1.2 Identity in Identity Management

Identity in the domain of identity management has a much narrower scope than real- world notions of identity. In identity management, identity is defined as a reference or designation used to uniquely distinguish a particular person, organization, or device.

An identity must be unique<sup id="fnr-uniqueID"><a href="#fn-uniqueID" class="fnote"></a></sup>. This means that each person and organization can be distinguished from all other persons and organizations and that, when required, each person and organization can be uniquely identified. The uniqueness requirement ensures that a program or service can be delivered to a specific person or organization and that a program or service is delivered to the right person or organization.


### 4.2 Defining the Population

In the Canadian context, the universe of persons is defined as all citizens and residents of Canada (including deceased persons) for whom an identity has been established in Canada. The universe of organizations is defined as all organizations registered in Canada (including inactive organizations) for which an identity has been established in Canada. Those persons or organizations that fall within the mandate of a program or service constitute the population of the program or service<sup id="fnr-populationCharacteristics"><a href="#fn-populationCharacteristics" class="fnote"></a></sup>.

In the public sector, the following are some examples of program/service populations in Canada:

* Persons who were born in Alberta
* Persons who are required to file a federal income tax return
* Persons who are licensed to drive in Quebec
* Persons who are military veterans
* Persons who are covered by provincial health insurance in Ontario
* Organizations which are licensed to cultivate cannabis in Canada
* Organizations which are required to register with FINTRAC
* Organizations which are licensed to cut timber in British Columbia
* Organizations which are subject to the supervision of the Office of the Superintendent of Financial Institutions
* Organizations which are licensed to construct and operate oil and gas facilities in Saskatchewan

### 4.3 Defining the Identity Context

In delivering their programs and services, program/service providers operate within a certain environment or set of circumstances, which in the domain of identity management is referred to as the identity context. Identity context is determined by factors such as mandate, target population (i.e., clients, customer base), and other responsibilities prescribed by legislation or agreements.

Understanding and defining the identity context assists program/service providers in determining what identity information is required and what identity information is not required. Identity context also assists in determining commonalities with other program/service providers, and whether identity information and assurance processes can be leveraged across contexts.

The following considerations should be kept in mind when defining the identity context of a given program or service:

* Intended recipients of the program or service – recipients may be external to the program/service provider (e.g., citizens, businesses, non-profit organizations), or internal to the program/service provider (e.g., employees, departments)
* Size, characteristics, and composition of the client population
* Commonalities with other programs and services (i.e., across program/service providers)
* Program/service providers with similar mandates
* Use of shared services where the shared service delivery context may differ from the program context

### 4.4 Determining Identity Information Requirements

A property or characteristic associated with an identifiable person or organization is referred to as an *identity attribute* or an *identity data element*. Examples of identity attributes for a person include *name* and *date of birth*. Examples of identity attributes for an organization include *legal name* and *date of creation*. For any given program or service, identity information is the set of identity attributes that is both:
* Sufficient to distinguish between different persons or organizations within the program/service population (i.e., achieve the uniqueness requirement for identity); and
* Sufficient to describe the person or organization as required by the program or service.

Identity information is a strict subset of the much broader set of information referred to as either personal information (“information about an identifiable person”) or organizational information (“information about an identifiable organization”). Personal information or organizational information that is collected and used for the specific purpose of administering a program or delivering a service is referred to as *program-specific* personal information or *program-specific* organizational information. Program- specific personal information is usually restricted to the program and constrained by privacy legislation to ensure consistent use for which it was collected (e.g., to determine program eligibility), with a few exceptions.

When determining the identity information requirements for a program or service, program/service providers need to distinguish between identity information andprogram-specific personal information, as these can overlap<sup id="fnr-identityPersonalOverlap"><a href="#fn-identityPersonalOverlap" class="fnote"></a></sup>. For example, *date of birth* can be used to help achieve identity uniqueness (i.e., it is used as identity information) – but *date of birth* can also be used as an age eligibility requirement (i.e., it is used as program-specific personal information). When overlap between identity information and program-specific personal information occurs, it is a good practice to describe both purposes. This ensures that the use of identity information is consistent with the original purpose for which the identity information was obtained and that it can be managed separately or additionally protected by appropriate security and privacy controls. Program/service providers are advised to reduce the overlap between identity information and program-specific personal information as much as possible.

#### 4.4.1 Identifier

The set of identity attributes that is used to uniquely distinguish a particular person or organization within a program/service population is referred to as an *identifier*. This set of identity attributes is usually a subset of the identity information requirements of a program or service.

Different sets of identity attributes may be specified as an identifier depending on program or service requirements and, in some cases, legislation and regulation. For example, one program may specify *name* and *date of birth* as the identifier set of identity attributes. Another program may specify *name*, *date of birth*, and *sex* as the identifier set of identity attributes. Yet another program may use an *assigned identifier*<sup id="fnr-assignedIdentifier"><a href="#fn-assignedIdentifier" class="fnote"></a></sup> (such as a health insurance number or a business number) as the identifier set of identity attributes.

When determining the set of identity attributes to be used as an identifier, the following factors should be considered:

* **Universality** – Every person or organization within the program/service population must possess the identifier set of identity attributes. However, even when an identity attribute is universal, widespread missing or incomplete values for the identity attribute may render it useless as part of an identifier set. For example, many dates of birth for persons born outside of Canada consist only of the year or the year and the month.
* **Uniqueness** – The values associated with the identity attributes must be sufficiently different for each person or organization within the program/service population that the persons or organizations within the program/service population can be distinguished from one another. For example, date of birth information by itself is insufficient to distinguish between persons in a population because many people have the same birthdate.
* **Constancy** – The values associated with the identity attributes should vary minimally (if at all) over time. For example, having address information in the identifier set is problematic because a person’s address is likely to change several times in their lifetime.
* **Collectability** – Obtaining a set of values for the identity attributes should be relatively easy. For example, human DNA sequences are universal, unique, and very stable over time, but they are somewhat difficult to obtain.

These four factors are not an exhaustive list. Another factor that might be considered is whether the program or service has the legal authority to collect the identity attribute. Yet another factor might be the degree of invasiveness of collecting an identity attribute when other identity attributes might be sufficient for the purpose (e.g., DNA samples shouldn’t be collected where name would suffice).

#### 4.4.2 Assigned Identifier

It is generally agreed that *name* and *date of birth* comprise the minimum set of identity attributes required to constitute an identifier for a person. Analyses<sup id="fnr-identityResolutionProject"><a href="#fn-identityResolutionProject" class="fnote"></a></sup> have shown that a combination of *name* (*surname* + *first given name*) and full *date of birth* will distinguish between upwards of 96% of the persons in any population. While adding other identity attributes (e.g., *sex*, *place of birth*) to the set provides some marginal improvement, no combination of identity attributes can guarantee absolute uniqueness for 100% of a given population.

Consequently, due to the potential for identity overlap in whatever residual percentage of the population remains, program/service providers employ the use of an *assigned identifier*. An assigned identifier is an artificial identity attribute that is used solely for the purpose of providing identity uniqueness. It consists of a numeric or alphanumeric string that is generated automatically and is assigned to a person or organization at the time of identity establishment.

However, before an assigned identifier can be associated with a person or organization, the uniqueness of the person’s or organization’s identity within the relevant population must first be established (i.e., identity resolution must be achieved [see the next section]) through the use of other identity attributes (e.g., *name*, *date of birth*, etc.). Therefore, the use of an assigned identifier does not eliminate the need for traditional identity resolution techniques, but it does reduce the need to a one-time only occurrence for each person or organization within a population.

Once associated with a person or organization, an assigned identifier uniquely distinguishes that person or organization from all other persons or organizations in a population without the use of any other identity attributes. Examples of assigned identifiers include birth registration numbers, business numbers, driver’s license numbers, social insurance numbers, and customer account numbers. The following considerations apply to the use of assigned identifiers:

* Assigned identifiers may be kept internal to the program that maintains them.
* Assigned identifiers maintained by one program may be provided to other programs so that those programs can also use the assigned identifier to distinguish between different persons or organizations within their program/service population; however, there may be restrictions on this practice due to privacy considerations or legislation.
* Certain assigned identifiers may be subject to legal and policy restrictions which may vary between sectors and jurisdictions. For example, the Government of Canada imposes restrictions on the collection, use, retention, disclosure, and disposal of the social insurance number.

### 4.5 Identity Resolution

Identity resolution is defined as the establishment of the uniqueness of a person or organization within a program/service population through the use of identity information. A program or service defines its identity resolution requirements in terms of identity attributes; that is, it specifies the set of identity attributes that is required to achieve identity resolution within its population. Since the identifier is the set of identity attributes that is used to uniquely distinguish a unique and particular person or organization within a program/service population, the identifier is the means by which identity resolution is achieved.

### 4.6 Ensuring the Accuracy of Identity Information

Identity information must be accurate, complete, and up to date<sup id="fnr-upToDateRequirement"><a href="#fn-upToDateRequirement" class="fnote"></a></sup>. Accuracy ensures the quality of identity information. It ensures that the information represents what is true about a person or organization, and that it is complete and up to date.

For identity information to be considered accurate, three requirements must be met:

* **The identity information is correct and up to date.** Identity information, due to certain life events (e.g., marriage), may change over time. Ongoing updates to identity information may be required; otherwise, it becomes incorrect.
* **The identity information relates to a real person or organization.** Identity information must be associated with a person or organization which actually exists or existed at some point in time.
* **The identity information relates to the correct person or organization.** In large populations, persons or organizations may have the same or similar identity information as other persons or organizations. While the requirement for identity uniqueness addresses this issue, the possibility of relating identity information to the wrong person or organization still remains.

It is the responsibility of program/service providers to ensure the accuracy of the identity information that is used within their programs and services. The accuracy of identity information can be ensured by using an authoritative source. There are two methods by which this can be achieved:

* On an as needed basis, request the identity information from an authoritative source. This process is referred to as *identity information retrieval*. For example, a person’s place of birth might be electronically retrieved from the federal registry of persons born abroad.
* Subscribe to a notification service provided by an authoritative source. This process is referred to as *identity information notification*. For example, death notifications might be received from a provincial vital statistics registry.

These methods can be used independently or in combination, and an effective strategy usually requires the use of both.

If ensuring the accuracy of identity information by means of an authoritative source is not feasible, other methods may be employed, such as corroborating identity information using one or more instances of evidence of identity.

---
**Footnotes**

<a name="fn-JoeAndrieu" href="#fnr-JoeAndrieu" class="fn"></a>
The full text of the article can be found at: http://bit.ly/FunctionalIdentityPrimer.

<a name="fn-uniqueID" href="#fnr-uniqueID" class="fn"></a>
This is one of the requirements for establishing an identity assurance level. See Appendix C of the Standard on Identity and Credential Assurance [TBS c., 2013].

<a name="fn-populationCharacteristics" href="#fnr-populationCharacteristics" class="fn"></a>
The characteristics of a program/service population are a key factor in determining identity context. See the next section.

<a name="fn-identityPersonalOverlap" href="#fnr-identityPersonalOverlap" class="fn"></a>
This is usually not an issue for organizational information.

<a name="fn-assignedIdentifier" href="#fnr-assignedIdentifier" class="fn"></a>
See the next section.

<a name="fn-identityResolutionProject" href="#fnr-identityResolutionProject" class="fn"></a>
NASPO IDPV Project, Report of the IDPV Identity Resolution Project, February 17, 2014

<a name="fn-upToDateRequirement" href="#fnr-upToDateRequirement" class="fn"></a>
This is one of the requirements for establishing an identity assurance level. See Appendix C of the Standard on Identity and Credential Assurance [TBS c., 2013].
