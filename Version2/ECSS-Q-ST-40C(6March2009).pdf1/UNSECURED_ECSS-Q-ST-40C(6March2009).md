ECSS-Q-ST-40C6 March 2009Space product

assurance

Safety

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐Q‐ST‐40C  Working  Group,  reviewed  by  the  ECSS 

- Executive Secretariat and approved by the ECSS Technical Authority. 

- Disclaimer

- ECSS does not provide any warranty whatsoever, whether expressed, implied, or statutory, including, 

- but not limited to, any warranty of merchantability or fitness for a particular purpose or any warranty 

- that  the  contents  of  the  item  are  error‐free.  In  no  respect  shall  ECSS  incur  any  liability  for  any 

- damages, including, but not limited to, direct, indirect, special, or consequential damages arising out 

- of, resulting from, or in any way connected to the use of this Standard, whether or not based upon 

- warranty, business agreement, tort, or otherwise; whether or not injury was sustained by persons or 

- property or otherwise; and whether or not loss was sustained from, or arose out of, the results of, the 

- item, or any services that may be provided by ECSS. 

- Published by:  

- Copyright:

ESA Requirements and Standards Division 

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2009 © by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐Q‐40A  19 April 1996 </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐40B  17 May 2002 </td>
		<td>Second issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐40C  6 March 2009 </td>
		<td>Third issue  The main changes between ECSS‐Q‐40B and the current version are the  following:  •  Complete and thorough review of ECSS‐Q‐40B with the focus on  simplification and streamlining to improve clarity and consistency  of requirements.  • •  Applicability guidelines of ECSS‐Q‐ST‐40 to the different space  systems has been defined (see applicability matrix provided in  Annex E).  System safety programme requirements reworked, i.e. the system  safety programme supports the risk management process  described in ECSS‐M‐ST‐80.  Space debris mitigation streamlined.  • •  Atmospheric re‐entry addressed.  • • • •  Common scheme for consequence severity classification used in  Safety design principles reworked.  Safety risk reduction and control updated.  Safety analysis requirements and techniques updated.  ECSS‐Q‐ST‐30C and ECSS‐Q‐ST‐40C.  • Identification and control of safety‐critical functions updated.  •  Established link to ECSS standard on “Critical‐item control”  (ECSS‐Q‐ST‐10‐04).  •  Harmonized ECSS‐Q‐ST‐40C with associated Level 3 standards.  • Informative annex on European legislation and ‘CE’ marking  added (Annex F).  •  DRDs revisited and updated.  •  Document reworked to be in compliance with ECSS standards  drafting rules.   </td>
	</tr>
</table>

3 ECSS‐Q‐ST‐40C 6 March 2009 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................8

- 2 Normative references.............................................................................................9

- 3 Terms, definitions and abbreviated terms..........................................................10

- 3.1  Terms from other standards .....................................................................................10

- 3.2  Terms specific to the present standard ....................................................................10

- 3.3  Abbreviated terms ....................................................................................................12

- 4 Safety principles...................................................................................................14

- 4.1  Objective ..................................................................................................................14

- 4.2  Policy........................................................................................................................14

4.2.1  General.......................................................................................................14Implementation...........................................................................................144.2.2

- 4.3  Safety programme....................................................................................................15

- 5 Safety programme ................................................................................................16

- 5.1  Scope .......................................................................................................................16

- 5.2  Safety programme plan ............................................................................................16

- 5.3  Conformance............................................................................................................16

- 5.4  Safety organization...................................................................................................17

Safety manager ..........................................................................................175.4.1

Safety manager access and authority ........................................................175.4.2

Safety audits...............................................................................................185.4.3

Approval of documentation.........................................................................185.4.4

5.4.5

Approval of hazardous operations..............................................................185.4.6  Representation on boards ..........................................................................18Safety approval authority............................................................................185.4.7

- 5.5  Safety risk assessment and control..........................................................................19

- 5.6  Safety critical items ..................................................................................................19

- 5.7  Project phases and safety review cycle ...................................................................19

4 ![Im0](images/Im0)

![Im0](images/Im0)

5.7.1

5.7.2

5.7.3

ECSS‐Q‐ST‐40C 6 March 2009 Safety program tasks and reviews .............................................................19Progress meetings......................................................................................23Safety reviews ............................................................................................23- 5.8  Safety compliance demonstration ............................................................................23

- 5.9  Safety training ..........................................................................................................24

5.9.1  General.......................................................................................................245.9.2

Product specific training .............................................................................245.9.3  General awareness briefings......................................................................245.9.4

Basic technical training...............................................................................25Training records..........................................................................................255.9.5

- 5.10  Accident-incident reporting and investigation...........................................................25

- 5.11  Safety documentation...............................................................................................25

5.11.1  General.......................................................................................................255.11.2  Safety data package...................................................................................255.11.3  Safety deviations and waivers ....................................................................265.11.4  Safety lessons learned ...............................................................................275.11.5  Documentation of safety critical items ........................................................27- 6 Safety engineering ...............................................................................................28

- 6.1  Overview ..................................................................................................................28

- 6.2  Safety requirements identification and traceability ...................................................28

- 6.3  Safety design objectives...........................................................................................28

6.3.1

Safety policy and principles........................................................................286.3.2  Design selection .........................................................................................286.3.3  Hazard reduction precedence ....................................................................296.3.4

Environmental compatibility........................................................................316.3.5

External services ........................................................................................316.3.6  Hazard detection - signalling and safing.....................................................31Space debris mitigation ..............................................................................326.3.7

Atmospheric re-entry ..................................................................................326.3.8

6.3.9

Safety of Earth return missions ..................................................................326.3.10  Safety of human spaceflight missions ........................................................336.3.11  Access........................................................................................................33- 6.4  Safety risk reduction and control ..............................................................................33

Severity of hazardous event.......................................................................336.4.1

Failure tolerance requirements...................................................................356.4.2

6.4.3  Design for minimum risk .............................................................................366.4.4

Probabilistic safety targets..........................................................................375 ![Im0](images/Im0)

- 6.5

ECSS‐Q‐ST‐40C 6 March 2009 Identification and control of safety-critical functions .................................................38Identification ...............................................................................................386.5.1

Inadvertent operation..................................................................................386.5.2

6.5.3

Status information.......................................................................................38Safe shutdown and failure tolerance requirements ....................................386.5.4

6.5.5

Electronic, electrical, electromechanical components ................................38Software functions......................................................................................396.5.6

- 6.6  Operational Safety....................................................................................................39

Basic requirements.....................................................................................396.6.1

6.6.2

Flight operations and mission control .........................................................406.6.3  Ground operations......................................................................................41- 7 Safety analysis requirements and techniques...................................................43

- 7.1  Overview ..................................................................................................................43

- 7.2  General.....................................................................................................................43

- 7.3  Assessment and allocation of requirements.............................................................44

7.3.1

Safety requirements ...................................................................................447.3.2

Additional safety requirements ...................................................................447.3.3  Define safety requirements - functions .......................................................447.3.4  Define safety requirements - subsystems ..................................................44Justification.................................................................................................447.3.5

7.3.6

Functional and subsystem specification.....................................................44- 7.4  Safety analyses during the project life cycle ............................................................44

- 7.5  Safety analyses ........................................................................................................45

7.5.1  General.......................................................................................................457.5.2  Hazard analysis..........................................................................................45Safety risk assessment...............................................................................467.5.3

7.5.4

Supporting assessment and analysis .........................................................46- 8 Safety verification.................................................................................................50

- 8.1  General.....................................................................................................................50

- 8.2  Hazard reporting and review ....................................................................................50

8.2.1  Hazard reporting system ............................................................................508.2.2

Safety status review ...................................................................................508.2.3  Documentation ...........................................................................................50- 8.3  Safety verification methods ......................................................................................51

Verification engineering and planning ........................................................518.3.1

8.3.2  Methods and reports...................................................................................518.3.3

Analysis ......................................................................................................516 ![Im0](images/Im0)

8.3.4

8.3.5

ECSS‐Q‐ST‐40C 6 March 2009 Inspections .................................................................................................51Verification and approval............................................................................52- 8.4  Verification of safety-critical functions ......................................................................52

8.4.1

Validation....................................................................................................528.4.2  Qualification................................................................................................528.4.3

Failure tests................................................................................................53Verification of design or operational characteristics ...................................538.4.4

8.4.5

Safety verification testing............................................................................53- 8.5  Hazard close-out ......................................................................................................53

8.5.1

Safety assurance verification......................................................................538.5.2  Hazard close-out verification ......................................................................54- 8.6  Declaration of conformity of ground equipment........................................................54

- Annex A (informative) Analyses applicability matrix ...........................................55

- Annex B (normative) Safety programme plan - DRD............................................57

- Annex C (normative) Safety verification tracking log (SVTL) DRD .....................59

- Annex D (normative) Safety analysis report including hazard reports -

- DRD ......................................................................................................................63

- Annex E (informative) Criteria for probabilistic safety targets............................65

- Annex F (informative) Applicability guidelines.....................................................66

- Annex G (informative) European legislation and ‘CE’ marking...........................72

- Bibliography.............................................................................................................75

 

- Tables

- Table 6-1: Severity of consequences.....................................................................................35

 

7 ECSS‐Q‐ST‐40C 6 March 2009 ScopeThis  Standard  defines  the  safety  programme  and  the  safety  technical requirements aiming to protect flight and ground personnel, the launch vehicle, associated payloads, ground support equipment, the general public, public and private  property,  the  space  system  and  associated  segments  and  the environment from hazards associated with European space systems. 

This Standard is applicable to all European space projects. 

This standard may be tailored for the specific characteristic and constraints of a space project in conformance with ECSS‐S‐ST‐00. 

 

8 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐E‐ST‐10 

ECSS system – Glossary of terms 

Space engineering – System engineering general 

requirements 

Space engineering – Fracture control 

Space engineering – Structural factors of safety for spaceflight hardware 

Space engineering – Software general requirements Space project management – Project planning and 

implementation 

Space project management – Configuration and 

information management 

Space project management – Risk management 

Space product assurance – Product assurance 

management 

Space product assurance – Critical‐item control 

Space product assurance – Quality assurance 

Space product assurance – Dependability 

Space product assurance – Electrical, electronic and electromechanical (EEE) components 

Space product assurance – Materials, mechanical parts and processes 

Space product assurance – Software product assurance ECSS‐E‐ST‐32‐01 

ECSS‐E‐ST‐32‐10 

ECSS‐E‐ST‐40 

ECSS‐M‐ST‐10 

ECSS‐M‐ST‐40 

ECSS‐M‐ST‐80 

ECSS‐Q‐ST‐10 

ECSS‐Q‐ST‐10‐04 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐30 

