## Defining an Open Platform

## Apperta Foundation - Defining an Open Platform

Health and care faces a crisis, with growing demands and spiralling costs. In other sectors we have
seen digital technology transform the way services are delivered, but so far, despite substantial
investment, such transformational effects have eluded us in health and care.

The Apperta Foundation believes innovative technologies can achieve the transformation that we
seek, yet if we want a different outcome from future investment we are going to have to do things
differently and break away from 20th Century technology and business models that lock data in
proprietary formats and customers into obsolete systems.

Change requires innovation and innovation does not come from the incumbent players. If we look
to other sectors we can see that it was Amazon not Foyles, eBay not Exchange and Mart, Wikipedia
not Encyclopedia Britannica that transformed their sectors through digital innovation.

In health and care, the complexity of the environment in terms of the informatics, regulation
governance and culture make the barriers to entry for innovative new players much higher than
they were in other sectors In health and care we have seen no new entrants to the market reach
discernible scale in the last twenty-five years.

We believe that open digital platforms based on open standards can lower barriers to entry,
stimulate innovation and enable successful startups rapidly get to scale.

This is not just our view but one shared by global experts and the major consultancies. More than
this, it is an approach that has already been proven at scale elsewhere.

We want to create an ecosystem where health and care communities can deploy and scale up an
open platform implementation confident that the data they store in it and the applications that run
on it are portable to any other implementation. This requires an unambiguous definition of what
we mean by an open platform and the standards on which it should be based.

This document is an attempt to propose such a definition, based on standards that have been
proven to work worldwide including HL7 FHIR, SNOMED-CT, IHE_XDS and openEHR.

We put this document forward as a blueprint to enable and support those pioneers keen to progress
on the journey to take digital health and care into the 21st Century.

Mr Bill Aylward MA MB BChir FRCS FRCOphth MD
Chair Apperta Foundation

#### Foreword

Dr Rebecca Wassall PhD
CEO Apperta
Clinical Lecturer / StR in Special Care Dentistry
Newcastle University

Dr Rebecca Wassall PhD
CEO Apperta
Clinical Lecturer / StR in Special Care Dentistry
Newcastle University

About Apperta

The Apperta Foundation is a not-for-profit community interest company supported by NHS England and NHS Digital led by clinicians to promote open systems and standards for digital health and social care.

We want to make the data, information and knowledge in IT systems open, shareable and computable to facilitate the creation of innovative digital services to transform the delivery of health and social care.

Apperta Foundation - Defining an Open Platform

#### Contents

{{ contents }}

##### Links

This document contains a number of links to background information
and sources of evidence coloured light blue in the text thus. In
the electronic version clicking on these takes you to the relevant
information on the Internet. Reader of the printed version should refer
to the electronic version at http://www.openplatforms.apperta.org/

# 1. Executive Summary

**Failure of the present approach to IT**

**Healthcare systems around the world are under increasing pressure and while there is a widespread belief that digital technologies have the potential to have a transformational impact, as they have in other sectors we are yet to see this in health and care.** 

This failure flows from the complexity (technical, cultural, and regulatory) of the health and care environment which creates insurmountable barriers for the sort of innovative start-ups that have been the engine of transformation in other sectors.

There is a strong and growing view that open platforms represent a solution, lowering the barrier of entry into the market and through this, supporting the injection of innovation.

**An 11% saving of national healthcare costs**

McKinsey and Co have projected that health and care systems implementing an open innovation platform can save more than 11% of total national healthcare costs, a view supported by others^1.

**Open platforms supporting 12 million patients already exist!**

There are a number of large-scale open platforms implementations supporting 12 million patients built in compliance with the HL7 FHIR, SNOMED CT, openEHR and IHE-XDS standards, delivering open platforms at scale across the globe. We should follow suit in the UK, building on the pioneering work of NHS Digital supported^
by Code4Health, Ripple Foundation and others using these standards.

**Why does the status quo inhibit new entrants?**

The complexity of both the health and care environment and the data means that the likelihood of a new entrant succeeding is significantly less than in other sectors.

Any new product must integrate with existing systems and share data with them. Here the proliferation of non-standard interfaces and data formats and the difficulty of getting information and cooperation from existing vendors make this an often impossible task.

In addition, regulatory barriers relating to safety, information governance and cybersecurity which are necessarily higher in health and care than many other sectors, place a further burden on new entrants.

These combine with a conservative, risk averse culture and the horrors of public sector procurement to make health and care an extraordinarily difficult market for a new entrant to get a foothold in.

**An open platform breaks the mould!**

**Open platforms liberate both data and applications making them portable and interoperable across different
platform implementations.**

**Away with vendor lock-in!**

An open platform is based on open standards. So **any** application built for an open platform, will operate on any open platform.

**The open platforms approach is vendor and technology neutral, eliminates lock-in, facilitates innovation and competition** , and forces vendors to compete on quality, value, and service.

**What does an open platform look like?**

An open platform will provide the infrastructure and services that are wholly based on openly published standards.

An open platform implementation will exist in a secure cloud environment exposing the services that application developers need to securely store, share and process data. It will enable them to
access and consume knowledge and resources via a set of standardised open Application Programming Interfaces
(APIs). This frees the application developer to focus on what they are good at - creating applications!

There are potentially many hundreds of possible platform services, but a minimum viable platform needs only
support a handful of services **based on the core standards of HL7 FHIR, SNOMED CT, openEHR and IHE-XDS.**

**The 8 principles of an open platform**

An open platform adheres to the following eight principles:

1. Open Standards Based
2. Shared Common Information Models
3. Supporting Application Portability
4. Federatable
5. Vendor and Technology Neutral
6. Supporting Open Data
7. Providing Open APIs
8. Operability (as in DevOps)

**Information Governance and Cyber Security**

There are many well recognised challenges presented by IG and cyber security. IG is a significant barrier both
for new entrant developers and existing service providers, thereby slowing the injection of innovation into the health and care market. Many of the existing systems in health and care were designed as on-premise installations with no or limited internet connectivity. Wider exposure to the internet can present significant IG cyber security challenges.
There is also growing public concern about privacy, how patients’ data is used, and the control they have over it.

An open platform approach can help address these challenges by providing tools and services to deal with IG and security issues so the app developer does not have to.

**Vision**

The endgame is to create an open ecosystem that will drive competition at the application, service and platform levels. There will be no vendor lock-in. The end user will be able to select a unique set of applications drawn from multiple vendors, where each application will meet the end user’s unique needs,
and where each application will work seamlessly together. The user will make their selection on the basis of
quality, value and performance.

All data will be held in open, shareable and computable formats, where the applications, services and
platforms are all substitutable.

**Next Steps**

