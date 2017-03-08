ECSS-Q-ST-20-10C8 October 2010Space product

assurance

Off-the-shelf items utilization in

space systems

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This Standard has been prepared by the ECSS‐Q‐ST‐20‐10C Working Group, reviewed by the ECSS 

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

-  

-  

-  

- Copyright:  

ESA Requirements and Standards Division 

ESTEC, P.O. Box 299, 

2200 AG Noordwijk 

The Netherlands 

2010© by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐Q‐ST‐20‐10A </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐20‐10B </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐20‐10C  8 October 2010 </td>
		<td>First issue </td>
	</tr>
</table>

3 ECSS‐Q‐ST‐20‐10C 8 October 2010 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................6

- 2 Normative references.............................................................................................7

- 3 Terms, definitions and abbreviated terms............................................................8

- 3.1  Terms from other standards .......................................................................................8

- 3.2  Terms specific to the present standard ......................................................................8

- 3.3  Abbreviated terms ......................................................................................................8

- 4 Principles ..............................................................................................................10

- 4.1  Structure and organization of OTS item selection process ......................................10

4.1.1  Market investigation and OTS items identification......................................104.1.2  OTS item characterization and selection....................................................104.1.3  OTS item procurement and qualification ....................................................11- 5 Requirements........................................................................................................13

- 5.1  Documentation .........................................................................................................13

5.1.1  OTS plan ....................................................................................................135.1.2

Equipment specification..............................................................................135.1.3  OTS item evaluation dossier ......................................................................13- 5.2  Market investigation and OTS item identification .....................................................14

5.2.1  OTS item identification ...............................................................................145.2.2

Preliminary Make-or-Buy decision point.....................................................15- 5.3  OTS characterization................................................................................................16

5.3.1  General.......................................................................................................165.3.2

Product assurance evaluation for OTS item characterization ....................17- 5.4  Performance evaluation - Engineering related activities ..........................................21

Structural and mechanical evaluation.........................................................215.4.1

Thermal evaluation.....................................................................................215.4.2

5.4.3

Electrical.....................................................................................................225.4.4  Maintenance...............................................................................................244 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 - 5.5  Final Make or Buy Decision......................................................................................24

- 5.6  OTS item procurement and qualification ..................................................................24

5.6.1  OTS item procurement ...............................................................................245.6.2  Qualification................................................................................................25- Annex A (normative) OTS plan - DRD....................................................................26

- Annex B (normative) OTS item evaluation dossier - DRD....................................28

- Annex C (informative) ECSS-DRD Informational Reference................................34

- Bibliography.............................................................................................................35

- Figures

- Figure 4-1: OTS items selection process flow........................................................................12

- Figure B-1 : Example of an OTS item status evaluation matrix..............................................31

- Figure B-2 : Example of an comparison of existing OTS item qualification vs project

requirements........................................................................................................32- Figure B-3 : Example of OTS item dedicated data summary .................................................33

 

5 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 ScopeThis  Standard  applies  to  all  parties  involved  at  all  levels  in  the  utilization  of OTS items into space segment hardware and launchers. 

For the purpose of this Standard, Off‐the‐Shelf (OTS) Items are those that, even if  not  necessarily developed  for space applications, can  be  procured  from  the market and utilized in a space system.  

This  Standard  contains  the  requirements  for  the  utilization  of  OTS  Items,  in terms of their selection, characterization and procurement for space system use. This  Standard  considers  complex  OTS  items,  as  for  example:  motherboards, cards,  data  storage  units/items,  optical  equipments,  photo  cameras  and  video units,  LANs,  mechanical/electrical  and  electromechanical  devices,  batteries, sensors, monitoring support units, medical equipments and items, laptops.  This Standard does not cover:  





software OTS, 

re‐use of OTS items already qualified for space applications, 

NOTE   However,  items  not  belonging  to  the  same  lot 

of  the  OTS  item  already  evaluated  using  this 

standard,  can  be  subjected  to  partial  re‐

evaluation  and  re‐qualification  since,  on  the 

commercial market, fast evolution of the design 

occurs. 



Pieces,  parts  and  materials,  such  as  electrical,  electronic  and electromechanical 

fasteners, connectors, fittings, adhesives, insulation, wiring and plumbing. 

thermocouples, 

(EEE)  parts, 

rivets, 

This standard is not specifically addressing the re‐use of OTS items for the same space application for which they were initially qualified. 

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

6 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐E‐ST‐10 

ECSS‐E‐ST‐10‐02 

ECSS‐E‐ST‐10‐12 

ECSS‐E‐ST‐20 

ECSS‐E‐ST‐31 

ECSS‐E‐ST‐32 

ECSS‐E‐ST‐50‐05 

ECSS‐E‐ST‐50‐14 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐60 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐70‐28 

 

ECSS System ‐ Glossary of terms 

Space engineering ‐ System engineering general 

requirements 

Space engineering ‐ Verification 

Space engineering ‐ Methods for the calculation of radiation received and its effects, and a policy for design margins 

Space engineering ‐ Electrical and electronic 

Space engineering ‐ Thermal control general 

requirements 

Space engineering ‐ Structural general requirements Space engineering ‐ Radio frequency and 

modulation 

Space engineering ‐ Spacecraft discrete interfaces Space product assurance ‐ Quality assurance 

Space product assurance ‐ Electrical, electronic and electromechanical (EEE) components 

Space product assurance ‐ Materials, mechanical parts and processes 

Space product assurance ‐ Repair and modification of printed circuit board assemblies for space use 

7 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 apply. 

- 3.2  Terms specific to the present standard

3.2.1  manufacturer

industrial subject that has developed and produced the OTS item and makes it available on the market 

- 3.3  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

 

Abbreviation 

CIDL 

CoC 

DML 

DPL 

DRD 

EEE 

EMC 

EMI 

ESD 

EQSR 

FMEA 

FMECA 

