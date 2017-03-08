ECSS-S-ST-00C31 July 2008ECSS system

Description, implementation and

general requirements

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands ![Im1](images/Im1)

ECSS‐S‐ST‐00C 31 July 2008 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐S‐ST‐00  Working  Group,  reviewed  by  the  ECSS 

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

2008 © by the European Space Agency for the members of ECSS 

2 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 Change log![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>ECSS‐S‐00A  13 December 2005 </td>
		<td>First issue </td>
	</tr>
	<tr align="center">
		<td>ECSS‐S‐00B </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐S‐ST‐00C  31 July 2008 </td>
		<td>Second issue  This issue of ECSS‐S‐ST‐00C supersedes ECSS‐S‐00A and replaces  ECSS‐M‐00B, ECSS‐E‐00A and ECSS‐Q‐00A.  The main changes to the previous versions are summarized hereafter:  •  The descriptive text of the previous of ECSS‐S‐00 was reorganized  and complemented with text from ECSS‐M‐00B, ECSS‐E‐00A and  ECSS‐Q‐00A to introduce the content of the disciplines of the three  ECSS branches.  •  Requirements were added as follows:  •  Top‐level requirements from ECSS‐M‐00B were moved to  ECSS‐S‐ST‐00C while the remaining requirements were moved to  ECSS‐ST‐M‐10C.  •  Top‐level requirements from ECSS‐Q‐00A were moved to  ECSS‐S‐ST‐00C while the remaining requirements were moved to  ECSS‐Q‐ST‐10C.  •  New top‐level requirements missing in the ECSS Standards.  •  Example of template for an “ECSS applicable requirements matrix  (EARM)” for the requirements of ECSS‐S‐ST‐00 was added in  Annex A.  •  A form for ECSS Change Request/Document Improvement  Proposal for user feedback was added as Annex B. </td>
	</tr>
</table>

3 ECSS‐S‐ST‐00C 31 July 2008 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................6

- 2 Normative references.............................................................................................7

- 3 Terms, definitions and abbreviated terms............................................................8

- 3.1  Terms from other standards .......................................................................................8

- 3.2  Abbreviated terms ......................................................................................................8

- 4 ECSS system objectives and policy .....................................................................9

- 5 ECSS System description....................................................................................10

- 5.1  Overview ..................................................................................................................10

- 5.2  Types of ECSS documents ......................................................................................10

5.2.1

Standards ...................................................................................................105.2.2  Handbooks .................................................................................................115.2.3

Technical memoranda................................................................................11- 5.3  Structure and architecture of ECSS Standards System.............................................11

5.3.1  Overview.....................................................................................................115.3.2  Management (M-branch)............................................................................13Engineering (E-branch) ..............................................................................145.3.3

5.3.4

Product Assurance (Q-branch)...................................................................17- 6 Introduction into space programmes .................................................................20

- 6.1  The customer-supplier model...................................................................................20

- 6.2  Business agreements...............................................................................................20

- 6.3  Applicability of ECSS documents .............................................................................21

- 7 Application of ECSS Standards ..........................................................................23

- 7.1

Introduction...............................................................................................................23- 7.2  Preparatory activities................................................................................................23

Identification of project characteristics - Step 1 ..........................................23Analysis of project characteristics and identification of risks - Step 2 ........247.2.1

7.2.2

4 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 - 7.3  Tailoring activities.....................................................................................................25

Selection of applicable ECSS Standards - Step 3......................................257.3.1

Selection of requirements from applicable standards - Step 4 ...................257.3.2

7.3.3  Completion of requirements - Step 5..........................................................267.3.4  Harmonization of requirements - Step 6.....................................................267.3.5  Documenting of requirements applicability - Step 7 ...................................26- 8 User feedback .......................................................................................................28

- 9 Requirements........................................................................................................29

- 9.1  Applicability ..............................................................................................................29

- 9.2  Requirements on customers ....................................................................................29

- 9.3  Requirements on suppliers.......................................................................................30

- Annex A (informative) Example of template for an EARM for the

- requirements of ECSS-S-ST-00C .......................................................................31

- Annex B (informative) ECSS Change Request / Document Improvement

- Proposal...............................................................................................................33

- Bibliography.............................................................................................................34

- Figures

- Figure 5-1: ECSS User Standards structured as Branches ...................................................12

- Figure 5-2: Disciplines of the ECSS Standards system .........................................................12

- Figure 6-1:  Customer–supplier network concept...................................................................22

- Figure 7-1: 7–step tailoring process .......................................................................................27

- Tables

- Table 5-1: Disciplines in the management branch .................................................................13

- Table 5-2: Disciplines in the engineering branch ...................................................................15

- Table 5-3: Disciplines in the product assurance branch.........................................................17

 

5 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 ScopeThis  document  is  the  ECSS  top–level  document  for  ECSS  users.  It  gives  a general  introduction  into  ECSS  and  the  use  of  ECSS  Documents  in  space programmes and projects.  

Its purpose is to provide users with an overview of the ECSS System, together with an introduction to the three branches of applicability and to the disciplines covered by the set of ECSS Standards and the processes involved in generating and using these standards. 

As  an  introduction  into  space  programmes,  space  projects  actors  and  their customer‐supplier relationships are described.  

The three branches (Management, Product Assurance and Engineering) of ECSS system  and  their  disciplines  are  then  presented  as  well  as  link  amongst  the branches. 

Application  of  the  ECSS  System  for  space  projects  in  the  customer‐supplier chain is explained and a practical tailoring method is described together with methods for collecting and processing user feedback. 

Finally  top‐level  requirements  are  defined  for  implementation  of  the  ECSS system in space projects/programmes. 

This standard is applicable to all the procurements of space products. 

With effect from the date of approval, this Standard announces the adoption of the external document on a restricted basis for use in the European Cooperation for Space Standardization (ECSS) system. 

This standard may be tailored for the specific characteristic and constraints of a space project in conformance with clause 7 of this standard. 

 

 

6 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revisions of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the most recent editions of the  normative  documents  indicated  below.  For  undated  references  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

 

ECSS system – Glossary of terms 

7 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For 

the  purpose  of 

ECSS‐S‐ST‐00‐01 apply. 

this  Standard, 

the 

terms  and  definitions 

from - 3.2  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01 and the following apply: 

Abbreviation  Meaning 

DRD 

EARM 

ECM 

HB 

ID 

PA 

PRD 

SDO 

TM 

document requirements definition 

ECSS applicable requirements matrix 

ECSS compliance matrix 

handbook 

implementation document 

product assurance 

project requirements document 

standard development organization 

technical memorandum 

 

8 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 ECSS system objectives and policyThe overall objectives of using the ECSS system of standards include: 

•

•

•

•

achieving more cost effective space programmes and projects in Europe, improving the competitiveness of European space industry, 

improving the quality and safety of space projects and products,  

facilitating  clear  and  unambiguous  communication  between  all  parties involved, in a form suitable for reference or quotation in legally binding documents, 

reducing risk and guarantee interoperability and interface compatibility by applying proved and recognized requirements and methods. 

•

In  order  to  meet  the  above  stated  objectives,  the  ECSS  policy  has  been developed: see ECSS‐P‐00. 

ECSS documents are produced to support the formal customer‐supplier relation in developing space programs and projects. 

In order to ensure European space programmes and projects’ efficiency in terms of technical performance, life cycle cost‐effectiveness and on‐time deliveries, the ECSS  System  can  be  adapted  to  specific  domains  of  application  by  use  of tailoring activities. 

NOTE 

See  attachment  “Example  of  ECSS  Applicable 

Requirements Matrix (EARM)”. 

Systematic  feedback  of  experience  from  programmes,  projects  and  other appropriate  sources  into  the  ECSS  System  allows  improvement  of  ECSS Standards. 

9 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 ECSS System description- 5.1  Overview

The  ECSS  System  has  been  developed  as  a  cooperative  effort  between  the European  space  agencies  and  space  industries.  It  comprises  a  comprehensive set of documents addressing all essential aspects of the three major branches for the successful implementation of space programmes and projects, namely 

•

•

•

ECSS user oriented documents other than the present one and ECSS‐ST‐00‐01 fall in one of those branches.  

ECSS includes  three  types  of  documents:  standards, handbooks and  technical memoranda. 

Project management, 

Engineering, and 

Product assurance. 

- 5.2  Types of ECSS documents

Standards

5.2.1

Standards  are  documents  for  direct  use  in  invitation  to  tender  and  business agreements for implementing space related activities.  

They state verifiable requirements, supported by the minimum descriptive text necessary to understand their context.  

Each  requirement  contained  within  a  Standard  has  a  unique  identification, allowing full traceability and easy verification of compliance. 

Standards are named as ECSS‐<X>‐ST‐<Number> <Version>, where: 

<X>  represents  the  branch  and  can  take  the  following  values:  P  or  S  (ECSS system), M (management), E (engineering) or Q (product assurance). 

<Number> is one or two groups of two digits. 

<Version> is a letter from “A” onwards. 

When a requirement asks for the delivery of a document, the scope and content is  specified  in  a  dedicated  DRD  (Document  Requirements  Definition),  which forms an integral part of a standard.  

10 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 The ECSS Standards focus primarily on what is required to comply with each standard, rather than how to achieve this. This approach provides the flexibility for different customers and suppliers to use established “in–house” procedures, or processes, to comply with these standards.  

Handbooks

5.2.2

Handbooks are non‐normative documents providing background information, orientation, advice or recommendations related to one specific discipline or to a specific technique, technology, process or activity.  

ECSS handbooks provide guidelines and good practices, and collection of data. They are named as ECSS‐<X>‐HB‐<Number> <Version>, where <X>, <Number> and <Version> have the same meaning than for standards. 

Handbooks do not contain requirements, but provide additional information on selected  topics  addressed  by  the  ECSS  standards.  Handbooks  can  be  used  as reference document or transformed into normative documents by the customer. Technical memoranda

5.2.3

Technical  memoranda  are  non‐normative  documents  providing  useful information to the space community on a specific subject.  

They are prepared to record and present data which are not the subjects for a standard or for a handbook or not yet mature to be published as standard or handbook. 

They are named as ECSS‐<X>‐TM‐<Number> <Version>, where <X>, <Number> and <Version> have the same meaning than for standards. 

Technical  memoranda  do  not  contain  requirements,  but  provide  additional information  on  selected  topics  addressed  by  the  ECSS  standards.  Technical memoranda  can  be  used  as  reference  document  and  are  not  intended  to  be transformed into normative documents. 

- 5.3  Structure and architecture of ECSS Standards System

5.3.1  Overview

The  present  document  is  the  top  level  user  document  of  ECSS.  Beneath  this document there are three parallel branches, one each for project management, engineering,  and  product  assurance  (see  Figure  5‐1).  Project  management branch  documents  have  an  “M”  prefix,  engineering  standards  have  an  “E” prefix, and product assurance standards have a “Q” prefix. 

Some  documents  adopted  by  ECSS  are  originated  from  other  Standard Development Organizations (SDO) (see ECSS‐P‐00 and Figure 5‐1). 

Within each branch, disciplines and corresponding requirements are covered by dedicated  standards.  ECSS  Disciplines  can  also  be  supported  by  Handbooks (HB) and Technical Memoranda (TM) as necessary. 

The disciplines addressed by the ECSS Standards system are given in Figure 5‐2. 11 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 ## ECSS-S-ST-00

## ECSS System – Description,

## implementation and requirements

## ECSS-M Standards

## ECSS-E Standards

## ECSS-Q Standards

External Standards

“adopted” by ECSS

Figure 5‐1: ECSS User Standards structured as Branches 

- ECSS-S-ST-00 – ECSS System – Description, implementation and

general requirements

Space project management disciplines

M-10 - Project planning and implementation

M-40 - Configuration and information management

M-60 - Cost and schedule management

M-70 - Integrated logistic support

M-80 - Risk management

Space engineering disciplines

E-10 - System engineering

E-20 - Electrical and optical engineering

E-30 - Mechanical engineering

E-40 - Software engineering

E-50 - Communications

E-60 - Control engineering

E-70 - Ground systems and operations

Space product assurance discipline

Q-10 - Product assurance management

Q-20 - Quality assurance

Q-30 - Dependability

Q-40 - Safety

Q-60 - Electrical, electronic, electromechanical (EEE) components

Q-70 - Materials, mechanical parts and processes

Q-80 - Software product assurance

Figure 5‐2: Disciplines of the ECSS Standards system  

12 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 5.3.2  Management (M-branch)

The  overall  objective  of  project  management  is  to  implement  a  process  to achieve  successful  completion  of  the  project  in  terms  of  cost,  schedule  and technical  performance.  Project  management 

following  a structured approach throughout all stages of its life cycle and at all levels of the customer‐supplier chain. 

It  integrates  all  management,  engineering  and  product  assurance  functions required to execute the project. 

Table 5‐1 presents an overview of the disciplines covered by ECSS management branch. It is not intended to be exhaustive. 

is  performed 

![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>M‐10 </td>
		<td>Project Planning and  Implementation </td>
	</tr>
	<tr align="center">
		<td>M‐40 </td>
		<td>Configuration and  Information  Management </td>
	</tr>
</table>

13 ECSS‐S‐ST‐00C 31 July 2008 ![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>M‐60 </td>
		<td>Cost and Schedule  Management </td>
	</tr>
	<tr align="center">
		<td>M‐70 </td>
		<td>Integrated Logistic  Support </td>
	</tr>
	<tr align="center">
		<td>M‐80 </td>
		<td>Risk Management </td>
	</tr>
</table>

Engineering (E-branch)

5.3.3

ECSS‐E  disciplines  cover  the  engineering  aspects  of  space  systems  and products, including: 

•

the engineering process as applied to space systems and their elements or functions, and 

technical  aspects  of  products  used  to  accomplish,  or  associated  with, space missions. 

•

14 ECSS‐S‐ST‐00C 31 July 2008 Table 5‐2 presents an overview of the disciplines covered by ECSS engineering branch. It is not intended to be exhaustive. 

![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>E‐10 </td>
		<td></td>
	</tr>
	<tr align="center">
		<td>E‐20 </td>
		<td>Electrical and  Optical Engineering </td>
	</tr>
	<tr align="center">
		<td>E‐30 </td>
		<td>Mechanical  Engineering </td>
	</tr>
</table>

15 ECSS‐S‐ST‐00C 31 July 2008 ![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>E‐40 </td>
		<td>Software  Engineering </td>
	</tr>
	<tr align="center">
		<td>E‐50 </td>
		<td>Communications </td>
	</tr>
	<tr align="center">
		<td>E‐60 </td>
		<td></td>
	</tr>
	<tr align="center">
		<td>E‐70 </td>
		<td>Ground Systems  and Operations </td>
	</tr>
</table>

16  

ECSS‐S‐ST‐00C 31 July 2008 Product Assurance (Q-branch)

5.3.4

The prime objective of Product Assurance is to assure that the Space Products accomplish their defined mission objectives and more specifically that they are Safe,  Available  and  Reliable.  In  support  of  project  Risk  Management,  PA assures  an  adequate  identification,  appraisal,  prevention  and  control  of technical risks within project constraints. 

Table  5‐3  presents  an  overview  of  the  disciplines  covered  by  ECSS  product assurance branch. It is not intended to be exhaustive. 

![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>Q‐10 </td>
		<td>Product Assurance  Management </td>
	</tr>
	<tr align="center">
		<td>Q‐20 </td>
		<td>Quality Assurance </td>
	</tr>
</table>

17 ECSS‐S‐ST‐00C 31 July 2008 ![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>Q‐30 </td>
		<td>Dependability </td>
	</tr>
	<tr align="center">
		<td>Q‐40 </td>
		<td>Safety </td>
	</tr>
	<tr align="center">
		<td>Q‐60 </td>
		<td>Electrical, Electronic,  Electromechanical  (EEE) Components </td>
	</tr>
</table>

18 ECSS‐S‐ST‐00C 31 July 2008 ![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Discipline </td>
		<td>Title </td>
	</tr>
	<tr align="center">
		<td>Q‐70 </td>
		<td>Materials, Mechanical  Parts and Processes </td>
	</tr>
	<tr align="center">
		<td>Q‐80 </td>
		<td>Software Product  Assurance </td>
	</tr>
</table>

19 ECSS‐S‐ST‐00C 31 July 2008 Introduction into space programmes- 6.1  The customer-supplier model

The  production  of  space  systems  calls  for  the  cooperation  of  several organizations  that  share  the  common  objective  of  providing  a  product  that satisfies  the  customer’s  needs  (performance  within  cost  and  schedule constraints). 

All space project actors are either a customer or a supplier, or both. 

In its simplest form, a project can comprise one customer with just one supplier; however, most space projects comprise a number of hierarchical levels, where:  •

•

the actor at the top level of the hierarchy is the top level customer, 

the  actors  at  intermediate  levels  of  the  hierarchy  are  both  supplier  and customer, 

the actors at the lowest level of the hierarchy are suppliers only.  

•

- 6.2  Business agreements

Within  the  project,  exchanges  of  products  and  services  are  governed  by business  agreements,  used  as  a  generic  term  throughout  the  ECSS  Standards when referring to a legally binding agreement between two or more actors in the  customer–supplier  chain.  These  agreements  include  the  terms  and conditions  agreed  between  the  parties,  the  rules  by  which  business  is conducted, the actors’ commitments and obligations for the provision of goods and  services,  the  methods  of  acceptance  and  compensation,  monetary,  or otherwise. Business agreements serve as a framework prescribing the activities throughout the execution of work, and as a reference to verify compliance. 

Business agreements are recorded in a variety of forms, such as 

•

•

•

•

•

•

•

Contracts, 

Memoranda of understanding, 

Inter–governmental agreements, 

Inter–agency agreements, 

Partnerships, 

Bartering agreements, and 

Purchase orders. 

20 ![Im2](images/Im2)

![Im2](images/Im2)

- 6.3  Applicability of ECSS documents

ECSS‐S‐ST‐00C 31 July 2008 The ECSS documents themselves do not have legal standing and they do not constitute business agreements: they are made applicable by invoking them in business  agreements,  most  commonly  in  contracts.  The  applicability  of standards and requirements is specified in the project requirements documents (PRDs),  which  are  included  in  business  agreements,  which  are  agreed  by  the parties and binding them. 

NOTE   Description of PRD is provided in ECSS‐M‐ST‐10, 

Clause 4.1.10.  

The  top–level  customer’s  PRD  forms  the  basis  for  the  generation  of  all  lower level customer PRDs. An integral part of a PRD, at any level, is the set of ECSS Standards  tailored  as  necessary  and  documented  in  an  “ECSS  Applicability Requirements Matrixʺ (EARM), as described in clause 7.3.5. 

A supplier, at any level, is responsible for demonstrating compliance with the project  requirements  contained  in  his  customer’s  PRD,  through,  for  example, the  elaboration  of  a  compliance  matrix,  and  ultimately  for  supplying  a conforming  product.  The  compliance  to  the  PRD 

in  an Implementation Documents (IDs), for example project plans (e.g. management, engineering and product assurance) and compliance matrix.  

is  presented 

NOTE   Description  of 

Implementation  Document 

is 

provided in ECSS‐M‐ST‐10.  

The hierarchical structure in Figure 6‐1 constitutes the customer–supplier chain within a project with its contractual chain of documents.  

21 ![Im2](images/Im2)

Other contract(s) at

prime level

ECSS‐S‐ST‐00C 31 July 2008 Top-level customer

PRD 0

ID 0

Supplier

Customer

Prime contractoror equivalentComplete

- customer-supplier

chain

Elemental

customer-supplier

chain

PRD 1

ID 1

PRD i

ID i

PRD n

ID n

Supplier

Customer

Organization

PRD i.1

ID i.1

PRD i.n

ID i.n

PRD i.i

ID i.i

Supplier

Customer

Organization

Lowest Elemental

customer-supplier

chain

PRD m.1

ID m.1

PRD m.n

ID m.n

PRD m.i

ID m.i

Supplier

Lowest level

supplier

Figure 6‐1:  Customer–supplier network concept 

22 ECSS‐S‐ST‐00C 31 July 2008 Application of ECSS Standards- 7.1

Introduction

The project’s requirements within the PRD are composed by two sets: 

•

•

requirements covered by ECSS disciplines, subject to tailoring, and 

other requirements specific to the project (not considered in this Clause, e.g. mission specific requirements) 

The ECSS Standards and requirements to be made applicable at each level of the customer–supplier chain are influenced by the type and phase of the project involved, and by the type of business agreement to be used for managing the project. 

The ECSS System provides a comprehensive set of coherent standards covering the requirements for the procurement of a generic space product. This system can be adapted to a wide range of project types. The process of adapting the requirements to the project specificities is called tailoring.  

It  is  important  to  complete  the  preparatory  activities  (see  clause  7.2)  before addressing  the  range,  degree  and  phasing  of  applicability  of  the  total  set  of ECSS Standards to a particular project. 

Figure 7‐1 and the clauses 7.2 and 7.3 describe a recommended 7‐step process for the preparation and application of tailoring to establish the applicability of ECSS  Standards  and  their  requirements  to  a  project  and  to  apply  tailoring  as necessary. 

- 7.2  Preparatory activities

7.2.1

Identification of project characteristics -

Step 1

Overall project characteristics are derived taking into account experience gained and lessons learned from comparable projects, and are used for establishing the project  context,  scope,  scale,  orientation  and  other  elements  key  to  the successful  achievement  of  the  project  objectives.  They  are  specified  in  both programmatic and technical terms. Programmatic characteristics cover overall risk  policy,  including  risk  sharing,  as  well  as  political,  financial,  schedule, economic  and  contractual  aspects.  Technical  characteristics  cover  mission 23 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 objectives  (including  life  cycle  and  environment),  technical  complexity, technology, engineering, quality, scientific and product–oriented aspects. 

7.2.2

Analysis of project characteristics and

identification of risks - Step 2

After identifying its characteristics, the project is analysed to identify significant cost,  schedule,  technical  drivers,  as  well  as  critical  issues  and  specific constraints. These are used to identify and evaluate inherent and induced risks. Main  strategic,  organisational,  economical  or 

technical  characteristics considered for a project are as follows: 

•

•

Objective of the mission (e.g. scientific, commercial, institutional); 

Product type (e.g. space segment, space transportation segment, ground segment and operations, equipment, instrument); 

Mission  characteristics  (e.g.  type  of  orbit,  expected  life  duration, availability); 

Constraints  with  the  environment  (e.g.  external  interfaces,  external regulations, procurement constraints) the project belongs to; 

Expected cost to completion;  

Schedule drivers; 

Level  of  commitment  (e.g.  partnership,  supplier)  or  type  of  business agreement (e.g. fixed price, cost‐reimbursement); 

Maturity of design or technology (e.g. recurrent development, readiness level); 

Technical product complexity; 

Organisational or contractual complexity;  

Supplier maturity. 

•

•

•

•

•

•

•

•

•

NOTE 

This  list  is  not  exhaustive  and  can  be  completed 

according to project needs. Some elements of this 

list are imposed to the project, whereas the others 

are subject to choice within the project itself. 

The  resulting  project  risk  factors  are  documented  and  the  causes  and consequences of the identified risks are determined. This is the first step in the risk  management  process,  which  is  continued  to  monitor  and  manage  risk mitigation actions throughout the life of the project. 

24 ![Im2](images/Im2)

![Im2](images/Im2)

- 7.3  Tailoring activities

ECSS‐S‐ST‐00C 31 July 2008 7.3.1

Selection of applicable ECSS Standards -Step 3

Using  the  results  of  the  preparatory  activities  as  the  primary  input,  the complete set of ECSS Standards is evaluated for relevance to the overall project needs.  Those  standards  found  to  be  relevant  are  identified  as  applicable standards for the implementation of the project. In making this determination, it is important to recognise that at this level, due to the integrated structure of the ECSS System, identifying a standard as directly applicable also makes other standards called by it explicitly applicable. 

The subset of applicable standards selected through the above process can vary, depending  mainly  on  the  type,  size  and  complexity  of  the  project  being addressed.  The  project  phase,  or  phases,  for  which  the  applicability  of  ECSS Standards and their requirements is being selected, is another important factor to be considered. The early phases in a project lifecycle most often do not need a high  percentage  of  the  requirements  available  in  ECSS  Standards  to  be  made applicable to achieve their objective. However, in order to establish an overall view  of  the  phasing  in  of  requirements,  it  is  good  practice  that  this  initial selection of applicable standards covers all project phases up to and including the  development  phase,  which  is  typically  the  most  demanding  phase  of  a project. With this initial selection established, appropriate and coherent subsets of  the  standards  to  be  made  applicable  during  the  course  of  project implementation can then be selected to match the specific needs of the earlier project phases. 

7.3.2

Selection of requirements from applicablestandards - Step 4

Having established the list of applicable ECSS Standards for a project, the extent to  which  the  requirements  contained  within  these  standards  are  made applicable  is assessed  against  cost,  schedule,  and  technical  drivers,  as  well as against the identified risks and their mitigation strategies. 

Each requirement within the applicable standards is assessed and classified as: (Y) Applicable without change, 

(M) Applicable with modification, or 

(N) Not applicable (deleted). 

a.  Where all requirements in a standard are classified as applicable without change, the whole standard is fully applicable. 

b.  Where  an  applicable  standard  contains  requirements  of  different classifications, these are recorded as follows: 

1.

for each requirement classified as (Y), the applicability is recorded as such; 

25 ECSS‐S‐ST‐00C 31 July 2008 2.

3.

for  each  requirement  classified  as  (M),  the  modification  can  be  a change  to,  or  deletion  of,  part  of  the  existing  text,  or  new  text added to the existing text to enhance or clarify the requirement. In all cases, the complete modified text is recorded and justified; 

for  each  requirement  classified  as  (N),  the  non–applicability  is recorded and justified. 

c.  Where any requirement in an applicable standard is classified as (M), or (N), the standard is partially applicable. 

Completion of requirements - Step 5

7.3.3

When a lack, which is not project specific, is identified in the requirements of an ECSS standard, a new requirement is generated or adopted preferably from a standard of an SDO. Such requirements are classified as: 

(A) Additional requirement.

For each requirement classified as (A), the complete new text is recorded and justified. 

Harmonization of requirements - Step 6

7.3.4

Having completed the selection of applicable ECSS Standards and requirements and  the  addition  of  any  new  requirements  in  accordance  with  the  above process, the coherence and consistency of the overall set of requirements to be applied to the project is reviewed to eliminate the risk of conflict, duplication, or lack of necessary requirements. 

7.3.5

Documenting of requirements applicability -Step 7

The method of recording the applicability of ECSS Standards and requirements for a project in an efficient and structured manner is to consolidate it into an “ECSS  Applicability  Requirements  Matrix”  (EARM)  or  equivalent  document, which will be part of the PDR. Annex A provides an example of a template of the EARM for the requirements of this Standard. 

26 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 project's strategic aspects

project's technical aspects

Identify project characteristics

Project characteristics

Analyse project characteristics,

and identify risks

cost, risk and technical drivers

- ECSS M-, Q- and E- standards

Select applicable standards

- Additional international standards

New requirements

Set of applicable ECSS standards

Select requirements from the applicable

standards

Set of requirements

Complete requirements

Completed set of requirements

Harmonize requirements

Harmonized set of requirements

Document requirements applicability

 

Figure 7‐1: 7–step tailoring process 

27 ![Im2](images/Im2)

![Im3](images/Im3)

![Im4](images/Im4)

![Im6](images/Im6)

![Im5](images/Im5)

![Im3](images/Im3)

![Im4](images/Im4)

![Im6](images/Im6)

![Im7](images/Im7)

![Im3](images/Im3)

![Im4](images/Im4)

![Im6](images/Im6)

![Im8](images/Im8)

![Im9](images/Im9)

![Im4](images/Im4)

![Im6](images/Im6)

![Im11](images/Im11)

![Im9](images/Im9)

![Im4](images/Im4)

![Im6](images/Im6)

![Im10](images/Im10)

![Im9](images/Im9)

![Im4](images/Im4)

![Im6](images/Im6)

![Im12](images/Im12)

![Im14](images/Im14)

![Im15](images/Im15)

![Im16](images/Im16)

![Im17](images/Im17)

![Im18](images/Im18)

![Im19](images/Im19)

![Im9](images/Im9)

![Im4](images/Im4)

![Im20](images/Im20)

![Im22](images/Im22)

![Im22](images/Im22)

![Im6](images/Im6)

![Im25](images/Im25)

![Im24](images/Im24)

![Im13](images/Im13)

![Im21](images/Im21)

![Im23](images/Im23)

ECSS‐S‐ST‐00C 31 July 2008 User feedbackThe  ECSS  users  apply  ECSS  documents  to  projects,  including  any  adaptation through  tailoring  necessary  to  meet  specific  projects’  needs.  They  are  also expected  to  provide  feedback  to  the  ECSS  developers.  This  feedback  is  the primary source for maintaining and enhancing the ECSS System. 

In  addition  to  user  feedback  provided  during  the  development  of  ECSS documents, following feedback is expected: 

•

The  set  of  requirements  tailored  from  ECSS  documents  to  the  project specificities  and  made  applicable  as  part  of  the  business  agreement(s). For  example,  this  can  be  documented  into  an  ECSS  Applicable Requirements Matrix (EARM). 

Status of compliance with respect to the above set of ECSS requirements. This  can  be  documented  into  an  ECSS  Compliance  Matrix  (ECM).  This matrix provides, during the development phase, the actual indication of compliance. 

Change proposals to ECSS documents or to the ECSS System as a whole, provided in the form of an ECSS Change Request at any time; see form and process in Annex B. 

•

•

This  information  represents  important  customer  feedback  because  they provide  information  on  how  ECSS  documents  were  applied  and  on  how requirements evolved during project life cycle. 

Any user feedback should in the end be made available to the ECSS Secretariat, via his/her representative in ECSS organisation (e.g. uploading information in the  ECSS  website  (www.ecss.nl)),  for  recording  and  passing  it  to  the appropriate ECSS bodies for assessment and further processing. 

28 ![Im2](images/Im2)

ECSS‐S‐ST‐00C 31 July 2008 Requirements- 9.1  Applicability

This clause addresses the requirements to make applicable the ECSS standards for  the  development  of  space  products.  The  following  requirements  apply  to any element of customer‐supplier chain, from top to lowest level, as illustrated in Figure 6‐1. 

- 9.2  Requirements on customers

a.

b.

c.

d.

The customer shall select which ECSS Standards to make applicable and to  use  to  establish  the  project/product  requirements,  including  use  of ECSS‐S‐ST‐00‐01 for terms and definitions. 

The  customer  shall  define,  as  part  of  the  project  requirements documentation  (PRD),  the  set  of  requirements  tailored  from  ECSS documents to the project specificities which are made applicable. 

The  customer  shall  produce,  as  part  of  the  PRD,  a  documentation identifying the ECSS requirements applicable to the project. 

NOTE   An  “ECSS  applicable 

requirements  matrix” 

is  a  recommended  method  for  this 

(EARM) 

component of the PRD. 

The documentation identifying the requirements applicable to the project shall include following data (e.g. EARM): 

1.

The  complete  list  of  ECSS  standards  either  fully  or  partially applicable to the project/product, including any standard (ECSS or not) made applicable via the chain of normative references; 

For  each  partially  applicable  standard,  the  status  of  each requirement: 

o

o

o

The complete list of additional requirements 

For  modified  and  additional  requirements, 

formulation  

applicable without modification 

applicable with modification 

not applicable 

their  complete 2.

3.

4.

29 ![Im2](images/Im2)

![Im2](images/Im2)

- 9.3  Requirements on suppliers

a.

The supplier shall demonstrate compliance with the PRD requirements. ECSS‐S‐ST‐00C 31 July 2008 NOTE   An  “ECSS  compliance  matrix” 

to 

(ECM) 

document 

is  a 

recommended  method 

the 

demonstration of this compliance. The ECM is part 

of  the  project  compliance  matrix,  addressing 

compliance  to  the  applicable  ECSS  requirements 

(e.g. EARM). 

b.

The  documentation  identifying  the  compliance  to  ECSS  requirements applicable to the project (e.g. the ECM) shall include following data: 

1.

The  complete  list  of  ECSS  requirements  applicable  to  the  project (e.g. in the EARM). 

For  each  requirement,  the  actual  indication  of  compliance.  When deviation is identified the justification is provided. 

2.

30 ECSS‐S‐ST‐00C 31 July 2008 Annex A(informative)Example of template for an EARM for the requirements ofECSS-S-ST-00C![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Identifier </td>
		<td>Requirement </td>
		<td>Applicable  (A/M/D/N) </td>
		<td>Modified  requirement </td>
	</tr>
	<tr align="center">
		<td>9.2a. </td>
		<td>The customer shall select which ECSS Standards to make applicable and to use to establish the project/product  requirements, including use of ECSS‐S‐ST‐00‐01 for terms and definitions. </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>9.2b. </td>
		<td>The customer shall define, as part of the project requirements documentation (PRD), the set of requirements  tailored from ECSS documents to the project specificities which are made applicable. </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>9.2c. </td>
		<td>The customer shall produce, as part of the PRD, a documentation identifying the ECSS requirements  applicable to the project. </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>9.2d. </td>
		<td>The documentation identifying the requirements applicable to the project (e.g. the EARM) shall include  following data:  1.  including any standard (ECSS or not) made applicable via the chain of normative references;  2.  The complete list of ECSS standards either fully or partially applicable to the project/product,  For each partially applicable ECSS standard, the status of each requirement:  applicable without change (A)   applicable with modification (M)  • • •  not applicable (D) </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

31 ECSS‐S‐ST‐00C 31 July 2008 ![Im2](images/Im2)

<table align="center">
	<tr align="center">
		<td>Identifier </td>
		<td>Requirement </td>
		<td>Applicable  (A/M/D/N) </td>
		<td>Modified  requirement </td>
	</tr>
	<tr align="center">
		<td></td>
		<td>The complete list of new generated requirements (N) including identification of origin if existing  For modified (M) and new generated (N) requirements, its complete formulation  3.  4. </td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<td>9.3a. </td>
		<td>The supplier shall demonstrate compliance with the PRD requirements. </td>
		<td> </td>
		<td> </td>
	</tr>
	<tr align="center">
		<td>9.3b. </td>
		<td>The documentation identifying the compliance to ECSS requirements applicable to the project (e.g. the ECM)  shall include following data:  1.  2.  justification is provided.  The complete list of ECSS requirements applicable to the project (e.g. in the EARM).  For each requirement, the actual indication of compliance. When deviation is identified the </td>
		<td> </td>
		<td> </td>
	</tr>
</table>

32 ECSS‐S‐ST‐00C 31 July 2008 Annex B (informative)ECSS Change Request / DocumentImprovement Proposal- A Change Request / Document Improvement Proposal for an ECSS Standard may be submitted to the 

- ECSS  Secretariat  at  any  time  after  the  standard’s  publication  using  the  form  presented  below.  This 

- form  can  be  downloaded  in  MS  Word  format  from  the  ECSS  Website  (www.ecss.nl,  in  the  menus: 

- Standards ‐ ECSS forms). 

- Filling instructions: 

1.

2.

3.

4.

5.

6.

7.

8.

Originator’s name ‐ Insert the originator’s name and address 

ECSS document number ‐ Insert the complete ECSS reference number 

Date ‐ Insert current date 

Number ‐ Insert originator’s numbering of CR/DIP (optional) 

Location ‐ Insert clause, table or figure number and page number where deficiency has been identified 

Changes ‐ Identify any improvement proposed, giving as much detail as possible Justification ‐ Describe the purpose, reasons and benefits of the proposed change Disposition 

- Once completed, please send the CR/DIP by e‐mail to: ecss‐secretariat@esa.int 

33 ![Im2](images/Im2)

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

ECSS‐S‐ST‐00C 31 July 2008 BibliographyECSS‐P‐00 

ECSS‐M‐ST‐10 

ECSS‐M‐ST‐40 

ECSS‐M‐ST‐60 

ECSS‐M‐ST‐70 

ECSS‐M‐ST‐80 

ECSS‐E‐ST‐10 

ECSS‐E‐ST‐20 

ECSS‐E‐ST‐31 

ECSS‐E‐ST‐32 

ECSS‐E‐ST‐34 

ECSS‐E‐ST‐35 

ECSS‐E‐ST‐40 

ECSS‐E‐ST‐50 

ECSS‐E‐ST‐60 

ECSS‐E‐ST‐70 

ECSS‐Q‐ST‐10 

ECSS‐Q‐ST‐20 

ECSS‐Q‐ST‐30 

ECSS‐Q‐ST‐40 

ECSS‐Q‐ST‐60 

ECSS‐Q‐ST‐70 

ECSS‐Q‐ST‐80 

 

-  

ECSS – Standardization policy 

Space project management ‐ Project planning and implementation Space project management – Configuration and information 

management 

Space project management ‐ Cost and schedule management 

Space project management ‐ Integrated logistic support 

Space project management ‐ Risk management 

Space engineering ‐ System engineering general requirements 

Space engineering ‐ Electrical and electronic 

Space engineering – Thermal control general requirements 

Space engineering – Structural general requirements 

Space engineering – Environmental control and life support (ECLS) Space engineering – Propulsion general requirements 

Space engineering ‐ Software general requirements 

Space engineering ‐ Communications 

Space engineering ‐ Control engineering 

Space engineering ‐ Ground systems and operations 

Space product assurance ‐ Product assurance management 

Space product assurance ‐ Quality assurance 

Space product assurance – Dependability 

Space product assurance – Safety 

Space product assurance ‐ Electrical, electronic and electromechanical (EEE) components 

Space product assurance ‐ Materials, mechanical parts and processes Space product assurance ‐ Software product assurance 

34 ![Im2](images/Im2)

