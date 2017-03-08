ECSS-Q-ST-70-18C15 November 2008Space product

assurance

Preparation, assembly and

mounting of RF coaxial cables

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This Standard has been prepared by the ECSS Executive Secretariat endorsed by the document and 

- discipline focal point and approved by the ECSS Technical Authority. 

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

2008 © by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐Q‐70‐18A  31 August 2001 </td>
		<td>First issue   Transforming ESA PSS‐01‐718  into an ECSS Standard </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐70‐18B </td>
		<td>Never issued  </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐70‐18C  15 November 2008 </td>
		<td>Second issue  The following is a summary of changes between ECSS‐Q‐70‐18A and the  present issue:  •  Redrafting ECSS‐Q‐70‐18A according to ECSS drafting rules and new  template.  •  Reorganization of the content to separate descriptive text and  requirements, and creation of DRD.   </td>
	</tr>
</table>

3 ECSS‐Q‐ST‐70‐18C 15 November 2008 Table of contents- Change log.................................................................................................................3

- Introduction................................................................................................................7

- 1 Scope.......................................................................................................................8

- 2 Normative references.............................................................................................9

- 3 Terms, definitions and abbreviated terms..........................................................10

- 3.1  Terms from other standards .....................................................................................10

- 3.2  Terms specific to the present standard ....................................................................10

- 3.3  Abbreviated terms ....................................................................................................10

- 4 Principles and prerequisites of reliable soldered or crimped cable

- connections .........................................................................................................11

- 4.1  Principles of reliable soldered or crimped semi-rigid cable connections ..................11

- 4.2  Prerequisites for assembly and mounting of semi-rigid coaxial cables ....................11

- 4.3  Alternative coaxial cable technologies .....................................................................12

5.1.1

5.1.2

5.1.3

5.1.4

- 5 Requirements........................................................................................................13

- 5.1  Preparatory conditions .............................................................................................13

Facility cleanliness......................................................................................13Environmental conditions ...........................................................................13Lighting requirements.................................................................................14Equipment and tools...................................................................................14- 5.2  Material selection .....................................................................................................16

Solder .........................................................................................................165.2.1

Flux.............................................................................................................175.2.2

5.2.3

Solvents......................................................................................................175.2.4  Cable selection...........................................................................................185.2.5  Connector selection....................................................................................18- 5.3  Preparation of semi-rigid cable.................................................................................19

5.3.1  General.......................................................................................................19Inspection of cable......................................................................................195.3.2

4 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 5.3.3  Cutting cable to initial oversize length ........................................................195.3.4  Cable forming and minimum bend radius...................................................19Preconditioning heat treatment...................................................................205.3.5

5.3.6

Trimming cable to final length.....................................................................21Stripping the cable ends.............................................................................225.3.7

5.3.8

Inspection of stripped cable ends...............................................................22- 5.4  Preparation for soldering assembly of semi-rigid cables..........................................23

5.4.1  General.......................................................................................................235.4.2  Degolding and pretinning............................................................................23Solder preforms..........................................................................................245.4.3

- 5.5  Assembly of connectors to RF coaxial cables..........................................................25

5.5.1

Solder assembly of semi-rigid cables .........................................................255.5.2  Crimp assembly of semi-rigid cables and other assembly techniques .......295.5.3  Completed assemblies ...............................................................................29- 5.6  Mounting of cables ...................................................................................................30

Semi-rigid cables with straight solder-type connectors ..............................305.6.1

Semi-rigid cables with right-angle connectors ............................................315.6.2

5.6.3  Other cable mounting technologies............................................................31- 5.7  Process verification ..................................................................................................32

5.7.1  General.......................................................................................................32Temperature cycling...................................................................................325.7.2

5.7.3

Vibration .....................................................................................................32- 5.8  Quality assurance.....................................................................................................32

5.8.1  Data............................................................................................................325.8.2  Nonconformance ........................................................................................335.8.3  Calibration ..................................................................................................335.8.4

Traceability .................................................................................................335.8.5  Workmanship standards.............................................................................335.8.6

Inspection ...................................................................................................335.8.7  Operator and inspector training and certification........................................34- Annex A (normative) Logbook – DRD....................................................................35

- Annex B (normative) Workmanship standards.....................................................36

- B.1  Overview ..................................................................................................................36

- B.2

Illustrations ...............................................................................................................36- Annex C (informative) Graphical information .......................................................38

- C.1  Overview ..................................................................................................................38

5 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 - C.2  Typical cable cut-off fixture.......................................................................................38

- C.3  Typical cable-forming tool ........................................................................................39

- C.4  Approved and non-approved straight solder-type cable-end connectors.................40

- C.5  Method of producing solder performs.......................................................................41

- C.6  Centre contact assembly..........................................................................................41

- Bibliography.............................................................................................................42

- Figures

- Figure B-1 : Photograph showing non-captive nut and preferred solder fillet ........................36

- Figure B-2 : Microsection through preferred solder fillet, revealing full penetration of

solder path ...........................................................................................................36- Figure B-3 : Unacceptable solder fillet dimensions ................................................................37

- Figure C-1 : Typical cable cut-off fixture.................................................................................38

- Figure C-2 : Typical cable-forming tool ..................................................................................39

- Figure C-3 : Approved and non-approved straight solder-type cable-end connectors...........40

- Figure C-4 : Method of producing solder preforms.................................................................41

- Figure C-5 : Centre contact assembly....................................................................................41

- Tables

- Table 5-1: Design rules for minimum bend radius..................................................................20

- Table 5-2: Preconditioning heat treatment process................................................................21

 

6 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 IntroductionThe  main  part  of  this  Standard  is  based  on  industrial  experience  and recommendations from European soldering technology experts. Modifications are  incorporated  into  the  text  to  provide  for  the  specific  requirement  of low‐outgassing  electrical  systems  which  are  required  by  scientific  and application  satellites.  Other  additions  were  made  in  the  light  of  recent technological advances and results of metallurgical test programmes. The use of processes  other  than  solder  assembly  is  recognized,  but  only  certain  general requirements are given in this Standard. 

These  requirements  apply  to  assemblies  designed  to  operate  within  the temperature limits from ‐45 °C to +85 °C. More extreme temperatures or other unusual  environmental  applications  require  special  design  measures  or processing steps to provide environmental survival capability. 

7 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 ScopeThis  Standard  defines  the  technical  requirements  and  quality  assurance provisions for the assembly and mounting of high‐reliability, radio‐frequency (RF)  coaxial‐cable  interconnections  for  use  as  transmission  lines  in  spacecraft and associated equipment. 

In general, these assemblies are designed for low‐loss, stable operation from the relatively  low  frequencies  through  the  higher  frequencies  in  the  microwave regions. 

These  transmission‐line  cables  should  not  be  confused  with  low‐frequency cables  with  conductive  sheaths  (usually  copper  braid),  which  are  used  in applications  where  shielding  of  the  centre  conductors  from  the  surrounding electrical ambient is required. The interconnection of those shielded cables, not covered by the present standard, is covered in ECSS‐Q‐ST‐70‐08. 

This standard may be tailored for the specific characteristics and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

 

8 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply, However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐Q‐ST‐10‐09 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐60 

ECSS‐Q‐ST‐70‐02 

ECSS‐Q‐ST‐70‐08 

ECSS‐Q‐ST‐70‐26 

ECSS‐Q‐ST‐70‐28 

MIL‐C‐17G(3) SUP1 

 

ECSS system — Glossary of terms 

Space product assurance — Nonconformance control system 

Space product assurance — Quality assurance 

Space product assurance — Electrical, electronic and electromechanical (EEE) components 

Space product assurance — Thermal vacuum outgassing test for the screening of space materials 

Space product assurance — Manual soldering of 

high‐reliability electrical connections 

Space product assurance — Crimping of high‐reliability electrical connections 

Space product assurance — Repair and modification of printed circuit board assemblies 

General specification for cables, radio frequency, flexible and semi‐rigid. (8 Jan 1996) 