ISO 

Meaning 

configuration item data list 

certificate of conformance 

declared material list 

declared process list 

document requirements definition 

electronic, electrical, electromechanical 

electromagnetic compatibility 

electromagnetic interference 

electrostatic discharge 

equipment qualification status review 

failure modes effects analysis 

failure modes effects and criticality analysis 

International Organization for Standardization 

8 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Abbreviation 

ITAR 

LCC 

LET 

LU 

MTTF 

NIEL 

OTS 

PAD 

PDR 

PCB 

QSL 

RAM 

RFD 

RFW 

SEE 

SEU 

SRR 

STD 

TID 

VCD 

 

Meaning 

International Traffic in Arms Regulation 

life cycle cost 

linear energy transfer 

latch up 

mean time to failure 

non‐ionising energy loss 

off‐the‐shelf  

part approval documents 

preliminary design review 

printed circuit board 

qualification status list 

reliability, availability, maintainability 

request for deviation 

request for waiver 

single level effect 

single event upset 

system requirements review 

standard 

total ionising dose 

verification control document 

9 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Principles- 4.1  Structure and organization of OTS item selection

process

4.1.1  Market investigation and OTS items

identification

When a supplier decides upon the possibility of using OTS items, it is necessary that from the very beginning a preliminary equipment specification be issued. In parallel to this an OTS Plan is prepared. 

At this point, the relevant market survey can be started. 

For each OTS item candidate an evaluation dossier is initiated and all these OTS item  candidates  are  compared  to  the  project  requirements  in  order  to  have  a preliminary make or buy decision. 

As an input to the System SRR, a preliminary OTS make/buy decision milestone identifies  a  restricted  number  (maximum  three)  of  OTS  item  candidates  for which the buy approach is viable. Refer to Figure 4‐1 first sector. 

NOTE 

The  liability  for  introducing  an  OTS  Item  into 

the  Project  remains  always  with  the  design 

authority which is in charge of the make‐or‐buy 

decision. 

4.1.2  OTS item characterization and selection

After  the  System  SRR,  the  updated  equipment  specification  and  OTS  Plan  is used as input to the characterization of each OTS item candidate. 

During the characterization the OTS item candidates are deeply investigated in order to assess their performance and qualification status and to identify any possible modification to be introduced in the OTS item or in the system hosting it and any delta qualification activity. 

The  OTS  item  evaluation  dossiers  are  incrementally  updated  to  reflect  the results of these investigations; at the end the best suitable OTS item candidate is selected,  and  all  related  modifications  and  delta  qualification  activities  are identified thus confirming that the OTS item is qualifiable. 

The  OTS  item  evaluation  dossier  of  the  selected  candidate,  together  with  the equipment specification and the OTS Plan, both updated for PDR, are used to support the final make‐or‐buy decision milestone at the System PDR. 

Refer to Figure 4‐1 second sector. 

10 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 4.1.3  OTS item procurement and qualification

After the final make‐or‐buy decision milestone at the System PDR, if the “Buy“ decision has been taken, the procurement activities can start. 

Since this ECSS is not dealing with the simple re‐procurement of already space qualified OTS Items, two options for procurement can be envisaged: 



OTS  Items  for   q ualification  and  OTS  Items  for  flight  are  procured  at different times; 

Both OTS Items for qualification and for flight are procured at the same time. 



The  supplier  selects  which  option  is  the  best  based  on  the  relevant  Project programmatic needs. 

Regardless of the procurement option selected, the Supplier then performs the necessary  qualification  and  acceptance  related  activities  as  per  the  Project applicable  requirements,  detailed  inside  the  OTS  plan  and  the  equipment specification.  

The  qualification  phase  ends  when  the  selected  OTS  Item  has  reached  the Qualification status requested by the Project.   

The output of this phase is the completed OTS Item Evaluation Dossier that is used to support the OTS Item Qualification status assessment.  

Procurement  of  flight  units,  when  the  flight  hardware  is  procured  separately from the one used for qualification, is then initiated. 

 

11 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Figure 4‐1: OTS items selection process flow 12 ![Im0](images/Im0)

![Im70](images/Im70)

![Im69](images/Im69)

![Im68](images/Im68)

![Im69](images/Im69)

![Im71](images/Im71)

![Im34](images/Im34)

![Im108](images/Im108)

![Im109](images/Im109)

![Im110](images/Im110)

![Im111](images/Im111)

![Im112](images/Im112)

![Im62](images/Im62)

![Im63](images/Im63)

![Im89](images/Im89)

![Im90](images/Im90)

![Im78](images/Im78)

![Im79](images/Im79)

![Im100](images/Im100)

![Im91](images/Im91)

![Im92](images/Im92)

![Im99](images/Im99)

![Im113](images/Im113)

![Im114](images/Im114)

![Im96](images/Im96)

![Im97](images/Im97)

![Im64](images/Im64)

![Im65](images/Im65)

![Im62](images/Im62)

![Im63](images/Im63)

![Im115](images/Im115)

![Im116](images/Im116)

![Im34](images/Im34)

![Im94](images/Im94)

![Im95](images/Im95)

![Im101](images/Im101)

![Im20](images/Im20)

![Im21](images/Im21)

![Im93](images/Im93)

![Im102](images/Im102)

![Im103](images/Im103)

![Im18](images/Im18)

![Im19](images/Im19)

![Im145](images/Im145)

![Im146](images/Im146)

![Im98](images/Im98)

![Im104](images/Im104)

![Im105](images/Im105)

![Im24](images/Im24)

![Im25](images/Im25)

![Im117](images/Im117)

![Im118](images/Im118)

![Im61](images/Im61)

![Im32](images/Im32)

![Im33](images/Im33)

![Im22](images/Im22)

![Im23](images/Im23)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im72](images/Im72)

![Im73](images/Im73)

![Im35](images/Im35)

![Im26](images/Im26)

