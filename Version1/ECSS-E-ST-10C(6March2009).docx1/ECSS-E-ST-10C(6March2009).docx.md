-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Terms specific to the present
            standard](#terms-specific-to-the-present-standard)
        -   [The system engineering
            process](#the-system-engineering-process)
-   [Bibliography](#bibliography)

![](./media/image1.jpeg)

Space engineering

System engineering general requirements

**Foreword**

This Standard is one of the series of ECSS Standards intended to be
applied together for the management, engineering and product assurance
in space projects and applications. ECSS is a cooperative effort of the
European Space Agency, national space agencies and European industry
associations for the purpose of developing and maintaining common
standards. Requirements in this Standard are defined in terms of what
shall be accomplished, rather than in terms of how to organize and
perform the necessary work. This allows existing organizational
structures and methods to be applied where they are effective, and for
the structures and methods to evolve as necessary without rewriting the
standards.

This Standard has been prepared by the ECSS-E-ST-10C Working Group,
reviewed by the ECSS Executive Secretariat and approved by the ECSS
Technical Authority.

**Disclaimer**

ECSS does not provide any warranty whatsoever, whether expressed,
implied, or statutory, including, but not limited to, any warranty of
merchantability or fitness for a particular purpose or any warranty that
the contents of the item are error-free. In no respect shall ECSS incur
any liability for any damages, including, but not limited to, direct,
indirect, special, or consequential damages arising out of, resulting
from, or in any way connected to the use of this Standard, whether or
not based upon warranty, business agreement, tort, or otherwise; whether
or not injury was sustained by persons or property or otherwise; and
whether or not loss was sustained from, or arose out of, the results of,
the item, or any services that may be provided by ECSS.

Published by: ESA Requirements and Standards Division

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

Copyright: 2009 © by the European Space Agency for the members of ECSS

 Change log

  ------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ECSS-E-10A          First issue
                      
  19 April 1996       

  ECSS-E-10 Part 1B   Second issue
                      
  18 November 2004    

  ECSS-E-ST-10C       Third issue
                      
  6 March 2009        The main driver for the changes in this issue of the standard comes from the intention to include in this document only requirements and moving to an ECSS Handbook (ECSS-E-HB-10) all the informative material related to the process, in line with the ECSS Task Force \#2 recommendations.
                      
                      Consequently, the former clause 5 “System engineering process”, which contained a thorough description of a reference space system development process has been replaced by a brief overview of the project phases and related system engineering tasks in the current clause 6 “Overview of system engineering tasks per project phase”.
                      
                      Former Clause 4 has now been split into an introductory clause 4 “Overview of Systems engineering” and clause 5 “General Requirements”.
                      
                      The remaining requirements have been reworded for readability and consistency. Repetition of requirements included in other related standards have been eliminated.
                      
                      Regarding the documentation model, the only significant modification originates in the simplification of the concept of Functional Specification and Technical Specification, established in the previous issue of ECSS-E-10-06. In the new issue of ECSS-E-ST-10-06 only one specification, the technical requirements specification (customer specification), is considered. This is reflected in this standard, as explained in clause 5.2.3.1
                      
                      Other changes are explained below:
                      
                      -   Clause 2: Normative references
                      
                      > Extended and completed
                      
                      -   Clause 3: Terms, definitions and abbreviated terms
                      
                      > Includes additional definitions and abbreviated terms. In particular definition of the Technology Readiness Levels (TRL) has been added.
                      
                      -   Clause 4: Overview of system engineering
                      
                      > Includes the first clause of former clause four “The system engineering discipline”. A brief characterisation of the System engineering process has been added to this introductory clause.
                      
                      -   Clause 5: General requirements
                      
                      > The set of requirements initially contained in clause 4 of previous issue have been considerably restructured.
                      >
                      > Non mandatory requirements contained in previous issue have been eliminated, leaving only “mandatory requirements” or “shall” requirements.
                      >
                      > Descriptive text has been eliminated and it will be included in the System engineering handbook (to be published).
                      >
                      > The use of technology readiness level (TRL) is introduced in clause 5.6.7.
                      
                      -   Clause 6: Overview of system engineering tasks per project phase
                      
                      > This new issue contains high level requirements on the system engineering tasks to be complied with for each of the project phases.
                      
                      -   Annex A: System engineering documents delivery per review
                      
                      > This annex replaces and expands old annex B. It includes the listing of the main documents per phase of the project development indicating when the document needs to be available.
                      
                      -   Annexe B to Q: Document Requirements Descriptions (DRD)
                      
                      > This annexes include all the project documents pertinent to this standard. In the previous issue of the standard the DRDs were not included.
                      
                      -   Annex R: Mapping of typical DDP to ECSS documents
                      
                      > This is an addition with respect to the previous issue. It presents where specific subjects contained in the previously used Design and Development Plan are located in the new set of ECSS documents.
  ------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 Table of contents {#table-of-contents .Contents}

[Change log 3](#change-log)

[1 Scope 8](#scope)

[2 Normative references 10](#normative-references)

[3 Terms, definitions and abbreviated terms
11](#terms-definitions-and-abbreviated-terms)

[3.1 Terms from other standards 11](#terms-from-other-standards)

[3.2 Terms specific to the present standard
11](#terms-specific-to-the-present-standard)

[3.3 Abbreviated terms 14](#abbreviated-terms)

[4 Overview of system engineering 16](#overview-of-system-engineering)

[4.1 The system engineering discipline
16](#the-system-engineering-discipline)

[4.2 The system engineering process 20](#the-system-engineering-process)

[5 General requirements 21](#general-requirements)

[5.1 System engineering plan 21](#system-engineering-plan)

[5.2 Requirement engineering 21](#requirement-engineering)

[5.2.1 General 21](#general)

[5.2.2 Requirement traceability 22](#requirement-traceability)

[5.2.3 Requirement engineering process
22](#requirement-engineering-process)

[5.3 Analysis 24](#analysis)

[5.3.1 System analysis 24](#system-analysis)

[5.3.2 System environments and design and test factors
25](#system-environments-and-design-and-test-factors)

[5.3.3 Trade-off analyses 26](#trade-off-analyses)

[5.3.4 Analysis methods, tools and models
26](#analysis-methods-tools-and-models)

[5.4 Design and configuration 27](#design-and-configuration)

[5.4.1 Design 27](#design)

[5.4.2 Configuration 29](#configuration)

[5.5 Verification 29](#verification)

[5.5.1 General 29](#general-2)

[5.5.2 Product verification 29](#product-verification)

[5.6 System engineering integration and control
30](#system-engineering-integration-and-control)

[5.6.1 Management of system engineering activities
30](#management-of-system-engineering-activities)

[5.6.2 Planning 31](#planning)

[5.6.3 Engineering data 31](#engineering-data)

[5.6.4 Interface control 32](#interface-control)

[5.6.5 Coordinate systems and units 32](#coordinate-systems-and-units)

[5.6.6 Technical budgets and margin policy
32](#technical-budgets-and-margin-policy)

[5.6.7 Technology 32](#technology)

[5.6.8 Risk control 33](#risk-control)

[5.6.9 Changes and nonconformances control
33](#changes-and-nonconformances-control)

[6 Overview of system engineering tasks per project phase
34](#overview-of-system-engineering-tasks-per-project-phase)

[6.1 Overview 34](#overview)

[6.2 General 34](#general-3)

[6.3 Phase 0: Mission analysis-need identification
35](#phase-0-mission-analysis-need-identification)

[6.4 Phase A: Feasibility 35](#phase-a-feasibility)

[6.5 Phase B: Preliminary definition
35](#phase-b-preliminary-definition)

[6.6 Phase C: Detailed definition 35](#phase-c-detailed-definition)

[6.7 Phase D: Qualification and production
36](#phase-d-qualification-and-production)

[6.8 Phase E: Operations / utilization
36](#phase-e-operations-utilization)

[6.9 Phase F: Disposal 36](#phase-f-disposal)

[Annex A (informative) System engineering documents delivery per review
37](#__RefHeading___Toc223952979)

[Annex B (normative) Mission description document (MDD) – DRD
41](#__RefHeading___Toc223952980)

[Annex C (normative) System concept report – DRD
45](#__RefHeading___Toc223952981)

[Annex D (normative) System engineering plan (SEP) – DRD
46](#__RefHeading___Toc223952982)

[Annex E (normative) Technology plan (TP) – DRD
55](#__RefHeading___Toc223952983)

[Annex F (normative) Technology matrix - DRD
58](#__RefHeading___Toc223952984)

[Annex G (normative) Design definition file (DDF) - DRD
60](#__RefHeading___Toc223952985)

[Annex H (normative) Function tree - DRD
65](#__RefHeading___Toc223952986)

[Annex I (normative) Technical budget - DRD
67](#__RefHeading___Toc223952987)

[Annex J (normative) Specification tree - DRD
69](#__RefHeading___Toc223952988)

[Annex K (normative) Design justification file (DJF) - DRD
71](#__RefHeading___Toc223952989)

[Annex L (normative) Trade-off report - DRD
78](#__RefHeading___Toc223952990)

[Annex M (normative) Interface requirement document (IRD) - DRD
81](#__RefHeading___Toc223952991)

[Annex N (normative) Requirements traceability matrix (RTM) - DRD
83](#__RefHeading___Toc223952992)

[Annex O (normative) Requirements justification file (RJF) - DRD
85](#__RefHeading___Toc223952993)

[Annex P (normative) Product user manual (PUM or UM) - DRD
88](#__RefHeading___Toc223952994)

[Annex Q (normative) Analysis report – DRD
96](#__RefHeading___Toc223952995)

[Annex R (informative) Mapping of typical DDP to ECSS documents
98](#__RefHeading___Toc223952996)

[Bibliography 100](#bibliography)

Figures

[Figure 4‑1: System engineering functions and boundaries
18](#__RefHeading___Toc223952998)

[Figure 4‑2: System engineering functions and relationships
19](#__RefHeading___Toc223952999)

[Figure B-1 : Relationship between documents
42](#__RefHeading___Toc223953000)

Tables

[Table A-1 : System engineering deliverable documents
38](#__RefHeading___Toc223953001)

\
Scope
=====

This standard specifies the system engineering implementation
requirements for space systems and space products development.

Specific objectives of this standard are:

-   to implement the system engineering requirements to ensure a firm
    technical basis and to minimize technical risk and cost for space
    systems and space products development;

-   to specify the essential system engineering tasks, their objectives
    and outputs;

-   to implement integration and control of engineering disciplines and
    lower level system engineering work;

-   to implement the “customer-system-supplier model” through the
    development of systems and products for space applications.

This Standard is intended to apply to all space systems and product, at
any level of the system decomposition, including hardware, software,
procedures, man-in-the-loop, facilities and services. Through the
document and its annexes the requirements however apply as they are to
complex systems only; for lower level elements tailoring is necessary.

Specific requirements related to system engineering, like technical
specification, verification, and testing are specified in dedicated
documents and standards within the set of ECSS system engineering
standards ECSS-E-ST-10-XX.

Discipline or element specific engineering implementation requirements
are covered in dedicated ECSS standards. These standards are based on
the same principles, process and documentation model. The applicability
of each these standards can therefore not be considered in isolation
from the others.

ECSS-E-HB-10 “System engineering guidelines” contains guidelines related
to this standard, including a description of the reference system
engineering process for a space system and its products.

1.  1 The term “Discipline” is defined in ECSS-M-ST-10, as “a specific
    > area of expertise within a general subject”. The name of the
    > discipline normally indicates the type of expertise, e.g. in the
    > ECSS system mechanical engineering, software and communications
    > are disciplines within the engineering domain.

2.  2 The requirements on the system engineering process are gathered in
    > this standard; specific aspects of the SE process are further
    > elaborated in dedicated standards.

This standard may be tailored for the specific characteristic and
constrains of a space project in conformance with ECSS-S-ST-00.

\
Normative references
====================

The following normative documents contain provisions which, through
reference in this text, constitute provisions of this ECSS Standard. For
dated references, subsequent amendments to, or revision of any of these
publications do not apply, However, parties to agreements based on this
ECSS Standard are encouraged to investigate the possibility of applying
the more recent editions of the normative documents indicated below. For
undated references, the latest edition of the publication referred to
applies.

  ------------------------------------------------------ ---------------------------------------------------------------------
  ECSS-S-ST-00-01                                        ECSS system - Glossary of terms
  ECSS-E-ST-10-02                                        Space engineering – Verification
  ECSS-E-ST-10-06                                        Space engineering – Technical requirements specification
  ECSS-E-ST-10-09                                        Space engineering – Reference coordinate system
  ECSS-E-ST-10-24[]{#_Ref223158234 .anchor} [^1]^)^      Space engineering – Interface control
  ECSS-M-ST-10                                           Space project management – Project planning and implementation
  ECSS-M-ST-40                                           Space project management – Configuration and information management
  ECSS-Q-ST-20-10 Error: Reference source not found^)^   Off-the-shelf items utilization in space systems
  ------------------------------------------------------ ---------------------------------------------------------------------

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms from other standards
        --------------------------

For the purpose of this Standard, the terms and definitions from
ECSS-S-ST-00-01 apply, in particular for the following terms:

> **acceptance **
>
> **approval**
>
> **configuration baseline**
>
> **design**
>
> **development**
>
> **equipment**
>
> **inspection**
>
> **integration**
>
> **need**
>
> **performance** (see also ECSS-E-ST-10-06)
>
> **product tree**
>
> **requirement**
>
> **specification**
>
> **subsystem**
>
> **system**
>
> **test**
>
> **verification**

Terms specific to the present standard
--------------------------------------

1.  agreement

act of an authorized representative of an organization by which it
confirms satisfactory performance of specific services

1.  critical

characteristic of a process, process condition, parameter, requirement
or item that deserves control and special attention in order to meet the
objectives (e.g. of a mission) within given constraints

1.  design to cost

method of managing a project, which enables the project to be controlled
from its inception in order to meet defined performances within
pre-established objectives of cost and time

1.  integration

process of physically and functionally combining lower level products
(hardware or software) to obtain a particular functional configuration

1.  []{#_Ref211940749 .anchor}mission statement

document expressing the set of collected needs

1.  The mission statement is a document established by the customer,
    > which reflects the users needs, and is used as input to Phase 0 of
    > a space system project.

<!-- -->

1.  requirement traceability

requirement attribute that links each single requirement to its higher
level requirements inside the requirement set

1.  This enables the derivation of a requirement tree, which
    > demonstrates the coherent flow-down of the requirements.

<!-- -->

1.  recurring product

product which conforms to a qualified design and is produced according
to the corresponding production master file

1.  system engineering

interdisciplinary approach governing the total technical effort required
to transform a requirement into a system solution

1.  From IEEE P1220.

<!-- -->

1.  system engineering organisation

entity within a project team of a supplier which performs the system
engineering activities of the project

1.  For further details see clause 4.2.

<!-- -->

1.  system engineering process

set of inter-related or interacting activities, each transforming inputs
into outputs, to implement system engineering

1.  technical requirement

required technical capability of the product in terms of performances,
interfaces and operations

1.  These are requirements related to a product and not those related to
    > the process or management of the project or business agreement.

<!-- -->

1.  []{#_Ref211999481 .anchor}technology readiness level

achieved status of development of a technology

1.  TRL levels 1 to 9 are defined as follows:

  ------ ------------------------------------------------------------------------------------------------
  TRL1   Basic principles observed and reported
  TRL2   Technology concept and/or application formulated
  TRL3   Analytical and experimental critical function and/or characteristic proof-of-concept performed
  TRL4   Component and/or breadboard validated in the laboratory environment
  TRL5   Component and/or breadboard validated in the relevant environment
  TRL6   System/subsystem model or prototype demonstrated in the relevant environment (ground or space)
  TRL7   System prototype demonstrated in a space environment
  TRL8   Actual system completed and flight-qualified through test and demonstrated (ground or flight)
  TRL9   Actual system “flight-proven” through successful mission operations.
  ------ ------------------------------------------------------------------------------------------------

1.  verification matrix

initial issue of the VCD which contains for each requirement to be
verified the methods, levels and stages of product verification

1.  See ECSS-E-ST-10-02 for a more detailed definition of the VCD.

    1.  Abbreviated terms
        -----------------

For the purpose of this Standard, the abbreviated terms from
ECSS-S-ST-00-01 and the following apply:

  -------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Abbreviation   Meaning

  AIT            assembly, integration and test

  AIV plan       assembly, integration and verification plan

  AOCS           attitude and orbit control sub-system

  AR             acceptance review

  CDR            critical design review

  COTS           commercial off-the-shelf

  CRR            commissioning results review
                 
                 NOTE For space vehicles (e.g. launcher, transfer vehicle, crew transport vehicle) the CRR can be replaced or complemented by a flight qualification review (FQR).

  DDF            design definition file

  DDP            design development plan

  DJF            design justification file

  DRD            document requirements definition

  ECSS           European Cooperation for Space Standardization

  ELR            end-of-life review

  FDIR           failure, detection, isolation, recovery

  FM             flight model

  FMECA          failure modes, effects, and criticality analysis

  FRR            flight readiness review

  FTA            fault tree analysis

  GSE            ground support equipment

  ICD            interface control document

  ILS            integrated logistic support

  IRD            interface requirement document

  LRR            launch readiness review

  MCR            mission closed-out review

  MDD            mission description document

  MDR            mission definition review

  MOP            mission operations plan

  MS             mission statement

  ORR            operational readiness review

  PDR            preliminary design review

  PMP            project management plan

  PRR            preliminary requirement review

  PUM            product user manual

  QR             qualification review

  RAMS           reliability, availability, maintainability, safety

  RF             radio frequency

  RJF            requirement justification file

  ROD            review of design

  ROM/RAM        read only memory / random access memory

  RTM            requirement traceability matrix

  R&D            research and development

  SE             system engineering

  SEP            system engineering plan

  SFT            system functional test

  SRR            system requirement review

  SVT            system validation test

  TP             technology plan

  TRL            technology readiness level

  TS             technical requirements specification

  UM             user manual

  VCD            verification control document

  VP             verification plan

  w.r.t.         with respect to
  -------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.  \
    Overview of system engineering
    ==============================

    1.  The system engineering discipline
        ---------------------------------

System engineering is defined as an interdisciplinary approach governing
the total technical effort to transform requirements into a system
solution.

A system is defined as an integrated set of elements to accomplish a
defined objective. These elements include hardware, software, firmware,
human resources, information, techniques, facilities services, and other
support elements.

In this standard the concept of “system” is used in a wide sense. The
highest level, often called “mission level” or “space system”, consists
usually of one (or more) space segment(s), of a ground segment, and of a
user segment. Elements of system decomposition are also considered a
system. For the purpose of this standard the system can be any element
at any level of decomposition as defined by the function tree (see Annex
H) or the product tree (see ECSS-M-ST-10 Annex B). The scope of an
element can include hardware, software, procedures, man-in-the-loop,
facilities and services.

From the perspective of the considered system, requirements originate
from the next upper level (the customer) and elements are procured from
the next lower level (the suppliers).

1.  1 The customer-supplier model is described in ECSS-S-ST-00.

2.  2 Through this standard the notion of customer refers to several
    > actors ,in relation to the project phase. In fact a customer can
    > be e.g. a scientific community in phase 0, a commercial user in
    > phase A or an Agency in phase B. A supplier can on the other hand
    > be an Agency in both phase 0 and phase A.

Figure Overview of system engineering-1 shows the boundaries of the
system engineering discipline, its relationship with production,
operations, product assurance and management disciplines and its
internal partition into the following functions:

-   requirement engineering, which consist on requirement analysis and
    validation, requirement allocation, and requirement maintenance;

-   analysis, which is performed for the purpose of resolving
    requirements conflicts, decomposing and allocating requirements
    during functional analysis, assessing system effectiveness
    (including analysing risk factors); and complementing testing
    evaluation and providing trade studies for assessing effectiveness,
    risk, cost and planning;

-   design and configuration which results in a physical architecture,
    and its complete system functional, physical and software
    characteristics;

-   verification, which objective is to demonstrate that the
    deliverables conform to the specified requirements, including
    qualification and acceptance;

-   system engineering integration and control, which ensures the
    integration of the various engineering disciplines and participants
    throughout all the project phases.

Figure Overview of system engineering-2 shows system engineering
functions, their relationships and their main activities during the
system engineering process.

System engineering functions are applied in an iterative mode during
implementation of the system engineering process described in clause
4.2.

Within the frame of a project, the system engineering functions are
implemented by a system engineering organisation of the supplier which
is in charge of transforming the requirements of the customer into a
system solution delivered by the supplier.

1.  With respect to the next lower level, the supplier plays the role of
    > the customer.

[[[[[[[[[[[[[[[[]{#_1285683814 .anchor}]{#_1285683860
.anchor}]{#_1285741648 .anchor}]{#_1285784514 .anchor}]{#_1296888935
.anchor}]{#_1296900408 .anchor}]{#_1296900477 .anchor}]{#_1296900491
.anchor}]{#_1296901077 .anchor}]{#_1296972312 .anchor}]{#_1296972589
.anchor}]{#_1296973847 .anchor}]{#_1296987216 .anchor}]{#_1297608487
.anchor}]{#_1297608765 .anchor}]{#_1297609610 .anchor}

[[[]{#_Ref173810052 .anchor}]{#_Ref211942059
.anchor}]{#__RefHeading___Toc223952998 .anchor}Figure Chapter‑1: System
engineering functions and boundaries

[[[]{#_Ref173810088 .anchor}]{#_Ref211942167
.anchor}]{#__RefHeading___Toc223952999 .anchor}Figure Chapter‑2: System
engineering functions and relationships

The system engineering process
------------------------------

The system engineering activities of a project are conducted by an
entity within the project team of a supplier. This entity is called in
this document “system engineering organisation”.

The system engineering process consists of activities to be performed by
the system engineering organisation within each project phase. The
objective is to obtain a product which satisfies the customer technical
requirements within pre-established objectives of cost and time. The
requirements for these activities are described in clause 5.

The system engineering process is intrinsically iterative across the
whole life of a project, in particular in the initial phases (i.e. 0, A,
and B) of the development of a complex system (e.g. a spacecraft),
procured through a multilayered set of suppliers.

During these phases, the system engineering organisation derives design
oriented technical solutions using as an input the design-independent
customer requirements contained in a technical requirements
specification (TS). This is achieved through an iterative top-down
process by trading off several design solutions at increasing level of
detail.

1.  For definition and requirements for a technical requirements
    > specification see ECSS-E-ST-10-06.

Through this process the system engineering organisation performs a
multidisciplinary functional decomposition to obtain logical lower level
products (both hardware and software). At the same time the system
engineering organisation decides on balanced allocations, throughout the
system, of resources allocated by the customer and respects agreed
margin philosophies as a function of the relevant technology readiness
levels.

The system engineering process is in turn applied by each system
engineering organisation of each supplier of the elements of the product
decomposition.

The functional decomposition defines, for each level of the system, the
technical requirements for the procurement of subassemblies or lower
level products as well as the requirements for the verification of the
final characteristics of each product.

The system engineering process uses the results of these lower level
verification activities to build a bottom-up multilayered evidence that
the customer requirements have been met.

The system engineering process is applied with various degrees of depth
depending on the level of maturity of the product (e.g. new development
or off-the-shelf).

The system engineering process can be applied with different level of
tailoring as agreed between customer and supplier in their business
agreement.

The system engineering organization has interfaces with organizations in
charge of management, product assurance, engineering disciplines,
production, and operations and logistics.

1.  1 The system engineering process is defined in detail in
    > ECSS-E-HB-10 “System engineering guidelines”.

2.  2 The project phases are defined in ECSS-M-ST-10.

<!-- -->

1.  \
    General requirements
    ====================

    1.  System engineering plan
        -----------------------

        a.  []{#_Ref212011360 .anchor}The system engineering
            organization shall produce a system engineering plan (SEP)
            in conformance with Annex D.

        b.  The system engineering organization shall establish the SEP
            with the contributions and constraints of management,
            product assurance, engineering disciplines, production, and
            operations and logistics.

        c.  The system engineering plan shall relate to the lower level
            plans and ensure consistency between these plans.

<!-- -->

1.  1 The early version of the Project Management Plan (PMP), which
    > includes the early version of the SEP, contains all the
    > information which was traditionally contained in the Design and
    > Development Plan (DDP). See Annex R which illustrates the mapping
    > between a typical DDP and ECSS DRDs.

2.  2 The SEP content evolves with the phase of the project, with more
    > information on risk analysis and new technologies in early phases
    > 0, A and B, and more information on verification and validation
    > aspects in phases C, D

    1.  Requirement engineering
        -----------------------

        1.  ### General

            a.  The system engineering organisation shall analyse the
                requirements for the system issued by the customer.

<!-- -->

1.  This analysis enables transforming these requirements into a system
    > solution.

    a.  The system engineering organisation shall derive, generate,
        control and maintain the set of requirements for the lower level
        elements, defining their design and operational constraints and
        the parameters of functionality, performance, and verification
        necessary to meet the system requirements issued by the
        customer.

    b.  The system engineering organisation shall ensure consistency of
        the requirements at system level, at lower levels, as well as
        amongst levels[]{#_Ref173833946 .anchor}.

    c.  [[]{#ref173833946 .anchor}]{#_Ref212019915 .anchor}The system
        engineering organisation shall ensure conformance of each
        requirement with characteristics specified in ECSS-E-ST-10-06
        clause 8.

2.  Main characteristics are: traceable, unique, single, verifiable,
    > unambiguous.

    a.  []{#_Ref212870362 .anchor}The system engineering organisation
        shall ensure that each requirement for the lower level elements
        has a justification reflected in the requirement justification
        file in conformance with Annex O.

3.  This applies also to a standard as a whole. Tailoring of a standard
    > in a list of applicable standards, or of a requirement in an
    > applicable standard, is possible where each tailoring measure is
    > duly justified.

    1.  ### Requirement traceability

        a.  The system engineering organisation shall ensure forward and
            backward traceability of all requirements:

            1.  to their sources;

4.  For example: a higher level requirement, an imposed management
    > constraint, an applicable standard, an accepted lower level
    > constraint.

    1.  to the lower level requirements;

    2.  to changes in the design inducing modifications of the
        requirements;

    3.  to their verification close-out.

    <!-- -->

    a.  []{#_Ref173831531 .anchor}The system engineering organisation
        shall establish the requirements traceability matrix in
        conformance with Annex N.

    b.  The system engineering organisation shall ensure that the
        close-out traceability is documented in the VCD in conformance
        with ECSS-E-ST-10-02 Annex B.

    <!-- -->

    1.  ### Requirement engineering process

        1.  #### Technical requirements specifications

            a.  The system engineering organisation shall establish
                technical requirements specifications of the next lower
                level products consistent among them and with the
                technical specification received from the customer

            b.  The system engineering organisation shall ensure that
                the technical requirements specifications it establishes
                conform to ECSS-E-ST-10-06 and its DRD in Annex A.

            c.  []{#_Ref212018843 .anchor}The system engineering
                organisation shall establish for its own product and
                lower level ones a specification tree in conformance
                with Annex J.

            d.  In systems where the supply chain consists of at least 3
                layers (including the customer), the system engineering
                organisation of the highest level supplier shall define
                at the beginning of a project, a set of requirements
                specifications covering aspects common to more than one
                lower level product.

<!-- -->

1.  1 These “common” technical specifications have been historically
    > called support specifications (e.g. GDIR “General Design and
    > Interface Requirements”, environmental, test, EMC requirements
    > specifications) and are separated from other requirements
    > specifications addressing product specific characteristics and
    > functionalities.

2.  2 Requirements for equipment level products (or below) can be issued
    > in self contained specifications.

    1.  #### Requirement consolidation 

        a.  The system engineering organisation shall identify and
            resolve at the beginning of each project phase, incomplete,
            ambiguous, and contradictory requirements (with the customer
            for requirements issued by him).

        b.  The system engineering organisation shall reflect the
            consolidated requirements in updates of the specifications.

    2.  #### Requirement analysis

        a.  The system engineering organisation shall identify
            requirements impacting strongly on system risk.

        b.  [[]{#OLE_LINK4 .anchor}]{#OLE_LINK5 .anchor}The system
            engineering organisation shall perform the requirements
            analysis to the level of depth necessary to identify
            elements impacting on system risks.

    3.  #### Requirements verification methods

        a.  The system engineering organisation shall ensure that for
            each requirement contained in the technical requirements
            specification, one or a combination of verification methods
            are identified.

<!-- -->

1.  Technical requirements specification is defined in ECSS-E-ST-10-06
    > Annex A.

    a.  The system engineering organisation shall ensure that for each
        requirement contained in the technical requirements
        specification, the verification methods are reflected in the
        verification matrix.

2.  Technical requirements specification is defined in ECSS-E-ST-10-06
    > Annex A.

    1.  #### Requirement allocation

        a.  The system engineering organisation shall ensure that the
            system requirements (and their verification methods) are
            allocated to lower levels and included in the specifications
            of the related products.

    2.  #### Requirements consistency

        a.  The system engineering organisation shall verify that
            requirements are individually and globally consistent and
            non redundant.

        b.  The system engineering organisation shall verify that the
            lower level requirements are consistent with system
            requirements.

    3.  #### Requirements validation 

        a.  In phase 0 the system engineering organisation shall
            validate the requirements against the expressed needs
            together with the customer.

3.  For definition of “needs” see ECSS-E-ST-10-06.

    1.  #### Requirements maintenance

        a.  The system engineering organisation shall ensure that agreed
            changes to requirements are implemented in system and lower
            levels specifications.

        b.  The system engineering organisation shall exercise the
            maintenance during the system life cycle, down to end of the
            Phase F Mission Close-out Review.

    2.  #### Requirements baseline

        a.  The system engineering organisation shall establish the list
            of documents constituting the system requirements baselines
            in contribution to the configuration baselines.

4.  Details on configuration baselines are provided in ECSS-M-ST-40.

    1.  Analysis 
        ---------

        1.  ### System analysis

            a.  []{#_Ref174185209 .anchor}In phase 0 the system
                engineering organisation shall perform an analysis of
                the Mission Statement document, produce Mission
                Description document(s) in conformance with Annex B, and
                maintain this latter document for the final selected
                concept.[]{#_Ref173815267 .anchor}

            b.  []{#_Ref212018340 .anchor}The system engineering
                organisation shall perform a functional analysis,
                produce the functional architecture, and produce the
                function tree which satisfy the customer technical
                requirements specification, in conformance with Annex H.

            c.  []{#_Ref212870112 .anchor}The system engineering
                organisation shall document the functional architecture
                in the design definition file (DDF) in conformance with
                Annex G.

            d.  [[]{#_Ref212017253 .anchor}]{#_Ref212870225 .anchor}The
                system engineering organisation shall justify the
                functional architecture in the DJF in conformance with
                Annex K.

            e.  []{#ref212017253 .anchor}The system engineering
                organisation shall perform a physical analysis, produce
                the physical architecture and produce the product tree
                in conformance with ECSS-M-ST-10 Annex B.

            f.  []{#_Ref212870123 .anchor}The system engineering
                organisation shall document the physical architecture in
                the DDF in conformance with Annex G.

            g.  [[]{#_Ref173818812 .anchor}]{#_Ref212870231 .anchor}The
                system engineering organisation shall justify the
                physical architecture in the DJF in conformance with
                Annex K.

            h.  []{#_Ref212870235 .anchor}The system engineering
                organisation shall analyse the performances of the
                system, including end-to-end evaluation, documenting the
                results of the analysis in the Design Justification File
                in conformance with Annex K[]{#_Ref173837003 .anchor}.

            i.  The system engineering organisation shall analyse
                influence of mission, design, development, operations
                and constraints on cost and schedule as input to the
                project cost and schedule consolidation and to the
                utilisation recurring cost (design to cost).

            j.  []{#_Ref212870417 .anchor}The system engineering
                organisation shall ensure that any analysis is
                documented in an analysis report, in conformance with
                Annex Q.

        2.  ### System environments and design and test factors 

            a.  The system engineering organisation shall establish the
                influence of all types of environments applied during
                each life profile event on system and its elements in
                terms of nominal and extreme environmental conditions
                including all applicable operational phases.

            b.  The system engineering organisation shall establish the
                criteria for qualification and acceptance in conformance
                with Annex K of system and system elements for all types
                of environment.

            c.  The system engineering organisation shall ensure that
                analyses include design induced effects between system
                components or the system and its external environment
                and account for analysis uncertainties, in conformance
                with Annex K.

            d.  The system engineering organisation shall establish the
                design and test factors and margins applicable for
                design in conformance with Annex K.

<!-- -->

1.  1 Design factors are factors applied to specified loads to ensure
    > robustness of the design.

2.  2 Test factors are factors applied to specified loads to demonstrate
    > margins w.r.t. these loads (e.g. qualification / acceptance
    > factors).

    a.  The system engineering organisation shall establish environment
        conditions for product verification.

    <!-- -->

    1.  ### Trade-off analyses

        a.  The system engineering organisation shall conduct or
            consolidate trade-off analyses to:

            1.  assist in selecting system concepts, designs and
                solutions (including people, parts and materials
                availability);

            2.  support material selection and process decisions;

            3.  support make-or-buy and supplier selection;

            4.  examine alternative technologies to satisfy functional
                and design requirements;

            5.  evaluate environmental and cost impacts of materials and
                processes;

            6.  evaluate alternative physical architectures to select
                preferred products and processes;

            7.  establish the system and its configuration items;

            8.  analyze planning critical paths and propose
                alternatives;

            9.  select standard components, techniques, services and
                facilities that reduce system life-cycle cost;

            10. establish model and product verification philosophy for
                achieving qualification and acceptance objectives while
                considering testability;

            11. assess design capacity to evolve.

        b.  [[]{#_Ref173829251 .anchor}]{#_Ref212019559 .anchor}The
            system engineering organisation shall evaluate alternative
            concepts, designs and solutions against each other in a
            Trade-off report in conformance with Annex L.

        c.  []{#_Ref212005539 .anchor}The system engineering
            organisation shall document alternative system concepts
            considered during system trade-off studies in a System
            Concept Report in conformance with Annex C.

    2.  ### Analysis methods, tools and models

        a.  []{#_Ref212869989 .anchor}The system engineering
            organisation shall define the analysis methods and tools to
            be used during the product life cycle, as well as the
            related models and data exchanges between the tools, and
            document these in the SEP in conformance with Annex D.

        b.  The system engineering organisation shall ensure that
            analysis tools are validated.

        c.  The system engineering organisation shall ensure that
            analysis tools are maintained.

        d.  The system engineering organisation shall ensure that
            analysis tools are capable of exchanging and using models
            and data.

3.  1 For exchange of models and data, see ECSS-E-TM-10-20 and
    > ECSS-E-TM-10-21.

4.  2 Exchange can be either direct or via interfaces.

    a.  The system engineering organisation shall ensure that analysis
        tools are capable of transferring models and data for
        multi-disciplinary analysis.

5.  1 Details on product data exchange and system modelling and
    > simulation are provided in ECSS-E-TM-10-20 and ECSS-E-TM-10-21.

6.  2 Exchange can be either direct or via interfaces.

    a.  The system engineering organisation shall ensure that models
        produced by analysis tools are validated based on documented
        procedures and results.

    b.  The system engineering organisation shall ensure that modelling
        and test accuracy as well as limitations are considered (as part
        of Annex K) when establishing the performances and specifying
        environmental conditions for product verification.

    c.  The system engineering organisation shall ensure that models are
        kept operational for the lifetime of the product.

    <!-- -->

    1.  Design and configuration
        ------------------------

        1.  ### Design

            1.  #### General

                a.  The system engineering organisation shall establish
                    a design of the system from its functional
                    architecture, requirement allocation, and technology
                    selection.

<!-- -->

1.  This includes definition of the interfaces and corresponding ICDs.

    a.  []{#_Ref212870137 .anchor}The system engineering organisation
        shall ensure that the design addresses system aspects, covering
        its whole lifecycle, producing the physical architecture
        documented in conformance with Annex G and the product tree in
        conformance with ECSS-M-ST-10 Annex B.

    b.  []{#ref212870137 .anchor}The system engineering organization
        shall take into account the outcome of the design and
        verification activities of the lower level products.

    c.  The system engineering organisation shall ensure that the design
        covers hardware, software, and man in the loop.

    d.  The system engineering organisation shall ensure that the design
        is supported by analyses consistent with the level of maturity
        of the design.

    e.  The system engineering organisation shall ensure that all
        interface points with the production organisation are duly
        supported by communication, cooperation and provision of inputs
        between the two organizations.

2.  This relates to integration procedures and production master file.

    1.  #### Budgets

        a.  []{#_Ref223168098 .anchor}The system engineering
            organisation shall define and maintain all technical budgets
            of the system in conformance with Annex I in terms of
            target, current status and their trends.

        b.  The system engineering organisation shall apportion and
            control budget requirements to all levels of system
            decomposition.

        c.  The system engineering organisation shall apply the margin
            policy as defined in the SEP.

    2.  #### Design methods, tools and models

        a.  [[]{#OLE_LINK2 .anchor}]{#OLE_LINK3 .anchor}The system
            engineering organisation shall define the design methods,
            tools and related models to be used during the product life
            cycle and document them in the SEP.

        b.  The system engineering organisation shall ensure that design
            tools are validated and maintained.

        c.  The system engineering organisation shall ensure that design
            tools are capable of exchanging and using design models and
            data).

        d.  The system engineering organisation shall ensure that design
            models related to the product as documented in the final DDF
            and DJF are kept operational for the lifetime of the
            product.

        e.  The system engineering organisation shall ensure that design
            models produced by design tools shall are validated.

        f.  The system engineering organisation shall ensure that all
            design models refer to a coordinate system agreed with the
            customer and related to the project Coordinate System
            Document in conformance with ECSS-E-ST-10-09 Annex A with
            transformation methods as defined in ECSS-E-ST-10-09.

    3.  #### Design files

        a.  []{#_Ref212870145 .anchor}The system engineering
            organisation shall establish and maintain a design
            definition file in conformance with Annex G.

        b.  []{#_Ref212870254 .anchor}The system engineering
            organisation shall establish and maintain a design
            justification file in conformance with Annex K.

        c.  []{#_Ref173834641 .anchor}The system engineering
            organisation shall establish and maintain a product user’s
            manual (PUM) or user’s manual (UM) in conformance with
            Annex P.

3.  In case the product considered is a space segment, the Space Segment
    > User Manual defined in ECSS-E-ST-70 Annex E is generated with
    > support of the system engineering organization.

    1.  ### Configuration

        1.  #### Configuration content

            a.  []{#_Ref219882816 .anchor}The system engineering
                organisation shall ensure that the configuration
                includes the complete system functional, physical and
                software characteristics, budgets, interfaces and
                relationships between external and internal items.

            b.  The system engineering organisation shall ensure that
                the configuration includes all lower decomposition
                levels.

            c.  The system engineering organisation shall ensure that
                the configuration is documented in the DDF and in
                configuration definition documents.

4.  Details on configuration definition documents are provided in
    > ECSS-M-ST-40.

    1.  #### Configuration baselines

        a.  The system engineering organisation shall establish the
            system configuration baselines to be placed under control at
            defined project milestones.

5.  Details on system configuration baselines are provided in
    > ECSS-M-ST-40.

    1.  #### Configuration assembly constraints

        a.  The system engineering organisation shall define the
            hierarchy and assembly sequence of the system elements with
            the physical architecture.

        b.  The system engineering organisation shall document the
            hierarchy and assembly sequence of the system elements with
            the physical architecture.

    <!-- -->

    1.  Verification
        ------------

        1.  ### General

            a.  The system engineering organisation shall implement the
                product verification according to ECSS-E-ST-10-02.

6.  By implementing the product verification as per ECSS-E-ST-10-02 the
    > system engineering organisation defines the Verification Plan, as
    > specified in ECSS-E-ST-10-02 Annex A.

    1.  ### Product verification

        a.  The system engineering organisation shall ensure that the
            verification of the product is performed on the physical
            architecture as defined in the DDF.

        b.  The system engineering organisation shall assign the product
            to a verification product category, as defined in
            ECSS-E-ST-10-02 Table 5-1.

        c.  The system engineering organisation shall specify the
            configuration and environment conditions for product
            verification and the criteria for its qualification and
            acceptance.

        d.  The system engineering organisation shall confirm that all
            product verification objectives are achieved by analysing
            the results of the verification activities.

7.  This includes analysis of Verification Control Document and its
    > closeout documents, as defined in ECSS-E-ST-10-02 Annex B.

    a.  The system engineering organisation shall ensure that validation
        of systems with man-in-the-loop takes into account the man
        related limitations.

    b.  The system engineering organisation shall ensure that the
        verification covers the complete product including hardware,
        software, man in the loop, operations and representative mission
        scenarios (including pre-launch, launch and early orbit,
        in-orbit, post-landing, or other mission scenario).

<!-- -->

1.  1 The testing performed during and at the end of the integration of
    > a system is defined as System Functional Test (SFT).

2.  2 For system composed of different segments (e.g. space segment,
    > ground segment), the testing performed to ensure operability and
    > functionality of the complete system is defined as System
    > Validation Test (SVT).

    1.  System engineering integration and control 
        -------------------------------------------

        1.  ### Management of system engineering activities

            a.  The system engineering organization shall define, plan,
                and manage the integrated technical effort in accordance
                with the SEP and the previous clauses of this document,
                including quantification of this effort as input to
                management.

            b.  The system engineering organization shall set up the
                system engineering organization and interfaces in
                accordance with the system engineering plan.

<!-- -->

1.  For example: to customer, to lower levels, management, product
    > assurance, production, operations and logistics.

    a.  The system engineering organization shall initiate and control,
        in accordance with the SEP, the activities of engineering
        disciplines, of product assurance, of production, and of
        operations and ILS relevant for the achievement of its
        objectives.

2.  Examples of such activities are:

-   Engineering disciplines: mechanical and thermal;

-   PA: FMECA and RAMS;

-   Production: producibility;

-   ILS: operability, maintainability.

    a.  The system engineering organization shall make engineering
        decisions with the support and implementation of:

        1.  studies, trade-offs and analyses,

        2.  models, simulators, breadboards,

        3.  development activities,

        4.  technical optimisation efforts.

    b.  The system engineering organization shall ensure the
        availability of product and process data which enables the
        complete system to be produced, tested, delivered, operated,
        maintained, and properly disposed of.

    c.  The system engineering organisation shall establish a working
        link to the project configuration control to ensure that all
        binding changes resulting from engineering changes, dispositions
        and decisions are correctly picked- up and processed.

    d.  The system engineering organization shall ensure that the
        experience gained in past and in parallel activities is
        systematically considered.

    <!-- -->

    1.  ### Planning

        a.  The system engineering organization shall ensure that the
            SEP is in agreement with the project schedule.

1.  Details on the project schedule content are provided in
    > ECSS-M-ST-60, in particular the DRD Annex B.

    1.  ### Engineering data 

        a.  The system engineering organization shall define the
            engineering data to be stored in a data repository.

        b.  The system engineering organization shall ensure that
            engineering data can be exchanged in electronic form between
            the different organizations in charge of the elements of the
            product decomposition levels via agreed and validated
            interfaces.

    2.  ### Interface control

        a.  []{#_Ref219882843 .anchor}The system engineering
            organization shall control external interfaces as well as
            internal interfaces to the system by means of technical
            requirements specification in conformance with
            ECSS-E-ST-10-06 Annex A and interface control documents in
            conformance with ECSS-E-ST-10-24 Annex A.

<!-- -->

1.  1 The control of the external interfaces is performed in cooperation
    > with the parties involved in the interface.

2.  2 Interface requirements can be rolled-out of the technical
    > specification as interface requirements documents

    a.  []{#_Ref223168886 .anchor}When the interface requirements are
        rolled out in a self standing IRD, this document shall be in
        conformance with Annex M.

    b.  All interface requirements shall be accompanied by their
        verification requirements.

    <!-- -->

    1.  ### Coordinate systems and units

        a.  The system engineering organisation shall define the
            coordinate systems and related units in conformance with the
            Coordinate System Document DRD ECSS-E-ST-10-09 Annex A.

        b.  The system engineering organisation shall define the units
            system to be used during the product life cycle and document
            it in the SEP.

    2.  ### Technical budgets and margin policy

        a.  The system engineering organization shall control all
            technical budgets defined in conformance with Annex I.

        b.  The system engineering organization shall define the margin
            policy as applicable to the maturity level of the product.

<!-- -->

1.  Details are provided in the system engineering plan in Annex D
    > &lt;4.2&gt;b.5.).

    1.  ### Technology

        a.  []{#_Ref219882774 .anchor}The system engineering
            organization shall identify candidate technologies, and
            document them in the Technology Matrix in conformance with
            Annex F.

        b.  []{#_Ref219882745 .anchor}The system engineering
            organization shall ensure that the technologies proposed are
            assessed and confirmed in terms of availability and maturity
            (according to TRL levels defined in 3.2.12), and documented
            in the Technology Plan in conformance with Annex E.

        c.  The system engineering organization shall demonstrate
            supportability and feasibility within the defined industrial
            organization’s cost and schedule constraints.

    2.  ### Risk control

        a.  The system engineering organization shall contribute to the
            identification of the risk and of its mitigation measures.

        b.  The system engineering organization shall ensure the
            availability of engineering data and approaches in support
            of risk management.

2.  Details on risk management are provided in ECSS-M-ST-80.

    a.  The system engineering organization shall implement and control
        the elements of the risk management plan which are within system
        engineering responsibility.

    <!-- -->

    1.  ### Changes and nonconformances control

        a.  The system engineering organization shall provide a
            technical assessment on any change proposal to the baseline
            of the product.

        b.  The system engineering organization shall provide a
            technical assessment on any nonconformance to the status of
            the product.

        c.  The system engineering organization shall implement and
            control agreed actions.

<!-- -->

1.  1 Change is related to a request for deviation.

2.  2 Nonconformance is related to a request for waiver.

3.  3 The change procedure/control is defined as part of the
    > configuration management as defined in ECSS-M-ST-40.

<!-- -->

1.  \
    Overview of system engineering tasks per project phase 
    =======================================================

    1.  Overview
        --------

The allocation of specific system engineering requirements per phase
depends strongly on the type of business agreement established between
Customer and Supplier and the nature and level of complexity of the
system subject of the agreement. The breakdown and the details of the
tasks are defined in the business agreement specific documents.

1.  Some projects define them in a Statement of work (SoW).

The actors in the customer-supplier relationship change between phases
and across levels. In the following clauses each system engineering
organisation is meant to be the supplier’s system engineering
organisation during that phase.

1.  General
    -------

    a.  The system engineering organisation shall plan its activities in
        conformance with the project phases as defined by management.

<!-- -->

1.  The phases or combination thereof to be implemented for a project
    > are specified in the business agreement.

    a.  The system engineering organisation shall plan the system
        engineering activities for the considered project phases in
        accordance with ECSS-M-ST-10.

2.  This includes contribution to the associated reviews.

    a.  The system engineering organization shall monitor the execution
        of all system engineering activities including lower levels.

3.  For details regarding system engineering activities, see
    > ECSS-E-HB-10.

    a.  The system engineering organisation shall identify the critical
        elements.

    b.  The system engineering organisation shall ensure that for
        critical elements which are not at the next lower level, the
        technical requirements specification, the design definition file
        and the design justification file are available early in the
        project to control the project risk.

4.  Information regarding the expected delivery of system engineering
    > documents for each project review is provided in Annex A.

The documents to be approved by the customer as well as the time of
their approval are listed in the business agreement.

1.  Phase 0: Mission analysis-need identification
    ---------------------------------------------

    a.  The system engineering organization shall support the customer
        in identifying his needs.

    b.  The system engineering organization shall propose possible
        system concepts.

    c.  The system engineering organization shall support the MDR and
        ensure implementation of the MDR actions.

2.  Phase A: Feasibility
    --------------------

    a.  The system engineering organization shall finalise the
        expression of the needs identified in Phase 0.

    b.  The system engineering organization shall propose solutions
        (including identification of criticalities and risks) to meet
        the perceived needs.

    c.  The system engineering organization shall support the PRR and
        ensure implementation of PRR actions.

3.  Phase B: Preliminary definition
    -------------------------------

    a.  The system engineering organization shall establish the system
        preliminary definition for the solution selected at end of
        Phase A.

    b.  The system engineering organization shall demonstrate that the
        solution meets the technical requirements according to the
        schedule, the budget, the target cost and the organization
        requirements.

    c.  The system engineering organization shall support the SRR and
        PDR, and ensure implementation of the SRR and PDR actions.

4.  Phase C: Detailed definition
    ----------------------------

    a.  The system engineering organization shall establish the system
        detailed definition.

    b.  The system engineering organization shall demonstrate its
        capability to meet the technical requirements of the system
        technical requirements specification.

    c.  The system engineering organization shall support the CDR and
        ensure implementation of the CDR actions.

5.  Phase D: Qualification and production
    -------------------------------------

    a.  The system engineering organization shall finalize the
        development of the system by qualification and acceptance.

    b.  The system engineering organization shall finalize the
        preparation for operations and utilization.

    c.  The system engineering organization shall support QR and AR and
        ensure implementation of the QR and AR actions.

6.  Phase E: Operations / utilization
    ---------------------------------

    a.  The system engineering organization shall support the launch
        campaign.

    b.  The system engineering organization shall support the entity in
        charge of the operations and utilization following the terms of
        a business agreement.

    c.  The system engineering organization shall support the FRR, ORR,
        LRR, CRR, ELR, and recurring products AR, and ensure
        implementation of the actions of those reviews.

    d.  The system engineering organization shall ensure execution of
        all system engineering activities and provision of documents in
        support to anomaly investigations and resolutions.

<!-- -->

1.  Phase E and its reviews as presented in A.1.1.1.1&lt;1.1&gt;Table
    > 1.1 refer only to mission level. In case of lower level product,
    > activities to be considered by the system engineering organisation
    > are only related to maintenance and anomaly investigations.

    1.  Phase F: Disposal
        -----------------

        a.  The system engineering organization shall support the entity
            in charge of the disposal following the terms of a business
            agreement.

        b.  The system engineering organization shall support the MCR
            and ensure implementation of the actions of the MCR.

2.  Phase F and its review as presented in A.1.1.1.1&lt;1.1&gt;Table 1.1
    > refer only to mission level. In case of lower level product,
    > activities to be considered by the system engineering organisation
    > are only related to disposal.

<!-- -->

A.  [[]{#_Ref174176404 .anchor}]{#__RefHeading___Toc223952979
    .anchor}(informative)\
    System engineering documents delivery\
    per review

Scope of the Table 1.1 is to present relation of documents associated to
engineering activities to support project review objectives as specified
in ECSS-M-ST-10.

1.  This table constitutes a first indication for the data package
    > content at various reviews. The full content of such data package
    > is established as part of the business agreement, which also
    > defines the delivery of the document between reviews.

The table lists the documents generated by the engineering organization
necessary for the project reviews (identified by “+”), except for
verification documents, which are identified in Table G-1 of
ECSS-E-ST-10-02.

The various crosses in a row indicate the increased levels of maturity
progressively expected versus reviews. The last cross in a row indicates
that at that review the document is expected to be completed and
finalized.

For the SEP, DDF and DJF, the elements of these documents which are not
identified by a “+” in the table are not expected to be delivered for
the quoted review.

1.  All documents, even when not marked as deliverables in Table 1.1,
    > are expected to be available and maintained under configuration
    > management as per ECSS-M-ST-40 (e.g. to allow for backtracking in
    > case of changes).

Documents listed in Table 1.1 are either ECSS-E-ST-10 DRDs, or DRDs to
other ECSS-E-XX, ECSS-M-XX, or ECSS-Q-XX standards, or defined within
the referenced DRDs.

1.  []{#__RefHeading___Toc223953001 .anchor}: [[[]{#_Ref173841397
    .anchor}]{#_Ref173841446 .anchor}]{#_Ref174176520 .anchor}System
    engineering deliverable documents

  ------------------------------------------------------------------------ ----------------- ----------- --------- ---------- ----------- ----------- --------- --------- --------- ------- ------- ------- ------- ------- -------
  []{#RANGE!A1:P58 .anchor}Document title                                  ECSS document     DRD ref.    Phase 0   Phase A    Phase B     Phase C     Phase D   Phase E   Phase F

                                                                                                         MDR       PRR        SRR         PDR         CDR       QR        AR

  Mission description document                                             ECSS-E-ST-10      Annex B     **+**     **+**                                                  

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Specifications                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Preliminary technical requirements specification                         ECSS-E-ST-10-06   Annex A     **+**     **+**                                                  

  Technical requirements specification                                     ECSS-E-ST-10-06   Annex A     ** **                **+**                                       

  Interface requirements document                                          ECSS-E-ST-10      Annex M     ** **     **+**      **+**       **+**                           

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  System engineering plan                                                  ECSS-E-ST-10      Annex D     **+**     **+**      **+**       **+**       **+**     **+**     **+**

  Technology plan                                                          ECSS-E-ST-10      Annex E               **+**      **+**       **+**                           

  Technology matrix                                                        ECSS-E-ST-10      Annex F     ** **     **+**      **+**       **+**                           

  Verification plan                                                        ECSS-E-ST-10-02   Annex B     ** **     **+**      **+**       **+**       **+**     **+**     **+**

  AIT QM/FM plan                                                           ECSS-E-ST-10-03   Annex A     ** **                            **+**       **+**     **+**     **+**

  Orbital debris mitigation plan                                           ISO 24113                     **+**     **+**      **+**       **+**       **+**     **+**     **+**

  Other related plans\                                                                       ** **       ** **     **+**      **+**       **+**       **+**     **+**     **+**
  (as called in ECSS-E-ST-10 Annex D)                                                                                                                                     

  Coordinate system document                                               ECSS-E-ST-10-09   Annex A               **+**      **+**       **+**       **+**     **+**     

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Design definition file                                                   ECSS-E-ST-10      Annex G     ** **     **+**      **+**       **+**       **+**     **+**     

  Function tree                                                            ECSS-E-ST-10      Annex H     ** **     **+**      **+**       **+**                           

  Product tree                                                             ECSS-M-ST-10      Annex B     ** **     **+**      **+**       **+**                           

  Specification tree                                                       ECSS-E-ST-10      Annex J     ** **     ** **      **+**       **+**                           

  Technical budget                                                         ECSS-E-ST-10      Annex I     ** **     **+**      **+**       **+**       **+**     **+**     **+**

  Preliminary technical requirements specifications for next lower level   ECSS-E-ST-10-06                         **+**      **+**                                       

  Technical requirements specifications for next lower level               ECSS-E-ST-10-06                                    **+**       **+**                           

  Design definition file for next lower level                                                                                             **+**       **+**     **+**     **+**

  Interface control document                                               ECSS-E-ST-10-24   Annex A     ** **     ** **      **+**       **+**       **+**     **+**     **+**

  Product User manual / User Manual                                        ECSS-E-ST-10      Annex P     ** **     ** **      ** **                   **+**     **+**     **+**

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Design justification file                                                ECSS-E-ST-10      Annex K     ** **     **+**      **+**       **+**       **+**     **+**     

  Requirements traceability matrix w.r.t. next lower level                 ECSS-E-ST-10      Annex N     ** **     **+**      **+**       **+**                           

  Requirement justification file                                           ECSS-E-ST-10      Annex O     **+**     **+**      **+**       **+**                           

  System concept report                                                    ECSS-E-ST-10      Annex C     **+**     **+**                                                  

  Trade off reports                                                        ECSS-E-ST-10      Annex L     **+**     **+**      **+**       **+**       **+**               

  Verification control document                                            ECSS-E-ST-10-02   Annex C     ** **     **+(1)**   **+(1) **   **+(1) **   **+**     **+**     **+**

  Test specification                                                       ECSS-E-ST-10-03   Annex D     ** **     ** **      ** **       ** **       **+**     **+**     **+**

  Analysis report                                                          ECSS-E-ST-10      Annex Q     ** **     **+**      **+**       **+**       **+**     **+**     **+**

  Mathematical model description                                                                         ** **     ** **      **+**       **+**       **+**     **+**     ** **

  Correlation report                                                                                     ** **     ** **      ** **       ** **       **+**     **+**     ** **

  Test procedure                                                           ECSS-E-ST-10-03   Annex C     ** **     ** **      ** **       ** **       **+**     **+**     **+**

  Test report                                                              ECSS-E-ST-10-02   Annex D     ** **     ** **      ** **       ** **       **+**     **+**     **+**

  Verification report                                                      ECSS-E-ST-10-02   Annex H     ** **     ** **      ** **       ** **       **+**     **+**     **+**

  Design justification file for next lower level                                                         ** **     ** **      ** **       ** **       **+**     **+**     **+**

  Review of design report                                                  ECSS-E-ST-10-02   Annex F     ** **     ** **      ** **       ** **       **+**     **+**     ** **

  Inspection report                                                        ECSS-E-ST-10-02   Annex G     ** **     ** **      ** **       ** **       **+**     **+**     **+**

  GSE specifications                                                                                     ** **     ** **      ** **       **+**       **+**     **+**     **+**

  GSE Data packages                                                                                      ** **     ** **      ** **       ** **       **+**     **+**     **+**

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Other documents                                                                                        ** **     ** **      ** **       ** **       ** **     ** **     ** **

                                                                                                                                                                          

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

                                                                                                         ** **     ** **      ** **       ** **       ** **     ** **     ** **

  Note (1) : Document limited to the verification matrix
  ------------------------------------------------------------------------ ----------------- ----------- --------- ---------- ----------- ----------- --------- --------- --------- ------- ------- ------- ------- ------- -------

A.  []{#_Ref173838392 .anchor} []{#__RefHeading___Toc223952980
    .anchor}(normative)\
    Mission description document (MDD) – DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1cc.

1.  Purpose and objective

The objective of the mission description document (MDD) is to provide
input for the later selection of the best concept meeting the mission
statement (MS) in iteration with the preparation of the preliminary
technical requirements specification (TS) (as defined in ECSS-E-ST-10-06
Annex A).

It is prepared in Phase 0 and Phase A for each possible concept, as
indicated in requirement cc.

Links and chronology amongst the MS, TS, MDD, system engineering plan,
project management plan and system concept report are provided on the
Figure 1.1.

The MDD is produced by system engineering organization of the mission
responsible (typically an Agency or other institutional actors ) ) and
defines a concept that aims at satisfying the preliminary technical
requirements specification, and presents how the objectives, operation
profile, major system events and capabilities, contingencies and
performance standards are expected to be achieved.

For each mission concept, the MDD is a complete description of that
concept. And to each MDD a SEP evaluating the related system engineering
effort and a report evaluating the related programmatic aspect are
associated.

The system concept report assesses the different concepts from a
technical, programmatic and risk point of view, includes a trade-off
including weighting factors which bears some management aspects,
followed by a system concept selection.

[[[[[[[[[[[[[[[[]{#_1285746861 .anchor}]{#_1285784518
.anchor}]{#_1289547096 .anchor}]{#_1289547116 .anchor}]{#_1289722908
.anchor}]{#_1289750752 .anchor}]{#_1289900838 .anchor}]{#_1289909795
.anchor}]{#_1289909888 .anchor}]{#_1289912023 .anchor}]{#_1296888938
.anchor}]{#_1296972591 .anchor}]{#_1296973850 .anchor}]{#_1296987218
.anchor}]{#_1297608489 .anchor}]{#_1297609612 .anchor}

1.  []{#__RefHeading___Toc223953000 .anchor}: []{#_Ref174177235
    .anchor}Relationship between documents

<!-- -->

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The MDD shall contain a description of the purpose,
            objective, content and the reason prompting its preparation
            (e.g. logic, organization, process or procedure).

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The MDD shall list the applicable and reference documents in
            support to the generation of the document, and include, as a
            minimum, the current preliminary technical requirements
            specification.

        <!-- -->

        1.  Preliminary technical requirements specification summary

        <!-- -->

        a.  The MDD shall provide a summary of the preliminary technical
            requirements specification objectives and list the design
            driving requirements, derived from the current initial
            specification.

        <!-- -->

        1.  Concept description

        <!-- -->

        a.  The MDD shall provide:

            1.  Overview of the concept

            2.  Mission analysis

            3.  System description, element by element

<!-- -->

1.  For example: For a spacecraft, its ground control segment, and a
    > user segment, e.g.

Space Segment

-   Payload

-   Platform

-   Launch Vehicle

-   Orbit related aspects

-   On-Board Data Handling

-   Reference Operation Scenarios / Observation characteristics

-   Operability / Autonomy Requirements

Ground Segment

-   Functional Requirements and Major Elements

-   Monitoring and Control Segment

-   Data Processing Segment

User segment

-   Functional Requirements and Major Elements

-   Monitoring requirements

    a.  Description of how the system works in each mission phase

        1.  Performance drivers

        2.  Constraints

        3.  Main events

        4.  Operations scenarios

1.  For example: For a spacecraft, the following phase:

-   Launch preparation

-   Launch and Early Orbit Phase

-   In Orbit Commissioning

-   Nominal Operations

-   Spacecraft Disposal

    1.  Assessment of the performance

    <!-- -->

    a.  The MDD shall provide the

        1.  assessment against the current preliminary technical
            requirements specification requirements, and

        2.  identification of non-compliances, and their impact on the
            current preliminary technical requirements specification.

    <!-- -->

    1.  Identification of risk areas

    <!-- -->

    a.  The MDD shall provide the list of identified risk related to the
        concept, including as a minimum technology, contingencies
        handling, and programmatic aspects.

    <!-- -->

    1.  Conclusion

    <!-- -->

    a.  The MDD shall summarize the strengths and weaknesses of the
        concept.

    <!-- -->

    1.  Special remarks

None.

A.  [[]{#_Ref173840313 .anchor}]{#__RefHeading___Toc223952981
    .anchor}(normative)\
    System concept report – DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1tt.

1.  Purpose and objective

The system concept report describes the principal technical
characteristics of alternative system concepts, relating to performance,
architectures, driving technologies, interfaces, risk, their evaluation
and classification, and later addresses the selected concept.

1.  Expected response

    1.  Scope and content

        a.  The system concept report shall be an instantiation of the
            trade-off report at system level in Phase 0 and Phase A of a
            project, conforming to ECSS-E-ST-10 Annex L.

<!-- -->

1.  The system concept report can be extended to Phase B where needed
    > (e.g. late trade-offs).

    a.  This report shall address all technical (e.g. engineering
        disciplines), programmatic and related aspects relevant to the
        system.

    b.  Where relevant, specific e.g. discipline trade-off’s shall be
        performed, contributing to the system trade-off, each one being
        reported in a document conforming to ECSS-E-ST-10 Annex L.

    <!-- -->

    1.  Special remarks

None.

A.  [[[[[[]{#_Ref173810511 .anchor}]{#_Ref173813697
    .anchor}]{#_Ref173815472 .anchor}]{#_Ref173818839
    .anchor}]{#_Ref173829418 .anchor}]{#__RefHeading___Toc223952982
    .anchor}(normative)\
    System engineering plan (SEP) – DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirements 1.1.1.1.1a and
1.1.1.1.1uu.

1.  Purpose and objective

The objective of the system engineering plan (SEP) is to define the
approach, methods, procedures, resources and organization to co-ordinate
and manage all technical activities necessary to specify, design,
verify, operate and maintain a system or product in conformance with the
customer’s requirements. In particular the SEP is established to fulfil
the major technical project objectives, taking into account the defined
project phases and milestones (as defined in ECSS-M-ST-10).

The SEP covers the full project lifecycle according to the scope of the
business agreement. It is established for each item of the product tree
(as defined in ECSS-M-ST-10).

It highlights the risks, the critical elements, the specified
technologies, as well as potential commonalities, possibilities of reuse
and standardization, and provides means for handling these issues.

The SEP is an element of the project management plan (as defined in
ECSS-M-ST-10).

1.  It is important to adapt the SEP content to the phase of the
    > project, with more information on risk analysis and new
    > technologies in early phases 0, A and B, and more information on
    > verification and validation aspects in phases C, D.

    1.  Expected response

        1.  []{#_Ref174178632 .anchor}Scope and content

            1.  Introduction

            <!-- -->

            a.  The SEP shall contain a description of the purpose,
                objective, content and the reason prompting its
                preparation (e.g. programme or project reference and
                phase).

            <!-- -->

            1.  Applicable and reference documents

            <!-- -->

            a.  The SEP shall list the applicable and reference
                documents in support to the generation of the document.

            b.  The SEP shall include the references to the following
                applicable documents:

                1.  Business agreement

                2.  Project management plan, as defined in ECSS-M-ST-10
                    Annex A

                3.  Product assurance plan, as defined in ECSS-Q-ST-10
                    Annex A

                4.  Configuration management plan, as defined in
                    ECSS-M-ST-40 Annex A

                5.  Production plan

                6.  Mission operations plan, as defined in ECSS-E-ST-70
                    Annex G

                7.  ILS plan.

            <!-- -->

            1.  Project overview

                1.  []{#_Ref212044675 .anchor}Project objectives and
                    constraints

            <!-- -->

            a.  The SEP shall contain the following description of:

                1.  The project objective and the main elements that
                    characterize the user’s need.

                2.  The objective of the system or product as
                    established by the TS (as defined in the
                    ECSS-E-ST-10-06 Annex A).

                3.  The main elements of the system architecture (i.e.
                    first level elements of the architecture adopted for
                    the system and identification of their reuse
                    constraints).

                4.  The principal characteristics of the project
                    lifecycle and the incremental development of the
                    system (e.g. successive versions, progressive
                    implementation of system functions).

                5.  The main elements supporting the project lifecycle
                    (e.g. ground support equipments, and facilities).

                6.  The organizational constraints impacting system
                    engineering activities (e.g. the external and
                    internal industrial organization (e.g. contractors,
                    partners, suppliers, own company) constraints).

                7.  The list of the critical issues identified at the
                    beginning of the project phase(s).

                8.  The list of national and international regulations.

                9.  The capacity for verification and validation of the
                    product, taking into account the means available,
                    e.g. for tests, analysis, or simulation.

                <!-- -->

                1.  []{#_Ref212044721 .anchor}Product evolution logic

            <!-- -->

            a.  The SEP shall detail the incremental development of the
                system:

                1.  progressive implementation of system
                    functionalities,

                2.  identification of possible successive versions,

                3.  objectives and strategy for the implementation of
                    the successive versions.

                <!-- -->

                1.  []{#_Ref212044725 .anchor}Project phase(s), reviews
                    and planning

            <!-- -->

            a.  The SEP shall provide an implementation and schedule of
                the system engineering activities and identify for the
                considered phase(s), as a minimum:

                1.  the main project milestones driving the system
                    engineering process,

                2.  the phase(s) of the project lifecycle and the main
                    reviews in accordance to project management plan.

            b.  The SEP shall provide dates of milestones or the
                duration of phases and the critical path according to
                the project master schedule.

                1.  []{#_Ref212044727 .anchor}Procurement approach

            <!-- -->

            a.  The SEP shall describe the strategy for acquisition of
                the items of the system or products defined in the
                product tree (e.g. make or buy, product line,
                incremental development).

                1.  Initial critical issues

            <!-- -->

            a.  The SEP shall list the critical issues identified at the
                beginning of the project phase(s) covered in the SEP
                (e.g. any specific issues, problems, critical subjects,
                which require dedicated attention, investigation, action
                and planning).

            <!-- -->

            1.  System design approach

                1.  System engineering inputs

            <!-- -->

            a.  The SEP shall list the driving inputs for the system
                engineering activities described and defined by the:

                1.  business agreement,

                2.  outputs from previous phase(s) or expected under the
                    heading of activities which are not controlled
                    within the context of this SEP (e.g. data provided
                    by the customer, data coming from other projects,
                    upstream or predevelopment studies, product lines),

                3.  project management plan, product assurance plan,
                    risk management plan, and configuration and
                    documentation management plans.

            b.  The SEP shall list the external means and facilities
                (e.g. equipment, software, and premises) made available
                by the customer or by any other entity external to the
                organization that is responsible of this SEP, and, for
                each identified mean or facility, identify the
                applicable interface requirements (e.g. interface
                control documentation) as well as the authority in
                charge of it.

            c.  The SEP shall list the internal means and facilities
                (e.g. equipment, software, and premises) made available
                by the organization in charge of the development of the
                system or product.

            d.  The SEP shall contain the Coordinate System Document (as
                defined in ECSS-E-ST-10-09 Annex A).

            e.  The SEP shall define the units system to be used in the
                project.

                1.  []{#_Ref212864466 .anchor}System engineering outputs

            <!-- -->

            a.  The SEP shall list the specified system engineering
                outputs as defined in ECSS-E-ST-10 clause 6 for the
                specific project phase(s) covered in the SEP.

2.  An overview of document delivery is given in Annex A.

    a.  []{#_Ref212864477 .anchor}The SEP shall describe the following:

        1.  The strategy for the system engineering activities in line
            with the guidelines addressed by the management plan. In
            particular, identifying intermediate technical events for
            each phase in compliance with the master program schedule.

        2.  The system design activities, with their objectives and
            major outputs according to the phase.

        3.  The major engineering activities for each intermediate
            technical events, showing their mutual interactions and
            their relationships with the principal milestones (i.e.
            internal or contractual) of the project.

        4.  The model philosophy (as defined in ECSS-E-ST-10-02 clause
            4.2.5) in terms of number and characterization of models,
            from system to the requested lower level, necessary to
            achieve a high confidence in the product verification.

        5.  []{#_Ref212864418 .anchor}The margin policy according to
            project phase, product category and maturity level.

    b.  The SEP shall also describe

        1.  the method(s) and process(es) considered for the engineering
            activities (e.g. concurrent engineering, value analysis, or
            iteration cycle),

        2.  the interrelation between the different engineering
            disciplines and other project activities (e.g. production,
            quality assurance, and operations and logistics),

        3.  the interaction with other actors (e.g. customer and
            suppliers),

        4.  the consistency and coherency of simultaneous activities
            (e.g. performed in parallel),

        5.  which and how, control activities are implemented,

        6.  Assessment of potential COTS usage

    c.  In the case of a system incremental evolution, the SEP shall
        describe the design strategy for the:

        1.  development of the initial release of the product,

        2.  development, the verification of subsequent releases and
            their deployment,

        3.  introduction of new technologies,

        4.  tools and methods used for analysis,

        5.  control of the evolutions for each release.

        <!-- -->

        1.  System engineering team responsibilities and organization

    <!-- -->

    a.  The SEP shall contain the following:

        1.  Definition of the entities participating in the system
            engineering activities and the corresponding functions
            according to the project management plan.

        2.  Identification of key engineering roles and responsibilities
            (e.g. system engineers, disciplines engineers, and technical
            managers).

        3.  Description of the co-operative work amongst the different
            teams participating in the system design.

        <!-- -->

        1.  System engineering interfaces

    <!-- -->

    a.  The SEP shall describe the external and internal interfaces in
        line with the project management plan.

    <!-- -->

    1.  Implementation and related plans

        1.  System engineering tasks description

&lt;5.1.1&gt; System engineering process description

a.  The SEP shall describe the system engineering process tailored to
    the specifics of the considered project, and identify all the system
    engineering tasks to be implemented from the starting conditions
    (e.g. kick-off) to the closing event (e.g. review), their
    relationship, and their interfaces with other actors of the project,
    and identify and describe any existing iteration within the process.

<!-- -->

1.  Details are provided in ECSS-E-HB-10 “System engineering
    > guidelines”.

    a.  For each task, the input information and their origin, the
        document(s) delivered (i.e. expected output) and their
        destination, the system engineering function(s) performed and
        the contribution of other actors shall be identified.

2.  Details are provided in ECSS-E-HB-10 “System engineering
    > guidelines”.

&lt;5.1.2&gt; Engineering disciplines integration

a.  The SEP shall address the following activities that concern the
    different engineering disciplines, recalling the relevant applicable
    standards and ancillary dedicated plans that are considered integral
    part of this SEP.

b.  The SEP shall define the process and control to be put in place to
    meet requirements for the thermal, structures, mechanisms,
    environmental control and life support, propulsion, pyrotechnics,
    mechanical parts, and materials functions and interfaces.

<!-- -->

1.  These requirements refer to Mechanical engineering as defined in
    > ECSS-E-ST-3x series of standards.

    a.  The SEP shall define the process and control to be put in place
        to meet requirements for electrical and electronic engineering,
        covering all electrical and electronic aspects of the relevant
        space product, including functions such as power generation,
        storage, conversion and distribution, and optical, avionics and
        microwave domains, electromagnetic compatibility, and electrical
        interfaces.

2.  These requirements refer to Electrical and electronic engineering as
    > defined in ECSS-E-ST-20.

    a.  The SEP shall define process and control to be put in place to
        meet requirements for software engineering, covering, amongst
        others, flight and ground software, checkout software and
        simulation software.

3.  These requirements refer to Software engineering as defined in
    > ECSS-E-ST-40.

    a.  The SEP shall define process and control to be put in place to
        meet requirements for communication engineering, covering,
        amongst others, spacecraft-to-ground, spacecraft-to-spacecraft,
        ground-to-ground and on-board communications links.

<!-- -->

1.  1 These requirements refer for Communications engineering as defined
    > in ECSS-E-ST-50.

2.  2 It includes aspects such link budgets, data management, RF, audio
    > and video communications and protocols.

    a.  The SEP shall define process and control to be put in place to
        meet requirements for control engineering, covering, amongst
        others, AOCS, robotics, rendez-vous and docking.

<!-- -->

1.  These requirements refer to Control engineering as defined in
    > ECSS-E-ST-60.

    a.  The SEP shall define the process and control to be put in place
        to meet requirements specifying natural environment for all
        space regimes (e.g. debris regulations, or planetary
        contamination protection) and general models and rules for
        determining the local induced environment

2.  These requirements refer to Space environment as defined in
    > ECSS-E-ST-10-04.

    a.  The SEP shall define the process and control to be put in place
        to meet requirements for the approach, methods, procedures,
        organization and resources to be implemented to ensure proper
        technical interfaces between system engineering and production.

    b.  The SEP shall define the process and control to be put in place
        to meet requirements of operations of the space segment,
        covering, amongst others:

        1.  mission operation definition and preparation,

        2.  mission and trajectory analysis, and

        3.  operability analysis (e.g. autonomy, operational scenario,
            nominal and non-nominal modes, failure detection isolation
            and recovery).

3.  These requirements refer to Operations engineering as defined in
    > ECSS-E-ST-70.

    a.  The SEP shall define the process and control to be put in place
        to meet requirements for ground and in-orbit logistics and
        maintenance, addressing, amongst others, technical activities,
        related engineering standards, methods and analyses to be
        performed to ensure that the development of space systems (i.e.
        manned and unmanned) properly takes into account and integrates
        the supportability and support aspects for the whole life cycle.

    b.  The SEP shall define the process and control to be put in place
        to meet requirements for human activities and environments
        associated with space systems.

4.  These requirements refer to Human factors engineering as defined in
    > ECSS-E-ST-10-11.

    a.  The SEP shall define process and control to be put in place to
        meet requirements for implementation of design selections
        relating to humans for any item with associated human interface,
        including computer based system and equipment.

&lt;5.1.3&gt; Work package

a.  The SEP shall define and describe the work package(s) for the
    relevant engineering tasks, which are maintained in the work
    breakdown structure.

    1.  []{#_Ref219882696 .anchor}Related plans

<!-- -->

a.  When the SEP includes sub-plans covering parts of system engineering
    activities, these sub-plans shall be annexed to the SEP.

b.  []{#_Ref219882701 .anchor}The system engineering organization shall
    identify in the SEP the other plans relevant to its activity
    belonging to the following categories:

<!-- -->

1.  Some of these plans can be integrated in the SEP in the early phases
    > of a project.

    1.  Programmatic plans

2.  Examples of programmatic plans are: the SEP plans of sub-products
    > constituting the system or product, Industrial procurement plan,
    > risk management plan, off-the-shelf plan (see ECSS-Q-ST-20-10).

    1.  Verification plans

<!-- -->

1.  1 Examples of verification plans are: verification plan (VP), AIT
    > plan, AIV plan and technology plan, system calibration plan,
    > Security Aspects Verification Plan. Some of those DRDs are defined
    > in this document, in ECSS-E-ST-10-02 or ECSS-E-ST-10-03.

2.  2 VP and AIT plans can be integral parts of the SEP, or rolled out
    > separately (without overlap), or combined as the AIV Plan which
    > can also be rolled out separately. However, the existence of the
    > AIV Plan excludes independent VP and AIT plans

    1.  Engineering discipline plans

<!-- -->

1.  Examples of engineering discipline plans are: Fracture Control Plan
    > (see ECSS-E-ST-32), Micro-gravity Control Plan, Electro-Magnetic
    > Compatibility Plan (see ECSS-E-ST-20), Audible Noise Control Plan,
    > Radio Frequency Plan, Alignment Requirements and Control Plan,
    > System Performance Simulations Plan, Software Development Plan,
    > Orbital Debris Mitigation Plan and Disposal Plan (as defined in
    > ISO 24113), Planetary protection Plan, Cleanliness and
    > Contamination Control Plan.

    1.  Operations plans

2.  Examples of operation plans are: launch site operations and
    > logistics plan, system commissioning and operation support plan,

    a.  The SEP shall describe the constraints and the interactions
        impacting the system engineering activities derived from the
        analysis of the plans identified as relevant in
        D.2.1.1.1&lt;5.2&gt;b.

        1.  System engineering methods, tools and models

    <!-- -->

    a.  The SEP shall list and briefly describe the methods, tools, and
        data models that the system engineering team uses in performing
        their tasks.

    b.  In relation to requirements traceability and demonstration of
        verification (compliance with requirements, VCD), the specific
        methods and tools shall be described (including interfaces to
        next lower level suppliers), and reuse of elements (e.g. COTS)
        identified.

        1.  Critical issues

    <!-- -->

    a.  The SEP shall describe any specific issues, problems requiring
        dedicated attention, investigations or actions during the
        current phase and identify risks, and risk mitigation measures.

    <!-- -->

    1.  System engineering for the following phase(s)

    <!-- -->

    a.  The SEP shall introduce the system engineering activities, to be
        conducted during subsequent phase(s) of the project, and as a
        minimum, list any identified critical issue and risk to be
        mitigated during the subsequent phase(s).

    <!-- -->

    1.  Special remarks

None.

A.  [[[[]{#_Ref173813519 .anchor}]{#_Ref173813825
    .anchor}]{#_Ref173837811 .anchor}]{#__RefHeading___Toc223952983
    .anchor}(normative)\
    Technology plan (TP) – DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1zzzz.

1.  Purpose and objective

The objective of the technology plan (TP) is to define the approach,
methods, procedures, resources and organization to evaluate the ability
of a critical technology to meet the intended requirements. Also, the
objective of this plan is to ensure effective preparation of the
technologies necessary for a timely implementation of the system, in
accordance to the requirements imposed by the specific characteristics
of the relevant product.

It is established for each item of the function tree (as defined in
ECSS-E-ST-10, Annex H), and highlights the technical requirements, and
the critical technology of each item.

The TP is part of the system engineering plan (SEP) (as defined in
ECSS-E-ST-10, Annex E).

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The TP shall contain a description of the purpose,
            objective, content and the reason prompting its preparation
            (e.g. programme or project reference and phase).

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The TP shall list the applicable and reference documents in
            support to the generation of the document and include the
            reference to the following applicable documents:

            1.  SEP

            2.  Technology matrix (as defined in ECSS-E-ST-10, Annex F)

            3.  Function tree

            4.  Specification tree.

        <!-- -->

        1.  Project overview

        <!-- -->

        a.  The TP shall contain a summary of the main aspects of:

            1.  project objectives and constraints (i.e. section
                &lt;3.1&gt; of ECSS-E-ST-10, Annex D "SEP DRD");

            2.  product evolution logic (i.e. section &lt;&lt;3.2&gt; of
                ECSS-E-ST-10, Annex D "SEP DRD");

            3.  project phase(s), reviews and planning (i.e. section
                &lt;3.3&gt; of ECSS-E-ST-10, Annex D "SEP DRD"),

            4.  Procurement approach (i.e. section &lt;3.4&gt; of
                ECSS-E-ST-10, Annex D "SEP DRD")

        <!-- -->

        1.  Tasks description

            1.  TP expected outputs

        <!-- -->

        a.  The TP expected output shall be an answer concerning the
            possibility for using the identified or needed technology to
            perform a function.

            1.  TP inputs

        <!-- -->

        a.  For each system function, the TP input shall be:

            1.  technical requirements,

            2.  the selected technology or technological element and its
                TRL,

            3.  the list of the identified project risks and critical
                aspects, and

            4.  the schedule for Engineering activities.

            <!-- -->

            1.  TP tasks

        <!-- -->

        a.  The TP shall establish and describe the necessary activities
            to complete the acquisition of each technology or
            technological element, including verification strategies and
            methods, and the link to product assurance aspects.

        b.  The TP shall define the model philosophy for each technology
            or technological element, based on an assessment on the
            maturity status and on the criticality of the technology
            with respect to functions' requirements.

        c.  The TP shall describe the technology development activities,
            their required or possible interrelations and timings, as
            necessary for the satisfactory acquisition of the
            technologies and procurement of the technological elements.

        d.  The TP shall identify technical milestones, showing their
            interactions and relationships with the SEP milestones.

            1.  Responsibilities and organization

        <!-- -->

        a.  The TP shall contain the following:

            1.  definition of the entities participating in the
                engineering activities and the corresponding functions
                according to the SEP;

            2.  identification of key engineering roles and
                responsibilities for each technology or technological
                element.

            <!-- -->

            1.  TP interfaces

        <!-- -->

        a.  The TP shall describe the external and internal interfaces
            in conformance to the SEP.

        <!-- -->

        1.  Critical issues

        <!-- -->

        a.  The TP shall describe, for any identified technology risk
            and related critical aspects for the project, the specific
            actions taken for risk mitigation based on identified
            technology readiness level (TRL).

    2.  Special remarks

        a.  The content of the TP may be merged with the content of the
            SEP.

        b.  The TP shall introduce the related activities, to be
            conducted during all phase(s) of the project.

<!-- -->

A.  [[[]{#_Ref173814488 .anchor}]{#_Ref173837750
    .anchor}]{#__RefHeading___Toc223952984 .anchor}(normative)\
    Technology matrix - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1yyyy.

1.  Purpose and objective

The technology matrix presents, for each technical requirement/function,
the list of technologies or technological elements, which have the
potential to meet this requirement. It summarizes candidate technologies
per individual requirement.

The technology matrix is part of the Design Justification File (as
defined in ECSS-E-ST-10, Annex K). It is the basic document for
presenting all identified potential technologies for the product.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The technology matrix shall contain a description of the
            purpose, objective, content and the reason prompting its
            preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The technology matrix shall list the applicable and
            reference documents in support to the generation of the
            document and include the reference to the following
            applicable documents:

            1.  Specification tree

            2.  Preliminary technical requirements specifications

            3.  Function tree.

        <!-- -->

        1.  List of technical requirements/functions

        <!-- -->

        a.  The technology matrix shall list the system technical
            requirements/functions as defined in the functional
            architecture and its corresponding function tree, and their
            associated preliminary TS.

        <!-- -->

        1.  List of potential technologies for each technical
            requirement/function

        <!-- -->

        a.  The technology matrix shall list the system technical
            requirements/functions and for each, a potential technology
            or technological element.

<!-- -->

1.  Sources to identify potential technologies are technology watch,
    > corporate technology plan, or research and development programme.

    a.  For each technology or technological element, the following
        information shall be listed:

        1.  index of technology readiness and maturity as defined in
            proposed table in definition 3.2.12 “technology readiness
            level”;

        2.  proof of company's maturity concerning the knowledge and
            mastership of the technology, including a description of the
            necessary technology acquisition activities;

        3.  identification of potential risks, e.g. technology
            availability, programmatic and financial aspects.

    <!-- -->

    1.  Ranking of the potential technologies for each function

    <!-- -->

    a.  The technology matrix shall propose a ranking of the potential
        technology or technological element for each system requirement/
        function.

    <!-- -->

    1.  Conclusion

    <!-- -->

    a.  The technology matrix shall provide, for each system
        requirement/function, the selected technology or technological
        element, a list of the identified project risks and critical
        aspects, and an identified back-up technological solution.

    <!-- -->

    1.  Special remarks

None.

A.  [[[[[]{#_Ref173818473 .anchor}]{#_Ref173818696
    .anchor}]{#_Ref173818865 .anchor}]{#_Ref173838421
    .anchor}]{#__RefHeading___Toc223952985 .anchor}(normative)\
    Design definition file (DDF) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirements 1.1.1.1.1ee,
1.1.1.1.1hh, 1.1.1.1.1ddd and 1.1.1.1.1rrr.

1.  Purpose and objective

The objective of the design definition file (DDF) is to establish the
technical definition of a system or product that complies with its
technical requirements specification (as defined in ECSS-E-ST-10-06
Annex A).

The design definition file is a basic structure referring to all
information relative to the functional and physical architectures and
characteristics of a system or product, necessary for its
identification, manufacturing, utilization, support, configuration
management and removal from service.

The DDF is a collection of all documentation that establishes the system
or product characteristics such as lower level technical specifications,
design and interface description, drawings, electrical schematics,
specified constraints (e.g. on materials, manufacturing, processes, and
logistic).

It details the as-designed configuration baseline (as defined in
ECSS-M-ST-40) of the system or product and is built up and updated under
the responsibility of the team in charge of system engineering. It is
the technical baseline for the production, assembly, integration and
test, operations and maintenance of the product.

The DDF, the technical requirements specification, and the Design
Justification File (as defined in ECSS-E-ST-10 Annex K) are the basic
documents used for product development. They are interrelated such as:

-   the design (i.e. DDF) is the response to the requirements stated in
    the TS,

-   the justification (i.e. DJF) demonstrates the conformance of the
    design (i.e. DDF) to the requirements stated in the TS.

1.  The DDF is a logical file covering all TS disciplines required for
    > the considered system. In general, the elements of the DDF are
    > “rolled out” as separate documents.

    1.  Expected response

        1.  Scope and content

            1.  Introduction

            <!-- -->

            a.  The DDF shall contain a description of the purpose,
                objective and the reason prompting its preparation (e.g.
                programme or project reference and phase).

            <!-- -->

            1.  Applicable and reference documents

            <!-- -->

            a.  The DDF shall contain the list of applicable and
                reference documents, used in support to the generation
                of the document.

            b.  The DDF shall include the reference to the following
                applicable documents:

                1.  Business agreement

                2.  System engineering plan (as defined in ECSS-E-ST-10
                    Annex D)

                3.  Coordinate system document (as defined in
                    ECSS-E-ST-10-09 Annex A)

                4.  Technical requirements specification (TS)

                5.  Product assurance plan

                6.  Configuration management plan (as defined in
                    ECSS-M-ST-40)

                7.  Configuration status report (as defined in
                    ECSS-M-ST-40).

            c.  The DDF shall refer to DDFs of next higher and lower
                level products.

            <!-- -->

            1.  Summary of the project and technical requirements

            <!-- -->

            a.  The DDF shall contain a brief description of the product
                and of the main technical requirements throughout its
                life cycle phases (e.g. launch, deployed, operations,
                end-of-life).

            b.  The DDF shall contain the description of the system or
                product design documentation, based on the product tree
                (as defined in ECSS-M-ST-10) and also include, or refer
                to, the specifications tree (as defined in ECSS-E-ST-10
                Annex J).

            c.  The DDF of a system shall contain at least the technical
                requirements specifications of the elements in which the
                system is broken down

            <!-- -->

            1.  Functional description

                1.  Functional architecture

            <!-- -->

            a.  The DDF shall contain the description of the functional
                architecture of the system or product i.e. the
                arrangement of functions, their sub-functions and
                interfaces (internal and external), and the performance
                requirements to satisfy the requirements of the TS.

            b.  The DDF shall present the data and their flow
                interchanged between the different functions, the
                conditions for control, and the execution sequencing for
                the different operational modes and states.

2.  The Functional Architecture is an output of the functional analysis
    > process (as defined in ECSS-E-ST-10 clause 1.1.1.1.1cc)

    1.  Function tree

    <!-- -->

    a.  The DDF shall contain or refer to the system or product function
        tree, the latter conforming to ECSS-E-ST-10 Annex H.

        1.  Description of functional chains

    <!-- -->

    a.  The DDF shall describe the functional chains that contribute to
        the realization of the functional requirements of the TS and
        their contributing functions, consider the different operational
        modes and states, and indicate the selected physical
        implementation for each of the functions.

    <!-- -->

    1.  Physical description

        1.  Physical architecture

    <!-- -->

    a.  The DDF shall contain the description of physical architecture
        of the system or product i.e. the arrangement of elements, their
        decomposition, interfaces (internal and external), and physical
        constraints, which form the basis of a system or product design
        to satisfy the functional architecture and the technical
        requirements.

3.  The Physical Architecture is an output of the preliminary design
    > definition activities (as defined in clause 1.1.1.1.1hh).

    1.  Product tree

    <!-- -->

    a.  The DDF shall contain or refer to the product tree of the system
        or product, as defined in ECSS-M-ST-10 Annex B.

4.  The Product Tree is a breakdown of the Physical Architecture.

    1.  Specification tree

    <!-- -->

    a.  The DDF shall contain or refer to the specification tree of the
        system or product, the latter conforming to Annex J.

        1.  Description of elements of the physical architecture

    <!-- -->

    a.  The DDF shall provide

        1.  the nomenclature of the system or product,

        2.  the overall system or product drawings,

        3.  for each element of the system, the description of the
            different constituents of the physical architecture,

        4.  the characteristics of the respective elements,

        5.  their configuration management identifier (e.g. hardware
            part number, software version number, drawings number,
            electrical schematics numbers).

    b.  The DDF shall reference any documentation containing detailed
        technical descriptions and associated matrices to ensure overall
        consistency and completeness.

        1.  Description of interfaces

    <!-- -->

    a.  The DDF shall describe the physical and functional
        characteristics of the internal and external interfaces of the
        system and refer to the relevant IRD and ICD, respectively
        conforming to Annex M and ECSS-E-ST-10-24.

    <!-- -->

    1.  System technical budget, margins and deviations

    <!-- -->

    a.  The DDF shall present the budget allocation of the technical
        parameters of the system and provide the actual status of the
        system margins, and deviations.

    b.  The DDF shall contain or refer to the system or product
        technical budget, the latter conforming to Annex I.

    <!-- -->

    1.  System design constraints

        1.  Constraints for production

    <!-- -->

    a.  The DDF shall present the constraints induced by the system or
        product design definition on the production activities e.g.
        operational allowable envelopes, restrictions on assembling
        sequences, procedures and testing modes, exclusion zones,
        manufacturing environmental conditions, and conditions for
        procurement.

        1.  Constraints for operation

    <!-- -->

    a.  The DDF shall present the constraints induced by the system or
        product design definition on the implementation of the
        operations e.g. operational allowable envelopes, restrictions on
        operating modes, and exclusion zones.

        1.  Constraints for transportation and storage

    <!-- -->

    a.  The DDF shall present the constraints induced by the system or
        product design definition on the transportation activities and
        during the periods of storage of the product e.g. allowable
        envelopes, restrictions on transportation and storage, exclusion
        zones, packaging, shock levels, temperature environments,
        humidity, cleanliness, regulations, and dangerous materials.

        1.  Constraints for maintainability

    <!-- -->

    a.  The DDF shall present the constraints induced by the system or
        product design definition on the maintenance activities and
        procedures e.g. operational allowable envelopes, accessibility,
        tooling, support materials, parts availability, and deliveries.

    <!-- -->

    1.  Engineering database

    <!-- -->

    a.  The DDF shall contain the information on the system or product
        engineering database that contains the complete set of design
        parameters, or a reference to it.

5.  Information about the set of design parameters is provided in
    > ECSS-E-TM-10-10.

    1.  Conclusion

    <!-- -->

    a.  The DDF shall list and summarize all deviations of the design
        with respect to the technical specifications and constraints
        induced by the system or product design definition.

    <!-- -->

    1.  Special remarks

None.

A.  [[[]{#_Ref173813798 .anchor}]{#_Ref173815596
    .anchor}]{#__RefHeading___Toc223952986 .anchor}(normative)\
    Function tree - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1dd.

1.  Purpose and objective

The objective of the function tree document is to describe the
hierarchical decomposition of a system or product capabilities into
successive level of functions and sub-functions.

The function tree is part of the Design Definition File. It is the
starting point for the establishment of the Product Tree (as defined in
ECSS-M-ST-10) and is a basic structure to establish preliminary
technical requirements specification(s) (as defined in ECSS-E-ST-10-06
Annex A).

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The function tree document shall contain a description of
            the purpose, objective and the reason prompting its
            preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The function tree document shall contain the list of
            applicable and reference documents, used in support to the
            generation of the document.

        <!-- -->

        1.  Project summary and user’s need presentation

        <!-- -->

        a.  The function tree document shall contain a brief description
            of the project and of the key user’s needs.

        <!-- -->

        1.  Tree structure

        <!-- -->

        a.  The function tree document shall provide the complete list
            of functions that the system or product shall perform, and
            contain a graphical representation where the main specified
            function(s) (i.e. at the top level of the tree) is/are
            decomposed into lower level functions.

        b.  When recurrent products from previous space projects are
            used, the product’s functions shall be identified in the
            tree structure, and addition, every necessary function by
            the system or product that is not under the supplier’s
            responsibility identified in the tree structure.

    2.  Special remarks

        a.  The function tree shall be coherent with other functional
            descriptions of the system or product (e.g. functional
            architecture, functional block diagram).

<!-- -->

A.  [[[[]{#_Ref173817102 .anchor}]{#_Ref173828946
    .anchor}]{#_Ref173837699 .anchor}]{#__RefHeading___Toc223952987
    .anchor}(normative)\
    Technical budget - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1iii.

1.  Purpose and objective

The technical budget defines for each key engineering parameter of a
system or product, the nature of this parameter, its measure, specified
value, metrics requirements and current actual or computed value and
assessed value.

The technical budget is part of the Design Definition File (as defined
in ECSS-E-ST-10 Annex G). It is the basic document for providing
adequate control of the key engineering parameter properties to meet the
system or product technical requirements.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The technical budget shall contain a description of the
            purpose, objective, content and the reason prompting its
            preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The technical budget shall list the applicable and reference
            documents in support to the generation of the document.

        <!-- -->

        1.  List of selected key engineering parameters

        <!-- -->

        a.  The technical budget shall:

            1.  list the selected key engineering parameters (those
                specified by the customer and those selected by the
                supplier),

<!-- -->

1.  Examples of key engineering parameters are mass, communication
    > links, power, and on-board computer memory capacity.

    1.  present the reason for their selection,

    2.  identify for each key engineering parameters the stages of
        maturity of the design.

    3.  present the related margin policy for these parameters.

    <!-- -->

    1.  Assessment of key engineering parameters

    <!-- -->

    a.  For each key engineering parameter, the technical budget shall:

        1.  provide the specified value of the parameter,

        2.  provide the supplier’s margin resulting of the allocation of
            the parameter to the lower level products,

        3.  provide the specified values with the reference to the
            relevant technical requirement of the lower level products,

        4.  propose a specific program to conform to the specified value
            in case of nonconformance,

        5.  contain a chart of parameter history that presents the
            evolution of the parameter’s value at the different design
            maturity steps for which the evaluation of the parameter is
            performed,

        6.  list the documentation sources (e.g. analysis report and
            verification report).

    <!-- -->

    1.  Conclusion

    <!-- -->

    a.  The technical budget shall contain a conclusion that identifies
        the key engineering parameters having a negative margin, and
        identify for each of those:

        1.  the impact on the technical requirements and the associated
            risk for the project, and

        2.  the specific program to conform to the specified value and
            for project risk mitigation.

    <!-- -->

    1.  Special remarks

None.

A.  [[[[[[[]{#_Ref173815561 .anchor}]{#_Ref173816585
    .anchor}]{#_Ref173831337 .anchor}]{#_Ref173831340
    .anchor}]{#_Ref173831691 .anchor}]{#_Ref173838272
    .anchor}]{#__RefHeading___Toc223952988 .anchor}(normative)\
    Specification tree - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1n.

1.  Purpose and objective

The objective of the specification tree document is to define the
hierarchical relationship of all technical requirements specifications
for the different elements of a system or product.

The specification tree is part of the Design Definition File (as defined
in ECSS-E-ST-10 Annex G). It is the basic structure to perform the
system or product requirements traceability and to manage their internal
interfaces.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The specification tree document shall contain a description
            of the purpose, objective and the reason prompting its
            preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The specification tree document shall contain the list of
            applicable and reference documents, used in support to the
            generation of the document.

        <!-- -->

        1.  Project summary and user’s need presentation

        <!-- -->

        a.  The specification tree document shall contain a brief
            description of the project and the key user’s needs.

        <!-- -->

        1.  Tree structure

        <!-- -->

        a.  The specification tree document shall provide the complete
            list of specifications defining the system or product, and
            contain a graphical representation where the system or
            product specification (i.e. at the top level of the tree) is
            decomposed into lower level product specifications.

        b.  When recurrent products from previous space projects are
            used, their specification shall be identified in the tree
            structure, and in addition, for every necessary product that
            is not under the supplier’s responsibility, their
            specification shall be identified in the tree structure.

    2.  Special remarks

        a.  The specification tree shall be coherent with the product
            tree (see ECSS-M-ST-10) and the business agreement structure
            (see ECSS-M-ST-60).

<!-- -->

A.  [[[[[]{#_Ref173815044 .anchor}]{#_Ref173815366
    .anchor}]{#_Ref173834115 .anchor}]{#_Ref173834349
    .anchor}]{#__RefHeading___Toc223952989 .anchor}(normative)\
    Design justification file (DJF) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirements 1.1.1.1.1ff,
1.1.1.1.1ii, 1.1.1.1.1jj and 1.1.1.1.1sss.

1.  Purpose and objective

The objective of the design justification file (DJF) is to present the
rationale for the selection of the design solution, and to demonstrate
that the design meets the baseline requirements.

The DJF is progressively prepared during the detailed design process and
according to the system engineering plan (SEP) (as defined in
ECSS-E-ST-10 Annex D), and serves the following purposes:

-   it provides access to the necessary justification information,

-   it presents a review of all acquired justifications,

-   it constitutes a basic element for decision taking concerning the
    product definition qualification.

The DJF together with the Design Definition File (DDF) (as defined in
Annex G) and the technical requirements specification (TS) (as defined
in ECSS-E-ST-10-06 Annex A) are the basic documents used for the
development of the product. These documents are used to monitor the
evolution of the design.

The DJF is a collection of all documentation that traces the evolution
of the design during the development and maintenance of the product. The
DJF is updated according to the evolution of the DDF, in accordance with
the above-mentioned objectives.

The DJF provides also access to coherent and substantiated information
which can be used to support decision-making in the analysis of change
requests for the management of non conformances.

The DJF contains results obtained during the evolution of the design as
a consequence of the activities performed along the design process:

-   Analysis and trade-off reports concerning the evaluation of
    alternative design solutions and the justification of the choice.

-   All results obtained during the verification of the design as a
    consequence of the activities performed along the verification
    process.

-   Test Reports on engineering model, structural and thermal model and
    qualification model (e.g. Protoflight Models).

1.  The DJF is a logical file covering all technical disciplines
    > required for the considered system. In general, the elements of
    > the DJF are “rolled out” as separate documents.

    1.  Expected response

        1.  []{#_Ref223867247 .anchor}Scope and content

            1.  Introduction

            <!-- -->

            a.  The DJF shall contain a description of the purpose,
                objective, content and the reason prompting its
                preparation.

            <!-- -->

            1.  Applicable and reference documents

            <!-- -->

            a.  The DJF shall list the applicable and reference
                documents in support to its generation.

            b.  The applicable document list shall contain the reference
                to the relevant product specifications, and the relevant
                DDF and system engineering plan.

            c.  The reference document list shall contain the reference
                to:

                1.  Trade-Off-Reports, as defined Annex L.

                2.  Analysis Reports (e.g. requirements allocation
                    analysis, functional analysis).

                3.  Requirements Traceability Matrix, as defined in
                    Annex N (with link to analysis).

                4.  Verification Control Document

                5.  All verification documentation, such as:

                    a.  Analysis Reports (e.g. reports w.r.t.
                        qualification aspects)

                    b.  Test Reports

                    c.  ROD Reports

                    d.  Inspection Reports

                    e.  Verification Reports

            <!-- -->

            1.  Design description

            <!-- -->

            a.  The DJF shall contain a description of the expected
                product, its intended mission, architecture and design,
                and the functioning principles on which it is based.

            b.  The DJF shall define the requirement criteria levels for
                qualification and acceptance verification of the
                product.

            <!-- -->

            1.  []{#_Ref223867362 .anchor}Design Justification File
                Synthesis

            <!-- -->

            a.  The DJF shall present status of the design justification
                in response to requirements, with emphasis on the
                driving requirements that have a big impact on the
                system design, production and maintainability (see also
                K.2.1&lt;8.2.4&gt;a.)

            b.  The DJF shall present an overall system qualification
                status synthesis, including:

                1.  the list of requirements which have not been met
                    (e.g. nonconformances), including proposed actions,

                2.  the list of all critical points, and how
                    criticalities have been or are intended to be
                    resolved,

                3.  the identification of requirements which have not
                    been justified yet, and associated risks analysis,
                    with emphasis on those that can have an impact at
                    system level.

            <!-- -->

            1.  Justification of the Functional Architecture

            <!-- -->

            a.  The DJF shall contain the demonstration that all
                requirements of the preliminary technical requirements
                specification are allocated to functional blocks of the
                system functional architecture.

            b.  Where requirements assigned to functional blocks do not
                have their origin within any of the customer preliminary
                technical specifications, these requirements shall be
                justified.

            <!-- -->

            1.  Justification of the Physical Architecture

            <!-- -->

            a.  The DJF shall contain the demonstration that the system
                design conforms to the requirements of the technical
                specification, and identify products which are reused
                (e.g. COTS).

            b.  The DJF shall also provide the justification for the
                choice of architectural elements at the next lower
                level, or lower levels in case of system critical
                elements.

            c.  Where requirements do not have their origin within any
                of the upper level technical specifications, these shall
                be justified.

            <!-- -->

            1.  Development activities and synthesis of development
                results

            <!-- -->

            a.  The DJF shall present the development activities (e.g.
                assessments, analyses, tests, and trade-offs) and the
                design drivers, which lead to and justify the design as
                defined in the DDF, in line with the development
                approach identified in the SEP.

            b.  The justification shall concern all the engineering
                disciplines contributing to design and development of
                the product (including its operational modes and
                scenarios).

            c.  The DJF shall include the status of DJF of lower level
                products.

2.  Activities related to verification are dealt with in section
    > K.2.1&lt;8&gt;.

    a.  For the system and each discipline, following information shall
        be produced:

        1.  Activity inputs, such as requirements, operational modes,
            assumptions, analysis cases, boundary conditions, model
            descriptions and limitations.

        2.  Activity results, such as

            a.  raw results,

            b.  evaluation of results,

            c.  evaluation of margins with respect to the technical
                requirements contained in the TS,

            d.  identification of any marginal areas.

        3.  Activity synthesis, such as

            a.  evidence of compliance to the technical requirements
                contained in the TS,

            b.  list of technical requirements which have not been met,
                including proposed actions,

            c.  list of all critical points, and how criticalities have
                been or are intended to be resolved,

            d.  identification of aspects of the design, which are not
                yet justified, and assessment of inherent risks.

    b.  The DJF shall reference the requirements traceability matrix,
        e.g. w.r.t. building up the justification of a considered system
        top level requirements in terms of the various elements
        contributing to it, including where relevant contribution from
        other disciplines (e.g. pointing as a function of thermal,
        structures, and AOCS).

    <!-- -->

    1.  Verification activities and synthesis of results

        1.  Verification plan

    <!-- -->

    a.  The DJF shall integrate or refer to the document that conforms
        to the verification plan DRD defined in ECSS-E-ST-10-02 Annex A.

3.  The verification activities are detailed in the Verification Plan
    > (VP), which also contains the justification of the verification
    > strategy (as defined in ECSS-E-ST-10-02).

    1.  Qualification verification and synthesis of results

&lt;8.2.1&gt; Qualification evidence

a.  The DJF shall present the evidence of the qualification of the
    design in conformance to the applicable technical requirements and
    proper qualification margins.

<!-- -->

1.  This is done in line with the qualification approach identified in
    > the VP.

    a.  The DJF shall cover the system and all disciplines relevant to
        the product in all its operational modes and scenarios,
        addressing all applicable technical requirements and proper
        qualification margins.

<!-- -->

1.  1 This is done in line with the system verification matrix.

2.  2 The formal compliance with the qualification requirements is
    > recorded in the VCD, together with references to the close-out
    > documents.

&lt;8.2.2&gt; Implementation of the qualification plan

a.  The DJF shall present the implementation of the qualification plan
    and the status thereof, addressing the detailed definition of
    qualification activities (e.g. analysis, test, ROD, and inspection),
    including the detailed definition of the tests, the prediction of
    expected test results, test success criteria, test specifications,
    and model validations.

<!-- -->

1.  Details on test specifications are provided in ECSS-E-ST-10-03
    > Annex B.

&lt;8.2.3&gt; Validation of models

a.  The DJF shall contain all evidence (e.g. analyses, test results, and
    model descriptions and correlations) regarding the suitability and
    validation of all models used for the analysis of the system.

&lt;8.2.4&gt; Requirements status log

a.  The DJF shall include a requirement status log addressing each
    requirement in turn, and including the

    1.  reference to relevant elements of the verification plan,

    2.  synthesis of the justifications acquired, calling up references
        to the supporting activities and evidence (e.g. Technical Notes
        listed in section K.2.1&lt;4&gt;),

    3.  list of justifications to be acquired and related activities,

    4.  conclusion / action flag.

&lt;8.2.5&gt; Manufacturing process status log

a.  The DJF shall include a requirement status log, addressing design
    relevant aspects of manufacturing processes, and recording their
    characteristics in regard to qualification.

    1.  Acceptance verification

<!-- -->

a.  The DJF shall present the implementation of the acceptance
    verification and the status thereof, addressing the detailed
    definition of acceptance activities (e.g. inspection, test,
    analysis), including the detailed definition of the tests, the
    prediction of expected test results, test success criteria, and test
    specifications.

<!-- -->

1.  Details on test specifications are provided in ECSS-E-ST-10-03
    > Annex B.

    a.  The DJF shall cover the system and all disciplines relevant to
        the product, addressing all acceptance verification activities
        in line with the system verification Plan (VP).

    <!-- -->

    1.  Justification of System Technical Budgets and Margins

    <!-- -->

    a.  The DJF shall present a synthesis of all technical budgets and
        margins for specific parameters according to the functional and
        physical architectures.

2.  For technical budgets and margins, see ECSS-E-ST-10 Annex I.

    1.  Justification of Constraints imposed by the System Design

        1.  Design constraints on the production

    <!-- -->

    a.  The DJF shall present the justification of constraints induced
        by the system or product design definition on the production
        activities e.g. operational allowable envelopes, restrictions on
        assembling sequences, procedures and testing modes, exclusion
        zones, manufacturing environmental conditions, and conditions
        for procurement.

        1.  System design constraints for operation

    <!-- -->

    a.  The DJF shall present the justification of constraints induced
        by the system or product design definition on the implementation
        of the operations e.g. operational allowable envelopes,
        restrictions on operating modes, and exclusion zones.

        1.  System design constraints for transportation and storage

    <!-- -->

    a.  The DJF shall present the justification of constraints induced
        by the system or product design definition on the transportation
        activities and during the periods of storage of the product e.g.
        allowable envelopes, restrictions on transportation and storage,
        exclusion zones, packaging, shock levels, temperature
        environments, humidity, cleanliness, regulations, and dangerous
        materials.

        1.  System design constraints for maintainability

    <!-- -->

    a.  The DJF shall present the justification of constraints induced
        by the system or product design definition on the maintenance
        activities and procedures e.g. operational allowable envelopes,
        accessibility, tooling, support materials, parts availability,
        and deliveries.

    <!-- -->

    1.  Constituent documents

    <!-- -->

    a.  The DJF shall integrate or refer to the documents that conform
        to the:

        1.  ECSS-E-ST-10 Annex L, Trade-Off-Report - DRD

        2.  ECSS-E-ST-10 Annex Q, Analysis Report - DRD

        3.  ECSS-E-ST-10 Annex O, Requirement Justification File - DRD

        4.  ECSS-E-ST-10 Annex N, Requirements Traceability Matrix – DRD

        5.  ECSS-E-ST-10-02 Annex B, Verification Control Document - DRD

        6.  ECSS-E-ST-10-02 Annex C, Test Report - DRD

        7.  ECSS-E-ST-10-02 Annex D, Review Of Design Report - DRD

        8.  ECSS-E-ST-10-02 Annex E, Inspection Report - DRD

        9.  ECSS-E-ST-10-02 Annex F, Verification Report - DRD

    b.  The DJF shall include or refer to the DJF of lower level
        elements of the product.

    <!-- -->

    1.  Special remarks

None.

A.  [[]{#_Ref173828960 .anchor}]{#__RefHeading___Toc223952990
    .anchor}(normative)\
    Trade-off report - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1ss.

1.  Purpose and objective

The Trade-off report provides the system-engineering point of view on
alternative design solutions, an evaluation and a classification of the
alternative design solutions, and the justification of their ranking.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The trade-off report shall contain a description of the
            purpose, objective, content and the reason prompting its
            preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The trade-off report shall list the applicable and reference
            documents in support to the generation of the document and
            include the reference to the following applicable documents:

            1.  Mission description document, if relevant

            2.  Technical requirements specification

            3.  System engineering plan

            4.  Project phasing and planning requirement document.

        <!-- -->

        1.  Objective and context of the trade-off study

        <!-- -->

        a.  The trade-off report shall contain a brief description of
            the purpose of the trade-off study and its context (e.g.
            logic, organization, process or procedure).

        <!-- -->

        1.  Key technical requirements

        <!-- -->

        a.  The trade-off report shall list the key technical
            requirements from the TS (as defined in ECSS-E-ST-10-06) to
            be satisfied by the possible alternative design solutions to
            conform to the needs or requirements of the user.

        b.  The research of possible alternative design solutions should
            not preclude the identification of design solutions which
            are not currently mature enough, but which can be potential
            design solution for future similar applications.

<!-- -->

1.  A possible design solution is a technical answer that has the
    > capability to meet a set of technical requirements.

    a.  The system trade-off report shall identify and present the
        sources of information used to identify the possible design
        solution, e.g. R&D results, lessons learned, or similar
        applications.

    <!-- -->

    1.  Evaluation criteria

    <!-- -->

    a.  The trade-off report shall list the selected evaluation criteria
        and precise the justification for selecting those criteria, and
        provide the weighting of criteria and their justifications.

2.  The criteria are selected theme by theme from the Technical
    > Specification (as defined in ECSS-E-ST-10-06 Annex A), the
    > programmatic aspects (including e.g. budget, schedule, etc… for
    > development, manufacturing, as well as target cost for operations
    > and recurrent items), and the technical risks.

    a.  The trade-off report shall identify the entity responsible for
        the evaluation of the design solutions for any criteria, as well
        as the source and agreement regarding weighting factors (e.g.
        with management).

    <!-- -->

    1.  Presentation of the alternative design solutions

    <!-- -->

    a.  The trade-off report shall present every different alternative
        design solutions proposed by the organization in charge of the
        development of the system or product, the proposals from the
        customer and supplier if any, and emphasize the technical
        description that is correlated to the criteria of evaluation.

    b.  The trade-off report shall characterize each alternative design
        solution in terms of technology status or maturity, performances
        capability, and risks.

    <!-- -->

    1.  Evaluation of the alternative design solutions

    <!-- -->

    a.  The system trade-off report shall present the result of the
        evaluation of every identified alternative design solution with
        regard to the key technical requirements.

    b.  For each alternative design solution the following shall be
        performed:

        1.  assessment of all the key technical requirements /
            evaluation criteria,

        2.  presentation of the pros and cons of the design solution,
            and

        3.  identification of the technical and programmatic risks.

    c.  The trade-off report shall present, in a table, the result of
        the evaluation per criteria.

    <!-- -->

    1.  Classification of the alternative design solutions

    <!-- -->

    a.  Based on the proposed scheme for weighting the evaluation
        criteria, the trade-off report shall provide a classification of
        the different alternative design solutions.

    <!-- -->

    1.  Analysis of the robustness of the classification

    <!-- -->

    a.  The trade-off report shall provide the result of a sensitivity
        analysis of the criteria that provide advantage to the solution
        ranked first, e.g. when changing the weighting of the evaluation
        criteria.

    <!-- -->

    1.  Conclusion

    <!-- -->

    a.  The trade-off report shall recommend one solution and explain
        the reason for this choice (e.g. evaluation criteria where the
        selected solution take advantage), and precise the condition for
        the application of the recommended solution.

    b.  The trade-off report shall present the identified technical and
        programmatic risks induced by the choice of the recommended
        solution, and any additional activity necessary to be performed
        for risk mitigation.

    <!-- -->

    1.  Special remarks

None.

A.  [[]{#_Ref173817064 .anchor}]{#__RefHeading___Toc223952991
    .anchor}(normative)\
    Interface requirement document (IRD) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1ssss.

1.  Purpose and objective

For a product, the interface requirement document (IRD) is a specific
type of technical specification that defines the requirements for the
interfaces among the items - at the same level in the product tree
structure - constituting this product.

The IRD is a document either included in or called up by the technical
requirements specification (TS) (as defined in ECSS-E-ST-10-06 Annex A)
of the product.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The IRD shall contain a description of the purpose,
            objective, content and the reason prompting its preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The IRD shall list the applicable and reference documents in
            support to the generation of the document.

        b.  The IRD shall include the following references:

            1.  Product tree (as defined in ECSS-M-ST-10 Annex B)

            2.  Specification tree (as defined in ECSS-E-ST-10 Annex J).

        <!-- -->

        1.  Interface requirements

        <!-- -->

        a.  The interface requirements shall be grouped per couple of
            product elements having an interface.

        b.  The interface requirements shall be expressed according to
            ECSS-E-ST-10-06.

        c.  The interface requirements shall be grouped per nature of
            interface.

<!-- -->

1.  For example: Nature of interface includes, but is not restricted to,
    > mechanical, electrical, thermal and software interfaces.

    1.  Special remarks

        a.  The content of the IRD may be merged with the content of the
            technical requirements specification (as defined in
            ECSS-E-ST-10-06 Annex A) of the elements of the product.

<!-- -->

A.  [[]{#_Ref173828992 .anchor}]{#__RefHeading___Toc223952992
    .anchor}(normative)\
    Requirements traceability matrix (RTM) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement j.

1.  Purpose and objective

The requirement traceability matrix (RTM) defines the relationships
between the requirements of a deliverable product defined by a technical
requirements specification and the apportioned requirements of the
product's lower level elements.

The purpose of the RTM is to help verify that all stated and derived
requirements are allocated to system components and other deliverables
(forward trace).

The matrix is also used to determine the source of requirements
(backward trace). Requirements traceability includes tracing any
information that satisfy the requirements such as capabilities, design
elements, and tests.

The RTM is also used to ensure that all requirements are met and to
locate affected system components when there is a requirements change.
The ability to locate affected components allows the impact of
requirements changes on the system to be determined, facilitating cost,
benefit, and schedule determinations.

1.  Expected response

    1.  Scope and content

        1.  Introduction

        <!-- -->

        a.  The RTM shall contain a description of the purpose,
            objective, content and the reason prompting its preparation.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The RTM shall list the applicable and reference documents in
            support to the generation of the document.

        b.  The RTM shall include the following:

            1.  Technical requirements specification (as defined in
                ECSS-E-ST-10-06 Annex A) of the product and its lower
                level elements

            2.  Product tree (as defined in ECSS-M-ST-10 Annex B)

            3.  Specification tree (as defined in ECSS-E-ST-10 Annex J).

        <!-- -->

        1.  Requirement traceability

        <!-- -->

        a.  The RTM shall list all the technical requirement of the
            product TS.

        b.  The RTM shall list all the lower level elements constituting
            the product and their technical requirements (contained in
            the lower-level element TS).

        c.  The requirement identification shall be identical in the RTM
            and the different TS.

        d.  Each technical requirement of the product shall be linked to
            at least one requirement of a lower level element.

<!-- -->

1.  The required visibility of the traceability down the elements of the
    > product tree is depending on the criticality of some lower level
    > elements w.r.t. the product requirements.

    a.  Each technical requirement of a lower level element should be
        linked to a technical requirement of the product.

    b.  When a technical requirement of a lower level element is not
        linked to a technical requirement of the product, this
        requirement shall be justified and an evaluation of its
        existence or removal on the product shall be agreed between the
        customer and the supplier.

    <!-- -->

    1.  Special remarks

None.

A.  [[]{#_Ref173828982 .anchor}]{#__RefHeading___Toc223952993
    .anchor}(normative)\
    Requirements justification file (RJF) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1h.

1.  Purpose and objective

The requirement justification file (RJF) is a generic title referring to
all documentation which:

-   Records and describes the needs and the associated constrains
    resulting from the different trade-offs.

-   Demonstrates how the requirements of the technical requirements
    specification (TS) (as defined in ECSS-E-ST-10-06 Annex A) at each
    level can satisfy the needs and the constraints of the TS of the
    level above.

1.  A top level RJF document is established at the upper level of the
    > project structure that is, according to ECSS-M-ST-10, the
    > first-level customer situated at level 0 of the customer supplier
    > network. For other levels, the RJF is part of the design
    > justification file (DJF) (as defined in, Annex K).

    1.  Expected response

        1.  Scope and content

            1.  Introduction

            <!-- -->

            a.  The RJF shall contain a description of the purpose,
                objective, content and the reason prompting its
                preparation.

            <!-- -->

            1.  Applicable and reference documents

            <!-- -->

            a.  The RJF shall list the applicable and reference
                documents in support to the generation of the document.

            b.  The RJF shall include the reference to the technical
                requirements specification.

            <!-- -->

            1.  Selected concept/solution justification

            <!-- -->

            a.  The RJF shall present the rationale for the selection of
                a concept for the technical requirements specification.

2.  For justification, reference can be made to the system concept
    > report of the considered project.

    1.  Life profile justification for the selected concept/solution

    <!-- -->

    a.  The RJF shall present and justify the life profile situations
        for the concept presented in the technical requirements
        specification.

3.  For justification, reference can be made to the system concept
    > report of the considered project where relevant.

    1.  Environments and constraints justification

    <!-- -->

    a.  The RJF shall present and justify the different environments and
        constraints for each life profile situations for the concept
        presented in the technical requirements specification.

4.  For justification, reference can be made to the system concept
    > report of the considered project where relevant.

    1.  Technical requirements justification

    <!-- -->

    a.  The RJF shall list all the technical requirements, and their
        identifier, expressed by the corresponding TS as they are
        organized in these documents.

    b.  For each technical requirement the following information shall
        be provided:

        1.  the justification of the requirement (i.e. justified
            source),

        2.  the Entity or owner responsible for the requirement,

        3.  if one technical requirement is induced by several sources,
            the reason of the specified performance,

        4.  the justification of the quantified performance (such as the
            range, the approach used to determine the level, e.g.
            measure, estimation),

        5.  the justification of the selected verification method.

    <!-- -->

    1.  Requirement traceability

    <!-- -->

    a.  The RJF shall present the requirement traceability between the
        technical requirements of the TS, and their justified source.

    <!-- -->

    1.  Compliance matrix for COTS

    <!-- -->

    a.  For COTS, the RJF shall contain a compliance matrix between the
        technical specification/characteristics of the COTS and the
        technical requirement expressed by the TS.

    <!-- -->

    1.  Special remarks

        a.  The RJF may be part of the design justification file (DJF)
            (as defined in ECSS-E-ST-10 Annex K).

<!-- -->

A.  [[]{#_Ref173840834 .anchor}]{#__RefHeading___Toc223952994
    .anchor}(normative)\
    Product user manual (PUM or UM) - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10 requirement ttt.

1.  Purpose and objective

The objective of the product user manual (PUM) is to provide information
on design, operations and data of the product that is required by the
user to handle, install, operate, maintain and dispose the product
during its life time.

1.  Expected response

    1.  []{#_Ref223867440 .anchor}Scope and content

        1.  Introduction

        <!-- -->

        a.  The introduction shall describe the purpose and objective of
            the PUM.

        <!-- -->

        1.  Applicable and reference documents

        <!-- -->

        a.  The PUM shall list the applicable and reference documents in
            support of the generation of the document.

        <!-- -->

        1.  Product function definition

            1.  Product expected functions

        <!-- -->

        a.  The PUM shall provide a general description of the expected
            functions of the product during its lifetime in expected
            operational context and environment.

            1.  Product functional constraints

        <!-- -->

        a.  The PUM shall describe all product functional constraints.

            1.  Life time phases and purposes

        <!-- -->

        a.  The PUM shall address the whole product life cycle and all
            its modes:

            1.  Handling

            2.  Storage

            3.  Installation

            4.  Operations (nominal and contingency)

            5.  Maintenance

            6.  Disposal.

        <!-- -->

        a.  The PUM shall consider potential consequences of the
            environment on those sequences (e.g. sensor blinding,
            eclipses);

        <!-- -->

        1.  Product description

            1.  Design summary

        <!-- -->

        a.  The PUM shall include the following:

            1.  summary of the product design, showing the definition of
                the product, its constituents, the distribution of
                functions and the major interfaces;

            2.  block diagram of the product;

            3.  top-level description of the product software
                architecture;

            4.  description of nominal product operations scenarios and
                constraints e.g. mutually exclusive modes of operation,
                power or resource sharing.

            <!-- -->

            1.  Product level autonomy

        <!-- -->

        a.  The PUM shall include the following:

            1.  description of product-level autonomy provisions in the
                areas of fault management (FDIR);

            2.  definition, for each autonomous function, of the logic
                or rules used and of its internal (product constituents)
                and external interfaces.

            <!-- -->

            1.  Product configurations

        <!-- -->

        a.  The PUM shall include the following:

            1.  drawings of the overall product configuration in all
                product modes;

            2.  definition of the product reference axes system(s);

            3.  drawings of the product layouts.

            <!-- -->

            1.  Product budgets

        <!-- -->

        a.  The PUM shall provide the distribution (or allocation) of
            the following budgets, per product constituent, or per
            operating mode, as appropriate:

            1.  mass properties;

            2.  alignment;

            3.  power consumption for all operational modes;

            4.  thermal budget and constraints and predictions;

            5.  Description of interfaces and related budgets. (e.g. RF
                links);

            6.  telemetry and telecommand date rates;

            7.  memory;

            8.  timing.

            <!-- -->

            1.  Interface specifications

        <!-- -->

        a.  The PUM shall provide a cross-reference to the applicable
            version of the ICD.

            1.  Handling

        <!-- -->

        a.  The PUM shall describe the conditions and procedures for the
            handling of the product, be it integrated or stand-alone.

        b.  The PUM shall describe the specific design features,
            transport and environmental conditions, required GSE, and
            limitations for the handling of the product.

            1.  Storage

        <!-- -->

        a.  The PUM shall describe the conditions and procedures for the
            storage of the product, be it integrated or stand-alone.

        b.  The PUM shall describe the specific design features,
            environmental conditions, required GSE, monitoring
            requirements, life-limited items, health maintenance
            procedures (activation, monitoring) and limitations for the
            storage of the product.

            1.  Installation

        <!-- -->

        a.  The PUM shall describe the conditions and procedures for the
            installation of the product, be it integrated or
            stand-alone.

        b.  The PUM shall describe the specific design features,
            required GSE, modes, environmental conditions, and
            limitations for the installation of the product.

            1.  Product operations

&lt;4.9.1&gt; General

a.  The PUM shall include timelines, modes and procedures, constraints
    to operate the product during its life cycle in nominal and
    contingency conditions, and highlight critical operations.

<!-- -->

1.  1 When the product is a space segment, the product operations
    > aspects are included in a specific part of the UM called Flight
    > Operations Manual (FOM).

2.  2 The implementation of the FOM by the ground segment responsible
    > organisation is contained in the Mission Operations Plan (MOP, as
    > defined in ECSS-E-ST-70 Annex G).

&lt;4.9.2&gt; Timelines

a.  The PUM shall include:

    1.  Baseline event timelines for all nominal and contingency modes
        and phases.

    2.  Related constraints.

b.  Each timeline shall contain a detailed description (i.e. down to the
    level of each single operational action) of the complete sequence of
    operations to be carried out, including a description of the
    rationale behind the chosen sequence of events, a definition of any
    constraints (e.g. absolute timing, relative timing) and the
    interrelationships between operations in the sequence.

&lt;4.9.3&gt; Product modes

a.  The PUM shall describe all nominal and contingency modes, including:

    1.  their purpose (i.e. circumstances under which they are used),

    2.  the related procedures,

    3.  operational constraints,

    4.  resource utilization,

    5.  the definition of the associated modes, and

    6.  monitoring requirements.

b.  The PUM shall describe the allowable mode transitions and the
    operations procedure corresponding to each such transition.

c.  Appropriate cross-reference shall be made to product constituent
    modes and procedures.

&lt;4.9.4&gt; Product failure analysis

a.  The PUM shall provide the results of the product failure modes,
    effects and criticality analysis (FMECA) and the resulting list of
    single point failures.

b.  Potential product failures shall be identified by means of a
    fault-tree analysis (FTA).

    1.  Maintenance

<!-- -->

a.  The PUM shall describe the conditions, procedures and logistics for
    the maintenance of the product, be it integrated or stand-alone.

<!-- -->

1.  The description can refer to the document that conforms to the
    > Integrated Logistic Support Plan in conformance with ECSS-M-ST-70.

    1.  Disposal

    <!-- -->

    a.  The PUM shall describe the conditions and procedures for the
        disposal of the product, be it integrated or stand-alone.

    b.  The procedures shall include passivation, as relevant.

    c.  The PUM shall identify the risks during and after disposal.

    <!-- -->

    1.  Products constituents description

        1.  General

    <!-- -->

    a.  The information specified in P.2.1&lt;5.2&gt; to
        P.2.1&lt;5.9&gt; shall be provided for each product constituent.

        1.  []{#_Ref212635408 .anchor}Product constituent design summary

    <!-- -->

    a.  The PUM shall describe the product constituent including:

        1.  the overall functions of the product constituent and the
            definition of its operational modes during the different
            mission phases;

        2.  description of any product constituent management functions,
            fault management concept and redundancy provisions;

        3.  a summary description of the component units/equipment and
            software including the functions which each supports;

        4.  product constituent functional block diagrams and a diagram
            showing the source of telemetry outputs and the sink of
            telecommand inputs;

        5.  interfaces;

        6.  budgets.

        <!-- -->

        1.  Product constituent design definition

    <!-- -->

    a.  The following shall be provided for each product constituent:

        1.  a detailed design description, including block diagrams,
            functional diagrams, logic and circuit diagrams;

        2.  physical characteristics including location and connections
            to the support structure, axes definition and alignment
            where relevant, dimensions and mass properties;

        3.  principle of operation and operational constraints of the
            product constituent;

        4.  if a product constituent is composed of many complex
            elements, it may be necessary to provide a lower level of
            breakdown.

        <!-- -->

        1.  Software

    <!-- -->

    a.  The PUM shall include:

        1.  description of software design,

        2.  product constituent software,

        3.  application process service software, and

        4.  memory map.

    b.  The PUM shall describe the organization of the software and its
        physical mapping onto hardware.

    c.  The PUM shall describe the details of each software component
        i.e. scheduler, interrupt handler, I/O system, telecommand
        packet handling system, telemetry packet handling system,
        including for each component its functions, component routines,
        input/output interfaces, timing and performance characteristics,
        flowcharts and details of any operational constraints.

    d.  For the application process service software, the PUM shall:

        1.  describe the services implemented making cross-reference to
            ECSS-E-ST-70-41 “Telemetry and telecommand packet
            utilization”, as tailored for the mission;

        2.  summarize all telemetry and telecommand structures (e.g.
            packets) including the conditions under which they are
            generated, the generation frequency, content and
            interpretation.

    e.  For each memory block, a map shall be provided showing RAM and
        ROM address areas, areas allocated for program code, buffer
        space and working parameters (e.g. content of protected memory).

        1.  Product component performance

    <!-- -->

    a.  The PUM shall describe all relevant product constituent
        performance characteristics, define the expected performance
        degradation as a function of time during the mission, and
        identify the resulting impact in terms of modifications to
        operational requirements or constraints.

        1.  Product component telemetry and telecommand lists

    <!-- -->

    a.  For each product constituent, the following lists shall be
        provided:

        1.  a list of the housekeeping telemetry parameters;

        2.  a list of the telecommands.

    b.  Each housekeeping telemetry shall have a functional description
        with validity conditions, telecommand relationship, and all
        technical information necessary for using it.

    c.  Each telecommand shall have a functional description with
        utilization conditions (e.g. pre-transmission validity,
        criticality level), command parameters (syntax and semantics)
        and execution verification in telemetry.

        1.  Product component failure analysis

    <!-- -->

    a.  The PUM shall describe:

        1.  Identification of potential product constituent failures by
            means of a systematic failure analysis (including a
            subsystem FMECA and FTA).

        2.  Identification of the methods by which the higher levels can
            identify a failure condition from analysis of the telemetry
            data and isolate the source of the failure.

        <!-- -->

        1.  []{#_Ref212041387 .anchor}Product components operations

    <!-- -->

    a.  The PUM shall describe:

        1.  product constituent modes;

        2.  nominal operational procedures;

        3.  contingency procedures.

    b.  []{#_Ref212041391 .anchor}product constituent modes shall be
        defined for all distinct nominal and back-up modes of the
        subsystem including:

        1.  purpose (i.e. conditions under which each is used);

        2.  operational constraints;

        3.  resource utilization;

        4.  the definition of the associated modes for each product
            constituent and its software functions;

        5.  higher level monitoring requirements;

        6.  []{#_Ref212041403 .anchor}identification of the allowable
            mode transitions and any product constituent operational
            constraints.

    c.  []{#_Ref212041495 .anchor}Nominal operational procedures shall
        be defined for each nominal mode transition identified under
        P.2.1&lt;5.8&gt;b.6.

    d.  []{#_Ref212041756 .anchor}For each procedure described in
        P.2.1&lt;5.8&gt;c., the following shall be provided:

        1.  an introduction describing the purpose of the procedure and
            the phase(s) or conditions when applicable;

        2.  the body of the procedure, structured according to
            operational steps, including:

            a.  pre-conditions for the start of the step defining, where
                applicable:

-   product or product constituent level pre-requisites (e.g.
    > configuration and resource requirements, such as power, fuel);

-   external interfacing products pre-requisites.

    a.  telecommands to be sent;

    b.  telemetry data to be monitored to verify correct execution of
        the step;

    c.  interrelationships between steps (e.g. conditional branching
        within the procedure, timing requirements or constraints, hold
        and check points);

    d.  conditions for completion of the step.

    <!-- -->

    a.  Contingency procedures shall be defined for each failure case
        identified in the product constituent failure analysis
        (FMECA/FTA).

1.  This can utilize a nominal operational procedure already identified
    > in P.2.1&lt;5.8&gt;c. above.

    a.  For contingency procedures, the same details shall be provided
        as for nominal operational procedures in P.2.1&lt;5.8&gt;d.
        above.

    b.  Where the recovery method for a failure or group of failures is
        mode, mission, or phase dependent, separate procedures shall be
        described for each mode/mission phase.

        1.  []{#_Ref212635459 .anchor}Product component data definition

    <!-- -->

    a.  For each operational mode of the product constituent, sensor
        output data, conditions under which they are generated, their
        contents, and data rate shall be described.

    b.  Required on-board processing performed on sensor data and
        algorithms used for this shall be described.

    <!-- -->

    1.  Special remarks

        a.  Where the objective is to allow for the accommodation of
            equipment designed a posteriori w.r.t an existing platform
            or vehicle, the following documents shall be part of the UM:

            1.  The accommodation handbook describing the location,
                mounting, all interfaces and clearances of equipment in
                a platform or vehicle.

            2.  The installation plan describing the approach, methods,
                procedures, resources and organization to install,
                commission, and check the operation of the equipment in
                its fixed operational environment.

<!-- -->

A.  [[[]{#_Ref173840056 .anchor}]{#_Ref174180741
    .anchor}]{#__RefHeading___Toc223952995 .anchor}(normative)\
    Analysis report – DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-E-ST-10, requirement 1.1.1.1.1ll.

1.  Purpose and objective

The analysis report describes, for each analysis, the relevant
assumptions, utilized methods, techniques and results.

1.  When the analysis report is used for product verification purposes,
    > specific requirements as per clause Q.2.1.1.1&lt;8&gt; apply.

    1.  Expected response

        1.  []{#_Ref212636018 .anchor}Scope and content

            1.  Introduction

            <!-- -->

            a.  The analysis report shall contain a description of the
                purpose, objective, content and the reason prompting its
                preparation.

            b.  Any open issue, assumption and constraint relevant to
                this document shall be stated and described.

            <!-- -->

            1.  Applicable and reference documents

            <!-- -->

            a.  The analysis report shall list the applicable and
                reference documents in support to the generation of the
                document, and make a clear reference to the
                configuration baseline of the product considered for the
                analysis.

            <!-- -->

            1.  Definitions and abbreviations

            <!-- -->

            a.  The analysis report shall list the applicable dictionary
                or glossary and the meaning of specific terms or
                abbreviations utilized in the document with the relevant
                meaning.

            <!-- -->

            1.  Analysis approach

            <!-- -->

            a.  The analysis report shall summarize the analysis content
                and the method utilized.

            <!-- -->

            1.  Assumptions and limitations

            <!-- -->

            a.  The analysis report shall describe the basic
                assumptions, the boundary conditions, validity of the
                analysis, life profile aspects, and all other related
                limitations.

            <!-- -->

            1.  Analysis description

            <!-- -->

            a.  The analysis report shall describe and justify the
                analysis methods used including software, tools and
                associated models.

            <!-- -->

            1.  Analysis results

            <!-- -->

            a.  The analysis report shall present the main calculations,
                associated results, accuracies, sensitivities, margins
                where relevant.

            <!-- -->

            1.  []{#_Ref212636022 .anchor}Conclusions

            <!-- -->

            a.  The analysis report shall:

                1.  summarize the analysis results,

                2.  summarize the conditions of validity of this
                    analysis,

                3.  clearly state and describe any open issue.

            b.  Where the analysis report is used for the verification
                of requirements it shall list the requirements to be
                verified (in correlation with the VCD), summarize the
                analysis results, present comparison with the
                requirements, and indicate the verification closeout
                judgements (e.g. requirement met / not met).

        2.  Special remarks

None.

A.  [[]{#_Ref223950804 .anchor}]{#__RefHeading___Toc223952996
    .anchor}(informative)\
    Mapping of typical DDP to ECSS documents

+-----------------------------------+-----------------------------------+
| **Design Development Plan (DDP)   | **ECSS coverage**                 |
| content**                         |                                   |
+-----------------------------------+-----------------------------------+
| **Introduction**                  | M-ST-10 - PMP &lt;3&gt;           |
|                                   |                                   |
| -   General summary of the scope, | E-ST-10 - SEP &lt;3.1&gt;         |
|     objective and constraints     |                                   |
|                                   | M-ST-10 - PMP &lt;4&gt;           |
| -   Definition of                 |                                   |
|     responsibilities and          |                                   |
|     pre-requisites                |                                   |
+-----------------------------------+-----------------------------------+
| **System definition including     | M-ST-10 - PT                      |
| high level product tree**         |                                   |
|                                   | M-ST-60 - 9.6.2 req.              |
| -   Identification of customer    |                                   |
|     furnished products            | E-ST-10 - SEP &lt;4.2&gt;.6 and   |
|                                   | &lt;5.2.13&gt;                    |
| -   Availability of and need to   |                                   |
|     reuse existing products       | M-ST-10 - PT &lt;3&gt;.e          |
|                                   |                                   |
| -   Specification tree            | E-ST-10 - Annex J                 |
+-----------------------------------+-----------------------------------+
| **Technology assessment**         | E-ST-10 - SEP &lt;5.2.5&gt;       |
|                                   |                                   |
| Availability of and need to       | E-ST-10 - TP &lt;4.3&gt;          |
| develop new technologies          |                                   |
+-----------------------------------+-----------------------------------+
| **System design flow and          | E-ST-10 - SEP &lt;4.2&gt;.4       |
| philosophy of models**            |                                   |
|                                   | E-ST-10 - SEP &lt;4.2&gt;.5       |
| -   Model philosophy              |                                   |
|                                   |                                   |
| -   Design margin philosophy for  |                                   |
|     budgets                       |                                   |
|                                   |                                   |
|     -   Margin philosophy for     |                                   |
|         requirements as flown     |                                   |
|         down from system to       |                                   |
|         subsystem- assembly – and |                                   |
|         equipment level           |                                   |
|                                   |                                   |
|     -   Management of system      |                                   |
|         resource allocation over  |                                   |
|         the entire project phases |                                   |
|         and resource reporting to |                                   |
|         the next higher level     |                                   |
|                                   |                                   |
|     -   Rationale                 |                                   |
+-----------------------------------+-----------------------------------+
| **System control and              | E- ST-10 - SEP &lt;5.2.2&gt;      |
| verification**                    |                                   |
|                                   | -&gt; E- ST-10-02 - VP            |
| -   Qualification and acceptance  |                                   |
|     philosophy                    | -&gt; E- ST-10-02 - VCD (inc. VM) |
|                                   |                                   |
| -   Budget allocation philosophy  |                                   |
|                                   |                                   |
| -   Compliance to requirements    |                                   |
|     demonstration philosophy      |                                   |
|                                   |                                   |
| -   High-level Assembly,          |                                   |
|     Integration & Verification    |                                   |
|     Plan, incl.:                  |                                   |
|                                   |                                   |
|     -   end to end test           |                                   |
|                                   |                                   |
|     -   mission simulation and    |                                   |
|         Dress Rehearsals          |                                   |
+-----------------------------------+-----------------------------------+
| **Planning and definition of      | M- ST-10 - PMP &lt;7&gt;          |
| milestones and reviews**          |                                   |
| including the analysis of the     | -&gt; M- ST-60 - S                |
| critical path(s)                  |                                   |
|                                   | M- ST-10-01                       |
| -   definition and scope of       |                                   |
|     reviews in terms of           | E-ST-10 - SEP &lt;3.3&gt;         |
|                                   |                                   |
|     -   baselining of             |                                   |
|         requirements and          |                                   |
|         requirements control      |                                   |
|                                   |                                   |
|     -   design releases and       |                                   |
|         control of released       |                                   |
|         design including external |                                   |
|         and internal interfaces   |                                   |
+-----------------------------------+-----------------------------------+
| **Definition of required Ground   |                                   |
| Support Equipment** and schedule  |                                   |
| of development and delivery       |                                   |
+-----------------------------------+-----------------------------------+
| **Risk assessment** linked to     | E- ST-10 - SEP &lt;5.4&gt;        |
| development choices               | &lt;3.5&gt;                       |
|                                   |                                   |
|                                   | M- ST-80 - RAR                    |
+-----------------------------------+-----------------------------------+
| M-ST-10 - PMP                     | = ECSS-M-ST-10, Project           |
|                                   | management plan DRD - Annex A     |
+-----------------------------------+-----------------------------------+
| M-ST-10 - PT                      | = ECSS-M-ST-10, Product tree DRD  |
|                                   | - Annex B                         |
+-----------------------------------+-----------------------------------+
| M-ST-60 - S                       | = ECSS-M-ST-60, Schedule DRD -    |
|                                   | Annex B                           |
+-----------------------------------+-----------------------------------+
| M-ST-80 - RAR                     | = ECSS-M-ST-80, Risk assessment   |
|                                   | report DRD - Annex C              |
+-----------------------------------+-----------------------------------+
| E-ST-10 - SEP                     | = ECSS-E-ST-10, System            |
|                                   | engineering plan DRD - Annex D    |
+-----------------------------------+-----------------------------------+
| E-ST-10 - TP                      | = ECSS-E-ST-10, Technology plan   |
|                                   | DRD - Annex E                     |
+-----------------------------------+-----------------------------------+
| E-ST-10-02 - VP                   | = ECSS-E-ST-10-02, Verification   |
|                                   | plan DRD - Annex B                |
+-----------------------------------+-----------------------------------+
| E-ST-10-02 - VCD                  | = ECSS-E-ST-10-02, Verification   |
|                                   | control document DRD - Annex C\   |
|                                   | (Note: Verification matrix =      |
|                                   | 1^st^ issue of CVD)               |
+-----------------------------------+-----------------------------------+

 Bibliography

  --------------------- ----------------------------------------------------------------------------
  ECSS-S-ST-00          ECSS system – Description, implementation and general requirements
  ECSS-E-ST-10-03       Space engineering – Testing
  ECSS-E-ST-10-04       Space engineering – Space environment
  ECSS-E-ST-10-11       Space engineering – Human factors engineering
  ECSS-E-ST-20          Space engineering – Electrical and electronic
  ECSS-E-ST-3x series   Space engineering – Materials series
  ECSS-E-ST-40          Space engineering – Software general requirements
  ECSS-E-ST-50          Space engineering – Communications
  ECSS-E-ST-60          Space engineering – Control engineering
  ECSS-E-ST-70          Space engineering – Ground systems and operations
  ECSS-E-ST-70-41       Space engineering – Telemetry and telecommand packet utilization
  ECSS-E-HB-10          Space engineering – System engineering guidelines
  ECSS-E-TM-10-10       Space engineering – Logistic engineering
  ECSS-E-TM-10-20       Space engineering – Product data exchange
  ECSS-E-TM-10-21       Space engineering – System modelling and simulation
  ECSS-M-ST-60          Space project management – Cost and schedule management
  ECSS-M-ST-70          Space engineering – Integrated logistic support
  ECSS-M-ST-80          Space project management – Risk management
  ECSS-Q-ST-10          Space product assurance – Product assurance management
  IEEE P1220            Standard for application and management of the systems engineering process
  ISO/CD 24113          Space systems – Space debris mitigation
  --------------------- ----------------------------------------------------------------------------

[^1]: To be published.