ECSS‐Q‐ST‐60 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐80 

9 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 apply (see in clause 3.2 differences for ʺfail‐safeʺ and ʺsystemʺ), in particular for the following terms: 

accident 

failure 

hazard 

NOTE 

(Specific to this Standard) Hazards are potential 

threats  to  the  safety  of  a  system.  They  are  not 

events. 

hazardous event 

inhibit 

risk 

safety 

NOTE 

(Specific to this Standard) Spacecraft is part of 

flight system 

safety‐critical function 

- 3.2  Terms specific to the present standard

cause

3.2.1

action or condition by which a hazardous event is initiated (an initiating event) NOTE 1  The  cause  can  arise  as  the  result  of  failure, 

human  error,  design  inadequacy,  induced  or 

natural  environment,  system  configuration  or 

operational mode(s). 

NOTE 2  This  definition  is  specific  to  this  Standard, 

when used in the context of hazard analysis. 

10 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 fail-safe

3.2.2

design  property  of  a  system  (or  part  of  it),  which  prevents  its  failures  from resulting in critical or catastrophic consequences 

NOTE 

This  definition  is  specific  to  this  Standard 

(different from ECSS‐S‐ST‐00‐01), for use in the 

context of safety analysis. 

hazard control

3.2.3

preventive  or  mitigation  measure,  associated  to  a  hazard  scenario,  which  is introduced  into  the  system  design  and  operation  to  avoid  the  events  or  to interrupt their propagation to consequence 

hazardous command

3.2.4

command that can remove an inhibit to a safety‐critical function or activate a hazardous subsystem 

hazard reduction

3.2.5

process of elimination or minimization and control of hazards 

hazard scenario

3.2.6

sequence  of  events  leading  from  the  initial  cause  to  the  unwanted  safety consequence 

NOTE 

The cause can be a single initiating event, or an 

additional  action  or  a  change  of  condition 

activating a dormant problem. 

likelihood

3.2.7

probability of occurrence or the measure for the occurrence rate 

operator error

3.2.8

failure  of  an  operator  to  perform  an  action  as  required  or  trained  or  the inadvertent or incorrect action of an operator 

[ISO 14620‐1] 

safety approval authority

3.2.9

entity  that  defines  or  makes  applicable,  for a  given  project,  detailed  technical safety requirements, and reviews their implementation  

safety audit

3.2.10

independent examination to determine whether the procedures specific to the safety requirements are implemented effectively and are suitable to achieve the specified objectives 

11 ![Im0](images/Im0)

![Im0](images/Im0)

safety risk

3.2.11

measure  of  the  threat  to  safety  posed  by  the  hazard  scenarios  and  their consequences 

ECSS‐Q‐ST‐40C 6 March 2009 NOTE 1  Safety risk is always associated with a specific 

hazard scenario or a particular set of scenarios. 

The  risk  posed  by  a  single  scenario  is  called 

individual scenario risk. The risk posed by a set 

of  scenarios  with  the  same  top  consequence  is 

called overall risk. 

NOTE 2  The magnitude of a safety risk is a combination 

of  the  severity  and  the  likelihood  of  the 

consequence. 

safety status parameter

3.2.12

parameter that makes it possible to assess the status of an implemented hazard control 

system

3.2.13

set  of  interdependent  elements  constituted  to  achieve  a  given  objective  by performing a specified function 

[IEC 50:1992] 

NOTE 

The system is considered to be separated from 

the environment and other external systems by 

an  imaginary  surface  which  cuts  the  links 

between  them  and  the  considered  system. 

Through  these  links,  the  system  is  affected  by 

the environment, is acted upon by the external 

systems, or acts itself on the environment or the 

external systems. 

system safety

3.2.14

application of engineering and management principles, criteria, and techniques to  optimize  all  aspects  of  safety  within  the  constraints  of  operational effectiveness, time, and cost throughout all phases of the system life cycle  

[ISO 14620‐1] 

- 3.3  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

 

Abbreviation  Meaning 

AR 

CCB 

CDR 

acceptance review 

configuration control board 

critical design review 

12 ECSS‐Q‐ST‐40C 6 March 2009 CRR 

EEE 

ELR 

FMEA 

FMECA 

FRR 

FTA 

GSE 

IEC 

LRR 

MIP 

NRB 

NUREG‐CR 

ORR 

PDR 

PRR 

QR 

SRR 

SVTL 

TRB 

 

commissioning result review  

electronic, electrical, electromechanical 

end‐of‐life review 

failure modes and effects analysis 

failure modes, effects and criticality analysis 

flight readiness review 

fault tree analysis 

ground support equipment 

International Electrotechnical Commission 

launch readiness review 

mandatory inspection point 

nonconformance review board 

US Nuclear Regulatory Commission contractor report 

operational readiness review 

preliminary design review 

preliminary requirements review 

qualification review 

system requirements review 

safety verification tracking log 

test review board 

13 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Safety principles- 4.1  Objective

The objective of safety assurance is to ensure that all safety risks associated with the  design,  development,  production  and  operations  of  space  product  are adequately  identified,  assessed,  minimized,  controlled  and  finally  accepted through the implementation of a safety assurance programme. 

- 4.2  Policy

4.2.1  General

The ECSS safety policy is to:  

•

⎯

⎯

⎯

⎯

ensure that space systems do not cause a hazard to, in order of priority:  ⎯

human life,  

the environment,  

public and private property (including launch facilities),  

spacecraft and launcher,  

ground support equipment and facilities,  

•

•

•

determine and evaluate the safety risks associated with project activities,  minimize safety risks in a technically effective and cost effective manner,  ensure adequate verification of safety control measures.  

Implementation

4.2.2

The ECSS safety policy is implemented by applying a safety programme which ensures that:  

•

•

•

•

safety is designed into the system, 

safety controls are adequately implemented in the verification plan,  

safety requirements including launch centre safety regulations are met,  hazards  are  identified,  and  eliminated  or,  where  this  is  not  possible, minimized, ranked and controlled  in accordance with project objectives in  a  manner acceptable  to  the  customer  and  to  the safety  organisations involved in the implementation of the mission. 

14 ![Im0](images/Im0)

![Im0](images/Im0)

- 4.3  Safety programme

ECSS‐Q‐ST‐40C 6 March 2009 The safety programme comprises the: 

•

identification  and  control  of  all  safety  related  risks  with  respect  to  the design, development and operations of space products,  

assessment of the risks based on qualitative and quantitative analysis as appropriate,  

application of a hazard reduction precedence and of control measures of the residual risks. 

•

•

15 ECSS‐Q‐ST‐40C 6 March 2009 Safety programme- 5.1  Scope

a.

b.

The supplier shall establish and maintain a safety programme to assure conformance with project safety policy and requirements. 

The  safety  programme  shall  establish  a  safety  management  system  to implement  provisions  of  this  Standard  ‐  commensurate  with  the programme requirements and tailored by the customer  

NOTE 1  For tailoring, refer to clause 1. 

NOTE 2  The system safety programme requirements are 

subject  to  tailoring,  without  diminishing  the 

intent  to  protect  flight  and  ground  personnel, 

the launch vehicle, associated payloads, ground 

support  equipment,  the  general  public,  public 

and  private  property,  the  space  system  and 

associated segments and the environment from 

hazards associated with space systems. 

NOTE 3  As  support  to  tailoring,  informative  Annex  F 

provides  a  guideline  for  determining 

the 

applicability of this standard depending on the 

type of project. 

- 5.2

Safety programme plan

a.

b.

The  supplier  shall  establish  and  maintain  a  safety  programme  plan  in conformance with the DRD in Annex B. 

NOTE 

The  plan  can  either  be  included  as  part  of  an 

overall  project  product  assurance  plan  or  as  a 

separate safety programme plan. 

The supplier shall cover, in his safety programme plan, the safety tasks for the project phases in conformance with 5.7.1. 

- 5.3  Conformance

a.

The  supplier  shall  comply  with  all  applicable  national  or  international safety regulations. 

16 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 b.

c.

The launch site safety regulations and rules shall be applied. 

The implementation of safety requirements shall not be compromised by other requirements. 

NOTE 

For example: security requirements. 

- 5.4  Safety organization

Safety manager

5.4.1

a.

b.

Each  supplier  shall  appoint  a  safety  manager  who  has  appropriate training or experience. 

The 

safety  manager 

independence to: 

1.

shall  have  organisational  authority  and establish and maintain a safety programme in accordance with the project safety requirements, 

manage  all  safety  assurance  aspects  of  the  design  of  the  system (including  software)  and  its  operation  in  accordance  with  the Safety Plan, 

coordinate the interfaces: 

(a)  with  the  relevant  bodies 

in  the  project 2.

3.

involved 

in accordance with the safety plan, 

(b)  with the safety launcher authority. 

NOTE   Depending  on  the  project  safety  criticality,  the 

safety  manager  can  be  combined  with  other 

functions (e.g. PA manager) when agreed with 

the customer. 

5.4.2

Safety manager access and authority

5.4.2.1  Access

a.

The safety manager shall: 

1.

have  the  right  of  access  to  safety‐related  data  relevant  to  project safety in conformance with ECSS‐M‐ST‐40,  

have  unimpeded  access  to  any  management 

organizational constraint on any aspect of project safety. 

level  without 2.

5.4.2.2  Authority

a.

The safety manager or safety relevant authority shall have the authority to: 

1.

reject  any  project  document,  or  to  stop  any  project  activity  that does not conform to approved safety requirements or procedures, 17 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 2.

interrupt  hazardous  operations  when  it  becomes  clear  by  the Safety Manager that the operation does not conform to the agreed measures defined in the corresponding hazard report and derived approved hazard procedure. 

Safety audits

The supplier shall perform safety audits or reviews to verify compliance to project safety policy and requirements. 

The safety audits shall be in accordance with ECSS‐M‐ST‐10 and ECSS‐Q‐ST‐10. 

NOTE 

The  safety  audits  can  be  part  of  the  project 

audits. 

c.

The customer shall be informed of the audit schedule. 

5.4.3

a.

b.

5.4.4

a.

5.4.5

a.

5.4.6

a.

b.

5.4.7

a.

Approval of documentation

Documentation related to safety shall be approved by the safety manager upon  his  verification  of  completeness,  compliance  with  stated  safety requirements  and  formal  closeout  of  open  safety  verification  items  (as defined and agreed during safety audits and reviews). 

Approval of hazardous operations

The safety manager (or a designated representative) shall have concluded the  review  of,  and  approved,  any  hazardous  operation  before  it  is executed. 

Representation on boards