![Im27](images/Im27)

![Im106](images/Im106)

![Im33](images/Im33)

![Im107](images/Im107)

![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im41](images/Im41)

![Im38](images/Im38)

![Im39](images/Im39)

![Im40](images/Im40)

![Im7](images/Im7)

![Im5](images/Im5)

![Im6](images/Im6)

![Im127](images/Im127)

![Im42](images/Im42)

![Im43](images/Im43)

![Im8](images/Im8)

![Im9](images/Im9)

![Im44](images/Im44)

![Im10](images/Im10)

![Im128](images/Im128)

![Im129](images/Im129)

![Im130](images/Im130)

![Im131](images/Im131)

![Im36](images/Im36)

![Im37](images/Im37)

![Im28](images/Im28)

![Im132](images/Im132)

![Im29](images/Im29)

![Im13](images/Im13)

![Im48](images/Im48)

![Im29](images/Im29)

![Im47](images/Im47)

![Im133](images/Im133)

![Im134](images/Im134)

![Im30](images/Im30)

![Im31](images/Im31)

![Im49](images/Im49)

![Im87](images/Im87)

![Im88](images/Im88)

![Im135](images/Im135)

![Im28](images/Im28)

![Im50](images/Im50)

![Im11](images/Im11)

![Im12](images/Im12)

![Im136](images/Im136)

![Im52](images/Im52)

![Im51](images/Im51)

![Im13](images/Im13)

![Im41](images/Im41)

![Im74](images/Im74)

![Im53](images/Im53)

![Im14](images/Im14)

![Im137](images/Im137)

![Im45](images/Im45)

![Im42](images/Im42)

![Im54](images/Im54)

![Im138](images/Im138)

![Im142](images/Im142)

![Im142](images/Im142)

![Im13](images/Im13)

![Im56](images/Im56)

![Im57](images/Im57)

![Im16](images/Im16)

![Im15](images/Im15)

![Im17](images/Im17)

![Im55](images/Im55)

![Im139](images/Im139)

![Im46](images/Im46)

![Im31](images/Im31)

![Im14](images/Im14)

![Im140](images/Im140)

![Im143](images/Im143)

![Im28](images/Im28)

![Im141](images/Im141)

![Im75](images/Im75)

![Im76](images/Im76)

![Im59](images/Im59)

![Im60](images/Im60)

![Im17](images/Im17)

![Im42](images/Im42)

![Im144](images/Im144)

![Im13](images/Im13)

![Im46](images/Im46)

![Im31](images/Im31)

![Im58](images/Im58)

![Im77](images/Im77)

![Im66](images/Im66)

![Im67](images/Im67)

![Im80](images/Im80)

![Im81](images/Im81)

![Im82](images/Im82)

![Im83](images/Im83)

![Im85](images/Im85)

![Im86](images/Im86)

![Im122](images/Im122)

![Im123](images/Im123)

![Im84](images/Im84)

![Im124](images/Im124)

![Im125](images/Im125)

![Im119](images/Im119)

![Im120](images/Im120)

![Im121](images/Im121)

![Im126](images/Im126)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Requirements- 5.1  Documentation

5.1.1  OTS plan

a.

A dedicated OTS plan shall be established in conformance with the DRD in Annex A. 

NOTE 

The  OTS  plan  describes  the  OTS  item  process 

selection,  characterization  and  qualification 

activities in accordance with the contents of this 

ECSS Standard. The contents is specified in the 

annex DRD. 

b.

c.

The supplier shall submit an OTS plan with the proposal, but not later than the system SRR. 

The OTS item review selection process shall be synchronized with project review planning as per Figure 4‐1. 

5.1.2

a.

Equipment specification

The  supplier  shall  generate  and  maintain  an  equipment  specification with clear allocation of requirements for the OTS item and submit it for approval to the customer. 

The supplier shall submit the preliminary equipment specification at the beginning  of  the  OTS  item  identification  phase  and  deliver  it  to  the customer for review at system SRR. 

The  preliminary  equipment  specification  shall  be  used  as  a  technical reference for the market investigation and OTS item identification. 

The  equipment  specification  shall  be  formalized  after  SRR and  shall  be used during the OTS item characterization and selection. 

The PDR issue of the equipment specification shall be used as an input to the final make‐or‐buy decision. 

b.

c.

d.

e.

5.1.3  OTS item evaluation dossier

a.

For  each  OTS  item  candidate,  an  OTS  item  evaluation  dossier,  in conformance with the DRD in Annex B, shall be established during the market investigation and OTS Item identification. 

13 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 b.

c.

d.

The OTS item evaluation dossiers shall be used to support the trade‐off decision leading to the first preliminary Make/Buy decision point prior to SRR. 

The  OTS  item  evaluation  dossiers  of  the  remaining  candidates  shall  be used  to  support  the  OTS  items  characterization  and  selection  up  to  the final Make/Buy decision point at the system PDR. 

After  the  Buy  decision  has  been  taken,  the  evaluation  dossier  of  the selected  OTS  item  shall  be  maintained  and  updated  to  include  all  the results of the qualification phase. 

- 5.2  Market investigation and OTS item identification

5.2.1  OTS item identification

5.2.1.1  Market investigation

a.

b.

In  order  to  evaluate  the  possible  use  of  OTS  item  the  supplier  shall investigate  the  existence  of  products  already  successfully  qualified  in similar application. 

If as result of project investigation specified in 5.2.1.1a, no space qualified products are found, and the intention to use OTS Items is confirmed, the supplier  shall  extend  the  market  survey  to  high  quality  and  reliability products,  to  narrow  down  the  selection  of  candidate  OTS  items  to qualified manufactures and traceable production processes. 

NOTE 

Exampled  of  high  quality  and  reliability 

products are, for instance, aeronautics, military, 

and nuclear. 

5.2.1.2  OTS item criticality

a.

