ECSS-E-ST-33-01C6 March 2009Space engineering

Mechanisms

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐E‐ST‐33‐01  Working  Group,  reviewed  by  the  ECSS 

- Executive Secretariat and approved by the ECSS Technical Authority. 

- Disclaimer

- ECSS does not provide any warranty whatsoever, whether expressed, implied, or statutory, including, 

- but not limited to, any warranty of merchantability or fitness for a particular purpose or any warranty 

- that the contents of the item are error‐free. In no respect shall ECSS incur any liability for any damages, 

- including, but not limited to, direct, indirect, special, or consequential damages arising out of, resulting 

- from,  or  in  any  way  connected  to  the  use  of  this  Standard,  whether  or  not  based  upon  warranty, 

- business agreement, tort, or otherwise; whether or not injury was sustained by persons or property or 

- otherwise; and whether or not loss was sustained from, or arose out of, the results of, the item, or any 

- services that may be provided by ECSS. 

- Published by:  

- Copyright:

ESA Requirements and Standards Division 

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2009 © by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐E‐30 Part 3A </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐33‐01B </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐33‐01C  6 March 2009 </td>
		<td>Second issue  The following is a summary of changes between ECSS‐E‐30 Part 3A and  the present issue:  •  Complete review, restructuring and rewording of standard to be in line  with ECSS drafting rules and formatting  •  Addition of DRDs  •  Deletion of the Tailoring information formerly contained in Annex A  •  Harmonization of the standard with other ECSS standards  •  Review and update of cross‐references to other ECSS standards   </td>
	</tr>
</table>

3 ECSS‐E‐ST‐33‐01C 6 March 2009 Table of contents- Change log.................................................................................................................3

- Introduction................................................................................................................6

- 1 Scope.......................................................................................................................7

- 2 Normative references.............................................................................................8

- 3 Terms, definitions and abbreviated terms..........................................................10

- 3.1  Terms from other standards .....................................................................................10

- 3.2  Terms specific to the present standard ....................................................................10

- 3.3  Abbreviated terms ....................................................................................................12

- 4 Requirements........................................................................................................14

- 4.1  Overview ..................................................................................................................14

- 4.2  General requirements...............................................................................................14

4.2.1  Overview.....................................................................................................144.2.2  Mission specific requirements ....................................................................144.2.3  Units ...........................................................................................................154.2.4

Product characteristics ...............................................................................154.2.5  Reliability and redundancy .........................................................................16Flushing and purging..................................................................................174.2.6

- 4.3  Mission and environments........................................................................................17

- 4.4  Functional.................................................................................................................18

4.4.1

System performance ..................................................................................184.4.2  Mechanism function....................................................................................18- 4.5  Constraints ...............................................................................................................18

4.5.1  Overview.....................................................................................................184.5.2  Materials.....................................................................................................184.5.3  Operational constraints...............................................................................20Interfaces..................................................................................................................204.6.1  Overview.....................................................................................................20Thermo-mechanical interfaces ...................................................................204.6.2

- 4.6

4 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 - 4.7  Design requirements ................................................................................................21

4.7.1  Overview.....................................................................................................214.7.2  General design ...........................................................................................214.7.3

Tribology.....................................................................................................214.7.4

Thermal control...........................................................................................244.7.5  Mechanical design and sizing.....................................................................26Pyrotechnics...............................................................................................354.7.6

4.7.7

Electrical and electronic..............................................................................354.7.8  Open-loop and closed-loop control system for mechanisms......................37- 4.8  Verification................................................................................................................39

4.8.1  General.......................................................................................................394.8.2

Verification by analysis...............................................................................39Verification by test ......................................................................................444.8.3

- 4.9  Production and manufacturing .................................................................................50

4.9.1  Manufacturing process ...............................................................................504.9.2  Manufacturing drawings .............................................................................514.9.3

Assembly....................................................................................................51- 4.10  Deliverables..............................................................................................................51

- Annex A (normative) Specific mechanism specification (SMS) - DRD ...............52

- Annex B (normative) Mechanism design description (MDD) - DRD....................56

- Annex C (normative) Mechanism analytical verification (MAV) - DRD................58

- Annex D (normative)  Mechanism user manual (MUM) - DRD .............................60

- Annex E (informative) Documentation technical items........................................64

- Bibliography.............................................................................................................65

- Tables

- Table 4-1: Outgassing limits...................................................................................................23

- Table 4-2: Minimum uncertainty factors .................................................................................28

- Table 4-3: Life test duration factors........................................................................................48

## Table 4-4: Examples of lifetime to be demonstrated by test ..................................................48

- Table E-1 : Documentation technical items............................................................................64

 

5 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 IntroductionThis  document  has  been  established  to  provide  mechanism  engineering  teams with a set of requirements, design rules and guidelines based on the state of the art knowledge and experience in the field of space mechanisms. 

The  use  of  this  document  helps  mechanisms  developers  to  establish  generic mechanisms designs and to derive application specific requirements. 

The  main  objectives  are  to  achieve  reliable  operation  of  space  mechanisms  in orbit  and  to  prevent  anomalies  during  the  development  phase  influencing schedule and cost efficiency of space programmes. 

6 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 ScopeThis  Standard  specifies  the  requirements  applicable  to  the  concept  definition, design,  analysis,  development,  production,  test  verification  and 

in‐orbit operation of space mechanisms on spacecraft and payloads in order to meet the mission performance requirements. 

This version of the standard has not been produced with the objective to cover also  the  requirements  for  mechanisms  on  launchers.  Applicability  of  the requirements  contained  in  this  current  version  of  the  standard  to  launcher mechanisms is a decision left to the individual launcher project. 

Requirements  in  this  Standard  are  defined  in  terms  of  what  shall  be accomplished, rather than in terms of how to organise and perform the necessary work. This allows existing organizational structures and methods to be applied where  they  are  effective,  and  for  the  structures  and  methods  to  evolve  as necessary without rewriting the standards. 

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

7 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Normative referencesThe following normative documents contain provisions which, through reference in  this  text,  constitute  provisions  of  this  ECSS  standard.  For  dated  references, subsequent amendments to or revisions of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the most recent editions of the normative documents  indicated  below.  For  undated  references  the  latest  edition  of  the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐E‐ST‐10‐02 

ECSS‐E‐ST‐20 

ECSS‐E‐ST‐20‐06 

ECSS‐E‐ST‐20‐07 

ECSS‐E‐ST‐31 

ECSS‐E‐ST‐32 

ECSS‐E‐ST‐32‐10 

ECSS‐E‐ST‐33‐11 

ECSS‐Q‐ST‐30 

ECSS‐Q‐ST‐40 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐70‐36 

ECSS‐Q‐ST‐70‐37 

ECSS‐Q‐ST‐70‐71 

ISO 76, Edition 2, 

Amendment 1  

ISO 128 

ISO 677 

ECSS system — Glossary of terms 

Space engineering – Verification 

Space engineering – Electrical and electronic 

Space engineering – Spacecraft charging 

Space engineering – Electromagnetic compatibility Space engineering – Thermal control general 

requirements 

Space engineering ‐ Structural 

Space engineering – Structural factors of safety for spaceflight hardware 

Space engineering – Explosive systems and devices Space product assurance ‐ Dependability 

Space product assurance – Safety 

Space product assurance – material, mechanical 

part and process 

Space product assurance – Material selection for 

controlling stress corrosion cracking 

Space product assurance – Determination of the 

susceptibility of metals to stress corrosion cracking Space product assurance – Data for selection of 

space materials and processes 

Rolling bearings – Static load rating 

Technical drawings 

Straight bevel gears for general engineering and for heavy engineering – Basic rack 

8 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Straight bevel gears for general engineering and for heavy engineering – Modules and diametral pitches Calculation of the load capacity of spur and helical gears — Part 1: Basic principles, introduction and general influence factors 

Calculation of the load capacity of spur and helical gears — Part 2: Calculation of surface durability 

(pitting) 

Calculation of the load capacity of spur and helical gears — Part 3: Calculation of tooth bending 

strength 

 

ISO 678 

ISO 6336‐1 

ISO 6336‐2 

ISO 6336‐3 

 

 

9 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For  the  purpose  of  this  Standard,  the  term  and  definition  from  ECSS‐S‐ST‐00‐01 apply, and in particular the following: 

interface 

- 3.2  Terms specific to the present standard

actuator

3.2.1

component that performs the moving function of a mechanism 

NOTE   An  actuator  can  be  either  an  electric  motor,  or any  other  mechanical  (e.g.  spring)  or  electric component or part providing the torque or force for the motion of the mechanism. 

cleanliness

3.2.2

level  in  both  particulate  contamination  and  molecular  contamination  that contaminates the part or assembly 

component

3.2.3

assembly  or  any  combination  of  parts,  subassemblies  and  assemblies,  and assemblies mounted together and normally capable of independent operation in a variety of situations 

control system

3.2.4

system  (open  or  closed  loop)  which  controls  the  relative  motion  of  the mechanism 

3.2.5

torque at the mechanism or actuator output  

## deliverable output torque (TL )

NOTE 1  The  deliverable  output  torque  or  force  can  be specified  by  the  customer  for  an  undefined purpose and not affect the actual performance of the mechanism. 

10 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 2  For  example:  A  theoretical  torque  or  force  of  a robotic  mechanism  (service  tool)  for  which  no specific function except torque or force provision can  be  specified  at  an  early  stage  in  the  project development. 

3.2.6

force at the mechanism or actuator output  

## deliverable output force (FL)

elementary function

3.2.7

lowest level function 

NOTE 

For  example:  One  degree  of  freedom  (rotation and  translation),  torque  or  force  generation, sensing. 

3.2.8

force to accelerate the mass 

## inertial resistance force (FD)

3.2.9

torque to accelerate the inertia 

## inertial resistance torque(TD)

fasteners

3.2.10

part used to provide attachment of two or more separate parts, components or assemblies  

NOTE 

For  example:  Fasteners  have  the  function  of locking  the  parts  together  and  providing  the structural load path between the parts or, if used as  a  securing  part,  to  ensure  proper  locating  of the parts to be secured. 

flushing or purging

3.2.11

control  of  the  mechanism  environment  by  enclosing  the  mechanism  in  specific gaseous  or  fluid  media  which  are  surrounding,  passing  over  or  through  the mechanism 

latching or locking

3.2.12

intentional  constraining  of  one  or  more  previously  unconstrained  degrees  of freedom which cannot be released without specific action 

lubrication

3.2.13

use  of  specific  material  surface  properties  or  an  applied  material  between  two contacting or moving surfaces in order to reduce friction, wear or adhesion 

mechanism

3.2.14

assembly of components that are linked together to enable a relative motion 11 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 off-loading

3.2.15

complete or partial unloading of a part or assembly from an initial pre‐load NOTE   Off‐loading  is  usually  employed  so  as  not  to expose a mechanisms part or assembly to launch loads or other induced loads. 

phase margin

3.2.16

indicator for the stability of dynamic control systems 

positively locked

3.2.17

form‐locked into a defined position from which release can only be obtained by application of a specific actuation force 

primary function

3.2.18

high level function  

NOTE 

For  example:  To  hold,  to  release,  to  deploy,  to track, and to point. 

3.2.19

threaded fastener

fastener with a threaded portion  

NOTE 

For example: Screws, bolts and studs. 

tribology

3.2.20

discipline that deals with the design, friction, wear and lubrication of interacting surfaces in relative motion to each other 

venting

3.2.21

compensation  of  the  internal  mechanism  pressure  environment  with  its surrounding pressure environment  

NOTE 

For  example:  Use  of  dedicated  venting  holes  or passages 

- 3.3  Abbreviated terms

For  the  purpose  of  this  Standard,  the  abbreviated  terms  from  ECSS‐S‐ST‐00‐01 and the following apply: 

 

Abbreviation 

A/D 

AC 

COG 

CVCM 

D/A 

Meaning 

analogue to digital  

alternating current 

centre of gravity 

collected volatile condensable material 

digital to analogue 

12 ![Im0](images/Im0)

![Im0](images/Im0)

DC 

EMC 

ESD 

F 

FD

FL 

FMECA 

Fmin 

FOS 

FR 

GSE 

HA 

HD 

HV 

HY 

I 

I/F 

LEO 

M 

MAV 

MDD 

MUM 

MLI 

MOI 

MOS 

MS 

n.a.  

SMS 

RML 

S 

S/C 

T 

TD 

TL

Tmin 

TML 

 

ECSS‐E‐ST‐33‐01C 6 March 2009 direct current 

electromagnetic compatibility 

electrostatic discharge 

actuation force 

inertial resistance force  

deliverable output force 

failure mode effects and criticality analysis 

minimum actuator force required 

factor of safety 

friction torque or force 

ground support equipment 

harness and other torque or force resistances 

adhesion torque or force 

hardness Vickers 

hysteresis torque or force 

inertia resistance (linear or angular) 

Interface 

low Earth orbit 

mass  

mechanism analytical verification 

mechanism design description 

mechanism user manual 

multi‐layer insulation 

moment of inertia 

margin of safety 

strength safety margin 

not applicable 

specific mechanism specification 

recovered mass loss 

spring force 

spacecraft 

actuation torque 

inertial resistance torque 

deliverable output torque 

minimum actuator torque required 

total mass loss 

13 ECSS‐E‐ST‐33‐01C 6 March 2009 Requirements- 4.1  Overview

This  Standard  addresses  the  requirements  related  to  the  generic  aspects  of  the engineering  steps  for  the  various  engineering  disciplines  involved  in  the achievement of the specified space mechanism performance.  

The following requirements are identified considering interfaces and interactions of  mechanisms  with  those  disciplines:  thermal  control,  structures,  functional operations,  materials  and  parts,  pyrotechnics,  propulsion,  electrical  and electronics,  and  servo‐control  interactions.  Where  interactions  with  other European  space  regulation  are  identified,  reference  is  made  to  the  related regulation. 

