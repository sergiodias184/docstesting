ECSS-M-ST-40C Rev. 16 March 2009Space project

management

Configuration and information

management

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐M‐ST‐40  Working  Group,  reviewed  by  the  ECSS 

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

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐M‐40A  19 April 1996 </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐M‐40B  20 May 2005 </td>
		<td>Second issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐M‐ST‐40C  31 July 2008 </td>
		<td>Third issue  This  issue  combines  the  contents  of  ECSS‐M‐40B  and  ECSS‐M‐50B.  It supersedes these two standards.  The  descriptive  text  of  the  previous  standards  has  been  combined  and  rewritten to delete duplications.  The requirements of ECSS‐M‐40B and ECSS‐M‐50B have been maintained  with following main changes:  •  Requirements  on  product  tree  and  DRD  were  deleted  and  moved  to  ECSS‐M‐ST‐10C.  •  Configuration  management  plan  DRD  from  ECSS‐M‐40B  and  Information/documentation management plan from ECSS‐M‐50B were  merged into the Configuration management plan DRD in the current  Standard.  </td>
	</tr>
	<tr align="center">
		<td>ECSS‐M‐ST‐40C Rev. 1  6 March 2009 </td>
		<td>Third issue revision 1  Changes with respect to version C (31 July 2008) are identified with  revision tracking. </td>
	</tr>
</table>

3 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Table of contents- Change log.................................................................................................................3

- Introduction................................................................................................................7

- 1 Scope.......................................................................................................................8

- 2 Normative references.............................................................................................9

- 3 Terms, definitions and abbreviated terms..........................................................10

- 3.1  Terms from other standards .....................................................................................10

- 3.2  Terms specific to the present standard ....................................................................10

- 3.3  Abbreviated terms ....................................................................................................12

- 4 Configuration management principles ...............................................................14

- 4.1  Overview ..................................................................................................................14

4.1.1  Configuration and information/documentation activities .............................144.1.2  Configuration management process and objectives...................................144.1.3

Information/documentation management process and objectives .............15- 4.2  Management and planning.......................................................................................16

4.2.1  Configuration management plan ................................................................164.2.2  Configuration management interfaces........................................................16Implementation of configuration management .........................................................184.3.1  Overview.....................................................................................................184.3.2  Configuration identification .........................................................................204.3.3  Configuration control ..................................................................................244.3.4  Configuration status accounting .................................................................264.3.5  Configuration verification............................................................................274.3.6  Configuration management process audit..................................................274.3.7  Configuration management approach for operational phase .....................27Implementation of information/documentation management......................284.3.8

- 4.3

- 5 Configuration management requirements .........................................................33

- 5.1  General.....................................................................................................................33

- 5.2  Management and planning.......................................................................................33

4 ![Im0](images/Im0)

![Im0](images/Im0)

- 5.3

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 5.2.1  Configuration management plan ................................................................335.2.2  Configuration management interfaces........................................................34Implementation of configuration management .........................................................345.3.1  Configuration identification .........................................................................345.3.2  Configuration control ..................................................................................395.3.3  Configuration status accounting .................................................................415.3.4  Configuration verification............................................................................425.3.5

Audit of the configuration management system .........................................435.3.6  Configuration management approach for operational phase .....................43Implementation of information/documentation management......................445.3.7

- Annex A (normative) Configuration management plan - DRD.............................49

- Annex B (normative) Configuration item list - DRD..............................................56

- Annex C (normative) Configuration item data list (CIDL) - DRD..........................58

- Annex D (normative) As-built configuration list - DRD ........................................60

- Annex E (normative) Software configuration file (SCF) - DRD ............................62

- Annex F (normative) Configuration status accounting reports -DRD.................65

- Annex G (normative) Change request - DRD ........................................................68

- Annex H (normative) Change proposal - DRD ......................................................70

- Annex I (normative) Request for deviation - DRD.................................................72

- Annex J (normative) Request for waiver - DRD ....................................................74

- Annex K (informative) Configuration item selection ............................................76

- Annex L (informative) Technical data package description ................................78

- Annex M (informative) Digital signature..............................................................100

- Bibliography...........................................................................................................103

- Figures

- Figure 4-1 Configuration management...................................................................................15

- Figure 4-2 Configuration management interface (inputs).......................................................17

- Figure 4-3 Configuration management interface (outputs).....................................................18

- Figure 4-4 Implementation of configuration management......................................................20

- Figure 4-5 Configuration identification....................................................................................21

- Figure 4-6 CI product tree structure .......................................................................................22

5 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 - Figure 4-7 Configuration control.............................................................................................25

- Figure 4-8 Implementation of information/documentation management ................................28

- Figure 4-9 TDP contents ........................................................................................................30

- Figure 4-10 Delivery process for TDP ....................................................................................31

- Figure 4-11 Project phases and baseline definitions..............................................................32

- Figure L-1 TDP ZIP file...........................................................................................................79

- Figure L-2 : ZIP archive..........................................................................................................80

- Figure L-3 : XML schema tree................................................................................................80

- Figure M-1 Digital signature .................................................................................................101

- Tables

- Table G-1 : Change request scope and content ....................................................................69

- Table H-1 : Change proposal scope and content...................................................................71

- Table I-1 : Request for deviation scope and content..............................................................73

- Table J-1 : Request for waiver scope and content .................................................................75

- Table L-1 : data_package.......................................................................................................82

- Table L-2 : data_definition_exchange ....................................................................................82

- Table L-3 : item_properties ....................................................................................................87

- Table L-4 : element ................................................................................................................88

- Table L-5 : database ..............................................................................................................98

- Table L-6 : Additional information on Table L-1 to Table L-5 .................................................99

 

6 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Introductiondocument 

defines 

the 

configuration  management 

This 

information/documentation requirements for space projects. 

The  document  is  structured  into  two main  parts,  the  first  part presenting  the processes and the second one providing the detailed requirements. 

In  addition,  the  expected  configuration  and 

management  documentation 

in 

requirements definitions (DRDs). 

information/documentation the  annexed  document is 

specified 

and 7 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 ScopeThe  scope  of  this  standard  is  to  describe  the  processes  and  provide  the requirements  for  managing  the  information/documentation  and  configuration of products within a space programme or project. 

The  requirements  specified  herein  apply  to,  and  affect  the  supplier  and customer at all levels. 

This standard may be tailored for the specific characteristics and constraints of a space project in conformance with ECSS‐S‐ST‐00. 

8 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revisions of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the most recent editions of the  normative  documents  indicated  below.  For  undated  references  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐M‐ST‐10 

ECSS‐Q‐ST‐10‐09  

ECSS‐Q‐ST‐20 

ECSS system – Glossary of terms 

Space  project  management  –  Project  planning  and implementation 

Space product assurance – Nonconformance control system 

Space product assurance – Quality assurance 

9 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 apply, in particular for the following terms: 

configuration

configuration baseline

configuration control

configuration document

configuration identification

configuration item

configuration management

- 3.2  Terms specific to the present standard

change control

3.2.1

activity  for  control  of  changes  or  departures  to  the  product  after  formal approval of its configuration baseline 

NOTE   Adapted from ISO 10007. 

class 1 change

3.2.2

change that affects approved technical specifications, including interfaces of the same level, and associated terms of the business agreement between a customer and his supplier  

class 2 change

3.2.3

change that does not fulfil class 1 change criteria 

configuration control board

3.2.4

person  or  a  group  of  persons  assigned  responsibility  and  authority  to  make decisions on the configuration 

NOTE 1  This 

configuration 

control  board 

dispositioning authority in ISO 10007. 

is 

called 

NOTE 2  Relevant interested parties within and outside the 

organization are represented on the configuration 

control board. 

10 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 NOTE 3  Adapted from ISO 10007. 

configuration definition document

3.2.5

document  that  defines  the  physical  configuration  and  establishes  the  item  or material  identification  code  (part  or  identifying  number)  at  any  level  in  the product structure 

NOTE   Adapted from ASME Y14.100. 

configured item

3.2.6

any level of product whose functional or physical characteristics are recorded in a retrievable, consistent manner 

departure

3.2.7

inability  of  a  product  to  meet  one  of  its  functional  performance  or  technical requirements

NOTE 1  Two types exist: 

•  planned  departure  resulting  in  request  for 

deviation, and 

•  unplanned  departure  resulting  in  request  for 

waiver. 

NOTE 2  Departures  do  not  change 

the  engineering 

documentation. 

information/documentation management

3.2.8

process for ensuring timely and effective creation, collection, review, delivery, storage, and archiving of project information 

information system

3.2.9

set  of  resources,  procedures  and  data  required  in  support  of  project management processes 

metadata

3.2.10

metadata  are  structured,  encoded  data  that  describe  characteristics  of  in‐formation‐bearing  entities  to  aid  in  the  identification,  discovery,  assessment, and management of the described entities 

NOTE   Adapted  from  Committee  on  Cataloguing  Task 

Force on metadata Summary Report. 

product item

3.2.11

element of the product tree having a unique identifier 

3.2.12

self-signed certificate

certificate auto‐generated by the signer 

technical data package

3.2.13

ZIP file containing structured collection of files with their related metadata, to be exchanged between information systems 

11 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 NOTE   Adapted from ISO10303 AP232 TDP definition. 

technical description

3.2.14

technical definition in terms of documentation of a product, e.g. functional or performance,  and  design  requirements,  test  and  verification  documentation, analyses, drawings, parts and material lists, processes and tooling. 

- 3.3  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply:  

Abbreviation 

ABCL 

AR 

CAD 

CAGE 

CCB 

CD 

CDR 

CI 

CIDL 

CM 

CP 

CR 

CSA 

DB 

DCB 

DRD 

DRL 

DUNS 

DXF 

EIDP 

FCB 

FCV 

FTP 

H/W 

ICD 

IDM 

IEC 

IETF 

IS 

Meaning 

as‐built configuration data list 

acceptance review 

computer aided design 

commercial and government entity 

configuration control board 

compact disk 

critical design review 

configuration item 

configuration item data list 

configuration management 

change proposal 

change request 

configuration status accounting 

design baseline 

development configuration baseline 

document requirements definition 

document requirements list 

data universal numbering system 

drawing exchange format 

end item data package 

functional configuration baseline 

functional configuration verification 

file transfer protocol 

hardware 

interface control document 

information documentation management 

International Electrotechnical Commission 

internet engineering task force 

information system 

12 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 ISO 

ITU 

JPEG 

LZW 

MOB 

MS 

NATO 

NCR 

OTS 

PA 

PCB 

PCV 

PDF 

PDR 

PI 

PMP 

PRR 

QR 

RFD 

RFW 

RID 

ROM 

SCF 

SMTP 

SRR 

STEP 

S/W 

TDP 

TIFF 

TRR 

TS 

WBS 

XML 

International Organization for Standardization 

International Telecommunication Union 

joint photographic experts group 

Lempel‐Ziv‐Welch 

mission objective baseline 

Microsoft 

North Atlantic Treaty Organization 

nonconformance report 

off‐the‐shelf 

product assurance 

product configuration baseline 

physical configuration verification 

portable document format 

preliminary design review 

product item 

parts, materials and processes 

preliminary requirements review 

qualification review 

request for deviation 

request for waiver 

review item discrepancy 

read only memory 

software configuration file 

simple mail transfer protocol 

system requirements review 

standard for the exchange of product 

software 

technical data package 

tagged image file format 

test readiness review 

technical specification 

work breakdown structure 

extensible mark‐up language 

13 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Configuration management principles- 4.1  Overview

4.1.1

Configuration and

information/documentation activities

Configuration  and  information/documentation  management  are  interrelated processes  for  managing  projects.  The  main  activities  of  these  processes, depicted in Figure 4‐1, are: 

•

•

management and planning; 

implementation of CM activities, i.e. configuration identification, control, status accounting, and verification and audit; 

implementation  of  IDM  activities,  i.e.  creation,  collection,  review, delivery, storage and retrieval, and archiving. 

•

4.1.2

Configuration management process and

objectives

Configuration  management  is  the  process  for  establishing  and  maintaining  a consistent  record  of  a  product’s  functional  and  physical  characteristics compared 

its  design  and  operational  requirements.  Configuration management  is  applied  throughout  the  entire  life  cycle  of  the  product  and allows one to: 

•

to 

•

•

•

•

•

•

know at any time the technical description of a product using approved documentation; 

record and control the evolution in the technical description of a product (e.g. system and its products); 

provide  traceability  of  the  evolution  of  the  product’s  technical description; 

ensure the consistency of the internal interfaces; 

verify and demonstrate to all actors that documentation is and remains the exact image of the products it describes; 

identify the current configuration baseline and the as‐built configuration of  a  product,  to  record  discrepancies  detected  during  production, delivery or operation and dispositioned for further use; 

enable any actor to know the operational possibilities and limitations of each product item and, in case of nonconformance, to know which items are affected. 

14 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 - NOTE:  Corrective actions are improvements on the process itself as a consequence of lessons learned and any

feedback provided on the project

Figure 4‐1 Configuration management 

4.1.3

Information/documentation management

process and objectives

Information/documentation management is the process for ensuring timely and effective creation, collection, review, delivery, storage, and archiving of project information.  To  achieve  this  objective,  all  recorded  project  information  is managed electronically. 

Information/documentation  management  is  applied  throughout  the  entire  life cycle of the project and allows someone to 

•

ensure  the  correctness,  accessibility,  rapid  availability,  reliability  and security  of  information  provided  to  all  the  actors  both  internal  and external to the project; 

ensure the coherence of the overall project information, thus facilitating effective and efficient use of the information; 

ensure that all the actors who need access to information are aware of its availability, the means of access, and related methods and procedures; support the programme / project reporting. 