The  safety  manager  or  designated  delegate  shall  be  represented  at configuration  control  boards  (CCBs),  nonconformance  review  boards (NRBs),  test  review  board  (TRBs),  and  at  qualification,  and  acceptance reviews,  where  safety  requirements  and  safety‐critical  functions  are involved. 

The safety function shall be further represented at all boards dealing with health matters where exposure or endurance limits are defined for flight and ground crews. 

Safety approval authority

The safety approval authority shall: 

1.

2.

3.

4.

review and disposes the safety data submittals, 

approve the close‐out of hazards, 

decide on deviations and waivers, and finally 

accept the statement of safety compliance. 

18 ![Im0](images/Im0)

![Im0](images/Im0)

- 5.5  Safety risk assessment and control

ECSS‐Q‐ST‐40C 6 March 2009 a.

b.

c.

The safety risk identification, reduction and control shall be part of the projectʹs risk management process as specified in ECSS‐M‐ST‐80. 

Safety risk identification, reduction and control shall be a continuous and iterative process throughout the project life cycle, encompassing 

1.

2.

3.

4.

5.

For 

identification  of  hazards  and  associated  safety  risks, consideration  shall  be  given  to  past  experience,  studies,  ground  and flight tests, reviews, the industrial process as well as the operational use. allocation of safety requirements; 

hazard and safety risk identification; 

evaluation (including categorisation) of consequence severity; 

hazard and safety risk reduction and control; 

close out and acceptance of residual risk. 

the 

- 5.6  Safety critical items

a.

The safety critical items shall be part of the projectʹs overall critical items control programme as specified in ECSS‐Q‐ST‐10‐04. 

- 5.7  Project phases and safety review cycle

5.7.1

Safety program tasks and reviews

5.7.1.1  Mission analysis/Needs identification - Phase 0

a.

Safety analysis shall support the identification of sources of safety risk as well  as  the  performance  of  preliminary  trade‐off  analyses  between alternative system concepts. 

The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

b.

2.

3.

4.

5.

6.

Analyse  safety  requirements  and  lessons‐learnt  associated  with similar previous missions; 

Perform preliminary hazard analysis of the proposed system and operations concept to support concept trade‐offs; 

Perform comparative safety risk assessment of the concept options; Identify the relevant project safety requirements; 

Plan safety activities for the feasibility phase; 

Support the mission definition review. 

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

19 ![Im0](images/Im0)

5.7.1.2

a.

b.

c.

Feasibility - Phase A

ECSS‐Q‐ST‐40C 6 March 2009 Safety analysis shall support trade‐off analyses in arriving at the concept that  has  acceptable  safety  risk  considering  the  project  and  mission constraints.  

The  design  technology  selected  and  the  operational  concept  to  be implemented  shall  be  selected  based  on  the  analysis  data for  the  safest system architecture to eliminate or reduce hazards to acceptable levels. The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

Commence hazard analyses of the design and operations concepts in  order  to  identify  applicable  system  level  hazards,  hazardous conditions, and potential hazardous events and consequences;  Support concept trades by identifying safety critical aspects of the concept options; 

Apply  hazard  elimination  and  minimization  and  make  safety recommendations;  

Perform  comparative  safety  risk  assessments  of  the  concept options;  

Identify system level safety critical functions; 

Identify system level project specific safety requirements;  

Plan safety activities for the project definition phase;  

Support the preliminary requirements review.  

2.

3.

4.

5.

6.

7.

8.

5.7.1.3

a.

b.

c.

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

Preliminary definition - Phase B

The  safety  analysis  shall  support  a  continued  and  more  detailed  safety optimization of the system design and operations and the identification of technical safety requirements and their applicability. 

The  analysis  shall  also  provide  inputs  to  safety  risk  assessment  in support of safety risk evaluation, the identification of risk contributors in the design and in the operational concept. 

The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

Update hazard analysis in support of design and mission concept definition  activities;  identify  additional  project  specific  safety requirements;  

Update  safety  critical  functions  identification,  and  define  the failure tolerance requirements;  

Identify emergency, warning, and caution situations; 

Update  the  system  safety  risk  assessment  as  part  of  the contribution  provided  by 

the  risk management process; 

the  safety  domain 

2.

3.

4.

to 

20 ECSS‐Q‐ST‐40C 6 March 2009 5.

6.

7.

8.

9.

Identify project safety requirements;  

Ensure  that  project  requirement  documentation  and  activities comply with project safety requirements; 

Support  a  system  requirements  review  and  preliminary  design review;  

Plan verification of safety requirements implementation;  

Prepare the safety plan for the detailed definition, production and qualification phase.  

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

5.7.1.4  Detailed definition, production and qualification

testing - Phase C/D

a.

b.

c.

d.

Safety  analysis  shall  support  detailed  design,  production,  qualification, testing. 

Safety analysis shall also support operational safety optimization, safety requirements implementation evaluation, risk reduction verification, and hazard and risk acceptance. 

Analysis of operations shall also support the identification of emergency and  contingency  response  planning  and  training  requirements,  and  the development of procedures. 

The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

2.

3.

Perform detailed system level hazard analysis;  

Perform supporting safety analysis; 

Update the project technical safety requirements to incorporate the results of safety analyses;  

Ensure 

implementation  and  verification programme covers identified hazard control verification activities;  the  project 

that 

4.

5.

6.

7.

NOTE 

For example: reviews, inspections, analyses and 

tests. 

Update  safety  critical  functions  identification,  failure  tolerance requirements, and identify safety critical items;  

Implement control programme for safety critical items;  

Perform safety risk assessment in support of design improvement, project  resource  apportionment,  control  programme  for  safety critical items and project reviews;  

8.  Monitor verification of safety requirements implementation;  

9.

10.  Check  that  all  open  verification  items  are  recorded  and  agreed Verify and document hazard control implementation;  

11.

procedures are in place; 

Support the critical design review, the qualification review and the acceptance review; 

21 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 12.

13.

Perform project internal safety reviews and internal audits;  

Identify, monitor and control project assembly, integration, testing and  handling  operations  which  are  potentially  hazardous  to personnel or hardware;  

14.  Review  and  approve  hazardous  and  safety  critical  operational procedures; 

Perform accident‐incident reporting and investigation;  

Support  customer  safety 

milestones; 

Prepare a project safety “lessons‐learned” report;  

Prepare operational phase safety plan.  

15.

16.

17.

18.

reviews  at  defined  programme b.

c.

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

5.7.1.5  Utilization - Phase E

a.

Safety analysis shall evaluate design and operational changes for impact to safety, assuring that safety margins are maintained and that operations are conducted within accepted risk. 

The  analysis shall also  support  the  evaluation  of  operational anomalies for impact to safety, and the continued evaluation of risk trends. 

The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

2.

3.

4.

5.

Issue the operational phase safety plan; 

Review operational procedures;  

Approve safety critical operational procedures;  

Identify and monitor hazardous operations;  

Support the flight readiness review, operational readiness review, launch readiness review and flight qualification reviews; 

Support ground and flight operations;  

Perform safety critical items control;  

6.

7.

8.  Monitor  and  assess  evolution  of  the  system  configuration  and 9.

operations resulting from design fixes and updates; 

Update hazard analyses and implement additional hazard controls as necessary;  

Investigate safety related flight anomalies and trends;  

10.

11.  Update safety risk assessment as necessary to support operational decisions; 

Prepare disposal phase safety plan.  

12.

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

22 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 5.7.1.6  Disposal - Phase F

a.

b.

c.

Safety  analysis  shall  evaluate  all  disposal  operations  and  associated hazards.  

Disposal  solutions  shall  be  identified  which  meet  the  projectʹs  safety requirements. 

The following safety programme tasks shall apply for human spaceflight programmes and safety critical systems: 

1.

2.

Perform hazard analysis with respect to the disposal operations; Check that the disposal operation conforms to international safety regulations by performing the necessary safety analysis; 

Review the procedures of the disposal operations; 

Support the mission close‐out review. 

3.

4.

NOTE 

These tasks should also serve as a guideline for 

other space programmes. 

Progress meetings

The supplier shall hold regular safety status and progress meetings with the customer and his lower tier suppliers as part of the project progress meetings as specified in ECSS‐M‐ST‐10.  

The relevant customer and supplier specialists shall attend the meetings. 5.7.2

a.

b.

5.7.3

a.

Safety reviews

The customer shall define, conduct and chair the safety reviews to ensure satisfactory  implementation  of  safety  programme  and  technical  safety requirements.  

NOTE   A supplier is considered as a customer vis‐à‐vis 

its  lower  tier  suppliers  (as  defined  in  ECSS‐S‐

ST‐00). 

b.

c.

d.

The  supplier  shall  support  safety  reviews  by  the  customer  and  the relevant  safety  approval  authority,  as  specified  in  the  relevant  review plans.  

Each supplier participating in a safety review shall prepare, and submit for review, the safety data package. 

Safety reviews shall be performed, and the review objectives achieved, in conformance with clause 5.7.1. 

- 5.8  Safety compliance demonstration

a.

The  supplier  shall  provide  a  statement  of  safety  compliance  to demonstrate  that  the  space  system  elements  conform  to  stated  safety requirements.  

23 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 b.

c.

The supplier shall include in his statement of compliance a statement that open verifications are followed up in the safety verification tracking log (SVTL),  as  defined  in  clause  8.5.1,  and  do  not  affect  further  safe processing. 

The  project  shall  provide  to  the  safety  approval  authority  all  safety‐related  information  for  their  acceptance  of  the  statement  of  safety compliance. 

- 5.9  Safety training

5.9.1  General

a.

Safety  training  shall  be  part  of  the  overall  training  in  accordance  with ECSS‐Q‐ST‐20. 

All  safety  related  training  of  any  personnel  working  ‐  permanently  or occasionally ‐ with system elements that can have hazardous properties shall have three major aspects: 

1.

general  awareness  briefings  on  safety  measures  to  be  taken  at  a given location or working environment; 

basic technical training in the required safety techniques and skills which 

function  under consideration; 

is  a  prerequisite 

the 

job 

to 

fulfil 

NOTE 

For  example:  inspection,  test,  maintenance  or 

integration. 

product specific training that focuses on the hazards related to the specific system element. 

Product specific training

The  supplier shall identify  the  need  for  product  specific  safety  training and  implement  the  corresponding  safety  training  programme  for  all relevant parties.  

The supplier shall inform the customer of any safety training identified by  him  as  necessary  for  the  flight  operations  crew  or  mission  control personnel, together with a definition of the type of training required and its scope. 

The supplier shall support the implementation of the customerʹs training programme for the flight operations crew or mission control personnel. 2.

3.

5.9.2

a.

b.

b.

c.

5.9.3  General awareness briefings

a.

All  personnel  accessing  the  area  where  the  product  is  processed  shall participate previously in the general safety awareness briefing. 

