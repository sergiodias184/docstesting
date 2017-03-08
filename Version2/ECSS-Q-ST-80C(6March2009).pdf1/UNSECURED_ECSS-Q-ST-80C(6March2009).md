ECSS-Q-ST-80C6 March 2009Space product

assurance

Software product assurance

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐Q‐ST‐80C  Working  Group,  reviewed  by  the  ECSS 

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

ECSS‐Q‐ST‐80C 6 March 2009 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐Q‐80A  19 April 1996 </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐80B  10 October 2003 </td>
		<td>Second issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐Q‐ST‐80C  6 March 2009 </td>
		<td>Third issue  Main changes with respect to previous version are:  •  definition of software criticality categories and tailoring of the Standard  • • based on those;  improvement of requirements on re‐use of software, software safety  and dependability and software process assessment and improvement;  streamlining of requirements to make the Standard more suitable for  direct use in business agreements. </td>
	</tr>
</table>

3 ECSS‐Q‐ST‐80C 6 March 2009 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................8

- 2 Normative references.............................................................................................9

- 3 Terms, definitions and abbreviated terms..........................................................10

- 3.1  Terms for other standards ........................................................................................10

- 3.2  Terms specific to the present standard ....................................................................10

- 3.3  Abbreviated terms ....................................................................................................16

- 4 Space system software product assurance principles .....................................18

- 4.1

Introduction...............................................................................................................18- 4.2  Organization of this Standard...................................................................................19

- 4.3  Tailoring of this Standard .........................................................................................21

- 5 Software product assurance programme implementation ...............................22

- 5.1  Organization and responsibility ................................................................................22

5.1.1  Organization ...............................................................................................225.1.2  Responsibility and authority........................................................................225.1.3  Resources ..................................................................................................23Software product assurance manager/engineer.........................................235.1.4

5.1.5

Training.......................................................................................................23- 5.2  Software product assurance programme management ...........................................24

Software product assurance planning and control .....................................245.2.1

Software product assurance reporting........................................................255.2.2

Audits..........................................................................................................265.2.3

Alerts ..........................................................................................................265.2.4

Software problems......................................................................................265.2.5

5.2.6  Nonconformances ......................................................................................275.2.7  Quality requirements and quality models ...................................................27- 5.3  Risk management and critical item control...............................................................28

5.3.1  Risk management.......................................................................................284 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 5.3.2  Critical item control.....................................................................................28- 5.4  Supplier selection and control ..................................................................................28

Supplier selection .......................................................................................285.4.1

Supplier requirements ................................................................................295.4.2

5.4.3

Supplier monitoring.....................................................................................295.4.4  Criticality classification................................................................................30- 5.5  Procurement.............................................................................................................30

5.5.1

Procurement documents ............................................................................305.5.2  Review of procured software component list..............................................30Procurement details....................................................................................305.5.3

Identification ...............................................................................................305.5.4

5.5.5

Inspection ...................................................................................................30Exportability................................................................................................315.5.6

- 5.6  Tools and supporting environment ...........................................................................31

5.6.1  Methods and tools ......................................................................................315.6.2  Development environment selection ..........................................................31- 5.7  Assessment and improvement process....................................................................32

Process assessment ..................................................................................32Assessment process ..................................................................................33Process improvement.................................................................................345.7.1

5.7.2

5.7.3

6.1.1

6.1.2

6.1.3

6.1.4

6.1.5

- 6 Software process assurance ...............................................................................35

- 6.1  Software development life cycle...............................................................................35

Life cycle definition .....................................................................................35Process quality objectives ..........................................................................35Life cycle definition review..........................................................................35Life cycle resources....................................................................................35Software validation process schedule ........................................................36- 6.2  Requirements applicable to all software engineering processes..............................36

6.2.1  Documentation of processes......................................................................366.2.2

Software dependability and safety..............................................................376.2.3  Handling of critical software........................................................................39Software configuration management..........................................................416.2.4

6.2.5

Process metrics..........................................................................................436.2.6

Verification..................................................................................................446.2.7  Reuse of existing software .........................................................................47Automatic code generation.........................................................................506.2.8

5 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 - 6.3  Requirements applicable to individual software engineering processes or

activities....................................................................................................................51Software related system requirements process .........................................516.3.1

6.3.2

Software requirements analysis .................................................................516.3.3

Software architectural design and design of software items ......................536.3.4  Coding ........................................................................................................546.3.5

Testing and validation.................................................................................556.3.6

Software delivery and acceptance..............................................................606.3.7  Operations..................................................................................................616.3.8  Maintenance...............................................................................................62- 7 Software product quality assurance...................................................................64

- 7.1  Product quality objectives and metrication ...............................................................64

7.1.1  Deriving of requirements ............................................................................647.1.2  Quantitative definition of quality requirements............................................64Assurance activities for product quality requirements ................................647.1.3

7.1.4

Product metrics...........................................................................................647.1.5

Basic metrics ..............................................................................................657.1.6  Reporting of metrics ...................................................................................657.1.7  Numerical accuracy....................................................................................657.1.8

Analysis of software maturity......................................................................66- 7.2  Product quality requirements....................................................................................66

7.2.1  Requirements baseline and technical specification....................................667.2.2  Design and related documentation.............................................................677.2.3

Test and validation documentation.............................................................67- 7.3  Software intended for reuse .....................................................................................68

7.3.1  Customer requirements..............................................................................687.3.2

Separate documentation ............................................................................687.3.3

Self-contained information..........................................................................687.3.4  Requirements for intended reuse ...............................................................687.3.5  Configuration management for intended reuse ..........................................687.3.6

Testing on different platforms .....................................................................697.3.7  Certificate of conformance..........................................................................69- 7.4  Standard ground hardware and services for operational system .............................69

7.4.1  Hardware procurement...............................................................................697.4.2

Service procurement ..................................................................................697.4.3  Constraints .................................................................................................70Selection.....................................................................................................707.4.4

6 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 7.4.5  Maintenance...............................................................................................70- 7.5  Firmware ..................................................................................................................70

7.5.1  Device programming ..................................................................................707.5.2  Marking.......................................................................................................717.5.3  Calibration ..................................................................................................71- Annex A (informative)  Software documentation..................................................72

- Annex B (normative)  Software product assurance plan (SPAP) - DRD .............78

- Annex C (normative)  Software product assurance milestone report

- (SPAMR) - DRD....................................................................................................85

- Annex D (normative)  Tailoring of this Standard based on software

- criticality ..............................................................................................................88

- D.1  Software criticality categories...................................................................................88

- D.2  Applicability matrix....................................................................................................88

- Annex E (informative)  List of requirements with built-in tailoring

- capability..............................................................................................................99

- Annex F (informative) Document organization and content at each

- milestone ...........................................................................................................100

- F.1

Introduction.............................................................................................................100- F.2  ECSS-Q-ST-80 Expected Output at SRR ..............................................................100

- F.3  ECSS-Q-ST-80 Expected Output at PDR ..............................................................102

- F.4  ECSS-Q-ST-80 Expected Output at CDR ..............................................................106

- F.5  ECSS-Q-ST-80 Expected Output at QR.................................................................108

- F.6  ECSS-Q-ST-80 Expected Output at AR.................................................................109

- F.7  ECSS-Q-ST-80 Expected Output not associated with any specific milestone

review .....................................................................................................................111- Bibliography...........................................................................................................113

 

- Figures

- Figure 4-1: Software related processes in ECSS Standards .................................................19

- Figure 4-2: Structure of this Standard ....................................................................................20

- Figure A-1 : Overview of software documents .......................................................................72

- Tables

- Table A-1 : ECSS-E-ST-40 and ECSS-Q-ST-80 Document requirements list (DRL) ............73

- Table B-1 : SPAP traceability to ECSS-E-ST-40 and ECSS-Q-ST-80 clauses......................78

- Table C-1 : SPAP traceability to ECSS-E-ST-40 and ECSS-Q-ST-80 clauses .....................85

- Table D-1 : Software criticality categories ..............................................................................88

- Table D-2 : Applicability matrix based on software criticality..................................................89

7 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 ScopeThis Standard defines a set of software product assurance requirements to be used  for  the  development  and  maintenance  of  software  for  space  systems. Space systems include manned and unmanned spacecraft, launchers, payloads, experiments  and  their  associated  ground  equipment  and  facilities.  Software includes the software component of firmware. 

This  Standard  also  applies  to  the  development  or  reuse  of  non‐deliverable software  which  affects  the  quality  of  the  deliverable  product  or  service provided by a space system, if the service is implemented by software. 

ECSS‐Q‐ST‐80  interfaces  with  space  engineering  and  management,  which  are addressed in the Engineering (‐E) and Management (‐M) branches of the ECSS System,  and  explains  how  they  relate  to  the  software  product  assurance processes. 

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

Tailoring  of  this  Standard  to  a  specific  business  agreement  or  project,  when software  product  assurance  requirements  are  prepared,  is  also  addressed  in clause 4.3. 

8 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply, However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01  

ECSS‐E‐ST‐40 

ECSS‐Q‐ST‐10 

ECSS‐Q‐ST‐10‐04 

ECSS‐Q‐ST‐10‐09 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐30 

ECSS‐Q‐ST‐40 

ECSS‐M‐ST‐10 

ECSS‐M‐ST‐10‐01 

ECSS‐M‐ST‐40 

ECSS‐M‐ST‐80 

ISO/IEC 15504 Part 2:2003 

 

ECSS system — Glossary of terms 

Space engineering — Software general 

requirements 

Space product assurance – Product assurance management 

Space product assurance – Critical‐item control Space product assurance – Nonconformance 

control system 

Space product assurance – Quality assurance Space product assurance – Dependability 

Space product assurance – Safety 

Space project management – Project planning and implementation 

Space project management –Organization and conduct of reviews 

Space project management – Configuration and information management 

Space project management – Risk management Software engineering ‐ Process assessment – 

Part 2: Performing an assessment ‐ First Edition  9 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Terms, definitions and abbreviated terms- 3.1  Terms for other standards

For the purpose of this Standard, the terms and definitions from ECSS‐ST‐00‐01 apply in particular for the term: 

acceptance test 

software product 

NOTE 

The terms and definitions are common for the 

ECSS‐E‐ST‐40 and ECSS‐Q‐ST‐80 Standards. 

- 3.2  Terms specific to the present standard

automatic code generation

3.2.1

generation of source code with a tool from a model 

code coverage

3.2.2

percentage of the software that has been executed (covered) by the test suite  competent assessor

3.2.3

person  who  has  demonstrated  the  necessary  skills,  competencies  and experience to lead a process assessment in conformance with ISO/IEC 15504 NOTE   Adapted from ISO/IEC 15504:1998, Part 9. 

condition

3.2.4

boolean expression not containing boolean operators 

configurable code

3.2.5

code (source code or executable code) that can be tailored by setting values of parameters 

NOTE 

This  definition  covers  in  particular  classes  of 

configurable  code  obtained  by  the  following 

configuration means: 

•  configuration  based  on 

the  use  of  a 

compilation directive; 

10 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 •  configuration  based  on  the  use  of  a  link 

directive; 

•  configuration 

through 

parameter defined in a configuration file; 

performed 

a 

•  configuration  performed 

through  data 

defined  in  a  database  with  impact  on  the 

actually  executable  parts  of  the  software 

(e.g.  parameters  defining  branch  structures 

that  result  in  the  non‐execution  of  existing 

parts of the code). 

COTS, OTS, MOTS software

3.2.6

for  the  purpose  of  this  Standard,  commercial‐off‐the‐shelf,  off‐the‐shelf  and modified‐off‐the‐shelf software for which evidence of use is available  

critical software

3.2.7

software of criticality category A, B or C  

NOTE 

See  ECSS‐Q‐ST‐80C  Table  D‐1  –  Software 

criticality categories. 

deactivated code

3.2.8

code  that,  although  incorporated  through  correct  design  and  coding,  is intended to execute in certain software product configurations only, or in none of them 

[adapted from RTCA/DO‐178B] 

decision

3.2.9

boolean expression composed of conditions and zero or more boolean operators that are used in a control construct. 

NOTE 1  For  example:  “if.....then  .....else”  or  the  “case” 

statement are control construct. 

NOTE 2  A  decision  without  a  boolean  operator  is  a 

NOTE 3 

condition. 

If  a  condition  appears  more  than  once  in  a 

decision, each occurrence is a distinct condition. 

decision coverage

3.2.10

measure of the part of the program within which every point of entry and exit is invoked at least once and every decision has taken “true” and “false” values at least once. 

NOTE   Decision  coverage 

statement coverage. 

includes,  by  definition, 

existing software

3.2.11

any software developed outside the business agreement to which this Standard is applicable, including software from previous developments provided by the 11 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 supplier,  software  from  previous  developments  provided  by  the  customer, COTS, OTS and MOTS software, freeware and open source software 

integration testing

3.2.12

testing  in  which  software  components,  hardware  components,  or  both  are combined and tested to evaluate the interaction between them  

[IEEE 610.12:1990] 

logical model

3.2.13

implementation‐independent  model  of  software  items  used  to  analyse  and document software requirements 

margin philosophy

3.2.14

rationale  for  margins  allocated  to  the  performance  parameters  and  computer resources of a development, and the way to manage these margins during the execution of the project 

metric

3.2.15

defined measurement method and the measurement scale 

NOTE 1  Metrics  can  be  internal  or  external,  and  direct  or 

indirect. 

NOTE 2  Metrics 

include  methods 

for 

categorising 

qualitative data. 

[ISO/IEC 9126‐1:2001] 

migration

3.2.16

porting of a software product to a new environment 

mission products

3.2.17

products and services delivered by the space system 

NOTE 

For example: Communications services, science 

data. 

modified condition and decision coverage

3.2.18

measure of the part of the program within which every point of entry and exit has been invoked at least once, every decision in the program has taken “true” and  “false”  values  at  least  once,  and  each  condition  in  a  decision  has  been shown to independently affect that decision’s outcome 

NOTE   A condition is shown to independently affect a 

decision’s  outcome  by  varying  that  condition 

while  holding 

fixed  all  other  possible 

conditions. 

operational

3.2.19

for the purpose of this Standard, related to the software operation 

NOTE 

It is not related to the spacecraft operation. 

12 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 portability (a quality characteristic)

3.2.20

capability of software to be transferred from one environment to another  

quality characteristics (software)

3.2.21

set  of  attributes  of  a  software  product  by  which  its  quality  is  described  and evaluated 

NOTE   A  software  quality  characteristic  can  have 

multiple levels of sub‐characteristics. 

quality model (software)

3.2.22

set  of  characteristics  and  the  relationships  between  them  which  provide  the basis for specifying quality requirements and evaluating quality  

[ISO/IEC 9126‐1:2001] 

real-time

3.2.23

pertaining to a system or mode of operation in which computation is performed during  the  actual  time  that  an  external  process  occurs,  in  order  that  the computation  results  can  be  used  to  control,  monitor,  or  respond  in  a  timely manner to the external process  

[IEEE 610.12:1990] 

regression testing (software)

3.2.24

selective retesting of a system or component to verify that modifications have not caused unintended effects and that the system or component still complies with its specified requirements  

[IEEE 610.12:1990] 

reusability

3.2.25

degree  to  which  a  software  unit  or  other  work  product  can  be  used  in  more than one computer program or software system 

[IEEE 610.12:1990] 

singular input

3.2.26

input corresponding to a singularity of the function 

software

3.2.27

see “software product” in ECSS‐S‐ST‐00‐01 

software component

3.2.28

part of a software system 

NOTE 1  Software component is used as a general term. 

NOTE 2  Components can be assembled and decomposed to 

form new components. In the production activities, 

components  are  implemented  as  units,  tasks  or 

programs,  any  of  which  can  be  configuration 

items. This usage of the term is more general than 

13 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 in  ANSI/IEEE  parlance,  which  defines 

a 

component  as  a  “basic  part  of  a  system  or 

program”;  in  this  Standard,  components  are  not 

always “basic” as they can be decomposed. 

software intensive system

3.2.29

space  system  in  which  the  dominant  part  of  the  constituents  are  software elements  

NOTE 

In  such  systems,  subsystems  consist  mainly  of 

software.  For  this  type  of  system,  the  majority 

of interfaces are software‐software interfaces. 

software item

3.2.30

see “software product” in ECSS‐S‐ST‐00‐01 

software observability

3.2.31

property of a system for which the values of status variables can be determined throughout observations of the output variables  

software problem

3.2.32

condition of a software product that causes difficulty or uncertainty in the use of the software  

[CMU/SEI‐92‐TR‐022] 

software product assurance

3.2.33

totality  of  activities,  standards,  controls  and  procedures  in  the  lifetime  of  a software  product  which  establishes  confidence  that  the  delivered  software product, or software affecting the quality of the delivered product, conforms to customer requirements 

software unit

3.2.34

separately compilable piece of source code  

NOTE 

In this Standard no distinction is made between 

a  software  unit  and  a  database;  both  are 

covered by the same requirements. 

statement coverage

3.2.35

measure of the part of the program within which every executable source code statement has been invoked at least once.  

stress test

3.2.36

test  that  evaluates  a  system  or  software  component  at  or  beyond  its  required capabilities  

14 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 test case

3.2.37

set  of  test  inputs,  execution  conditions  and  expected  results  developed  for  a particular objective such as to exercise a particular program path or to verify compliance with a specified requirement 

test design

3.2.38

documentation specifying the details of the test approach for a software feature or combination of software features and identifying associated tests 

test procedure

3.2.39

detailed instructions for the set up, operation and evaluation of the results for a given test 

test script

3.2.40

file  containing  a  set  of  commands  or  instructions  written  in  native  format (computer or tool processable) in order to automate the execution of one or a combination of test procedures (and the associated evaluation of the results) unit test

3.2.41

test of individual software unit 

unreachable code

3.2.42

code that cannot be executed due to design or coding error 

usability (a quality characteristic)

3.2.43

capability of the software to be understood, learned, used and liked by the user, when used under specified conditions 

validation

3.2.44

<software>  process  to  confirm  that  the  requirements  baseline  functions  and performances are correctly and completely implemented in the final product verification

3.2.45

<software> process to confirm that adequate specifications and inputs exist for any  activity,  and  that  the  outputs  of  the  activities  are  correct  and  consistent with the specifications and input 

walk-through

3.2.46

static analysis technique in which a designer or programmer leads members of the development team and other interested parties through a software product, and the participants ask questions and make comments about possible errors, violation of development standards, and other problems 

[IEEE 1028‐1997] 

15 ![Im0](images/Im0)

![Im0](images/Im0)

- 3.3  Abbreviated terms

ECSS‐Q‐ST‐80C 6 March 2009 For the purpose of this Standard and of ECSS‐E‐ST‐40, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

For the definition of DRD acronyms see Annex A. 

NOTE 

The  abbreviated  terms  are  common  for  the 

ECSS‐E‐ST‐40 and ECSS‐Q‐ST‐80 Standards. 

 

Abbreviation 

AR 

Meaning 

acceptance review 

NOTE  The term SW‐AR can be used for clarity 

to  denote  ARs  that  solely 

involve  software 

products. 

CDR 

CMMI 

COTS 

CPU 

DDF 

DDR 

DJF 

DRD 

ECSS 

eo 

GS 

HMI 

HSIA 