•

•

•

15 ![Im0](images/Im0)

![Im33](images/Im33)

![Im34](images/Im34)

![Im10](images/Im10)

![Im11](images/Im11)

![Im23](images/Im23)

![Im24](images/Im24)

![Im101](images/Im101)

![Im102](images/Im102)

![Im99](images/Im99)

![Im100](images/Im100)

![Im48](images/Im48)

![Im49](images/Im49)

![Im12](images/Im12)

![Im13](images/Im13)

![Im59](images/Im59)

![Im95](images/Im95)

![Im96](images/Im96)

![Im97](images/Im97)

![Im98](images/Im98)

![Im58](images/Im58)

![Im70](images/Im70)

![Im70](images/Im70)

![Im44](images/Im44)

![Im89](images/Im89)

![Im90](images/Im90)

![Im73](images/Im73)

![Im73](images/Im73)

![Im73](images/Im73)

![Im51](images/Im51)

![Im52](images/Im52)

![Im30](images/Im30)

![Im32](images/Im32)

![Im50](images/Im50)

![Im103](images/Im103)

![Im104](images/Im104)

![Im69](images/Im69)

![Im93](images/Im93)

![Im94](images/Im94)

![Im91](images/Im91)

![Im92](images/Im92)

![Im105](images/Im105)

![Im106](images/Im106)

![Im71](images/Im71)

![Im53](images/Im53)

![Im54](images/Im54)

![Im46](images/Im46)

![Im30](images/Im30)

![Im32](images/Im32)

![Im87](images/Im87)

![Im88](images/Im88)

![Im40](images/Im40)

![Im56](images/Im56)

![Im57](images/Im57)

![Im84](images/Im84)

![Im85](images/Im85)

![Im18](images/Im18)

![Im60](images/Im60)

![Im61](images/Im61)

![Im13](images/Im13)

![Im86](images/Im86)

![Im62](images/Im62)

![Im63](images/Im63)

![Im55](images/Im55)

![Im82](images/Im82)

![Im83](images/Im83)

![Im64](images/Im64)

![Im65](images/Im65)

![Im66](images/Im66)

![Im70](images/Im70)

![Im70](images/Im70)

![Im80](images/Im80)

![Im81](images/Im81)

![Im67](images/Im67)

![Im68](images/Im68)

![Im73](images/Im73)

![Im73](images/Im73)

![Im73](images/Im73)

![Im73](images/Im73)

![Im69](images/Im69)

![Im79](images/Im79)

![Im13](images/Im13)

![Im76](images/Im76)

![Im75](images/Im75)

![Im72](images/Im72)

![Im74](images/Im74)

![Im77](images/Im77)

![Im71](images/Im71)

![Im30](images/Im30)

![Im32](images/Im32)

![Im78](images/Im78)

![Im37](images/Im37)

![Im38](images/Im38)

![Im41](images/Im41)

![Im39](images/Im39)

![Im40](images/Im40)

![Im21](images/Im21)

![Im22](images/Im22)

![Im14](images/Im14)

![Im15](images/Im15)

![Im1](images/Im1)

![Im2](images/Im2)

![Im19](images/Im19)

![Im20](images/Im20)

![Im46](images/Im46)

![Im6](images/Im6)

![Im7](images/Im7)

![Im42](images/Im42)

![Im43](images/Im43)

![Im25](images/Im25)

![Im26](images/Im26)

![Im3](images/Im3)

![Im4](images/Im4)

![Im44](images/Im44)

![Im27](images/Im27)

![Im8](images/Im8)

![Im9](images/Im9)

![Im45](images/Im45)

![Im47](images/Im47)

![Im28](images/Im28)

![Im29](images/Im29)

![Im31](images/Im31)

![Im16](images/Im16)

![Im17](images/Im17)

![Im5](images/Im5)

![Im35](images/Im35)

![Im36](images/Im36)

![Im30](images/Im30)

![Im32](images/Im32)

![Im0](images/Im0)

- 4.2  Management and planning

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Configuration management plan

4.2.1

The  customer  defines  the  configuration  management  requirements  for  a programme or project. These requirements are applicable to all the actors of the programme  or  project  as  defined  by  the  customer  at  each  level  towards  his supplier(s).  Each  supplier  produces  a  configuration  management  plan  (CM plan)  responding  to  his  customer’s  configuration  management  requirements. The  CM  plan  is  submitted  to  the  customer  for  approval.  Upon  customer approval, the supplier executes his own CM plan and ensures that his lower tier suppliers execute their CM plan.  

The purpose of the CM plan is to define the process and resources for managing the  configuration  of  the  product  in  a  controlled  and  traceable  manner throughout the programme or project life cycle. It also describes the means for an  efficient  comparison  between  the  predicted  (“as‐designed”) and  the  actual (“as‐built”)  configuration  of  the  delivered  product.  It  defines  the  relationship with  the  project  management,  system  engineering  and  quality  management process.  

It either provides all elements necessary to ensure that the implementation of the information/documentation management meets all customer requirements, and  that  it  is  in  line  with  the  programme  or  project  organization  and management structure. 

The  customer  defines  the  programme  or  project  phase  during  which  the  CM plan is prepared and approved. 

Each  actor  assigns  a  person  responsible  for  implementing  configuration management  activities  and  for 

information/documentation management  activities  within  his  programme  or  project  team.  His  role, responsibilities and authorities are described in the CM plan. 

implementing 

Information/documentation  management 

Configuration management interfaces

4.2.2

Configuration  management  and  Information/documentation  management  are integral  parts  of  project  management.  Configuration  management  interfaces with  engineering,  product  assurance,  manufacturing  and  production  and contributes  to  programme  or  project  organization  and  their  schedule  for execution  by  identifying  all  constraints  related  to  the  business  agreement provisions. 

interfaces  with configuration management and it contributes to programme or project activities by provision of all the necessary information through the information system. The  information  system  is  a  repository  of  information  where  the  project disciplines implement data and activate processes. These interfaces are used to establish the configuration management process. 

Necessary inputs for configuration management are depicted in Figure 4‐2. 

Figure 4‐3 summarizes the outputs provided by configuration management and Information/documentation management to other project activities. 

16 ![Im0](images/Im0)

Other project 

management 

activities 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Management requirements and schedule 

Logistic/Maintenance plan 

Request for changes 

RIDs

- Product 

- assurance 

Request for changes

Project documentation

RIDs

Configuration management

Information/documentation 

management

EngineeringEngineering requirements

Product tree 

Request for changes 

Project documentation 

RIDs 

Figure 4‐2 Configuration management interface (inputs) 

17 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Other project 

management 

activities 

CIs + Configuration item list 

Dispositioned changes (CPs, RFDs, RFWs) 

Configuration status accounting reports 

Validated baseline 

CM proposed corrective actions 

Validated CM system  

Product 

- assurance 

CIs + Configuration item list 

Baseline content (agreed set of 

documents) 

Dispositioned changes (CPs, RFDs, 

RFWs) 

- Configuration item data list/Software 

configuration file 

- As‐built configuration list definition 

Validated baseline 

Validated CM system 

Reliable and secure information 

Configuration management

Information/documentation 

management

EngineeringCIs + Configuration item list 

Baseline content (agreed set of 

documents) 

Dispositioned changes (CPs, RFDs, RFWs) 

Configuration item data list/Software configuration file 

Validated baseline  

Reliable and secure information Figure 4‐3 Configuration management interface (outputs) 

- 4.3

Implementation of configuration management

4.3.1  Overview

Implementation  of 

comprises  definition, organization, execution and supervision of the following activities, as depicted in Figure 4‐4:  

•

configuration  management 

Configuration identification 

⎯

⎯

⎯

⎯

⎯

to identify the product architecture;  

to  select  configuration  items  and  to  define  their  configuration documents;  

to establish means for identifying products and documentation;  to define identification requirements for software media;  

to  establish  configuration  baselines 

requirements‐ and design‐management. 

the  purpose  of for 

18 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 •

Configuration control 

⎯

⎯

⎯

⎯

⎯

to establish and implement a change control process for individual products and systems, and their internal and external interfaces; to  record  and  control  the  configuration  of  a  product  at  any  time during its evolution; 

to record the different configurations of a product; 

to  define  and  maintain  software  libraries  or  repositories  where current  and  historic  software  baselines  are  stored  in  a  controlled environment; 

to  store  and  maintain  software  products  and  relevant  media including back‐up copies in a controlled environment. 

•

Configuration status accounting 

⎯

⎯

to  provide  a  product  definition  by  reference  to  approved  and recorded configuration statuses; 

to  enable  access  to  software  libraries  according  to  established privileges. 

•

Configuration verification and audit 

⎯

⎯

to verify and demonstrate that the product meets its documented functional, performance and physical characteristics; 

to  verify  that  the  configuration  management  system  is  effective and  meets  the  programme  or  project  configuration  management requirements. 

Implementation  of  information/documentation  management  comprises  the activities depicted in Figure 4‐8 and described in clause 4.3.8. 

19 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure 4‐4 Implementation of configuration management 

4.3.2

Configuration identification

4.3.2.1  Overview

Configuration identification, as depicted in Figure 4‐5, incrementally establishes and  releases  controlled  documentation  for  the  purpose  of 

identifying configuration characteristics of a product until it is fully defined with respect to its  intended  functional,  performance  and  physical  characteristics,  thereby ensuring the continuous integrity of the product configuration. 

Configuration  identification  also  provides  the  basis  for  evolution  through controlled changes and status accounting of a product throughout its life cycle. It ensures that all programme or project disciplines are provided with identical documentation for their use. 

By applying product item identifiers to the product, configuration identification enables traceability from the product to its defining documentation. 

The product item identifier is represented through the item identification code established  by  the  governing  configuration  definition  document.  The  product item identifier can be  

a.

the  same  code  applied  for  identifying  the  configuration  definition document, 

a code containing this code, or  

a different code defined within the configuration definition document.  b.

c.

20 ![Im0](images/Im0)

![Im2](images/Im2)

![Im1](images/Im1)

![Im5](images/Im5)

![Im41](images/Im41)

![Im42](images/Im42)

![Im44](images/Im44)

![Im45](images/Im45)

![Im43](images/Im43)

![Im4](images/Im4)

![Im3](images/Im3)

![Im6](images/Im6)

![Im48](images/Im48)

![Im49](images/Im49)

![Im7](images/Im7)

![Im8](images/Im8)

![Im12](images/Im12)

![Im13](images/Im13)

![Im10](images/Im10)

![Im11](images/Im11)

![Im46](images/Im46)

![Im47](images/Im47)

![Im29](images/Im29)

![Im38](images/Im38)

![Im9](images/Im9)

![Im34](images/Im34)

![Im34](images/Im34)

![Im50](images/Im50)

![Im51](images/Im51)

![Im53](images/Im53)

![Im54](images/Im54)

![Im52](images/Im52)

![Im29](images/Im29)

![Im38](images/Im38)

![Im31](images/Im31)

![Im31](images/Im31)

![Im34](images/Im34)

![Im34](images/Im34)

![Im34](images/Im34)

![Im16](images/Im16)

![Im14](images/Im14)

![Im15](images/Im15)

![Im27](images/Im27)

![Im28](images/Im28)

![Im30](images/Im30)

![Im35](images/Im35)

![Im36](images/Im36)

![Im33](images/Im33)

![Im37](images/Im37)

![Im32](images/Im32)

![Im29](images/Im29)

![Im38](images/Im38)

![Im56](images/Im56)

![Im55](images/Im55)

![Im57](images/Im57)

![Im58](images/Im58)

![Im4](images/Im4)

![Im60](images/Im60)

![Im61](images/Im61)

![Im62](images/Im62)

![Im18](images/Im18)

![Im59](images/Im59)

![Im63](images/Im63)

![Im64](images/Im64)

![Im10](images/Im10)

![Im17](images/Im17)

![Im21](images/Im21)

![Im19](images/Im19)

![Im20](images/Im20)

![Im39](images/Im39)

![Im24](images/Im24)

![Im40](images/Im40)

![Im25](images/Im25)

![Im26](images/Im26)

![Im23](images/Im23)

![Im22](images/Im22)

![Im20](images/Im20)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 NOTE 

item 

To  avoid  the  possible  existence  of  the  same 

product 

identifier  for  different  product 

item(s), a common practice is to prefix the product 

item  identifier  with  an  enterprise  identifier,  such 

as a DUNS number, or NATO CAGE code. 

Individual  unit  identification  of  a  product  can  also  include  an  additional identifier, such as a serial (or fabrication) number, or lot (or batch) number. 

Figure 4‐5 Configuration identification  

4.3.2.2  Configuration item

Configuration  items,  as  defined  in  ECSS‐S‐ST‐00‐01,  fall  into  two  categories, which are: 

4.3.2.2.1  Developed configuration item

This  is  a  configuration  item  subject  to  development  and  fully  or  partially designed for the programme or project. Its configuration management conforms to  the  programme  or  project  configuration  management  requirements  and  is carried out by the supplier responsible for its development. 

4.3.2.2.2  Non-developed configuration item

This is a configuration item being a standardized or “off‐the‐shelf” product that is  not  developed  specifically  for  the  programme  or  project.  It  is  subject  to supplier  definition  documentation  and  configuration  management.  This  CI category also includes any product that has been developed and qualified for another  programme  or  project  with  comparable  requirements  and  which  is used without modification. 

Configuration management of non‐developed CIs conforms to the programme or project configuration management requirements to the extent necessary for its integration into the next higher level configuration item.  

21 ![Im0](images/Im0)

![Im42](images/Im42)

![Im5](images/Im5)

![Im6](images/Im6)

![Im3](images/Im3)

![Im4](images/Im4)

![Im22](images/Im22)