9 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 apply, in particular for the following terms: 

requirement 

- 3.2  Terms specific to the present standard

minimum bend radius

3.2.1

inside radius of the bend measured on the outer surface of the cable 

- 3.3  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

 

Abbreviation 

FEP 

PTFE 

SMA 

VSWR 

 

Meaning 

fluorinated ethylene propylene 

polytetrafluoroethylene 

sub miniature version A 

voltage standing wave ratio 

10 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Principles and prerequisites of reliablesoldered or crimped cable connections- 4.1  Principles of reliable soldered or crimped semi-rigid

cable connections

Reliable soldered or crimped connections result from proper design, control of tools, materials and work environments and careful workmanship. 

The basic design concepts, adherence to which ensures reliable connections and prevents joint failure, are: 

a.

Avoidance of dimensional mismatch between the coaxial‐cable assembly and  the  units  being  connected;  i.e.  not  forcing  the  semi‐rigid  cable assembly into position and thereby cracking or pre‐stressing one of the joints. 

Use of cable‐end connectors with retractable (non‐captive) coupling nuts; after completion of mounting, the coaxial‐cable assembly is not in a state of  tension  resulting  from  axial  movement  when  the  connectors  are threaded together. 

b.

c.  Minimizing the internal stresses on the soldered or crimped connections resulting from exposure to thermal cycling.  

NOTE 

The  thermal  coefficient  of  expansion  of  the 

dielectric is about ten (10) times that of copper and 

in service this can introduce a tensile stress on the 

joint. 

d.

The  various  assembly  and  mounting  processes  are  covered  by quality‐control inspection steps. 

- 4.2  Prerequisites for assembly and mounting of

semi-rigid coaxial cables

Each supplier maintains documented soldering or crimping programmes which meet the requirements of this Standard for the types of connections employed and  the  articles  involved.  The  programmes  include  procedures  for  training, certification,  maintenance  of  certified  status,  recertification  and  revocation  of certified status for soldering, crimping and inspection personnel. The supplier also  prepares  and  has  readily  available  workmanship  standards  consisting  of 11 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 involved, 

including 

for  all  connections 

satisfactory  work  samples  or  visual  aids  which  clearly  illustrate  the  quality characteristics 

the  applicable illustrations in Annex B of this Standard. 

Records are kept to provide identification between the finished product and the operator. Records are also maintained of the training, testing and certification status  of  assembly  operators.  Records  are  retained  for  at  least  one  year,  or longer if this is a specific requirement of the customer’s project. 

Equipment  and  tools  are  verified  and  calibrated  periodically  for  proper operation, and records of tool calibration and verification are maintained (see clause 5.8). 

For  soldering  or  crimping  requirements  not  covered  in  this  Standard,  the supplier  submits  a  process  procedure 

including  all  pertinent  quality requirements  to  the  customer’s  relevant  project  office  for  approval  in accordance with ECSS‐Q‐ST‐70. 

- 4.3  Alternative coaxial cable technologies

Alternative coaxial cable technologies are accepted for application in individual customer  programmes  following  the  completion  of  qualification  and  batch acceptance  test  programmes  in  accordance  with  clause  5.7.  The  precise test‐programme  and  results  are  subject  to  review  and  acceptance  by  the relevant customer programme. For materials used in the alternative technology see ECSS‐Q‐ST‐70‐71. 

Some  mounting  requirements  for  alternative  technologies  are  given  in  clause 5.6.3 of this Standard. 

12 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Requirements- 5.1  Preparatory conditions

Facility cleanliness

5.1.1

a.

Unless classified as a cleanroom, the supplier shall maintain the areas in which  soldering  is  carried  out  in  a  neat  orderly  fashion  with  no  loose material that can cause contamination of the soldered connection. 

b.

c.

d.

e.

f.

g.

NOTE 

Examples  for  loose  material  are  dirt,  dust,  solder 

particles, oils and clipped wires. 

The supplier shall keep furniture to a minimum in the work areas and be arranged to allow easy and thorough cleaning of the floor. 

A washroom and eating, drinking and smoking facilities shall be located close to, but outside, the soldering areas. 

The  supplier  shall  cover  working  surfaces  with  an  easily  cleaned  hard top  or  have  a  replaceable  surface  of  clean,  non‐corrosive  silicone‐free paper. 

The supplier shall only use clean tools in the soldering operation. 

The  supplier  shall  remove  excess  lubricants  from  the  tools  before soldering starts. 

Before assembly, wire, terminal and connector contacts shall be visually examined for cleanliness, absence of oil films and freedom from tarnish or corrosion. 

5.1.2

a.

b.

c.

Environmental conditions

The  supplier  shall  have  an  assembly  area  which  has  a  controlled environment that limits entry of contamination. 

The  supplier  shall  maintain  the  following  environmental  conditions  in the area: 

1.

2.

The work stations shall not be exposed to draughts. 

Room temperature: (22 ± 3) °C 

Relative humidity at room temperature (55 ± 10) %. 

13 ![Im0](images/Im0)

![Im0](images/Im0)

d.

The supplier shall use a filter system to supply fresh air to the room, so that there is a positive pressure difference with respect to adjacent rooms. ECSS‐Q‐ST‐70‐18C 15 November 2008 5.1.3

a.

b.

Lighting requirements

The supplier shall ensure a lighting intensity of a minimum of 1 080 lux on the work surface. 

The  supplier  shall  ensure  that  at  least  90  %  of  the  work  area  is shadowless and without severe reflections. 

5.1.4

Equipment and tools

5.1.4.1  Brushes

a.

The  supplier  shall  use  brushes  for  cleaning,  provided  that  they  do  not scratch  the  metal  surface  to  be  cleaned  or  damage  adjacent  materials beyond their visual inspection requirements. 

NOTE   Medium‐stiff  natural‐  or  synthetic‐bristle  brushes 

can be used. 

b.

c.

The supplier shall clean these brushes before use in a solvent prescribed in clause 5.2.3.  

The supplier shall not use wire brushes. 

Files

5.1.4.2

a.

The supplier shall use smooth, single cut and mill type files for dressing copper soldering‐iron tips and removing burrs from the conductor. 

The supplier shall not use files on surface‐treated tips or pretinned items. NOTE   Nickel plated is an example for surface‐treatment. 

The supplier shall keep the files in a good condition and shall be cleaned before use. 

The supplier shall not keep the files in a cleanroom environment. 

b.

c.

d.

b.

5.1.4.3  Cutting tools

a.

The  supplier  shall  use  at  least  the  following  cutting  tools  for  the preparation of the semi‐rigid cable: 

1.

jeweller’s saws having fine teeth; 

NOTE   A 0,28 mm ‐ 0,33 mm blade is preferred. 

single edged razor blades; 

wire cutters. 

2.

3.

The supplier shall use the jeweller’s saw together with a cable clamping device. 

14 ECSS‐Q‐ST‐70‐18C 15 November 2008 NOTE   An  example  of  such  a  cable  clamping  device  is 

shown in Figure C‐1. 

c.

d.

The supplier shall cut the dielectric and inner conductor with a tool that produces a clean, smooth‐cut surface along the entire cutting edge. 

The  supplier  shall  not  perform  any  twisting  action  during  this  cutting operation. 

5.1.4.4  Cable-forming tools

a.

The  supplier  shall  use  bending  jigs  to  form  the  cable  to  predetermined shapes as identified by the engineering drawing. 

NOTE   An  example  of  such  a  bending  jig  is  shown  in 

Figure C‐2. 

b.

c.

The supplier shall use roller sizes consistent with each cable diameter. The  supplier  shall  use  this  equipment  in  such  a  way  that  it  does  not introduce dents, nicks, wrinkles or cracks in the cable outer conductor. 5.1.4.5  Cable stripping and dressing tools

a.

The supplier shall use cable stripping and dressing tools in such a way that  they  do  not  twist,  ring,  nick,  or  score  the  underlying  material surface. 