HW 

ICD 

INTRSA 

IRD 

ISO 

ISV 

ISVV 

MGT 

MF 

MOTS 

critical design review 

NOTE  The  term  SW‐CDR  can  be  used  for 

clarity 

involve 

software products. 

to  denote  CDRs 

that  solely 

capability maturity model integration 

commercial‐off‐the‐shelf  

central processing unit 

design definition file 

detailed design review 

design justification file 

document requirements definition 

European Cooperation for Space Standardization 

expected output 

ground segment 

human machine interface 

hardware‐software interaction analysis 

hardware  

interface control document 

international registration scheme for assessors 

interface requirements document 

International Organization for Standardization 

independent software validation 

independent software verification and validation 

management file 

maintenance file 

modified off‐the‐shelf 

16 ECSS‐Q‐ST‐80C 6 March 2009 on‐board control procedure 

operational plan 

operational readiness review 

off‐the‐shelf 

product assurance file 

preliminary design review 

NOTE  The term SW‐PDR can be used for clarity 

to  denote  PDRs  that  solely  involve  software 

products. 

preliminary requirement review 

qualification review 

NOTE  The term SW‐QR can be used for clarity 

to  denote  QRs  that  solely 

involve  software 

products. 

requirements baseline 

standard CMMI appraisal method for process 

improvement 

software development environment 

software operation support 

software product assurance 

software product assurance milestone report 

software product assurance plan 

software problem report 

software review board 

system requirements review 

NOTE  The term SW‐SRR can be used for clarity 

to  denote  SRRs  that  solely  involve  software 

products. 

software 

software engineering 

test readiness review  

technical specification 

OBCP 

OP 

ORR  

OTS 

PAF 

PDR 

PRR 

QR 

RB 

SCAMPI 

SDE 

SOS 

SPA 

SPAMR 

SPAP 

SPR 

SRB 

SRR 

SW 

SWE 

TRR 

TS 

 

17 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 - Space system software product assurance

principles- 4.1

Introduction

The  objectives  of  software  product  assurance  are  to  provide  adequate confidence  to  the  customer  and  to  the  supplier  that  the  developed  or procured/reused  software  satisfies  its  requirements  throughout  the  system lifetime. In particular, that the software is developed to perform properly and safely in its operational environment, meeting the quality objectives agreed for the project.  

This Standard contributes to these objectives by defining the software product assurance  requirements  to  be  met  in  a  particular  space  project.  These requirements deal with quality management and framework, life cycle activities and process definition and quality characteristics of products.  

One  of  the  fundamental  principles  of  this  Standard  is  the  customer‐supplier relationship,  assumed  for  all  software  developments.  The  organizational aspects  of  this  are  defined  in  ECSS‐M‐ST‐10.  The  customer  is,  in  the  general case,  the  procurer  of  two  strongly associated  products:  the  hardware  and  the software components of a system, subsystem, set, equipment or assembly. The concept  of  the  customer‐supplier  relationship  is  applied  recursively,  i.e.  the customer  can  himself  be  a  supplier  to  a  higher  level  in  the  space  system hierarchy. 

The  requirements  of  this  Standard  are  applicable  to  the  supplier,  unless otherwise explicitly stated. 

The  supplier  demonstrates  compliance  with  the  software  product  assurance requirements and provides the specified evidence of compliance. 

To this end, the supplier specifies the software product assurance requirements for his/her suppliers, taking into account their responsibilities and the specific nature of their deliverables. 

This  Standard  complements  ECSS‐E‐ST‐40  “Space  engineering  —  Software general requirements”, with product assurance aspects, integrated in the space system  software  engineering  processes  as  defined  in  ECSS‐E‐ST‐40.  Together the two standards specify all processes for space software development. 

Figure 4‐1 schematically presents the different Software processes addressed by the set of the ECSS standards. 

18 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Other ECSS

## ECSS-E-ST-40

## ECSS-Q-ST-80

Details for SPA and/or SWE## Life cycle processes

Supporting life cycle processes

## Acquisition

## Supply

Documentation

Configuration management

Development

## Operation

## Maintenance

Quality assurance

Verification

Validation

Joint review

Audit

Problem resolution

Organizational life cycle processes

Management

Improvement

Infrastructure

Training

Figure 4‐1: Software related processes in ECSS Standards 

- 4.2  Organization of this Standard

Software product assurance programme implementation 

Software process assurance  

Software product quality assurance. 

This Standard is organized into three main parts: 

•

•

•

The software documentation collecting the expected output of the ECSS‐E‐ST‐40 and ECSS‐Q‐ST‐80 requirements is summarized in Annex A.  

Annex B and Annex C specify the DRDs (document requirements definitions) of the software product assurance documents (SPAP and SPAMR). The DRDs of  other  software  engineering  and  management  documents  are  included  in ECSS‐E‐ST‐40 and ECSS‐M‐ST‐40. 

In the preparation of this Standard the ISO/IEC 12207 standard has been used extensively, providing a common internationally recognized framework for the terminology and software life cycle processes description.  

The organization of this Standard is reflected in detail in Figure 4‐2. 

19 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>5.1  Organization and responsibility</td>
		<td>5.5  Procurement</td>
	</tr>
	<tr align="center">
		<td>5.2  Software product assurance  programme management</td>
		<td>5.6  Tools and supporting  environment</td>
	</tr>
	<tr align="center">
		<td>5.3  Risk management and critical  item control</td>
		<td rowspan=2>5.7  Assessment and improvement  process</td>
	</tr>
	<tr align="center">
		<td>5.4  Supplier selection and control</td>
	</tr>
</table>

<table align="center">
	<tr align="center">
		<td rowspan=6>Software product assurance programme implementation  5.1  Organization and responsibility 5.2  Software product assurance  5.5  Procurement 5.6  Tools and supporting  programme management environment 5.3  Risk management and critical  5.7  Assessment and improvement  item control process 5.4  Supplier selection and control  </td>
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

<table align="center">
	<tr align="center">
		<td rowspan=5>Software process assurance  6.1  Software development life cycle 6.2  Requirements applicable to all software engineering processes 6.3  Requirements applicable to individual software engineering processes  or activities  </td>
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

<table align="center">
	<tr align="center">
		<td>6.1  Software development life cycle</td>
	</tr>
	<tr align="center">
		<td>6.2  Requirements applicable to all software engineering processes</td>
	</tr>
	<tr align="center">
		<td>6.3  Requirements applicable to individual software engineering processes  or activities</td>
	</tr>
</table>

<table align="center">
	<tr align="center">
		<td rowspan=7>Software product quality assurance  7.1  Product quality objectives and metrication 7.2  Product quality requirements 7.3  Software intended for reuse 7.4  Standard ground hardware and services for operational system 7.5  Firmware  </td>
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

<table align="center">
	<tr align="center">
		<td>7.1  Product quality objectives and metrication</td>
	</tr>
	<tr align="center">
		<td>7.2  Product quality requirements</td>
	</tr>
	<tr align="center">
		<td>7.3  Software intended for reuse</td>
	</tr>
	<tr align="center">
		<td>7.4  Standard ground hardware and services for operational system</td>
	</tr>
	<tr align="center">
		<td>7.5  Firmware</td>
	</tr>
</table>

Figure 4‐2: Structure of this Standard 

Each requirement of this Standard is identified by a hierarchical number, plus a letter  if  necessary  (e.g.  5.3.1.5,  bullet  a).  For  each  requirement,  the  associated output  is  given  in  the  “Expected  Output”  section.  When  several  outputs  are expected, they are identified by a letter (e.g. “a”, “b”, etc.). With each output, the  destination  file  of  the  output  is  indicated  in  brackets,  together  with  the corresponding  document  DRD  (after  a  comma)  and  review(s)  (after  a semicolon). For example: “[PAF, SPAP; SRR]” denotes an output contained in the Software Product Assurance Plan, part of the Product Assurance File, and required at SRR. When no DRD is defined for an Expected Output, and/or the Expected Output is not to be provided at any specific milestone review, then the corresponding sections of that Expected Output are replaced by dashes (e.g. “[PAF, ‐; ‐]”). 

This standards details for the Software Product Assurance aspects some of the general  requirements  already  addressed  by  the  ECSS  Management,  Product Assurance and Quality Assurance standards. 

20 ![Im0](images/Im0)

- 4.3  Tailoring of this Standard

ECSS‐Q‐ST‐80C 6 March 2009 The  general  information  and  requirements  for  the  selection  and  tailoring  of applicable standards are defined in ECSS‐S‐ST‐00. 

There are several drivers for tailoring, such as dependability and safety aspects, software  development  constraints,  product  quality  objectives  and  business objectives.  

Tailoring  for  dependability  and  safety  aspects  is  based  on  the  selection  of requirements  related  to  the  verification,  validation  and  levels  of  proofs demanded by the criticality of the software. Annex D contains a tailoring of this Standard based on software criticality. 

Tailoring  for  software  development  constraints  takes  into  account  the  special characteristics  of  the  software  being  developed,  and  of  the  development environment. The type of software development (e.g. database or real‐time) and the  target  system  (e.g.  embedded  processor,  host  system,  programmable devices, or application‐specific integrated circuits) are also taken into account (see  Annex  S  of  ECSS‐E‐ST‐40).  Specific  requirements  for  verification,  review and  inspection  are  imposed,  for  example,  when  full  validation  on  the  target computer is not feasible or where performance goals are difficult to achieve. Tailoring  for  product  quality  and  business  objectives  is  done  by  selecting requirements on quality of the product as explained in clause 7 of this Standard based on the quality objectives for the product specified by the customer. 

21 ECSS‐Q‐ST‐80C 6 March 2009 Software product assurance programmeimplementation- 5.1  Organization and responsibility

5.1.1  Organization

a.

The supplier shall ensure that an organizational structure is defined for software  development,  and  that  individuals  have  defined  tasks  and responsibilities. 

5.1.2

Responsibility and authority

5.1.2.1

a.

The responsibility, the authority and the interrelation of personnel who manage,  perform  and  verify  work  affecting  software  quality  shall  be defined and documented. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR].

5.1.2.2

a.

The  responsibilities  and  the  interfaces  of  each  organisation,  either external  or  internal,  involved  in  a  project  shall  be  defined  and documented. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR].

5.1.2.3

a.

The  delegation  of  software  product  assurance  tasks  by  a  supplier  to  a lower level supplier shall be done in a documented and controlled way, with the supplier retaining the responsibility towards the customer. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR].

22 ![Im0](images/Im0)

![Im0](images/Im0)

5.1.3

Resources

ECSS‐Q‐ST‐80C 6 March 2009 5.1.3.1

a.

The  supplier  shall  provide  adequate  resources  to  perform  the  required software product assurance tasks. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR].

5.1.3.2

a.

Reviews and audits of processes and of products shall be carried out by personnel not directly involved in the work being performed. 

5.1.4

Software product assurance

manager/engineer

5.1.4.1

a.

The  supplier  shall  identify  the  personnel  responsible  for  software product assurance for the project (SW PA manager/engineer). 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR].

5.1.4.2

a.

The software product assurance manager/engineer shall 

1.

report  to  the  project  manager  (through  the  project  product assurance manager, if any); 

have  organisational  authority  and  independence  to  propose  and maintain a software product assurance programme in accordance with the project software product assurance requirements; 

have  unimpeded  access  to  higher  management  as  necessary  to fulfil his/her duties. 

2.

3.

5.1.5

Training

5.1.5.1

a.

The supplier shall review the project requirements to establish and make timely provision for acquiring or developing the resources and skills for the management and technical staff. 

EXPECTED OUTPUT:  Training plan [MGT, -; SRR].

5.1.5.2

a.

The supplier shall maintain training records. 

EXPECTED OUTPUT:  Records of training and experience [PAF, -; -].

23 ![Im0](images/Im0)

5.1.5.3

a.

ECSS‐Q‐ST‐80C 6 March 2009 The  supplier  shall  ensure  that  the  right  composition  and  categories  of appropriately  trained  personnel  are  available  for  the  planned  activities and tasks in a timely manner. 

5.1.5.4

a.

The supplier shall determine the training subjects based on the specific tools,  techniques,  methodologies  and  computer  resources  to  be  used  in the development and management of the software product.  

NOTE 

Personnel can undergo training to acquire skills 

and  knowledge  relevant  to  the  specific  field 

with which the software is to deal. 

- 5.2  Software product assurance programme management

5.2.1

Software product assurance planning andcontrol

5.2.1.1

a.

The supplier shall develop a software product assurance plan in response to  the  software  product  assurance  requirements  in  conformance  with DRD in annex B. 

The  software  product  assurance  plan  shall  be  either  a  standalone document or a section of the supplier overall product assurance plan. EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

b.

SPAP; SRR, PDR].

5.2.1.2

a.

Any  internal  manuals,  standards  or  procedures  referred  to  by  the software  product  assurance  plan  shall  become  an  integral  part  of  the supplier’s software product assurance programme. 

5.2.1.3

a.

The  software  product  assurance  plan shall  be  revisited  and updated  as needed at each milestone to ensure that the activities to be undertaken in the following phase are fully defined. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; CDR, QR, AR, ORR].

5.2.1.4

a.

Before  acceptance  review,  the  supplier  shall  either  supplement  the software product assurance plan to specify the quality measures related 24 ECSS‐Q‐ST‐80C 6 March 2009 to the operations and maintenance processes, or issue a specific software product assurance plan.  

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; AR].

5.2.1.5

a.

The  supplier  shall  provide  with  the  software  product  assurance  plan  a compliance  matrix  documenting  conformance  with  the  individual software  product  assurance  requirements  applicable  for  the  project  or business agreement. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

b.

For each software product assurance requirement, the compliance matrix shall provide a reference to the document where the expected output of that requirement is located. 

NOTE 

For  compliance  with  the  required  DRDs  a 

general statement of compliance is acceptable. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

Software product assurance reporting

5.2.2

5.2.2.1

a.

The supplier shall report on a regular basis on the status of the software product assurance programme implementation, if appropriate as part of the overall product assurance reporting of the project. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

5.2.2.2

a.

The software product assurance report shall include: 

1.

an assessment of the current quality of the product and processes, based on measured properties, with reference to the metrication as defined in the software product assurance plan; 

verifications undertaken; 

problems detected; 

problems resolved.  

2.

3.

4.

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

5.2.2.3

a.

The  supplier  shall  deliver  at  each  milestone  review  a  software  product assurance  milestone  report,  covering  the  software  product  assurance activities performed during the past project phases. 

EXPECTED OUTPUT:  Software product assurance milestone report

[PAF,  SPAMR;  SRR,  PDR,  CDR,  QR,  AR,

ORR].

25 ![Im0](images/Im0)

![Im0](images/Im0)

Audits

ECSS‐Q‐ST‐80C 6 March 2009 For software audits, ECSS‐Q‐ST‐10 clause 5.2.3 shall apply. 

EXPECTED OUTPUT:  Audit plan and schedule [PAF, -; SRR].

5.2.3

a.

5.2.4

a.

Alerts

For software alerts, ECSS‐Q‐ST‐10 clause 5.2.9 shall apply. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Preliminary alert information [PAF, -; -];

b.  Alert information [PAF, -; -].

5.2.5

Software problems

5.2.5.1

a.

The  supplier  shall  define  and  implement  procedures  for  the  logging, analysis  and  correction  of  all  software  problems  encountered  during software development. 

EXPECTED OUTPUT:  Software  problem

reporting  procedures

[PAF, -; PDR].

5.2.5.2

a.

The software problem report shall contain the following information: 1.

2.

3.

4.

5.

6.

EXPECTED OUTPUT:  Software  problem

identification of the software item; 

description of the problem; 

recommended solution; 

final disposition; 

modifications implemented (e.g. documents, code, and tools); 

tests re‐executed. 

reporting  procedures

[PAF, -; PDR].

5.2.5.3

a.

The procedures for software problems shall define the interface with the nonconformance  system  (i.e.  the  circumstances  under  which  a  problem qualifies as a nonconformance). 

EXPECTED OUTPUT:  Software  problem

reporting  procedures

[PAF, -; PDR].

5.2.5.4

a.

The  supplier  shall  ensure  the  correct  application  of  problem  reporting procedures. 

26 ![Im0](images/Im0)

5.2.6

Nonconformances

ECSS‐Q‐ST‐80C 6 March 2009 5.2.6.1

a.

For software nonconformance handling, ECSS‐Q‐ST‐10‐09 shall apply  EXPECTED OUTPUT:  The following outputs are expected:

a.  NCR  SW  procedure  as  part  of  the  Softwareproduct assurance plan [PAF, SPAP; SRR];b.  Nonconformance reports [DJF, -; -].

b.  When dealing with software nonconformance, the NRB shall include, at least,  a  representative  from  the  software  product  assurance  and  the software engineering organizations. 

EXPECTED OUTPUT:  Identification of SW experts in NRB [MGT, -;

SRR]

5.2.6.2

a.

The  software  product  assurance  plan  shall  specify  the  point  in  the software life cycle from which the nonconformance procedures apply. EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

5.2.7  Quality requirements and quality models

5.2.7.1

a.

Quality  models  shall  be  used 

requirements. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

to  specify 

the  software  quality SPAP; PDR].

5.2.7.2

a.

The following characteristics shall be used to specify the quality model: 1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

functionality; 

reliability; 

maintainability; 

reusability; 

suitability for safety; 

security; 

usability; 

efficiency; 

portability; 

software development effectiveness. 

27 ECSS‐Q‐ST‐80C 6 March 2009 NOTE 1  Quality models are the basis for the identification 

of  process  metrics  (see  clause  6.2.5)  and  product 

metrics (see clause 7.1.4). 

NOTE 2  quality models are also addressed by ISO/IEC 9126 

or ECSS‐Q‐HB‐80‐04. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

- 5.3  Risk management and critical item control

Risk management

5.3.1

a.

Risk management for software shall be performed by cross‐reference to the project risk policy, as specified in ECSS‐M‐ST‐80. 

5.3.2

Critical item control

5.3.2.1

a.

5.3.2.2

a.

For critical item control, ECSS‐Q‐ST‐10‐04 shall apply. 

The supplier shall identify the characteristics of the software items that qualify them for inclusion in the Critical Item List. 

- 5.4  Supplier selection and control

5.4.1

Supplier selection

5.4.1.1

a.

For supplier selection ECSS‐Q‐ST‐20 clause 5.4.1 shall apply. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Results  of  pre-award  audits  and  assessments[PAF, -; -];

b.  Records of procurement sources [PAF, -; -].For  the  selection  of  suppliers  of  existing  software,  including  software contained in OTS equipments and units, the expected output of clauses 6.2.7.2 to 6.2.7.6 shall be made available. 

EXPECTED OUTPUT:  Software reuse file [DJF, SRF; -].

5.4.1.2

a.

28 ![Im0](images/Im0)

![Im0](images/Im0)

5.4.2

Supplier requirements

ECSS‐Q‐ST‐80C 6 March 2009 5.4.2.1

a.

The supplier shall establish software product assurance requirements for the next level suppliers, tailored to their role in the project, including a requirement to produce a software product assurance plan. 

EXPECTED OUTPUT:  Software product assurance requirements for

suppliers [PAF, -; SRR].

5.4.2.2

a.

The supplier shall provide the software product assurance requirements applicable to the next level suppliers for customer’s acceptance. 

