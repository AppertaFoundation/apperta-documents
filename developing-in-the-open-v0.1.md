
# Developing in the Open

## Custodian Principles

** **

# 1.        Aims of this document

This document outlines the terms of engagement that should be met by those who aim to develop or support health and care solutions in partnership with the Apperta Foundation CIC.

The purpose of the instructions in this document is to ensure the long-term sustainability projects and to ensure that they remain unambiguously under the custodianship of the Apperta Foundation CIC on behalf of the public health service.

Adherence to these instructions helps ensure code quality standards and mitigate risk of reputational damage.

A fundamental Apperta principle is that digital assets are made available to a standard that enables organisations to transfer to alternative suppliers or products so that they remain in control and do not become subject to lock-in.

Apperta endorsed projects must be considered as a commitment to maintain and release assets and products openly for the entirety of the lifetime of the product, addressing the need to professionally implement patches and remedy defects with an appropriate frequency.

** ** 

# 2.        Community Custodian Responsibilities

## General principles

The Apperta community custodian role is managed through the Apperta subcommittees for each specific product. The community custodians have a number of key responsibilities that complement the role of the technical custodian and it is focussed on ensuring the product is useful, usable and safe. These responsibilities are outlined below.
* 1. The community custodian must take responsibility for the management of the product roadmap including sharing within the appropriate product community
* 2. The community custodian must review and manage suggestions and contributions from the community such new features and changes to the solution via issues or Pull Requests
* 3. The community custodian must maintain a simple list or directory of such supported apps and/or components with links to the Technical Custodians repository, project documentation, and URLs for demonstration purposes.
* 4. The community custodian must have a fork, clone, replica or snapshot of any/all code repositories at the point of completion of a project and/or ownership rights on the repositories containing any/all of the code.

# 3.        Technical Custodian Responsibilities

## General principles

Apperta will contract with one or many Technical Custodian Providers to deliver the principles described here. This includes the Product Management, Development Management and Repository Management.
* 1. Assets in scope of this agreement must adhere to the documented responsibilities contained within this document including;
  * a. Product management
  * b. Development management
  * c. Repository management