![Im23](images/Im23)

![Im25](images/Im25)

![Im26](images/Im26)

![Im2](images/Im2)

![Im24](images/Im24)

![Im7](images/Im7)

![Im8](images/Im8)

![Im1](images/Im1)

![Im10](images/Im10)

![Im11](images/Im11)

![Im9](images/Im9)

![Im27](images/Im27)

![Im28](images/Im28)

![Im12](images/Im12)

![Im13](images/Im13)

![Im14](images/Im14)

![Im37](images/Im37)

![Im38](images/Im38)

![Im15](images/Im15)

![Im16](images/Im16)

![Im33](images/Im33)

![Im33](images/Im33)

![Im17](images/Im17)

![Im29](images/Im29)

![Im30](images/Im30)

![Im34](images/Im34)

![Im35](images/Im35)

![Im32](images/Im32)

![Im31](images/Im31)

![Im36](images/Im36)

![Im39](images/Im39)

![Im18](images/Im18)

![Im19](images/Im19)

![Im40](images/Im40)

![Im41](images/Im41)

![Im20](images/Im20)

![Im21](images/Im21)

![Im31](images/Im31)

![Im36](images/Im36)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Selection of configuration items

4.3.2.3

The  product  tree,  as  defined  in  ECSS‐M‐ST‐10,  is  used  for  the  selection  of configuration  items  and  serves  as  a  basis  for  the  programme  or  project  work breakdown structure. 

Configuration  items  are  identified  at  various  levels  of  the  product  tree,  as depicted  in  Figure  4‐6,  and  defined  at  least  by  a  technical  specification. Configuration item assignment provides the means for configuration control of the product. Each CI becomes also a configured item during its development. Selection  of  configuration  items  starts  at  the  early  definition  phase  of  a programme or project to build a manageable set of hardware or software items. The responsibility for identifying an item as a CI rests with the customer, unless delegated by him to the supplier. 

No  fixed  rules  govern  the  selection  of  configuration  items.  The  process  for selecting configuration items relies on good system engineering judgment, and configuration  management 

trade‐off considerations. 

experience, 

supported  by 

cost 

CI 

System

CI

CI 

Customer/supplier level 

Supplier/lower tier supplier levelCI (*)

(*) in both levels 

CI

CI

Figure 4‐6 CI product tree structure 

4.3.2.4  Configuration baseline

Configuration  baselines  represent  the  approved  status  of  requirements  and design at key milestones of the programme or project and provide the point of departure for further evolution (see Figure 4‐11). These configuration baselines are applicable to both hardware and software. 

A  configuration  baseline  comprises  the  documentation  that  describes  the characteristics of a product. This documentation is formally designated as the configuration reference at a key point in the product life cycle corresponding to a  major  product  definition  event.  Any  subsequent  change  of  a  product characteristic  proposed  for  this  documentation  is  subject  to  a  formal  change 22 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 procedure  involving  all  the  actors  and  disciplines  concerned  before  it  can  be incorporated. 

During the life cycle of the product, configuration baselines are elaborated in the following sequence: 

•

Mission  objective  baseline  (MOB)  is  established  at  PRR  based  on  the approved functional specification. This baseline establishes the purpose of  the  system, 

its  associated  constraints  and  environments,  the operational and performances capabilities for each phase of its life cycle, and the permissible flexibility. 

Functional  configuration  baseline  (FCB)  is  established  at  SRR  based  on the approved system technical specification. This baseline establishes the system’s characteristics in terms of its technical requirements, as well as the criteria and corresponding levels of qualification and acceptance. 

Development  configuration  baseline (DCB)  is  established  at  PDR based on  approved  technical  specifications  (TS).  This  baseline  establishes  the product’s  characteristics  in  terms  of  technical  requirements  and  design constraints, as well as their verification conditions. 

•

•

•

•

NOTE 

FCB  and  DCB  are  also  named  “Requirements 

baselines” in different standards. 

Design baseline (DB) is established at CDR based on the approved design documentation.  

Product configuration baseline (PCB) is established at FCV/PCV for serial production,  or  QR/AR  for  prototypes  based  on  the  approved  set  of documents  containing  all  the  functional  and  physical  characteristics required for production, acceptance, operation, support and disposal. The log book, as in ECSS‐Q‐ST‐20, is established at successful completion of the acceptance review and is maintained during the utilization and disposal phases. Details  relevant  to  the  configuration  management  approach  during  these phases are provided in clause 4.3.7.  

Identification marking

4.3.2.5

Each item, H/W and S/W is uniquely identified by a specific identification code. The  identification  code  is  assigned  to  a  product  to  distinguish  it  during  its entire life. The rules for the identification coding system are established in the CM plan.  

A configured H/W item is identified by a part number and, if necessary, a serial or  lot  number  such  that  every  single  item  has  a  unique  identifier.  In  this context, bulk material is treated as a part. A configured S/W item is identified by  a  unique  code  and  version  number.  When  the  configured  item  is  a configuration item, its identification also includes a CI identifier. These different product  identification  data  are  applied  on  the  product  itself  or,  when  not possible, linked to the product. 

23 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 identification  also  provides 

the  means 

4.3.2.6  Digital file and media identification

Configuration 

for  maintaining traceability from a product to its design definition data resident in an electronic database (digital files). 

Such data, represented by digital files, are composed by a variety of subset data, which  are  merged  in  a  controlled  manner  in  order  to  represent  the  product design definition concerned in the intended configuration. 

Configuration  management  for  these  sets  of  data  and  their  integration  into  a complete  product  design  definition  is  an  existing  application  of  software  CM processes (e.g. library management). 

Digital  files  defining  the  configuration  characteristics  of  a  product  item  are therefore subject to the same  configuration management principles applicable to configuration documentation.  

The  application  of  configuration  identification  rules  to  digital  data  are applicable for 

•

•

•

•

digital data identification, 

digital data storage, 

maintenance of digital data relating to the product, 

version  control  of  digital  data  and  the  related  change  management process,  

controlled access to digital data, and 

digital data transmittal. 

•

•

4.3.3

Configuration control

4.3.3.1  Overview

Configuration control, as depicted in Figure 4‐7, is the process for controlling the  evolution  of,  or  departures  from  agreed  baselines.  It  includes  the preparation, 

implementation  of engineering and contractual changes, deviations and waivers. 

justification,  evaluation,  disposition  and 

24 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure 4‐7 Configuration control 

4.3.3.2  Change procedure

Configuration  control  ensures  that  all  changes,  deviations  and  waivers  to agreed  configuration  baselines, 

including  their  released  and  approved documentation are processed and controlled in a traceable manner.  

The  configuration  control  process  ensures  that  the  following  activities  are covered: 

•

•

prevention of changes affecting degradation of product capability; 

involvement of all actors in the concerned analysis and decision process of changes; 

control  that  authorized  changes  or  deviation  are  implemented,  verified and recorded; 

•

prevention of the implementation of unauthorized changes or deviations. Change control procedures are applied following the establishment of the first baseline. 

All  released  baseline  documentation,  thereafter,  is  subject  to  configuration control,  including  submission  to  the  customer  for  higher‐level  approval  or review, as necessary. As such, no formal change can be generated without an approved baseline. 

A change can be either 

•

initiated by the customer (e.g. evolution of requirements) followed by a reply from the supplier within a defined time limit, or 

proposed  by  the  supplier  (e.g.  self  initiated  improvement  of  design) followed by a response from the customer.  

•

•

4.3.3.3  Configuration control board

Configuration control boards (CCB) are established at each project level as the relevant  authority  for  all  changes.  The  CCB  is  convened  by  the  configuration manager  in  agreement  with  the  project  manager.  The  CCB  consists  of 25 ![Im0](images/Im0)

![Im30](images/Im30)

![Im5](images/Im5)

![Im6](images/Im6)

![Im4](images/Im4)

![Im35](images/Im35)

![Im36](images/Im36)

![Im3](images/Im3)

![Im37](images/Im37)

![Im1](images/Im1)

![Im2](images/Im2)

![Im10](images/Im10)

![Im8](images/Im8)

![Im7](images/Im7)

![Im38](images/Im38)

![Im39](images/Im39)

![Im11](images/Im11)

![Im12](images/Im12)

![Im9](images/Im9)

![Im19](images/Im19)

![Im13](images/Im13)

![Im14](images/Im14)

![Im33](images/Im33)

![Im34](images/Im34)

![Im22](images/Im22)

![Im23](images/Im23)

![Im20](images/Im20)

![Im15](images/Im15)

![Im21](images/Im21)

![Im24](images/Im24)

![Im25](images/Im25)

![Im27](images/Im27)

![Im27](images/Im27)

![Im16](images/Im16)

![Im17](images/Im17)

![Im28](images/Im28)

![Im29](images/Im29)

![Im26](images/Im26)

![Im21](images/Im21)

![Im24](images/Im24)

![Im31](images/Im31)

![Im32](images/Im32)

![Im18](images/Im18)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 permanent representatives of all programme or project disciplines necessary for the  review  and  evaluation  of  changes.  The  members  of  the  CCB  are  with decision‐making authority. 

A change initiated by the customer can only be implemented after examination and approval of the supplier’s response, e.g. change proposal. 

technical 

specification  and  other 

4.3.3.4  Classification of changes and departures

The  classification  of  a  change  or  departure  defines  the  type  of  approval  and release  cycle  required  according  to  criteria  with  regard  to  impacts  on  cost, schedule, 

technical  or  contractual characteristics. 

Every  change  is  classified  by  the  CCB  as  a  class  1  or  class  2  change  and departure as major or minor. The change or departure can be reclassified by the next higher level CCB. 

According to its effects, a change proposal or a departure request is processed through the different levels of the organization. The appropriate level to decide its disposition is the level for which the effects of the change or departure have no repercussions on the commitments made to the customer. The disposition is, however, transmitted to the customer for information. 

Interface control

4.3.3.5

Interface  control  is  part  of  the  configuration  control  activity  and  defines  the process  necessary  to  freeze  and  implement  interface  data,  and  the  control  of changes  affecting  the  interfaces.  The  interface  control  process  is  under  the responsibility of system engineering supported by configuration management. The CM activity provides the means to identify, track and report on the status of approved interfaces. 

Control of interfaces is performed through the “interface control document(s) (ICDs)”,  which  is/are  prepared  to  cover  all  aspects  relevant  to  interfaces  (e.g. mechanical,  electrical,  thermal  and  software).  Configuration  management provides  the  necessary  assistance  and  support  in  recording  the  status  of  the interface data and in verifying their compliance against requirements. 

4.3.4

Configuration status accounting

4.3.4.1  Overview

Configuration status accounting comprises the creation and organization of the knowledge  base  necessary  for  performing  configuration  management.  It provides the source of configuration information to support all programme or project disciplines and activities through the establishment and maintenance of  •

a  record  of  approved  configuration  documentation  (e.g.  data  sets)  and related identification numbers, 

the  status  of  proposed  changes  to  and  requested  departures  from  the established configuration, 

the implementation status of approved changes and deviations, and 

•

•

26 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 •

the  actual  configuration  of  all  units  of  configured  items  being  in  the operational inventory. 

Together these comprise the configuration status accounting report. 

4.3.4.2  As-designed and as-built data list

The  CIDL  is  a  document  generated  for  reporting  the  current  design  status  of each product configuration item. This document is provided at the PDR with the  establishment  of  the  development  configuration  baseline  and  maintained during the lifecycle of the product CI. 

The  CIDL  itself  and  the  data  included  serve  as  a  point  of  departure  for  the control of subsequent performance, design and build changes. 

When software product CIs are involved, a software configuration file is also prepared in order to provide more extensive information relevant to installation and use of the described product. 

The CIDL is the source for the preparation of the ABCL, which is the document used  to  report  the  as‐built  and  as‐tested  status  for  each  serial  number  of product CI. 

Configuration verification

4.3.5

Configuration  verification  is  the  process  to  verify  the  current  configuration status of the analyzed product and results in the establishment of configuration baselines  as  defined  in  clause  4.3.2.5.  This  activity  is  performed  during programme  or  project  reviews,  which  are  defined  in  ECSS‐M‐ST‐10  together with their objectives. 

At the end of each review, the documents and data sets that identify the current configuration  baseline  are  updated  to  be  in  conformance  with  the  review dispositions and then presented to the customer for approval. 

Configuration management process audit4.3.6

The  effectiveness  of  the  configuration  management  system  is  measured  by audits  to  verify  the  proper  application  of  configuration  management requirements during the life cycle of the product as specified by the customer. Audits are conducted in accordance with requirements defined in ECSS‐M‐ST‐10. 

4.3.7

Configuration management approach for

operational phase

The activities performed by configuration management during the operational phase  (phase  E  and  F  of  a  project)  are  those  required  by  the  set  of  reviews established by ECSS‐M‐ST‐10.  

If necessary, a dedicated CM plan can be prepared to describe the process to meet the objectives of the operational phase. 

27 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 During  this  phase  the  functions  of  CM  are  continued  from  previous  project phases. 

4.3.8

Implementation of

information/documentation management

4.3.8.1  Overview

Implementation  of  information/documentation  management  comprises  the activities as described in the following sub‐clauses. 

4.3.8.2  Creation and revision

During  this  phase  the  content  of  a  document  is  established  and  the documentation  reference  is  assigned.  This  activity  is  performed  under  the responsibility of the organization assigned in the DRL. Attributes in addition to the  documentation  reference  can  be  included  as  needed  (e.g.  DRL/DRD reference,  CI  Identifier,  authorities  involved  in  the  review  process).  For configuration controlled documents, the configuration control process defined in this standard is applied.  

In this phase the document bears the status “In Preparation”. It is considered preliminary and is therefore not used for binding agreements. The same logic applies for a new version of a document under preparation. 