EXPECTED OUTPUT:  Software product assurance requirements for

suppliers [PAF, -; SRR].

5.4.3

Supplier monitoring

5.4.3.1

a.

The supplier shall monitor the next lower level suppliers’ conformance to the product assurance requirements.  

5.4.3.2

a.

level  suppliers’  product  assurance  plans, 

The monitoring process shall include the review and approval of the next lower 

the  continuous verification  of  processes  and  products,  and  the  monitoring  of  the  final validation of the product. 

5.4.3.3

a.

The  supplier  shall  ensure  that  software  development  processes  are defined  and  applied  by  the  next  lower  level  suppliers  in  conformance with the software product assurance requirements for suppliers. 

EXPECTED OUTPUT:  Next

software  product

suppliers’

level

assurance plan [PAF, SPAP; PDR].

5.4.3.4

a.

The  supplier  shall  provide  the  next  lower  level  suppliers’  software product assurance plan for customer’s acceptance. 

EXPECTED OUTPUT:  Next

software  product

suppliers’

level

assurance plan [PAF, SPAP; PDR].

29 ![Im0](images/Im0)

5.4.4

a.

Criticality classification

ECSS‐Q‐ST‐80C 6 March 2009 The  supplier  shall  provide  the  lower  level  suppliers  with  the  relevant results of the safety and dependability analyses performed at higher and his level (ref. clauses 6.2.2.1 and 6.2.2.2), including: 

1.

the  criticality  classification  of  the  software  products  to  be developed; 

information about the failures that can be caused at higher level by the software products to be developed. 

2.

EXPECTED OUTPUT:  Safety and dependability analyses results for

lower level suppliers [RB, -; SRR].

- 5.5  Procurement

Procurement documents

For procurement documents, ECSS‐Q‐ST‐20 clause 5.4.2 shall apply. 

Review of procured software component listThe  choice  of  procured  software  shall  be  described  and  submitted  for customer review. 

EXPECTED OUTPUT:  Software  development  plan  [MGT,  SDP;

SRR, PDR].

Procurement details

For each of the software items the following data shall be provided: 

1.

ordering criteria 

NOTE 

For example: versions, options and extensions. 

2.

3.

4.

receiving inspection criteria; 

back‐up solutions if the product becomes unavailable; 

contractual  arrangements  with  the  supplier  for  the  development, maintenance and upgrades to new releases. 

EXPECTED OUTPUT:  Procurement data [MGT, -; SRR, PDR].

5.5.1

a.

5.5.2

a.

5.5.3

a.

5.5.4

a.

5.5.5

a.

All  the  procured  software  shall  be  identified  and  registered  by configuration management. 

Identification

Inspection

The supplier shall subject the procured software to a planned receiving inspection,  in  accordance  with  ECSS‐Q‐ST‐20  clause  5.4.4,  and  the receiving inspection criteria as required by clause 5.5.3. 

EXPECTED OUTPUT:  Receiving  inspection  report  [PAF,  -;  PDR,

CDR, QR].

30 ![Im0](images/Im0)

Exportability

ECSS‐Q‐ST‐80C 6 March 2009 5.5.6

a.

Exportability constraints shall be identified. 

- 5.6  Tools and supporting environment

5.6.1  Methods and tools

(including 

5.6.1.1

a.  Methods  and  tools  to  be  used  for  all  the  activities  of  the  development specification, cycle, 

modelling,  design, 

configuration management,  verification and  product assurance)  shall  be identified  by the supplier and agreed by the customer. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

requirements  analysis, 

validation, 

software 

testing, 

coding, 

SPAP; SRR, PDR].

5.6.1.2

a.

The  choice  of  development  methods  and  tools  shall  be  justified  by demonstrating through testing or documented assessment that: 

1.

the  development  team  has  appropriate  experience  or  training  to apply them, 

the  tools  and  methods  are  appropriate  for  the  functional  and operational characteristics of the product, and 

the tools are available (in an appropriate hardware environment) throughout  the  development  and  maintenance  lifetime  of  the product. 

2.

3.

EXPECTED OUTPUT:  Software product assurance milestone report

[PAF, SPAMR; SRR, PDR].

5.6.1.3

a.

The correct use of methods and tools shall be verified and reported.  

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

5.6.2

Development environment selection

5.6.2.1

a.

The  software  development  environment  shall  be  selected  according  to the following criteria: 

1.

2.

availability; 

compatibility; 

31 ECSS‐Q‐ST‐80C 6 March 2009 the  operational technical  consistency  with 

3.

4.

5.

6.

7.

8.

9.

10.

performance; 

maintenance; 

durability  and 

equipment; 

the  assessment  of  the  product  with  respect  to  requirements, including the criticality category; 

the available support documentation; 

the acceptance and warranty conditions; 

the conditions of installation, preparation, training and use; 

the  maintenance  conditions, 

evolutions; 

copyright and intellectual property rights constraints; 

dependence on one specific supplier. 

11.

12.

EXPECTED OUTPUT:  Software  development  plan  [MGT,  SDP;

including 

the  possibilities  of SRR, PDR].

5.6.2.2

a.

The  suitability  of  the  software  development  environment  shall  be justified. 

EXPECTED OUTPUT:  Software  development  plan  [MGT,  SDP;

SRR, PDR].

5.6.2.3

a.

The availability of the software development environment to developers and  other  users  shall  be  verified  before  the  start  of  each  development phase. 

- 5.7  Assessment and improvement process

Process assessment

5.7.1

a.

The supplier shall monitor and control the effectiveness of the processes used  during  the  development  of  the  software,  including  the  relevant processes corresponding to the services called from other organizational entities outside the project team. 

NOTE 

The  process  assessment  and 

improvement 

performed at organization level can be used to 

provide evidence of compliance for the project. 

records:

improvement

process

assessments

assessment

EXPECTED OUTPUT:  Software

Overall

and

programme plan [PAF, -; -].

32 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Assessment process

The process assessment model and method to be used when performing any software process assessment shall be documented.  

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software process assessment record: assessmentmodel [PAF, -; -];

b.  Software process assessment record: assessmentmethod [PAF, -; -].

Assessments performed and process assessment models used shall be in conformance with ISO/IEC 15504 (Part 2). 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software process assessment record: evidence ofconformance  of  the  process  assessment  model[PAF, -; -];

b.  Software process assessment record: assessmentmethod [PAF, -; -].

NOTE 1  The  model  and  method  documented  in  ECSS‐Q‐

HB‐80‐02 are conformant to ISO/IEC 15504 (Part 2). 

NOTE 2  Currently the CMMI model is not fully conformant 

it  can  be  used, 

to  ISO/IEC  15504,  however 

provided that the SCAMPI A method is applied. 

5.7.2

5.7.2.1

a.

5.7.2.2

a.

5.7.2.3

a.

The  process  assessment  model,  the  method,  the  assessment  scope,  the results and the assessors shall be verified as complying with the project requirements. 

NOTE 1  Examples of assessment scopes are: organizational 

unit evaluated, and processes evaluated. 

NOTE 2  ECSS‐Q‐HB‐80‐02  provides  space  specific  process 

reference model and their indicators. 

EXPECTED OUTPUT:  Software

process

record:

Software  process  assessment  recognition

evidence [PAF, -; -].

assessment

5.7.2.4

a.

Assessments, carried out in accordance with ECSS‐Q‐HB‐80‐02, shall be performed by a competent assessor, whereas the other assessment team members can be either competent assessor or provisional assessor. 

NOTE 1  For  other  assessment  schemes  conformant  to 

ISO/IEC  15504  (Part  2),  assessors  certified  under 

INTRSA are competent assessors. 

NOTE 2  When  using  CMMI/SCAMPI  A,  SEI  authorized 

EXPECTED OUTPUT:  Software

lead appraisers are competent assessors. 

assessment

process

record:

competent assessor justification [PAF, -; -].

33 ![Im0](images/Im0)

![Im0](images/Im0)

5.7.3

Process improvement

ECSS‐Q‐ST‐80C 6 March 2009 5.7.3.1

a.

b.

The  results  of  the  assessment  shall  be  used  as  feedback  to  improve  as necessary  the  performed  processes,  to  recommend  changes  in  the direction of the project, and to determine technology advancement needs. The  suppliers  shall  ensure  that  the  results  of  previous  assessments  are used in its project activity  

EXPECTED OUTPUT:  Software

assessment

records:

process

improvement plan [PAF, -; -].

5.7.3.2

a.

The process improvement shall be conducted according to a documented process improvement process. 

NOTE 1  For  the  definition  of  the  process  improvement 

process, see ECSS‐Q‐HB‐80‐02. 

NOTE 2  For CMMI, the process improvement is described 

in the OPF (Organizational Process Focus) process 

area. 

EXPECTED OUTPUT:  Software

assessment

improvement process [PAF, -; -].

process

records:

5.7.3.3

a.

Evidence  of  the  improvement  in  performed  processes  or  in  project documentation shall be provided. 

NOTE 

See ECSS‐Q‐HB‐80‐02. 

EXPECTED OUTPUT:  Software

process

assessment

records:

evidence of improvements [PAF, -; -].

34 ECSS‐Q‐ST‐80C 6 March 2009 Software process assurance- 6.1  Software development life cycle

6.1.1

a.

b.

Life cycle definition

The software development life cycle shall be defined or referenced in the software product assurance plan. 

The following characteristics of the software life cycle shall be defined: 1.

2.

3.

4.

5.

6.

7.

phases; 

input and output of each phase; 

status of completion of phase output; 

milestones; 

dependencies; 

responsibilities; 

role of the customer at each milestone review, in conformance with ECSS‐M‐ST‐10 and ECSS‐M‐ST‐10‐01. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

Process quality objectives

In  the  definition  of  the  life  cycle  and  associated  milestones  and documents, the quality objectives shall be used. 

Life cycle definition review

The software life cycle shall be reviewed against the contractual software engineering and product assurance requirements.  

6.1.2

a.

6.1.3

a.

6.1.4

a.

Life cycle resources

The  software  life  cycle  shall  be  reviewed  for  suitability  and  for  the availability of resources to implement it by all functions involved in its application. 

35 ![Im0](images/Im0)

![Im0](images/Im0)

6.1.5

a.

Software validation process schedule

ECSS‐Q‐ST‐80C 6 March 2009 A milestone (SW TRR as defined in ECSS‐E‐ST‐40 clause 5.3.5.1) shall be scheduled  immediately  before  the  software  validation  process  starts,  to check that: 

1.

the  software  status  is  compatible  with  the  commencement  of validation activities; 

the necessary resources, software product assurance plans, test and validation documentation, simulators or other technical means are available and ready for use. 

2.

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

- 6.2  Requirements applicable to all software engineering

processes

6.2.1

6.2.1.1

a.

Documentation of processes

The following activities shall be covered either in software‐specific plans or in project general plans: 

1.

2.

3.

4.

5.

EXPECTED OUTPUT:  Software project plans [MGT, MF, DJF].

development; 

specification, design and customer documents to be produced; configuration and documentation management; 

verification, testing and validation activities; 

maintenance. 

All plans shall be finalized before the start of the related activities. 

EXPECTED OUTPUT:  Software project plans [MGT, MF, DJF].

6.2.1.2

a.

6.2.1.3

a.

6.2.1.4

a.

All  plans  shall  be  updated  for  each  milestone  to  reflect  any  changes during development. 

EXPECTED OUTPUT:  Software project plans [MGT, MF, DJF].

The  software  product  assurance  plan  shall  identify  all  plans  to  be produced  and  used,  the  relationship  between  them  and  the  time‐scales for their preparation and update. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

36 ![Im0](images/Im0)

6.2.1.5

a.

Each  plan  shall  be  reviewed  against 

requirements.  

ECSS‐Q‐ST‐80C 6 March 2009 the  relevant  contractual 6.2.1.6

a.

Procedures  and  project  standards  shall  address  all  types  of  software products included in the project. 

EXPECTED OUTPUT:  Procedures and standards [PAF, -; PDR].

6.2.1.7

a.

All procedures and project standards shall be finalized before starting the related activities. 

EXPECTED OUTPUT:  Procedures and standards [PAF, -; PDR].

6.2.1.8

a.

Each procedure or standard shall be reviewed against the relevant plans and contractual requirements. 

6.2.1.9

a.

Before any activity is started, each procedure or standard for that activity shall  be  reviewed  by  all  functions  involved  in  its  application,  for suitability and for the availability of resources to implement it. 

6.2.2

Software dependability and safety

6.2.2.1

a.

For  the  system‐level  analyses  leading  to  the  criticality  classification  of software products based on the severity of failures consequences, ECSS‐Q‐ST‐40 Table 6‐1, and ECSS‐Q‐ST‐30 Table 5‐1, shall apply. 

EXPECTED OUTPUT:  Criticality classification of software products

[PAF, -; SRR, PDR].

6.2.2.2

a.

The supplier shall perform a software dependability and safety analysis of the software products, in accordance with the requirements of ECSS‐Q‐ST‐30  and ECSS‐Q‐ST‐40  and  using the  results  of  system‐level  safety and  dependability  analyses,  in  order  to  determine  the  criticality  of  the individual software components. 

EXPECTED OUTPUT:  Software  dependability  and  safety  analysis

report [PAF, -; PDR].

37 ![Im0](images/Im0)

6.2.2.3

a.

ECSS‐Q‐ST‐80C 6 March 2009 The supplier shall identify the methods and techniques for the software dependability  and  safety  analysis  to  be  performed  at  technical specification and design level. 

b.  Methods and techniques for software dependability and safety analysis shall be agreed between the supplier and customer. 

NOTE 

indication  on 

ECSS‐Q‐HB‐80‐03  provides 

methods  and  techniques  that  can  be  applied 

such as:  

•  software 

and 

criticality analysis (for the performing of this 

analysis, see also ECSS‐Q‐ST‐30‐02); 

failure  modes, 

effects 

•  software fault tree analysis; 

•  software common cause failure analysis. 

EXPECTED OUTPUT:  Criticality

classification

components [PAF, -; PDR].

of

software

6.2.2.4

a.

Based on the results of the software criticality analysis, the supplier shall apply  engineering  measures  to  reduce  the  number  of  critical  software components  and  mitigate  the  risks  associated  with  the  critical  software (ref. clause 6.2.3). 

6.2.2.5

a.

The  supplier  shall  report  on  the  status  of  the  implementation  and verification 

analysis recommendations. 

EXPECTED OUTPUT:  Software  dependability  and  safety  analysis

SW  dependability 

safety 

and 

of 

the 

report [PAF, -; CDR, QR, AR].

6.2.2.6

a.

The supplier shall update the software dependability and safety analysis at  each  software  development  milestone,  to  confirm  the  criticality category of software components. 

EXPECTED OUTPUT:  Software  dependability  and  safety  analysis

report [PAF, -; CDR, QR, AR].

6.2.2.7

a.

The supplier shall provide the results of the software dependability and safety  analysis  for  integration  into  the  system‐level  dependability  and safety analyses, addressing in particular: 

1.

2.

additional failure modes identified at software design level; 

recommendations for system‐level activities. 

38 ECSS‐Q‐ST‐80C 6 March 2009 NOTE 

For example: introduction of hardware inhibits, 

and modifications of the system architecture. 

EXPECTED OUTPUT:  Software  dependability  and  safety  analysis

report [PAF, -; PDR, CDR].

6.2.2.8

a.

As part of the software requirements analysis activities (ref. clause 6.3.2), the  supplier  shall  contribute  to  the  Hardware‐Software  Interaction Analysis (HSIA) by identifying, for each hardware failure included in the HSIA, the requirements that specify the software behaviour in the event of that hardware failure. 

6.2.2.9

a.

During  the  verification  and  validation  of  the  software  requirements resulting from the Hardware‐Software Interaction Analysis, the supplier shall verify that the software reacts correctly to hardware failures, and no undesired software malfunctions occur that may lead to system failures. 6.2.3

Handling of critical software

6.2.3.1

a.

The supplier shall define and implement measures to avoid propagation of failures between software components of different criticality. 

NOTE 

This can be achieved by design measures such 

as  separate  hardware  platforms,  isolation  of 

software  processes  or  prohibition  of  shared 

memory (segregation and partitioning).  

b.

Software  components  whose  malfunction  may  cause  failures  of  higher criticality  components  shall  be  classified  in  accordance  with  the consequences of those failures. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software  product  assurance  plan  [PAF,  SPAP;PDR, CDR];

b.  Software  dependability  and  safety  analysisreport [PAF, -; PDR, CDR, QR, AR].

6.2.3.2

a.

The  supplier  shall  define,  justify  and  apply  measures  to  assure  the dependability and safety of critical software. 

NOTE 

These measures can include: 

•  use of software design or methods that have 

similar 

performed 

application; 

insertion of features for failure isolation and 

handling  (ref.  ECSS‐Q‐HB‐80‐03,  software 

a 

successfully 

in 

•

39 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 failure  modes, 

analysis); 

effects 

and 

criticality 

•  defensive programming techniques, such as 

input verification and consistency checks; 

•  use  of  a  “safe  subset”  of  programming 

language; 

•  use  of  formal  design  language  for  formal 

proof; 

•  100 %  code  branch  coverage  at  unit  testing 

level; 

full inspection of source code; 

•

•  witnessed or independent testing; 

•  gathering and analysis of failure statistics; 

•  removing  deactivated  code  or  showing 

through  a  combination  of  analysis  and 

testing  that  the  means  by  which  such  code 

can 

are 

prevented, isolated, or eliminated. 

inadvertently 

executed 

be 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR, CDR].

6.2.3.3

a.

The  application  of  the  chosen  measures  to  handle  the  critical  software shall be verified. 

EXPECTED OUTPUT:  Software product assurance milestone report

[PAF, SPAMR; PDR, CDR, QR, AR].

6.2.3.4

a.

Critical software shall be subject to regression testing after: 

1.

any change of functionality of the underlying platform hardware; NOTE 

For example:  instruction set of a processor. 

2.

any  change  of  the  tools  that  affect  directly  or  indirectly  the generation of the executable code. 

NOTE 

In case of minor changes in tools that affect the 

generation  of  the  executable  code,  a  binary 

comparison of the executable code generated by 

the different tools can be used to verify that no 

modifications are introduced. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR, CDR].

40 ![Im0](images/Im0)

![Im0](images/Im0)

6.2.3.5

a.

ECSS‐Q‐ST‐80C 6 March 2009 The  need  for  additional  verification  and  validation  of  critical  software shall be analysed after: 

1.

any  change  of  functionality  or  performance  of  the  underlying platform hardware; 

any  change  in  the  environment  in  which  the  software  or  the platform hardware operate. 

2.

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR, CDR].

6.2.3.6

a.

Identified  unreachable  code  shall  be  removed  and  the  need  for  re‐verification and re‐validation shall be analysed.  

6.2.3.7

a.

Unit and integration testing shall be (re‐)executed on non‐instrumented code. 

6.2.3.8

a.

Validation testing shall be (re‐)executed on non‐instrumented code. 

6.2.4

Software configuration management

6.2.4.1

a.

ECSS‐M‐ST‐40 shall be applied for software configuration management, complemented by the following requirements. 

6.2.4.2

a.

The  software  configuration  management  system  shall  allow  any reference version to be re‐generated from backups. 