24 ![Im0](images/Im0)

![Im0](images/Im0)

Basic technical training

ECSS‐Q‐ST‐40C 6 March 2009 The  supplier  shall  provide  basic  technical  training  to  all  project engineering and safety personnel working with hazardous products. 

5.9.4

a.

5.9.5

a.

Training records

The supplier shall maintain records of personnel having received safety training in accordance with ECSS‐Q‐ST‐20. 

- 5.10  Accident-incident reporting and investigation

a.

b.

c.

d.

e.

f.

The  supplier  shall  report  to  the  customer  all  accidents  and  incidents occurred during project activities under the control of the supplier or his lower tier suppliers that affect the system element.  

The  supplier  shall  support  ‐  at  request  ‐  project  related  accident  and incident  investigations  that  occur  outside  of  the  supplier’s  control  or facility. 

The  supplier  shall  coordinate  the  investigation  activities  in  cooperation with other supplier functional departments and lower tier suppliers. 

The accident or incident investigation report shall be formally closed by the supplier upon approval by the customer. 

If the conclusion of the assessment is that the accident‐incident has had an effect on the project, i.e. the safety of the product or its operation, the organisations safety representative shall be informed. 

In  case  of  5.10e.,  the  accident‐incident  report  shall  become  part  of  the projectʹs safety data and is documented in the safety data package. 

- 5.11  Safety documentation

5.11.1  General

a.

to  support 

The  supplier  shall  maintain,  as  part  of  the  project  documentation,  all safety‐related  data 

reviews  and  safety  compliance demonstration. 

The customer shall be given access to this data on request during audits, safety  reviews  and  meetings  held  at  the  supplier’s  premises  in accordance with ECSS‐M‐ST‐40. 

b.

5.11.2  Safety data package

a.

The  supplier  shall  submit  a  safety  data  package  (SDP)  to  support reviews. 

NOTE 

This  can  be  a  stand‐alone  package  or  be 

integrated  into  the  overall  data  package  if  the 

25 ECSS‐Q‐ST‐40C 6 March 2009 safety  review  is  part  of  an  overall  project 

review. 

The safety data package shall contain at least the following safety related documentation: 

1.

Safety analysis report (in accordance with Annex D); 

2.

Supporting analysis (if applicable); 

3.

Safety risk assessment (if applicable); 

4.

Hazardous ground operations list and procedures; 

5.

Safety verification tracking log (SVTL, in accordance with Annex C). The contents of the safety data packages for the planned safety reviews of a  project  or  programme  shall  be  specified  by  the  Safety  Approval Authority to assure they support the objectives of the safety reviews for which they are delivered (in conformance with clause 5.7.2).  

The  supplier  shall  use  the  actual  configuration  baseline,  as  defined  by ECSS‐M‐ST‐40, as the design and operational baseline that is the subject of the safety data package. 

The supplier shall integrate safety data related to the various subsystems or equipment that makes up the system into the safety data package that is presented at the review. 

All  safety  data  shall  be  traceable  from  the  safety  data  package  and available for review. 

b.

c.

d.

e.

f.

5.11.3  Safety deviations and waivers

5.11.3.1  Request for deviation or waiver

a.

Safety requirements that cannot be met shall be identified as specified in ECSS‐M‐ST‐40. 

A  request  for  deviation  or  waiver  shall  be  generated  and  tracked according to the requirements of ECSS‐M‐ST‐40.  

b.

5.11.3.2  Assessment of deviation or waiver

a.

All RFD/RFW shall be assessed in order to identify those which impact safety.  

The  accumulated  deviations  and  waivers  that  affect  safety  shall  be assessed  to  ensure  that  the  effects  of  individual  deviations  do  not invalidate the rationale used for the acceptance of other deviations. 

b.

5.11.3.3  Acceptance by the safety approval authority

a.

Safety  deviations  and  waivers  shall  be  subject  to  safety  approval authority acceptance. 

26 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 5.11.3.4  Review and disposition

a.

Deviations and waivers that affect project safety requirements or safety‐critical functions which the supplier considers acceptable shall be subject of  review  and  disposition  by  the  customer  and  the  safety  approval authority. 

5.11.4  Safety lessons learned

a.

Safety  lessons  learned  shall  be  collected  during  the  project  and  used during the project, as far as they are relevant. 

NOTE 

Safety  lessons  learned  should  consider  as  a 

minimum: 

•

the impact of newly imposed requirements; 

•  assessment  of  all  malfunctions,  accidents, 

anomalies, deviations and waivers; 

•  effectiveness  of  safety  strategies  of  the 

project; 

•  new  safety  tools  and  methods  that  have 

been developed or demonstrated; 

•  effective versus ineffective verifications that 

have been performed; 

•  changes  proposed  to  safety  policy,  strategy 

or technical requirements with rationale. 

b.

The  safety  lessons  learned  information  shall  be  made  available  to  the customer  and  suppliers,  particularly  to  project  and  safety  managers  as well  as  design  and  safety  engineers  upon  request  for  use  on  other projects.  

5.11.5  Documentation of safety critical items

a.

The  safety  critical  items  identified  by  the  safety  analysis  shall  be documented in accordance with ECSS‐Q‐ST‐10‐04. 

27 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Safety engineering- 6.1  Overview

Safety  is  an  integral  part  of  all  project  product  assurance  and  engineering activities. It is not a stand‐alone activity. The quality of all safety engineering related  work  is  based  on  assurance  that  the  system  is  designed,  qualified, manufactured,  and  operated  in  accordance  with  the  ECSS  product  assurance requirements.  

Safety engineering consists of safety analysis, management of hazard and risk reduction  processes,  hazard  and  risk  potential  assessment,  design  assurance, and hazard and risk control activities. 

Safety engineering makes use of lessons learned throughout the programme. - 6.2  Safety requirements identification and traceability

a.

Safety requirements shall be identified and traced from the system level into the design and then allocated to the lower levels. 

b.  When specified by the project, the identified safety requirements shall be justified in the design and presented in an appropriate document. 

- 6.3  Safety design objectives

Safety policy and principles

6.3.1

The  order  of  priority  with  respect  to  safety,  which  is  part  of  ECSS  policy,  is presented in clause 4. 

Design selection

6.3.2

a.

Appropriate design features shall be selected to ensure inherent safety. NOTE 

Such  features  are  fail  safe  design  solutions, 

damage  control,  containment  and  isolation  of 

potential hazards.  

28 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 6.3.3

Hazard reduction precedence

6.3.3.1  General

a.

The  following  sequence  of  activities  shall  be  applied  to  identified hazards,  hazardous  conditions,  and  functions  whose  failures  have hazardous consequences: 

1.

Hazard elimination 

2.

Hazard minimization 

3.

Hazard control. 

6.3.3.2  Hazard elimination

a.

Hazards  and  hazardous  conditions  shall,  consistent  with  the  project constraints  and  mission  objectives,  be  eliminated  from  the  design  and operational concepts by the selection of design technology, architecture and operational characteristics.  

6.3.3.3  Hazard minimization

a.  Where hazards and hazardous conditions are not eliminated, the severity of  the  associated  hazardous  events  and  consequences  shall,  consistent with  the  project  constraints  and  mission  objectives,  be  reduced  to  an accepted 

the  design  architecture, technologies, and operational characteristics allowing the substitution of those hazards by other hazards with lower potential threat. 

the  change  of 

through 

level 

6.3.3.4  Hazard control

6.3.3.4.1  General

a.

b.

Hazards  that  have  not  been  eliminated  and  have  been  subjected  to hazard minimization (as defined in 6.3.3.3a) shall be controlled through preventative  or  mitigation  measures,  associated  to  hazard  scenarios, which are introduced into the system design and operation to avoid the events or to interrupt their propagation to consequences. 

The following measures shall be applied in order of precedence: 

1.

2.

3.  Warning devices 

4.

Design selection 

Automatic safety devices 

Special procedures. 

6.3.3.4.2  Design selection - Failure tolerance design

a.

Failure  tolerance  is  the  basic  safety  requirement  that  shall  be  used  to control most hazards.  

The design shall tolerate a minimum number of credible failures and/or operator errors determined by the hazard consequence. 

The supplier shall establish the list of failures to be considered as ʺnon credibleʺ for customer approval as early as possible in development. 

b.

c.

29 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 6.3.3.4.3  Design selection - Design for minimum risk

a.

Hazard  which  cannot  be  controlled  by  compliance  to  failure  tolerance shall be reduced to an accepted level by compliance with specific safety related properties and characteristics of the design.  

NOTE 

Examples  are:  structures,  pressures  vessels, 

mechanisms, 

compatibility, 

flammability. 

material 

6.3.3.4.4  Automatic safety devices

a.

Hazards  that  are  not  eliminated  through  design  selection  shall  be reduced  and  made  controllable  through  the  use  of  automatic  safety devices as part of the system, subsystem or equipment.  

The  safety  devices,  specified  in  6.3.3.4.4a,  shall  not  be  dependant  on human performance. 

Use of software in automatic safety devices should be avoided. 

If  software  is  used  in  automatic  safety  devices,  justification  shall  be provided. 

b.

c.

d.

6.3.3.4.5  Warning devices

a.  When it is not practical to preclude the existence or occurrence of known hazards or to use automatic safety devices, devices shall be used for the timely detection of the condition and the generation of a warning signal. This  shall  be  coupled  with  emergency  controls  of  corrective  action  for operators to safe or shut down the affected subsystem. 

b.

6.3.3.4.6  Special procedures

a.  When it is not possible to reduce the magnitude of a hazard through the design,  the  use  of  safety  devices  or  the  use  of  warning  devices,  special procedures  shall  be  developed  to  control  the  hazardous  conditions  for the enhancement of safety. 

Special procedures shall be verified by test and appropriate training be provided for personnel. 

Hazard  detection  shall  be  implemented  if  alternative  means  cannot  be used. 

To permit the use of real time monitoring, hazard detection and safing systems  for  hazard  control,  the  availability  of  sufficient  response  time shall be verified and corresponding safing procedures be developed and verified and the personnel trained. 

d.

b.

c.

NOTE 

Special procedures are the least effective of the 

hazard  control  and  risk  reduction  measures 

available.  They  can  include  emergency  and 

contingency 

procedural 

constraints,  or  the  application  of  a  controlled 

maintenance programme.  

procedures, 

30 ![Im0](images/Im0)

![Im0](images/Im0)

Environmental compatibility

ECSS‐Q‐ST‐40C 6 March 2009 The system design shall meet the safety requirements under the worst‐case natural and induced environments defined for the project. 

Design  and  performance  margins  shall  be  established  and  applied  for worst‐case  combinations  of  induced  and  natural  environments  and operating characteristics. 

