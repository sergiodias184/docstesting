-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
-   [Introduction](#introduction)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Abbreviated terms](#abbreviated-terms)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-35-01C(15November2008).docx1//media/image1.png){width="4.157638888888889in"
height="2.55in"}

Space engineering

Liquid and electric propulsion for spacecraft

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

This Standard has been prepared by the ECSS-E-35-01 Working Group,
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

  ------------------ --------------
  ECSS-E-ST-35-01A   Never issued

  ECSS-E-ST-35-01B   Never issued

  ECSS-E-ST-35-01C   First issue
                     
  15 November 2008   
  ------------------ --------------

 Table of contents {#table-of-contents .Contents}

[Change log 3](#change-log)

[Introduction 8](#introduction)

[1 Scope 9](#scope)

[2 Normative references 10](#normative-references)

[3 Terms, definitions and abbreviated terms
11](#terms-definitions-and-abbreviated-terms)

[3.1 Terms from other standards 11](#terms-from-other-standards)

[3.2 Abbreviated terms 11](#abbreviated-terms)

[4 Liquid propulsion systems for spacecraft
12](#liquid-propulsion-systems-for-spacecraft)

[4.1 Overview 12](#overview)

[4.2 Functional 12](#functional)

[4.2.1 Mission 12](#mission)

[4.2.2 Functions 13](#functions)

[4.3 Constraints 13](#constraints)

[4.3.1 Accelerations 13](#accelerations)

[4.3.2 Pressure vessels and pressurized components
14](#pressure-vessels-and-pressurized-components)

[4.3.3 Induced and environmental temperatures
14](#induced-and-environmental-temperatures)

[4.3.4 Thermal fluxes 14](#thermal-fluxes)

[4.3.5 Thruster plume effects 14](#thruster-plume-effects)

[4.4 Interfaces 14](#interfaces)

[4.5 Design 15](#design)

[4.5.1 General 15](#general)

[4.5.2 Selection 16](#selection)

[4.5.3 Sizing 17](#sizing)

[4.5.4 Design development 18](#design-development)

[4.5.5 Contamination 19](#contamination)

[4.5.6 Draining 19](#draining)

[4.5.7 Risk of explosion 20](#risk-of-explosion)

[4.5.8 Components guidelines 20](#components-guidelines)

[4.5.9 Filters 22](#filters)

[4.5.10 Pressure vessels 22](#pressure-vessels)

[4.5.11 Propellant tanks 22](#propellant-tanks)

[4.5.12 Blow-down ratio 24](#blow-down-ratio)

[4.5.13 Flow calibration 24](#flow-calibration)

[4.5.14 Thrusters 24](#thrusters)

[4.5.15 Thrust-vector control (TVC) 25](#thrust-vector-control-tvc)

[4.5.16 Pyrotechnic devices 26](#pyrotechnic-devices)

[4.5.17 Mass imbalance 26](#mass-imbalance)

[4.5.18 Monitoring and failure detection
26](#monitoring-and-failure-detection)

[4.5.19 Ground support equipment (GSE)
26](#ground-support-equipment-gse)

[4.6 Verification 27](#verification)

[4.6.1 General 27](#general-6)

[4.6.2 Verification by analysis 28](#verification-by-analysis)

[4.6.3 Verification by test 30](#verification-by-test)

[4.6.4 Data exchange for models 35](#data-exchange-for-models)

[4.7 Quality factors 35](#quality-factors)

[4.7.1 Reliability 35](#reliability)

[4.7.2 Production and manufacturing process
35](#production-and-manufacturing-process)

[4.8 Operation and disposal 35](#operation-and-disposal)

[4.8.1 General 35](#general-8)

[4.8.2 Operations on ground 36](#operations-on-ground)

[4.8.3 Tank operation 36](#tank-operation)

[4.8.4 Disposal 36](#disposal)

[4.9 Supporting documents 37](#supporting-documents)

[5 Electric propulsion systems for spacecraft
38](#electric-propulsion-systems-for-spacecraft)

[5.1 Overview 38](#overview-1)

[5.2 Functional 39](#functional-1)

[5.2.1 Mission 39](#mission-1)

[5.2.2 Function 39](#function)

[5.2.3 Performance 39](#performance)

[5.3 Constraints 40](#constraints-1)

[5.3.1 General 40](#general-9)

[5.3.2 Thermal fluxes 40](#thermal-fluxes-1)

[5.3.3 Thruster plume effects 41](#thruster-plume-effects-1)

[5.3.4 High frequency current loops 41](#high-frequency-current-loops)

[5.3.5 Electromagnetic compatibility 41](#electromagnetic-compatibility)

[5.3.6 Spacecraft charging 41](#spacecraft-charging)

[5.4 Interfaces 42](#interfaces-1)

[5.4.1 Interface with the spacecraft 42](#interface-with-the-spacecraft)

[5.4.2 Interface with the power bus 42](#interface-with-the-power-bus)

[5.5 Design 43](#design-1)

[5.5.1 General 43](#general-10)

[5.5.2 Selection 44](#selection-1)

[5.5.3 Sizing 45](#sizing-1)

[5.5.4 Design development 46](#design-development-1)

[5.5.5 Contamination 46](#contamination-2)

[5.5.6 Propellant protection 47](#propellant-protection)

[5.5.7 Components guidelines 47](#components-guidelines-1)

[5.5.8 Propellant management assembly
47](#propellant-management-assembly)

[5.5.9 Pressure vessels 48](#pressure-vessels-1)

[5.5.10 Propellant tanks 49](#propellant-tanks-1)

[5.5.11 Blow-down ratio 49](#blow-down-ratio-1)

[5.5.12 Thrusters 49](#thrusters-1)

[5.5.13 Thrust-vector control 52](#thrust-vector-control)

[5.5.14 Power supply, control and processing subsystem
52](#power-supply-control-and-processing-subsystem)

[5.5.15 Electrical design 53](#electrical-design)

[5.5.16 Pyrotechnic devices 54](#pyrotechnic-devices-1)

[5.5.17 Monitoring and failure detection
54](#monitoring-and-failure-detection-1)

[5.5.18 Ground support equipment (GSE)
55](#ground-support-equipment-gse-1)

[5.6 Verification 55](#verification-1)

[5.6.1 General 55](#general-18)

[5.6.2 Verification by analysis 56](#verification-by-analysis-1)

[5.6.3 Verification by test 57](#verification-by-test-1)

[5.6.4 Data exchange for models 59](#data-exchange-for-models-1)

[5.7 Quality factors 59](#quality-factors-1)

[5.7.1 Reliability 59](#reliability-1)

[5.7.2 Production and manufacturing 59](#production-and-manufacturing)

[5.8 Operation and disposal 59](#operation-and-disposal-1)

[5.9 Supporting documents 60](#supporting-documents-1)

[Bibliography 61](#bibliography)

Tables

[Table 4‑1: Component failure modes 20](#__RefHeading___Toc214790126)

 Introduction

The ECSS Propulsion standards structure is as follows.

ECSS-E-ST-35 Propulsion general requirements

-   Standards, covering particular type of propulsion

<!-- -->

-   ECSS-E-ST-35-01 Liquid and electric propulsion for spacecrafts

-   ECSS-E-ST-35-02 Solid propulsion for spacecrafts and launchers

-   ECSS-E-ST-35-03 Liquid propulsion for launchers

<!-- -->

-   Standard covering particular propulsion aspects

<!-- -->

-   ECSS-E-ST-35-06 Cleanliness requirements for spacecraft propulsion
    hardware

-   ECSS-E-ST-35-10 Compatibility testing for liquid propulsion systems

\
Scope
=====

This Standard defines the regulatory aspects applicable to elements and
processes for liquid, including cold gas, and electrical propulsion for
spacecraft. It specifies the activities to be performed in the
engineering of such propulsion systems, their applicability, and defines
the requirements for the engineering aspects: functional, interfaces,
environmental, design, quality factors, operational and verification.

General requirements applying to all type of Propulsion Systems
Engineering are defined in ECSS-E-ST-35.

This standard may be tailored for the specific characteristics and
constraints of a space project in conformance with ECSS-S-ST-00.

\
Normative references
====================

The following normative documents contain provisions which, through
reference in this text, constitute provisions of this ECSS Standard. For
dated references, subsequent amendments to, or revision of any of these
publications, do not apply. However, parties to agreements based on this
ECSS Standard are encouraged to investigate the possibility of applying
the more recent editions of the normative documents indicated below. For
undated references, the latest edition of the publication referred to
applies.

  ----------------- -------------------------------------------------------------
  ECSS-S-ST-00-01   ECSS system – Glossary of terms
  ECSS-E-ST-10      Space engineering – System engineering general requirements
  ECSS-E-ST-20      Space engineering – Electrical and electronic
  ECSS-E-ST-20-06   Space engineering – Spacecraft changing
  ECSS-E-ST-20-07   Space engineering – Electromagnetic compatibility
  ECSS-E-ST-31      Space engineering – Thermal control general requirements
  ECSS-E-ST-32      Space engineering – Structural general requirements
  ECSS-E-ST-35      Space engineering – Propulsion general requirements
  ECSS-Q-ST-30      Space product assurance – Dependability
                    
                    
  ----------------- -------------------------------------------------------------

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms from other standards
        --------------------------

For the purpose of this Standard, the terms and definitions from
ECSS-S-ST-00-01 and ECSS-E-ST-35 apply.

Abbreviated terms
-----------------

For the purpose of this Standard, the abbreviated terms from
ECSS-ST-00-01 apply.

1.  \
    Liquid propulsion systems for spacecraft
    ========================================

    1.  Overview
        --------

Liquid propulsion systems for spacecraft provide the forces and torques
for orbit transfer, orbit maintenance and attitude control. For
manoeuvrable spacecraft, capsules and transport vehicles, they provide
in addition the forces and torques for rendez-vous and docking.

Apart from what is specific for propellant combustion, liquid propulsion
criteria are also applicable to cold gas propulsion systems.

The present clause 4 covers also the design and use of propulsion ground
support equipment (GSE), defined in ECSS-E-ST-70.

1.  Functional
    ----------

    1.  ### Mission

        a.  The propulsion system shall conform to the spacecraft
            mission requirements including:

            1.  Ground operations

<!-- -->

1.  For example: functional control, testing, propellant, simulant
    > loading and spacecraft transportation.

    1.  Pre-launch and launch activities

2.  For example: integration, storage, ageing and transport.

    1.  In-orbit operations.

3.  For example: orbit transfer, orbit maintenance and attitude control)
    > and the complete in-orbit life.

    1.  ### Functions

        a.  The propulsion system shall provide the total impulse,
            minimum impulse bit, thrust levels and torques required by
            the AOCS.

        b.  The following aspects shall be defined:

            1.  Thruster firing modes

4.  For example: steady state, off-modulation, pulse mode.

    1.  Thrust level and orientation

    2.  Thrust-vector control

    3.  Thrust centroid time

    4.  Minimum impulse bit

    5.  Impulse reproducibility

    6.  Total impulse

    7.  Cycle life

    8.  Mission life

    9.  Reliability level

    10. Thrust noise

    11. Propellant gauging.

    <!-- -->

    a.  The propulsion system shall fulfil its functions while subjected
        to the specified external loads during its mission, including:

        1.  mechanical loads;

5.  For example: quasi-static loads, vibrations, transportation.

    1.  thermal loads;

    2.  electrical loads.

    <!-- -->

    1.  Constraints
        -----------

        1.  ### Accelerations

            a.  Limits on acceleration levels, induced or experienced by
                the propulsion system, shall be specified at spacecraft
                level.

6.  This is in order to:

-   avoid perturbations, e.g. during possible observations or
    > experiments;

-   protect sensitive equipments;

-   design adequate tank PMD.

    1.  ### Pressure vessels and pressurized components

        a.  Support structures of pressure vessels and pressurized
            components shall allow deformations of the vessels due to
            pressure or temperature changes and cycles to occur without
            causing stresses that exceed acceptable limits.

    2.  ### Induced and environmental temperatures

        a.  The non-operating and operating temperature limitations of
            the propulsion system shall be specified.

    3.  ### Thermal fluxes

        a.  []{#_Ref207609625 .anchor}Thruster surroundings shall
            conform to the radiative and conductive heat fluxes rejected
            by the thrusters.

    4.  ### Thruster plume effects 

        a.  []{#_Ref197770232 .anchor}Elements of the spacecraft
            sensitive to plume effects shall be identified.

        b.  []{#_Ref197915887 .anchor}The allowed plume effects on
            elements identified in clause 1.1.1.1.1i shall be specified
            at spacecraft level.

        c.  []{#_Ref197770277 .anchor}The generation of perturbing
            torques, forces, thermal gradients, contamination and
            erosion of surfaces, due to plume effects, shall be defined
            and documented accordingly.

        d.  The plume analysis specified in 1.1.1.1.1k shall be reported
            in conformance with the Plume analysis report DRD in
            ECSS-E-ST-35.

    <!-- -->

    1.  Interfaces
        ----------

        a.  The liquid propulsion system shall conform to its specified
            spacecraft interfaces, including:

            1.  Structure

1.  For example: inserts, tank support structure and vibration levels.

    1.  Thermal

2.  For example: conduction, radiation levels, tank, thruster and line
    > thermal control.

    1.  Power

3.  For example: valve drivers, pressure transducers, thermistors,
    > heaters and thermocouples.

    1.  Electromagnetic compatibility

    2.  Pyrotechnics

4.  For example: pyrotechnic valves.

    1.  Mechanisms

5.  For example: valves, regulators, actuators and actuation system.

    1.  AOCS, OBDH and TM/TC.

6.  For example: commanding, handling of data for status and health
    > monitoring and failure detection.

    a.  Interfaces shall be defined:

        1.  For ground tests and loading activities, with the propulsion
            GSE.

        2.  For safety and prelaunch operation with the launcher
            authorities.

    <!-- -->

    1.  Design
        ------

        1.  ### General

            1.  #### Architecture

                a.  The propulsion system architecture shall apply the
                    requirements in ECSS-Q-ST-30.

                b.  The propulsion system architecture shall provide
                    evidence that fail safe, redundancy, reliability and
                    safety requirements are met.

            2.  #### Replacement of parts

                a.  For replacement of parts during development, testing
                    and mission life pre-launch activities ECSS-E-ST-35,
                    requirements 4.5.1c, d and e. shall be applied.

            3.  #### Water-hammer effect

                a.  []{#_Ref208209057 .anchor}A water-hammer effects
                    analysis shall be performed to support the
                    propulsion system design and ensure proper
                    functioning.

                b.  The analysis specified in 1.1.1.1.1r shall be
                    reported in conformance with the Propulsion
                    transient analysis report DRD in ECSS-E-ST-35.

            4.  #### Piping

                a.  A pipework design analysis shall be performed
                    including non-consumables, cross-coupling, leakage,
                    pressure, eigenfrequencies, water-hammer.

                b.  The consequences in terms of operational
                    restrictions shall be identified.

            5.  #### Closed volumes

                a.  The design of the propulsion system shall prevent
                    hazardous pressure increase in closed volumes.

                b.  The need for any pressure relief capability shall be
                    identified and analysed.

            6.  #### Pressure vessels and pressurized components

                a.  The design of pressure vessels and pressurized
                    components shall:

                    1.  Apply margins and factors of safety (FOS) for
                        proof, burst and component life cycle.

7.  See ECSS-E-ST-32-02.

    1.  Conform to the environmental aspects, including but not limited
        to:

        a.  Temperature

        b.  Vibration

        c.  Humidity

        d.  Corrosive environment

        e.  Vacuum

        f.  Outgassing

        g.  Radiation.

    <!-- -->

    1.  #### Multi-tanks

        a.  If a multi-tank layout is used, inadvertent propellant
            transfer between tanks shall be prevented by design.

        b.  If PMD tanks are being used, the consequences of selecting
            parallel or series connections shall be analysed.

    2.  #### Cycles

        a.  The system and its components shall be designed for the
            expected number of cycles during the whole mission life, for
            both on-ground and in-service operation.

    <!-- -->

    1.  ### Selection

        1.  #### Reporting

            a.  The reporting shall be done in the DJF in conformance
                with ECSS-E-ST-10.

        2.  #### General

            a.  The selection shall be based on trade-off analyses of:

                1.  The propulsion system.

8.  For example: monopropellant, bipropellant, or cold gas.

    1.  The operating mode.

9.  For example: pressure regulated and blow-down.

    a.  Selected materials, propellants and test fluids shall be
        compatible for all components.

10. Compatibility includes:

-   dissolution;

-   chemical reaction;

-   erosion;

-   corrosion.

    1.  #### Propellant selection

        1.  ##### General

            a.  The criteria to be used for propellant selection shall
                include:

                1.  Mission requirements

                2.  Resulting layout of the propulsion system

                3.  Availability of off-the-shelf components

                4.  Experience

                5.  Compatibility and contamination

                6.  Performance.

            b.  The propellant shall be defined and specified including:

                1.  Chemical composition

                2.  Purity

                3.  Cleanliness.

        2.  ##### Propellant for Thruster qualification

            a.  Thruster qualification firing tests shall use the same
                propellant grade as the one selected for flight.

    <!-- -->

    1.  ### Sizing

        a.  The sizing process shall begin with a definition of the life
            phases of each subsystem or component, including at least:

            1.  Pressure cycles combined with temperature cycles

            2.  Propellant, pressurant and leakage budgets

            3.  Establishment of the operational envelope

            4.  Minimum and maximum electrical supply voltages

            5.  Interfaces with GSE functions

            6.  Evolution of the operational conditions.

        b.  The sizing process shall demonstrate margins based on:

            1.  Safety

            2.  Reliability requirements established by the customer

            3.  Industry and launch authorities, or agencies operational
                constraints

            4.  Thruster performance efficiency

            5.  Plume effects

            6.  Modelling errors and uncertainties.

        c.  Pressurant, propellant and contaminants budgets shall
            include:

            1.  Their impact on lifetime

            2.  Variation of performance during lifetime

            3.  Quantity for deorbiting

            4.  Residuals.

    2.  ### Design development

        1.  #### General

            a.  The development shall allow for an incremental
                verification at component or block level, if a fully
                representative functional test (i.e. hot firing and
                gravity-dependent functions) cannot be performed after
                the integration of the system components on the
                spacecraft.

            b.  If the flight version of the system is divided into
                independent blocks, they should be separated by safety
                barriers such as pyrovalves, latch valves or burst
                membranes.

        2.  #### Development tests

            a.  Development tests of each block should be defined to
                represent the conditions foreseen during the operation
                of the complete system.

            b.  At least the following characteristics of the propellant
                feed system shall be determined by hydraulic tests:

                1.  mass flow rate;

                2.  dynamic and static pressure;

                3.  temperature;

                4.  response time.

            c.  []{#_Ref197915611 .anchor}The testability at integrated
                spacecraft level and the ability to return after test to
                safe and clean conditions shall be demonstrated for each
                of the system blocks.

            d.  Design and procedures shall be defined according to
                1.1.1.1.1oo.

    3.  ### Contamination

        1.  #### External contamination

            a.  The thruster design, layout and orientation should
                prevent contaminant deposition on elements sensitive to
                contamination identified in clause 1.1.1.1.1i.

1.  Contaminants deposition on sensitive elements, such as solar panels,
    > star trackers, and optics, depends on the propellants used, the
    > thruster characteristics, the layout of the propulsion system, the
    > thruster orientation and the thruster duty cycle.

    a.  The potential hazard of contamination and the expected level of
        contamination due to thruster exhaust shall be included in the
        plume analysis.

2.  See clause 1.1.1.1.1k.

    1.  #### Internal contamination 

        a.  The propulsion system shall be designed to avoid the effects
            of internal contaminants, including propellant vapours, by:

            1.  Preventing intrusion, internal generation and
                circulation of contaminants.

            2.  Preventing or controlling accumulation of contaminants
                throughout the various parts of the system.

            3.  Preventing accumulation of contaminants during the
                various steps of production, verification and operation
                of the system.

<!-- -->

1.  1 The presence of contaminants inside the propulsion system can lead
    > to the loss of performance of some components or even to
    > catastrophic failures.

2.  2 For example, propellant vapours can be considered as contaminants
    > in a pressurisation system.

    a.  []{#_Ref207624172 .anchor}The expected maximum level of
        contaminants inside the propulsion system shall be specified.

    b.  The propulsion system design shall conform to the expected
        maximum level of contaminants.

    <!-- -->

    1.  ### Draining

        a.  The system design shall allow for on-ground draining.

        b.  The location of fill-and-drain valves and piping layout
            shall:

            1.  Prevent trapping of liquid in the system by on-ground
                draining.

            2.  Prevent contact between dissimilar fluids.

            3.  Allow purging of the system after draining.

    2.  ### Risk of explosion

        a.  For hydrazine and other monopropellants, adiabatic
            compression of vapours, hot spots or undesired contact with
            a catalyst material shall be avoided.

        b.  []{#_Ref197915465 .anchor}Propellant explosions, leakage of
            propellant and propellant vapours shall be prevented.

        c.  Item 1.1.1.1.1yy shall be supported by analysis, simulation,
            or testing or all of them.

        d.  The propulsion system design shall ensure elimination of
            undesired mixtures, migration or leakage of propellant and
            propellant vapours, and condensation of fuel.

        e.  The propulsion system requirements shall specify operation
            under conditions different from operational conditions, such
            as ground tests.

    3.  ### Components guidelines

        a.  A design assessment for failure tolerance shall be performed
            for every component.

3.  1 See ECSS-Q-ST-30-02.

4.  2 Table Liquid propulsion systems for spacecraft-1 covers the
    > component failure modes generally encountered in the use of
    > standard components. Failure to operate are not mentioned while
    > external leakage is only reported for tanks and tubing.

> [[]{#_Ref197770538 .anchor}]{#__RefHeading___Toc214790126
> .anchor}Table Chapter‑1: Component failure modes

+-----------------+-----------------+-----------------+-----------------+
| Component\      | Failure\        | Failure\        | Failure\        |
| type            | mode            | detection       | prevention      |
+-----------------+-----------------+-----------------+-----------------+
| Tanks, tubing   | Crack growth    | External        | Analysis        |
|                 |                 | leakage         |                 |
+-----------------+-----------------+-----------------+-----------------+
|                 | Corrosion       | - Visual        | - Surface       |
|                 | pitting         | inspection      | treatment       |
|                 |                 |                 |                 |
|                 |                 | - Contamination | - Material      |
|                 |                 |                 | selection       |
+-----------------+-----------------+-----------------+-----------------+
|                 | Internal        | - Decreased     | - Design,       |
|                 | leakage         | expulsion\      |    manufacturin |
|                 | (diaphragms)    |  efficiency     | g               |
|                 |                 |                 |    procedures,  |
|                 |                 | - gas bubble    | quality         |
|                 |                 | in\             |    control      |
|                 |                 |  propellant     |                 |
|                 |                 |                 | - material      |
|                 |                 |                 | selection       |
+-----------------+-----------------+-----------------+-----------------+
|                 | Structural      | - Visual        | Design, quality |
|                 | failure of PMD  | inspection      | control         |
|                 | screens         |                 | manufacturing   |
|                 |                 | - X-ray,        | procedures      |
|                 |                 | Ultrasound      |                 |
+-----------------+-----------------+-----------------+-----------------+
| Pressure        | Internal        | Pressure test   | Cleanliness     |
| regulator       | leakage         |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| Electrically    | - Undesired     | - Pressure test | - Electrical    |
| actuated valves | operation       |                 | inhibits        |
|                 |                 | - Position      |                 |
|                 | - Internal      | indication      | - Cleanliness   |
|                 | leakage         |                 |                 |
|                 |                 | - Internal leak |                 |
|                 |                 | test            |                 |
+-----------------+-----------------+-----------------+-----------------+
| Pneumatically   | - Undesired\    | - Pressure test | Cleanliness     |
| actuated valves | operation       |                 |                 |
|                 |                 | - Position      |                 |
|                 | - Internal      | indication      |                 |
|                 | leakage         |                 |                 |
|                 |                 | - Internal leak |                 |
|                 |                 | test            |                 |
+-----------------+-----------------+-----------------+-----------------+
| Propellant      | Undesired       | Leakage         | Cleanliness     |
| fill-and-drain  | operation       |                 |                 |
| valves          |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
|                 | Propellant      | Chemical        | Use of:\        |
|                 | mixing          | reaction        | - different     |
|                 |                 |                 | colours\        |
|                 |                 |                 | for components\ |
|                 |                 |                 | - different     |
|                 |                 |                 | connectors\     |
|                 |                 |                 | (size and       |
|                 |                 |                 | thread)         |
+-----------------+-----------------+-----------------+-----------------+
| Manually        | Internal        | - Pressure test | - Cleanliness   |
| actuated valves | leakage         |                 |                 |
|                 |                 | - Internal leak |                 |
|                 |                 | test            |                 |
+-----------------+-----------------+-----------------+-----------------+
| Non-return      | Internal        | - Pressure test | - Cleanliness   |
| valves          | leakage         |                 |                 |
|                 |                 | - Internal leak | - Design        |
|                 |                 | test            | assessment      |
+-----------------+-----------------+-----------------+-----------------+
| Pyrovalves      | Undesired       | Pressure test   | - Electrical    |
|                 | operation       |                 | inhibits        |
|                 |                 |                 |                 |
|                 |                 |                 | - Cleanliness   |
+-----------------+-----------------+-----------------+-----------------+
|                 | Particle        | Pressure test & | Design          |
|                 | generation      | Ground test     | assessment      |
+-----------------+-----------------+-----------------+-----------------+
| Thrust chambers | Structural      | Firing test     | Design          |
| and nozzles     | failure         |                 | assessment      |
+-----------------+-----------------+-----------------+-----------------+
|                 | Overheating     | Firing test     | Design          |
|                 | cooling circuit |                 | assessment      |
+-----------------+-----------------+-----------------+-----------------+
|                 | Loss of         | Gas-flow test   | - Shock         |
|                 | catalyst        |                 | absorber,\      |
|                 | integrity       |                 | orientation of\ |
|                 |                 |                 | thruster.       |
|                 |                 |                 |                 |
|                 |                 |                 | - Preheating    |
|                 |                 |                 | of\             |
|                 |                 |                 | catalyst bed    |
+-----------------+-----------------+-----------------+-----------------+
|                 | Catalyst        | Performance     | - Use of        |
|                 | poisoning       | loss            | purified\       |
|                 |                 |                 | anhydrous\      |
|                 |                 |                 | hydrazine;      |
|                 |                 |                 |                 |
|                 |                 |                 | - Si-leaching\  |
|                 |                 |                 | minimization    |
|                 |                 |                 | from\           |
|                 |                 |                 | bladder or\     |
|                 |                 |                 | diaphragm       |
|                 |                 |                 | tanks.          |
+-----------------+-----------------+-----------------+-----------------+
| Filters         | Clogging        | Pressure test   | Cleanliness     |
+-----------------+-----------------+-----------------+-----------------+
| Pressure        | Zero shift,     | Calibration     | -               |
| transducer      | measurement     |                 |                 |
|                 | anomalies       |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| Orifices,       | Clogging        | Pressure test   | Cleanliness     |
| cavitating      |                 |                 |                 |
| venturis, flow  |                 |                 |                 |
| restrictors     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+

1.  ### Filters

    a.  All filters used at system or component level shall be designed
        and positioned according to the results of contaminant control
        and reliability studies.

    b.  Filters shall be installed immediately downstream of potential
        particle generating components and, depending on the result of
        the failure risk analysis, directly upstream of components
        sensitive to pollution or contamination.

<!-- -->

1.  For example: actuation valves, pressure regulators, injectors and
    > thrusters.

    a.  Design of filters shall cover at least:

        1.  Total throughput

        2.  Retention capacity

        3.  Pressure drop

        4.  Absolute and relative filtering rate

        5.  Particle size.

    <!-- -->

    1.  ### Pressure vessels

        a.  In order to eliminate explosion or leakage risks,
            requirements on design, development, production,
            verification and operation of pressure vessels for
            propulsion systems shall be addressed specifically.

2.  For design and verification requirements of pressured vessels see
    > ECSS-E-ST-32-02.

    1.  ### Propellant tanks

        1.  #### General

            a.  The tank design shall account for all forces acting on
                the propellant during ground handling and all mission
                phases.

            b.  To avoid propellant freezing and control propellant tank
                pressures, the tank and line temperatures shall be
                controlled during the whole mission.

            c.  []{#_Ref207607827 .anchor}The tank design shall comply
                with the propellant gauging requirements.

            d.  The reporting of the item identified in 1.1.1.1.1jjj
                shall be in conformance with the Gauging analysis report
                DRD in ECSS-E-ST-35.

            e.  Propellant tank design shall prevent ingestion of
                pressurant gas into the propellant supply lines during
                ground handling and all mission phases.

            f.  The tank design shall comply with sloshing requirements.

            g.  Propellant tanks shall provide the thrusters with
                propellants according to their specified conditions.

            h.  The tanks shall conform to the dynamic spacecraft
                specifications.

<!-- -->

1.  1 Commonly used tanks on spacecraft are:

-   Simple shell, (tank without internal devices).

-   Positive Expulsion Device (PED) tanks (e.g. diaphragm, bladder and
    > bellows).

-   Surface Tension Device (STD) or Propellant Management Device (PMD)
    > tanks.

1.  2 Propellant tanks can contain the following additional devices:

-   Anti-vortex, to ensure a proper propellant expulsion and to avoid
    > gas ingestion.

-   Sumps, to allow engine starts in a zero gravity environment; they
    > can be combined with a gauging device and an anti-vortex device.

-   Baffles or other anti-sloshing devices, selected and dimensioned
    > according to spacecraft standards and mission requirements.

-   Gauging devices, selected in conformance with the selected tank type
    > and the spacecraft and mission requirements.

    1.  #### Positive expulsion device (PED) tanks

        a.  The materials used for PEDs shall be selected according to,
            at least:

            1.  Contamination into propellant

1.  For example: by silica-leaching.

    1.  Pressurant gas permeation through the PED

    2.  Propellant adsorption

    3.  Material compatibility.

2.  For example: very slow propellant decomposition and gas formation.

    a.  In case metallic diaphragms are used in a multiple tank
        configuration, the design shall prevent asymmetrical depletion.

    b.  The design of the PED tank shall comply with the launch
        configuration

3.  For example: filling ratio.

    1.  #### Surface tension device (STD) tanks

        a.  Due to the difficulty of on-ground functional testing, the
            STD design shall be supported by:

            1.  A detailed analysis allocating margins for all mission
                phases.

            2.  A demonstration plan including tests.

4.  For example: neutral buoyancy, bubble point, expulsion against
    > gravity.

    1.  ### Blow-down ratio

        a.  For propulsion systems working in blow-down mode, the ratio
            of pressurant volume between BOL and EOL shall be consistent
            with thruster specifications.

5.  For example: I~sp~, combustion stability and mixture ratio shift.

    1.  ### Flow calibration

        a.  The flow calibration of the propulsion system shall ensure
            the performance of thrusters for every phase of the mission
            and environmental conditions.

        b.  Flow calibration can be done at propulsion system or
            thruster level.

    2.  ### Thrusters

        a.  The thruster design shall comply with operating conditions
            including:

            1.  Inlet pressure range

            2.  Temperature range for both propellant and thruster

            3.  Voltage range.

        <!-- -->

        1.  #### Thruster alignment

            a.  The support structure shall allow the installation of a
                device to adjust thruster alignment.

        2.  #### Thrust mismatch

            a.  The difference in thrust between two thrusters operating
                in pair on the same branch shall meet the thrust
                mismatch requirements.

        3.  #### Flow calibration orifices

            a.  Flow calibration orifices, if necessary, shall be
                designed to adapt pressure and flow rates, based on the
                analysis of:

                1.  Pressure drop

                2.  Mixture ratio

                3.  Spacecraft CoM shift

                4.  Thruster cross-coupling

                5.  Temperature.

        4.  #### Heat soak-back

            a.  The thruster design shall allow nominal operation during
                possible heat soak-back conditions inherent to the
                specified thruster operation modes (i.e. duty cycles).

            b.  The thruster integrity shall not be impaired by heat
                soak-back.

        5.  #### Catalyst bed heating

            a.  Early thruster performance degradation of thrusters
                using catalysts shall be avoided by providing means to
                heat up the catalyst bed before firing.

        6.  #### Thermal environment

            a.  To avoid overheating of the thruster, its thermal
                behaviour, when integrated with the spacecraft, shall be
                analysed.

            b.  Reporting of the analysis specified in a. shall be in
                conformance with the Thermal analysis DRD in
                ECSS-E-ST-31 and the Addendum: Specific propulsion
                aspects for thermal analysis DRD in ECSS-E-ST-35.

        7.  #### Impulse bit repeatability

            a.  Impulse bit repeatability requirements shall comply with
                AOCS requirements.

            b.  The influence of impulse bit repeatability on the
                propellant budget at system level shall be defined.

6.  Stringent requirements on impulse bit repeatability have an impact
    > on propulsion system complexity due to the difficulties to
    > identify and act upon the sources for deviations (e.g. dribble
    > volume, valve function, soak-back conditions and previous thruster
    > operation) and to verify conformity to the specification (e.g.
    > test conditions and test evaluation).

    1.  ### Thrust-vector control (TVC)

        a.  Thrust-vector control shall allow adjustment of the
            thrust-vector direction on command.

        b.  At engine level, the following parameters shall be known:

            1.  Mass and CoM of the movable part of the engine

            2.  Inertia of the movable part of the engine

            3.  The needed torque

7.  The needed torque is calculated taking into account all
    > contributions, joints, feed lines and other flexible lines or
    > connections.

    1.  The engine structural dynamics in the operational configuration.

    <!-- -->

    a.  For the performance of the TVC system, the following parameters
        shall be used:

        1.  The maximum thrust deflection angle

        2.  The accuracy and repeatability

        3.  The response times for:

            a.  command to actuation;

            b.  actuation to full deflection and back.

    b.  The stiffness of the engine mounting, including feed lines and
        piping, and the actuator mounting on the engine shall meet the
        minimum values.

    <!-- -->

    1.  ### Pyrotechnic devices

        a.  Each pyrovalve should be designed to prohibit wrong
            connection.

8.  For pyrotechnics devices, see ECSS-E-ST-33-11.

    1.  ### Mass imbalance

        a.  The maximum mass imbalance of the propulsion system shall be
            specified.

9.  The spacecraft centre of mass changes through the mission due to
    > tank depletion and thermal differentials.

    1.  ### Monitoring and failure detection 

        a.  Health monitoring and failure detection shall be available
            through telemetry.

<!-- -->

1.  1 Pressure and temperature of tanks, valve status and operating
    > branch pressure measurements are recommended as a minimum.

2.  2 Thrusters operation and health can be monitored with thermocouples
    > or thermistors, but also additional equipments (e.g. pressure
    > transducers and accelerometers).

    a.  The minimum monitoring needs allowing a safe mode operation
        shall be identified.

    b.  The autonomous actions required to allow a safe operation shall
        be identified.

    c.  Monitoring shall ensure the propellant gauging function.

    <!-- -->

    1.  ### Ground support equipment (GSE)

        1.  #### General

            a.  The design of the propulsion GSE shall conform to the
                safety requirements of the facility where it is
                operated.

            b.  The design of the GSE and the procedures to operate it
                shall prevent the inadvertent activation of the systems
                and subsystems.

        2.  #### Fluid

            a.  The GSE design and the procedures to operate it shall
                prevent the spillage or venting of dangerous materials.

            b.  The design shall prevent overpressures exceeding the
                applicable MEOP with a safety factor.

            c.  The design shall provide evacuation lines to the
                facilities in case of operation of any relief valve.

<!-- -->

1.  See ECSS-E-ST-70 for general specification regarding ground support.

    a.  The design shall prevent contact between materials causing
        hazards, such as explosion, chemical reaction and poisoning.

    b.  The GSE design, functioning and procedures shall ensure that the
        fluids delivered to the spacecraft, including the effects of
        dissolved gas, are conforming to the required levels of:

        1.  Contamination

        2.  Pressure

        3.  Temperature

        4.  Cleanliness.

    <!-- -->

    1.  #### Electrical

        a.  The design of the GSE shall allow the safe check-out of all
            electrical components.

        b.  In case the GSE is used in the vicinity of inflammable or
            explosive materials, it shall be explosion proof.

    <!-- -->

    1.  Verification
        ------------

        1.  ### General

            a.  A verification matrix shall be established indicating
                the type of verification method to apply for the
                individual requirements.

<!-- -->

1.  1 For verification of liquid propulsion systems, see
    > ECSS-E-ST-10-02.

2.  2 Verification is performed to demonstrate that the system or
    > subsystem fully conforms to the requirements. This can be achieved
    > by adequately documented analysis, tests, review of the design,
    > inspection, or by a combination of them.

3.  3 In the following clauses of this clause 4.6, it is considered
    > that:

-   verification by review of the design is included in verification by
    > analysis, and

-   verification by inspection is included in verification by test.

    1.  ### Verification by analysis

        1.  #### Propellant and pressurant

            a.  Propellant and pressurant grade and the associated
                database on the physico-chemical characteristics, to be
                used for the analyses, shall be defined.

        2.  #### Steady state

            1.  ##### General

                a.  Representative validated models shall be used.

            2.  ##### Steady-state characteristics

                a.  The establishment of the steady-state
                    characteristics for the complete set of operating
                    conditions of the propulsion system shall be
                    performed including:

                    1.  []{#_Ref207607328 .anchor}The establishment of:

                        a.  The pressure losses in lines and components.

                        b.  The mixture ratio shifts and their effects
                            on propellant residuals, propellant budgets
                            and the thruster performance shifts.

                        c.  The mass of unusable propellants due to tank
                            expulsion efficiencies, line and component
                            trapping, propellant vaporization, leakage
                            and permeation, and thermal gradients
                            between tanks.

                        d.  In case of a blow-down analysis, the
                            evaluation of the pressure through the
                            mission life, using the temperature history
                            during the mission.

                    2.  The analysis of the aspects specified in
                        1.1.1.1.1ddddd.1, reported in conformance with
                        the Propulsion performance analysis report DRD
                        in ECSS-E-ST-35.

                    3.  The demonstration by the pressurant budget, that
                        the amount of pressurant gas carried on-board,
                        with the expected leakage, permeation,
                        evaporation and pressurant dissolution, ensures
                        a proper thruster inlet pressure throughout the
                        mission.

                    4.  The demonstration by the PMD analysis, of its
                        proper functioning with a sufficient margin in
                        all mission phases.

            3.  ##### Thermal analysis

                a.  Thruster thermal analysis shall be:

                    1.  performed to demonstrate its compatibility with
                        the external environment and proper thruster
                        operation.

1.  For example: limitation of flow control valve and surroundings
    > temperature, and vapour lock.

    1.  reported in conformance with the Thermal analysis DRD in
        ECSS-E-ST-31 and the Addendum: Specific propulsion aspects for
        thermal analysis DRD in ECSS-E-ST-35.

    <!-- -->

    1.  ##### Leakage budget

        a.  The maximum acceptable leakage rate of the system and its
            valves shall be analysed with regard to the total mission
            duration, on ground and in flight.

    2.  ##### Contamination 

        a.  Analysis of the total contamination throughout the mission
            shall show that a sufficient margin exists before blocking
            of flow passages, and a subsequent reduction in system
            performances occurs.

2.  Blocking of flow passages can occur in, e.g. filters, vales and
    > orifices.

    1.  ##### Plume analysis

        a.  The impact of the thruster plumes on the structure,
            experiments and spacecraft motion shall be analysed at
            spacecraft level.

        b.  It shall be established whether protection devices are
            required at spacecraft level.

        c.  The plume effects on the propulsion system performance shall
            be evaluated.

        d.  The plume analysis shall be reported in conformance with the
            Plume analysis report DRD in ECSS-E-ST-35.

    2.  ##### Gauging analysis

        a.  The gauging analysis shall demonstrate that the required
            accuracy is obtained with the on-board measurement equipment
            and its related data handling.

        b.  The gauging analysis shall be reported in conformance with
            the Gauging analysis report DRD in ECSS-E-ST-35.

    3.  ##### CoM shift

        a.  Analyses shall show that the spacecraft CoM remains within
            the specified CoM shift.

    4.  ##### Tank pressurization 

        a.  The effects of temperature and pressure on the pressurant,
            propellant and tank shell, pressurant dissolution and tank
            shell deformation shall be used for an accurate tank
            pressurization analysis.

    <!-- -->

    1.  #### Transients

        1.  ##### Reporting

            a.  The transient analyses of clause 4.6.2.3 shall be
                reported in conformance with the Propulsion transient
                analysis report DRD in ECSS-E-ST-35.

            b.  The mathematical modelling specified in 4.6.2.3 shall be
                reported in conformance with the Mathematical modelling
                for propulsion analysis DRD in ECSS-E-ST-35.

        2.  ##### Pressure transients

            a.  The effects of rapid pressurization due to line priming
                shall be assessed by analysis.

            b.  The risk of propellant adiabatic decomposition shall be
                analysed.

        3.  ##### Thruster cross-coupling

            a.  If several thrusters are operated simultaneously, the
                cross-coupling effect of pressure fluctuations created
                by the actuation of flow control valves (i.e. thruster
                performance and valve operation) shall be analysed.

        4.  ##### Water-hammer effects.

            a.  Water-hammer effects shall be analysed including:

                1.  Failure of lines (tubes) or components

                2.  Adiabatic decomposition of propellants

                3.  Cross-coupling between valves or thrusters.

        5.  ##### Sloshing

            a.  Oscillations induced by the motion of the propellant in
                the tanks on the spacecraft structure and stability
                shall be analysed.

            b.  A representative model of the tank and fluid behaviour
                shall be used for the sloshing analysis.

            c.  Sloshing analysis shall be reported in conformance with
                the Sloshing analysis report DRD in ECSS-E-ST-35.

        6.  ##### Spin load

            a.  The effect of spacecraft rotation on propellant motion
                during the mission shall be assessed by analysis.

    <!-- -->

    1.  ### Verification by test

        1.  #### Thruster firing test

            a.  The conformity of the thrusters to their requirements
                shall be verified by test.

            b.  Thruster firing tests shall be performed to verify the
                performance of the thrusters with the following
                parameters:

                1.  Range of inlet pressures

                2.  Ambient pressure

                3.  Propellant temperatures

                4.  Dissolved gas in propellant

                5.  Thermal environment

                6.  Specified duty cycles

                7.  Lifetime

                8.  Initial chamber temperature

                9.  Contaminants throughput

                10. Valve voltage.

            c.  Thruster firing tests shall verify:

                1.  Combustion stability

                2.  Start and stop transient

                3.  Thermal design

                4.  performance over life, including at least:

                    a.  I~sp~

                    b.  Thrust level

                    c.  Impulse bit

                    d.  Response delays

                    e.  Thruster temperature.

            d.  Thruster firing tests shall be used to establish the
                performance model.

        2.  #### Proof pressure test

            a.  Proof pressure tests shall be performed on all pressure
                vessels and pressurized components.

3.  For minimum factors of safety, see [[]{#OLE_LINK1
    > .anchor}]{#OLE_LINK2 .anchor}ECSS-E-ST-32-02.

    a.  As proof pressure tests are major contributors to crack growth,
        the number of proof pressure tests shall conform to the fracture
        control plan.

    b.  Stress corrosion cracking effects resulting from proof pressure
        tests may be neglected if the total duration of these tests is
        limited, this limit being defined on a case by case basis.

<!-- -->

1.  1 This limit depends on the characteristics of materials in contact
    > and mission requirements.

2.  2 See ECSS-Q-ST-70-36 and NASA-MSFC-SPEC-522B.

    a.  A system proof test shall be conducted at a pressure higher than
        the system MEOP.

<!-- -->

1.  For details on ‘proof pressure test’ see ECSS-E-ST-10-03.

    a.  Component proof pressure tests shall conducted at a pressure
        higher than the particular MEOP of this component.

2.  For details on ‘proof pressure test’ see ECSS-E-ST-10-03.

    a.  All welds in lines and fittings shall either be proof tested to
        at least 1,5 MEOP or subject to full NDI.

3.  The proof testing can be restricted to component-level verification.

    1.  #### Burst pressure test 

        a.  Only the qualification test programmes for pressure vessels
            and other pressurized components, except lines and fittings,
            shall include a burst test.

        b.  The test shall be performed either

-   up to rupture; or

-   up to the design burst pressure as defined in ECSS-E-ST-32
    maintained for a minimum 30 seconds.

    a.  Fluids used for burst pressure should be liquids;

    b.  Fluids used for burst pressure shall:

        1.  Not pose a hazard to test personnel.

        2.  Be compatible with the structural material in the
            pressurized hardware.

1.  See also ISO/CD 14623-1, ISO/AWI 14623-2, AIAA S-080-1998, AIAA
    > S-081-1999.

    1.  #### Cleanliness control

        1.  ##### Particulate

            a.  A control of the maximum allowable number of particles
                shall be performed adequately, using the system,
                subsystem, and component level requirements and the
                particle size, particle type and the minimum clearances.

        2.  ##### Non-volatile residue

            a.  The non-volatile residue content of liquid to enter the
                propulsion system shall be specified in the standards
                for these liquids.

            b.  A control of the non-volatile residue content in the
                liquid introduced into the system and of the wetted
                surfaces shall be performed.

    2.  #### Contamination control

        a.  In case the parameters for total contamination defined 4.5.5
            cannot be verified by analysis, specific tests shall be
            conducted to establish the evolution of the level of
            contamination over time.

2.  Accelerated tests can be used.

    a.  The total contamination verification shall include at least the
        following aspects when applicable:

        1.  Dissolution of silica into hydrazine and hydrazine
            compounds.

        2.  The chemical reaction between propellants and metals.

        3.  The dissolution of chemicals from seals, diaphragms, and
            other elements into propellants or gases.

    <!-- -->

    1.  #### Compatibility

        a.  In case the compatibility between propellants and materials
            in possible contact with each other, and between dissimilar
            materials in contact with each other, is not known, the
            conformance to the compatibility requirements shall be
            established over time.

3.  Accelerated tests can be used.

    1.  #### Pressure transients test

        a.  []{#_Ref197915536 .anchor}In those cases where verification
            by analysis is considered inadequate, tests shall be
            performed to verify the adequacy of the design of the
            propulsion system with respect to pressure and flow
            transients.

        b.  Cases addressed in 1.1.1.1.1tttttt shall include at least:

            1.  Water-hammer effects

            2.  Transients during system pressurisation

            3.  Design of flow orifices

            4.  Thruster cross-coupling effects

            5.  Hydrazine detonation due to adiabatic compression when
                applicable.

        c.  Due to the very quick response of the phenomena,
            high-frequency measurement devices and data acquisition
            shall be used for pressure transients test.

        d.  The system or subsystem to be tested shall be representative
            of the flight one.

        e.  For the tests, real propellants and pressurant gases should
            be used.

        f.  For liquid propellants, gas saturation shall be
            representative.

    2.  #### Tank expulsion efficiency

        a.  A verification of the tank expulsion efficiency shall be
            performed.

        b.  The test results, in combination with analysis, shall
            demonstrate the adequacy of the design with the specified
            margin under all mission conditions.

    3.  #### Flow test

        a.  During propulsion system development flow tests shall be
            performed to measure the performance of the feed system.

4.  For example: pressure losses.

    a.  During system AIT a flow test shall be performed to verify the
        proper functioning of the system.

5.  For example: gas flow test, proper connection of valves.

    a.  In case the pressure loss models or the models for the dynamic
        behaviour of the system are insufficiently known, this flow test
        should be extended to provide the required data.

    <!-- -->

    1.  #### Leak test

        a.  The system and the system components shall be tested for
            internal and external leakage.

        b.  A thruster gas flow test shall be performed at system level.

6.  By performing a flow test on a thruster, the confidence in the
    > functioning of the thruster without a hot firing test is
    > increased. The verification of the pressure through the thruster
    > injector head gives an indication of possible blockage by
    > particles.

    1.  #### Dryness

        a.  The level of residual humidity shall be specified.

        b.  The dryness control shall be performed before loading and
            after unloading.

7.  Humidity in the system can affect the material (e.g. stress
    > corrosion) and the propellant quality.

    1.  #### Electrical test

        a.  All electrical components shall be tested for their
            functionality.

        b.  In case a functional test is not possible electrical
            continuity shall be tested.

8.  For example: a functional test is not possible in the case of
    > initiators and pyrotechnic devices,

    1.  #### Thruster alignment

        a.  Thruster alignment shall be tested for conformity to the
            requirements.

    2.  #### Calibration

        a.  All components or subsystems that provide data shall be
            calibrated.

    3.  #### Ageing

        a.  For propulsion systems which are designed to be activated
            after extremely long periods, or which are designed to
            operate for long time, it shall be verified that the
            propulsion system still conforms to all requirements after
            representative ageing tests.

<!-- -->

1.  1 Tests can be performed at sample or component level, subsystem
    > level or system level.

2.  2 Example for extremely long periods: deep space or interplanetary
    > missions.

    1.  ### Data exchange for models

        a.  Test results, as well as all models shall be established and
            structured with a commonly agreed structure and format.

<!-- -->

1.  Examples of such models are: thermal, mechanical, performance
    > models.

    1.  Quality factors
        ---------------

        1.  ### Reliability

            a.  The design shall comply with the reliability
                requirements with respect to:

                1.  The probability of success of the mission

                2.  The design life.

        2.  ### Production and manufacturing process

            a.  Procedures shall be established and maintained to ensure
                that the production of components, subsystems and
                systems conforms to all the requirements.

            b.  Procedures to avoid contamination, to achieve and
                maintain cleanliness and to guarantee reproducibility
                shall be established and maintained.

            c.  All fluids entering the propulsion system or the
                propulsion GSE shall be verified for purity, particulate
                content and non-volatile residues.

    2.  Operation and disposal
        ----------------------

        1.  ### General

            a.  Any operation of the system or part of it shall be
                described in a procedure.

            b.  Before operation, the contents of the procedure shall be
                verified and approved by the facility operator.

            c.  The operation procedures shall:

                1.  Observe the operational limits of the components,
                    subsystems and systems.

                2.  Conform to the limited life cycle of the system and
                    its components.

            d.  The number of cycles a system has undergone and the
                number of cycles, that cycle limited components have
                undergone during ground operations shall be recorded in
                the system and component documentation.

            e.  At the end of any operation, the propulsion system shall
                be configured by isolating, draining or venting the
                system, to minimize risks.

2.  Minimize the risks of, e.g. explosion, toxicity and corrosion.

    1.  ### Operations on ground

        a.  The operation procedures shall identify any risk for
            personnel, installations and system.

        b.  The transportation and handling procedures for the system or
            subsystem shall conform to the system, subsystem and
            component requirements.

        c.  Special attention shall be given to safety and contamination
            issues for every operation where:

            1.  Fluids are put in motion, either via their introduction
                into the propulsion system, or via expulsion from the
                propulsion system.

            2.  Barriers are removed.

3.  For example: cap removal, latch valve actuation and pipe
    > disconnection.

    a.  Tests at component and system level to be performed during AIT
        operations shall be included in the component and system
        requirements.

    b.  The operational procedures shall comply with all specific
        requirements of the sites where the operations are performed.

    <!-- -->

    1.  ### Tank operation

        a.  Pressure gradients during pressurization and
            depressurization operations shall be limited not to exceed
            the allowed temperatures.

        b.  During tank operation the limiting Δp for diaphragm tanks
            shall not be exceeded.

    2.  ### Disposal

        a.  Disposal of contaminated, toxic and dangerous materials or
            fluids or equipment shall be performed according to the
            applicable local regulations and facility rules.

        b.  After operation of a propulsion system, special procedures
            shall be established in case manned interventions are
            planned.

4.  After the operation of a propulsion system, a number of safety
    > barriers no longer exist.

    1.  Supporting documents
        --------------------

        a.  For supporting documents, ECSS-E-ST-35 clause 4.11 shall be
            applied.

        b.  The following specific analyses and documents, shall be
            delivered as a minimum:

            1.  Performance analysis (in conformance with ECSS-E-ST-35)

            2.  Transient analysis (in conformance with ECSS-E-ST-35)

            3.  Sloshing analysis (in conformance with ECSS-E-ST-35)

            4.  Thermal analysis (in conformance with ECSS-E-ST-31 and
                ECSS-E-ST-35)

            5.  Plume analysis (in conformance with ECSS-E-ST-35)

            6.  Gauging analysis (in conformance with ECSS-E-ST-35)

            7.  Mathematical modelling (in conformance with
                ECSS-E-ST-35)

<!-- -->

1.  1 These documents also include the available test results.

2.  2 ECSS-E-ST-35 clause 4.11 provides a table with cross-reference
    > between terms used in this volume to identify project documents
    > and the Document Requirements Definition, which specifies the
    > contents of these documents.

<!-- -->

1.  \
    Electric propulsion systems for spacecraft
    ==========================================

    1.  Overview
        --------

Electric propulsion is based on the acceleration of a propellant by
electric heating or electric and magnetic body forces.

Depending on the working principle of the thruster, electric propulsion
is subdivided in the following three main categories:

-   Electro-thermal thrusters (e.g. resistojets, arcjets, PACTs).

-   Electrostatic thrusters (e.g. ion thrusters with a grid, Hall-effect
    thrusters, FEEP thrusters).

-   Electromagnetic thrusters (e.g. MPD and PPT).

Electric propulsion thrusters are characterized by high specific
impulses, low thrusts and long operation times.

Electric propulsion is also characterized by strong interactions with
other spacecraft subsystems, such as power-supply subsystems and thermal
control subsystems.

The EP system can be separated into three subsystems;

-   A propellant storage and supply subsystem, where spacecraft liquid
    propulsion rules are applicable (see clause 4 of this Standard),
    unless otherwise stated,

-   A power supply control and processing subsystem, not under the scope
    of this ECSS Standard, and where ECSS-E-ST-20 is applicable, unless
    otherwise stated,

-   A thruster subsystem.

Depending on the type of EP system and the hosting spacecraft, a
specific component can belong to one or another of the previously
defined subsystems, according to the design, procurement or for
contractual reasons.

1.  Functional
    ----------

    1.  ### Mission

        a.  The propulsion system shall conform to the spacecraft
            mission requirements including:

            1.  Ground operation (including functional control, testing,
                propellant, simulant loading and spacecraft
                transportation).

            2.  Pre-launch and launch activities (including integration,
                storage, ageing and transport).

            3.  In-orbit operation (including orbit transfer, orbit
                maintenance and attitude control) and the complete
                in-orbit life.

    2.  ### Function

        a.  The propulsion system shall provide the total impulse
            required to fulfil the mission objectives.

        b.  The propulsion system shall provide the thrust and torques
            defined by the AOCS.

        c.  The propulsion system shall be able to operate in a number
            of modes defined by the AOCS.

<!-- -->

1.  Example the modes: off, standby, steady state thrust, pulsed thrust.

    a.  The specific propulsion system operational modes shall also be
        defined.

    b.  The propulsion system shall provide the means to align, adjust
        or both the thrust vector, as defined by the AOCS.

    c.  The propulsion system shall provide the means for propellant
        gauging during the mission.

    <!-- -->

    1.  ### Performance

        a.  The following general performance requirements shall be
            defined:

            1.  Specific impulse

            2.  Propellant mass flow rate

            3.  Electrical power consumption

            4.  Thrust vector alignment and control

            5.  Beam divergence.

        b.  The following thrust performance requirements shall be
            defined:

            1.  Thrust level and range

            2.  Thrust modulation

            3.  Thrust resolution and accuracy

            4.  Thrust noise.

        c.  Thruster response times shall be defined with respect to:

            1.  Start-up (time to achieve nominal thrust)

            2.  Changes in thrust level during normal operation

            3.  Shut-down (time to transit from nominal to zero thrust).

        d.  Repeatability of performance (between different flight units
            and between consecutive firings of a single unit) shall be
            determined in terms of:

            1.  Bias

            2.  Linearity

            3.  Hysteresis

            4.  Scale factor.

        e.  The following lifetime and reliability requirements shall be
            defined:

            1.  Total impulse

            2.  Cycle life

            3.  Mission life

            4.  Reliability level.

        f.  All external loads applicable to the propulsion system shall
            be specified, including:

            1.  Mechanical loads

2.  For example: quasi-static loads; vibrations, transportation.

    1.  Thermal loads

    2.  Electrical loads.

    <!-- -->

    1.  Constraints
        -----------

        1.  ### General

            a.  The constraints induced by thruster initialisation,
                start up and restart sequences shall be identified and
                reported in the DJF.

        2.  ### Thermal fluxes

            a.  Maximum values of thermal fluxes of the thruster
                subsystem shall be defined.

            b.  Since the heat dissipated by the power supply subsystem
                can be significant even with a good efficiency, if
                overheating of the system is shown by the thermal
                analysis, a specific layout of the spacecraft or
                specific devices for the cooling of the subsystem shall
                be provided.

            c.  Thruster surroundings shall conform to the radiative and
                conductive heat fluxes rejected by the thrusters.

            d.  Reporting shall be in conformance the Thermal analysis
                DRD in ECSS-E-ST-31 and the Addendum: Specific
                propulsion aspects for thermal analysis DRD in with
                ECSS-E-ST-35.

        3.  ### Thruster plume effects

            a.  The plume effects analysis on the spacecraft shall be
                performed and reported in conformance with clause 4.3.5
                and 4.6.2.2.6.

            b.  The plume analysis shall include the effects of primary
                ions and charge exchange ions around the thrusters.

        4.  ### High frequency current loops

            a.  The spacecraft electrical architecture shall be
                compliant to induced high frequency current loops.

3.  Due to the plasma nature of some plumes, a high frequency current
    > loop can be induced during thruster firing including the thruster,
    > plasma, the solar array (e.g. the spacecraft mechanical structure
    > and the thruster power supply subsystem).

    1.  ### Electromagnetic compatibility

        a.  The electromagnetic compatibility of the EP system with the
            spacecraft shall be ensured.

4.  For example: payload, telemetry, TM and TC and pyrotechnic devices.

    1.  ### Spacecraft charging

        a.  In case of thrusters generating an electrically charged beam
            (i.e. electrostatic thrusters), the thruster shall have a
            device, the neutralizer, which prevent inducing a charge on
            the subsystem and therefore the spacecraft.

        b.  For spacecraft charging and beam neutralisation related
            effects, ECSS-E-ST-20-06 shall be applied.

    <!-- -->

    1.  Interfaces
        ----------

        1.  ### Interface with the spacecraft

            a.  The EP system shall conform to its specified spacecraft
                interfaces, including:

                1.  Structure

5.  For example: inserts, tank support structure and vibration levels.

    1.  Thermal

6.  For example: conduction, radiation levels, tank, thruster and line
    > thermal control.

    1.  Power

7.  For example: valve drivers, pressure transducers, thermistors,
    > heaters and thermocouples.

    1.  Grounding

    2.  Electromagnetic compatibility

    3.  Pyrotechnics

8.  For example: pyrotechnic valves.

    1.  Mechanisms

9.  For example: valves, regulators, actuators and actuation system.

    1.  AOCS, OBDH and TM/TC.

10. For example: commanding, handling of data for status and health
    > monitoring and failure detection.

    a.  Interfaces shall be defined:

        1.  For ground tests and loading activities with the GSE.

        2.  For safety and prelaunch operation with the launcher
            authorities.

    <!-- -->

    1.  ### Interface with the power bus

        a.  The following parameters shall be available to the
            propulsion subsystem designer:

            1.  Bus voltage and its accuracy.

            2.  Maximum available power.

            3.  Bus impedance in relation to the frequency to access the
                capacity of the bus to sustain surge currents.

            4.  EMI level from the bus to assess the susceptibility of
                the power supply and control unit.

    <!-- -->

    1.  Design
        ------

        1.  ### General

            1.  #### Architecture 

                a.  The EP system architecture shall apply the
                    requirements of ECSS-ST-Q-30.

                b.  The propulsion system architecture shall conform to
                    fail safe, redundancy, reliability and safety
                    requirements.

            2.  #### Replacement of parts

                a.  For replacement of parts during development, testing
                    and mission life pre-launch activities ECSS-E-ST-35
                    clauses 4.5.1c, d and e. shall be applied.

            3.  #### Water-hammer effect

                a.  []{#_Ref214683750 .anchor}A water-hammer effects
                    analysis shall be performed to support the
                    propulsion system design and ensure proper
                    functioning.

                b.  The analysis specified in 1.1.1.1.1mmmmmmmmm shall
                    be reported in conformance with the Propulsion
                    transients analysis report DRD inECSS-E-ST-35.

            4.  #### Piping

                a.  A pipework design analysis shall be performed
                    including non-consumables, leakage, pressure,
                    eigenfrequencies and potential cross-coupling,
                    water-hammer, bending by mechanisms effects.

                b.  The consequences in terms of operational
                    restrictions shall be identified.

            5.  #### Closed volumes

                a.  For closed volumes the requirements of clause
                    4.5.1.5 shall be applied.

            6.  #### Pressure vessels and pressurized components

                a.  For the design of pressure vessels and pressurized
                    components, the requirements of clause 4.5.1.6 shall
                    be applied.

            7.  #### Multi-tanks

                a.  If a multi-tank layout is used, the requirements of
                    clause 4.5.1.7 shall be applied.

            8.  #### Mass imbalance

                a.  For mass imbalance the requirements of clause 4.5.17
                    shall be applied.

            9.  #### Cycles

                a.  The system shall meet the requirements on the number
                    of cycles and cycle life for the whole mission at
                    component, propulsion and spacecraft system level,
                    for both on ground and in-service operation.

            10. #### Electromagnetic compatibility

                a.  Electric propulsion systems shall be
                    electromagnetically compatible with the other parts
                    of the spacecraft.

            11. #### High voltages

                a.  Where high-voltages are involved, the EP system
                    shall be designed to avoid risks of electrical
                    shorts and breakdowns.

                b.  The HV power outputs to the thruster shall be
                    defined in terms of voltage and power needs.

                c.  The grounding concept for the HV elements shall be
                    defined including the paths for routing this HV
                    power.

11. The safety requirements (i.e. ECSS-Q-ST-40) apply when designing the
    > HV elements.

    1.  ### Selection

        1.  #### Reporting

            a.  The reporting shall be done in the DJF in conformance
                with ECSS-E-ST-10.

        2.  #### Propulsion system selection

            a.  The propulsion system and operating modes selection
                shall be supported by detailed mission and trade-off
                analyses.

            b.  The choice of the EP system shall be made using the
                available electrical power for the EP system during the
                whole duration of the mission.

            c.  Compatibility of the selected materials, propellants and
                test fluids shall be demonstrated for all components.

        3.  #### Propellant selection

            1.  ##### General

                a.  The criteria to be used for propellant selection
                    shall include:

                    1.  Mission requirements

                    2.  Compatibility and contamination

                    3.  Performance.

                b.  The propellant shall be defined and specified
                    including;

                    1.  Chemical composition

                    2.  Purity

                    3.  Cleanliness.

            2.  ##### Propellant for thruster qualification

                a.  Thruster qualification firing tests shall use the
                    same propellant grade as the one selected for
                    flight.

    2.  ### Sizing

        1.  #### General

            a.  The sizing of components for an EP system shall include
                the evolution of the operational conditions.

            b.  Propellant, pressurant and contaminants budgets are
                major inputs for the sizing process and shall be
                available.

12. For example: impact on lifetime, variation of performance during
    > lifetime, quantities for disposal and unusable residuals.

    a.  The electrical power available to the propulsion system
        throughout the mission is also a major input for the sizing and
        shall be determined.

    <!-- -->

    1.  #### Sizing process

        a.  The sizing process shall begin with a definition of the life
            phases of each element, including at least:

            1.  Thrust level and range

            2.  Total impulse

            3.  Available power

            4.  Mass budget

            5.  Operating cycles

            6.  Propellant, pressurant and leakage budgets

            7.  Capacity of protections for sensitive components

13. For example: oxygen absorbers for hollow cathodes.

    1.  Accommodation envelop.

    <!-- -->

    a.  The sizing process shall account for margins based on:

        1.  Safety

        2.  Reliability requirements established by the customer

        3.  Industry and launch authorities or agencies operational
            constraints

        4.  Thruster performance efficiency

        5.  Plume effects

        6.  Modelling errors and uncertainties.

    b.  Pressurant, propellant and contaminants budgets shall include:

        1.  Their impact on lifetime

        2.  Variation of performance during lifetime

        3.  Quantity for deorbiting

        4.  Residuals.

    <!-- -->

    1.  ### Design development

        1.  #### General

            a.  The development shall allow for an incremental
                verification at component, subsystem and propulsion
                system level, if a fully representative functional test
                cannot be performed after the integration of the system
                on the spacecraft.

            b.  If the flight version of the system is divided into
                independent blocks, they should be separated by safety
                barriers.

        2.  #### Development tests

            a.  Development tests shall be performed by incremental test
                at component, subsystem and system level.

14. Development tests at spacecraft level can be performed with
    > electrical simulators for thrusters.

    a.  The design and procedures shall be defined such that the
        testability at integrated spacecraft level and the capability to
        return after test to safe and clean conditions is guaranteed for
        each system and subsystem.

    <!-- -->

    1.  ### Contamination

        1.  #### External contamination

            a.  The thruster design, layout and orientation should
                prevent contaminant deposition on elements sensitive to
                contamination identified in clause 1.1.1.1.1i.

15. Contaminants deposition on sensitive elements, such as solar panels,
    > star trackers, and optics, depends on the propellants used, the
    > thruster characteristics, the layout of the propulsion system, the
    > thruster orientation and the thruster duty cycle.

    a.  The potential hazard of contamination and the expected level of
        contamination due to thruster exhaust, shall be included in the
        plume analysis.

    b.  The potential hazard due to external contamination to the
        thruster shall be analysed.

16. Example of contamination to the thruster: by chemical propulsion or
    > debris.

    1.  #### Internal contamination

        a.  The propulsion system shall be designed to avoid the effects
            of internal contaminants by:

            1.  Preventing intrusion, internal generation and
                circulation of contaminants.

            2.  Preventing or controlling accumulation of contaminants
                throughout the various parts of the system.

            3.  Preventing accumulation of contaminants during the
                various steps of production, verification and operation
                of the system.

17. Electric thrusters or some of their components (e.g. neutralizers
    > and ionization chambers) are sensitive to chemical contamination
    > that, causing a change of the surface properties, can poison
    > temporarily or indefinitely the components and affect their
    > performance and operating life.

    a.  The propulsion system shall conform to the specified maximum
        level of contaminants.

18. For engineering requirements on materials, see ECSS-E-ST-32-08.

    1.  ### Propellant protection

        a.  Unwanted oxidation of propellants shall be prevented.

        b.  For propellants subject to oxidation under ambient
            conditions, exposure to air shall be prevented.

19. Example of such propellant is Caesium.

    1.  ### Components guidelines

        a.  A design assessment for failure tolerance shall be performed
            for every component.

20. See ECSS-ST-Q-30-02.

    1.  ### Propellant management assembly

        1.  #### General

            a.  The propellant management assembly design shall allow
                for on-ground draining.

21. Clause 5.5.8 addresses specific requirements on the propellant
    > management assembly and components used in EP systems.

    a.  The location of fill-and-drain valves and piping layout shall
        prevent:

        1.  Trapping of propellants or simulants fluids in the system by
            on-ground draining.

        2.  Contact between dissimilar fluids.

    b.  For fluids with a high triple-point, it shall be ensured, either

-   that the fluid is maintained in a gaseous state, or

-   active thermal control of the propellant management assembly is
    implemented.

    1.  #### Flow control unit

        a.  In case the mass flow rate is not-self-adjusted, the design
            shall address the specific issues related to the very small,
            well regulated mass flow rates used in electric propulsion.

1.  Example of self-adjusted mass flow rate is by capillary-fed
    > thrusters.

    1.  #### Pressure regulators

        a.  The design of a pressure regulator shall be compatible with
            the propellant throughput and cycle life as required for the
            mission.

2.  Pressure regulators for electric propulsion, have to deliver very
    > small flow rates for extended period of time compared to liquid
    > propulsion.

    1.  #### Oxygen absorbers

        a.  The use of oxygen absorbers shall be assessed.

        b.  Oxygen absorbers shall be located as close as possible to
            components that can be contaminated.

3.  Residual oxygen can be present in the propellant, due to its
    > adherence to the propellant management assembly pipelines or
    > because of the impurity of the propellant itself. Components of EP
    > systems such as cathodes and neutralizers can be oxygen
    > contamination sensitive.

    1.  #### Propellant filters

        a.  For gas and liquid filters design, clause 4.5.9 shall be
            applied.

    <!-- -->

    1.  ### Pressure vessels

        a.  For pressure vessels design, clause 4.5.10 shall be applied.

    2.  ### Propellant tanks

        a.  Propellant tanks shall provide the thrusters with
            propellants according to their specified conditions.

        b.  For propellant tanks design of EP systems using gaseous
            propellants, clause 4.5.10 shall be applied.

4.  Example of gaseous propellant: xenon.

    a.  For propellant tanks design of EP systems using liquid
        propellants, clause 4.5.11 shall be applied.

<!-- -->

1.  1 A large variety of propellants are used for electric propulsion
    > thrusters (i.e. gaseous, liquid and solid); therefore different
    > tank design rules are applicable.

2.  2 Some gaseous propellants, such as xenon, are usually stored in
    > supercritical condition.

3.  3 The fluid characteristics of supercritical Xenon (e.g. density)
    > can be substantially different from those of a simulant pressurant
    > gas during environmental testing (e.g. vibration testing). Thus,
    > analysing this point during system design can prevent coupling
    > modes between the spacecraft structure, xenon tank and the xenon
    > itself as a free-moving high density fluid. With this objective,
    > selection of the xenon tank and tank shape is done in conformance
    > to the spacecraft eigenfrequencies.

    1.  ### Blow-down ratio

        a.  For EP systems working in blow-down mode clause 4.5.12 shall
            be applied.

    2.  ### Thrusters

        1.  #### Thrust level

            a.  The thruster shall provide the required performance over
                the full thrust range.

            b.  The thruster shall provide the requested thrust
                stability (i.e. drift and fluctuations) and
                repeatability.

        2.  #### Thrust noise

            a.  The thrust random variation around its mean value, or
                thrust noise, shall be maintained within the specified
                range.

<!-- -->

1.  Thrust noise is usually composed of contributions from the thruster,
    > the propellant feed system and the power electronics.

    1.  #### Thrust accuracy

        a.  Thrust shall remain within the ranges derived from the AOCS
            analysis.

        b.  Transfer functions, when needed, shall account for the
            following parameters:

            1.  Bias

            2.  Dcale factor

            3.  Hysteresis

            4.  Response time of the system.

    2.  #### Thrust modulation

        a.  The thruster shall be capable of high- and low- frequency
            modes modulation if required by AOCS.

    3.  #### Thrust mismatch

        a.  The difference in thrust between two thrusters operating in
            pair on the same branch shall not exceed the specified
            value.

    4.  #### Thrust-vector alignment

        a.  Thrust-vector alignment shall be obtained by correction
            methods over geometrical and operational factors as
            specified in 1.1.1.1.1ttttttttttt and 1.1.1.1.1uuuuuuuuuuu.

        b.  []{#_Ref197848144 .anchor}The thrust misalignment due to
            geometrical factors shall be corrected by

            1.  []{#_Ref207610076 .anchor}Introducing structural devices
                into the thruster support to adjust the thrust
                alignment.

            2.  []{#_Ref207610079 .anchor}Fine adjustment of the
                components inside the thruster with influence on the
                thrust-vector.

            3.  A combination of 1.1.1.1.1ttttttttttt.1 and
                1.1.1.1.1ttttttttttt.2.

2.  Geometrical factors are the mounting of the thrust-vector-sensitive
    > components (i.e. grids) and the mechanical interface between the
    > thruster and the spacecraft. This type of misalignment can be
    > corrected either by fine adjustment of the thrust-vector-sensitive
    > components inside the thruster, or by introducing structural
    > devices into the thruster support to adjust the thrust alignment.

    a.  []{#_Ref197848147 .anchor}The effect of operational factors
        shall be compensated by the introduction at system level of
        thrust-vector control systems.

3.  Operational factors are mainly due to electro-thermal distortions or
    > the erosion of thrust-vector-sensitive components during
    > operations.

    1.  #### Electrical parameters

        a.  []{#_Ref197848272 .anchor}The thruster design shall be
            derived from a trade-off considering the impact on the
            spacecraft electrical system and the thruster performance in
            every mission phase.

4.  The impact on the spacecraft electrical systems is minimized while
    > maximizing the thruster performance.

    a.  Requirement 1.1.1.1.1vvvvvvvvvvv shall be performed in the
        framework of a design optimization process at EP subsystem
        level.

    <!-- -->

    1.  #### Thermal environment

        a.  The heat fluxes at the interface between the thruster and
            supporting structure shall be specified.

        b.  To avoid overheating of the thruster, its thermal behaviour,
            when integrated on the spacecraft, shall be analysed.

        c.  Reporting shall be in conformance with the Thermal analysis
            DRD in ECSS-E-ST-31 and the Addendum: Specific propulsion
            aspects for thermal analysis DRD in ECSS-E-ST-35.

    2.  #### Operational lifetime

        a.  The design of life limited components of the thruster shall
            be compatible with the operational life of the thruster.

    3.  #### Operational cycles

        a.  The EP system design shall be compliant to the mission cycle
            requirements.

    4.  #### Thrust interruption

        a.  The thruster shall be designed to avoid such thrust
            interruptions.

        b.  The thruster shall be designed such that if interruptions
            are experienced they do not degrade life or performance.

<!-- -->

1.  1 Depending on the technology, thrust interruptions are also called
    > sparcs (FEEP), arcs, beam out or flameout.

2.  2 Many electric propulsion thrusters experience thrust interruption
    > during operation.

    1.  #### Neutraliser

        a.  The neutraliser, if needed, shall be designed to deliver the
            required neutralisation current over the mission lifetime

<!-- -->

1.  The neutraliser is generally considered a thruster component.

    1.  ### Thrust-vector control

        1.  #### Devices for thrust-vector control

            a.  Devices used for thrust-vector control shall be either

                1.  actively controlled pointing mechanisms supporting
                    the thruster, subject of clause 5.5.13.2 ; or

                2.  thrust-vector steering solutions within the thruster
                    itself, subject of clause 5.5.13.3.

2.  Thrust-vector control of electric thrusters is often used

-   for propellant consumption minimization by maintaining the
    > thrust-vector through the CoM of the satellite, which normally
    > changes during the mission; or

-   to change the general orientation of the thruster between different
    > operational configurations.

    1.  #### Thruster orientation mechanism

        a.  For the design of thruster orientation mechanisms for
            electric propulsion, clause 4.5.15 shall be applied.

    2.  #### Internal thrust-vector steering devices

        a.  If internal thrust-vector steering solutions are being
            introduced into the design, the impact on life time and
            performance shall be assessed.

    <!-- -->

    1.  ### Power supply, control and processing subsystem

        1.  #### General

            a.  For power supply, control and processing equipment,
                ECSS-E-ST-20 shall be applied.

1.  1 The purpose of the power supply, control and processing devices in
    > an EP system is to provide the thruster and other
    > electrically-powered components with the adequate electrical input
    > parameters during transient and at steady-state operations.

2.  2 Depending on the type of EP system, the power supply, control and
    > processing functions can be performed by dedicated equipment or
    > carried out as part of the tasks of the spacecraft power system.

3.  3 Most commonly, the power conditioning devices of an EP system
    > include also functions to control and process incoming and
    > outgoing data and commands.

4.  4 For redundancy, operational purposes and mass optimization,
    > thruster switching devices can be introduced in the EP system to
    > provide cross-strapping of electrical power between the power
    > supplies and several thrusters.

    1.  #### Compatibility with thruster

        a.  The compatibility assessment between the power supply
            outputs and the thruster shall be performed.

        b.  A design analysis shall be performed to identify if a filter
            unit is required to meet the EMC requirements.

        c.  If a filter unit is required, its design and location shall
            be defined.

    <!-- -->

    1.  ### Electrical design

        1.  #### General

            a.  The electrical design shall conform to ECSS-E-ST-20.

        2.  #### Electromagnetic compatibility (EMC)

            a.  For electromagnetic compatibility, design of the
                thruster, harnesses and power unit should conform to
                ECSS-E-ST-20 and ECSS-E-ST-20-07.

            b.  The design of the following shall conform to
                ECSS-E-ST-20 and ECSS-E-ST-20-07.

                1.  Interference

                2.  susceptibility

                3.  grounding

                4.  Shielding

                5.  Isolation.

        3.  #### Electric reference potential, grounding, insulation

            a.  The grounding scheme and insulation shall limit
                interferences with other spacecraft systems to within
                the specified levels.

<!-- -->

1.  For an operating thruster, the electrical reference potential
    > strongly depends on the interactions between the thruster
    > generated plasma and the satellite mechanical structure through
    > the external environment. As a consequence, the reference
    > potential can differ from the potential of the common structure
    > (i.e. ground).

    a.  Reporting shall be available in DJF and DJD.

2.  For DJF and DJD see ECSS-E-ST-10.

    1.  #### Electrostatic discharge protection

        a.  The EP system shall be protected from electrostatic
            discharges caused by:

            1.  Charge accumulation on inactive thruster electrodes
                exposed to space or plasma from another operating
                engine.

            2.  Transients spikes.

3.  For example: during thruster start-up, and shut-down.

    1.  #### Parasitic discharge prevention

        a.  The design of the EP system should prevent parasitic
            discharges between parts of the thruster at different
            potentials.

<!-- -->

1.  1 Parasitic discharges in electrostatic engines can possibly not be
    > avoided completely.

2.  2 During operation, the thruster is partially immersed in ambient
    > plasma and its own generated plasma.

    a.  The design of the EP system shall prevent the presence of gases
        during the operation of the thruster.

<!-- -->

1.  Parasitic discharge can be enhanced by the presence of gas. Gas can
    > appear due to venting, trapped gas or outgassing.

    1.  ### Pyrotechnic devices

For pyrotechnic devices ECSS-E-ST-33-11 applies.

1.  ### Monitoring and failure detection

    a.  The requirements of clause 4.5.18 shall be applied.

    b.  EP systems shall include the monitoring of the electrical
        parameters.

    c.  Monitoring of the plasma parameters should be done by plasma
        diagnostics packages.

<!-- -->

1.  Langmuir probes and retarding potential analysers are typical
    > devices that can be used to monitor plasma parameters.

    1.  ### Ground support equipment (GSE)

        1.  #### General

            a.  The design of the propulsion GSE shall respect the
                safety requirements of the facility where it is
                operated.

        2.  #### Fluid

            a.  For the design of GSE handling fluids, the requirements
                of clause 4.5.19.2 shall be applied.

            b.  The loading of propellant in supercritical condition
                shall be performed by means of dedicated equipment and
                following procedures preventing the presence of liquid
                propellant in any part of the propellant feed subsystem.

2.  Example of this kind of propellant: xenon.

    1.  #### Electrical

        a.  The design of the GSE shall allow the safe check-out of all
            electrical components of the EP system.

        b.  The procedures to operate and the design of the equipment
            shall prevent the inadvertent activation of the spacecraft
            components.

        c.  As thrusters cannot normally be operated under atmospheric
            conditions, an electrical thruster simulator shall be
            available in order to allow tests to be performed on the EP
            system.

        d.  The GSE shall be designed to prevent inadvertent electrical
            discharge.

        e.  In case the GSE is used in the vicinity of inflammable or
            explosive materials, it shall be explosion proof.

    <!-- -->

    1.  Verification
        ------------

        1.  ### General

            a.  A verification matrix shall be established indicating
                the type of verification method to be applied for the
                individual requirements.

<!-- -->

1.  1 For verification of electric propulsion systems, see
    > ECSS-E-ST-10-02.

2.  2 Verification is performed to demonstrate that the system or
    > subsystem fully conforms to the requirements. This can be achieved
    > by adequately documented analysis, tests, review of the design,
    > inspection, or by a combination of them.

3.  3 In the following clauses of this clause 5.6 it is considered that:

-   verification by review of the design is included in verification by
    > analysis, and

-   verification by inspection is included in verification by test.

    1.  ### Verification by analysis

        1.  #### General

            a.  For EP system, the following shall be applied:

                1.  Clause 4.6.2.

                2.  The additional clauses of this clause 5.6.2.

1.  Methodology principles for the verification by analysis of an EP
    > system are similar to the ones for liquid propulsion systems
    > presented in the clause 4.6.2. However, new elements are being
    > introduced by additional physical phenomena and the modelling of
    > additional components, such as:

-   electric thrusters often generate electrically charged particles;

-   the generated plume is quite rarefied, but with high kinetic energy;

-   the thrusters use electrostatic, magnetic and electromagnetic fields
    > or utilize electric arcs or heaters for their operations;

-   In addition, electric thruster operations are normally of much
    > longer;

-   duration than liquid thruster operations and this can also have an
    > impact on the analysis to perform.

    1.  #### System analyses 

        a.  The following analyses shall be made:

            1.  Power, propellant, mass and TM/TC budgets.

            2.  Mechanical and thermal.

            3.  Performance.

            4.  EMC.

            5.  Spacecraft interactions.

1.  For example: plume effects, potential control, communication
    > interferences.

    1.  EP system venting.

    2.  Life time.

    <!-- -->

    1.  #### Mutual effects of electrostatic and magnetic fields

        a.  In case multiple electric thrusters are used simultaneously,
            the mutual effects of the electrostatic and magnetic fields
            on thrusters and EP system performance shall be assessed.

    2.  #### Lifetime

        a.  Analytical tools capable of predicting the evolution in time
            of the operational parameters of the system and the
            degradation of life-critical components shall be developed
            to support the qualification processes of EP systems.

        b.  These tools shall be verified by means of a thruster life
            test.

    3.  #### Time-related phenomena

        a.  []{#_Ref207686704 .anchor}At least the following specific
            phenomena during transient phases shall be evaluated when
            analysing the EP system:

            1.  Gas pressure oscillations

            2.  Inrush power consumption

            3.  Electrostatic and electromagnetic perturbations.

2.  Transient phases are for example: start-up and shut-down.

    a.  []{#_Ref207686708 .anchor}The time response of an EP system
        shall be analysed.

3.  This is of particular interest in some cases, such as applications
    > where the thrusters are operated as actuators in closed-loop
    > systems for fine pointing and control requirements or for
    > autonomous operations.

    a.  The analyses specified in 1.1.1.1.1lllllllllllll and
        1.1.1.1.1mmmmmmmmmmmmm shall be reported in conformance with the
        Propulsion transients analysis report DRD in ECSS-E-ST-35.

    <!-- -->

    1.  ### Verification by test

        1.  #### General

            a.  In case the implications of the functioning of an
                electrical propulsion system on the spacecraft system
                level cannot be fully verified by analysis, specific
                tests shall be performed.

4.  These tests can be performed:

-   at component level where sufficient information can be obtained to
    > assess the effects on system or subsystem level; or

-   at system or subsystem level; or

-   at spacecraft level.

    a.  The verification tests of each block shall be defined to
        represent the conditions that are expected to be encountered
        during the operation of the complete system.

    b.  Test methods related to acceptance, environmental tests, EMC
        tests, plume tests, and life tests shall be defined.

1.  Particularly those described in the following clauses.

    1.  #### Operating test

        a.  The following aspects shall be defined with reference to
            their impact on performance:

            1.  Vacuum pressure level

            2.  Type and capacity of pumping

            3.  Minimum distance of the thruster to the vacuum chamber
                walls

            4.  Measurement and calibration of diagnostics

            5.  Effect of backsputter products.

2.  This is because most of the electric thrusters can only be operated
    > in vacuum.

    1.  #### Electromagnetic compatibility (EMC) test

        a.  EMC tests shall be performed at propulsion system level
            using flight representative power supplies and conditioning
            systems, harnesses and thruster.

        b.  Bias from ground-type interference shall be assessed for a
            precise analysis of the results of such tests.

3.  For these tests ECSS-E-ST-20-07 applies.

    1.  #### Plume characterization tests

        a.  Plume characterization tests shall cover at least the
            following aspects;

            1.  Main beam characterisation

4.  For example: divergence, energy distribution, plasma density.

    1.  Thrust vector alignment

    2.  Erosion products characterisation

    3.  Back flow CEX characterisation.

5.  For example: density, energy distribution.

    a.  The tests shall be defined in terms of:

        1.  Vacuum pressure level

        2.  The distance from the thruster exit to the probes

        3.  The distance from the thruster exit to the vacuum chamber
            walls.

    <!-- -->

    1.  #### Life tests

        a.  A life test shall be performed on one complete functional
            chain at least (i.e. thruster, flow control system and the
            power supply system, filters).

        b.  Life tests shall be conducted according to the mission duty
            cycles, with a reduction of the off-cycle duration in
            agreement with a good representation of the thermal
            transients.

        c.  For facility back-sputtering, it shall be demonstrated that
            the design of the test facility limits the quantity of
            sputtered material, and that back-sputtering is measured.

        d.  Life tests shall use flight-grade propellant.

        e.  The purity of the propellant shall be monitored.

        f.  The health status of the propulsion system shall be
            monitored during the life test, on a regular basis, by
            performance tests in conformance with 5.6.3.6.

    2.  #### Performance tests

        a.  Performance tests, including direct thrust measurement,
            shall verify that the performances of the system, including
            the thruster, flow control unit and the power supply and
            conditioning, conform to the requirements.

6.  Performance tests can be included in the life tests.

    1.  #### Calibration

        a.  []{#_Ref214684432 .anchor}All components or subsystems which
            provide data shall be calibrated.

        b.  Conformity to the requirements of the components or
            subsystems, specified in 1.1.1.1.1dddddddddddddd, shall be
            demonstrated.

    <!-- -->

    1.  ### Data exchange for models

        a.  Tests results, as well as all models, shall be established
            and structured with a commonly agreed structure and format.

7.  Example of these models are: thermal, mechanical, electric,
    > magnetic, performance models.

    1.  Quality factors
        ---------------

        1.  ### Reliability

            a.  For reliability, clause 4.7.1 shall be applied.

        2.  ### Production and manufacturing

            a.  For production and manufacturing, clause 4.7.2 shall be
                applied.

    2.  Operation and disposal
        ----------------------

        a.  For operation and disposal, clause 4.8 shall be applied.

    3.  Supporting documents
        --------------------

        a.  For deliverables, clause 4.9 shall be applied.

        b.  Additionally, an EMC analysis shall be delivered.

 Bibliography

  ---------------------- -----------------------------------------------------------------------------------------
  ECSS-S-ST-00           ECSS system – Description, implementation and general requirements
  ECSS-E-ST-10-02        Space engineering – Verification
  ECSS-E-ST-10-03        Space engineering – Testing
  ECSS-E-ST-32-02        Space engineering – Structural design and verification of pressurized hardware
  ECSS-E-ST-32-08        Space engineering – Materials
                         
  ECSS-E-ST-33-11        Space engineering – Explosive systems and devices
  ECSS-E-ST-70           Space engineering – Ground systems and operations
  ECSS-Q-ST-30-02        Space product assurance – Failure modes, effect (and criticality) analysis (FMEA/FMECA)
  ECSS-Q-ST-40           Space product assurance – Safety
  ECSS-Q-ST-70-36        Space product assurance – Material selection for controlling stress-corrosion cracking
  NASA-MSFC-SPEC-522B    Design criteria for controlling stress corrosion cracking
  ISO/CD 14623-1         Space systems - Pressure vessel structural design - Part 1: Metallic pressure vessels
  ISO/AWI 14623-2        Space systems - Pressure vessel structural design - Part 2: Composite pressure vessels
  ANSI/AIAA S-080-1998   Metallic Pressure Vessels, Pressurized Structures, and Pressure Components
  ANSI/AIAA S-081-1999   Composite Overwrapped Pressure Vessels (COPVs)
  ---------------------- -----------------------------------------------------------------------------------------
