ECSS-E-ST-32-01C Rev. 16 March 2009Space engineering

Fracture control

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐E‐ST‐32‐01  Working  Group,  reviewed  by  the  ECSS 

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

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐E‐30‐01A  13 April 1999 </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐32‐01B </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐32‐01C  15 November 2008 </td>
		<td>Second issue  The main changes are summarized below:  •  6.3.5 – metallic low risk fracture items are introduced.  •  6.4.4 – fracture control summary report introduced.  •  7 – various improvements, incl. B‐values for lower bound properties  and application of EPFM where appropriate.  •  8.2 – reference is now made to ECSS‐E‐ST‐32‐02 for pressurized  hardware; pressurized structures and hazardous fluid containers are  introduced.  •  8.3 – requirements for welding are updated and include now reference  to standardized nomenclature.  •  8.4 & 10.5 – requirements for composite, bonded and sandwich items are  significantly updated: major changes are made in order to address the risk  of degradation due to impact damage and to complement the existing  verification by means of proof testing (also applicable to clause 11).  •  8.7 – requirements for glass components are updated (incl. improved  coherence with SSP 30560A).  •  8.8 – requirements for fasteners are updated.  •  10.3 – requirements for NDI are updated and include now more details  on standard NDI; the Table 2 of ECSS‐E‐31‐01A is now deleted.  •  10.7 – requirements for detected defects are introduced.  •  11 – updated to include highly loaded metallic safe life items; some  special requirements are deleted.  •  For DRDs of fracture control documentation, reference is now made to  ECSS‐E‐ST‐32.  •  Coherence with other structural ECSS standards has been checked.  •  Coordination with recent developments in fracture control  standardization at NASA, e.g. reflected in NASA‐STD‐5019, NASA‐ STD‐5009 and MSFC‐RQMT‐3479.   •  Substantial editing of the text to comply with ECSS drafting rules. </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐32‐01C Rev. 1  6 March 2009 </td>
		<td>Second issue revision 1  Changes with respect to version C (15 November2008) are identified with  revision tracking.  Main changes are:  •  Requirement 8.7c., on page 59, contained duplicated requirements. The  duplicates were removed. Clause 8.7 contains in total 9 requirements </td>
	</tr>
</table>

3 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td></td>
		<td>(8.7a. to 8.7.i).  •  Correction of normative references.  •  Split of terms “catastrophic hazard” and “crack aspect ratio, a/c” into  two terms.  •  Addition of missing abbreviated terms for “Fty, Ftu and KC.  •  The single requirement of clause 10.5.2.2.3 “Proof test monitoring”  moved to 10.5.2.2.1 as requirement “e.”, clause header 10.5.2.2.3  deleted.  •  Deletion of clause header 11.2.2.2 “Identification of potential fracture‐ critical items” (which had essentially the same title as 11.2.2.1), causing  a renumbering of its only requirement to requirement 11.2.2.1b., and  renumbering of following clauses.  •  Editorial changes </td>
	</tr>
</table>

4 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................9

- 2 Normative references...........................................................................................10

- 3 Terms, definitions and abbreviated terms..........................................................12

- 3.1  Terms from other standards .....................................................................................12

- 3.2  Terms specific to the present standard ....................................................................13

- 3.3  Abbreviated terms ....................................................................................................19

- 4 Principles ..............................................................................................................21

- 5 Fracture control programme ...............................................................................23

- 5.1  General.....................................................................................................................23

- 5.2  Fracture control plan ................................................................................................23

- 5.3  Reviews....................................................................................................................24

5.3.1  General.......................................................................................................24Safety and project reviews .........................................................................255.3.2

- 6 Identification and evaluation of PFCI..................................................................27

- 6.1

Identification of PFCIs ..............................................................................................27- 6.2  Evaluation of PFCIs..................................................................................................28

6.2.1  Damage tolerance ......................................................................................28Fracture critical item classification..............................................................306.2.2

- 6.3  Compliance procedures ...........................................................................................30

6.3.1  General.......................................................................................................30Safe life items.............................................................................................306.3.2

6.3.3

Fail-safe items ............................................................................................316.3.4  Contained items..........................................................................................32Low-risk fracture items ...............................................................................336.3.5

- 6.4  Documentation requirements ...................................................................................38

Fracture control plan...................................................................................38Lists ............................................................................................................386.4.1

6.4.2

5 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Analysis and test documents......................................................................38Fracture control summary report ................................................................386.4.3

6.4.4

- 7 Fracture mechanics analysis...............................................................................40

- 7.1  General.....................................................................................................................40

- 7.2  Analytical life prediction............................................................................................41

Identification of all load events ...................................................................417.2.1

7.2.2

Identification of the most critical location and orientation of the crack........417.2.3  Derivation of stresses for the critical location .............................................427.2.4  Derivation of the stress spectrum...............................................................427.2.5  Derivation of material data..........................................................................437.2.6

Identification of the initial crack size and shape .........................................43Identification of an applicable stress intensity factor solution .....................447.2.7

7.2.8

Performance of crack growth calculations..................................................45- 7.3  Critical crack-size calculation ...................................................................................45

- 8 Special requirements ...........................................................................................47

Introduction...............................................................................................................47- 8.1

- 8.2  Pressurized hardware ..............................................................................................47

8.2.1  General.......................................................................................................478.2.2

Pressure vessels ........................................................................................47Pressurized structures................................................................................508.2.3

8.2.4

Pressure components.................................................................................508.2.5

Low risk sealed containers .........................................................................518.2.6  Hazardous fluid containers .........................................................................51- 8.3  Welds .......................................................................................................................52

8.3.1  Nomenclature .............................................................................................528.3.2

Safe life analysis of welds ..........................................................................52- 8.4  Composite, bonded and sandwich structures...........................................................53

8.4.1  General.......................................................................................................538.4.2  Defect assessment.....................................................................................538.4.3  Damage threat assessment........................................................................558.4.4  Compliance procedures..............................................................................56- 8.5  Non-metallic items other than composite, bonded, sandwich and glass items ........59

- 8.6  Rotating machinery ..................................................................................................60

- 8.7  Glass components....................................................................................................60

- 8.8  Fasteners .................................................................................................................61

- 9 Material selection .................................................................................................63

6 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 - 10 Quality assurance and Inspection ....................................................................64

- 10.1  Overview ..................................................................................................................64

- 10.2  Nonconformances ....................................................................................................64

- 10.3  Inspection of PFCI....................................................................................................64

10.3.1  General.......................................................................................................6410.3.2

Inspection of raw material...........................................................................65Inspection of safe life finished items...........................................................6610.3.3

- 10.4  Non-destructive inspection of metallic materials ......................................................67

10.4.1  General.......................................................................................................6710.4.2  NDI categories versus initial crack size ......................................................6710.4.3

Inspection procedure requirements for standard NDI.................................71- 10.5  NDI for composites, bonded and sandwich parts.....................................................74

10.5.1  General.......................................................................................................7410.5.2

Inspection requirements .............................................................................75- 10.6  Traceability ...............................................................................................................76

10.6.1  General.......................................................................................................7610.6.2  Requirements .............................................................................................77- 10.7  Detected defects ......................................................................................................77

10.7.1  General.......................................................................................................7710.7.2  Acceptability verification .............................................................................78Improved probability of detection................................................................7910.7.3

- 11 Reduced fracture control programme ..............................................................80

- 11.1  Applicability ..............................................................................................................80

- 11.2  Requirements ...........................................................................................................80

11.2.1  General.......................................................................................................8011.2.2  Modifications...............................................................................................80- Annex A (informative) The ESACRACK software package..................................82

- Annex B (informative) References .........................................................................83

- Bibliography.............................................................................................................84

- Figures

- Figure 5-1: Identification of PFCI............................................................................................24

- Figure 6-1: Fracture control evaluation procedures ...............................................................29

- Figure 6-2: Safe life item evaluation procedure for metallic materials....................................35

- Figure 6-3: Safe life item evaluation procedure for composite, bonded and sandwich

items ....................................................................................................................367 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 - Figure 6-4: Evaluation procedure for fail-safe items...............................................................37

- Figure 8-1: Procedure for metallic pressure vessel and metallic liner evaluation ..................49

- Figure 10-1: Initial crack geometries for parts without holes ..................................................73

- Figure 10-2: Initial crack geometries for parts with holes .......................................................74

- Figure 10-3: Initial crack geometries for cylindrical parts .......................................................74

- Tables

- Table 8-1: Factor on stress for sustained crack growth analysis of glass items ....................61

- Table 10-1: Initial crack size summary, standard NDI............................................................70

8 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 ScopeThis ECSS Engineering Standard specifies the fracture control requirements to be imposed on space segments of space systems and their related GSE. 

The  fracture  control  programme  is  applicable  for  space  systems  and  related GSE when required by ECSS‐Q‐ST‐40 or by the NASA document NST 1700.7, incl. ISS addendum. 

The requirements contained in this Standard, when implemented, also satisfy the  fracture  control  requirements  applicable  to  the  NASA  STS  and  ISS  as specified in the NASA document NSTS 1700.7 (incl. the ISS Addendum). 

The NASA nomenclature differs in some cases from that used by ECSS. When STS/ISS‐specific  requirements  and  nomenclature  are 

included,  they  are identified as such. 

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

 

9 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply, However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

![Im0](images/Im0)

<table align="center">
</table>

ECSS‐E‐ST‐32‐02 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐40 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐70‐36 

ECSS‐Q‐ST‐70‐45 

ASTM E 164 

ASTM E 426 

ASTM E 1417 

ASTM E 1444 

ASTM E 1742 

DOT/FAA/AR‐

MMPDS 

EN 4179 

Space engineering – Structural design and 

verification of pressurized hardware 

Space product assurance – Quality assurance 

Space product assurance – Safety 

Space product assurance – Materials, mechanical parts and processes 

Space product assurance – Material selection for 

controlling stress‐corrosion cracking 

Space product assurance – Mechanical testing of metallic materials 

Standard Practice for Ultrasonic Contact 

Examination of Weldments 

Standard Practice for Electromagnetic (Eddy‐

Current) Examination of Seamless and Welded 

Tubular Products, Austenitic Stainless Steel and 

Similar Alloys 

Standard Practice for Liquid Penetrant Examination Standard Practice for Magnetic Particle Examination Standard Practice for Radiographic Examination Metallic Materials Properties Development and 

Standardization (MMPDS) (former MIL‐HDBK‐5) Aerospace – Qualification and Authorization of 

Personnel for Non‐destructive Testing 

10 ![Im0](images/Im0)

EN ISO 6520‐1 

ISO 17659 

MIL‐HDBK‐6870 

NAS‐410 

NSTS 1700.7 

NSTS 1700.7 ISS 

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Welding and allied processes – Classification of 

geometric imperfections in metallic materials – Part 1: Fusion welding 

Welding – Multilingual terms for welded joints with illustrations 

Inspection program requirements, nondestructive, for aircraft and missile materials and parts 

Nondestructive testing personnel qualification and certification 

Safety Policy and Requirements For Payloads Using the Space Transportation System (STS) 

Safety Policy and Requirements For Payloads Using <table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

11 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐ST‐00‐01 apply, in particular for the following terms: 

customer 

NOTE 

In this standard, the customer is considered to 

represent  the  responsible  fracture  control  or 

safety authority. 

For the purpose of this Standard, the following term and definition from ECSS‐E‐ST‐10‐03 apply: 

![Im0](images/Im0)

<table align="center">
</table>

flaw 

NOTE 

The term defect is used as a synonymous. 

maximum design pressure (MDP) 

service life 

For the purpose of this Standard, the following term and definition from ECSS‐E‐ST‐32‐02 apply: 

burst pressure 

hazardous fluid container 

leak before burst, LBB 

pressure component 

pressure vessel 

pressurized structure 

sealed container 

special pressurized equipment 

visual damage threshold, VDT 

NOTE 1  For 

typical 

implementation  of 

thin‐walled 

composite  structure,  the  VDT  is  sometimes  more 

specifically  defined  as  the  impact  energy  of  an 

12 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 impactor  with  a  hemi‐spherical  tip  of  16  mm 

diameter  resulting  in  0,3 mm  or  more  remaining 

surface  deflection,  after  sufficiently  long  time  to 

cover  potential  evolution  of  the  indentation  over 

time  (due  to  e.g.  wet  ageing,  fatigue  loading, 

viscoelasticity  of  the  resin)  between  impact  and 

inspection. 

It  can  be  time  consuming  to  determine  the  VDT 

based  on  remaining  surface  deflection  of  0,3 mm 

(see  NOTE  1)  after  a  sufficiently  long  time. 

Therefore,  tests  which  cause  mechanical  damage 

corresponding  to  a  deflection  of  at  least  1 mm, 

immediately  after  impact,  are  sometimes  used  to 

determine the VDT. 

NOTE 2 

For the purpose of this Standard, the following term and definition from ECSS‐Q‐ST‐40 apply: 

catastrophic hazard 

critical hazard 

- 3.2  Terms specific to the present standard

aggressive environment

3.2.1

combination  of  liquid  or  gaseous  media  and  temperature  that  alters  static  or fatigue crack‐growth characteristics from normal behaviour associated with an ambient temperature and laboratory air environment 

analytical life

3.2.2

life evaluated analytically by crack‐growth analysis or fatigue analysis 

![Im0](images/Im0)

<table align="center">
</table>

<NASA  STS  or  ISS  payloads>  potential  risk  situation  that  can  result  in  a <table align="center">
</table>

close visual inspection

3.2.5

close proximity, intense visual examination of the internal and external surfaces of a structure, including structural details or locations, for indications of impact damage, flaws, and other surface defects 

NOTE 

The  inspection  capability  is  evaluated  by  the 

surface deflection measurement (impact depth). 

The  close  visual  inspection  is  considered  to 

13 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 detect  reliably  a  deflection  larger  than  the 

visual damage threshold (VDT). 

containment

3.2.6

damage tolerance design principle that, if a part fails, prevents the propagation of failure effects beyond the container boundaries 

NOTE 1  A contained part is not considered PFCI, unless its 

release  can  cause  a  hazard  inside  the  container. 

The container is a PFCI, and its structural integrity 

after  impact  is  verified  as  part  of  fracture  control 

activities. 

In  this  standard,  the  term  containment  in  most 

cases also covers items which are e.g. restrained by 

a  tether  to  prevent  the  occurrence  of  hazardous 

events due to failure of the item. 

NOTE 2 

crack-like defect

3.2.7

defect that has the same mechanical behaviour as a crack 

NOTE 1  “Crack”  and  “crack‐like  defect”  are  considered 

synonymous in this standard. 

NOTE 2  Crack‐like  defects  can,  for  example,  be  initiated 

during  material  production,  fabrication  or  testing 

or  developed  during 

life  of  a 

component. 

the  service 

NOTE 3  The term “crack‐like defect” can include: 

•  For  metallic  materials  flaws, 

pores and other similar defects. 

inclusions, 

•  For  non‐metallic  materials,  debonding, 

broken fibres, delamination, impact damage 

and other specific defects depending on the 

material. 

![Im0](images/Im0)

<table align="center">
</table>

<part‐through corner crack> ratio of crack depth to crack length  

crack growth rate

3.2.10

rate of change of crack dimension with respect to the number of load cycles or time 

NOTE 

For example da/dN, dc/dN, da/dt and dc/dt. 

crack growth retardation

3.2.11

reduction  of  crack‐growth  rate  due  to  overloading  of  the  cracked  structural member 

14 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 critical crack size

3.2.12

the crack size at which the structure fails under the maximum specified load NOTE 

The  maximum  specified  load  is  in  many  cases 

the  limit  load,  but  sometimes  higher  than  the 

limit load (e.g. for detected defects, composites 

and glass items) 

critical initial defect, CID

3.2.13

critical (i.e., maximum) initial crack size for which the structure can survive  the specified number of lifetimes. 

critical stress-intensity factor

3.2.14

value  of  the  stress‐intensity  factor  at  the  tip  of  a  crack  at  which  unstable propagation of the crack occurs 

NOTE 1  This  value  is  also  called  the  fracture  toughness. 

The  parameter  KIC  is  the  fracture  toughness  for 

plane  strain  and  is  an  inherent  property  of  the 

material.  For  stress  conditions  other  than  plane 

strain,  the  fracture  toughness  is  denoted  KC.  In 

fracture mechanics analyses, failure is assumed to 

be  imminent  when  the  applied  stress‐intensity 

factor  is  equal  to  or  exceeds  its  critical  value,  i.e. 

the fracture toughness. See 3.2.25. 

toughness 

is  used  as  a 

NOTE 2  The 

fracture 

term 

synonymous.  

cyclic loading

3.2.15

fluctuating load (or pressure) characterized by relative degrees of loading and unloading of a structure 

NOTE 

For example, loads due to transient responses, 

flutter,  pressure 

vibro‐acoustic 

cycling 

reciprocating 

mechanical equipment. 

and  oscillating  or 

excitation, 

damage tolerance threshold strain

3.2.16

<composite  structural  items>  maximum  strain  level  below  which  damage compatible  with  the  sizes  established  by  non‐destructive  inspection  (NDI), special visual inspection, the damage threat assessment, or the minimum sizes imposed does not grow in 106 cycles (108 cycles for rotating hardware) at a load ratio appropriate to the application 

NOTE 1  Strain  level  is  the  maximum  absolute  value  of 

strain in a load cycle. 

NOTE 2  The  damage 

tolerance 

threshold  strain 

is  a 

function  of  the  material  type  and  lay‐up  and  is 

determined 

the  design 

environment  to  the  applicable  or  worst  type  and 

orientation  of  strain  and  flaw  for  a  particular 

test  data 

from 

in 

15 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 design  and  flaw  size  (e.g.  the  size  determined  by 

the VDT). 

damage tolerant

3.2.17

characteristic of a structure for which the amount of general degradation or the size and distribution of local defects expected during operation, or both, do not lead to structural degradation below specified performance 

defect

3.2.18

see ‘flaw’ (3.1) 

detected defect

3.2.19

defect known to exist in the hardware 

fail-safe

3.2.20

<structures>  damage‐tolerance  design  principle,  where  a  structure  has redundancy  to  ensure  that  failure  of  one  structural  element  does  not  cause general failure of the entire structure during the remaining lifetime 