EXPECTED OUTPUT:  Software  configuration  management  plan

[MGT, SCMP; SRR, PDR].

6.2.4.3

a.

The software configuration file and the software release document shall be provided with each software delivery. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software configuration file [DDF, SCF; -];

b.  Software release document [DDF, SRelD; -].41 ![Im0](images/Im0)

6.2.4.4

a.

ECSS‐Q‐ST‐80C 6 March 2009 The software configuration file shall be available and up to date for each project milestone. 

EXPECTED OUTPUT:  Software  configuration

file  [DDF,  SCF;

CDR, QR, AR, ORR].

6.2.4.5

a.

b.

Any components of the code generation tool that are customizable by the user shall be put under configuration control. 

The change control procedures defined for the project shall address the specific aspects of these components. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software  configuration  file  [DDF,  SCF;  CDR,QR, AR, ORR];

b.  Software configuration management plan [MGT,SCMP; SRR, PDR].

The supplier shall ensure that all authorized changes are implemented in accordance with the software configuration management plan. 

EXPECTED OUTPUT:  Authorized changes - Software configuration

file [DDF, SCF; CDR, QR, AR, ORR].

6.2.4.6

a.

6.2.4.7

a.

2.

3.

The  following  documents  shall  be  controlled  (see  ECSS‐Q‐ST‐10  clause 5.2.5): 

1.

procedural documents describing the quality system to be applied during the software life cycle; 

planning documents describing the planning and progress of the activities; 

documents describing a particular software product, including: (a)

(b)

(c)

(d)

(e)

(f)

development phase inputs, 

development phase outputs, 

verification and validation plans and results, 

test case specifications, test procedures and test reports, 

traceability matrices, 

documentation  for  the  software  and  system  operators  and users, and 

(g)  maintenance documentation. 

42 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 The  supplier  shall  identify  a  method  and  tool  to  protect  the  supplied software against corruption. 

6.2.4.8

a.

NOTE 

For example: source, executable and data. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software  product  assurance  plan  [PAF,  SPAP;SRR, PDR];

b.  Software  configuration  file  [DDF,  SCF;  CDR,QR, AR, ORR].

6.2.4.9

a.

The  supplier  shall  define  a  checksum‐type  key  calculation  for  the delivered operational software. 

NOTE 

For example: executable binary, database.  

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

6.2.4.10

a.

The checksum value shall be provided in the software configuration file with each software delivery. 

EXPECTED OUTPUT:  Software configuration file [DDF, SCF; -].

6.2.4.11

a.

The media through which the software is delivered to the customer shall be  marked  by  the  supplier  indicating  the  following  information  as  a minimum: 

1.

2.

3.

EXPECTED OUTPUT:  The following outputs are expected:

the software name; 

the version number; 

the reference to the software configuration file. 

a.  Software  product  assurance  plan  [PAF,  SPAP;SRR, PDR];

b.  Labels [DDF, -; -].

Process metrics

6.2.5

6.2.5.1

a.  Metrics  shall  be  used  to  manage  the  development  and  to  assess  the quality of the development processes.  

NOTE 

Process  metrics  are  based  on  quality  models 

(see clause 5.2.7). 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

43 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 6.2.5.2

a.

Process metrics shall be collected, stored and analysed on a regular basis by applying quality models and procedures.  

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

6.2.5.3

a.

The  following  basic  process  metrics  shall  be  used  within  the  supplier’s organization:  

1.

duration:  how  phases  and  tasks  are  being  completed  versus  the planned schedule; 

effort:  how  much  effort  is  consumed  by  the  various  phases  and tasks compared to the plan. 

2.

EXPECTED OUTPUT:  Internal metrics report.

6.2.5.4

a.

Process  metrics  shall  be  used  within  the  supplier’s  organization  and reported to the customer, including: 

1.

2.

number of problems detected during verification; 

number  of  problems  detected  during  integration  and  validation testing and use.  

NOTE 

See  also  software  problem  reporting  described 

in clause 5.2.5. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.2.5.5

a.  Metrics  reports  shall  be  included  in  the  software  product  assurance reports. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

Verification

6.2.6

6.2.6.1

a.

Activities  for  the  verification  of  the  quality  requirements  shall  be specified in the definition of the verification plan.  

NOTE 

inspection, 

Verification includes various techniques such as 

review, 

testing,  walk‐through, 

cross‐reading, 

model 

simulation, and many types of analysis such as 

traceability  analysis,  formal  proof  or  fault  tree 

analysis.  

desk‐checking, 

EXPECTED OUTPUT:  Software  verification  plan  [DJF,  SVerP;

PDR].

44 ![Im0](images/Im0)

6.2.6.2

a.

b.

ECSS‐Q‐ST‐80C 6 March 2009 The  outputs  of  each  development  activity  shall  be  verified  for conformance against pre‐defined criteria. 

Only outputs which have been subjected to planned verifications shall be used as inputs for subsequent activities. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.2.6.3

a.

A summary of the assurance activities concerning the verification process and  their  findings  shall  be  included  in  software  product  assurance reports. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.2.6.4

a.

The completion of actions related to software problem reports generated during verification shall be verified and recorded. 

EXPECTED OUTPUT:  Software  problem  reports  [DJF,  -;  SRR,

PDR, CDR, QR, AR, ORR].

6.2.6.5

a.

Software  containing  deactivated  code  shall  be  verified  specifically  to ensure that the deactivated code cannot be activated or that its accidental activation cannot harm the operation of the system. 

EXPECTED OUTPUT:  Software  verification  report  [DJF,  SVR;

CDR, QR, AR].

6.2.6.6

a.

Software  containing  configurable  code  shall  be  verified  specifically  to ensure that any unintended configuration cannot be activated at run time or included during code generation. 

EXPECTED OUTPUT:  Software  verification  report  [DJF,  SVR;

CDR, QR, AR].

6.2.6.7

a.

The supplier shall ensure that: 

1.

the planned verification activities are adequate to confirm that the products  of  each  phase  are  conformant  to  the  applicable requirements; 

the verification activities are performed according to the plan.  2.

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

45 ![Im0](images/Im0)

6.2.6.8

a.

ECSS‐Q‐ST‐80C 6 March 2009 Reviews  and  inspections  shall  be  carried  out  according  to  defined criteria,  and  according  to  the  defined  level  of  independence  of  the reviewer from the author of the reviewed item.  

6.2.6.9

a.

Each  review  and  inspection  shall  be  based  on  a  written  plan  or procedure. 

NOTE 

For  projects  reviews,  ECSS‐E‐ST‐40  clause 

5.3.3.3, bullet b and Annex P are applicable. 

EXPECTED OUTPUT:  Review  and  inspection  plans  or  procedures

[PAF, -; -].

6.2.6.10

a.

The review or inspection plans or procedures shall specify:  

1.

2.

3.

4.

5.

EXPECTED OUTPUT:  Review  and  inspection  plans  or  procedures

the reviewed or inspected items; 

the person in charge; 

the participants; 

the means of review or inspection (e.g. tools or check list); 

the nature of the report. 

[PAF, -; -].

6.2.6.11

a.

Review and inspection reports shall: 

1.

2.

refer to the corresponding review/inspection procedure or plan;  identify  the  reviewed  item,  the  author,  the  reviewer,  the  review criteria and the findings of the review. 

EXPECTED OUTPUT:  Review and inspection reports [PAF, -; -].

6.2.6.12

a.

Traceability  matrices  (as  defined  in  ECSS‐E‐ST‐40  clause  5.8)  shall  be verified at each milestone. 

EXPECTED OUTPUT:  Software product assurance milestone report

[PAF,  SPAMR;  SRR,  PDR,  CDR,  QR,  AR,

ORR].

6.2.6.13

a.

b.

Independent software verification shall be performed by a third party. Independent  software  verification  shall  be  a  combination  of  reviews, inspections, analyses, simulations, testing and auditing. 

46 ECSS‐Q‐ST‐80C 6 March 2009 NOTE 

This  requirement  is  applicable  where the  risks 

associated  with  the  project  justify  the  costs 

involved.  The  customer  can  consider  a  less 

rigorous 

independence,  e.g.  an 

independent team in the same organization. 

level  of 

EXPECTED OUTPUT:  The following outputs are expected:

a.  ISVV plan [DJF, -; SRR, PDR];

b.  ISVV report [DJF, -; PDR, CDR, QR, AR].

6.2.7

Reuse of existing software

General

6.2.7.1

The  requirements  in  6.2.7  do  not  apply  to  tools  and  software  development environment, for which requirements of clause 5.6 apply. 

6.2.7.2

a.

Analyses of the advantages to be obtained with the selection of existing software (ref. 3.2.11) instead of new development shall be carried out. EXPECTED OUTPUT:  The following outputs are expected:

a.  Software reuse approach, including approach todelta qualification [PAF, SPAP; SRR, PDR];b.  Software reuse file [DJF, SRF; SRR, PDR].

6.2.7.3

a.

6.2.7.4

a.

The  existing  software  shall  be  assessed  with  regards  to  the  applicable functional, performance and quality requirements. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software reuse approach, including approach todelta qualification [PAF, SPAP; SRR, PDR];b.  Software reuse file [DJF, SRF; SRR, PDR].

The quality level of the existing software shall be analysed with respect to  the  project  requirements,  according  to  the  criticality  of  the  system function implemented, taking into account the following aspects: 

1.

2.

3.

software requirements documentation; 

software architectural and detailed design documentation; 

forward and backward traceability between system requirements, software requirements, design and code; 

unit tests documentation and coverage; 

integration tests documentation and coverage; 

validation documentation and coverage; 

verification reports; 

performance; 

4.

5.

6.

7.

8.

47 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 NOTE 

For example: memory occupation, CPU load. 

9.

10.

11.

operational performances; 

residual nonconformances and waivers; 

user operational documentation; 

NOTE 

For example: user manual. 

code quality (adherence to coding standards, metrics). 

12.

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software reuse approach, including approach todelta qualification [PAF, SPAP; SRR, PDR];b.  Software reuse file [DJF, SRF; SRR, PDR].

6.2.7.5

a.

The  results  of  the  reused  software  analysis  shall  be  recorded  in  the software reuse file, together with an assessment of the possible level of reuse  and  a  description  of  the  assumptions  and  the  methods  applied when estimating the level of reuse. 

NOTE 

Results of the reused software analysis, such as 

detailed  reference  to  requirement  and  design 

documents, test reports and coverage results. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software reuse approach, including approach todelta qualification [PAF, SPAP; SRR, PDR];b.  Software reuse file [DJF, SRF; SRR, PDR].

6.2.7.6

a.

The  analysis  of  the  suitability  of  existing  software  for  reuse  shall  be complemented by an assessment of the following aspects: 

1.

2.

3.

4.

5.

the acceptance and warranty conditions; 

the available support documentation;  

the conditions of installation, preparation, training and use;  

the identification and registration by configuration management;  maintenance 

possibilities of changes;  

the durability and validity of methods and tools used in the initial development, that are envisaged to be used again;  

the  copyright  and 

(modification rights);  

the licensing conditions; 

exportability constraints. 

8.

9.

EXPECTED OUTPUT:  Software reuse file [DJF, SRF; SRR, PDR].

intellectual  property  rights  constraints 6.

7.

responsibility  and 

conditions, 

including 

the 48 ![Im0](images/Im0)

![Im0](images/Im0)

6.2.7.7

a.

ECSS‐Q‐ST‐80C 6 March 2009 Corrective  actions  shall  be  identified,  documented  in  the  reuse  file  and applied to the reused software not meeting the applicable requirements related to the aspects as specified in clauses 6.2.7.2 to 6.2.7.6. 

EXPECTED OUTPUT:  Software reuse file [DJF, SRF; SRR, PDR].

6.2.7.8

a.

b.

Reverse  engineering  techniques  shall  be  applied  to  generate  missing documentation  and  to  reach  the  required  verification  and  validation coverage. 

For software products whose life cycle data from previous development are  not  available  and  reverse  engineering  techniques  are  not  fully applicable, the following methods shall be applied: 

1.

generation of validation and verification documents based on the available user documentation (e.g. user manual) and execution of tests in order to achieve the required level of test coverage; 

use  of  the  product  service  history  to  provide  evidence  of  the product’s  suitability 

including information about: 

(a)

the  current  application, 

for 

2.

relevance  of  the  product  service  history  for  the  new operational environment; 

configuration  management  and  change  control  of  the software product; 

effectiveness of problem reporting; 

actual error rates and maintenance records; 

impact of modifications. 

(b)

(c)

(d)

(e)

EXPECTED OUTPUT:  Software reuse file [DJF, SRF; SRR, PDR].

6.2.7.9

a.

The  software  reuse file shall  be  updated  at  project milestones  to  reflect the  results  of  the  identified  corrective  actions  for  reused  software  not meeting the project requirements. 

EXPECTED OUTPUT:  Software  reuse  file  [DJF,  SRF;  CDR,  QR,

AR].

6.2.7.10

a.

6.2.7.11

a.

All the reused software shall be kept under configuration control. 

The detailed configuration status of the reused software baseline shall be provided to the customer in the reuse file for acceptance. 

EXPECTED OUTPUT:  Software  reuse  file  [DJF,  SRF;  SRR,  PDR,

CDR, QR, AR].

49 ![Im0](images/Im0)

6.2.8

Automatic code generation

ECSS‐Q‐ST‐80C 6 March 2009 6.2.8.1

a.

For the selection of tools for automatic code generation, the supplier shall evaluate the following aspects: 

1.

evolution of the tools in relation to the tools that use the generated code as an input; 

NOTE 

For  example:  compilers  or  code  management 

systems. 

2.

3.

4.

5.

6.

7.

customization of the tools to comply with project standards;  

portability requirements for the generated code;  

collection of the required design and code metrics;  

verification of software components containing generated code;  configuration  control  of  the  tools  including  the  parameters  for customisation; 

compliance with open standards. 

The  requirements  on  testing  applicable  to  the  automatically  generated code  shall  ensure  the  achievement  of  the  same  objectives  as  those  for manually generated code. 

EXPECTED OUTPUT:  Validation  and  testing  documentation  [DJF,

SValP;  PDR],  [DJF,  SVS;  CDR,  QR,  AR],

[DJF, SUITP; PDR, CDR].

6.2.8.2

a.

6.2.8.3

a.

The  required  level  of  verification  and  validation  of  the  automatic generation  tool  shall  be  at  least  the  same  as  the  one  required  for  the generated code, if the tool is used to skip verification or testing activities on the target code. 

6.2.8.4

a.  Modelling standards for automatic code generation tools shall be defined and applied. 

EXPECTED OUTPUT:  Modelling standards [PAF, -; SRR, PDR].

6.2.8.5

a.

Adherence to modelling standards shall be verified. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

50 ![Im0](images/Im0)

6.2.8.6

a.

ECSS‐Q‐ST‐80C 6 March 2009 Clause  6.3.4  shall  apply  to  automatically  generated  code,  unless  the supplier  demonstrates  that  the  automatically  generated  code  does  not need to be manually modified. 

6.2.8.7

a.

The  verification  and  validation  documentation  shall  address  separately the activities to be performed for manually and automatically generated code. 

EXPECTED OUTPUT:  Validation  and  testing  documentation  [DJF,

SValP;  PDR],  [DJF,  SVS;  CDR,  QR,  AR],

[DJF, SUITP; PDR, CDR].

- 6.3  Requirements applicable to individual software

engineering processes or activities

6.3.1

6.3.1.1

a.

Software related system requirements

process

For  the  definition  of  the  software  related  system  requirements  to  be specified  in  the  requirements  baseline,  ECSS‐E‐ST‐40  clause  5.2  shall apply. 

6.3.1.2

a.

The requirements baseline shall be subject to documentation control and configuration management as part of the development documentation. 6.3.1.3

a.

For the definition of the requirements baseline, all results from the safety and dependability  analyses  (including  results  from  the  HSIA  ECSS‐Q‐ST‐30 clause 6.4.2.3) shall be used. 

6.3.2

6.3.2.1

a.

Software requirements analysis

The requirements baseline shall be analyzed to fully and unambiguously define the software requirements in the technical specification. 

6.3.2.2

a.

The technical specification shall be subject to documentation control and configuration management as part of the development documentation. 51 ![Im0](images/Im0)

6.3.2.3

a.

ECSS‐Q‐ST‐80C 6 March 2009 For the definition of the technical specification, all results from the safety and dependability  analyses  (including  results  from  the  HSIA  ECSS‐Q‐ST‐30 clause 6.4.2.3) shall be used. 

6.3.2.4

a.

In  addition  to  the  functional  requirements,  the  technical  specification shall  include  all  non‐functional  requirements  necessary  to  satisfy  the requirements baseline, including, as a minimum, the following: 

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.  metrication, and 

11.

performance, 

safety, 

reliability, 

robustness, 

quality, 

maintainability, 

configuration management, 

security, 

privacy, 

verification and validation. 

NOTE 

Performance 

requirements on numerical accuracy. 

requirements 

include 

EXPECTED OUTPUT:  Software  requirements  specification  [TS,

SRS; PDR].

6.3.2.5

a.

Prior  to  the  technical  specification  elaboration,  customer  and  supplier shall agree on the following principles and rules as a minimum: 

1.

assignment of persons (on both sides) responsible for establishing the technical specification; 

methods for agreeing on requirements and approving changes; efforts  to  prevent  misunderstandings  such  as  definition  of  terms, explanations of background of requirements; 

recording and reviewing discussion results on both sides. 

2.

3.

4.

52 ![Im0](images/Im0)

6.3.3

6.3.3.1

a.

ECSS‐Q‐ST‐80C 6 March 2009 Software architectural design and design ofsoftware items

The design definition file shall be subject to documentation control and configuration management.  

6.3.3.2

a.  Mandatory and advisory design standards shall be defined and applied. EXPECTED OUTPUT:  Design standards [PAF, -; SRR, PDR].

6.3.3.3

a.

For software in which numerical accuracy is relevant to mission success specific  rules  on  design  and  code  shall  be  defined  to  ensure  that  the specified level of accuracy is obtained. 

NOTE 

For  example:  for  an  attitude  and  orbit  control 

subsystem, 

generation 

components. 

scientific 

data 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

6.3.3.4

a.

6.3.3.5

a.

b.

Adherence to design standards shall be verified. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

The  supplier  shall  define  means,  criteria  and  tools  to  ensure  that  the complexity and modularity of the design meet the quality requirements. The  design  evaluation  shall  be  performed  in  parallel  with  the  design process, in order to provide feedback to the software design team. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

6.3.3.6

a.

Synthesis  of  the  results  obtained  in  the  software  complexity  and modularity  evaluation  and  corrective  actions  implemented  shall  be described in the software product assurance reports. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.3.3.7

a.

The  supplier  shall  review  the  design  documentation  to  ensure  that  it contains the appropriate level of information for maintenance activities. EXPECTED OUTPUT:  The following outputs are expected:

a.  Software  product  assurance  plan  [PAF,  SPAP;PDR];

b.  Software product assurance reports [PAF, -; -].53 ![Im0](images/Im0)

6.3.4

6.3.4.1

a.

ECSS‐Q‐ST‐80C 6 March 2009 Coding

Coding  standards  (including  consistent  naming  conventions  and adequate commentary rules) shall be specified and observed. 