Healthcare in general and the NHS in particular have needed a target architecture for some time. We have a set
of open standards (HL7 FHIR, SNOMED CT, openEHR and IHE-XDS) that have been shown to work well together for health and care. We propose that open platforms based on these standards should form the basis for a target architecture for the UK that aligns with global developments and which has been successfully implemented
elsewhere (see section 7.3.5.1 below).

**Aims of this document**

This document proposes a definition of an open platform and the principles that should be met by those who wish to claim they have an open platform.

The document also seeks to identify the issues that need to be resolved to promote the growth of an open digital ecosystem for health and social care and how these might be addressed.

# 2. Introduction

**While IT systems are pervasive across health and care organisations, health care systems around the world are under pressure and have not generated the widespread transformation found in other market sectors.**

This is despite the broad acknowledgement that digital technology has the potential to offer significant benefits.

Support for the potential benefits of anopen platform approach is growing with digital pioneers^3 , large IT and consultancy companies^4 , and national health systems^5 recognising the potential benefits. This progress is hampered by a lack of a clear definition of what does and does not constitute an open platform and a
lack of clarity on the issues that need to be addressed to make progress.

This document proposes a definition of an open platform and the principles that should be met by those who wish to claim they have an open platform. Comments and further contributions are invited from interested parties.

This document also seeks to identify the issues that need to be resolved to promote the growth of an open digital ecosystem for health and social care and how these might be addressed.

# 3. Why an Open Platform?

The complexity of the health and care environment is a major barrier to change creating a high, often
insurmountable, barrier to entry for innovative market entrants.

If we are to encourage innovation we need to lower this barrier and believe than by creating an open
platform that offloads some of this complexity from individual developers to the platform we can stimulate the
innovation and change we seek.

**3.1 Complexity**

A major reason for failure of digital technology within the health and care sector is its unparalleled complexity compared to other sectors and the failure of policy makers to recognise this complexity. There are many dimensions to this complexity including:

- The data: clinical and care data is complex. To create true “interoperability”, an open approach is required for defining data models;
       - The decision process, due to the number and varieties of types of parties involved in health and care
       - Non-determinance: there are generally no simple rules based approaches that can be applied to delivering health and care; and
       - Information governance. Much of the data is personal, and exchange and storage of information needs to be undertaken applying strict and legally enforceable rules.

Health and care is complex, while other sectors are simple or just complicated. We draw this distinction based on the definitions from the Cynefin Framework and work based on it the health context by Dr Tony Shannon.

In summary:

- Simple and complicated systems are deterministic: we can predict how changing a system’s inputs and parameters will affect the system’s behaviour. Complicated systems can be fully understood by their repeated decomposition until we are left witha set of simple, easily understood components. Modern engineering practice is highly capable of dealing with very complicated systems.
- In complex systems we can’t predict how changing a system’s inputs and parameters will affect the system’s behaviour. Complex systems exhibit emergent properties, not apparent in the system’s components parts. Attempts to manage them as complicated systems produce unexpected and unpredictable results. The key is to identify key patterns at play within the complexity and harness those patterns. An example is the clinical process in healthcare and the process orientation of the openEHR architecture.

**3.2 The engine of change**

**Startups, created by innovative individuals, are generally the engines for innovation and transformation.**
The complexity within health and care encompassing technical, cultural and regulatory dimensions means that small companies are unable to get a foothold in this market sector. The number and complexity of the issues that have to be addressed to create a minimal viable product is such that it is very difficult to adequately address them and breakout from promising prototype to minimum viable product.

**3.3 The Role of Platforms**

There are numerous examples in markets outside health and care, where the pre-existence of a platform has been
responsible for stimulating IT innovation. This includes the Sabre platform in travel, SWIFT in payment services and iOS and Android in relation to mobile apps.

The pre-existence of a platform provides the information infrastructure to developers so their focus is then
solely on what they are good at. This is in creating new and innovative user solutions, exploiting the  information to which platforms provide ready access.

The platform deals with onerous problems such as interoperability, information governance, cybersecurity
and business continuity leaving app developers to focus on their applications, functionality, and design. In this way, the existence of platforms speeds up development and stimulate innovation.

**3.4 Who should own the Platform?**

Thought leaders within health and care have recognised the need for a  platform approach for over 20 years. The initial approach was to adopt platforms based on proprietary standards, with companies seeking to own the platform.

This approach has been tried and abandoned by most players both for new entrant developers and existing
service providers,. Most parties have acknowledged that, due to the combined pressures from competitors, customers and regulators, there is unlikely to be a winner and that it is preferable to support the creation of an open platform and seek commercial opportunities elsewhere in the value chain.

We see evidence of growing support for open platforms with initiatives like the Health Services Platform Consortium and Commonwell Health Alliance in the USA, and the adoption of the open platform standards openEHR and IHE-XDS at scale in many places across the globe. Many parties come to the conclusion that the problem is too big for even the largest players to solve with proprietary approaches. Only an open approach that allows for global cooperation on the creation and curation of clinical content can succeed.

# 4. Proposed Definition of an Open Platform

**4.1 Introduction**

When trying to define an open platform it is necessary to understand the needs of the different stakeholder groups, as well as the generic and underlying functionalities of health and care software applications.

**4.2 What do Health and Care**

**Applications do?**

At an abstract level all health and care applications do either or both of the following:

1. Support the processes that deliver care;
    and/or
2. Collect and/or analyse data to support
    the delivery of care.

At a functional level, all health and care applications:

1. Create, consume and update information about the subjects of care - i.e. the health and care record;
2. Consume and process knowledge - i.e. data, metadata, care pathways, decision support rules and heuristics etc.; and 
3. Manage the consumption of care resources - (this includes creating, consuming, processing and updating information about them - i.e. referrals, orders, treatments, and services).

Most applications don’t directly create knowledge, but by collecting data through the care process they can support activities that refine current knowledge and create new knowledge.

**4.3 How do Users want to use Applications?**

An individual user who is involved in the health and care system (patient or service user, family or informal carer or health and care worker or professional) would like to be able to choose a set of applications from multiple vendors that best support their needs.

An open platform enables applications from multiple vendors to be orchestrated to work together to meet an individual user’s needs.


# 4. Proposed Definition of an Open Platform

**4.4 What do Developers want from a Platform?**

Developers want to focus on writing the front end applications. They would like to be able to call upon ready made resources and services (via API calls) that are supplied by the platform. These resources are provided by an open platform as described above.

**4.5 Healthcare Payers and Providers?**

Healthcare payers seek lower costs, better value and a more agile response from solution providers to their changing needs.

They wish to be able to choose the best options from multiple vendors and to be able to move easily when the best option changes.