NOTE   Many pieces of commercially available equipment 

exist  to  strip the  outer  conductor  or  the  dielectric 

material.  These  can  be  automatic,  power‐driven 

devices  with  precision  factory‐set  non‐adjustable 

cutting and stripping dies, or precision hand‐type 

strippers with accurately machined cutting heads. 

b.

The  supplier  shall  perform  either  periodic  calibration  or  sample evaluation during a production run. 

5.1.4.6  Heat-treatment chamber

a.

The supplier shall use thermal cycling cabinets, ovens, refrigeration units or  cold  chambers  capable  of  maintaining  temperatures  between  ‐50 °C and +90 °C 

NOTE   Under  certain  circumstances  (see  Table  5‐2  step 

3.3) greater temperature extremes can be required. 

b.

The supplier shall calibrate the working zone to within ±5 °C. 

Soldering equipment

5.1.4.7

a.

The  supplier  shall  accomplish  one  of  the  following  soldering  methods that conforms to the requirements on “Equipment and tools” of ECSS‐Q‐ST‐70‐08: 

1.

2.

by hand or 

by using a resistance heating unit or 

15 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 3.

other contact heat source  

b.  When  non‐contact  heat  sources  are  utilized,  the  supplier  shall  set  up, operate  and  demonstrate  to  the  satisfaction  of  the  customer  that  the particular  method  and  schedule  produces 

joints  of  an  acceptable standard. 

NOTE 

This  includes  verification  testing  as  detailed  in 

clause 5.7. 

5.1.4.8  Crimping equipment

a.

The  supplier  shall  use 

manufacturer as a guide. 

the  settings  recommended  by 

the 

tool NOTE 

This is necessary since manual crimping tools are 

available; they are custom designed and applicable 

only for particular connector shells. 

b.

c.

The supplier shall set up the tool for the cable and connector types by a detailed  calibration  programme  based  on  the  requirements  of  ECSS‐Q‐ST‐70‐26. 

The supplier shall perform verification testing as detailed in clause 5.7. 5.1.4.9  Assembly equipment, tools and processes for othertechnologies

a.

The  supplier shall  only  use  the  equipment,  tools,  and  processes for  the assembly of the cables and connectors that are designed to avoid damage or degradation of the cables and connectors. 

NOTE 

The equipment, tools, and processes can be subject 

to  a  manufacturing  audit  by  the  customer  before 

application in their programme. 

5.1.4.10  Defective or uncalibrated equipment or tools

a.

The  supplier  shall  promptly  remove  and  replace  defective  or uncalibrated equipment or tools from the work areas. 

- 5.2  Material selection

Solder

5.2.1

a.

The  supplier shall use solder  ribbon, wire and  preforms,  provided  that the alloy and flux conform to the requirements on “material selection” of ECSS‐Q‐ST‐70‐08. 

NOTE 1  The following solder alloys are approved: 

•  60  Sn  (remainder 

lead):  For  degolding 

operations, coating and pretinning. 

16 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 •  96  Sn 

(remainder  silver):  For  making 

coaxial‐cable  outer‐conductor‐to  connector 

solder joint. 

•  96  Sn  or  63  Sn  (remainder  lead):  For 

contact‐pin soldering and cover soldering of 

right angle connectors. 

NOTE 2  Refer  also 

to 

table  of  “Chemical 

composition  of  spacecraft  solders”  in  ECSS‐Q‐

ST‐70‐08. 

the 

Flux

5.2.2

a.

The supplier should perform degolding and pretinning operations with activated fluxes. 

NOTE 

Examples  of  activated  fluxes  are  J‐STD‐004  Type 

ROL1 and ROH1. 

b.

c.

The supplier shall completely remove activated fluxes immediately after use and before any further soldering operation. 

The supplier shall only use pure rosin flux for spacecraft assembly work. NOTE   An  example  of  pure  rosin  flux  is  J‐STD‐004  Type 

ROL0. 

Solvents

5.2.3

a.

b.

c.

d.

e.

f.

The supplier shall only use solvents for the removal of grease, oil, dirt, flux and flux residues that are non‐conductive and non‐corrosive. 

The supplier shall only use solvents for the removal of grease, oil, dirt, flux and flux residues that do not dissolve or degrade the quality of parts or materials or remove their identification markings. 

The  supplier  shall  label  the  solvents  and  maintain  them  in  a  clean  and uncontaminated condition. 

The supplier shall not use solvents showing evidence of contamination or decomposition. 

The  supplier  shall  not  use  solvents  that  transfer  dissolved  flux  residue onto contact surfaces. 

NOTE 

This can be the case for switches, potentiometers or 

connectors. 

The  supplier  shall  use  solvents  in  conformance  with  ECSS‐Q‐ST‐70‐08, clause 6.4h. 

17 ![Im0](images/Im0)

![Im0](images/Im0)

5.2.4

a.

Cable selection

ECSS‐Q‐ST‐70‐18C 15 November 2008 The  supplier  shall  procure  semi‐rigid  cables  in  conformance  with  the detailed requirements of MIL‐C‐17G(3) SUP1. 

b.

c.

d.

NOTE 

The selection of a particular coaxial cable involves 

consideration of the specific electrical, mechanical 

and environmental requirements of the project. 

The  supplier  shall  procure  semi‐rigid  cable  with  outer  conductor diameter  standardized  as  either  0,085  inches  or  0,141  inches  (±0,001 inches) and fabricated from copper. 

NOTE 

The  outer  conductor  can  be  finished  with  silver 

plating. 

The  supplier  shall  procure  semi‐rigid  cable  with  dielectric  material composed  of  polytetrafluoroethylene  (PTFE)  or  fluorinated  ethylene propylene (FEP). 

The supplier shall select the material composition of the inner conductor following a review of the specific project/equipment requirements. 

the  proposed 

NOTE 1  The  review  also  considers 

connector designs. 

In general copper is a suitable inner conductor. 

NOTE 2 

Connector selection

5.2.5

a.

b.

c.

d.

e.

f.

g.

The supplier shall only select approved connectors in conformance with the  requirements  on  “Quality  levels”  of  ECSS‐Q‐ST‐60,  for  use  in assembling solder‐type semi‐rigid cables. 

The supplier may use connectors with the form of: 

1.

straight  cable‐end  connector,  with  a  centre  contact,  and non‐captive coupling nut; 

NOTE 

See Figure C‐3 for distinction between non‐captive 

and captive coupling nut connectors. 

right angle cable‐end connector. 

flange‐mount male receptacle, either two‐ or four‐hole type. 

2.

3.

The  use  of  right  angle  cable‐end  connector  shall  be  restricted  to applications where stress‐free mounting of cables with these captive nut connectors can be assured. 

For other applications the use of right angle cable‐end connector should be minimized. 

All  non‐metallic  materials  incorporated  in  the  connector  shall  meet  the outgassing requirements according to ECSS‐Q‐ST‐70‐02. 

The supplier shall not use pure tin or cadmium finishes. 

For  the  use  of  special  connectors  for  non‐solder  systems,  the  supplier shall obtain customer approval. 

18 ![Im0](images/Im0)

- 5.3  Preparation of semi-rigid cable

ECSS‐Q‐ST‐70‐18C 15 November 2008 5.3.1  General

a.

The supplier shall ensure that the delivered coaxial cables are in the form of straight lengths. 

NOTE 

The  initial  preparation  is  similar  for  each  cable 

diameter  and  each  connector  type  and  whether 

joining is by soldering or crimping. 

Inspection of cable

The supplier shall remove the delivered cable from its container and shall inspect it for dents, nicks, wrinkles, blisters and contamination. 

If  dents,  nicks,  wrinkles,  blisters  or  contamination  are  identified,  the supplier shall reject the cable. 

5.3.2

a.

b.

5.3.3

a.

Cutting cable to initial oversize length

The supplier shall calculate the total specified length of the cable from the engineering drawing. 

NOTE 

This includes also bends and angles 