The supplier shall identify if the OTS item is proposed for use in a safety or mission critical function. 

The supplier shall identify any potential criticality involved with the use of the OTS item. 

b.

5.2.1.3  OTS item data collection

a.

The supplier shall exclude a priori any OTS item whose performance has been previously reported as non‐satisfactory. 

NOTE   When the OTS item is still affected by an active 

alert or equivalent industrial practices. 

b.

c.

d.

The supplier shall propose an OTS item which is designed for aerospace or military application in preference to an OTS item which is not. 

The supplier shall identify any deviation of OTS item candidates from the equipment specification requirements. 

The supplier shall identify all the OTS item functions which can lead to negative effects. 

14 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 e.

f.

g.

h.

The  supplier  shall  verify  with  the  OTS  item  manufacturer  the  design margins, and prefer those determined by test. 

The supplier shall gather all the available qualification data of the OTS item candidates. 

The  supplier  shall  collect  all  the  available  data  relevant  to  the manufacturer in order to evaluate its experience, position and stability in the business, and OTS item commercial business practices, strategies in development, maintenance, distribution of updates, availability of spares, willingness to co‐operate with the supplier. 

The  supplier  shall  collect  all  the  information  to  allow  the  rough estimation of the OTS item cost, taking into account all aspects. 

5.2.2

Preliminary Make-or-Buy decision point

5.2.2.1  Market investigation output

a.

Based on the data collected during the market investigation the supplier shall decide, prior to the system SRR, if to propose a “buy” approach on the basis of the existence of viable OTS items in a minimum number of two. 

b.  When  several  viable  OTS  item  candidates  exist,  the  supplier  shall perform  a  trade‐off  activity  to  reduce  their  number  to  a  maximum  of three. 

Trade-off

5.2.2.2

a.

2.

3.

4.

5.

6.

The  trade‐off  activities  shall  be  based  as  a  minimum  on  the  following criteria: 

1.

item  ability  to  provide  the  required  capabilities  and OTS 

performances and to cope with the system design constraints; 

OTS  item  compliance  with  the  PA  and  Safety  applicable  project requirements; 

OTS item compliance versus the function criticality at system level; OTS item testability; 

OTS item compliance with the interface requirements; 

OTS  item  ability  to  be  procured  and  used  without  special restrictions; 

ITAR, exportability, and copyright; 

Short and long term cost impacts of using the OTS item; 

Technical, cost and schedule risks in using the OTS item; 

7.

8.

9.

10.  Availability of OTS item certification documentation; 

11.

12.  Manufacturer  experience,  position  and  stability  in  the  business, to  place  contractual Proper tracking of configuration changes; 

willingness 

to  cooperate,  possibility 

15 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 the  system  development  and arrangement 

maintenance phase; 

for  supporting 

13.  Manufacturer quality system; 

NOTE 

For  example:  The  OTS  item  manufacturer  can 

demonstrate  a  track  record  for  production, 

Quality control procedures are established. 

14.  Obsolescence possibilities and back‐up solutions; 

15.  OTS item life cycle support. 

NOTE 

- 5.3  OTS characterization

example:  Availability 

For 

spares, 

refurbishment  possibilities,  service  experience 

supporting the successful operation of the OTS 

item, Repair capability. 

of 

5.3.1  General

a.

b.

The  supplier  shall  perform  the  OTS  item  characterization  activity  with respect to the equipment specification ensuring that all the requirements are met. 

In the frame of the OTS item characterization of requirement 5.3.1a, the supplier shall collect in the evaluation dossier the following: 

1.

2.

available users documentation; 

manufacturer data sheet derived requirements and their validation and verification; 

available  qualification  status  versus  preliminary  equipment specification; 

available test data; 

existing anomalies, non conformance reports and  problem reports; potential evolutions; 

3.

4.

5.

6.

NOTE 

example: 

For 

modifications. 

Future 

 manufacturer

 

c.

d.

results of the PA activities evaluation as per clause 5.3.2. 

7.

The  supplier  shall  evaluate  and  agree 

the  system  architecture modifications that allow the usage of the OTS items minimizing the need of OTS item modification. 

The output of the OTS item characterization phase shall be the make‐or‐buy decision. 

16 ![Im0](images/Im0)

![Im0](images/Im0)

5.3.2

ECSS‐Q‐ST‐20‐10C 8 October 2010 Product assurance evaluation for OTS itemcharacterization

5.3.2.1  Dependability

5.3.2.1.1  Criticality

a.

The supplier shall verify the system level RAM analyses to identify if the OTS item is used in critical functions and request customer approval for its application. 

The supplier shall assess the dependability criticality of the OTS item on the basis of the specific application. 

NOTE 

For example (in order of increasing criticality): 

Experiments  or  payload;  satellites;  manned 

modules; launchers; re‐entry vehicles. 

The supplier shall identify the dependability technical risks in satisfying dependability requirements. 

b.

c.

b.

c.

b.

c.

5.3.2.1.2  FMEA / FMECA

a.

The supplier shall analyse the OTS item in the FMECA as a black box. NOTE 

This in order to assess functions and interfaces 

criticalities versus the system requirements. 

b.

The supplier shall get the analysis from the manufacturer when available or consult the available analysis or design files at manufacturer site. 

Item monitors

5.3.2.1.3

a.

The supplier shall collect the information from manufacturer on the OTS item monitoring status. 

The supplier shall provide dedicated interfaces towards the OTS item via ad‐hoc data interface unit. 

The  supplier  shall  co‐ordinate  with  the  first 

compensations for the missing monitoring. 

level  supplier  the 5.3.2.1.4  OTS item operability

a.

The supplier shall verify capability to control the item in all operational conditions to prevent failures and hazards. 

The  supplier  shall  verify  the  capability  to  switch‐off  the  item  in  all conditions, considering also the case of internal item battery provision. The supplier shall verify compatibility of OTS item warm‐up time with respect to system performances. 