They wish to ensure that they can use their data as they wish and will not be constrained by it being locked-in to proprietary formats or systems.

An open platform facilitates agile development of healthcare apps and solutions, takes advantage of the lower
cost of cloud infrastructure, eliminates vendor lock-in and encourages competition.

**4.6 Proposed Definition**

The following definition is based on a one previously proposed^6 with amendments based on feedback from a number of interested parties.

In health and care, an open digital ecosystem can make it easier to build applications that support safe, high quality compassionate care. It allows applications and services from multiple vendors to work together for an individual user whatever their role (e.g. clinician, patient, carer, social worker, commissioner, manager, care worker, etc.) such that there is a many-to-many substitutability between applications and services. In other words, an application requiring a service can use any available service provider via common APIs.

An open ecosystem is vendor and technology neutral and eliminates lock-in, facilitates innovation and forces vendors to compete on quality, value, and service.

An open platform adheres to the following principles in order to meet the need of all stakeholders:

**1. Open Standards Based** - The implementation should be based on agile open standards^7. Any willing  party should be able to use these standards without charge to build an independent, compliant instance of the complete platform;
**2. Shared Common Information Models** - There should be a set of common information models^8 in use by all  instances of the open platform, independent of any given technical implementation;
**3. Supporting Application Portability**- Applications written to run on one platform implementation should be able to run with either trivial or no change on another platform that has been independently developed;
**4. Federatable** - It should be possible to connect any implementation of the open platform to all others that were independently developed, in a federated structure, to allow the sharing of appropriate information and workflows between them;
**5. Vendor and Technology Neutral** - The standards should not depend on particular technologies or require components from particular vendors. Anyone building an implementation of the open platform may elect to use any available technology and may choose to include or exclude proprietary components;
**6. Supporting Open Data** - Data should be exposed as needed (subject to good information governance practice) in an open, shareable, computable format in near to real-time. Implementors may choose to use this format natively in their persistence (storage) layer of the open platform itself or meet this requirement by using mappings and transformations from some other open or proprietary format;
**7. Providing Open APIs** - The full specification of the APIs (the means by which applications are connected to the platform) should be freely available.
**8. Operability (as in DevOps^9)** - The platform should support the principles of operability^10 (this is all about the qualities of a system that enables applications to operate well throughout their full life cycle). Software systems which follow software operability good practice will tend to be simpler to operate and maintain, with a reduced cost of ownership, and almost certainly fewer operational problems.

# 5. Open Platform Architecture

The specific architecture of an implementation of an open platform meeting the proposed definition will vary from implementation to implementation. However, at a high conceptual level the architecture will take a form similar to that in the diagram below.

As a minimum the platform provider will provide a **service bus** that provides authentication, routing, and API management allowing **applications** to securely access the APIs provided by **platform service providers.**

Optionally, a platform provider may provide facilities to build or host applications and platform services; or they may provide some of the platform services themselves. The platform provider may provide federation services to enable applications to access the data or services held on other compliant platforms.

A typical platform will have the capability to support a large number of users running thousands of applications, and will offer a number of platform services (typically low double figures in number).

# 6. Platform Services

**Platform services provide those facilities needed to build interoperable health and social care applications. The platform services offer those things that app developers cannot or do not want to do themselves.**

A platform provides access to these services via secure and robust APIs (Application Programming Interfaces)
while the services themselves are designed to provide flexible and scalable access to the resources required.

The number of platform services that could be provided is unlimited and will include services to help developers deal with both generic technical challenges and challenges specific to the health and social care environment. However, a useful platform can be provided with just a few services. For more details of the concept of a Minimal Viable open Platform (MVP - the minimum number of services necessary to provide a viable open platform) see section 9.

This section lists the classes of service that might be usefully provided on an open platform in health and social care.

**6.1 Identity Assurance, Authorisation and Authentication Services**

 **1. Identity Assurance**

Identity Assurance is concerned with establishing that an individual claiming a particular identity is that person. Identity Assurance can be extended to establishing that the individual has the status or qualifications they claim (e.g. is a registered health or care professional licensed to practice in the UK).

Health and care apps are concerned about the identity assurance of individuals and their role(s) in health and care. Identity can be assured at a number of levels and is typically achieved by the individual providing various proofs of identity and qualifications. This can range from a simple check that an individual has control over an email address they use to identify themselves, through to developed vetting by the security services. For health and care purposes something between these two extremes is required. An example candidate is the GOV.UK Verify service. An open platform may choose to provide access to this type of service as an “Assured Identity Service” for its users.

**2. Authorisation**

Authorisation is concerned with the authority an individual has. Authorisation can be described in general terms: Is individual “I” allowed to perform action “A” on an object “O”? This may include i’s authority to access data or perform an action on a particular patient or service user. Alternatively, authorisation might capture a data subjects consents for particular uses of data or actions. The rights to grant authorisations and consents sit with a multitude of entities including both individuals and organisations. The open platform may choose to provide the assured records of such authorisations as a “Service” for its users.

**3. Authentication**

Authentication is concerned with the technical measures that allow an individual to access and use their
identity credentials, e.g. passwords, keys, biometrics, etc. Authentication is typically achieved by proving some combination of one or more of:

- Something they know - a password or secret;
- Something they have - a key, a smart card, or some other unique device; or
- Something about them - a fingerprint, a voice print or other biometric.

Authentication services are a core part of an open platform implementation.

**6.2 Data Repositories**

An essential component of any open platform is the provision of data repositories to store data about patients
and service users who are the subjects of care, and for these to be held in an open shareable format. The repositories are the patient’s own record and have been variously described as an Electronic Health Record (EHR), Integrated Digital Care Record (ICDR), and a Personal Health/Care Record (PHR/PCR).

Current open platform implementations typically provide three linked repositories:

- **A demographics service** sometimes described as a registry or master index containing basic demographic information about the subject of care.
- **A structured data repository** a repository where highly structured information can be stored in an open shareable format. By far the most widely implemented examples of a structured data repositories are those based on the openEHR standard.
- **A “document” store,** sometimes described as a Vendor Neutral Archive (VNA). This is a repository to store documents and other unstructured or semi-structured data along with supporting structured metadata. VNA’s are widely used to store textual documents or images, but they are capable of storing anything that can be represented in any arbitrary digital format. By far the most widely implemented examples of a document store are those based on the IHE-XDS standard.


A platform providing just the service bus and a data repository provides the minimal viable configuration for an open platform (see section 9).

**6.3 Record Locator Services**

A record locator service provides an extension to a demographics service, enabling records to be located where
there are multiple data repositories on a single platform implementation or there is access across multiple federated platforms implementations.

In the context of the NHS England, a record locator service is an obvious extension of the the Spine PDS. 