- 4.2  General requirements

4.2.1  Overview

This  group  of  requirements  covers  the  interaction  of  mechanisms  engineering with project management, processes, parts and components, product assurance, and the related requirements affecting the conceptual definition, design, sizing, analysis, development, and hardware production of mechanisms. 

In view of the criticality of space mechanisms, which are often potential mission critical single point failures, particular attention is placed upon the reliability and redundancy of space mechanisms (see clause 4.2.5). 

4.2.2  Mission specific requirements

a.

A dedicated specific mechanism specification (SMS) shall be established in conformance  with  Annex  A  for  each  individual  mechanism  in  a  project, and agreed by the customer. 

NOTE 

identifies  all  specific The  SMS  specification 

requirements  for  a  specific  mechanism  in  a project,  that  are  not  covered  by  the  present standard. 

14 ![Im0](images/Im0)

![Im0](images/Im0)

Units

ECSS‐E‐ST‐33‐01C 6 March 2009 SI‐units and associated symbols system shall be used. 

4.2.3

a.

4.2.4

Product characteristics

4.2.4.1  Marking and labelling

4.2.4.1.1  Specific identification

a.

The  identification  of  delivered  pieces  of  hardware,  parts,  components, sub‐assemblies and assemblies shall carry at least the equipment title. NOTE 1  For  the  identification  of  pieces  of  hardware, parts, 

and assemblies of the mechanism, see clause 5.3.1.5 of ECSS‐M‐ST‐40. 

sub‐assemblies, 

components, 

NOTE 2  The identification can be removable. 

NOTE 3  The  identification  number  and  the  equipment title can be defined by the contracting authority. 

4.2.4.1.2  Marking

a.  Marking shall be applied on non‐functional surfaces. 

b.

Bearings shall not be marked by the use of vibro‐etch marks on the lateral faces of the bearing races. 

NOTE 

Etched marks on the lateral faces of the bearing races  affect  the  mounting  tolerances  of  the bearing 

the  bearing’s tribological performance characteristics. 

the  housing  and 

in 

Parts and components

4.2.4.2

a.

Existing  parts  and  components  used  in  mechanisms  shall  have  been previously  qualified  for 

to  a qualification procedure approved by the customer. 

intended  application  according 

the 

NOTE 

Existing  parts  and  components  relate  to  parts and  components 

that  were  not  specifically developed for this specific application and cover commercially 

off‐the‐shelf hardware. 

available 

and 

b.

c.

Existing  parts  and  components  used  in  mechanisms  should  have  been previously qualified at part or component level. 

Flight proven parts and components should be used. 

NOTE 

For  the  selection  of  not‐flight  proven  parts  and components, see ECSS‐Q‐ST‐60 for EEE parts and ECSS‐Q‐ST‐70 for materials and parts. 

15 ![Im0](images/Im0)

Interchangeability

ECSS‐E‐ST‐33‐01C 6 March 2009 All items having the same identification number shall be functionally and dimensionally interchangeable. 

4.2.4.3

a.

4.2.4.4  Maintainability

a.

The mechanism should be designed to be maintenance free during storage and ground life. 

If the design is not maintenance free, the maintenance requirements shall be documented in the SMS, justified, agreed by the customer. 

If ground maintenance during storage or ground operation is not avoided, the maintenance procedures shall be provided. 

b.

c.

4.2.5

Reliability and redundancy

4.2.5.1  Reliability

a.

b.

c.

2.

For all mechanisms, which are critical to mission success, conformance to the  specified  reliability  figure  shall  be  demonstrated  according  to  the following methods: 

1.

electronic  components:  by  parts  count  as  a  minimum  or  other methods approved by the customer; 

mechanical parts: by stress analysis or other methods approved by the customer; 

mechanical limited‐life  by life test approved by the customer. 

3.

For non‐critical mechanisms, conformance to the reliability figure shall be demonstrated  by  simplified  methods  (e.g.  parts  count  or  other  methods accepted by the customer). 

NOTE 

The  methods  to  achieve  by  design,  derive  by analysis,  and  demonstrate  by  test  the  specified reliability figures are presented in ECSS‐Q‐ST‐30. 

Failure of one part or element shall not result in consequential damage to the equipment or other spacecraft components. 

For structural reliability aspects ECSS‐E‐ST‐32 shall apply. 

d.

e.  Where structural failure of a mechanism can cause a catastrophic or critical hazardous  event,  fasteners  and  load  carrying  paths  within  mechanisms shall be designed in conformance with fracture control principles.  

NOTE   Definitions of catastrophic and critical hazardous events  are  provided  in  ECSS‐Q‐ST‐40.  Fracture control  principles  are  covered  in  ECSS‐E‐ST‐32‐

01. 

4.2.5.2  Redundancy

a.

During the design of the mechanism, all single point failure modes shall be identified. 

16 ECSS‐E‐ST‐33‐01C 6 March 2009 b.

c.

d.

All single points of failure should be eliminated by redundant components. If single points of failure cannot be avoided, they shall be justified by the supplier and approved by the customer. 

Redundancy concepts shall be agreed by the customer. 

NOTE 

Redundancy  concepts  are  selected  to  minimize the  number  of  single  points  of  failure  and  to conform to the reliability requirements. 

f.

e.  Where  a  single  point  failure  mode  is  identified  and  redundancy  is  not provided, compliance with the reliability, availability and maintainability requirements specified in ECSS‐Q‐ST‐30 shall be demonstrated.  

Unless redundancy is achieved by the provision of a complete redundant mechanism,  active  elements  of  mechanisms,  such  as  sensors,  motor windings, brushes, actuators, switches and electronics, shall be redundant. Failure  of  one  element  or  part  shall  not  prevent  the  other  redundant element or part from performing its intended function, nor the mechanism from  meeting  its  performance  requirements  specified  in  the  specific mechanism specification. 

g.

NOTE   High‐reliability  of  a  mechanism 

can  be incorporated in a design by including component redundancy  or  high  design  margins.  The  aim  is to  deliver  a  design  which  is  single  failure tolerant. 

Flushing and purging

4.2.6

a.

If operating the mechanism in air is detrimental to the performance of the mechanism over its complete mission, means for flushing the critical parts with an inert clean dry gas shall be provided. 

NOTE 

Example  of  detrimental  cause  to  operate  the mechanism in air is the presence of moisture or other deleterious contamination. 

b.

Only lubricants qualified in respect to the residual humidity of the dry gas shall be used. 

- 4.3  Mission and environments

a.

The mechanism engineering shall consider every mission phase identified for  the  specific  space  programme  and  conform  to  the  related  mission requirements and environmental constraints. 

NOTE 

The  mission  starts  with  on‐ground  life  of  the mechanisms  after  assembly  and  is  completed  at the end of operational life of the space system. 

17 ![Im0](images/Im0)

![Im0](images/Im0)

- 4.4  Functional

ECSS‐E‐ST‐33‐01C 6 March 2009 System performance

4.4.1

a.

The  mechanism  functional  performance  shall  conform  to  the  system performance requirements. 

4.4.2  Mechanism function

a.

The  kinematic  requirements  applicable  to  each  position  change  shall  be specified. 

NOTE 

For  example,  position  over  time,  velocity  and acceleration.  

b.  Mechanical  interface,  position  accuracy  or  velocity  tolerances  shall  be c.

d.

specified and verified that they conform to the functional needs. 

The envelope of movement for each moving part shall be defined. 

The  movement  of  each  part  shall  ensure  that  there  is  no  mechanical interference  with  any  other  part  of  the  mechanism,  the  spacecraft,  the payload or the launcher. 

- 4.5  Constraints

4.5.1  Overview

This  group  of  requirements  covers  the  constraints  to  which  mechanisms  are designed, manufactured and operated. 

For the physical constraints, it is important to ensure that the requirements for climatic protection and for sterilization are defined in the SMS, as identified in A.2.1<4>. 

4.5.2  Materials

4.5.2.1  Material selection

a.  Materials shall be selected in conformance with ECSS‐Q‐ST‐70 clause 5, or be verified that they conform to requirements, approved by the customer. NOTE 1  For  general  requirements  on  materials  used  for space  mechanisms,  see  ECSS‐E‐ST‐32‐08.  The material  requirements  in  4.5.2.2  to  4.5.2.7  are specific to mechanisms. 

NOTE  2  For selection of materials, see ECSS‐Q‐ST‐70‐71. 

NOTE  3  For additional requirements relating to tribology, see clause 4.7.3. 

18 ECSS‐E‐ST‐33‐01C 6 March 2009 4.5.2.2  Corrosion

a.

For corrosion, ECSS‐Q‐ST‐70‐71 clause “Chemical (corrosion)” shall apply. 4.5.2.3  Dissimilar metals

a.

For dissimilar metals, ECSS‐Q‐ST‐70 clause 5.1.12 “Galvanic compatibility” shall apply.  

NOTE 

To  fulfil  requirement  4.5.2.3a,  dissimilar  metals should  not  be  used  in  contact  with  each  other, unless  they  have  been  treated  in  accordance  to 4.5.2.3b or are resistant. 

b.  Materials treatments to prevent galvanic and electrolytic corrosion shall be approved by the customer. 

Stress corrosion cracking

4.5.2.4

a.  Materials shall be selected as specified in ECSS‐Q‐ST‐70‐36. 

b.  Materials  with  unknown  characteristics  shall  be  tested  in  conformance with ECSS‐Q‐ST‐70‐37. 

ECSS‐Q‐ST‐70‐71 clause “Stress corrosion resistance” shall apply. 

c.

Fungus protection

For  fungus  protection,  ECSS‐Q‐ST‐70‐71  clause  “Bacterial  and  fungus growth” shall apply. 

4.5.2.5

a.

4.5.2.6

a.

Flammable, toxic and unstable materials

For  flammable  materials,  ECSS‐Q‐ST‐70‐71  clause  “Flammability”  shall apply. 

For toxic materials, ECSS‐Q‐ST‐70‐71 clause “Offgassing and toxicity” shall apply. 

In  manned  space  systems,  flammable,  toxic  and  unstable  materials  shall not be used. 

b.

c.

Induced emissions (stray light protection)

4.5.2.7

a.  Materials  and  their  coatings  shall  be  selected  so  that  their  surface properties  reduce  induced  emissions  (stray  light  and  others)  below  the levels of stray light specified in the SMS. 

4.5.2.8  Radiation

a.

The exposure to radiation shall not degrade the functional performance of the mechanism below the minimum functional performances specified in the SMS, over the complete mission. 

ECSS‐Q‐ST‐70‐71 clause “Radiation” shall apply. 

b.

19 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 4.5.2.9  Atomic oxygen

a.

The  exposure  to  atomic  oxygen  shall  not  degrade  the  functional performance  of 

the  minimum 

functional performances specified in the SMS, over the complete mission. 

ECSS‐Q‐ST‐70‐71 clause “Atomic oxygen” shall apply. 

the  mechanism  below 

b.

b.

c.

4.5.2.10  Fluid compatibility

a.

For fluid compatibility, ECSS‐Q‐ST‐70‐71 clause “Fluid compatibility” shall apply. 

4.5.3  Operational constraints

a.

The  mechanism  should  not  impose  any  operational  constraints  on  the spacecraft and mission. 

If  operational  constraints  are  imposed  by  the  mechanism,  they  shall  be identified, justified and approved by the customer. 

All  operational  constraints  shall  be  documented  in  the  mechanism  user manual. 

NOTE 

For the contents of the user manual, see Annex D. d.  Mechanisms moving with limited oscillatory travel shall be identified. e.

All  oscillatory  rolling  elements  should  be  exercised  over  a  complete revolution  at  regular  intervals,  according  to  an  operational  procedure agreed by the customer. 

NOTE 

Examples of oscillatory rolling elements are: ball bearing and nuts. 

f.

Operational procedures to exercise the mechanism beyond the oscillatory travel range shall be defined. 

- 4.6

Interfaces

4.6.1  Overview

This  group  of  requirements  covers  the  interfaces  of  mechanisms  on  spacecraft and  payload.  Most  of  the  interfaces  requirements  are  application  specific,  and therefore are covered by the SMS, as identified in A.2.1<5>. 

4.6.2

a.

Thermo-mechanical interfaces

Thermo‐mechanical  interfaces  shall  be  designed  to  take  into  account  the stresses  induced  by  the  structure  between  the  mechanism  and  its  I/F attachment points. 

20 ![Im0](images/Im0)

![Im0](images/Im0)

- 4.7  Design requirements

ECSS‐E‐ST‐33‐01C 6 March 2009 4.7.1  Overview

This clause covers general design, tribology, thermal control, mechanical design and sizing, pyrotechnics, electric and electronics, and control engineering. 

The  requirements  for  tribology  (see  clause  4.7.3)  cover  the  tribological  related issues  of  mechanisms  on  the  spacecraft  and  payload.  The  tribology  of  surfaces that  separate  or  move  relative  to  one  another  play  a  key  function  in  the conceptual  definition,  design,  analysis,  test  verification,  launch,  and  in‐orbit performance of the mechanisms. 

The thermal requirements (see clause 4.7.4) cover the interaction of mechanisms engineering  with  thermal  control  and 

its  related  requirements  affecting mechanisms  engineering.  General  thermal  control  requirements  are  covered  in ECSS‐E‐ST‐31. 

The  requirements  for  mechanical  design  and  sizing  (see  clause  4.7.5)  cover  the overall  conceptual  design,  the  mechanical  sizing  of  parts,  components  and assemblies, and the detailed design definition of mechanisms. General structural requirements,  including  design  loads  (for  example,  pyrotechnical  shock),  are covered in ECSS‐E‐ST‐32. 

The  requirements  for  electrical  and  electronics  (see  clause  4.7.7)  cover  the interaction of mechanisms engineering with electrical and electronic engineering and 

