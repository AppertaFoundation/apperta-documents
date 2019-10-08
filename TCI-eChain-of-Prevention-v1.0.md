A Translational Clinical Informatics approach to deteriorating patient
care

Produced by and Copyright of Apperta Foundation CIC 2019. This
information is licensed under Creative Commons BY-SA-4.0. To view this
licence visit:
[[https://creativecommons.org/licenses/by-sa/4.0/]{.underline}](https://creativecommons.org/licenses/by-sa/4.0/)

[![](/media/image1.png){width="0.9166666666666666in"
height="0.3229166666666667in"}](https://creativecommons.org/licenses/by-sa/4.0/)

The authors of this document and first deteriorating patient workshop
team would like to dedicate this document to Master Aaron McCarter and
his brave family for their help in sharing his story to shape
developments in the care of seriously ill patients.

I would also like to thank my wife (Helen), family and those who have
been in my corner, unconditionally, for the first part of a journey to
transform development of safety critical information systems with open
standards.

To all those for which an integrated chain of prevention has been too
late, this work is the beginning of a movement for the integration of
deteriorating patient care across specialty silos and business systems
with open standards.

[Aim 4](#aim)

[Why this approach with digital health technology for deteriorating
patients?
4](#why-this-approach-with-digital-health-technology-for-deteriorating-patients)

[Scale of the problem: NCEPOD, NMR & NPfIT
4](#scale-of-the-problem-ncepod-nmr-npfit)

[Health IT: an improvement science & high reliability perspective
7](#health-it-an-improvement-science-high-reliability-perspective)

[Anatomy of rescue care: Rapid Response Systems & Chain of Prevention
8](#anatomy-of-rescue-care-rapid-response-systems-chain-of-prevention)

[Problems with deteriorating patient care - why does it *(still)* go
wrong?
10](#problems-with-deteriorating-patient-care---why-does-it-still-go-wrong)

[Role of family or carers in Chain of prevention v2.0
11](#role-of-family-or-carers-in-chain-of-prevention-v2.0)

[Processing information - an alternative paradigm for digital health
technology
11](#processing-information---an-alternative-paradigm-for-digital-health-technology)

[What does it do? A mechanism of action perspective on Health IT
12](#what-does-it-do-a-mechanism-of-action-perspective-on-health-it)

[Translational Clinical Informatics: A Code to Clinical Practice
Approach
13](#translational-clinical-informatics-a-code-to-clinical-practice-approach)

[Scoping system "structure, function & pathology" for Health IT
13](#scoping-system-structure-function-pathology-for-health-it)

[Building a Minimum Viable Prototype (not product!)
14](#building-a-minimum-viable-prototype-not-product)

[High Fidelity Simulation 14](#high-fidelity-simulation)

[Iterative development of operationally viable prototype before
procurement
15](#iterative-development-of-operationally-viable-prototype-before-procurement)

[Deployment for continuous improvement and change management
15](#deployment-for-continuous-improvement-and-change-management)

[Outcomes based accountability: measuring utility, usability &
use-affinity
15](#outcomes-based-accountability-measuring-utility-usability-use-affinity)

[Summary 16](#summary)

[Appendix 1: Scoping workshop facilitator guide
17](#appendix-1-scoping-workshop-facilitator-guide)

[Suggested outcomes for an eChain of prevention (eCOP) v2.0 workshop
17](#suggested-outcomes-for-an-echain-of-prevention-ecop-v2.0-workshop)

[eCOP v2.0 Workshop Agenda & Details
18](#ecop-v2.0-workshop-agenda-details)

[Guidance on conducting eCOPv2.0 TCI workshop & description of
deliverables
19](#guidance-on-conducting-ecopv2.0-tci-workshop-description-of-deliverables)

[Process Map: Monitoring - Communication - Response chains of eCOP v2.0
20](#process-map-monitoring---communication---response-chains-of-ecop-v2.0)

[TCI scoping template: ISBAR-NEWS 20](#tci-scoping-template-isbar-news)

[Acknowledgements 22](#acknowledgements)

[References 23](#references)

 

Aim 
----

The overall project aim is to establish a standardised approach to
knowledge transfer for digital transformation of rescue systems of care
throughout the healthcare industry. In contrast to current proprietary
approaches the project will be led by a collaborative consortium of NHS
trusts and industry partners. This work is enabled by a substantial
grant from Innovate UK and will utilise extensive patient and public
engagement to transform care of deteriorating patients by enabling more
effective and lower cost digital systems to better support professionals
in delivery of care. The community will use an open approach, support
scale and spread of a standardised electronic Chain of Prevention
(eCoP). It is intended that each organisation making use of the approach
outlined in this publication will provide feedback to support continuous
improvement and evolve the digital transformation projects for
deteriorating patients. This will help the system for digital
transformation take as much of an active learning approach to improving
the design and deployment of technology as the organisations do in
providing care.

This publication aims to provide a description of, rationale for and
guidance on the use of Translational Clinical Informatics methodology
for development and deployment of electronic health record technology to
improve deteriorating patient care.

Why this approach with digital health technology for deteriorating patients? 
-----------------------------------------------------------------------------

Deteriorating patient care is a public health problem for which the
development of interoperable and integrated digital solutions has been
lacking. Structure and processes of care for deteriorating patients are
ubiquitous, they could and should be standardised. This has not been the
case at a national level. From personal experience and literature review
organisations have found integration of similar systems, with
overlapping clinical function technically challenging and expensive.
Furthermore, projects that have been successful locally will not
necessarily be suitable for scale or spread without significant local
customisation. By curating a common understanding of the structure and
processes of care for deteriorating patients and the processing of
information by end users it is possible to create a national standard
for development and deployment of electronic health record technology to
support care of deteriorating patients. This approach allows a more
organised approach to one of the biggest clinical and socio-technical
challenges in 21st century medicine, the digitisation of health records
(1)

### Scale of the problem: NCEPOD, NMR & NPfIT

Over the last century healthcare has evolved dramatically. Both the
number and complexity of patients requiring hospital admission has
increased significantly. With advances in clinical practice the range
and severity of conditions that are survivable with acute care has kept
pace with these changing demographics. Cardiac arrest, both in and out
of hospital, has received intensive national attention and efforts to
treat patients in the last fifty years. In more recent years focus of
the acute care community has shifted from an emphasis on treatment of,
to the prevention of cardiac arrest (2). Despite the evolution of acute
care systems (3) failure to recognise and respond to deterioration is
persistent problem. Repeated confidential enquiries (4-10), national
audits and observational studies (11 - 19) report a significant
proportion of patients still experience suboptimal care prior to a wide
range of adverse clinical outcomes (ACOs) or serious adverse events
(SAIs) in addition to cardiac arrest. These outcomes include unplanned
ICU admission, emergency surgery, acute kidney injury and in patient
death. Most recently, the National Mortality Review programme and the
National Confidential Enquiry into Patient Outcome and Death (NCEPOD)
thirty years of learning report highlighted failure to rescue is a
serious and persistent problem (20, 21). With around sixteen million
emergency admissions to acute trusts each year in NHS England (22) even
a small fraction of potentially avoidable adverse clinical outcomes is
an enormous problem. As the population continues to expand and emergency
admissions continue to increase, deteriorating patient care is a serious
public health problem that requires high reliability approach to care.

Digital transformation is widely accepted as one of the ways in which
care providers can keep pace with the challenge of providing high
reliability care in an ageing NHS. Despite numerous potential benefits,
the NHS has been notoriously slow to support adoption of health
information technology. This latent digital inertia has been further
magnified by the highly flawed and failed National Programme for IT
(NPfIT) (1, 23). In the wake of NPfIT digital transformation attempts
have continued with both tier one vendors offering enterprise solutions
to a small number of trusts with large funds for capital expenditure and
smaller standalone systems for specific clinical processes. This
developed into a best of breed approach to achieving a single integrated
national EHR. From a deteriorating patient perspective a number of
systems that address operational problems such as patient flow,
electronic observations and task planning began to spread in acute
trusts. Over the last five years a number of papers on a range of topics
relevant to deteriorating patients have been published with headline
results of saving lives. Focus of these papers range from automation of
early warning scores (24-28), acute kidney injury alerts (29) to sepsis
alerts and machine learning algorithms (30, 31) to predict ACOs. Despite
the implicit potential of standalone digital record technology to
improve patient outcomes, the broader clinical community remains
disappointed with its impact. There remains a number of barriers to
adoption, some are clinical (use, usability etc.) some are technical and
some are transformational (scale of change to practices is difficult to
roll out without huge amounts of leadership support) and some of the
issues lie with interoperability (and all of the sub-context surrounding
that). Review of the recent evidence reveals a number of problems with
conflict of interests, methodological limitations and fixation of magic
bullet solutions for a complex but ubiquitous socio-technical problem.

Three broad challenges have been identified as critical to the success
of EHR technology (32, 23). Usability, interoperability and resistance
to process of care transformation have been identified a critical
contributors to the widespread failure of EHR technology to achieve its
expected potential impact on patient outcomes. Although the paper
highlighting this problem was published in 2013 the themes are
persistent as is highlighted by the establishment of organisations such
as Interopen and NHSX.

Whilst there are examples of localised successes published in the
popular media there is a real problem with scalability, spread and cost.
Recent evidence highlights the magnitude of investment required to
achieve performance gains. Although process adherence and patient
satisfaction improved organisational efficiency did not. This was
attributed to the large cost associated with EHR implementation. This
publication refers to a seven year period in which over \$30bn was
invested in North America (33). Whilst, at a high level, deteriorating
patient care is a very uniform process, digital transformation is not.
Not every organisation can afford the capital expenditure for an
enterprise wide EHR implementation from a tier one vendor with
sufficient digital maturity to deliver a multifunctional rapid response
system of care. This means each of the several hundred acute trusts and
commissioning groups and many thousand GP practices in NHS England are
looking to procure solutions at local level in settings with very
different levels of digital maturity. This wide range of digital
maturity means that feature and workflow expansion required for an
effective deteriorating patient system is delivered in heterogeneous
organisational contexts with various levels of digital processes and
systems (Figure 1). Furthermore, without a standardised and robust
approach to development and deployment of digital tools for
deteriorating patients there is significant potential to waste a large
amount of money, bit by bit, on small stand-alone solutions that are not
poorly integrated. The problem of integration and having an active
efferent limb is further highlighted by the move of many recent eObs
vendors to partner with or become bigger EHR providers.

Figure 1. Delivering electronic transformation of deteriorating patient
care in heterogeneous settings.

![](/media/image2.png){width="6.267716535433071in"
height="2.0416666666666665in"}

System development and deployment on a mix of different paper and
digital systems means that each implementation must draw clinical
information from an already established range of different or replace a
paper process. It can be appreciated from figure one that while each
business or speciality system and setting deals with a discrete use case
the underlying clinical information is essentially identical from a
conceptual perspective. Unfortunately, the clinical information recorded
on paper or stored electronically is highly mismatched. So when it comes
to integrating this information more horizontally, the new system must
reinvent a large fraction of clinical information that already exists in
each system but is not computationally identical. As this happens at a
local level and drives revenue, vendors are eager to customise to local
needs and engage with clinicians. Such proprietary packaging of medical
knowledge with local customisation is the main cause of poor semantic
interoperability. Limited interoperability causes vendor lock in that
stalls iteration and feature roadmap development with large upfront
costs that could have been avoided. This economic burden directly drives
the second factor contributing relative failure of EHR to effect
improvements in patient care at a national level. Problems with
usability are also highlighted by emerging concerns about EHR
contribution to physician burnout in America. Usability in the acute
setting is a complex challenge as clinicians have to contend with low
technology to user ratios, busy wards and the need to access, analyse
and author clinical information at or near the bedside. Process change
is essential if digital transformation is to improve outcomes for
patients that deteriorate in hospital. There are established
organisational barriers that limit horizontal team working across
settings and specialties. Electronic observations as a solution to
suboptimal deteriorating patient care is a prime example of this.
Improved Early Warning Score accuracy and automation still requires
ability to action alerts. Irrespective of c-Statistic there will
inevitably be an unavoidable increase in clinical workload from
optimising recognition of patient deterioration. Failure to adjust
people & process to optimise workflow around enhanced detection and
escalation of care will neutralise the benefits of enhancing afferent
limb performance in the new system of care.

In summary, there is a real population need for digital transformation
of deteriorating patient care. Digital transformation offers potential
to achieve a high reliability approach to recognition and rescue of
patient deterioration. However, efforts up to this point have not been
robust and reproducible from a clinical or cost effectiveness
perspective. Systems for deteriorating patient care are both ubiquitous
and standardisable. By taking a universal approach to development and
deployment of deteriorating patient systems key stakeholders will
address factors contributing to the relative failure of EHR technology
to help deliver the triple aim up to this point. The next sections
outline how improvement science supports system scoping for a
translational clinical informatics approach to developing and deploying
useful and usable systems with robust and reproducible process, outcome
and balancing measures.

### Health IT: an improvement science & high reliability perspective

Developing technology for deployment in complex systems requires a
rigorous understanding of the care pathways, social context and digital
landscape within an organisation. A single focus on mapping a workflow
fails to capture the complexity in which the application will be
deployed. Typical informatics discovery or business process mapping
tools tend to focus on small aspects of a complicated system. Building
related elements separately without a shared understanding of the bigger
picture creates barriers to horizontal integration of digital solutions
at a later point. While some patients may come to hospital under single
speciality and receive mono-speciality care along a specific workflow,
this is not usually the case. The patient journey cuts horizontally
across multiple specialties and silos within the organisation. While
semantic and pure technical interoperability of discrete systems is well
recognised, horizontal interoperability along the patient journey and
within the healthcare system is not. This can be considered as a
socio-technical interoperability problem. As digital maturity increases
or new technology evolves integration of separate systems around the
patient journey that were developed with a specific process in mind
becomes a much bigger problem. Combining an improvement science approach
to understanding the system with conventional approaches allows the
community to curate deeper and socio-technical insights that form the
basis for digital transformation of deteriorating patient care. The open
standards community believes considering socio-technical
interoperability early in the design phase improves future proofing in a
rapidly expanding field. Both Donabedian (33) and high reliability
system models (34) of care are particularly important to understanding
the structure and process of care. The NASSS framework provides critical
contextual insight into the interactions of a proposed technology and
its physical and social environment (35).

From a Donabedian perspective patient outcomes are determined by
structure and process of care (33). High reliability considerations view
structure and processes from those with a separate functions of routine
or planned and rescue systems of care. The focus is split between
minimising error by getting care right first time and resolving error or
rescuing the system when an error occurs (34). In the healthcare setting
routine and rescue systems are not thought of as completely distinct
elements. Structure & process for rescue systems of care are well
defined and discussed in more detail below. Most clinicians will be
familiar with these concepts as the getting it right, first time (GIRFT)
initiative and rapid response systems (RRS). High reliability systems
are also characterised by an open and active learning culture. This must
be incorporated into plans for digital transformation of deteriorating
patient care. Given the link to ACOs it is especially important that
such digital tools support an objective framework for both critical
appraisal of ACO antecedents and celebration of the ACOs avoided by the
team. The role of learning is acknowledged below with a description of
the chain of prevention.

As suggested above, routine systems of care are predetermined workflows
or clinical pathways organised around a specific specialty, disease or
clinical problem. Acute myocardial infarction, emergency laparotomy and
severe sepsis pathways are good examples. These systems operate well
when the condition frequently presents in an overt and readily
identifiable way. However, many patients either do not have a clear
diagnostic label or deteriorate while receiving a routine pathway of
care.

Rescue systems of care are designed to recognise evolving or established
life threatening organ dysfunction that precedes adverse clinical
outcomes such as death, cardiac arrest or unplanned critical care
admission. In some cases, such as acute kidney injury, the organ
dysfunction is the target condition and antecedents are more than
clinical signs on examination. Rescue systems of care are ubiquitous and
cross cutting systems that have been described in many ways. As this
project overall aim is to improve reduce of deteriorating patients,
anatomy of rescue care is described in more detail below.

Use of the NASSS (35) framework for eCOP will be explored as the project
progresses. It is likely there will be additional information added
based on learning from later development and deployment work.

Summary

-   Appreciate the system from a Donabedian & high reliability
    perspective - i.e. the patient journey not a silo or speciality
    workflow or setting

-   Sociotechnical interoperability of systems silos is improved when
    they are designed with the overarching view of SPO rescue systems.

-   Application NASSS framework will be tested.

### Anatomy of rescue care: Rapid Response Systems & Chain of Prevention

In 2006 the first international consensus conference on medical
emergency teams defined four elements of rapid response systems (RRS).
This was to unify the emerging concepts of rapid response teams,
critical care outreach and medical emergency teams. Conceptually, front
line elements of rapid response systems were described in terms of
linear afferent and efferent limbs for recognition and rescue of
deteriorating patients, respectively (3). Overarching governance and
case review elements were also described. More recent work used the
cardiac arrest chain of survival concept to present RRS components as
separate links in a chain of prevention (COP) that includes education,
monitoring, recognition, call for help and response (2).

In reality RRS span multiple structural, electronic, paper and human
elements that do not always form a neat feedback loop or linear chain
within a golden final six hours prior to an ACO. Clinical professionals
involved in rapid response systems of care varies considerably. Some
organisations have specific medical emergency teams or patient at risk
teams while other areas use critical care outreach teams to support
recognition and rescue of deteriorating patients. Furthermore, patient
populations served are very heterogeneous as RRS / COP span all
specialties and settings in healthcare.

For purposes of standardising digital transformation of deteriorating
patient care while maximising interoperability this work utilises the
chain of prevention concept. Despite their simplicity both RRS & COP are
useful concepts to describe a complex system. Both are generally based
around a vital sign generated early warning score (EWS) trigger with
escalation protocol and ABCDE based assessment for recognition and
response from a professional with a level of clinical competency that
matches acuity of the physiological trigger. One of the key areas not
well addressed in either of the descriptions above is the role of
communication and handover within and between teams over time. Patient
deterioration often progresses in a way that cuts across shifts,
specialities and even physical settings or sites. Communication within
and between teams is an essential element of a RRS or COP. This is
illustrated below with a modification to the chain of prevention
proposed by Smith (2). Version 2.0 of the Chain of Prevention contains a
communication ring that emphasises the flow and evolution of clinical
information is as important as the call for help in an established
crisis.

![](/media/image3.png){width="6.270833333333333in" height="2.65625in"}

Summary

-   Active learning system - celebrates & critically identifies &
    incorporates best practice

###  

### Problems with deteriorating patient care - why does it [*(still)*](#section-1) go wrong?

Design of digital health technology must consider underlying causes of
system failure. With deteriorating patient care system failure has
catastrophic consequences. Finding recurrent themes in complex systems
that can fail in an almost infinite number of ways is difficult. By
examining ACOs through a chain of prevention lens it is possible to
localise where the weak links are and examine why they fail. With over
30 years of NCEPOD reports, Observational studies and case record review
programmes several themes have been highlighted. At a system level there
are many problems not directly amenable to digital transformation. Acute
care is provided by consultant supervision of trainees for a high volume
of patients in time constrained setting. Furthermore the complexity of
patient acute illness and underlying comorbidity is increasing. Not only
are clinicians operating in time constrained settings they are operating
at or near and sometimes over capacity. The system factors contributing
to ACOs can be summarised as high volume, high velocity care for complex
patients at or over capacity. At a process of care level there are
multiple opportunities to improve care that are amenable to digital
transformation. Problems have been described with both monitoring and
response links while there are many problems with a lack of learning
from ACOs. Monitoring with early warning scores is an obvious process
that can be improved. But it must also be remembered that for many
health care professionals the EWS also serves as their recognition tool.
The NEWS2 iteration into an ABCDE format highlights the shift toward use
of vital signs as a recognition tool. From a recognition and response
perspective problems with deteriorating patient care can be condensed
into:

1.  Content of clinical assessment

2.  Cognition - bias and error

3.  Contingency plans

4.  Communication within and between teams

Content of clinical assessment: incomplete ABCDE note & NEWS chart is a
common finding in chart review of patients that experience adverse
clinical outcomes. This means assessment of patient condition or risk of
adverse event is incomplete. Much work has focused on NEWS. More recent
publications highlight the problem with ABCDE assessment and actions by
junior members of the team.

Cognitive bias and error frequently contribute to delays in recognition
& response to evolving or established serious / critical illness (37 -
44). It has not received much attention from RRS perspective and the
impact is often diluted by latent but accidental recovery processes.
This leads to a degree of redundancy and intrinsic dissonance in the
system toward causality over contribution & latent threat.

Contingency plans are often inadequate and fail to take into account
patient personalised risk

Communication between and within teams in space and time is a serious
challenge. The goal is to achieve common grounding / mutual
understanding between agents but a low signal to noise ratio and other
factors pervert the high fidelity flow and evolution of clinical
information (45).

Active learning is also an essential component of high reliability care.
Digital COP projects should consider integration of national mortality
review and human factors frameworks to facilitate optimal organisational
learning (16 - 18, 46).

### Role of family or carers in Chain of prevention v2.0

While rescue care processes traditionally focus on clinical team
performance there is evidence that family or carer involvement is not
only beneficial but essential for high reliability care. Often family
members or carers of patients that suffer an adverse clinical outcome
describe an uneasy and persistent visceral sensation that something is
not quite right despite reassurance that is often (unintentionally)
obstructive. Evidence from recent work on nurses worry (47) suggests
that family or carers recognise signs of evolving or established organ
dysfunction from serious illness but are unable to express (or be heard)
in a way or with vocabulary that matches the assessment construct used
by professionals. There are some questions around family initiated
escalation of care

1.  Are family and carers competent to escalate / communicate concern

2.  How do they escalate / communicate concerns?

3.  Who escalate / communicate concerns to?

4.  What if there appears to be persistent obstruction / avoidance in
    face of failure to improve?

There is no doubt that digital transformation could enhance family or
carer activation of RRS/COP. Unless this aspect is designed at an early
phase clinical performance and interoperability will be difficult to
build at a later stage.

### Processing information - an alternative paradigm for digital health technology

There is a poorly expressed distinction between providing information
for process of care or clinical workflows and processing information by
an end user to make decisions about care. The former is an attractive
option for decision makers and an easier target for vendors than the
latter. Optimising processing information is not solely about user
interface and experience. There are various ways in which processing
information at a single or multi-patient level can be enhanced.
Maximising processing of information should be recognised as a critical
function of all digital health technology let alone something as safety
critical as eCOP. Health care professionals process information in four
main ways in the conduct of care:

1.  A1: Access

2.  A2: Analysis

3.  A3: Authoring

4.  A4: Actioning

**A1:** Access to information is a core element of care. Defining who &
what is important in the care pathway for deteriorating patients.

**A2:** Analysis of information from multiple sources in a time
efficient and cognitive ergonomic format is the key to usability and
utility.

**A3:** Authoring forms an essential part of care management and
communication within and between teams. As discussed in more detail
below, there are considerations around how records support cognitive
synthesis and information hierarchy has a strong influence on UI real
estate and the process of common grounding.

**A4:** Actioning instructions and appreciation of process state is an
important part of care management and communication. Critical processes
often end up omitted because of problems in process state management.

Although clinicians process information in four main ways as outlined
above, understanding the purpose for processing information by an end
user is helpful in the user interface and features design of any digital
health technology. Health care professionals process information for
care or communication we events. Both care and communication events
require information processing for synthesis, state process monitoring
and sharing information for common grounding (45). Although purpose of
clinical information processing is very similar, the user interface and
features requirements can be considerably different.

1.  Clinical Care encounters

    a.  Synthesis & State process

        -   Diagnosis & dysfunction

        -   Tests & treatment

    b.  Shared understanding / Common Grounding

        -   Patient & family or carer understanding of

2.  Communication for handoff

    c.  Synthesis & State process

        -   New issues escalated / challenged

    d.  Shared understanding / Common Grounding

        -   MDT & shift changes

Both the above purposes must deal with presentation of, and interaction
with, large volume and variety of complex information to an end user.
There will also be an inherent structure and hierarchy that affects how
the information should be presented and interacted with. Further
consideration must be given to the variety of professionals processing
the information for these two broad and very different purposes. This
leads to consideration of rules for context based presentation and
features that support interaction with the clinical information.

### What does it do? A mechanism of action perspective on Health IT

One of the most noticeable problems during discovery for digital health
projects is that discussion often switches between content and features
without explicit awareness of the distinction and dependency of either.
This leads to difficulty in scoping and costly post deployment features
expansion. There is also a significant impact on usability as clinical
expectations for advanced functions to facilitate authoring, analysis or
action go unmet. Building on the information processing perspective it
is important to appreciate feature or function development f

Having a shared understanding of the basic mechanisms of action for
digital health technology will support more effective clinical
engagement between health care professionals and application architects.
There are four broad mechanisms by which digital health technology can
support processing of clinical information by healthcare professionals.

1.  TM1: Task management & automation / alerting

2.  TM2: Telemedicine / remote consulting

3.  DM1: Decision / cognitive support.

4.  DM2: Data mining / science & AI

**TM1**: Task management & automation / alerting - is one of the lower
hanging fruit in digital transformation but the underlying need to
curate and contextualise clinical information for a particular end user
is a difficult challenge. The flow and evolution of information must be
grounded with multiple actors in every patient's story at both low and
high levels of granularity.

**TM2**: Telemedicine / remote consulting - bringing the clinical
expertise to many patients electronically instead of physically has a
clear advantage.

**DM1**: Decision / cognitive support is already provided with paper
records. Using clinical noting templates to minimise diagnostic error is
a long-standing practice. Digital records have potential to support
cognition in a much more dynamic way. Usability and distinction between
primary and secondary use data is critical to avoid excessive data
collection burden during the clinical encounter. Clinical noting is a
medium for the integration and synthesis information critical to
diagnosis and treatment. Cognitive support could be regarded as passive
decision support. Active Decision support is an important feature but
requires clear information model and local engagement for process
triggers and action agreement.

**DM2**: Data mining / science & AI. Advanced analytics are promising
but, at the time of writing, have not yet penetrated front line digital
health technology. There are also ethical considerations around fair use
of special category data for research and development of a product that
will be sold back to the data subject in a way that could impact on
their right to access health care. Personalised risk prediction and hand
over are promising areas to explore application of these functions.

Translational Clinical Informatics: A Code to Clinical Practice Approach
------------------------------------------------------------------------

In the first section the relative failure of traditional digital
transformation projects was highlighted. Using the eChain of Prevention
as an example, an alternative paradigm for development and deployment of
digital health technology is discussed in this section. Given
similarities with pharmaceutical research and development methods, this
paradigm is discussed as a translational clinical informatics model.
Translational Clinical Informatics combines an improvement science
methods with iterative design and use of high fidelity simulation for
both development and deployment in complex adaptive systems such as RRS.

### Scoping system "structure, function & pathology" for Health IT

Using a high reliability lens to appreciate existence of routine and
rescue systems of care as a framework to understand the overarching
structure and process that can be improved for better outcomes. Rescue
care structure and elements of the chain of prevention span a number of
clinical processes that are considered discrete with traditional
informatics approaches. Functionally, each link in the chain of
prevention can be considered from a processing information perspective.
Both care and communication events are encompassed with the chain of
prevention and each has specific functional considerations. Pathology of
adverse clinical outcomes in terms of system failure are well
appreciated. Pharmacology or digital health technology mechanism of
action approach allows developers to target weak links in the chain of
prevention.

Figure 2. Structure & function approach to digital health technology
design

### ![](/media/image4.png){width="6.270833333333333in" height="2.125in"}Building a Minimum Viable Prototype (not product!)

Following exploration and development of a robust understanding of the
system as outlined above, design of a minimum viable prototype (MVP) for
iterative preclinical development is the next step. Clinical and
technical requirements specification of an eChain of Prevention MVP must
cover a set of minimum features for an afferent and efferent element
application and map potential links with various EHR Systems to maximise
future development as digital maturity increases.

Clinical requirements

-   Task Management / navigation

-   Event Schedule classes (1S & 2US)

-   Task-Patient-Device process

-   ISBAR framework / template for dynamic situation & background

-   Transcription / transfer of clinical action / assessment

-   IBSAR framework / template for recommendations: Analysis & Task
    planning

-   Event audit & edit

-   Master Physiology Event Timeline

EHR systems eCOP may need to link with.

-   General dependencies - enterprise wide systems e.g. PAS / MPI /
    Spine / Enhanced Prescribing Database

-   Education - incident reporting & review tools

-   Monitoring - observations & telemonitoring

-   Recognition - ABCDE clinical noting

-   Communication - hand off systems

-   Response - CPOE Systems

Developing an operationally viable product (OVP) by testing and
iteratively developing the MVP is the final step before deployment. The
use of high fidelity simulation to support this process is discussed
below.

### High Fidelity Simulation 

Many clinicians and other health care professionals recount their early
encounters with mission critical digital health tech as on the job
training. Yet airline pilots receive many hours training and redundant
live flight time when becoming familiar with new flight controls. High
fidelity simulation has potential for dual benefit to both development
and deployment phases of new digital health technology. From a
development perspective, one of the main problems with DHT is the
potential for a golden goose effect. Traditional design test build
deploy cycle has proven costly with post procurement "critical" feature
development that was overlooked early in the project. Recent evidence
highlights that it has taken \$30bn in America for EHR suppliers to
begin deployment of systems that have adequate usability. On the job
familiarisation with complicated software is not a safe or effective way
to deploy even a small standalone system. By extending the use of high
fidelity simulation into deployment phase there are additional benefits
to staff, from an organisational learning perspective. Learning how to
use new tools in a range of clinical scenarios optimises understanding
of the clinical system or problem that is being used for the simulation.

#### Iterative development of operationally viable prototype before procurement 

Even with the most fastidiously developed clinical specifications,
further insight into the structure and functions of eCOP will be gained
with high fidelity simulation based preclinical testing. With sufficient
spread of clinical scenarios it is possible to saturate how the tool
would be used by most people most of the time. Using traditional DBTD
leaves a much bigger gap for implementation that is usually filled with
a large number of requests for customisation. (48 - 51)

#### Deployment for continuous improvement and change management 

Using high fidelity simulation for deployment is not just good change
management, it has a potentially very useful unintended benefit on care
of deteriorating patients. As highlighted above the change management
process effectively becomes a complex multifaceted intervention that
supports core knowledge and competency development beyond use of
technology. Wright Singh Meeks (52, 53)

### Outcomes based accountability: measuring utility, usability & use-affinity

There are a variety of measures that can be used and misused in the
evaluation of digital health technology. As already highlighted above,
both the clinical problem and solution are not amenable to a traditional
evidence based medicine approach. By combining an improvement science,
Donabedian and information systems approach it is possible and more
robust to use a suite of measures in evaluating the impact of a digital
health technology (54, 55). The measures available are listed by
complexity, below.

-   **Counting**: Accuracy & adherence of afferent & efferent limb
    processes. Should include balancing measures around workload and
    alarm fatigue.

-   **Timing**: Score to door time, Trigger time or duration and
    frequency

-   **Outcomes**: MAELOR, 3rd Consensus conference on Medical emergency
    teams, CUMSUM charts for predicted mortality

-   **Quality of care**: Use of structured judgment review methods helps
    standardise review of care when explicit measures are not available.

-   **Quality of information system**: User acceptance testing, Delone &
    McLean, NICE digital health technology evidence framework.

-   **Cost effectiveness**: NICE DHT evidence framework

The overall method in which impact is measured is also important. Before
and after designs have significant methodological disadvantages. Use of
stepped wedge design methods in deployment has been reported and is a
pragmatic way to balance the constraints of complex systems with the
need for more robust evidence of effectiveness (56, 57)

As the project proceeds more detail on measures used and results
generated will be added.

Summary

-   Appropriate panel of measures for continuous improvement should
    include a variety of process and outcome measures.

Summary 
--------

Understanding the structure and process of care and problems within the
system supports enhanced design of digital health technology for
deteriorating patients. Using an iterative improvement science based
approach from code to clinical practice maximises the utility, usability
and user-affinity predeployment. This will optimise the clinical and
cost benefit of digital health technology deployed in a live healthcare
setting for seriously ill patients.

Appendix 1: Scoping workshop facilitator guide
----------------------------------------------

### Suggested outcomes for an eChain of prevention (eCOP) v2.0 workshop

-   Formalise a shared understanding of Rapid Response Systems and Chain
    of Prevention concepts as safety critical systems in preventing
    adverse clinical outcomes.

-   Consider chain of prevention failure from an information processing
    perspective.

-   Appreciate how generic functions of eHealth technology can support
    information processing to remediate failures in deteriorating
    patient care with an eChain of prevention.

-   Describe the use of high fidelity simulation for both iterative
    preclinical development and deployment to ensure innovation that is
    useful, usable and used.

###  

### eCOP v2.0 Workshop Agenda & Details

  ------------------------------------------------------------------- ------------------------------------------------------------------------------------
  **[Scoping for an eChain of prevention \[Outline\]]{.underline}**   
  0900 - 0930                                                         Registration, introductions & outline for common grounding
  0930 - 1015                                                         **Deteriorating patients: lessons from NCEPOD, NMR & NPfIT**
  1015 - 1045                                                         **Overview of eChain of Prevention & Translational Clinical Informatics Approach**
  1045 - 1100                                                         Instructions to group for workshop participation
  1100 - 1130                                                         Tea / Coffee
  1130 - 1230                                                         **First Solution Requirement group discussion - Process mapping the chain**
  1230 - 1330                                                         Lunch
  1330 - 1500                                                         **Second Solution Requirement group discussion - Structure, function & features**
  1500 - 1530                                                         Tea / Coffee
  1530 - 1700                                                         **Features roadmap discussion**
  ------------------------------------------------------------------- ------------------------------------------------------------------------------------

### Guidance on conducting eCOPv2.0 TCI workshop & description of deliverables

Introduction - What is it and why are we using it? An overview of the
holistic approach (add diagram from your presentation). eChain of
Prevention with details of what is described above.

Steps to follow during workshops;

1.  Structure, Process & Outcome

    a.  Consideration of problems with Deteriorating Care

    b.  Definition of adverse clinical outcomes

    c.  Structure of the chain of prevention & RRS

    d.  Process & macro (minimum) workflow

2.  Consideration of RRS / COP from an Information Processing mapped to
    4As & 4 main mechanisms of action

3.  Scoping ISBAR - NEWS tool

    e.  Content scoping for work on gap analysis in UK Clinical Models

    f.  Function, features & charts - UX/UI

4.  Discuss role of High Fidelity Simulation in development and
    deployment

#### Process Map: Monitoring - Communication - Response chains of eCOP v2.0

Observation (Low, Medium, High), this is equally applicable to apply
this approach for RESET, any acute care EHR technology. See separate
diagram.

#### TCI scoping template: ISBAR-NEWS 

<table>
<tbody>
<tr class="odd">
<td>Structure / Content</td>
<td>Function / features</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>Section</td>
<td>Element</td>
<td>Data</td>
<td>End user information Processing notes</td>
<td>e-Mechanisms of Action / features notes</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td>A1</td>
<td>A2</td>
<td>A3</td>
<td>A4</td>
<td>TM1</td>
<td>TM2</td>
<td>DM1</td>
<td>DM2</td>
</tr>
<tr class="even">
<td>ID (Patient / Professional)</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td>Situation</td>
<td>Precipitant</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>Background</td>
<td>Presenting</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>PM/D/PHx</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>Progress</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td>Assessment / Action - NEWS</td>
<td>All Vitals</td>
<td>NEWS</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>RR</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>SpO2 (Def)</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>SpO2 (Alt)</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>FiO2</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>HR</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>SBP</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>DBP</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>ACVPU</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>TEMP</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>NEWS</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>Recommendations</td>
<td>Assessment</td>
<td><p>Spec/</p>
<p>Grade/</p>
<p>Date/</p>
<p>Timing/</p></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>Intervention</td>
<td><p>A-E Class</p>
<p>T/T Class</p></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>Monitoring</td>
<td><p>NEWS</p>
<p>Other</p></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

#### 

Acknowledgements
----------------

This work draws on the ideas and work of many people, but of particular
note are those that have contributed directly to this document who
include.

-   Dr Alexander Davey - Translational Clinical Informatics Director,
    Digital Care Systems Limited & Consultant Anaesthetist, Belfast
    Health and Social Care Trust.

-   David Jobling - Product Lead, Apperta Foundation (CIC)

-   First Clinical requirements workshop team....

    -   Melissa McCarter - PPI lead (Northern Ireland).

    -   Nikki Holliday - Coventry University, Design Manager.

    -   Carol Anne - CCOT, Belfast Health and Social Care Trust.

    -   Deirdre Long - Lead Nurse Informatics, Belfast Health and Social
        Care Trust.

    -   Sarah Pitt - CCOT Belfast Health and Social Care Trust.

    -   Adrian Burke - CCIO, Cheshire and Wirral Partnership NHS
        Foundation Trust.

    -   Marjorie Goold - Consultant Nurse, Cheshire and Wirral
        Partnership NHS Foundation Trust.

    -   Nigel Miskell - Clinical Training Manager, Cheshire and Wirral
        Partnership NHS Foundation Trust.

    -   Shirley Birch - Clinical Lead Dementia Assessment Unit, Cheshire
        and Wirral Partnership NHS Foundation Trust.

    -   Jean Evans - Staff Nurse Dementia Assessment Unit, Cheshire and
        Wirral Partnership NHS Foundation Trust.

    -   Stephen Bell - Digital Care Systems Ltd.

    -   Gary Beckwith - Director, Gobby Ltd.

    -   Nawaf Al-Subaie - Consultant Intensive Care Medicine.

 

References
----------

1.  Justinia T. The UK\'s National Programme for IT: Why was it
    dismantled? Health Serv Manage Res. 2017;30:2-9.

2.  Smith GB. In-hospital cardiac arrest: Is it time for an in-hospital
    'chain of prevention'? Resuscitation 2010;81:1209 -- 1211.

3.  Devita MA, Bellomo R, Hillman K, Kellum J, Rotondi A, Teres D, et
    al. Findings of the first consensus conference on medical emergency
    teams. Critical Care Medicine. 2006; 34: 2463-2478.

4.  McQuillan P, Pilkington S, Allan A, Taylor B, Short A, Morgan G, et
    al. Confidential inquiry into quality of care before admission to
    intensive care. BMJ. 1998 Jun 20;316(7148):1853-8. Erratum in: BMJ
    1998 Sep 5;317(7159):631.

5.  Expert group on learning from adverse events in the NHS.
    Organization with a memory. London 2001

6.  An acute problem? A report by the National Confidential Enquiry into
    Patient Outcome and Death (2005)

7.  Emergency admissions: A journey in the right direction. A report by
    the National Confidential Enquiry into Patient Outcome and
    Death (2007)

8.  Perioperative care: knowing the risk. A report by the National
    Confidential Enquiry into Patient Outcome and Death (2011)

9.  Time to Intervene? A review of patients who underwent
    cardiopulmonary resuscitation as a result of an in-hospital
    cardiorespiratory arrest. A report by the National Confidential
    Enquiry into Patient Outcome and Death (2012)

10. Just Say Sepsis A report by the National Confidential Enquiry into
    Patient Outcome and Death (2015)

11. NELA project team. First patient report of the National Emergency
    RCoA London 2015

12. The International Surgical Outcomes Study group. Global patient
    outcomes after elective surgery: prospective cohort study in 27
    low-, middle- and high-income countries. Br J Anaesth 2016; 117 (5):
    601-609.

13. Moonesinghe SR, Harris S, Mythen MG et al. Survival after
    postoperative morbidity: a longitudinal observational cohort study.
    Br J Anaesth. 2014;113:977-84.

14. Garry DA, McKechnie SR, Culliford DJ, Ezra M, Garry PS, Loveland RC,
    et al. A prospective multicentre observational study of adverse
    iatrogenic events and substandard care preceding intensive care unit
    admission (PREVENT). Anaesthesia 2014;69:137-142.

15. Hogan H, Healey F, Neale G, et al. Preventable deaths due to
    problems in care in English acute hospitals: a retrospective case
    record review study. BMJ QualSaf 2012;21:737--45

16. Hutchinson A, Coster JE, Cooper KL, et al. A structured judgement
    method to enhance mortality case note review: development and
    evaluation. BMJ Qual Saf 2013;22:1032--1040.

17. Hogan H, Healey F, Neale G, Thomson R, Black N, Vincent C. Learning
    from preventable deaths: exploring case record reviewers\'
    narratives using change analysis. J R Soc Med. 2014;107:365-75.

18. Shah, A et al. Towards optimising local reviews of severe incidents
    in maternity care: messages from a comparison of local and external
    reviews. BMJ Qual Saf 2016;0:1-8.

19. Roberts AP, Morrow G, Walkley M, Flavell L, Phillips T, Sykes E, et
    al. From research to practice: results of 7300 mortality
    retrospective case record reviews in four acute hospitals in the
    North-East of England. BMJ Open Qual. 2017 24;6:e000123.

20. National Mortality Case Record Review (NMCRR) Annual report. In
    partnership with National Mortality Case Record Review
    Programme (2018)

21. National Confidential Enquiry into Patient Outcome and Death. Themes
    and Recommendations Common to all Hospital Specialities (2019)

22. [[https://www.nhsconfed.org/resources/key-statistics-on-the-nhs]{.underline}](https://www.nhsconfed.org/resources/key-statistics-on-the-nhs)
    accessed 30 September 2019

23. Magrabi F, Baker M, Sinha I, Ong MS, Harrison S, Kidd MR, Runciman
    WB, Coiera E. Clinical safety of England\'s national programme for
    IT: a retrospective analysis of all reported safety events 2005
    to 2011. Int J Med Inform. 2015;84(3):198-206.

24. Schmidt PE, Meredith P, Prytherch DR, Watson D, Watson V, Killen RM,
    Greengross P, Mohammed MA, Smith GB. Impact of introducing an
    electronic physiological surveillance system on hospital mortality.
    BMJ Qual Saf. 2015;24:176-7.

25. Dawes TR, Cheek E, Bewick V, Dennis M, Duckitt RW, Walker J, Forni
    LG, Venn R. Introduction of an electronic physiological early
    warning system: effects on mortality and length of stay. Br J
    Anaesth. 2014;113:603-9.

26. Bellomo R, Ackerman M, Bailey M, Beale R, Clancy G, Danesh V,
    Hvarfner A, et al; Vital Signs to Identify, Target, and Assess Level
    of Care Study (VITAL Care Study) Investigators. A controlled trial
    of electronic automated advisory vital signs monitoring in general
    hospital wards. Crit Care Med. 2012;40:2349-61.

27. Subbe CP, Duller B, Bellomo R. Effect of an automated notification
    system for deteriorating ward patients on clinical outcomes. Crit
    Care. 2017 14;21:52.

28. Bonnici T, Gerry S, Wong D, Knight J, Watkinson P. Evaluation of the
    effect of implementing an electronic early warning score system:
    protocol for a stepped wedge study. BMC Med Inform Decis Mak.
    2016;9;16:19.

29. Wilson FP, Shashaty M, Testani J, Aqeel I, Borovskiy Y, Ellenberg
    SS, et al. Automated, electronic alerts for acute kidney injury: a
    single-blind, parallel-group, randomised controlled trial. Lancet.
    2015 16;385:1966-74.

30. Churpek MM, Yuen TC, Winslow C, Meltzer DO, Kattan MW, Edelson DP.
    Multicenter Comparison of Machine Learning Methods and Conventional
    Regression for Predicting Clinical Deterioration on the Wards. Crit
    Care Med. 2016;44:368-74.

31. Kipnis P, Turk BJ, Wulf DA, LaGuardia JC, Liu V, Churpek MM, et al.
    Development and validation of an electronic medical record-based
    alert score for detection of inpatient deterioration outside the
    ICU. J Biomed Inform. 2016;64:10-19.

32. Kellermann AL, Jones SS. What it will take to achieve the
    as-yet-unfulfilled promises of health information technology. Health
    Aff. 2013;32(1):63-8.

33. Adler-Milstein J, Everson J, Lee SY. EHR Adoption and Hospital
    Performance: Time-Related Effects. Health Serv Res. 2015;50:1751-71.

34. Donabedian A. The quality of care. How can it be assessed? JAMA.
    1988 23-30;260(12):1743-8.

35. Sheridan TB. Risk, human error, and system resilience: fundamental
    ideas. Hum Factors. 2008;50:418-26.

36. Greenhalgh T, Wherton J, Papoutsi C, Lynch J, Hughes G, A\'Court et
    al. Beyond Adoption: A New Framework for Theorizing and Evaluating
    Nonadoption, Abandonment, and Challenges to the Scale-Up, Spread,
    and Sustainability of Health and Care Technologies. J Med Internet
    Res. 2017 1;19:e367.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

37. Graber ML, Kissam S, Payne VL, Meyer AN, Sorensen A, Lenfestey N.
    Cognitive interventions to reduce diagnostic error: a narrative
    review. BMJ Qual Saf. 2012;21:535-57.

38. Petersen JA, Mackel R, Antonsen K, Rasmussen LS Serious adverse
    events in a hospital using early warning score - what went wrong?
    Resuscitation. 2014; 85:1699-703.

39. Coulter Smith MA, Smith P, Crow R. A critical review: a combined
    conceptual framework of severity of illness and clinical judgement
    for analysing diagnostic judgements in critical illness. J Clin
    Nurs. 2014;23:784-98.

40. Padilla RM, Mayo AM. Clinical deterioration: A concept analysis. J
    Clin Nurs. 2018;27:1360-1368.

41. Gerrard C, Young D. Suboptimal care of patients before admission to
    intensive care is caused by a failure to appreciate or apply the
    ABCs of life support. British Medical Journal. 1998.

42. Callaghan A, Kinsman L, Cooper S, Radomski N. The factors that
    influence junior doctors' capacity to recognise, respond and manage
    patient deterioration in an acute ward setting: an integrative
    review. Aus Crit Care 2016 in press

43. Troels Thim, Niels Henrik Vinther Krarup, Erik Lerkevang Grove,
    Claus Valter Rohde, Bo Løfgren. Initial assessment and treatment
    with the Airway, Breathing, Circulation, Disability, Exposure
    (ABCDE) approach. Int J Gen Med. 2012; 5: 117--121. 5 Carling J. Are
    graduate doctors adequately prepared to manage acutely unwell
    patients? The Clinical Teacher. 2010;7:102-105..

44. Victoria R Tallentire, Samantha E Smith, Janet Skinner & Helen S
    Cameron. Understanding the behaviour of newly qualified doctors in
    acute care contexts. Medical Education 2011; 45: 995-1005. 

45. Flemming D, Hübner U. How to improve change of shift handovers and
    collaborative grounding and what role does the electronic patient
    record system play? Results of a systematic literature review. Int J
    Med Inform. 2013;82:580-92.

46. Higginson J, Walters R, Fulop N. Mortality and morbidity meetings:
    an untapped resource for improving the governance of patient safety?
    BMJ QualSaf 2012

47. Douw G, Huisman-de Waal G, van Zanten AR, van der Hoeven JG,
    Schoonhoven L. Nurses\' \'worry\' as predictor of deteriorating
    surgical ward patients: A prospective cohort study of the
    Dutch-Early-Nurse-Worry-Indicator-Score. Int J Nurs Stud. 2016
    Jul;59:134-40.

48. Dereck L. Hunt, MD; R. Brian Haynes, MD, PhD; Steven E. Hanna, MA,
    PhD; Kristina Smith. Effects of Computer- Based Clinical Decision
    Support Systems on Physician Performance and Patient Outcomes.
    JAMA., 1998;280:

49. Wright A, Aaron S, Sittig DF. Testing electronic health records in
    the \"production\" environment: an essential step in the journey to
    a safe and effective health care system. J Am Med Inform Assoc.
    2017;24:188-192.

50. Field LC, McEvoy MD, Smalley JC, Clark CA, McEvoy MB, Rieke H et al.
    Use of an electronic decision support tool improves management of
    simulated in-hospital cardiac arrest. Resuscitation. 2014 Jan;
    85(1):138-42.

51. Davey RUK poster

52. Singh H, Sittig DF. Measuring and improving patient safety through
    health information technology: The Health IT Safety Framework. BMJ
    Qual Saf. 2016;25:226-32.

53. Meeks DW, Takian A, Sittig DF, Singh H, Barber N. Exploring the
    sociotechnical intersection of patient safety and electronic health
    record implementation. J Am Med Inform Assoc. 2014;21:e28-34.

54. Scantlebury A, Sheard L, Watt I, Cairns P, Wright J, Adamson J.
    Exploring the implementation of an electronic record into a
    maternity unit: a qualitative study using Normalisation Process
    Theory. BMC Med Inform Decis Mak. 2017:7;17:4.

55. Nguyen L, Bellucci E, Nguyen LT. Electronic health records
    implementation: an evaluation of information system impact and
    contingency factors. Int J Med Inform. 2014;83:779-96.

56. Hemming K, Haines TP, Chilton PJ, Girling AJ, Lilford RJ. The
    stepped wedge cluster randomised trial: rationale, design, analysis,
    and reporting. BMJ. 2015;350:h391.

57. Brown CA, Lilford RJ. The stepped wedge trial design: a systematic
    review. BMC Med Res Methodol. 2006;8;6:54.