The supplier shall then add approximately 10 mm to the length to allow for bending, preconditioning and end dressing. 

The  supplier  shall  hold  the  cable  in  a  special  fixture  and  cut  it  to  the initial oversize length using the jeweller’s saw. 

NOTE 

Such as fixture is illustrated in Figure C‐1. 

The supplier shall not overtighten the special fixture. 

This is to avoid damage to the cable. 

NOTE 

The supplier shall debur and examine the cut end. 

b.

c.

d.

e.

5.3.4

a.

Cable forming and minimum bend radius

All cables shall be formed to the required shape dimensions before cable preconditioning using a bending jig. 

NOTE   An  example  of  such  a  bending  jig  is  shown  in 

Figure C‐2. 

b.

c.

d.

The  supplier  shall  perform  only  one  bending  operation  to  form  each shape. 

The supplier shall not make attempts to reshape a bent cable. 

The  supplier  shall  establish  design  rules  with  minimum  bend  radii  as given in Table 5‐1. 

19 ECSS‐Q‐ST‐70‐18C 15 November 2008 Each finished cable end shall have a minimum straight length of cable to allow for clearance during the assembly and mounting operations. 

The straight length shall be greater than 10 mm for 0,085 diameter cable. The straight length shall be greater than 20 mm for 0,141 diameter cable. The supplier shall prevent wrinkling or cracking when forming the cable. The  supplier  shall  apply  a  slow,  even  and  continuous  pressure  when bending of the cable. 

e.

f.

g.

h.

i.

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Cable diameter (inches) </td>
		<td>Minimum bend radius (mm) </td>
	</tr>
	<tr align="center">
		<td>0,085 </td>
		<td>3,2 </td>
	</tr>
	<tr align="center">
		<td>0,141 </td>
		<td>6,3 </td>
	</tr>
</table>

 

5.3.5

Preconditioning heat treatment

5.3.5.1  General

a.

The supplier shall achieve core stress relief by preconditioning each cable before it becomes a cable assembly. 

NOTE 

The  electrical  and  mechanical  performances 

specified  for  semi‐rigid  cables  are  achieved  by  a 

compression  fit  between  the  outer  conductor  and 

the  dielectric  core,  which,  in  turn,  necessitates 

manufacturing processes that cause deformation of 

the  core  by  compression  and  elongation.  The 

resulting stress that is initially non‐uniform tends 

to equalize by cold flow within a few weeks after 

the  manufacturing  and  causes  withdrawal  of  the 

core into the cable. If this occurs in cable that has 

become  part  of  a  cable  assembly,  the  resulting 

development  of  an  air‐gap  at  the  cable/connector 

interface causes an increase in the voltage standing 

wave ratio (VSWR). Therefore the preconditioning 

is performed. 

5.3.5.2  Heat treatment process

a.

The  supplier  shall  perform  preconditioning  in  conformance  with  Table 5‐2 on cables that are formed into the required bend configuration. 

The supplier shall not perform preconditioning on a soldered or crimped cable. 

b.

NOTE 

This  is  valid  even  if  only  one  lead  end  is 

terminated to a connector. 

20 ECSS‐Q‐ST‐70‐18C 15 November 2008 c.

d.

The  supplier  shall  place  the  entire  cable  in  the  thermal  cycling arrangement. 

The rate of change of temperature shall not exceed 2 °C per minute. 

Recommendations 

special 

requirements  (e.g.  higher  operating  temperature 

extremes) 

can 

cable 

manufacturers. 

for  dealing  with 

NOTE 

be 

obtained 

from 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Step </td>
		<td>Procedure </td>
	</tr>
	<tr align="center">
		<td>1 </td>
		<td>Cool the cable down to ‐45 °C and maintain this temperature for at  least 1 hour. </td>
	</tr>
	<tr align="center">
		<td>2 </td>
		<td>Let the cable return to room temperature and maintain it at this  temperature for at least 1 hour. </td>
	</tr>
	<tr align="center">
		<td>3.1 </td>
		<td>Heat the cable to the upper temperature and maintain it at this  temperature for at least 1 hour. </td>
	</tr>
	<tr align="center">
		<td>3.2 </td>
		<td>Ensure that the upper temperature at least +85 °C for both 0,085  inch diameter and 0,141 inch diameter cable. </td>
	</tr>
	<tr align="center">
		<td>3.3 </td>
		<td>When the equipment or spacecraft qualification temperatures  exceed these values, use the expected maximum operating  temperature as the upper preconditioning temperature. </td>
	</tr>
	<tr align="center">
		<td>4.1 </td>
		<td>Let the cable  return to room temperature. </td>
	</tr>
	<tr align="center">
		<td>4.2 </td>
		<td>Trim off flush any protruding core with the edge of the outer  conductor. </td>
	</tr>
	<tr align="center">
		<td>5 </td>
		<td>Maintain the cable at room temperature for at least 1 hour. </td>
	</tr>
	<tr align="center">
		<td>6.1 </td>
		<td>Submit the cable to a minimum of three complete thermal cycles,  any dielectric protruding from the end of the cable being trimmed  off after each exposure. </td>
	</tr>
	<tr align="center">
		<td>6.2 </td>
		<td>If trimming of dielectric is necessary after the final cycle, perform  a further cycle until a trim‐free cycle is achieved. </td>
	</tr>
	<tr align="center">
		<td>6.3 </td>
		<td>An alternative method is to accurately measure the protrusion  after each exposure. </td>
	</tr>
	<tr align="center">
		<td>6.4 </td>
		<td>When it is recorded that no additional protrusion has taken place,  perform the trimming operation at the end of that final thermal  cycle. </td>
	</tr>
	<tr align="center">
		<td>7 </td>
		<td>After the last thermal cycle, maintain the cable at room  temperature for at least 24 hours before further processing is  undertaken. </td>
	</tr>
</table>

5.3.6

a.

Trimming cable to final length

After the preconditioning, the supplier shall adjust the cable form to the tolerance of the engineering drawing. 

21 ![Im0](images/Im0)

the  supplier  shall  follow  written NOTE 

See also clause 5.1.4.5. 

For  each  stripping  operation, 

instructions. 

NOTE 

This  allows  a  reproducible  process  that  does  not 

damage the conductor surfaces. 

The supplier shall regularly change cutting and milling blades. 

The supplier shall remove burrs. 

5.3.7

a.

b.

c.

d.

5.3.8

a.

ECSS‐Q‐ST‐70‐18C 15 November 2008 b.

c.

The supplier shall cut the cable to size such that when it is assembled it fits with minimum stress. 

The  supplier  shall  perform  cutting  in  conformance  with  the  directions given in clause 5.3.3. 

Stripping the cable ends

The supplier shall use milling tools for stripping the cable ends. 

Inspection of stripped cable ends

For each of the stripped ends, the supplier shall perform a quality control inspection checking the following criteria: 

1.

2.

no metal or foreign particles are on the face of the dielectric. 

the outer conductor contains no burrs or major surface defects and is flush with the dielectric. 

unremoved  dielectric  near  the  centre  conductor  does  not  exceed 0,2 mm. 

3.

b.

The supplier shall specify the length of the wire inner conductor. 

NOTE 

This is necessary since the length is dependent on 

the connector type. 

c.

The  supplier  shall  report  measurements  of  the  external  length  of  the centre conductor as shown in Figure 5‐1 in the logbook for cable prior to assembly with SMA connectors having separate pin contacts. 

22 ECSS‐Q‐ST‐70‐18C 15 November 2008 Remove burrs

Dielectric

Outer conductor

0,2 mm max. unremoved dielectric is acceptable

Figure 5‐1: Dimensional inspection requirements 

Centre conductor- 5.4  Preparation for soldering assembly of semi-rigid

cables

5.4.1  General

a.

The supplier shall establish written procedures which define the various process  steps  including  as  a  minimum  the  requirements  of  clause  5.4.2 and 5.4.3. 

Degolding and pretinning

5.4.2

a.