its  related  requirements  affecting  mechanisms  engineering.  General requirements  for  electrical  and  electronic  are  covered  in  ECSS‐E‐ST‐20.  If  no electrical or electronic provisions are applied on the mechanism, the applicability of  ECSS‐E‐ST‐20  is  limited  to  the  potential  compatibility  requirements  of mechanical systems with electrical and electronic systems. 

4.7.2  General design

a.

The  mechanism  design  shall  be  compatible  with  operation  on  ground  in ambient and thermal vacuum conditions.  

4.7.3

Tribology

4.7.3.1  General

a.  Mechanisms  shall  be  designed  with  a  lubrication  function  between surfaces  in  relative  motion  in  order  to  ensure  they  conform  to  the mechanism performance requirements specified in the specific mechanism specification, throughout the specified lifetime. 

NOTE 

The  lubrication  function  aims  to  provide  the motorization margins and minimize wear. 

b.  Mechanisms shall use only lubricants or lubricating surfaces qualified for the mission. 

NOTE 1  For  example,  environment, 

lifetime,  contact cycles, pressure, 

temperature,  number  of 

21 ECSS‐E‐ST‐33‐01C 6 March 2009 minimum  and  maximum  velocity  of  surfaces  in relative motion. 

NOTE 2  For space environment, see ECSS‐E‐ST‐10‐04. 

NOTE 3  Vacuum  is  one  of  the  main  concerns  regarding lubrication. 

c.

d.

e.

f.

It shall be verified that the degradation of the lubricant in the on‐ground and  in‐orbit  environments  does  not  lead  to  a  mechanism  performance degradation below the limits specified in the SMS. 

NOTE 

Examples of such degradation are friction, wear and lubricant performance variability. 

The use of sliding surfaces shall be avoided.  

If requirement 4.7.3.1d cannot be met, sliding surfaces are used one of the surfaces  shall  be  hard  and  the  other  shall  be  lubricated  or  shall  be composed of a self‐lubricating material. 

NOTE 

Example  of  self‐lubricating  material:  polyimide resins. 

Metal  to  metal  tribological  contacts  should  be  composed  of  dissimilar materials, in conformance with 4.5.2.3. 

g.  Metal to metal tribological sliding contacts shall be composed of dissimilar h.

i.

j.

materials in conformance with 4.5.2.3. 

Prior to the application of lubricant and in order to facilitate adhesion or wetting of lubricant on the substrate surface, the surfaces shall be cleaned in conformance with a procedure approved by the customer. 

The cleaning of the surfaces prior to lubricant application shall not degrade the lubricating action. 

The lubricant shall conform to the molecular and particulate contamination requirements specified for the entire mission. 

NOTE 

For molecular and particulate contamination, see ECSS‐Q‐ST‐70‐01. 

4.7.3.2  Dry lubrication

a.

During  the  lubrication  of  mechanism  tribological  surfaces,  samples  of representative material, surface roughness, surface cleanliness and surface orientation  shall  be  co‐deposited  in  each  process  run  with  the  flight components so that verification checks can be performed. 

The  thickness  and  adhesion  of  the  lubricant  on  samples  defined  in requirement 4.7.3.2a shall be verified. 

The  dry  lubricant  application  process  shall  be  verified  with  respect  to lubricant performance and repeatability. 

b.

c.

4.7.3.3

Fluid lubrication

4.7.3.3.1  Amount of fluid lubricant

a.

The quantity of lubricant used shall be determined. 

22 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 

This determination allows quantifying a surplus of lubricant at the end of the total lifetime of the mechanism. 

b.

c.

The  quantity  of  lubricant  shall  take  into  account  outgassing,  creep  and other sources of absorption or degradation.  

The  effect  of  exposure  to  on‐ground  storage  and  related  gravity  effects, and other ground or in‐orbit accelerations on lubricant distribution shall be validated. 

4.7.3.3.2  Outgassing

a.

The  outgassing  rate  of  fluid  lubricants  shall  be  measured  by  a  screening test approved by the customer. 

NOTE 

See ECSS‐Q‐ST‐70‐02. 

b.

The  limits  of  acceptance  for  material  outgassing  shall  be  in  conformance with Table 4‐1. 

NOTE 

The  limits  in  Table  4‐1  can  be  more  stringent  if the materials concerned are later used in critical areas.  The  use  of  materials  conforming  to  the limits stated in Table 4‐1 does not ensure that the spacecraft 

remains uncontaminated.  Specific 

for mission  involving  advanced  optical  instruments are  covered  by  the  SMS,  as 

in A.2.1<6>c. 

requirements 

identified 

system  or 

component 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Application </td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>General applications </td>
		<td>< 1 </td>
		<td>n.a. </td>
		<td>< 0,1 </td>
	</tr>
	<tr align="center">
		<td>Optical device applications </td>
		<td>n.a. </td>
		<td>< 0,1 </td>
		<td>< 0,01 </td>
	</tr>
</table>

 

4.7.3.3.3  Anti-creep barriers

a.

Anti‐creep barriers shall be used to avoid migration of fluid lubricants to the external sensitive equipment agreed by the customer. 

NOTE 

It is also important to use the anti‐creep barriers for sensitive equipment within the mechanism. 

b.

c.

Anti‐creep  barriers  shall  be  used  when  migration  of  fluids  lubricants causes  a  change  of  the  lubricant  amount  on  the  parts  to  be  lubricated resulting  in  mechanism  performance  degradation  below  the  limits specified in the SMS. 

The integrity of the anti‐creep barrier shall be verifiable by indicators. NOTE 

For example, UV‐detectable. 

23 ECSS‐E‐ST‐33‐01C 6 March 2009 4.7.3.4

Tribological components

4.7.3.4.1  Life

a.

The  life  of  tribological  components  shall  be  verified  under  worst  case ground and flight conditions. 

4.7.3.4.2  Bearing pre-loading

a.

Ball  bearings  shall  be  pre‐loaded  with  a  load  calculated  in  order  to withstand the mechanical environment during launch and throughout the mission.  

The calculation specified in requirement 4.7.3.4.2a shall be made available to the customer. 

Pre‐loading  should  be  applied  by  solid  pre‐load  or  flexible  pre‐load produced by loading techniques without sliding at the bearing mounting interfaces. 

If  pre‐loading  is  not  applied  by  4.7.3.4.2c  solutions,  sliding  shall  be facilitated  by  a  lubricated  sliding  sleeve,  bush  or  dedicated  tribological coating. 

If  bearing  gapping  occurs  during  vibration,  adequacy  of  lubricant  and potential  consequential  mechanisms  damage  or  degradation  due  to bearing components or shaft motion shall be demonstrated to conform to the specified functional performance and lifetime. 

Any set pre‐load at component level shall be measured. 

Bearing preload should be measured after final mechanism assembly. If bearing preload is not measured after final mechanism assembly, it shall be assessed by means of measurements approved by the customer. 

If bearing preload can be affected by the running‐in process, the preload shall be confirmed after running‐in.  

b.

c.

d.

e.

f.

g.

h.

i.

4.7.3.4.3  Mechanical cables

a.  Mechanical cables under friction used on moving parts or assemblies shall be lubricated in conformance with 4.7.3.1, 4.7.3.2 and 4.7.3.3. 

4.7.4

Thermal control

Thermal engineering

4.7.4.1

a.

The  mechanism  engineering  shall  conform  to  the  thermal  engineering requirements specified by the customer. 

NOTE 

For thermal control, see ECSS‐E‐ST‐31. 

4.7.4.2  Mechanisms thermal design and sizing

a.

The thermal design of the mechanism shall ensure that all components are maintained within their qualification temperature range under all specified 24 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 b.

c.

d.

e.

Acceptance margin: 5 K above specification 

Qualification margin: 10 K above specification  

ground, test, launch and in‐orbit conditions throughout the lifetime of the mechanism. 

The  mechanism  shall  be  compatible  with  on‐ground  thermal  vacuum testing representative of in‐orbit thermal conditions.  

The  following  minimum  temperature  margins  defined  in  ECSS‐E‐ST‐31 clause 3.2 shall be applied: 

1.

2.

Unless  the  use  of  active  thermal  control  is  previously  agreed  with  the customer, thermal control shall be passive.  

The mechanism design shall take into account the worst‐case combinations (including uncertainties) of: 

1.

2.

3.

4.

extremes of operational and survival steady‐state,  

transient temperatures,  

mechanism heat dissipation, and 

the temperature gradients across the mechanism. 

NOTE 

Failure  to  consider  the  effects  of  differential expansion can lead to a catastrophic failure. 

4.7.4.3  Multi-layer insulation (MLI)

a.  When  using  MLI,  supported  at  discrete  positions  at  the  distance  of  not more than 100 mm, the following shall be provided: 

1.

between  structural  components  and  MLI  hardware  a  minimum clearance of 20 mm (in out‐of‐plane direction to the MLI), 

between  MLI  protected  moving  parts  and  other  MLI  hardware  a minimum clearance of 35 mm (in out‐of‐plane direction to the MLI). 2.

NOTE 

is  relative 

to  moving  parts  of Clearance 

mechanisms or on spacecraft structure close to its moving paths. 

b.

For other design solutions, it shall be verified that clearances with margins, agreed by the customer, are maintained throughout the mission. 

NOTE 

Example  of  such  design  solutions  are  MLI  not supported at discrete positions or MLI supported at  discrete  positions  which  are  more  than  100 mm apart. 

c.

The  MLI  clearance  assessment  shall  take  into  account  the  dynamic envelopes of the MLI during vibration exposure and venting or purging or in orbit environment. 

NOTE 

For example, spin. 

25 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 4.7.5  Mechanical design and sizing

4.7.5.1  General

a.  Mechanisms  shall  be  designed  to  meet  the  mechanical  performance requirements and to withstand the specified environment during handling, transportation,  testing,  storage,  launch  and  operation  in  orbit  for  the specified lifetime. 

4.7.5.2

Structural dimensioning

4.7.5.2.1  General

a.  Mechanisms in their different configurations shall conform to the specified stiffness, strength and safety requirements derived from the launcher and the spacecraft structural requirements. 

4.7.5.2.2  Loads

a.

b.

The load general requirements of ECSS‐E‐ST‐32, shall apply in‐orbit loads. The operational loads shall be added to the in‐orbit loads.  

NOTE   Operational loads are the loads generated by the including operation, 

during 

mechanism 

thermoelastic effects. 

c.

d.

The operational loads of the mechanisms shall be derived according to the functional  dimensioning  requirements  based  on  dynamic  performance analyses or test measurements in worst‐case conditions.  

For the derivation of the operational loads, the related induced reaction of the spacecraft shall be taken into account.  

4.7.5.2.3  Limit loads

a.

The worst‐case condition requirements of ECSS‐E‐ST‐32 clause 4.2.7 shall apply  with  the  following  modifications;  for  cases  where  a  statistical distribution of the loads cannot be demonstrated, the limit loads shall be defined based on the worst‐case conditions. 

NOTE 

Examples of cases where a statistical distribution of 

loads  cannot  be  demonstrated  are mechanisms operating loads. 

the 

4.7.5.2.4  Material allowables

For  the  allowable  A‐values  of  materials,  to  be  used  for  structural  sizing,  see ECSS‐E‐ST‐32, clause 4.5. 

NOTE 

For  metallic  materials,  A‐values  data  can  be found  in  the  latest  version  of  the  document: Metallic  Material  Properties  Development  and Standardisation (MMPDS). 

4.7.5.2.5  Margin of safety (MOS)

a.

For structural margin of safety requirements, ECSS‐E‐ST‐32 shall apply. 26 ![Im0](images/Im0)

![Im0](images/Im0)

c.

ECSS‐E‐ST‐33‐01C 6 March 2009 b.  Mechanisms  shall  be  designed  with  a  positive  margin  of  safety  against yielding  and  against  ultimate  under  all  environmental  and  operational load conditions. 

The  actual  stress  or  load  shall  be  considered  at  their  worst  case qualification level. 

The margin of safety (MOS) shall be derived from stresses or load. 

The  margin  of  safety  (MOS)  shall  employ  the  factors  of  safety  (FOS) identified in clause 4.7.5.2.6. 

The margin of safety (MOS) shall be the smallest of the following values: d.

e.

f.

MOS = (allowable stress limit / (actual stress x FOS)) ‐1, or 

MOS = (allowable load limit / (actual load x FOS)) ‐1 

g.

The margin of safety (MOS) shall be greater than zero. 

4.7.5.2.6  Factors of safety (FOS)

a.

yield stress factor of safety: 

 

ultimate stress factor of safety: 

buckling factor of safety: 

 

minimum fatigue factor (cycles): 

For the structural factors of safety, requirements of ECSS‐E‐ST‐32‐10 shall apply. 

In  the  computation  of  safety  margins  the  following  minimum  factors  of safety shall be used for standard metallic materials: 

1.

2.

3.

4.

Fatigue  verification  shall  take  into  account  thermoelastic  cycles  over  all lifetime. 

Factors of safety for other materials shall be approved by the customer on a case by case basis. 

The following specific factors of safety shall apply: 

1.

2.

For cables, stress factor of safety against rupture 

For stops, shaft shoulders and recesses, against yield 

 1,25 

 

 2

 

1,5 

 

4  

  

 

3 2 b.

c.

d.

e.

 

 

 

 

4.7.5.3

Functional dimensioning (motorization)

4.7.5.3.1  Motorization factors

a.

Actuators shall be sized to provide throughout the operational lifetime and over the full range of travel actuation torques (or forces) in conformance with 4.7.5.3.1d or 4.7.5.3.1e.  

NOTE 1  Example  of  actuators  are  electrical,  mechanical and thermal. 

NOTE 2  Components providing helping torques or forces are treated as motorization. 

b.

