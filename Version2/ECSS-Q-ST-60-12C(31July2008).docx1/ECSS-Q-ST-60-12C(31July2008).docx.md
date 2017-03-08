-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
-   [Introduction](#introduction)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Terms specific to the present
            document](#terms-specific-to-the-present-document)
    -   [\
        Responsibilities ](#responsibilities)
        -   [Methodology](#methodology)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-Q-ST-60-12C(31July2008).docx1//media/image1.jpeg){width="4.697916666666667in"
height="2.8333333333333335in"}

Space product assurance

Design, selection, procurement and use of die form monolithic microwave
integrated circuits (MMICs)

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

This Standard has been prepared by the ECSS-Q-ST-60-12C Working Group,
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

 Change log

  ------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ECSS-Q-60-12A      First issue
                     
  25 August 2006     

  ECSS-Q-60-12B      Never issued

  ECSS-Q-ST-60-12C   Second issue
                     
  31 July 2008       The following editorial changes have been implemented to comply with the ECSS drafting rules:
                     
                     -   Terms and definitions have been divided in clauses 3.1 and 3.2.
                     
                     -   For synonymous, the ECSS format have been applied (see 3.2.11-3.2.13).
                     
                     -   When descriptive text and requirements were under the same heading, they have been split in two different headings (see e.g. 5.1).
                     
                     -   Clarifications to requirements have been presented as NOTES (see e.g. NOTE to 7.1.3).
                     
                     -   Each requirement has been given an individual identifier.
                     
                     -   Verbal forms have been used consistently, and in conformance with the ECSS drafting rules, and each requirement has been given an individual identifier (see e.g. 4.2).
                     
                     -   Requirements in tables have been moved to the body text (see 1.1.1.1.1zzzz, 1.1.1.1.1aaaaa and Table Application approval -2).
                     
                     -   Document requirement definitions in 7.2.1, 7.3.10, 7.3.13, 7.3.14, 1.1.1.1.1bbbbb, 1.1.1.1.1ccccc and 10.2.4.3 have been moved respectively to Annexes A, B, C, D, E and F.
                     
                     -   The following requirements have been reworded for clarity: 7.2.1, 7.2.10d, 1.1.1.1.1ssss, 1.1.1.1.1ddddd and 1.1.1.1.1pppppppp.2.
                     
                     -   Only documents explicitly called up in requirements have been included in Clause 2 “Normative references”. Only documents explicitly mentioned in the text (other than requirements) have been included in Bibliography. References not explicitly mentioned in the text have been included in informative Annex H “References”.
                     
  ------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 Table of contents {#table-of-contents .Contents}

[Change log 3](#change-log)

[Introduction 7](#introduction)

[1 Scope 8](#scope)

[2 Normative references 9](#normative-references)

[3 Terms, definitions and abbreviated terms
10](#terms-definitions-and-abbreviated-terms)

[3.1 Terms from other standards 10](#terms-from-other-standards)

[3.2 Terms specific to the present document
10](#terms-specific-to-the-present-document)

[3.3 Abbreviated terms 12](#abbreviated-terms)

[4 General requirements 14](#general-requirements)

[4.1 Overview 14](#overview)

[4.2 Flight model MMIC dies lots procurement
14](#flight-model-mmic-dies-lots-procurement)

[4.3 Minimum quality requirements 14](#minimum-quality-requirements)

[5 Selection 15](#selection)

[5.1 General 15](#general)

[5.1.1 Overview 15](#overview-1)

[5.1.2 Requirements 15](#requirements)

[5.2 Process selection 16](#process-selection)

[5.3 Models, and design tools 16](#models-and-design-tools)

[6 Responsibilities 17](#responsibilities)

[7 MMIC design 18](#mmic-design)

[7.1 Principles of MMIC design 18](#principles-of-mmic-design)

[7.1.1 Overview 18](#overview-2)

[7.1.2 General 18](#general-1)

[7.1.3 Number of design iterations 18](#number-of-design-iterations)

[7.1.4 Design trade­offs 19](#design-tradeoffs)

[7.2 Design tasks 19](#design-tasks)

[7.2.1 Electrical design specification
19](#electrical-design-specification)

[7.2.2 Design variations 19](#design-variations)

[7.2.3 Parasitic effects 19](#parasitic-effects)

[7.2.4 Transient simulation 20](#transient-simulation)

[7.2.5 Thermal analysis 20](#thermal-analysis)

[7.2.6 Sensitivity to temperature, process variation and supply voltages
20](#sensitivity-to-temperature-process-variation-and-supply-voltages)

[7.2.7 Design testability 21](#design-testability)

[7.2.8 Design stability analysis 21](#design-stability-analysis)

[7.2.9 Maximum rating and robustness 21](#maximum-rating-and-robustness)

[7.2.10 Layout optimization 22](#layout-optimization)

[7.2.11 DRC or ERC 22](#drc-or-erc)

[7.3 Design reviews 23](#design-reviews)

[7.3.1 General 23](#general-2)

[7.3.2 MMIC architecture 23](#mmic-architecture)

[7.3.3 Schematic 23](#schematic)

[7.3.4 Simulation results 23](#simulation-results)

[7.3.5 Sensitivity and stability analysis
24](#sensitivity-and-stability-analysis)

[7.3.6 Derating 24](#derating)

[7.3.7 Layout 24](#layout)

[7.3.8 Tests matrix 24](#tests-matrix)

[7.3.9 Assembly 24](#assembly)

[7.3.10 Compliance matrix 25](#compliance-matrix)

[7.3.11 MMIC detail specification 25](#mmic-detail-specification)

[7.3.12 Development plan 25](#development-plan)

[7.3.13 Design documentation 25](#design-documentation)

[7.3.14 MMIC summary design sheet 25](#mmic-summary-design-sheet)

[8 Application approval 26](#application-approval)

[8.1 General 26](#general-3)

[8.2 Test flow and test procedures 26](#test-flow-and-test-procedures)

[9 Procurement and LAT specification
28](#procurement-and-lat-specification)

[10 Procurement 29](#procurement)

[10.1 General 29](#general-4)

[10.1.1 Overview 29](#overview-3)

[10.1.2 Methodology 29](#methodology)

[10.2 Wafer screening and WAT 29](#wafer-screening-and-wat)

[10.2.1 General 29](#general-5)

[10.2.2 Wafer screening and WAT flows
29](#wafer-screening-and-wat-flows)

[10.2.3 Wafer manufacturing and control
30](#wafer-manufacturing-and-control)

[10.2.4 Wafer acceptance test 31](#wafer-acceptance-test)

[10.2.5 Packaging 32](#packaging)

[10.2.6 Deliverables 32](#deliverables)

[10.3 Dies incoming testing 33](#dies-incoming-testing)

[10.3.1 General 33](#general-7)

[10.3.2 Assembly test 33](#assembly-test)

[10.3.3 Visual inspection 34](#visual-inspection)

[10.3.4 Electrical characterization 34](#electrical-characterization)

[10.4 User LAT procurement sequences
35](#user-lat-procurement-sequences)

[10.4.1 General 35](#general-8)

[10.4.2 Sequence A: process, design and application validated
38](#sequence-a-process-design-and-application-validated)

[10.4.3 Sequence B: process validated and new design or new application
38](#sequence-b-process-validated-and-new-design-or-new-application)

[10.4.4 Sequence C: process, design and application not validated
39](#sequence-c-process-design-and-application-not-validated)

[10.4.5 Sequence D: application approval testing
40](#sequence-d-application-approval-testing)

[10.4.6 Destructive physical analysis after user LAT
40](#destructive-physical-analysis-after-user-lat)

[10.5 Failure criteria and lot failure
41](#failure-criteria-and-lot-failure)

[Annex A (normative) MMIC electrical design specification - DRD
42](#__RefHeading___Toc205199048)

[Annex B (normative) Compliance matrix for custom MMIC design - DRD
43](#__RefHeading___Toc205199049)

[Annex C (normative) Design package document - DRD
44](#__RefHeading___Toc205199050)

[Annex D (normative) MMIC summary design sheet - DRD
46](#__RefHeading___Toc205199051)

[Annex E (normative) MMIC procurement specification - DRD
47](#__RefHeading___Toc205199052)

[Annex F (normative) MMIC lot acceptance specification for user LAT -
DRD 48](#__RefHeading___Toc205199053)

[Annex G (normative) MMIC visual inspection summary sheet - DRD
50](#__RefHeading___Toc205199054)

[Annex H (informative) References 51](#__RefHeading___Toc205199055)

[Bibliography 52](#bibliography)

Figures

[Figure 10‑1: Wafer screening and WAT 30](#__RefHeading___Toc205199057)

[Figure 10‑2: Dies or die incoming testing
34](#__RefHeading___Toc205199058)

[Figure 10‑3: Acceptance flow for flight model die lots
35](#__RefHeading___Toc205199059)

[Figure 10‑4: User LAT flow 37](#__RefHeading___Toc205199060)

Tables

[Table 6‑1: Customer and supplier responsibilities for the “foundry” and
“catalogue” modes 17](#__RefHeading___Toc205199061)

[Table 8‑1: CTA tests and procedures for testing in sequence D
27](#__RefHeading___Toc205199062)

 Introduction

This Standard covers the design, selection, procurement and use of III‑V
monolithic microwave integrated circuits (MMICs) for space equipment.

It defines the design activity for the technical (methodology, phases to
be followed) and quality (quality assurance, design review) aspects,
and, the selection and procurement rules for these components taking
into account whether or not the processes have been validated.

\
Scope
=====

This Standard applies to all types of MMIC (monolithic microwave
integrated circuit) based on III‑V compound materials for RF
applications (i.e. frequency range ≥ 1 GHz). The requirements for the
procurement of components in die form are defined.

It is not within the scope of this Standard to address packaged MMICs
and discrete microwave components, these are dealt with in the relevant
ESCC specification (ESCC 9010 and ESCC 5010).

This standard may be tailored for the specific characteristic and
constraints of a space project in conformance with ECSS-S-ST-00.

\
Normative references
====================

The following normative documents contain provisions which, through
reference in this text, constitute provisions of this ECSS Standard. For
dated references, subsequent amendments to, or revisions of, any of
these publications do not apply. However, parties to agreements based on
this ECSS Standard are encouraged to investigate the possibility of
applying the most recent editions of the normative documents indicated
below. For undated references the latest edition of the publication
referred to applies.

  ----------------- -----------------------------------------------------------------------------------------
  ECSS‑S-ST‑00-01   ECSS system— Glossary of terms
  ECSS‑Q‑ST-30‑11   Space product assurance — Derating -‑ EEE components
  ECSS‑Q‑ST-60      Space product assurance ‑ Electrical, electronic and electromechanical (EEE) components
  ECSS‑Q‑ST-60‑05   Space product assurance — Generic requirements for hybrids
  MIL‑STD‑883       Tests methods and procedures for microelectronics
  ESCC 20600        Preservation, packaging and despatch of ESCC electronic components
  ESCC 24600        Minimum quality management system requirements
  ESCC 2049010      Internal visual inspection of monolithic microwave devices
  ESCC 2439010      Requirements for capability approval of MMICs
  ESCC 9010         Generic specification for MMICs
  ----------------- -----------------------------------------------------------------------------------------

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms from other standards
        --------------------------

For the purpose of this document, the terms and definitions given in
ECSS‑S‑ST‑00‑01 apply.

For the purpose of this document, the following term from
ECSS-Q-ST-60-05 applies:

**process identification document**

Terms specific to the present document
--------------------------------------

1.  batch lot

wafers from the same basic raw materials processed as a single set in
the manufacturing sequence (diffusion, metallization and passivation
process) in a limited and controlled period of time

1.  A unique identifier or code is assigned to a batch lot and to each
    wafer for processing traceability purposes.

<!-- -->

1.  design rules check

control procedure for verifying that design rules have been satisfied

1.  1 Design rules checks are generally issued by the supplier.

2.  2 DRC is performed using software.

<!-- -->

1.  designer

organization responsible for the design of the MMICs

1.  []{#_Ref201738195 .anchor}die lot

set of all dies coming from a single wafer lot

1.  electrical rule check

control procedure for verifying that the electrical rules have been
satisfied

1.  Electrical rules are generally issued by the manufacturer.

<!-- -->

1.  evaluated process

mature technology that has been successfully submitted to a set of
electrical and environmental testing to demonstrate performance and
reliability limits

1.  1 ECSS‑Q‑ST-60‑01 contains a list of evaluated processes.

2.  2 The ESCC 2269010 specification defines the requirements for the
    evaluation.

<!-- -->

1.  []{#_Ref201571139 .anchor}manufacturer

foundry responsible for the manufacturing of the MMICs

1.  process control monitor

test vehicle used by the supplier to assess the stability of the
manufacturing process by means of controls conducted during a wafer
production cycle

1.  The PCM is repeated a number of times (depending on the
    manufacturers) on each wafer lot. The measurements taken during the
    PCM are used to accept or reject the wafer according to the relevant
    DC and RF criteria defined in the design manual.

<!-- -->

1.  production lot

device types manufactured from the same basic raw materials on the same
production line, processed under the same manufacturing techniques and
controls using the same type of equipment

1.  A production lot may be composed of one or many batch lots.

<!-- -->

1.  qualified process

process that has been successfully submitted to a formal qualification
testing

1.  The ESCC 20100 specification defines the requirements for the
    qualification.

<!-- -->

1.  []{#_Ref201570205 .anchor}reticule

group of circuit layouts (MMIC, TCV, DEC, PCM) defined by design at the
mask level, for duplication over the entire wafer during the MMIC
manufacturing

1.  statistical process control

tool to control the quality and the stability of the technological
process

1.  SPC is implemented by measuring key parameters during the different
    manufacturing steps and their analysis using appropriate methods.

<!-- -->

1.  []{#_Ref201995549 .anchor}tile

See **reticule**

1.  user

entity responsible for the integration of the MMICs at upper level

1.  Example: MMICs are integrated by users into, for example, modules,
    hybrids, piece of equipment.

<!-- -->

1.  validated design

design that is successfully submitted to application approval testing
and an MMIC user LAT test

1.  validated process

process that is evaluated or qualified

1.  wafer lot

wafers manufactured from one or more batch lots

1.  Depending on the maturity of the process a wafer lot is defined as
    follows:

-   Case 1 (non­evaluated or qualified process): a wafer lot is a single
    wafer.

-   Case 2 (evaluated or qualified process and new MMIC design): a wafer
    lot is one batch lot.

-   Case 3 (mature process and recurrent MMIC design): a wafer lot is
    considered to be a production lot of 4 batches manufactured within a
    3 month period.

    1.  Abbreviated terms
        -----------------

For the purpose of this standard, the abbreviated terms of
ECSS-S-ST-00-01 and the following apply:

  -------------- -----------------------------------------
  Abbreviation   Meaning
  AQL            acceptance quality level
  CTA            circuit type approval
  DEC            dynamic evaluation circuit
  DRC            design rules check
  ERC            electrical rule check
  HTRB           high­temperature reverse bias
  LAT            lot acceptance test
  LTRB           low­temperature reverse bias
  MMIC           monolithic microwave integrated circuit
  PAD            part approval document
  PCM            process control monitor
  PID            process identification document
  RGA            residual gas analysis
  SAM            scanning acoustic microscopy
  SEM            scanning electron microscope
  SEU            single event upset
  SPC            statistical process control
  TCV            technological characterization vehicle
  WAT            wafer acceptance testing
  -------------- -----------------------------------------

1.  \
    General requirements
    ====================

    1.  Overview
        --------

This Clause defines the requirements for die MMIC procurement. It
completes the user LAT requirements for MMIC die lot procurement as
defined in ECSS‑Q‑ST-60‑05.

The responsibilities of the participants (e.g. designer, manufacturer or
end­user) are given from the prototype phase to the delivery of the dies
for flight model hybrid manufacturing.

1.  Flight model MMIC dies lots procurement
    ---------------------------------------

    a.  The following steps involved in procuring MMICs for Space
        applications shall be followed:

        1.  Process selection, in conformance with clause 5.

        2.  Allocation of responsibilities, in conformance with
            clause 6.

        3.  MMIC design, in conformance with clause 7.

        4.  Application approval, in conformance with clause 8

        5.  Procurement and LAT specifications, in conformance with
            clause 9.

        6.  Die form procurement sequences, in conformance with
            clause 10.

    b.  The requirements for the qualification and procurement of MMIC
        packaged devices given in ESCC 9010 shall apply.

2.  Minimum quality requirements 
    -----------------------------

    a.  The requirements for processing, production control and clean
        room conditions defined in ESCC 24600 shall apply.

    b.  The manufacturer shall implement and maintain a product quality
        programme, to ensure that reliability and quality is maintained
        throughout all the phases of manufacturing and testing in
        conformance with the requirements in ECSS‑Q‑ST-60.

<!-- -->

1.  \
    Selection
    =========

    1.  General
        -------

        1.  ### Overview

During the selection of the manufacturing process by the entity in
charge of the procurement, components are assessed for their conformance
to the requirements on reliability, application and environmental
resistance as defined for the project.

1.  ### Requirements

    a.  The selection of a foundry shall take into account the maturity
        of the technology, the validation status and the qualification
        domain as defined in ESCC 2439010.

    b.  The MMIC design shall be analysed and validated in terms of
        application domain compared to the qualification domain and
        space application requirements.

<!-- -->

1.  The qualification domain is documented in terms of the following
    boundaries with respect to any potential failure mode identified on
    the process:

-   The physical design and procedures that are closely related to the
    manufacturing process (no major process change identified since the
    evaluation testing).

-   The electrical design in term of extreme limits (thermal, DC and RF
    parameters).

-   Function (e.g. oscillator, gain block), and appli­cation (e.g. small
    signal, pulsed, high drive).

-   The performances, the reliability figures, and the environmental
    resistance.

    1.  Process selection
        -----------------

        a.  The selection of the foundry, and the manufacturing process,
            shall be justified by the supplier, and approved by the
            customer.

        b.  The agreement shall be based on the specific application for
            which the MMIC is designed and on further considerations
            such as:

            1.  The maturity of the process.

1.  E.g. large volume production or experimental technology.

    1.  The adequacy of the application to the electrical foundry
        manual, considering, as a minimum, the following items:

        a.  Equivalent circuits based on measurement results for all
            passive elements, including lumped and distributed
            components, in a format compatible for use with standard
            circuit simulators.

2.  E.g. transmission lines and discontinuities.

    a.  Small signal (at various bias points) and large signal models of
        active components based on measurement results, in a format
        compatible for use with standard circuit simulators.

3.  Example of such components are transistors, but also Schottky and
    varactor diodes.

    a.  Availability of standard components

4.  E.g. lange couplers.

    a.  Layout libraries, in a format compatible for use with standard
        circuit simulators.

    b.  Thermal, reliability, process variation design parameters.

    c.  Space evaluation or qualification status including the results
        of reliability evaluations performed by the foundry.

    <!-- -->

    a.  A foundry manual for each process used, shall be delivered to
        the customer (provided the current issue is not already
        available) prior to the design phase.

    b.  The MMIC specifications (satisfying the overall equipment
        requirements) shall be established within the technical limits
        of the MMIC process used, and be finalised following an
        iterative process.

    <!-- -->

    1.  Models, and design tools
        ------------------------

        a.  Only approved models (fully experimentally verified and
            included in the foundry manual) and design tools shall be
            used to design all the passive and active (linear and
            non­linear) elements.

        b.  Any non­standard models and design tools shall be justified,
            and approved by the customer.

\
Responsibilities 
=================

There are two modes for developing and procuring MMICs:

-   “Foundry” mode: the customer designs the MMIC and is entirely
    responsible for the design, and the supplier (or manufacturer) only
    guarantees the technology.

-   “Catalogue” mode: the supplier designs the MMIC and is entirely
    responsible for both the design and the technology, except for
    issues related to incompatibility between the MMIC and the
    environment in the customer application.

Table Responsibilities -1 summarizes the responsibilities of the
supplier and the customer.

[[]{#_Ref201725439 .anchor}]{#__RefHeading___Toc205199061 .anchor}Table
Chapter‑1: Customer and supplier responsibilities for the “foundry” and
“catalogue” modes

  ----------------------------------------------------------------------------------- ----------------------------------- ---------------- ----------
  Description                                                                         Reference                           Responsibility
                                                                                                                          supplier
  Process selection                                                                   clause 5                            X
  Design model validated and design tasks conducted                                   clause 7.2                          
  Design reviews                                                                      clause 7.3                          X
  Procurement specification                                                                                               
  ‑ for MMIC chip procurement under manufacturer and customer shared responsibility   clause 7.3.14                       X
  ‑ for LAT under customer responsibility),                                           clause 9                            
  Application approval                                                                clauses 8and 10.4.5                 
  Procurement activity including:                                                     clause 10                           
  ‑ wafer screening and WAT                                                           clause 10.2.4                       X
  ‑ dies incoming control                                                             clause 10.3                         
  ‑ LAT                                                                               clauses 10.4.2, 10.4.3 and 10.4.4   
  ‑ DPA                                                                               clause 10.4.6                       
  ‑ Failure analysis                                                                  clause 10.5                         
  ----------------------------------------------------------------------------------- ----------------------------------- ---------------- ----------

1.  \
    MMIC design
    ===========

    1.  Principles of MMIC design
        -------------------------

        1.  ### Overview

In this Clause the steps in the design phases and the responsibilities
of the designer in the development of the prototype MMICs are defined.

This Clause does not apply to catalogue MMICs already designed for which
the supplier guarantees the microwave performances.

1.  ### General

    a.  The synergies between the specific application for which the
        MMIC is designed and other application areas shall be
        investigated for possible utilization.

<!-- -->

1.  Example of other application areas are: commercial, professional,
    and military applications.

    a.  If the supplier is developing, or has already developed, for
        another application, an MMIC having a similar functionality to
        that required by the customer, this MMIC may be considered as a
        starting point for the new design.

    <!-- -->

    1.  ### Number of design iterations

        a.  The decision to proceed with a second design and
            manufacturing iteration (redesign) shall be made, for each
            MMIC, based on the conformance of the electrical design
            specification and the electrical measurements of the first
            iteration.

        b.  Additional iterations shall be carried out until sufficient
            margins can be demonstrated.

2.  A design iteration consists of circuit development, simulation,
    fabrication and measurement.

    1.  ### Design trade­offs

        a.  A design trade­off shall be performed including, as a
            minimum, the following:

            1.  circuit principles and heritage circuit topology and
                dependability;

            2.  gain and compression distribution inside the circuit;

            3.  overall electrical performance;

            4.  testability;

            5.  radiation;

            6.  assembly;

            7.  integration;

            8.  cost effectiveness of the packaging.

    <!-- -->

    1.  Design tasks
        ------------

        1.  ### Electrical design specification

            a.  []{#_Ref201726266 .anchor}Prior to any design, the
                customer shall develop an electrical design
                specification of the electrical performances for the
                application in conformance with Annex A.

        2.  ### Design variations

            a.  Several design variations for circuit architecture shall
                be implemented when the critical characteristics of the
                circuit are such that multiple variations on a design
                iteration maximise the probability of first­pass
                success.

            b.  The differences between the variations should be such
                that the probability of success of at least one of the
                variations is maximized.

            c.  Test structures of the most sensitive and critical
                passive and active circuit elements or sub­parts may be
                included in the design iteration to increase the
                diagnostic capabilities.

        3.  ### Parasitic effects

            a.  []{#_Ref201726597 .anchor}Parasitic effects shall be
                considered in all the designs and simulated with
                appropriate (e.g. electromagnetic) design tools.

3.  Examples include the effect of transmission line discontinuities
    (especially for unusual geometry and for those elements having a
    very critical influence on overall performance), on­die coupling,
    interconnections (e.g. bonding wires, external capacitors, impedance
    of interconnected circuits), assembly, and packaging.

    a.  The simulation specified in requirement 1.1.1.1.1v may be
        complemented with experimental data from circuits having a
        similar layout and characteristics.

    b.  If the confidence in a selected structure or component
        simulation is not sufficient, measures shall be taken to avoid
        this structure in the design, whenever possible, or the design
        modified to reduce the criticality of this structure.

    <!-- -->

    1.  ### Transient simulation

        a.  []{#_Ref201726657 .anchor}Transient simulations shall be
            made when circuits operate in pulse conditions.

        b.  []{#_Ref201726659 .anchor}Simulated results shall be derived
            for parameters such as, turn on and off times, variations
            versus pulse length and pulse repetition frequency.

        c.  Requirements 1.1.1.1.1y and 1.1.1.1.1z shall also be applied
            to oscillators for determining, for example, the build up
            time.

    2.  ### Thermal analysis

        a.  The maximum channel (or junction) temperature shall be
            computed for the maximum equipment base­plate temperature
            (operating temperature range).

        b.  Measures shall be taken to minimise the temperature by
            selecting the appropriate size or combination of active
            devices, their location on the die, and the mounting
            techniques

4.  E.g. eutectic attachment versus epoxy attachment.

    a.  The effects and characteristics of the packages on the circuits
        shall be analysed.

5.  E.g. power dissipation.

    1.  ### Sensitivity to temperature, process variation and supply voltages 

        a.  The sensitivity to temperature, process variation and supply
            voltages shall be simulated using foundry data or measured
            data from test components.

        b.  Yield analysis and estimates based on the design book data
            shall be carried out to ensure that the circuit operates as
            specified in the wafer­acceptance criteria (both RF and DC
            parameters), and that it can withstand uncertainties such
            as, the accuracy of electrical model parameters and
            variations.

6.  This includes the choice of, for example, optimum topologies,
    components, sizes, design centring, worst­case analysis, yield
    analysis and yield estimate.

    a.  The analysis shall be carried out for all parameters subjected
        to process variations and include, whenever possible,
        correlations between the different elements that cause
        variations.

    b.  When delivered by the foundry, SPC data should be used.

    <!-- -->

    1.  ### Design testability

        a.  Ground­source­ground pads with the standard pitch defined in
            the design book, shall be included for all RF ports.

        b.  For specific cases, alternative pad arrangements (e.g. G­S
            or S+ S­ pads) may be used after justification is provided
            (for example, a significant area reduction effect on the
            die).

        c.  DC pads should be positioned orthogonally to the RF pads.

        d.  For critical cases and at higher frequencies, an on­wafer
            calibration standard can be inserted in the tile.

7.  E.g. to remove uncertainties related to substrate thickness
    variation.

    1.  ### Design stability analysis

        a.  []{#_Ref201726883 .anchor}Design stability analysis shall be
            carried out from the DC to the maximum frequency of the
            active devices used.

        b.  The analysis specified in requirement 1.1.1.1.1mm (e.g.
            using µ factor or both K and B1 factors) shall be
            complemented by an internal multi­loop analysis to exclude
            any possibility of oscillations of the odd­mode type.

        c.  For a cascaded structure, as a minimum, the stability of
            each block shall be checked individually.

        d.  The analysis specified in requirement 1.1.1.1.1mm shall also
            include the effect of feedback paths caused by the
            following:

            1.  the biasing elements (on and off­die);

            2.  the final packaging;

            3.  the effects of process variations, temperature, and
                slight changes of biasing conditions.

        e.  Circuit stability during on­wafer characterization shall be
            addressed.

    2.  ### Maximum rating and robustness

        a.  The designer shall apply and verify the maximum rating
            specified by the manufacturer.

        b.  The designer shall apply the additional derating in
            conformance to ECSS‑Q‑ST-30‑11 or an equivalent customer
            specification as long as the customer specification does not
            relax ECSS‑Q‑ST-30‑11 requirements.

        c.  The maximum current densities and maximum voltages shall be
            evaluated in the whole circuit both at DC and RF operating
            conditions.

8.  E.g. multi­carrier signal.

    a.  The maximum level of stress under RF conditions in any device
        shall be limited to conditions equivalent to those for which the
        process reliability evaluation is carried out.

9.  Example of these RF conditions are gain compression, and effects of
    multi­carrier loading.

    a.  The circuit topology shall take into account the circuit
        reliability while maintaining acceptable electrical
        characteristics.

10. Example of reliability conditions to take into account are the use
    of L­parallel, C­series matching networks at input to reduce
    sensitivity to static discharge, and choice of transmission line
    size.

    a.  The effect of radiation shall be included (if applicable to the
        process used).

    b.  Any new MMIC design shall be analysed with respect to the
        process reliability figures compatible with the future
        application.

    c.  If the results of the analysis of the design and the application
        are out of the qualified domain, the customer (or the supplier)
        shall define a quality or reliability test plan for documenting
        the shortcomings.

    <!-- -->

    1.  ### Layout optimization

        a.  The die area shall be optimised to improve yield and reduce
            cost, without compromising on the functional performance of
            the die and testability.

        b.  A hierarchical design should be used.

        c.  The circuit layout shall be delivered in GDSII format.

        d.  The number of available die sites per tile shall be
            specified, and the layout of the complete tile shall be
            delivered (except PCM die).

        e.  The location and function of any connecting pads shall be
            specified and numbered.

        f.  Testability considerations shall be taken into account.

        g.  Assembly drawing shall be complete and include all other
            components additional to the MMIC.

11. E.g. filtering capacitors.

    a.  The packaging drawing (if applicable) shall be included.

    <!-- -->

    1.  ### DRC or ERC

        a.  []{#_Ref201744822 .anchor}The successful output of the
            design rules checking (DRC) performed at the foundry shall
            be demonstrated to show conformance with the foundry layout
            rules (e.g. no errors detected).

        b.  []{#_Ref201744825 .anchor}The successful output of the
            electrical rules checking (ERC) performed at the foundry (if
            performed) shall be demonstrated to show conformance with
            the foundry electrical rules

12. []{#ref201744825 .anchor}E.g. no errors detected.

    a.  For all the points not covered by requirements 1.1.1.1.1hhh and
        1.1.1.1.1iii, the supplier shall demonstrate that the design is
        made within a domain for which the selected process is fully
        proven.

13. E.g. frequency range of applicability of models, biasing ranges.

    1.  Design reviews
        --------------

        1.  ### General

            a.  Design and layout review meetings shall be held between
                the supplier and customer.

            b.  The supplier shall manage the participation of persons
                involved in the design and manufacturing.

            c.  When the design is completed, the designer shall send
                the file to the manufacturer for assembly of the final
                reticule and performance of the DRC.

            d.  The design review shall be organized by the supplier at
                the manufacturer facilities with persons involved in the
                design and manufacturing to assess whether the circuits
                are ready for manufacturing.

            e.  In the design review meeting, the requirements in
                clauses 7.3.2 to 7.3.14 shall be addressed in the given
                order.

        2.  ### MMIC architecture 

            a.  The designer shall provide a description of the
                function(s) and their features.

            b.  The manufacturer shall verify that the characteristics
                are realistic with regard to the domain of the process.

        3.  ### Schematic 

            a.  The designer shall present the electrical scheme of the
                circuits.

        4.  ### Simulation results

            a.  The designer shall state the software or hardware type
                used for the design.

            b.  The designer shall provide the simulation results
                demonstrating that the circuit belongs to the
                functionality domain specified and that the MMIC was
                designed using, for example, models and cells, specified
                in the design manual.

            c.  Any discrepancy or modification in, for example, the
                models and cells, shall be clearly identified, and
                justification and documentation supplied.

            d.  The designer shall demonstrate that the electrical
                models used in the simulations are valid for the
                specified application domain, including the worst case
                analyses.

        5.  ### Sensitivity and stability analysis

            a.  The designer shall provide the results of the
                sensitivity analysis.

            b.  Variations in the manufacturing process shall be taken
                into account in the design.

            c.  Variations in the environment shall be taken into
                account by the supplier who shall manage the impact.

14. For example to forward the sensitivity and stability data to the
    user.

    1.  ### Derating

        a.  The designer shall provide the derating for each passive or
            active element, calculated from the manufacturer maximum
            rating.

        b.  The derating analysis shall be performed for the worst case
            of use scenario and conform to the requirements of the
            ECSS‑Q‑ST-30‑11.

    2.  ### Layout

        a.  The manufacturer shall provide the DRC and ERC results.

        b.  If no software is available, the ERC shall be made
            “manually” on a large­scale drawing with the following:

            1.  highlight the connection nodes;

            2.  surround the basic cells;

            3.  mark the DC and RF paths;

            4.  measurement of the track dimensions and compare them to
                the design rules (current density).

        c.  For the manual ERC, the designer shall provide, for the
            review and for each circuit, a schematic of the electrical
            connections.

    3.  ### Tests matrix

        a.  The testing matrix, to be performed by the manufacturer at
            wafer level or at individual die level, shall be provided by
            the designer.

        b.  The manufacturer shall ensure that he has adequate test
            facilities to perform the tests.

    4.  ### Assembly

        a.  The designer shall specify the mounting technique for
            assembling the MMICs.

        b.  The supplier shall verify that the MMIC process is
            compatible with the intended mounting technique.

    5.  ### Compliance matrix

        a.  []{#_Ref201746914 .anchor}The supplier shall issue a
            compliance matrix for custom MMIC designs (check­list) in
            conformance with Annex B, based on manufacturer and designer
            data.

        b.  The compliance matrix for custom MMIC design shall be
            available for customer review.

    6.  ### MMIC detail specification 

        a.  The designer shall provide the preliminary MMIC detail
            specification of the circuit based on ESCC format (or
            equivalent).

    7.  ### Development plan

        a.  The development plan of the circuit(s) defining the planning
            of manufacturing and testing shall be agreed upon by the
            entity in charge of the procurement of the MMIC.

        b.  The design review shall be completed and the authorization
            for manufacturing given when all the items indicated in the
            conformance matrix and in the development plan are accepted.

        c.  If there are nonconformances, the end of the review shall be
            pronounced when the corrective actions are closed.

        d.  All the reviews shall be recorded as minutes of a meeting,
            written and signed in session.

    8.  ### Design documentation

        a.  []{#_Ref205199068 .anchor}For the design of an MMIC, a
            design package document in conformance with Annex C shall be
            provided to the customer for approval

        b.  The MMIC manufacturing shall not commence before the data
            package document has been approved by the customer.

        c.  The supplier shall provide a compliance table between target
            requirements and simulated results.

    9.  ### MMIC summary design sheet

        a.  []{#_Ref201748398 .anchor}Once the design of the MMIC is
            finalised and verified by tests, a summary design sheet
            shall be prepared by the supplier, in conformance with Annex
            D, for approval from the entity in charge of the procurement
            of the MMIC.

<!-- -->

1.  \
    Application approval 
    =====================

    1.  General
        -------

        a.  Application approval shall be carried out on each new
            designed MMIC in order to validate the compatibility between
            the MMIC and its specified application.

        b.  Dedicated test flow and test procedures shall be implemented
            in conformance with requirements in clause 8.2.

        c.  For microwave hybrids, the testing shall be complementary to
            the circuit type approval (CTA) as described in the
            ECSS‑Q‑ST-60‑05.

        d.  Additional hybrids shall be made available with the same
            quality level as for the CTA (minimum EM hybrid quality
            level).

        e.  Deviations and test conditions to this flow shall be
            justified by the hybrid manufacturer and agreed with the
            customer through the part approval document (PAD) procedure.

    2.  Test flow and test procedures
        -----------------------------

        a.  The test sequence shall be included as part of the hybrid
            CTA activities in conformance with ECSS‑Q‑ST-60‑05. Table
            Application approval -2 summarises the test groups and
            procedures.

        b.  []{#_Ref201735750 .anchor}The environment test specified in
            row 7 of Table Application approval -2 shall validate the
            compatibility of the new MMIC design circuits with the
            package environment.

        c.  []{#_Ref201735758 .anchor}It shall not be considered to be a
            duplication of environmental testing specified in row 7 of
            Table Application approval -2 carried out in the context of
            the hybrid evaluation and qualification activities used for
            validating the compatibility between the MMIC and hybrid
            technologies.

[[]{#_Ref201732437 .anchor}]{#__RefHeading___Toc205199062 .anchor}Table
Chapter‑2: CTA tests and procedures for testing in sequence D

+-------------+-------------+-------------+-------------+-------------+
| Test No.    | Test        | Procedure   | Sample size | Related     |
|             |             | and         |             | failure     |
|             |             | conditions  |             | mechanism   |
+-------------+-------------+-------------+-------------+-------------+
| 1           | Thermal     | Thermal     | 2           | ‑           |
|             |             | analysis of |             | Acceleratio |
|             |             | the MMIC to |             | n           |
|             |             | identify    |             | factor of   |
|             |             | hot spots   |             | failure     |
|             |             | or excess   |             | mechanisms. |
|             |             | temperature |             |             |
|             |             | during      |             | ‑           |
|             |             | worst­case  |             | Thermo‑meta |
|             |             | operations. |             | llurgical.  |
|             |             | Thermo­grap |             |             |
|             |             | hic         |             | ‑ Diffusion |
|             |             | measurement |             | effect      |
|             |             | shall be    |             | (gate       |
|             |             | carried out |             | sinking,    |
|             |             | when the    |             | ohmic metal |
|             |             | thermal     |             | diffusion). |
|             |             | analysis    |             |             |
|             |             | has         |             |             |
|             |             | indicated a |             |             |
|             |             | less than   |             |             |
|             |             | 20 °C       |             |             |
|             |             | margin to   |             |             |
|             |             | the maximum |             |             |
|             |             | rated       |             |             |
|             |             | temperature |             |             |
|             |             | under       |             |             |
|             |             | worst­case  |             |             |
|             |             | operation.  |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 2           | Electrical  | Current     | NA          | Electromigr |
|             |             | density     |             | ation       |
|             |             | analysis on |             |             |
|             |             | the MMIC    |             |             |
|             |             | for         |             |             |
|             |             | worst­case  |             |             |
|             |             | operation   |             |             |
|             |             | and         |             |             |
|             |             | comparison  |             |             |
|             |             | with the    |             |             |
|             |             | design book |             |             |
|             |             | maximum     |             |             |
|             |             | rating.     |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 3           |             | Characteriz | 2           | Trapping    |
|             |             | ation       |             | effect      |
|             |             | of MMIC     |             |             |
|             |             | behaviour   |             |             |
|             |             | over        |             |             |
|             |             | temperature |             |             |
|             |             | range,      |             |             |
|             |             | under DC or |             |             |
|             |             | RF and      |             |             |
|             |             | continuous  |             |             |
|             |             | or pulse    |             |             |
|             |             | operation   |             |             |
|             |             | (e.g.       |             |             |
|             |             | stability,  |             |             |
|             |             | lagging).   |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 4           |             | RF Stress   | 4           | ‑           |
|             |             | overdrive.  |             | Application |
|             |             | RF step     |             | related     |
|             |             | stress at   |             | with impact |
|             |             | room        |             | ionization. |
|             |             | temperature |             |             |
|             |             | ,           |             | ‑ High RF   |
|             |             | 168 h       |             | reverse     |
|             |             | minimum for |             | gate        |
|             |             | the last    |             | current.    |
|             |             | step. Last  |             |             |
|             |             | step stress |             | ‑ Power     |
|             |             | shall       |             | slump burn  |
|             |             | demonstrate |             | out due to  |
|             |             | a minimum   |             | RF.         |
|             |             | of 4dB      |             |             |
|             |             | margin      |             |             |
|             |             | against     |             |             |
|             |             | worst­case  |             |             |
|             |             | operation   |             |             |
|             |             | including   |             |             |
|             |             | modulation  |             |             |
|             |             | with no     |             |             |
|             |             | drift on DC |             |             |
|             |             | and RF      |             |             |
|             |             | parameters. |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 5           | Radiation   | Heavy ions: | 4           | ‑ Burn out. |
|             |             | analysis    |             |             |
|             |             | versus      |             | ‑ SEU for   |
|             |             | mission     |             | digital     |
|             |             | profile.    |             | application |
|             |             | Heavy ions  |             | .           |
|             |             | testing     |             |             |
|             |             | under room  |             |             |
|             |             | temperature |             |             |
|             |             | reverse     |             |             |
|             |             | bias        |             |             |
|             |             | conditions. |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 6           |             | Electron,   | 4           | Atoms       |
|             |             | proton,     |             | displacemen |
|             |             | neutron:    |             | t           |
|             |             | applicabili |             |             |
|             |             | ty          |             |             |
|             |             | to be       |             |             |
|             |             | addressed   |             |             |
|             |             | on a        |             |             |
|             |             | case­by­cas |             |             |
|             |             | e           |             |             |
|             |             | basis.      |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 7           | Environment | Hydrogen:   | 6           | ‑ H~2~      |
|             | \           | high­temper |             | poisoning.  |
|             | (see        | ature       |             |             |
|             | 1.1.1.1.1zz | storage     |             | ‑ DC        |
|             | zz\         | test or     |             | parameters  |
|             | and         | HTRB under  |             | drift.      |
|             | 1.1.1.1.1aa | N~2~/H~2~   |             |             |
|             | aaa)        | (minimum 5% |             | ‑ Sudden    |
|             |             | H~2~)       |             | I~dss~      |
|             |             | environment |             | drop.       |
|             |             | for a       |             |             |
|             |             | minimum of  |             |             |
|             |             | 240 h or    |             |             |
|             |             | equivalent. |             |             |
|             |             | RGA         |             |             |
|             |             | analysis    |             |             |
|             |             | extended to |             |             |
|             |             | all         |             |             |
|             |             | elements    |             |             |
|             |             | after test. |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 8           |             | Epoxy or    | 6           | ‑ Ionic     |
|             |             | other       |             | contaminant |
|             |             | contaminant |             | (epoxy,     |
|             |             | :           |             | residue, RF |
|             |             | DC life     |             | absorbers). |
|             |             | test HTRB)  |             |             |
|             |             | at 150 °C   |             | ‑ DC        |
|             |             | for a       |             | parameters  |
|             |             | minimum of  |             | drift.      |
|             |             | 240 h or    |             |             |
|             |             | equivalent. |             |             |
|             |             | Drift       |             |             |
|             |             | recovery    |             |             |
|             |             | under       |             |             |
|             |             | high­temper |             |             |
|             |             | ature       |             |             |
|             |             | storage     |             |             |
|             |             | with leads  |             |             |
|             |             | short­circu |             |             |
|             |             | ited        |             |             |
|             |             | at          |             |             |
|             |             | T=150 °C,   |             |             |
|             |             | 168 h. RGA  |             |             |
|             |             | extended to |             |             |
|             |             | all         |             |             |
|             |             | elements.   |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 9           |             | Moisture,   | 6           | ‑           |
|             |             | LTRB        |             | Electrical  |
|             |             | (T~amb ~&lt |             | parameters  |
|             |             | ; dew       |             | drift.      |
|             |             | point)      |             |             |
|             |             | 168 h under |             | ‑ Burn­out. |
|             |             | specified   |             |             |
|             |             | humidity    |             |             |
|             |             | environment |             |             |
|             |             | due to      |             |             |
|             |             | assembly    |             |             |
|             |             | and storage |             |             |
|             |             | condition   |             |             |
|             |             | or due to   |             |             |
|             |             | additional  |             |             |
|             |             | element in  |             |             |
|             |             | package     |             |             |
|             |             | e.g. RF     |             |             |
|             |             | absorbent.  |             |             |
|             |             | RGA         |             |             |
|             |             | extended to |             |             |
|             |             | all         |             |             |
|             |             | elements.   |             |             |
+-------------+-------------+-------------+-------------+-------------+

1.  \
    Procurement and LAT specification
    =================================

    a.  []{#_Ref201749417 .anchor}A MMIC procurement specification shall
        be issued by the supplier in conformance with Annex E, and
        associated with each MMIC.

    b.  []{#_Ref201749652 .anchor}A MMIC lot acceptance specification
        for user LAT shall be issued by the supplier in conformance with
        Annex F.

    c.  []{#_Ref201997616 .anchor}The MMIC lot acceptance specification
        for user LAT shall be implemented.

<!-- -->

1.  Clause 10 defines the requirements for the MMIC procurement
    specification and the MMIC lot acceptance specification for user
    LAT.

    a.  If the mounting and wiring processes are different from the user
        hybrid process, the procured lot shall be validated with respect
        to the user process by performing an additional LAT or by using
        the LAT performed at hybrid level providing sufficient confident
        data are available.

<!-- -->

1.  \
    Procurement
    ===========

    1.  General
        -------

        1.  ### Overview

This Clause contains the deviations and amendments to ECSS‑Q‑ST-60‑05,
specific to MMIC procurement.

### Methodology

The procurement activity shall comprise the following three steps:

a.  Wafer screening and wafer acceptance testing (WAT) (MMIC
    manufacturer responsibility), in conformance with requirements in
    clause 10.2.

b.  Dies incoming inspection (hybrid manufacturer responsibility), in
    conformance with requirements in clause 10.3.

c.  User lot acceptance testing (LAT) (hybrid manufacturer
    responsibility), in conformance with requirements in clause 10.4.

<!-- -->

1.  Wafer screening and WAT
    -----------------------

    1.  ### General

        a.  Wafer screening and wafer acceptance testing (WAT) shall be
            the responsibility of the manufacturer.

<!-- -->

1.  The test flow and relevant test conditions are described in clauses
    10.2.2 to 10.2.6.

    1.  ### Wafer screening and WAT flows

Figure Procurement-1 illustrates the sequence of activities for wafer
screening and WAT.

[[[[[[[[[[[[[[[[]{#_1275478135 .anchor}]{#_1275478747
.anchor}]{#_1275478823 .anchor}]{#_1275735345 .anchor}]{#_1276101092
.anchor}]{#_1276433935 .anchor}]{#_1278939859 .anchor}]{#_1278940877
.anchor}]{#_1278940997 .anchor}]{#_1278941207 .anchor}]{#_1278941210
.anchor}]{#_1278941605 .anchor}]{#_1278941618 .anchor}]{#_1278941631
.anchor}]{#_1278941650 .anchor}]{#_1278945615 .anchor}

[[]{#_Ref201737415 .anchor}]{#__RefHeading___Toc205199057 .anchor}Figure
Chapter‑1: Wafer screening and WAT

1.  ### Wafer manufacturing and control

    a.  PCM measurements, rules and controls, shall be in conformance
        with the manufacturer design book requirements.

    b.  Wafers shall be accepted, based on PCM specifications, as
        defined by the manufacturer.

    c.  PCM data that is manufacturer proprietary information, can be
        delivered, if agreed upon by the manufacturer, and user or
        customer.

    d.  DC and RF on­wafer probing shall be performed by the
        manufacturer prior to the dicing and be used to sort the dies as
        defined in the procurement specification.

    e.  []{#_Ref201737485 .anchor}Optional reviews such as a customer
        source inspection, may be agreed between the user and the
        manufacturer.

    f.  During the optional reviews specified in 1.1.1.1.1nnnnn,
        documentation shall be available that includes:

        1.  materials and in­process controls;

        2.  lot travellers;

        3.  PCM acceptance;

        4.  SPC data review;

        5.  SEM of specific processing step;

        6.  production and quality assurance controls;

        7.  manufacturer visual inspection data documents and reports.

2.  ### Wafer acceptance test

    1.  #### General

        a.  Wafer acceptance testing (WAT) is the responsibility of, and
            shall be performed by, the manufacturer.

        b.  The WAT shall verify that the process and the MMIC designs
            are compliant to the space grade quality level.

        c.  The WAT shall comprise the following:

            1.  PCM measurements and a check for wafer release according
                to the manufacturer specification;

            2.  100 % DC and RF on wafer probing;

            3.  100 % die visual inspection;

            4.  a manufacturer assembly test (bond pull test and die
                shear test).

        d.  On completion of the WAT, the wafers (issued from the same
            batch) shall be guaranteed and delivered after dicing in die
            form as specified in the procurement specification.

    2.  #### DC and RF probing

        a.  All the MMICs shall be electrically probed for DC and RF, as
            defined in the procurement specification.

        b.  The dies that pass shall be identified and stored with the
            appropriate packaging and under suitable conditions.

    3.  #### Dicing and 100 % visual inspection 

        a.  All visual inspection sequences shall be performed according
            to ESCC 2049010 or MIL‑STD‑883, method 2010 condition A or
            according to standard professional grade (manufacturer or
            user procedure) if validated by the customer.

        b.  100% of the naked die shall be visually inspected after
            dicing.

        c.  []{#_Ref201750580 .anchor}A summary sheet of the visual
            inspection shall be produced by the supplier in conformance
            with Annex G, and made available to the customer.

    4.  #### Manufacturer assembly test

        a.  In order to guarantee the quality of the interface (bonding
            pad metals and die back face metals), the manufacturer shall
            implement an assembly test sequence if specified in the
            procurement specification.

        b.  The assembly test sequence shall be performed by sampling
            rejected dies (assembled using the manufacturer process)
            from the wafers manufactured, and includes the following:

            1.  A bond pull test on 10 wires as per MIL‑STD‑883 method
                2011.\
                No failures allowed.

            2.  A die shear test on 2 parts as per MIL‑STD‑883 method
                2019.\
                No failure allowed.

        c.  []{#_Ref201737658 .anchor}If the test sequence performed is
            based on the user assembly process and in conformance with
            the user assembly test defined for the incoming inspection,
            then this test shall not to be repeated by the user when
            dies are received.

        d.  For requirement 1.1.1.1.1aaaaaa, a document shall be issued
            by the user stating that the assembly process used by the
            manufacturer is representative of the hybrid process.

3.  ### Packaging

    a.  All deliverable dies shall be packed in conformance with
        ESCC 20600.

    b.  Waffle packs should be used but can attract dust and cause
        scratching if not handled with care.

    c.  Gel packs shall be validated with respect to any contamination
        or residue after storage.

    d.  All packaging shall be opened in a suitable clean room using the
        appropriate procedure.

    e.  Several categories of dies may be delivered (including yield
        information):

        1.  good DC or RF and good visual;

        2.  good DC or RF and bad visual;

        3.  test structures (TCV, DEC, PCM).

4.  ### Deliverables

    a.  The data package shall comprise the results of the controls
        described in clauses 10.2.3 to 10.2.5.

    b.  If a data package is not delivered, all data shall be retained
        by the manufacturer for a minimum of 5 years during which time
        it shall be available to the customer for review, upon request.

    c.  The manufacturer data package documentation shall consist of the
        following:

        1.  Cover sheet or declaration of conformity, full traceability
            (including for lot, batch, wafers, dies), purchase order
            reference, manufacturer’s name and location of manufacturing
            plant.

        2.  Certificate of conformity (manufacturer’s name and location
            of manufacturing plant, date and manufacturer’s QA
            signature, reference to the generic and detail
            specification, including issue and date).

        3.  Wafer acceptance test data and PCM data summary sheet.

        4.  DC or RF measurement data for every MMIC type and associated
            yields.

        5.  QA visual inspection report (front side and back side).

    d.  In the “foundry” mode, each type of MMIC shall be delivered,
        with traceability and quantity information written on the
        packaging, in two categories:

        1.  ‘‘accept: good dies (DC or RF) and good visual’’,

        2.  ‘‘reject: good dies (DC or RF) and bad visual’’.

<!-- -->

1.  Dies incoming testing
    ---------------------

    1.  ### General

        a.  Dies incoming testing shall be carried out when a new die
            lot is received in conformance with Figure Procurement-2

<!-- -->

1.  See also clause 3.2.4.

    a.  The testing shall include the following test sequence:

        1.  bondability testing;

        2.  visual inspection;

        3.  electrical characterization.

    b.  Testing shall be carried out by the user for every MMIC die lot
        and prior to the user LAT.

    <!-- -->

    1.  ### Assembly test

        a.  The assembly test shall verify the compatibility between the
            MMIC process and the hybrid technology.

        b.  The mounting process and the type of package used for the
            tests shall be representative of the processes employed for
            the FM hybrids by the user.

        c.  The mounting process and the type of package used for the
            tests shall be described in the specifications included in
            the PID of the user.

        d.  Dies rejected during the front side visual inspection issued
            from the controls can be used to perform the test.

        e.  The MMIC selected for the tests shall have, if possible, the
            maximum via hole density.

        f.  Wire pull testing shall be performed according to
            MIL‑STD‑883 method 2011 on 22 wires or on all the wires if
            less. No failure allowed.

        g.  The shear test on mounted dies shall be according to
            MIL‑STD‑883 method 2019 on 4 dies. No failure allowed.

[[[[[[[[[[]{#_1275479721 .anchor}]{#_1275479777 .anchor}]{#_1275735346
.anchor}]{#_1276101093 .anchor}]{#_1278939860 .anchor}]{#_1278940878
.anchor}]{#_1278941704 .anchor}]{#_1278942025 .anchor}]{#_1278942042
.anchor}]{#_1278945616 .anchor}

[[[]{#_Ref201738059 .anchor}]{#_Ref201738064
.anchor}]{#__RefHeading___Toc205199058 .anchor}Figure Chapter‑2: Dies or
die incoming testing

1.  ### Visual inspection

    a.  The user quality assurance inspector shall carry out a visual
        inspection of the lot on a 100 % basis or on an AQL 1 %.

2.  ### Electrical characterization

    a.  If an electrical characterization test is performed, 2 parts per
        design shall be assembled on a carrier or in a package similar
        to the one used for hybrid FM production.

<!-- -->

1.  The objective of this optional testing is to select dies lots for
    specific application requirements, which cannot be characterised on
    the wafer.

    1.  User LAT procurement sequences
        ------------------------------

        1.  ### General

            1.  #### Overview

The purpose of the LAT performed by the manufacturer is to assess the
reliability of the technology (LAT DEC or TCV) and the reliability of
the MMIC design (LAT MMIC). The purpose of the LAT performed by the user
is to assess the technology and MMIC design, and the compatibility of
the MMIC with the assembly process.

[[[[[[[[]{#_1275480527 .anchor}]{#_1275480550 .anchor}]{#_1275735347
.anchor}]{#_1276101094 .anchor}]{#_1278939861 .anchor}]{#_1278940879
.anchor}]{#_1278942083 .anchor}]{#_1278945617 .anchor}

[[]{#_Ref201738872 .anchor}]{#__RefHeading___Toc205199059 .anchor}Figure
Chapter‑3: Acceptance flow for flight model die lots

Depending on the validated process status of the MMIC, the maturity of
the design and the application, the acceptance flow for FM dies is
defined in three flow test sequences (Figure Procurement-3):

-   Sequence A: This flow applies when process, design and application
    have already been validated.

-   Sequence B: This flow is applies when the process is validated and a
    new design or a new application needs to be validated.

-   Sequence C: This flow is applies when the MMIC design, application
    and the process are not validated.

    1.  #### Requirements

        a.  From the three sequences A, B and C shown in Figure
            Procurement-3, the severity of acceptance testing shall be
            specified in order to obtain consistent Space grade quality
            levels.

        b.  Sequence D of Figure Procurement-3 is the application
            approval as defined in clause 8 and shall be performed to
            validate new designs or new applications.

        c.  The user LAT shall be performed using TCV, DEC or MMICs as
            per Figure Procurement-4 in conformance with ESCC 2439010.

        d.  Test vehicles shall be mounted in packages that enable tests
            (maximum junction temperature T~j~ = 175 °C), electrical
            measurements and inspections to be performed.

        e.  For a LAT performed by the user, the assembly processes and
            the type of package used for TCV, DEC and MMIC mounting
            shall be representative of the processes defined in the
            user’s PID.

        f.  The number of units that are assembled shall be sufficient
            to ensure that after screening, the specified number of
            units as defined in Figure Procurement-4 are available.

        g.  The screening of the assembled devices shall include the
            following:

            1.  visual inspection (if specified);

            2.  sealing and serialization;

            3.  hermeticity (if applicable) (fine and gross leak test)
                as per MIL‑STD‑883 method 1014;

            4.  DC and RF initial electrical measurement at room
                temperature (including one control device for
                reproducibility verification) under nominal DC biasing
                and nominal RF input;

            5.  DC burn in at T~ch~ = 175 °C, for 96 h under nominal
                biasing condition (no RF);

            6.  DC and RF final electrical measurement at room
                temperature (including one control device for
                reproducibility verification) under nominal DC biasing
                and nominal RF input.

1.  See clause 9 for requirements on issuing a specification for user
    LAT.

[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_1275480856 .anchor}]{#_1275480931
.anchor}]{#_1275481221 .anchor}]{#_1275484222 .anchor}]{#_1275484225
.anchor}]{#_1275735348 .anchor}]{#_1276101095 .anchor}]{#_1276434922
.anchor}]{#_1278939862 .anchor}]{#_1278940880 .anchor}]{#_1278942591
.anchor}]{#_1278943147 .anchor}]{#_1278943153 .anchor}]{#_1278943163
.anchor}]{#_1278943166 .anchor}]{#_1278943329 .anchor}]{#_1278943341
.anchor}]{#_1278944143 .anchor}]{#_1278944149 .anchor}]{#_1278944364
.anchor}]{#_1278944372 .anchor}]{#_1278944383 .anchor}]{#_1278944386
.anchor}]{#_1278944395 .anchor}]{#_1278944411 .anchor}]{#_1278944422
.anchor}]{#_1278944479 .anchor}]{#_1278944487 .anchor}]{#_1278944540
.anchor}]{#_1278945618 .anchor}]{#_1279049852 .anchor}

[[]{#_Ref201743299 .anchor}]{#__RefHeading___Toc205199060 .anchor}Figure
Chapter‑4: User LAT flow

1.  ### Sequence A: process, design and application validated

    a.  The user LAT sequence A in Figure Procurement-4 shall be applied
        to the procurement of MMICs processed with a validated process
        in conformance with customer’s requirements and for which the
        designs have been validated from a reliability point of view by
        performing application approval testing.

    b.  For high­grade level, the sequence A in Figure Procurement-4
        shall be conducted on DEC or TCV structures only.

    c.  The sampling is related to the number of wafers and shall be 3
        DEC or TCV per wafer with a total 12 parts per wafer lot and one
        control device.

    d.  []{#_Ref201743646 .anchor}A life test shall be performed on the
        12 parts assembled using processes defined in the user’s PID and
        under nominal biasing conditions (no RF) and high temperature,
        in an oven, in order to achieve a maximum channel temperature of
        175 °C with a tolerance of ‑5 °C.

    e.  []{#_Ref201743672 .anchor}The duration of the test shall be 168
        hours for high­grade level (failure criteria A=0, R=1).

    f.  []{#_Ref201743704 .anchor}If epoxy die attach is used:

        1.  the temperature within the oven shall be a maximum of 130 °C
            with a tolerance of ‑5 °C; and

        2.  the duration of the life test shall be based on the
            Arrhenius acceleration factor with Ea=0,6 eV.

    g.  100 % final electrical measurements at room temperature and
        delta calculation shall be made. No failure allowed.

    h.  A DPA shall be performed on 2 parts as per clause 10.4.6. No
        defect allowed.

    i.  Sequence A in Figure Procurement-4 is not applicable for low
        grade level.

2.  ### Sequence B: process validated and new design or new application

    a.  Sequence B in Figure Procurement-4 shall be applied to the
        procurement of MMICs processed with a validated process
        according to the customer’s requirements and for which the
        design is new and not validated from a reliability point of
        view.

    b.  For high­grade level, sequence B in Figure Procurement-4 shall
        be conducted on DEC or TCV structures and on MMIC dice assembled
        using the processes defined in the user’s PID.

    c.  The sampling is related to the number of wafers and shall be 3
        DEC or TCV per wafer and 3 MMIC (new) per wafer with a total 12
        parts per wafer lot and one control device.

    d.  A 168 h life test shall be performed as per clauses
        1.1.1.1.1hhhhhhh and 1.1.1.1.1iiiiiii on 6 parts DEC or TCV
        structures.

    e.  A 240 h life test shall also be performed on 6 MMIC.

    f.  If the parts are epoxy die attached, the same restrictions as
        given in requirement 1.1.1.1.1jjjjjjj shall apply and the
        calculations for the duration of the test shall be based on the
        same acceleration factor.

    g.  100 % final electrical measurement at room temperature and delta
        calculation shall be made. No failure allowed.

    h.  A DPA shall be performed on 2 parts (either TCV, DEC or MMIC) as
        per clause 10.4.6. No defect allowed.

    i.  Sequence B is not applicable for low­grade level.

3.  ### Sequence C: process, design and application not validated

    a.  Sequence C in Figure Procurement-4 shall be applied to the
        procurement of MMIC processed with a non­validated process
        according to the customer’s requirements.

    b.  The user LAT shall be considered to be the lot validation.

    c.  It shall be performed on MMICs with the modified conditions
        given in requirements 1.1.1.1.1zzzzzzz to 1.1.1.1.1ffffffff.

    d.  []{#_Ref201744872 .anchor}For high­grade level, a 1 000 h life
        test shall be applied on 12 packaged MMIC per wafer lot
        (assembly process as per user’s PID).

    e.  If the parts are epoxy die attached, the same restrictions as
        given in requirement 1.1.1.1.1jjjjjjj shall apply and the
        calculations for the duration of the test shall be based on the
        same acceleration factor.

    f.  For low grade level, the duration of the life test shall be
        reduced to 500 h on 6 parts per wafer lot only.

    g.  100% final electrical measurement at room temperature and delta
        calculation shall be made. No failure allowed.

    h.  For both levels, a DPA shall be performed on 2 parts (one before
        the life test and one after) (either TCV, DEC or MMIC) as per
        clause 10.4.6. No defect allowed.

    i.  A construction analysis (CA) shall be performed on 3 dice for
        the first procured lot.

    j.  []{#_Ref201744877 .anchor}The CA shall include, as a minimum,
        the following analyses:

        1.  external visual inspection (MIL STD 883 method 2009);

        2.  internal visual inspection (MIL STD 883 method 2010);

        3.  SEM inspection (MIL STD 883 method 2018);

        4.  identification of bonding pad and back side metals and their
            thicknesses;

        5.  passivation material and thickness;

        6.  die dimension;

        7.  micro­section showing the gate zone (with dimensions).

4.  ### Sequence D: application approval testing

    a.  When specified, sequence D in Figure Procurement-4 shall be
        applied, prior to the user LAT sequences.

    b.  A test plan shall be issued and agreed upon by the customer.

    c.  The test plan shall detail the tests to be performed on a
        defined quantity of CTA as described in ECSS‑Q‑ST-60‑05 (see
        Table 2 of clause 8.2).

    d.  The test plan shall be documented and some tests may be omitted
        if the heritages on the technology or on the design are
        sufficient and demonstrated.

    e.  The user shall be responsible for defining the tests to support
        the reliability tests based on Table Application approval -2.

    f.  []{#_Ref201744087 .anchor}Hybrids or dedicated packaged MMIC
        (one MMIC per package) can be used to complete this sequence of
        test.

    g.  For requirement 1.1.1.1.1llllllll, the packaged parts shall be
        representative of the production process defined in the PID
        (assembly and sealing process) and be screened according to the
        flow defined in Figure Procurement-4 and clause 10.4.

    h.  []{#_Ref201744219 .anchor}Due to the conditions of stress, some
        tests may be conducted up to and above the failure limits with
        the purpose of assessing the existing margin due to a specific
        constraint.

    i.  If 1.1.1.1.1nnnnnnnn is performed, it should be stated in the
        test plan document.

5.  ### Destructive physical analysis after user LAT

    a.  The following tests shall be performed as part of the DPA:

        1.  External visual inspection MIL‑STD‑883 Method 2009.8

        2.  []{#_Ref201997632 .anchor}Seal test MIL‑STD‑883 Method 1014
            condition A2 ‑ condition C

        3.  Internal visual inspection ESCC 2409010 or equivalent

        4.  Bond pull test MIL‑STD‑883 Method 2011 condition D

        5.  Die shear test MIL‑STD‑883 Method 2019

        6.  RGA (option) MIL‑STD‑883 Method 1018.2.

<!-- -->

1.  Failure criteria and lot failure
    --------------------------------

    a.  A component shall be considered to be failed if one or more of
        the electrical parameters (DC and RF) exceed the limits defined
        in Table 4 of the corresponding detail specification.

    b.  In the case of a LAT performed by the manufacturer failures due
        to the assembly of the test structures shall be excluded from
        the results, and therefore not lead to lot failure.

    c.  In the case of a LAT performed by the user, a part shall be
        considered failed if at least one test does not satisfy the
        limits defined in the specification associated to the process.

    d.  Any relevant failures (see requirement 1.1.1.1.1vvvvvvvv)
        observed in assembly tests shall be included in a nonconformance
        sheet and the problem subjected to a review.

    e.  The customer shall be informed of the nonconformance and decide
        when it can be closed.

    f.  []{#_Ref201744748 .anchor}A failure shall be considered a
        relevant failure if only address a problem at die level

<!-- -->

1.  []{#ref201744748 .anchor}For example: bond pull failure criteria at
    wire neck is not considered as a defect from the die point of view.

    a.  []{#_Ref201744357 .anchor}During user LAT, if the number of
        components failed during assembly or screening exceeds 10% of
        the components submitted to these tests and associated
        electrical measurements, the lot shall be considered as failed.

    b.  In the case of requirement 1.1.1.1.1wwwwwwww the lot shall be
        treated using the nonconformance procedure.

    c.  Parts failed during the LAT screening may be replaced by new
        assembled and re­screened parts in order to make up the quantity
        for the life test sequence.

    d.  A component shall be counted as failed if one or more electrical
        parameters (DC and RF) exceed the limits defined in Table 4 of
        the corresponding detail specification.

<!-- -->

A.  [[]{#_Ref201745817 .anchor}]{#__RefHeading___Toc205199048
    .anchor}(normative)\
    MMIC electrical design specification - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-Q-ST-60-12, requirement 1.1.1.1.1r.

1.  Purpose and objective

The MMIC electrical design specification is the baseline for the design
and for the acceptance of the MMIC.

1.  Expected response

    1.  Scope and content

        a.  The MMIC electrical design specification shall contain, as a
            minimum, the following:

            1.  electrical performances and application,

            2.  die dimension,

            3.  in and out interfaces.

    2.  Special remarks

None.

A.  [[]{#_Ref201746485 .anchor}]{#__RefHeading___Toc205199049
    .anchor}(normative)\
    Compliance matrix for custom MMIC design - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-Q-ST-60-12, requirement 1.1.1.1.1iiii.

1.  Purpose and objective

The purpose of the compliance matrix for custom MMIC design is to
summarize the status of the compliance with respect to the specification
of the business agreement.

1.  Expected response

    1.  Scope and content

        a.  The compliance matrix shall summarise the following:

            1.  The function description and associated main
                characteristics.

            2.  The software or hardware used for the design.

            3.  Verification that the circuit belongs to the specified
                functional domain and is designed using, for example,
                the models and cells, described in the design manual. If
                not, an extension of the qualification domain shall be
                provided.

            4.  The results of the sensitivity and stability analyses.

            5.  The derating of the elementary parts.

            6.  The DRC results.

            7.  The ERC results.

            8.  Verification from the manufacturer that he can perform
                the set of tests specified by the designer for the wafer
                or dies release.

    2.  Special remarks

        a.  The existence of the compliance matrix shall be indicated in
            the PAD sheet.

<!-- -->

A.  [[]{#_Ref201747349 .anchor}]{#__RefHeading___Toc205199050
    .anchor}(normative)\
    Design package document - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-Q-ST-60-12, requirement 1.1.1.1.1pppp.

1.  Purpose and objective

The MMIC design data package document is the set of configured documents
related to the design.

1.  Expected response

    1.  Scope and content

        a.  The design package document shall include the following:

            1.  Description of functionality and any functional blocks.

            2.  List of the major critical items in the circuit design
                and the trade­offs performed.

            3.  Schematic diagrams.

            4.  Linear simulation including out­of­band response.

            5.  Noise analysis, including phase noise (if applicable to
                the specific circuit).

            6.  Non­linear simulation, steady state (if applicable to
                the specific circuit).

            7.  Transient simulation.

            8.  Electromagnetic analysis (if applicable to the circuit:
                this depends on).

<!-- -->

1.  For example, the frequency of operation, sensitivity of the circuit,
    > density on the die, thickness of the substrate, type of
    > transmission lines used, similarity with already produced die.

    1.  DC analysis (if applicable to the circuit),

2.  For example, for non­linear circuits or circuits using DC coupled
    > active elements.

    1.  Tolerance analysis, stability analysis, thermal analysis,
        reliability analysis.

    2.  Layout.

    3.  DRC or ERC.

    4.  On­wafer testing (when performed).

    5.  Cost analysis budgetary cost estimates for production runs of
        the MMIC designed, including in the case of circuits to be
        produced in large quantities, a detail cost estimates.

    6.  Test plan or procedures (including the calibration approach and
        accuracy).

    7.  On­wafer and test­jig measurements (including test­jig
        mechanical and electrical characteristics).

    <!-- -->

    1.  Special remarks

None.

A.  [[]{#_Ref201748313 .anchor}]{#__RefHeading___Toc205199051
    .anchor}(normative)\
    MMIC summary design sheet - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-Q-ST-60-12, requirement 1.1.1.1.1ssss.

1.  Purpose and objective

The MMIC summary design sheet is the set of data characterizing in short
the MMIC.

1.  Expected response

    1.  Scope and content

        a.  The MMIC summary design sheet shall include the following:

            1.  Name of the circuit.

            2.  Function.

            3.  Electrical diagram.

            4.  Main performance characteristics.

            5.  Compliance table between target and simulated
                performance.

            6.  Name of the final GDSII file.

            7.  Layout drawing (with dimensions and identification of
                each connection pad position and function).

            8.  Foundry process used.

            9.  Assembly drawing (including external components needed).

            10. List of nominal biasing and control voltages or
                currents, and total power consumption.

            11. List of nominal RF signals to be applied or measured.

            12. Photograph (in colour and details).

    2.  Special remarks

None.

A.  []{#_Ref201748897 .anchor} [[]{#_Ref201750208
    .anchor}]{#__RefHeading___Toc205199052 .anchor}(normative)\
    MMIC procurement specification - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called from ECSS-Q-ST-60-12, requirement 1.1.1.1.1bbbbb.

1.  Purpose and objective

The MMIC procurement specification is a support for the acceptance of
the MMIC.

1.  Expected response

    1.  Scope and content

        a.  The MMIC procurement specification shall include, as a
            minimum, the following:

            1.  The physical description of the tile and all associated
                die (name, dimensions, cells).

            2.  The electrical test plan (DC biasing, RF input
                conditions) for on­wafer probing.

            3.  All parameter specification limits to be applied for die
                sort.

            4.  Packaging definition.

            5.  Quality level of visual inspection for die delivered.

    2.  Special remarks

        a.  The MMIC procurement specification may be merged with the
            MMIC lot acceptance specification for user LAT (see Annex F)
            on completion of all testing by the manufacturer and user
            for the finalization of the MMIC detail specification.

<!-- -->

A.  []{#_Ref201749239 .anchor} []{#__RefHeading___Toc205199053
    .anchor}(normative)\
    MMIC lot acceptance specification for user LAT - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called up from ECSS-Q-ST-60-12, requirement 1.1.1.1.1ccccc.

1.  Purpose and objective

The MMIC lot acceptance specification for user LAT is a support for the
acceptance of the MMIC.

1.  Expected response

    1.  Scope and content

        a.  The MMIC lot acceptance specification for user LAT shall
            contain, as a minimum, the following:

            1.  Die reference submitted to user LAT (using either a TCV,
                a DEC or an MMIC).

            2.  The description of the package to be used for the
                mounting with lead identification.

            3.  The description of the mounting and wiring processes.

            4.  Table 1: maximum ratings. This table shall include the
                limiting electrical, mechanical and thermal parameters.

            5.  Table 2: electrical measurements at ambient temperature
                with static and dynamic parameters.

            6.  Table 3: electrical measurements at high and low
                temperatures.

            7.  Table 4: parameter drifts. This table shows the
                electrical parameters before and after burn­in with the
                maximum drift allowed.

            8.  Table 5: burn in conditions. This table shows the oven
                temperature and power applied.

            9.  Table 6: electrical measurements after endurance tests.
                This table shows the parameters measured and the minimum
                and maximum values tolerated following the life test at
                the ambient temperature.

            10. Table 7: life test conditions. This table shows the oven
                temperature and power applied.

    2.  Special remarks

        a.  The MMIC lot acceptance specification may be merged with the
            MMIC procurement specification (see ECSS-Q-60-12 Annex E) on
            completion of all testing by the manufacturer and user for
            the finalization of the MMIC detail specification.

<!-- -->

A.  [[]{#_Ref201750858 .anchor}]{#__RefHeading___Toc205199054 .anchor}
    (normative)\
    MMIC visual inspection summary sheet - DRD

    1.  DRD identification

        1.  Requirement identification and source document

This DRD is called up from ECSS-Q-ST-60-12, requirement 1.1.1.1.1xxxxx.

1.  Purpose and objective

The purpose of the MMIC visual inspection summary sheet is to summarize
the results of the visual inspection performed as part of the wafer
acceptance test of the MMIC.

1.  Expected response

    1.  Scope and content

        a.  The MMIC visual inspection shall include all references for
            traceability purpose and, as a minimum, the quantities of
            the following:

            1.  good dies, sorted after DC and RF testing;

            2.  rejected dies after visual inspection;

            3.  accepted dies for each type of MMIC.

    2.  Special remarks

None.

A.  []{#__RefHeading___Toc205199055 .anchor}(informative)\
    References

<!-- -->

1.  ESCC QPL, ESA qualified parts list

2.  ESCC/REF 001, List of ESCC documents and specifications under
    configuration control

3.  CECC 00200, Register of approvals

4.  ISO 14621-1, Space systems ‑ Electrical, electronic and
    electromechanical (EEE) parts ‑ Part 1: Parts management

5.  ISO 14621-1, Space systems ‑ Electrical, electronic and
    electromechanical (EEE) parts ‑ Part 2: Control programme
    requirements

 Bibliography

  -------------- ----------------------------------------------------------------------------------------
  ECSS-S-ST-00   ECSS system ‑ Description and implementation and general requirements
  ESCC 5010      Generic specification for discrete microwave semiconductor components
  ESCC 20100     Requirements for qualification of standard electronic components for space application
  ESCC 2269010   Evaluation test programme for MMICs
  -------------- ----------------------------------------------------------------------------------------