fastener

3.2.21

item that joins other structural items and transfers loads from one to the other across a joint 

fatigue

3.2.22

cumulative  irreversible  damage  incurred  by  cyclic  application  of  loads  to materials and structures  

NOTE 1  Fatigue  can  initiate  and  extend  cracks,  which 

degrade the strength of materials and structures. 

NOTE 2  Examples of factors influencing fatigue behaviour 

of  the  material  are  the  environment,  surface 

condition and part dimensions  

fracture critical item

3.2.23

item classified as such 

fracture limited life item

3.2.24

hardware  item  that  requires  periodic  re‐inspection  or  replacement  to  be  in conformance with fracture control requirements 

fracture toughness

3.2.25

materials’ resistance to the unstable propagation of a crack 

NOTE 

See critical stress intensity factor, 3.2.14. 

initial crack size

3.2.26

maximum crack size, as defined by non‐destructive inspection, for performing a fracture control evaluation 

16 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 joint

3.2.27

element that connects other structural elements and transfers loads from one to the other across a connection 

load enhancement factor, LEF

3.2.28

factor to be applied on the load level of the spectrum of fatigue test(s) in order to demonstrate with the test(s) a specified level of reliability and confidence NOTE 1  The  LEF  is  dependent  upon  the  material  or 

construction,  the  number  of  test  articles,  and  the 

duration of the tests. 

NOTE 2  MIL‐HDBK‐17F,  Volume  3,  Section  7.6.3  gives  an 

approach  for  calculating  the  LEF  for  composite 

structures. 

loading event

3.2.29

condition, phenomenon, environment or mission phase to which the structural system is exposed and which induces loads in the structure 

load spectrum

3.2.30

representation of the cumulative static and dynamic loadings anticipated for a structural element during its service life 

NOTE 

Load spectrum is also called load history. 

mechanical damage

3.2.31

induced  flaw  in  a  composite  hardware  item  that  is  caused  by  external influences, such as surface abrasions, cuts, or impacts 

potential fracture critical item, PFCI

3.2.32

item for which the initiation or propagation of cracks in structural items during the service life can result in a catastrophic or critical hazard, or NASA STS/ISS catastrophic hazardous consequences 

NOTE 

Pressure  vessels  and  rotating  machinery  are 

always considered PFCI. See Figure 5‐1. 

3.2.33

ratio of the minimum stress to maximum stress 

R-ratio

residual stress

3.2.34

stress that remains in the structure, owing to processing, fabrication, assembly or prior loading 

rotating machinery

3.2.35

rotating mechanical assembly that has a kinetic energy of 19300 joules or more, or an angular momentum of 136 Nms or more 

NOTE 

The amount of kinetic energy is based on 0,5 Iω2 

where I is the moment of inertia (kg.m2) and ω 

is the angular velocity (rad/s). 

17 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 safe life

3.2.36

fracture‐control  design  principle,  for  which  the  largest  undetected  defect  that can exist in the part does not grow to failure when subjected to the cyclic and sustained loads and environments encountered in the service life 

special NDI

3.2.37

NDI  methods  that  are  capable  of  detecting  cracks  or  crack‐like  flaws  smaller than  those  assumed  detectable  by  Standard  NDI  or  do  not  conform  to  the requirements for Standard NDI 

NOTE 1  See 10.4.2.1 and 10.4.3. 

NOTE 2  Special NDI methods are not limited to fluorescent 

penetrant,  radiography,  ultrasonic,  eddy  current, 

and magnetic particle. See also 10.4.2.2. 

standard NDI

3.2.38

NDI  methods  of  metallic  materials  for  which  the  required  statistically  based flaw detection capability has been established. and it is listed in Table 10‐1 

 For standard NDI, see clauses 10.4.2.1 and 10.4.3.  

NOTE 1 

NOTE 2  For  required  statistically  based  flaw  detection 

capability, see 10.4.2.1e.  

NOTE 2  Limitations on the applicability of standard NDI to 

radiographic  NDI  can  be  found  in  10.4.2.1f  and 

10.4.2.1g. 

NOTE 4  Standard  NDI  methods  addressed  by 

this 

document  are  limited  to  fluorescent  penetrant, 

radiography,  ultrasonic,  eddy 

current,  and 

magnetic particle. 

stress-corrosion cracking, SCC

3.2.39

initiation  or propagation, or  both,  of  cracks,  owing  to  the  combined  action  of applied  sustained  stresses,  material  properties  and  aggressive  environmental effects 

NOTE 

The  maximum  value  of  the  stress‐intensity 

factor  for  a  given  material  at  which  no 

environmentally  induced  crack  growth  occurs 

at sustained load for the specified environment 

is KISCC. 

stress intensity factor, K

3.2.40

calculated quantity that is used in fracture mechanics analyses as a measure of the stress‐field intensity near the tip of an idealised crack 

NOTE 

Calculated  for  a  specific  crack  size,  applied 

stress level and part geometry. See 3.2.14. 

threshold stress intensity range, ΔKth

3.2.41

stress‐intensity  range  below  which  crack  growth  does  not  occur  under  cyclic loading 

18 ![Im0](images/Im0)

![Im0](images/Im0)

variable amplitude spectrum

3.2.42

load spectrum or history whose amplitude varies with time 

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 - 3.3  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

 

Abbreviation  Meaning 

a/c 

AR 

ASME 

ASTM 

BS 

CDR 

CID 

COPV 

DOT 

DRD 

EN 

EPFM 

ESA 

FAD 

FCI 

FCIL 

FE 

FLLI 

FLLIL 

crack aspect ratio (see 3.2.8) 

acceptance review 

American Society of Mechanical Engineers 

American Society for Testing and Materials 

British Standard 

critical design review 

critical initial defect 

composite overwrapped pressure vessel 

United States Department of Transportation 

document requirements definition 

European Standard 

elastic‐plastic fracture mechanics 

European Space Agency 

failure assessment diagram 

fracture‐critical item 

fracture‐critical items list 

finite element 

fracture‐limited life item 

fracture‐limited life items list 

foreign object debris 

<table align="center">
	<tr align="center">
	</tr>
</table>

GSE 

ISO 

ISS 

J‐R curve 

K‐R curve 

LBB 

LEF 

ground support equipment 

International Organisation for Standardisation 

International Space Station 

resistance curve based on J‐integral 

resistance curve based on stress intensity factor (K) 

leak before burst 

load enhancement factor 

19 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 linear elastic fracture mechanics 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

plane strain fracture toughness 

threshold stress‐intensity factor for stress‐corrosion cracking threshold stress‐intensity range 

maximum design pressure 

maximum expected operating pressure 

National Aeronautics and Space Administration 

non‐destructive inspection 

non‐hazardous leak before burst 

National Space Transportation System (NASA Space Shuttle) preliminary design review 

potential fracture‐critical item 

potential fracture‐critical items list 

ratio of the minimum stress to maximum stress 

reduced fracture‐control programme 

Society of Automotive Engineers 

stress‐corrosion cracking 

international system of units 

system requirements review 

Space Transportation System (US Space Shuttle) 

ultrasonic 

visual damage threshold 

KIC

KISCC

ΔKth

MDP 

MEOP 

NASA 

NDI 

NHLBB 

NSTS 

PDR 

PFCI 

PFCIL 

R 

RFCP 

SAE 

SCC 

SI 

SRR 

STS 

US 

VDT 

 

20 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Principlesfollowing  assumptions  and  prerequisites  are 

The 

the implementation  of  the  requirements  contained  in  this  standard.  They  can  be used  as  reference  for  example  when  alternative  approaches,  not  directly covered by the requirements of this standard, are assessed for equivalent safety or reliability. 

•

the  basis  of 

All  structural  elements  contain  crack‐like  defects  located  in  the  most critical area of the component in the most unfavourable orientation. The inability  of  non‐destructive  inspection  (NDI)  techniques  to  detect  such defects does not negate this assumption, but merely establishes an upper bound on the initial size of the cracks which result from these defects. For conservatism, this crack size then becomes the smallest allowable size to be used in any analysis or assessment. 

After undergoing a sufficient number of cycles at sufficiently high stress amplitude, materials exhibit a tendency to propagate cracks, even in non‐aggressive environments. 

Whether, under cyclic or sustained tensile stress, a pre‐existing (or load‐induced) crack does or does not propagate depends on: 

⎯

⎯

⎯

⎯

⎯

⎯

⎯

the material behaviour with crack; 

the initial size and geometry of the crack; 

the presence of an aggressive environment; 

the geometry of the item; 

the magnitude and number of loading cycles; 

the duration of sustained load; 

the temperature of the material. 

For metallic materials, the engineering discipline of linear elastic fracture mechanics  (LEFM)  provides  analytical  tools  for  the  prediction  of  crack propagation and critical crack size. Validity of LEFM, depends on stress level,  crack  configuration  and  structural  geometry.  The  engineering discipline of elastic‐plastic fracture mechanics (EPFM) provides analytical tools for the prediction of crack initiation, stable ductile crack growth and critical crack size. 

For  non‐metallic  materials  (other  than glass and  other  brittle  materials) and  fibre‐reinforced  composites  (both  with  metal  and  with  polymer matrix),  linear  elastic  fracture  mechanics  technology  is  agreed  by  most 21 •

•

•

•

![Im0](images/Im0)

![Im0](images/Im0)

•

•

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 authorities to be inadequate, with the exception of interlaminar fracture mechanics  applied  to  debonding  and  delamination.  Fracture  control  of these materials relies on the techniques of safe life assessment supported by tests, containment, fail safe assessment, and proof testing.  

Composite, bonded and sandwich items are manufactured and verified to high quality control standards to assure aerospace quality hardware. The hardware developer of composite, bonded and sandwich items uses only manufacturing processes and controls (NDI, coupon tests, sampling techniques, etc.) that are demonstrated to be reliable and consistent with established  aerospace 

composite/bonded structures. 

The  observed  scatter  in  measured  material  properties  and  fracture mechanics analysis uncertainties is considered. 

industry  practices 

for 

NOTE 

For example, scatter factor and LEF 

For NSTS and ISS payloads, entities controlling the pressure are two‐fault tolerant, see NSTS 1700.7 (incl. ISS Addendum). 

NOTE 

For  example,  regulators,  relief  devices  and 

thermal control systems 

22 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Fracture control programmeA fracture control programme shall be implemented by the supplier for space systems and their related GSE in conformance with this Standard, when  required  by  ECSS‐Q‐ST‐40  or  the  NASA  document  NSTS  1700.7, incl. ISS Addendum (clause 208.1). 

Fracture control requirements as defined in this standard shall be applied where structural failure can result in a catastrophic or critical hazard.  NOTE 

System 

In  NASA  NSTS  1700.7  (Safety  Policy  and 

Requirements  For  Payloads  Using  the  Space 

Transportation 

ISS 

Addendum,  the  payload  structural  design  is 

based on fracture control procedures when the 

failure  of  a  structural  item  can  result  in  a 

catastrophic event. 

[STS]), 

incl. 

Implementation of fracture control for structural GSE may be limited to items which are not covered by other structural safety requirements. 

In  many  cases  this  limits  fracture  control 

verification  to  elements  directly  interfacing 

with flight hardware. 

NOTE 

Items  for  which  implementation  of  fracture  control  programme  is required shall be selected in conformance with Figure 5‐1.  

For  unmanned,  single‐mission,  space  vehicles  and  their  payloads,  and GSE the reduced fracture control programme, specified in clause 11, may be implemented. 

- 5.1  General

a.

b.

c.

d.

e.

- 5.2  Fracture control plan

a.

b.

The  supplier  shall  prepare  and  implement  a  fracture  control  plan  in conformance with ECSS‐E‐ST‐32 ‘Fracture control plan – DRD’. 

The fracture control plan shall be subject to approval by the customer. 23 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009    Legend 

*  contained or restrained items (see 

subclause 6.3.4) are generally not 

considered PFCI. Their containers are. 

Design concept

and 

management 

Manned or reusable 

projects 

Unmanned, single mission 

projects or GSE* 

Reduced fracture control per 

clause 11 

Structural screening

Hazard analysis 

For reduced fracture control identify items per subclause 11.2

Can failure lead to 

catastrophic or 

critical hazard ?* 

No

Is item a pressure 

vessel or rotating 

machinery ? 

No 

Yes 

Yes

Fracture control required

Record item as potential 

fracture–critical item 

Fracture control not 

required 

Figure 5‐1: Identification of PFCI 

- 5.3  Reviews

5.3.1  General

a.

Fracture control activities and status shall be reported during all project reviews. 

NOTE 

For project reviews, see ECSS‐M‐ST‐10. 

24 ![Im0](images/Im0)

![Im0](images/Im0)

Safety and project reviews

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 The schedule of fracture control activities shall be related to, and support, the project safety review schedule.  

5.3.2

a.

NOTE   As  specified  in  ECSS‐Q‐ST‐40,  safety  reviews 

are  performed  in  parallel  with  major  project 

reviews. 

b.

Fracture  control  documentation  shall  be  provided  for  the  reviews  as follows: 

1.

2.

For a system requirements review (SRR) 

The  results  of  preliminary  hazard  analysis  and  fracture  control screening (which follows the methodology given in Figure 5‐1) and a  written  statement  as  to  whether  or  not  fracture  control  is applicable.  

For a preliminary design review (PDR) 

(a)  A  written  statement  which  either  confirms  that  fracture control  is  required  or  else  provides  a  justification  for  not implementing fracture control. 

Identification of fracture control‐related project activities in the fracture control plan including: 

−  Definition  of  the  scope  of  planned  fracture  control activities  dependent  upon  the  results  of  the  hazard‐analysis and fracture control screening performed. 

(b)

−  Identification of low‐risk fracture items. 

−  Identification  of  primary  design  requirements  and constraints  which  are  affected  by  or  affecting  fracture control implementation. 

NOTE 

For the fracture control plan, see 5.2. 

(c)

(d)

Submission of the fracture control plan to the customer for approval. 

Lists of potential fracture critical items and fracture critical items in conformance with clause 6.4.2. 

3.

For a critical design review (CDR) 

(a)  A  final  fracture  control  plan  which  is  approved  by  the customer. 

(b)  Verification  requirements  for  inspection  procedures  and (c)

personnel. 

The  status  of  fracture  control  activities,  together  with  a specific schedule for completion of the verification activities. (d)  A  description  and  summary  of  the  results  of  pertinent analyses and tests. 

NOTE 

See clause 6.4. 

25 ![Im0](images/Im0)

4.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 (e)

(f)

(g)

List of potential fracture critical items in conformance with clause 6.4.2. 

List of fracture critical items in conformance with clause 6.4.2. List of fracture limited‐life items in conformance with clause 6.4.2. 

(b)

(c)

For an acceptance review (AR) or qualification review (QR) 

(a)  A  fracture  control  summary  report  in  conformance  with clause  6.4.4,  showing  completion  of  all  fracture  control verification activities. 

Relevant test, inspection, procurement and analysis reports in conformance with clause 6.4. 

List of potential fracture critical items in conformance with clause 6.4.2. 

List of fracture critical items in conformance with clause 6.4.2. List of fracture limited‐life items in conformance with clause 6.4.2. 

Pressure‐vessel summary log, and, for payloads of the NSTS and  ISS,  in  conformance  with  NSTS/ISS  13830  clauses  7.2 and 7.12. 

(d)

(e)

(f)

26 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Identification and evaluation of PFCI- 6.1

Identification of PFCIs

a.

Fracture  control  screening  of  structural  elements  (structural  screening) shall be performed to identify PFCI for the complete structure, including related GSE directly connected to the flight structure, except when clause 11 applies. 

NOTE 

See also Figure 5‐1. 

b.  When  clause  11  applies,  the  fracture  control  screening  of  structural c.

d.

elements may be limited to the items listed in 11.2.2.1. 

For the purpose of 6.1g, the structural screening to identify PFCI shall be documented. 

NOTE 

The  screening  results,  incl.  explanation  why 

certain  structural 

(if  any)  are  not 

considered as PFCI, can be reported e.g. in the 

PFCIL 

items 

In  support  of  the  structural  screening,  the  hazard  analysis  of  the  space system,  performed  in  conformance  with  ECSS‐Q‐ST‐40  clause  on “Hazard  analysis”,  shall  identify  where  structural  failure  of  flight ![Im0](images/Im0)

<table align="center">
</table>

by fracture control implementation. 

<table align="center">
</table>

e.

listed in 6.1e. 

For payloads on the NSTS or ISS, including transportation events to ISS, the  supplier  shall  identify  structural  items  as  PFCI,  with  potential  to cause a catastrophic hazard: 

1.  Where failure of the item can result in the release of any element or fragment  with  a  mass  of  more  than  113,5 g  (0,25 pounds)  during launch or landing. 

2.  Where failure of the item can result in the release or separation of any tension preloaded structural element or fragment with a mass of more than 13 g (0,03 pounds) if the item has a fracture toughness (KIC) to tensile yield strength ratio less than 1,66 mm½ (0,33 in1/2), or if  the  item  is  a  steel  bolt  whose  ultimate  strength  exceeds 1 240 MPa (180 ksi). 

27 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 3.  Where  failure  of  the  item  can  result  in  the  release  of  hazardous substances. 

4.  Where  failure  of  the  item  can  prevent  configuration  for  safe descent from orbit. 

5.  Where  failure  of  the  item  can  result  in  the  release  during  zero gravity flight of any mass that can impact critical hardware or crew personnel,  with  a  velocity  higher  than  10,7 m/s  (35 ft/s)  or  a momentum exceeding 1,21 Ns (8,75 ft–lb/s). 

f.

Containers  and  restraining  elements,  which  prevent  failed  items  from creating a catastrophic or critical hazard, shall be classified PFCI. 

NOTE 

In addition to verification as safe‐life or fail‐safe 

or  low  risk  item  (as  appropriate),  containers 

and restraining elements are verified to provide 

adequate  containment  or  restraint  in  case  of 

failure of the items. 

g.

h.

Potential  fracture‐critical  items  (PFCI)  identified  in  conformance  with 6.1a,  6.1c,  6.1d,  6.1e    shall  be  included  in  the  potential  fracture‐critical item list (PFCIL), specified in clause 6.4. 