Figure 4‐8 Implementation of information/documentation management 

28 ![Im0](images/Im0)

![Im19](images/Im19)

![Im49](images/Im49)

![Im86](images/Im86)

![Im87](images/Im87)

![Im88](images/Im88)

![Im50](images/Im50)

![Im82](images/Im82)

![Im83](images/Im83)

![Im26](images/Im26)

![Im25](images/Im25)

![Im84](images/Im84)

![Im85](images/Im85)

![Im51](images/Im51)

![Im52](images/Im52)

![Im19](images/Im19)

![Im19](images/Im19)

![Im27](images/Im27)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im16](images/Im16)

![Im22](images/Im22)

![Im1](images/Im1)

![Im46](images/Im46)

![Im18](images/Im18)

![Im21](images/Im21)

![Im23](images/Im23)

![Im66](images/Im66)

![Im67](images/Im67)

![Im20](images/Im20)

![Im32](images/Im32)

![Im17](images/Im17)

![Im24](images/Im24)

![Im3](images/Im3)

![Im22](images/Im22)

![Im22](images/Im22)

![Im34](images/Im34)

![Im33](images/Im33)

![Im2](images/Im2)

![Im68](images/Im68)

![Im69](images/Im69)

![Im70](images/Im70)

![Im17](images/Im17)

![Im24](images/Im24)

![Im47](images/Im47)

![Im48](images/Im48)

![Im71](images/Im71)

![Im72](images/Im72)

![Im42](images/Im42)

![Im43](images/Im43)

![Im4](images/Im4)

![Im75](images/Im75)

![Im37](images/Im37)

![Im73](images/Im73)

![Im74](images/Im74)

![Im40](images/Im40)

![Im41](images/Im41)

![Im37](images/Im37)

![Im37](images/Im37)

![Im38](images/Im38)

![Im39](images/Im39)

![Im36](images/Im36)

![Im35](images/Im35)

![Im58](images/Im58)

![Im59](images/Im59)

![Im53](images/Im53)

![Im80](images/Im80)

![Im77](images/Im77)

![Im54](images/Im54)

![Im76](images/Im76)

![Im5](images/Im5)

![Im78](images/Im78)

![Im55](images/Im55)

![Im56](images/Im56)

![Im57](images/Im57)

![Im79](images/Im79)

![Im81](images/Im81)

![Im17](images/Im17)

![Im24](images/Im24)

![Im58](images/Im58)

![Im59](images/Im59)

![Im64](images/Im64)

![Im65](images/Im65)

![Im62](images/Im62)

![Im63](images/Im63)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

![Im9](images/Im9)

![Im44](images/Im44)

![Im45](images/Im45)

![Im60](images/Im60)

![Im61](images/Im61)

![Im2](images/Im2)

![Im10](images/Im10)

![Im11](images/Im11)

![Im28](images/Im28)

![Im29](images/Im29)

![Im30](images/Im30)

![Im31](images/Im31)

![Im12](images/Im12)

![Im9](images/Im9)

![Im2](images/Im2)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 4.3.8.3  Review

4.3.8.3.1  Review activity

When  the  document  is  complete,  it  is  submitted  for  review  and  approval  as required. The review process is then initiated as specified within the CM Plan. In this phase the document bears the status “In Review”. 

The same restriction regarding its use applies as for the creation/revision phase, and is therefore not to be used for binding agreements. The review authority either confirms that the content complies with the applicable requirements, or states the identified discrepancies together with the proposed resolution. In the latter  case,  the  document  is  returned  to  the  creation/revision  phase  for incorporation of comments and resolution of the identified discrepancies.  

During the review process a document can be “withdrawn” (if it did not pass the review cycle and is maintained or traced for historical purposes only) or get the  status  “obsolete”  or  “superseded”(when 

it  has  been  released  but superseded by a new document). 

4.3.8.3.2  Approval and release

Approval can be given either by electronic signature or by process as defined in the CM Plan. 

Electronic signature or approval by process ensures that 

a.

b.

the document has not been modified after its approval (i.e. integrity), and the author cannot deny his responsibility for the content of the document (i.e. non‐repudiation). 

At  the  end  of  the  review  phase  once  all  required  approvals  are  given,  the document reaches the status “Released”. 

Once  released  the  document  is  valid  for  use  and  therefore  ready  for distribution. After the document is released, any modification to the document implies a new version. 

4.3.8.4  Delivery

Documents are delivered in line with the procedures defined by the CM Plan taking into account the level of confidentiality applicable to each document. The status of the document is not changed during delivery. 

Documents are delivered using “Technical Data Package (TDP)” format which defines  the  way  to  exchange  content  files  and  their  related  metadata  and  to structure them within folders. 

The TDP is a ZIP file containing document file(s) and metadata describing these documents.  Metadata  used  in  the  TDP  are  a  subset  of  the  ISO  10303  STEP AP232 metadata added by some specific metadata defined in Annex L. 

The metadata are stored in the ʺdatapackage.xmlʺ file. See Figure 4‐9. 

29 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure 4‐9 TDP contents 

The delivery process is summarized in the following diagram. The main steps are: 

a.

the originating organization “exportsʺ content files and metadata from its Information System (IS) to TDP; 

the originating organization provides TDP to recipient organization via e.g. e‐mail, ftp, CD‐ROM; 

the  recipient  organization  ʺopens  and  controlsʺ  the  compliance  of  the TDP; 

the recipient organization ʺimportsʺ the TDP into its Information System. b.

c.

d.

30 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im5](images/Im5)

![Im6](images/Im6)

![Im7](images/Im7)

![Im8](images/Im8)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure 4‐10 Delivery process for TDP 

Storage and retrieval

4.3.8.5

Storage and retrieval overlaps with the other phases defined above. The status of the document is not changed during storage and retrieval.  

The information system is deployed in order to handle metadata and static and dynamic content. The reproducibility and integrity of the stored information is ensured for the programme/project life cycle. 

4.3.8.6  Archiving and retrieval

Archiving  is  the  last  phase  of  the  information  process.  It  ensures  that  project information/documentation is: 

•

•

•

preserved from damage or loss, 

accessible and retrievable for use, and 

access controlled to authorized personnel. 

31 ![Im0](images/Im0)

![Im25](images/Im25)

![Im26](images/Im26)

![Im27](images/Im27)

![Im28](images/Im28)

![Im29](images/Im29)

![Im30](images/Im30)

![Im6](images/Im6)

![Im6](images/Im6)

![Im6](images/Im6)

![Im11](images/Im11)

![Im12](images/Im12)

![Im3](images/Im3)

![Im1](images/Im1)

![Im2](images/Im2)

![Im11](images/Im11)

![Im12](images/Im12)

![Im7](images/Im7)

![Im9](images/Im9)

![Im4](images/Im4)

![Im5](images/Im5)

![Im8](images/Im8)

![Im10](images/Im10)

![Im23](images/Im23)

![Im24](images/Im24)

![Im11](images/Im11)

![Im13](images/Im13)

![Im14](images/Im14)

![Im15](images/Im15)

![Im11](images/Im11)

![Im13](images/Im13)

![Im6](images/Im6)

![Im6](images/Im6)

![Im6](images/Im6)

![Im19](images/Im19)

![Im20](images/Im20)

![Im17](images/Im17)

![Im18](images/Im18)

![Im3](images/Im3)

![Im7](images/Im7)

![Im9](images/Im9)

![Im31](images/Im31)

![Im5](images/Im5)

![Im8](images/Im8)

![Im10](images/Im10)

![Im16](images/Im16)

![Im21](images/Im21)

![Im22](images/Im22)

![Im32](images/Im32)

![Im33](images/Im33)

![Im34](images/Im34)

![Im35](images/Im35)

![Im36](images/Im36)

![Im37](images/Im37)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure 4‐11 Project phases and baseline definitions  

32 ![Im0](images/Im0)

![Im1](images/Im1)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Configuration management requirements- 5.1  General

In  this  ECSS  Standard,  in  order  to  facilitate  reading  and  traceability,  the paragraph numbering in this clause is consistent with the paragraph numbering of clause 4.  

- 5.2  Management and planning

5.2.1

Configuration management plan

5.2.1.1  General

a.

Each  supplier  shall  provide  for  customer’s  approval  a  configuration management  plan 

in  conformance  with  Annex  A,  configuration management plan DRD. 

Internal  procedures  called  up  in  the  configuration  management  plan shall be made available for customer review upon request. 

Information security

Information  shall  only  be  classified  when  imposed  by  national  or international laws, or by programme / project requirements, or to protect company / organizational interests. 

Information  shall  be  protected  against  unauthorized  access  and according to the confidentiality classes.  

The  information  access  and  confidentiality  classes  shall  be  agreed between customer and supplier. 

The list of authorized personnel having access to the information system shall be agreed between the customer and supplier. 

b.

5.2.1.2

a.

b.

c.

d.

5.2.1.3  Classification

![Im0](images/Im0)

<table align="center">
</table>

b.

Classification classes shall be clearly indicated on the documents. 

33 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Classified information shall be accessible only to persons having the right authorizations and privileges. 

Classified  information  shall  be  used  only  in  a  secure  environment  or c.

d.

![Im0](images/Im0)

<table align="center">
</table>

The  assigned  classification  shall  be  maintained  only  as  long  as  the information requires protection. 

The  responsibility  for  classifying  information  shall  rest  solely  with  the originating organization. 

Destruction  of  classified 

destruction shall be recorded. 

Classified information shall be downgraded or declassified only with the prior written consent of the originating organization. 

the  method  used  for information  and 

e.

f.

g.

h.

5.2.2

a.

b.

c.

d.

e.

Configuration management interfaces

Configuration  management  processes  shall 

interface  with  project management and planning, taking into account the contractual provision and  schedule  organization  for  the  definition  and  phasing  of  CM activities. 

Configuration  management  processes  shall  interface  with  engineering and product assurance for agreeing the technical information for which the CM process controls. 

Configuration  management  processes  shall  interface  with  IDM  for defining  rules  for  documentation  identification  and  processing,  control and distribution. 

Configuration  management  processes  shall  interface  with  IDM  to support  Engineering,  Product  Assurance  (PA),  manufacturing  and production by providing the information/documentation in time and in adequate format for their activities. 

Configuration  management  processes  shall  interface  with  logistic  and maintenance processes to determine up to which level of product the CM process shall be applied. 

- 5.3

Implementation of configuration management

5.3.1

Configuration identification

5.3.1.1  Configuration item

a.

A configuration item shall be defined in relation to the following criteria: 1.

by its complete design documentation if it is developed for space application; 

34 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 2.

3.

including  the 

list  of its  procurement  specification, 

by 

its performances  and  interface  characteristics,  if  it  is  an  off‐the‐shelf (OTS) product; 

by reference to its governing standard, if it is a product defined by a standard. 

5.3.1.2  Configuration item selection

a.

Based on customer input, the supplier shall identify in the product tree, the  configuration  items  and  their  applicable  specifications,  and  agree these with its customer. 

NOTE 1  Detailed  guideline  for  selecting  configuration 

items is given in Annex K. 

NOTE 2  For product tree see ECSS‐M‐ST‐10. 

b.

c.

The supplier shall prepare the list of configuration items it supplies and keep  this  under  configuration  control  in  conformance  with  Annex  B, configuration item list DRD. 

The  configuration  item  list  shall  be  provided  at  the  PDR  for  customer approval. 

5.3.1.3  Configuration baseline

a.

The  supplier  shall  agree  with  its  customer  which  documentation  shall constitute each configuration baseline. 

NOTE 1  For  hardware  products,  configuration  baselines 

include the following documents: 

•

•

•  general specifications (e.g. environment, 

the functional specification; 

the technical specification; 

radiation, design rules, interfaces, and PMP); 

•

•

•

•  procurement specification for OTS items; 

•  standardization document; 

•  engineering  drawings  (e.g.  interface  control 

drawings,  parts  and  assembly  drawings,  and 

installation drawings) and associated lists; 

the interface control document; 

the configuration items data list; 

the installation/user/operating/maintenance 

manual; 

test specifications; 

test procedures; 

•

•

•  applicable engineering changes; 

•  applicable deviations. 

35 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 NOTE 2  For  software  products,  configuration  baselines 

include the following documents: 

•  software  system  technical  specification,  when 

applicable; 

•  software requirements document (SRD); 

•  software design document; 

•

interface control document; 

•  software configuration file (SCF) (including the 

source code listing); 

•  software release document; 

•

the installation/user/operating/maintenance 

manual; 

the 

the 

development tools (e.g. compilers, and linkers); 

configuration 

description 

of 

•

•  software validation testing specifications; 

•  software test procedures; 

•  maintenance procedures; 

•  applicable engineering changes; 

•  applicable deviations. 

b.

The baseline documentation shall reflect the actual configuration of the product, at any given point of the product life cycle. 

5.3.1.4  Baseline establishment

a.

Baselines shall be established at the conclusion of each technical review as the starting point for configuration control as defined below:  

1.

for 

The  starting  point  of  configuration  control 

functional specification  is  at  conclusion  of  the  preliminary  requirements review (PRR), establishing the mission objective baseline. 

The  starting  point  of  configuration  control  for  system  technical specifications  (TS)  is  at  conclusion  of  the  system  requirements review (SRR), establishing the functional configuration baseline. The  starting  point  of  configuration  control  for  product  technical specifications  (TS)  and  ICDs  is  at  conclusion  of  the  preliminary design review (PDR), establishing the development configuration baseline.  This  represents  freezing  of  performance  and  design 2.

3.

![Im0](images/Im0)

<table align="center">
</table>