The  supplier  shall  remove  gold  from  all  surface  areas  to  be  joined  by soldering. 

NOTE 

The  central  contact  pin  can  be  degolded  and 

pretinned with a soldering iron by melting a short 

length of 63 Sn or 60 Sn solder wire within the cup 

to dissolve gold plating; the liquid solder can then 

be wicked‐out with stranded wire. 

b.

c.

The supplier shall degold and pretin the jointing surface of the connector body by fitting the connector to a suitable sized PTFE plug held vertically in a vice. 

The supplier may melt solder wire onto the jointing area and remove it with the aid of a solder wick at least twice until the solidified pretinned surface has a shiny appearance indicating a gold‐free condition. 

d.  With  the  right‐angle  type  of  connector,  the  supplier  shall  degold  and pretin the solder mounting surfaces of the inspection and assembly cover and the corresponding surfaces of the body before assembly. 

The supplier shall pretin the cable’s outer and inner conductors. 

The supplier shall check for possible dielectric protrusion after the cable has cooled down to room temperature. 

e.

f.

23 ![Im0](images/Im0)

![Im1](images/Im1)

ECSS‐Q‐ST‐70‐18C 15 November 2008 g.

h.

i.

j.

k.

l.

The supplier shall trim any protrusion with a scalpel blade. 

The supplier shall check the fit of the pretinned cable in the connector. The  supplier  may  use  activated  fluxes  for  degolding  and  pretinning operations. 

If activated fluxes are used, the supplier shall remove them immediately after the cable has returned to room temperature. 

There shall be no dewetting of the solder on the cable conductor or on the connector. 

The supplier shall clean all surfaces with an approved solvent until they are free from all residual flux and other visible contamination. 

NOTE 1  For solvents refer to clause 5.2.3. 

NOTE 2  The  recommended  degolding  and  pretinning 

temperatures are 250 °C to 280 °C, and 210 °C 

to  260  °C,  respectively,  when  using  solder 

immersion. 

m.

The supplier should perform pretinning just before proceeding with the assembly of the connector on the cable. 

5.4.3

a.

Solder preforms

The supplier shall either  

⎯

⎯

use solder preforms with an internal diameter matching the outer diameter  of  the  coaxial  cable  which  are  available  as  prefluxed continuous rings, or  

prepare  solder  preforms  by  winding  96  Sn  solder  wire  around mandrels  having  the  same  outer  diameter  as  the  coaxial  cable (0,085 or 0,141 inches). 

The supplier shall predetermine the diameter of the wire and the number of turns by trials. 

NOTE 

This is necessary since they depend on the type of 

connector. 

The supplier shall make as many preforms as the number of connectors to be soldered. 

The supplier shall use a scalpel blade to cut solder turns in a direction perpendicular to the wire wrap. 

NOTE 

This is shown in Figure C‐4. 

Before use, the supplier shall clean the preforms with one of the solvent cleaners specified in clause 5.2.3 

b.

c.

d.

e.

24 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 - 5.5  Assembly of connectors to RF coaxial cables

5.5.1

Solder assembly of semi-rigid cables

5.5.1.1

Straight cable-end connector

5.5.1.1.1  Centre contact assembly

a.

b.

c.

d.

e.

f.

g.

The centre contact shall be slid onto the prepared centre conductor of the cable with an easy sliding fit. 

The  centre  conductor  shall  be  visible  across  the  full  diameter  of  the inspection hole. 

The  gap  between  the  rear/end  of  the  centre  contact  and  the  face  of  the dielectric/outer  conductor  shall  be  as  specified 

in  the  assembly instructions for the type of cable‐end connector being used. 

NOTE   An example is given in Figure C‐5. 

The supplier shall solder the centre contact to the centre conductor with the solder specified in clause 5.2.1 and the equipment specified in clause 5.1.4.7. 

After  the  solder  has  solidified  and  cooled,  the  supplier  shall  clean  the joint with one of the solvent cleaners specified in clause 5.2.3. 

After  soldering,  the  supplier  shall  recheck  the  gap  between  the  centre contact and the face of the dielectric/outer conductor. 

The  supplier  shall  inspect  the  solder  connection  against  the  following criteria: 

1.

2.

The inspection hole is filled with solder. 

The  appearance  of  the  solder  joint  satisfies  the  “Acceptance criteria” given in ECSS‐Q‐ST‐70‐08. 

There is no flux or other residues on the cable or the contact. 

There is no solder spillage or flow onto the mating surfaces of the contact. 

3.

4.

5.  Where any solder flow or spillage has occurred on the non‐mating outer surfaces of the contact, it does not cause the effective contact dimensions  to  exceed  those  specified  for  successful  connector assembly. 

5.5.1.1.2  Connector-body/cable assembly

a.

The supplier shall assemble the remaining connector parts to the cable in the following sequence: 

1.

Slide  any  cable  identification  and  other  sleeves  onto  the  cable  in the sequence defined by the cable assembly or layout drawings or specifications. 

25 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 2.

3.

4.

In the case of a straight cable‐end connector, slide the coupling nut onto the cable with the internal thread facing the end of the cable to which the connector is being assembled. 

Slide the solder pre‐form (if used) onto the cable. 

Assemble the body of the connector to the centre contact and the end of the cable.  

The assembly of the body of the connector to the centre contact and the end of the cable should be with an easy sliding fit in both cases (centre contact and pretinned outer conductor fitting). 

At this stage, the supplier shall check the dimensional relationships of the connector body to the centre conductor and the correct full insertion of the cable outer conductor into the connector body. 

The supplier shall solder the outer conductor of the cable to the body of the connector with the solder specified in clause 5.2.1 and the equipment specified in clause 5.1.4.7. 

After  the  solder  has  solidified  and  cooled,  the  supplier  shall  clean  the joint with one of the solvent cleaners specified in clause 5.2.3. 

b.

c.

d.

e.

Inspection of assembly

5.5.1.1.3

a.

After soldering and cleaning, the supplier shall inspect the assembly of the connector to the cable against the following criteria: 

1.

The dimensional relationship of the centre contact and body of the connector is correct. 

The  appearance  of  the  outer  conductor  to  connector  body  solder joint satisfies the visual “Acceptance criteria” given in ECSS‐Q‐ST‐70‐08. 

There is no solder flow or other residues on the cable or connector. There is no solder flow or spillage onto the mating surfaces of the connector  or  onto  the  shoulder  of  the  connector  body  where  it interfaces with the coupling nut. 

Any other solder flow or spillage onto the body of the connector does not affect the operation of the coupling nut. 

There is no solder spillage or other contamination on the coupling nut. 

2.

3.

4.

5.

6.

5.5.1.2  Right angle cable-end connector

a.

The  supplier  shall  assemble  the  connector  to  the  cable‐end conformance with the requirements 5.5.1.2b to 5.5.1.2r. 

After preconditioning as defined in clause 5.3.5, the supplier shall cut the cable‐end to the dimensions necessary for correct fitting to the connector as shown in Figure 5‐2. 

The  supplier  shall  then  degold  and  pretin  the  cable‐end  as  defined  in clause 5.4.2. 

in b.

c.

26 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 The supplier shall prepare the connector by degolding the bifurcated pin, the seating for the cover and the cover. 

The  supplier  shall  insert  the  cable  into  the  connector  and  the  assembly (cable  and  connector)  and  shall  ensure  that  the  angular  relationship between preformed cable and connector is correct. 

The supplier shall inspect the insertion of the cable into the connector via the  inspection/assembly  hole  to  ensure  that  it  is  in  conformance  with Figure 5‐2. 

The supplier shall make first the solder joint between the inner conductor of the cable and the bifurcated pin of the connector with the aid of a fine soldering iron and the solder defined in clause 5.2.1. 

After  the  solder  has  solidified  and  cooled,  the  supplier  shall  clean  the centre‐conductor solder joint and the cavity in the connector body with one of the solvent cleaners specified in clause 5.2.3. 