In  order  to  ensure  that  the  implementation  of  the  fracture  control programme  is  compatible  with  the  current  design  and  service‐life scenario,  hazard  analysis  and  structural  screening  shall  be  repeated  to incorporate design progress and design changes. 

- 6.2  Evaluation of PFCIs

6.2.1

a.

b.

Damage tolerance

Each PFCI shall be damage tolerant. 

For the damage tolerance evaluation of PFCI, one of the following design principles shall be used in conformance with 6.3: 

⎯

⎯

⎯

 

Safe life, or 

Fail‐safe, or 

Low‐risk fracture 

NOTE 1  An  overview  of  the  fracture  control  evaluation 

procedure,  including  damage  tolerance  design 

approaches,  classification  of  Potential  Fracture 

Critical  Items  and  the  relevant  documentation  is 

illustrated in Figure 6‐1. 

NOTE 2  Another  way  to  implement  damage  tolerance  is 

is 

containment. 

considered  a  fracture  control  activity  (see  clause 

6.3.4).  The  container  (or  restraint)  is  a  PFCI  (see 

6.1f). Contained (or restrained) items are however 

not considered PFCI (see Figure 5‐1). 

Containment 

verification 

28 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 ![Im0](images/Im0)

![Im71](images/Im71)

![Im69](images/Im69)

![Im70](images/Im70)

![Im65](images/Im65)

![Im66](images/Im66)

![Im74](images/Im74)

![Im75](images/Im75)

![Im76](images/Im76)

![Im77](images/Im77)

![Im63](images/Im63)

![Im64](images/Im64)

![Im67](images/Im67)

![Im68](images/Im68)

![Im72](images/Im72)

![Im73](images/Im73)

![Im15](images/Im15)

![Im82](images/Im82)

![Im83](images/Im83)

![Im56](images/Im56)

![Im57](images/Im57)

![Im15](images/Im15)

![Im84](images/Im84)

![Im85](images/Im85)

![Im86](images/Im86)

![Im87](images/Im87)

![Im15](images/Im15)

![Im58](images/Im58)

![Im88](images/Im88)

![Im89](images/Im89)

![Im22](images/Im22)

![Im23](images/Im23)

![Im9](images/Im9)

![Im10](images/Im10)

![Im26](images/Im26)

![Im11](images/Im11)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im1](images/Im1)

![Im2](images/Im2)

![Im4](images/Im4)

![Im5](images/Im5)

![Im24](images/Im24)

![Im25](images/Im25)

![Im15](images/Im15)

![Im16](images/Im16)

![Im17](images/Im17)

![Im6](images/Im6)

![Im7](images/Im7)

![Im15](images/Im15)

![Im18](images/Im18)

![Im19](images/Im19)

![Im20](images/Im20)

![Im21](images/Im21)

![Im59](images/Im59)

![Im60](images/Im60)

![Im3](images/Im3)

![Im27](images/Im27)

![Im28](images/Im28)

![Im15](images/Im15)

![Im8](images/Im8)

![Im29](images/Im29)

![Im30](images/Im30)

![Im31](images/Im31)

![Im32](images/Im32)

![Im15](images/Im15)

![Im33](images/Im33)

![Im34](images/Im34)

![Im15](images/Im15)

![Im35](images/Im35)

![Im36](images/Im36)

![Im38](images/Im38)

![Im39](images/Im39)

![Im15](images/Im15)

![Im40](images/Im40)

![Im41](images/Im41)

![Im15](images/Im15)

![Im15](images/Im15)

![Im78](images/Im78)

![Im79](images/Im79)

![Im44](images/Im44)

![Im45](images/Im45)

![Im42](images/Im42)

![Im43](images/Im43)

![Im61](images/Im61)

![Im62](images/Im62)

![Im37](images/Im37)

![Im15](images/Im15)

![Im46](images/Im46)

![Im47](images/Im47)

![Im15](images/Im15)

![Im80](images/Im80)

![Im81](images/Im81)

![Im48](images/Im48)

![Im49](images/Im49)

![Im15](images/Im15)

![Im50](images/Im50)

![Im51](images/Im51)

![Im15](images/Im15)

![Im52](images/Im52)

![Im53](images/Im53)

![Im54](images/Im54)

![Im55](images/Im55)

![Im15](images/Im15)

<table align="center">
	<tr align="center">
		<td></td>
	</tr>
</table>

-  

Figure 6‐1: Fracture control evaluation procedures 29 ![Im0](images/Im0)

6.2.2

a.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Fracture critical item classification

The following items shall be classified as fracture critical item (FCI): 

1.

Composite,  bonded,  sandwich  or  other  non‐metallic  PFCI,  unless fail safe, low‐risk fracture or contained. 

2.  Metallic  PFCI  which  require  NDI  better  than  standard  NDI,  as 3.

4.

specified in clause 10.3. 

Pressure  vessels  in  conformance  with  clause  8.2.2,  or  pressurised structures specified fracture critical in clause 8.2.3. 

PFCI which require periodic re‐inspection or replacement in order to achieve the required life.  

NOTE 1  Such  items  are  called  fracture  limited‐life  items 

(FLLI) as a subset of FCI. 

NOTE 2  Having  FLLI 

is  not  always  desirable 

from 

programmatic considerations. 

5.

Rotating machinery as specified in clause 3.2.35. 

- 6.3  Compliance procedures

6.3.1  General

a.

The verification of PFCIs shall be done by analysis or by test or both. 

For various items special compliance procedure 

requirements are specified in clause 8. 

NOTE 

b.

The  methodology  applied  for  evaluation  by  test  shall  be  subject  to customer approval. 

NOTE 

is 

Customer  approval 

specified,  because 

evaluation  by  test  is  not  specified  to  the  same 

level  of  detail  than  evaluation  by  analysis. 

Evaluation  by  test  is  similar  to  evaluation  by 

analysis,  where  appropriate  and  not  specified 

otherwise. 

Safe life items

6.3.2

a.

The evaluation procedure for a PFCI considered as a safe life item shall be in conformance with Figure 6‐3, for metallic items, and Figure 6‐4, for composite, bonded and sandwich items. 

Except  where  it  is  explicitly  specified  otherwise,  the  initial  crack  or damage size used for the verification (by analysis or test) of safe life items shall be detectable by the applied NDI with at least 90% probability and 95% confidence. 

For  metallic  materials,  the  worst  crack‐like  defect  in  the  part  shall  not grow  to  such  an  extent  that  the  minimum  specified  performance  is  no b.

c.

30 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 longer  assured  within  a  specified  safe  life  interval,  using  a  design  life factor of at least four (4). 

NOTE 

For  example,  minimum  specified  performance 

can  be  the  limit‐load  capability  (no  failure  or 

burst  or  excessive  deformation)  or  no‐leak, 

depending on the hazard to be prevented. 

d.

e.

f.

g.

h.

For metallic materials the maximum sustained stress‐intensity factor Kmax, shall not exceed the threshold stress‐intensity factor for stress‐corrosion cracking KISCC. 

For composite, bonded and sandwich items, the worst damage in the part shall not grow within a safe life interval, using a design life factor of 1 and a load enhancement factor of 1,15, after which the structure is still able to assure ultimate load capability. 

For  limited  life  items,  a  reduced  service  life  shall  be  verified,  which allows re‐inspection or replacement of the items when:  

1.

The analytical life is less than 2 flights, for manned Shuttle‐mission. NOTE 

This is to allow for a potential aborted mission 

and subsequent reflight. 

The analytical life is less than one flight, for any other case. 

2.

For metallic materials, safe life analysis shall be performed as specified in clause 7. 

Safe  life  items  made  of  non‐metallic  materials,  other  than  composite, bonded and sandwich items, shall be in conformance with 8.5 and 8.7. 6.3.3

a.

b.

Fail-safe items

The evaluation procedure for a PFCI considered as fail‐safe item shall be as specified in Figure 6‐4. 

The  structure  remaining  after  failure  of  any  element  of  the  PFCI  shall sustain  the  limit  loads  with  a  safety  factor  of  1,0  for  metallic  and  glass items or 1,15 for composite, bonded and sandwich items, without losing minimum specified performance. 

NOTE   Minimum 

specified  performance 

includes 

prevention of large scale yielding. 

c.

The  failure  of  the  item  shall  not  result  in  the  release  of  any  part  or fragment which can create a catastrophic or critical hazard. 

NOTE 

For  payloads  on  the  NSTS  or  ISS,  including 

transportation  events  to  ISS,  as  minimum  the 

mass and momentum limits defined in 6.1e are 

used. More in general, the maximum acceptable 

mass and velocity of released items is based on 

the results of the hazard analysis. 

d.

For  metallic  parts  the  fatigue  life  of  the  remaining  structure  shall  be evaluated by linear damage accumulation rule (Minerʹs rule). 

31 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 e.

f.

g.

h.

i.

For metallic parts, mean fatigue life material characteristics and a design life factor of at least four (4) shall be used.  

For composite, bonded and sandwich parts the fatigue assessment shall be  performed  using  the  mean  fatigue  life  material  characteristics,  a design life factor of 1 and a load enhancement factor of 1,15. 

In  the  case  that  no  fatigue  data  are  available,  the  fatigue  analysis  for metallic  parts  may  be  replaced  by  a  crack  growth  analysis  using  an equivalent initial crack size of a = c = 0,125 mm (corner or surface crack), and demonstrating no failure after four (4) times the service life. 

For  limited  life  items,  a  reduced  service  life  shall  be  verified,  which allows replacement of the items when: 

1.

Less than 2 flight lives remain, for manned Shuttle‐mission. 

This is to allow for a potential aborted mission 

and subsequent re‐launch. 

NOTE 

Less than one flight life remains, for any other case. 

2.

Fail‐safe  items  made  of  non‐metallic  materials,  other  than  composite, bonded, sandwich and glass items, shall be in conformance with 8.5. 

Contained items

6.3.4

a.

It shall be verified by analysis or test that the release of any loose item which can create a catastrophic or critical hazard is effectively prevented by an enclosure, protective cover or restraining element. 

NOTE 

Successful containment verification implies not 

to  consider  the  contained  items  as  PFCI.  The 

containing or restraining elements are PFCI (see 

6.1). 

b.

c.

d.

e.

f.

For payloads of the NASA STS or ISS, it shall be verified by analysis or test that any loose item exceeding the allowable mass defined in clause 6.1e  is  prevented  from  being  released  into  the  cargo  bay  or  crew compartments. 

For metallic enclosures, it shall be verified that the loose item does not penetrate or fracture the enclosure with a safety factor of 1,5 on its kinetic energy. 

For composite, bonded and sandwich enclosures, it shall be verified by test (or analysis supported by test) that the loose part does not penetrate or fracture the enclosure with a safety factor of 1,5 on its kinetic energy. Composite, bonded and sandwich enclosures shall not be fracture critical in conformance with clause 6.2.2, for reasons such as providing a single point of failure support that can create a catastrophic or critical hazard if the enclosure failed. 

Engineering judgment supported by documented technical rationale may be  used  when  it  is  obvious  that  an  enclosure,  a  barrier,  or  a  restraint prevents the part from escaping. 

32 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 NOTE 

Examples of such enclosures that have obvious 

containment  capability  include  metallic  boxes 

containing closely packed electronics, detectors, 

cameras,  and  electric  motors;  pumps  and 

gearboxes  having  conventional  housings;  and 

shrouded  or  enclosed  fans  not  exceeding 

200 mm  in  diameter  and  an  8 000  revolutions 

per minute (rpm) speed. 

g.  When enclosures are designed to be opened the closure devices shall be single  failure  tolerant  against  failure  to  close  if  they  are  required  to  be closed again to establish containment for a later phase of the mission. 6.3.5

Low-risk fracture items

6.3.5.1  General

a.  Metallic  low‐risk fracture  items  shall  be  in  conformance  with  6.3.5.2  and 6.3.5.3. 

b.  Composite,  bonded  and  sandwich  low‐risk fracture  items  shall  be  in conformance with 8.4.4.3. 

Limitations on applicability for metallic parts

6.3.5.2

a.

The following PFCI shall not be accepted as low risk fracture items: 

1.

shells  of  human‐tended  modules  or  personnel 2.

3.

Pressure 

compartments. 

Pressure vessels. 

Pressurized  components  in  a  pressurized  system  containing  a hazardous fluid. 

High‐energy or high momentum rotating machinery. 

Fasteners. 

4.

5.

The maximum tensile stress based on net cross‐sectional area in the part at  limit  load  shall  be  no  greater  than  30  percent  of  the  ultimate  tensile strength for the metal used. 

The  use  of  low‐risk fracture  classification  shall  be  agreed  with  the customer. 

b.

c.

6.3.5.3

Inherent assurance against catastrophic or criticalfailure from a flaw for metallic parts

6.3.5.3.1  Remote possibility of significant crack-like defect

a.

The following criteria shall be met: 

1.

Low‐risk fracture  items  are  fabricated  from  a  well‐characterized metal,  procured  in  conformance  with  an  aerospace  standard  or equivalent standard approved by the customer, which is selected from  Table  5‐1  (Alloys  with  high  resistance  to  stress‐corrosion 33 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 2.

cracking) of ECSS‐Q‐ST‐70‐36 and therefore not sensitive to stress corrosion  cracking  in  environmental  conditions  addressed  by ECSS‐Q‐ST‐70‐36. 

Low‐risk fracture items are not fabricated using a process that has a recognized risk of causing significant crack‐like defects, such as welding,  forging,  casting,  or  quenching  heat  treatment  (for materials susceptible to cracking during heat treatment quenching) unless  specific  NDI  or  testing,  which  has  been  approved  by  the customer, is applied to sufficiently screen for defects.  

NOTE 1 

It  can  be  assumed  that  significant  crack‐like 

defects do not occur during machining of sheet, 

bar, and plate products from materials that are 

known  to  have  good  machinability  properties, 

do  not  have  low  fracture  toughness  (i.e.  when 

the ratio KIc/Fty < 1,66 √mm; for steel bolts with 

unknown  KIc, 

is 

assumed when Ftu > 1240 MPa), and are metals 

or  alloys  produced 

in  conformance  with 

aerospace  specifications  and  standards  or 

equivalent grade specifications. 

toughness 

low 

fracture 

NOTE 2  Low‐risk fracture 

items  meet 

inspection 

standards consistent with aerospace practices to 

ensure  aerospace‐quality  flight  hardware.  This 

includes raw material inspection. 

3.

4.

5.

Low‐risk fracture  items  receive  visual  inspection  of  100%  of  the surface of the finished part. 

Low‐risk fracture items are inspected at the individual part level NOTE 

This is to assure maximum accessibility. 

Low‐risk fracture  items  are  rejected  in  case  of  detected  surface damage that can affect part life. 

6.3.5.3.2  Remote possibility of significant crack growth

a.

One of the following criteria shall be met: 

⎯

⎯

testing 

Low‐risk fracture  items  are  not  subjected  to  fatigue  loading beyond  acceptance  or  normal  protoflight 

(if  any), transportation,  and  one  mission  (including  a  potential  aborted mission), or 

Low‐risk fracture items are shown to possess acceptable resistance to crack growth from potential initial defects caused by machining, assembly,  and  handling,  by  demonstrating  that  assumed  initial surface cracks of 3 mm depth and 6 mm length and corner cracks of 3 mm radius from holes and edges do not grow to failure in less than four complete service lifetimes. 

34 ![Im0](images/Im0)

![Im0](images/Im0)

Yes 

Safe life item

Can item be verified 

by proof test only? 

(see 8.2.4.b) 

No 

Set initial defect size in conformace with standard 

(see clause 10.4.2.1)

Calculate analytical life in conformance with clause 7

Item not fracture–

critical**, but 

remains a PFCI 

Yes 

Is analytical life

> four times 

service life ? 

No

Is improved 

inspection  

possible? 

Yes

No 

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Redesign 

Rerun fracture analysis with improved 

inspection, in conformance with clause 7

Yes 

Is analytical life 

> four times service 

life ? 

No 

Is analytical life 

> four times reduced* 

service life? 

Yes

   Is acceptance 

of this item appropriate  

by system programmatics? 

Yes 

No 

No 

Legend

*  Incl. min. 2 flights for manned 

Shuttle‐mission payloads 

** Unless fracture critical for another reason (see 6.2.2) 

>  greater than 

Fracture–critical item 

Fracture limited‐life item 

- Note: Including metal matrix composites reinforced by particles or whiskers.

Figure 6‐2: Safe life item evaluation procedure for metallic materials 

35 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Figure 6‐3: Safe life item evaluation procedure for composite, bonded and 

sandwich items 

36 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im3](images/Im3)

![Im19](images/Im19)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im10](images/Im10)

![Im11](images/Im11)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im118](images/Im118)

![Im119](images/Im119)

![Im81](images/Im81)

![Im82](images/Im82)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im83](images/Im83)

![Im84](images/Im84)

![Im15](images/Im15)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im22](images/Im22)

![Im23](images/Im23)

![Im20](images/Im20)

![Im21](images/Im21)

![Im17](images/Im17)

![Im15](images/Im15)

![Im62](images/Im62)

![Im24](images/Im24)

![Im25](images/Im25)

![Im28](images/Im28)

![Im29](images/Im29)

![Im26](images/Im26)

![Im27](images/Im27)

![Im30](images/Im30)

![Im16](images/Im16)

![Im31](images/Im31)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im35](images/Im35)

![Im85](images/Im85)

![Im86](images/Im86)

![Im87](images/Im87)

![Im88](images/Im88)

![Im36](images/Im36)

![Im37](images/Im37)

![Im16](images/Im16)

![Im16](images/Im16)

![Im89](images/Im89)

![Im90](images/Im90)

![Im120](images/Im120)

![Im121](images/Im121)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im38](images/Im38)

![Im39](images/Im39)

![Im17](images/Im17)

![Im15](images/Im15)

![Im62](images/Im62)

![Im40](images/Im40)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im15](images/Im15)

![Im41](images/Im41)

![Im27](images/Im27)

![Im30](images/Im30)

![Im125](images/Im125)

![Im44](images/Im44)

![Im45](images/Im45)

![Im46](images/Im46)

![Im47](images/Im47)