EXPECTED OUTPUT:  Coding standards [PAF, -; PDR].

6.3.4.2

a.

The standards shall be consistent with the product quality requirements. NOTE 

Coding  standards  depend  on  the  software 

quality objectives (see clause 5.2.7). 

EXPECTED OUTPUT:  Coding standards [PAF, -; PDR].

6.3.4.3

a.

The  tools  to  be  used  in  implementing  and  checking  conformance  with coding standards shall be identified in the product assurance plan before coding activities start. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

6.3.4.4

a.

Coding  standards  shall  be  reviewed  with  the  customer  to  ensure  that they reflect product quality requirements. 

EXPECTED OUTPUT:  Coding  standards  and  description  of  tools

[PAF, -; PDR].

6.3.4.5

a.

Use of low‐level programming languages shall be justified. 

EXPECTED OUTPUT:  Software

development

plan

[MGT,

SDP; PDR].

6.3.4.6

a.

The supplier shall define measurements, criteria and tools to ensure that the software code meets the quality requirements. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

b.

The  code  evaluation  shall  be  performed  in  parallel  with  the  coding process, in order to provide feedback to the software programmers. 

6.3.4.7

a.

Synthesis of the code analysis results and corrective actions implemented shall be described in the software product assurance reports. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

54 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 The  code  shall  be  put  under  configuration  control  immediately  after successful unit testing. 

6.3.4.8

a.

6.3.5

Testing and validation

6.3.5.1

a.

Testing shall be performed in accordance with a strategy for each testing level (i.e. unit, integration, validation against the technical specification, validation  against 

the  requirements  baseline,  acceptance),  which includes: 

1.

the types of tests to be performed; 

NOTE 

For example: functional, boundary, performance, 

and usability tests. 

2.

3.

the  tests  to  be  performed  in  accordance  with  the  plans  and procedures; 

the  means  and  organizations  to  perform  assurance  function  for testing and validation. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR, CDR].

6.3.5.2

a.

Based  on  the  criticality  of  the  software,  test  coverage  goals  for  each testing level shall be agreed between the customer and the supplier and their achievement monitored by metrics:  

1.

2.

3.

for unit level testing; 

for integration level testing; 

for  validation  against  the  technical  specification  and  validation against the requirements baseline. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR, CDR].

6.3.5.3

a.

The  supplier  shall  ensure  through  internal  review  that  the  test procedures  and  data  are  adequate,  feasible and  traceable and  that  they satisfy the requirements. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.3.5.4

a.

Test  readiness  reviews  shall  be  held  before  the  commencement  of  test activities, as defined in the software development plan. 

EXPECTED OUTPUT:  Test readiness review reports [DJF, -; TRR].

55 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Test coverage shall be checked with respect to the stated goals. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

Feedback  from  the  results  of  test  coverage  evaluation  shall  be continuously provided to the software developers. 

6.3.5.5

a.

b.

6.3.5.6

a.

The  supplier  shall  ensure  that  nonconformances  and  software  problem reports detected during testing are properly documented and reported to those concerned. 

EXPECTED OUTPUT:  Nonconformance

software

problem  reports  [DJF,  -;  CDR,  QR,  AR,

ORR].

reports  and

6.3.5.7

a.

The test coverage of configurable code shall be checked to ensure that the stated requirements are met in each tested configuration. 

EXPECTED OUTPUT:  Statement  of  compliance  with  test  plans and

procedures [PAF, -; CDR, QR, AR, ORR].

6.3.5.8

a.

The completion of actions related to software problem reports generated during testing and validation shall be verified and recorded. 

EXPECTED OUTPUT:  Software  problem  reports  [DJF,  -;  SRR,

PDR, CDR, QR, AR, ORR].

6.3.5.9

a.

Provisions shall be made to allow witnessing of tests by the customer. 6.3.5.10

a.

Provisions  shall  be  made  to  allow  witnessing  of  tests  by  supplier personnel independent of the development. 

6.3.5.11

a.

NOTE 

For  example:  specialist  software  product 

assurance personnel. 

The supplier shall ensure that: 

1.

tests are conducted in accordance with approved test procedures and data,  

the configuration under test is correct,  

the tests are properly documented, and  

the test reports are up to date and valid.  

2.

3.

4.

EXPECTED OUTPUT:  Statement  of  compliance  with  test  plans and

procedures [PAF, -; CDR, QR, AR, ORR].

56 ![Im0](images/Im0)

6.3.5.12

a.

ECSS‐Q‐ST‐80C 6 March 2009 The  supplier  shall  ensure  that  tests  are  repeatable  by  verifying  the storage  and  recording  of  tested  software,  support  software,  test environment, supporting documents and problems found. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

6.3.5.13

a.

The  supplier  shall  confirm  in  writing  that  the  tests  are  successfully completed. 

EXPECTED OUTPUT:  Testing and validation reports [DJF, -; CDR,

QR, AR, ORR].

6.3.5.14

a.

Review  boards  looking  to  engineering  and  product  assurance  aspects shall be convened after the completion of test phases, as defined in the software development plan. 

6.3.5.15

a.

Areas  affected  by  any  modification  shall  be  identified  and  re‐tested (regression testing). 

6.3.5.16

a.

In case of re‐testing, all test related documentation (test procedures, data and reports) shall be updated accordingly. 

EXPECTED OUTPUT:  Updated  test  documentation  [DJF,  -;  CDR,

QR, AR, ORR].

6.3.5.17

a.

The need for regression testing and additional verification of the software shall be analysed after any change of the platform hardware. 

EXPECTED OUTPUT:  Updated  test  documentation  [DJF,  -;  CDR,

QR, AR, ORR].

6.3.5.18

a.

The need for regression testing and additional verification of the software shall be analysed after a change or update of any tool used to generate it. NOTE 

For example: source code or object code. 

EXPECTED OUTPUT:  Updated  test  documentation  [DJF,  -;  CDR,

QR, AR, ORR].

6.3.5.19

a.

Validation  shall  be  carried  out  by  staff  who  have  not  taken  part  in  the design or coding of the software being validated. 

57 ECSS‐Q‐ST‐80C 6 March 2009 NOTE 

This  can  be achieved  at  the  level  of  the  whole 

software  product,  or  on  a  component  by 

component basis. 

Validation of the flight software against the requirement baseline on the flight equipment model shall be performed on a software version without any patch.  

6.3.5.20

a.

6.3.5.21

a.

The supplier shall review the test documentation to ensure that it is up to date and organized to facilitate its reuse for maintenance. 

6.3.5.22

a.

Tests  shall  be  organized  as  activities  in  their  own  right  in  terms  of planning, resources and team composition.  

EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,

SValP; PDR], [DJF, SUITP; PDR, CDR].

6.3.5.23

a.

The  necessary  resources  for  testing  shall  be  identified  early  in  the  life cycle, taking into account the operating and maintenance requirements.  EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,

SValP; PDR], [DJF, SUITP; PDR, CDR].

6.3.5.24

a.

Test  tool  development  or  acquisition  (hardware  and  software)  shall  be planned for in the overall project plan. 

EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,

SValP; PDR], [DJF, SUITP; PDR, CDR].

6.3.5.25

a.

The  supplier  shall  establish  and  review  the  test  procedures  and  data before starting testing activities and also document the constraints of the tests  concerning  physical,  performance,  functional,  controllability  and observability limitations. 

EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,

SValP;  PDR],  [DJF,  SVS;  CDR,  QR,  AR],

[DJF, SUITP; PDR, CDR].

6.3.5.26

a.

Before  offering  the  product  for  delivery  and  customer  acceptance,  the supplier  shall  validate  its  operation  as  a  complete  product,  under conditions  similar  to  the  application  environment  as  specified  in  the requirements baseline. 

58 ![Im0](images/Im0)

![Im0](images/Im0)

6.3.5.27

a.  When  testing  under  the  operational  environment  is  performed,  the ECSS‐Q‐ST‐80C 6 March 2009 following concerns shall be addressed: 

1.

2.

the features to be tested in the operational environment; 

the  specific  responsibilities  of  the  supplier  and  customer  for carrying out and evaluating the test; 

restoration of the previous operational environment (after test). 3.

EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,  -;

AR].

6.3.5.28

a.

Independent software validation shall be performed by a third party. NOTE 

This  requirement  is  applicable  where the  risks 

associated  with  the  project  justify  the  costs 

involved.  The  customer  can  consider  a  less 

rigorous 

independence,  e.g.  an 

independent team in the same organization. 

level  of 

EXPECTED OUTPUT:  The following outputs are expected:

a.  ISVV plan [DJF, -; SRR, PDR];

b.  ISVV report [DJF, -; PDR, CDR, QR, AR].

6.3.5.29

a.

The  validation  shall  include  testing  in  the  different  configurations possible  or  in  a  representative  set  of  them  when  it  is  evident  that  the number of possible configurations is too high to allow validation in all of them. 

EXPECTED OUTPUT:  Test  and  validation  documentation  [DJF,

SValP; PDR], [DJF, SVS; CDR, QR, AR].

6.3.5.30

a.

Software  containing  deactivated  code  shall  be  validated  specifically  to ensure that the deactivated code cannot be activated or that its accidental activation cannot harm the operation of the system. 

EXPECTED OUTPUT:  Testing and validation reports [DJF, -; CDR,

QR, AR].

6.3.5.31

a.

Software  containing  configurable  code  shall  be  validated  specifically  to ensure that unintended configuration cannot be activated at run time or included during code generation. 

EXPECTED OUTPUT:  Testing and validation reports [DJF, -; CDR,

QR, AR].

59 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 6.3.5.32

a.

Activities for the validation of the quality requirements shall be specified in the definition of the validation specification.  

EXPECTED OUTPUT:  Software validation specification [DJF, SVS;

CDR, QR, AR].

6.3.6

Software delivery and acceptance

6.3.6.1

a.

The  roles,  responsibilities and  obligations  of  the supplier and  customer during installation shall be established. 

EXPECTED OUTPUT:  Installation procedure [DDF, SCF; AR].

6.3.6.2

a.

The  installation  shall  be  performed  in  accordance  with  the  installation procedure. 

6.3.6.3

a.

The  customer  shall  establish  an  acceptance  test  plan  specifying  the intended  acceptance  tests  including  specific  tests  suited  to  the  target environment (see ECSS‐E‐ST‐40 clause 5.7.3.1). 

NOTE 1  The acceptance tests can be partly made up of tests 

used during previous test activities. 

NOTE 2  The  acceptance  test  plan  takes  into  account  the 

requirement  for  operational  demonstration,  either 

as part of acceptance or after acceptance. 

EXPECTED OUTPUT:  Acceptance test plan [DJF, -; QR, AR].

6.3.6.4

a.

The  customer  shall  ensure  that  the  acceptance  tests  are  performed  in accordance  with  the  approved  acceptance  test  plan  (see  ECSS‐E‐ST‐40 clause 5.7.3.2). 

6.3.6.5

a.

Before  the  software  is  presented  for  customer  acceptance,  the  supplier shall ensure that: 

1.

the delivered software complies with the contractual requirements (including  any  specified  content  of  the  software  acceptance  data package); 

the source and object code supplied correspond to each other; 

all agreed changes are implemented; 

all nonconformances are either resolved or declared. 

2.

3.

4.

60 ![Im0](images/Im0)

6.3.6.6

a.

ECSS‐Q‐ST‐80C 6 March 2009 The customer shall verify that the executable code was regenerated from configuration  managed  source  code  components  and  installed  in accordance with predefined procedures on the target environment. 

6.3.6.7

a.

Any  discovered  problems  shall  be  documented  in  nonconformance reports. 

EXPECTED OUTPUT:  Nonconformance reports [DJF, -; AR].

6.3.6.8

a.

On completion of the acceptance tests, a report shall be drawn up and be signed by the supplier’s representatives, the customer’s representatives, the software quality engineers of both parties and the representative of the organization charged with the maintenance of the software product. EXPECTED OUTPUT:  Acceptance test report [DJF, -; AR].

6.3.6.9

a.

The customer shall certify conformance to the procedures and state the conclusion concerning the test result for the software product under test (accepted, conditionally accepted, rejected). 

EXPECTED OUTPUT:  Acceptance test report [DJF, -; AR].

6.3.7  Operations

6.3.7.1

a.

During  operations,  the  quality  of  the  mission  products  related  to software shall be agreed with the customer and users. 

NOTE   Quality  of  mission  products  can 

include 

parameters such as: error‐free data, availability 

of  data  and  permissible  outages;  permissible 

information degradation. 

EXPECTED OUTPUT:  Software operation support plan [OP, -; ORR].

6.3.7.2

a.

During the demonstration that the software conforms to the operational requirements, the following shall be covered as a minimum: 

1.

availability  and  maintainability  of  the  host  system  (including reboot after maintenance interventions); 

safety features; 

human‐computer interface; 

operating procedures; 

ability to meet the mission product quality requirements. 

2.

3.

4.

5.

EXPECTED OUTPUT:  Validation  of  the  operational  requirements

[PAF, -; ORR].

61 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 6.3.7.3

a.

The  product  assurance  plan  for  system  operations  shall  include consideration of software. 

EXPECTED OUTPUT:  Input  to  product  assurance  plan  for  systems

operation [PAF, -; ORR]

6.3.8  Maintenance

6.3.8.1

a.

The organization responsible for maintenance shall be identified to allow a smooth transition into the operations and maintenance. 

NOTE   An  organization,  with  representatives  from 

both  supplier  and  customer,  can  be  set  up  to 

support the maintenance activities. Attention is 

drawn to the importance of the flexibility of this 

organization  to  cope  with  the  unexpected 

occurrence of problems and the identification of 

facilities  and  resources  to  be  used  for  the 

maintenance activities. 

EXPECTED OUTPUT:  Maintenance plan [MF, -; QR, AR, ORR].

6.3.8.2

a.

The  maintenance  organization  shall  specify  the  assurance,  verification and validation activities applicable to maintenance interventions. 

EXPECTED OUTPUT:  Maintenance plan [MF, -; QR, AR, ORR].

6.3.8.3

a.

The  maintenance  plans  shall  be  verified  against  specified  requirements for maintenance of the software product. 

6.3.8.4

a.

The  maintenance  plans  and  procedures  can 

address  corrective,  improving,  adaptive  and 

differentiating 

preventive 

“routine” 

between 

“emergency” 

maintenance activities. 

maintenance, 

and 

NOTE 

The maintenance plans and procedures shall include the following as a minimum: 

1.

2.

scope of maintenance; 

identification of the first version of the software product for which maintenance is to be done; 

support organization; 

maintenance life cycle; 

3.

4.

62 ECSS‐Q‐ST‐80C 6 March 2009 maintenance activities; 

quality measures to be applied during the maintenance; 

maintenance records and reports. 

5.

6.

7.

EXPECTED OUTPUT:  Maintenance plan [MF, -; QR, AR, ORR].

6.3.8.5

a.

Rules for the submission of maintenance reports shall be established and agreed as part of the maintenance plan. 

EXPECTED OUTPUT:  Maintenance plan [MF, -; QR, AR, ORR].

6.3.8.6

a.

All  maintenance  activities  shall  be  logged  in  predefined  formats  and retained.  

EXPECTED OUTPUT:  Maintenance records [MF, -; -].

6.3.8.7

a.  Maintenance  records  shall  be  established  for  each  software  product, including, as a minimum, the following information,: 

1.

list  of  requests  for  assistance  or  problem  reports  that  have  been received and the current status of each; 

organization responsible for responding to requests for assistance or implementing the appropriate corrective actions; 

priorities assigned to the corrective actions; 

results of the corrective actions; 

statistical data on failure occurrences and maintenance activities. 2.

3.

4.

5.

NOTE 

The record of the maintenance activities can be 

utilized for evaluation and enhancement of the 

software  product  and  for  improvement  of  the 

quality system itself. 

EXPECTED OUTPUT:  Maintenance records [MF, -; -].

63 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Software product quality assurance- 7.1  Product quality objectives and metrication

Deriving of requirements

7.1.1

a.

The  software  quality  requirements  (including  safety  and  dependability requirements) shall be derived from the requirements defined at system level. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Requirement baseline [RB, SSS; SRR];

b.  Technical specification [TS, SRS; PDR].

7.1.2  Quantitative definition of quality

requirements

a.

Quality  requirements  shall  be  expressed  in  quantitative  terms  or constraints. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Requirement baseline [RB, SSS; SRR];

b.  Technical specification [TS, SRS; PDR].

7.1.3

Assurance activities for product quality

requirements

a.

The supplier shall define assurance activities to ensure that the product meets the quality requirements as specified in the technical specification. EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

7.1.4

a.

Product metrics

to  verify 

the 

implementation  of 

In  order 

the  product  quality requirements,  the  supplier  shall  define  a  metrication  programme  based on the identified quality model (see clause 5.2.7), specifying: 

1.

2.

the metrics to be collected and stored; 

the means to collect metrics (measurements); 

64 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 3.

4.

5.

6.

to 

the  product  quality target  values,  with  reference 

the 

requirements; 

the  analyses  to  be  performed  on  the  collected  metrics,  including the ones to derive: 

(a)

descriptive statistics; 

NOTE 

For example: the number of units at each level 

of complexity. 

trend analysis (such as trends in software problems). 

(b)

how the results of the analyses performed on the collected metrics are  fed  back  to  the  development  team  and  used  to  identify corrective actions; 

the schedule of metrics collection, storing, analysis and reporting, with reference to the whole software life cycle. 

NOTE   Guidance  for  software  metrication  programme 

implementation  can  be  found  in  ECSS‐Q‐HB‐

80‐04.  

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; SRR, PDR].

Basic metrics

7.1.5

a.

The following basic products metrics shall be used: 

1.

2.

3.

4.

5.

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

size (code); 

complexity (design, code); 

fault density and failure intensity; 

test coverage; 

number of failures. 

SPAP; SRR, PDR].

Reporting of metrics

The  results  of  metrics  collection  and  analysis  shall  be  included  in  the software  product  assurance  reports,  in  order  to  provide  the  customer with an insight into the level of quality obtained. 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

7.1.6

a.

7.1.7

a.

Numerical accuracy

Numerical accuracy shall be estimated and verified. 

EXPECTED OUTPUT:  Numerical  accuracy  analysis  [DJF,  SVR;

PDR, CDR, QR].

65 ![Im0](images/Im0)

![Im0](images/Im0)

7.1.8

a.

Analysis of software maturity

ECSS‐Q‐ST‐80C 6 March 2009 The  supplier  shall  define  the  organization  and  means  implemented  to collect and analyse data required for the study of software maturity. 

For  example:  failures,  corrections,  duration  of 

runs. 

NOTE 

EXPECTED OUTPUT:  Software product assurance reports [PAF, -; -].

- 7.2  Product quality requirements

7.2.1

Requirements baseline and technical

specification

7.2.1.1

a.

The  software  quality  requirements  shall  be  documented 

requirements baseline and technical specification. 

EXPECTED OUTPUT:  The following outputs are expected:

in  the a.  Requirement baseline [RB, SSS; SRR];

b.  Technical specification [TS, SRS; PDR].

7.2.1.2

a.

The software requirements shall be:  

1.

2.

3.

4.

5.

6.

correct; 

unambiguous; 

complete; 

consistent; 

verifiable; 