To  derive  the  factored  worst‐case  resistive  torques  (or  forces),  the components  of  resistance,  considering  in‐orbit  worst‐case  conditions 27 ECSS‐E‐ST‐33‐01C 6 March 2009 (environmental  effects),  shall  be  multiplied  by  the  minimum  uncertainty factors specified in the resistive component columns of the Table 4‐2. Example  of  such  environmental  effects  are vacuum, temperature, and zero G. 

NOTE 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Component of  resistance </td>
		<td>Symbol </td>
		<td>Theoretical  Factor </td>
		<td>Measured  Factor </td>
	</tr>
	<tr align="center">
		<td>Inertia  </td>
		<td>I </td>
		<td>1,1 </td>
		<td>1,1 </td>
	</tr>
	<tr align="center">
		<td>Spring </td>
		<td>S </td>
		<td>1,2 </td>
		<td>1,2 </td>
	</tr>
	<tr align="center">
		<td>Motor mag. losses </td>
		<td>HM </td>
		<td>1,5 </td>
		<td>1,2 </td>
	</tr>
	<tr align="center">
		<td>Friction </td>
		<td>FR  </td>
		<td>3 </td>
		<td>1,5 </td>
	</tr>
	<tr align="center">
		<td>Hysteresis </td>
		<td>HY </td>
		<td>3 </td>
		<td>1,5 </td>
	</tr>
	<tr align="center">
		<td>Others (Harness) </td>
		<td>HA </td>
		<td>3 </td>
		<td>1,5 </td>
	</tr>
	<tr align="center">
		<td>Adhesion </td>
		<td>HD </td>
		<td>3 </td>
		<td>3 </td>
	</tr>
</table>

The  theoretical  uncertainty  factors  in  Table  4‐2  may  be  reduced  to  the measured factors providing that the worst‐case measured torque or force resistive components are determined by measurement according to a test procedure approved by the customer and demonstrate the adequacy of the uncertainty  factor  with  respect  to  the  dispersions  of  the  resistive component functional performances. 

The minimum actuation torque (Tmin) shall be derived by the equation: ## T

## T25,1)+

Dmin

1,1(2

×=

2,1

5,1

## H

## H

## H

## H

++

+

+

+

+

+

## S

## I

M

D

A

Y

## TL## F

R

where: 

⎯

⎯

in  an 

I  is  the  inertial  torque  applied  to  a  mechanism  subjected  to acceleration 

inertial  frame  of  reference  (e.g.  spinning spacecraft, payload or other). 

TD  is  the  inertial  resistance  torque  caused  by  the  worst‐case acceleration  function  specified  by  the  customer  at  the  mechanism level. 

TL is the deliverable output torque, when specified by the customer. ⎯

The minimum actuation force (Fmin) shall be derived by the equation: 

F

25,1)+

min