5.3.2.1.5

a.

b.

Installation and maintenance

The supplier shall identify OTS item maintenance requirements. 

The  supplier  shall  identify  provision  of  installation  and  maintenance features to prevent failure. 

17 ![Im0](images/Im0)

c.

The  supplier  shall  verify  the  possibility  that  the  manufacturer  can provide spares throughout the project duration. 

ECSS‐Q‐ST‐20‐10C 8 October 2010 Internal redundancy / design for minimum risk

5.3.2.1.6

a.  When  evaluating  the  OTS  item  internal  redundancy,  the  supplier  shall ensure that the project failure tolerance requirements are complied with.  The  supplier  shall  not  use  internally  redundant  OTS  items  without  the availability of the following information:  

1.

2.

The  supplier  shall  provide  all  the  missing  information  on  the  internal redundancy and design to minimum risk on the OTS item. 

the reliability history; 

OTS item internal redundancy management and architecture. 

b.

c.

NOTE 

For example: X‐ray, NDI inspections, proof test, 

and functional test. 

5.3.2.1.7  Reliability figure

a.

The  supplier  shall  provide  an  OTS  item  reliability  figure  to  support system‐level reliability assessments or engineering trade‐offs. 

NOTE 

If  the  reliability  figure  is  not  provided  by  the 

manufacturer,  it  can  be  obtained  e.g.  by  the 

following means: 

  Search  for  data  from 

  experience  from 

previous use;  

  Assess  data  credibility  via  manufacturer 

interview and OTS item evaluation; 

Independent expert judgement; 



  Assess OTS item reliability via prediction; 

  Assess OTS item reliability via similarity; 

  Perform  prediction  (part  count)  when  item 

EEE part list is available. 

5.3.2.1.8  Life

a.

The supplier shall ask the existing field data that justify the operational life claimed by the manufacturer. 

NOTE 

For example: Market feedback for the products, 

worst  case  analysis,  possibility  to  get  the 

internal  parts  activation  energy  characteristics 

and operating temperature. 

b.

c.

d.

The supplier shall assess life data credibility via manufacturer interview and item evaluation. 

The supplier shall assess the need for performing a life test at item level. For requirements 5.3.2.1.8a. to c. the customer approval is required. 

18 ECSS‐Q‐ST‐20‐10C 8 October 2010 5.3.2.1.9  Derating

a.

b.

The supplier shall get data on the actual OTS item derating factors and on  its  proven  heritage,  and  assess  if  OTS  item  derating  is  critical  with respect to the mission requirements. 

In case requirement 5.3.2.1.9a. cannot be met, the supplier shall perform analysis and test on the item. 

NOTE 

The  use  of  board  thermography  is  to  get  a 

rough  estimation  of  thermal  margin  on  the 

most critical components also via identification 

of  temperature  hot  spots,  generate  thermal 

model of PCB and provide simulations. 

5.3.2.2

Safety

5.3.2.2.1  Safety criticality

a.

The OTS item shall conform to the safety requirements of the function in which it is used.  

For safety critical applications any OTS internal redundancy shall not be considered 

b.

5.3.2.2.2  OTS safety data

a.

The  supplier  shall  provide  safety  data  containing  information  on  used materials, mechanical parts, electrical components, and in general all the information necessary to perform the safety analysis. 

NOTE 

Electrical  components  include  internal  energy 

sources like batteries, shatterable materials. 

b.

c.

The  supplier  shall,  for  manned  modules,  ensure  compatibility  between pressure  differential  and  fire  control  requirements  for  all  those  cases where depressurization is a fire control method. 

The  supplier  shall,  in  case  information  cannot  be  obtained  from  the manufacturer, perform the necessary verification activities. 

NOTE 

For  example:  X‐Ray,  NDI  inspections,  and 

proof test. 

5.3.2.3

EEE parts (inside OTS item)

5.3.2.3.1  EEE parts management

a.

b.

c.

Preference shall be given to OTS item candidates for which the employed EEE parts are known. 

The  supplier  shall,  in  case  of  part  list provision,  assess  the  information provided for each EEE part. 

The supplier shall perform inspection on OTS item to evaluate confidence on provided part list or, if no list is provided, identify constituent EEE parts. 

19 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 d.

e.

f.

g.

h.

The  supplier  shall  perform  analysis  or  a  test  campaign  to  assess  the compliance of the whole OTS item with project requirements. 

NOTE 

For example: Total dose radiation test. 

Evaluate the EEE parts with regards to the environmental conditions like temperature, radiation and vacuum. 

The supplier shall perform PCB inspection to identify used parts. 

The supplier shall perform in‐depth inspection to acquire the information necessary to complete the OTS item dossier. 

The supplier shall decide on risk reduction measures in order to solve the EEE parts potential issues. 

NOTE 

For  example:  PCB  coating,  item  segregation, 

exchange of parts, exchange of connectors and 

harness,  introduction  of  epoxy  adhesive  for 

massive  components  of  the  PCB  to  allow  the 

item  surviving  the  acceleration  and  vibration 

test conditions. 

5.3.2.3.2  Part quality

a.

The supplier shall assess part purchase policy applied by the OTS item manufacturer. 

NOTE 

Part  quality  level,  multiple  suppliers  for  each 

part  type,  part  incoming  inspection,  burn  in 

data, and mechanical tests. 

b.

The supplier shall assess manufacturer part handling approach. 

NOTE 

Storage  and 

transport  control,  control  of 

assembly  process  versus  standard  as  function 

of part type characteristics, e.g. plastic parts). 

c.

d.

The  supplier  shall  procure  OTS  items  from  a  recognized  source,  either directly  from  the  manufacturer  of  the  item  or  from  an  authorized procurer of the manufacturer of the item.  

The  supplier  shall  be  able  to  track  the  supply  chain  back  to  the manufacturer of the OTS item. 