![Im16](images/Im16)

![Im42](images/Im42)

![Im43](images/Im43)

![Im16](images/Im16)

![Im48](images/Im48)

![Im49](images/Im49)

![Im92](images/Im92)

![Im93](images/Im93)

![Im91](images/Im91)

![Im21](images/Im21)

![Im57](images/Im57)

![Im58](images/Im58)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im120](images/Im120)

![Im121](images/Im121)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im94](images/Im94)

![Im17](images/Im17)

![Im17](images/Im17)

![Im18](images/Im18)

![Im40](images/Im40)

![Im15](images/Im15)

![Im50](images/Im50)

![Im17](images/Im17)

![Im17](images/Im17)

![Im17](images/Im17)

![Im18](images/Im18)

![Im15](images/Im15)

![Im95](images/Im95)

![Im15](images/Im15)

![Im62](images/Im62)

![Im123](images/Im123)

![Im124](images/Im124)

![Im16](images/Im16)

![Im108](images/Im108)

![Im109](images/Im109)

![Im51](images/Im51)

![Im125](images/Im125)

![Im52](images/Im52)

![Im33](images/Im33)

![Im112](images/Im112)

![Im113](images/Im113)

![Im75](images/Im75)

![Im53](images/Im53)

![Im54](images/Im54)

![Im110](images/Im110)

![Im111](images/Im111)

![Im16](images/Im16)

![Im126](images/Im126)

![Im114](images/Im114)

![Im115](images/Im115)

![Im57](images/Im57)

![Im58](images/Im58)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im16](images/Im16)

![Im55](images/Im55)

![Im56](images/Im56)

![Im59](images/Im59)

![Im60](images/Im60)

![Im40](images/Im40)

![Im16](images/Im16)

![Im16](images/Im16)

![Im120](images/Im120)

![Im121](images/Im121)

![Im120](images/Im120)

![Im121](images/Im121)

![Im17](images/Im17)

![Im17](images/Im17)

![Im18](images/Im18)

![Im15](images/Im15)

![Im116](images/Im116)

![Im117](images/Im117)

![Im17](images/Im17)

![Im40](images/Im40)

![Im61](images/Im61)

![Im15](images/Im15)

![Im62](images/Im62)

![Im126](images/Im126)

![Im19](images/Im19)

![Im96](images/Im96)

![Im97](images/Im97)

![Im27](images/Im27)

![Im30](images/Im30)

![Im40](images/Im40)

![Im125](images/Im125)

![Im98](images/Im98)

![Im99](images/Im99)

![Im100](images/Im100)

![Im101](images/Im101)

![Im67](images/Im67)

![Im74](images/Im74)

![Im75](images/Im75)

![Im104](images/Im104)

![Im105](images/Im105)

![Im107](images/Im107)

![Im78](images/Im78)

![Im125](images/Im125)

![Im63](images/Im63)

![Im64](images/Im64)

![Im19](images/Im19)

![Im19](images/Im19)

![Im106](images/Im106)

![Im102](images/Im102)

![Im103](images/Im103)

![Im65](images/Im65)

![Im66](images/Im66)

![Im68](images/Im68)

![Im69](images/Im69)

![Im40](images/Im40)

![Im67](images/Im67)

![Im74](images/Im74)

![Im75](images/Im75)

![Im72](images/Im72)

![Im73](images/Im73)

![Im77](images/Im77)

![Im78](images/Im78)

![Im19](images/Im19)

![Im19](images/Im19)

![Im76](images/Im76)

![Im70](images/Im70)

![Im71](images/Im71)

![Im120](images/Im120)

![Im121](images/Im121)

![Im125](images/Im125)

![Im40](images/Im40)

![Im122](images/Im122)

![Im121](images/Im121)

![Im79](images/Im79)

![Im80](images/Im80)

![Im19](images/Im19)

![Im130](images/Im130)

![Im131](images/Im131)

![Im132](images/Im132)

![Im133](images/Im133)

![Im134](images/Im134)

![Im135](images/Im135)

![Im136](images/Im136)

![Im137](images/Im137)

![Im138](images/Im138)

![Im139](images/Im139)

![Im140](images/Im140)

![Im141](images/Im141)

![Im142](images/Im142)

![Im143](images/Im143)

![Im144](images/Im144)

![Im146](images/Im146)

![Im146](images/Im146)

![Im146](images/Im146)

![Im154](images/Im154)

![Im155](images/Im155)

![Im146](images/Im146)

![Im146](images/Im146)

![Im146](images/Im146)

![Im146](images/Im146)

![Im146](images/Im146)

![Im146](images/Im146)

![Im156](images/Im156)

![Im157](images/Im157)

![Im158](images/Im158)

![Im159](images/Im159)

![Im160](images/Im160)

![Im163](images/Im163)

![Im162](images/Im162)

![Im147](images/Im147)

![Im147](images/Im147)

![Im128](images/Im128)

![Im148](images/Im148)

![Im145](images/Im145)

![Im149](images/Im149)

![Im150](images/Im150)

![Im153](images/Im153)

![Im147](images/Im147)

![Im127](images/Im127)

![Im129](images/Im129)

![Im152](images/Im152)

![Im145](images/Im145)

![Im151](images/Im151)

![Im161](images/Im161)

![Im127](images/Im127)

![Im129](images/Im129)

![Im0](images/Im0)

Incl. min. 2 flights for Shuttle-mission payloads

- Legend

- *

- >  greater than

(1)  SF=1.00 for metallic parts

SF=1.15 for composite parts

Fail–safe item

Identify all load paths

Is potential

redundancy

provided ?

Yes

No

Can an item with

more than the allowable

mass become loose ?

See 6.1

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Yes

Is the item

contained ?

No

No

Yes

Analyse the consequences of the loss of the individual members and

identify the worst case

Is an increase in

load/stresses to be expected ?

e.g. caused by changed dynamic

behaviour due to the failure of

any of the individual

members

No

Yes

Calculate the new stress/load

Can the remaining

structure sustain limit

load x SF (1)?

No

Yes

Fatigue analysis

Yes

Yes

No

Is it a composite,

sandwich item?

bonded or

Item is not

fracture critical,

but verified as

fail-safe PFCI

Yes

No

No

Is analytical life

> 1 time service

life with load

enhancement

factor of 1.15?

No

Is analytical life

> four times service

life ?

No

Is analytical life

> four times reduced*

service life ?

Yes

Is acceptance of

this item appropriate by

system program-

matics ?

Yes

Fracture limited-life Item

Fracture–critical item

Figure 6‐4: Evaluation procedure for fail‐safe items 

The item is not fail–

safe. Redesign or evaluate assafe life item

37 ![Im0](images/Im0)

- 6.4  Documentation requirements

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Fracture control plan

A fracture control plan shall be provided in conformance with clause 5.2. 6.4.1

a.

6.4.2

a.

Lists

A PFCIL, FCIL and FLLIL shall be provided in conformance with ECSS‐E‐ST‐32 ‘Fracture control items lists (PFCIL, FCIL and FLLIL) ‐ DRD’ 

NOTE 1  The  potential  fracture‐critical  item  list  (PFCIL)  is 

compiled  from  the  results  of  the  fracture  control 

screening. 

NOTE 2  The  fracture‐critical  item  list  (FCIL)  includes  the 

same information as the PFCIL for each FCI, and in 

addition  specifies  a  reference  to  the  document 

which  shows  for  each  item  the  fracture  analysis 

and/or test results and the analytical life. 

NOTE 3  The fracture limited‐life item list (FLLIL) includes 

the  same  information  as  the  FCIL  for  each  FLLI, 

and in addition specify the inspection method and 

period,  and  identifies  the  maintenance  manual  in 

which inspection procedures are defined. 

NOTE 4  The  above  three  lists  can  be  reported  in  one 

document. 

Analysis and test documents

6.4.3

a.

The analysis of all PFCIs, FCIs, contained and restrained items shall be documented  in  a  fracture  control  analysis  report  in  conformance  with ECSS‐E‐ST‐32 ‘Fracture control analysis (FCA) ‐ DRD’. 

b.  When  testing  is  used  in  addition  to  analysis  of  PFCIs,  FCIs,  contained and  restrained  items,  the  test  method  and  test  results  shall  be documented  in  test  plans,  specifications,  procedures  and  reports  in conformance with: 

1.

2.

3.

4.

ECSS‐E‐ST‐10‐02 ‘Verification plan ‐ DRD’, 

ECSS‐E‐ST‐10‐03 ‘Test specification (TSPE) ‐ DRD’, 

ECSS‐E‐ST‐10‐03 ‘Test procedure (TPRO) ‐ DRD’, 

ECSS‐E‐ST‐10‐02 ‘Test report (TRPT) ‐ DRD’. 

NOTE 

The  “Verification  plan”  can  be  limited  to  a 

“Test plan”. 

Fracture control summary report

A  fracture  control  summary  report  shall  be  provided  with  each deliverable flight hardware item. 

The fracture control summary report shall contain the following: 

6.4.4

a.

b.

38 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 1.

2.

3.

4.

5.

Summary of identified PFCI, FCI, FLLI and applied NDI methods, with specific reference to low risk fracture PFCI, pressurized PFCI, safe life fasteners, composite PFCI, bonded PFCI, sandwich PFCI, glass  and  other  shatterable/brittle  PFCI,  other  non‐metallic  PFCI, and detected defects that remain in PFCI. 

A  summary  discussion  of  alternative  approaches  or  specialised assessment applied and tests performed. 

A statement that inspections or tests specified for fracture control were, in fact, applied in conformance with requirements, and that the proper use of the approved materials has been verified. 

A  statement  that  hardware  configuration  of  PFCI  and  their assemblies has been physically verified. 

References to supporting documentation. 

NOTE 

For example, analysis reports, test reports, NDI 

reports, 

results  and 

associated lists. 

structural 

screening 

39 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Fracture mechanics analysisStress distribution 

Load spectra 

Fracture  mechanics  analysis  shall  be  performed  to  determine  the analytical life of a safe life metallic item. 

The  following  data  shall  be  made  available  in  order  to  enable  crack growth prediction and critical crack‐size calculation: 

1.

2.

3.  Material properties 

4.

5.

For  the  fracture  mechanics  analysis,  the  latest  version  of  the  software package ESACRACK may be used. 

Initial crack size 

Stress intensity factor solutions. 

NOTE 1  Additional  information  on  this  software  package 

can  be  found  in  Annex  A,  which  also  addresses 

some of the limitations of this software. 

- 7.1  General

a.

b.

c.

![Im0](images/Im0)

<table align="center">
</table>

software. Update of the existing analysis using the 

latest version is normally performed, for example, 

in cases where the analysis is used to support the 

acceptance  of  detected  defects  (see  10.7),  or  in 

specific cases where there is a clear indication that 

the  existing  analysis  made  with  an  older  version 

can be inadequate. 

<table align="center">
</table>

submitted to the customer for approval prior to their use. 

A fracture mechanics analysis shall include the following two items: 

1.

2.

Crack‐growth calculation in conformance with 7.2. 

Critical crack‐size calculations in conformance with 7.3. 

NOTE 

In  most  cases  the  fracture  mechanics  analysis 

demonstrates a margin on the required lifetime 

and  crack  size,  based  on  initial  crack  sizes 

40 e.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 defined  for  standard  or  special  NDI.  As 

alternative,  the  critical  (i.e.,  maximum)  initial 

defect (CID) size for which the item can survive 

four  times  the  required  service  life  can  be 

calculated  iteratively,  after  which  it  can  be 

verified  by  inspection  that  the  probability  of 

having cracks greater than or equal to this size 

is  sufficiently  small.  This  CID  approach  is 

specifically appropriate for analysis of cracks to 

be screened by proof testing. The CID approach 

can  require  careful  scrutiny  of  the  validity  of 

the  analysis,  because  it  does  not  demonstrate 

any margin in the analysis results. 

- 7.2  Analytical life prediction

Identification of all load events

7.2.1

a.

b.

The service‐life profile of the item shall be defined in order to identify all cyclic and sustained load events to be included in the stress spectrum. All load events expected for the item shall be included in the service‐life profile. 

NOTE 

testing; 

Examples  of  load  events  expected  throughout 

the service life are: 

•  manufacturing and assembly; 

•

•  pressurisations on ground 

•  handling, e.g. by a dolly or a hoist; 

•

transportation by land, sea and air; 

•  ascent (launch);  

•  stay  in  orbit,  including  thermally  induced 

loads and operational loads; 

•  descent (re‐entry); 

•

landing. 

c.

For Shuttle missions, an aborted mission and subsequent reflight shall be included in the service‐life profile of the item. 

7.2.2

Identification of the most critical location

and orientation of the crack

a.

b.

The most critical location and orientation of the crack on the item shall be identified for the analysis. 

To  identify  the  most  critical  location,  the  following parameters  shall  be considered: 

41 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 1.

2.

3.

4.

5.

The maximum level of local stress. 

The range of cycling stress. 

Locations with high stresses or stress intensities. 

Areas where material fracture properties can be low. 

Stresses which, combined with the environment, result in reduced fracture resistance. 

Stress‐concentration, environmental and fretting effects. 

Severity of stress spectrum 

6.

7.

In cases where the most critical location or orientation of the initial crack is not obvious, the analysis shall consider a sufficient number of locations and orientations. 

c.

7.2.3

Derivation of stresses for the critical

location

a.

For the critical location, as identified in 7.2.2, the principal stresses shall be derived which are caused by the load components which act on the item during the load events identified in 7.2.1. 

to 

For  example,  principal 

translational  and 

rotational  accelerations, 

pressure,  temperature  and  loads  induced  by 

adjacent structure. 

stresses  due 

NOTE 

b.

The  stresses  shall  be  derived  for  the  worst  credible  combination  of  all influencing aspects 

NOTE 

influencing  aspects 

For  example, 

to  be 

considered include: geometrical discontinuities 

and 

imperfections,  manufacturing  defects, 

residual stresses 

Derivation of the stress spectrum

7.2.4

a.

b.

A  stress spectrum  shall  be  derived  for the  critical  location  identified  in 7.2.2, based on the load events identified in 7.2.1 and the stresses derived in 7.2.3. 

In the stress spectrum, the number of cycles in each step, and the upper and lower values of the stress components in each step shall be defined. NOTE 

For  example,  stress  components  are  remote 

tension  stress,  remote  bending  stress  and  pin 

bearing stress. 

c.

The stress spectrum shall be provided to the customer for approval. 

42 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Derivation of material data

7.2.5

a.  Material properties used in the analytical evaluation shall be valid for the anticipated  environment,  grain  direction,  material  thickness,  specimen width and load ratio (R). 

NOTE   Where 

the  operational 

temperature  range 

overlaps  with  the  ductile  to  brittle  fracture 

transition  temperature  range  of  the  material, 

the variation of material behaviour as function 

of  temperature  effect  over  this  temperature 

range is taken into account in the analysis. 

b.  Mean values of crack growth rate (da/dN, da/dt) shall be used. 

c.  Mean value of threshold stress intensity range (ΔKth) shall be used. 

d.

Lower boundary values shall be used, for: 

1.

Critical stress intensity factor, KIC or KC (fracture toughness), and other residual strength related properties (e.g. flow stress). 

Environmentally controlled threshold stress intensity for sustained loading, KISCC. 

2.

e.

f.

g.

h.

i.

Lower boundary values shall be derived as follows: 

1.

values with a 90% probability and 95% confidence level of being exceeded (B‐value as defined in DOT/FAA/AR‐MMPDS), or 

in cases where insufficient test data are available: 70 % of the mean values. 

2.

For the derivation of the proof loading to be applied for identification of initial crack sizes, upper boundary values, defined as 1,3 times the mean values, shall be used for the critical stress intensity factor, KIC or KC. 

For the derivation of the proof loading to be applied for identification of initial crack sizes, in the case of through cracks, and in case the elastic‐plastic  approach  is  applicable,  a  factor  of  1,3  shall  be  applied  to  the complete K‐R curve, or an equivalent factor 1,69 if the J‐R curve is used. For those materials where a significant reduction of the KC for thin sheets is observed, the reduced value shall be used in the analysis. 

NOTE 

This  reduction  of  fracture  toughness  is  not 

automatically accounted for in the ESACRACK 

software. 

Mechanical 

conformance with ECSS‐Q‐ST‐70‐45. 

testing  of  metallic  materials  shall  be  performed in 7.2.6

Identification of the initial crack size and

shape

a.

The initial crack shape shall be identified by considering the geometry of the  item  and  the  critical  location,  in  line  with  Figure  10‐1,  Figure  10‐2, and Figure 10‐3. 

43 ![Im0](images/Im0)

![Im0](images/Im0)

b.

c.

d.

e.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 The initial crack sizes used in the analysis shall be defined based on the inspection level or proof load screening used for the item. 

NOTE 

See also clause 10. 

Crack aspect ratios (a/c) of 0,2 and 1,0 shall be considered in the analysis. An initial crack size as specified in 7.2.6e shall be assumed if: 

1.

A  large  number  of  holes  are  drilled  or  the  automatic  hole preparation is used and NDI of holes cannot be performed. 

The  load  is  not  transmitted  through  a  single  hole,  such  as  for  a fitting. 

The holes are not punched. 

The material is not prone to cracking during machining. 

NDI is performed prior to the machining of the holes. 

No  heat  treatment  or  potentially  crack  forming  fabrication processes are performed subsequent to NDI. 

Approval is obtained from the customer. 

2.

3.

4.

5.

6.

7.

For  automatic  hole  preparation  indicated  in  7.2.6d,  an  initial  crack  size shall be assumed based on the worst of the following: 

1.

The  initial  crack  size  determined  by  the  NDI  performed  before hole preparation, or 

The potential damage from hole preparation operations, as defined below: 

(a)

2.

(b)

(c)

For drilled holes with driven rivets, the assumed defect due to potential damage is a 0,13 mm length crack through the thickness at one side of the hole. 

For fastener holes other than those for driven rivets, where the  material  thickness  is  equal  to  or  less  than  1,3  mm,  the assumed  fabrication  defect  due  to  potential  damage  is  a 1,3mm length crack through the thickness at one side of the hole. 