The supplier shall inspect the solder joint to ensure that full insertion of the  inner  conductor  of  the  cable  into  the  bifurcated  pin  of  the  centre conductor of the connector has taken place. 

NOTE 

See also Figure 5‐2. 

The  supplier  shall  inspect  the  solder  joint  to  ensure  that  the  “Final inspection” requirements of ECSS‐Q‐ST‐70‐08 are satisfied. 

The  supplier  shall  now  solder  the  outer  conductor  of  the  cable  to  the body of the connector with the aid of the solder specified in clause 5.2.1 and the equipment specified in clause 5.1.4.7. 

After  the  solder  has  solidified  and  cooled,  the  supplier  shall  clean  the joint with one of the solvent cleaners specified in clause 5.2.3. 

The  supplier  shall  inspect  the  solder  joints  between  the  cable  and  the connector to ensure that the dimensions of the cable‐connector interface still conform to Figure 5‐2 

The  supplier  shall  inspect  the  solder  joints  between  the  cable  and  the connector  to  ensure  that  the  solder  joints  conform  to  the  “Final inspection” requirements of ECSS‐Q‐ST‐70‐08. 

The  supplier  shall  now  assemble  the  cover  to  the  inspection/assembly hole and the solder joint formed with a soldering iron using the solder specified in clause 5.2.1. 

The supplier shall not add extra solder during this operation. 

NOTE 1  The  joint  relies  on  reflowing  of  the  solder 

the  degolding/pretinning 

applied  during 

operation only. 

NOTE 2  This is to prevent the flow of excess solder into 

the cavity in the connector body. 

After  the  solder  has  solidified  and  cooled,  the  supplier  shall  clean  the joint with one of the solvent cleaners specified in clause 5.2.3. 

The  supplier  shall  inspect  the  cover  solder  joint  with  respect  to  the following criteria: 

d.

e.

f.

g.

h.

i.

j.

k.

l.

m.

n.

o.

p.

q.

r.

27 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 1.

2.

3.

The  solder  joint  extends  around  the  complete  periphery  of  the cover. 

The cover is fully inserted into the shoulder of the hole  

NOTE 

The solder joint conforms to the “Final inspection” requirements of ECSS‐Q‐ST‐70‐08. 

See Figure 5‐2. 

see Note 3

see Note 1

Teflon plug

Copper sheath

PTFE dielectric

Solder joint

Note 1

The cable is inserted into the connector

body so that the outer conductor and

PTFE dielectric are flush with the inner

wall of the connector cavity.

Note 2

With the cable inserted as described in

Note 1, the inner conductor is fully inserted

into the bifurcated end of the inner contact

of the connector.

Note 3

Cover fully inserted and soldered into

shoulder of connector cavity.

Note 4

Captive-type coupling nut (see Figure B-3).

Taking care to avoid stress during cable

mounting.

Detail of cable inner conductor inserted into

bifurcated end of inner contact of connector

Figure 5‐2: Right angle cable‐end connector assembly 

see detailbelow andNote 2

see Note 428 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im10](images/Im10)

![Im11](images/Im11)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im16](images/Im16)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im20](images/Im20)

![Im21](images/Im21)

![Im22](images/Im22)

![Im23](images/Im23)

![Im24](images/Im24)

![Im25](images/Im25)

![Im26](images/Im26)

![Im27](images/Im27)

![Im28](images/Im28)

![Im29](images/Im29)

![Im30](images/Im30)

![Im31](images/Im31)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im35](images/Im35)

![Im36](images/Im36)

![Im37](images/Im37)

![Im38](images/Im38)

![Im39](images/Im39)

![Im40](images/Im40)

![Im41](images/Im41)

![Im42](images/Im42)

![Im43](images/Im43)

![Im44](images/Im44)

![Im45](images/Im45)

![Im46](images/Im46)

![Im47](images/Im47)

![Im48](images/Im48)

![Im49](images/Im49)

![Im50](images/Im50)

![Im51](images/Im51)

![Im52](images/Im52)

![Im53](images/Im53)

![Im54](images/Im54)

![Im55](images/Im55)

![Im56](images/Im56)

![Im57](images/Im57)

![Im58](images/Im58)

![Im59](images/Im59)

![Im60](images/Im60)

![Im61](images/Im61)

![Im62](images/Im62)

![Im63](images/Im63)

![Im64](images/Im64)

![Im65](images/Im65)

![Im66](images/Im66)

![Im67](images/Im67)

![Im68](images/Im68)

![Im69](images/Im69)

![Im70](images/Im70)

![Im71](images/Im71)

![Im72](images/Im72)

![Im73](images/Im73)

![Im74](images/Im74)

![Im75](images/Im75)

![Im76](images/Im76)

![Im77](images/Im77)

![Im78](images/Im78)

![Im79](images/Im79)

![Im80](images/Im80)

![Im81](images/Im81)

![Im82](images/Im82)

![Im83](images/Im83)

![Im84](images/Im84)

![Im85](images/Im85)

![Im86](images/Im86)

![Im87](images/Im87)

![Im88](images/Im88)

![Im89](images/Im89)

![Im90](images/Im90)

![Im91](images/Im91)

![Im92](images/Im92)

![Im93](images/Im93)

![Im94](images/Im94)

![Im95](images/Im95)

![Im96](images/Im96)

![Im97](images/Im97)

![Im98](images/Im98)

![Im99](images/Im99)

![Im100](images/Im100)

![Im101](images/Im101)

![Im102](images/Im102)

![Im103](images/Im103)

![Im104](images/Im104)

![Im105](images/Im105)

![Im106](images/Im106)

![Im107](images/Im107)

![Im108](images/Im108)

![Im109](images/Im109)

![Im110](images/Im110)

![Im111](images/Im111)

![Im112](images/Im112)

![Im113](images/Im113)

![Im114](images/Im114)

![Im115](images/Im115)

![Im116](images/Im116)

![Im117](images/Im117)

![Im118](images/Im118)

![Im119](images/Im119)

![Im120](images/Im120)

![Im121](images/Im121)

![Im122](images/Im122)

![Im123](images/Im123)

![Im124](images/Im124)

![Im125](images/Im125)

![Im126](images/Im126)

![Im127](images/Im127)

![Im128](images/Im128)

![Im129](images/Im129)

![Im130](images/Im130)

![Im131](images/Im131)

![Im132](images/Im132)

![Im133](images/Im133)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

![Im1](images/Im1)

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

![Im145](images/Im145)

![Im146](images/Im146)

![Im147](images/Im147)

![Im148](images/Im148)

![Im149](images/Im149)

![Im150](images/Im150)

![Im151](images/Im151)

![Im152](images/Im152)

![Im153](images/Im153)

![Im154](images/Im154)

![Im155](images/Im155)

![Im156](images/Im156)

![Im157](images/Im157)

![Im158](images/Im158)

![Im159](images/Im159)

![Im160](images/Im160)

![Im161](images/Im161)

![Im162](images/Im162)

![Im163](images/Im163)

![Im164](images/Im164)

![Im1](images/Im1)

![Im165](images/Im165)

ECSS‐Q‐ST‐70‐18C 15 November 2008 5.5.2

Crimp assembly of semi-rigid cables and

other assembly techniques

a.

b.

c.

The  supplier  shall  assemble  the  connectors  and  cables  in  conformance with formally documented and qualified procedures. 

The supplier shall submit these procedures for customer acceptance. 

This  acceptance  can  involve  a  customer  audit  of 

the  facilities  and  procedures  used  for  assembling 

the cables and connectors. 

NOTE 

As  final  stage  of  assembly,  the  supplier  shall  perform  an  inspection covering  dimensional  conformance,  cleanliness,  lack  of  damage  and quality of the assembly techniques used. 

Completed assemblies

5.5.3

a.  When the assembly of the cable and connectors is complete, the supplier shall inspect it to ensure that it is dimensionally correct and clean. 

NOTE 1  “Dimensionally  correct”  means  in  accordance 

with the layout drawing or jig. 

NOTE 2  “Clean”  means 

for  example 