External services

Loss, malfunctioning, and sudden restoration of external services shall be defined as an input to the development phase. 

The  system  design  shall  be  defined  so  that  catastrophic  or  critical consequences  are  not  induced  by  loss,  malfunctioning,  and  sudden restoration of external services. 

6.3.4

a.

b.

6.3.5

a.

b.

6.3.6

a.

Hazard detection - signalling and safing

Safety  monitoring,  display,  alarm  and  safing  capabilities  shall  be incorporated for manned space systems. 

These  capabilities  shall  provide  the  information  to  allow  the  crew  and system  operators  to  take  actions  to  protect  personnel  from  the consequences of failures within safety‐critical functions and the failure of hazard control measures. 

The system design shall provide the capability for detecting failures that result  in  degradation  of  failure  tolerance  with  respect  to  the  hazard detection, signalling and safing function. 

The performance of these functions shall be verifiable during flight and ground operational phases. 

The emergency, caution and warning function shall detect and notify the crew  and  system  operators  of  emergency,  warning  and  caution situations. 

Safing  functions  and  capabilities  shall  be  included  that  provide  for  the containment or control of emergency, warning and caution situations.  Provisions  shall  be  included  for  the  monitoring  of  safing  function execution.  

Dedicated safing functions shall be provided for emergency situations. Control of warning and caution situations shall be acceptable by system reconfiguration or by dedicated safing functions. 

A  single  failure  shall  not  cause  loss  of  the  emergency  and  warning function. 

b.

c.

d.

e.

f.

g.

h.

i.

j.

k.  Where  the  operation  of  a  safing  system  introduces  a  new  hazard, inadvertent  activation  of  the  safing  system  shall  be  controlled  in accordance with the failure tolerance requirements. 

31 ECSS‐Q‐ST‐40C 6 March 2009 l.

m.

A  single  failure  shall  not  cause  loss  of  the  emergency  and  warning functions together with the monitored functions.  

Emergency,  warning  and  caution  data,  out  of  limit  annunciation  and safing commands shall be given priority over other data processing and command functions. 

o.

n.  When systems or elements are integrated into, or docked with the other systems  or  elements,  the  emergency,  warning,  caution,  and  safing function  shall  enable  the  areas  of  control  responsibility  to  monitor  and display  the  applicable  parameters,  and  to  control  the  related  safing functions.  

Emergency, warning, and caution parameter status information shall be available and displayed at the launch control and mission control centres in “near real time” during the operational phases.  

It shall be possible for the crew to ascertain and monitor in “real time” the status of emergency, warning and caution parameters of non‐crewed systems or elements prior to docking with crewed systems. 

p.

Space debris mitigation

The design and the operational characteristics of the space system shall be such that the generation of space debris is minimized consistent with the project constraints and mission objectives. 

Atmospheric re-entry

The space vehicle shall be designed and operated (post‐mission disposal manoeuvres) such that, where applicable, the risk of a catastrophic event does not exceed the level of acceptable risk specified by the project and by the launch base safety authority. 

6.3.7

a.

6.3.8

a.

6.3.9

a.

b.

c.

d.

NOTE   Hardware  of  a  space  system  that  is  returned 

from  orbit  presents  a  potential  threat  to  the 

Earthʹs  population  due  to  the  risk  of  debris 

entering  the  atmosphere  in  an  uncontrolled 

manner. 

Safety of Earth return missions

introduction  of  extraterrestrial  matter  shall  not  affect 

Biological contamination (including organic‐constituents) resulting from the introduction of extraterrestrial matter shall be avoided. 

The 

environmental conditions on Earth. 

Extraterrestrial  matter  shall  be  treated  as  hazardous  substances  until proven otherwise. 

A  containment  function  for  hazardous  substances  of  the  spacecraft, which prevents release in case of accidents until recovery or arrival at a dedicated containment facility, shall be provided.  

the 32 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 e.

If  containment  cannot  be  verified,  the  hazardous  substances  (and  any part of the space system that has potentially been exposed) shall not be returned to Earth (unless sterilized in space). 

6.3.10  Safety of human spaceflight missions

a.

b.

A mission abort capability shall be provided. 

Safing and safe heaven functions shall be provided.  

NOTE 

These  functions  can  be  implemented  through 

measures  such  as 

resource  conservation, 

increased  shielding  (solar  flares,  meteoroids 

and 

systems 

reconfiguration and trajectory changes.  

radiation), 

vehicle 

or 

c.

d.

e.

f.

Escape and rescue functions shall be provided.  

The  capability  to  reconfigure  the  system  to  restore  the  functional capability of safety critical functions in case of failures or accidents shall be provided.  

The capability to monitor, detect and assess hazards and effects of slow insidious  events  with  hazardous  consequences  shall  be  detailed according to project constraints and mission objectives. 

NOTE 

Such hazards include fatigue, corrosion, micro‐

organisms, aging, deterioration, contamination.  

The  space  system  shall  provide  an  on‐board  medical  facility  and  the capability 

impaired  or  deceased crewmember. 

for  handling  a  permanently 

6.3.11  Access

a.

System  shall  be  designed  such  that  any  required  access  to  system elements during flight or ground operations can be accomplished with an accepted level of risk to personnel.  

- 6.4  Safety risk reduction and control

6.4.1

a.

b.

c.

Severity of hazardous event

The  severity  of  potential  consequences  of  identified  hazardous  events shall be categorized as shown in Table 6‐1. 

An  understanding  of  the  criteria  defined  in  Table  6‐1  shall  be  agreed between customer and supplier. 

Detrimental  environmental  effects,  from  the  point  of  view  of  severe hazardous  consequences  to  the  global  public,  shall  be  included  in  the consequence severity evaluation. 

33 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 NOTE 1  Table  6‐1  is  used  both  in  ECSS‐Q‐ST‐30  and 

ECSS‐Q‐ST‐40. 

person 

only. 

NOTE 2  This impact can be immediate and personal. It 

also can be on a broader scale not limited to a 

single 

hazardous 

consequences can be short term or long term. 

In space flight, the environment concerned can 

be  outer  space,  including  the  Moon  and  the 

planets,  geostationary  orbit  (GEO),  low  Earth 

orbit (LEO) as well as the Earth’s atmosphere. 

NOTE 3 

The 

d.

e.

f.

g.

The  availability  of  the  following  shall  not  be  used  as  rationale  for  the reduction of the severity:  

1.

design features which reduce the probability of a hazardous event occurring, but which do not affect its severity;  

warning devices, crew safe haven, or crew escape capabilities.  2.

For  international  programmes,  a  coherent  set  of  consequence  severity shall be established for joint operational phases. 

These  categories  shall  not  violate  the  safety  policy  and  principles  as defined in clause 4.2.1 for the protection of human life or the principles of categorization in accordance with the definition of consequence severity categories in Table 6‐1. 

The  expert  assessment  on  determining  limits  for  exposures  that  do  not create  a  hazard,  those  that  create  critical  hazards  and  those  that  create catastrophic  hazards  shall  be  performed  by  the  responsible  authority,  early in the design process. 

NOTE 

Examples  of  responsible  authority  are  medical 

boards or radiation protection committees. 

h.

The  detailed  safety  requirements  and  measures  shall  be  derived  from allowed exposure levels. 

NOTE 

For example: maximum allowable concentrations, 

maximum  emission  concentrations  or  radiation 

doses. 

34 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
		<td>Major </td>
		<td>3 </td>
		<td>Major mission degradation </td>
		<td>‐‐‐ </td>
	</tr>
	<tr align="center">
		<td>Minor or  Negligible </td>
		<td>4 </td>
		<td>Minor mission degradation or  any other effect </td>
		<td>‐‐‐ </td>
	</tr>
	<tr align="center">
		<td colspan=4>NOTE:  When several categories can be applied to the system or system component, the highest severity takes  priority </td>
	</tr>
</table>

![Im1](images/Im1)

![Im1](images/Im1)

![Im3](images/Im3)

![Im2](images/Im2)

![Im1](images/Im1)

![Im1](images/Im1)

![Im3](images/Im3)

![Im2](images/Im2)

![Im1](images/Im1)

![Im1](images/Im1)

 

6.4.2

Failure tolerance requirements

6.4.2.1  Basic requirements

a.

Failure  tolerance  shall  be  the  basic  safety  requirement  used  to  control hazards. 

No  single  system  failure  or  single  operator  error  shall  have  critical  or catastrophic consequences.     

No  combination  of  two  independent  system  failures  or  operator  errors shall have catastrophic consequences. 

Safety inhibits shall be independent, verifiable, stable and stay in a safe position even in case of energy failure. 

b.

c.

d.

e.  Multiple  failures,  which  result  from  common‐cause  or  common‐mode failure mechanisms, shall be analysed as single failures for determining failure tolerance. 

35 ECSS‐Q‐ST‐40C 6 March 2009 6.4.2.2  Redundancy separation

a.

The system design shall: 

1.

include  the  capability  for  on‐board  redundancy  management  of safety‐critical functions,  

provide failure tolerance and redundancy status information to the flight and ground crews, including immediate crew notification in the  case  of  failure  detection,  redundancy  switch‐over,  or  loss  of operational redundancy, 

include  failure  detection,  failure  isolation  and  switching  of redundant items. 

2.

3.

b.

c.

The capability shall be provided to the flight crew and mission control to override automatic safing and redundancy switch‐over. 

Alternate  or  redundant  safety‐critical  functions  shall  be  physically  and functionally  separated  or  protected  in  such  a  way  that  any  event  that causes  the  loss  of  one  path  does  not  result  in  the  loss  of  alternative  or redundant paths. 

Failure propagation

6.4.2.3

a.

Hardware failures or software errors shall not cause additional failures with hazardous effects or propagate to cause the hazardous operation of interfacing hardware. 

6.4.3

Design for minimum risk

6.4.3.1  General

a.

Technical  requirements  for  areas  of  design  for  minimum  risk  shall  be identified and approved by the relevant safety approval authorities 

is  a  safety 

to  control  hazards  by 

and 

“Design 

requirement  used 

specifying 

safety‐related 

characteristics of the design. 

for  minimum  risk” 

properties 

NOTE 

Safety factors

Structural safety factors shall be defined and applied in accordance with ECSS‐E‐ST‐32‐10 or higher safety factor where applicable. 

Safety  margins  shall  be  based  on  worst  credible  combinations  of environmental conditions. 

6.4.3.2

a.

b.

6.4.3.3

a.

Fracture control

For  manned  systems,  where  structural  failure  can  have  catastrophic  or critical  consequences,  structures,  pressure  vessels,  fasteners  and  load‐bearing paths within mechanisms shall be designed in accordance with ECSS‐E‐ST‐32‐01. 