For fastener holes other than those for driven rivets, where the  thickness  is  greater  than  1,3  mm,  the  initial  crack  size due to potential damage is a 1,3 mm radius corner crack at one side of the hole. 

7.2.7

Identification of an applicable stress

intensity factor solution

a.

b.

Stress  intensity  factor  solutions  for  the  relevant  item  geometry,  crack shape, crack size and loading shall be used. 

Local  stresses  caused  by  stress  concentrations  shall  be  included  in  the applied  stress  spectrum  if  their  effect  is  not  fully  included  in  the  used stress intensity factor solutions used in 7.2.7a. 

44 ![Im0](images/Im0)

7.2.8

a.

b.

c.

d.

e.

f.

g.

h.

i.

j.

Performance of crack growth calculationsECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Crack  growth  calculations  shall  be  performed  using  the  variables  as defined in 7.2.1 to 7.2.7. 

The  analysis  methodology  used  shall  account  for  the  two‐dimensional growth characteristics of cracks, multiple loading events with variation in amplitude,  excursions  between  mean  stress  levels  and  negative  stress ratios. 

The complete loading spectrum shall be analytically imposed at least four (4) times in sequence, one after another. 

The loading spectrum shall be an envelope of all the credible load events that can be encountered during the design life. 

Growth of cracks beyond the critical crack size shall not be considered in the crack growth analysis. 

In  cases  where  leakage  is  hazardous,  growth  of  cracks  through  the thickness shall not be considered in the crack growth analysis. 

Beneficial  retardation  effects  on  crack  growth  rates  from  variable amplitude  spectrum  loading  shall  not  be  considered  without  the approval of the customer. 

For  components  where  a  crack  grows  into  a  hole,  the  analysis  shall assume that the crack propagation is not arrested or retarded by the hole. For cyclic plastic deformation, EPFM crack‐growth methodology shall be used, which is subject to customer approval. 

For  manufacturing  steps,  which  can  cause  crack  extension  without  the possibility of subsequent NDI the maximum possible crack growth shall be considered in the safe life calculation. 

NOTE 

For  example,  the  autofrettage  pressure  cycle 

during  manufacturing  of  a  COPV  which  can 

lead  to  crack  growth  by  linear  or  non‐linear 

material  behaviour.  Especially  the  non‐linear 

material  behaviour  can  lead  to  stable  crack 

growth 

can  be 

considerably underestimated. 

tearing)  which 

(ductile 

k.

Shear (i.e. mode II or mode III) loading of the crack shall be considered, using an analysis method agreed with the customer. 

- 7.3  Critical crack-size calculation

a.

The critical crack‐size (ac) shall be calculated by means of LEFM: 

## a

c

## K

)

(

c

∑=

## SF

(

π

i

 

)

i

where  Si  are  the  maximum  specified  stresses  and  Fi  are  the  stress intensity magnification factors for the different load cases (which depend on the crack size a) and KC is the critical stress intensity factor. 

45 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 NOTE 

The  maximum  specified  load  is  in  many  cases 

the  limit  load,  but  sometimes  higher  than  the 

limit load (e.g. for detected defects, composites 

and glass items). 

b.

In those cases outside the range of validity of LEFM, the critical crack size shall  be  evaluated  by  appropriate  EPFM  methods  or  by  a  structure representative test. 

NOTE 1  This  applies  also  to  crack  extension  under  non‐

linear  material  behaviour.  For  example  ductile 

tearing.  

NOTE 3 

NOTE 2  The  consideration  of  structure  representative 

conditions  is  of  great  importance  in  the  case  of 

EPFM,  where  for  example  stress  multi‐axiality 

effects can significantly influence the results of the 

analysis or test. 

In  the  NASGRO  module  of  the  ESACRACK 

software a simplified verification can be performed 

to ensure that no premature failure under elastic‐

plastic conditions occurs, based on comparison of 

the  so‐called net‐section  stress  and  flow  stress.  In 

most  of  the  common  applications  this  can  be 

considered  as  adequate.  For  e.g.  verification  of 

highly  critical,  highly  stressed  (e.g.  pressure 

vessels, launcher tanks) applications and detected 

defects  it  can  be  necessary  to  performed  more 

advanced EPFM analysis or testing. 

c.

The material properties used for the critical crack size calculation shall be in conformance with 7.2.5. 

46 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Special requirements- 8.1

Introduction

Except where it is explicitly specified that they replace requirements, these special requirements apply in addition to those specified in clauses 4 to 7 and 9 to 11. - 8.2  Pressurized hardware

8.2.1  General

a.

All  pressurized  systems  in  NSTS  and  ISS  payloads  shall  be  in conformance  with 

ISS Addendum). 

the  requirements  of  NSTS  1700.7 