5.3.2.4  Mechanical parts, materials and processes

5.3.2.4.1  Mechanical parts and materials management

a.

The supplier shall perform inspection on OTS item. 

NOTE 

This  inspection  aims  at  improving  confidence 

on  provided  part  list  and  when  no  list  is 

provided  to  identify  constituent  materials  and 

mechanical parts. 

b.

The supplier shall perform an analytical assessment or a test campaign to assess the whole item compliance with project requirements. 

20 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 NOTE 

For  example:  Toxicity, 

outgassing tests. 

flammability  and 

c.

The supplier shall decide on risk reduction measures. 

NOTE 

For  example:  Item  segregation,  exchange  of 

parts if materials are non‐compliant, conformal 

coating  or  potting  of  the  PCBs  with  non‐

flammable  compound,  exchange  of  housing, 

exchange of specific flammable parts. 

5.3.2.4.2  Prohibited materials

a.

The supplier shall perform OTS item inspection to identify the presence of any prohibited materials. 

The supplier shall perform lab inspection. 

NOTE 

For  example:  Chemical,  off‐gassing,  out‐

gassing, flammability. 

The supplier shall decide on risk reduction measures in order to solve the prohibited material issue and request customer approval. 

- 5.4  Performance evaluation - Engineering related

activities

b.

c.

b.

c.

d.

b.

5.4.1

a.

Structural and mechanical evaluation

The  supplier  shall  verify  that  the  OTS  item  is  able  to  operate  in  the mechanical environment of the specific application. 

The  supplier  shall  verify  that  the  OTS  item  does  not  generate  any detrimental mechanical effect within the operational environment. 

The supplier shall identify that the modifications to be performed on the OTS item, in order to cope with the anticipated mechanical environment, are justified and their adequacy is demonstrated. 

The supplier shall perform verification of the structural characteristics of the OTS item in accordance with the requirements of ECSS‐E‐ST‐32. 

5.4.2

a.

Thermal evaluation

The supplier shall verify that OTS item is able to operate in the thermal environment of the specific application. 

The  supplier  shall  verify  that  the  OTS  item  thermal  design  is  able  to withstand  those  environmental  factors  encountered  during  all  mission phases and take due account of any possible degradations. 

NOTE 

Causes  for  degradation  can  be  e.g.  wear,  non‐

condensable  gas  build‐up,  mechanical  loads, 

and test environment. 

c.

The supplier shall ensure that any OTS item cooled by natural convection system is modified to a suitable alternative cooling method. 

21 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 d.

e.

f.

The supplier shall analyse and identify any modification to be performed on the OTS item in order to cope with the foreseen thermal environment. The  supplier  shall  consider  the  safety  related  requirements,  like  touch temperature,  flammability  problems  and  ignition  hazards,  as  driving criteria for the OTS item acceptance or exclusion from the early phases of the evaluation process. 

The  supplier  shall  verify  the  OTS  item  thermal  requirements  in accordance with ECSS‐E‐ST‐31. 

5.4.3

Electrical

5.4.3.1  General

a.

The  supplier  shall  verify  that  the  OTS  item  electrical  design  is  able  to operate in accordance with the intended application. 

The  supplier  shall  identify  through  analysis  all  the  modifications  to  be performed on the OTS item in order to cope with the required electrical performances. 

All safety issues shall be considered as driving criteria for the OTS item acceptance or exclusion from the early phases of the evaluation process.  NOTE 

Safety  issues  can  be  high  voltages  or  high 

electrical  powers,  EMC/EMI,  grounding,  and 

radiation. 

d.  Warm‐up time of the OTS items shall be verified to ensure compatibility of the item with the system needs. 

b.

c.

b.

c.

d.

e.

f.

5.4.3.2

a.

Electrical power requirements

The  supplier  shall  verify  the  OTS  item  electrical  requirements  in accordance with ECSS‐E‐ST‐20. 

AC/DC shall not be used in space applications. 

NOTE 

This  constraint  forces  to  remove  or  to  exclude 

the unit power supply and redesign it.  

The OTS item new power supply shall be designed and manufactured by the  supplier  according  to  the  space  environment  and  constraints  in accordance with ECSS‐E‐ST‐20. 

The OTS item, where the already available DC/DC converter input power lines  are  compatible  to  spacecraft  power  bus,  shall  be  verified  or modified  by  the  supplier  according  to  the  space  environment  and constraints as per ECSS‐E‐ST‐20. 

Fuses whose performances are not in accordance with the ECSS‐E‐ST‐20 shall be removed and replaced by the supplier with other fuses or other appropriate devices. 

For  OTS  items  where  the  only  power  source  is  a  rechargeable  or  non‐rechargeable  battery,  the  supplier  shall  investigate  the  possibility  to substitute this power source by a space qualified one. 

22 ![Im0](images/Im0)

![Im0](images/Im0)

g.

In case a substitution of the power source, as per 5.4.3.2f., is not possible, a  DC/DC  converter  shall  be  designed  by  the  supplier  according  to  the space environment and constraints of ECSS‐E‐ST‐20. 

ECSS‐Q‐ST‐20‐10C 8 October 2010 5.4.3.3  Data handling

a.

The supplier proposing the use of an OTS item Data Handling System or of an OTS item as a part of a Data Handling System shall verify its design requirements according to ECSS‐E‐ST‐50‐14. 

The  supplier  proposing  an  OTS  item  interfacing  with  a  Data  Handling System shall verify its interfaces performances according to ECSS‐E‐ST‐50‐14. 

For OTS items with non‐compatible data interfaces, a dedicated interface adapter  shall  be  developed  by  the  supplier,  in  order  to  ensure  the compatibility, according to ECSS‐E‐ST‐50‐14. 

b.

c.

5.4.3.4  Radio frequency transmission and reception

a.

The  supplier  shall  verify  the  OTS  item  RF  compatibility  according  to ECSS‐E‐ST‐50‐05. 