traceable. 

7.2.1.3

a.

For each requirement the method for verification and validation shall be specified. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Requirement baseline [RB, SSS; SRR];

b.  Technical specification [TS, SRS; PDR].

66 ![Im0](images/Im0)

7.2.2

Design and related documentation

ECSS‐Q‐ST‐80C 6 March 2009 7.2.2.1

a.

The  software  design  shall  meet  the  non‐functional  requirements  as documented in the technical specification. 

The software shall be designed to facilitate testing. 

7.2.2.2

a.

7.2.2.3

a.

Software with a long planned lifetime shall be designed with minimum dependency on the operating system and the hardware, in order to aid portability. 

NOTE 

This  requirement  is  applicable  to  situations 

where  the  software  lifetime  can  lead  to  the 

obsolescence  and  non‐availability  of 

the 

original  operating  system  and/or  hardware, 

thereby  jeopardizing  the  maintainability  the 

software. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Software  product  assurance  plan  [PAF,  SPAP;SRR, PDR];

b.  Justification  of  design  choices  [DDF,  SDD;PDR, CDR].

7.2.3

Test and validation documentation

7.2.3.1

a.

Detailed  test  and  validation  documentation  (data,  procedures  and expected  results)  defined  in  the  ECSS‐E‐ST‐40  DJF  shall  be  consistent with the defined test and validation strategy (see clause 6.3.5 and ECSS‐E‐ST‐40 clauses 5.5.3, 5.5.4, 5.6 and 5.8). 

7.2.3.2

a.

The test documentation shall cover the test environment, tools and test software, personnel required and associated training requirements. 

7.2.3.3

a.

The criteria for completion of each test and any contingency steps shall be specified. 

7.2.3.4

a.

Test procedures, data and expected results shall be specified. 

67 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 The  hardware  and  software  configuration  shall  be  identified  and documented as part of the test documentation. 

7.2.3.5

a.

7.2.3.6

a.

For any requirements not covered by testing a verification report shall be drawn  up  documenting  or  referring  to  the  verification  activities performed. 

EXPECTED OUTPUT:  Software  verification  report  [DJF,  SVR;

CDR, QR, AR].

- 7.3  Software intended for reuse

Customer requirements

For  the  development  of  software  intended  for  reuse,  ECSS‐E‐ST‐40 clauses 5.2.4.7 and 5.4.3.6 shall apply. 

Separate documentation

The information related to the components developed for reuse shall be separated  from  the  others 

in  the  technical  specification,  design justification file, design definition file and product assurance file.  

7.3.1

a.

7.3.2

a.

7.3.3

a.

7.3.4

a.

Self-contained information

The  information  related  to  components  developed  for  reuse  in  the technical specification, the design justification file, the design definition file and the product assurance file shall be self‐contained. 

Requirements for intended reuse

The  technical  specification  of  components  developed  for  reuse  shall include  requirements  for  maintainability,  portability  and  verification  of those components. 

EXPECTED OUTPUT:  Technical

reusable

specification

components [TS, -; PDR].

for

7.3.5

Configuration management for intended

reuse

a.

The  configuration  management  system  shall  include  provisions  for handling specific aspects of software developed for reuse, such as: 

⎯

longer lifetime of the components developed for reuse compared to the other components of the project; 

68 ECSS‐Q‐ST‐80C 6 March 2009 ⎯

⎯

evolution or change of the development environment for the next project that intends to use the components; 

transfer  of  the  configuration  and  documentation  management information to the next project reusing the software. 

EXPECTED OUTPUT:  Software  configuration  management  plan

[MGT, SCMP; SRR, PDR].

Testing on different platforms

7.3.6

a.  Where the components developed for reuse are developed to be reusable on different platforms, the testing of the software shall be performed on all those platforms.  

EXPECTED OUTPUT:  Verification  and  validation  documentation

for reusable components [DJF, -; CDR].

7.3.7

a.

Certificate of conformance

The supplier shall provide a certificate of conformance that the tests have been successfully completed on all the relevant platforms. 

NOTE 

In  case  not  all  platforms  are  available,  the 

certificate of conformance states the limitations 

of the validation performed. 

EXPECTED OUTPUT:  Verification  and  validation  documentation

for reusable components [DJF, -; CDR].

- 7.4  Standard ground hardware and services for

operational system

7.4.1

a.

7.4.2

a.

Hardware procurement

The  subcontracting  and  procurement  of  hardware  shall  be  carried  out according to the requirements of ECSS‐Q‐ST‐20 clause 7. 

EXPECTED OUTPUT:  The following outputs are expected:

a.  Justification  of  selection  of  operational  groundequipment [DJF, -; SRR, PDR];

b.  Receiving  inspection  reports  [PAF,  -;  SRR,PDR].

Service procurement

The  procurement  of  support  services  to  be  used  in  operational  phases shall be justified as covering service level agreements, quality of services and  escalation  procedures,  as  needed  for  system  exploitation  and maintenance. 

EXPECTED OUTPUT:  Justification  of  selection  of  operational

support services [DJF, -; SRR, PDR].

69 ![Im0](images/Im0)

![Im0](images/Im0)

7.4.3

a.

Constraints

ECSS‐Q‐ST‐80C 6 March 2009 The  choice  of  procured  hardware  and  services  shall  address  the constraints associated with both the development and the actual use of the software. 

EXPECTED OUTPUT:  Justification  of  selection  of  operational

ground equipment [DJF, -; SRR, PDR].

Selection

7.4.4

a.

the  operational technical  consistency  with 

The  ground  computer  equipment  and  supporting  services 

for implementing the final system shall be selected according to the project requirements regarding: 

1.

2.

3.

performance; 

maintenance; 

durability  and 

equipment; 

the  assessment  of  the  product  with  respect  to  requirements, including the criticality category; 

the available support documentation; 

the acceptance and warranty conditions; 

the conditions of installation, preparation, training and use; 

the  maintenance  conditions, 

evolutions; 

copyright constraints; 

availability; 

compatibility; 

site operational constraints. 

9.

10.

11.

12.

EXPECTED OUTPUT:  Justification  of  selection  of  operational

including 

the  possibilities  of 4.

5.

6.

7.

8.

ground equipment [DJF, -; SRR, PDR].

7.4.5  Maintenance

a.

Taking account of the provider’s maintenance and product policy, it shall be  ensured  that  the  hardware  and  support  services  can  be  maintained throughout  the  specified  life  of  the  software  product  within  the operational constraints. 

- 7.5  Firmware

7.5.1

a.

Device programming

supplier 

shall  establish  procedures 

for 

The 

programming and duplication of firmware devices. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

firmware  device SPAP; PDR].

70 ECSS‐Q‐ST‐80C 6 March 2009 7.5.2  Marking

a.

The firmware device shall be indelibly marked to allow the identification (by  reference)  of  the  hardware  component  and  of  the  software component. 

EXPECTED OUTPUT:  Software  product  assurance  plan  [PAF,

SPAP; PDR].

7.5.3

a.

Calibration

The supplier shall ensure that the firmware programming equipment is calibrated. 

71 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Annex A (informative)Software documentationThis annex defines the structure of the software documents to be produced, as depicted in Figure A‐1. 

MGT

- Management File

RB

Baseline

Requirements

Design Definition

DDF

File

Software development

plan

Software configuration

management plan

(DRD in ECSS-M-ST-40)

Software review plan

...

Software system

specification

Software interface

requirements docum

...

ent

Software design

document

Software configuration file

(DRD in ECSS-M-ST-40)

Software release

document

Software user manual

...

Maintenance

MF

File

Maintenance plan

(without DRD)

Migration plan

(without DRD)

...

- Product Assurance

PAF

File

Software product

assurance plan

Software product assurance

milestone report

Software product assurance

requirements for suppliers

...

TS

Technical

Specification

Design Justification

DJF

File

OP

Operational

ents

Software requirem

specification

Interface control

document

...

Operational plan

Operational testingspecification

...

Software validation plan

Software verification plan

Software unit and

integration plan

Software validation

specification

Software reuse file

Software verification report

...

Figure A‐1: Overview of software documents 

Table A‐1 represents the document requirements list, identifying the software documentation to be produced in accordance with the requirements defined in this Standard and in ECSS‐E‐ST‐40. 

 

72 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Related  file </td>
		<td>DRL item  (e.g. Plan, document, file, report, form, matrix) </td>
		<td>DRL item having a  DRD </td>
		<td>SRR </td>
		<td></td>
		<td></td>
		<td>QR </td>
		<td>AR </td>
		<td>ORR </td>
	</tr>
	<tr align="center">
		<td rowspan=3>RB </td>
		<td>Software system specification (SSS)  </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Interface requirements document (IRD) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Safety and dependability analysis results for lower level  suppliers </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td rowspan=2>TS </td>
		<td>Software requirements specification (SRS) </td>
		<td>ECSS‐E‐ST‐40 Annex D </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software interface control document (ICD) </td>
		<td>ECSS‐E‐ST‐40 Annex E </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td rowspan=7>DDF </td>
		<td>Software design document (SDD) </td>
		<td>ECSS‐E‐ST‐40 Annex F </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software configuration file (SCF) </td>
		<td>ECSS‐M‐ST‐40 Annex E </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Software release document (SRelD)  </td>
		<td>ECSS‐E‐ST‐40 Annex G </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software user manual (SUM) </td>
		<td>ECSS‐E‐ST‐40 Annex H </td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software source code and media labels </td>
		<td>‐ </td>
		<td> </td>
		<td> </td>
		<td>(cid:57) </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software product and media labels </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Training material  </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td rowspan=4>DJF </td>
		<td>Software verification plan (SVerP)  </td>
		<td>ECSS‐E‐ST‐40 Annex I </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software validation plan (SValP)  </td>
		<td>ECSS‐E‐ST‐40 Annex J </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Independent software verification & validation plan  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software integration test plan (SUITP) </td>
		<td>ECSS‐E‐ST‐40C Annex K </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
</table>

73 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Related  file </td>
		<td>DRL item  (e.g. Plan, document, file, report, form, matrix) </td>
		<td>DRL item having a  DRD </td>
		<td>SRR </td>
		<td></td>
		<td></td>
		<td>QR </td>
		<td>AR </td>
		<td>ORR </td>
	</tr>
	<tr align="center">
		<td rowspan=16></td>
		<td>Software unit test plan (SUITP) </td>
		<td>ECSS‐E‐ST‐40 Annex K </td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software validation specification (SVS) with respect to TS  </td>
		<td>ECSS‐E‐ST‐40 Annex L </td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software validation specification (SVS) with respect to RB  </td>
		<td>ECSS‐E‐ST‐40 Annex L </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Acceptance test plan  </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software unit test report  </td>
		<td>‐ </td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software integration test report  </td>
		<td>‐ </td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software validation report with respect to TS </td>
		<td>‐ </td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software validation report with respect to RB </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Acceptance test report  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Installation report  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software verification report (SVR) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Independent software verification & validation report  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Software reuse file (SRF) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software problem reports and nonconformance reports </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Joint review report </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Justification of selection of operational ground equipment  and services  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

74 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Related  file </td>
		<td>DRL item  (e.g. Plan, document, file, report, form, matrix) </td>
		<td>DRL item having a  DRD </td>
		<td>SRR </td>
		<td></td>
		<td></td>
		<td>QR </td>
		<td>AR </td>
		<td>ORR </td>
	</tr>
	<tr align="center">
		<td rowspan=7>MGT </td>
		<td>Software development plan (SDP) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software review plan (SRevP) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software configuration management plan </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Training plan </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Interface management procedures </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Identification of NRB SW members </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Procurement data </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td rowspan=5>MF </td>
		<td>Maintenance plan  </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Maintenance records </td>
		<td>‐ </td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>SPR and NCR ‐ Modification analysis report ‐ Problem  analysis report ‐ Modification identification  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Migration plan and notification </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Retirement plan and notification </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td rowspan=3>OP </td>
		<td>Software operation support plan  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Operational testing results </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>SPR and NCR ‐ User’s request record software product ‐ Post  operation review report </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
	</tr>
</table>

75 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Related  file </td>
		<td>(e.g. Plan, document, file, report, form, matrix)  DRL item </td>
		<td>DRD  DRL item having a </td>
		<td>SRR </td>
		<td></td>
		<td></td>
		<td>QR </td>
		<td>AR </td>
		<td>ORR </td>
	</tr>
	<tr align="center">
		<td rowspan=18>PAF </td>
		<td>Software product assurance plan (SPAP)  </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Software product assurance requirements for suppliers  </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Audit plan and schedule </td>
		<td>‐ </td>
		<td>(cid:57) </td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Review and inspection plans or procedures </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Procedures and standards </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Modelling and design standards </td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Coding standards and description of tools </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software problem reporting procedures </td>
		<td>‐  </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software dependability and safety analysis report ‐  Criticality classification of software components </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software product assurance reports </td>
		<td>‐  </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software product assurance milestone report (SPAMR) </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Statement of compliance with test plans and procedures </td>
		<td>‐ </td>
		<td> </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Records of training and experience  </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>(Preliminary) alert information </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Result of pre‐award audits and assessments, and of  procurement sources </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software process assessment plan </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Software process assessment records </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Review and inspection reports </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

76 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Related  file </td>
		<td>DRL item  (e.g. Plan, document, file, report, form, matrix) </td>
		<td>DRL item having a  DRD </td>
		<td>SRR </td>
		<td></td>
		<td></td>
		<td>QR </td>
		<td>AR </td>
		<td>ORR </td>
	</tr>
	<tr align="center">
		<td rowspan=2></td>
		<td>Receiving inspection reports </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>Input to product assurance plan for systems operation </td>
		<td>‐ </td>
		<td></td>
		<td></td>
		<td></td>
		<td> </td>
		<td></td>
		<td></td>
	</tr>
</table>

 

 

77 ECSS‐Q‐ST‐80C 6 March 2009 Annex B (normative)- Software product assurance plan (SPAP) -

DRD- B.1  DRD identification

### B.1.1

### Requirement identification and source documentThe  software  product  assurance  plan  (SPAP)  is  called  from  the  normative provisions summarized in Table B‐1. 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS Standard </td>
		<td>Clause </td>
		<td>DRD section </td>
	</tr>
	<tr align="center">
		<td rowspan=20>ECSS‐Q‐ST‐80  </td>
		<td>5.1.2.1</td>
		<td><5>.a, <5>.b </td>
	</tr>
	<tr align="center">
		<td>5.1.2.2</td>
		<td><5>.a, <5>.b </td>
	</tr>
	<tr align="center">
		<td>5.1.2.3</td>
		<td><5>.a </td>
	</tr>
	<tr align="center">
		<td>5.1.3.1</td>
		<td><5>.c </td>
	</tr>
	<tr align="center">
		<td>5.1.4.1</td>
		<td><5>.b </td>
	</tr>
	<tr align="center">
		<td>5.2.1.1</td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.1.3</td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.1.4</td>
		<td><6>.g.7 </td>
	</tr>
	<tr align="center">
		<td>5.2.1.5</td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>5.2.6.2</td>
		<td><6>.d </td>
	</tr>
	<tr align="center">
		<td>5.2.7.2</td>
		<td><5>.e </td>
	</tr>
	<tr align="center">
		<td>5.4.3.3</td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.4.3.4</td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.6.1.1</td>
		<td><5>.h </td>
	</tr>
	<tr align="center">
		<td>6.1.1</td>
		<td><6>.a </td>
	</tr>
	<tr align="center">
		<td>6.1.5</td>
		<td><6>.a.3 </td>
	</tr>
	<tr align="center">
		<td>6.2.1.4</td>
		<td><6>.b </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1</td>
		<td><6>.c </td>
	</tr>
	<tr align="center">
		<td>6.2.3.2</td>
		<td><6>.c </td>
	</tr>
	<tr align="center">
		<td>6.2.3.4</td>
		<td><6>.c </td>
	</tr>
</table>

78 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS Standard </td>
		<td>Clause </td>
		<td>DRD section </td>
	</tr>
	<tr align="center">
		<td rowspan=23></td>
		<td>6.2.3.5</td>
		<td><6>.c </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8</td>
		<td><6>.d </td>
	</tr>
	<tr align="center">
		<td>6.2.4.9</td>
		<td><6>.d </td>
	</tr>
	<tr align="center">
		<td>6.2.4.11</td>
		<td><6>.d </td>
	</tr>
	<tr align="center">
		<td>6.2.5.1</td>
		<td><6>.e </td>
	</tr>
	<tr align="center">
		<td>6.2.5.2</td>
		<td><6>.e </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2</td>
		<td><6>.f </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3</td>
		<td><6>.f </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4</td>
		<td><6>.f </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5</td>
		<td><6>.f </td>
	</tr>
	<tr align="center">
		<td>6.3.3.3</td>
		<td><6>.h.3 </td>
	</tr>
	<tr align="center">
		<td>6.3.3.5</td>
		<td><6>.g.2 </td>
	</tr>
	<tr align="center">
		<td>6.3.3.7</td>
		<td><6>.g.2 </td>
	</tr>
	<tr align="center">
		<td>6.3.4.3</td>
		<td><6>.h.2 </td>
	</tr>
	<tr align="center">
		<td>6.3.4.6</td>
		<td><6>.g.3 </td>
	</tr>
	<tr align="center">
		<td>6.3.5.1</td>
		<td><6>.g.4 </td>
	</tr>
	<tr align="center">
		<td>6.3.5.2</td>
		<td><6>.g.4 </td>
	</tr>
	<tr align="center">
		<td>7.1.3</td>
		<td><7>.b.4 </td>
	</tr>
	<tr align="center">
		<td>7.1.5</td>
		<td><7>.b </td>
	</tr>
	<tr align="center">
		<td>7.1.6</td>
		<td><7>.b </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3</td>
		<td><7>.a </td>
	</tr>
	<tr align="center">
		<td>7.5.1</td>
		<td><6>.h.3 </td>
	</tr>
	<tr align="center">
		<td>7.5.2</td>
		<td><6>.h.3 </td>
	</tr>
</table>

 

### Purpose and objective

### B.1.2

The software product assurance plan is a constituent of the product assurance file (PAF).  

The purpose of the software product assurance plan is to provide information on the organizational aspects and the technical approach to the execution of the software product assurance programme  

79 ![Im0](images/Im0)

- B.2  Expected response

ECSS‐Q‐ST‐80C 6 March 2009 ### B.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

<4>

a.

<5>

Introduction 

The  SPAP  shall  contain  a  description  of  the  purpose,  objective,  content and the reason prompting its preparation. 

Applicable and reference documents 

The  SPAP  shall  list  the  applicable  and  reference  documents  to  support the generation of the document. 

 Terms, definitions and abbreviated terms  

The  SPAP  shall  include  any  additional  terms,  definition  or  abbreviated terms used. 

 System Overview 

The  SPAP  shall  include  or  refer  to  a  description  of  the  system  and software products being developed. 

 Software product assurance programme implementation <5.1> Organization 

a.

b.

3.

4.

5.

The SPAP shall describe the organization of software product assurance activities,  including  responsibility,  authority  and  the  interrelation  of personnel  who  manage,  perform  and  verify  work  affecting  software quality. 

The following topics shall be included: 

1.

2.

organizational structure; 

interfaces of each organisation, either external or internal, involved in the project;  