36 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 b.

For  unmanned  systems,  only  pressure  vessels  shall  be  designed  in accordance  with  ECSS‐E‐ST‐32‐01,  when  required  by  launch  site  safety authority. 

6.4.3.4  Materials

a.  Materials shall be selected and controlled in accordance with ECSS‐Q‐ST‐70. b.  Material  selection  shall  assure  that  hazards  associated  with  material characteristics are either eliminated or controlled. 

NOTE 

toxicity, 

Examples  of  these  material  properties  to  be 

characterized 

flammability, 

resistance 

to  stress  corrosion,  outgassing, 

offgassing, resistance to radiation, resistance to 

thermal 

thermal 

degradation,  resistance  to  cleaning  fluid  and 

microbiological growth. 

tracking, 

cycling, 

are: 

arc 

c.

If requirement 6.4.3.4b. is not feasible, the system design shall include the necessary  provisions  to  control  hazardous  events  associated  with material  characteristics  in  accordance  with  the  requirements  of  this Standard. 

NOTE   An example of provisions to be included by the 

system  design  is  containment  of  hazardous 

substances.  

Probabilistic safety targets

6.4.4

a.  When given, the probabilistic safety targets shall be used for 

1.

2.

3.

the  disposition  making 

identifying and ranking major risk contributors, 

making the acceptable risk decision for each identified hazard, supporting 

nonconformance to the qualitative requirements is identified. 

Probabilistic  safety  targets  can  be  established 

by the customer for hazardous consequences at 

system level for each project or programme.  

NOTE 

for 

those  cases  where b.

Probabilistic  safety  targets  shall  conform  to  the  requirements  given  by launch safety authorities and national and international regulations. 

Informative  Annex  E  provides  criteria  for  the 

establishing of probabilistic safety targets. 

NOTE 

37 ![Im0](images/Im0)

![Im0](images/Im0)

- 6.5

Identification and control of safety-critical functionsECSS‐Q‐ST‐40C 6 March 2009 Identification

6.5.1

a.

A safety critical function that, if lost or degraded, or through incorrect or inadvertent  operation,  can  result  in  a  catastrophic  or  critical  hazardous consequence, shall be identified as a safety‐critical function. 

NOTE   As  an  example,  a  series  of  operational  events 

that  can  result  in  a  hazard  if  they  occur 

inadvertently or are operated out of order. 

b.

Identification shall be done without taking into account hazards controls to be or already implemented. 

Inadvertent operation

Inadvertent operation of a safety‐critical function shall be prevented by 1.

2.

two independent inhibits, if it induces critical consequences, or three independent inhibits, if it induces catastrophic consequences. 6.5.2

a.

6.5.3

a.

b.

Status information

The  system  shall  provide  failure  tolerance  and  redundancy  status information of safety‐critical functions. 

The system shall provide the status of at least two inhibits on functions that,  if  inadvertently  operated,  can  lead  to  catastrophic  consequences, including 

1.

2.

3.

4.

notification in real time in case of failure detection, 

announcement of any loss of operational redundancy,  

notification of redundancy switch‐over, or  

changes of inhibit status. 

6.5.4

Safe shutdown and failure tolerance

requirements

a.

The  design  shall  either  provide  the  capability  for  the  safe  shutdown  of safety‐critical  functions  prior  to  in‐flight  maintenance  operations  or conform  to  the  failure  tolerance  requirements  during  maintenance operations. 

6.5.5

Electronic, electrical, electromechanical

components

a.

Electronic,  electrical,  electromechanical  (EEE)  components  used  to support  safety‐critical  functions  in  flight  standard  hardware  shall  be selected  and  procured  in  accordance  with  the  applicable  programme requirements of ECSS‐Q‐ST‐60. 

38 ![Im0](images/Im0)

6.5.6

Software functions

ECSS‐Q‐ST‐40C 6 March 2009 6.5.6.1

a.

b.

Software criticality

Safety aspects associated with the software function shall be an integral part of the overall system safety efforts and not be assessed in isolation. A  software  component  shall  be  considered  safety‐critical  if  the  loss  or degradation of its function, or its incorrect or inadvertent operation, can result in catastrophic or critical consequences.   

6.5.6.2  Analysis of safety-critical software

a.

During the project life cycle, safety analysis shall be carried out to: 

1.

identify the criticality of software components in accordance with the severity of the consequences as defined in Table 6‐1, 

determine  where  and  under  what  conditions  the  system  can trigger hazardous events caused by the software, 

define verification methods for hazard controls involving software, provide verification evidence of hazard control implementation.  2.

3.

4.

Evaluation of software criticality

The  criticality  of  a  software  component  shall  be  evaluated  taking  into account the overall system design which can provide for, e.g. back‐up or emergency procedures, hardware inhibits and certain time to effect. 

6.5.6.3

a.

6.5.6.4

a.

Software development

A  safety‐critical  software  component  shall  be  designed,  implemented, verified  and  operated  according  to  the  engineering  and  product assurance requirements defined in ECSS‐E‐ST‐40 and ECSS‐Q‐ST‐80. 

Safety‐critical  software  shall  be  analysed  for  the  identification  and verification  of  adequate  software  controls  and  inhibits  and  validated accordingly.  

The  level  of  required  software  product  assurance  effort  shall  be determined in accordance with the criticality of the software component. b.

c.

- 6.6  Operational Safety

6.6.1

a.

b.

Basic requirements

Safety involvement in the operational phase shall be planned. 

Responsibilities,  rules  and  contingency  procedures  shall  be  established prior to operation for hazardous “limit” conditions that can occur during ground and in‐flight operations. 

39 ECSS‐Q‐ST‐40C 6 March 2009 c.

d.

Operating  ranges  and  performance  limits  for  safe  operation  shall  be established and specified. 

The  design  shall  not  require  continuous  active  control  by  personnel  in order  to  stay  within  the  established  operating  ranges  and  performance limits. 

f.

e.  Man‐machine interfaces shall be designed and the personnel tasks shall be  scoped  to  reduce  the  potential  for  hazardous  events  resulting  from human error to an accepted level. 

Limits  for  crew  exposure  to  natural  and  system‐induced  environments shall  be  established  and  maintained  by  design  features  or  operational constraints that cover nominal, contingency, and emergency operational modes,  in  order  to  preclude  crew  injury  or  inability  to  perform  safety‐critical functions. 

6.6.2

6.6.2.1

a.

Flight operations and mission control

Launcher operations

to 

the  humans,  public  and  private  property  and 

Hazards 

the environment,  resulting  from  launcher  system  operation  or  malfunction shall  be  precluded  by  compliance  with  the  regulations  of  the  launch safety authority. 

6.6.2.2  Contamination

a.

Normal  or  abort  operations  shall  not  result  in  contamination  of  the Earth’s  environment  that  endangers  human  health,  crops  or  natural resources  or  that  exceed 

international regulations. 

limits  set  by  national  or 

Flight rules

6.6.2.3

a.

Flight rules shall be prepared for each mission that outline pre‐planned decisions  in  case  of  off‐nominal  situations  and  consistent  with  safety requirements. 

6.6.2.4  Hazardous commanding control

a.

b.

c.

d.

Hazardous  commanding  control  shall  ensure  that  all  hazardous commands are identified. 

Hazardous  commanding  control  shall  ensure  that  failure  modes, associated  with  flight  and  ground  operation  ‐  including  hardware, software and procedures ‐ used in commanding from control centres or other ground equipment, are included in the safety assessment. 

Hazardous  commanding  control  shall  ensure  that  the  system  design provides protection to avoid the erroneous acceptance of commands that can result in catastrophic or critical consequences. 

.Hazardous commanding control shall ensure that commands, which can result  in  catastrophic  or  critical  hazardous  consequences,  are  not performed until they are authorized and verified. 

40 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 6.6.2.5  Mission operation change control

a.  Mission operation change control shall ensure that all changes, which are desired  or  become  necessary  during  mission,  are  reviewed  for  safety impact. 

b.  Mission operation change control shall ensure that the responsible safety approval authority approves all operational change requests with safety impact. 

Safety surveillance and anomaly control

6.6.2.6

a.

b.

c.

Safety status parameters shall be identified. 

Safety status parameters shall be monitored. 

Deviation from specified limits shall be managed. 

6.6.2.7  Hazardous debris, fallout and impact control

a.

In  the  case  of  a  deviation  from  the  planned  launch  trajectory  during ascent,  launch  vehicle  stages  shall  be  remotely  destroyed  or  have  their propulsion  engines  shut  off  to  prevent  stages  or  debris  from  falling outside pre‐defined safe areas. 

The  launch  vehicle  and  spent  stage  trajectories  shall  be  monitored  to determine vehicle, stage or debris impact points. 

Residual propellants contained in spent or aborted suborbital stages shall be safely dispersed. 

b.

c.

6.6.3  Ground operations

6.6.3.1  Applicability

a.

Safety requirements of the clause shall be applied during the following ground operations: 

1.

2.

3.

4.

5.

development, qualification or acceptance testing; 

assembly, integration or test operations; 

launch site operations; 

servicing or turn‐around operations; and 

transportation or handling operations, 

Initiation

6.6.3.2

a.

The  supplier  shall  establish  procedures  to  perform  safety  readiness reviews  and  inspections  prior  to  the  performance  of  any  applicable operation. 

41 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 6.6.3.3  Review and inspection

a.

To  verify  conformance  to  safety  requirements,  readiness  reviews  and inspections  shall  include  safety  review  and  assessment  of  facilities, equipment  (incl.  GSE),  test  articles,  operating,  test  and  contingency procedures,  access  controls,  and  personnel  capabilities  to  comply  with the safety requirements. 

6.6.3.4  Hazardous operations

a.

Hazardous  operations  shall  be  monitored  for  conforming  to  safety requirements  and  procedures,  and  for  the  possible  development  of unforeseen hazardous situations.  

b.  Where necessary, contingency and emergency plans or procedures shall be established and verified prior to the commencement of the operation.  The safety manager or safety relevant authority shall have the authority to stop any operation that does not conform to safety requirements.  

c.

6.6.3.5

a.

b.

Launch and landing site

Launch, landing, turn‐around and mission operations shall be subject to hazard analysis. 

For ground operations, the analysis shall address the: 

1.

potential hazardous consequences of human error and procedural deficiencies; 

adequacy and maintenance of operational margins; 

potential for human exposure to hazards and hazardous effects; requirements for operator and flight crew training; 

adequacy  of 

information  and  data  provided  by  the  flight hardware, ground support equipment (GSE), or test equipment, as appropriate,  to  support  the  performance  of  the  operations  in accordance  with  all  applicable  safety  requirements  (including  all safety regulations). 

2.

3.