The  starting  point  of  configuration  control  of  the  product  design for PFM/FM model manufacturing for qualification purposes is at the conclusion of the CDR, establishing the design baseline. 

The starting point of configuration control of the qualified product design for serial production is at the conclusion of the PCV, or for 4.

5.

36 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 prototype(s)  at  QR/AR,  establishing  the  product  configuration baseline. 

The starting point of configuration control of the user manual is at conclusion of the qualification review (QR). 

The starting point for issue and maintenance of the log book is at conclusion of the acceptance review (AR). 

6.

7.

b.

The supplier shall maintain the configuration baselines through out the programme or project life cycle. 

Identification marking

5.3.1.5

a.

Any  product  item  shall  be  identified  to  guarantee  its  traceability throughout the programme or project life cycle. 

For developed hardware CI, the following information shall be included: 1.

2.

3.

CI‐identifier 

Part number 

Serial or lot number 

b.

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

c.

d.

e.

Product name or abbreviation. 

product name or abbreviation. 

CI‐identifier 

Software identifier 

Version and revision number 

Release date 

5.  Manufacturer identifier 

6.

For  developed  software  CIs,  the  following  shall  be  included  in  the header: 

1.

2.

3.

4.

5.  Manufacturer identifier 

6.

For  OTS  and  standard  products,  the  following  information  shall  be included as a minimum: 

1.

2.

3.  Manufacturer identifier 

4.

All product items, not defined as configuration item, shall be marked or labelled including the following information: 

1.

2.

Part number 

Serial or lot number, when applicable 

Part number 

Serial or lot number 

Product name or abbreviation. 

37 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 f.

g.

link 

to 

identification 

to  provide  a 

3.  Manufacturer identifier. 

All  product  items  subject  to  major  nonconformances  shall  receive supplemental 

the  departure authorization document. 

For  media  containing  software,  the  following  information  shall  be included as a minimum: 

1.

2.

3.

4.

5.  Manufacturer identifier; 

6.

7.

8.

9.

Product name or abbreviation; 

SCF reference including issue and date; 

Total number of delivered media per information set (1 of ...); 

Copy or serial number of data set. 

CI‐identifier; 

S/W identifier; 

Version and revision number; 

Date of generation; 

h.  When  the  physical  dimensions  of  the  item  restricts  full  identification marking, the following shall apply: 

1.

Select a minimum set of information which uniquely identifies the items. 

Identify on a permanent tag, if possible. 

If permanent tag is not possible, identify on a removable tag or on the packaging. 

2.

3.

i.

j.

k.

The identification marking methods applied shall be compatible with the product’s operational environment. 

The  identification  marking  methods  applied  shall  be  defined  in  the configuration definition document. 

Identification marking of software products shall be established through the hardware product where the software is resident (i.e. the firmware), or the media in which the software is stored. 

5.3.1.6  Digital file and media identification

a.

Digital  files  defining  configuration  characteristics  shall  be  uniquely identified and linked to their related product configuration data. 

The digital data files forming part of each configuration baseline shall be stored in a secure environment with controlled access. 

Digital  files  composing  the  definition  of  configuration  characteristics shall  be  maintainable  throughout  the  life  cycle  of  the  programme  or project. 

Digital  files  defining  the  configuration  characteristics  shall  be  stored within  the  CM  system  by  its  native  code  and  by  a  PC  readable  file b.

c.

d.

![Im0](images/Im0)

<table align="center">
</table>

38 ![Im0](images/Im0)

e.

f.

g.

h.

i.

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 The  system  shall  be  able  to  manage  check‐in/check‐out,  multiple versions. 

The system shall be able to generate any current, baseline or past version of the file.  

Distribution, delivery or publishing of the file shall be generated from the master file. 

Paper forms of digital files shall be traceable to the master file. 

The  order  of  precedence  between  the  master  file  and  the  printed documentation shall be established. 

<table align="center">
	<tr align="center">
	</tr>
</table>

k.

l.

CI identifier 

File names 

Version and issue 

Date of generation 

Generating entity 

Total number of delivered media per information set (1 of ...). 

Digital data media shall be identified by the following: 

1.

2.

3.

4.

5.

6.

The  following  information  shall  be  provided  together  with  digital  data media: 

1.

2.

3.

4.

Host system 

Application software 

Printer and style details 

Special instruction for further processing of the data file. 

5.3.2

Configuration control

5.3.2.1  Change procedure

a.

A  change  procedure  shall  be  established  to  describe  the  process  for changing a configuration baseline. 

Any  change  to  a  configuration  item,  in  relation  to  an  approved configuration baseline, shall be described, justified and classified by the requesting party, before submission for review and disposition. 

Each actor shall establish a configuration control board to evaluate and approve  any  change  to  a  configuration  item  relative  to  a  configuration baseline. 

Related changes of several products resulting from a common need for change shall be processed simultaneously. 

b.

c.

d.

39 ![Im0](images/Im0)

e.

Changes  related  to  an  element  common  to  several  products  shall  be presented to all the concerned actors for impact assessment. 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 5.3.2.2  Classification of changes and departures

a.

A  class  1  change,  or  a  major  departure,  shall  be  approved  by  the customer before its implementation. 

A  class  2  change,  or  a  minor  departure,  shall  be  implemented  after supplier approval and provided to the customer for information. 

Customer  may  reclassify  the  class  2  proposed  changes  and  minor departures. 

Unplanned departures shall be classified and processed in conformance to ECSS‐Q‐ST‐10‐09. 

b.

c.

d.

e.  Major planned departures shall be processed as for class 1 changes. 

f.

Minor planned departures shall be processed as for class 2 changes. 

g.

For planned departures from requirements or design, the supplier shall submit  a  request  for  deviation  describing  why  the  product  concerned cannot meet requirements of the baselined configuration documentation. The supplier shall ensure that changes or departures are approved at the level  for  which  the  effects  of  the  change  or  the  departure  can  have  no repercussion on the commitments made to the customer. 

The evaluation shall be transmitted to the customer for information. 

h.

i.

Initiation of change

5.3.2.3

a.

All  changes  initiated  by  the  customer  shall  use  a  change  request  in conformance with Annex G, change request DRD. 

All  changes  initiated  by  the  supplier  shall  use  a  change  proposal  in conformance with Annex H, change proposal DRD. 

b.

b.

c.

5.3.2.4  Change assessment

a.

Both  customer  and  supplier  shall  establish  procedures  for  the  analysis, review and disposition of proposed changes. 

The  change  assessment  shall  cover  all  technical,  programmatic  and operational  impacts  on  all  affected  products  for  which  the  actor  is responsible. 

Each project actor shall assess any request or proposal for a change to a configuration  baseline,  which  is  presented  to  him  by  his  customer  or supplier. 

5.3.2.5  Change disposition

a.

All changes shall be dispositioned by the configuration control board as either: 

1.

approved,  defining  the  applicability  of  evolution  and  associated implementation modes, 

40 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 2.

3.

rejected, with a supporting rational, or 

deferred until additional information is provided. 

5.3.2.6  Departures from configuration baseline

a.

The  supplier  shall  request  planned  departures  from  requirements  or design  using  a  request  for  deviation  in  conformance  with  Annex  I, request for deviation DRD. 

The  supplier  shall  request  unplanned  departures  from  requirements  or design using a request for waiver in conformance with Annex J, request for waiver DRD. 

The  configuration  control  board  shall  process  deviations  and  waivers from baselined requirements or design when customer requirements are affected. 

Departures shall be limited to a number of items or a period of time.  Deviations  related  to  an  element  common  to  several  products  shall  be presented to all the concerned actors for impact assessment. 

5.3.2.7  Baseline and documentation update

a.

Configuration  baselines  shall  be  updated  in  conformance  with  the disposition of approved changes and deviations.  

Configuration‐controlled  documents  shall  be  revised  to  incorporate approved changes. 

b.

b.

c.

d.

e.

c.

d.

e.

Interface control

5.3.2.8

a.

b.

Each actor shall record the status of interface definition data. 

Each actor shall ensure that all interface definition data is consistent with its product configuration. 

The  supplier  shall  identify  and  control  the  internal  interfaces  of  its product  and  those  interfaces  for  which  he  has  received  delegated authority. 

Configuration management shall establish, concurrently with the system engineering,  the  overall  organization  and  procedures  to  process  and manage changes to interfaces. 

Each  actor 

clearly 

documentation the data subject to interface management. 

configuration  definition shall 

identify 

in 

5.3.3

Configuration status accounting

5.3.3.1  General

a.

All  actors  shall  establish  a  configuration  status  accounting  system  to record, store and retrieve the following configuration data: 

1.

status of the configuration baselines; 

41 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 2.

3.

4.

5.

6.

design status of the configuration items; 

as‐built status of accepted products; 

status of configuration documentation and configuration data sets; status  of  approval  of  changes  and  deviations  and  their  status  of implementation, the status of waivers; 

status of actions derived from technical reviews and configuration verification reviews. 

b.

Each  supplier  shall  provide  configuration  status  accounting  reports  in conformance  with  Annex  F,  configuration  status  accounting  reports DRD. 

5.3.3.2  As-designed data list

a.

The  supplier  shall  provide  a  configuration  item  data  list  (CIDL),  in conformance  with  Annex  C,  configuration  item  data  list  DRD,  for  each deliverable CI. 

For  each  deliverable  software  CI,  the  supplier  shall  provide  a  software configuration  file  (SCF)  in  conformance  with  Annex  E,  software configuration file DRD. 

A  CIDL  shall  be  available  for  the  first  design  review  to  determine  the initial configuration baseline. 

The complete CIDL for an individual CI, model or deliverable item shall be available at project reviews. 

Changes implemented after delivery of the product shall be incorporated in the CIDL. 

The updated CIDL shall be provided for log‐book updating. 

b.

c.

d.

e.

f.

b.

c.

5.3.3.3  As-built data list

a.

For  each  deliverable  serial  number  of  CI,  the  supplier  shall  provide  an as‐built  configuration  data  list  in  conformance  with  Annex  D,  as‐built configuration list DRD. 

The ABCL shall identify the “as manufactured” and “as tested” statuses applicable to parts composing a CI. 

Using the CIDL as a reference, any difference between the ABCL and the CIDL  shall  be  documented  in  the  ABCL  by  reference  to  the  applicable NCR(s) or RFW(s). 

5.3.4

Configuration verification

5.3.4.1

a.

Verification of the product configuration definitionAt SRR, the functional configuration definition shall be verified against mission objectives. 

42 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 b.

c.

At  PDR,  the  development  configuration  definition  shall  be  verified against the applicable technical specifications. 

At  CDR,  the  design  definition  shall  be  verified  against  the  relevant design documentation. 

5.3.4.2

a.

b.

c.

Verification of the product configuration

The  supplier  shall  perform  configuration  verification  by  systematically comparing  the  “as‐built”  configuration  of  a  CI  with  its  “as  designed” configuration. 

Configuration  in  terms  of  functional  and  performance  characteristics shall be verified at qualification review (QR) for prototype or proto‐flight production, and FCV for serial production. 

Configuration 

terms  of  physical  and  nominal  performance characteristics  shall  be  verified  at  AR  for  prototype  or  proto‐flight production and PCV for serial production. 

in 

5.3.5

Audit of the configuration management

system

a.

b.

Each project actor shall conduct internal audits to verify the application of configuration management requirements internal to his organization.  Each project actor shall conduct external audits to verify the application of configuration management requirements by its lower tier suppliers, in accordance with the requirements defined in ECSS‐M‐ST‐10. 

5.3.6

a.

Configuration management approach for

operational phase

following  product  configuration  related  activities  shall  be The 

implemented during the operational phase: 

1.

Preparation  of  a  CM  plan  in  conformance  with  Annex  A, configuration management plan DRD, to meet the objective of the operational phase. 

NOTE 

This  requirement  can  be  fulfilled  by  adapting  the 

development  phase  CM  plan  or  creating  a 

dedicated CM plan. 

2.

Provisioning  of,  or  access  to  development  phase  documents  as established at product delivery.  

4.

3.  Maintenance and control of ground models (i.e. engineering model and  mock‐ups)  supporting  the  flight  operations  to  be  flight representative.  

Inventory  control  of  flight  spare  parts  in  terms  of  quantity  and ![Im0](images/Im0)

<table align="center">
</table>

43 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 (a)

(b)

(c)

for  in‐line  production  with  no  retrofit  to  delivered  units, production  changes  are  undertaken  by  normal  change processing; 

for  in‐line  production  with  retrofitting  of  delivered  units, retrofit  changes  are  either  carried  out  by  the  supplier  on basis of contractor modification documentation; or 

retrofit of delivered units (no more production) by the user, on  basis  of  a  modification  kit  with  accompanying modification instructions. 

Design  change  implementation  on  product  according  to  the following cases: 

(a)

normal  change  processing  for  in‐line  production  with  no retrofitting of delivered product; 

documentation  update 

in‐line  production  with retrofitting of delivered product performed by the supplier; or 

(b)

for 

6.

(c)  modification 

kit  with 

accompanying  modification instructions for retrofitting by the user of the product. 

5.3.7

Implementation of

information/documentation management

5.3.7.1  General

a.

b.

c.

Each actor shall ensure that the information management processes and information system are in accordance with the project needs. 

The  information  system  shall  support  the  creation,  collection,  review, delivery,  storage,  retrieval  and  archiving  of  information/documentation and related data. 

The relevant project information/documentation shall be accessible to all authorized project members.  

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

e.

f.

All information/documentation released for a programme or project shall be managed electronically.  

In case of discrepancies between electronic and paper based information the electronically stored version shall take precedence. 

NOTE 

In case of conflict the national/European law takes 

precedence. 

44 ECSS‐M‐ST‐40C Rev. 1 ![Im0](images/Im0)