**6.4 Resource Discovery and Scheduling**

Applications will often need information about resources available to provide health and care services and be able to allocate them or schedule their use for a particular patient and service user. The scope of such activities is very wide ranging and may include:

- Requests for tests and investigations;
- Referrals for advice or treatment;
- GP appointments;
- A nursing home bed; or
- A home care visit.

Health and social care organisations presently spend significant resources to both locate and secure suitable resources. Their methods are commonly manual and highly inefficient, leading to interruptions in patient flows, the sub-optimal use of resources, and avoidable costs and suffering.

There are potentially a number of platform services that could be created to assist with the process of discovering available resources, allocating them,and scheduling their use and handling the resultant financial flows.

There are some existing services that could be exposed via an open platform of which the most significant in the NHS for example is the e-Referral Service.

**6.5 Knowledge Sources**

Applications need to access information and knowledge in order to function. This knowledge is highly diverse. At one end of the spectrum, it includes data that is easily interpreted and can be easily provided in the form of simple static lists and tables. At the other end of the spectrum, it includes complex representations of clinical pathways (workflows), decision support rules and heuristics, and data that is rapidly changing or difficult to interpret. Examples include: details or order sets and test batteries; drug information; resource
availability; clinical terminologies; and content definitions.

An open platform may provide Knowledge Sources as “Services” that are accessible through standard APIs. The Knowledge Source Services may either simply return the required data, or in the case of complex knowledge, the Service may return a relevant interpretation based on data provided by the requestor. For example, a drug knowledge source might return a specific dosage recommendation rather than simply the standard dose or dose range.

There is a vast range of knowledge sources that could be provided through an open platform. These include:

**6.5.1 Workflow**

Services to orchestrate workflow between applications could bring significant extra capabilities to an open platform. Many care pathways cut across multiple systems and organisations and many failures of care are the result of poor or failed handovers between individuals and organisations on the care pathway.

The effective management of care pathways that cut across multiple applications requires open and computable standards for the representation and management of workflows. Currently work in this area is immature. Generic workflow standards such as BPMN-2 have the potential to handle many of the workflows found in health but can’t handle some of the many highly complex non-deterministic workflows found in health and care.
Here specific healthcare standards such as openEHR’s GDL and PROforma might provide the required functionality. openClinical.net provides a working implementation of PROforma while openClinical.org provides a good overview of much of the work in this area.

**6.5.2 Terminology Services**

Terminologies used in health and care such as SNOMED CT are large and complex and difficult to implement.

While some developers may require access to raw terminology data, for many developers, sophisticated  terminology services are available that have the potential to handle much of SNOMED CT’s intrinsic complexity (e.g. equivalence, subsumption, mapping between terminologies and the handling of subsets and supersets).

**6.5.3 Clinical Calculators**

There are a large number of calculations made in medicine. Some are simple and easily handled by developers. Others are difficult and error-prone, requiring complex look-ups and adjustments against multiple factors or normative datasets (e.g. paediatric weight centiles) and some are safety critical (e.g. opiates equivalence calculations).

Quality assured clinical calculators can be provided as a platform service, removing both the complexity of the calculation and management of any associated risks from the developer.

**6.5.4 TRUD Data**

The Technology Reference data Update Distribution site run by NHS Digital contains a large number of sets of
reference data. These datasets are available for download and most can be used free of charge after a simple
registration process.

However many of these could be made more conveniently available via an API on the open platform.

**6.5.5 Organisation Data Service**

The Organisation Data Service run by NHS Digital contains data about NHS and partner organisations. This data
is available for download in a machine readable form (some of the most detailed information is only available to NHS users).

This data could usefully be made available via an API. This has been recognised by the The Organisation Data Service (ODS) Strategy 2015-2020. However, to-date, there has been no commitment by the NHS to implement this strategy recommendation which will be necessary if these data are to be made available as an open platform service.

**6.5.6 Drug Information**

Many applications require information about medicines. The requirement for drug information includes simple static data (such as form, strength, route and pack sizes) and more sophisticated active decision support (relating to such things as contraindications, interactions, cross-sensitivities and dosage). There are freely available sources for much of the static data likely to be required (e.g. NHS dm+d). For comprehensive information, it is necessary to turn to commercial providers some of whom have suitable APIs. These APIs could be made available via an open platform

**6.6 Legacy Connectors**

**Applications running on an open platform will need to communicate with existing systems in health and care that are not themselves complaint with open platform.**

Creating connectors with legacy systems requires that three distinct aspects are addressed:

1. Technical and informatics issues;
2. Commercial agreement with system
    vendors; and
3. Access agreement with the data
    controller and/or data subject and IG.

Where an open platform offers legacy connectors to its users, it has the potential to address (at least in some part) all of these issues. This will present a significant benefit to the open platform’s users as it will remove many aspects that are presently a significant barrier to application development.

**6.6.1 Technical and Informatics issues**

**1. Technical Issues**

Technical issues include technical mappings and transforms to allow legacy system connectors to be exposed by way of a modern API (currently REST with GraphQL emerging). The mapping may involve older API technologies on the legacy system (e.g. SOAP, WSDL, etc.); or it may involve exposing non-API based interfaces on legacy systems as a modern API.

Legacy interfaces were often designed for limited use by a few trusted developers, and they frequently lack the management, authentication and cybersecurity protections required by APIs that may be exposed to the Internet. An open platform typically provides an API Management Gateway that can handle the technical
transformations, provide related open source adaptors for reuse and provide the management and protection of the underlying legacy interface.

**2. Informatics Issues**

The stages of integration that are possible on the journey from the current healthcare IT landscape, with many legacy systems that struggle to share structured data, towards a federated set of systems based on a common architecture, demands support for a step wise approach. In exploring a 6 staged maturity model towards an Integrated Digital Care Record future, this work may be a useful way to explore the journey ahead for many of us.

The key informatics challenge towards a set of consistently modelled record artefacts is content mapping. This problem arises because systems represent similar concepts (e.g. clinical or care data) in different ways, using different levels of granularity, and with differing usage of standard terminologies.

*A key feature of an open platform is that all systems share a common set of open information models.*

**6.6.2 Commercial Issues**

All systems vendors recognise the importance of interoperability. The vendor community as a whole knows that they can grow the total market size and thus the opportunity for individual vendors by creating a better Return on Investment (ROI) for customers through interoperability. Indeed, it is the vendor community that has led most of the successful work in the area of interoperability (e.g. IHE, HL7 v2, MIG, INTEROPen) driven by commercial imperatives to solve interoperability issues in order to sell systems.

**However, it must be recognised that many established vendors have business models reliant on customer  lock-in and will resist opening up their systems in a way that undermines this core business approach**. 