(incl. 

NOTE 1  Pressurized hardware (including pressure vessels, 

pressurized  structures,  pressure  components,  and 

special  pressurized  equipment)  comply  with 

ECSS‐E‐ST‐32‐02. 

NOTE 2  For  the  attachments  of  pressurized  hardware, 

which  are  not  part  of  the  pressurized  shell,  no 

special  requirements  are  specified  in  8.2.  They 

follow  the  normal  rules  of  this  standard  (e.g.  be 

verified  safe 

to  prevent 

catastrophic or critical hazards. 

fail  safe) 

life  or 

8.2.2

Pressure vessels

8.2.2.1  Overview

Pressure vessels are classified as fracture critical, in conformance with 6.2.2. Pressure  vessels  are  subject  to  the  implementation  of  fracture  critical  item tracking, control and documentation procedures, in conformance with 10.6. 8.2.2.2  Requirements

a.

In addition to the maximum design pressure (MDP), as defined in clause 3.1  of  this  standard,  all  external  loads  shall  be  included  in  the  fracture control verification. 

47 ![Im0](images/Im0)

![Im0](images/Im0)

NOTE 

Example  of 

acceleration loads. 

external 

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 loads  are  vehicle 

b.

c.

d.

Fracture mechanics verification of metallic pressure vessels and metallic liners of COPV shall, when required in conformance with ECSS‐E‐ST‐32‐02, be performed in conformance with Figure 8‐1 and clauses 6.3.2 and 7. The verification of 8.2.2.2b, shall demonstrate safe life against hazardous leakage and burst. 

For  non‐hazardous  leak  before  burst  (NHLBB)  vessels,  all  areas  which cannot be verified LBB, shall be verified as safe life. 

NOTE 

For  example,  at  load  introduction  (e.g.  boss 

area)  and  in  other  thick‐walled  regions,  when 

agreed with the customer. 

48 ![Im0](images/Im0)

- *  Incl. min. two flights for Shuttle-mission

Legend

payloads (see 6.3.3.h.1)

- >  greater than

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Pressure vessel

Redesign

Fracture–critical item

Yes

Is the item

non-hazardous leak

before burst?

No

Proof

Is crack detection

to be performed by

proof test or other

NDI?

Other NDI

Compute analytical life

according to clause 7 using the

initial crack size to be screened

by proof test

Yes

Is vessel life

before leak or burst

> four times service

life?

Fracture-critical item

Yes

Fracture limited-life

item

Yes

Is acceptance of

this FLLI acceptable by

system programmatics?

Yes

Compute analytical life

according to clause 7 using

initial crack size conform

standard NDI

No

Is improved inspection

possible?

No

Yes

Compute analytical life

according to clause 7 using

initial crack size

conform improved inspection

Is vessel life

before leak or burst

> four times

service life?

No

Is vessel life

before leak or burst

> four times reduced*

service life?

No

- Figure 8‐1: Procedure for metallic pressure vessel and metallic liner evaluation 

No

49 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Pressurized structures

8.2.3

8.2.3.1  General

a.

A pressurized structure shall be classified as a fracture critical item, when any of the following applies: 

1.

2.

It is the pressure shell of a manned module. 

It  contains  stored  energy  of  19310 joules  (14240 foot‐pounds)  or more,  the  amount  being  based  on  the  adiabatic  expansion  of  a perfect gas. 

It contains a gas or liquid which creates a hazard if released. 

It is subjected to a maximum design pressure (MDP) greater than 0,69 MPa (100 psi). 

3.

4.

b.

c.

d.

e.

Pressurized  structures  shall  be  in  conformance  with  ECSS‐E‐ST‐32‐02, clause 4.4. 

Pressurized  structures  conforming  to  ECSS‐E‐ST‐32‐02  which  have composite  overwrap  or  are  fully  made  of  composite  shall  not  be implemented for STS or ISS missions without approval of the customer. NOTE 

such 

For 

see 

clauses 4.4.2, 4.4.3 and 4.4.4 of ECSS‐E‐ST‐32‐02. 

pressurized 

structures, 

Fracture  mechanics  verification  of  metallic  pressurized  structures  and metallic  liners  of  overwrapped  pressurized  structures  shall,  when required  in  conformance  with  8.2.3.1b,  be  performed  in  conformance with clauses 6.3.2 and 7 of this Standard. 

The verification of 8.2.3.1d, shall demonstrate safe life against hazardous leakage and burst. 

8.2.3.2  Manned pressurized structures

a.

The  design  of  manned  pressurized  structures  shall  be  in  conformance with the LBB criterion, in conformance with ECSS‐E‐ST‐32‐02, clause on “Failure mode demonstration”. 

The design shall be safe life to leakage. 

8.2.4

a.

b.

b.

c.

d.

Pressure components

For  pressure  components,  the  complete  pressure  system  shall  be  proof tested  and  leak  checked  in  addition  to  an  acceptance  proof  test  of  the individual items. 

Safe life analysis may be omitted if the item is proof tested to a level of 1,5  or  more  times  the  design  limit  load,  including  MDP  and  vehicle accelerations. 

All  fusion  joints  shall  be  100 %  inspected  by  means  of  a  qualified  NDI method. 

Concurrence of the customer shall be obtained where 100 % NDI is not considered practicable. 

50 ![Im0](images/Im0)

![Im0](images/Im0)

8.2.5

a.

Low risk sealed containers

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Additional  fracture  assessment  need  not  be  performed  on  sealed containers meeting the following criteria: 

1.

The container is not part of a system with a pressure source and is individually sealed. 

Leakage  of  the  contained  gas  does  not  result  in  a  catastrophic hazard and the pressure shell is verified leak before burst (LBB). The  container  or  housing  is  made  from  a  conventional  alloy  of steel, aluminium, nickel, copper or titanium. 

The MDP does not exceed 0,15 MPa. 

The  free  volume  within  the  container  does  not  exceed  0,051 m3 (1,8 cubic  feet)  at  0,15 MPa  (22 psi)  or  0,076 m3  (2,7 cubic  feet)  at 0,10 MPa  (15 psi),  or  any  pressure‐volume  combination  not exceeding  a  stored  energy  potential  of  19310 joules  (14240 foot‐pounds). 

2.

3.

4.

5.

b.

c.

For sealed containers with a MDP higher than 0,15 MPa (22 psi), but less than 0,69 MPa (15 psi), and a potential energy not exceeding 19310 joules (14240 foot‐pounds)  meeting  criteria  8.2.5a.1,  8.2.5a.2  and  8.2.5a.3, additional  fracture  assessment  need  not  be  performed  if  the  following apply: 

1.

the  minimum  factor  of  safety  is  2,5 × MDP  (verified  by  stress analysis or test), or 

the container is proof‐tested to a minimum of 1,5 × MDP 

2.

All  sealed  containers  shall  be  capable  of  sustaining  0,10 MPa  (15 psi) pressure difference with a minimum safety factor of 1,5. 

Hazardous fluid containers

8.2.6

a.

Subject  to  approval  of  the  customer,  hazardous  fluid  containers  shall comply with the following: 

1.

Have a stored energy of less than 19310 Joules (14240 foot‐pounds) with an internal pressure of less than 0,69 MPa (100 psi). 

Have a minimum safety factor of 2,5 times MDP.  

Be  in  conformance  with  the  fracture  control  requirements  for pressure components specified in clause 8.2.4. 

2.

3.

4.  When  agreed  with  the  customer  not  to  use  a  proof  test  to  a minimum factor of 1,5, safe‐life can be assured by NDI application and crack growth analysis. 

Integrity against leakage is verified by test at a minimum pressure of 1,0 times MDP. 

5.

b.

If provision 8.2.6a is not met, hazardous fluid containers shall: 

1.

2.

Have safe‐life against rupture and leakage. 

Be  treated  and  certified  the  same  as  pressure  vessels  when  the contained fluid has a delta pressure greater than one atmosphere. 51 ![Im0](images/Im0)

- 8.3  Welds

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Nomenclature

The standardised nomenclature for the different types of welds and their characteristics,  including  imperfections,  as  presented  in  ISO 17659  and EN ISO 6520‐1 shall be used. 

8.3.1

a.

8.3.2

a.

Safe life analysis of welds

For  welds,  the  fracture  mechanics analysis  shall  be  performed  with  the aid  of  the  material  properties  of  the  weldments,  including  weldment repairs. 

b.  When  the  material  properties  specified  in  8.3.2a  are  not  available,  they 2.

3.

shall be derived by means of a test programme covering: 

1.

Ultimate  and  yield  strength  for  all  welding  conditions  used, including  mechanical  properties  (as  in  8.3.2a)  in  the  presence  of different  misalignments,  angles  between  joints  or  typical  defects, and their consequences. 

Fracture  toughness  KC,  stress‐corrosion  cracking  threshold  KISCC, and crack propagation parameters for each type of thickness. 

Young’s modulus for weld material: 

(a)

Evaluated  by  test  only  in  those  cases,  where  a  significant amount  of  a  second  phase  with  a  different  modulus compared to the base material appears.  

If  the  microstructure  with  respect  to  the  different  phases does not change, the base material Young’s modulus applies also for weld material. 

(b)

c.

d.

e.

f.

The test programme specified in 8.3.2b shall be performed on a number of specimens agreed with the customer, but not less than 5, in order to permit a statistical evaluation of final values. 

The 

fracture  mechanics  assessment  shall  be  performed  under consideration of any potential weld geometrical imperfection as follows: 1.

In a first step, a screening of the applied weld process and material is  performed 

identify  all  potential  weld  geometrical imperfections. 

to 

NOTE 

See EN ISO 6520‐1 

2.

Acceptance limits for the identified geometrical imperfections are determined and included in the fracture mechanics analysis. 

Any  residual  stresses,  both  in  the  weld  and  in  the  heat‐affected  zone, shall be used in the safe life analysis. 

Except  in  the  case  specified  in  8.3.2g,  even  though  inspected  for embedded  flaws  and  pores,  the  initial  crack  geometry  for  the  analysis 52 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 g.

shall always be assumed to be a surface part‐through‐crack or through‐crack, as specified in clause 10. 

Embedded crack cases shall not be used in cases other than those where NDI  methods  are  used  which  enable  the  determination  of  the  relative distance of the embedded flaw to the surface.  

NOTE 

For example, embedded cracks (see Figure 10‐1 

geometry  6)  can  be  used  when  ultrasonic 

inspection is applied. 

- 8.4  Composite, bonded and sandwich structures

8.4.1  General

a.

PFCI  made  of  fibre‐reinforced  composite,  including  bonded  joints, sandwiches and  potted  inserts,  which are  classified  safe life  and  which are  not  low‐risk fracture  items  in  conformance  with  8.4.4.3,  shall  be treated as fracture critical items. 

All  PFCI  falling  into  the  category  fibre‐reinforced  composites,  bonded and sandwich structures shall comply with clauses 8.4.2 to 8.4.4. 

b.

c.

NOTE 

includes  adhesive  bonds 

This 

structures. 

in  metallic 

Composite  overwraps  of  COPV  and  other  composite  overwrapped pressurized hardware shall be in conformance with clause 8.2 and ECSS‐E‐ST‐32‐02, as minimum. 

NOTE 1  This means that these composite PFCI do not need 

the  detailed 

compliant  with 

to  be 

requirements of this clause 8.4. 

fully 

NOTE 2  For  the  attachments  of  pressurized  hardware, 

which  are  not  part  of  the  pressurized  shell,  no 

special requirements are specified in 8.2 and ECSS‐

E‐ST‐32‐02.  Composite,  bonded  and  sandwich 

attachment  hardware  follows  the  rules  of  this 

clause  8.4  to  prevent  catastrophic  or  critical 

hazards. 

8.4.2

Defect assessment

8.4.2.1  Manufacturing defects

a.

A  list  of  potential  manufacturing  defects,  including  their  maximum acceptable  size  (or  ratio  for  porosity),  shall  be  established,  covering  all applied manufacturing processes.  

NOTE 

the  manufacturing  process, 

For  example,  the  following  defects,  depending 

on 

can  be 

considered: 

•  High porosity ratio 

53 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 •  Delamination 

•  Fibre misalignment 

•  Cut or broken fibres 

•

Joint debonding. 

b.

The  maximum  acceptable  defect  size  (or  ratio)  considered  in  the verification shall be detectable by the applied NDI, in conformance with 10.3 and 10.5. 

NOTE   With  approval  of  the  customer,  acceptable 

defect  size  (or  ratio)  consistent  with  the 

manufacturing  process 

(including  process 

control)  are  sometimes  used  in  the  fracture 

control  verification  for  certain  manufacturing 

defect types, instead of defects based on NDI. 

c.

d.

The  effects  of  the  potential  manufacturing  defects  on  the  structural integrity shall be established, documented and verified. 

NOTE 

Examples of such effects are strength, stability, 

and fatigue. 

Acceptance criteria based on a fracture control methodology, as defined in this clause 8.4, shall be established for those manufacturing defects for which the effect is not already included in material properties used for structural design and qualification. 

NOTE 

For example, in conformance with 8.4.2.1c and 

8.4.2.1d  porosity  can  be  excluded 

from 

verification  by  means  of  a  fracture  control 

methodology,  if  the  detectable  ratio  by  means 

of NDI is fully represented in the derivation of 

strength and fatigue allowables. 

8.4.2.2  Mechanical damage

a.  Mechanical damage shall be considered in conformance with the damage threat assessment as specified in clause 8.4.3  

NOTE 

For example, the following mechanical damage 

due  to  events  which  can  occur  during  the 

service life, can be considered: 

•

Impact 

•  Scratch 

•  Abrasion. 

8.4.2.3  Defect assessment procedures

a.

The  following  types  of  defects  shall  be  included  in  the  safe  life verification in conformance with 8.4.4.2: 

1.  Mechanical damage at the maximum expected level, as specified in clause 8.4.4.2 and 8.4.3. 

54 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 2.  Manufacturing  defects  at  the  maximum  size  (or  ratio) in conformance  with  applied  inspection  methods  as  specified  in clause 8.4.2.1. 

Detected defects in conformance with clause 10.7. 

3.

For  fail  safe  verification  in  conformance  with  8.4.4.1,  detected  defects shall be included in conformance with clause 10.7. 

Low‐risk fracture verification in conformance with 8.4.4.3 shall consider the damage associated with the visual damage threshold (VDT) or larger. b.

c.

NOTE 

For  detected  defects  in  low‐risk fracture  items, 

see clause 10.7. 

8.4.3

Damage threat assessment

Introduction

8.4.3.1

The objectives of the damage threat assessment are to: 

•  Determine  the  upper  level  of  mechanical  damage  which  is  taken  into account in the safe life verification. 

•  Ensure that the verification of fail‐safe and low‐risk fracture items is based on  valid  assumptions,  i.e.:  to  consider  only  detected  defects  for  fail  safe items, and VDT for low‐risk fracture items. 

The damage threat assessment takes into account damage protection, inspection and indication performed throughout the service life of the item. 

The damage threat assessment is also applied to those safe life items screened for  manufacturing  defects  by  proof  testing,  in  conformance  with  8.4.4.2g,  to ensure that no detrimental damage occurs after proof testing. 

8.4.3.2

Identification of potentially damaging events andresulting mechanical damage

a.

The  events  that  can  cause  mechanical  damage  during  the  service  life, shall  be  identified  and  documented  in  the  fracture  control  analysis report. 

NOTE 1  The service life includes the following phases: 

•  Handling, 

•  Test, 

•  Transportation, 

•

In‐service use,  

•  Maintenance,  

•  The  manufacturing  phase,  which  are  not 

covered by NDI. 

NOTE 2  The following are examples of credible events: 

•  Tool drop 

•  Bumping or falling during handling 

55 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 b.

c.

d.

•  Scratch during assembly. 

For  the  events  identified  in  8.4.3.2a  the  type  and  maximum  credible magnitude  of  the  associated  threats  to  the  integrity  of  the  hardware during those events shall be identified. 

NOTE 

For example, the magnitude of the threat can be 

described  by  the  energy  at  impact,  the  shape, 

material  and  orientation  of  the  impactor  and 

the worst impact location. 

The  assessment  shall  include  the  potential  consequences  of  impact  of items considered as low mass or low momentum (in conformance with 6.1),  or  due  to  items  considered  as  contained  or  restrained  (in conformance with 6.3.4), in case they are released. 

For  the  type  and  maximum  magnitude  of  the  threat  during  each  event that can cause mechanical damage, as identified in 8.4.3.2a, 8.4.3.2b and 8.4.3.2c, the resulting mechanical damage shall be identified with its type and size or level. 

NOTE 1  Types of damage are for example: impact damage 

fibres  and 

(including  delamination,  broken 

perforation), scratch, and abrasion. 

NOTE 2  Damage  size  or  level  can  be  characterised,  for 

example, by energy level for impact, or depth and 

length for a scratch. 

8.4.3.3  Mechanical damage protection

a.

In  the  case  where  protective  devices  are  used  to  reduce  the  effects  of events, to avoid some events, or to protect the structure, the effectiveness of the devices shall be demonstrated by test. 

8.4.3.4  Mechanical damage inspection and indicators

a.

Close  visual  inspection  shall  be  performed  for  each  PFCI  and  FCI,  just before each launch or just before closeout of surrounding structure after which mechanical damage is no longer credible, as determined in 8.4.3.2. NDI shall meet the requirements of clause 10.3. 

In  case  mechanical  damage  indicators  are  applied  to  provide  positive evidence  of  a  mechanical  damage  event,  their  effectiveness  shall  be demonstrated by test. 

b.

c.

8.4.4

Compliance procedures

8.4.4.1

a.

b.

Fail safe items

A fail safe item shall meet all the requirements for the fail safe approach described in clauses 6.2, 6.3, and 10.7. 

For a fail safe item it shall be demonstrated by test or analysis supported by  test  that  there  is  no  unacceptable  degradation  (in  conformance  with 56 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 8.4.4.1a) of the alternative load path, due to cyclic loads or environmental effects. 

NOTE   No  damage  needs  to  be  considered  for  the 

alternative  load  path,  unless  detected  defects 

exist (see clause 8.4.2.3). 

c.

A  fail safe  item  shall  be  inspected  at  least  by  close  visual  inspection covering hundred per cent of the item before each flight, in addition to NDI during manufacturing. 

Safe life items

8.4.4.2

a.

A safe life item shall meet all the requirements for the safe life approach described in clauses 6.2, 6.3, and 10.7. 

See also Figure 6‐3. 

NOTE 

b.

c.

d.

e.

f.

g.

For a safe life item the requirements of 8.4.4.2a shall be satisfied by full‐scale  or  sub‐scale  tests  complemented  by  coupon  testing,  or  analysis supported by tests representative of structural details. 

For a safe life item the tests of 8.4.4.2b shall be performed in the presence of 

(in conformance with 8.4.2.1) and mechanical damage as defined in 8.4.4.2d, as specified in 8.4.2.3. 

induced  defects  representative  of  manufacturing  defects 

NOTE 

The  use  of  interlaminar  fracture  mechanics 

analysis is submitted to customer approval and 

includes  the  successful  demonstration  of  the 

methodology  by  test  on  sub‐component  or 

component (structure) level. 

The most severe of the following mechanical damage shall be considered for verification of safe life items: 

1.

The  maximum  size  or  level  that  can  be  induced,  in  conformance with  8.4.3.2  and  8.4.3.3,  and  remain  undetected,  in  conformance with 8.4.3.4. 

2.  Mechanical damage resulting from impact energy associated with the visual damage threshold. 

For a safe life item the test articles and tests of the test program of 8.4.4.2b shall be representative of manufacturing process, environment and loading type (considering local load introduction where applicable) demonstrating ultimate load capability and no growth of defects at the end of one time the service life with a load enhancement factor (LEF) of 1,15. 

NOTE 

Test  articles  can  be 

flight  representative 

structural  elements,  (sub)components  or  full‐

scale parts. 

For  a  safe life  item  the  test  programme  (including  applied  LEF  and fatigue spectrum) shall be approved by the customer;  

For a safe life item, a proof test for manufacturing defect screening may be applied when: 

57 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 It is subjected to customer approval. 

A proof test factor of at least 1,2 is applied to the limit loads. 

NOTE 1  The  effect  of  material  degradation  due 

to 

environmental  exposure  is  treated  on  a  case  by 

case basis. It can result in a higher proof test factor, 

which is agreed with the customer. 

NOTE 2  A  large  number  of  complicated load  cases  can  be 

necessary  to  ensure  that  all  locations  of  the 

structure 

for 

manufacturing  defects  during  the  proof  testing. 

Simplification of the proof load cases can result in 

higher test loads, overdesign of the flight structure 

and increased risk of failure during the test. 

adequately 

screened 

are 

For  multi‐mission  hardware,  the  proof  test  is  repeated  between flights. 

The  applied  proof  loads  do  not  exceed  80 %  of  the  ultimate strength. 

Post test NDI is applied for all proof tested composite, bonded and sandwich parts. 

1.

2.

3.

4.

5.

NOTE 

Special  problems  can  arise  in  certain  instances 

such  as  a  region  of  high  load  transfer  where 

compliance with the proof test requirements for 

the 

local 

yielding  of  the  metal  component.  These  are 

treated on a case by case basis. 

introduces 

composite 

structure 

Low-risk fracture items

8.4.4.3

a.

A  low‐risk fracture  item  shall  not  be  a  pressure  vessel,  high  energy rotating  machinery,  habitable  module  or  otherwise  fracture  critical pressurized structure, and not contain a hazardous fluid. 

For a low‐risk fracture item, the result of the damage threat assessment shall be that, as a result of damage inspection and protection, no damage larger than the visual damage threshold is expected. 

A low‐risk fracture item shall be inspected, as a minimum, by close visual inspection  covering  hundred  per  cent  of  the  item  before  each  flight,  in addition to NDI during manufacturing. 

A low‐risk fracture item shall not include a single point failure bonded area. 

For a low‐risk fracture item the strain at the limit load shall be below the damage tolerance threshold strain.  

b.

c.

d.

e.

f.  With  approval  of  the  customer,  it  may  be  considered  that  the  strain  is below  the  damage  tolerance  threshold  strain  without  specific  testing, when: 

58 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 1.

2.

At the limit load the maximum tensile stresses, taken into account the stress concentration factor, is lower than 40 % of the material ultimate capability. 

At  the  limit  load  the  maximum  compressive  stresses,  taken  into account  the  stress  concentration  factor,  is  lower  than  25 %  of  the material ultimate capability. 

- 8.5  Non-metallic items other than composite, bonded,

sandwich and glass items

a.

b.

c.

d.

e.

f.

Potential fracture critical items made of non‐metallic material, other than those covered by clause 8.4 (composite, bonded and sandwich items) and clause 8.7 (glass), which are safe life, shall be treated as fracture critical items. 

NOTE 

For example, ceramic, C/SiC, C/C. 

Fracture control implementation for PFCI made of non‐metallic material shall be subject to customer approval. 

An  item  shall  not  be  accepted  as  a  fail  safe  item  unless  it  meets  the following two conditions: 

1.

It meets all the requirements for the fail safe approach described in clauses 6.2 and 6.3. 

It  has  been  demonstrated  that,  for  the 

is  no unacceptable degradation of the alternative load path, due to cyclic loads or environmental effects. 

item,  there 

2.

An  item  shall  not  be  accepted  as  a  safe  life  item  unless  it  meets  the following two conditions: 

1.

It  has  been  demonstrated  by  fatigue  analysis  (accounting  for  the effects  of  cyclic  and  sustained  loading)  supported  by  tests  that, during  a  time  period  of  four  times  the  service  life,  there  is  no unacceptable  degradation  due  to  cyclic  loads  or  environmental effects in the presence of induced defects, compatible with applied NDI techniques, using representative coupons. 

NOTE 

Results  of  representative  earlier  tests  can  be 

used  to  support  the  analysis,  when  approved 

by the customer 

2.

It undergoes a proof‐test of all flight hardware to not less than one and two tenth (1,2) times the limit load. 

In those cases where problems arise to fulfil the proof test requirement, these shall be treated on a case by case basis. 

NOTE 

compliance  with 

For  example,  the  region  of  high  load  transfer 

where 

test 

requirements  for  the  non‐metallic  structure 

introduces yielding of the metal component. 

the  proof 

Test  loads  on  the  non‐metallic  item  shall  not  exceed  80%  percent  of ultimate strength. 

59 ![Im0](images/Im0)

![Im0](images/Im0)

- 8.6  Rotating machinery

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 a.

b.

Rotating  machinery  shall  be  proof  (spin)  tested  and  subjected  to  NDI before and after proof testing.  

The  proof  test  factor  shall  be  derived  by  means  of  fracture  mechanics analysis, but not be less than 1,1.  

NOTE 

Rotating  hardware  not  considered  as  rotating 

machinery in conformance with 3.2.35 is treated 

as any structural item. 

- 8.7  Glass components

a.

b.

c.

d.

e.

f.

g.

The verification of all potential fracture critical glass components, except those verified as fail‐safe or contained, shall include an analysis of crack growth  under  conditions  of  the  stresses  and  the  environments encountered during their service life. 

A  fracture  mechanics  analysis  for  potential  sustained  crack  growth (da/dt) shall be performed in conformance with clauses 7, 8.7c, 8.7d, 8.7e and 8.7f for each safe life glass item, in order to demonstrate that the item sustains  after  four  (4)  times  its  service  life  at  least  one  and  four  tenths (1,4) times the design limit load without fracture. 

The sustained crack growth analysis shall apply factors to the sustained stresses of the stress spectrum as specified in Table 8‐1, depending on the duration of each load event that induces sustained stress. 

The initial crack depth used for design and analysis of glass items shall: 1.

Not be smaller than three (3) times the detectable flaw depth based on the NDI methods used. 

Be subject to approval by the customer. 

2.

The smallest crack aspect ratio used for analytical life predictions shall be a/c = 0,1. 

Crack  growth  properties  at  100 %  moisture  shall  be  used  for  life predictions. 

Proof testing or NDI, consistent with the loading expected during service life,  shall  be  conducted  to  screen  for  manufacturing  flaws  in  each potential  fracture‐critical  glass  item  based  on  the  result  of  the  fracture mechanics analysis, with the following conditions: 

1.

Proof  testing  is  performed  for  acceptance  of  pressurized  glass components (such as windows and viewports) to screen the flaws larger than the initial crack depth, with minimum proof pressure of two (2) times the MDP. 

Proof testing is performed in an environment suitable to limit flaw growth during test. 

Humidity and encapsulated water is removed from the surface of the glass before proof testing. 

2.

3.

60 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 NOTE 

Encapsulated water can be accumulated during 

e.g. storage before proof testing 

h.

i.

If  a  factor  of  safety  on  strength  of  5  or  greater  can  be  shown,  and  if approved by the customer, the proof test in conformance with 8.7g.1 may be omitted. 

It  shall  be  demonstrated  that  glass  inside  a  habitable  area  is  safe  from breakage  by  safe  life  verification  in  conformance  with  8.7b,  or  is contained, or that released particles are smaller than 50 µm. 

Table 8‐1: Factor on stress for sustained crack growth analysis of ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Duration of sustained stress event </td>
		<td>Factor on stress </td>
	</tr>
	<tr align="center">
		<td>life ≤ 1 week </td>
		<td>1,4 </td>
	</tr>
	<tr align="center">
		<td>1 week < life ≤ 1 month </td>
		<td>1,3 </td>
	</tr>
	<tr align="center">
		<td>1 month < life ≤ 1 year </td>
		<td>1,2 </td>
	</tr>
	<tr align="center">
		<td>life > 1 year </td>
		<td>1,1 </td>
	</tr>
	<tr align="center">
		<td colspan=2>NOTE  The factor on stress is larger for shorter design life because of the flaw  growth velocity sensitivity to small variations in the stress intensity </td>
	</tr>
</table>

 

- 8.8  Fasteners

a.

b.

c.

Fasteners  smaller  than  diameter  5 mm  (or  3/16”)  shall  not  be  used  in safe life applications. 

Titanium alloy fasteners shall not be used in safe life applications. 

All  potential  fracture‐critical  fasteners  shall  be  procured  and  tested  in conformance  with  aerospace  standards  for  structural  fasteners  or equivalent specifications agreed with the customer. 

NOTE 

For  example,  LN,  AIR  and  NAS  standards,  or 

ISO,  EN  and  national  standards  which  are 

explicitly intended for aerospace applications. 

d.

Fasteners procured and tested in conformance with aerospace standards for non‐structural fasteners shall not be used. 

NOTE 

those 

secondary 

connections  where 

For 

significant redundancy exists and fatigue is not 

a major concern, sometimes such non‐structural 

fasteners  are  applied.  This  is  agreed  with  the 

customer on a case by case basis. 

e.

f.

All  safe life  fasteners  shall  be  marked  and  stored  separately  following NDI or proof testing. 

Safe life fasteners shall be NDI‐inspected by the eddy current method in the shank, head fillet, and thread areas. 

61 ![Im0](images/Im0)

g.

h.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 The standard crack size to be considered in the thread and fillet area for the  safe life 

in  8.8f,  shall  be a = c = 1,91 mm. 

NOTE 

inspected  as  required 

fasteners, 

This  assumes  rolled  thread  and  fillet, 

conformance with 8.8c. 

in 

Application of rivets shall conform to the requirements for fail‐safe items of clause 6.3.2. 

NOTE 

Rivets  are  permanently  deformed  during  their 

installation, and therefore cannot be adequately 

inspected for cracks in the installed condition. 

62 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Material selectiona.  Materials shall be selected and controlled in conformance with ECSS‐Q‐ST‐70 “Materials, mechanical parts and processes”. 

NOTE 

structural 

and 

takes 

into 

The  material  selection  process 

account 

non‐structural 

requirements.  The  materials  selected  possess 

toughness,  crack‐

the  appropriate 

growth 

and 

structural 

properties, such as Young’s modulus and yield 

strength, in specified environmental conditions. 

fracture 

characteristics, 

b.  Where  validated  properties  for  analysis  are  not  available,  or  available properties are not validated by standard or other test procedures agreed with the customer, the statistical basis for average and minimum values shall be established by tests. 

For applications where failure of a material can result in catastrophic or critical  hazard,  alloys  which  possess  high  resistance  to  stress‐corrosion cracking  in  conformance  with  Table  5‐1  (Alloys  with  high  resistance  to stress‐corrosion cracking) of ECSS‐Q‐ST‐70‐36 shall be used. 

c.

NOTE 

Strength,  fracture  and  fatigue  properties  for  a 

large  number  of  aerospace  materials  are 

documented  in  the  ESA  developed  materials 

database  “FRAMES‐2”,  which  can  be  obtained 

from Mechanical Systems Department, ESA. 

Further examples of frequently used sources for 

material  data  are 

the  Metallic  Materials 

(DOT/FAA/AR‐MMPDS) 

Handbook 

and 

Aerospace 

Structural  Metals  Handbook 

(CINDAS/ Purdue) 

63 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Quality assurance and Inspection- 10.1  Overview

For quality assurance requirements see ECSS‐Q‐ST‐20 “Quality assurance”. For materials  selection  and  quality  control  requirements  see  ECSS‐Q‐ST‐70 “Materials, mechanical parts and processes”. 

- 10.2  Nonconformances

a.

b.

For dispositioning of nonconformances for PFCIs, a reassessment of these items to verify conformance with the fracture control requirements shall be performed. 

NOTE 

For  nonconformances  control  see  ECSS‐Q‐ST‐

10‐09. 

All  nonconformances  which  affect  fracture‐critical  items  and  primary structural hardware designed to safe life principles shall be dispositioned as “major nonconformances”. 

- 10.3  Inspection of PFCI

10.3.1  General

a.

All PFCI shall be subject to an inspection programme, in order to validate the analytical life predictions and to permit hardware to be released as acceptable. 

NDI shall be performed for the complete items. 

b.

c.

d.

e.

NOTE 

The NDI to be applied to an item (or region of 

an item) is based on the most critical location of 

the item (or region of the item). 

Detected defects shall be treated as specified in clause 10.7. 

Inspections shall be implemented for limited life items, as needed. 

Rolled threads shall not be etched. 

NOTE 

This refers to both  the inspection for cracks of 

safe 

(where  eddy  current 

fasteners 

life 

64 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 inspection  is  preferred  in  conformance  with 

8.8f),  and  penetrant 

inspection  of  other 

fasteners which is sometimes performed as part 

of process control. 

f.

g.

h.

i.

j.

k.

l.

Verification  of  structural  redundancy  for  fail‐safe  items  shall  be performed before each flight. 

Post  test  NDI  shall  be  performed  for  all  proof‐tested  items  (where  the proof test is not the NDI method). 

NOTE   With  approval  of  the  customer,  the  post  test 

NDI  can 

increased 

probability  of  defects,  e.g.  focusing  on  welds, 

castings, forgings, bonds, and composite parts.  

focus  on  areas  with 

Inspection of all welds shall include a search for surface flaws as well as embedded flaws. 

100 %  inspection  of  all  fusion  joints  of  pressurized  lines  shall  be performed before and after proof test, using a qualified NDI method. NOTE   After  proof  testing  the  NDI  can  be  limited  to 

100% surface flaw inspection, and re‐inspection 

of areas with detected pores/porosity. 

NDI  requirements  shall  be  stated  on  design  and  manufacturing documentation. 

Inspection  shall  be  performed  by  qualified  personnel,  certified  for  the relevant inspection method, in conformance with NAS 410, or EN 4179 or equivalent standard agreed with the customer. 

The applied NDI procedures and the justification of their crack detection capability shall be approved by the customer. 

NOTE 

This applies to all NDI procedures applied for 

implementation  of  fracture  control,  including 

standard NDI procedures. See also 10.4.2.1c. 

m.  Dedicated jigs, fixtures and equipment needed to perform re‐inspection after delivery shall be delivered with fracture‐critical items. 

Inspection of raw material

10.3.2

a.

b.

Raw materials for all safe life, fail‐safe and low‐risk fracture items shall be  inspected  to  ensure  conformance  with  the  general  material  quality specification and absence of unacceptable embedded flaws. 

For  metallic  items,  the  raw  material  inspection  shall  be  performed  in conformance with AMS‐STD‐2154, Class A as a minimum. 

NOTE   Alternative  equivalent  inspection  methods  are 

subject to customer approval. 

![Im0](images/Im0)

<table align="center">
</table>

65 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 d.

e.

f.

The hardware developer of composite, bonded and sandwich items shall enforce  a  rigorous  programme  to  control  contamination  and  foreign object debris (FOD) during processing. 

Glass  items  shall  be  inspected  and  proof  tested  in  conformance  with clause 8.7. 

Other  non‐metallic  items  shall  be  inspected  and  proof  tested  in conformance with clause 8.5. 

10.3.3

a.

Inspection of safe life finished items

Inspection of all finished safe life items by the NDI method relevant to the assumed initial flaw size shall be performed. 

b.  Metallic safe life items shall be inspected in conformance with clause 10.4. c.

Items  to  be  inspected  using  penetrant,  shall  have  their  mechanically disturbed surfaces etched prior to inspection. 

NOTE 

 See also clause 10.4.3.2 for the case of standard 

penetrant NDI. 

d.  Where  etching  or  inspection  cannot  be  performed  on  the  finished  part, that  etching  and  penetrant‐inspection  shall  be  performed  at  the  latest practical stage of finishing. 

e.

f.

g.

h.

NOTE 

For  example,  before  final  machining  of  parts 

with  precision  tolerances,  or  at  the  assembly 

level before holes are drilled. 

Composite, bonded and sandwich safe life items shall be inspected and proof tested in conformance with clause 10.5. 

Safe  life  items  made  of  glass  shall  be  inspected  and  proof  tested  in conformance with clause 8.7. 

Safe  life  items  made  of  other  non‐metallic  materials  shall  be  inspected and proof tested in conformance with clause 8.5. 

For transparent optical elements, a standard initial crack size of 2,54 mm length  shall  be  used  when  visual  inspection  with  10  times  or  higher magnification  is  performed  with  lighting  applied  at  right  angles  to  the actual flaw orientation. 

NOTE 1  Example  of  such  transparent  optical  elements  are 

windows and lenses. 

NOTE 2  This visual inspection method detects both surface 

and embedded flaws. 

i.

Except for glass items, visual inspection shall not be the only NDI. 

66 ![Im0](images/Im0)

![Im0](images/Im0)

- 10.4  Non-destructive inspection of metallic materials

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 10.4.1  General

a.

b.

Non‐destructive inspection (NDI) levels shall be categorized as standard NDI, special NDI or proof testing NDI. 

The responsible for planning, definition and supervision of special NDI activities shall have a qualification level 3 in conformance with NAS 410 or EN 4179. 

10.4.2  NDI categories versus initial crack size

10.4.2.1  Standard NDI

a.

The initial crack sizes and geometries as defined in Table 10‐1 shall apply for standard NDI of metallic materials. 

NOTE 

Initial  crack  geometries  are  shown  in  Figure 

10‐1, Figure 10‐2 and Figure 10‐3. 

b.

For  the  standard  NDI  level  of  inspection  one  or  more  of  the  following standard industrial NDI techniques applied to metallic materials shall be used:  

⎯

⎯

⎯

Fluorescent penetrant 

X‐ray 

<table align="center">
</table>

c.

Implementation  of  standard  NDI  on  metallic  parts  based  on  the  crack sizes of Table 10‐1 may be performed without a formal demonstration of the crack detection capability specified in 10.4.2.1d. 

NOTE 

The  crack  size  data  in  Table  10‐1  are  based 

principally on NDI capability studies that were 

conducted  on  flat,  fatigue  cracked  panels. 

When  the  component’s  geometrical  features, 

such  as  sharp  radii,  fillets,  recesses,  surface 

finish  and  cleanliness,  material  selection, 

reduced  accessibility  and  other  conditions  can 

influence the detection capability of the applied 

standard NDI method, the method is evaluated 

based on similarity with proven applications or 

demonstration  testing  on  a  small  number  of 

samples 

the  minimum 

detectable crack size. This is done to ensure that 

the detection capability of the applied standard 

NDI inspection is not influenced. 

representative  of 

d.

Standard NDI shall be performed in conformance with MIL‐HDBK‐6870. 67 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 e.

f.

Standard  NDI  shall  provide  crack  detection  to  at  least  95 %  confidence and 90 % probability level. 

NOTE 

Table  10‐1  gives,  for  various  NDI  techniques 

and part geometries, the largest crack sizes that 

can remain undetected at these probability and 

confidence levels.  

Radiographic NDI standard flaw sizes (that are only applicable for flaw orientation in the X‐radiation plane) shall not apply to very tight flaws. NOTE 

For example, tight flaws are: forging flaws, heat 

treatment 

induced 

cracks,  fatigue  cracks,  flaws  in  compressive 

stress field. 

induced  flaws,  welding 

g.

For  tight  flaws  referred  to  in  10.4.2.1f,  special  NDI  requirements  shall apply as defined in 10.4.2.2. 

10.4.2.2  Special NDI

a.

Special  NDI  shall  be  used  only  in  special  cases  where  limited  life  is demonstrated  for  standard  initial  crack  sizes  and  serious  problems  can occur  as  a  result  of  redesign  or  acceptance  of  the  limited  life,  and  its application is subject to approval by the customer. 

A  statistical  demonstration  of  90 %  probability  of  detection  with  95 % confidence shall be performed for the special NDI method.  

NOTE 

The  demonstration  is  specific  to  the  relevant 

procedure, part and individual inspector. 

The  demonstration  specified  in  10.4.2.2b  shall  be  carried  out  on specimens representative of the actual configuration to be inspected. 

For  NDI  processes  which  are 

the  statistical demonstration  of  10.4.2.2b  may  be  replaced  by  verification  by  test  of process parameters and their tolerances which can affect the sensitivity. fully  automated, 

NOTE 

For example, automated eddy current scanning. 

In the verification by test specified in 10.4.2.2d, a minimum of 5 samples shall be used, which cover the full range of parameters of the cracks to be detected  by  the  automated  process,  in  combination  with  the  structural details to be inspected. 

b.

c.

d.

e.

10.4.2.3  Crack Screening Proof Test

a.  Where  proof  testing  of  a  flight  item  is  performed  as  a  screening  or inspection  technique  for  cracks,  which  are  larger  than  the  initial  cracks used  in  the  analytical  life  prediction,  in  the  proof  tests  performed, procedures and stress analysis predictions shall ensure that the predicted stress level and distribution are actually achieved, and that the absence of test failure ensures that the cracks of the sizes to be screened out are not present in any critical location or in any orientation of the item. 

b.  Where  proof  testing  of  a  flight  item  is  performed  as  a  screening  or inspection  technique  for  cracks,  which  are  larger  than  the  initial  cracks 68 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 used in the analytical life prediction, cracks screened by proof test shall have aspect ratios identical to the initial cracks applied in the analytical life prediction. 

c.  Where  proof  testing  of  a  flight  item  is  performed  as  a  screening  or inspection  technique  for  cracks,  which  are  larger  than  the  initial  cracks used  in  the  analytical  life  prediction,  the  justification  of  the  proof  test procedure shall be provided, which includes all effects that can affect the proof test definition, including as a minimum:  

1.

Potential  of  stable  crack  growth  beyond  the  crack  size  to  be screened during the proof test. 

NOTE 

This results in unacceptable degradation of the 

flight hardware. 

2.  Weld and parent material inhomogeneities if welds are present. 3.

testing  and  operations  are  at  different Environment, 

environmental conditions. 

if 

d.  Where  proof  testing  of  a  flight  item  is  performed  as  a  screening  or inspection  technique  for  cracks,  which  are  larger  than  the  initial  cracks used  in  the  analytical  life  prediction,  proof  test  procedures  shall  be submitted to the customer for approval prior to the start of testing. 

NOTE 1  Proof testing can result in the application of loads 

substantially in excess of those usually imposed on 

flight  hardware  in  order  to  screen  for  cracks  of 

sufficiently small size. This can result in significant 

risk  to  damage  and  reject  otherwise  acceptable 

hardware. 

fracture  analysis  methodology 

to  accurately  predict 

NOTE 2  Requirements  for  crack  growth  and  critical  crack 

size analysis are specified in clause 7. A significant 

amount of test data can be necessary to validate or 

complement  the  analysis  results  in  order  to  limit 

the  risk  of  damage  to  flight  hardware.  Advanced 

non‐linear 

is 

normally  applied 

the 

behaviour  of  cracks  under  proof  loading,  except 

for  e.g.  thick‐walled  items  with  part‐through 

cracks  where  the  minimum  remaining  ligament 

(material  thickness  ahead  of  crack  tip)  is  greater 

than 2,5 (K1c/  σy)2. A crack screening proof test of 

thin‐walled  items  is  generally  not  recommended 

because  of  the  increased  risk  of  damage  due  to 

stable crack growth during the proof test.  

69 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>NDI method </td>
		<td>Crack  location </td>
		<td>Part  thickness t  [mm] </td>
		<td>Crack  configuration  number  (see NOTE 1) </td>
		<td></td>
		<td>Crack  length  c  [mm] </td>
	</tr>
	<tr align="center">
		<td rowspan=3>Eddy current  NDI </td>
		<td>Open  surface </td>
		<td>t ≤ 1,27  t > 1,27 </td>
		<td>4  1, 3, 8 </td>
		<td>through   surface </td>
		<td>1,27  2,54  1,27 </td>
	</tr>
	<tr align="center">
		<td>Edge or hole </td>
		<td>t ≤ 1,91  t > 1,91 </td>
		<td>5, 9  2, 7 </td>
		<td>through   corner </td>
		<td>2,54  1,91 </td>
	</tr>
	<tr align="center">
		<td>Cylinder </td>
		<td>N/A </td>
		<td>10 </td>
		<td>surface </td>
		<td>1,27 </td>
	</tr>
	<tr align="center">
		<td rowspan=3>Penetrant NDI  Sensitivity  Level ≥3 </td>
		<td>Open  surface </td>
		<td>t ≤ 1,27  1,27 ≤ t ≤1,91 t > 1,91 </td>
		<td>4  4  1, 3, 8 </td>
		<td>through  through  surface </td>
		<td>2,54  3,82 ‐ t  4,05  1,91 </td>
	</tr>
	<tr align="center">
		<td>Edge or hole </td>
		<td>t ≤ 2,50  t > 2,50 </td>
		<td>5, 9  2, 7 </td>
		<td>through  corner </td>
		<td>2,54  2,54 </td>
	</tr>
	<tr align="center">
		<td>Cylinder </td>
		<td>N/A </td>
		<td>10 </td>
		<td>surface </td>
		<td>1,91 </td>
	</tr>
	<tr align="center">
		<td rowspan=3>Penetrant NDI  of titanium  alloys, welds  and Sensitivity  Level < 3 for all </td>
		<td>Open  surface </td>
		<td>t ≤ 3,0  t > 3,0 </td>
		<td>4  1, 3, 8 </td>
		<td>through  surface </td>
		<td>3,00  3,00  7,50 </td>
	</tr>
	<tr align="center">
		<td>Edge or hole </td>
		<td>t ≤ 3,0  t > 3,0 </td>
		<td>5, 9  2, 7 </td>
		<td>through  surface </td>
		<td>3,00  3,00 </td>
	</tr>
	<tr align="center">
		<td></td>
		<td>N/A </td>
		<td>10 </td>
		<td>surface </td>
		<td>3,00 </td>
	</tr>
	<tr align="center">
		<td rowspan=3>Magnetic  Particle NDI </td>
		<td>Open  surface </td>
		<td>t ≤ 1,91  t > 1,91 </td>
		<td>4  1, 3, 8 </td>
		<td>through  surface </td>
		<td>3,18  4,78  3,18 </td>
	</tr>
	<tr align="center">
		<td>Edge or hole </td>
		<td>t ≤ 1,91  t > 1,91 </td>
		<td>5, 9  2, 7 </td>
		<td>through  corner </td>
		<td>6,35  6,35 </td>
	</tr>
	<tr align="center">
		<td>Cylinder </td>
		<td>N/A </td>
		<td>10 </td>
		<td>surface </td>
		<td>3,18 </td>
	</tr>
	<tr align="center">
		<td>Radiographic  NDI </td>
		<td>Open  surface </td>
		<td>0,63 ≤ t ≤2,72 t > 2,72 </td>
		<td>1, 2, 3, 7, 8 </td>
		<td>surface </td>
		<td>1,91  0,7 × t </td>
	</tr>
	<tr align="center">
		<td></td>
		<td>surface </td>
		<td>t ≥ 2,54 </td>
		<td>1, 2, 3, 7, 8 </td>
		<td>surface </td>
		<td>3,81  1,65 </td>
	</tr>
	<tr align="center">
		<td colspan=7>NOTE 1  The crack configuration numbers refer to the crack configurations shown in Figure 10‐1, Figure 10‐2 and Figure  10‐3.  NOTE 2  For cylindrically shaped items (see Figure 10‐3) the crack depth a can be derived from the crack length c of this  table for a/c = 1,0 with the following formula:  a sec tan r 1( − + = c r c r )   Exception: fastener thread and fillets, see clause 8.8. </td>
	</tr>
</table>

 

70 ![Im0](images/Im0)

10.4.3

Inspection procedure requirements for

standard NDI

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 10.4.3.1  Standard radiographic NDI

a.

b.

c.

Radiographic  inspection  for  the  detection  of  volumetric  flaws  shall  be performed in conformance with ASTM E 1742. 

The  radiographic  quality  level  shall  be  equal  or  better  than  2‐1T (clause 6.9 of ASTM E 1742). 

The  radiation  of  the  beam  shall  be  within  ±5°  of  the  orientation  of  the plane of the crack to be detected. 

Radiographic 

different 

orientations  can  be  needed  to  ensure  that  the 

complete  volume  of  an  item  is  sufficiently 

inspected for potentially critical cracks that can 

be in a wide range of orientations. 

exposures 

NOTE 

at 

10.4.3.2  Standard penetrant NDI

a.

Penetrant  NDI  standard  flaw  sizes  shall  only  be  applied  to  fluorescent <table align="center">
</table>

NOTE 

Fluorescent  penetrants  of  level  2  sensitivity  or 

better  as  defined 

ISO 3452‐2  can  be 

considered equivalent. 

in 

b.

c.

d.

e.

For  metals  other  than  titanium, inspected  with  fluorescent  penetrant  to less  than  level 3  sensitivity  as  defined  in  10.4.3.2a,  the  standard  crack sizes of Table 10‐1, defined for titanium alloys shall be applied. 

All  machined,  or  otherwise  mechanically  disturbed  surfaces,  to  be penetrant  inspected,  shall  be  etched  to  assure  removal  of  masking material  prior  to  penetrant  application  for  all  processes  and  materials, where masking can appear. 

For  welds,  the  standard  crack  sizes  of  Table  10‐1,  defined  for  titanium alloys, shall be used in all cases, unless the weld surface is smoothened after welding to a level agreed with the customer. 

NOTE 

Limited  verification  of  the  crack  detection 

capability of the actual weld inspection can be 

appropriate. See also 10.4.2.1c. 

Interface surface finish shall be Ra=3,2 μm or lower. 

<table align="center">
</table>

Linear discontinuities of any length shall not be accepted. 

b.

71 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 c.

d.

e.

Ultrasonic  inspection  shall  be  performed  using  longitudinal  or  shear waves, applied via unobstructed bare flat surfaces, at right‐angles to all possible orientations of the cracks to be detected. 

Interface surface finish shall be Ra=3,2 μm or lower. 

Ultrasonic inspection for surface or embedded flaws in welds or in parent material surrounding the welds shall be in conformance with ASTM E 164. 10.4.3.4  Standard eddy current NDI

a.

Eddy Current inspection shall be in conformance with ASTM E 426 or a standard approved by the customer. 

A  minimum  signal‐to‐noise  ratio  of  3:1  shall  be  achieved  for  standard NDI. 

For  automated  inspection  or  inspection  with  signal  recording  and analysis a reduction of this ratio, as approved by the customer, may be applied. 

The interface surface finish shall be Ra = 3,2 μm or lower. 

b.

c.

d.

10.4.3.5  Standard magnetic particle NDI

a.  Magnetic particle inspection shall be in conformance with ASTM E 1444. b.

The wet process, continuous method technique, with fluorescent particles shall be used. 

Interface surface finish shall be Ra = 3,2 μm or lower. 

c.

72 ![Im0](images/Im0)

![Im0](images/Im0)

a

t

t

2c

W

2c

W

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Part-through cracks

c

a

t

W

t

2c

a

W

Through cracks

t

c

W

Embedded cracks

t

2a

2c

W

e

Figure 10‐1: Initial crack geometries for parts without holes 

73 ![Im0](images/Im0)

Part-through cracks

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 c

a

<table align="center">
</table>

t

W

O

2c

W

a

Through cracks

t

c

W

Figure 10‐2: Initial crack geometries for parts with holes 

Figure 10‐3: Initial crack geometries for cylindrical parts 

- 10.5  NDI for composites, bonded and sandwich parts

(10) 

10.5.1  General

a.

The standards EN 4179 or NAS 410 shall be applied for all NDI methods explicitly addressed by these standards. 

NOTE 

If  NDI  methods  are  used  which  are  not 

explicitly  addressed  by  EN 4179  or  NAS 410, 

apply clause 10.5.2.2.2a. 

74 ![Im1](images/Im1)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 b.

c.

d.

The  inspectors  shall  be  certified  to  at  least  level 2  for  the  NDI  method used. 

The NDI procedure shall be approved by a level 3 inspector. 

The capability of each applied NDI shall be demonstrated by the supplier in conformance with clause 10.5.2.2. 

NOTE 

The concepts of standard NDI and special NDI 

are  not  applicable  for  composite,  bonded  and 

sandwich parts. 

Inspection requirements

10.5.2

10.5.2.1  Close visual inspection

a.

b.

The maximum distance to perform the inspection shall be 0,3 m;  

An inspection procedure shall be written, which specifies: 

1.

2.

3.

4.

5.

6.

Access requirements 

Distance between eyes and inspected area 

Optimum lighting 

Cleaning 

The location of the successive inspected area 

The minimum inspection time needed to inspect each area. 

NOTE   A formal statistical capability demonstration of 

the detectability of the VDT by means of close 

visual 

the 

procedure  is  agreed  between  customer  and 

supplier. 

is  not  needed,  but 

inspection 

c.  When  an  indication  is  found,  optical  magnification  (lenses)  and  other NDI methods shall be applied to determine whether it or not to consider it as a detected defect in conformance with 10.7. 

10.5.2.2  NDI methods other than close visual inspection

10.5.2.2.1  General

a.

Applied  NDI  methods  shall  provide  crack  detection  to  at  least  90 % probability level (confidence level 95 %) in conformance with 10.5.2.2.1b. The capability of an NDI method (i.e. the reliably detectable defect size) shall be demonstrated by test on specimens with induced defects.  

Specimens with induced defects shall be used in the inspection procedure as standard for calibration. 

The capability of the inspection method shall be investigated on at least 5 specimens in order to analyse all defect parameters. 

b.

c.

d.

NOTE 1  Defect parameters to be investigated include defect 

type, position, size, shape and orientation. 

75 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 NOTE 2  Depending on e.g. the complexity of the item to be 

inspected  and  the  criticality  of  the  defects  to  be 

found  the  number  of  samples  to  be  used  can  be 

significantly higher than 5. 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

a.

b.

c.

d.

In the cases other than those addressed by 10.5.1a, the procedure shall be written by an expert for the NDI method. 

NOTE 

For  example,  the  procedure  can  be  written  by 

an operator practicing this method. 

In the cases other than those addressed by 10.5.1a, the procedure shall be approved  by  a  level 3  inspector  for  a  similar  NDI  method  covered  by EN 4179 or NAS 410. 

NOTE 1  The  certification  of  the  level 3  inspector  can  be 

considered  similar  when  obtained  for  a  method 

applicable  to  composite  parts  and  based  on  the 

most similar physical principle. 

NOTE 2  For  example,  X‐ray  certification  for  tomography 

method. 

In the cases other than those addressed by 10.5.1a, the procedure shall be based  on  the  same  rules  as  those  used  for  NDI  methods  explicitly addressed by the standards EN 4179 or NAS 410. 

In the cases other than those addressed by 10.5.1a, the implemented NDI method shall be documented and the physical principles used explained. - 10.6  Traceability

10.6.1  General

a.

2.

Traceability  of  PFCI  and  the  materials  they  are  made  of  shall  be implemented  in  conformance  with  ECSS‐Q‐ST‐20  to  provide  assurance that: 

1.

The material used in the manufacture of structural hardware has properties  fully  representative  of  those  used  in  the  analysis  or verification tests. 

Structural  hardware 

conformance  with 

implementation of the fracture control programme. 

is  manufactured  and 

the 

inspected specific 

requirements 

for 

in the 76 ![Im0](images/Im0)

10.6.2  Requirements

a.

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 and  quality 

associated  drawings,  manufacturing 

All 

control documentation shall identify that the item is a potential fracture‐critical item (unless when it is a fail‐safe or low‐risk fracture metallic item) or a fracture critical item. 

Each  fracture‐critical  item  shall  be  traceable  by  its  own  unique  serial number. 

Each  fracture‐critical  item  shall  be  identified  as  fracture‐critical  on  its accompanying tag and data package. 

For  each  fracture‐critical  item  a  log  shall  be  maintained,  which documents  the  environmental  and  operational  aspects  (including  fluid exposure for pressure vessels) of all storage conditions during the life of the item. 

For  each  fracture‐critical  item  a  log  shall  be  maintained,  which documents all loadings due to testing, assembly and operation, including pressure cycles and torqueing of fasteners.  

b.

c.

d.

e.

- 10.7   Detected defects

10.7.1  General

a.

Safe life and fail safe items with detected defects with a size larger than the following, shall be subjected to additional verification requirements as defined in clause 10.7.2: 

⎯

⎯

⎯

The acceptance criteria used in the manufacturing process; or 

50 %  of  the  maximum  allowed  detectable  NDI  size  in  any dimension; or 

50 %  of  the  standard NDI  size  defined  in  Table 10‐1, for  metallic materials 

NOTE 1  Acceptance criteria for flaws in the manufacturing 

process  ensure  that  material  property  values  are 

not reduced below the qualified minimum values 

used for design. 

Detailed  requirements  for  acceptance  criteria 

for  flaws  other  than  crack‐like  defects  are  not 

within the scope of this ECSS standard. 

NOTE 2  For  example,  definition  of  acceptance  criteria  for 

defects includes consideration of ultimate strength, 

fatigue life, leakage. 

b.

Any PFCI containing detected defects shall not be used without approval of the customer. 

NOTE 1  The first option to be considered when a defect is 

detected in flight hardware is to remove or repair 

the defect. 

77 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 NOTE 2  For highly critical hardware (especially when used 

for  manned 

spaceflight),  more  conservative 

verification methodology can be requested by the 

customer (see e.g. NASA‐HDBK‐5010). 

c.

Low risk fracture items shall not contain detected defects. 

10.7.2  Acceptability verification

10.7.2.1  Safe life parts with a detected defect

10.7.2.1.1  General

a.

The detected defect shall be verified as crack‐like defect, and a fracture mechanics  analysis  or  test  performed  to  verify  the  acceptability  of  this defect. 

NOTE   Only in the case of a well‐known type of defect 

(e.g.  pores) 

for  which  a  data  base  of 

representative 

test  data 

is  available,  an 

assessment  without  replacing  the  defect  by  a 

crack can be used. 

b.

The analysis or test shall be performed as follows: 

1.

2.

Define  the  dimensions  and  location  of  the  detected  defect conservatively (e.g. for a surface crack the length and depth). 

In the case of irregular defect shapes or grouped defects, make a recharacterisation  for  the  analytical  prediction  (in  the  case  of metallic  part)  or  for  test  with  induced  defect  (for  metallic  or composite part). 

NOTE 

For  metallic  parts,  flaw  characterization  as 

proposed  by  BS 7910  or  ASME  boiler  and 

pressure  vessel  code  Section XI,  article  IGA‐

3000 can be applied. 

3.

Demonstrate by analysis that the stresses used are conservative. NOTE 

analysis  methods,  which 

Improved 

are 

subjected to customer approval, can be needed 

to achieve this. 

c.

d.

There  shall  be  no  indication  that  the  cause  of  the  defect  affects  the validity of the material properties used in the safe life verification. 

The  analysis  or  test  shall  demonstrate  ultimate  load  capability  at  the beginning of life. 

10.7.2.1.2  For metallic parts

a.

The safe life crack growth analysis shall be performed as specified in 7, with the complete load spectrum applied 6 times in sequence. 

78 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 b.

c.

Cases  where  the  analysis  specified  in  10.7.2.1.1a  can  be  replaced  by  a representative  fatigue  test  of  a  part  containing  a  representative  defect other than a crack shall be agreed with the customer. 

NOTE 

This is agreed only in the case of a well‐known 

type of defect. 

The  fatigue  test  specified  in  10.7.2.1.2b  shall  demonstrate  limit  load capability  after  application  of  the  complete  load  spectrum  6  times  in sequence. 

10.7.2.1.3  For composite, bonded and sandwich parts

a.

The safe life verification shall be performed in conformance with clause 8.4. 10.7.2.2  Fail safe parts with a detected defect

a.

The  part  shall  meet  the  requirements  in  6.3  for  safe  parts  using  the detected defect in conformance with 10.7.2.2b. 

For the verification of 10.7.2.2a, the detected defect shall be assumed in the most unfavourable situation.  

b.

NOTE 1  This  means  the  situation  where  the  choice  of  the 

failed  part  places  the  detected  defect  in  the  most 

unfavourably loaded remaining part.  

NOTE 2  This includes fatigue, verification, considering the 

detected  defects.  Alternatively, 

can  be 

demonstrated that the structure can withstand the 

failure  of  any  other  part,  in  addition  to  failure  of 

parts  containing  detected  defects  (using  safety 

factors  as  specified 

in  6.3.3,  and  without 

considering a defect in the remaining structure). 

it 

c.

For metallic parts the detected defect shall be verified as crack‐like defect, and a fracture mechanics analysis or test shall be performed to verify the acceptability of this defect. 

NOTE   Only in the case of a well‐known type of defect 

for  which  a  data  base  of 

(e.g.  pores) 

representative 

test  data 

is  available,  an 

assessment  without  replacing  the  defect  by  a 

crack can be used. 

d.

For composite, bonded and sandwich parts the fatigue verification shall be based on tests of representative defects. 

10.7.3

a.

Improved probability of detection

If  the  origin  of  a  detected  defect  is  not  uniquely  determined  and eliminated, and regular occurrence of significant crack‐like defects is not excluded  by  means  of  improvement  of  the  manufacturing  process,  an improved  NDI  method  approved  by  the  customer  shall  be  used,  such that 

it  provides  a  probability  higher  than  90%  of  detection  of unacceptable defects.  

79 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Reduced fracture control programme- 11.1   Applicability

As  specified  in  5.1  for  unmanned,  single‐mission,  space  vehicles  and  their payloads,  and  for  GSE,  a  reduced  fracture  control  programme  (RFCP)  as defined  in  this  clause  can  be  implemented,  instead  of  the  general  fracture control programme. 

- 11.2   Requirements

11.2.1  General

a.

A reduced fracture control programme shall be in conformance with all the requirements given in this standard, with the modifications specified in 11.2.2. 

11.2.2  Modifications

Identification of PFCIs

11.2.2.1

a.

The identification of PFCIs may be limited to the following items: 

1.

2.

3.

4.

Pressurized systems. 

Rotating machinery. 

Fasteners used in safe life applications. 

Items fabricated using welding, forging or casting and which are used  at  limit  stress  levels  exceeding  25 %  of  the  ultimate  tensile strength of the material. 

Non‐metallic structural items. 

5.

6.  Metallic  structural  items  used  in  safe  life  applications,  with  limit stress  levels  exceeding  50%  of  the  yield  tensile  strength  of  the material. 

NOTE 1  When approved by the customer, the scope of this 

requirement  can  be  reduced  to  single  point  of 

failure  items  loaded  in  tension  with  relatively 

80 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 small  cross‐section 

mounts, small strut or pin, GSE interface). 