contaminants, particles and burrs. 

free 

from 

b.

The completed and inspected cable assembly shall have protective caps fitted over the connectors. 

c.  Where  for  thermal  or  other  reasons  the  cable  assembly  is  painted,  the paint shall be applied to the outer conductor of the cable only and shall stop at least 5 mm before the joint to the connector (e.g. solder fillet and crimp ferrule). 

NOTE 

Connectors are not painted. 

d.

e.

f.

g.

The paint used shall conform to the “Acceptance limits” requirements of ECSS‐Q‐ST‐70‐02. 

The supplier shall store the cable in a suitable container inside a sealed bag with an inert atmosphere. 

The  storage  packaging  shall  be  adequate  to  protect  the  cable  against deformation, damage and contamination. 

The  supplier  shall  provide  a  suitable  shipping  container  to  give  the necessary  additional  protection  to  the  storage  packaging  for  delivery purposes. 

29 ![Im0](images/Im0)

![Im0](images/Im0)

- 5.6  Mounting of cables

5.6.1

Semi-rigid cables with straight solder-typeconnectors

ECSS‐Q‐ST‐70‐18C 15 November 2008 a.

b.

c.

d.

e.

f.

g.

h.

i.

j.

k.

l.

m.

The  supplier  shall  remove  the  assembled  cable  from  its  storage packaging only when it is needed for immediate mounting. 

After removal from the storage packaging, the supplier shall inspect the cable assembly before mounting. 

The supplier shall ensure that the mating surfaces and screw threads are clean and free from damage. 

The  supplier  shall  retract  the  connector  coupling  nuts  along  the  cable until they are at least 1 cm clear of the connector body. 

The connector inner contacts shall be inserted into the receptacles in the mating halves and slid home so that the mating faces of the bodies of the mating connectors are in contact. 

During this operation, the supplier shall apply no lateral force to correct misalignment of the cable‐end connectors and the mating connectors. Longitudinal force shall only be applied in the case where the connectors mating with the cable are facing each other 

In the case specified in 5.6.1g, the following shall apply: 

1.

limit the force to that required to compress the cable temporarily by the length of one connector inner contact mating face. 

ensure that the cable has generous stress relief bends 

NOTE 

2.

This  allows  the  temporary  compression  to  be,  in 

fact, a minor bending. 

At the completion of the connector mating operation, the cable shall be lying without external force, both cable‐end connectors having the inner contacts  fully  inserted  and  the  cable  lying  in  contact  with  all  support points. 

The  supplier  shall  now  loosely  screw  the  two  connector  coupling  nuts onto the mating connector bodies and tighten to the specified torque, but in the range 0,8 Nm to 1,1 Nm. 

During the nut mating and torquing operations, the supplier shall ensure that  no  rotation  of  the  cable‐end  connector  body  or  of  the  cable  takes place. 

The  supplier  shall  now  secure  the  cable  to  its  support  points  (where applicable). 

The  supplier  shall  reject  any  cable  that  cannot  be 

in conformance with the procedure described in the requirements 5.6.1a to 5.6.1l and shall provide a new cable to the correct dimensions. 

installed 30 ECSS‐Q‐ST‐70‐18C 15 November 2008 5.6.2

Semi-rigid cables with right-angle

connectors

a.

b.

c.

d.

e.

f.

The  supplier  shall  unpack  and  inspect  the  cable  as  defined  in requirements 5.6.1a to 5.6.1c.. 

The  supplier  shall  align  the  cable‐end  connectors  with  their  mating connectors  simultaneously  and  the  centre  contacts  with  their  mating receptacles. 

During this operation, the supplier shall apply no lateral force to correct misalignment of the cable‐end connectors and the mating connectors. The  supplier  shall  screw  the  connector  coupling  nuts  onto  the  mating connector bodies until finger‐tight and shall then unscrew it 1/4 turn. NOTE 

In this condition the cable is resting in contact with 

its support points (where applicable), but is free to 

move  within  the  constraint  given  by  the  1/4  turn 

loosening of the connectors. 

The  supplier  shall  now  finger‐tighten  and  torque  the  connectors  to  the specified figure for the particular connector, but in the range 0,8 Nm to 1,1 Nm). 

During the nut mating and torquing operations, the supplier shall ensure that  no  rotation  of  the  cable‐end  connector  body  or  of  the  cable  takes place. 

5.6.3  Other cable mounting technologies

a.

The mounting requirements for other technologies should be defined by the suppliers of the connectors, cables or assemblies. 

The  supplier  shall  use  everywhere  stress‐free  mounting  of  assembled cables to the interfacing connectors . 

For  each  technology,  the  supplier  shall  respect  the  bend‐radius constraints for the particular type of cable. 

The  supplier  shall  respect  the  cable‐support  requirements  for  the particular type of cable. 

Particularly  in  the  case  of  flexible  cables  having  an  expanded  type  of dielectric, the cable clamps should be of a carefully designed rigid type that enables any forces resulting from vibration to be distributed over a significant length of the cable. 

b.

c.

d.

e.

NOTE 2  This  is  done  to  avoid  local  dielectric  crushing 

electrical 

degradation 

and, 

hence, 

performance. 

of 

31 ![Im0](images/Im0)

![Im0](images/Im0)

- 5.7  Process verification

ECSS‐Q‐ST‐70‐18C 15 November 2008 5.7.1  General

a.

The supplier shall conduct verification tests to establish confidence in the reliability  of  solder‐joint  configurations  and  processing  methods  not shown in this Standard. 

The configuration shall be considered verified if no cracked solder joints or part damage is found after 200 thermal cycles in accordance with the test  conditions  given  in  clause  5.7.2  and  vibration  given  in  clause  5.7.3 and  when 

is  examined  under  15×  minimum magnification. 

The  supplier  shall  ascertain 

the interconnection  by  metallography,  microsections  being  made  in  the longitudinal mid‐plane of the assembly. 

the  absence  of  cracks  within 

the  configuration 

b.

c.

Temperature cycling

5.7.2

a.

The supplier shall perform the temperature cycling in conformance with the requirements given in clause 13.3 of ECSS‐Q‐ST‐70‐08. 

5.7.3

a.

b.

c.

NOTE 

These conditions can be modified by the customer 

to  conform  with  the  particular  environmental 

qualification  conditions  for  the  assembly  being 

verified. 

Vibration

After completion of the temperature cycling, the supplier shall subject the test specimen to vibration. 

The supplier shall derive the test levels, frequencies and durations from the system requirements. 

The severity of the vibration tests shall not be inferior to that shown in the following tables of ECSS‐Q‐ST‐70‐08: 

1.

2.  Minimum severity for sine vibration testing 

3.  Minimum severity for random vibration testing for all applications Sine survey 

except launchers 

4.  Minimum severity for random vibration testing for launchers. 

- 5.8  Quality assurance

Data

5.8.1

a.

The supplier shall retain the quality records for at least ten years, or in accordance with project business agreement requirements. 

32 ECSS‐Q‐ST‐70‐18C 15 November 2008 NOTE 

Example of quality records are logbooks. 

b.

The content of the quality records shall be in conformance with the DRD in Annex A. 

Nonconformance

5.8.2

a.

The supplier shall disposition any nonconformance observed in respect of  the  soldering  process 

in  conformance  with  quality  assurance requirements in ECSS‐Q‐ST‐10‐09. 

If  a  repair  procedure  is  agreed,  the  supplier  shall  perform  it  in conformance with ECSS‐Q‐ST‐70‐28. 

Calibration

5.8.3

a.

The  supplier  shall  calibrate  any  measuring  equipment  to  traceable reference standards.  

The supplier shall record any suspected or actual equipment failure as a project nonconformance report according to ECSS‐Q‐ST‐20. 

NOTE 

This  is  to  ensure  that  previous  results  can  be 

examined to ascertain whether or not re‐inspection 

or retesting is required. 

The  supplier  shall  notify  the  final  customer  of  the  nonconformance details. 

b.