While they will be supportive of providing limited APIs such as those proposed by INTEROPen, they will resist
more fundamental changes to open up all of the data in their systems, removing the commercial benefit they currently gain through data lock-in.

Many vendors have partner programmes designed to facilitate third parties wishing to connect to their systems.
As the number of third parties wishing to connect grows, this “many-to-many relationship” creates serious problems. These problems affect both the vendor and the third party.

A legacy vendor may not be able to handle requests from hundreds of app developers and a small app developer may find it too difficult to engage with multiple partner programmes. Some legacy vendors may also use their position to obstruct connections that they do not see as in their commercial interest.

An open platform provider can act as a broker in this relationship, shifting control over the decision of who connects, from the legacy vendor and to the data controller or data subject. We know from the GPSoC Programme that giving legacy vendors too much power (for instance in who connects and how they connect), severely restricts interoperability.

**6.6.3 Access Agreement and Information Governance**

Finally, once technical and commercial issues are resolved an app developer still needs permission to connect from the data controller of the system to which they wish to connect. The data controller needs to establish the bonafides of the user of any connecting application and where the connection is being approved on the basis of the data subject's wishes (as will often be the case for apps used by patients), that the data subject has consented.

Here too an open platform provider can act as a broker much simplifying this problem for the app developer, app user, and data controller by providing identity assurance and authentication by either acting as a trusted third party (itself providing certifications relating to the app or app user) or in a trust-agnostic mode (where it simply provides a gateway to an external source of trust). In addition, by proxying connections to legacy systems, a platform can protect underlying systems from damaging behaviour by an app (either malicious or unintentional) eliminating the need for technical accreditation of apps by end systems vendors.

# 7. Standards for an Open Platform

**Open standards are critical to achieving the central aim of an open platform** - that is, portability for data and substitutability for applications so that neither gets locked into a particular vendor's platform.

This requires standards in two areas:

- Open Interface standards (APIs); and
- Content standards.

Before turning attention to these standards, we will consider the difference between technical and content-based standards.

**7.1 An Understanding of Technical vs Content-based Standards.....**

Defining suitable open API standards is primarily a technical problem and is not a difficult problem to address. *There are well established standards from the Open API Initiative. APIs for an open platform should be defined using these standards.*

**Content Standards**

Content standards define the way in which the content (often called “clinical content”) is represented in systems and interactions between them. Content standards can be applied to the way information is stored in an electronic record or to the payload of a message or API. Content standards typically describe how information describing a particular concept (e.g. A blood pressure or dementia assessment) should be formatted, structured and coded to make it unambiguously computable.

Defining content is primarily a clinical^11 rather than a technical problem. It is concerned with getting clinicians to agree what they mean by a given concept, the parameters associated with the concept and how they are represented. This is work that needs to be led by clinicians supported by informaticians.

There is much confusion in the area of interoperability in health and care that flows from the failure to understand the difference between technical and content standards. This confusion is compounded by the fact that leading standards like HL7 FHIR and openEHR address both technical and content issues. Nevertheless, the
way they address this is quite different, with FHIR focusing on a limited range of content. The consequence is that FHIR lacks the mature community, governance and tooling for large scale content development and maintenance.

Content is ideally defined in a way that is agnostic to any particular technical representation. This is particularly important as content standards tend to be convergent and stable over the long-term whereas technical standards are constantly changing.

**7.2 Open API Standards**

**An open platform appears to applications as nothing more than a set of open APIs which enable them to access platform services.**

The endgame for an open platform architecture is to have a complete set of platform microservices for all those things that can usefully be offloaded to the platform by the developers’ app. Each microservice will include a standard and stable open API expressed using the standards defined by the Open API Initiative. The number of platform microservices is potentially large (maybe some hundreds to a few thousand). However, the problem is a long-tailed one, which means an open platform with a small number of services (less than 10) can provide high utility to developers.

**7.2.1 Defining an open API**

In defining an open API, an open platform will be required to specify the technical operation of the API (this is a generic issue) and the actions that the API will support (this is a domain specific/flavoured issue):

**(1) Technical Operation**

API technologies are continually changing but the current preference amongst application developers is for REST APIs carrying a JSON payload. This would be the current choice of API technology for an open platform.

However, REST APIs are designed to return a fixed, predetermined payload. This can make complex queries (that are common in the health and care domain) inefficient and onerous for the developer. The complex queries will require a subset of the data from the payloads of many REST APIs calls. Here new approaches based on GraphQL^12 are gaining currency and GraphQL and other technologies such as Apache Thrift would appear to be the API
technologies to watch.

**(2) API Actions**

Typically, there will be a small number of actions (~10) that an application will need to perform on a given service. What these actions are will depend on the nature of the service, but they will typically include
querying, reading and writing data to and from the service or the control of transactions managed by the service.

**7.2.2 Open APIs that are Currently Available**

The majority of open APIs that have been developed to-date have been focused on interactions with electronic health records (EHRs). Available open APIs of note include:

**openEHR EHRScape API** - This provides comprehensive REST APIs to any openEHR compliant Clinical Data Repository (CDR);
**HL7 FHIR API** - This provides a REST API to any FHIR compliant EHR; 
**SMART** - This provides a definition of a set of openAPIs for EHRs and data warehouses, to enable app developers to build apps that will connect to any SMART enabled system. The current version of SMART is built on HL7 FHIR. The use of FHIR simplifies SMART enablement of systems but limits the data available to SMART apps to that available in implemented FHIR profiles on the underlying system; and
**IHE Profiles API Specification** This provides specifications of the APIs for IHE.

**7.2.3 HL7 FHIR**

HL7 FHIR is worthy of special reference because of the attractiveness of this standard to developers and the interest it has generated in both the global and local informatics communities.

HL7 FHIR provides a REST API that can be implemented on any EHR system. FHIR provides a small number of definitions for common elements of clinical content (FHIR Resources) that it carries in a structured JSON payload. FHIR is well suited to the provision of a common open API on EHR systems in a way that does not require radical changes to the internal data structures of systems. It was designed as a messaging standard and
elegantly handles the common messaging requirements between systems.

HL7 FHIR is an important standard and any open platform implementation should support those FHIR profiles that have been adopted in the care community they cover. In the UK context this would be those FHIR profiles  developed by INTEROPen.

**7.3 Managing Content**

**7.3.1 Defining “Content”**

The term “content” (often called “clinical content) is used to describe the data elements that make up a health and care record and the metadata that supports them (for example, a blood pressure, an allergy, an assessment, a goal, etc.). These elements represent the health and care record in terms of data types, values, and terminology bindings.The elements must be computable, open and shareable. The methodology for defining clinical
content must support the entire lifecycle of content management, i.e. discovery --> creation --> peer-review --> publication --> maintenance.