The  supplier  shall  implement  the  modifications  on  the  OTS  item  to comply with the RF requirements of ECSS‐E‐ST‐50‐05. 

b.

5.4.3.5

a.

Electromagnetic compatibility

The  supplier  shall  verify  OTS  item  conformance  to  EMC  requirements according to ECSS‐E‐ST‐20. 

For OTS items that exist in plastic cases only, the viability of upgrading their housing to a metallic one shall be investigated and implemented by the supplier, where feasible. 

b.

b.

c.

d.

5.4.3.6  High energy radiations

a.

The  supplier  shall  verify  OTS  item  conformance  to  project  applicable radiation environment. 

The analysis of OTS item EEE internal parts for the Total Ionizing Dose (TID),  Non‐Ionising  Energy  Loss  Fluence  (NIEL)  and  the  Single  Event Effect  (SEE)  due  to  the  heavy  ions  and  high  energy  protons  shall  be performed by the supplier in accordance with ECSS‐E‐ST‐10‐12.  

The  supplier  shall  perform  a  dedicated  analysis  to  evaluate  the criticalities  from  Single  Event  Upset  (SEU)  and  Latch  Up  (LU)  and provide adequate preventive or corrective actions. 

For  OTS  items  not  specifically  characterized  for  space  applications  in terms  of  radiation  behaviour,  a  dedicated  test  campaign  shall  be conducted by the supplier to measure the sensitivity of these equipment in terms of at least Total Ionising Dose with Gamma rays, Single Event Effects with Protons beams. 

23 ![Im0](images/Im0)

5.4.3.7

a.

b.

c.

EEE quality and constraints

ECSS‐Q‐ST‐20‐10C 8 October 2010 The  supplier  shall  identify  any  prohibited  parts  according  to  project requirements and take corrective actions in accordance with ECSS‐Q‐ST‐60. 

Supplier shall ensure that assembled printed circuit boards are repaired or modified according to ECSS‐Q‐ST‐70‐28. 

The supplier shall identify any materials, mechanical parts and processes prohibited  by  project  requirements  and  take  corrective  actions  in accordance with ECSS‐Q‐ST‐70. 

5.4.4  Maintenance

a.

The supplier shall identify any maintenance activity specific for the OTS item. 

- 5.5  Final Make or Buy Decision

a.

b.

c.

Based  on  the  data  collected  and  on  the  results  achieved  during  the characterization  phase,  the  supplier  shall  decide  if  to  propose  the  final buy approach, not later than the system PDR. 

The  OTS  Item  qualification  capability  shall  be  demonstrated  by  the supplier together with conformance with the EQSR approach. 

At  the  system  PDR,  the  supplier  shall  submit  to  the  customer  for concurrence, the final OTS‐Item make‐or‐buy decision. 

- 5.6  OTS item procurement and qualification

5.6.1  OTS item procurement

5.6.1.1  OTS item procurement documentation

a.

The supplier shall identify the procurement document and freeze it in the OTS item evaluation dossier. 

NOTE   A  procurement  document  can  be an  OTS  item 

dedicated  specification  or  the  manufacturer 

bulletin. 

b.

From the data of the OTS item evaluation dossier a final OTS item report shall be issued by the OTS item supplier and approved by the first level supplier. 

5.6.1.2  Batches

a.

The supplier shall purchase all OTS items from a single lot. 

NOTE 

Single  lot  purchase  is  done  to  minimize  the 

risks  deriving  from  OTS  items  developed  at 

different times and with differences in terms of 

materials,  internal  parts  (including  EEE  parts) 

24 ECSS‐Q‐ST‐20‐10C 8 October 2010 and  with  differences 

process. 

in 

the  development 

b.

c.

d.

The  supplier  shall  verify  that  lot  variances  do  not  impact  the  data contained in the OTS item evaluation dossier. 

The supplier shall check that the number of OTS items purchased in the same lot conform to the project needs and with the obsolescence strategy of the manufacturer. 

The supplier shall make sure that the number of the OTS item purchased include spare parts and maintenance needs. 

5.6.1.3  Configuration control of modified OTS item

a.

Supplier  shall  ensure  that,  in  case  the  final  OTS  item  candidate  needs modifications  to  meet  the  project  requirements,  these  modifications  are kept  under  configuration  control  by  the  configuration  control  methods applicable to the project. 

5.6.1.4  Quality assurance

a.

The supplier shall verify that the procurement documentation of the OTS items are in accordance with the ECSS‐Q‐ST‐20. 

5.6.2  Qualification

a.

implementation 

and approach,  methodology, 

The  principles, 

documentation requirements of ECSS‐E‐ST‐10 shall apply. 

The  fundamental  concepts  of  the  verification  process,  the  criteria  for defining the verification strategy and the rules for the implementation of the  verification  program,  established  within  ECSS‐E‐ST‐10‐02  shall  be followed. 

The  supplier  shall  derive  the  OTS  item  qualification  program  from  the equipment specification. 

The supplier shall use the approved OTS item evaluation dossier and the relevant OTS item reports as an input to the qualification program. 

b.

c.

d.

25 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 Annex A (normative)OTS plan - DRD- A.1  DRD identification

### Requirement identification and source document### A.1.1

This DRD is called from requirement ECSS‐Q‐ST‐20‐10, requirement 5.1.1a. 

### Purpose and objective

### A.1.2

The  OTS  plan  defines  the  OTS  item  process  selection,  characterization  and qualification activities. 

- A.2  Expected response

### A.2.1

### Scope and contents

<1>

a.

<2>

a.

<3>

a.

Introduction 

The  OTS  plan  shall  contain  a  description  of  the  purpose,  objective, content and the reason prompting its preparation. 

Applicable and reference documents 

The  OTS  plan  shall  list  the  applicable  and  reference  documents  in support to the generation of the document. 

Definitions and abbreviations 