(examples: 

lugs, 

iso‐static 

NOTE 2  For PFCIs, see 6.1.  

![Im0](images/Im0)

<table align="center">
</table>

11.2.2.2  Documentation requirements

a.

The  information  specified  in  clause  6.4.2  may  be  consolidated  into  one list; separate lists need not be prepared. 

11.2.2.3  Glass and non-metallic items other than

composites, bonded and sandwich items

a.

The requirements of clauses 8.5 and 8.7 may be replaced by the following requirement:  structural  glass  and  other  non‐metallic  items  (other  than composites,  bonded  and  sandwich  items)  shall  be  proof‐tested  at  1,2 times the limit load. 

NOTE 

It  is  well‐known  that  glass  and  other  brittle 

items subjected to static load can be sensitive to 

growth  of  inherent  flaws  (i.e.  static  fatigue). 

This  effect 

in  the 

structural  verification, 

into  account 

empirical  data  (e.g.  statistical  methods,  taking 

into account the surface roughness of the item).  

is  normally  considered 

taking 

11.2.2.4  Rotating machinery

a.

The  requirements  of  clause  8.6  may  be  replaced  by  the  following requirement: ‘rotating machinery (wheels and gyros) shall be proof‐spin‐tested at one and one tenth (1,1) times nominal operational speed. 

81 ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Annex A (informative)The ESACRACK software packageGenerate load and stress spectra (ESALOAD) 

Perform fracture mechanics analysis (NASGRO® module NASFLA) 

Generate stress intensity factor solutions (NASGRO® module NASBEM) Process crack growth material data (NASGRO® module NASMAT) 

Perform fatigue analysis (ESAFATIG). 

The ESACRACK software package is intended to be used for damage tolerance analysis  of  spaceflight  vehicles  and  payloads  as  well  as  ground  support equipment. The package consists of various analysis tools that enable the user to:  •

•

•

•

•

The  flight  load  spectra  distributed  with  ESACRACK  have  been  derived  for payloads  of  the  NSTS,  and  cannot  be  used  for  other  structures  without adequate verification. 

The  software  package ESACRACK  can  be  obtained  from Mechanical  Systems Department of ESA. 

The  data  contained  in  the  standard  materials  data  bases  provided  with  the NASGRO  and  ESAFATIG  software,  and  the  stress  intensity  and  net  section stress  solutions 

in  the  NASGRO  software,  are  generally acceptable  for  fracture  control  analysis.  The  judgement  of  the  applicability  of these data for the actual hardware remains the responsibility of the user of the software, however. 

The material data in the NASGRO database are mean or typical values, and a reduction  as  specified  in  clause  7.2.5  is  therefore  applied  for  the  toughness parameters.  A  reduction  option  is  implemented  in  older  versions  of  the ESACRACK software. 

Caution: The NASGRO software offers a number of advanced analysis options which  are  potentially  unconservative  and  not  allowed  by  this  standard,  or require  specifically  validated  material  data  (e.g.  retardation  models  like  the strip‐yield model, elastic‐plastic analysis, shakedown analysis). Application of such options is normally subject to customer approval. 

In some cases (e.g. for fracture analysis of detected cracks, for determination of defect acceptance criteria or proof test crack screening capability, or for crack growth prediction where the spectrum can cause acceleration of crack growth) the application of such advanced options in NASGRO or other fracture analysis software can be necessary. 

implemented 

82 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 Annex B (informative)ReferencesBroek, ‘The practical use of fracture mechanics’, 1989, Kluwer, ISBN 90‐247‐3707‐9. 

Berger,  Blauel,  Pyttel  &  Hodulak,  ‘FKM  Guideline  –  Fracture Mechanics  Proof  of  Strength  for  Engineering  Components’,  2nd revised edition, 2004, VDMA Verlag GmbH, ISBN 3‐8163‐0496‐6. 

Sierakoswki  &  Newaz,  ‘Damage  tolerance  in  advanced  composites’, 1995, Technomic Publishing, ISBN 1‐56676‐261‐8 

‘Aerospace Structural Metals Handbook’, CINDAS/Purdue University Saxena  ‘Nonlinear  Fracture  Mechanics  for  Engineers’,  1998,  CRC Press, ISBN 0‐8493‐9496‐1 

Chell,  McClung,  Kuhlman,  Russell,  Garr,  Donnelly,  ‘Guidelines  for Proof Test Analysis’, 1999, NASA/CR‐1999‐209427 

McClung,  Chell,  Lee,  Russell,  Orient,  ‘Development  of  a  Practical Methodology  for  Elastic‐Plastic  and  Fully  Plastic  Fatigue  Crack Growth’, 1999, NASA/CR‐1999‐209428 

[R1] 

[R2] 

[R3] 

[R4] 

[R5] 

[R6] 

[R7] 

 

83 ![Im0](images/Im0)

ECSS‐E‐ST‐32‐01C Rev. 1 6 March 2009 BibliographyECSS‐S‐ST‐00 

ECSS‐Q‐ST‐10‐09  

ISO 3452‐2  

NASA‐HDBK‐5010 

MIL‐HDBK‐17 

BS 7910  

 

ECSS  system  –  Description,  implementation  and general requirements 

Space  product  assurance  ‐  Nonconformance  control system 

Non‐destructive  testing  ‐  Penetrant  testing  ‐  Part  2: Testing of penetrant materials 

‘Fracture  control 

for payloads,  experiments,  and  similar  hardware’,  2005, NASA 

Composite Materials Handbook 

Guide  on  methods  for  assessing  the  acceptability  of flaws in metallic structures 

implementation  handbook 

84 ![Im0](images/Im0)