**7.3.2 Sharing of Content - Facilitating long term Maintenance of Content**

Making metadata and content open and shareable not only facilitates interoperability but also allows the increasingly large and burdensome task of its creation and maintenance to be shared. Sharing the creation of clinical content will improve quality and reduce duplication of effort.

Sharing becomes even more important with the significant increase in the volume of content arising from the Internet of Things, Genomics, personalised medicine, decision support, data analytics, and population health. This will result in an explosive growth in the need for shared computable definitions of clinical content from less than 100 that approaches like FHIR are able to address to nearer 10,000.

This challenge of both content creation and ongoing maintenance requires new approaches and global cooperation.^13 Sharing perhaps represents the only way that this workload will be able to be handled.

**7.3.3 Sharing of Content - Stimulating innovation by app developers**

Having these elements of content is also key to enabling new app developers to innovate without becoming mired
in the complexities of health and care data. This is a clinical rather than technical challenge. This piece by Ewan Davis explains why clinicians rather than modellers should create clinical content, drawing on the  expertise of informaticians. The same applies in social care as it is practitioners not modellers who need to create and maintain content.

**7.3.4 Sharing of Content - Stimulating interoperability, and supporting scalability**

Current approaches to interoperability have had limited success, are not scalable beyond a small set of messages and APIs , and do not support the needs of new entrants to the market, particularly when these require novel content. The previous narrow focus on system interoperability will not support the emerging requirements which take us from a “messaging mentality” to what Thomas Beale describes as “pervasive semantics” in his blog here.

**7.3.5 Content Standards**

The following standards are potential candidates for the representation of clinical content within an open  platform:

**7.3.5.1 openEHR**

openEHR is the only currently available open standard^14 for the representation of fine-grained structured clinical content that is sufficiently mature and proven at scale. Thus, it is the only contender as the
standard for the storage of fine-grained computable data in an open platform.

openEHR has a well-established worldwide community along with a well-developed set of software tools for
creating and maintaining content. This puts openEHR in an excellent position to address the challenge of creating and curating of fine grained computable content at scale.

**openEHR has been adopted as a standard for the representation of clinical content in the Norwegian hospital sector and as a national standard in India, Slovenia and Brazil and is used for standards development in Australia, Finland, Sweden, Russia, Philippines and Canada.** openEHR has mature and open governance arrangements and an established global community ofI HE-XDS has been used to provide the NW
Shared Infrastructure Service LPRES

**7.3.5.2 IHE-XDS**

IHE-XDS is an open standard that provides a mechanism designed for the sharing of documents and images along with relevant metadata in a health and care environment. IHE-XDS provides standards for vendor neutral archive (VNA) in which data can be stored in open formats and a registry which stores metadata to facilitate data retrieval. Although primarily used for documents and images, it can be used for managing any type of
unstructured or semi-structured data. 


**7.3.5.3 IHE-XDS + openEHR**

IHE-XDS and openEHR work well together and this combination has been used successfully at scale in both Moscow and Slovenia. XDS handles unstructured and semi-structured data while openEHR handles fine-grained structured data with links between the openEHR clinical data repository and the XDS VNA enabling the creation of a seamless record.

This combination would seem to represent the most obvious target architecture where UK local health communities wish to create an open-platform.

**7.3.5.4 Terminologies and SNOMED CT**

Terminologies play an important part in the definition of clinical content and here the recognised standard is SNOMED CT although a platform may need to support other classification systems both to support legacy systems’ interfaces and use cases where SNOMED CT is not universally used (e.g. LOINC which is used by HL7 FHIR to code laboratory data). Ideally a platform should provide terminology services supporting standard terminologies and locally defined terminologies along with mechanisms to support mappings between them where this is relevant. Terminologies and classifications in addition to SNOMED CT that should be considered include:

- ICD9
- ICD10
- Read 2
- CVT3
- LOINC
- ICPC
- dm+d^19

clinicians, Informaticians and vendors coordinated by the not-for-profit openEHR Foundation based in London.  There are a number of proprietary implementations of the openEHR standard that have been deployed at scale^15 as well as a number of promising open source projects. Although created in London, there has been limited
use of openEHR in the UK with only a handful of small projects. However, this is beginning to change with the recent adoption of openEHR for important projects including Leeds^16 , Plymouth^17 and Genomics England^18

openEHR also provides the core of the NHS Digital supported Code4Health platform that provides a sandpit environment where developers and clinicians can learn about open platform principles and technologies, enabling them to experiment to build prototype applications.

**IHE-XDS is well supported by the vendor community and has been used at scale in many places both standalone and combination with openEHR.** In the UK, SNOMED CT will be the primary terminology used in a open platform.
However, there is not a consensus on the role SNOMED CT sshould play. In particular, the extent to which the use of post coordinated SNOMED CT expressions is either practical or desirable. There is a significant problem: policy makers who have attempted to mandate the use of SNOMED CT have little or no idea of its complexity.

However, the use of SNOMED CT primarily as a pre-coordinated terminology is relatively straightforward and
plays an important role in achieving interoperability.

**7.3.5.5 HL7 FHIR**

As is stated above (section 7.2.3) HL7 FHIR is an important standard primarily concerned with the specification of common open APIs for EHR systems and it should be supported by any open platform implementation.

However, while much clinical content can be satisfactorily represented by FHIR resources. FHIR is immature (HL7 formally describe it as a “Standard for Trial Use”) and it lacks the established methodology, community, governance and tooling to enable its use creating and curating of fine grained computable content at scale
and is not suitable as the prime means of representing clinical content in an open platform ecosystem.

FHIR was designed to support interoperability between systems and focuses on a small number of profiles
to support common interoperability requirements. It was not intended as a format for the storage of data within
systems or as a mechanism for large scale clinical content creation and curation.

It is proposed that clinical content development should focus on openEHR where the established methodology,
community, governance and tooling exist and that the output of this work is used in the creation of FHIR resources and profiles where these are required.This blog by Thomas Beale explains how FHIR and openEHR can work together.

**7.4 User Interface (UI) and User Experience (UX) standards and frameworks**

**7.4.1 Vision**

The vision of an open digital ecosystem is that any end user will be able to select a unique set of applications drawn from multiple vendors, where each applications will meet the end user’s unique needs, and where each application will work seamlessly together. The applications should be:

- Interoperable - Able to share relevant data between themselves;
- Orchestrated - Work together;
- Form-factor agile 
- Adapt their UI to the form-factor of the device they are used on; and
- UI/UX consistent - Operating with a common look and feel.