relationship to the system level product assurance and safety; 

independence of the software product assurance function; 

delegation  of  software  product  assurance  tasks  to  a  lower  level supplier, if any. 

<5.2> Responsibilities 

a.

The  SPAP  shall  describe  the  responsibilities  of  the  software  product assurance function. 

80 ECSS‐Q‐ST‐80C 6 March 2009 <5.3> Resources 

a.

The SPAP shall describe the resources to be used to perform the software product assurance function. 

The description in B.2.1<5.3>a. shall include human resources and skills, hardware and software tools. 

b.

<5.4> Reporting 

a.

The  SPAP  shall  describe  the  reporting  to  be  performed  by  software product assurance. 

<5.5> Quality models 

a.

The SPAP shall describe the quality models applicable to the project and how they are used to specify the quality requirements. 

<5.6> Risk management 

a.

The  SPAP  shall  describe  the  contribution  of  the  software  product assurance function to the project risk management. 

<5.7> Supplier selection and control  

a.

The  SPAP  shall  describe  the  contribution  of  the  software  product assurance function to the next level suppliers selection and control. 

<5.8> Methods and tools 

a.

The SPAP shall describe the methods and tools used for all the activities of the development cycle, and their level of maturity. 

<5.9> Process assessment and improvement 

a.

b.

1.  The SPAP shall state the scope and objectives of process assessment. 2.  The SPAP shall describe the methods and tools to be used for process assessment and improvement. 

<5.10>  Operations and maintenance (optional) 

a.

The SPAP shall specify the quality measures related to the operations and maintenance processes (alternatively, a separate SPAP is produced). 

<6>

Software process assurance  

<6.1> Software development cycle 

a.

The SPAP shall refer to the software development cycle description in the software development plan.  

If  not  covered  in  the  software  development  plan, the  life  cycle  shall  be described. 

The life cycle shall include a milestone immediately before the starting of the software validation. 

b.

c.

81 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 <6.2> Projects plans 

a.

b.

The SPAP shall describe all plans to be produced and used in the project. The  relationship  between  the  project  plans  and  a  timely  planning  for their preparation and update shall be described. 

<6.3> Software dependability and safety 

a.

The SPAP shall contain a description and justification of the measures to be applied for the handling of critical software, including the analyses to be performed and the standards applicable for critical software. 

<6.4> Software documentation and configuration management 

a.

The  SPAP  shall  describe  the  contribution  of  the  software  product assurance function to the proper implementation of documentation and configuration management. 

The nonconformance control system shall be described or referenced. The point  in  the  software  life  cycle  from  which  the  nonconformance procedures apply shall be specified. 

The  SPAP  shall  identify  method  and  tool  to  protect  the  supplied software, a checksum‐type key calculation for the delivered operational software, and a labelling method for the delivered media. 

b.

c.

<6.5> Process metrics  

a.

The  SPAP  shall  describe  the  process  metrics  derived  from  the  defined quality models, the means to collect, store and analyze them, and the way they are used to manage the development processes. 

<6.6> Reuse of software  

a.

The SPAP shall describe the approach for the reuse of existing software, including delta qualification.  

<6.7> Product assurance planning for individual processes and 

a.

activities 

The  following  processes  and  activities  shall  be  covered,  taking  into account the project scope and life cycle: 

1.

software requirements analysis; 

2.

software architectural design and design of software items; 

3.

coding; 

4.

testing and validation (including regression testing); 

5.

verification; 

6.

software delivery and acceptance; 

7.

operations and maintenance. 

<6.8> Procedures and standards  

a.

The SPAP shall describe or list by reference all procedures and standards applicable to the development of the software in the project. 

82 ![Im0](images/Im0)

![Im0](images/Im0)

b.

c.

<7>

a.

b.

ECSS‐Q‐ST‐80C 6 March 2009 The  software  product  assurance  measures  to  ensure  adherence  to  the project procedures and standards shall be described.  

The  standards  and  procedures  to  be  described  or  listed  in  accordance with  B.2.1<6.8>a  shall  be  as  a  minimum  those  covering  the  following aspects: 

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

11.

12.

13.

14.

15.

16.

17.

18.  maintenance; 

19.

project management; 

risk management; 

configuration and documentation management; 

verification and validation; 

requirements engineering; 

design; 

coding; 

metrication; 

nonconformance control; 

audits; 

alerts; 

procurement; 

reuse of existing software; 

use of methods and tools; 

numerical accuracy; 

delivery, installation and acceptance; 

operations; 

device programming and marking. 

Software product quality assurance 

The SPAP shall describe the approach taken to ensure the quality of the software product.  

The description of the approach specified in B.2.1<7>a shall include the: 1.

specification  of  the  product  metrics,  their  target  values  and  the means to collect them; 

definition of a timely metrication programme; 

analyses to be performed on the collected metrics; 

way the results are fed back to the development team; 

documentation quality requirements; 

assurance  activities  meant  to  ensure  that  the  product  meets  the quality requirements. 

2.

3.

4.

5.

6.

<8>

a.

Compliance matrix to software product assurance 

requirements  

The SPAP shall include the compliance matrix to the applicable software product  assurance  requirements  (e.g.  ECSS‐Q‐ST‐80  clauses,  as  tailored by a product assurance requirements document), or provide a reference to it. 

83 ECSS‐Q‐ST‐80C 6 March 2009 b.

For  each  software  product  assurance  requirement,  the  following information shall be provided: 

1.

requirement identifier; 

2.

compliance  

(C = compliant, NC = non–compliant, NA = not applicable); 

reference  to  the  project  documentation  covering  the  requirement (e.g. section of the software product assurance plan); 

remarks. 

3.

4.

### Special remarks

### B.2.2

The  response  to  this  DRD  may  be  combined  with  the  response  to  the  project product assurance plan, as defined in ECSS‐Q‐ST‐10. 

84 ![Im0](images/Im0)

ECSS‐Q‐ST‐80C 6 March 2009 Annex C (normative)Software product assurance milestonereport (SPAMR) - DRD- A-A-

- C.1  DRD identification

### C.1.1

### Requirement identification and source documentThe  software  product  assurance  milestone  report  (SPAMR)  is  called  from  the normative provisions summarized in Table C‐1. 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td></td>
		<td></td>
		<td>DRD section </td>
	</tr>
	<tr align="center">
		<td rowspan=17></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
</table>

85 ECSS‐Q‐ST‐80C 6 March 2009 ### Purpose and objective

### C.1.2

The software product assurance milestone report is a constituent of the product assurance file (PAF).  

The  main  purpose  of  the  software  product  assurance  milestone  report  is  to collect and present at project milestones the reporting on the software product assurance activities performed during the past project phases. 

- C.2  Expected response

### C.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

<4>

a.

b.

Introduction 

The SPAMR shall contain a description of the purpose, objective, content and the reason prompting its preparation. 

Applicable and reference documents 

The SPAMR shall list the applicable and reference documents to support the generation of the document. 

Terms, definitions and abbreviated terms  

The SPAMR shall include any additional terms, definition or abbreviated terms used. 

Verification activities performed 

The SPAMR shall contain reporting on verification activities performed by the product assurance function, including: 

1.

2.

3.

4.

5.

The SPAMR shall contain reporting on the verification of the measures applied for the handling of critical software. 

reviews; 

inspections; 

walk‐throughs; 

review of traceability matrices; 

documents reviewed. 

<5>  Methods and tools  

a.

The SPAMR shall include or reference a justification of the suitability of the  methods  and  tools  applied  in  all  the  activities  of  the  development cycle,  including  requirements  analysis,  software  specification,  design, coding,  validation,  testing,  configuration  management,  verification  and product assurance. 

The  SPAMR  shall  include  reporting  on  the  correct  use  of  methods  and tools. 

b.

86 ![Im0](images/Im0)

![Im0](images/Im0)

Adherence to design and coding standards 

ECSS‐Q‐ST‐80C 6 March 2009 The  SPAMR  shall  include  reporting  on  the  adherence  of  software products  to  the  applicable  modelling,  design  and  coding  standards, including: 

1.

reporting on the application of measures meant to ensure that the design complexity and modularity meet the quality requirements; reporting  on  design  documentation  w.r.t. 

for maintenance. 

suitability 

2.

Product and process metrics 

the  relevant  analyses  performed, 

The SPAMR shall include reporting on the collected product and process metrics, 

the  corrective  actions undertaken and the status of these actions. 

The results of the software maturity analysis shall also be reported. 

Testing and validation 

The  SPAMR  shall  include  reporting  on  adequacy  of  the  testing  and validation 

traceability repeatability), and on the achieved test coverage w.r.t. stated goals. 

documentation 

feasibility, 