The  OTS  plan  shall  list  the  applicable  dictionary  or  glossary  and  the meaning of specific terms or abbreviations utilized in the document with the relevant meaning. 

26 ![Im0](images/Im0)

![Im0](images/Im0)

<4>

a.

<5>

a.

<6>

a.

<7>

a.

<8>

a.

ECSS‐Q‐ST‐20‐10C 8 October 2010 Responsibility and organization 

The  OTS  plan  shall  describe  the  project  team  organization  and  the responsibilities for the activities and documentation. 

OTS item selection  

The OTS plan shall describe the market survey, the data evaluation and the  selection  activities  based  on  the  requirements  of  ECSS‐Q‐ST‐20‐10 clause 5.2 and 5.3. 

OTS item characterization  

The  OTS  plan  shall  present  the  OTS  item  characterization  activities  for selection of the final candidate based on the requirements of ECSS‐Q‐ST‐20‐10 clause 5.3. 

OTS item performance evaluation 

The  OTS  plan  shall  present  the  OTS  item  performance  evaluation activities for selection of the final candidate based on the requirements of ECSS‐Q‐ST‐20‐10 clause 5.3. 

OTS item procurement and qualification 

The OTS plan shall describe the: 

1.

procurement  activities  once  the  project  has  completed  the  OTS item selection and characterization processes; 

activities  for  the  configuration  control  to  track  any  OTS  item modification; 

description  of  the  procurement  verification  approach  and  its implementation; 

product assurance approach and its implementation; 

batch policy; 

qualification  activities  and  logic  according  to  ECSS‐E‐ST‐10,  and ECSS‐E‐ST‐10‐02. 

2.

3.

4.

5.

6.

### Special remarks

### A.2.2

None. 

27 ECSS‐Q‐ST‐20‐10C 8 October 2010 Annex B (normative)OTS item evaluation dossier - DRD- B.1  DRD identification

### B.1.1

### Requirement identification and source

### document

This DRD is called from requirement ECSS‐Q‐ST‐20‐10, requirement 5.1.3a. 

### Purpose and objective

### B.1.2

The OTS item evaluation dossier provides a detailed incremental overview of the  OTS  item  since  the  initial  selection  up  to  the  OTS  item  qualification  and approval for its use in the specific project. 

In order to avoid loss of information or data, at the end of the characterization phase,  when  the  final  candidate  has  been  selected,  its  evaluation  dossier  is formalized in a project document (report). 

- B.2  Expected response

### Scope and contents

### B.2.1

a.

The OTS item evaluation dossier contents shall contain as a minimum: Trade offs results. 

1.

2.  Manufacturer  datasheets,  documentation  and  information  data from / on the manufacturer, waivers, historical data. 

Programmatic data. 

3.

NOTE 

For  example:  Cost,  procurement  time,  export 

limitation. 

28 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 4.

5.

6.

7.

Compliance Matrix to the Equipment specification. 

OTS item environmental characteristics. 

NOTE 

For example: Thermal, mechanical, EMI, EMC.  

OTS  Item  status  evaluation  matrix  (refer  to  provided  example  in point B.2.2). 

RAMS information. 

NOTE 

For example: FMEA, Safety assessment, internal 

redundancy, reliability figures. 

Safety Data Sheets and or Safety technical data. 

Risk assessment. 

PMP and EEE information and result of in‐depth inspection. 

8.

9.

10.

11.  Modifications  needed  and  modifications  implemented  including PADs for self procured EEE parts. 

Procurement document. 

12.

13.  Operation and logistic information. 

NOTE 

For example: Life, storage, handling instruction, 

user’s manual. 

14.  All  the  data/information  /  analyses  /  test  results  obtained  during the characterization phase. 

15.  All the data / information / analyses / test results obtained during 16.

the qualification phase, including any non conformance report. European  CE  marking  or  equivalent  internationally  recognized marking. 

### Special remarks

### B.2.2

a.

The OTS item evaluation dossier shall be a living document in a form of a folder(s), established for each OTS item candidate. 

### Examples of OTS Item Status Evaluation Matrix### B.2.3

 

29 ![Im0](images/Im0)

ECSS‐Q‐ST‐20‐10C 8 October 2010 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td colspan=5>OTS item status evaluation matrix </td>
	</tr>
	<tr align="center">
		<td colspan=2>Product name :  </td>
		<td colspan=3>Supplier :  </td>
	</tr>
	<tr align="center">
		<td colspan=2>Part number (P/N) :  </td>
		<td colspan=3>Country :  </td>
	</tr>
	<tr align="center">
		<td>Documentation </td>
		<td colspan=2>OTS Item Original Documentation  Title /Reference/Issue/Revision </td>
		<td>Project Documentation  Title /Reference/Issue/Revision </td>
		<td>Difference </td>
	</tr>
	<tr align="center">
		<td>Equipment specification  </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Configuration item data list (CIDL) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Assembly Drawing </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Interface Data sheet (IDS) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Interface Control Documents (including  drawings) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Declared processes list (DPL) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Declared materials list (DML) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Declared Mechanical parts list  </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Part Approval Documents (PAD) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>EEE part list  (EEE PL) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Cleanliness data </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>User Manual </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Qualification Status List (QSL) </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Mechanical Analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Thermal analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Radiation analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>EMC/ESD analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Reliability analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>FMECA </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Safety analysis/safety datasheets/safety  procedures </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Derating analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Parts Stress Analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Worst case Analysis </td>
		<td colspan=2> </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

30 ECSS‐Q‐ST‐20‐10C 8 October 2010 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Verification Control Document </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Test Reports </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Inspection Reports </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Certificate of Conformance (CoC) w.r.t.  International Standards </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>NCRs/RFWs </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Acceptance data package </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

31 ECSS‐Q‐ST‐20‐10C 8 October 2010 ![Im0](images/Im0)