4.

5.

6.6.3.6  Ground support equipment

a.

b.

c.

d.

All  Ground  support  equipment  (GSE)  shall  be  subjected  to  hazard analysis. 

All GSE shall conform to the ‘Essential Health & Safety Requirements’ of all applicable EU ‘New Approach directives’.  

Conformance to 6.6.3.6b. shall be shown by the addition of the ‘CE’ mark to the product and the issuing of a ‘Declaration of Conformity’. 

Conformance 

demonstrated. 

NOTE 

to  any  other  product  related  directives  shall  be Further guidance is given in Annex G. 

42 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Safety analysis requirements andtechniques- 7.1  Overview

Safety risks are the result of the hazardous characteristics associated with the: •

design,  including  the  technology  selected,  the  physical  arrangement  of elements, subsystems and equipment, and software functions;  

operating modes; 

potential for operator error;  

operating environment; 

hazardous  effects  that  result  from  the  failure  of  functions  (including software). 

•

•

•

•

- 7.2  General

a.

b.

c.

d.

Safety analysis shall be performed in a systematic manner as a basis for all applicable phases and to ensure that hazards are identified, eliminated or minimized and controlled and safety risks are assessed and reduced. Safety analyses shall be initiated early in the design process and provide concurrent  support  to  project  engineering  in  the  selection  of  the  least hazardous design and operational options that are compatible with the project  mission  and  programme  constraints  and  conform  to  the requirements. 

The  results  of  safety  analyses  shall  also  be  used  to  support  project management  in  the  assessment  of  the  overall  risks,  verification  of  risk reduction, ranking of risk sources, support to project resource allocation, monitoring of risk trends, and residual risk acceptance.  

Analysis shall always be made with reference to a defined configuration baseline as defined by ECSS‐M‐ST‐40. 

43 ![Im0](images/Im0)

![Im0](images/Im0)

- 7.3  Assessment and allocation of requirements

ECSS‐Q‐ST‐40C 6 March 2009 Safety requirements

The  supplier  shall  respond  to  and  comply  with  the  applicable  safety requirements for the project. 

Additional safety requirements

The  supplier  shall  identify  additional  safety  requirements,  where applicable, through the use of lessons learned from previous projects and the safety analyses performed during the project. 

Define safety requirements - functions

The  supplier  shall  define  the  safety  requirements  for  the  various functions of the system. 

7.3.1

a.

7.3.2

a.

7.3.3

a.

7.3.4

a.

7.3.5

a.

7.3.6

a.

Define safety requirements - subsystems

The  supplier  shall  define  the  safety  requirements  associated  with  the various subsystems and lower levels. 

Justification

The  supplier  shall  justify  to  the  customer  the  proposed  allocation  of safety  requirements  at  the  latest  at  the  end  of  the  detailed  definition phase. 

Functional and subsystem specification

The  supplier  shall  ensure  that  the  function  and  subsystem  safety requirements  are  included  in  the  relevant  functional  and  subsystem specification. 

- 7.4  Safety analyses during the project life cycle

a.

Safety analysis shall be refined and updated in an iterative manner as the design  process  proceeds,  to  ensure  that  hazards  and  hazardous  events are  assessed,  and  that  the  relevant  detailed  design  and  operational requirements, hazard controls, and verification activities are defined and implemented. 

NOTE 

Refer to 5.7 for detailed safety programme tasks 

in the different project phases 

44 ![Im0](images/Im0)

- 7.5  Safety analyses

ECSS‐Q‐ST‐40C 6 March 2009 7.5.1  General

a.

The  safety analysis  report  shall  be  established  in  conformance with  the DRD in Annex D in order to gather results of safety analyses, which use deterministic  and  probabilistic  methods  which  are  described  in  the clauses 7.5.2 to 7.5.4. 

Hazard analysis

7.5.2

a.

Hazard analysis shall be performed in a systematic manner, beginning in the  concept  phase  and  continuing  through  the  operational  phase, including end‐of‐life and disposal. 

Hazard analysis shall support the hazard reduction process. 

Hazard analysis shall identify and evaluate: 

1.

hazards  associated  with  system  design,  its  operation  (both  on ground and in flight) and the operation environment;  

the  hazardous  effects  resulting  from  the  physical  and  functional propagation of initiator events; 

the hazardous events resulting from the failure of system functions and functional components; 

time critical situations.  

2.

3.

b.

c.

d.

e.

4.

The following potential initiator events shall be considered: 

1.

2.

3.

4.

hardware failure (random or time dependent); 

latent software error; 

operator error; 

design inadequacies, including: 

(a)

(b)

(c)  material inadequacies and incompatibilities; 

(d)

natural and induced environmental effects; 

procedural deficiencies. 

hardware‐software interactions; 

inadequate margins; 

unintended operating modes caused by sneak‐circuits; 

5.

6.

Hazard  analysis 

includes  a  systematic  analysis  of  the  “system” operations  and  operating  procedures  that  shall  be  performed  in  the detailed design and operational stages of a project.  

NOTE 

This  analysis  evaluates  the  capability  of  the 

system to be operated safely, to determine the 

safest  operating  modes,  and  to  evaluate  the 

acceptability of the operating procedures. 

45 ![Im0](images/Im0)

f.

The  systematic  analysis  of  system  operation  and  operating  procedures shall be repeated as the design and operational detail evolves, including the system’s operational modes and man‐machine interfaces. 

ECSS‐Q‐ST‐40C 6 March 2009 Safety risk assessment

7.5.3

a.

Safety risk assessment shall  

1.

comprise  the  identification,  classification  and  ranking  of  safety risks and their contributors, 

be  based  on  deterministic  hazard  analysis  by  combining  the consequence  severity  and  the  likelihood  of  occurrence  of  the consequence, 

be used to facilitate effective and efficient safety risk reduction and control,  

support project risk management as defined in ECSS‐M‐ST‐80,  assess compliance with probabilistic safety targets. 

2.

3.

4.

5.

NOTE 1  The estimation of event likelihoods is based on 

the use of different sources of data i.e.:  

•  previous  experience  on 

the  particular 

system  (i.e.  measured  or  observed  directly 

relevant test or experience data),  

•  data  from  other  systems  or  projects  (i.e. 

extrapolation  from  generic  data,  similarity 

data, or physical models), and  

•  expert  judgment  (i.e.  direct  estimation  of 

likelihoods by domain specialists). 

NOTE 2  The  determination  of  likelihood  is  not  a  mean 

to  downgrade  the  severity  of  function  (see 

6.4.1d) 

b.

Safety  risk  assessment  shall  be  started  early  in  the  design  process  and performed in progressive steps during the implementation of the safety programme.  

Supporting assessment and analysis

7.5.4

7.5.4.1  General

a.

Following supporting assessment and analysis methods shall be used as necessary (tailored by project) to support hazards analysis and safety risk assessment. 

NOTE 1  Example  of  tailoring  by  project  is  when  the 

supporting  assessment  and  analysis  methods 

are not applicable in e.g. unmanned missions. 

NOTE 2  Assessments  and  analyses  from  ECSS‐Q‐ST‐30 

can be used to support safety assessment. 

Supporting analyses shall be agreed with all relevant parties. 

b.

46 ECSS‐Q‐ST‐40C 6 March 2009 7.5.4.2  Warning time analysis

a.  Warning time analysis shall be performed during the concept definition phase and the design and development phase in order to evaluate time‐critical  situations  identified  in  the  hazard  analysis  and  to  support  the implementation of hazardous‐situation detection and warning devices or contingency procedures.  

The analysis shall determine the 

1.

b.

time interval during which the event is detected and the response action taken;  

detection  capability  of  the  proposed  design  with  respect  to detection sensitivity and detection time;  

resultant time available for response; 

adequacy  of  the  proposed  design  or  contingency  procedures, including  emergency  evacuation,  rescue,  system  reconfiguration, redundancy switching, and maintenance. 

The detection times shall be determined from the 

1.

occurrence  of  the  initiating  event  to  the  time  when  a  hazardous consequence occurs (propagation time);  

occurrence of the initiating event to the time of earliest detection or annunciation; and  

time taken for corrective action to be implemented. 

2.

3.

2.

3.

4.

c.

7.5.4.3  Caution and warning analysis

a.

Caution  and  warning  analysis  shall  be  performed  during  the  concept definition phase and the design and development phase of human space flight programmes in order to identify 

1.

2.

3.

4.

emergency, warning, and caution parameters; 

the required safing functions and capabilities; 

limit sensing requirements; 

the applicability of the individual “caution and warning” functions to the different mission phases.  

b.

The caution and warning analysis shall utilize the results of the warning time and hazards analyses as appropriate. 

7.5.4.4  Common-cause and common-mode failure analysis7.5.4.4.1  Multiple failures

a.  Multiple  failures,  which  result  from  common‐cause  or  common‐mode failure mechanisms, shall be analysed as single failures for determining failure tolerance.  

47 ![Im0](images/Im0)

![Im0](images/Im0)

Identification of requirements and scope

ECSS‐Q‐ST‐40C 6 March 2009 The  supplier  shall  identify  the  requirement  for  and  the  scope  of dedicated  common‐cause  and  common‐mode  analyses  by  means  of  the review of the results of the other safety analyses, such as FTA and hazard analysis, and of the characteristic of the system and of its environment. 7.5.4.4.2

a.

7.5.4.4.3

a.

b.

7.5.4.4.5

a.

7.5.4.5

a.

b.

Identification of common-cause failures

The  supplier  shall 

assessment of the effects of common‐causes.  

identify  potential  common‐cause 

failures  by NOTE 

For  example:  radiation,  thermal  environment 

and fires. 

b.

The  common‐cause  failure  analysis  shall  be  performed  in  coordination with the FTA and the hazard analysis. 

NOTE 

The  analysis  of  common‐cause  failures  can 

require  that  use  be  made  of  the  result  of 

dedicated  engineering  analyses,  e.g.  thermal 

analyses, meteorite or debris impact analysis. 

7.5.4.4.4  Analysis of common-mode failures

a.

Common‐mode failures shall be analysed by means of the use of check‐lists (to be established by the supplier) that list potential common‐modes for  system  components  during  the  manufacturing,  integration,  test, operation and maintenance phases.  

The 

FMEA/FMECA. 

common‐mode  analysis 

coordinated  with 

shall  be 

the Integration of results

Results of common‐cause and common‐mode analysis shall be integrated with  the  results  of  the  system  level  safety  analyses  (fault  tree  analysis, hazard analysis). 

Fault tree analysis

The  fault  tree  analysis  shall  be  used  to  establish  the  systematic  link between the system‐level hazard and the contributing hazardous events and subsystem, equipment or piece part failure. 