<table align="center">
</table>

a.

information/documentation  content  shall  be  established Responsibility  for  the  information/documentation  content  shall  lie  with the organization closest to the data source. 

Author(s)  for  creating  the information/documentation  shall  be  assigned responsibility by the relevant organization. 

The 

accordance with the DRD which describes the document. 

Author(s)  shall  always  identify  the  reason(s)  for  generating  a  new document issue. 

Process for revising information/documents shall involve and apply the same authorities and approval process as for previous issues. 

During  the  creation  phase  the  information/documentation  shall  be in b.

c.

d.

e.

f.

<table align="center">
</table>

b.

a.

information  shall  be  maintained  within 

All  project‐related 

information system. 

Data applicable to a programme or project shall be ordered in such a way that  they  can  be  extracted  from  the  information  system  and  ordered according to the predefined values.  

the c.  Metadata  shall  be  identified  and  entered  into  the  information  system, <table align="center">
</table>

b.

a.

In  the  case  of  paper  documents,  their  content  shall  be  converted  to electronic  format  and  uploaded  into  the  information  system  together with its metadata. 

The process of converting electronic content from its native format to the <table align="center">
</table>

a.

b.

Each document and each document issue shall be uniquely identified. Configuration management requirements shall be taken into account for documents that are part of a configuration baseline. 

<table align="center">
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

5.3.7.2.5  Revision

a.

b.

Changes to information/documentation shall be always justified. 

Changes  to  information/documentation  and  their  justification  shall  be traceable within the information /documentation. 

45 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 c.

d.

The  updating  of  any  configuration  controlled  document  shall  be processed according to the configuration process. 

Once  released,  the  integrity  of  any  information/documentation  shall  be ![Im0](images/Im0)

<table align="center">
</table>

a.

actor 

a 

for 

each shall 

review 

implement 

Each 

cycle 

information/documentation item he is required to release.  

The  review  cycle  for  classified  information/documentation  shall  be established  according  to  the  level  of  classification  defined  for  the information/documentation itself. 

The  supplier  shall  implement  a  control  process  to  ensure  that  all information  requiring  customer  or  lower  tier  supplier  signatures  are submitted on time to the customer or lower tier supplier. 

The customer shall confirm his approval or non‐approval with rationale to the relevant supplier in accordance with their business agreement. The lower tier supplier shall confirm his approval or non‐approval with rationale  to  the  relevant  customer  within  the  contractually  agreed timeframe. 

Any  discrepancy  raised  against  a  document  shall  be  provided  to  the originating organization in writing. 

Information/documents  shall  be  delivered  when  the  review  cycle  has b.

c.

d.

e.

f.

g.

<table align="center">
</table>

a.

b.

Information/documentation shall be signed using digital signature. 

The  digital  signature  shall  be  in  compliance  with  internationally recognized standards. 

Self‐signed certificates shall not be used. 

The 

information/documentation in any electronic format. 

The digital signature shall support multiple signing. 

Digitally signed information shall provide indication that the information has been digitally signed.  

A  digitally  signed  document  shall  provide  on  the  cover  page  an indication stating that the document has been digitally signed. 

implemented 

c.

d.

e.

f.

g.

signature 

digital 

shall 

sign be 

to 

NOTE 

Information about digital signature is provided in 

<table align="center">
</table>

a.

Information/documentation  approved  by  an  informatics  process  shall clearly indicate approval in a visible manner: 

46 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 1.

on  the  cover  page  of  the  electronic  document  file  (source  file  or .pdf‐file); 

as part of the information file header. 

2.

Actors  involved  in  the  approval  loop  shall  be  identified  on  approved Information/documentation. 

The information system managing the process shall record the processing steps of approval. 

A  Log‐File  of  the  processing  steps  of  approval  shall  be  generated automatically by the information system.  

The  Log‐File 

together  with 

shall  be 

stored 

the 

released b.

c.

d.

e.

![Im0](images/Im0)

<table align="center">
</table>

a.

Information/documentation shall be delivered using TDP. 

b.

c.

d.

NOTE 

For  details  see  Annex  L,  Technical  Data  Package 

Description. 

Customer  and  Supplier  shall  agree  upon  the  optional  meta‐data  to  be exchanged. 

NOTE 

For  details  see  Annex  L,  Technical  Data  Package 

Description. 

Based  on  customer  input,  the  supplier  shall  provide  for  customer approval  the  method,  format  and  schedule  for  the  delivery  of  the required information. 

The following formats shall be used for delivery: 

<table align="center">
	<tr align="center">
		<td>Read‐only documents  </td>
		<td>Acrobat PDF compatible format </td>
	</tr>
	<tr align="center">
		<td>Editable documents </td>
		<td>MS Office compatible format </td>
	</tr>
	<tr align="center">
		<td>Photographic images </td>
		<td>JPEG compatible format </td>
	</tr>
	<tr align="center">
		<td>Technical images </td>
		<td>TIFF with LZW or other lossless  compression </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>Technical Data Package </td>
		<td>TDP ZIP </td>
	</tr>
</table>

 

e.

NOTE   Additional  formats  can  be 

implemented  and 

agreed with the customer  

The delivery mechanism shall ensure that the information: 

1.

2.

comes from a given, identified sender (guarantee of authenticity);  cannot  be  disclaimed  by 

(guarantee  of  non‐repudiation); 

cannot be read by third parties during transmission (guarantee of confidentiality); 

the  sender 

3.

47 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 third  parties  during 

transmission 4.

cannot  be  modified  by 

(guarantee of data integrity). 

NOTE 

Electronic mail via SMTP and file transfer via FTP 

cannot  be  used  with  unencrypted  files,  because 

these  delivery  methods  do  not  meet  the  above 

requirements. 

f.  Where a concurrent environment is available, accessibility to it shall be possible  by  using  established  privileges  and  rules  for  authorized ![Im0](images/Im0)

<table align="center">
</table>

a.

throughout 

the 

the  programme/project  members 

Each actor shall ensure that the information/documentation is available to 

entire programme/project life cycle.  

Each  actor  shall  store  all  released  document  issues  in  the  information system. 

Each actor shall store information/documentation in its native format for future 

the programme/project life cycle. 

Information/documentation shall be protected against environmental and accidental risks and against unauthorized access. 

Access  to  classified  information/documentation  shall  be  restricted  to together  with  metadata, 

throughout 

update, 

b.

c.

d.

e.

<table align="center">
</table>

b.

a.

The supplier shall define and implement an archiving solution to ensure that project information/documentation is: 

1.

2.

3.

The supplier shall agree with the customer the duration of the archiving activities. 

preserved from damage or loss, 

accessible and retrievable for use, and 

access controlled to authorized personnel. 

48 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex A (normative)Configuration management plan - DRD- A.1  DRD identification

### A.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.2.1.1a. 

### Purpose and objective

### A.1.2

The  objective  of  the  configuration  management  plan  is  to  provide  in  a  single document  all  elements  necessary  to  ensure  that  the  implementation  of configuration management meets customer requirements and is commensurate with the programme or project, organization, and management structure. 

- A.2  Expected response

### A.2.1

### Scope and content

<1>

a.

<2>

a.

Introduction 

The  configuration  management  plan  shall  contain  a  description  of  the purpose and objective prompting its preparation. 

Applicable and reference documents 

The  configuration  management  plan  shall  list  the  applicable  and reference documents in support of the generation of the document. 

<3>  Management 

<3.1> Organization 

a.

The  configuration  management  plan  shall  describe  the  organizational context,  both  technical  and  managerial,  within  which  the  prescribed configuration management activities shall be implemented.  

49 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 b.

c.

The configuration management plan shall also describe the interface with other CM organizations (customer and supplier) and the CM relationship to other internal organization elements. 

The configuration management plan shall also describe the interface for the information management activities. 

<3.2> Responsibilities 

a.

The  configuration  management  plan  shall  describe  the  allocation  of responsibilities  and  authorities  for  configuration  management  activities to  organizations  and  individuals  within  the  programme  or  project structure. 

<3.3> Policies, directives and procedures 

a.

Any  external  constraints,  or  requirements,  placed  on  the  configuration management  plan  by  other  policies,  directives,  or  procedures  shall  be identified  in  this  section  together  with  the  consequences  of  applying these to the programme or project.  

<3.4> Security  

a.

Customer  and  suppliers  shall 

the  configuration management plan the classification classes to be applied and the relevant documentation set. 

indicate  within 

<4>

Configuration Management  

<4.1> General 

a.

b.

The  configuration  management  plan  shall  identify  all  functions  and processes,  both  technical  and  managerial,  required  for  managing  the configuration of the programme or project.  

The configuration management plan shall introduce the following, as a minimum: 

1.

2.

3.

4.

5.

6.

configuration identification; 

configuration control; 

configuration status accounting; 

configuration audits and reviews; 

interface control; 

supplier control. 

<4.2> Configuration identification 

a.

The  configuration  management  plan  shall  identify,  name,  and  describe the  documented  physical  and 

the information  to  be  maintained  under  configuration  management  control functional  characteristics  of 

![Im0](images/Im0)

<table align="center">
</table>

50 ![Im0](images/Im0)

c.

d.

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 1.

2.

3.

product tree establishment (System decomposition); 

identification  of  configuration  items,  i.e.  the  selection  process  of the  items  to  be  controlled  and  their  definitions as  they  evolve  or are selected; 

naming  of  configuration  items,  i.e.  the  specification  of  the identification system for assigning unique identifiers to each item to be controlled; 

configuration baselines establishment and maintenance; 

interface identification; 

configuration documentation and data release procedures. 

procedure to enter a software configuration item into a baseline; procedure to configure and establish a baseline; 

software products and records to define a baseline; 

procedure to approve a baseline; 

authority to approve a baseline. 

4.

5.

6.

In case of software configuration item and where a tool is used to build its baseline, the following shall be described: 

1.

2.

3.

4.

5.

In  case  software  libraries  are  established,  the  following  shall  be identified: 

1.

2.

3.

4.

5.

library types; 

library locations; 

media used for each library; 

library population mechanism; 

number  of  identical  libraries  and  the  mechanism  for  maintaining parallel contents; 

library contents and status of each item included in; 

conditions  for  entering  a  SCI,  including  the  status  of  maturity compatible  with  the  contents  required  for  a  particular  software library type; 

provision  for  protecting  libraries  from  malicious  and  accidental harm and deterioration; 

software recovery procedures; 

conditions for retrieving any object of the library; 

library access provisions and procedures. 

6.

7.

8.

9.

10.

11.

<4.3> Configuration control 

a.

The  configuration  management  plan  shall  describe  the  configuration control process and data for implementing changes to the configuration items and identify the records to be used for tracking and documenting the sequence of steps for each change. 

51 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 b.

The  configuration  management  plan  shall  describe  the  following,  as  a minimum: 

1.

2.

3.

4.

5.

6.

7.

8.

9.

configuration control board functions, responsibilities, authorities; processing changes; 

change requests; 

change proposal; 

change evaluation; 

change approval; 

change implementation; 

processing planned configuration departures (deviations); 

processing  unplanned 

nonconformances, waivers). 

configuration  departures 