We make the case for open standards, components and frameworks at the UX/UI level of an open platform, very well aware of the generally poor level of usability in healthcare IT, mindful of the unnecessary cognitive load this puts on already busy clinicians at the frontline.

In the same way that stepping into a rental car generally results in the driver easily finding the common components required to steer, accelerate, brake, indicate, etc as they are placed in a highly consistent manner across the automotive industry, we believe there now is a compelling case for a common usability framework in
healthcare.

Attention to clinical safety is one of the bywords for good practice in modern healthcare and any inspection of the people/process/technology challenge when seeing the varied UX landscape across a typical healthcare environment quickly explains why we have the rate of medical errors that are so problematic today.

**7.4.2 Achieving the Vision**

Achieving this vision of an open digital ecosystem that has a consistent UX/UI is non-trivial. It requires the development of standards and frameworks that will support developers to build applications that achieve these objectives.

It is possible to draw analogies here from other sectors. For example the open source Wordpress content management system (CMS) provides a core “platform” which can be augmented with plug-ins
from multiple vendors (as of May 2017, there are over 50,000 Wordpress plugins) to create a unique website. By separating the UI components into “themes”, a site built with plugins from multiple vendors can be given a consistent UI/UX by applying an appropriate theme of which there are many thousands to choose from.

The ultimate aim is to see a number of such frameworks developed that provide similar capabilities for application developers in health and care. In the world of CMSs there are of course frameworks other than Wordpress, and the same can be expected in health and care.

**7.4.3 A starting point for a health and care frameworks...** 

There are a number of generic frameworks that can be used to create a consistent UI/UX. While these would require work to satisfy the full needs of health and care, they offer significant flexibility and could be augmented with specific health and care specific UI components. Frameworks of note include:

- Bootstrap;
- Angular JS;
- React;
- Semantic UI

What all of these frameworks have in common is that they are open source projects created by leading Internet
companies (Twitter, Facebook, Google and Pivotal) all of whom recognise that by open sourcing their tools they gain much more than they give away. These companies also recognise the need to do so in a way that allows commercial exploitation of the frameworks by others (each framework is released using a commercial friendly licence).

Some years ago there was some beautiful UX work done in the US as part of Health Design Challenge, which yielded a range of new UX ideas for healthcare. Some other related and relevant work within the NHS in England. This included the NHS Common User Interface (CUI) Project - This is work from the NPfIT. Whilst it is no longer maintained, it provides a starting point of good practice and principles.

While these efforts have explored new UX possibilities in healthcare, there is a paucity of open source UX/UI
frameworks that have been implemented for healthcare.To address this, the Ripple Foundation - (non profit organisation who are promoting an open integrated health and care platform compatible with the definition proposed in this document) have built and supported several related components including an open source
patterns & component based UX/UI framework called PulseTile which appears to be a leading example of the
way ahead.

# 8. Information Governance and Cyber Security

An open platform approach raises a number of issues and opportunities in relation to information governance and
cyber security.

There are increasing concerns with regard to the way personal health data is shared both for the direct care of the individual and for secondary purposes. The use of an open platform in and of itself does not mean either a more liberal or restrictive approach to information sharing. However, an open platform can provide facilities
make it easier to control and manage the sharing of information and the protection of patient privacy.

Many of the existing systems in health and care were designed when such systems would be hosted on-premise with
no connectivity beyond the physical estate of the organisation which they served. APIs on system (if they existed at all) were designed for the use of trusted developers working within the organisation and
certainly not to be exposed to a broader community of developers via the Internet. Such systems rely heavily on physical security for their cybersecurity.

Over recent years we have seen the growth of the Internet and increasing pressure from Government for tax-payer
funded services to take advantage of the cost benefits of cloud computing to open up their systems to innovation and new ways of working.

These changes promise considerable benefits, but with it go risks that need to be carefully managed.

