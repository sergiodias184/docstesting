-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Terms specific to the present
            standard](#terms-specific-to-the-present-standard)
        -   [Abbreviated terms](#abbreviated-terms)
    -   [\
        Objectives of availability
        analysis](#objectives-of-availability-analysis)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-Q-ST-30-09(31July2008).docx1//media/image1.jpeg){width="4.697916666666667in"
height="2.8333333333333335in"}

Space product assurance

Availability analysis

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

This Standard has been prepared by the ECSS Q-ST-30-09C Working Group,
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

Copyright: 2008 © by the European Space Agency for the members of ECSS

 Change log {#change-log .Contents}

  ------------------ -----------------------------------------------------------------------------------------------------------------------
  ECSS-Q-30-09A      First issue
                     
  7 December 2005    

  ECSS-Q-30-09B      Never issued

  ECSS-Q-ST-30-09C   Second issue
                     
  31 July 2008       Minor editorial update to conform to ECSS drafting rules and to be consistent with the renumbering of ECSS standards.
  ------------------ -----------------------------------------------------------------------------------------------------------------------

 Table of contents {#table-of-contents .Contents}

[1 Scope 6](#scope)

[2 Normative references 7](#normative-references)

[3 Terms, definitions and abbreviated terms
8](#terms-definitions-and-abbreviated-terms)

[3.1 Terms from other standards 8](#terms-from-other-standards)

[3.2 Terms specific to the present standard
8](#terms-specific-to-the-present-standard)

[3.3 Abbreviated terms 11](#abbreviated-terms)

[4 Objectives of availability analysis
12](#objectives-of-availability-analysis)

[5 Specifying availability and the use of metrics
13](#specifying-availability-and-the-use-of-metrics)

[5.1 General 13](#general)

[5.1.1 Introduction 13](#introduction)

[5.1.2 Availability requirements 13](#availability-requirements)

[5.2 Different ways of specifying availability
14](#different-ways-of-specifying-availability)

[5.2.1 Probability figure convention 14](#probability-figure-convention)

[5.2.2 Availability during mission lifetime for a specified service
14](#availability-during-mission-lifetime-for-a-specified-service)

[5.2.3 Availability at a specific time (or time interval) for a
specified service
15](#availability-at-a-specific-time-or-time-interval-for-a-specified-service)

[5.2.4 Percentage or number of successfully delivered products
16](#percentage-or-number-of-successfully-delivered-products)

[5.2.5 Outage probability distribution
16](#outage-probability-distribution)

[5.3 Metrics commonly used 17](#metrics-commonly-used)

[5.4 Metrics mapping 17](#metrics-mapping)

[5.4.1 General 17](#general-1)

[5.4.2 Metrics mapping at system or subsystem level
17](#metrics-mapping-at-system-or-subsystem-level)

[5.4.3 Metrics mapping at equipment level
18](#metrics-mapping-at-equipment-level)

[6 Availability assessment process 19](#availability-assessment-process)

[6.1 Overview of the assessment process
19](#overview-of-the-assessment-process)

[6.2 Availability allocation 20](#availability-allocation)

[6.3 Iterative availability assessment
21](#iterative-availability-assessment)

[6.4 Availability report content 23](#availability-report-content)

[7 Implementation of availability analysis
24](#implementation-of-availability-analysis)

[7.1 Overview 24](#overview-3)

[7.2 Availability activities and programme phases ^)^
24](#availability-activities-and-programme-phases)

[7.2.1 Feasibility phase (Phase A) 24](#feasibility-phase-phase-a)

[7.2.2 Preliminary definition phase (Phase B)
25](#preliminary-definition-phase-phase-b)

[7.2.3 Detailed definition and production phases (Phase C/D)
25](#detailed-definition-and-production-phases-phase-cd)

[7.2.4 Utilization phase (Phase E) 26](#utilization-phase-phase-e)

[Annex A (informative) Suitable methods for availability assessment
27](#__RefHeading___Toc205278588)

[A.1 Overview 27](#__RefHeading___Toc205278589)

[A.2 Analytical method 27](#__RefHeading___Toc205278590)

[A.3 Markov process 28](#__RefHeading___Toc205278591)

[A.4 Monte­Carlo simulation 29](#__RefHeading___Toc205278592)

[Annex B (informative) Typical work package description for availability
activities 30](#__RefHeading___Toc205278593)

[Bibliography 31](#bibliography)

Figures

[Figure 3‑1: Relations between the various values that characterize the
reliability, maintainability and availability of equipment
9](#__RefHeading___Toc205278595)

[Figure 6‑1: Availability assessment process
20](#__RefHeading___Toc205278596)

[Figure 6‑2: Example of a dynamic behaviour model
22](#__RefHeading___Toc205278597)

[Figure A-1 : Basic availability formulae
28](#__RefHeading___Toc205278598)

[Figure A-2 : Example of Markov graph 29](#__RefHeading___Toc205278599)

[Figure A-3 : Example of Petri net modelling
29](#__RefHeading___Toc205278600)

Tables

[Table 5‑1 Availability and supporting metrics applicable at
system and subsystem level 18](#__RefHeading___Toc205278601)

\
Scope
=====

This Standard is part of a series of ECSS Standards belonging to
ECSS‑Q‑ST-30, Space product assurance – Dependability. The present
standard defines the requirements on availability activities and
provides where necessary guidelines to support, plan and implement the
activities.

It defines the requirement typology that is followed, with regard to the
availability of space systems or subsystems in order to meet the mission
performance and needs according to the dependability and safety
principles and objectives.

This Standard also describes the process that is followed and the most
significant methodologies for the availability analysis to cover such
aspects as

-   evaluation of the space element or system availability figure,

-   allocation of the requirement at lower level, and

-   outputs to be provided.

This Standard applies to all elements of a space project (flight and
ground segments), where Availability analyses are part of the
dependability programme, providing inputs for the system concept
definition and design development.

The on­ground activities and the operational phases are considered, for
availability purposes, in order to

-   acquire additional information essential for a better system model
    finalization and evaluation, and

-   monitor the system behaviour to optimize its operational performance
    and improve the availability model for future applications.

This standard may be tailored for the specific characteristic and
constraints of a space project in conformance with ECSS-S-ST-00.

\
Normative references
====================

The following normative documents contain provisions which, through
reference in this text, constitute provisions of this ECSS Standard. For
dated references, subsequent amendments to, or revisions of any of these
publications do not apply. However, parties to agreements based on this
ECSS Standard are encouraged to investigate the possibility of applying
the most recent editions of the normative documents indicated below. For
undated references the latest edition of the publication referred to
applies.

  ----------------- ---------------------------------
  ECSS‑S‑ST‑00‑01   ECSS system — Glossary of terms
  ----------------- ---------------------------------

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms from other standards
        --------------------------

> For the purpose of this Standard, the terms and definitions from
> ECSS‑S‑ST‑00‑01- apply.

Terms specific to the present standard
--------------------------------------

1.  achieved availability

probability that a system, subsystem or equipment, when used under
stated conditions in an ideal support environment operates
satisfactorily at a given time

1.  The downtime is associated only to the active preventive and
    corrective maintenance.

<!-- -->

1.  active redundancy

every entity is operating and the system can continue to operate without
downtime or defects despite the loss of one or more entities

1.  corrective maintenance

maintenance performed to restore system hardware integrity following
anomalies or equipment problems encountered during system operations

1.  flight segment

product or a set of products intended to be operated in space

1.  ground segment

all ground infrastructure elements that are used to support the
preparation activities leading up to mission operations, the conduct of
mission operations and all post­operational activities

1.  hot redundancy

redundancy entity is “ON”, but not necessarily in the right
configuration to accomplish the function

1.  instantaneous availability

&lt;intrinsic or inherent&gt; probability that an item is in a state to
perform a required function under given conditions at a given instant in
time, assuming that the required external resources are provided

1.  Preventive maintenance is generally not taken into account for
    intrinsic availability.

<!-- -->

1.  instantaneous availability

&lt;operational&gt; probability that an item is in a state to perform a
required function under given conditions at a given instant of time,
taking into account the maintenance strategy (spares policy and related
in logistic delays and constraints)

1.  lead time (supplier delay)

mean time for supplier to provide spares (including shipping time)

1.  logistic delay

mean time for human and material maintenance means to be available
(call­out time)

1.  mean availability

&lt;intrinsic or inherent&gt; percentage of time that a system,
subsystem or equipment, used under stated conditions, without any
scheduled or preventive action and with ideal logistical support,
operates satisfactorily for a defined time period

1.  mean availability

&lt;operational&gt; percentage of defined time period in which a system,
subsystem or equipment, operates satisfactorily used under stated
conditions in an actual support environment

1.  The down time is relevant to the corrective maintenance, preventive
    maintenance, logistic and administrative delays.

<!-- -->

1.  mean down time

mean time between service interruption and service resumption

1.  See Figure Terms, definitions and abbreviated terms-1.

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-Q-ST-30-09(31July2008).docx1//media/image2.wmf){width="6.468055555555556in"
height="1.3479166666666667in"}

[[]{#_Ref201673826 .anchor}]{#__RefHeading___Toc205278595 .anchor}Figure
Chapter‑1: Relations between the various values that characterize the
reliability, maintainability and availability of equipment

1.  mean time between failures

mean time between two consecutive failures

1.  mean time between outages

mean time of operation of an entity between two consecutive
non­operational phases caused by corrective or preventive maintenance
activities

1.  mean time to failure

mean time of working of an entity before its first failure

1.  Also known as “mean time to first failure” (MTTFF).

<!-- -->

1.  mean time to outage

mean time of working of an entity before its first outage

1.  mean time to repair

mean duration to repair equipment with human and material maintenance
means being available

1.  mean up time

mean time of working of an entity after corrective maintenance (covering
repair and replacement)

1.  outage

state of an item of being unable to perform its required function

\[IEC Multilingual Dictionary:2001 edition\]

1.  1 Causes of outages can be failures, upsets or planned and unplanned
    events.

2.  2 The failures can be due to cataleptic intrinsic events or external
    events.

<!-- -->

1.  passive redundancy

redundancy not activated before necessary

1.  Also knows as “standby redundancy” or “cold redundancy”.

<!-- -->

1.  preventive maintenance

scheduled or on­condition maintenance actions performed on equipment to
reduce its probability of failure or degradation

1.  Preventive maintenance is performed to keep the system at designed
    reliability and safety levels before failure occurrence.

<!-- -->

1.  steady­state availability (asymptotic availability)

limit, if any, on the instantaneous availability as time approaches
infinite

Abbreviated terms
-----------------

For the purpose of this Standard, the abbreviated terms from
ECSS-S-ST-00-01 and the following apply:

  --------------- -------------------------------------------------
  Abbreviations   Meaning
  FMECA           failure modes, effects and criticality analysis
  GPS             global positioning system
  LD              logistic delay
  MDT             mean down time
  MTBF            mean time between failures
  MTBO            mean time between outages
  MTTF            mean time to failure
  MTTFF           mean time to first failure
  MTTO            mean time to outage
  MTTR            mean time to repair
  MUT             mean up time
  NRB             nonconformance review board
  PDF             probability density function
  RAM             reliability availability and maintainability
  SOW             statement of work
  TWT             travelling wave tube
  w.r.t.          with respect to
  --------------- -------------------------------------------------

\
Objectives of availability analysis
===================================

The availability analysis is developed in order to

-   verify the conformance of the selected system design with the
    applicable availability requirements, and

-   provide inputs to estimate the life cycle cost of the system.

The above design activity leads to the optimization of the system
concept definition with respect to design baseline, operations and
logistics provisions.

The availability analysis identifies the unavailability contributors in
order to quantify their impact in supporting the

-   decision making process, and

-   risk evaluation, reduction and control (see ECSS‑M‑ST-80).

The availability activity is fully integrated into the development
programme to ensure the correct support to the other disciplines
(e.g. engineering, operations and logistics).

1.  \
    Specifying availability and the use of metrics
    ==============================================

    1.  General
        -------

        1.  ### Introduction

The mission success criteria, from a probabilistic point of view, can be
established in different ways. As a consequence, the selection of the
most adequate dependability requirement depends on all of the
operational constraints and mission objectives.

1.  ### Availability requirements

    a.  Availability requirements shall respect the mandatory
        characteristics defined by the system engineering process.

<!-- -->

1.  E.g. traceable, identified, unique, or unambiguous.

    a.  For each availability requirement, a verification method shall
        exist.

    b.  Each availability requirement shall be a quantitative
        requirement.

    c.  The process leading to the definition of the availability
        requirement shall be user oriented (availability of mission
        service) and not design focused.

    d.  The process leading to the definition of the availability
        requirement shall include the following aspects necessary to
        characterize the project under development:

        1.  Functional and performances objectives.

2.  For example, what is the “threshold” between nominal behaviour and
    > failure mode? What are the contributors to mission success under
    > system visibility and responsibility?

    1.  “Environmental” conditions.

3.  For example, for which environment, interfaces, provisions,… shall
    > the above objectives be met?.

    1.  Operational time frame.

4.  For example, for which period, at what date.

    1.  Unavailability contributors to be taken into account in the
        analysis on the basis of the supplier’s visibility and
        responsibility for the logistic scenario or support.

5.  For example, detection, logistics, and administrative delays.

    a.  Availability requirements shall be specified according to one or
        several of the following classes of availability specifications
        detailed in clause 5.2.

    <!-- -->

    1.  Different ways of specifying availability
        -----------------------------------------

        1.  ### Probability figure convention

            a.  For each type of availability requirement, specified
                figures shall be defined as “mean” or “best estimate”
                probability figures (point estimation). Unit failure
                rates are generally computed in this way (or sometimes
                at 60 % confidence level).

        2.  ### Availability during mission lifetime for a specified service

            1.  #### Overview

Availability during mission lifetime for a specified service is
currently used for missions where a “steady-state” nominal service is
planned, and for which a percentage of the mission time can be specified
as an availability performance measure.

The availability during mission lifetime applies to maintainable,
on-ground or in-orbit (e.g. Space Station), and non-maintainable systems
(e.g. satellites).

Generic potential contributors for outage periods can be, for instance,
maintenance activities (preventive as far nominal service is impacted,
corrective), periodic manoeuvres, reconfiguration delays for redundant
payload, recoveries from safe mode, upsets, eclipses.

In some applications, the mission lifetime can be subdivided into
several periods for which the availability requirement applies.

1.  For example, “The system shall be operational during 11 months per
    year during the mission lifetime”.

    1.  #### Requirements

        a.  If the operative scenario duration is longer than the system
            or equipment mean down time (more than 5 MDT), so that the
            instantaneous or mean availability can reach an asymptotic
            (or steady state) behaviour, then the requirement shall be
            formulated in terms of steady­state availability, assuring a
            simplifying (and generally conservative) approach.

        b.  The availability during mission lifetime shall be computed
            as the ratio of time during which service is fulfilled over
            the total mission lifetime.

        c.  For non­maintainable systems, the availability during
            mission lifetime requirements shall be established
            considering that the mission is still operational at end of
            life.

2.  For example, no single point failure is considered as an
    unavailability contributor.

    a.  The availability during mission lifetime can take into account
        radiation’s effects: such as upset for logic parts, SET for opto
        and linear parts, and latch up.

    b.  Functional effects on equipment or subsystems due to radiation
        single events shall be evaluated to give quantified inputs to
        availability analyses.

3.  ECSS-Q-ST-60 branch standard gives methodology to evaluate behaviour
    of electronic parts within their functional conditions.

    1.  ### Availability at a specific time (or time interval) for a specified service

        1.  #### Overview

Availability at a specific time applies mainly for systems where
specific critical operations are scheduled in the mission timeline.
Typical applications are a launcher control bench availability at a
specific time or a scientific satellite with a planned comet rendezvous
mission.

1.  #### Requirements

    a.  The availability at a specific time requirement shall address
        the probability that this “quasi­instantaneous” operation is
        successfully handled.

    b.  For non­maintainable systems, the availability at a specific
        time requirement shall specify by a single requirement both the
        availability and reliability characteristic.

    c.  Availability at a specific time shall be computed considering
        the mission loss probability.

<!-- -->

1.  ### Percentage or number of successfully delivered products

    1.  #### Overview

For some applications, the user­oriented approach characterizes the
system in a “black­box” manner and specifying availability according to
the number off, for instance, delivered products, services, or mission
data with respect to user demands or nominal scenario.

1.  #### Requirements

    a.  If the availability is specified by a percentage or number of
        successfully delivered products, the availability requirement
        shall be expressed as follows:

        1.  A ratio of successfully delivered products over number of
            requested products.

<!-- -->

1.  For instance w.r.t. the applicable criteria for performance, delay,
    > and coverage.

    1.  Cumulated service hours during the mission.

2.  For example, expected number of TWTs × hours operation from a 12 out
    > of 16 redundant channels configuration over 10 years.

    1.  Acquired database volume or percentage.

3.  For example, geographical coverage for an Earth observation mission.

    1.  ### Outage probability distribution

        a.  In the specific case that the availability is specified by
            an outage distribution and duration, and if a maximum
            duration is specified, a probability of exceeding this
            duration shall be associated.

<!-- -->

1.  1 This can apply at subsystem level when a short service
    interruption is masked or filtered by the upper level function.

2.  2 For example, typically a GPS receiver temporary outage is
    tolerated by a navigation model. For this type of application,
    numerous short outages would be preferable to a few long ones.

    a.  If several classes of outage are identified, an availability
        specified through an outage probability distribution shall be
        allocated for each class (associated duration and
        probabilities).

    <!-- -->

    1.  Metrics commonly used
        ---------------------

        a.  The availability requirements shall be quantified using one
            or several of the following metrics:

            1.  inherent instantaneous availability;

            2.  operational instantaneous availability;

            3.  inherent mean availability;

            4.  operational mean availability;

            5.  inherent steady­state availability;

            6.  operational steady­state;

            7.  outage duration and occurrence;

            8.  MUT and MDT (or mean time to restore);

            9.  MTBF or MTBO, and MTTR;

            10. MTTF or MTTO;

            11. amount of successfully delivered products.

    2.  Metrics mapping
        ---------------

        1.  ### General

            a.  Following the definition of the system level
                availability requirements according to clause 5.2, the
                availability metrics and supporting metrics shall be
                selected according to Table Specifying availability and
                the use of metrics-1.

        2.  ### Metrics mapping at system or subsystem level

            a.  The metrics selection performed at system level depends
                on all of the mission characteristics, in particular,
                the choice between an instantaneous availability, mean
                availability or steady state availability shall be based
                on the mission time schedule.

            b.  The choice between Inherent and Operational availability
                shall be based on the possibility to access information
                from the logistic support analysis necessary to assess
                the Operational availability.

<!-- -->

1.  If logistic and administrative delays necessary to assess the
    Operational availability cannot be obtained, the achieved
    availability may be used as the metric to take preventive
    maintenance into account in the assessment.

    a.  The choice between MUT with MDT and outage distribution shall be
        based on the number or duration of mission specific events, or
        only on the mean values for up time and down time.

    <!-- -->

    1.  ### Metrics mapping at equipment level

        a.  The choice between MTBF with MTTR and outage distribution
            shall be based on the number or duration of mission specific
            events, or only on the mean values for up time and down
            time.

2.  For availability considerations, the equipment level refers to the
    lowest level of replaceable unit (LRU level).

> [[]{#_Ref205276365 .anchor}]{#__RefHeading___Toc205278601
> .anchor}Table Chapter‑1 Availability and supporting metrics applicable
> at system and subsystem level

  ------------------------- ----------------------------------------------- ------------------------------------- ---------------------------------------- ---------------------------- ------------------------------- ------------------------------------ -------------------------- -------------------------------- --------------------------------------- -------------------- ----------- ------------------------------------------
                                                                            Metric
                                                                            Inherent instantaneous availability
  System/ Subsystem level   Availability during mission lifetime            
                            Availability at a specific time interval        ♦
                            Outage probability distribution                 
                            Percentage of successfully delivered products   
  Equipment level           Availability during mission lifetime            
                            Availability at a specific time interval        
                            Outage probability distribution                 
                            Percentage of successfully delivered products   Not applicable at equipment level
  ------------------------- ----------------------------------------------- ------------------------------------- ---------------------------------------- ---------------------------- ------------------------------- ------------------------------------ -------------------------- -------------------------------- --------------------------------------- -------------------- ----------- ------------------------------------------

1.  \
    Availability assessment process
    ===============================

    1.  Overview of the assessment process
        ----------------------------------

The availability assessment process is represented as shown in Figure
Availability assessment process-2. The process steps identified in the
different sections of the figure are addressed in detail in clauses 6.2
through 6.4 and in Annex A for the assessment availability methods.

[[]{#ref201678470 .anchor}]{#_Ref201678470 .anchor}

[[]{#_Ref205276448 .anchor}]{#__RefHeading___Toc205278596 .anchor}Figure
Chapter‑2: Availability assessment process

1.  Availability allocation
    -----------------------

    a.  The availability allocation shall be based on the following:

<!-- -->

1.  subsystem failure’s effect on the mission derived from the system
    analysis,

    1.  previous experience from similar programmes,

    2.  subsystem complexity or cost,

    3.  subsystem technology maturity, and

    4.  previously designed and developed subsystem.

<!-- -->

1.  The criteria order of priority is application dependent.

    a.  The availability requirement allocation process shall be
        addressed early in the design phases (according to clause 7) in
        order to realistically evaluate the criticality of each system
        section and therefore the most appropriate baseline.

    <!-- -->

    1.  Iterative availability assessment
        ---------------------------------

        a.  A preliminary availability evaluation based on previous
            experience or judgement expertise shall be performed in
            order to assess a risk of not meeting the requirements.

2.  Such a preliminary availability evaluation is performed during the
    allocation process if a realistic allocation cannot be achieved.

    a.  The assessment process shall be conducted as follows:

    <!-- -->

    1.  Identification of the most appropriate method for availability
        assessment (see Annex A).

        1.  Collection and verification of data coming from the lower
            level analyses.

        2.  System availability assessment (including compliance
            verification) and identification of the project
            criticalities.

        3.  Architecture, operations or logistics modifications or more
            accurate analysis to reach the availability objective.

<!-- -->

1.  1 This can imply the subsystem or equipment level contribution.

2.  2 Example of a more accurate analysis is a refinement of the working
    hypothesis on the stand­by failure rates, more realistic modelling
    of the functional redundancies.

    1.  Decision making process to eliminate (or reduce the impact of)
        the criticalities.

    2.  Assessment process reiteration in each project phase according
        to the system design evolution.

    <!-- -->

    a.  An appropriate method, Analytic, Markovian or Monte­Carlo
        simulation, recognized as suitable for the assessment shall be
        used and the choice shall be explained and justified.

    b.  Sources of numerical data shall be provided.

<!-- -->

1.  For example, internal database from supplier data, field return
    experience, or calculation from standard handbooks, such as MIL HDBK
    217 or UTEC 80810.

    a.  Each equipment item’s availability shall be estimated, taking
        into account random and deterministic events.

2.  The dynamic behaviour models can be typically sketched as shown in
    Figure Availability assessment process-3. More complex flow charts
    can be developed depending on the system architecture and renewal
    process characteristics.

    a.  The results of availability analyses shall be reiterated in a
        timely manner through the design, integration processes and
        operation engineering to reflect the actual system baseline.

    b.  For flight equipment, the availability analysis shall take into
        account radiation effects.

3.  For example, upset for logic parts such as SET for opto and linear
    parts, and latch up.

    a.  Functional effects on flight equipment due to radiation single
        events shall be evaluated to provide quantified inputs for
        availability analysis.

4.  The ECSS‑Q‑ST-60 branch standard describes a methodology to evaluate
    behaviour of electronic parts within their functional conditions.

[[[[[[[[]{#_Ref201678450 .anchor}]{#_1275999303 .anchor}]{#_1275999319
.anchor}]{#_1278774797 .anchor}]{#_1279017848 .anchor}]{#_1279018945
.anchor}]{#_1279019481 .anchor}]{#_1279020260 .anchor}

[[]{#_Ref205277569 .anchor}]{#__RefHeading___Toc205278597 .anchor}Figure
Chapter‑3: Example of a dynamic behaviour model

1.  Availability report content
    ---------------------------

    a.  The availability analysis performed in each project phase shall
        contribute to the preparation of the following:

        1.  specifications,

        2.  trade­off reports, and

        3.  availability assessment reports.

    b.  With regard to the specifications, the requirements defined at
        lower level as a result of the allocation process shall be
        reported in a dedicated section.

    c.  The specifications section shall also include all the additional
        information (e.g. logistics constraints, operations provisions,
        and reference mission scenario) useful for the correct
        implementation of the requirements.

    d.  The availability evaluations and considerations shall be clearly
        described with the relevant data and assumptions.

    e.  The availability assessment report shall provide all the
        information needed to understand correctly the evaluations
        performed and to allow appropriate integration of the results
        obtained with the higher level analysis.

    f.  The availability assessment report shall cover the following
        aspects:

        1.  A self­standing description of the system or equipment
            baseline, logistics support and operations.

        2.  The content, derived from the relevant reports, useful for
            acquiring all the elements taken into account in the
            availability model.

        3.  The availability requirements description and interpretation
            (to enable the verification of the correct requirement
            implementation).

        4.  The availability model description (including details of the
            selected mathematical approach and relevant assumptions or
            hypotheses).

        5.  Inputs (e.g. reliability data, logistic times, and working
            hypotheses).

        6.  The results obtained.

        7.  The conclusions and recommendations.

    g.  The availability assessment reports shall be delivered at
        project review as per business agreement’s SOW.

<!-- -->

1.  \
    Implementation of availability analysis
    =======================================

    1.  Overview
        --------

Availability is regularly integrated into the design process. The
availability characteristics can be traded with other system attributes
such as cost and performance during the optimization of the design.

Availability teams are regularly integrated into the development teams
during the design process. Availability analysis should be performed in
close interaction with the following functions:

-   integrated logistics support;

-   operations;

-   engineering.

    1.  Availability activities and programme phases [^1]^)^
        ----------------------------------------------------

        1.  ### Feasibility phase (Phase A)

            a.  During Phase A, the availability analysis shall cover
                the following aspects:

                1.  Identification of the methodology for the most
                    realistic evaluation of the availability figures.

1.  The methodology can be improved or even changed in the following
    phases.

    1.  Support to the preliminary design definition in terms of
        trade­off studies, rough availability estimations,
        identification of critical areas.

    2.  Evaluation of the availability performance of the selected
        reference system or equipment baseline.

    3.  Allocation (where necessary) of the applicable requirements at
        lower level.

    4.  Planning of the availability tasks for the design definition
        phase (Phase B or Phase C).

    <!-- -->

    1.  ### Preliminary definition phase (Phase B)

        a.  During Phase B, the availability analysis shall cover the
            following aspects:

            1.  Finalization of the availability methodology.

            2.  A review of the lower level analyses.

            3.  Support to local trade­off studies and design
                definition.

            4.  Contribution to maintenance strategy definition.

            5.  Definition of input data for the availability model.

2.  E.g. manufacturer data, lower level outputs, data sources, and
    logistics information.

    1.  Evaluation of the availability performance of the selected
        reference system or equipment baseline.

    2.  Revision of the allocation process (where necessary).

    3.  Support to preparation of availability specifications.

    4.  Identification of the critical areas and support to the decision
        making process.

    5.  Planning of the availability tasks for the detailed design
        definition phase and development and preparation of the relevant
        section in the PA plan.

    <!-- -->

    1.  ### Detailed definition and production phases (Phase C/D)

        a.  During Phase C/D, the availability analysis shall cover the
            following aspects:

            1.  A review of the lower level analyses.

            2.  Consolidation of the input data (input data consistency
                check).

            3.  Support to the design, logistics and operations
                activities.

            4.  Contribution to design reviews.

            5.  Evaluation of the availability performance of the system
                or equipment baseline.

            6.  Identification of the critical parameters or points to
                be monitored or controlled.

            7.  Support to quality assurance activity during
                manufacture, integration and test, nonconformance review
                board (NRB) and failure review board.

            8.  Support flight readiness reviews.

    2.  ### Utilization phase (Phase E)

        a.  During Phase E, the availability analysis shall cover the
            following aspects:

            1.  Support to ground and flight operations.

            2.  Evaluation of the design and operational changes and
                their impacts on availability.

            3.  Collection of availability data during operation to
                assess the operational availability and issue of the
                operational availability report (when required).

<!-- -->

A.  [[[[]{#_Ref202257241 .anchor}]{#_Ref202257248
    .anchor}]{#_Ref203985620 .anchor}]{#__RefHeading___Toc205278588
    .anchor}(informative)\
    Suitable methods for availability assessment

    1.  []{#__RefHeading___Toc205278589 .anchor}Overview

This annex provides a short description of the main methods available to
assess availability performance.

The application of probability theory to the availability problems has
led to the development of different methodologies that allow all
practical situations to be managed with the accuracy required or
specified by the customer. The selection of a particular mathematical
approach depends on several considerations, such as:

-   a probability density function associated with the parameters
    involved;

-   complexity of the system design and associated operations and
    logistics support;

-   time constraints for project development;

-   preventive maintenance planned during the system’s operating life;

-   spares policy.

The main methods are listed in this annex; for further details, refer to
the technical literature on reliability and availability engineering.

1.  []{#__RefHeading___Toc205278590 .anchor}Analytical method

The calculations use the following mathematical modelling:

This generic formula can be adapted to the application (e.g. for
operational or intrinsic for system as well as equipment level).

For components or functions that are physically independent, the
resulting availability is evaluated using the basic formulae shown in
Figure 1.1, depending on the redundancy scheme.

[[[[[[[[]{#_1275999772 .anchor}]{#_1275999801 .anchor}]{#_1278774800
.anchor}]{#_1279017850 .anchor}]{#_1279018947 .anchor}]{#_1279019483
.anchor}]{#_1279019780 .anchor}]{#_1279020263 .anchor}

1.  []{#__RefHeading___Toc205278598 .anchor}:[]{#_Ref201679867 .anchor}
    Basic availability formulae

<!-- -->

1.  []{#__RefHeading___Toc205278591 .anchor}Markov process

This approach, shown in Figure 1.1, is based on the exponential law for
the time to failure and the time to repair. Markov process theory is
important because:

-   it provides a good representation of system behaviour for
    communication with the engineering teams, and

-   it allows the estimation of good approximations for the asymptotic
    (or steady­state) availability of some space applications, and has,
    for example, been efficiently applied to space ground segments.

However, the system complexity can generate a high number of expected
states that have impact on the calculation aspects (time and accuracy).
Realistic representation of logistic times (generally associated with
normal or log normal distributions) is also not possible. Markov Graph
is for a simple parallel model, states 1 and 2 representing a functional
system with or without redundancy being available for each state.

1.  []{#__RefHeading___Toc205278599 .anchor}:[]{#_Ref202258105 .anchor}
    Example of Markov graph

<!-- -->

1.  []{#__RefHeading___Toc205278592 .anchor}Monte­Carlo simulation

This numerical technique allows the evaluation of availability taking
into account, in a realistic way, all aspects associated with the
design, logistics and operations.

In a lot of applications, Petri nets are used to model the system
operating scenario, shown in Figure 1.1. The main advantages of
Monte­Carlo simulation are the ability to handle complex system
scenarios with deterministic or probabilistic delays, and one shot
reliability. However, this method can involve:

-   heavy effort for system modelling (not recommended for short­term
    programmes), and

-   long calculation times (not acceptable during the trade­off or
    feasibility study).

    1.  []{#__RefHeading___Toc205278600 .anchor}:[]{#_Ref202258144
        > .anchor} Example of Petri net modelling

A.  []{#__RefHeading___Toc205278593 .anchor}(informative)\
    Typical work package description for availability activities

The system or subsystem level RAM group can advantageously develop the
following activities accordingly to the business agreement’s SOW:

a.  Review the availability requirements and verify their acceptability
    with preliminary evaluations based on previous experiences or
    approximate models. This step is important for avoiding the
    implementation of unachievable requirements considering, among
    others, the allowed logistics support, operations provisions, and
    power and mass budget.

b.  Identify the most appropriate availability model taking into account
    the mission scenario, project complexity, and time and cost
    constraints. If the selected methodology is extended to a lower
    level, dedicated procedures shall be used.

c.  Prepare the lower level specification to translate the system
    availability requirements.

d.  Define the system availability model.

e.  Review the lower level availability reports.

f.  Verify and consolidate the inputs coming from the other design areas
    (e.g. engineering, logistics, and operations).

g.  Evaluate the system availability.

h.  Trade­off analysis.

i.  Provide support to project management to finalize the system
    operational cost.

j.  Availability activities progress reporting.

k.  Provide support to design reviews.

l.  Prepare audits to verify the subcontractors knowledge and
    organization relevant to the availability discipline.

m.  Support the logistics and operations department for specific
    probabilistic or qualitative assessments useful in the finalization
    of the availability model.

n.  Support during the system exploitation phase for:

    1.  data collection,

    2.  decision making process, and

    3.  optimization of system operation.

 Bibliography

  -------------- --------------------------------------------------------------------------------------------------------------------------
  ECSS-S-ST-00   ECSS system – Description, implementation and general requirements
  ECSS‑Q‑ST-30   Space product assurance ‑ Dependability
  ECSS‑M-ST-10   Space project management – Project planning and implementation
  ECSS‑M‑ST-80   Space project management ‑ Risk management
  MIL HDBK 217   Military handbook ‑ Reliability prediction of electronic equipment
  UTEC 80810     Modèle universel pour le calcul de la fiabilité prévisionnelle des composants, cartes et équipements électroniques, CNET
  -------------- --------------------------------------------------------------------------------------------------------------------------

[^1]: ^)^ For programme phases see ECSS‑M-ST-10.
