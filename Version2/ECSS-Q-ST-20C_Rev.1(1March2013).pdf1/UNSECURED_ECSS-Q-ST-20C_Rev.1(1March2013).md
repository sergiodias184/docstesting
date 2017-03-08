ECSS-Q-ST-20C Rev.11 March 2013Space product

assurance

Quality assurance

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013- Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry

- associations for the purpose of developing and maintaining common standards. Requirements in this

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be

- applied where they are effective, and for the structures and methods to evolve as necessary without

- rewriting the standards.

- This  Standard  has  been  prepared  by  the  ECSS-Q-ST-20  Working  Group,  reviewed  by  the  ECSS

- Executive Secretariat and approved by the ECSS Technical Authority.

- Disclaimer

- ECSS does not provide any warranty whatsoever, whether expressed, implied, or statutory, including,

- but not limited to, any warranty of merchantability or fitness for a particular purpose or any warranty

- that  the  contents  of  the  item  are  error-free.  In  no  respect  shall  ECSS  incur  any  liability  for  any

- damages, including, but not limited to, direct, indirect, special, or consequential damages arising out

- of, resulting from, or in any way connected to the use of this Standard, whether or not based upon

- warranty, business agreement, tort, or otherwise; whether or not injury was sustained by persons or

- property or otherwise; and whether or not loss was sustained from, or arose out of, the results of, the

- item, or any services that may be provided by ECSS.

- Published by:   ESA Requirements and Standards Division

- Copyright:

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2013© by the European Space Agency for the members of ECSS

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS-Q-20A 19 April 1996</td>
		<td>First issue</td>
	</tr>
	<tr align="center">
		<td>ECSS-Q-20-B 8 March 2002</td>
		<td>Second issue</td>
	</tr>
	<tr align="center">
		<td>ECSS-Q-ST-20C 15 November 2008</td>
		<td>Third issue Major changes of this version of ECSS-Q-ST-20 with regard to the previous version are: •  Transfer of PA related requirements to the newly established ECSS-Q- ST-10, Product assurance management; •  Adaptation of structure of document and formulation of requirements to be consistent with ECSS drafting rules. •  Deletion of ECSS-Q-20B or transfer to ECSS-Q-ST-10C: o  Clause "4.6 Quality assurance programme audits" deleted; transferred to Q-ST-10 clause "5.1.4 PA audits"; o  Clause "4.7 QA role in configuration management" deleted; transferred to Q-ST-10 clause "5.6 PA role in configuration management"; o  Clause "4.8 Critical items control" deleted; transferred to Q-ST-10 clause "5.2 Critical items control and PA interfaces to project risk management"; o  Clause "11 Operations" deleted. •  New requirements: o  Annex A of Q-20B: Ground Support Equipment moved to clause 5.8 of this document.</td>
	</tr>
	<tr align="center">
		<td>ECSS-Q-ST-20C Rev.1 1 March 2013</td>
		<td>Third issue Revision 1 Major changes of this version with regard to the previous version are: Implementation of Change Requests • •  Addition of applicable terms from ECSS-S-ST-00-01 in 3.1 •  Abbreviated terms for “CoC, NCR, VCB and VCD” added •  Clause 5.3.2.4 “Qualification process” aligned with ECSS-E-ST-10-02 •  Addition of the “Pre-Tailoring matrix” in Clause 6 •  Annex D abbreviated title of DRD changed from “DoC” to “CoC” •  Addition of Annex J “ECSS-Q-ST-20 applicability according to programme phases”</td>
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td></td>
		<td> Detailed changes: Addition of definitions in 3.2 for terms: - Inspectability -  producibility - repeatability testability -  Added requirements: 5.2.7.2f; 5.3.2.4.1d; 5.5.8j; 5.5.11a-b; A.2<9>a; D.2.1a.8  Modified requirements: 5.1.2b and c; 5.2.4a-f(replacement of term “stamp” by “acceptance authority media”); 5.2.7.2a. (NOTE added); 5.2.7.2b.4 (typo);.5.3.1.1a (NOTE removed and text used for definition 3.2.3); 5.3.1.2a (NOTE removed and text used for definition 3.2.4); 5.3.1.3a (NOTE removed and text used for definitions 3.2.2 and 3.2.5); 5.3.2.4.1a-c (NOTES added); 5.4.1.2a.1and 3 (NOTE moved after last item of list); 5.4.3b; 5.4.3c; 5.4.3c.1 and 4 (NOTES moved after last item of list); 5.5.1d; 5.5.1e.3 and 4 (NOTES moved after last item of list); 5.5.2a; 5.5.2b.3 and 5; 5.5.3.1b NOTE; 5.5.3.2a.1 (NOTE moved after last item of list); 5.5.3.2a.2; 5.5.5c (NOTE deleted); 5.5.6.1d; 5.5.8e; 5.5.9.1d (NOTE added); 5.5.9.2a-b; 5.6.3.1a; 5.6.4a,c-e; 5.6.5a; 5.7.1b; 5.7.3a (NOTE deleted); 5.7.3g (NOTE added); Clauses 5.8.4 to 5.8.7 merged into 5.8.4; clause 5.8.4 renamed to “Acceptance and delivery”; 5.8.5a (now: req. 5.8.4.2a) modified and NOTE deleted; A.2<3>a; B.2.1a.7; B.2.1a.17 (NOTE 2 added);  Moved requirements: 5.8.1.1.1a-c moved to 5.8.1a-c; clause 5.8.4 renamed to “Acceptance and delivery”; 5.8.5a-c moved to 5.8.4.2a-c; 5.8.6a-b moved to 5.8.4.3a-b; 5.8.7a moved to 5.8.4.4a.  Deleted requirements: 5.2.4g; </td>
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013Table of contents- Change log ................................................................................................................. 3

- 1 Scope ....................................................................................................................... 8

- 2 Normative references ............................................................................................. 9

- 3 Terms and definitions .......................................................................................... 10

- 3.1  Terms from other standards .................................................................................... 10

- 3.2  Terms specific to the present standard ................................................................... 10

- 3.3  Abbreviated terms and symbols .............................................................................. 12

- 3.4  Nomenclature ......................................................................................................... 13

- 4 Quality assurance principles ............................................................................... 14

- 4.1  QA management principles ..................................................................................... 14

- 4.2  General principles ................................................................................................... 14

- 4.3  Design and verification principles ............................................................................ 14

- 4.4  Procurement principles ........................................................................................... 15

- 4.5  Manufacturing, assembly and integration principles ................................................ 15

- 4.6  Testing principles .................................................................................................... 15

- 4.7  Acceptance and delivery principles ......................................................................... 15

- 4.8  GSE principles ........................................................................................................ 15

- 5 Quality assurance requirements ......................................................................... 16

- 5.1  QA management requirements ............................................................................... 16

5.1.1  Quality assurance plan .............................................................................. 165.1.2

Personnel training and certification ........................................................... 16- 5.2  QA general requirements ........................................................................................ 16