* 2. Activities must conform to the principles of the Apperta publication [Defining an Open Platform](https://apperta.org/openplatforms) and other Apperta published guidelines, adhering to using open standards as a basis for design and development
* 3. Projects must recognise  technical debt by evaluating and recording:
  * a. Technology choices
  * b. Requirement to rework code
  * c. Evolution of need since design
* 4. Projects must display the [Supported By Apperta badge](https://github.com/AppertaFoundation/apperta-image-assets/blob/master/supported_by_apperta_lores.png) where support has been provided by Apperta.

## Product management

* 1. A stable Gold Standard release of the Product must be provided.
* 2. To maintain Gold Standard endorsement, the product must:
  * a. Be approved by the relevant Apperta Subcommittee
  * b. Adhere to appropriate security and quality standards in line with guidance that Apperta will publish from time-to-time
  * c. Have all source code and releases publicly available in an Apperta agreed location
  * d. be DITO-conformant
* 3. A  pre-release Developer version should be available and the level of maturity must be stated (i.e. Concept, Prototype, Unstable, Active, Dormant)
* 4. Gold standard Products should have an unrestricted Demonstrator that:
  * a. Is accessible from the public internet through standard applications
  * b. Enables the full functionality to be evaluated by a potential user
  * c. Is linked to Code4Health™ Platform
  * d. Is maintained in line with current releases
  * e. Includes sample which should not contain any genuine identifiable (or practically re-identifiable) personal data
  * f. Can be available under subdomains of the apperta.org top level domain
* 5. Gold Standard Products should be available as an easy to execute, open standard image using standard execution methods including at least one of:
  * a. Virtual machine image
  * b.  A containerised package
  * c. Installable package (RPM, APT, exe, Flatpack, Snap)
  * d. Self-contained executable or script (exe, elf, sh, py, pl)
* 6. Products should have a mechanism to provide real time in-system feedback to an Apperta approved solution and/or location.

## Development management

* 1. Assets considered part of the &#39;Gold Standard&#39; release must be developed and released in an Apperta managed public repository
* 2. Developments must use a publicly accessible open standard VCS management tool (for example, Git, SVN, BZR)
* 3. Assets must be created and released under an [OSI-approved open source licen](https://opensource.org/licenses)[c](https://opensource.org/licenses)[e](https://opensource.org/licenses), agreed with the relevant Apperta subcommittee and unless licence compatibility requires otherwise should be one of the following:
  * a. AGPL
  * b.  MIT
  * c. Apache2
  * d. Mozzila
  * e.  Creative Commons (all variants)
  * f Open Government licence
* 4. Development should work toward achieving the NHS Digital managed DCB0129 Clinical Risk Management standard
  * a. Where development has been verified to this standard, the badge must be presented
* 5. Development should be conformant to Linux Foundation Projects Openchain Definition
  * a. Where and organisations development processes  have been assessed as conformant with the Openchain specification will be listed at [https://www.openchainproject.org/conformance](https://www.openchainproject.org/conformance) and the assessed badge must be displayed prominently
  * b. OpenChain conformance must be maintained in line with OpenChain specification requirements.
* 6. Products must be designed for portability and must not be designed for any one provider or platform
* 7. Products must be designed to be re-used within the sector and must not have artificial barriers to re-use
* 8. Developments must  avoid Passive Management by ensuring that code is:
  * a. Organised
  * b. Documented
  * c. The project process is open and transparent
  * d. Open to community challenge
* 9. Developments must  be subject to regular vulnerability scanning of all assets including 3rd party libraries at least monthly
  * a. This should operate as an automated process as part of a Continuous Integration (CI) function
* 10. Developments must adhere to coding standards applicable to the particular language
  * a. This should operate as an automated process as part of a Continuous Integration (CI) function
* 11. Developments must provide facility to track issues, ongoing developments and changes openly
  * a.  Issue management tools should be connected to the software repositories
* 12. Developments must be reviewed for contributions from the community such as Issues and Pull Requests.
* 13. Developments should create and maintain sample data to enable testers and users to reliably evaluate the product

## Repository management

* 1. Primary code repositories (Master) must remain under the direction of Apperta
* 2. Pull requests must be reviewed and commented or accepted or declined within 30 days
* 3. Branches of the primary repositories should be held by the Maintainer and must be merged with the Master:
  * 3.1 After every work package is complete
  * 3.2 After bug fixes or remedial work completed
  * 3.3 At least every month when routine work is carried out
  * 3.4 Within 14 days of a request by Apperta
* 4. Repositories must include the following files in plain text or Markdown format within the repository:
  * 4.1 Readme file to contain (or directions to the location of files containing):
    * i. An overview of the product
    * ii.  Installation instructions to enable a user to install and start the product
    * iii. Dependencies required to start the product
    * iv.  Version updates / changes
    * v. Technical debt register
    * vi. Copyright notice including all assets
    * vii. Attributions
    * viii. Reference to Changelog
    * ix. LICENCE file including a copy of the OSI approved licence
  * 4.2 The most recent version of the &#39;Apperta Foundation Disclaimer Notice&#39; , available here: [https://github.com/AppertaFoundation/apperta-documents/blob/master/apperta-disclaimer.md](https://github.com/AppertaFoundation/apperta-documents/blob/master/apperta-disclaimer.md)

** **

# Definitions

●       Community Custodian
●       Technical Custodian
●       Apperta: &quot;[The Apperta Foundation CIC](https://apperta.org/)&quot;
●       DITO: &#39;Develop In The Open&#39; principles and standard as detailed in this document
●       Product: A packaged software application comprised of Assets that delivers a process or processes to a user
●       Project: The activity of developing software to a specific outcome such as a product or asset, and including other technical and non-technical activities to arrive at such outcome
●       Development: the activity of creating or improving an existing product.
●       Solutions: Package of delivery of products with associated services (data, migration, on-boarding, feature development, support)
●       Repository: contains the code of a Product and supports the ongoing management of such product and is created through the Development activity.
●       Asset: Software, documentation, process or other digital component
●       Custodian: The role providing governance and control of assets and projects
●       Technical Custodian Provider (TCP): The role of providing, by contract, technical support and management services to Apperta
●       Adopt: The process where Apperta become the custodian of the asset or product
●       Technical Custodian / Maintainers - &quot;The individual, group of individuals, organisation, company, or other institution from which the original open source project was created&quot;
●       VCS: Version Control System - A tool to enable the tracking of code and changes to such code. A[lso known as RCS (Revision Control System) or SCM (Source](https://en.wikipedia.org/wiki/Version_control)Code Management)
●       CI: Continuous Integration - Automated processing of quality and functional tests when code is committed
●       Apperta Brand Assertion – i.e. supported by Apperta logo, Apperta named repository

** **

** **

# References

* [Exemplar text for repositories regarding reasonable expectations of the community for project and product support](https://github.com/ethercis/ethercis#productproject-support)

* [OSEHRA paper on licensing terms for open source healthcare applications](https://www.osehra.org/sites/default/files/osehra_licensing_terms_v.1.0.pdf)

* [The UK government&#39;s design principles and examples of how they&#39;ve been used.](https://www.gov.uk/guidance/government-design-principles)

* [Open Source Guides](https://opensource.guide/)

* [DCB0129 (formally SCCI0129) Clinical Risk Management: its Application in the Manufacture of Health IT Systems](https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb0129-clinical-risk-management-its-application-in-the-manufacture-of-health-it-systems)

* [Open Chain Conformance - Self-Certification](https://www.openchainproject.org/conformance)

* NHS Digital - Enterprise Architecture Policy, Coding in the Open

* Key words (Imperatives) to indicate intent from [https://tools.ietf.org/html/rfc2119](https://tools.ietf.org/html/rfc2119)