(product <4.4> Interface control 

a.

The configuration management plan shall describe the process and data for  coordinating  changes  to  the  programme  or  project  configuration management items with changes to interfaces. 

<4.5> Supplier control 

a.

For both subcontracted and acquired products (i.e. equipment, software or service), the configuration management plan shall define the process and  data  to  flow  down  the  CM  requirements  and  the  programme monitoring methods to control the supplier.  

The configuration management plan shall define the process and data to incorporate  the  supplier  developed  items  into  programme  or  project configuration management and to coordinate changes to these items.  The configuration management plan shall also describe how the product is received, tested, and placed under configuration control. 

b.

c.

b.

<4.6> Configuration status accounting 

a.

The configuration management plan shall describe the process and data for reporting the status of configuration items.  

The  following  minimum  information  shall  be  tracked  and  reported  for each configuration management item: 

1.

2.

3.

4.

status of the configuration baselines; 

design status of the configuration item; 

status of configuration documentation and configuration data sets; status  of  approval  of  changes  and  deviations  and 

their implementation status; 

status of discrepancies and actions arising from technical reviews and configuration verification reviews. 

5.

52 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <4.7> Configuration verification 

a.

The configuration management plan shall describe the process and data to  verify  the  current  configuration  status  from  which  the  configuration baselines are established.  

The  configuration  management  plan  shall  provide  the  description  of verification plans, procedures and schedules. 

The  configuration  management  plan  shall  identify  how  the  recording, reporting  and  tracking  of  action  items  and  incorporation  of  review recommendations are maintained. 

b.

c.

b.

<4.8> Audits of CM system 

a.

The configuration management plan shall describe the process, data and schedule  for  configuration  audits  to  ensure  that  the  configuration management of the programme or project is performed.  

As a minimum, the configuration management plan shall enable that 1.

the CM process is properly defined, implemented and controlled, and 

the configuration management items reflect the required physical and functional characteristics. 

2.

<4.9> Technical data management 

a.

The configuration management plan shall describe the process and data to access and maintain text and CAD files, data and software repositories, and the implementation of any PDM system. 

<5>

Information/documentation  management 

<5.1> Information identification 

a.

shall  describe 

The  configuration  management  plan 

the  main information/documentation categories, such as management information, contractual  documentation  or  engineering  data,  to  be  established  and used throughout the programme/project life cycle. 

The  configuration  management  plan  shall  describe  methods  for information/document identification including versioning. 

The configuration management plan should list the codes for companies, information 

types,  models,  subsystems,  etc.  which  are  applied specifically  in  the  identification  method  or  are  in  general  use  during project execution.  

The  configuration  management  plan  shall 

structures of the main information categories. 

identify  the  metadata b.

c.

d.

<5.2> Data formats 

a.

The  configuration  management  plan  shall  define  for  the  various information categories the data formats to be used for 

53 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 content creation and update 

distribution 

archiving 

1.

2.

3.

The  configuration  management  plan  shall  specify  which  format  takes precedence in case a format conversion is applied. 

b.

<5.3> Processes 

a.

The configuration management plan shall describe the actors involved in, as well as the method and processes for, creating, collecting, reviewing, approving, storing, delivering and archiving information items. 

The configuration management plan shall describe the handling of legacy documentation and ʺoff‐the‐shelfʺ documentation. 

The  configuration  management  plan  shall  define  the  information retention period. 

b.

c.

<5.4> Information systems 

a.

The  configuration  management  plan  shall  list  the  project  information ![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

<5.5> Delivery methods 

a.

The configuration management plan shall describe the methods used to deliver TDPs. 

<5.6> Digital signature 

a.

The  configuration  management  plan  shall  define  the  procedures, methods  and  rules  applicable  to  digital  signatures.  This  comprises information about the following aspects: 

1.

2.

3.

4.

5.

certificate type 

management of signature key 

time stamping 

signing of PDF documents 

multiple signatures per document 

<5.7> Information status reporting 

a.

b.

The  configuration  management  plan  shall  describe  the  process  and content for reporting the status of information items. 

For  documentation  the  following  attributes  shall  be  reported  as  a minimum: document identification, version, title, issue date, status, and document category. 

54 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <6>

Schedule and resources 

<6.1> Schedule 

a.

The  configuration  management  plan  shall  establish  the  sequence  and coordination for all the configuration management activities and all the events affecting the CM plan’s implementation. 

<6.2> Resources 

a.

The configuration management plan shall identify the tools, techniques, equipment, personnel, and training necessary for the implementation of configuration management activities. 

### Special remarks

### A.2.2

a.

The  response  to  this  DRD  may  be  combined  with  the  response  to  the project management plan, as defined in ECSS‐M‐ST‐10. 

55 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex B (normative)Configuration item list - DRD- B.1  DRD Identification

### B.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.1.2b. 

### Purpose and objective

### B.1.2

The objective of the configuration item list is to provide a reporting instrument defining the programme or project items subject to configuration management process. 

- B.2  Expected response

### B.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

Introduction 

The  introduction  shall  describe  the  purpose  and  objective  of  the configuration item list. 

Applicable and reference documents 

The  configuration  item  list  shall  list  the  applicable  and  reference documents in support to the generation of the document. 

List 

The configuration item list shall contain for each configuration item (CI) the following information: 

1.

2.

3.

identification code (derived from the product item code); 

models identification and quantity; 

CI name; 

56 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 4.

5.

6.

CI category (developed, non‐developed); 

CI supplier; 

applicable specification. 

### Special remarks

### B.2.2

None. 

57 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 ![Im0](images/Im0)

<table align="center">
</table>

### C.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.3.2a. 

### Purpose and objective

### C.1.2

The  configuration  item  data  list  (CIDL)  is  a  document  generated  from  the central database giving the current design status of a configuration item (CI), at any point of time in sufficient detail, providing its complete definition. 

- C.2  Expected response

### C.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

Introduction 

The  introduction  shall  describe  the  purpose  and  objective  of  the configuration item data list. 

Applicable and reference documents 

The  configuration  item  data  list  shall  list  the  applicable  and  reference documents in support to the generation of the document. 

List 

The configuration item data list shall include the following: 

1.

2.

Cover sheets and scope. 

Customer controlled documentation, including 

(a)

(b)

customer specifications and ICDs, and 

support specifications. 

58 ![Im0](images/Im0)

3.

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 compatibility  with Engineering or design documentation, including 

(a)

verification  plans  demonstrating 

specified requirements, 

<table align="center">
	<tr align="center">
	</tr>
</table>

4.

5.

declared PMP lists, 

lower level specifications, 

lower level ICDs, 

drawings and associated lists, 

test specifications, 

test procedures, and 

users manual or handbook. 

(c)

(d)

(e)

(f)

(g)

(h)

(i)

List of applicable changes not yet incorporated into the baselined documentation,  and  deviations  (including  status,  directly  related to  the  document  (e.g.  specification)  to  which  the  change  belongs to). 

CI number breakdown 

(a)

indentured  breakdown  by  part  numbers  starting  from  the part number associated with the CI down to the lowest level of composition; 

quantity  of  each  part  number  used  on  the  next  higher assembly; 

issue status of the  drawings and associated lists applicable to each part number. 

(b)

(c)

b.

Each entry in the CIDL shall relate to the applicable model(s) of the CI and be defined by its document number, title, issue and release date. 

### Special remarks

### C.2.2

None. 

59 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex D (normative)As-built configuration list - DRD- D.1  DRD identification

### D.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.3.3a. 

### Purpose and objective

### D.1.2

The objective of the as‐built configuration list (ABCL) is to provide a reporting instrument defining the as‐built status per each serial number of configuration item subject to formal acceptance. 

- D.2  Expected response

### D.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

Introduction 

The introduction shall describe the purpose and objective of the as‐built configuration list. 

Applicable and reference documents 

The  as‐built  configuration  list  shall  list  the  applicable  and  reference documents in support to the generation of the document. 

List 

The  as‐built  configuration  list  shall  list  all  discrepancies  between  the as‐designed configuration documented in the configuration item data list and  the  as‐built  configuration  documented  by  nonconformance  reports or waivers. 

60 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 b.

The  ABCL  configuration  item  breakdown  section,  obtained  from  the equivalent  configuration  item  data  list  section,  shall  be  completed  by adding the following information: 

1.

serial number identification; 

2.

lot or batch number identification; 

3.

reference(s) of applicable nonconformance report(s) or request for waiver(s). 

### Special remarks

### D.2.2

None. 

61 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex E (normative)Software configuration file (SCF) - DRD- E.1  DRD identification

### E.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.3.2b and from ECSS‐E‐ST‐40 and ECSS‐Q‐ST‐80. 

### Purpose and objective

### E.1.2

The objective of the software configuration file is to provide the configuration status  of  the  software  configuration  item.  It  controls  its  evolution  during  the programme or project life cycle. 

The SCF is a constituent of the design definition file (as defined in ECSS‐E‐ST‐10). 

- E.2  Expected response

### E.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

Introduction 

The introduction shall describe the purpose and objective of the SCF.  Applicable and reference documents 

The SCF shall list the applicable and reference documents to support the generation of the document. 

Terms, definitions and abbreviated terms  

The  SCF  shall  include  any  additional  terms,  definition  or  abbreviated terms used. 

62 ![Im0](images/Im0)

![Im0](images/Im0)

Software configuration item overview  

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 The  SCF  shall  contain  a  brief  description  of  the  software  configuration item.  

For  the  software  configuration  item,  the  following  information  shall  be provided:  

1.

2.

3.

how to get information about the  software configuration item; composition of the software configuration item: code, documents; means to develop, modify, install, run the software configuration item; 

differences from the reference or previous version; 

status of software problem reports, software change requests, and software  waivers  and  deviations  related 

the  software configuration item. 

4.

5.

to 

<4>

a.

b.

<5>

a.

Inventory of materials  

The  SCF  shall  list  all  physical  media  and  associated  documentation <table align="center">
	<tr align="center">
	</tr>
</table>

b.

The  SCF  shall  define  the  instructions  necessary  to  get  information <table align="center">
</table>

<6>

a.

<7>

a.

b.

Baseline documents 

The  SCF  shall  identify  all  the  documents  applicable  to  the  delivered software configuration item version. 

Inventory of software configuration item 

The SCF shall describe the content of the software configuration item. The SCF shall list all files constituting the software configuration item:  1.

2.

3.

4.

5.

6.

source  codes with name, version, description; 

binary codes with name, version, description;  

associated data files necessary to run the software; 

media labelling references; 

checksum values; 

identification and protection method and tool description. 

<8>  Means necessary for the software configuration item 

a.

The SCF shall describe all items (i.e. hardware and software) that are not part  of  the  software  configuration  item,  and  which  are  necessary  to 63 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 develop,  modify,    generate  and  run  the  software  configuration  item, including: 

![Im0](images/Im0)

<table align="center">
	<tr align="center">
	</tr>
</table>

2.

3.

build files and software generation process; 

other software configuration items. 

<9>

a.

Installation instructions 

The  SCF  shall  describe  how  to  install  the  software  configuration  item version, its means and procedures necessary to install the product and to verify its installation.  

<10>  Change list  

a.

b.

This  SCF  shall  contain  the  list  of  all  changes  incorporated  into  the software configuration item version, with a cross reference to the affected software configuration item document, if any.  

Changes not incorporated yet but affecting the S/W CI shall also be listed and include.  

1.

2.

3.

4.

software problem reports; 

software change requests and proposals; 

contractual change notices; 

software waivers and deviations. 

<11>  Auxiliary information 

a.

The SCF shall include any auxiliary information to describe the software configuration. 

<12>

a.

Possible problems and  known errors 

The SCF shall identify any possible problems or known errors with the software configuration item version and any steps being taken to resolve the problems or errors. 

### Special remarks

### E.2.2

None. 

64 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex F (normative)Configuration status accounting reports -DRD- F.1  DRD identification

### F.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.3.1b. 

### Purpose and objective

### F.1.2

The purpose of configuration status accounting reports is to provide a reliable source  of  configuration  information  to  support  all  programme  or  project activities.  They  provide  the  knowledge  base  necessary  for  performing configuration management. 

- F.2  Expected response

### F.2.1

### Scope and content

<1>

a.

<2>

a.

<3>

a.

Introduction 

The  introduction  shall  describe  the  purpose  and  objective  of  the configuration status accounting reports. 

Applicable and reference documents 

The configuration status accounting reports shall list the applicable and reference documents in support to the generation of the document 

Description 

The configuration status accounting reports shall contain information on: 1.

Documents index and status list 

(a)

document identification; 

65 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 2.

3.

4.

5.

issue and revision; 

issue and revision date; 

title; 

remarks; 

identification of obsolete documents. 

deviation document number; 

issue and revision; 

issue and revision date; 

title; 

document or requirement affected; 

configuration item(s) affected; 

status of approval. 

(b)

(c)

(d)

(e)

(f)

Drawing index and status list 

(a)

drawing identification; 

(b)

issue and revision; 

(c)

issue and revision date; 

(d)

title; 

(e)

remarks; 

(f)  model applicability of the drawing. 

Request for deviation index and status list 

(a)

(b)

(c)

(d)

(e)

(f)

(g)

Request for waiver index and status list 

(a)  waiver document number; 

(b)

(c)

(d)

(e)

(f)  NCR originating the waiver; 

(g)

(h)

Change proposal (CP) index and status list 

(a)  CP document number; 

(b)

(c)

(d)

(e)

(f)

issue and revision; 

issue and revision date; 

title; 

document or requirement affected; 

serial number of configuration item(s) affected; 

status of approval. 

issue and revision; 

issue and revision date; 

title; 

change request originating the change; 

configuration item(s) affected; 

66 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 status of approval. 

6.

(g)

Review item discrepancies (RID) index and status list 

(a)

(b)

(c)

(d)

(e)

(f)

(g)

(h)  RID closure date; 

(i)

design review identification; 

RID identification; 

title of the discrepancy; 

affected document number and issue; 

affected paragraph; 

RID status; 

identification of action assigned; 

remarks. 

### Special remarks

### F.2.2

None. 

67 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex G (normative)Change request - DRD- G.1  DRD identification

### G.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.2.3a. 

### Purpose and objective

### G.1.2

The  objective  of  a  change  request  is  to  collect  the  information  that  formally defines  a  proposed  programme  or  project  change  versus  the  existing requirements. 

- G.2  Expected response

### Scope and content

### G.2.1

a.

The change request shall contain the information in Table G‐1. 

### Special remarks

### G.2.2

None. 

68 ![Im0](images/Im0)

![Im0](images/Im0)

 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <table align="center">
	<tr align="center">
		<td></td>
		<td></td>
		<td>Description </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the change request originating  organization </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Unique identification and register number </td>
	</tr>
	<tr align="center">
		<td>3 </td>
		<td>Issue </td>
		<td>Issue status of the change request </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Issue date of the change request </td>
	</tr>
	<tr align="center">
		<td>5 </td>
		<td>Project </td>
		<td>Project under which the change request is  supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Title of change request </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the CI(s) or PI(s) (number and  name) which are affected by the change request </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the document(s) to which the  change request applies (document number and  issue, paragraph or requirement id) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Reason why the proposed change has to made  (Rationale) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Change description, and when requirements are  affected, proposed new wording </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Names, date and signatures of the relevant  authorities </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Information on the authorization to proceed or  the limit of liability, if the change has to be  incorporated immediately </td>
	</tr>
</table>

 

69 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex H (normative)Change proposal - DRD- H.1  DRD identification

### H.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.2.3b. 

### Purpose and objective

### H.1.2

The objective of the change proposal is to be the vehicle for proposing a major change to an approved baselined data or the business agreement. 

- H.2  Expected response

### Scope and content

### H.2.1

a.

The change proposal shall contain the information in Table H‐1. 

### Special remarks

### H.2.2

None. 

70 ![Im0](images/Im0)

![Im0](images/Im0)

 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <table align="center">
	<tr align="center">
		<td>No. </td>
		<td>Data </td>
		<td>Description </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the change proposal originating  organization </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Unique identification and register number </td>
	</tr>
	<tr align="center">
		<td>3 </td>
		<td>Issue </td>
		<td>Issue status of the change proposal </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Issue date of the change proposal </td>
	</tr>
	<tr align="center">
		<td>5 </td>
		<td>Project </td>
		<td>Project under which the change proposal is  supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Change request reference on which the change  proposal is supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Title of change </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Recommended classification </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Recommended introduction point and  identification of the application range of the  change </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Description of the change </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the CI or PI (number and name)  affected by the change proposal </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the document(s) (e.g. number  and issue, paragraph or design data) affected by  the change </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Reason for Change; Describe the rational for the  change proposal approval </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Indication on related factors (e.g. interfaces,  safety) of the change:  performances, interfaces, interchangeability,  qualification, reliability, maintainability, safety,  electrical and mechanical parameters, material or  processes, parts, testing, ground segment, GSE  and tooling, user documentation, cost, schedule.  </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Estimated influences on business agreement  provisions </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Detailed cost identification and overall summary  price of the change </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Effects on schedule </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Regarding the intended use  </td>
	</tr>
	<tr align="center">
		<td>19 </td>
		<td>Initiator approval </td>
		<td>Names, date and signatures of the relevant  authorities </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Names, date and signatures of the relevant  authorities </td>
	</tr>
</table>

 

71 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex I (normative)Request for deviation - DRD- I.1  DRD identification

### I.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.2.6a. 

### Purpose and objective

### I.1.2

The objective of the request for deviation is to be the vehicle for requiring and agreeing  the  departure  from  a  customer’s  requirement  that  is  part  of  an approved configuration baseline.  

- I.2  Expected response

### Scope and content

### I.2.1

a.

The request for deviation shall contain the information in Table I‐1. 

### Special remarks

### I.2.2

None. 

72 ![Im0](images/Im0)

![Im0](images/Im0)

 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <table align="center">
	<tr align="center">
		<td>Id </td>
		<td>Data </td>
		<td>Description </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the request for deviation  originating organization </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Unique identification and register number </td>
	</tr>
	<tr align="center">
		<td>3 </td>
		<td>Issue </td>
		<td>Issue status of the request for deviation </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Issue date of the request for deviation </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Recommended classification (i.e. major or minor) </td>
	</tr>
	<tr align="center">
		<td>6 </td>
		<td>Project </td>
		<td>Project under which the nonconforming item is  supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Business agreement identification under which  the nonconforming item is supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Order number under which the nonconforming  item is supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Location of the request for deviation originator  </td>
	</tr>
	<tr align="center">
		<td>10 </td>
		<td>Item designation </td>
		<td>Identification of the nonconforming item per  name and number, according to its configuration  item data list </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the CI(s) (number and name)  affected by the deviation </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Effectivity of the deviation by model or serial  number  </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the document(s) to which the  item does not conform (document number and  issue, paragraph or requirement id) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Title or short description of the request for  deviation </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Description of the deviation from the relevant  requirement or design feature </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Reason why the proposed deviation can be  accepted (rationale) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Item characteristics affected by the deviation </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Decision, names, date and signatures of the  relevant authorities </td>
	</tr>
</table>

 

73 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex J (normative)Request for waiver - DRD- J.1  DRD identification

### J.1.1

### Requirement identification and source

### document

This DRD is called from ECSS‐M‐ST‐40, requirement 5.3.2.6b. 

### Purpose and objective:

### J.1.2

The  objective  of  the  request  for  waiver  is  to  be  the  vehicle  for  requiring  and agreeing  to  the  use  or  the  delivery  of  a  product  that  does  not  conform  to  its approved product configuration baseline.  

- J.2  Expected response

### Scope and content

### J.2.1

a.

The request for waiver shall contain the information in Table J‐1. 

### Special remarks

### J.2.2

None. 

74 ![Im0](images/Im0)

![Im0](images/Im0)

 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 <table align="center">
	<tr align="center">
		<td>Id </td>
		<td>Data </td>
		<td>Description </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the request for waiver originating  organization </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Unique identification and register number </td>
	</tr>
	<tr align="center">
		<td>3 </td>
		<td>Issue </td>
		<td>Issue status of the request for waiver </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Issue date of the request for waiver </td>
	</tr>
	<tr align="center">
		<td>5 </td>
		<td>Project </td>
		<td>Project under which the nonconforming item is  supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Business agreement identification under which the  nonconforming item is supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Order number under which the nonconforming item is  supplied </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Location of the request for waiver originator </td>
	</tr>
	<tr align="center">
		<td>9 </td>
		<td>Item designation </td>
		<td>Identification of the nonconforming item per name and  number, according to its configuration item data list </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the CI (number and name) affected by  the waiver </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Model or serial number (or batch / lot number) of the  nonconforming item(s) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the document(s) (number and issue,  paragraph or design data) to which the item does not  conform </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Title or short description of the request for waiver  (consistent with the title of the related nonconformance  report) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Description of the nonconformity, supported by  sketches and attachments as appropriate </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Reason why the proposed nonconformity can be  accepted (Rationale) </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification number of the nonconformance report  related to the request for waiver </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Identification of the minutes of meeting of the  nonconformance review board which decided to raise  the request for waiver </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Item characteristics affected by the nonconformity </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Regarding the intended use  </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Major or minor as per the classification criteria </td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td>Decision, name, date and signature of the relevant  authorities </td>
	</tr>
</table>

 

75 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex K (informative)Configuration item selection- K.1  General

The  selection  of  configuration  items  (CI)  is  a  management  decision  based  on experience  and  good  judgment.  Therefore,  this  annex  exposes  the  risk  in selecting too many or too few items, and provides a check‐list to be used to help the selection process. 

- K.2  Effects of selecting too many configuration items

Too many CIs can result in effects hampering visibility and management rather than improving it. These effects include: 

•

increased  administrative  burden  in  preparing,  processing,  and  status reporting of related documentation, which tends to be multiplied by the number of CIs; or 

increased  development  time  and  cost  as  well  as  possibly  creating  an inefficient design. 

•

Possible increase in management effort, difficulties in maintaining coordination and unnecessary generation of paper work or files. 

- K.3  Effects of selecting too few configuration items

in 

increasing  cost  and  difficulties 

Too few configuration items can result in decreasing management visibility and progress  assessment, 

logistics  and maintenance. 

When  the  lowest  level  designated  CI  is  a  complex  item  (e.g.  implementing unrelated functions, containing both hardware and software components), the following can result: 

•

•

•

•

the potential for reuse of the CI, or portions of the CI is diminished; 

re‐procurement of the CI and components is complicated; 

potential re‐procurement sources are limited; 

formal  testing  of  critical  capabilities  may  be  delayed  or  made  more difficult; 

the  inability  to  account  for  the  deployment  of  a  CI  whose  component parts are disbursed to different locations; 

•

76 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 •

•

•

•

•

in  managing  and  accounting  for  common difficulty in addressing the effectiveness of changes and retrofit actions, particularly when there are different quantities or separately deliverable components; 

increased  complexity 

assemblies and components; 

loss  of  identity  through  separation  of  affected  portions  of  a  CI  during operational or depot maintenance or modification installation activity; inability  to  control  individual,  but  identical,  remove  or  replace  items when CI identification and control is set at too high a level; 

loss of operational use of one function because of maintenance of another function within the same CI. 

- K.4  Configuration item selection check-list

The following list of questions is proposed to help the selection process of CIs.  If  most  of  the  questions  can  be  answered  with  YES,  then  the  item  is  a  good candidate  for  being  a  CI.  On  the  contrary,  if  most  of  the  questions  can  be answered with NO, then the item is not a good candidate. If the questions can be answered with approximately equal numbers of YES’s and NO’s, additional judgment is needed. 

a.

b.  Will  the  product  require  development  of  a  new  design  or  a  significant Is the product critical from a safety, schedule or financial point of view? c.

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

modification to an existing design? 

Does the product incorporate new or unproven technologies? 

Does the product have an interface with hardware or software developed under another contract? 

Is the item required for logistic support or activity? 

Do all components of the product have common mission, installation and deployment requirements, common testing and acceptance? 

Does the product have interdependent functions? 

Does the product have reconfiguration capability? 

Is it, or does it have the potential (schedule or location) to be designated for separate procurement? 

Can (or must) the item be independently tested? 

Is it readily identifiable with respect to size, shape and weight? 

With  respect  to  form,  fit  or  function,  does  it  interface  with  other  CIs whose configuration is controlled by other entities? 

Is  there  a  requirement  to  know  the  exact  configuration  and  status  of changes to it during its life cycle? 

Does  the  item  have  separate  mission,  training,  test,  maintenance  and support  functions,  or  require  separately  designated  versions  for  such purposes? 

77 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Annex L (informative)Technical data package description- L.1  Scope and content

This annex describes the approach, the relevant steps to create a TDP and the semantics of the metadata model. 

The TDP can be created by using stand alone tools which allow creation of TDP by  picking  up  files  from  hard  disk  (in  this  case,  metadata  are  retyped manually), or by IS integrated tools which allow creation of the TDP from files and metadata already stored in the IS. 

In both cases, a mapping between  terms in this standard (see column 1 of Table L‐1 to Table L‐5) and the company terminology needs to be performed. 

When  using  IS  integrated  tools,  a  second  mapping  between  terms  in  this standard  and  the  IS  internal  data  structure  (e.g.  columns  of  the  relational database of the IS) needs to be performed, and a connector (export or import) that is compliant with the requirements of clause 5.3.7.4 is implemented. 

- L.2  Steps to create an TDP

a.

b.

Create an XML document (called datapackage.xml) containing tags and values  about  documents  to  exchange,  in  the  order  defined  by  the ecss_m_st_40.xsd  XML  Schema.  (See  XML  Schema  on  ECSS  website http://www.ecss.nl). 

Include the document content files and the datapackage.xml file inside a zip file. 

- L.3  Detailed TDP ZIP file definition:

a.

The TDP ZIP file contains: 

⎯

⎯

The Content file(s) (in the root directory or in any folder of the zip file) 

Only one datapackage.xml file in the \META‐INF folder. 

as shown in the following Figure L‐1:  

78 ![Im0](images/Im0)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure L‐1 TDP ZIP file  

The datapackage.xml file is ʺXML validʺ i.e. it is structurally compliant with the grammar defined by the ecss_m_st_40c.xsd XML Schema. (See XML Schema on ECSS website http://www.ecss.nl).  

b.

![Im0](images/Im0)

![Im1](images/Im1)

<table align="center">
</table>

Each  content  file  is  named  as  follows:  REFERENCE_C{_I}{_[VOL]}.ext Where: 

⎯

⎯

⎯

⎯

REFERENCE  mandatory  (REFERENCE  being  the  identifying number of the document) 

_C mandatory (C being the change level) 

_I if relevant  (I being the issue level) 

_[VOL] mandatory if the ʺnumber of volumeʺ > 1 (VOL being the volume  number  in  the  case  of  several  files  attached  to  the  same reference/change_level/issue_level 

The file path of a content file within the ZIP archive relative to the meta‐inf/datapackage.xml 

the  “context_file_name” implementation field. 

is  stored 

file 

inside 

d.

e.

- L.4

In the following TDP‐ZIP archive file of Figure L‐2, the content file ʺDSI‐SP‐SC‐2006‐2524_01_00.docʺ is stored in the ʺ\GDOC_DOCʺ folder of the ʺDSI‐SP‐SC‐2006‐2524.doc.zipʺ file. 

79 ECSS‐M‐ST‐40C Rev. 1 6 March 2009 Figure L‐2: ZIP archive  

In the associated ʺdatapackage.xmlʺ file which is in the ʺ\meta‐infʺ folder, the ʺcontext_file_nameʺ field is filled as follow: 

…<entry_file context_file_name=ʺ..\GDOC_DOC\DSI‐SP‐SC‐2006‐

2524_01_00.docʺ native_format_file_name=ʺMy OriginalDocName.docʺ/> 

 

- L.5  Semantics of the metadata model

The metadata model is defined by an XML schema tree, see Figure L‐3.  

Figure L‐3: XML schema tree 

The top level branches shown are as follows: 

a.

data_package: root of the metadata model (See Table L‐1) 

1.

dde_definition_exchange: 

(a)

dde_properties:  metadata  related  to  the  whole  TDP  (See Table L‐2). 

80 ![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 (b)

(c)

item_properties: metadata to build virtual folders. Each item can have many elements (See Table L‐3). 

elements_properties:  metadata  to  describe  a  file  (See  Table L‐4). 

b.

database: persons and companies that are linked to elements (See Table L‐5). 

- L.6  Data Tables description

Table L‐1 to Table L‐5 describe the final blocks of the previous tree (defined by the ecss_m_st_40.xsd XML Schema). 

They  also  provide  the  semantics  of  each  term  with  the  corresponding  ISO definition if any. 

NOTE 

are  given 

of 

ease  human 

These 

tables 

understanding 

the  metadata  model. 

However, only the ecss_m_st_40.xsd XML Schema 

is applicable (see clause 5.3.7.4c). 

to 

The  column  ʺISO  10303  AP‐232  Definitionʺ  contains  the  ISO  definition.  If specific  comments  in  this  standard  alter  the  ISO  definition,  they  are  written inside a grey box. 

In  order  to  locate  precisely  the  blocks  in  the  XML  Schema  tree,  the  full  XML path  is  given  above  each  group  of  terms  using  XPATH  syntax  (See http://www.w3.org/TR/xpath). 

The mandatory terms are enclosed inside asterisks and written bold. 

Multiple terms relating to the same parent term are separated by dashed lines. Table L‐6 provides additional information necessary to the comparison of terms used in Table L‐1 to Table L‐5. 

81 ![Im0](images/Im0)

![Im0](images/Im0)

 

ECSS‐M‐ST‐40C Rev. 1 6 March 2009 