(including 

SPRs and SW NCRs 

The  SPAMR  shall  include  reporting  on  the  status  of  software  problem reports and nonconformances relevant to software. 

<6>

a.

<7>

a.

b.

<8>

a.

<9>

a.

<10>  References to progress reports 

a.  Whenever  relevant  and  up‐to‐date 

information  has  been  already delivered as part of the regular PA progress reporting, a representative summary  shall  be  provided,  together  with  a  detailed  reference  to  the progress report(s) containing that information. 

### Special remarks

### C.2.2

The  response  to  this  DRD  may  be  combined  with  the  response  to  the  project product assurance report, as defined in ECSS‐Q‐ST‐10. 

87 ECSS‐Q‐ST‐80C 6 March 2009 Annex D (normative)Tailoring of this Standard based onsoftware criticality- D.1  Software criticality categories

The following software criticality categories are defined, based on the severity of the consequences of system failures (ref. ECSS‐Q‐ST‐40 Table 5‐1, and ECSS‐Q‐ST‐30 Table 6‐1). 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Category </td>
		<td>Definition </td>
	</tr>
	<tr align="center">
		<td>A </td>
		<td>Software that if not executed, or if not correctly  executed, or whose anomalous behaviour can cause  or contribute to a system failure resulting in:  (cid:198) Catastrophic consequences </td>
	</tr>
	<tr align="center">
		<td>B </td>
		<td>Software that if not executed, or if not correctly  executed, or whose anomalous behaviour can cause  or contribute to a system failure resulting in:  (cid:198) Critical consequences </td>
	</tr>
	<tr align="center">
		<td>C </td>
		<td>Software that if not executed, or if not correctly  executed, or whose anomalous behaviour can cause  or contribute to a system failure resulting in:  (cid:198) Major consequences </td>
	</tr>
	<tr align="center">
		<td>D </td>
		<td>Software that if not executed, or if not correctly  executed, or whose anomalous behaviour can cause  or contribute to a system failure resulting in:  (cid:198) Minor or Negligible consequences </td>
	</tr>
</table>

 

- D.2  Applicability matrix

The following applicability matrix represents a tailoring of the requirements of this Standard based on the software criticality categories defined in D.1. 

For each clause of this Standard and for each software criticality category, an indication is given whether that clause is applicable (Y), not applicable (N), or applicable  under  the  conditions  thereby  specified  to  that  software  criticality category. 

88 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>5 </td>
		<td>Software product assurance  programme implementation </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1 </td>
		<td>Organization and responsibility </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1.1 </td>
		<td>Organization </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.2 </td>
		<td>Responsibility and authority </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.3 </td>
		<td>Resources </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.1.4 </td>
		<td>Software product assurance  manager/engineer </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1.4.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.4.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.5 </td>
		<td>Training </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.1.5.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.1.5.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.1.5.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.1.5.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2 </td>
		<td>Software product assurance programme  management </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.1 </td>
		<td>Software product assurance planning and  control </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.1.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.1.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.1.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.2 </td>
		<td>Software product assurance reporting </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.3 </td>
		<td>Audits </td>
		<td>Y </td>
		<td>Y </td>
		<td>Audits planned  and performed  only when  necessary </td>
	</tr>
	<tr align="center">
		<td>5.2.4 </td>
		<td>Alerts </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

89 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>5.2.5 </td>
		<td>Software problems </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.5.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.5.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.5.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.5.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.6 </td>
		<td>Nonconformances </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.6.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.6.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.7 </td>
		<td>Quality requirements and quality models </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.2.7.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.2.7.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Relevant  characteristics  only (e.g.  suitability for  safety is not  relevant for cat. D  software) </td>
	</tr>
	<tr align="center">
		<td>5.3 </td>
		<td>Risk management and critical item control </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.3.1 </td>
		<td>Risk management </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.3.2 </td>
		<td>Critical item control </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.3.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.3.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4 </td>
		<td>Supplier selection and control </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.4.1 </td>
		<td>Supplier selection </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.4.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.2 </td>
		<td>Supplier requirements </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.4.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.4.3 </td>
		<td>Supplier monitoring </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.4.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.3.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.4.3.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.4.4 </td>
		<td>Criticality classification </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.5 </td>
		<td>Procurement </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.5.1 </td>
		<td>Procurement documents </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.5.2 </td>
		<td>Review of procured software component  list </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

90 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>5.5.3 </td>
		<td>Procurement details </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.5.4 </td>
		<td>Identification </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.5.5 </td>
		<td>Inspection </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.5.6 </td>
		<td>Exportability </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.6 </td>
		<td>Tools and supporting environment </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.6.1 </td>
		<td>Methods and tools </td>
		<td>‐ </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.6.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>The proposed  methods and  tools shall have  been successfully  used at least in  one project before  (possibly a non‐ space project) </td>
	</tr>
	<tr align="center">
		<td>5.6.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.6.1.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.6.2 </td>
		<td>Development environment selection </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.6.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.6.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Expected output  not required </td>
	</tr>
	<tr align="center">
		<td>5.6.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>5.7 </td>
		<td>Assessment and improvement process </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.7.1 </td>
		<td>Process assessment </td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.2 </td>
		<td>Assessment process </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.7.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.2.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.3 </td>
		<td>Process improvement </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>5.7.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>5.7.3.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6 </td>
		<td>Software process assurance </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.1 </td>
		<td>Software development life cycle </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.1.1 </td>
		<td>Life cycle definition </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.1.2 </td>
		<td>Quality objectives </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.1.3 </td>
		<td>Life cycle definition review </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

91 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.1.4 </td>
		<td>Life cycle resources </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.1.5 </td>
		<td>Software validation process schedule </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2 </td>
		<td>Requirements applicable to all software  engineering processes </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.1 </td>
		<td>Documentation of processes </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.1.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2 </td>
		<td>Software dependability and safety </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.2.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.2.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.3 </td>
		<td>Handling of critical software </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.3.8 </td>
		<td></td>
		<td>Y </td>
		<td>N </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.4 </td>
		<td>Software configuration management </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.4.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

92 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.2.4.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.10 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.4.11 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.5 </td>
		<td>Process metrics </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.5.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.5.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.5.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.5.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Limited to  number of  problems  detected during  validation </td>
	</tr>
	<tr align="center">
		<td>6.2.5.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6 </td>
		<td>Verification </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.6.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.6.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.6.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.10 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.11 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13 </td>
		<td></td>
		<td>Y </td>
		<td>N </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.2.7 </td>
		<td>Reuse of existing software </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.7.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Bullets c, d, e and  g not applicable.  Bullet b limited to  architectural  design </td>
	</tr>
</table>

93 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Limited to the  extent to ensure  maintainability of  the software </td>
	</tr>
	<tr align="center">
		<td>6.2.7.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Limited to the  extent to ensure  maintainability of  the software </td>
	</tr>
	<tr align="center">
		<td>6.2.7.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.10 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8 </td>
		<td>Automatic code generation </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.2.8.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3 </td>
		<td>Requirements applicable to individual  software engineering processes or activities </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.1 </td>
		<td>Software related system requirements  process </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.1.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.2 </td>
		<td>Software requirements analysis </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.2.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.2.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.3 </td>
		<td>Software architectural design and design of  software items </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Documentation  control only </td>
	</tr>
	<tr align="center">
		<td>6.3.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Only  recommended </td>
	</tr>
</table>

94 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.3.3.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.3.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Only if design  standards are  applied (6.3.2.2) </td>
	</tr>
	<tr align="center">
		<td>6.3.3.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.3.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.3.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4 </td>
		<td>Coding </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.4.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.4.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.4.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.4.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>The code shall be  put under  configuration  control at the  beginning of  validation testing </td>
	</tr>
	<tr align="center">
		<td>6.3.5 </td>
		<td>Testing and validation </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.5.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>No formal unit  testing and  integration  activity required </td>
	</tr>
	<tr align="center">
		<td>6.3.5.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>No formal unit  testing and  integration  activity required </td>
	</tr>
	<tr align="center">
		<td>6.3.5.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Test procedures  and data verified  by sample </td>
	</tr>
	<tr align="center">
		<td>6.3.5.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Applicable to  validation and  acceptance tests  only </td>
	</tr>
	<tr align="center">
		<td>6.3.5.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
</table>

95 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.3.5.10 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.5.11 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.12 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.13 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.14 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Applicable to  validation and  acceptance tests  only </td>
	</tr>
	<tr align="center">
		<td>6.3.5.15 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.16 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.17 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.18 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.19 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.5.20 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.21 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.22 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.23 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.24 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.26 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.27 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28 </td>
		<td></td>
		<td>Y </td>
		<td>N </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.5.29 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.5.30 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.5.31 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>6.3.5.32 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6 </td>
		<td>Software delivery and acceptance </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.6.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.8 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.6.9 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.7 </td>
		<td>Operations </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.7.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

96 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>6.3.7.2 </td>
		<td></td>
		<td>Y </td>
		<td>Bullet on  safety  features  not  applicable </td>
		<td>Bullet on safety  features not  applicable </td>
	</tr>
	<tr align="center">
		<td>6.3.7.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8 </td>
		<td>Maintenance </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>6.3.8.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>6.3.8.7 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Statistical data  not collected </td>
	</tr>
	<tr align="center">
		<td>7 </td>
		<td>Software product quality assurance </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.1 </td>
		<td>Product quality objectives and metrication </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.1.1 </td>
		<td>Deriving of requirements </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.1.2 </td>
		<td>Quantitative definition of quality  requirements </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.1.3 </td>
		<td>Assurance activities for product quality  requirements </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.1.4 </td>
		<td>Product metrics </td>
		<td>Y </td>
		<td>Y </td>
		<td>Bullet d.1 not  applicable </td>
	</tr>
	<tr align="center">
		<td>7.1.5 </td>
		<td>Basic metrics </td>
		<td>Y </td>
		<td>Y </td>
		<td>Design‐relevant  and fault  density/failure  intensity metrics  not required </td>
	</tr>
	<tr align="center">
		<td>7.1.6 </td>
		<td>Reporting of metrics </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.1.7 </td>
		<td>Numerical accuracy </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.1.8 </td>
		<td>Analysis of software maturity </td>
		<td>Y </td>
		<td>Y </td>
		<td>N </td>
	</tr>
	<tr align="center">
		<td>7.2 </td>
		<td>Product quality requirements </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.2.1 </td>
		<td>Requirements baseline and technical  specification </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.2.1.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.1.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.1.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.2 </td>
		<td>Design and related documentation </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.2.2.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.2.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

97 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Description </td>
		<td>B </td>
		<td>C </td>
		<td>D </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3 </td>
		<td>Test and validation documentation </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.2.3.1 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3.2 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3.3 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3.4 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3.5 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.2.3.6 </td>
		<td></td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3 </td>
		<td>Software intended for reuse </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.3.1 </td>
		<td>Customer requirements </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.2 </td>
		<td>Separate documentation </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.3 </td>
		<td>Self‐contained information </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.4 </td>
		<td>Requirements for intended reuse </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.5 </td>
		<td>Configuration management for intended  reuse </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.6 </td>
		<td>Testing on different platforms </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.3.7 </td>
		<td>Certificate of conformance </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.4 </td>
		<td>Standard hardware for operational system </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.4.1 </td>
		<td>Hardware procurement </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.4.2 </td>
		<td>Service procurement </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.4.3 </td>
		<td>Constraints </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.4.4 </td>
		<td>Selection </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.4.5 </td>
		<td>Maintenance </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.5 </td>
		<td>Firmware </td>
		<td>‐ </td>
		<td>‐ </td>
		<td>‐ </td>
	</tr>
	<tr align="center">
		<td>7.5.1 </td>
		<td>Device programming </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.5.2 </td>
		<td>Marking </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
	<tr align="center">
		<td>7.5.3 </td>
		<td>Calibration </td>
		<td>Y </td>
		<td>Y </td>
		<td>Y </td>
	</tr>
</table>

 

98 ECSS‐Q‐ST‐80C 6 March 2009 Annex E (informative)List of requirements with built-in tailoringcapabilityThe  following  requirements  are  applicable  under  specific  conditions,  as ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>5.1.4.2</td>
		<td>The software product assurance manager/engineer shall report to  the project manager (through the project product assurance  manager, if any) </td>
	</tr>
	<tr align="center">
		<td>5.2.2.1</td>
		<td>The supplier shall report on a regular basis on the status of the  software product assurance programme implementation, if  appropriate as part of the overall product assurance reporting of  the project. </td>
	</tr>
	<tr align="center">
		<td>6.2.3.4</td>
		<td>In case of minor changes in tools that affect the generation of the  executable code, a binary comparison of the executable code  generated by the different tools can be used to verify that no  modifications are introduced </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13</td>
		<td>This requirement is applicable where the risks associated with the  project justify the costs involved. The customer may consider a  less rigorous level of independence, e.g. an independent team in  the same organization. </td>
	</tr>
</table>

 

The  following  requirements  foresee  an  agreement  between  the  customer  and <table align="center">
	<tr align="center">
		<td>6.3.2.5</td>
		<td>Prior to the technical specification elaboration, customer and  supplier shall agree on the following principles and rules as a  minimum: […]. </td>
	</tr>
	<tr align="center">
		<td>6.3.5.2</td>
		<td>Based on the criticality of the software, test coverage goals for  each testing level shall be agreed between the customer and the  supplier and their achievement monitored by metrics: […]. </td>
	</tr>
</table>

 

 

99 ECSS‐Q‐ST‐80C 6 March 2009 Annex F (informative)Document organization and content ateach milestone- F.1

Introduction

The  following  table  shows  the  organization  of  the  Expected  Output  of  the clauses of this Standard, sorted per review, then per destination file, then per DRD. 

When no DRD is available, “‐” is shown. 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected Output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>7.1.1.a </td>
		<td>Requirement baseline </td>
		<td>RB </td>
		<td>SSS </td>
		<td><5.9> </td>
	</tr>
	<tr align="center">
		<td>7.1.2.a </td>
		<td>Requirement baseline </td>
		<td>RB </td>
		<td>SSS </td>
		<td><5.9> </td>
	</tr>
	<tr align="center">
		<td>7.2.1.1.a </td>
		<td>Requirement baseline </td>
		<td>RB </td>
		<td>SSS </td>
		<td><5.9> </td>
	</tr>
	<tr align="center">
		<td>7.2.1.3.a </td>
		<td>Requirement baseline </td>
		<td>RB </td>
		<td>SSS </td>
		<td><5.1> </td>
	</tr>
	<tr align="center">
		<td>5.4.4 </td>
		<td>Safety and dependability analyses  results for lower level suppliers </td>
		<td>RB </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.1.2.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.1> </td>
	</tr>
	<tr align="center">
		<td>5.1.2.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.1>, <5.2> </td>
	</tr>
	<tr align="center">
		<td>5.1.2.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.1> </td>
	</tr>
	<tr align="center">
		<td>5.1.3.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.3> </td>
	</tr>
	<tr align="center">
		<td>5.1.3.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.1>, <5.3> </td>
	</tr>
	<tr align="center">
		<td>5.1.4.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.1>, <5.3> </td>
	</tr>
	<tr align="center">
		<td>5.2.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>5.2.6.1.a.a </td>
		<td>NCR SW procedure as part of the  Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.6.2. </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>5.6.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.8> </td>
	</tr>
	<tr align="center">
		<td>6.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.1> </td>
	</tr>
</table>

100 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected Output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.1> </td>
	</tr>
	<tr align="center">
		<td>6.2.1.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.2> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.9 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.11.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>7.1.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.1.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.6.1.2 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>5.2.3 </td>
		<td>Audit plan and schedule </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.4.2.1 </td>
		<td>Software product assurance  requirements for suppliers </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.4.2.2 </td>
		<td>Software product assurance  requirements for suppliers </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.1 </td>
		<td>Criticality classification of software  products </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.4 </td>
		<td>Modelling standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.2 </td>
		<td>Design standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.1.b </td>
		<td>Receiving inspection report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.5.2 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><4.8> </td>
	</tr>
	<tr align="center">
		<td>5.6.2.1 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><5.4> </td>
	</tr>
	<tr align="center">
		<td>5.6.2.2 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><5.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.2 </td>
		<td>Software configuration  management plan </td>
		<td>MGT </td>
		<td>SCMP </td>
		<td> </td>
	</tr>
</table>

101 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected Output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>7.3.5 </td>
		<td>Configuration management for  reusable components </td>
		<td>MGT </td>
		<td>SCMP </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.1.5.1 </td>
		<td>Training plan </td>
		<td>MGT </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.6.1.b </td>
		<td></td>
		<td></td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.5.3 </td>
		<td>Procurement data </td>
		<td>MGT </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><4>, <5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.6 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><4>, <5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.7 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.8 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><9> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV plan </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.a </td>
		<td>ISVV plan </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.1.a </td>
		<td>Justification of selection of  operational ground equipment </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.2 </td>
		<td>Justification of selection of  operational support services </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.3 </td>
		<td>Justification of selection of  operational ground equipment </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.4 </td>
		<td>Justification of selection of  operational ground equipment </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

 

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.3.2.4 </td>
		<td></td>
		<td></td>
		<td>SRS </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>7.1.1.b </td>
		<td>Technical specification </td>
		<td>TS </td>
		<td>SRS </td>
		<td><5.10> </td>
	</tr>
	<tr align="center">
		<td>7.1.2.b </td>
		<td>Technical specification </td>
		<td>TS </td>
		<td>SRS </td>
		<td><5.10> </td>
	</tr>
	<tr align="center">
		<td>7.2.1.1.b </td>
		<td>Technical specification </td>
		<td>TS </td>
		<td>SRS </td>
		<td><5.10> </td>
	</tr>
	<tr align="center">
		<td>7.2.1.3.b </td>
		<td>Technical specification </td>
		<td>TS </td>
		<td>SRS </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>7.3.4 </td>
		<td>Technical specification for reusable  components </td>
		<td>TS </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><8> </td>
	</tr>
</table>

102 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>5.2.6.2. </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>5.2.7.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.5> </td>
	</tr>
	<tr align="center">
		<td>5.2.7.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.5> </td>
	</tr>
	<tr align="center">
		<td>5.4.3.3 </td>
		<td>Next level suppliers’ software  product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.4.3.4 </td>
		<td>Next level suppliers’ software  product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.6.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.8> </td>
	</tr>
	<tr align="center">
		<td>6.1.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.1> </td>
	</tr>
	<tr align="center">
		<td>6.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.1> </td>
	</tr>
	<tr align="center">
		<td>6.2.1.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.2> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.3> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.3> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.9 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.11.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5.a </td>
		<td>Software reuse approach, including  approach to delta qualification </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.8> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.7.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.8> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.6 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.8> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>7.1.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.1.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.1.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><7> </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
</table>

103 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>7.5.1 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.8> </td>
	</tr>
	<tr align="center">
		<td>7.5.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.8> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.6.1.2 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>5.2.5.1 </td>
		<td>Software problem reporting  procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.5.2 </td>
		<td>Software problem reporting  procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.5.3 </td>
		<td>Software problem reporting  procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.5.5 </td>
		<td>Receiving inspection report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.1.6 </td>
		<td>Procedures and standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.1.7 </td>
		<td>Procedures and standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.1 </td>
		<td>Criticality classification of software  products </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.2 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.3 </td>
		<td>Criticality classification of software  components </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.7 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.b </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.4 </td>
		<td>Modelling standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.2 </td>
		<td>Design standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.1 </td>
		<td>Coding standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.2 </td>
		<td>Coding standards </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.4 </td>
		<td>Coding standards and description  of tools </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.1.b </td>
		<td>Receiving inspection report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.5.2 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><4.8> </td>
	</tr>
	<tr align="center">
		<td>5.6.2.1 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><5.4> </td>
	</tr>
	<tr align="center">
		<td>5.6.2.2 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><5.4> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.5 </td>
		<td>Software development plan </td>
		<td>MGT </td>
		<td>SDP </td>
		<td><5.4> </td>
	</tr>
</table>

104 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.2.4.2 </td>
		<td>Software configuration  management plan </td>
		<td>MGT </td>
		<td>SCMP </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.3.5 </td>
		<td>Configuration management for  reusable components </td>
		<td>MGT </td>
		<td>SCMP </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.5.3 </td>
		<td>Procurement data </td>
		<td>MGT </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.1.7 </td>
		<td>Numerical accuracy analysis </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.1 </td>
		<td>Software verification plan  </td>
		<td>DJF </td>
		<td>SVerP </td>
		<td><6.3> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SValP </td>
		<td><4.1> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SValP </td>
		<td><4.1> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.22 </td>
		<td></td>
		<td></td>
		<td>SValP </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.23 </td>
		<td></td>
		<td></td>
		<td>SValP </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.24 </td>
		<td></td>
		<td></td>
		<td>SValP </td>
		<td><4.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td></td>
		<td></td>
		<td>SValP </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.29 </td>
		<td></td>
		<td></td>
		<td>SValP </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><7.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><7.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.22 </td>
		<td></td>
		<td></td>
		<td>SUITP </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.23 </td>
		<td></td>
		<td></td>
		<td>SUITP </td>
		<td><5.3> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.24 </td>
		<td></td>
		<td></td>
		<td>SUITP </td>
		<td><5.5> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td></td>
		<td></td>
		<td>SUITP </td>
		<td><9.2>, <10> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.2.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.3.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><4>, <5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.4.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.5.b </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.6 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><4>, <5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.7 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.8 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><9> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV plan </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.a </td>
		<td>ISVV plan </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.b </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.1.a </td>
		<td>Justification of selection of </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

105 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td></td>
		<td>operational ground equipment </td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>7.4.2 </td>
		<td>Justification of selection of  operational support services </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.3 </td>
		<td>Justification of selection of  operational ground equipment </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.4.4 </td>
		<td>Justification of selection of  operational ground equipment </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3.b </td>
		<td>Justification of design choices </td>
		<td>DDF </td>
		<td>SDD </td>
		<td><4.5> </td>
	</tr>
</table>

 

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>5.2.1.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.a </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.3> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.2 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.3> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.5 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><6.7> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.3.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>5.5.5 </td>
		<td>Receiving inspection report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.5 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.6 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.7 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.b </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.7 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.11 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
</table>

106 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><7.2>, <8> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.29 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.32 </td>
		<td>Software validation specification </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.5 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>7.1.7 </td>
		<td>Numerical accuracy analysis </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>7.2.3.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><7.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><7.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.22 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.23 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><5.3> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.24 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><5.5> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SUITP </td>
		<td><9.2>, <10> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.9 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><9> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.6 </td>
		<td>Nonconformance reports and  software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.13 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.16 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.17 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.18 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.b </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.30 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.31 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.3.6 </td>
		<td>Verification and validation  documentation for reusable  components </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.3.7 </td>
		<td>Verification and validation  documentation for reusable  components </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.4 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.5 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8.b </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>7.2.2.3.b </td>
		<td>Justification of design choices </td>
		<td>DDF </td>
		<td>SDD </td>
		<td><4.5> </td>
	</tr>
</table>

107 ![Im0](images/Im0)

 

ECSS‐Q‐ST‐80C 6 March 2009 <table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>5.2.1.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.3.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>5.5.5 </td>
		<td>Receiving inspection report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.5 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.6 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.b </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.7 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.11 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.1 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.2 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.4 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.5 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><7.2>, <8> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.29 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.32 </td>
		<td>Software validation specification </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.5 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>7.1.7 </td>
		<td>Numerical accuracy analysis </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>7.2.3.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.9 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><9> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

108 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.6 </td>
		<td>Nonconformance reports and  software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.13 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.16 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.17 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.18 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.b </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.30 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.31 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.4 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.5 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8.b </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
</table>

-  

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>5.2.1.3 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>5.2.1.4 </td>
		<td>Software product assurance plan </td>
		<td>PAF </td>
		<td>SPAP </td>
		<td><5.10> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.3.3 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.12 </td>
		<td>Software product assurance  milestone report </td>
		<td>PAF </td>
		<td>SPAMR </td>
		<td><4> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.5 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.2.6 </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.3.1.b </td>
		<td>Software dependability and safety  analysis report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.7 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.11 </td>
		<td>Statement of compliance with test  plans and procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.1 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.2 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

109 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.3.8.4 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.5 </td>
		<td>Maintenance plan </td>
		<td>MF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.2 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.7 </td>
		<td>Validation and testing  documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5.6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.25 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><7.2>, <8> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.29 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><6> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.32 </td>
		<td>Software validation specification </td>
		<td>DJF </td>
		<td>SVS </td>
		<td><5> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.5 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.4> </td>
	</tr>
	<tr align="center">
		<td>7.2.3.6 </td>
		<td>Software verification report </td>
		<td>DJF </td>
		<td>SVR </td>
		<td><4.5> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.9 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><8> </td>
	</tr>
	<tr align="center">
		<td>6.2.7.11 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td><9> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.4 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.13.a </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.6 </td>
		<td>Nonconformance reports and  software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.8 </td>
		<td>Software problem reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.13 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.16 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.17 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.18 </td>
		<td>Updated test documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.27 </td>
		<td>Test and validation documentation </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.28.b </td>
		<td>ISVV report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.30 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.31 </td>
		<td>Testing and validation reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.6.3 </td>
		<td>Acceptance test plan </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.6.7 </td>
		<td>Nonconformance reports </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.6.8 </td>
		<td>Acceptance test report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.6.9 </td>
		<td>Acceptance test report </td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.4.4 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.5 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.8.b </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.3.6.1 </td>
		<td>Installation procedure </td>
		<td>DDF </td>
		<td>SCF </td>
		<td><4.2> </td>
	</tr>
</table>

 

110 ![Im0](images/Im0)

- F.7  ECSS-Q-ST-80 Expected Output not associated with

ECSS‐Q‐ST‐80C 6 March 2009 <table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>5.1.5.2 </td>
		<td>Records of training and experience </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.1 </td>
		<td>Software product assurance report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.2.2 </td>
		<td>Software product assurance report </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.4.a </td>
		<td>Preliminary alert information </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.2.4.b </td>
		<td>Alert information </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.4.1.1.a </td>
		<td>Results of pre‐award audits and  assessments </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.4.1.1.b </td>
		<td>Records of procurement sources </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.6.1.3 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.1 </td>
		<td>Software process assessment  records: Overall assessments and  improvement programme plan </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.1.a </td>
		<td>Software process assessment record:  assessment model </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.1.b </td>
		<td>Software process assessment record:  assessment method </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.2.a </td>
		<td>Software process assessment record:  evidence of conformance of the  process assessment model </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.2.b </td>
		<td>Software process assessment record:  assessment method </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.3 </td>
		<td>Software process assessment record:  Software process assessment  recognition evidence </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.2.4 </td>
		<td>Software process assessment record:  competent assessor justification </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.3.1 </td>
		<td>Software process assessment  records: improvement plan </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.3.2 </td>
		<td>Software process assessment  records: improvement process </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.7.3.3 </td>
		<td>Software process assessment  records: evidence of improvements </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.4 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.5.5 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.2 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.3 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.7 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.9 </td>
		<td>Review and inspection plans or  procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

111 ECSS‐Q‐ST‐80C 6 March 2009 ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Clause </td>
		<td>Expected output </td>
		<td></td>
		<td></td>
		<td>Section </td>
	</tr>
	<tr align="center">
		<td>6.2.6.10 </td>
		<td>Review and inspection plans or  procedures </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.6.11 </td>
		<td>Review and inspection records </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.2.8.5 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.4 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.6 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.3.7.b </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.4.7 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.3 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.5 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.5.12 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.1.6 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>7.1.7 </td>
		<td>Software product assurance reports </td>
		<td>PAF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>6.3.8.6 </td>
		<td>Maintenance records </td>
		<td>MF </td>
		<td>‐ </td>
		<td>  </td>
	</tr>
	<tr align="center">
		<td>6.3.8.7 </td>
		<td>Maintenance records </td>
		<td>MF </td>
		<td>‐ </td>
		<td>  </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>DJF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>5.4.1.2 </td>
		<td>Software reuse file </td>
		<td>DJF </td>
		<td>SRF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.3.a </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.3.b </td>
		<td>Software release document </td>
		<td>DDF </td>
		<td>SRelD </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.10 </td>
		<td>Software configuration file </td>
		<td>DDF </td>
		<td>SCF </td>
		<td>All </td>
	</tr>
	<tr align="center">
		<td>6.2.4.11.b </td>
		<td>Labels </td>
		<td>DDF </td>
		<td>‐ </td>
		<td> </td>
	</tr>
</table>

 

 

112 ECSS‐Q‐ST‐80C 6 March 2009 BibliographyECSS‐S‐ST‐00 

ECSS‐Q‐HB‐80‐02 

ECSS‐Q‐HB‐80‐03 

ECSS‐Q‐HB‐80‐04 

ECSS‐Q‐ST‐30‐02 

IEEE 610.12:1990 

IEEE 1028‐1997 

ISO 9000:2000 

ISO 9126‐1:2001 

ISO/IEC 12207:1995 

ISO/IEC 15504:1998  

RTCA/DO‐178B 

CMU/SEI‐92‐TR‐022 

CMU/SEI‐2006‐TR‐008 

 

ECSS system — Description, implementation and general requirement 

Space product assurance — Software process 

assessment and improvement 

Space product assurance — Software 

dependability and safety methods and techniques Space product assurance — Software metrication programme definition and implementation 

Space product assurance — Failure modes, effects (and criticality) analysis 

IEEE Standard Glossary of software engineering terminology 

IEEE Standard for Software Reviews 

Quality management systems — Fundamentals and vocabulary 

Software engineering — Product quality — Part 1: Quality model 

Information technology — Software life cycle 

processes 

Information technology — Software process 

assessment 

Software considerations in airborne systems and equipment certification 

Software Quality Measurement: A framework for counting problems and defects 

CMMI for Development, Version 1.2 

-  

113 ![Im0](images/Im0)