1,1(2

×=

2,1

5,1

F

R

H

H

H

H

+

+

+

+

+

+

S

I

M

D

A

Y

FD+FL 

c.

d.

e.

 

where: 

⎯

⎯

in  an 

I  is  the  inertial  force  applied  to  a  mechanism  subjected  to acceleration 

inertial  frame  of  reference  (e.g.  spinning spacecraft, payload or other). 

FD  is  the  inertial  resistance  force  caused  by  the  worst‐case acceleration  function  specified  by  the  customer  at  the  mechanism level. 

28 ECSS‐E‐ST‐33‐01C 6 March 2009 ⎯

FL is the deliverable output force, when specified by the customer. NOTE 1  Margins  against  any  dynamic  coupling  between the  mechanism  and  its  payload  are  not  covered by  the  above  formulae,  and  they  are  addressed on a case by case basis when appropriate. 

NOTE 2  The  inertial  resistance  torque  (TD)  or  force  (FD) (specified by the customer) apply to mechanisms which have a specified acceleration requirement or for which an indirect acceleration requirement can  be  deduced  from  speed,  time  or  other (dynamic) requirements. 

force  requirements  specified 

NOTE 3  When a function of the mechanism is to deliver output  torques  (TL)  or  forces  (FL)  for  further actuation  at  higher  level,  the  output  torque  or force is derived by the customer according to the torque  or 

in 4.7.5.3.1d and 4.7.5.3.1e., taking into account the specified  uncertainty  factors  on  the  individual components  of  resistance  and  applying  a motorization factor of two as presented as :  

HI

H

1,1(2

′+′

+′

×=

DA

HH

I

1,1(2

+′

′+′

×=

DA

where  all  components  of  resistance  in  the  two equations  above  are  related  to  the  customer specific actuation application. 

H

+′

Y

H

+′

Y

F

+′

R

F

+′

R

2,1

2,1

S

+′

S

+′

5,1

5,1

))T

L

F

L

H

+′

M

H

+′

M

f.

The kinetic energy of the moving components, and its effects, shall not be taken into account to meet the specified motorization factor. 

NOTE 

Such  effects  are  acceleration  and  deceleration force and torque of moving components. 

4.7.5.3.2  Actuation torque (or force) dimensioning.

a.

The actuation torque T (or force F ) is the summation of all the actuating components  as  specified  in  the  following  clauses  4.7.5.3.2c.,  4.7.5.3.2d., 4.7.5.3.2e. 

NOTE 

Examples  of  actuating  components  are  electro magnetic,  pneumatic,  active  components,  acting spring, and acting inertia. 

b.

T (or force F) shall be greater or equal than Tmin (or Fmin) as calculated in the clause 4.7.5.3.1. 

c.  When the actuation torque (or force) is supplied by an electronic controlled device,  the  actuation  torque  (or  force)  supplied  by  this  device  shall  be derived considering worst‐case conditions. 

NOTE 1  Example  of  such  electronic  devices  are  an electromagnetic  motor,  or  piezo  actuator,  or pneumatic, or  active components. 

29 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 2  Example  of  such  worst  case  conditions  are supplied voltage, current, and frequency. 

d.  When part of the actuation torque (or force) is provided by inertia means, the actuation torque (or force) supplied by the inertia shall:  

1.

be derived considering worst‐case conditions defined and agreed by the customer.  

be  multiplied  by  the  maximum  uncertainty  factor  of  0,9  and  then comply with the equations in clause 4.7.5.3.1. 

2.

NOTE 

Inertia is calculated in the appropriate reference frame and according to the type of movement. 

f.

e.  When the actuation torque (or force) is supplied by a spring actuator, the actuation  torque  (or  force)  supplied  by  the  spring,  shall  be  derived considering  worst‐case  conditions,  and  be  multiplied  by  the  maximum uncertainty factor of 0,8. 

Spring actuators shall be redundant unless it is 

1.

2.

agreed by the customer,  

verified  by  analysis  and  test  that  the  spring  sizing  and  functional performance  characteristics  meet  the  specified  reliability  of  the mission, and 

verified that a spring failure can not cause any catastrophic, critical or  major  hazardous  event  in  conformance  with  ECSS‐Q‐ST‐40, clause 6.4. 

3.

g.

h.

Actuating torques or forces based on hysteresis, harness generated, or any item  whose  primary  function  is  not  to  provide  torques  or  forces,  should not be used as a motorization source. 

If torques (or forces) based on hysteresis, harness generated, or any item whose  primary  function  is  not  to  provide  torques  or  forces  are  used  as motorization sources their use shall: 

1.

2.

3.

be justified,  

agreed by the customer, and  

the adequacy of the uncertainty factor with respect to the dispersion of  the  component  actuation  functional  performances  verified  by analysis and test. 

4.7.5.4  Other mechanical design and sizing requirements4.7.5.4.1  Replaceable elements

a.  Where  parts  or  components  are  intended  for  possible  replacement  or  re‐installation, they shall be designed to ensure they can only be installed in the correct orientation and position. 

b.  Mechanisms using deformable elements shall be designed to ensure they can only be installed in the correct orientation and position. 

NOTE 

Examples  of  such  mechanisms  are  crush dampers. 

30 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 c.

The design of replaceable items shall inhibit the reuse in the mechanism or spacecraft in the un‐refurbished state. 

4.7.5.4.2  Status monitoring

a.

Unless  monitored  at  spacecraft  system  level,  the  design  of  mechanisms shall include means to monitor the execution of its main functions.  

b.  Mission critical mechanisms shall be designed in such way that monitoring information of its critical functions is accessible to the spacecraft telemetry. NOTE 

For telemetry requirements, see ECSS‐E‐ST‐70‐11, clause 5.9.5 

4.7.5.4.3  Latching or locking

a.

Latching mechanisms used to assure positive locking shall be designed to avoid  inadvertent  opening  by  vibration  or  shock  occurring  during  the mission. 

Unless  agreed  by  the  customer,  locking  or  latching  mechanisms  shall provide an indication of whether the latch or lock is open or closed. 

Electrically  actuated  deployable  items  shall  use  positive  latching  or locking. 

The  latch  capture  range  shall  ensure  capture  of  the  mechanism  over  the complete 

temperature  gradients  and manufacturing and assembly tolerances. 

The design shall not prevent subsequent successful latching if latching is not achieved on the initial completion of motion. 

Latches shall be self locking. 

Latches shall be resettable for ground testing. 

Off‐load mechanisms shall be capable of being operated manually. 

Shock loads for latches and locks shall be derived by analysis or test, and specified in the mechanism requirements specification. 

temperatures  or 

range  of 

b.

c.

d.

e.

f.

g.

h.

i.

4.7.5.4.4  End stops

a.  Mechanisms  with  restricted  travel  or  rotation  shall  be  provided  with regular or emergency mechanical end stops to limit their motion and travel extremes to the maximum position specified in the SMS. 

End  stops  shall  be  provided  to  prevent  interference  with  interfacing equipment. 

b.

NOTE 

Regular  end  stops  are  provided  for  proper functioning of the actuated item. 

c.

d.

The mechanical end stops and arresting mechanisms shall be designed to withstand without damage the maximum shock loads with the structural margins defined in clause 4.7.5.4.5.  

The  end  stop  sizing  shall  conform  to  the  separable  contact  surfaces requirements specified in 4.7.5.4.5.  

31 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 e.

f.

g.

h.

The end stop sizing shall take into account the worst‐case loads, including the shock loads. 

Contact with an end stop shall not result in a non‐recoverable situation.  NOTE 

this In  case  of  specific  application  where 

requirement 

is  a  main  design  driver,  an alternative  solution  for  emergency  end  stop  can be adopted if agreed by the customer. 

Electrical deployment indicators shall not be used as mechanical end stops. NOTE 

Example  of  electrical  deployment  indicators  are micro‐switches. 

The mating surfaces used in separable end stops shall be Ra <0,4 μm.  4.7.5.4.5  Separable contact surfaces (other than gears, balls and

journal bearings)

a.

b.

c.

d.

e.

f.

g.

Except  for  gears  and  ball  or  journal  bearings,  separable  contact  surfaces shall be designed to maintain adhesion forces below the specified limits.  Except  for  gears  and  ball  or  journal  bearings,  the  contact  between  the mating surfaces shall be characterized. 

NOTE 

Characterisation 

includes  surfaces  roughness, hardness,  material  properties,  and  contact geometry. 

Except  for  gears  and  ball  or  journal  bearings,  the  repeatability  of  the contact  between  the  mating  surfaces  shall  be  verified  and  agreed  by  the customer. 

NOTE 

Repeatability includes contact loads, contact area, contact stress, and alignment. 

Except  for  gears  and  ball  or  journal  bearings,  the  peak  hertzian  contact stress shall be verified to be below 93 % of the yield limit of the weakest material. 

Except  for  gears  and  ball  or  journal  bearings,  sliding  at  the  separable contact  surfaces  before  separation  shall  be  prevented,  in  order  to  avoid potential contact surface property changes.  

Except for gears and ball or journal bearings, the functional dimensioning of the actuator which separates the contact surfaces shall be 

1.

2.

sized in conformance with clause 4.7.5.3, and 

verified  by  test  under  representative  environmental  conditions  to conform to clause 4.7.5.3. 

Except for gears and ball or journal bearings, and unless one surface is a self‐lubricating  material,  when  metallic  material  mating  or  separating surfaces subject to relative motion are used, they shall 

1.

2.

have a minimum hardness of 500 HV, and  

either: 

(a)

be composed of dissimilar material, or  

32 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 (b)

at least one of the two surfaces have a dissimilar coating.  NOTE 1  Example of self‐lubrificating material is bronze. 

NOTE 2  Examples  of  dissimilar  coatings  are  nitride, carbide or oxide.  

NOTE 3  The  use  of  bonded  or  sputtered  MoS2  or polymeric materials is not excluded. 

4.7.5.4.6  Ball bearings

a.

Ball  bearings  made  of  hardened  steel  as  defined  in  ISO  76  Edition  2 Amendment 1 subclause 1, shall be sized concerning the static load rating in  conformance  with  ISO  76  Edition  2  Amendment  1  subclause  2,  with respect to the maximum allowable hertzian contact stress.  

The  sizing  of  ball  bearings  made  of  materials  other  than  hardened  steel shall be agreed by the customer.  

Ball bearings should be shielded. 

b.

c.

4.7.5.4.7  Gears

a.

Dimensioning and sizing of gears shall be performed in conformance with, ISO 6336, ISO 677, and ISO 678.  

4.7.5.4.8  Mechanical clearances

a.  When designing and locating mechanisms, clearance shall be provided to prevent movable and actuating elements from:  

1.

interfering (collision) with the structure,  

2.

contacting  with  electrical  wiring  and  components, 

insulation, or other subsystem components,  

puncturing of fluid lines, valves and tanks, and 

blocking optical paths.  

3.

4.

Clearances shall be verified by analysis using worst‐case tolerance budgets including thermoelastic effects and operational loads.  

Clearances shall be verified by inspection.  

Clearances should be at least 3 times its associated tolerance. 

thermal b.

c.

d.

4.7.5.4.9  MLI clearance

a.

For MLI clearance, clause 4.7.4.3 shall apply. 

4.7.5.4.10  Threaded parts or locating devices

a.

b.

Threaded parts and locating devices shall use secondary, positive locking. Threaded fasteners shall be made from materials, which are not susceptible to stress corrosion cracking. 

NOTE 1  For  materials  preferred  list,  see  ECSS‐Q‐ST‐70‐36. For  other  materials  validation,  see  ECSS‐Q‐ST‐70‐

37. 

33 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 2  For  manufacturing  of  threaded  fasteners  see ECSS‐Q‐ST‐70‐46.  

c.

Threaded fasteners shall be designed to be fail‐safe. 

4.7.5.4.11  Venting

a.

Unless  the  mechanism  is  hermetically  sealed  or  sized  in  all  its  functions and performances for internal pressure build‐up, all closed cavities shall be provided  with  a  venting  hole  sized  according  to  the  launch  ascent depressurisation profile. 

The method and design of venting shall prevent particles contamination of bearings, optics and external sensitive components agreed by the customer. b.

c.

NOTE 1 

is 

It 

important 

contamination  of 

within the mechanism. 

to  prevent  also  particles the  sensitive  components NOTE 2  Filters with mesh size of 1 to 2 microns placed in the  venting  path  are  means  to  prevent  particles contamination. 

If  venting  to  the  outside  of  a  lubricated  enclosure  is  implemented, compatibility of the lubricant with the other spacecraft materials used and with  contamination  requirements  specified  in  the  specific  mechanism specification shall be verified. 

4.7.5.4.12  Release and locking devices with pyrotechnics or other

actuators

a.

Pyrotechnic  and  other  release  and  locking  device  actuators  should  be redundant. 

NOTE 

Example  of  such  actuators  are  thermal  knives, memory metal and paraffin actuators. 

b.  Where no actuator redundancy is provided, redundancy shall be provided by  duplicating  up  to  and  including  the  level  of  the  initiators,  heating element or equivalent for non‐pyrotechnic devices, and its power supply. The conformity of the design, material and manufacture of elements to be cut  used  in  release  and  locking  devices  to  the  reliability  requirements specified in the SMS shall be verified by test. 

c.

NOTE 

Example  of  such  elements  are  bolts,  rods  and cables. 

d.

e.

f.

g.

The  operation  of  release devices  shall  be  compatible  with  the  cleanliness requirements. 

All debris shall be contained. 

If critical, contamination shall be measured. 

Shock loads for release and locking devices shall be derived by analysis or test, and specified in the mechanism requirements specification. 

34 ![Im0](images/Im0)

![Im0](images/Im0)

Pyrotechnics

ECSS‐E‐ST‐33‐01C 6 March 2009 Pyrotechnic actuators shall be designed in conformance with ECSS‐E‐ST‐33‐11. 

4.7.6

a.

4.7.7

Electrical and electronic

4.7.7.1

Electrical design

4.7.7.1.1  General

a.  Mechanisms  shall  be  designed  to  meet  all  the  requirements  regarding electrical interfaces and performances. 

stable 

exhibit 

shall 

b.  Mechanisms 

c.

d.

e.

f.

g.

h.

i.

b.

electrical 

characteristics 

and electromechanical  transfer  functions  throughout  their  specified  period  of life. 

Electrical power consumption, generation and thermal dissipation shall be quantified by design. 

Fault propagation shall be prevented. 

Generated electrical disturbances shall conform to the project specific EMC requirements. 

If  brush  motors  are  used,  it  shall  be  verified  under  representative environment  and  over  specified  lifetime  that  debris  generation  does  not result in contamination. 

If  brush  motors  are  used,  it  shall  be  verified  under  representative environment  and  over  specified  lifetime  that  debris  generation  does  not result in electrical failure. 

NOTE 

For example, short circuit of commutators. 

If  brush  motors  are  used,  it  shall  be  verified  under  representative environment and over specified lifetime that brush wear does not result in functional performance degradation. 

If  brush  motors  are  used,  it  shall  be  verified  under  representative environment and over specified lifetime that long storage period does not result in  functional performance degradation. 

Insulation

4.7.7.2

a.

Electrical wires shall be insulated from the structure and from each other by not less than 10 MΩ measured with a DC voltage of 500 V applied. Electric  motor  windings  shall  be  insulated  from  the  structure  and  from each other by not less than 100 MΩ measured with a DC voltage five times the worst‐case flight operating voltage. 

35 ECSS‐E‐ST‐33‐01C 6 March 2009 4.7.7.3  Dielectric

a.

Electrical wires shall be designed to withstand a high voltage of 500 V AC (50 Hz)  applied  between  each  other  or  between  wires  and  the  structure without causing disruptive discharges. 

Electric motor windings shall be designed to withstand the following high voltage applied between each other or between windings and the structure without causing disruptive discharge: 

1.

2.

250 V AC (worst flight operating motor voltage up to 50 V), 

500 V AC (worst flight operating motor voltage up to 100 V). 

b.

b.

c.

d.

e.

4.7.7.4  Grounding

a.

Each mechanism shall be electrically bonded to the spacecraft structure or its carrying equipment.  

If  electronic  or  electrical  components  are  mounted  internally  to  or externally  on  the  mechanism  a  ground  bonding  strap  shall  be  used between the mechanism housing and the mounting ground plane. 

If  electronic  or  electrical  components  are  mounted  internally  to  or externally  on  the  mechanism,  the  length‐to‐width  ratio  of  the  bonding strap should be smaller than four. 

If  electronic  or  electrical  components  are  mounted  internally  to  or externally on the mechanism, the DC resistance, between the mechanism bonding  reference  point  and  the  mounting  ground  plane  or  carrying equipment ground plane in both polarities, shall be less than 10 mΩ. 

If  electronic  or  electrical  components  are  mounted  internally  to  or externally on the mechanism, the DC resistance, between any point on the mechanism  housing  and  the  bonding  point  reference  of  the  mechanism, shall be less than 5 mΩ.  

f.  Where  the  grounding  is  to  provide  protection  against  electrostatic discharge  only  and  the  mechanism  contains  no  electronics,  the  DC resistance shall be less than 0,1 Ω.  

Electrical connectors

4.7.7.5

a.  With  the  exception  of  the  bonding  strap  for  grounding,  all  electrical connections to the mechanism shall be made through electrical connectors of a type qualified for the intended application. 

Flying leads should be avoided.  

Connector types and configurations shall be selected to preclude damage or inadvertent operation resulting from mis‐mating. 

b.

c.

NOTE 

For example, for the number of pins. 

d.

Electrical connectors shall be redundant. 

36 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 4.7.7.6  Over current protection

a.  Mechanisms  containing  electrical  parts  and  circuitry  shall  be  protected against overcurrent due to abnormal applied voltage or internal conditions in conformance with ECSS‐E‐ST‐20, clause 5.8.1. 

NOTE 

current  protection 

The 

externally. 

can  be  provided b.

The mechanism shall be protected against the generation of over voltage in conformance with ECSS‐E‐ST‐20, clause 5.8.1. 

Strain on wires

4.7.7.7

a.

b.

c.

d.

Routing shall be designed  to be reproducible. 

Implementation shall be verified. 

Resistive torques or forces shall be measured under worst‐case conditions. The relative position of cables within the harness shall not change during motion. 

NOTE 

The  four  previous  requirements  are  introduced in order to achieve reproducible resistive torques or forces of moving cable harness. 

e.

Connections shall be protected from harness induced loads. 

4.7.7.8  Magnetic cleanliness and ESD or EMC protectiona.  Mechanisms  shall  conform  to  the  spacecraft  system  requirements  on magnetic  cleanliness 

in  conformance  with  ECSS‐E‐ST‐20‐07,  and conductivity  of  surfaces  for  electrostatic  discharge  (ESD)  protection  in conformance with ECSS‐E‐ST‐20‐06.  

4.7.8  Open-loop and closed-loop control systemfor mechanisms

4.7.8.1

a.

b.

4.7.8.2

a.

The  gain  margin  shall  be  higher  than  a  factor  of  two  (2)  throughout  the operational  lifetime  for  linear  or  quasi‐linear  control  systems,  including A/D and D/A conversions effects.  

Non‐linear control systems stability margin value and assessment method shall be agreed by the customer. 

The  phase  margin  shall  be  higher  than  30  degrees  throughout  the operational lifetime of the equipment and under worst‐case combination of parameters  (drift  and  temperature  effects),  including  A/D  and  D/A conversions effects.  

37 ![Im0](images/Im0)

![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 The  bandwidth  of  the  control  system  shall  be  designed  to  achieve  the commanded action within the specified response time. 

The damping ratio of the control system shall be greater than 0,05. 

NOTE 

This  is  the  same  than  require  an  equivalent  Q value (amplification factor) of less than 10. 

The control system shall not excite mechanism eigenmodes. 

The control system shall take into account aliasing effects. 

The control system shall not excite structural resonances of the spacecraft as specified by the customer. 

The  control  system  should  be  decoupled  between  the  six  directions  of movement (three translations and three rotations).  

If  requirement  4.7.8.6a  is  not  met,  then  coupling  effects  shall  be characterized.  

NOTE   Multidimensional  methods   provide   the  best results. 

The  control  system  shall  be  compatible  with  the  specified  maximum angular and linear rates and accelerations of the spacecraft. 

4.7.8.3

a.

4.7.8.4

a.

4.7.8.5

a.

b.

c.

4.7.8.6

a.

b.

4.7.8.7

a.

4.7.8.8

a.

b.

4.7.8.9

a.

b.

To  prevent  excessive  amplification  of  the  noise,  transfer  functions  of  the controller should not contain pure derivative terms.  

The  ratio  between  the  derivative  time  constant  and  the  time  constant limiting the high frequency gain should not exceed 20. 

Harnesses  and  cables  to  moving  parts  shall  be  characterized  in  terms  of hysteresis and stiffness in representative configuration over the full range of  displacement  and  over  the  specified  qualification  levels  in  terms  of temperature range, lifetime, speed effects. 

Harnesses  and  cables  to  moving  parts  shall  be  taken  into  account  in  the control system design.  

38 ![Im0](images/Im0)

4.7.8.10

a.

ECSS‐E‐ST‐33‐01C 6 March 2009 If  the  sampling  frequency  results  in  aliasing  of  the  sampled  data,  an anti‐aliasing  filter  to  reduce  the  bandwidth  of  the  analogue  signal  (to  be sampled) shall be used.  

4.7.8.11

a.

The  resolution  of  sensors  used  in  the  control  system  to  feedback information should be at least a factor of 5 (five) better than the specified resolution of the complete system. 

- 4.8  Verification

4.8.1  General

a.

Development of space mechanisms shall include a verification process in conformance with ECSS‐E‐ST‐10‐02.  

NOTE 1  The  mechanisms  verification  requirements  are subdivided  into  analytical  and  test  verification requirements. 

NOTE 2  The  model  definition  are  provided  in  ECSS‐E‐

HB‐10‐02. 

b.

A verification matrix shall be established by the supplier and provided to the customer for agreement. 

4.8.2

Verification by analysis

4.8.2.1  General

a.

b.

c.

The  mechanisms  parts,  components  and  assembly  analytical  verification shall include the analysis specified in 4.8.2.2 to 4.8.2.19. 

If  any  of  the  analysis  specified  in  requirement  4.8.2.1a  is  not  performed, justification shall be provided and agreed by the customer. 

The analyses specified in requirement 4.8.2.1a shall cover  

1.

the combinations of range of extreme conditions for the flight system and which do not necessarily all occur during qualification testing  NOTE 

For example, worst‐case friction levels.  

2.

the effect of on‐ground environmental conditions  

NOTE 

For  example,  air  pressure,  gravity  effects,  and test rigs perturbations. 

3.

the worst or extreme case conditions. 

39 ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.2.2  Worst-cases identification

a.

The  worst‐case  operational  and  non‐operational  sizing  of  a  mechanism shall  be  identified  according  to  the  environmental,  load  and  functional performance characteristics for the particular spacecraft and mechanism. Thermal analysis

4.8.2.3

a.

4.8.2.4

a.

For the derivation of margins of safety clause 4.7.4.1 shall apply. 

NOTE 

See  ECSS‐E‐ST‐31 

mechanisms. 

for 

thermal  analysis  of Structural analysis

For the derivation of margins of safety clause 4.7.5.2 shall apply. 

NOTE  1  Structural  analysis  includes  stiffness,  stress  or strength,  thermo‐mechanical  effects,  fatigue  and fracture control. See ECSS‐E‐ST‐32  for structural analysis of mechanisms. 

NOTE  2  The  objective  is  to  demonstrate  adequate  sizing of the component and the overall assembly for all sizing cases. 

Pre-load and tolerance budget analysis

4.8.2.5

a.  Mechanisms pre‐load and tolerance budget analysis shall take into account the  relevant  combination  of  the  worst‐cases  environmental,  functional, residual  loads  (including  external  and  induced  loads,  and  thermo‐mechanical effects) and manufacturing tolerances. 

b.  Mechanisms  pre‐load  and  tolerance  budget  analysis  shall  verify  the adequacy of mechanical plays in the worst‐case conditions. 

4.8.2.6

Functional performance analysis

4.8.2.6.1  General

a.

Functional  performance  analysis  shall  be  performed  in  all  specified environments  under  all  operational  conditions  (based  on  worst‐case identification)  to  derive  sizing  loads,  time  shocks,  speed,  dimensional stability and positional accuracy. 

4.8.2.6.2  Functional model requirements

a.

The  analysis  shall  be  based  on  an  analytical  or  numerical  model,  which represents the flight hardware mechanisms and its components, including interface conditions and overall spacecraft characteristics, with respect to  1.

2.

3.

4.

mass,  

inertia,  

location of the centre of mass,  

structural stiffness,  

40 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 b.

actuation forces or torques, and  

resistances for conditions specified in clause 4.7.5.3. 

5.

6.

The  model  specified  in  requirement  4.8.2.6.2a  shall  be  such  that  the following can be performed: 

1.

2.

a parametric study of all the mechanical variables, and 

an update of input parameters during the design and test phase.  4.8.2.6.3  Analysis requirements

a.

It shall be demonstrated by analysis that the mechanism conforms to  1.

2.

the specific mechanism requirement specification (SMS), and 

the  mechanical  design  and  sizing  requirements  (see  clause 4.7.5) under worst‐case parameter combinations.  

b.

c.

d.

e.

f.

Failure  cases  shall  be  analysed  and,  where  identified,  contingency scenarios shall be established and validated by analysis.  

An integrity check of the results of the analysis shall be performed.  

NOTE 

For example, energy or momentum balance.  

A  sensitivity  analysis  (parameter  variation)  covering  the  uncertainty  of parameters shall be carried out.  

If  test  results  do  not  match  predictions,  the  reason  of  the  disagreement shall be found, and the analysis shall be updated accordingly.  

Remaining deviations between test results and analyses shall be justified with respect to performance acceptability. 

4.8.2.7  Hertzian contact and contact stress

a.

An analysis shall be provided of the predicted hertzian contact or yield or bending  stresses  of  moving  surfaces  in  contact  (for  both,  separable  and sliding  contacts,  and  bearings)  under  worst‐case  conditions  to  verify  the compliance  with  the  material  allowables  of  the  chosen  material  couple, lubricant and other coating used. 

An  analysis  shall  be  provided  to  verify  sizing  of  ball  bearings  in conformance  with  ISO  76  Edition  2  Amendment  1  subclauses  2,  4,  5,  6 and 7. 

b.

Functional dimensioning analysis

4.8.2.8

a.

Conformance  of  mechanisms  to  specified  requirements  on  functional dimensioning shall be verified by analysis. 

NOTE 

Example of such requirements are torque, force, and kinematics. 

4.8.2.9  Reliability analysis, FMECA

a.

The reliability of a mechanism shall be determined. 

41 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 

For  reliability,  see  ECSS‐Q‐ST‐30.  For  FMECA, see ECSS‐Q‐ST‐30‐02. 

4.8.2.10  Gear analysis

a.

An analytical verification of the conformity of dimensioning and sizing of gears shall be performed. 

NOTE 

For gear dimensioning and sizing see ISO 6336. 

4.8.2.11  Shock generation and susceptibility

a.

The conformity of the mechanism to the requirements for shock generation and susceptibility specified in the SMS shall be verified by analysis. 

Dimensioning and sizing methods shall be agreed by the customer. 

b.

4.8.2.12  Disturbance generation (emission) and susceptibilitya.

The mechanism operation shall be verified by analysis to comply with the specified requirements for induced loads.  

NOTE 

For example, micro‐vibrations.  

b.

The moving parts of the mechanism should be balanced to conform to the specified requirements on disturbances. 

4.8.2.13  Analysis of control systems

a.

b.

c.

d.

e.

f.

A  mathematical  model  or  computer  simulation  describing  the  dynamic behaviour  of  the  mechanism  and  its  associated  control  system  shall  be established to perform verification by analysis. 

The functional performance of the control system shall be analysed for 1.

2.

3.

4.

5.

stability, 

bandwidth, 

dynamic and static accuracy, 

resolution, and 

generation of and susceptibility to disturbances at the interfaces of the mechanism. 

All non‐linearities shall be analysed. 

Non‐linearities such as backlash, dead zones, friction, saturation of drive electronics  shall  be  characterized  and  taken  into  account  in  the  control system analysis.  

Characterization  of  non‐linearities  shall  take  place  over  the  full  range  of displacements and over the full specified qualification temperature range.  The  worst‐case  combinations  of  parameters  occurring  during the operational  lifetime  of  the  equipment  shall  be  taken  into  account  in  the analysis of the non‐linearities. 

42 ![Im0](images/Im0)

![Im0](images/Im0)

g.

The  robustness  of  the  control  against  variations  in  the  environment, between  models  and  over  the  operational  lifetime  shall  be  verified  by analysis. 

ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.2.14  Lubrication analysis

a.

b.

c.

worst case peak contact hertzian stress; 

worst case operational contact hertzian stress; 

number and range of cycles; 

worst case environmental conditions. 

An analysis of the choice of lubrication system and its dimensioning for the proposed application and lifetime shall be provided. 

The analysis specified in requirement 4.8.2.14a shall be based on similarity to a qualified application with regards to the following parameters: 

1.

2.

3.

4.

For  fluid  lubrication  systems,  the  analysis  specified  in  requirement 4.8.2.14a  shall  verify  the  compatibility  of  the  lubricant  with  the  specified lifetime  increased  by  a  factor  of  1,5  under  the  following  worst  case operational conditions: 

1.

2.

qualification temperatures; 

operational temperature profile of the mechanism over the full life time. 

4.8.2.15  Lifetime analysis

a.

b.

Limited‐life components shall be identified. 

Conformance  of  limited‐life  components  to  the  lifetime  requirements specified  in  the  specific  mechanism  specification  shall  be  verified  by analysis,  using  as  a  minimum  the  lifetime  factors  specified  in  clause 4.8.3.3.14 in addition to the fatigue factor specified in clause 4.7.5.2. 

4.8.2.16  Hygroscopic effect analysis

a.

The  design  compatibility  with  the  hygroscopic  environment  during  the complete lifetime shall be verified by analysis. 

NOTE 

The hygroscopic environment is mainly relevant on‐ground. 

4.8.2.17  Magnetic and electromagnetic analysis

a.

The sizing of magnetic or electromagnetic components shall be verified by analysis. 

4.8.2.18  Radiation analysis

a.

Conformity  of  the  components  susceptible  to  radiation  to  the  (lifetime) performance requirements shall be verified by analysis. 

43 ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.2.19  Electrical analysis

a.

Electrical parts stress analysis shall be performed to demonstrate that the electrical parts conform to the derating requirements.  

For derating see ECSS‐Q‐ST‐30‐11. 

NOTE 

4.8.3

Verification by test

4.8.3.1  General

a.

The  tests  to  be  performed  to  verify  that  the  mechanism  fulfils  the requirements for use as space hardware shall be: 

1.

2.

defined in a test plan, and 

agreed by the customer.  

b.

c.

d.

e.

f.

g.

h.

NOTE 

The aim of testing can be either characterization, development, qualification or acceptance.  

The  permissible  operations  and  the  constraints  for  the  operations  on ground shall be defined by the supplier and agreed by the customer.  The  mechanisms  test  programme  shall  include  the  verification  that  the hardware conforms to the requirements on design specified in clause 4.7, on construction specified in clause 4.9, and on performance specified in the specific mechanism specification. 

The  tests  shall  verify  that  the  mechanism  conforms  to  the  functional dimensioning requirements specified in clause 4.7.5.3. 

Tests shall be performed to check mechanism performance in both launch and operational configurations. 

The mechanism shall be subjected to a thermal verification. 

The mechanism shall be subjected to a structural verification. 

NOTE 

For structural requirements, see ECSS‐E‐ST‐32. 

Non‐linearities  shall  be  measured  in  order  to  characterize  the  dynamic behaviour of the mechanism. 

NOTE 

Examples  of  non‐linearities  are  hysteresis  and backlash. 

4.8.3.2  Characterization or development testing

4.8.3.2.1  Model requirements

a.

Development tests shall be carried‐out on the bread‐board models to test the specific aspect agreed by the customer. 

NOTE 

The  objective  is  to  use  bread‐board  models  of varying  levels  of  sophistication  to  test  specific aspects or assumptions of a design on which the outcome of the design depends. 

44 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.3.2.2  Test

a.

Except  in  the  case  specified  in  requirement  4.8.3.2.2b,  the  following verification  tests  on  development  model  mechanisms  shall  be  performed during phases A or B of the project: 

1.

2.

3.

Verification test specified in requirement 4.8.3.2.2a need not be performed if  the  customer  agrees  that  the  test  available  data  from  previous  space application can be used instead. 

functional performance tests in ground ambient environment. 

vibration and thermal tests. 

tribological lifetime test on life critical components. 

b.

b.

4.8.3.3  Qualification testing

4.8.3.3.1  General

a.

All mechanisms shall be qualified by test for the application in which they are used. 

The qualification tests shall be performed in a representative sequence and in a representative environment, agreed by the customer. 

4.8.3.3.2  Structural qualification testing

a.

The mechanisms structure shall be qualified by testing. 

4.8.3.3.3  Thermal vacuum qualification testing

a.

b.

A thermal qualification of the mechanism shall be performed. 

Operation of the mechanism in a representative environment under worst‐case temperature gradients shall be verified by test at a level agreed by the customer. 

4.8.3.3.4  Functional qualification testing

a.

b.

Settling  and  thermal  stabilization  shall  be  performed  prior  to  functional performance testing. 

The  conformance  of  the  mechanism  to  the  performance  requirements following  exposure  to  environmental  conditions  (loads,  thermal)  at qualification level and mechanism qualification duration shall be verified by test. 

4.8.3.3.5  Energy or shock

a.  Mechanisms shall be verified by test to withstand release and end shocks caused by the motion of the mechanism.  

Latching shock emissions shall be measured. 

b.

4.8.3.3.6  Solid lubricated ball bearing verification

a.

Solid lubricated ball bearing material, design and performance (including the cage) shall be verified by testing. 

45 ![Im0](images/Im0)

![Im0](images/Im0)

b.

The environment for the lubricant life test demonstration shall be agreed by the customer. 

ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.3.3.7  Fluid lubricated ball bearing verification

a.

Ball bearing cage material, design, impregnation procedures for cages and reservoirs, and performance shall be verified by testing. 

Lubricant quantity shall be verified by tests. 

The compatibility of the fluid lubricant with the mechanism materials and other lubricants used within the mechanism shall be verified. 

b.

c.

4.8.3.3.8  EMC or ESD qualification testing

a.

The EMC performance (susceptibility and emissivity) of mechanisms shall be verified by testing when: 

1.

2.

EMC sensitive components are used on the mechanism, or  

spacecraft  specific  EMC  requirements  are  applicable 

mechanism. 

to the b.

ESD  testing  shall  be  performed  on  a  complete  mechanism  including  all electrical components and thermal hardware. 

NOTE 

For EMC and ESD see ECSS‐E‐ST‐20. 

4.8.3.3.9  Electrical qualification testing

a.

Electrical wires shall be tested to verify their insulation from the structure and from each other by not less than 10 MΩ with a DC voltage of 500 V applied for a duration of 2 min or until a steady state resistance value is measured. 

Electrical wires shall be tested to withstand a voltage of 500 V AC (50 Hz) applied  between  each  other  or  between  wires  and  the  structure  for  a duration of 1 min without causing disruptive discharges.  

b.

NOTE 

example, 

For 

breakdown. 

flash‐over, 

spark‐over 

and c.  Motor windings shall be tested to verify their insulation from the structure and from each other by not less than 100 MΩ with a DC voltage of at least five times the worst‐case flight operating voltage applied for a duration of 2 min or until a steady state resistance value is measured. 

d.  Motor windings shall be tested to withstand the following voltage (50 Hz) applied between each other or between windings and the structure for a duration of 1 min without causing disruptive discharges: 

1.

2.

250 V AC (worst flight operating motor voltage up to 50 V); 

500 V AC (worst flight operating motor voltage up to 100 V). 

NOTE 

Example  of  such  disruptive  discharges  are flash‐over, spark‐over and breakdown. 

46 ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.3.3.10  Control system qualification testing

a.

The  mathematical  model  used  to  analyse  the  dynamic  behaviour  of  the control  system  shall  be  correlated  with  measurements  performed  on representative hardware agreed by the customer. 

The  verification  of  control  system  performance  by  test  should  be performed using independent measurement devices.  

The control system transducer shall not be used as a reference during the tests  unless 

in  a representative environment. 

transducer  has  been  calibrated  previously 

the 

b.

c.

4.8.3.3.11  Lifetime qualification testing

a.

The  mechanism  design,  lubricant  lifetime  and  performance  shall  be verified  by  test  on  a  flight  representative  life  test  model  in  the  specified environment after exposure to flight representative environmental tests.  NOTE 

For  example,  worst‐case  loads  and  accumulated vibration durations. 

b.

Exposure of lifetime model to vibrations prior to life test shall include: 1.

exposure to accumulated durations of acceptance tests at acceptance load level and accumulated durations corresponding to the number of vibrations tests expected by the flight hardware, and  

one  time  exposure  to  qualification  load  level  and  duration  of vibration. 

2.

c.

The environment for the verification of the lifetime of a lubricant shall be agreed by the customer.  

4.8.3.3.12  Life test model requirements

a.

The model and lifetime testing shall be representative with respect to the following parameters: 

1.

Thermal  conditions,  loading  conditions,  contact  stress,  motion profile  and  speed  during  testing,  representative  of  the  operational conditions. 

Lubrication 

representative  of  worst‐cases  expected operational conditions, and for durations factored as agreed by the customer. 

NOTE 

in  clause The  duration  factors  are  defined 

4.8.3.3.14.  

2.

regime 

b.

Extended life durations to be agreed by the customer shall be implemented for the simulation of realistic conditions during accelerated tests. 

NOTE 

These  parameters  can  influence  the  life  of  the mechanism. 

4.8.3.3.13  Life test profile

a.

The profile and sequence of a life test shall be defined and agreed by the customer. 

47 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 4.8.3.3.14  Life test duration

a.

The  lifetime  qualification  shall  be  verified  using  the  factored  sum  of  the predicted nominal ground test cycles and the in‐orbit operation cycles.  For the test verification, the number of expected cycles shall be multiplied by the factors in Table 4‐3. 

b.

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Type </td>
		<td>Number of expected cycles </td>
		<td>Factor </td>
	</tr>
	<tr align="center">
		<td rowspan=3>Ground testing  (minimum 10 cycles to  be tested) </td>
		<td>1 to 1 000 cycles </td>
		<td>4 </td>
	</tr>
	<tr align="center">
		<td>1 001 to 100 000 cycles </td>
		<td>2 </td>
	</tr>
	<tr align="center">
		<td>> 100 000 cycles </td>
		<td>1,25 </td>
	</tr>
	<tr align="center">
		<td rowspan=4>In‐orbit       </td>
		<td>1 to 10 cycles </td>
		<td>10 </td>
	</tr>
	<tr align="center">
		<td>11 to 1 000 cycles </td>
		<td>4 </td>
	</tr>
	<tr align="center">
		<td>1 001 to 100 000 cycles </td>
		<td>2 </td>
	</tr>
	<tr align="center">
		<td>> 100 000 cycles </td>
		<td>1,25 </td>
	</tr>
</table>

 

c.

d.

The cycle definition shall be agreed by the customer and take into account at least. 

1.

2.

In  order  to  determine  the  lifetime  to  be  demonstrated  by  test,  an accumulation of cycles multiplied by their individual factors shall be used. the number of motions over the same location, and 

motion amplitude and number of reversals.  

NOTE 

Table 4‐4 presents two case examples to calculate the number of cycles to be used in the test. 

<table align="center">
	<tr align="center">
		<td></td>
		<td></td>
		<td>Calculations </td>
	</tr>
	<tr align="center">
		<td rowspan=5>Example 1 </td>
		<td>Expected ground test cycles: 15 </td>
		<td>15×4 = 60 </td>
	</tr>
	<tr align="center">
		<td>Expected in‐orbit cycles: 100 </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>First 10 cycles </td>
		<td>10×10 = 100 </td>
	</tr>
	<tr align="center">
		<td>Remaining 90 cycles </td>
		<td>90×4 = 360 </td>
	</tr>
	<tr align="center">
		<td>Total life test number </td>
		<td>520 </td>
	</tr>
	<tr align="center">
		<td rowspan=4>Example 2 </td>
		<td>Expected ground test cycles: 2 </td>
		<td>2×4 = 8 </td>
	</tr>
	<tr align="center">
		<td>But minimum is 10 </td>
		<td>10 </td>
	</tr>
	<tr align="center">
		<td>Expected in‐orbit cycles: 1 </td>
		<td>1×10 = 10 </td>
	</tr>
	<tr align="center">
		<td>Total life test number </td>
		<td>20 </td>
	</tr>
</table>

 

e.

Any  element  in  a  chain  of  actuation  shall  conform  to  the  maximum number of cycles applicable to any of the other elements in the chain. 48 ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 

Example  of  such  elements  are  motors,  bearings, and gears. 

4.8.3.3.15  Accelerated lifetime testing

a.

lifetime  testing 

If  accelerated 

lifetime performance  of  the  mechanism,  the  model  used  for  accelerated  lifetime testing shall be representative of the worst‐case environmental conditions with respect to degradation. 

is  employed  to  verify  the 

4.8.3.3.16  Post-test inspection

a.

After completion of the life test, the mechanisms shall be disassembled into its tribological components and the status of the components verified with respect to the life test success criteria identified in clause 4.8.3.3.17. 

4.8.3.3.17  Qualification testing success criteria

a.

Qualification testing of the mechanism or of mechanical subsystem shall be considered successful when all the following criteria are demonstrated at the end of the test: 

1.

No  direct  contact  between  metallic  elements  in  relative  motion identified in the interface of solid lubricated contact surfaces; 

Surface  properties  of  contact  surfaces  not  modified  beyond  the specified limits of their performance properties; 

No  chemical  deterioration  beyond  the  specified  limits  of  fluid lubricants is found; 

The  amount  and  size  of wear  products  conforms  to  contamination and  overall  mechanism  performance  requirements  specified  in  the specific mechanism specification; 

2.

3.

4.

6.

5.  Worst‐case  variation  or  degradation  peak  torque  or  force  overall throughout  qualification  (including  life)  testing  is  compatible  with the functional dimensioning requirements specified in clause 4.7.5.3; Deterioration  torque  or  force  performance  is  less  than  or  equal  to 50 % of the values measured at the beginning of qualification tests;  Other  degradation  factors  agreed  on  a  case  by  case  basis  with  the customer are within the specified limits; 

All  measured  performances  conform  to  the  requirement  of  the specific mechanism specification. 

7.

8.

4.8.3.4  Acceptance testing

4.8.3.4.1  Mechanical settling and thermal stabilization

a.  Mechanical settling  and thermal stabilization shall be performed prior to acceptance testing. 

4.8.3.4.2  Acceptance tests

a.

New builds of qualified designs shall be acceptance tested to verify that the actual manufactured hardware is free from manufacturing defects.  

49 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 b.

c.

d.

The acceptance test sequence shall be agreed by the customer. 

The acceptance level testing shall be carried out at levels, which are higher than expected in flight but less than the qualification levels. 

After acceptance testing, refurbishment should not be performed.  

NOTE 

This  is  for  the  test  levels  experienced  to  be  at  a level, which is not detrimental to the health of the hardware. 

4.8.3.4.3  Dielectric test

a.

Electrical wires shall be tested to withstand the following voltage (50 Hz) applied  between  each  other  or  between  wires  and  the  structure  for  a duration of 10 s without causing disruptive discharges: 

1.

2.

3.

250 V AC (worst flight operating voltage up to 50 V), or 

500 V AC (worst flight operating voltage up to 100 V), 

5  times  the  operating  voltage,  AC  (worst  flight  operating  voltage higher than 100 V). 

NOTE 

example, 

For 

breakdown. 

flash‐over, 

spark‐over 

and 4.8.3.4.4  Acceptance tests criteria

a.

Acceptance  testing  shall  be  considered  successful  when  all  the  following criteria are met: 

1.

The  peak  torque  or  force,  resulting  from  the  summation  of  the following,  comply  with  the  functional  dimensioning  requirements specified in clause 4.7.5.3:  

(a)

the worst‐case variation or degradation of the peak torque or force measured on the qualification model overall throughout life testing, and 

the worst case force or torque measured on the flight unit. (b)

Deterioration  torque  or  force  performance  throughout  acceptance tests is less than the values measured on the qualification model. All  measured  performances  conform  to  the  specific  mechanism specification (SMS). 

2.

3.

- 4.9  Production and manufacturing

4.9.1  Manufacturing process

a.

All processes used in the manufacture of space mechanisms hardware shall be  

1.

2.

approved by the customer, and  

part of the overall product assurance system. 

50 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 

is  normally  based  on 

This  approval 

their repeatability  and  proven  capability  of  achieving the specified levels of safety and reliability. 

4.9.2  Manufacturing drawings

a.  Manufacturing drawings shall be established in conformance with ISO 128. Assembly

4.9.3

a.

The  assembly  of  mechanisms  shall  be  performed  in  a  clean  environment specified by the customer. 

- 4.10  Deliverables

The  supplier  shall  provide  the  mechanisms  design  description conformance with the DRD in Annex B. 

The supplier shall provide the mechanisms analytical verification (MAV) in conformance with the DRD in Annex C. 

The  supplier  shall  provide  the  mechanism  user  manual  (MUM)  in conformance with the DRD in Annex D. 

in NOTE 1 

In accordance with requirement 4.2.2a, a specific mechanism specification is also delivered by the supplier for customer approval. 

NOTE  2  Requirements  4.10a 

covers 

to  4.10c 

the deliverable  documents  specific  to  the  present standard.  Table  E‐1  in  Annex  E  includes  the mechanism  documentation  technical  items,  and the ECSS documents where they are covered. 

a.

b.

c.

 

51 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Annex A (normative)Specific mechanism specification (SMS) -DRD- A.1  DRD identification

### Requirement identification and source document### A.1.1

This DRD is called from ECSS‐E‐ST‐33‐01, requirement 4.2.2a. 

### Purpose and objective

### A.1.2

The  purpose  of  the  specific  mechanism  specification  (SMS)  is  to  specify  the mechanism requirements specific to the particular application. It is expected that a SMS is developed for each individual mechanism in a project.  

The SMS is developed by the supplier, and propose to the customer for approval. - A.2  Expected response

### A.2.1

### Scope and content

<1>

a.

Introduction, references and terminology 

The SMS shall contain a description of the purpose, objective, content and the reason prompting its preparation. 

NOTE 

For  example:  “This  document  describes  the application  specific  requirements  of  the  <name> mechanism for the <name> project”. 

b.

c.

The SMS shall list any applicable and reference documents to support the generation of the document. 

The  SMS  shall  include  any  additional  definition,  abbreviation  or  symbol used. 

52 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 <2>

a.

<3>

a.

b.

c.

d.

e.

f.

Customer specific requirements 

The  SMS  shall  include  all  the  specific  requirements  expressed  by  the customer. 

General requirements 

The SMS shall specify or refer to the qualification procedure for parts and components. 

NOTE 

See 4.2.4.2a. 

If the mechanism is not maintenance free during storage and ground life, the  SMS  shall  list  the  maintenance  requirements,  including  for  each  of them: 

1.

2.

3.

4.

5.

6.

number of operations, 

frequency of operations, 

special tooling and test equipment, 

calibration and adjustments,  

fault identification and repair, and 

environment for maintainability operation. 

NOTE 

See 4.2.4.4b. 

The  SMS  shall  include  or  refer  to  the  method  to  demonstrate  the mechanism reliability compliance. 

NOTE 

See 4.2.5.1. 

The SMS shall describe the redundancy concepts for the mechanism. 

NOTE 

See 4.2.5.2d. 

The  SMS  shall  include  the  cleanliness  requirements  of  the  inert  dry  for flushing the critical parts of the mechanisms. 

NOTE 

See 4.2.6a. 

The  SMS  shall  include  the  minimum  functional  performances  to  be conformed to, over the complete mission (including on‐ground). 

NOTE 

This minimum functional performance is used to ensure that the mechanism is not degraded over the mission. In particular, it is used to ensure that there is not unacceptable degradation due to: 

•  Radiation (see 4.5.2.8); 

•  Atomic oxygen (see 4.5.2.9); 

•  Degradation of the lubricant in the on‐ground and in‐orbit environments (see 4.7.3.1c); 

•  Migration of fluid lubricants that can cause a change of the lubricant amount on the parts to be lubricated. In this case, anti‐creep barriers can be used (see 4.7.3.3.3c). 

53 ![Im0](images/Im0)

![Im0](images/Im0)

<4>

a.

b.

c.

<5>

a.

<6>

a.

b.

ECSS‐E‐ST‐33‐01C 6 March 2009 Constraints 

The SMS shall include the specific climatic protection and environmental requirements. 

The SMS shall include the sterilization requirements and the sterilization test procedure requirements. 

The SMS shall include the stray light and emission requirements. 

NOTE 

These  requirements  are  used  to  select  the materials and coatings (see 4.5.2.7). 

Interfaces requirements 

The SMS shall list the following interface definitions and requirements: 1.

2.

3.

4.

5.

6.

Structural 

Thermal 

Thermo‐mechanical 

Electrical 

Data 

Physical 

NOTE 

Examples  of  physical 

geometry, MOI, COG, and I/F pattern. 

interfaces  are:  mass, Optical 

Alignment 

Access and stay‐out zones 

7.

8.

9.

10.  GSE 

Design requirements 

The SMS shall list the handling, storage and operational requirements for all lubricated components. 

The  SMS  shall  include  the  limits  for  outgassing,  creeping  and  potential sources of contamination. 

NOTE 1  This limits have a strong impact on the design of the fluid lubricated system.  

NOTE 2  For  generic  requirements  on  outgassing  limits, see requirement 4.7.3.3.2.b. 

c.

d.

The  SMS  shall  define  the  specific  requirements  for  mission  involving advanced optical instruments. 

The  SMS  shall  include  the  qualification  temperature  range  under  all ground, test, launch and in‐orbit conditions. 

NOTE 

This  is  used  for  the  mechanism  thermal  design and sizing (see 4.7.4.2a). 

e.

The SMS shall list the shock load requirements for latches and locks. 

54 ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 

For  the  derivation  of  such  requirements,  see 4.7.5.4.3i. 

The SMS shall include the specified maximum positions of the mechanism. NOTE 

These maximum positions are provided to design end stops in accordance with 4.7.5.4.4a. 

The SMS shall specify the reliability requirements, to verify the conformity of  the  design,  material  and  manufacture  of  elements  to  be  cut  used  in release and locking. 

NOTE 

See 4.7.5.4.12c. 

The SMS shall specify the shock loads for release and locking devices. For  the  derivation  of  such  requirements,  see 4.7.5.4.12g. 

NOTE 

Verification requirements 

The SMS shall list the requirements for shock generation and susceptibility. f.

g.

h.

<7>

a.

NOTE 

See 4.8.2.11a. 

b.

The SMS shall list the limited‐life components lifetime requirements. 

NOTE 

See 4.8.2.15b. 

### Special remarks

### A.2.2

None. 

55 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Annex B (normative)- Mechanism design description (MDD) - DRD

- B.1  DRD identification

### Requirement identification and source document### B.1.1

This DRD is called from ECSS‐E‐ST‐33‐01, requirement 4.10a. 

### Purpose and objective

### B.1.2

The  purpose  of  the  mechanism  design  description  (MDD)  is  to  provide  the customer  with  a  comprehensive  understanding  of  the  mechanism  design  and functionality. 

- B.2  Expected response

### B.2.1

### Scope and content

<1>

a.

b.

Introduction, references and terminology 

The MDD shall contain a description of the purpose, objective, content and the reason prompting its preparation. 

NOTE 

For  example:  “This  document  describes  the functionality  and  design  of 

the  <name> mechanism for the <name> project. 

The MDD shall list: 

1.

the model standard of the mechanism being described; 

NOTE 

Examples  are  DM,  EM,  QM,  and  FM  for  which the definition is provided in ECSS‐E‐HB‐10‐02. 

2.

3.

the  list  of  documents  providing  additional  subsystem  design description; 

any  other  applicable  and  reference  documents  to  support  the generation of the document. 

c.

The MDD shall include any additional definition, abbreviation or symbol used. 

56 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 <2>  Mission and mechanism main functions 

a.

The  MDD  shall  describe  the  mission  and  the  role  of  the  mechanism  in achieving the mission.  

The primary functions of the mechanism shall be described. 

b.

<3>

a.

<4>

a.

Key requirements 

The  MDD  shall 

mechanism concept. 

include  the  requirements  that  drive  the  selected NOTE 

Examples  of  such  requirements  are  functional, operational, and imposed design solutions. 

Functional principle 

The MDD shall describe how the mechanism primary functions are broken down into their elementary functions. 

NOTE 

For example, use functional tree.   

b.

Schematic functional elements should be added to the tree.   

<5>

a.

<6>

a.

Detailed description of the mechanism 

The  MDD  shall  describe  the  mechanism  detailed  design,  including  the following: 

1.

2.

3.

4.

5.

6.

7.

product tree (sub assembly break down); 

physical design of the mechanism in all configurations; 

how each function is achieved; 

protection and redundancy implementation; 

general assembly drawings with cross sections or equivalent; 

interface descriptions (mechanical, thermal and electrical); 

static and dynamic envelopes. 

Performance and budgets 

The  MDD  shall  provide  informative  data  with  regard  to  performance, mass and power budgets. 

NOTE 

This  is  provided  for  information  only.  The contractual  values 

the verification files. 

are  provided 

in 

### Special remarks

### B.2.2

None. 

57 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Annex C (normative)Mechanism analytical verification (MAV) -DRD- C.1  DRD identification

### Requirement identification and source document### C.1.1

This DRD is called from ECSS‐ST‐E‐33‐01, requirement 4.10b. 

### Purpose and objective

### C.1.2

The  purpose  of  the  mechanism  analytical  verification  (MAV)  is  to  provide  the customer  with  a  comprehensive  functional  and  performance  analysis  of  the mechanism.  

- C.2  Expected response

### C.2.1

### Scope and content

<1>

a.

b.

Introduction, references and terminology 

The MAV shall contain a description of the purpose, objective, content and the reason prompting its preparation. 

NOTE 

For  example:  This  document  provides  all functional  and  performances  analyses  of  the “name” mechanism for the “name” project. This document  is  part  of  the  verification  files  and ensures that the mechanism is sized to meet the related requirements. 

The MAV shall list: 

1.

all  the  applicable  documents  regarding  requirements  related  to design and performance;  

the design definition file reference of the mechanism being analysed; the list of documents providing inputs to analyses presented in this document;  

2.

3.

58 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 NOTE 1  For 

example, 

analysis, and test reports. 

thermal  analysis, 

structural NOTE 2  Subsystems and components data to be included. 

4.

any  other  applicable  and  reference  documents  to  support  the generation of the document. 

c.

The MAV shall include any additional definition, abbreviation or symbol used. 

<2>  Mission and mechanism main functions 

a.

The  MAV  shall  describe  the  mission  and  the  role  of  the  mechanism  in achieving the mission.  

The primary functions of the mechanism shall be described. 

Analytical verification 

The  MAV  shall  provide  all  analyses  regarding  analytical  verification  as defined in 4.8.2 

For each of the analyses of C.2.1<3>a, the results shall be summarized in a table and compared to the requirements. 

NOTE 

Each  specific  analysis  can  be  provided  in  a separate document or grouped together. 

b.

<3>

a.

b.

### Special remarks

### C.2.2

None. 

59 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Annex D (normative)Mechanism user manual (MUM) - DRD- D.1  DRD identification

### Requirement identification and source document### D.1.1

This DRD is called from ECSS‐E‐ST‐33‐01, requirement 4.10c. 

### Purpose and objective

### D.1.2

The purpose of the mechanism user manual (MUM) is to provide the customer with  a  comprehensive  set  of 

instructions  for  storage, transportation,  handling,  integration  at  subsystem  or  system  level,  and  on ground and in‐orbit operation of the mechanism. 

information  and 

NOTE   Operational 

information 

instructions provided by the mechanism supplier are limited to mechanism level. 

and 

- D.2  Expected response

### D.2.1

### Scope and content

<1>

a.

b.

Introduction, references and terminology 

The user manual shall contain a description of the scope and applicability of the document. 

NOTE 

and 

handling, 

instructions 

For  example:  This  document  provides  all storage, information 

transportation, 

at subsystem  or  system  level,  and  on  ground  and in‐orbit  operation  of  the “name”  mechanism  for the “name” project. 

integration 

for 

The user manual shall include: 

1.

2.

3.

4.

the mechanism requirement specification; 

the delivered mechanism applicable CIDL; 

the list of consumables and spares; 

the list of GSE and special tools; 

60 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 the list of user manuals for GSE and special tools; 

the calibration data. 

5.

6.

The user manual shall include any additional definitions, abbreviations or symbols used. 

c.

<2>  Mission and mechanism main functions 

a.

The user manual shall describe the mission and the role of the mechanism in achieving the mission.  

The primary functions of the mechanism shall be described. 

b.

<3>

a.

<4>

a.

<5>

a.

b.

<6>

a.

Safety instructions 

The user manual shall present all aspects with regard to personnel safety and shall detail all necessary safety precautions.  

Traceability requirements 

The user manual shall define the information to be recorded after delivery. NOTE 

For example: Number of limited operations. 

Delivery configuration 

The  user  manual  shall  present  the  following  information  regarding  the mechanism delivery configuration: 

1.

short  description  of 

subassemblies; 

short  description  of  GSE  and  special  tools,    including  drawings  or pictures. 

the  mechanism  and  all  self  standing 2.

The description specified in D.2.1<5>a shall include drawings or pictures. Storage, transportation and handling 

The user manual shall describe the following topics: 

1.

2.

3.

4.

5.

6.

mechanism configuration for storage, transportation and handling; container characteristics and operation instructions; 

packing, and transportation instructions; 

unpacking and incoming inspections; 

handling and storage instructions; 

environmental  conditions  for  the  in    D.2.1<6>a.1.to    D.2.1<6>a.5. defined phases. 

NOTE 

Examples  of  such  environmental  conditions  are mechanical,  thermal,  hygrometry,  and  pressure, cleanliness. 

61 ![Im0](images/Im0)

![Im0](images/Im0)

<7>

a.

<8>

a.

<9>

a.

Interfaces definition 

ECSS‐E‐ST‐33‐01C 6 March 2009 The user manual shall provide the following information with regards to interfaces definition: 

1.

description of mechanical and thermal interfaces (including the list of applicable mechanical and thermal ICD); 

description  of  electrical  interfaces  (including  the  list  of  applicable electrical ICD); 

description  of  optical  interfaces  (including  the  list  of  applicable optical ICD). 

2.

3.

NOTE 

In  case  the  ICDs  are  provided  in  a  specific chapter  of  the  EIDP,  the  list  of  applicable  ICDs can be limited to the EIDP chapter reference.  

Integration instructions 

The user manual shall provide the following information with regards to integration instructions: 

1.

2.

integration sequence; 

preparation prior to integration, including 

(a)  mechanism and self standing subassemblies configuration; (b)  GSE and special tools to be used; 

(c)

(d)

(e)

(f)

(g)

step  by  step  mounting  instructions  including  torque  on  threaded fasteners,  alignment  provisions,  shims,  electrical  connections, intermediate inspections and checks; 

final inspections. 

items to be removed; 

specific precautions and safety instructions; 

cleaning instructions; 

environmental conditions for integration; 

detailed handling instructions for integration. 

3.

4.

NOTE 

For example, visual, electrical checks, clearances, and health checks. 

Onground operation instructions 

The user manual shall describe all activities to operate the mechanism on ground, including: 

1.

operational configuration; 

Preparation for start up: 

(a)

(b)  GSE and special tools to be used; 

(c)

(d)

items to be removed; 

specific  precautions  and  safety 

instructions 

limitations in terms of operation and performances; 

including 62 ECSS‐E‐ST‐33‐01C 6 March 2009 2.

3.

cleaning instructions; 

environmental conditions for operation. 

(e)

(f)

Step by step Start up operation instructions. 

For each operational mode  

(a)

(b)  GSE and special tools to be used; 

(c)

operational configuration; 

specific  precautions  and  safety 

instructions 

limitations in terms of operation and performances; 

environmental conditions for operation; 

step by step operation instructions; 

telemetry requirements and health monitoring; 

recovery contingencies. 

(d)

(e)

(f)

(g)

including NOTE 

Example  of  such  operational  modes  are  release, calibration, deployment, and pointing, scanning. 

<10>  Maintenance operations 

a.

The user manual shall describe all maintenance operations. 

NOTE 

For example: 

•  Time limited consumables replacement 

•  Cycles limited consumables replacement 

•  Periodic health check 

•  Periodic operations 

<11>

a.

b.

In‐orbit operation instructions 

The user manual shall describe all activities to operate the mechanism in‐orbit.  

For each operational mode  the following topics shall be described: 

1.

2.

3.

4.

5.

operational configuration; 

specific precautions including limitations in terms of operation; operation sequence; 

telemetry requirements and health monitoring; 

recovery contingencies. 

NOTE 

Examples of such operational modes are release, calibration, deployment, pointing, and scanning. 

### Special remarks

### D.2.2

None. 

63 ![Im0](images/Im0)

ECSS‐E‐ST‐33‐01C 6 March 2009 Annex E (informative)Documentation technical itemsTable E‐1 includes the mechanism documentation technical items, and the ECSS documents where they are covered. 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Document </td>
		<td>ECSS reference </td>
	</tr>
	<tr align="center">
		<td>Configuration item data </td>
		<td>ECSS‐M‐ST‐40 </td>
	</tr>
	<tr align="center">
		<td>Critical items </td>
		<td>ECSS‐Q‐ST‐10‐04 </td>
	</tr>
	<tr align="center">
		<td>Declared components </td>
		<td>ECSS‐Q‐ST‐60 </td>
	</tr>
	<tr align="center">
		<td>Declared materials, parts and processes </td>
		<td>ECSS‐Q‐ST‐70 </td>
	</tr>
	<tr align="center">
		<td>Design description </td>
		<td>ECSS‐E‐ST‐33‐01  Annex B</td>
	</tr>
	<tr align="center">
		<td>Design, development and verification approach </td>
		<td>ECSS‐E‐ST‐10‐02 </td>
	</tr>
	<tr align="center">
		<td>Failure modes and effects criticality analysis (FMECA) </td>
		<td>ECSS‐Q‐ST‐30‐02 </td>
	</tr>
	<tr align="center">
		<td>Fracture control </td>
		<td>ECSS‐E‐ST‐32‐01 </td>
	</tr>
	<tr align="center">
		<td>Analytical verification </td>
		<td>ECSS‐E‐ST‐33‐01  Annex C</td>
	</tr>
	<tr align="center">
		<td>Hazard and safety analysis </td>
		<td>ECSS‐Q‐ST‐40‐02 </td>
	</tr>
	<tr align="center">
		<td>Interface control </td>
		<td>ECSS‐E‐ST‐10 </td>
	</tr>
	<tr align="center">
		<td>Manufacturing file </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Mechanism user manual </td>
		<td>ECSS‐E‐ST‐33‐01  Annex D</td>
	</tr>
	<tr align="center">
		<td>Qualification status </td>
		<td>ECSS‐Q‐ST‐10 </td>
	</tr>
	<tr align="center">
		<td>Requirements compliance </td>
		<td>ECSS‐E‐ST‐10‐02 </td>
	</tr>
	<tr align="center">
		<td>Thermal analysis </td>
		<td>ECSS‐E‐ST‐31 </td>
	</tr>
	<tr align="center">
		<td>Structural analysis </td>
		<td>ECSS‐E‐ST‐32 </td>
	</tr>
</table>

 

 

64 ECSS‐E‐ST‐33‐01C 6 March 2009 BibliographyECSS‐S‐ST‐00 

ECSS‐E‐ST‐10 

ECSS‐E‐HB‐10‐02 

ECSS‐E‐ST‐10‐04 

ECSS‐E‐ST‐32‐01 

ECSS‐E‐ST‐10‐04 

ECSS‐E‐ST‐70‐11 

ECSS‐M‐ST‐40 

ECSS‐Q‐ST‐10 

ECSS‐Q‐ST‐10‐04 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐30‐02 

ECSS‐Q‐ST‐30‐11 

ECSS‐Q‐ST‐40‐02 

ECSS‐Q‐ST‐60 

ECSS‐Q‐ST‐70‐01 

ECSS‐Q‐ST‐70‐02 

ECSS‐Q‐ST‐70‐46 

 

ECSS system – Description, implementation and general requirements 

Space engineering – System engineering general 

requirements 

Space engineering – Verification handbook 

Space engineering – Space environment 

Space engineering – Fracture control 

Space engineering – Space environment 

Space engineering – Space segment operability 

Space project management – Configuration and 

information management 

Space engineering – Product assurance management Space product assurance – Critical‐item control 

Space product assurance – Quality assurance 

Space product assurance – Failure modes, effects (and criticality) analysis (FMEA/FMECA) 

Space product assurance – Derating – EEE components Space product assurance – Hazard analysis 

Space product assurance – Electrical, electronic and 

electromechanical (EEE) components 

Space product assurance – Contamination and 

cleanliness control 

Space product assurance – Thermal vacuum outgassing test for the screening of space materials 

Space product assurance – Requirements for 

manufacturing and procurement of threaded fasteners 65 ![Im0](images/Im0)