5.2.1  Critical-items control .................................................................................. 165.2.2  Nonconformance control system ............................................................... 165.2.3  Management of alerts ............................................................................... 175.2.4

Acceptance authority media ...................................................................... 175.2.5

Traceability ............................................................................................... 175.2.6  Metrology and calibration .......................................................................... 18![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 20135.2.7  Handling, storage and preservation ........................................................... 19Statistical quality control and analysis ....................................................... 205.2.8

- 5.3  QA requirements for design and verification ........................................................... 21

5.3.1  Design rules .............................................................................................. 215.3.2

Verification ................................................................................................ 21- 5.4  QA requirements for procurement ........................................................................... 24

5.4.1

Selection of procurement sources ............................................................. 245.4.2

Procurement documents ........................................................................... 255.4.3

Surveillance of procurement sources ........................................................ 255.4.4  Receiving inspection ................................................................................. 26- 5.5  QA requirements for manufacturing, assembly and integration ............................... 28

5.5.1

Planning of manufacturing, assembly and integration activities and

associated documents .............................................................................. 285.5.2  Manufacturing readiness reviews .............................................................. 295.5.3  Control of processes ................................................................................. 295.5.4  Workmanship standards............................................................................ 305.5.5  Materials and parts control ........................................................................ 305.5.6

Equipment control ..................................................................................... 315.5.7  Cleanliness and contamination control ...................................................... 315.5.8

Inspection ................................................................................................. 325.5.9

Specific requirements for assembly and integration .................................. 345.5.10  Manufacturing, assembly and integration records ..................................... 345.5.11  Electrostatic discharge control (ESD) ........................................................ 34- 5.6  QA requirements for testing .................................................................................... 35

Test facilities ............................................................................................. 35Test equipment ......................................................................................... 35Test documentation ................................................................................... 35Test performance monitoring .................................................................... 35Test reviews .............................................................................................. 36- 5.7  QA requirements for acceptance and delivery ........................................................ 36

Acceptance and delivery process .............................................................. 365.7.1

5.7.2

End item data package ............................................................................. 375.7.3  Delivery review board (DRB) ..................................................................... 375.7.4

Preparation for delivery ............................................................................. 385.7.5  Delivery ..................................................................................................... 38- 5.8  QA requirements for ground support equipment (GSE) .......................................... 38

5.8.1  Design, development and verification ........................................................ 385.8.2  Configuration control ................................................................................. 395.6.1

5.6.2

5.6.3

5.6.4

5.6.5

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013Production ................................................................................................. 395.8.3

Acceptance and delivery ........................................................................... 395.8.4

<<deleted, requirements moved to 5.8.4.2>> ............................................ 405.8.5

<<deleted, requirements moved to 5.8.4.3>> ............................................ 405.8.6

5.8.7

<<deleted, requirements moved to 5.8.4.4>> ............................................ 405.8.8  General requirements ............................................................................... 415.8.9  Maintenance ............................................................................................. 41- 6 Pre-tailoring matrix per space product types .................................................... 42

- Annex A (normative) QA plan - DRD ...................................................................... 51

- Annex B (normative) End item data package (EIDP) - DRD ................................. 53

- Annex C (normative) Logbook - DRD .................................................................... 55

- Annex D (normative) Certificate of conformity (CoC) - DRD ................................ 57

- Annex E (informative) Example of a logbook cover page .................................... 59

- Annex F (informative) Example of EIDP cover page ............................................ 60

- Annex G (informative) Example of EIDP contents ................................................ 61

- Annex H (informative) Example of Certificate of conformity ............................... 62

- Annex I (informative) QA document requirement list ........................................... 63

- Annex J (informative) ECSS-Q-ST-20 applicability according to

- programme phases ............................................................................................. 64

- Bibliography ............................................................................................................. 67

- Tables

- Table I-1 : QA document requirement list with respect to milestones .................................... 63

- Table J-1 : ECSS-Q-ST-20C Requirements per programme phase ...................................... 64

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013ScopeThis  Standard  defines  the  quality  assurance  (QA)  requirements  for  theestablishment  and  implementation  of  a  Quality  Assurance  programme  forproducts of space projects.

Discipline  related  qualification  activities  are  complemented  in  standardsspecific to those disciplines (e.g. ECSS-E-ST-32-01 for fracture control).

For software quality assurance, the software product assurance standard, ECSS-Q-ST-80 is applicable.

This Standard is applicable to all space projects.

This standard may be tailored for the specific characteristic and constrains of a![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013Normative referencesThe  following  normative  documents  contain  provisions  which,  throughreference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  datedreferences, subsequent amendments to, or revision of any of these publicationsdo not apply. However, parties to agreements based on this ECSS Standard areencouraged to investigate the possibility of applying the more recent editions ofthe  normative  documents  indicated  below.  For  undated  references,  the  latestedition of the publication referred to applies.

ECSS-S-ST-00-01

ECSS-Q-ST-10

ECSS system - Glossary of terms

Space product assurance - Product assurance

management

Space product assurance - Critical-item control

Space product assurance - Nonconformance controlECSS-Q-ST-10-04

ECSS-Q-ST-10-09

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

ECSS-Q-ST-20C Rev.11 March 2013Terms and definitions- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS-ST-00-01apply, in particular for the following terms:

nonconformance

process

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
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

- 3.2  Terms specific to the present standard

ground support equipment (GSE)

3.2.1

optical,  mechanical,  fluidic,  electrical  and  software  support  equipment  orsystems  used  for  example  for  calibration,  measurements,  testing,  simulation,<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

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
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.1![Im0](images/Im0)

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
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

Abbreviation  Meaning

AIV

BB

assembly, integration, verification

breadboard

<table align="center">
</table>

DRB

delivery review board

NOTE:  DRB is synonymous to “Acceptance Review

DRD

EEE

EGSE

EIDP

FGSE

FM

GSE

MGSE

Board” (ARB) in ECSS-M-ST-10

document requirements definition

electrical, electronic, electromechanical

electrical ground support equipment

end item data package

fluidic ground support equipment

flight model

ground support equipment

mechanical ground support equipment

<table align="center">
</table>

NRB

OGSE

PA

PM

QA

QM

nonconformance review board

optical ground support equipment

product assurance

project manager

quality assurance

qualification model

ECSS-Q-ST-20C Rev.11 March 2013RFD

RFW

TRB

request for deviation

request for waiver

test review board

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

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
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013Quality assurance principles- 4.1  QA management principles

The prime objective of Quality Assurance (QA) management is to ensure that aQA programme for projects covering  mission definition, design, developmentand production of space systems is established, maintained and implemented.All  QA  requirements  are  specified  through  definition  and  implementation  ofadequate methods and procedures.

Personnel whose performance determines or affects product quality are trainedand certified in accordance with project needs.

- 4.2  General principles

The implementation of the following phase-independent activities is ensured bythe QA function throughout the lead-time of projects:

•

•

•

•

•

•

•

•

critical-items control

nonconformance control

alert management

stamp control

traceability

metrology and calibration

handling, storage and preservation

statistical quality control (if required by the business agreement).

- 4.3  Design and verification principles

The objective of the QA function is to ensure that:

a.

a set of design rules and methods has been set up and is consistent withthe project techniques and technologies;

b.  methods, procedures and tools have been defined and are implementedin  order  to  prove  that  each  applicable  requirement  is  verified  throughone or more of the following methods: analysis, inspection, test, reviewof design, audits;

the  design  is  producible  and  repeatable  and  that  the  resulting  productcan be verified and operated within the required operating limits;

c.

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013d.

e.

f.

design and verification activities are planned in a consistent and logicalway;

the  verification  process  is  complete  and  includes  clear  test,  test  modeland verification logic;

a defined qualification approach is implemented to demonstrate that theitem performs satisfactorily in the intended environment.

- 4.4  Procurement principles

including  selection  of  procurement  sources,All  procurement  activities

procurement  documents,  procurement  source  surveillance  and  receivinginspection are controlled to ensure that all procured items and services conformto requirements.

- 4.5  Manufacturing, assembly and integration principles

All  manufacturing,  assembly  and  integration  operations  are  planned  andperformed  in  coordination  with  inspections  and  tests  to  ensure  that  thedeliverables are built, assembled and integrated to the approved configurationbaseline.

Special processes and new technologies are identified in a timely manner andadequate  evaluation  or  qualification  activities  should  be  implemented  in  linewith the overall schedule.

- 4.6  Testing principles

Test  facilities  and  test  equipment  are  validated  prior  to  their  use  to  ensureconformance to project requirements.

All  tests  are  performed  in  accordance  with  documented  and  releasedprocedures and results are comprehensively recorded.

- 4.7  Acceptance and delivery principles

The  objective  is  to  ensure  that  an  acceptance  and  delivery  process  isimplemented  which  allows  demonstrating  and  documenting  the  conformanceof the delivered item.

- 4.8  GSE principles

Design,  production,  delivery  and  maintenance  requirements  for  GSE  aredefined  and  implemented  allowing  for  testability,  availability,  safety,  lifeduration, operability and ability to interface as necessary with space segment ina safe way.

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013Quality assurance requirements- 5.1  QA management requirements

5.1.1  Quality assurance plan

a.

The  supplier  shall  prepare,  maintain  and  implement  a  QA  plan  inconformance with the DRD in Annex A.

The QA plan shall be submitted to the customer for approval.

b.

NOTE

Information on the schedule for delivery of the

QA plan is given in Annex I.

Personnel training and certification

The  supplier  shall  establish  a  documented  training  programme  for  the5.1.2

a.

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

The supplier shall maintain records of the training.

- 5.2  QA general requirements

d.

5.2.1

a.

5.2.2

a.

Critical-items control

The supplier shall implement Critical-items control in conformance withECSS-Q-ST-10-04.

Nonconformance control system

The  supplier  shall  implement  a  nonconformance  control  system  inconformance with ECSS-Q-ST-10-09.

ECSS-Q-ST-20C Rev.11 March 20135.2.3  Management of alerts

a.

The  supplier  shall  manage  alerts  in  conformance  with  ECSS-Q-ST-10,![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

1.

2.

signify the completion of operations and processes, and

indicate

incominginspection  performance  at  source  and

inspection,  in  process  inspection  and  tests,  final  inspection,  end<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

<table align="center">
</table>

<table align="center">
</table>

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

b.

c.

d.

e.

5.2.5

a.

Traceability

The  supplier  shall  ensure

that  a  bidirectional  and  unequivocalrelationship  between  parts,  materials  or  products  and  associateddocumentation or records is established and maintained.

The  supplier  shall  be  capable  to  trace  data,  personnel  and  equipmentrelated  to  procurement,  manufacturing,  inspection,  test,  assembly,integration and operations activities.

The supplier shall be capable to trace backward the locations of materials,parts, sub-assemblies.

The supplier shall be capable to trace forward the locations of materialsfrom raw stock.

The supplier shall establish controls to ensure that:

1.

2.

identification numbers are assigned in a systematic manner,

identification numbers of scrapped or destroyed items are not usedagain,

ECSS-Q-ST-20C Rev.11 March 20133.

identification numbers, once allocated, are not changed, unless thechange is authorized by the customer.

NOTE

Requirements  for  identification  are  addressed

in ECSS-M-ST-40.

5.2.6  Metrology and calibration

a.

The supplier shall control, calibrate and maintain inspection, measuringand test equipment, whether owned by the supplier, on loan, or providedby  the  customer  to  demonstrate  the  conformance  of  product  to  thespecified requirements.

The  supplier  shall  use  equipment  in  a  manner  which  ensures  thatmeasurement  uncertainty  is  known  and  is  consistent  with  the  specifiedmeasurement capability.

The  supplier  shall  include  in  the  calculations  of  all  measurements  thetotal  error  in  the  measurement  process  attributable  to  the  cumulativeerror  from  the  calibration  chain,  measuring  equipment  and  thosecontributed by personnel, procedures and the environment.

The supplier shall record the basis for the calculation of the cumulativeerrors as specified in requirement 5.2.6c.

The  supplier  shall  select  inspection,  measuring  and  test  equipment  inconformance with the required measurement accuracy and precision.The supplier shall identify, calibrate and adjust all inspection, measuringand  test  equipment  and  devices  that  can  affect  product  quality  atprescribed intervals, or prior to use, against certified equipment.

The  supplier  shall  establish,  document  and  maintain  calibrationprocedures,  including  details of  equipment  type,  identification  number,location, frequency of checks, check method, acceptance criteria and theaction to be taken when results exceed the specified accuracy.

The  supplier  shall  ensure  that  the  inspection,  measuring  and  testequipment is capable of the specified accuracy and precision.

The  supplier  shall  identify  inspection,  measuring  and  test  equipmentwith  a  suitable  indicator  or  approved  identification  record  to  show  thecalibration status.

The supplier shall maintain calibration records for inspection, measuringand test equipment.

The  supplier  shall  assess  and  document  the  validity  of  previousinspection and test results when inspection, measuring or test equipmentis found to be out of calibration.

The supplier shall ensure that the environmental conditions are suitablefor  the  calibrations,  inspections,  measurements  and  tests  being  carriedout.

The  supplier  shall  ensure  that  inspection,  measuring  and  test  facilities,including  both  test  hardware  and  test  software  are  protected  againstadjustments, which can invalidate the calibration setting.

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

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013n.

o.

The  supplier  shall  ensure  that  the  inspection,  measuring  and  testequipment is handled, preserved and stored such that the accuracy andfitness for use is maintained.

The  supplier  shall  check  the  test  hardware  or  test  software  used  forinspection to prove that it is capable of verifying the acceptability of theproduct prior to release for use during production and installation, andrecheck it at specified intervals.

NOTE 1  Examples  of  test  hardware  are:  jigs,  fixtures,

templates and patterns.

NOTE 2  Test  aids  such  as  test  leads,  break-out  boxes,

mains leads and similar items are not subject to

the  entire  set  of  requirements  defined  in  this

clause,  but  are  validated  in  a  way  appropriate

to their usage.

p.

q.

The supplier shall establish the extent and frequency of such checks andshall maintain records as evidence of control.

The  supplier  shall  make  the  measurement  design  data  available  to  thecustomer upon request.

5.2.7

Handling, storage and preservation

5.2.7.1  Handling

a.

The  supplier  shall  prevent  handling  damage  during  all  phases  ofmanufacturing, assembly, integration, testing, storage, transportation andoperation.

NOTE

Possible prevention measures are:

•  protection of items during handling,

•  handling devices, or

•  procedures and instructions.

Storage

5.2.7.2

a.

The supplier shall place the following items in secure storage areas:

1.

2.

incoming materials,

intermediate items needing temporary storage, and

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

b.

The  supplier  shall  place  the  following  items  in  designated  segregatedareas:

1.

2.

3.

limited life materials,

suspended limited life materials,

nonconforming items awaiting NRB disposition,

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

5.

items  designated  to  be  stored  separately  for  health  or  safetyreasons.

Each segregated area shall be identified and labelled for its intended use.The supplier shall maintain control over acceptance into and withdrawalfrom storage areas.

The  supplier  shall  maintain  records  to  ensure  that  all  stored  items  arewithin  the  usable  life  limits,  controlled  and  retested,  and  to  providec.

d.

e.

<table align="center">
	<tr align="center">
	</tr>
</table>

5.2.7.3

a.

Preservation

The supplier shall ensure that items subject to deterioration, corrosion orcontamination  through  exposure  to  any  environmental  elements  arepreserved  by  methods that ensure maximum protection consistent withlife and usage.

NOTE

Examples  of  such  environmental  elements  are:

air and moisture.

5.2.8

Statistical quality control and analysis

5.2.8.1  General

a.

Statistical quality control and analysis methods shall be used to maintainor improve the specified control of quality, when statistically significantwith respect to the product characteristics and to quantities produced.NOTE

Examples  of  statistical  quality  control  and

analysis  methods  are  sample  inspection  plans,

determination  of  quality

levels,  statistical

process control and process capabilities studies.

b.  When  employing  statistical  quality  control  and  analysis  methods,  thesupplier shall ensure that all the conditions for use are enforced.

NOTE

Example  of  such  conditions  are  sample

significance, recording and elaboration of data,

and formulation of clear decision rules.

c.

Statistical  quality  control  applications,  when  used  by  the  supplier  foracceptance of materials, parts, processes and products, shall be submittedto the customer for approval.

5.2.8.2

a.  When sampling plans are  used the supplier shall define and justify theSampling plans

following:

ECSS-Q-ST-20C Rev.11 March 20131.

sample  size,  sample  selection  methods  and  criteria  for  inspectionseverity,

acceptance / rejection criteria, and

screening of rejected lots.

2.

3.

The supplier shall maintain records of the sampling tests, together withthe identification of the characteristics to which sampling is applied.

b.

- 5.3  QA requirements for design and verification

![Im0](images/Im0)

<table align="center">
</table>

<table align="center">
</table>

5.3.1.2  Repeatability

a.

The  supplier  shall  ensure  that  the  product  is  designed  such  that  its<table align="center">
</table>

5.3.1.3

a.

Inspectability and testability

The supplier shall ensure that the product is designed such that it can be<table align="center">
</table>

5.3.1.4  Operability

a.

The supplier shall ensure that the product is designed such that it can beoperated  in  accordance  with  programme  constraints  and  requirements,throughout

storage,transportation, integration and operations.

including  handling,

its  whole

life

cycle

5.3.2

Verification

5.3.2.1  General

a.

The  supplier  shall  ensure  that  requirement  verification  is  performedprogressively, as each stage of the project is completed, and provides theorganized  base  of  data  upon  which  qualification  and  acceptance  isincrementally declared.

The  supplier  shall  ensure  that  top-down  requirement  allocations  andbottom-up requirement verifications are complete and consistent.

b.

ECSS-Q-ST-20C Rev.11 March 2013c.

d.

e.

The  supplier  shall  ensure  that  a  system  for  tracking  requirements  andverification  of  results  is  established  and  maintained  during  the  wholeproject life cycle.

The  supplier  shall  ensure  that  verification  methods  are  adequate  andconsistent with the type and criticality of the requirements.

The  supplier  shall  ensure  that  appropriate  reference  to  the  verificationdocumentation  is recorded  and  status  updated  at  project  reviews  up  tofinal acceptance.

5.3.2.2  Design verification analysis

a.

b.

The supplier shall ensure that the objectives of the analysis are defined inrelation with the development logic defined in the verification plan.

The following items shall be identified:

1.

2.

3.

reference of the configuration item definition under analysis;

environmental constraints considered in the analysis;

basic assumptions, analysis methods, mathematical models.

5.3.2.3  Design reviews

a.

The  supplier  shall  ensure  that  design  reviews  are  conducted  inaccordance with project requirements and written procedures.

NOTE   Design reviews address the following items:

![Im0](images/Im0)

<table align="center">
</table>

design documentation.

and

data

•  Methods

for

procurement, manufacturing, inspection and

test are available and validated.

required

•  Risks  of  not  achieving  requirements  are

highlighted and adequately controlled.

5.3.2.4  Qualification process

5.3.2.4.1  Qualification

a.

The  supplier  shall  ensure  that  all  configuration  items  and  theirconstituent  items,  either  off-the-shelf  or  specifically  designed,  areproperly qualified with margins commensurate with the application and<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

<table align="center">
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

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
	<tr align="center">
	</tr>
</table>

5.3.2.4.2  Qualification by similarity

a.

Qualification  by  similarity  with  an  identical  or  similar  product  shall  bejustified  by  providing  evidence  that  the  new  application  is  within  thelimits of the previously qualified design.

Any  difference  in  definition  with  respect  to  the  reference  product  andany difference in the required qualification tests shall be identified.

The need for complementary qualification tests shall be analysed and thedecision justified and submitted to the customer for approval.

For this purpose the supplier shall:

1.

evaluate  the  as-designed  or  as-built  configuration  and  relatednonconformances,

ensure that qualification requirements and qualification ranges arecompatible with project requirements,

ensure  that  qualification  test  results  meet  the  requirements  andany nonconformances are available for evaluation, and

ensure that a logbook of the selected model is available for review.2.

3.

4.

b.

c.

d.

b.

5.3.2.4.3  Qualification testing

a.

The  product  used  for  qualification  testing  shall  be  produced  inaccordance  with  a  full  and  clearly  identified  manufacturing  andinspection file.

To  obtain  authorization  to  initiate  qualification  tests  the  supplier  shalldemonstrate that:

1.

the  qualification  model is fully  representative  of  the  flight  modeland any differences have been analysed to evaluate their effect onthe qualification status;

inspection and test requirements are expressed in an unambiguousand quantified manner including:

(a)

(b)

(c)

(d)

(e)

test sequence;

test conditions;

test standards, if any;

applicable test levels, durations and tolerances;

accuracy in measurement.

2.

ECSS-Q-ST-20C Rev.11 March 20133.

the  qualification  test  procedures  and  facilities  are  defined,available and conforming to requirements of clause 5.5.11b.

5.3.2.4.4  Qualification status

a.

The supplier shall report the qualification status in conformance with the“Qualification status list” DRD as defined in ECSS-Q-ST-10.

5.3.2.4.5  Maintenance of qualification

a.

Once  the  design  is  qualified,  the  supplier  shall  assess  all  subsequentchanges,  deviations  and  anomalies  for  their  impact  on  the  qualificationstatus and shall perform requalification as necessary.

5.3.2.5  Design changes

a.

The supplier shall ensure that  all design changes  and modifications areidentified,  documented,

theirimplementation.

reviewed  and  approved  before

- 5.4  QA requirements for procurement

5.4.1

Selection of procurement sources

5.4.1.1  General

a.

The  supplier  QA  shall  participate  in  the  approval  and  the  selection  ofprocurement sources.

NOTE

The  selection  of  procurement  sources  for  EEE

components is defined in ECSS-Q-ST-60.

5.4.1.2

a.

Selection criteria

The supplier shall select its suppliers on the basis of one of the followingcriteria:

1.

The  supplier  has  been  certified  by  the  final  customer,  and  has  acurrent  approval  to  furnish  items  or  services  of  the  type  andquality level being procured.

The  supplier  is  furnishing,  or  has  furnished  within  the  past  twoyears,  items  or  services  of  the  type  and  quality  level  beingprocured under other contracts with the final customer.

The  supplier  has  demonstrated  continuous  capability  to  furnishitems  or  services  of  the  type  and  quality  level  being  procured,supported by objective documentation.

Supplier’s

agreementrequirements is demonstrated by a pre-award audit by the relevantcustomer.

capability

business

of

satisfying

2.

3.

4.

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

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
	<tr align="center">
	</tr>
</table>

b.

The  supplier  shall  document  and  maintain  on  file  results  of  supplierselection process.

5.4.1.3  Record and list of procurement sources

a.

The  supplier  shall  establish  and  maintain  records  of  all  procurementsources involved in business agreement performance.

The  supplier  shall  submit  to  the  customer,  upon  request,  the  list  ofprocurement  sources,  including  all  the  information  in  the  records5.4.1.3a, for information.

b.

5.4.2

a.

Procurement documents

b.

c.

d.

The  supplier  shall  ensure  that  supplies  are  identified  and  that  allapplicable requirements are defined in the procurement documents.

The supplier shall ensure that requirements to those contained in lowertier procurement documents are traceable.

The procurement documents shall contain, by statement or reference:1.

comprehensive technical descriptions of the items and services tobe procured,

details  of  the  applicable  requirements,  such  as  requirements  forpreservation,  packaging,  marking,

shipping,  accompanyingdocumentation and provisions for limited-life items,

details of QA activities to be performed, such as inspection and testcharacteristics, records and reports,

details of supplier’s QA activities at source, and

special acceptance conditions.

4.

5.

The supplier’s quality assurance organization shall review procurementdocuments prior to release, to verify the correct selection of procurementsources and appropriateness of their content.

2.

3.

5.4.3

a.

Surveillance of procurement sources

The supplier shall exercise surveillance over all the activities carried out<table align="center">
</table>

personnel at his suppliers’ facilities and source inspection.

ECSS-Q-ST-20C Rev.11 March 2013NOTE

Example  of  review

is

the  manufacturing

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

1.

2.

Testing or inspections cannot be accomplished by the supplier.Verification tests are destructive in nature and the quality cannotbe verified solely by inspection or test at supplier’s facility.

Supplies  are  designated  for  direct  shipment  from  source  to  acustomer site or the using site.

3.

4.  Manufacturing and AIV of complex equipment or subsystems.5.

Past performance or quality history of the lower level supplier ismarginal.

Functional criticality and technical complexity of the supplies.

6.

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

d.

e.

The  supplier  shall  ensure  that  each  of  his  suppliers  implementssurveillance on their lower level suppliers, in accordance with the samecriteria.

Surveillance may be delegated by the customer to third parties.

5.4.4

Receiving inspection

5.4.4.1  General

a.

b.

incoming  supplies,

The  supplier  shall  ensure  that  all

includingdocumentation  and  packaging,  whether  delivered  on  his  own  premisesor  elsewhere,  conform  to  the  requirements  of  the  procurementdocuments.

The  supplier  shall  perform  inspections  in  accordance  with  establishedprocedures  and  instructions,  to  ensure  that  quality  level  is  properlydetermined.

NOTE 1  Sampling  plans  in  receiving  inspection  are

defined in 5.2.8.2.

NOTE 2  Receiving  inspection  of  components  is  defined

in ECSS-Q-ST-60.

NOTE 3  Lot  or  batch  acceptance  of  materials  and

mechanical parts is defined in ECSS-Q-ST-70.

c.

Receiving  inspectors  shall  have  available  the  procurement  documents,specifications,  drawings  and  any  other  document  relevant  to  incomingsupplies as required in the procurement documents.

ECSS-Q-ST-20C Rev.11 March 20135.4.4.2  Receiving inspection activities

a.

Receiving inspection activities shall include:

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

verification  of  the  packaging  conditions  and  of  the  status  ofenvironmental sensors,

visual inspection of the delivered items,

verification  of  correct  identification  and,  where  appropriate,configuration identification for conformance to the ordering data,verification  of  the  evidence  of  inspection  and  tests  performed  bythe supplier and associated documentation,

verification  of  the  performance  of  supplier’s  source  inspection,when required,

performance of inspections and tests on selected characteristics ofincoming supplies or test specimens submitted with the supplies,identification of the shelf life of limited-life items,

identification  of  the  inspection  status  and  physical  separation  ofthe  supplies  in  the  receiving  inspection  area  according  to  thefollowing categories:

(a)

items  for  which  the  receiving  inspection  has  not  beencompleted;

conforming items;

nonconforming items.

(b)

(c)

prevention of unauthorized use of uninspected items,

identification  of  the  items  to  be  released  for  production  withconformance  status  and  traceability  data  to  be  recorded  inmanufacturing documents,

11.  maintenance  of  receiving  inspection  records in  conformance  with5.4.4.4.

5.4.4.3  Customer furnished items

a.

Receiving  inspection  of  items  supplied  by  the  customer  shall  consist  ofthe verification of identity and integrity after transportation.

NOTE   Additional  inspections  and  tests,  if  any,  are

specified in the business agreement.

5.4.4.4  Receiving inspection records

a.

The  supplier  shall  maintain  receiving  inspection  records  to  ensuretraceability  and  the  availability  of  historical  data  to  monitor  supplierperformance and quality trends.

![Im0](images/Im0)

![Im0](images/Im0)

- 5.5  QA requirements for manufacturing, assembly and

integration

ECSS-Q-ST-20C Rev.11 March 20135.5.1

Planning of manufacturing, assembly andintegration activities and associated

documents

a.

b.

c.

The  supplier  shall  document  the  planning  of  manufacturing,  assemblyand integration operations and inspections in the manufacturing plan orflow  chart  for  the  product,  including  the  sequence  of  operations  andassociated inspections and tests.

The  planning  shall  include  the  identification  of  MIPs  in  conformancewith  5.5.8,  together  with  the  reference  to  the  procedures  by  which  thevarious activities are performed and the required cleanliness levels andtemperature and humidity requirements of the facilities.

Instructions  shall  direct  the  actual  performance  of  manufacturing,assembly and integration  operations and inspections, to ensure that theactivities  proceed  in  an  orderly  manner  and  according  to  the  plannedsequence.

NOTE

For example: shop travellers.

<table align="center">
	<tr align="center">
	</tr>
</table>

e.

The QA organization shall review and approve such documents, and anymodifications thereof, to ensure that they include or refer to:

1.

2.

3.

4.

5.

6.

7.

8.

Identification of the item to be  manufactured or equipment to  beused.

Configuration  data,  including  parts  lists,  drawings,  changes  andspecifications.

Identification  of  the  production  and  inspection  equipment  to  beused for the manufacturing, assembly and integration of the item.Identification of critical characteristics.

Detailed definition, by description or reference, of manufacturing,assembly,  integration,  inspections  and  test  operations  to  beperformed, and special conditions to be maintained.

Provisions  for  inspections  and  tests  to  be  witnessed  by  customerrepresentative.

Accept  or  reject  criteria  (with  tolerances)  and  workmanshipstandards.

Details of sampling inspection procedures to be used, if any.

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

f.

g.

Only  “first  off”  shop  travellers  shall  be  reviewed  unless  subsequenttravellers incorporate a significant change of inspection requirements ororder of events.

The  supplier  shall  also  provide  for  detail  support  documents  andinstructions,  such  as  drawings,  procedure  and  instruction  sheets,  toenable operations to be correctly performed.

<table align="center">
</table>

2.

inspection  and

The manufacturing readiness review shall evaluate the following aspects:status of product definition and requirements, differences with the1.

status of the qualification model, and impacts of these differences;status  of  manufacturing,  assembly,

testdocumentation,  differences  with  the  status  of  the  qualificationb.

<table align="center">
</table>

implementation  of  dispositions  for  risk  reduction,  as  defined  byrisk  assessment,  into  the  manufacturing,  assembly,  integration,4.

<table align="center">
</table>

status, when relevant;

cleanliness  of  facilities,  with  respect  to  the  specified  cleanlinesslevels;

facility temperature and humidity with respect to requirements.6.

7.

b.

5.5.3

Control of processes

5.5.3.1  General

a.

The  supplier  shall  monitor  all  processes  used  for  manufacturing,assembly  and

integration,  and  enforce  all  applicable  processrequirements.

The supplier shall ensure that all manufacturing processes are covered by<table align="center">
	<tr align="center">
	</tr>
</table>

c.

d.

Process  specifications  shall

inspection and test, number of samples, accept or reject criteria.

Process witness samples shall be stored in controlled conditions.

include  QA  provisions,  methods  for![Im0](images/Im0)

5.5.3.2

a.

Special processes

ECSS-Q-ST-20C Rev.11 March 2013The supplier shall establish and implement procedures and controls forspecial processes, to ensure that:

<table align="center">
	<tr align="center">
	</tr>
</table>

3.  Materials,  equipment,  computer  systems  and  software,  andprocedures involved in the performance of the special process arevalidated and monitored.

Coordination

is  maintained  with  the  cognizant  engineeringfunction  to  ensure  proper  selection  of  the  non-destructive  or4.

<table align="center">
	<tr align="center">
	</tr>
</table>

5.5.3.3

a.

Statistical process control

Statistical methods for process control should be used for early detectionof  significant  variations  in  manufacturing  processes,  in  order  todetermine, analyse and eliminate the causes of undesirable variations.5.5.4  Workmanship standards

a.

The supplier shall employ workmanship standards throughout all phasesof  manufacturing,  assembly  and  integration,  to  ensure  acceptable  andconsistent workmanship quality levels.

b.  Workmanship standards shall identify acceptance or rejection criteria.c.

Physical  samples  or  visual  aids  shall  be  reviewed  and  agreed  by  thecustomer when they are used for the purpose of acceptance or rejection ofitems.

5.5.5  Materials and parts control

a.

The  supplier  shall  ensure  that  only  conforming  items  are  released  andused, and that those not required for the operation involved are removedfrom work operation areas.

Items having limited-life or definite characteristics of quality degradationor drift with age or use shall be marked to indicate the dates, test times orcycles at which life was initiated and at which the useful life expires.

b.

<table align="center">
</table>

![Im0](images/Im0)

5.5.6

Equipment control

ECSS-Q-ST-20C Rev.11 March 20135.5.6.1

a.

Tooling

The supplier shall make provisions for accountability, identification andmaintenance of manufacture, assembly and integration tooling.

b.  Manufacture,  assembly  and  integration  tooling  shall  be  checked  for  itsdimensional  accuracy,  regarding  the  product  drawings,  and  correctfunction.

<table align="center">
</table>

e.

Tools  shall  be  checked  for  accuracy  during  the  production  life  atadequate intervals.

Tools shall be submitted to re-approval following modification.

Tools  shall  be  properly  stored  to  prevent  misuse,  damage  anddeterioration.

Unnecessary tools shall be removed from working areas.

Records shall be kept of all manufacturing equipment.

f.

g.

h.

i.

5.5.6.2

a.

b.

Equipment for computer-aided manufacturing

The  supplier  shall  ensure  that  computer-aided  techniques  and  data  forprocessing  and  machining  are  validated  prior  to  use  and  controlledduring their use in manufacturing.

The  supplier  shall  ensure  that  provisions  are  made  for  the  testing,approval  and  configuration  control  of  the  software  involved  andprevention of its being tampered with.

5.5.7

Cleanliness and contamination control

5.5.7.1  General

a.

The  supplier  shall  establish  controls  for  cleanliness  of  spacecrafthardware and facilities, and the limitation of sources of contamination.NOTE

Cleanliness and contamination control methods

and processes are detailed in ECSS-Q-ST-70-01.

5.5.7.2  Cleanliness levels

a.

b.

items  shall  be  cleaned,  controlled  andContamination-sensitive

maintained to the required cleanliness levels.

The  required  cleanliness  levels  for  all levels  of  flight hardware  shall  beindicated  on  drawings,  specifications,  procedures,  or  other  documentscontrolling the manufacture, assembly, integration and test of the items.ECSS-Q-ST-20C Rev.11 March 20135.5.7.3  Cleaning materials and methods

a.

The supplier shall develop detailed methods for attaining the cleanlinesslevels specified for the hardware.

5.5.7.4  Contamination control

a.

Contamination shall be minimized  by operating in clean  working  areasand by proper handling, preservation, packaging and storage.

Contamination-sensitive items fabricated or processed in contamination-controlled environments shall be inspected, tested, modified or repairedin identical or cleaner environments, unless specific precautions are takento protect the items concerned from contamination.

Specific  protection  measures,  such  as  protective  dust  covers,  shall  beimplemented  to  protect  contamination-sensitive  items  when  they  areintegrated in a higher level of assembly.

5.5.7.5  Cleanliness of facilities

a.

Fabrication,  assembly  and  integration  of  contamination  sensitive  itemsshall be conducted in facilities that provide cleanliness levels compatiblewith the specified product cleanliness.

b.

c.

b.

c.

d.

5.5.8

a.

Inspection

Inspection and tests shall be planned at the points of the manufacturing,assembly  and  integration  flow  where  maximum  assurance  for  correctprocessing and  prevention  of  unrecoverable  or  costly  nonconformancescan be obtained.

All identified critical characteristics shall be inspected as defined in thecritical-item control programme.

Self-inspection

manufacturing,  assembly  and

considered sufficient for critical characteristics.

Among the inspections and tests as part of the manufacturing, assemblyand  integration  flow,  mandatory  inspection  points  (MIPs)  shall  beassociatedintegration  activities  shall  not  beoperators  performing

by

the

the

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

f.

MIPs shall be selected in accordance with the criteria as defined below,when one or more of the following conditions apply:

1.  When maximum visibility of quality is given.

2.  When critical processes are performed.

3.  Where the next step of the manufacturing sequence:

(a)

is irreversible, or

ECSS-Q-ST-20C Rev.11 March 2013(b)  makes  the  item  difficult  and  costly  to  disassemble  forinspection, or

renders the location inaccessible for inspection.

(c)

4.  When the item, once installed in the next higher assembly damagesby its failure the higher assembly.

5.  When  previous  failure  history  of  the  item  indicates  a  need  forinspection.

6.  When a potential adverse impact on the properties and integrity ofthe end product could result, owing to the criticality or complexityof the manufacturing step.

7.  When testing or critical inspections cannot be accomplished by thesupplier.

NOTE

For  example,  environments  or  test  equipment

not available at supplier’s facility.

g.

h.

i.

8.  When  verification  tests  are  destructive  in  nature  and  the  qualitycannot  be  verified  solely  by  inspection  or  test  at  the  supplier’sfacility.

9.  When  manufacturing  and  AIV  of  complex  equipment  orsubsystems is planned.

NOTE

For example, for payloads.

10.  When  past  performance  or  quality  history  of  the  lower  levelsupplier is marginal.

11.  When an item is going to final inspection.

Criteria 5.5.8f.7 to 10 shall be considered together with the criticality andcomplexity of the supplies and the supplier’s experience with the lowerlevel supplier.

A MIP shall require an invitation with the agreed notice before the event,and  the  participation  of  the  customer,  or  their  written  agreement  toproceed without their participation.

The  supplier  shall  make  provisions  for  a  positive  identification  of  theinspection and test status of any items at any stage of the manufacturing,assembly and integration cycle, starting from the incoming inspection up![Im0](images/Im0)

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
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

![Im0](images/Im0)

5.5.9

Specific requirements for assembly and

integration

ECSS-Q-ST-20C Rev.11 March 20135.5.9.1  Control of temporary installations and removals

a.

The  supplier  shall  ensure  the  control  of  flight  items  which  aretemporarily removed or non-flight items which are temporarily installedto facilitate assembly, integration, testing, handling or preservation of theend item.

The  control  shall  be  initiated  upon  installation  or  removal  of  the  firsttemporarily  installed  or  removed  item  and  be  maintained  throughdelivery and use of the end item.

The  supplier  shall  establish  and  maintain  records  of  temporaryinstallations and removals.

Temporarily installed items shall be accounted for to prevent their beingb.

c.

d.

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

Logbooks

5.5.9.2

a.

The  supplier  shall  prepare  and  maintain  system,  subsystem  and<table align="center">
	<tr align="center">
	</tr>
</table>

Subsystem  and  system  logbooks  shall  follow-on  from  the  individualequipment logbooks to form a full record.

The logbook shall accompany the hardware whenever it is placed in thecustody of another organization

The receiving organization shall maintain the logbook up-to-date.

c.

d.

e.

5.5.10  Manufacturing, assembly and integration

records

a.

The supplier shall establish and maintain manufacturing, assembly andintegration  records  to  provide  all  manufacturing,  assembly,  integration<table align="center">
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
	<tr align="center">
	</tr>
</table>

![Im0](images/Im0)

- 5.6  QA requirements for testing

ECSS-Q-ST-20C Rev.11 March 20135.6.1

a.

5.6.2

a.

b.

c.

Test facilities

The  supplier  shall  ensure  that  test  facilities,  either  internal  or  external,conform to specified requirements.

Test equipment

The  supplier  shall  ensure  that  computer-aided  testing  techniques  anddata are validated prior to use and controlled during their use in testing.The supplier shall ensure that provisions are made for testing, approvaland configuration control of the software involved and prevention of itsbeing tampered with.

The supplier shall ensure that test equipment are designed such that theircorrect operation can be verified without having to apply them to the testitem.

5.6.3

Test documentation

5.6.3.1

Test procedures

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

b.

The QA organization shall review and approve test procedures.

5.6.3.2

a.

Test reports

The supplier shall ensure that all tests are comprehensively documentedin test reports, and that they include, as a minimum:

1.

reference  to  the  applicable  test  procedure,  and  description  of  thedeviations from it during the actual testing,

test data records and evaluation, and

summary of test results.

2.

3.

The QA organization shall review and approve test reports.

Test performance monitoring

b.

5.6.4

<table align="center">
</table>

deviations are properly documented and treated.

ECSS-Q-ST-20C Rev.11 March 2013b.

Test  witnessing  by  QA  personnel  shall  be  considered  when  manualintervention is performed, at the setting-up, start and end of continuousfully automated test sequences, or when no  automatic recording of testparameters or results is available.

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

<table align="center">
</table>

f.

Testing shall be subject to the requirements for the control of hazardousoperations.

NOTE   Definition  of  hazardous  operations  is  given  in

ECSS-Q-ST-40.

g.  Where  safety  of  personnel  or  damage  to  items  or  associated  testequipment is possible, QA personnel shall have the authority to stop thetest.

5.6.5

Test reviews

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

b.

The  QA  organization  shall  be  represented  in  the  formal  boardsestablished  for  the  review  of  readiness  for  testing  and  testingaccomplishment.

- 5.7  QA requirements for acceptance and delivery

5.7.1

a.

Acceptance and delivery process

The  supplier  shall  establish  a  formal  acceptance  process  for  alldeliverable items, at any contractual level, to ensure that conformance ofthe items to be delivered is fully assessed and documented.

<table align="center">
</table>

![Im0](images/Im0)

5.7.2

a.

End item data package

ECSS-Q-ST-20C Rev.11 March 2013The  supplier  shall  provide  an  EIDP  for  each  deliverable  end  item  inconformance with the DRD in Annex B.

The EIDP shall constitute the basis for formal acceptance reviews.

EIDPs shall be maintained and integrated into higher level EIDPs duringsubsystem or system integration and testing.

The supplier shall ensure that a DRB is convened prior to the delivery of5.7.3

a.

Delivery review board (DRB)

b.

c.

<table align="center">
</table>

The  DRB  functions  at  system  level  shall  be  fulfilled  by  the  finalacceptance review and chaired by the customer.

The DRB shall be composed, at least, of the following members:

1.

Representatives of the receiving organization:

(a)

(b)

(c)

Project manager, or authorized representative, as chairman;PA manager, or authorized representative;

Engineering

representative.

design  manager,

authorizedor

or

2.

Submitting supplier’s representatives:

(a)

(b)

(c)

Project manager, or authorized representative;

PA manager, or authorized representative;

Engineering

representative.

design  manager,

or

or

authorized3.

level  customers’  representative(s),  as  observers  (notHigher

required for separate subsystems).

If the final customer reserves the right to attend DRBs at any lower levelas an observer, he shall be given due notice of such a DRB meeting.

The DRB shall be responsible for authorising the shipment of the itemsunder acceptance, and certifying in writing that:

1.

the  items  conform  to  the  contractual  requirements  and  to  anapproved design configuration;

the items are free from material and workmanship deficiencies;all  nonconformances  are  closed-out,  or  corresponding  plans,compatible with the delivery, are accepted;

the relevant EIDP is complete and accurate.

4.

Delivery  shall  only  be  authorized  by  the  unanimous  agreement  of  theDRB members.

For the delivery a certificate of conformity, in conformance with AnnexD, shall be made available and signed by the supplier.

2.

3.

b.

c.

d.

e.

f.

g.

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

5.7.4

Preparation for delivery

5.7.4.1

a.

Packaging

The supplier shall ensure that packaging materials, methods, proceduresand  instructions  provide  for  protection  of  items  while  at  the  supplier’splant, during transportation, and after their arrival at destination.

5.7.4.2  Marking and labelling

a.

The  supplier  shall  ensure  that  appropriate  marking  and  labelling  forpackaging, storage, transportation and shipping of items are performedin accordance with the applicable specifications.

5.7.5

Delivery

Shipping control

The supplier shall ensure that the items to be shipped from his plant areinspected before release and found to be complete, adequately preservedand  packaged,  correctly  marked  and  accompanied  by  all  the  requireddocumentation.

Accompanying  documentation  shall  include  the  EIDP  and,  attached  tothe  outside  of  the  shipping  container,  the  handling  and  packing  orunpacking procedure and any relevant safety procedures.

5.7.5.1

a.

b.

5.7.5.2

a.

Transportation

The supplier shall make provisions for the prevention of damage to itemsduring transportation.

- 5.8  QA requirements for ground support equipment

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
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

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
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

5.8.2

a.

Configuration control

The supplier shall ensure that GSE is configuration controlled.

5.8.3

Production

5.8.3.1

a.

Procurement

The  supplier  shall  ensure

demonstrated ability to conform to requirements, through:

1.

that  selected  GSE  suppliers  have  aprevious supply of items similar or more complex in the same fieldof techniques and technologies,

certification covering similar design, development and productionas applicable for similar items in conformance with 5.4.1.2, or

evidence,  documented  by

existing  design,  development,production  and  quality  standards,  of  having  similar  experienceassociated with known success.

2.

3.

b.

Procurement  documents  shall

identify  validation  and  receivinginspection requirements, and conform to the requirements in clause 5.4.2.5.8.3.2  Manufacturing, assembly, integration and test

a.

The supplier and his lower level suppliers should not deviate from theirstandard  practices  when  these  are  already  documented  and  recognized<table align="center">
</table>

5.8.4.1

a.

End item data package

The acceptance data package shall include:

1.

2.

information regarding interfaces,

deviations from contractual requirements,

ECSS-Q-ST-20C Rev.11 March 20133.

4.

certification of conformance to an identified baseline,

description  of  the  functioning  of  the  item,  and  instructions  tooperate and maintain it, and

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
	<tr align="center">
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 20135.8.8  General requirements

a.

The  following  requirements  shall  be  tailored  in  accordance  with  thecomplexity and criticality of the GSE item:

1.

2.

traceability requirements in 5.2.5, and

metrology and calibration requirements in 5.2.6.

5.8.9  Maintenance

a.

b.

The supplier shall ensure that maintenance activities are planned.

The supplier shall ensure that maintenance demonstration is performedin  order  to  prove  that  maintainability  requirements  are  satisfied  in  thereal operational environment.

![Im0](images/Im0)

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

<table align="center">
</table>

- For the terminology and definitions of the space product types see ECSS-S-ST-00-01 which is quoted in 3.1.

NOTE 1  In the matrix, the column “Software” is for consideration in the developmentof  software,  only  in  the  case  when  the  software  is  not  installed  in  ahardware. Since “Software product assurance” is covered by ECSS-Q-ST-80,this  document  is  not  applicable  to  SW  PA,  and  therefore  the  column“Software” in the matrix always states “NA”.

NOTE 2  Catalogue  Off-the-shelf  equipment  is  off-the-shelf  equipment  that  isprocured from a stock defined in a supplier catalogue. For example, a UNIXServer is a “Catalogue Off-the-shelf equipment” while a 30 m Antenna canbe an off-the-shelf even it is built on order only.

<table align="center">
	<tr align="center">
		<td>Column title</td>
		<td>Description</td>
	</tr>
	<tr align="center">
		<td>Applicability status</td>
		<td>There are seven product types, one per column. For the column “i” (i = 1 to 8) possible values are: “A” when applicable, “NA” when not applicable, or “Xi” to be decided on a case by case basis, with explanation in column comments • • • •  A* when requirement is applicable with supplementary indications in the “Comment” column A requirement is considered applicable for a product type if it is verified on this product type. It is possible to have a requirement applicable at various level of product (system, element, equipment and software) • • If a requirement is verified only at one level, and the information transmitted to the upper level without any treatment, it will be considered applicable only at the level it was verified (“ Yes “ in the column where it is verified). If a requirement is verified at one level, and also verified at the upper level, it will be considered applicable at both levels (a “Yes “ in both columns).</td>
	</tr>
	<tr align="center">
		<td>Comments</td>
		<td>The column “Comments” shall be used to explain the rationale for having not decided if applicable or not. It shall not be used to modify a requirement but it can provide clarification on specific conditions for the applicability of the requirement.</td>
	</tr>
</table>

ECSS-Q-ST-20C Rev.11 March 2013![Im0](images/Im0)