A fault tree analysis, or its equivalent, shall be performed to verify the failure tolerance requirements. 

NOTE 

Refer to ECSS‐Q‐ST‐40‐12 “Fault tree analysis ‐ 

Adoption  notice  ECSS/IEC  61025”  for  further 

instructions on fault tree analyses. 

7.5.4.6  Human error analysis

a.  Whenever  safety  analyses  identify  operator  errors  as  a  cause  of catastrophic or critical hazards, a dedicated analysis shall be carried out. 48 ECSS‐Q‐ST‐40C 6 March 2009 b.

c.

The human error analysis shall be used to support the safety analysis for the identification of human operator error modes and their effects and for the definition of adequate countermeasures to prevent or control human operator errors. 

The human error analysis shall be developed from the early phases of the project  onwards  in  order  to  define  recommendations  for  the  hardware and  software  design,  procedure  development  and  training  preparation programme. 

7.5.4.7

a.

Failure modes, effects and criticality analysis

The  results  of  failure  modes  and  effects  analysis  (FMEA)  or  failure modes, effects and criticality analysis (FMECA) shall be used to support the  hazard  analysis  in  the  evaluation  of  the  effects  of  failures. FMEA/FMECA and hazard analysis are complementary analyses. 

7.5.4.8

a.

b.

NOTE 

to 

Refer 

ECSS‐Q‐ST‐30‐02 

instructions on FMEA/FMECA. 

for 

further 

Zonal analysis

Zonal analysis shall be performed where redundancy is used to reduce the probability of losing a function or of inadvertently actuating a safety‐critical function. 

The  objectives  of  the  zonal  analysis  shall  ensure  that  equipment installation meets the adequate safety requirements regarding: 

1.

2.

3.

4.

basic installation rules and space practices; 

interaction between subsystems; 

implication of operator errors; 

effects of external events. 

NOTE 

Zonal  analysis  is  the  systematic  inspection  of 

the  topology  of  a  system,  the  evaluation  of 

potential component‐to‐component interactions 

with and without failure, and the assessment of 

the severity of potential hazards inherent in the 

system installation. 

49 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 Safety verification- 8.1  General

a.

b.

c.

A  system  shall  be  in  place  that  tracks  all  hazards  and  related  risks,  to relate  all  verifications  of  the  corresponding  hazard  uniquely  to unambiguous causes and controls. 

For common techniques for verification of design features used to control hazards, the requirements of ECSS‐E‐ST‐10 shall apply.  

To  successfully  complete  the  safety  process,  positive  feedback  shall  be provided on completion results for all verification items associated with a given hazard. 

- 8.2  Hazard reporting and review

Hazard reporting system

8.2.1

a.

The  supplier  shall  establish  a  hazard  reporting  system  for  tracking  the status of all identified hazards. 

The system shall be applied for all hazards with potentially catastrophic or critical consequences. 

The supplier shall report, and provide evidence, that 

1.

2.

3.

If verification cannot be completed, the supplier shall establish a Safety Verification Tracking Log (SVTL) (refer to clause 8.5.1a.). 

controls are defined and agreed; 

verification methods are defined and agreed;  

verification is completed. 

b.

c.

d.

Safety status review

Status of hazard control and risk reduction activities shall be reviewed at safety progress meetings and project safety reviews for compliance with decisions taken and achievement of intended results. 

8.2.2

a.

8.2.3

a.

Documentation

All hazard documentation shall be formally issued for each safety review and major project review, as specified in clause 5.11).  

50 ![Im0](images/Im0)

![Im0](images/Im0)

- 8.3  Safety verification methods

ECSS‐Q‐ST‐40C 6 March 2009 Verification engineering and planning

Verification engineering shall select the verification methods consistent: 1.

with  the  verification  requirements  documented  in  the  hazard report, 

with the launch base safety rules. 

2.

Verification  planning  shall  commence  in  an  integrated  manner  upon selection of the control method. 

8.3.1

a.

b.

b.

8.3.2  Methods and reports

a.

Safety verification methods shall include alternatively or in combination review of design, analysis, inspection and test. 

For all safety verifications traceability shall be provided. 

Analysis

8.3.3

a.

All  relevant  technical  safety  and  engineering  analyses  performed  or updated  with  analysis  in  respect  to  the  as‐built  configuration  shall  be used for verification.  

b.  When  similarity  analysis  is  provided,  for  tracking  purposes  it  shall contain  a  copy  of  (or  a  unique  reference  to)  the  referenced  previous verification, verification procedure and requirement valid at the time of the first verification. 

8.3.4

Inspections

8.3.4.1  General

a.

Inspections  which  are  considered  as  necessary  in  order  to  meet  safety requirements  of  the  system  shall  be  identified  and  included  in  user manuals and procedures. 

Preflight inspections

8.3.4.2

a.

All preflight safety inspections shall be assessed for inclusion in the MIP list.  

NOTE 

If  preflight  safety  inspections  are  included  on 

the  MIP  list,  closeout  is  feasible  by  MIP 

reporting 

as 

appropriate. 

individual 

reporting 

or 

b.

c.

Launch  preparation  inspections  shall  be  entered  into  the  launch  base procedure.  

The closeout shall be given by the approved launch authority procedure. 51 ECSS‐Q‐ST‐40C 6 March 2009 d.

e.

f.

Late access procedures shall be the subject of training and be performed by qualified personnel.  

Training for flight crew and mission operation teams shall be performed, including specific safety briefing, training and mission simulation.  

Close‐out  shall  be  by  safety‐approved  procedure,  documented  training session and simulations. 

8.3.4.3

a.

8.3.5

a.

b.

Inflight inspections

Inflight inspections shall be entered into flight procedures and operation manuals. 

Verification and approval

The  supplier  shall  select, and  propose to  the  safety  approval  authority, the  safety  verification  methods  to  be  used  in  conformance  to  the applicable safety requirements. 

The  results  of  safety  verification  shall  be  submitted  for  approval  to  the relevant safety approval authority. 

- 8.4  Verification of safety-critical functions

Validation

8.4.1

a.

Safety‐critical  functions  shall  be  verified  by  testing  which  include application of the operating procedures, the “man‐in‐the‐loop”, and the verification  of 

tolerance requirements. 

The  tests  shall  include  the  demonstration  of  nominal,  contingency  and emergency operational modes. 

the  effectiveness  of  applicable 

failure 

8.4.2  Qualification

a.

function  qualification 

The  safety‐critical  characteristics  of  all  safety‐critical  functions  shall  be qualified by test. 

Safety‐critical 

the determination  of  performance  margins  considering  worst  case combinations  of  induced  and  natural  environments  and  operating conditions.  

Qualification  “by  similarity”  shall  not  be  applied  except  after  customer approval on a case‐by‐case basis.  

include 

testing 

shall 

b.

b.

c.

52 ![Im0](images/Im0)

![Im0](images/Im0)

8.4.3

a.

Failure tests

ECSS‐Q‐ST‐40C 6 March 2009 Induced failure tests shall be performed when required by safety analysis for  evaluating  failure  effects,  and  for  demonstrating  failure  tolerance conformance in safety‐critical functions.  

8.4.4

Verification of design or operational

characteristics

a.

Verification  of  unique 

required  design  or  operational characteristics  shall  form  part  of  the  development,  qualification  or acceptance testing programmes as appropriate.  

safety 

Safety verification testing

8.4.5

a.  Where  full‐scale  testing  is  not  performed,  equivalent  safety  verification method based on technically representative hardware or models shall be justified, approved and performed.  

For the verification of hazard controls in catastrophic hazards where non‐flight  equipment  replaces  part  of  the  flight  equipment  to  test  a  flight function  the  verification  shall  be  performed  independently  by  a  third party which was not involved in the design and qualification of the flight model (FM). 

b.

- 8.5  Hazard close-out

8.5.1

a.

b.

Safety assurance verification

A  safety  verification  tracking  log  (SVTL)  shall  be  established,  in conformance with the DRD in Annex C, to collect all the open verification items of the different hazard reports from the safety analysis. 

In time for acceptance by the customer, and in preparation of transfer to the next stage of system integration, the safety manager shall verify that:  1.

hazard close‐outs performed so far by the responsible engineer are still valid;  

the  verifications  reflect  the  as‐built  or  as‐modified  status  of  the hardware; 

all open verifications at this time are acceptable for transfer to the next stage of system integration;  

all open verifications are entered into the verification tracking log (SVTL); 

the  verification  tracking  log  is  maintained  to  reflect  the  current status. 

5.

4.

2.

3.

c.

If  the  safety  verification  constrains  any  ground  operations,  the  safety manager shall give notification to the safety review panel. 

53 ![Im0](images/Im0)

Hazard close-out verification

ECSS‐Q‐ST‐40C 6 March 2009 The safety manager shall assure that each hazard considered for closure has the approval by the safety approval authority, verifying that 

1.

hazards  not  eliminated  are  controlled  in  accordance  with  the applicable  requirements  and  associated  verification  activities  are successfully completed, or, when applicable, 

deviations  from,  or  waivers  of  requirements,  are  granted  by  the safety approval authority. 

8.5.2

a.

2.

- 8.6  Declaration of conformity of ground equipment

a.

All  ground  equipment  that  falls  into  the  scope  of  an  applicable  ‘New Approach directive’ shall be ‘CE’ marked and supplied with a supporting ‘Declaration  of  Conformity’  and  User  Manual  detailing  all  safety warnings.ʺ 

NOTE   Additional 

information 

is  provided 

in 

Informative Annex G.   

54 ECSS‐Q‐ST‐40C 6 March 2009 Annex A (informative)Analyses applicability matrixScope of the Table A‐1 is to present relation of documents associated to safety activities to support project review objectives as specified in ECSS‐M‐ST‐10.  NOTE 

This table constitutes a first indication for the data 

package  content  at  various  reviews.  The  full 

content of such data package is established as part 

of the business agreement, which also defines the 

delivery of the document between reviews. 

The table lists the documents necessary for the project reviews (identified by “X”). The  various  crosses  in  a  row  indicate  the  increased  levels  of  maturity progressively expected versus reviews. The last cross in a row indicates that at that review the document is expected to be completed and finalized. 

NOTE   All  documents,  even  when  not  marked  as 

deliverables  in  Table  A‐1,  are  expected  to  be 

available  and  maintained  under  configuration 

management  as  per  ECSS‐M‐ST‐40  (e.g.  to  allow 

for backtracking in case of changes). 

Documents listed in Table A‐1 are either ECSS‐Q‐ST‐40 DRDs, or DRDs to other ECSS‐Q‐40‐XX standards. 

 

55 ![Im0](images/Im0)

ECSS‐Q‐ST‐40C 6 March 2009 ![Im0](images/Im0)