b.

c.

b.

c.

Traceability

5.8.4

a.

The  supplier  shall  maintain  traceability  throughout  the  process  from incoming inspection to final test, including details of test equipment and personnel employed in performing the task. 

5.8.5  Workmanship standards

a.

The supplier shall prepare visual standards consisting of work samples or  visual  aids  that  illustrate  the  quality  characteristics  of  all  soldered connections involved. 

The supplier shall make the visual standards specified in 5.8.5a, available to each operator and inspector. 

The supplier shall include the illustrations presented in Annex B of this Standard, supplemented as necessary, as examples. 

Inspection

5.8.6

a.

During all stages of the process, the inspection points shall be observed. 33 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 5.8.7  Operator and inspector training and

certification

a.

b.

c.

d.

e.

f.

g.

The  supplier  shall  employ  trained  and  competent  personnel  for  all soldering and crimping operations and inspections. 

The  supplier  shall  develop,  maintain  and 

implement  a  training programme  to  provide  for  excellence  of  workmanship  and  personnel skills  and  a  thorough  knowledge  of  the  requirements  detailed  in  this Standard.  

The  supplier  shall  obtain  certificates  for  trained  personnel  performing soldering and crimping operations and inspections. 

This  certification  shall  be  based  upon  objective  evidence  of  quality, resulting from test and inspection of completed joints. 

The supplier shall apply retraining or reassessment of personnel in cases of  repetitive  unacceptable  quality  levels  and  changes  in  soldering  or assembly techniques, parameters or required skills. 

The supplier shall maintain records of the training and certification status of operators and inspection personnel. 

All  training  shall  be  performed  at  a  school  authorized  by  the  final customer. 

34 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Annex A (normative)Logbook – DRD- A.1  DRD identification

### Requirement identification and source document### A.1.1

This DRD is called from ECSS‐Q‐ST‐70‐18, requirement 5.8.1b. 

### Purpose and objective

### A.1.2

The purpose of the logbook is to summarize the quality records. 

- A.2  Expected response

### A.2.1

a.

b.

c.

d.

e.

f.

### Scope and content

The logbook shall contain a copy of the final inspection documentation. The  logbook  shall  refer  to  the  non‐conformance  report  and  corrective actions. 

The logbook shall contain a copy of the inspection and test results with reference to the procedure, drawings, personnel, tools, solders, fluxes and solvents utilized. 

The  logbook  shall  contain  measurements  of  the  external  length  of  the centre conductor. 

The logbook shall contain records of the training and certification status of operators and inspection personnel. 

The logbook shall contain the finding and related corrective action raised during the audit. 

### Special remarks

### A.2.2

None. 

35 ![Im0](images/Im0)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Annex B (normative)Workmanship standards- B.1  Overview

Requirement 5.8.5c requires the inclusion of the illustrations presented in B.2 in the visual standards prepared by the supplier. 

- B.2

Illustrations

Figure B‐1: Photograph showing non‐captive nut and preferred solder fillet 

- Figure B‐2: Microsection through preferred solder fillet, revealing full penetration of 

solder path 

36 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Excessive fillet height

Figure B‐3: Unacceptable solder fillet dimensions 

Insufficient fillet length

37 ![Im0](images/Im0)

![Im1](images/Im1)

ECSS‐Q‐ST‐70‐18C 15 November 2008 Annex C (informative)Graphical information- C.1  Overview

A graphical representation of the typical dimensional inspection requirements can be found in Figure 5‐1. 

A view of the Right angle cable‐end connector assembly is shown in Figure 5‐2. Clauses C.2 to C.6 show additional useful graphical information. 

- C.2  Typical cable cut-off fixture

Clamp screws

Cable

Cable size designators

Figure C‐1: Typical cable cut‐off fixture 

Saw blade in slot

38 ![Im0](images/Im0)

![Im1](images/Im1)

![Im0](images/Im0)

- C.3  Typical cable-forming tool

ECSS‐Q‐ST‐70‐18C 15 November 2008 Roller for bend radii

Cable stop

Figure C‐2: Typical cable‐forming tool 

39 ![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im10](images/Im10)

![Im11](images/Im11)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im16](images/Im16)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im20](images/Im20)

![Im21](images/Im21)

![Im22](images/Im22)

![Im23](images/Im23)

![Im24](images/Im24)

![Im25](images/Im25)

![Im26](images/Im26)

![Im27](images/Im27)

![Im27](images/Im27)

![Im28](images/Im28)

![Im3](images/Im3)

![Im3](images/Im3)

![Im3](images/Im3)

![Im3](images/Im3)

![Im3](images/Im3)

![Im29](images/Im29)

![Im30](images/Im30)

![Im31](images/Im31)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im35](images/Im35)

![Im36](images/Im36)

![Im37](images/Im37)

![Im38](images/Im38)

![Im39](images/Im39)

![Im40](images/Im40)

![Im41](images/Im41)

![Im42](images/Im42)

![Im43](images/Im43)

![Im44](images/Im44)

![Im45](images/Im45)

![Im46](images/Im46)

![Im47](images/Im47)

![Im48](images/Im48)

![Im49](images/Im49)

![Im50](images/Im50)

![Im0](images/Im0)

- C.4  Approved and non-approved straight solder-type

cable-end connectors

Body

Centre contact

Coupling nut

ECSS‐Q‐ST‐70‐18C 15 November 2008 Shoulders on the body and the coupling nut enable

both rotation and retraction of the coupling nut with

respect to the body.

a. Approved connector with non-captive coupling nut

Teflon plug

Copper sheath

PTFE dielectric

Solder joint

Circlip permits rotation of the coupling nut with

respect  to  the  body  only.  Retraction  of  the

coupling nut along the cable is not possible

b. Non-approved connector with captive coupling nut

Figure C‐3: Approved and non‐approved straight solder‐type cable‐end connectors 40 ![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im10](images/Im10)

![Im11](images/Im11)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im16](images/Im16)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im20](images/Im20)

![Im21](images/Im21)

![Im22](images/Im22)

![Im23](images/Im23)

![Im24](images/Im24)

![Im25](images/Im25)

![Im26](images/Im26)

![Im27](images/Im27)

![Im28](images/Im28)

![Im29](images/Im29)

![Im30](images/Im30)

![Im31](images/Im31)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im35](images/Im35)

![Im36](images/Im36)

![Im37](images/Im37)

![Im38](images/Im38)

![Im39](images/Im39)

![Im40](images/Im40)

![Im41](images/Im41)

![Im42](images/Im42)

![Im43](images/Im43)

![Im44](images/Im44)

![Im45](images/Im45)

![Im46](images/Im46)

![Im47](images/Im47)

![Im48](images/Im48)

![Im49](images/Im49)

![Im50](images/Im50)

![Im51](images/Im51)

![Im52](images/Im52)

![Im53](images/Im53)

![Im54](images/Im54)

![Im55](images/Im55)

![Im56](images/Im56)

![Im57](images/Im57)

![Im58](images/Im58)

![Im59](images/Im59)

![Im60](images/Im60)

![Im61](images/Im61)

![Im62](images/Im62)

![Im63](images/Im63)

![Im64](images/Im64)

![Im65](images/Im65)

![Im66](images/Im66)

![Im67](images/Im67)

![Im68](images/Im68)

![Im0](images/Im0)

- C.5  Method of producing solder performs

ECSS‐Q‐ST‐70‐18C 15 November 2008 Figure C‐4: Method of producing solder preforms 

- C.6  Centre contact assembly

Inspection hole

Gap to be as specified in the

connector assembly instructions

Figure C‐5: Centre contact assembly 

 

41 ![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im10](images/Im10)

ECSS‐Q‐ST‐70‐18C 15 November 2008 BibliographyECSS‐S‐ST‐00 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐70‐71 

 

ECSS system – Description, implementation and general requirements 

Space product assurance — Materials, mechanical parts and processes 

Space product assurance — Data for selection of space materials 

42 ![Im0](images/Im0)

