-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Terms specific to the present
            standard](#terms-specific-to-the-present-standard)
        -   [Symbols](#symbols)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-32-02C_Rev.1(15November2008).docx1//media/image1.jpeg){width="4.697916666666667in"
height="2.8333333333333335in"}

Space engineering

Structural design and verification of pressurized hardware

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

This Standard has been prepared by the ECSS-E-ST-32-02 Working Group,
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

  ------------------------- -------------------------------------------------------------------------------------------------------------------
  ECSS-E-ST-32-02A          Never issued

  ECSS-E-ST-32-02B          Never issued

  ECSS-E-ST-32-02C          First issue
                            
  31 July 2008              

  ECSS-E-ST-32-02C Rev. 1   First issue revision 1.
                            
  15 November 2008          Changes with respect to version C (31 July 2008) are identified with revision tracking.
                            
                            Main changes are:
                            
                            -   The definitions of MEOP and MDP have been removed and references to the ECSS-E-ST-32 Standard have been done.
                            
  ------------------------- -------------------------------------------------------------------------------------------------------------------

 Table of contents {#table-of-contents .Contents}

[Change log 3](#change-log)

[1 Scope 7](#scope)

[2 Normative references 8](#normative-references)

[3 Terms, definitions, and abbreviated terms
9](#terms-definitions-and-abbreviated-terms)

[3.1 Terms from other standards 9](#terms-from-other-standards)

[3.2 Terms specific to the present standard
9](#terms-specific-to-the-present-standard)

[3.3 Abbreviated terms 15](#abbreviated-terms)

[3.4 Symbols 16](#symbols)

[4 General requirements 17](#general-requirements)

[4.1 Overview 17](#overview)

[4.1.1 Content 17](#content)

[4.1.2 Categories of pressurized hardware
17](#categories-of-pressurized-hardware)

[4.2 General 18](#general)

[4.2.1 Leak tightness 18](#leak-tightness)

[4.2.2 Classification of fracture critical parts
18](#classification-of-fracture-critical-parts)

[4.2.3 Operation and maintenance 19](#operation-and-maintenance)

[4.2.4 Service life extension, reactivation and re-acceptance
21](#service-life-extension-reactivation-and-re-acceptance)

[4.3 Pressure vessels 22](#pressure-vessels)

[4.3.1 Factors of safety 22](#factors-of-safety)

[4.3.2 Metallic pressure vessels 23](#metallic-pressure-vessels)

[4.3.3 COPV with metallic liner 26](#copv-with-metallic-liner)

[4.3.4 COPV with homogeneous non metallic liner and CPV
30](#copv-with-homogeneous-non-metallic-liner-and-cpv)

[4.4 Pressurized structures 34](#pressurized-structures)

[4.4.1 Factors of safety 34](#factors-of-safety-1)

[4.4.2 Metallic pressurized structures
35](#metallic-pressurized-structures)

[4.4.3 COPS with metallic liner 37](#cops-with-metallic-liner)

[4.4.4 COPS with homogeneous non metallic liner and CPS
40](#cops-with-homogeneous-non-metallic-liner-and-cps)

[4.5 Pressure components 44](#pressure-components)

[4.5.1 Metallic pressure components 44](#metallic-pressure-components)

[4.5.2 COPC with metallic liner 46](#copc-with-metallic-liner)

[4.5.3 COPC with homogeneous non metallic liner
49](#copc-with-homogeneous-non-metallic-liner)

[4.6 Special pressurized equipment 52](#special-pressurized-equipment)

[4.6.1 Metallic special pressurized equipment
52](#metallic-special-pressurized-equipment)

[4.6.2 COSPE with metallic liner 59](#cospe-with-metallic-liner)

[4.6.3 COSPE with homogeneous non metallic liner
62](#cospe-with-homogeneous-non-metallic-liner)

[5 Specific requirements 66](#specific-requirements)

[5.1 Overview 66](#overview-1)

[5.2 Structural engineering 66](#structural-engineering)

[5.3 Failure mode demonstration 67](#failure-mode-demonstration)

[5.3.1 General 67](#general-1)

[5.3.2 Demonstration of LBB by analysis
68](#demonstration-of-lbb-by-analysis)

[5.3.3 Demonstration of LBB by test using coupons
69](#demonstration-of-lbb-by-test-using-coupons)

[5.3.4 Demonstration of LBB by test using full-scale article
69](#demonstration-of-lbb-by-test-using-full-scale-article)

[5.3.5 Report of LBB demonstration 70](#report-of-lbb-demonstration)

[5.4 Qualification tests 71](#qualification-tests-12)

[5.4.1 General 71](#general-2)

[5.4.2 Proof pressure test 71](#proof-pressure-test)

[5.4.3 Leak test 72](#leak-test)

[5.4.4 Vibration test 72](#vibration-test)

[5.4.5 Pressure cycling test 72](#pressure-cycling-test)

[5.4.6 Design burst pressure test 72](#design-burst-pressure-test)

[5.4.7 Burst test 72](#burst-test)

[5.5 Acceptance tests 73](#acceptance-tests-12)

[5.5.1 General 73](#general-3)

[5.5.2 Proof pressure test 73](#proof-pressure-test-1)

[5.5.3 Leak test 73](#leak-test-1)

[5.6 Composite over-wrap material characterization
74](#composite-over-wrap-material-characterization)

[5.7 Inspection 74](#inspection)

[5.7.1 General 74](#general-4)

[5.7.2 Inspection techniques for composite over-wraps and composites
75](#inspection-techniques-for-composite-over-wraps-and-composites)

[Bibliography 76](#bibliography)

Figures

[Figure 4‑1: Breakdown of PH types covered by this Standard
17](#__RefHeading___Toc214365290)

[Figure 4‑2: Flowchart describing PH classifications covered by this
Standard 18](#__RefHeading___Toc214365291)

[Figure 4‑3: Development approach of MPV
24](#__RefHeading___Toc214365292)

[Figure 4‑4: Development approach of COPV with metallic liner
29](#__RefHeading___Toc214365293)

[Figure 4‑5: Development approach of COPV with homogeneous non metallic
liner and CPV 33](#__RefHeading___Toc214365294)

[Figure 4‑6: Development approach of MPS
36](#__RefHeading___Toc214365295)

[Figure 4‑7: Development approach of COPS with metallic liner
40](#__RefHeading___Toc214365296)

[Figure 4‑8: Development approach of COPS with homogeneous non metallic
liner and CPS 43](#__RefHeading___Toc214365297)

[Figure 4‑9: Development approach of MPC
46](#__RefHeading___Toc214365298)

[Figure 4‑10: Development approach of sealed containers
55](#__RefHeading___Toc214365299)

[Figure 4‑11: Development approach of cryostats (or Dewars)
56](#__RefHeading___Toc214365300)

[Figure 4‑12: Development approach of heat pipes
57](#__RefHeading___Toc214365301)

[Figure 4‑13: Development approach of hazardous fluid containers
58](#__RefHeading___Toc214365302)

Tables

[Table 4‑1: Factors of safety for PV (unmanned and manned missions)
23](#__RefHeading___Toc214365303)

[Table 4‑2: Factors of safety for PS (unmanned mission)
34](#__RefHeading___Toc214365304)

[Table 4‑3: Factors of safety for PS (manned mission)
34](#__RefHeading___Toc214365305)

[Table 4‑4: Factors of safety for manned modules
34](#__RefHeading___Toc214365306)

[Table 4‑5: Factors of safety for MPC (unmanned and manned missions)
44](#__RefHeading___Toc214365307)

[Table 4‑6: Factors of safety for COPC with metallic liner
(unmanned and manned missions) 47](#__RefHeading___Toc214365308)

[Table 4‑7: Factors of safety for COPC with homogeneous non metallic
liner (unmanned and manned missions) 50](#__RefHeading___Toc214365309)

[Table 4‑8: Factors of safety for MSPE (unmanned and manned missions)
53](#__RefHeading___Toc214365310)

[Table 4‑9: Factors of safety for COSPE with metallic liner
(unmanned and manned missions) 60](#__RefHeading___Toc214365311)

[Table 4‑10: Factors of safety for COSPE with homogeneous non metallic
liner (unmanned and manned missions) 62](#__RefHeading___Toc214365312)

\
Scope
=====

This Standard defines the structural design verification of metallic and
non-metallic pressurized hardware which includes pressure vessels,
pressurized structures, pressure components (such as valves, pumps,
lines, fittings, and hoses), and special pressurized equipment (e.g.
batteries, heat pipes, cryostats, sealed containers, hazardous fluids
container). External supports and structural interfaces of pressurized
hardware are not covered by this standard. Solid propellant motor cases
are not covered by this standard.

Objectives of the associated verification process are primarily to
demonstrate the qualification of design and performance, as meeting all
specified requirements, and to ensure that the flight hardware is free
from workmanship defects and acceptable for flight.

This Standard applies to all space products and in particular to launch
vehicles, transfer vehicles, re-entry vehicles, spacecraft, space
station, landing probes and rovers, sounding rockets, payloads and
instruments.

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

  ----------------- ---------------------------------------------------------------------
  ECSS-S-ST-00-01   ECSS system – Glossary of terms
  ECSS-E-ST-10-02   Space engineering – Verification
  ECSS-E-ST-10-03   Space engineering – Testing
  ECSS-E-ST-32      Space engineering – Structural general requirements
  ECSS-E-ST-32-01   Space engineering – Fracture control
  ECSS-E-ST-32-08   Space engineering – Materials
  ECSS-E-ST-32-10   Space engineering – Reliability based mechanical factors of safety
  ECSS-Q-ST-20      Space product assurance – Quality assurance
  ECSS-Q-ST-70      Space product assurance – Materials, mechanical parts and processes
  ----------------- ---------------------------------------------------------------------

1.  \
    Terms, definitions, and abbreviated terms
    =========================================

    1.  Terms from other standards
        --------------------------

For the purpose of this Standard, the terms and definitions from
ECSS-S-ST-00-01, ECSS-E-ST-32, and ECSS-E-ST-32-01 apply.

Terms specific to the present standard
--------------------------------------

1.  autofrettage

vessel sizing operation where pressure driven deflection is used to
plastically yield the metal liner into the overlying composite in order
to induce initial compressive stress states in the metal liner

1.  Autofrettage is considered to be part of the manufacturing process
    and is conducted prior to acceptance test.

<!-- -->

1.  boss

zone of a pressure vessel or a pressurized structure ensuring functional
interfaces (e.g. fluid connections and mechanical interfaces) of the
hardware with the pressurized system

1.  burst factor (j~burst~)

multiplying factor applied to the maximum design pressure (MDP), to
obtain the design burst pressure

1.  The burst factor corresponds to an ultimate factor of safety.

<!-- -->

1.  burst pressure

pressure level at which collapse, rupture or unstable fracture of the
pressurized hardware occurs

1.  composite over-wrap

layers of fibre-based composite material applied onto a liner,
sustaining significant pressure and environmental loads

1.  composite over-wrapped pressure vessel (COPV)

pressure vessel with a fibre-based composite structure fully or
partially encapsulating a liner

1.  For example:

-   the liner can be metallic or not.

-   the liner ensures the leak tightness of the vessel.

1.  composite over-wrapped pressurized component (COPC)

pressurized component with a fibre-based composite system fully or
partially encapsulating a liner

1.  For example:

-   the liner can be metallic or not.

-   the liner ensures the leak tightness of the vessel.

1.  composite over-wrapped pressurized structure (COPS)

pressurized structure with a fibre-based composite system fully or
partially encapsulating a liner

1.  For example:

-   the liner can be metallic or not.

-   the liner ensures the leak tightness of the vessel.

1.  composite over-wrapped special pressurized equipment (COSPE)

special pressurized equipment with a fibre-based composite system fully
or partially encapsulating a liner

1.  For example:

-   the liner can be metallic or not.

-   the liner ensures the leak tightness of the vessel.

1.  composite pressure vessel (CPV)

pressure vessel whose structural wall is fully composed with fibre based
composite material

1.  For example:

-   the permeation barrier can be ensured by a coating on the internal
    or the external shape of the composite wall, or by the composite
    wall itself, or by both.

-   low-pressure liquid hydrogen tank without liner.

1.  composite pressurized structure (CPS)

pressurized structure whose structural wall is fully composed with fibre
based composite material

1.  For example:

-   the permeation barrier can be ensured by a coating on the internal
    or external shape of the composite wall, or by the composite wall
    itself, or by both.

-   low-pressure liquid hydrogen structural tank without liner.

1.  critical flaw

specific flaw with a size such that unstable growth occurs under the
specific operating load and environment

1.  cryostat

vacuum-jacketed container designed to keep its contents at a low
(cryogenic) temperature

1.  Cryostat is also known as a Dewar, named after its inventor.

<!-- -->

1.  design burst pressure

differential pressure to be withstood by the pressurized hardware
without burst in the applicable operating environment

1.  The design burst pressure is equal to the product of the MDP and the
    burst factor.

<!-- -->

1.  differential pressure

internal pressure minus external pressure

1.  external pressure

absolute pressure outside the pressurized hardware

1.  fibre failure

rupture or kinking of a bundle of filaments

1.  There are two fibre failure modes: under tension (fibre rupture) and
    under compression (kinking).

<!-- -->

1.  fitting

pressure component of a pressurized system utilized to connect lines,
other pressure components or pressure vessels within the system

1.  hazardous fluid container

pressurized container, compartment or housing that is individually
sealed to contain a fluid, which can create a hazard if released

1.  hydrogen embrittlement

mechanical and environmental process that results from the initial
presence or absorption of excessive amounts of hydrogen in metals

1.  Usually it occurs in combination with residual or applied tensile
    stresses.

<!-- -->

1.  impact damage

induced defect caused by an object strike on the pressurized hardware or
pressurized hardware strike on an object

1.  Delamination in the composite over-wrap of a COPV, dent in the
    metallic liner of a COPV.

<!-- -->

1.  inter-fibre failure

micro-cracking in the matrix of a composite material, or at the
interface filament-matrix of a composite material

1.  internal pressure

absolute pressure inside the pressurized hardware

1.  leak-before-burst (LBB)

fracture mechanics design concept, showing that any potentially critical
flaw grows through the wall of a pressurized system and cause pressure
relieving leakage at MDP without burst (catastrophic failure)

1.  liner

part of pressurized hardware serving as a mandrel during the
manufacturing of the over-wrap and as fluid permeation barrier when in
contact with the stored fluid

1.  For example:

-   when the liner is made of metallic material, it can carry
    significant pressure and environmental loads.

-   when the liner is made of homogeneous non metallic material, it
    usually does not carry significant pressure and environmental loads.

1.  line

tubular pressurized hardware of a pressurized system provided as means
for transferring fluids between components of the system

1.  Flex hoses are included.

<!-- -->

1.  maximum design pressure (MDP)

See ECSS-E-ST-32.

1.  maximum expected operating pressure (MEOP)

See ECSS-E-ST-32.

1.  mechanical damage

induced flaw in pressurized hardware item which is caused by surface
abrasions, cuts or impacts

1.  The pressurized hardware item can be a metallic, homogeneous non
    metallic or composite item.

<!-- -->

1.  metallic pressure vessel (MPV)

pressure vessel fully composed of metallic material

1.  metallic pressurized structure (MPS)

pressurized structure fully composed of metallic material

1.  metallic pressurized component (MPC)

pressurized component fully composed of metallic material

1.  metallic special pressurized equipment (MSPE)

special pressurized equipment fully composed of metallic material

1.  non-hazardous LBB failure mode

leak-before-burst (LBB) behaviour that does not result in a hazard

1.  For example: LBB behaviour with a leak of liquid or gas that is not
    toxic, reactive or flammable.

<!-- -->

1.  pressure component (PC)

component in a pressurized system, other than a pressure vessel,
pressurized structure, or special pressurized equipment that is designed
largely by the internal pressure

1.  For example:

-   lines, fittings, gauges, valves, bellows, and hoses.

-   batteries not meeting the pressure vessel definition.

1.  pressure vessel (PV)

pressurized hardware designed primarily for the storage of pressurized
fluid with an energy level greater than or equal to 19310 Joules, or
with a pressure greater than or equal to 0,69 MPa, or which can create a
hazard if released

1.  E.g. the stored energy can be calculated by the formula for the
    reversible adiabatic (isentropic) expansion of the confined gas:

where:

*E* is the stored energy;

*P*~1~ is the internal pressure;

*P*~2~ is the external pressure;

*V* is the pressurized volume;

γ is the ratio of specific heat of the gas.

1.  pressurized hardware (PH)

hardware item that primarily contains internal pressure

1.  E.g. included are pressure vessels, pressurized structures, pressure
    components and special pressurized equipments.

<!-- -->

1.  pressurized structure (PS)

structure designed to carry both internal pressure and vehicle
structural loads

1.  E.g. launch vehicle main propellant tanks, crew cabins and manned
    modules.

<!-- -->

1.  pressurized system

system which consists of pressure vessels, or pressurized structures, or
both, and other pressure components, that are exposed to and
structurally designed largely by the acting pressure

1.  For example:

-   a pressurized system is often called a pressure system.

-   electrical or other control devices for system operations are not
    included.

1.  proof factor (j~proof~)

> multiplying factor applied to MDP to obtain design proof pressure

1.  proof pressure

product of MDP and proof factor

1.  proof test

test of flight hardware under proof load or pressure to give evidence of
satisfactory workmanship and material quality or to establish the
initial crack sizes in the hardware

1.  sealed container

pressurized container, compartment or housing that is individually
sealed to contain a fluid or to maintain an internal gaseous environment

1.  E.g. electronics housing

<!-- -->

1.  sizing pressure

pressure to which composite over-wrapped pressurized hardware is
subjected with the intent of yielding its metallic liner or a portion of
the liner

1.  E.g. the sizing pressure also refers to the pressure applied during
    autofrettage.

<!-- -->

1.  special pressurized equipment

pressurized hardware that meets the pressure vessel definition, but
which is not feasible or cost effective to conform to the requirements
applicable to pressure vessels

1.  For example:

-   pressurized hardware may be classified as special pressurized
    equipment with customer approval.

-   heat pipes, cryostats, sealed containers and hazardous fluids
    container.

-   sealed nickel-hydrogen batteries meeting the definition of a
    pressure vessel.

1.  visual damage threshold (VDT)

lowest impact energy level applied to a composite item that creates an
indication that is detectable by an inspector using an unaided visual
technique

1.  No quantitative reliability nor confidence level is associated with
    this technique.

    1.  Abbreviated terms
        -----------------

For the purpose of this Standard, the abbreviated terms from
ECSS-S-ST-00-01 and the following apply:

  -------------- ------------------------------------------------------
  Abbreviation   Meaning
  **BAI**        residual burst strength after impact
  **COPC**       composite over-wrapped pressurized component
  **COPS**       composite over-wrapped pressurized structures
  **COSPE**      composite over-wrapped special pressurized equipment
  **COPV**       composite over-wrapped pressure vessel
  **CPS**        composite pressurized structure
  **CPV**        composite pressure vessel
  **DLL**        design limit load
  **DUL**        design ultimate load
  **DYL**        design yield load
  **FCI **       fracture critical item
  **FLLI**       fracture limited life item
  **FOS**        factor of safety
  **ISS**        international space station
  **LBB **       leak-before-burst
  **MDP**        maximum design pressure
  **MEOP**       maximum expected operating pressure
  **MPC**        metallic pressurized component
  **MPS**        metallic pressurized structure
  **MPV**        metallic pressure vessel
  **MSPE**       metallic special pressurized equipment
  **NDI **       non-destructive inspection
  **PFCI **      potential fracture-critical item
  **PC**         pressure component
  **PH**         pressurized hardware
  **PV**         pressurized pressure vessel
  **PS**         pressurized structure
  **SPE**        special pressurized equipment
  **VDT**        visual damage threshold
  -------------- ------------------------------------------------------

Symbols
-------

**j~burst~** value of burst factor

**j~proof~** value of proof factor

**FOSU** value of ultimate factor of safety

**FOSY** value of yield factor of safety

1.  \
    General requirements
    ====================

    1.  Overview
        --------

        1.  ### Content

Clause 4 presents requirements which are general requirements in the
sense that:

-   requirements for all categories of pressurized hardware are
    specified in clause 4.2;

-   requirements for all pressure vessels are specified in clause 4.3;

-   requirements for all pressurized structures are specified in clause
    4.4;

-   requirements for all pressure components are specified in clause
    4.5;

-   requirements for all special pressurized equipments are specified in
    clause 4.6.

    1.  ### Categories of pressurized hardware

The pressurized hardware treated in this Standard are categorized in
Figure General requirements-1. A flowchart describing the classification
of pressurized hardware is in Figure General requirements-2.

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-32-02C_Rev.1(15November2008).docx1//media/image2.wmf){width="7.009027777777778in"
height="1.8444444444444446in"}

[[]{#_Ref70151995 .anchor}]{#__RefHeading___Toc214365290 .anchor}Figure
Chapter‑1: Breakdown of PH types covered by this Standard

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-32-02C_Rev.1(15November2008).docx1//media/image3.wmf){width="5.907638888888889in"
height="4.621527777777778in"}

[[]{#_Ref142378898 .anchor}]{#__RefHeading___Toc214365291 .anchor}Figure
Chapter‑2: Flowchart describing PH classifications covered by this
Standard

1.  General
    -------

    1.  ### Leak tightness

        a.  []{#_Ref150852673 .anchor}The maximum leak rates of the
            pressurized hardware versus pressure values shall be
            established through a detailed analysis of the pressurized
            system to which the pressurized hardware belongs.

        b.  Leak rate of all pressurized hardware shall conform to the
            level defined in 1.1.1.1.1a.

        c.  Leak rate of all pressurized hardware shall be such that
            operation of the system is ensured throughout the specified
            lifetime.

<!-- -->

1.  Pressurized hardware containing hazardous fluids reach end of
    safe-life when leakage occurs.

    1.  ### Classification of fracture critical parts

        a.  ‘Fracture critical item classification’ shall be performed
            in conformance with ECSS-E-ST-32-01.

2.  When pressurized hardware is classified as fracture critical, it is
    subjected to the implementation of the fracture critical item
    tracking, control and documentation procedures specified in
    ECSS-E-ST-32-01.

    1.  ### Operation and maintenance

        1.  #### Operating procedures

            a.  []{#_Ref149457619 .anchor}Operating procedures shall be
                established for all pressurized hardware.

            b.  The procedures specified in 1.1.1.1.1e shall be
                compatible with the safety requirements and personnel
                control requirements at the facility where the
                operations are conducted.

            c.  Step-by-step directions shall be written with such a
                detail to unambiguously describe the operation.

            d.  Schematics identifying the location and pressure limits
                of a relief valve and burst disc, shall be provided.

            e.  Procedures to ensure compatibility of the pressurizing
                system with the structural capability of the pressurized
                hardware shall be established.

            f.  Prior to initiating or performing a procedure involving
                hazardous operations with pressure systems, practice
                runs shall be conducted on non-pressurized systems.

            g.  Initial tests shall then be conducted at pressure levels
                not to exceed 50 % of the nominal operating pressure
                until operating characteristics can be established.

            h.  Warning signs with the hazard identified shall be posted
                at the operations facility prior to pressurization.

        2.  #### Safe operating limit

            a.  []{#_Ref96839694 .anchor}Safe operating limits shall be
                established for pressurized hardware based on analysis
                and testing employed during its design, development and
                qualification.

            b.  []{#_Ref96839721 .anchor}The safe operating limits
                specified in 1.1.1.1.1m shall be summarized in a format
                providing visibility of the structural characteristics
                and capability.

            c.  The information in the format specified in 1.1.1.1.1n
                shall include as a minimum the following data:

                1.  []{#_Ref96839820 .anchor}In a general case

                    a.  fabrication materials;

                    b.  critical design conditions;

                    c.  MDP;

                    d.  nominal operating pressure;

                    e.  proof pressure;

                    f.  design burst pressure;

                    g.  pressurization and depressurization sequence;

                    h.  operational cycle limits;

                    i.  operational system fluid;

                    j.  cleaning agent;

                    k.  NDI techniques employed;

                    l.  extreme thermal and chemical environments;

                    m.  maximum leakage levels versus pressure values;

                    n.  minimum margin of safety;

                    o.  potential failure mode.

                2.  For pressurized hardware with a non LBB failure
                    mode, additionally to the data included in
                    1.1.1.1.1o.1:

                    a.  the critical flaw sizes;

                    b.  the maximum acceptable flaw sizes.

            d.  Back-up documentation, including at least applicable
                references to design drawings, detail analyses,
                inspection records, and test reports, shall be
                indicated.

            e.  The minimum internal pressure to guaranty structural
                stabilization shall be identified and included in the
                acceptance data package.

        3.  #### Inspection and maintenance

            a.  The results of stress and safe-life analyses shall be
                used in conjunction with the results from the structural
                development and the qualification tests to define
                quantitative acceptance criteria for inspection and
                repair.

            b.  Damage limits shall be established by the supplier for
                pressurized hardware so that the inspection interval and
                repair schedule can be established.

            c.  Analyses of operational data developed per clause 5.7
                shall include forecast of remaining life and
                reassessment of inspection intervals.

        4.  #### Repair

            a.  All repaired or refurbished hardware shall be submitted
                to re-acceptance, as specified in clause 4.2.4.3, after
                each repair and refurbishment to verify their structural
                integrity.

        5.  #### Storage

            a.  []{#_Ref96840242 .anchor}When pressurized hardware is
                put into storage:

                1.  they shall be protected against exposure to adverse
                    environments that can cause corrosion or degrade the
                    material;

                2.  they shall be protected against mechanical damages;

                3.  induced stresses due to storage fixture constraints
                    shall be avoided by storage fixture design.

            b.  If 1.1.1.1.1v is not met, the hardware shall be
                submitted to re-acceptance as specified in clause
                4.2.4.3 prior to acceptance for use.

        6.  #### Documentation

            a.  []{#_Ref96840307 .anchor}Inspection, maintenance, and
                operation records shall be kept and maintained
                throughout the life of the pressurized hardware.

            b.  As a minimum, the records specified in 1.1.1.1.1x shall
                contain the following information:

                1.  temperature, pressurization history, and
                    pressurizing fluid for both tests and operations;

                2.  number of pressurization cycles experienced as well
                    as the maximum number in safe-life analysis or test;

                3.  results of any inspection conducted, including:
                    inspector, inspection dates, inspection techniques
                    employed, location and character of flaws, flaw
                    origin and cause;

                4.  storage condition;

                5.  maintenance and corrective action performed from
                    manufacturing to operational use, including
                    refurbishment;

                6.  sketches and photographs to show areas of structural
                    damage and the extent of repair;

                7.  acceptance and re-acceptance test performed,
                    including test condition and results;

                8.  analyses supporting the repair or modification which
                    can influence future use capability.

    2.  ### Service life extension, reactivation and re-acceptance

        1.  #### Service life extension

            a.  In case of safe-life demonstration, required for the
                hardware, the service life may be extended after
                performing a complete NDI, and leak test.

            b.  In case of fatigue life demonstration, required for the
                hardware, the service life may be extended without
                additional test or inspection, if there is available
                data including at least actual pressure, loads, and
                environments from the past period of service life, and
                the evaluation exhibits that the cumulative damage does
                not reach the specified service life.

            c.  The new service life shall be determined by fatigue-life
                or safe-life demonstration as required for this type of
                pressurized hardware.

        2.  #### Reactivation

            a.  Pressurized hardware which is reactivated for use after
                an extensive period in either an unknown, unprotected,
                or unregulated storage environment shall meet the
                requirements specified in clause 4.2.4.3 to ascertain
                their structural integrity before commitment to flight.

            b.  A specific inspection for corrosion and incidental
                damage prior to re-acceptance tests shall be performed.

        3.  #### Re-acceptance

            a.  []{#_Ref96843434 .anchor}All refurbished pressurized
                hardware shall undergo the same acceptance tests as
                specified for new hardware in clauses 4.3 to 4.6, in
                order to verify their structural integrity before
                commitment to flight.

            b.  If the demonstration specified in 1.1.1.1.1ee is not
                performed, it shall be demonstrated that the refurbished
                parts of the pressurized hardware are not affected by
                the corresponding tests.

            c.  []{#_Ref96843517 .anchor}Pressurized hardware exceeding
                the specified storage environment (e.g. temperature,
                humidity, time and storage fixture constraints) shall
                undergo the acceptance tests specified in clauses 4.3 to
                4.6 for new hardware.

            d.  If the demonstration specified in 1.1.1.1.1gg is not
                performed, it shall be demonstrated that all concerned
                parts of the pressurized hardware are not affected by
                the exceeded storage environment.

    <!-- -->

    1.  Pressure vessels
        ----------------

        1.  ### Factors of safety

            a.  The values in Table General requirements-1 shall be
                applied as minimum values of factors of safety for
                internal pressure.

            b.  For loads different from internal pressure, minimum
                values of factors of safety for ‘pressurized hardware’
                shall be applied in conformance with ECSS-E-ST-32-10.

<!-- -->

1.  1 Exceptions to the values provided in Table General requirements-1
    are sometimes specified by the customer or granted with customer
    approval.

When this is the case for a burst factor, the following relations can be
used for determination of the proof factor:

j~proof~ = (1 + j~burst~) / 2 when j~burst~ &lt; 2,0

j~proof~ = 1,5 when j~burst~ *&gt;* 2,0

[[]{#_Ref146339641 .anchor}]{#__RefHeading___Toc214365303 .anchor}Table
Chapter‑1: Factors of safety for PV (unmanned and manned missions)

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          Factor

  Internal pressure               1,0                                   1,25     1,0    1,5

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

1.  ### Metallic pressure vessels

    1.  #### Development approach

        a.  []{#_Ref146340073 .anchor}Clause 5.2 on structural
            engineering shall be applied.

        b.  []{#ref146340073 .anchor}The failure mode shall be
            demonstrated by analysis or test or both according to clause
            5.3.

        c.  []{#_Ref146339857 .anchor}Except in the case specified in
            1.1.1.1.1nn, ‘safe life item’ demonstration shall be
            performed by analysis or test in conformance with
            ECSS-E-ST-32-01.

        d.  []{#_Ref146339791 .anchor}For pressure vessels with a
            non-hazardous LBB failure mode, the safe-life demonstration
            specified in 1.1.1.1.1mm may be replaced by a fatigue life
            demonstration by analysis or test or both.

<!-- -->

1.  This can have an impact on the mission reliability.

    a.  In the case specified in 1.1.1.1.1nn, requirements for ‘fatigue
        analysis’ shall be applied in conformance with ECSS-E-ST-32.

    b.  Qualification tests shall be conducted according to clause
        4.3.2.2 to demonstrate the structural adequacy of the design.

    c.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    d.  For hydrogen embrittlement phenomena, requirements shall be
        applied in conformance with ECSS-E-ST-32-08.

    e.  For material selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with ECSS-E-ST-32.

    f.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    g.  Inspections shall be applied according to clause 5.7.

2.  The development approach is illustrated in Figure General
    requirements-3.

[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_Ref146339970 .anchor}]{#_Ref146339974
.anchor}]{#_1275135021 .anchor}]{#_1275135315 .anchor}]{#_1275204215
.anchor}]{#_1275204473 .anchor}]{#_1275204746 .anchor}]{#_1275204762
.anchor}]{#_1275204848 .anchor}]{#_1275204864 .anchor}]{#_1275205568
.anchor}]{#_1276163808 .anchor}]{#_1276429629 .anchor}]{#_1276442277
.anchor}]{#_1277216800 .anchor}]{#_1278171511 .anchor}]{#_1278171536
.anchor}]{#_1278171543 .anchor}]{#_1278171548 .anchor}]{#_1278251308
.anchor}]{#_1278251581 .anchor}]{#_1278252317 .anchor}]{#_1278254866
.anchor}]{#_1278255975 .anchor}]{#_1278256030 .anchor}]{#_1278256038
.anchor}]{#_1278324306 .anchor}]{#_1278324470 .anchor}]{#_1278324897
.anchor}]{#_1288105605 .anchor}

[[]{#_Ref201462727 .anchor}]{#__RefHeading___Toc214365292 .anchor}Figure
Chapter‑3: Development approach of MPV

1.  #### Qualification tests

    a.  []{#_Ref149458070 .anchor}A first qualification test article
        shall be submitted to the following chronology of operations:

        1.  non-destructive inspection (NDI);

        2.  proof pressure test;

        3.  leak test;

        4.  design burst pressure test;

        5.  burst test.

    b.  []{#_Ref149458040 .anchor}The first qualification test article
        specified in 1.1.1.1.1vv may be deleted with customer approval.

    c.  []{#_Ref149458125 .anchor}A second qualification test article
        shall be submitted to the following chronology of operations:

        1.  NDI;

        2.  proof pressure test;

        3.  leak test;

        4.  vibration tests;

        5.  pressure cycling test;

        6.  leak test;

        7.  design burst pressure test;

        8.  burst test.

    d.  The leak test after proof pressure test, specified in
        1.1.1.1.1xx, and the final burst test specified in 1.1.1.1.1xx
        may be deleted with customer approval.

    e.  When the vibration loads are enveloped by the other
        qualification tests, the vibration tests specified in
        1.1.1.1.1xx may be deleted with customer approval.

    f.  Clause 5.4 shall be applied to the qualification tests.

    g.  The need to apply external loads in combination with internal
        pressure during testing shall be considered taking into account
        their relative magnitude, the fatigue and destabilizing effects
        of external loads.

    h.  If external cycling loads are applied, the load shall be cycled
        to limit for four times the predicted number of operating cycles
        of the most severe design condition.

<!-- -->

1.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

2.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Clause 5.5 shall be applied to the acceptance tests.

    b.  Final NDI shall be performed on the weld-joints of the MPV as a
        minimum.

    <!-- -->

    1.  ### COPV with metallic liner

        1.  #### Development approach

            a.  Clause 5.2 on structural engineering shall be applied.

            b.  A stiffness demonstration shall be performed by analysis
                and test.

            c.  A strength and stability demonstration shall be
                performed by analysis and test.

            d.  The failure mode shall be demonstrated by analysis or
                test or both according to clause 5.3.

            e.  The metallic liner of the COPV shall exhibit a LBB
                failure mode.

            f.  []{#_Ref146340261 .anchor}‘Safe life item’ demonstration
                shall be performed for the metallic liner by analysis or
                test or both in conformance with ECSS-E-ST-32-01.

            g.  Fatigue-life demonstration shall be performed for the
                composite over-wrap by analysis or test or both in
                conformance with ECSS-E-ST-32.

            h.  Qualification tests shall be conducted according to
                clause 4.3.3.2 to demonstrate the structural adequacy of
                the design.

            i.  For corrosion effects (control and prevention), the
                requirements in ECSS-E-ST-32 shall apply.

            j.  For hydrogen embrittlement phenomena, requirements shall
                be applied in conformance with ECSS-E-ST-32-08.

            k.  For material selection, material design allowables and
                their characterisation, requirements shall be applied in
                conformance with clause 5.6 and ECSS-E-ST-32.

            l.  For ‘process control’, requirements shall be in
                conformance with ECSS-Q-ST-70.

            m.  Inspections shall be applied according to clause 5.7.

1.  The development approach is illustrated in Figure General
    requirements-4.

    1.  #### Qualification tests

        a.  []{#_Ref202353431 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  The first qualification test article specified in
            1.1.1.1.1ttt may be deleted with customer approval.

        c.  []{#_Ref201388648 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified in
            1.1.1.1.1vvv, and the final burst test specified
            in1.1.1.1.1vvv may be deleted with customer approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1vvv may be deleted with customer approval.

        f.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        g.  Clause 5.4 shall be applied to the qualification tests.

        h.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        i.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  For example: destabilizing load with constant minimum internal
    pressure or maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDI shall be performed on the over-wrap of the COPV as a
        minimum.

[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_Ref146340335
.anchor}]{#_Ref146340354 .anchor}]{#_1275136179 .anchor}]{#_1275136584
.anchor}]{#_1275136633 .anchor}]{#_1275136637 .anchor}]{#_1275136704
.anchor}]{#_1275136762 .anchor}]{#_1275136772 .anchor}]{#_1275204216
.anchor}]{#_1275205061 .anchor}]{#_1275205649 .anchor}]{#_1276163809
.anchor}]{#_1276429338 .anchor}]{#_1276432875 .anchor}]{#_1276442278
.anchor}]{#_1277216802 .anchor}]{#_1278165681 .anchor}]{#_1278165709
.anchor}]{#_1278171667 .anchor}]{#_1278251310 .anchor}]{#_1278255298
.anchor}]{#_1278255312 .anchor}]{#_1278255317 .anchor}]{#_1278255412
.anchor}]{#_1278255435 .anchor}]{#_1278255458 .anchor}]{#_1278255512
.anchor}]{#_1278255519 .anchor}]{#_1278255540 .anchor}]{#_1278255889
.anchor}]{#_1278255925 .anchor}]{#_1278255946 .anchor}]{#_1278255956
.anchor}]{#_1278324307 .anchor}]{#_1278324471 .anchor}]{#_1278324898
.anchor}]{#_1288105606 .anchor}

[[]{#_Ref156901258 .anchor}]{#__RefHeading___Toc214365293 .anchor}Figure
Chapter‑4: Development approach of COPV with metallic liner

1.  ### COPV with homogeneous non metallic liner and CPV

    1.  #### Development approach

        a.  Clause 5.2 on structural engineering shall be applied.

        b.  A stiffness demonstration shall be performed by analysis and
            test.

        c.  A strength and stability demonstration shall be performed by
            analysis and test.

        d.  The failure mode shall be demonstrated by test on full-scale
            article according to the requirements developed per clauses
            5.3.1, 5.3.4 and 5.3.5.

        e.  The liner of the COPV shall exhibit a LBB failure mode.

        f.  The CPV shall exhibit a LBB failure mode.

        g.  When the non-metallic liner of the COPV remains in
            compression up to MDP and flaws do not propagate during the
            LBB test, the flaws pre-fabricated in the liner of the LBB
            full-scale specimen may be through cracks.

        h.  []{#_Ref146340632 .anchor}‘Safe life item’ demonstration
            shall be performed in conformance with ECSS-E-ST-32-01:

            1.  by test for non-metallic items;

            2.  by analysis or test or both for metallic items (e.g.
                metallic bosses).

        i.  Qualification tests shall be conducted according to clause
            4.3.4.2 to demonstrate the structural adequacy of the
            design.

        j.  For corrosion effects (control and prevention), the
            requirements in ECSS-E-ST-32 shall apply.

        k.  For hydrogen embrittlement phenomena, requirements shall be
            applied in conformance with ECSS-E-ST-32-08.

        l.  For material selection, material design allowables and their
            characterisation, requirements shall be applied in
            conformance with clause 5.6 and ECSS-E-ST-32.

        m.  For ‘process control’, requirements shall be in conformance
            with ECSS-Q-ST-70.

        n.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-5.

    1.  #### Qualification tests

        a.  []{#_Ref204571837 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  []{#_Ref161144670 .anchor}The first qualification test
            article specified in 1.1.1.1.1uuuu may be deleted with
            customer approval.

        c.  []{#_Ref204571857 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified in
            1.1.1.1.1wwww, and the final burst test specified in
            1.1.1.1.1wwww may be deleted with customer approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1wwww may be deleted with customer approval.

        f.  For COPV, NDI operations shall be applied to the over-wrap,
            in addition to NDI on the liner.

        g.  For CPV, NDI operations shall be applied to the composite
            wall.

        h.  Clause 5.4 shall be applied to the qualification tests.

        i.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        j.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  For COPV, initial NDI operations shall be applied to the
        over-wrap, in addition to NDI on the liner.

    b.  For CPV, NDI operations shall be applied to the composite wall
        as a minimum.

    c.  Clause 5.5 shall be applied to the acceptance tests.

    d.  Final NDl shall be performed on the over-wrap of the COPV as a
        minimum.

[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_1275137007 .anchor}]{#_1275137313
.anchor}]{#_1275137337 .anchor}]{#_1275195768 .anchor}]{#_1275204217
.anchor}]{#_1275205678 .anchor}]{#_1275205790 .anchor}]{#_1275205793
.anchor}]{#_1275205810 .anchor}]{#_1276163810 .anchor}]{#_1276429309
.anchor}]{#_1276432766 .anchor}]{#_1276432779 .anchor}]{#_1276432795
.anchor}]{#_1276433390 .anchor}]{#_1276442279 .anchor}]{#_1277216803
.anchor}]{#_1278165776 .anchor}]{#_1278165809 .anchor}]{#_1278251311
.anchor}]{#_1278313795 .anchor}]{#_1278314057 .anchor}]{#_1278314618
.anchor}]{#_1278324308 .anchor}]{#_1278324472 .anchor}]{#_1278324899
.anchor}]{#_1288105607 .anchor}

[[]{#_Ref146340724 .anchor}]{#__RefHeading___Toc214365294 .anchor}Figure
Chapter‑5: Development approach of COPV with homogeneous non metallic
liner and CPV

1.  Pressurized structures
    ----------------------

    1.  ### Factors of safety

        a.  The values in Table General requirements-2 and Table General
            requirements-3 shall be applied as minimum values of factors
            of safety for internal pressure.

        b.  The values specified in ECSS-E-ST-32-10 shall be applied as
            minimum values of factors of safety for loads different from
            internal pressure.

<!-- -->

1.  Exceptions to the values provided in ECSS-ST-32-10 are sometimes
    specified by the customer or granted with customer approval.

    a.  Requirements for load combination shall be defined with customer
        approval.

    b.  The combined DYL shall be larger or equal than 1,0 times the
        combined DLL.

    c.  The combined DUL shall be larger or equal than 1,25 times the
        combined DLL in case of an unmanned mission.

    d.  The combined DUL shall be larger or equal than 1,4 times the
        combined DLL in case of a manned mission.

[[]{#_Ref70488758 .anchor}]{#__RefHeading___Toc214365304 .anchor}Table
Chapter‑2: Factors of safety for PS (unmanned mission)

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          Factor

  Internal pressure               1,1                                   1,1      1,25   1,25

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

[[[[]{#_Ref70488760 .anchor}]{#_Ref146340822 .anchor}]{#_Ref146340825
.anchor}]{#__RefHeading___Toc214365305 .anchor}Table Chapter‑3: Factors
of safety for PS (manned mission)

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          factor

  Internal pressure               1,1                                   1,1      1,4    1,4

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

[]{#__RefHeading___Toc214365306 .anchor}Table Chapter‑4: Factors of
safety for manned modules

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          factor

  Internal pressure               1,65                                  1,5      2,0    2,0

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

1.  ### Metallic pressurized structures 

    1.  #### Development approach

        a.  []{#_Ref96852105 .anchor}Clause 5.2 on structural
            engineering shall be applied.

        b.  [[]{#_Ref96852117 .anchor}]{#ref96852105 .anchor}The failure
            mode shall be demonstrated by analysis or test or both
            according to clause 5.3.

        c.  []{#_Ref96851617 .anchor}Except in the case specified in
            1.1.1.1.1sssss, ‘safe life item’ demonstration shall be
            performed by analysis or test or both in conformance with
            ECSS-E-ST-32-01.

        d.  [[]{#_Ref96851627 .anchor}]{#_Ref204572258 .anchor}For
            pressurized structures with a non-hazardous LBB failure
            mode, the safe-life demonstration specified in
            1.1.1.1.1rrrrr may be replaced by a fatigue life
            demonstration by analysis or test or both with customer
            approval.

<!-- -->

1.  []{#ref96851627 .anchor}This can have an impact on the mission
    reliability.

    a.  In the case specified in 1.1.1.1.1sssss, requirements for
        ‘fatigue analysis’ shall be applied in conformance with
        ECSS-E-ST-32.

    b.  Qualification tests shall be conducted according to clause
        4.4.2.2 to demonstrate the structural adequacy of the design.

    c.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    d.  For hydrogen embrittlement phenomena, requirements shall be
        applied in conformance with ECSS-E-ST-32-08.

    e.  For material selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with ECSS-E-ST-32.

    f.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    g.  Inspections shall be applied according to clause 5.7.

2.  The development approach is illustrated in Figure General
    requirements-6.

[[[[[[[[[[[[[[[[[[[]{#_1275137540 .anchor}]{#_1275204218
.anchor}]{#_1276163811 .anchor}]{#_1276434702 .anchor}]{#_1276442280
.anchor}]{#_1277216804 .anchor}]{#_1278251312 .anchor}]{#_1278314204
.anchor}]{#_1278314413 .anchor}]{#_1278314417 .anchor}]{#_1278314433
.anchor}]{#_1278314443 .anchor}]{#_1278314482 .anchor}]{#_1278314569
.anchor}]{#_1278314574 .anchor}]{#_1278324309 .anchor}]{#_1278324473
.anchor}]{#_1278324900 .anchor}]{#_1288105608 .anchor}

[[[]{#_Ref70490073 .anchor}]{#_Ref70490081
.anchor}]{#__RefHeading___Toc214365295 .anchor}Figure Chapter‑6:
Development approach of MPS

1.  #### Qualification tests

    a.  []{#_Ref149459165 .anchor}The qualification test article shall
        be submitted to the following chronology of operations:

        1.  NDI;

        2.  proof pressure test;

        3.  leak test;

        4.  pressure cycling test;

        5.  design burst pressure test.

    b.  The pressure cycling and design burst pressure tests specified
        in 1.1.1.1.1aaaaaa may be deleted with customer approval.

    c.  Clause 5.4 shall be applied to the qualification tests.

    d.  The need to apply external loads in combination with internal
        pressure during testing shall be considered taking into account
        their relative magnitude, fatigue and destabilizing effects of
        external loads.

    e.  If external cycling loads are applied, the load shall be cycled
        to limit for four times the predicted number of operating cycles
        of the most severe design condition.

<!-- -->

1.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

2.  The NDI prior to proof test can be substituted for that of the
    manufacturing process.

    a.  Clause 5.5 shall be applied to the acceptance tests.

    b.  Final NDI shall be performed on the weld-joints of the MPS as a
        minimum.

    <!-- -->

    1.  ### COPS with metallic liner

        1.  #### Development approach

            a.  Clause 5.2 on structural engineering shall be applied.

            b.  A stiffness demonstration shall be performed by analysis
                and test.

            c.  A strength and stability demonstration shall be
                performed by analysis and test.

            d.  The failure mode shall be demonstrated by analysis or
                test or both according to clause 5.3.

            e.  []{#_Ref96852359 .anchor}The metallic liner of the COPS
                shall exhibit a LBB failure mode.

            f.  ‘Safe life item’ demonstration shall be performed for
                the metallic liner by analysis or test or both in
                conformance with ECSS-E-ST-32-01.

            g.  []{#_Ref96852324 .anchor}Fatigue-life demonstration
                shall be performed for the composite over-wrap by
                analysis or test or both in conformance with
                ECSS-E-ST-32.

            h.  []{#ref96852324 .anchor}Qualification tests shall be
                conducted in conformance with clause 4.4.3.2 to
                demonstrate the structural adequacy of the design.

            i.  For corrosion effects (control and prevention), the
                requirements in ECSS-E-ST-32 shall apply.

            j.  For hydrogen embrittlement phenomena, requirements shall
                be applied in conformance with ECSS-E-ST-32-08.

            k.  For material selection, material design allowables and
                their characterisation, requirements shall be applied in
                conformance with clause 5.6 and ECSS-E-ST-32.

            l.  For ‘process control’, requirements shall be in
                conformance with ECSS-Q-ST-70.

            m.  Inspections shall be applied according to clause 5.7.

3.  The development approach is illustrated in Figure General
    requirements-7.

    1.  #### Qualification tests

        a.  []{#_Ref204572855 .anchor}The qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  pressure cycling test;

            5.  design burst pressure test.

        b.  The pressure cycling and design burst pressure tests
            specified in 1.1.1.1.1vvvvvv may be deleted with customer
            approval.

        c.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        d.  Clause 5.4 shall be applied to the qualification tests.

        e.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, fatigue and
            destabilizing effects of external loads.

        f.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

4.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

5.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDI shall be performed on the over-wrap of the COPS as a
        minimum.

[[[[[[[[[[[[[[[[[[[]{#_1275139479 .anchor}]{#_1275139795
.anchor}]{#_1275139889 .anchor}]{#_1275139893 .anchor}]{#_1275204219
.anchor}]{#_1276163812 .anchor}]{#_1276429125 .anchor}]{#_1276434920
.anchor}]{#_1276435028 .anchor}]{#_1276435032 .anchor}]{#_1276442281
.anchor}]{#_1277216805 .anchor}]{#_1278251313 .anchor}]{#_1278314827
.anchor}]{#_1278315091 .anchor}]{#_1278324310 .anchor}]{#_1278324474
.anchor}]{#_1278324902 .anchor}]{#_1288105609 .anchor}

[[]{#_Ref70760492 .anchor}]{#__RefHeading___Toc214365296 .anchor}Figure
Chapter‑7: Development approach of COPS with metallic liner

1.  ### COPS with homogeneous non metallic liner and CPS

    1.  #### Development approach

        a.  Clause 5.2 on structural engineering shall be applied.

        b.  A stiffness demonstration shall be performed by analysis and
            test.

        c.  A strength and stability demonstration shall be performed by
            analysis and test.

        d.  The failure mode shall be demonstrated by test on full-scale
            article according to clauses 5.3.1, 5.3.4 and 5.3.5.

        e.  The liner of the COPS shall exhibit a LBB failure mode.

        f.  The CPS shall exhibit a LBB failure mode.

        g.  When the non-metallic liner of the COPS remains in
            compression up to MDP and flaws do not propagate during the
            LBB test, the flaws pre-fabricated in the liner of the LBB
            full-scale specimen may be through cracks.

        h.  []{#_Ref96852771 .anchor}‘Safe life item’ demonstration
            shall be performed in conformance with ECSS-E-ST-32-01:

            1.  by test for non-metallic items;

            2.  by analysis or test or both for metallic items (e.g.
                metallic bosses).

        i.  []{#ref96852771 .anchor}Qualification tests shall be
            conducted according to clause 4.4.4.2 to demonstrate the
            structural adequacy of the design.

        j.  For corrosion effects (control and prevention), the
            requirements in ECSS-E-ST-32 shall apply.

        k.  For hydrogen embrittlement phenomena, requirements shall be
            applied in conformance with ECSS-E-ST-32-08.

        l.  For materials selection, material design allowables and
            their characterisation, requirements shall be applied in
            accordance with clause 5.6 and ECSS-E-ST-32.

        m.  For ‘process control’, requirements shall be in conformance
            with ECSS-Q-ST-70.

        n.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-8.

    1.  #### Qualification tests

        a.  The qualification test article shall be submitted to the
            following chronology of operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  pressure cycling test;

            5.  design burst pressure test.

        b.  For COPS, NDI operations shall be applied to the over-wrap,
            in addition to NDI on the liner.

        c.  For CPS, NDI operations shall be applied to the composite
            wall.

        d.  Clause 5.4 shall be applied to the qualification tests.

        e.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, fatigue and
            destabilizing effects of external loads.

        f.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  For COPS, initial NDI operations shall be applied to the
        over-wrap, in addition to NDI on the liner.

    b.  For CPS, NDI operations shall be applied to the composite wall
        as a minimum.

    c.  Clause 5.5 shall be applied to the acceptance tests.

    d.  Final NDI shall be performed on the over-wrap of the COPS as a
        minimum.

[[[[[[[[[[[[[[[[[[]{#_1275140059 .anchor}]{#_1275204220
.anchor}]{#_1276163813 .anchor}]{#_1276429098 .anchor}]{#_1276442282
.anchor}]{#_1277216807 .anchor}]{#_1277217060 .anchor}]{#_1277217074
.anchor}]{#_1277217078 .anchor}]{#_1278251314 .anchor}]{#_1278315246
.anchor}]{#_1278315414 .anchor}]{#_1278315418 .anchor}]{#_1278315443
.anchor}]{#_1278324311 .anchor}]{#_1278324475 .anchor}]{#_1278324903
.anchor}]{#_1288105611 .anchor}

[[]{#_Ref70762325 .anchor}]{#__RefHeading___Toc214365297 .anchor}Figure
Chapter‑8: Development approach of COPS with homogeneous non metallic
liner and CPS

1.  Pressure components
    -------------------

    1.  ### Metallic pressure components

        1.  #### Factors of safety

            a.  The values in Table General requirements-5 shall be
                applied as minimum values of factors of safety for
                internal pressure.

            b.  The values specified in ECSS-E-ST-32-10 shall be applied
                as minimum values of factors of safety for loads
                different from internal pressure.

<!-- -->

1.  Exceptions to the values provided in Table General requirements-5
    are sometimes specified by the customer or granted with customer
    approval.

[[]{#_Ref70762646 .anchor}]{#__RefHeading___Toc214365307 .anchor}Table
Chapter‑5: Factors of safety for MPC (unmanned and manned missions)

  ------------------------------------------------------------------------------------------- ------------------------------------- ------ -------- ------ --------
  Load                                                                                        Application                           FOSY   Proof\   FOSU   Burst\
                                                                                                                                           factor          factor

  Internal pressure                                                                           application 1                                1,5             4,0

                                                                                              application 2                                1,5             2,5

                                                                                              application 3                                1,5             2,5

  Mechanical loads\                                                                           Values specified in ECSS-E-ST-32-10
  (including external\                                                                        
  pressure)                                                                                   

  NOTES:\
  application 1: lines and fittings with diameter &lt; 38 mm\
  application 2: lines and fittings with diameter ≥ 38 mm\
  application 3: other MPC (including batteries not meeting the pressure vessel definition)
  ------------------------------------------------------------------------------------------- ------------------------------------- ------ -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

<!-- -->

1.  Thermal, stress and strain analyses and stiffness, strength and
    stability demonstrations are sometimes substituted with
    certification from qualified aerospace suppliers, with customer
    approval.

    a.  Qualification tests shall be conducted according to clause
        4.5.1.3 to demonstrate the structural adequacy of the design.

    b.  A ‘safe life item’ demonstration shall be performed by analysis
        or test or both in conformance with ECSS-E-ST-32-01 for pressure
        components not submitted to a proof pressure test or for which
        the proof factor used in the proof pressure test is less than
        1,5.

    c.  Fatigue-life demonstration shall be performed by analysis or
        test or both in conformance with ECSS-E-ST-32.

    d.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    e.  For hydrogen embrittlement phenomena, requirements shall be
        applied in conformance with ECSS-E-ST-32-08.

    f.  For material selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with ECSS-E-ST-32.

    g.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    h.  Inspections shall be applied according to clause 5.7.

2.  For example:

-   The development approach is illustrated in Figure General
    requirements-9.

-   Failure mode demonstration as per clause 5.3 is sometimes specified
    by the customer.

    1.  #### Qualification tests

        a.  Pressure components other than lines and fittings shall be
            submitted to a design burst pressure test.

1.  No qualification test is specified for lines and fittings on unit
    level.

    a.  Lines and fittings, which are joined to an assembly, shall be
        submitted to a design burst pressure test on a representative,
        flight-quality hardware assembly.

    b.  For pressure components other than lines and fittings at unit
        level, clauses 5.4.1 and 5.4.6 shall be applied to the
        qualification tests.

    <!-- -->

    1.  #### Acceptance tests

        a.  Pressure components shall be submitted to a proof pressure
            test or a leak test or both according to clause 5.5.

        b.  All items with fusion joints shall be submitted to a proof
            pressure test according to clause 5.5.2.

        c.  Proof and leak tests can be performed at the assembled
            pressurized system level.

        d.  All fusion joints shall be 100 % inspected by means of a NDI
            method, defined with customer approval, prior and after the
            proof pressure test.

[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_1275141340 .anchor}]{#_1275141723
.anchor}]{#_1275141793 .anchor}]{#_1275141809 .anchor}]{#_1275141836
.anchor}]{#_1275141859 .anchor}]{#_1275141898 .anchor}]{#_1275142043
.anchor}]{#_1275204221 .anchor}]{#_1275205891 .anchor}]{#_1275205920
.anchor}]{#_1276163814 .anchor}]{#_1276436143 .anchor}]{#_1276436675
.anchor}]{#_1276436716 .anchor}]{#_1276442283 .anchor}]{#_1277216808
.anchor}]{#_1278251315 .anchor}]{#_1278315635 .anchor}]{#_1278315750
.anchor}]{#_1278315753 .anchor}]{#_1278315884 .anchor}]{#_1278315920
.anchor}]{#_1278316144 .anchor}]{#_1278316168 .anchor}]{#_1278316171
.anchor}]{#_1278316198 .anchor}]{#_1278316201 .anchor}]{#_1278324313
.anchor}]{#_1278324476 .anchor}]{#_1278324904 .anchor}]{#_1288105612
.anchor}

[[]{#_Ref149625238 .anchor}]{#__RefHeading___Toc214365298 .anchor}Figure
Chapter‑9: Development approach of MPC

1.  ### COPC with metallic liner

    1.  #### Factors of safety

        a.  The values in Table General requirements-6 shall be applied
            as minimum values of factors of safety for internal
            pressure.

        b.  The values specified in ECSS-E-ST-32-10 shall be applied as
            minimum values of factors of safety for loads different from
            internal pressure.

<!-- -->

1.  Exceptions to the values provided in Table General requirements-6
    are sometimes specified by the customer or granted with customer
    approval.

When this is the case for a burst factor, the following relations can be
used for determination of the proof factor:

j~proof~ = (1 + j~burst~) / 2 when j~burst~ &lt; 2,0

j~proof~ = 1,5 when j~burst~ *&gt;* 2,0

> [[[]{#_Ref147301042 .anchor}]{#_Ref147301051
> .anchor}]{#__RefHeading___Toc214365308 .anchor}Table Chapter‑6:
> Factors of safety for COPC with metallic liner (unmanned and manned
> missions)

  ---------------------- ------------------------------------- -------- ------ --------
  Load                   FOSY                                  Proof\   FOSU   Burst\
                                                               factor          Factor

  Internal pressure      1,0                                   1,25     1,0    1,5

  Mechanical loads\      Values specified in ECSS-E-ST-32-10
  (including external\   
  pressure)              
  ---------------------- ------------------------------------- -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

    b.  A stiffness demonstration shall be performed by analysis and
        test.

    c.  A strength and stability demonstration shall be performed by
        analysis and test.

    d.  The failure mode shall be demonstrated by analysis or test or
        both according to clause 5.3.

    e.  The metallic liner of the COPC shall exhibit a LBB failure mode.

    f.  ‘Safe life item’ demonstration shall be performed for the
        metallic liner by analysis or test or both in conformance with
        ECSS-E-ST-32-01.

    g.  Fatigue-life demonstration shall be performed for the composite
        over-wrap by analysis or test or both in conformance with
        ECSS-E-ST-32.

    h.  Qualification tests shall be conducted according to clause
        4.5.2.3 to demonstrate the structural adequacy of the design.

    i.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    j.  For hydrogen embrittlement phenomena, requirements shall be
        applied in conformance with ECSS-E-ST-32-08.

    k.  For material selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with clause 5.6 and ECSS-E-ST-32.

    l.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    m.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-4.

    1.  #### Qualification tests

        a.  []{#_Ref202356602 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  The first qualification test article specified in
            1.1.1.1.1lllllllll may be deleted with customer approval.

        c.  []{#_Ref149467832 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified in
            1.1.1.1.1nnnnnnnnn, and the final burst test specified in
            1.1.1.1.1nnnnnnnnn may be deleted with customer approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1nnnnnnnnn may be deleted with customer approval.

        f.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        g.  Clause 5.4 shall be applied to the qualification tests.

        h.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        i.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDI shall be performed on the over-wrap of the COPC as a
        minimum.

    <!-- -->

    1.  ### COPC with homogeneous non metallic liner

        1.  #### Factors of safety

            a.  The values in Table General requirements-7 shall be
                applied as minimum values of factors of safety for
                internal pressure.

            b.  The values specified in ECSS-E-ST-32-10 shall be applied
                as minimum values of factors of safety for loads
                different from internal pressure.

1.  Exceptions to the values provided in Table General requirements-7
    are sometimes specified by the customer or granted with customer
    approval.

When this is the case for a burst factor, the following relations can be
used for determination of the proof factor:

j~proof~ = (1 + j~burst~) / 2 when j~burst~ &lt; 2,0

j~proof~ = 1,5 when j~burst~ *&gt;* 2,0

> [[]{#_Ref147303030 .anchor}]{#__RefHeading___Toc214365309
> .anchor}Table Chapter‑7: Factors of safety for COPC with homogeneous
> non metallic liner (unmanned and manned missions)

  ---------------------- ------------------------------------- -------- ------ --------
  Load                   FOSY                                  Proof\   FOSU   Burst\
                                                               factor          Factor

  Internal pressure      1,0                                   1,25     1,0    1,5

  Mechanical loads\      Values specified in ECSS-E-ST-32-10
  (including external\   
  pressure)              
  ---------------------- ------------------------------------- -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

    b.  A stiffness demonstration shall be performed by analysis and
        test.

    c.  A strength and stability demonstration shall be performed by
        analysis and test.

    d.  The failure mode shall be demonstrated by test on full-scale
        article according to the requirements developed per clauses
        5.3.1, 5.3.4 and 5.3.5.

    e.  The liner of the COPC shall exhibit a LBB failure mode.

    f.  When the non-metallic liner of the COPC remains in compression
        up to MDP and flaws do not propagate during the LBB test, the
        flaws pre-fabricated in the liner of the LBB full-scale specimen
        may be through cracks.

    g.  []{#_Ref147303488 .anchor}‘Safe life item’ demonstration shall
        be performed in conformance with ECSS-E-ST-32-01:

> by test for non-metallic items;
>
> by analysis or test or both for metallic items (e.g. metallic bosses).

a.  []{#ref147303488 .anchor}Qualification tests shall be conducted
    according to clause 4.5.3.3 to demonstrate the structural adequacy
    of the design.

b.  For corrosion effects (control and prevention), the requirements in
    ECSS-E-ST-32 shall apply.

c.  For hydrogen embrittlement phenomena, requirements shall be applied
    in conformance with ECSS-E-ST-32-08.

d.  For material selection, material design allowables and their
    characterisation, requirements shall be applied in conformance with
    clause 5.6 and ECSS-E-ST-32.

e.  For ‘process control’, requirements shall be in conformance with
    ECSS-Q-ST-70.

f.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-5.

    1.  #### Qualification tests

        a.  []{#_Ref149468087 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  []{#_Ref149468065 .anchor}The first qualification test
            article specified in 1.1.1.1.1nnnnnnnnnn may be deleted with
            customer approval.

        c.  []{#_Ref149468108 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified in
            1.1.1.1.1pppppppppp, and the final burst test specified in
            1.1.1.1.1pppppppppp may be deleted with customer approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1pppppppppp may be deleted with customer approval.

        f.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        g.  Clause 5.4 shall be applied to the qualification tests.

        h.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        i.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDI shall be performed on the over-wrap of the COPC as a
        minimum.

    <!-- -->

    1.  Special pressurized equipment
        -----------------------------

        1.  ### Metallic special pressurized equipment

            1.  #### Factors of safety

                a.  The values in Table General requirements-8 shall be
                    applied as minimum values of factors of safety for
                    internal pressure.

                b.  The values specified in ECSS-E-ST-32-10 shall be
                    applied as minimum values of factors of safety for
                    loads different from internal pressure.

1.  Exceptions to the values provided in Table General requirements-8
    are sometimes specified by the customer or granted with customer
    approval.

> [[]{#_Ref70764693 .anchor}]{#__RefHeading___Toc214365310 .anchor}Table
> Chapter‑8: Factors of safety for MSPE (unmanned and manned missions)

  ---------------------- -------------------------------------------------- -------------------------------------------------- -------- ------ --------
  Load                   Application                                        FOSY                                               Proof\   FOSU   Burst\
                                                                                                                               factor          factor

  Internal pressure      cryostats                                                                                             1,25            1,5

                         heat pipes                                                                                            1,5             2,5

                         sealed containers                                                                                     1,1             1,5

                         hazardous fluids container                                                                            1,5             2,5

                         batteries meeting the pressure vessel definition   Values specified in Table General requirements-1

  Mechanical loads\      Values specified in ECSS-E-ST-32-10
  (including external\   
  pressure)              
  ---------------------- -------------------------------------------------- -------------------------------------------------- -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

<!-- -->

1.  Thermal, stress and strain analyses and stiffness, strength and
    stability demonstrations are sometimes substituted with
    certification from qualified aerospace suppliers, with customer
    approval.

    a.  []{#_Ref149468228 .anchor}The failure mode shall be demonstrated
        by analysis or test or both, according to clause 5.3, for the
        following types of special pressurized equipment:

        1.  sealed container whose MDP is greater than or equal to 0,2
            MPa;

        2.  sealed container whose MDP is less than 0,2 MPa and that are
            not made of aluminium alloy, stainless steel or titanium
            alloy;

        3.  cryostats.

    b.  Special pressurized equipment defined in 1.1.1.1.1ddddddddddd,
        whose failure mode is not LBB or is LBB hazardous, shall be
        considered as pressure vessels, and therefore shall meet 4.3.

> NOTE Sealed containers with an LBB hazardous failure mode are
> sometimes designed as hazardous fluids containers.

a.  The development approach for batteries with pressurized cells that
    meet the definition of a pressure vessel shall conform to clause
    4.3.2.1.

b.  Qualification tests shall be conducted according to 4.6.1.3 to
    demonstrate the structural adequacy of the design.

c.  A ‘safe life item’ demonstration shall be performed by analysis or
    test or both in conformance with ECSS-E-ST-32-01 for heat pipes and
    hazardous fluids containers not submitted to a proof pressure test
    or for which the proof factor used in the proof pressure test is
    less than 1,5.

d.  Fatigue-life demonstration shall be performed by analysis or test or
    both in conformance with ECSS-E-ST-32.

e.  For corrosion effects (control and prevention), the requirements in
    ECSS-E-ST-32 shall apply.

f.  For hydrogen embrittlement phenomena, requirements shall be applied
    in conformance with ECSS-E-ST-32-08.

g.  For material selection, material design allowables and their
    characterisation, requirements shall be applied in conformance with
    ECSS-E-ST-32.

h.  For ‘process control’, requirements shall be in conformance with
    ECSS-Q-ST-70.

i.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  1 The development approach for sealed containers is illustrated in
    Figure General requirements-10.

2.  2 The development approach for cryostats (or Dewars) is illustrated
    in Figure General requirements-11.

3.  3 The development approach for heat pipes is illustrated in Figure
    General requirements-12.

4.  4 The development approach for hazardous fluids containers is
    illustrated in Figure General requirements-13.

5.  5 Failure mode demonstration as per clause 5.3 is sometimes
    specified for heat pipes by the customer.

[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[[]{#_1275142226 .anchor}]{#_1275142650
.anchor}]{#_1275197805 .anchor}]{#_1275197818 .anchor}]{#_1275197917
.anchor}]{#_1275197920 .anchor}]{#_1275197941 .anchor}]{#_1275197960
.anchor}]{#_1275197985 .anchor}]{#_1275197994 .anchor}]{#_1275198012
.anchor}]{#_1275198018 .anchor}]{#_1275204223 .anchor}]{#_1276163815
.anchor}]{#_1276442284 .anchor}]{#_1277216809 .anchor}]{#_1277217310
.anchor}]{#_1277217360 .anchor}]{#_1277217367 .anchor}]{#_1278251316
.anchor}]{#_1278317139 .anchor}]{#_1278317163 .anchor}]{#_1278317167
.anchor}]{#_1278317287 .anchor}]{#_1278317294 .anchor}]{#_1278317359
.anchor}]{#_1278317366 .anchor}]{#_1278317390 .anchor}]{#_1278324314
.anchor}]{#_1278324478 .anchor}]{#_1278324905 .anchor}]{#_1288105613
.anchor}

[[[]{#_Ref70767458 .anchor}]{#_Ref70767462
.anchor}]{#__RefHeading___Toc214365299 .anchor}Figure Chapter‑10:
Development approach of sealed containers

[[[[[[[[[[[[[[[[]{#_1275142747 .anchor}]{#_1275197764
.anchor}]{#_1275204224 .anchor}]{#_1276163816 .anchor}]{#_1276442285
.anchor}]{#_1277216811 .anchor}]{#_1277217414 .anchor}]{#_1277217433
.anchor}]{#_1277217437 .anchor}]{#_1278251318 .anchor}]{#_1278317398
.anchor}]{#_1278317520 .anchor}]{#_1278324315 .anchor}]{#_1278324479
.anchor}]{#_1278324906 .anchor}]{#_1288105614 .anchor}

[[]{#_Ref70767475 .anchor}]{#__RefHeading___Toc214365300 .anchor}Figure
Chapter‑11: Development approach of cryostats (or Dewars)

[[[[[[[[[[[[[[[[]{#_1275142977 .anchor}]{#_1275143397
.anchor}]{#_1275197713 .anchor}]{#_1275204225 .anchor}]{#_1276163818
.anchor}]{#_1276429049 .anchor}]{#_1276442286 .anchor}]{#_1277216812
.anchor}]{#_1277217466 .anchor}]{#_1278251319 .anchor}]{#_1278317538
.anchor}]{#_1278317882 .anchor}]{#_1278324316 .anchor}]{#_1278324480
.anchor}]{#_1278324907 .anchor}]{#_1288105615 .anchor}

[[]{#_Ref70767489 .anchor}]{#__RefHeading___Toc214365301 .anchor}Figure
Chapter‑12: Development approach of heat pipes

[[[[[[[[[[[[[[[]{#_Ref70765708 .anchor}]{#_1275196086
.anchor}]{#_1275196701 .anchor}]{#_1275204226 .anchor}]{#_1276163819
.anchor}]{#_1276442287 .anchor}]{#_1277216813 .anchor}]{#_1277217495
.anchor}]{#_1278251320 .anchor}]{#_1278317890 .anchor}]{#_1278318240
.anchor}]{#_1278324317 .anchor}]{#_1278324481 .anchor}]{#_1278324908
.anchor}]{#_1288105616 .anchor}

[[]{#_Ref142380517 .anchor}]{#__RefHeading___Toc214365302 .anchor}Figure
Chapter‑13: Development approach of hazardous fluid containers

1.  #### Qualification tests

    a.  All cryostats shall be submitted to the following chronology of
        operations:

        1.  proof pressure test;

        2.  vibration tests;

        3.  design burst pressure test.

    b.  All heat pipes and hazardous fluids containers shall be
        submitted to a design burst pressure test.

    c.  All batteries meeting the pressure vessel definition shall be
        submitted to the qualification tests as per clause 4.3.2.2.

    d.  For batteries meeting the pressure vessel definition, the
        qualification tests to be performed for functional performance
        shall be defined with customer approval.

<!-- -->

1.  Qualification leak test is sometimes replaced by thermal vacuum
    test.

    a.  Clauses 5.4.1, 5.4.2, 5.4.4 and 5.4.6, shall be applied to the
        qualification tests.

    <!-- -->

    1.  #### Acceptance tests

        a.  The following SPE shall be submitted to a proof pressure
            test:

            1.  sealed containers with MDP greater than or equal to 0,2
                MPa and exhibiting a LBB failure mode;

            2.  cryostats;

            3.  heat pipes;

            4.  hazardous fluids containers.

        b.  Cryostats shall be NDI inspected prior to the proof pressure
            test.

        c.  Fusion joints shall be 100 % inspected by means of a NDI
            method, defined with customer approval, prior and after the
            proof pressure test.

        d.  All batteries meeting the pressure vessel definition shall
            be submitted to the acceptance tests as per clause 4.3.2.3.

        e.  For batteries meeting the pressure vessel definition,
            additional acceptance tests shall be defined for functional
            performance with customer approval.

        f.  Clauses 5.5.1, 5.5.2, and 5.5.3 shall be applied to the
            acceptance tests.

2.  Proof and leak tests can be performed at the assembled pressurized
    system level.

    1.  ### COSPE with metallic liner

        1.  #### Factors of safety

            a.  The values in Table General requirements-9 shall be
                applied as minimum values of factors of safety for
                internal pressure.

            b.  The values specified in ECSS-E-ST-32-10 shall apply as
                minimum values of factors of safety for loads different
                from internal pressure.

3.  Exceptions to the values provided in Table General requirements-9
    are sometimes specified by the customer or granted with customer
    approval.

When this is the case for a burst factor, the following relations can be
used for determination of the proof factor:

j~proof~ = (1 + j~burst~) / 2 when j~burst~ &lt; 2,0

j~proof~ = 1,5 when j~burst~ *&gt;* 2,0

> [[[]{#_Ref147304113 .anchor}]{#_Ref147304126
> .anchor}]{#__RefHeading___Toc214365311 .anchor}Table Chapter‑9:
> Factors of safety for COSPE with metallic liner
> (unmanned and manned missions)

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          factor

  Internal pressure               1,0                                   1,25     1,0    1,5

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

    b.  A stiffness demonstration shall be performed by analysis and
        test.

    c.  A strength and stability demonstration shall be performed by
        analysis and test.

    d.  The failure mode shall be demonstrated by analysis or test or
        both according to clause 5.3.

    e.  The metallic liner of the COSPE shall exhibit a LBB failure
        mode.

    f.  ‘Safe life item’ demonstration shall be performed for the
        metallic liner by analysis or test or both in conformance with
        ECSS-E-ST-32-01.

    g.  Fatigue-life demonstration shall be performed for the composite
        over-wrap by analysis or test or both in conformance with
        ECSS-E-ST-32.

    h.  Qualification tests shall be conducted in conformance with
        clause 4.6.2.3 to demonstrate the structural adequacy of the
        design.

    i.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    j.  For hydrogen embrittlement phenomena, requirements shall be
        applied in conformance with ECSS-E-ST-32-08.

    k.  For material selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with clause 5.6 and ECSS-E-ST-32.

    l.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    m.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-4.

    1.  #### Qualification tests

        a.  []{#_Ref149468342 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  []{#_Ref149468318 .anchor}The first qualification test
            article specified in 1.1.1.1.1oooooooooooo may be deleted
            with customer approval.

        c.  []{#_Ref149468367 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified in
            1.1.1.1.1qqqqqqqqqqqq, and the final burst test, specified
            in 1.1.1.1.1qqqqqqqqqqqq may be deleted with customer
            approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1qqqqqqqqqqqq may be deleted with customer approval.

        f.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        g.  Clause 5.4 shall be applied to the qualification tests.

        h.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        i.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDI shall be performed on the over-wrap of the COSPE as a
        minimum.

    <!-- -->

    1.  ### COSPE with homogeneous non metallic liner

        1.  #### Factors of safety

            a.  The values in Table General requirements-10 shall be
                applied as minimum values of factors of safety for
                internal pressure.

            b.  The values specified in ECSS-E-ST-32-10 shall be applied
                as minimum values of factors of safety for loads
                different from internal pressure.

1.  Exceptions to the values provided in Table General requirements-10
    are sometimes specified by the customer or granted with customer
    approval.

When this is the case for a burst factor, the following relations can be
used for determination of the proof factor:

j~proof~ = (1 + j~burst~) / 2 when j~burst~ &lt; 2,0

j~proof~ = 1,5 when j~burst~ *&gt;* 2,0

[[]{#_Ref147307743 .anchor}]{#__RefHeading___Toc214365312 .anchor}Table
Chapter‑10: Factors of safety for COSPE with homogeneous non metallic
liner (unmanned and manned missions)

  ------------------------------- ------------------------------------- -------- ------ --------
  Load                            FOSY                                  Proof\   FOSU   Burst\
                                                                        factor          factor

  Internal pressure               1,0                                   1,25     1,0    1,5

  Mechanical loads\               Values specified in ECSS-E-ST-32-10
  (including external pressure)   
  ------------------------------- ------------------------------------- -------- ------ --------

1.  #### Development approach

    a.  Clause 5.2 on structural engineering shall be applied.

    b.  A stiffness demonstration shall be performed by analysis and
        test.

    c.  A strength and stability demonstration shall be performed by
        analysis and test.

    d.  The failure mode shall be demonstrated by test on full-scale
        article according to the requirements developed per clauses
        5.3.1, 5.3.4 and 5.3.5.

    e.  The liner of the COSPE shall exhibit a LBB failure mode.

    f.  When the non-metallic liner of the COSPE remains in compression
        up to MDP and flaws do not propagate during the LBB test, the
        flaws pre-fabricated in the liner of the LBB full-scale specimen
        may be through cracks.

    g.  ‘Safe life item’ demonstration shall be performed in accordance
        with ECSS-E-ST-32-01:

        1.  by test for non-metallic items;

        2.  by analysis or test or both for metallic items (e.g.
            metallic bosses).

    h.  Qualification tests shall be conducted according to clause
        4.6.3.3 to demonstrate the structural adequacy of the design.

    i.  For corrosion effects (control and prevention), the requirements
        in ECSS-E-ST-32 shall apply.

    j.  Embrittlement control shall be applied in accordance with
        ECSS-E-ST-32-08.

    k.  For materials selection, material design allowables and their
        characterisation, requirements shall be applied in conformance
        with clause 5.6 and ECSS-E-ST-32.

    l.  For ‘process control’, requirements shall be in conformance with
        ECSS-Q-ST-70.

    m.  Inspections shall be applied according to clause 5.7.

<!-- -->

1.  The development approach is illustrated in Figure General
    requirements-5.

    1.  #### Qualification tests

        a.  []{#_Ref149468586 .anchor}A first qualification test article
            shall be submitted to the following chronology of
            operations:

            1.  non-destructive inspection (NDI);

            2.  proof pressure test;

            3.  leak test;

            4.  design burst pressure test;

            5.  burst test.

        b.  []{#_Ref149468567 .anchor}The first qualification test
            article specified in 1.1.1.1.1qqqqqqqqqqqqq may be deleted
            with customer approval.

        c.  []{#_Ref149468606 .anchor}A second qualification test
            article shall be submitted to the following chronology of
            operations:

            1.  NDI;

            2.  proof pressure test;

            3.  leak test;

            4.  vibration tests;

            5.  pressure cycling test;

            6.  leak test;

            7.  design burst pressure test;

            8.  burst test.

        d.  The leak test after proof pressure test specified
            in1.1.1.1.1sssssssssssss, and the final burst test specified
            in 1.1.1.1.1sssssssssssss may be deleted with customer
            approval.

        e.  When the vibration loads are enveloped by the other
            qualification tests, the vibration tests specified in
            1.1.1.1.1sssssssssssss may be deleted with customer
            approval.

        f.  NDI operations shall be applied to the over-wrap, in
            addition to NDI on the liner.

        g.  Clause 5.4 shall be applied to the qualification tests.

        h.  The need to apply external loads in combination with
            internal pressure during testing shall be considered taking
            into account their relative magnitude, the fatigue and
            destabilizing effects of external loads.

        i.  If external cycling loads are applied, the load shall be
            cycled to limit for four times the predicted number of
            operating cycles of the most severe design condition.

2.  Destabilizing load with constant minimum internal pressure or
    maximum additive load with a constant MDP.

    1.  #### Acceptance tests

        a.  All hardware shall be submitted to the following chronology
            of operations:

            1.  initial NDI, in order to establish the initial condition
                of the hardware;

            2.  proof pressure test;

            3.  leak test;

            4.  final NDI.

3.  For example:

-   The NDI prior to proof test can be substituted for that of the
    manufacturing process.

-   Proof test monitoring by acoustic emission is acceptable for
    composite items instead of post testing NDI, with customer approval.

    a.  Initial NDI operations shall be applied to the over-wrap, in
        addition to NDI on the liner.

    b.  Clause 5.5 shall be applied to the acceptance tests.

    c.  Final NDl shall be performed on the over-wrap of the COSPE as a
        minimum.

1.  \
    Specific requirements
    =====================

    1.  Overview
        --------

This clause presents the detail of requirements used in the development
approach, qualification and acceptance of pressurized hardware.

These requirements are specific requirements in the sense that their
applicability depends on the category of pressurized hardware, as
presented in clauses 4.3 to 4.6.

The following requirements are included:

-   structural engineering;

-   failure mode demonstration;

-   damage control of pressurized composite hardware;

-   qualification tests;

-   acceptance tests;

-   composite over-wrap material characterisation;

-   inspection.

    1.  Structural engineering
        ----------------------

        a.  The structural design of pressurized hardware shall be in
            conformance with ECSS-E-ST-32.

        b.  The effect of each operating parameter of the system (e.g.
            pressure regulator lock-up characteristics, valve actuation
            and water hammer) and any external loads and environments
            shall be considered for MDP determination.

        c.  Proof pressure and design burst pressure shall be derived
            from the MDP using the factor of safety given in clause 4.

        d.  The range of internal pressure shall be taken into account
            in the stiffness analysis (e.g. foreign frequency analysis).

        e.  As a minimum, any item of pressurized hardware shall
            possess, throughout the respective service life of the
            hardware in the expected operating environments, a strength
            such to withstand:

            1.  proof pressure without detrimental deformation;

            2.  design burst pressure without experiencing rupture or
                fibre failure;

            3.  DYL and simultaneous internal pressure multiplied by
                FOSY for internal pressure without detrimental
                deformation;

            4.  MDP multiplied by FOSY for internal pressure and
                simultaneous loads multiplied by FOSY for mechanical and
                thermal loads, without detrimental deformation;

            5.  DUL and simultaneous internal pressure multiplied by
                FOSU for internal pressure without experiencing rupture
                or fibre failure;

            6.  MDP multiplied by FOSU for internal pressure and
                simultaneous loads multiplied by FOSU for mechanical and
                thermal loads, without experiencing rupture or fibre
                failure;

            7.  DUL and simultaneous external pressure multiplied by
                FOSU for mechanical and thermal loads, without
                experiencing rupture or fibre failure when pressurized
                to the minimum anticipated operating pressure.

        f.  The minimum internal pressure to guaranty structural
            stabilization shall be identified and included in the
            acceptance data package.

        g.  The pressurized hardware shall possess, throughout its
            service life in the expected operating environments, a
            stability such to withstand:

            1.  DUL and simultaneous external pressure multiplied by
                FOSU for pressure loads, without experiencing collapse
                when pressurized to the minimum anticipated operating
                pressure;

            2.  DUL and simultaneous internal pressure without
                experiencing collapse.

        h.  A scatter factor of five (5) shall be used in fatigue
            analysis.

    2.  Failure mode demonstration
        --------------------------

        1.  ### General

            a.  The failure mode demonstration (i.e. demonstration of
                LBB or no LBB) can be ensured by analysis or test or
                both.

            b.  The choice of the demonstration methodology (i.e.
                analysis or test or both) shall conform to the
                requirements on failure mode demonstration specified in
                clauses 4.2 to 4.5 according to the type of pressurized
                hardware.

1.  For example:

-   Failure mode may be demonstrated by similarity with an existing
    analysis or test with customer approval.

-   For new designs, without heritage, the demonstration by test is
    sometimes specified by the customer.

    a.  When failure mode is demonstrated by test, coupons or full-scale
        articles with prefabricated flaws shall be used as test
        specimens.

    b.  The failure mode shall be demonstrated for the structural items
        of the pressurized hardware, which serve as a fluid permeation
        barrier and which are primarily designed by pressure loads.

1.  For example:

-   For composite over-wrapped pressurized hardware, the liner is the
    fluid permeation barrier.

-   For composite over-wrapped pressurized hardware, the boss area can
    be primarily designed by shear and not by pressure loads.

-   For CPV and CPS, the composite wall itself is considered as the
    fluid permeation barrier.

    a.  When the failure mode demonstration is performed for metallic
        items, fracture mechanics principles shall be employed.

    b.  Areas where the LBB failure mode is not demonstrated shall be
        designed according to safe-life requirements as per clause 5.3.

    c.  For composite and composite over-wrapped pressurized hardware,
        potential degradation of the composite strength by the leaking
        fluid shall be accounted for in the failure mode demonstration.

    <!-- -->

    1.  ### Demonstration of LBB by analysis

        a.  []{#_Ref149468803 .anchor}It shall be shown that, at MDP, an
            initial surface crack with a flaw shape (a/c), ranging from
            0,2 to 1,0, meets the following conditions:

            1.  it does not fail as a surface crack; and

            2.  [[]{#_Ref149468805 .anchor}]{#_Ref202355412 .anchor}it
                grows through the wall of the hardware to become a
                through crack with a length greater than or equal to 10
                times the wall thickness of the metallic hardware item
                and remains stable.

1.  For example:

-   For a part-through surface crack, the crack aspect ratio is the
    ratio (a/c) of crack depth (a) to half crack length (c). For a
    part-through corner crack, the crack aspect ratio is the ratio (a/c)
    of crack depth (a) to crack length (c)/

-   If no assumption is made about the initial surface crack size, the
    specified range a/c between 0,2 and 1,0 leads to a maximum through
    crack length of 2 c = 10 t (for a = t, where t is the wall
    thickness).

    a.  When LBB demonstration is based on a through crack with a length
        less than 10 times the wall thickness in accordance with
        1.1.1.1.1ssssssssssssss.2, the considered initial crack size
        shall be justified.

1.  Justification of initial surface crack size can be based on NDI
    capability or on a crack whose depth is as close as possible to the
    wall thickness, within the range of a/c specified in clause
    5.3.2ssssssssssssss.

    1.  ### Demonstration of LBB by test using coupons

        a.  Coupons shall duplicate the materials (parent metals, weld
            joints, and heat affected zones) and the thickness of the
            metallic hardware items.

        b.  The coupon tests shall duplicate the loading conditions of
            the metallic hardware items.

2.  Loading conditions include stress state aspects of bi-axial,
    compressive stresses parallel to crack plane.

    a.  []{#_Ref157579195 .anchor}The flaws shall be surface cracks and
        the flaw shape of the pre-fabricated surface cracks shall range
        from a/c = 0,2 to 1,0.

3.  For the definition of a part-through surface crack, and a
    part-through corner crack see NOTE 1 in ssssssssssssss.

    a.  The initial surface crack size shall be justified.

4.  Justification of initial surface crack size can be based on NDI
    capability or on a crack whose depth is as close as possible to the
    wall thickness, within the range of a/c specified in
    1.1.1.1.1wwwwwwwwwwwwww.

    a.  Stress (or strain) cycles shall be applied to the specimens with
        the maximum stress (or strain) corresponding to the MDP level
        and minimum stress (or strain) kept to zero, or actual minimum
        stress (or strain), until the surface crack grows through the
        specimen's thickness to become a through crack.

    b.  It shall be shown that the length of the through crack becomes
        equal to or greater than 10 times the specimen's thickness and
        remains stable at MDP.

    <!-- -->

    1.  ### Demonstration of LBB by test using full-scale article

        a.  The full-scale article shall be representative of the flight
            hardware.

        b.  The type and initial size of pre-fabricated flaws shall be
            justified.

5.  Justification of initial flaw size can be based on NDI capability or
    on a crack whose depth is as close as possible to the wall
    thickness, within the range of a/c specified in sub
    clause1.1.1.1.1ccccccccccccccc.

    a.  []{#_Ref159208765 .anchor}For pre-flawed metallic items, the
        flaws shall be surface cracks and the aspect ratio of the
        pre-fabricated surface cracks shall range from a/c = 0,2 to 1,0.

6.  For the definition of a part-through surface crack, and a
    part-through corner crack see NOTE 1 in ssssssssssssss.

    a.  For pre-flawed composite items (liner or walls), the flaws may
        be through cracks with a length greater than or equal to 10
        times the wall thickness of the item.

    b.  Location and orientation of pre-fabricated flaws shall be the
        most critical with regard to LBB response.

    c.  Pressure cycles shall be applied to the pressurized hardware,
        with the upper pressure equal to MDP and the lower pressure
        greater than or equal to zero.

    d.  []{#_Ref151188409 .anchor}After a flaw has grown through the
        thickness to become a through flaw and leakage has been
        detected, internal pressure shall be increased up to MDP.

    e.  At least one of the following conditions shall be satisfied
        after 1.1.1.1.1ggggggggggggggg has been met:

-   no burst occurs at MDP and leak rate is equal to or greater than a
    value defined with customer approval. This criteria is applicable to
    composite over-wrapped pressurized hardware, or

-   the length of the through crack in the metallic item becomes equal
    to or greater than 10 times the wall thickness of the item and
    remains stable at MDP. This criteria is only applicable to metallic
    and fully composite pressurized hardware.

    a.  Test fluid shall be compatible with the materials used in the
        hardware and not pose a hazard to test personnel.

    b.  The full-scale test shall duplicate the loading conditions and
        pressurization medium (gas or liquid) of the flight hardware.

1.  E.g. loading conditions include stress state aspects of bi-axial,
    compressive stresses parallel to crack plane.

    1.  ### Report of LBB demonstration

        a.  []{#_Ref149468907 .anchor}When LBB is demonstrated by
            analysis:

            1.  []{#_Ref161114284 .anchor}an analysis report in
                conformance with ECSS-E-ST-10-02 shall be prepared;

            2.  in the report specified in 5.3.5kkkkkkkkkkkkkkk1,
                loading spectra, assumed initial flaw sizes, crack
                growth models, and fatigue crack growth rates shall be
                delineated.

        b.  When LBB is demonstrated by test, a test report shall be
            prepared in conformance with ECSS-E-ST-10-02.

    <!-- -->

    1.  Qualification tests
        -------------------

        1.  ### General

            a.  ‘General requirements’ and ‘Qualification testing’
                requirements shall apply in conformance with
                ECSS-E-ST-10-03.

            b.  When the hardware mounting induces axial or radial
                restrictions on the pressure driven expansion of the
                hardware, the burst test fixture shall simulate the
                structural response or reaction loads of the flight
                mounting.

            c.  When a qualification test is conducted at temperature
                other than temperature expected for the design loads,
                the change of material properties at this temperature
                shall be verified:

-   by adjustment of the pressure and load level, or

-   by analysis, supported by tests on samples or sub-scale articles and
    providing material strength design allowable versus temperature.

    a.  When NDI is performed in the qualification tests, it shall meet
        clause 5.7.

    b.  The test fluids shall not deteriorate the test article.

    c.  The test fluids shall not pose a hazard to the test personnel.

    d.  When the strength design allowable of the materials depends on
        the fluid to be stored in the flight hardware (e.g. when the
        stored fluid is liquid hydrogen), the change of material
        properties shall be verified:

-   by using this specific fluid to pressurize the test specimens, or

-   by analysis, supported by tests on samples or sub-scale articles and
    providing material strength design allowable versus fluid
    characteristics.

    a.  In case of changing the manufacturing process, the qualification
        tests shall be repeated unless it is demonstrated that the new
        manufacturing process maintains or improves material and
        geometrical characteristics.

    <!-- -->

    1.  ### Proof pressure test

        a.  During the proof pressure test, the load level (i.e.
            pressure level, external load level) shall be maintained for
            5 minutes as a minimum.

        b.  The interest for application of external loads in
            combination with internal pressures during testing shall be
            evaluated based on the relative magnitude, the destabilizing
            effect, or both, of stresses due to the external load.

    2.  ### Leak test

        a.  []{#_Ref146620159 .anchor}During the leak test, the pressure
            level shall be maintained at MDP or greater for 30 minutes
            as a minimum.

        b.  [[]{#_Ref146620173 .anchor}]{#_Ref204581841 .anchor}For
            qualification ‘leakage test’, requirements shall be in
            conformance with ECSS-E-ST-10-03.

1.  []{#_Ref70767617 .anchor}Exceptions to the values provided in
    1.1.1.1.1wwwwwwwwwwwwwww and 1.1.1.1.1xxxxxxxxxxxxxxx are sometimes
    specified by the customer or granted with customer approval.

    1.  ### Vibration test

        a.  Vibration testing shall be conducted at the pressure
            condition corresponding to the maximum predicted vibration
            environment.

        b.  Operational conditions (e.g. fluid density, and filling
            ratio) shall be taken into account in the test
            configuration.

    2.  ### Pressure cycling test

        a.  Pressure cycles shall range from zero differential pressure
            > to MDP and back to zero differential pressure for at least
            > 50 cycles or four times the number of planned pressure
            > cycles expected in one service life, whichever is greater.

        b.  Only cycles having a peak operating pressure that creates a
            > liner tensile stress (exceeds the compressive metal liner
            > pre-stress as imposed by the over-wrap, as a result of
            > vessel autofrettage) shall be considered in the life cycle
            > test of composite over-wrapped pressurized hardware.

    3.  ### Design burst pressure test

        a.  During the design burst pressure test, the design burst
            pressure level shall be maintained for 30 seconds as a
            minimum.

        b.  No burst or collapse shall occur prior to the end of the
            design burst pressure application.

    4.  ### Burst test

        a.  The pressure shall be increased until burst occurs.

        b.  The burst pressure shall be recorded.

    <!-- -->

    1.  Acceptance tests
        ----------------

        1.  ### General

            a.  ‘General requirements’ and ‘Accepting testing’
                requirements shall apply in conformance with
                ECSS-E-ST-10-03.

            b.  When an acceptance test is conducted at temperature
                other than temperature expected for the design loads,
                the change of material properties at this temperature
                shall be verified:

-   by adjustment of the pressure and load level, or

-   by analysis, supported by tests on samples or sub-scale articles and
    providing material strength design allowable versus temperature.

    a.  When NDI is performed in the acceptance tests, it shall meet
        clause 5.7.

    b.  When the strength design allowable of the materials depends on
        the fluid to be stored in the flight hardware (e.g. when the
        stored fluid is liquid hydrogen), the change of material
        properties shall be verified:

-   by using this fluid to pressurize the test specimens, or

-   by analysis, supported by tests on samples or sub-scale articles and
    providing material strength design allowable versus fluid
    characteristics.

    1.  ### Proof pressure test

        a.  During the proof pressure test, the load level (i.e.
            pressure level, external load level) shall be maintained for
            5 minutes as minimum.

        b.  The interest for application of external loads in
            combination with internal pressures during testing shall be
            evaluated based on the relative magnitude, the destabilizing
            effect, or both, of stresses due to the external load.

    2.  ### Leak test

        a.  []{#_Ref204581896 .anchor}During the leak test, the pressure
            level shall be maintained at MDP or greater for 30 minutes
            as minimum.

        b.  []{#_Ref204581897 .anchor}For acceptance ‘leakage test’,
            requirements shall be in conformance with ECSS-E-ST-10-03.

1.  Exceptions to the values provided in 1.1.1.1.1kkkkkkkkkkkkkkkk and
    1.1.1.1.1llllllllllllllll are sometimes specified by the customer or
    granted with customer approval.

    1.  Composite over-wrap material characterization
        ---------------------------------------------

        a.  Strength design allowable shall be generated from at least
            one of the following tests:

            1.  elementary testing on samples or coupons, which are
                representative of the characteristics of the hardware;

            2.  bursting of full or sub-scale specimens of different
                configurations, provided that applicability to the full
                scale article is demonstrated by analysis;

            3.  bursting of sub-scale specimens, provided that scaling
                factor is accounted for;

            4.  bursting of full-scale specimens.

        b.  Test results from at least two lots of yarns shall be used
            in the design allowable calculations unless all of the items
            are fabricated from the same lot of material.

        c.  When the composite wall of the pressurized hardware serves
            partially or totally as a permeation barrier (e.g. for CPV
            or CPS), any degradation of the wall due to the contact with
            the stored fluid shall be accounted for in the design
            allowable of material strength.

2.  When in contact with liquid hydrogen, the composite wall can
    experience superficial micro-cracking and degradation of its
    transverse shear and tensile strength.

    1.  Inspection
        ----------

        1.  ### General

            a.  []{#_Ref96938518 .anchor}An inspection plan shall be
                established prior to the start of fabrication.

            b.  For ‘Inspection’ plan, requirements shall be in
                conformance with ECSS-Q-ST-20.

            c.  For ‘Inspection of PFCI’, requirements shall be in
                conformance with ECSS-E-ST-32-01.

            d.  The inspection plan shall specify inspection points
                throughout the program, beginning with material
                procurement, continuing through fabrication, assembly,
                acceptance proof test and operation, and using the
                following techniques:

                1.  procurement of raw materials, in conformance with
                    ECSS-Q-ST-70;

                2.  procurement of mechanical parts in conformance with
                    ECSS-Q-ST-70;

                3.  NDI for detecting mechanical damage or flaw, in
                    conformance with clauses 5.7.2 and ECSS-E-ST-32-08.

            e.  []{#_Ref157592786 .anchor}Acceptance and rejection
                criteria shall be established within the inspection plan
                for each phase of inspection and for each type of
                inspection.

            f.  For ‘Detected defects’ outside of the acceptance
                criteria defined in 1.1.1.1.1tttttttttttttttt,
                requirements shall be in conformance ECSS-E-ST-32-01.

        2.  ### Inspection techniques for composite over-wraps and composites

            a.  After application of composite manufacturing process,
                any composite over-wrapped or composite item of
                pressurized hardware shall be subjected to the following
                inspections:

                1.  visual inspection for detecting impact damage,

                2.  state-of-the-art NDI techniques for inspecting
                    mechanical damage or flaw induced on the composite.

            b.  Visual inspection shall be performed by inspectors, who
                have been trained to detect visible damage on composite
                or composite over-wrapped pressurized hardware involving
                the use of actual damaged hardware.

            c.  The NDI procedures are based on using multiple NDI
                methods to perform survey inspections or diagnostic
                inspections as follows:

                1.  survey NDI inspections shall be conducted when the
                    location of the potential damage or flaw zone is
                    unknown;

                2.  diagnostic NDI inspections shall be performed within
                    a localized suspect zone to characterize the type
                    and extent of the damage or flaw.

            d.  All NDI techniques, whether used as a single inspection
                technique or as a combination of methods, shall have the
                capability to detect impact or flaw that can cause the
                composite over-wrapped or composite pressurized hardware
                to fail.

            e.  For ‘NDI for composite and bonded parts’, requirements
                shall be in conformance with ECSS-E-ST-32-01.

 Bibliography

  -------------- --------------------------------------------------------------------
  ECSS-S-ST-00   ECSS system - Description, implementation and general requirements
  -------------- --------------------------------------------------------------------