There is also growing public concern about privacy, how their data is used and the control they have over it, which regulatory changes (notably the forthcoming General Data Protection Regulations (GDPR).

In particular, Article 20 of the GDPR stipulates the need for Data Portability, which has clear resonance with a push towards open standards in healthcare records. 

*The data subject shall have the right to receive the personal data concerning him or her, which he or she has provided to a controller, in a structured, commonly used and machine-readable format and have the right to transmit those data to another controller without hindrance from the controller to which the personal data has been provided.*

Finally, a cloud based open platform has the potential to create novel solutions that don’t easily fit well with existing regulatory frameworks (e.g. co-produced PHR and multi-organisational records under shared  overnance.)

An open platform approach can help address these challenges in a number of ways:

- By providing platform services to address a number of IG issues, thus relieving the application developer from the burden. E.g.
       - Identity assurance
       - Attribute based access control
       - Authentication
       - Federated consent management
       - Audit trails
- By providing protected gateways to underlying systems, removing much of the cyber security burden from them
- Facilitate legacy connectivity as described in section 6.6.
- By virtue of its open data format, easily satisfy the data portability requirement of GDPR

# 9. Minimum Viable Open Platform (MVP)

Here there is a lesson to be learnt from a related global initiative, known as openHIE, who are advocating a
standards based, implementable and interchangeable openHIE Architecture alongside key related open source reference technologies to craft a Minimum Viable Open Platform for health and care.

We believe this blend of open standards and open source to be the right way forward and recommend such an
approach to be adopted more widely. In the context of the healthcare market in the UK/Ireland/Europe, we believe a Minimum Viable open Platform (MVP) requires relatively few of the services described below. The essential elements are:

- Authentication services;
- Master Patient Index (demographic service);
- Service Directory (staff and services)
    and
- Clinical Data Repository (CDR) based on openEHR

So we simply endorse and extend the approach taken by openHIE towards a reference implementation of an open
platform architecture. In addition, we advocate, incorporating an additional key element i.e. an open standards (openEHR) based CDR, which is already being deployed around the globe..

In the UK, inidus has built the Code4Health Platform supported by NHS Digital. This is fully consistent with
the open principles outlined within this document, standing as a MVP of such an open platform. It has been made freely available to the developer community and has already proven a number of prototype applications.

A second notable MVP is that of the Ripple Foundation. This incorporates an open source UX/UI framework along with an open source integration framework on an open source openEHR Clinical Data Repository..

# 10. Implementing an Open Platform Ecosystem

**Delivering the vision of an open platform is not about creating a single instance of a platform, but rather it is about creating an open platform ecosystem where a number of platform providers compete for business with each other.**

There are various models that might emerge for the creation of an open platform ecosystem. These include:

- The establishment of an open health and care commons/marketplace for open platform oriented components and services. The 1% Open Digital Challenge Fund push across the UK and Ireland has already evidenced the appetite in the market for such a change. The Digital Square that is just emerging from the internationally leading PATH NGO, who lead on openHIE, is thought to be another leading example.
- Local health and care communities providing a platform instance for their populations. This model may well fit well within the UK context, with the Sustainability and Transformation Partnerships (STPs) areas being the starting point (in England). This mirrors the current approach taken by STPs for Integrated Digital Care Record
systems.
- Individual patients deciding where they want to store their health data and to whom they grant access. This is a patient-centric approach and mirrors emerging Personal Health Record (PHR) systems.
- A focus on a particular subset of patients, for example those with a specific disease. This mirrors current approaches with disease registries.

These models could be combined in various ways. There are also likely to be other candidate models. Some models
may result in data for the same individual being stored in multiple places. In this case, which can be understood as a federation of open platform instances, an ecosystem record locator service would enable applications to find the relevant platform instance to retrieve or store the individual’s data.

# 11. Conclusion, Recommendations and Next Steps

We suggest that efforts towards an open platform already underway across the NHS and the wider world have all the hallmarks of a grassroots movement for change and so suggest the following steps to catalyse the efforts of those stakeholders involved.

1. Establish a clinically led **working group** , initially across the UK & Ireland, to progress this mission, working to align community efforts towards the open platform goal worldwide. The healthcare open platform working
    group should involve representatives from healthcare organisations and suppliers.
2. Establish a **custodian** to maintain the definition of an open platform standard presented within this document and the standards adopted or created that flow from it. We suggest that we, the Apperta Foundation are well placed to assume this function.
3. Define and prioritise additional **platform services** that will add value to the open platform standard (those identified in section 6 and others identified by the community).
4. Identify and if need be develop open APIs for additional services based on the openAPI spec. We suggest that INTEROPen is one of number of key organisations that could proactively contribute to this work.
5. Establish a clinically led service for the development of **clinical content** definitions for the UK as part of an international collaboration based on openEHR and SNOMED CT Terminology. We suggest that the Professional Records Standards Body PRSB could perform this role within the UK.
6. Adopt and support the development of **open source components** towards a reference implementation of an open platfOrm to stimulate the global ecosystem.
7. Proactively engage key governmental bodies as key enablers in this change, who should seek to build out this infrastructure with related advocacy, support, resource and funding.
8. Progress the related 1% Open Digital Platform Challenge Fund mechanism across the UK, Ireland and beyond to further stimulate the market towards this open platform future for healthcare.

As the healthcare world faces unprecedented challenges and pressures, the move towards an open platform in
healthcare is already underway. While the international leaders in the field are forging ahead, the next wave of first followers have a crucial role to play to step up the pace of change.

This paper is aimed at providing some thoughts and suggestions to stimulate debate and connect the health and care community towards sharing ideas, integrated action, and building support to fulfill this mission.

We want your views, ideas, support and participation. You can comment here [http://openplatforms.apperta.org/](http://openplatforms.apperta.org/) or email admin@apperata.org

# 12. Acknowledgements

This work draws on the ideas and work of many people, but of particular note are those that have contributed directly to this document who include.

- Ewan Davis - Woodcote Consulting
- Dr Tony Shannon - Ripple Foundation
- Dr Ian McNicoll - openEHR Foundation
- Dr Roland Appel - Maycroft Consulting
- Silas Davis - Monax
- Dr Rebecca Wassall - Apperta Foundation
- Peter Coates - NHS Digital Code4Health

#### References

1. McKinsey and Co "How healthcare systems can become digital-health leaders" https://[http://www.mckinsey.com/industries/healthcare-systems-and-services/our-insights/how-](http://www.mckinsey.com/industries/healthcare-systems-and-services/our-insights/how-)healthcare-systems-can-become-digital-health-leaders
2. Data portability is a requirement of the forthcoming GDPR which many legacy systems will find difficult to meet. https://ico.org.uk/for-organisations/data-protection-reform/overview-of-the-gdpr/individuals-rights/the-right-to-data-portability/
3. Some digital pioneers supporting open platforms include: NHS Code4Health, Ripple Foundation, inidus
4. Large IT Companies and consultancies: McKinsey & Co, Accenture, CGI, Leidos5. National health systems: Norway, Russia, Brazil, Slovenia, India
6. [http://www.woodcote-consulting.com/defining-an-open-platform/](http://www.woodcote-consulting.com/defining-an-open-platform/)
7. Standards need to be open and agile and It should be noted that formal international
    standards ISO/CEN/BSI are not open nor is their creation and maintenance agile. See
    section 7 Standards for an Open Platform below.
8. Information models provide an unambiguous description of a piece of information
    (content), its structure and parameters, and how they are represented.
9. See for example link.
10. https://blog.softwareoperability.com/what-is-operability/
11. In this document, the term clinician is used as shorthand for the relevant frontline
    health or social care professional who is the domain expert with regard to a given
    standard. This might be a doctor, nurse, allied health professional, clinical scientist,
    social worker, care worker or other relevant professional. Similarly the term, clinical is
    used to refer to the relevant professional domain in health and care (as distinct from
    the technical domain).
12. GraphQL is a query language for APIs, and a server-side runtime for executing queries
    by using a type system to define the data source. It was initially created by Facebook in
    2012 and later released under the BSD open source licence, and has attracted a growing
    community of users and developers.
13. This blog by Thomas Beale estimates the size of the challenge and the effort required
    to create and maintain the required content. His figure is 4,000 definitions of clinical
    content for medicine only and as he states it excludes the impact of genomics and personalised medicine. His estimate does not include areas outside medicine (social care, criminal justice and education) which are involved in many new models of care, nor does he consider the impact of the Internet of Things
14. openEHR is conformant to ISO 18308 [http://www.openehr.org/releases/1.0.2/](http://www.openehr.org/releases/1.0.2/)
    requirements/iso18308_conformance.pdf and represents content using its’ archetype
    definition language (ADL) which is used in ISO 13606-2 [http://www.openehr.org/](http://www.openehr.org/)
    releases/1.0.2/architecture/am/adl.pdf
15. Moscow, where openEHR support all Health and Social care delivered by Moscow City
    Council to 12 million citizens , Slovenia, where openEHR provides a countrywide EHR
    for 2 million citizens
16. openEHR will power the Leeds Person Held Record for Leeds City Council
17. Plymouth Hospitals NHS Trust are presently implementing openEP (an open platform
    electronic prescribing and medicines administration system). The open platform will
    in due course support operation of other apps based on openEHR..
18. openEHR is used by North Thames Genomics to collect phenotypic data.
19. This is strictly a UK extension of SNOMED CT in the drug information domain where
    dm+d identifiers are SNOMED CT codes in the international namespace.

### Copyright Apperta Foundation CIC apperta.org

Published November 2017 with minor corrections April 2018


