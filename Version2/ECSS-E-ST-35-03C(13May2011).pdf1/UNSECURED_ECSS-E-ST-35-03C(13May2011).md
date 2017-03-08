ECSS-E-ST-35-03C13 May 2011Space engineering

Liquid propulsion for launchers

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐E‐ST‐35‐03  Working  Group,  reviewed  by  the  ECSS 

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

-  

-  

-  

- Copyright:  

ESA Requirements and Standards Division 

ESTEC, P.O. Box 299, 

2200 AG Noordwijk 

The Netherlands 

2011© by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐E‐ST‐35‐03C  13 May 2011 </td>
		<td>First issue </td>
	</tr>
</table>

3 ECSS‐E‐ST‐35‐03C 13 May 2011 Table of contents- Change log.................................................................................................................3

- Introduction................................................................................................................6

- 1 Scope.......................................................................................................................7

- 2 Normative references.............................................................................................8

- 3 Terms, definitions and abbreviated terms............................................................9

- 3.1  Terms from other standards .......................................................................................9

- 3.2  Abbreviated terms ......................................................................................................9

- 4 Overview of a liquid propulsion system.............................................................10

- 5 Functional .............................................................................................................12

- 5.1  Overview ..................................................................................................................12

- 5.2  Mission .....................................................................................................................12

- 5.3  Functions..................................................................................................................12

- 6 Constraints............................................................................................................13

- 6.1  Acceleration..............................................................................................................13

- 6.2  Geometrical constraints............................................................................................13

- 6.3  Electrical constraints ................................................................................................13

- 6.4  Safety .......................................................................................................................13

- 7 Development.........................................................................................................14

- 7.1  Overview ..................................................................................................................14

- 7.2  Development logic....................................................................................................14

- 8 Interfaces...............................................................................................................17

- 8.1  Overview ..................................................................................................................17

- 8.2  General.....................................................................................................................17

- 9 Design....................................................................................................................18

- 9.1  General.....................................................................................................................18

- 9.2  Specification .............................................................................................................18

4 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 - 9.3  Propulsion system selection.....................................................................................18

9.3.1  Overview.....................................................................................................18System selection ........................................................................................189.3.2

9.3.3

Propellant selection ....................................................................................19Engine selection .........................................................................................199.3.4

9.3.5

Selection of the TVC system ......................................................................19- 9.4  Propulsive system detailed design ...........................................................................20

9.4.1  Overview.....................................................................................................209.4.2  General.......................................................................................................20Filling and draining system.........................................................................209.4.3

Propellant tanks and management.............................................................219.4.4

9.4.5

Propellant feed system...............................................................................24- 9.5  Liquid engines ..........................................................................................................25

9.5.1  General.......................................................................................................25Performance...............................................................................................269.5.2

Functional system analysis.........................................................................269.5.3

9.5.4

Thrust chamber assembly (TCA)................................................................309.5.5  Gas generator and pre-burner....................................................................379.5.6

Turbomachinery subsystem .......................................................................379.5.7  Control and monitoring systems .................................................................399.5.8

Auxiliary functions supplied by the stage....................................................419.5.9  Components ...............................................................................................42- 9.6  Mechanical design....................................................................................................45

- 10 Ground support equipment ...............................................................................49

- 11 Materials..............................................................................................................50

- 12 Verification..........................................................................................................51

- 13 Production and manufacturing .........................................................................52

- 14 In-service.............................................................................................................53

- 14.1  General.....................................................................................................................53

- 14.2  Operation..................................................................................................................53

- 15 Deliverables ........................................................................................................54

- Bibliography.............................................................................................................55

 

5 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Introductionfunctional; 

constraints; 

development; 

interfaces; 

design; 

GSE; 

materials; 

verification; 

production and manufacturing; 

in‐service (operation and disposal); 

deliverables. 

The  requirements  in  this  Standard  ECSS‐E‐ST‐35‐03  (and  in  the  3  other  space propulsion standards ECSS‐E‐ST‐35, ECSS‐E‐ST‐35‐01 and ECSS‐E‐ST‐35‐02) are organized with a typical structure as follows: 























 

This  standard  forms  parts  of  ECSS‐E‐ST‐35  series  which  has  the  following structure; 











Propulsion general requirements 

ECSS‐E‐ST‐35 

ECSS‐E‐ST‐35‐01   Liquid and electric propulsion for spacecrafts 

ECSS‐E‐ST‐35‐02 

Solid propulsion for spacecrafts and launchers 

ECSS‐E‐ST‐35‐03  Liquid propulsion for launchers 

ECSS‐E‐ST‐35‐06  Cleanliness  requirements  for  spacecraft  propulsion components, subsystems, and systems 

ECSS‐E‐ST‐35‐10  Compatibility 

components, subsystems, and systems 

liquid 

propulsion 

testing 

for 

the  normative  references, 

ECSS‐E‐ST‐35  contains  all 

terms,  definitions, abbreviated  terms,  symbols  and  DRD  that  are  applicable  for  ECSS‐E‐ST‐35, ECSS‐E‐ST‐35‐01, ECSS‐E‐ST‐35‐02 and ECSS‐E‐ST‐35‐03. 

In the use of this standard, the term ‘propulsion system’ is intended to be read and interpreted only and specifically for ‘liquid prolusion system’. 

6 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 ScopeGeneral requirements applying to all type of Propulsion Systems Engineering are defined in ECSS‐E‐ST‐35. For Liquid propulsion for launchers activities within a space  project  the  standards  ECSS‐E‐ST‐35  and  ECSS‐E‐ST‐35‐03  are  applied together. 

This Standard defines the specific regulatory aspects that apply to the elements and processes of liquid propulsion for launch vehicles. It specifies the activities to be  performed  in  the  engineering  of  these  propulsion  systems  and  their applicability.  It  defines  the  requirements  for  the  engineering  aspects  such  as functional, physical, environmental, quality factors, operational and verification. Other  forms  of  propulsion  (e.g.  nuclear,  nuclear‐electric,  solar‐thermal  and hybrid propulsion) are not presently covered in this issue of the Standard. 

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

7 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Normative referencesThe following normative documents contain provisions which, through reference in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated  references, subsequent amendments to, or revision of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the normative documents  indicated  below.  For  undated  references,  the  latest  edition  of  the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐E‐ST‐10 

ECSS‐E‐ST‐10‐02 

ECSS‐E‐ST‐10‐06 

ECSS‐E‐ST‐32 

ECSS‐E‐ST‐32‐01 

ECSS‐E‐ST‐32‐02 

ECSS‐E‐ST‐32‐10 

ECSS‐E‐ST‐35 

ECSS‐Q‐ST‐70 

ISO 15389:2001 

 

ECSS system ‐ Glossary of terms  

Space engineering ‐ System engineering 

general requirements 

Space engineering ‐ Verification 

Space engineering ‐ Technical requirements specification 

Space engineering ‐ Structural general 

requirements 

Space engineering ‐ Fracture control 

Space engineering ‐ Structural design and 

verification of pressurized hardware 

Space engineering ‐ Structural factors of safety for spaceflight hardware 

Space engineering ‐ Propulsion general 

requirements 

Space product assurance ‐ Materials, 

mechanical parts and processes 

Space systems ‐ Flight‐to‐ground umbilicals 8 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Terms, definitions and abbreviated terms- 3.1  Terms from other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 and ECSS‐E‐ST‐35 apply. 

- 3.2  Abbreviated terms

For the purpose of this Standard, the abbreviated terms from ECSS‐S‐ST‐00‐01, ECSS‐E‐ST‐35 and the following apply: 

 

Abbreviation 

LPS 

 

Meaning 

liquid propulsion system 

 

 

9 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Overview of a liquid propulsion system

Main functions of a liquid propulsion system are: 















To provide thrust 

To provide thrust vector control 

To provide multiple burn capability if necessary 

To supply pressurized gas for auxiliary functions (e.g. roll control, stage orientation ) 

To supply fluid for pneumatic control (e.g. Helium) 

To provide thrust for propellant settling 

To provide information concerning its status (e.g. measurement)  



 



The liquid propulsion system generally consists in: 















the engine 

the tank 

the feed system 

the pressurisation system 

the command system 

the TVC 

auxiliary systems such as the anti‐POGO device, roll control system The typical life of a liquid propulsion system is the following: 

  Manufacturing and assembly 











Acceptance test (if any) 

Storage and transport 

Launcher integration 

Pre‐launch activities (e.g. flushing, leak tightness checks) 

Tanks filling 

  Main stage Chill down (for cryogenic liquid propulsion system) 

Launch chronology (including launch‐abort activities) 

10 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 













Lift‐off 

Chill‐down (for cryogenic liquid propulsion upper stages) 

Boost phases 

Stage separation 

Ballistic phase 

Passivation 

De‐orbiting, reaching a graveyard orbit, or both 

NOTE 

The way how to write the technical specification is given in ECSS‐E‐ST‐10‐06. 

11 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Functional- 5.1  Overview

Thrust 

Isp 

Burning time 

The general functional specification coming from mission optimisation at system level provides values for: 







 

The additional functional requirements are: 









thrust level versus time (throttling) 

propellant budget management (e.g. mixture ratio variation) 

TVC (e.g. maximum angle, acceleration, response time) 

start‐up  and  shutdown  transient  requirements  (e.g.  duration,  impulse scatter) 

auxiliary power to be delivered to the launcher (e.g. electrical and fluids) re‐startability 

propellant depletion 







- 5.2  Mission

a.

- 5.3  Functions

ECSS‐E‐ST‐35 clause 4.2 shall apply. 

a.

The  technical  specification  shall  provide  the  values  of  thrust,  Isp  and burning time with their deviations. 

12 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Constraints- 6.1  Acceleration

a.

Accelerations in the axial and lateral directions, assessed at launch vehicle level, shall be specified as an input for the propulsion system. 

NOTE 

The acceleration has an impact on the: 



functioning of the vortex suppression devices in the tank outlets; 

  pressure at the pump inlets; 



  mechanical loads. 

flow pattern in the tank; 

- 6.2  Geometrical constraints

a.

The  dimensioning  of  the  liquid  propulsion  system  and  its  components shall conform to the overall launch vehicle dimensions, interfaces between stages, ground infrastructure and requirements for transportation. 

- 6.3  Electrical constraints

a.

a.

- 6.4  Safety

The design of the prop system shall be such that the electrical continuity is ensured. 

The  design  of  the  liquid  propulsion  system  shall  conform  to  the  safety requirements of the launch system. 

NOTE 

For Example, ground safety requirements, flight safety requirements. 

13 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Development- 7.1  Overview

The phases of development for a liquid propulsion system are as follows: 



definition  of  system  and  subsystem  requirements  conforming  to  mission requirements 

establishment of the general concepts 

trade‐off of various concepts 

preliminary design 

risk analysis of the preliminary design and trade‐off of various options detailed design and definition 

manufacturing and assembly of 



























components, 

subsystems. 

integration of subsystem and system 

testing of: 









components, 

subsystems, 

engines, and 

system (functional stage). 

selection of the design to be qualified 

qualification process 

review of first article 

- 7.2  Development logic

a.

The  development  logic  shall  include  a  requirement  verification  plan  in conformance with ECSS‐E‐ST‐10‐02 ‘verification plan’. 

NOTE 

Example  of  verification  methods  are  analyses, tests. 

14 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 b.

The development logic shall be structured into phases with a goal assigned to each phase. 

c.  Mathematical models shall be implemented during the preliminary design phase and used for system trade‐off analysis. 

NOTE 1  See clause 9.3. 

NOTE 2   Preliminary design phase is Phase B of ECSS‐M‐

ST‐10. 

d.  Mathematical  models  shall  be  updated  using  component  and  subsystem results at milestones agreed by the customer. 

e.  Mathematical models shall be validated using test results. 

f.

g.

Mathematical models shall be used to determine the design margins. The development logic shall list the activities that are submitted to cross‐check. 

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

NOTE 

See ECSS‐E‐ST‐35 clause 4.8.1. 

The  sequence  of  development  activities  shall  include  components  and subsystem tests prior to system tests. 

The development logic shall mention the difficulties and critical activities of the development. 

NOTE 

In particular major development critical path. 

The development logic shall include risk management activities for project and technical risks. 

The  development  activities  shall  include  verification  that  manufacturing and  control  processes  lead  to  products  that  satisfy  specified  product‐to‐product variation limit. 

Lessons learned from previous programs shall be introduced in the design development plan. 

The  critical  technologies,  manufacturing  and  control  processes  shall  be listed and their qualification process described. 

NOTE 

See ECSS‐Q‐ST‐20. 

Liquid  propulsion  system  verification  shall  be  obtained  by  testing  the liquid propulsion system in conditions representative of flight. 

NOTE 

Following the typical approach “Test as you fly”. 

Through  the  measurement  plan  of  the  qualification  flight  the  LPS qualification shall be checked by post flight analysis. 

The development test plan shall include limit testing and failure cases. At the end of the development, the testing of the integrated system in its final configuration, including the electrical system, shall include tests with representative interfaces. 

NOTE 

For  example, 

computer, 

instrumentation. 

typical 

electrical 

interfaces  are  control flight interface, 

15 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 r.

s.

t.

u.

Phase by phase analyses of the life cycle of the liquid propulsion system shall  be  performed  in  relationship  with  the  launch  vehicle  system  in support of the failure mode analysis and the mechanical and thermal load case selection. 

A matrix of configuration of engine hardware versus subsystem hardware shall be produced. 

An  integrated  schedule  for  subsystem  hardware  deliveries,  engine integration, engine testing for all development and qualification hardware shall be produced. 

The output of all the requirement of clause 7.2 shall be detailed in the SEP (System Engineering Plan) as defined in the ECSS‐E‐ST‐10 Annex D DRD. 16 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Interfaces- 8.1  Overview

The interfaces of the liquid propulsion system are generally the following: 











Stage components (e.g. skirt, stage thermal protection) 

Other stages of the launch vehicle 

Launch vehicle on‐board computer 

Electrical supply system 

Interfaces with GSE (including the flushing, venting, filling and draining systems) 

Transport 



- 8.2  General

a.

b.

For interface requirements ECSS‐E‐ST‐35 clause 4.4 shall apply. 

The  environmental  conditions  imposed  to  the  liquid  propulsion  system shall be specified. 

NOTE 

For example, temperature, humidity, salt content of the atmosphere, inter stage conditioning). 

c.

d.

The loads induced by the liquid propulsion system acting on the launch vehicle and the payload shall be identified, evaluated and reported in the design definition file as defined in the ECSS‐E‐ST‐10 Annex G DRD. 

Examples of these loads are chugging, side loads, vibrations, blast wave, thermal radiation. 

NOTE 

Interface  requirements  shall  be  derived  from  the  extreme  operating envelope. 

17 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Design- 9.1  General

a.

The statement of work shall provide a ranking and weights of the design criteria. 

NOTE 

Criteria  are  for  example  performance,  reliability and development cost and recurring cost. 

b.

The design resulting from the optimisation of the above criteria 9.1a shall be provided and justified. 

- 9.2  Specification

a.

The  specification  of  a  liquid  propulsion  system  or  subsystem  shall  be  in conformance with ECSS‐E‐ST‐10‐06. 

- 9.3  Propulsion system selection

9.3.1  Overview

The  mixture  ratio  is  derived  from  a  system  optimization  analysis,  taking  into account the characteristics of the envisaged liquid propulsion system and rocket engines. 

The mixture ratio and the total amount of propellants, is the determining factor for the sizing of the tanks, together with the pressure and temperature. 

System selection

9.3.2

a.

For the selection of the liquid propulsion system architecture, a trade‐off analysis shall be performed using the following parameters: 

1.

2.

3.

4.

5.

6.

type of propellants; 

engine architecture and thermodynamic cycle; 

propellant mixture ratio; 

propellant storage; 

pressurization and feed system; 

any additional parameters specified by the customer. 

18 ![Im0](images/Im0)

![Im0](images/Im0)

9.3.3

a.

Propellant selection

ECSS‐E‐ST‐35‐03C 13 May 2011 For the selection of the propellant, a trade‐off analysis shall be performed using the following parameters: 

1.

2.

3.

4.

5.

6.

7.

8.

9.

conformance to the launch vehicle system requirements; 

performance; 

availability; 

handling; 

storage; 

safety; 

cost; 

impact on the environment; 

any additional parameters specified by the customer. 

Engine selection

9.3.4

a.

For  the  selection  of  the  engine,  a  trade‐off  analysis  shall  be  performed using the following parameters: 

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

global stage performance (e.g. Isp, mass budget); 

development costs; 

recurring cost; 

industrial infra structure; 

test infra structure; 

reliability; 

strength; 

architecture and overall dimensions; 

the technical readiness level of the technologies; 

any additional parameters specified by the customer. 

Selection of the TVC system

9.3.5

a.

For the selection of the TVC, a trade‐off analysis shall be performed using the following parameters: 

1.

2.

3.

4.

5.

6.

global mass; 

strength; 

performance losses; 

power consumption; 

costs; 

reliability; 

19 ECSS‐E‐ST‐35‐03C 13 May 2011 7.

8.

9.

control loop stability; 

geometrical constraints; 

any additional parameters specified by the customer. 

- 9.4  Propulsive system detailed design

9.4.1  Overview

The propulsive system is the part of the liquid propulsion system that deals with the: 









filling and draining system; 

feeding system from the tank to the engine inlets; 

pressurisation system; 

functional  aspect  of  the  tanks  (e.g.  propellant  budget,  propellant management). 

The function of the propulsive system is to deliver the propellants to the engine in the specified thermodynamic conditions (e.g. aggregation state, pressure and temperature)  and  specified  flow  conditions  (e.g.  vorticity,  and  velocity distribution). 

9.4.2  General

a.

At liquid propulsion system level, functional and mechanical models shall be  established  and  used  to  derive  propulsive  system  components specifications and engine inlet conditions. 

Propulsive system components shall provide inputs to the functional and mechanical models at various steps of the development. 

The  liquid  propulsion  system  shall  allocate  reliability  objective  for  each propulsive system component. 

The liquid propulsion system test plan and instrumentation plan shall be established  such  that  it  can  be  demonstrated  that  the  test  objectives  of propulsive system components are reached. 

The  liquid  propulsion  system  shall  assign  pollution  objective  for  each propulsive  system  component,  in  terms  of  distribution  of  size  and numbers of incoming and exiting particles. 

b.

c.

d.

e.

9.4.3

Filling and draining system

9.4.3.1

a.

Filling and draining system on ground

The  filling  and  draining  subsystems  shall  conform  to  ISO  15389:2001(E) subclauses 4.4 to 4.7, and subclauses 4.9 and 4.20. 

20 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 b.

For cryogenic propellants, if the nominal draining lines between the liquid propulsion system and the GSE are disconnected before lift‐off, the liquid propulsion system shall be provided with emergency draining possibilities that enable draining after a launch abort. 

NOTE 

The filling subsystem can be combined with the draining functions. 

9.4.3.2  Draining system in flight (passivation and

degassing)

a.

b.

In‐flight  draining  shall  not  create  conditions  that  can  lead  to  loss  of performance of the launch vehicle. 

If  in‐flight  draining  cannot  be  performed  through  the  flow  paths  for  the normal operation of the propulsion system, specific lines or valves shall be incorporated in the liquid propulsion system to enable in‐flight draining. Flushing, purging and venting

9.4.3.3

a.

The subsystems or components of the liquid propulsion system for which flushing,  purging  or  venting  is  performed  during  ground  tests,  launch activities (including launch‐abort) and flight, shall be identified. 

The liquid propulsion system shall provide valves and lines to flush, purge or vent the subsystems or components identified in 9.4.3.3a. 

On ground, the flushed and purged fluids shall be collected. 

The flushing and purging systems shall neither create hazards to personnel nor harm the environment. 

Provisions  shall  be  taken  to  ensure  that  vented  fluids  do  not  create hazards. 

NOTE 

For example, burn‐off of vented hydrogen. 

Flushing,  purging  and  venting  in  flight  shall  not  create  unwanted propulsive effects. 

NOTE 

For example, non‐propulsive venting. 

b.

c.

d.

e.

f.

9.4.4

Propellant tanks and management

9.4.4.1  General

a.

the tank volume shall be designed using at least the following: 

1.

The  amount  of  propellant  to  be  used  during  nominal  propulsion operations; 

the amount of propellant provisions covering the liquid propulsion system and launch vehicle deviations; 

losses and ejected propellants; 

the amount of unusable propellant; 

the ullage volume; 

2.

3.

4.

5.

21 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 equipment and lines within the tank. 

6.

The  tank  volume  shall  be  determined  at  the  extreme  temperature  and pressure ranges. 

The propellant loaded mass shall be measured with the accuracy requested by TS. 

The tank shall be protected against over pressurisation. 

b.

c.

d.

9.4.4.2

Tank pressure and temperature and pressurisationsystem

9.4.4.2.1  General

a.

b.

c.

d.

e.

f.

g.

h.

i.

The management of the tank pressure shall be such that the engine inlet thermodynamic  conditions  comply  with  the  engine  requirements  for  all phases of the mission. 

The tank pressure analysis shall consider during all phases of the mission: 1.

2.

3.

4.

5.

6.

Tank heat balances shall be performed for all phases of the mission. 

The pressurization system shall cover the worst case in terms of pressurant consumption. 

internal heat fluxes; 

external heat fluxes; 

pressurant conditions; 

sloshing of propellant; 

expelled fluids; 

vehicle accelerations. 

NOTE 

The most usual worst case is when the: 



temperature of pressurant is minimum, 



final volume of propellant tank is maximum, 

  pressure  of  propellant  tank  is  maximum (based on pressure regulator characteristics). 

Pressurant  gas  budget  shall  include  provision  for  gas  leakage  through equipment of the pressurisation system. 

For the initial design a 30 % margin shall be used on the pressurant mass. The  pressurization  system  shall  not  induce  pressure  oscillations  in  the liquid propulsion system or stage. 

There  shall  not  be  back  flow  (gaseous  or  liquid)  into  the  pressurization system. 

The  pressurization  system  shall  prevent  detrimental  contact  between dissimilar fluids. 

22 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 9.4.4.2.2  Maximum tank pressure

a.

A MEOP shall be calculated using at least the: 

1.

2.

3.

4.

5.

time history of the tank pressure during the mission; 

acceleration; 

tank geometrical deviations; 

pressure regulator operation and deviation; 

internal and external heat flux. 

NOTE 

The maximum design pressure (MDP) is defined in ECSS‐E‐ST‐32, term 3.2.27 

9.4.4.2.3  Minimum tank pressure

a.

The  minimum  tank  operating  pressure  shall  conform  to  with  the  tank structural requirement. 

The  minimum  tank  operating  pressure  shall  conform  to  with  the  engine inlet requirement. 

b.

b.

c.

d.

e.

Tank draining

9.4.4.3

a.

An emergency draining or depletion procedure shall be present in case the nominal draining operation fails. 

For  all  tanks,  the  location  of  fill‐and‐drain  valves  and  the  piping  layout shall  be  such  that  liquids  are  not  trapped  in  the  system  by  on‐ground draining and dissimilar fluids do not come into contact with each other. The tank design shall be such that the occurrence of a vortex is prevented. NOTE 

This  usually  happens  when  the  tank  is  nearly empty 

If 9.4.4.3c. is not met an anti‐vortex device shall be installed at the sump to avoid gas ingestion into the feed lines. 

The  acceptability  of  propellant  depletion  shall  be  integrated  in  the “development logic” clause 7.2. 

Sloshing

9.4.4.4

a.

b.

Propellant sloshing shall be analysed during all phases of the mission. The effects of propellant sloshing in tank shall be analysed at both launch vehicle and liquid propulsion system levels. 

NOTE 1  The propellant sloshing can have an effect on for example: 

  Guidance,  navigation  and  control  of  the launch vehicle, 

  Propellant thermal stratification, 

  Tank pressurisation. 

NOTE 2  Anti  sloshing  device  can  be  introduced  to  limit the sloshing amplitude. 

23 ![Im0](images/Im0)

![Im0](images/Im0)

9.4.4.5

a.

Propellant Management Device (PMD)

ECSS‐E‐ST‐35‐03C 13 May 2011 The  adverse  effect  of  propellant  fluid  motion  and  micro  gravity  shall  be analysed. 

NOTE 

PMD device can be introduced to limit the above effects (such as swirl and sloshing). 

9.4.4.6  Common bulkheads

a.

The  management  of  the  pressure  of  each  tank  shall  demonstrate  that, during the whole mission, the bulkhead does not fail. 

9.4.4.7

a.

b.

c.

d.

Temperature management

For storable propellants, the temperature prevision accuracy shall be 0,5 K. For cryogenic propellants, the temperature prevision accuracy shall be 0,1 K. If  there  is  thermal  stratification,  the  temperature  distribution  shall  be evaluated  with  the  same  accuracy  as  respectively  9.4.4.7a  for  storable propellants and 9.4.4.7b for cryogenic propellant. 

A thermal balance shall be established for all phases of the mission. 

9.4.5

Propellant feed system

9.4.5.1  General

a.

The  feed  system  shall  ensure a  homogeneous  parallel  flow at  the  engine inlet  in  the  thermodynamic  conditions  defined  in  the  engine  technical specification. 

Pressure drop

9.4.5.2

a.

The pressure drops in the feed system shall be determined by calculations. NOTE 

The calculation of the feed system pressure drop takes  into  account  the  characteristics  of  the components constituting the feed system. 

b.

c.

The  LPS  measurement  plan  shall  allow  the  measurement  of  feed  system pressure drop. 

The combination of the deviations and uncertainties shall be performed via a statistical approach. 

NOTE 

Statistical 

can 

combination or Monte Carlo. 

approach 

be 

quadratic 24 ECSS‐E‐ST‐35‐03C 13 May 2011 9.4.5.3  Dynamic effect

9.4.5.3.1  Non-stationary effects

a.

b.

The occurrence of pressure fluctuations shall be analysed. 

The liquid propulsion system shall be designed so that no adverse effects of the pressure fluctuations occur during the mission. 

NOTE 

(Rapid)  variations  in  the  mass  flow  rate  in  the feed system can introduce pressure fluctuations. These are related to the time rate of change of the mass  flow  rate  and  to  the  geometry  of  the  feed system  (L,  D).  These  pressure  fluctuations  can interact with the structure of the feed system or adversely  affect  motor  operation,  e.g.  pump cavitation. 

c.  Water‐hammer  phenomena  shall  have  no  detrimental  effect  on  the structural and the functional behaviour of the propulsion system. 

Rapid decomposition of the propellant vapour shall be avoided. 

d.

NOTE 

This decomposition can be created by: 

  adiabatic compression, 

  contact with hot spots and catalyst materials. 

9.4.5.3.2  Propulsion system dynamic interaction with launch vehiclestructure (POGO)

a.

b.

c.

The POGO phenomenon shall be analysed for the whole mission. 

The result of the analysis in 9.4.5.3.2a shall be used to conclude regarding the need of an anti‐POGO device. 

POGO Mathematical modelling shall be reported as defined in the ECSS‐E‐ST‐35 Annex I DRD. 

- 9.5  Liquid engines

9.5.1  General

a.

At engine system level, geometrical (CAD models), functional, mechanical, thermal  models  shall  be  established  and  used  to  derive  subsystem specifications. 

Subsystem shall provide inputs to the above models at various steps of the development. 

The engine system shall allocate reliability objective for each subsystem. The test plan of the liquid engine shall include subsystem test objectives when  establishing  test  plan  and  allocate 

instrumentation  channels accordingly. 

b.

c.

d.

25 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 e.

f.

The  engine  system  shall  assign  pollution  objective  for  each  subsystem (including  distribution  of  size  and  numbers  of  incoming  and  exiting particles). 

The development of the engine subsystems shall be managed in the same way as the whole engine following the applied management rules. 

NOTE 1  This  means  that  the  development  of  subsystem will  also  contain  phasing,  reviews  and  a complete set of documentation deliverables). 

NOTE 2  A  launch  vehicle  liquid  engine  is  a  system composed of subsystems and components. 

NOTE 3  The  engine  design  is  based  on  the  flow  of information  from  the  system  to  the  subsystem and  vice  versa  all  along  the  development process. 

Performance

9.5.2

a.

The  engine  thrust  shall  be  calculated  as  the  vectorial  sum  of  the  thrusts generated by all engine components. 

NOTE 

This concerns: 







  ventings, purgings. 

the main nozzles, 

the contribution from dump cooling, 

the turbine exhaust gases, 

9.5.3

Functional system analysis

9.5.3.1  General

a.

Nominal engine performance and deviation shall be defined at a reference operating point. 

Engine  performance  losses  shall  be  analysed  and  reported  in  the  design justification file in as defined in ECSS‐E‐ST‐10 Annex K DRD. 

Contributions to engine thrust shall be analysed and reported in the design justification file as defined in ECSS‐E‐ST‐10 Annex K DRD. 

The operating limits of each major subsystem shall be reported at engine definition file level. 

b.

c.

d.

NOTE 

example,  maximum 

For 

speed corresponding  to  disk  burst,  flow  separation limit, combustion chamber mixture ratio limit. 

rotating 

Performance

The  performances  of  the engine shall be  determined  and  documented  in the design justification file as defined in ECSS‐E‐ST‐10 Annex K DRD. 9.5.3.2

a.

26 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 b.

The  deviation  and  offsets  of  the  performances  shall  be  determined  and documented  in  the  design  justification  file,  as  defined  in  ECSS‐E‐ST‐10 Annex K DRD. 

NOTE 

liquid  rocket  engine, 

the  performance Isp 

For 

concerns at least: 

  Thrust 



  Mixture ratio 

  Dry mass 

  Required NPSP 

  Roll moment 

  Fluid consumptions 

  Electrical consumptions 

9.5.3.3  Reference point and envelopes

9.5.3.3.1  Overview

For operational envelope see ECSS‐E‐ST‐35 clause 4.5.3.1. 

For qualification points see ECSS‐E‐ST‐35 clause 4.5.3.2. 

9.5.3.3.2  Operational envelope

a.

b.

c.

In the initial design process, an operational envelope shall be selected in conformance to the stage or launch vehicle requirements. 

The  liquid  propulsion  system  or  subsystem  shall  operate  within  the operational envelope specified in 9.5.3.3.2a. 

NOTE   During the design process, the launch vehicle or stage  requirements  can  change;  it  is  therefore prudent  to  consider  a  project  margin  when defining the operational envelope. 

The operational envelope shall be designed with the following parameters: 1.

The range of functional parameters of the liquid propulsion system during flight and testing. 

NOTE 

In  particular  flow  rate,  mixture  ratio,  tank propellant pressure. 

The range of interface parameters. 

NOTE 

In  particular  acceleration  effect,  inlet  pressure and  inlet  temperature  variations,  temperature environment. 

Deviations in the trimming and throttling of the propulsion system. Deviations in the various modelling processes. 

Deviations in component performances. 

Deviations in manufacturing. 

Deviations in measurements. 

2.

3.

4.

5.

6.

7.

27 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 d.

e.

The operational envelope shall be used for the initial design of propulsion systems, subsystems and components. 

The operational limits of the systems, subsystems or components shall be documented. 

9.5.3.3.3  Qualification points (test)

a.

The engine and its systems, subsystems and components shall be qualified to  demonstrate  that  the  engine,  system,  subsystems  and  components operate  as  specified  in  the  whole  operational  envelope,  including uncertainty and deviations. 

NOTE 

This  means  that  the  qualification  points  are covering the operational envelope. 

b.

c.

ground test facility conditions compared to the flight ones; 

deviations in the trimming and throttling of the propulsion system; deviations in the modelling processes; 

deviations in the component performances; 

deviations in manufacturing; 

deviations in measurements. 

The qualification points shall be defined using the following parameters: 1.

2.

3.

4.

5.

6.

If  a  rocket  engine  is  expected  to  operate  in  disconnected  envelopes (qualification  envelopes  which  do  not  overlap)  the  following  shall  be performed: 

1.

2.

3.

the engine qualified in each envelope separately; 

ensure that a transition between the two envelopes can be made; the transient process specified in 9.5.3.3.3c.2. qualified. 

9.5.3.3.4  Reference point

a.

b.

One or more reference points shall be defined. 

The  performance  optimization  point  shall  be  required  in  the  engine specification. 

9.5.3.3.5  Extreme envelope

a.

b.

An  extreme  envelope  shall  be  defined  around  the  qualification  points using: 

1.

2.

The extreme envelope shall be reported from the PDR. 

hardware deviation; 

test bench deviation. 

28 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 9.5.3.4

Transients

9.5.3.4.1  General

a.

Transient  analyses  shall  be  reported  in  conformance  with  the  DRD  in ECSS‐E‐ST‐35 Annex G ‘Propulsion transients analysis report’. 

9.5.3.4.2  Chill-down

a.

b.

Chill down criteria shall be defined. 

The propellant consumption for chill down and chill down duration shall be considered as performance parameters. 

9.5.3.4.3  Start-up

a.

The  supplier  shall  demonstrate  that  the  engine  functional  parameters during ignition and start‐up remain within the specified range. 

NOTE 

In  particular  mixture  ratio,  pump  rotational speed. 

A  test  bench  configuration  representative  of  the  stage  configuration  and flight environment shall be used. 

If 9.5.3.4.3b. is not met, a justification shall be provided and cross checked. The supplier shall demonstrate that any dynamic effect, generated during start‐up,  is  kept  within  the  specified  ranges  for  the  stage  and  launch vehicle. 

For  multi  engine  stage,  criteria  shall  be  defined  for  thrust  profile deviations between engines. 

The start‐up sequence shall include the following: 

1.

2.

3.

4.

If  a  liquid  propulsion  system  is  expected  to  be  activated  after  a  ballistic flight, a propellant settling analysis shall be carried out. 

pressurization of the propellant tanks, 

settling of the propellants in the tanks, 

performance of the OBCs, 

complete filling of lines, pumps and cooling circuits. 

b.

c.

d.

e.

f.

g.

In-flight transients

9.5.3.4.4

a.

In  flight  transient  between  two  operated  conditions  shall  not  create adverse dynamic effects. 

9.5.3.4.4a. shall be verified by tests. 

b.

9.5.3.4.5  Shutdown

a.

The  supplier  shall  demonstrate  that  the  engine  functional  parameters during shut‐down remain within the specified range. 

NOTE 

Functional parameters such as mixture ratio and pump rotational speed. 

29 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 b.

c.

d.

e.

A  test  bench  configuration  representative  of  the  stage  configuration  and flight environment shall be used. 

If 9.5.3.4.5b. is not met, a justification shall be provided and cross checked. The supplier shall demonstrate that any dynamic effect, generated during shut‐down,  is  kept  within  the  specified  ranges  for  the  stage  and  launch vehicle. 

For  multi  engine  stage,  criteria  shall  be  defined  for  thrust  profile deviations between engines. 

9.5.3.4.6  Thrust decay and tail off

a.

The thrust decay of an engine at nominal shutdown shall be determined analytically and derived from test results. 

The tail‐off characteristics shall be reproducible within the specified range. The total impulse and its deviation shall be determined. 

b.

c.

9.5.4

Thrust chamber assembly (TCA)

9.5.4.1  Overview

The TCA of liquid rocket engine for launch vehicle is an engine subsystem with the following functions: 









to enable admission of propellants; 

to ignite the propellants, maintain combustion, and enable shutdown; to eject high‐temperature, high‐pressure gases; 

to act as a power source for turbo‐pumps (e.g. for the expander bleed or tap‐off cycle); 

to transfer thrust; 

to act as a structural support for engine components and subsystems. 



 

In addition, the thrust chamber can have the following secondary functions: 

to enable the installation and functioning of transducers and measurement equipment; 

to provide pressurized fluids to subsystems (e.g. tank pressurization and TVC). 



 

The main components of the thrust chamber assembly are: 









the injector, 

the igniter, 

the combustion chamber and 

the nozzle. 

30 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 the feed system, 

the combustion chamber and 

the combustion process. 

 

Combustion instability in liquid rocket engines involves: 







 

The different types of instabilities that are commonly found, are low frequency or chugging, POGO and high frequency combustion instability. 

Low  frequency  oscillations  related  to  the  hydraulic  coupling  between  the  feed system and the combustion delay are designated as chugging. 

Low frequency oscillations involving the complete hydraulic feed system up to the tank and the structure are designated as POGO. 

Combustion  instabilities  related  to  the  combustion  process  are  usually  high frequency  (HF)  acoustic  oscillations.  They  are  related  to  the  mixing  and evaporation  processes.  HF  combustion  instability  is  manifested  by  violent combustion chamber pressure oscillations. 

Combustion instability damping devices can be used to: 









increase the engine stability margin, 

suppress the growth of oscillatory combustion, 

damp pressure oscillations, and 

limit the amplitude of pressure oscillations to values that conform to the engine requirements. 

NOTE 

Instabilities  often  occur  during  transients,  i.e. start‐up  and  shutdown.  Changing  the  valve sequence  or  timing  can  affect  the  instabilities. Gas purging also can affect the instabilities 

inlet manifold or manifolds; 

propellant dome or domes; 

passages to feed the injector elements; 

the faceplate that contains the injector elements. 

 

An injector is generally composed of: 









 

The main function of a combustion chamber are: 



to enable the combustion gases to attain the specified pressures with the specified efficiency; 

to  enable  the  engine  turbo  machinery  to  be  powered  in  the  case  of expander, bleed, and tap‐off cycles; 

if specified, to provide gases for tank pressurization; 





31 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 to sustain all loads including thrust; 

to transmit forces and torques to the stage. 





 

The function of the nozzle is to accelerate the combustion gases, thereby creating an  additional  thrust  compared  to  a  combustion  chamber  without  a  nozzle extension. 

As  an  auxiliary  function,  the  nozzle  can  support  lines  such  as  exhaust  lines  or drain lines. 

 

The different types of nozzles are: 



Radiatively cooled nozzle, 



Regeneratively cooled nozzle and 



Film cooled nozzle. 

9.5.4.2  General

a.

b.

TCA subsystem fire tests shall be included in the development plan. 

The  chemical  effects  of  the  propellants  and  of  the  burned  gases  shall  be analysed in the TCA design and justification. 

Performance

9.5.4.3

a.

b.

c.

The  values  of  the  performance  parameters  (Isp,  C*,  CF),  over  the  entire operational envelope of the TCA, shall be determined and reported in the design definition file, as defined in the ECSS‐E‐ST‐10 Annex G DRD. 

Losses  and  gains  shall  be  used  in  determining  or  assessing  the  effective specific impulse, independently of the analysis approach taken. 

A  budget  of each  elementary losses and  gains shall  be  established  for at least the following terms: 

1.

2.

3.

4.  Wall heat loss and boundary layer effects 

5.

Deviation of propellant composition 

Kinetic effects 

Combustion pressure loss 

Non‐uniform  flows  and  multi‐phase  flow  effects  (e.g.  unburned droplets, condensation) 

Hot gas tap‐off 

Ablative wall 

Temperature effects 

Film cooling effect 

Shock and flow separation 

6.

7.

8.

9.

10.

11.  Re‐injection of gas 

32 ![Im0](images/Im0)

![Im0](images/Im0)

9.5.4.4

a.

TCA contour

ECSS‐E‐ST‐35‐03C 13 May 2011 For determination of TCA contour, the performance requirements and the cooling capacity shall be used. 

The  TCA  contour,  including  the  length,  the  contraction  ratio,  the  throat diameter  and  the  throat  area,  shall  be  reported  and  justified  in  the  TCA design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD. b.

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

9.5.4.5  Cooling system

a.

pressure drop along the cooling channels; 

temperature rise along the cooling channels; 

the effect on the engine performance (Isp). 

The justification of the choice of the cooling principle shall be reported in the design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD. The  fluid  cooling  system  shall  be  designed  including  the  following parameters: 

1.

2.

3.

The justification of the choice of the coolant fluid shall be reported in the design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD. The  following  performance  parameters  shall  be  reported  in  the  design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD: 

1.

2.

3.

Dissymmetric  effects  shall  be  reported  in  the  design  justification  file,  as defined in the ECSS‐E‐ST‐10 Annex K DRD.  

pressure drop along the cooling channels; 

temperature rise along the cooling channels; 

chamber wall temperature distribution. 

NOTE 

For example including unbalance in coolant flow distribution. 

It shall be demonstrated that ageing effects do not deteriorate the cooling performances (e.g. coking). 

NOTE   Ageing effect such as coking. 

Deviations  of  surface  roughness  shall  not  deteriorate  the  cooling performances. 

NOTE 

For  example,  roughness  due  to  manufacturing processes. 

Vapour blockage during transient shall not induce any adverse effect. The external radiation heat flux shall be reported. 

Manufacturing  inspection  and  verification  processes  shall  be  defined  in order to demonstrate that the cooling system is free of any residual flow blockage and leak. 

After hot fire test, the check process shall detect flow blockage or leak in the cooling system. 

33 ![Im0](images/Im0)

l.

For  active  cooling  system,  the  outlet  coolant  flow  temperature  shall  be measured. 

ECSS‐E‐ST‐35‐03C 13 May 2011 m.  During engine start‐up, flow rate shall not block in the cooling channels. n.

During engine start‐up, the verification that the cooling film is established and effective shall be performed. 

In case of TRL lower than 5 the dedicated Technology plan, as defined in the ECSS‐E‐ST‐10 Annex E DRD, shall include: 

1.

2.

Calorimetric tests; 

Flow tests. 

o.

9.5.4.6  Heat soak back

a.

The effect of the transfer of heat of the TCA after shutdown of the engine, from the hot parts of the TCA to cooler parts, shall not overpass the design temperature range of the TCA. 

The effect of the transfer of heat of the TCA after shutdown of the engine, from the hot parts of the TCA to cooler parts, shall not overpass the design temperature range of the engine components. 

b.

b.

c.

d.

e.

f.

g.

h.

9.5.4.7  Combustion stability

a.

The  stability  margin  shall  be  a  design  criteria  when  designing  a  thrust chamber. 

The  stability  margin  of  an  engine  design  shall  be  determined  before  the thrust chamber CDR. 

For  low  frequency  oscillations,  P/P  threshold  shall  be  defined  (P: pressure drop across the injector and P: combustion chamber pressure). For high frequency oscillations, the thresholds of propellant temperatures shall be defined. 

NOTE 

For  example,  LH2  temperature  for  cryogenic engines. 

The  stability  margin  shall  be  demonstrated  by  tests  over  the  extreme envelope at transients and steady state. 

NOTE 

The  preferred  method 

artificial perturbation  of  the  combustion  process,  bomb and  gas  bubble  ingestion  and  the  evaluation  of the damping characteristics. 

the 

is 

Oscillation in the combustor shall not damage the engine. 

Oscillation  in  the  combustor  shall  not  adversely  affect  the  engine performance. 

The pressure oscillation history shall be reported in the design definition file, as defined in the ECSS‐E‐ST‐10 Annex G DRD. 

NOTE 

The  pressure  oscillation  history  is  the  level  of pressure  oscillation  with  respect  to  frequency and time. 

34 ![Im0](images/Im0)

9.5.4.8

TCA components

ECSS‐E‐ST‐35‐03C 13 May 2011 Injector

9.5.4.8.1

a.

b.

c.

d.

e.

f.

g.

h.

i.

c.

d.

e.

f.

g.

h.

Flow  homogeneity  at  the  inlet  of  the  injection  elements  and  at  faceplate exit shall be evaluated and reported. 

The  design  of  the  injector  shall  ensure  the  absence  of  low  and  high frequency oscillation during steady state operation. 

The design of the injector shall limit the heat load on the chamber wall to a level in compliance with the combustion chamber life requirement. 

The risk induced by pollution and icing shall be estimated. 

The mixing of propellants inside the injector shall be prevented during the whole mission. 

Specific injector tests shall be performed and reported in the case of: 

1.

2.

3.

In case of TRL lower than 5, the dedicated Technology plan, as defined in the ECSS‐E‐ST‐10 Annex E DRD, shall include: 

1.

2.

3.

The  manufacturing  inspections  and  verifications  shall  confirm  that  the flow passages are free of flow blockage and leak. 

After hot fire test, the check process shall detect if there is flow blockage or leak in the injector. 

new propellant, or 

new injection principle, or 

out of experience operating range. 

injector flow pattern test; 

spray test of injector elements; 

single element fire test. 

The ignition system shall ensure ignition over the whole extreme envelope. A  maximum  level  of  pressure  spikes  (amplitude  and  frequency)  in  the combustion chamber shall be defined. 

The ignition shall not lead to pressure spikes exceeding the specified level. Ignition criteria shall be defined including deviations. 

The limit of the ignition envelope shall be determined. 

The  development  logic  shall  include  the  demonstration  of  the  reliability requirement for ignition system. 

Damage  to  the  chamber wall  which  is  initiated  from  the  ignition  system shall be prevented. 

If there are specific requirements on the angular position of the igniter, the design  shall  be  such  that  mounting  can  only  be  done  in  the  specified position. 

Ignition system

9.5.4.8.2

a.

b.

35 ECSS‐E‐ST‐35‐03C 13 May 2011 i.

j.

The measurement to ensure that proper operation of the ignition system is obtained shall be defined. 

The  actual 

ignition  of 

measurements and compared to the ignition criteria. 

the  combustor  shall  be  monitored  with NOTE 

For pyrotechnic igniters, see ECSS‐E‐ST‐33‐11. 

9.5.4.8.3  Combustion chamber

a.

b.

NOTE 

Static pressure shall be measured during operation. 

Dynamic pressure fluctuations shall be measured during hot fire tests. The  implementation  of  the  dynamic  pressure sensors  is  such  that  the  high  frequencies  are captured  and  the  measurement  signal  is  not dampened  by 

test  port configuration or the high viscosity of the fluid. 

transmitting 

the 

c.

d.

e.

The  frequency  range  of  the  dynamic  pressure  fluctuations  measurement shall  cover  the  two  first  tangential  acoustic  modes,  the  two  first  radial acoustic  modes  and  the  two  first  longitudinal  acoustic  modes  of  the combustion chamber. 

A risk analysis at TCA and engine levels of the consequences of chamber wall cracks shall be performed. 

Combustion  roughness  requirement  shall  be  defined  in  the  technical specification. 

9.5.4.8.4  Nozzle extension

a.

For radiative nozzle, the self induced heat loads shall be assessed during operation and after shut‐down of the engine. 

For  heat  soak  back  (see  9.5.4.6)  a  risk  analysis  at  nozzle  extension  and engine levels of the consequences of nozzle wall cracks shall be performed. The  mechanical  design  justification  shall  include  an  evaluation  of  the margin concerning buckling. 

For  deployable  nozzle,  the  deployment time  shall  conform  to  the  launch vehicle requirements. 

For first stage engine, flow separation margins shall be demonstrated by tests. 

The  design  justification  file  shall  contain  an  evaluation  of  any  torque  or asymmetric effect that can be introduced by the nozzle. 

b.

c.

d.

e.

f.

NOTE 

For  example,  boundary  layer  interaction  with spirally wound coolant channels, tangential fluid injection. 

36 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 9.5.5  Gas generator and pre-burner

9.5.5.1  Overview

The  main  function  of  a  gas  generator  or  a  pre‐burner  is  to  provide  hot  gas  to drive the turbopump(s). 

The  propellants  are  usually  burned  at  a  mixture  ratio  lower  than  the  nominal mixture ratio for limiting the temperatures in the turbines. 

9.5.5.2  General

a.

Requirements  concerning  non‐uniformity  of  the  flow  pattern  at  the  gas generator,  pre‐burner  exit,  or  both,  shall  be  expressed  in  the  technical specification. 

Injector requirements of clause 9.5.4.8.1 shall apply. 

Combustion chamber requirements of clause 9.5.4.8.3 shall apply. 

Combustion stability requirements of clause 9.5.4.7 shall apply 

Performance requirements of TCA clause 9.5.4.3 shall apply. 

Ignition system requirements of TCA clause 9.5.4.8.4 shall apply. 

b.

c.

d.

e.

f.

9.5.6

Turbomachinery subsystem

to provide a pressure head to a given propellant mass flow. 

9.5.6.1  Overview

The main function of a turbopump is: 



 

The main constraints of a turbopump are: 





to operate within a given pressure and temperature domain at pump inlet, to  operate  within  a  given  pressure  and  temperature  domains  at  turbine inlet and outlet. 

9.5.6.2  General

a.

The  pump  hydraulic  performance  shall  be  established  over  the  entire extreme envelope using dimensionless coefficients. 

NOTE 

Pump  hydraulic  performance  are  pressure  rise, efficiency and suction performance. 

b.

c.

The  turbine  performance  shall  be  established  over  the  entire  extreme envelope using dimensionless coefficients. 

Pump and turbine performance losses shall be determined and reported in the design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD. 37 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 The pump and turbine characteristics shall be determined in the transient phases  (start‐up  and  shutdown)  to  ensure  safe  operation  during  these transient phases. 

A  safe  operation  domain  shall  be  established  in  the  (dimensionless  flow coefficient, dimensionless cavitation coefficient)axis. 

NOTE 

Safe  operation  can  be  defined  as  no  cavitation (using  for  instance  5  %  head  loss  criteria),  no pressure oscillation and excessive vibration. 

d.

e.

f.

g.

h.

i.

j.

k.

For  stable  pump  operation,  the  pump  shall  operate  in  the  part  of  the performance  curve  with  a  negative  slope  in  the  (dimensionless  flow coefficient, dimensionless pressure head coefficient) axis. 

Vibration limits shall be established. 

There shall be no resonance between frequencies of rotating parts and first and  second  harmonics  of  excitation  frequencies  on  the  whole  extreme envelope. 

The  safety  margin  regarding  proximity  of  frequencies  leading  to  a resonance shall be defined. 

The  safety  margin  regarding  proximity  between  critical  speed  and  the extreme envelope shall be defined. 

During  transient,  if  coincidence  appears,  the  life  of  the  concerned component (in terms of number of cycle and duration) shall be justified. For rotating blades, aeroelastic stability shall be assessed. 

l.

m.  When boost pump are used, the justification of their use shall be expressed at  the  liquid  propulsion  system  level  including  performance,  reliability and cost. 

NOTE 

Performance 

system, mass budget. 

includes  mass,  pressurisation If the suction performance is obtained using similitude tests transposition to real propellant shall be justified. 

NOTE 

Similitude  test  such  as  water  test  for  cryogenic propellant. 

Requirements concerning non‐uniformity of the flow pattern at the turbine exit shall be documented in the technical specification. 

Requirements concerning non‐uniformity of the flow pattern at the pump inlet shall be documented in the technical specification. 

The  acceptable  level  of  radial  loads,  amplitudes  and  frequencies,  due  to cavitation shall be established, including the characteristics of the bearings, shaft vibration amplitude and the turbo pump life requirements. 

The conditions at which pump flow blockage occurs shall be determined experimentally. 

The pump hydraulic impedance shall be evaluated as an input to POGO analysis. 

Bearing life shall be demonstrated by component tests. 

n.

o.

p.

q.

r.

s.

t.

38 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 u.

y.

z.

Bearing assembly conditions shall be established such that stress corrosion cracking is prevented. 

Barriers shall prevent contact between non‐compatible fluids. 

v.

w.  Dynamic seal package life shall be demonstrated by component tests. x.

The dynamic stability of the axial balancing system shall be analysed and verified experimentally for the conditions of the extreme envelope and the associated transients. 

The uncertainty in the axial loads of the active axial balancing system shall be analysed and reported in the definition file. 

The  design  of  turbopump  components  shall  consider  design  criteria applicable to the specific failure modes of these components. 

9.5.7

Control and monitoring systems

9.5.7.1  Overview

Control  systems  can  be  used  for  steady  operating  point  (looking  for  a  given chamber pressure or mixture ratio) or for transient sequence. 

Control systems can be passive or active and liquid propulsion system operated in an open or closed mode. 

Control systems rely on flow control system such as: 







Active  control  systems  use  information  given  by  monitoring  devices,  e.g. pressure sensor, rotational speed sensor, temperature sensor, in order to react on the status of the propulsion system. 

flow regulators, e.g. cavitating venturis; 

calibrated orifices or valves to introduce a pressure drop; 

specific damping devices. 

Stability

9.5.7.2

a.

b.

c.

d.

e.

f.

A stability analysis shall be made for the operating points of the extreme envelope of the liquid engine. 

The  analysis  specified  in  9.5.7.2a.  shall  be  performed  for  every  physical loop. 

For every loop, the stability margins shall be established. 

The damping ratio shall be less than ‐3 dB for the whole extreme envelope. The minimum stability margins shall be established by analysis. 

The  design  shall  ensure  that  when  the  control  system  is  operated, inadvertent couplings are not introduced: 

1.

2.

internally (pressure regulator and check valves); 

externally (e.g. tank pressurization system). 

39 ![Im0](images/Im0)

![Im0](images/Im0)

9.5.7.3  Control systems

a.

The value of the critical parameters for the equilibrium points, or values derived from these shall be compared with the values specified. 

ECSS‐E‐ST‐35‐03C 13 May 2011 NOTE   Mixture  ratio  is  an  example  of  value  derived from critical parameters. 

If  the  parameter  values,  or  derived  parameter  values,  differ  from  the specified values, the control system shall react to suppress this deviation. Actuator  commands  shall  be  generated  by  the  control  system  to  activate elements that reset the system parameters to their specified values. 

NOTE 

Servo  valves  and  flow  control  devices  are example of elements to be activated. 

An analysis shall be made to establish the 

1.

type of monitoring devices needed, 

2.

location of the monitoring devices, 

3.

type of passive or active control devices to use, 

4.

location of the control devices, and 

5.

type  of  activation  for  active  control  devices,  e.g.  hydraulic, pneumatic, electric. 

Passive control devices shall be used if the only requirement is to ensure stable equilibrium points with a given stability margins. 

Active control shall be implemented if the following apply: 

1.

It follows from the system requirements. 

NOTE 

Example  of  system  requirements:  thrust  profile, performance optimization, and safety. 

2.

3.

The start‐up or shutdown sequence, or the thrust modulation cannot be performed without a closed loop control system. 

It follows from the functional constraints. 

NOTE 

Example  of  functional  constraints:  limitation  of hot gas temperatures. 

The engine control system shall be developed and qualified together with the engine. 

The environment in which the control equipment on the engine functions shall be determined. 

NOTE 

Example of environment: temperature, vibration, shocks, humidity. 

If  closed  loop  systems  are  used,  the  sensors  shall  be  characterized  and validated. 

b.

c.

d.

e.

f.

g.

h.

i.

40 ECSS‐E‐ST‐35‐03C 13 May 2011 9.5.8

Auxiliary functions supplied by the stage

9.5.8.1  Overview

On liquid engine, components and interfaces can be heated or cooled and lines flushed to remove any remainders of propellants, and to ensure that the lines are dry.  Electric  heaters  or  gas  flows  can  be  used  for  heating,  and  cooling  and flushing  can  be  done  using  fluid  flows.  On  the  launch  pad,  these  services  are provided by the GSE (see clause 10). 

Electrical

9.5.8.2

a.

The  electrical  functions  to  be  supplied  for  the  operation  of  the  liquid propulsion system shall be identified and reported in the design definition file, as defined in the ECSS‐E‐ST‐10 Annex G DRD. 

NOTE 

For  example,  heating,  valve  operation,  actuator operation, 

transducers,  control  system,  and ignition. 

b.

c.

An electrical energy and power budget shall be made for the autonomous operation of the stage according to the extreme envelope. 

A margin for 9.5.8.2b shall be established and specified. 

9.5.8.3  Gases

a.

The  heating,  cooling,  purging  or  venting  operations  to  be  performed  for the operation of the liquid propulsion system shall be identified. 

NOTE 

For  example,  purging  of 

injectors,  coolant channels,  pipes,  lines  and  combustion  chamber, heating  or  cooling  of  components,  and  the environment of the engine or propulsion system. 

b.

c.

d.

e.

The  components  to  be  dried,  de‐iced  and  cleaned  of  particles  and remainders of propellants or combustion products shall be identified. Accounting  for  the  elements  identified  in  accordance  with  9.5.8.3a.  and 9.5.8.3b.,  the  amount  of  gas  and  the  type  of  gas  to  be  used  during  the autonomous  operation  of  the  stage  shall  be  identified  according  to  the extreme envelope. 

A  margin  shall  be  established  in  order  to  guarantee  that  the  operations identified in 9.5.8.3a. can be performed. 

The  gas  storage  for  stage  support  may  be  combined  with  other,  already present, gas storage devices. 

41 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 9.5.9

Components

9.5.9.1  General

a.

Standardized environment loads for components shall be applied. 

NOTE 1  Acceleration 

spectrum 

is  an  example  of standardized environment load. 

NOTE 2  Standardized  environment  loads  are  given  by  a general specification at launch vehicle level. 

b.

If  the  operational  loads  are  higher  than  the  standardized  environment loads,  complementary  qualification  linked  to  these  overloads  shall  be carried out. 

NOTE 1  Standardized  environment  loads  are  defined  as acceleration spectrum, environmental conditions to be applied whatever the location and the type of component for a given launch vehicle. 

NOTE 2  The operational loads are the loads derived from a mechanical analytical model of the propulsion system and from test results as available. 

c.

Component  functional  requirements  shall  be  verified  by  tests  under environmental loads. 

9.5.9.2

Valves

9.5.9.2.1  Overview

The functions of a valve are: 





to isolate a fluid volume or to admit fluid into a volume; 

to control a fluid flow rate. 

9.5.9.2.2  General

a.

The  valve  functional  characteristics  shall  be  established  over  the  entire extreme envelope. 

b.

c.

NOTE 

Example  of  functional  characteristics:  pressure drop, response times. 

The  valve 

life  requirements  shall 

development tests and in service needs. 

include  additional  cycles for NOTE 

Example  of  service  needs  are  leak  tests,  ground control 

liquid propulsion system and launch vehicle level. 

subsystem, 

operation 

at 

A “normally open”, “normally closed” or bi‐stable valve shall be selected according to the operational and safety analyses and the liquid propulsion system requirements. 

NOTE 

Valves that provide the function to shut‐off a line can  be  obtained 

in  a  “normally  open”  or “normally closed” configuration. In the “normal” 42 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 condition  no  power  is  applied  to  the  activation system. A bi‐stable valve is a valve that remains in  its  position  (open‐closed)  after  the  power  to the activation system is switched off. 

9.5.9.3

Pressure regulator

9.5.9.3.1  Overview

The pressure regulator function is to control the downstream static pressure to a prescribed level. 

There are two types of pressure regulators: 



the  mechanical  regulator  that  balances  the  pressure  forces  with  (an adjustable) spring‐like load; 

the electronic pressure regulator that consists of a valve that can be opened and closed if the downstream pressure exceeds preset limits. 



A pressure regulator usually opens at a pressure that is somewhat lower than the prescribed  downstream  pressure  and  closes  at  a  pressure  that  is  somewhat higher than the prescribed downstream pressure. The latter is called the “lock‐up” pressure. 

9.5.9.3.2  General

a.

The pressure regulator functional characteristics shall be established over the entire extreme envelope. 

NOTE 

For  example  downstream  pressure  versus  mass flow rate curve. 

b.

The  pressure  regulator  life  requirements  shall  include  additional  life duration for development tests and in service needs. 

NOTE 

Example  of  service  needs  are  leak  tests,  ground control 

liquid propulsion system and launch vehicle level. 

subsystem, 

operation 

at 

9.5.9.4  Ground board coupling devices

9.5.9.4.1  Overview

Ground‐board coupling device function is to provide the interface between the launcher  and  the  GSE  for  fluid  and  power  supply,  monitoring  and  command and, if necessary, for draining the launcher. 

NOTE 

For ground board coupling devices, refer to ISO 15389:2001. 

9.5.9.4.2  General

a.

The fluid valves used in the ground‐board decoupling devices shall be of the “normally closed” type. 

43 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 9.5.9.5  Calibrating orifices

9.5.9.5.1  Overview

The functions of calibrating orifices can be: 





to control the mass flow rate, 

to  decouple  upstream  conditions  from  fluctuations  in  downstream conditions. 

There are several types of calibrating orifices, e.g.: 









cavitating venturi for liquids; 

venturi for gas; 

calibrating orifice for liquid; 

sonic orifice for gases. 

9.5.9.5.2  General

a.

The  functional  characteristic  and  the  flow  stability  of  the  calibrating orifices  shall  be  verified  either  by  individual  test  or  liquid  propulsion system test. 

9.5.9.6  Gimbal joint

9.5.9.6.1  Overview

The function of the gimbal joint is to orient the engine with respect to the launch vehicle in order to perform TVC. 

The gimbal joint connects the engine to the stage. 

9.5.9.6.2  General

a.

The gimbal joint friction torque characteristics shall be established over the entire  extreme  envelope  of  thrust,  temperature  and  environmental pressure including manufacturing tolerances. 

Clearance  variation  shall  be  studied  over  the  whole  life  of  the  engine including  operating and non‐operating  engine  conditions,  environmental conditions and manufacturing tolerances. 

b.

b.

c.

Piping

9.5.9.7

a.

It shall be verified that no cavitation occurs due to high flow velocities in piping. 

The thermal insulation of LH2 and LHe cryogenic lines shall be designed in such a way that cryo‐pumping is prevented. 

NOTE 

For  example  bonding  of  the  insulation  to  the piping, double insulation with ventilation. 

The  non  uniformity  of  the  flow 

introduced  by  elbows  shall  be characterized and reported in the design definition file, as defined in the ECSS‐E‐ST‐10 Annex G DRD. 

44 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 NOTE 

This  non  uniformity  is  used  by  downstream components. 

d.

Flow fluctuation induced by bellows shall be avoided. 

9.5.9.8

POGO suppression device

9.5.9.8.1  Overview

The function of the POGO suppression device is to damp coupled pressure and mass flow fluctuations in the propellant feed line. 

9.5.9.8.2  General

a.

The  functioning  of  the  POGO  suppression  device  shall  be  verified experimentally at stage level. 

It shall be verified that the POGO suppression device does not adversely affect the functioning of the propulsion system. 

b.

NOTE 

For example gas ingestion into the feed line. 

- 9.6  Mechanical design

a.

b.

c.

Requirements  9.6b  to  9.6w  shall  apply  to  all  the  subsystem  and components of a propulsion system. 

ECSS‐E‐ST‐32‐02  (Structural  design  and  verification  of  pressurized hardware) and ECSS‐E‐ST‐32‐01 (Fracture control) shall not be applicable to the following liquid propulsion system components: 

1.

2.

3.

4.

5.

6.

7.

A  failure  mode  analysis  of  the  mechanical  failure  modes  of  a  liquid propulsion system shall be performed prior to completion of the detailed design and presented prior to the PDR and reported both in the FMECA, as  defined  in  the  ECSS‐Q‐ST‐30‐02  Annex  A  DRD,  and  the  design justification file, as defined in the ECSS‐E‐ST‐10 Annex K DRD. 

combustion chamber 

gas generator 

pre burner 

turbopump 

nozzle extension 

igniter 

mechanisms 

NOTE 

from  elastic  behaviour 

The major failure modes are: 

  Departure 

yielding) 

  Rupture 



  Progressive deformation, ratcheting 

Instability, plastic or elastic instability 

(gross 45 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011   Creep and relaxation 

  Fatigue ‐ crack initiation ‐ crack propagation 

  Excessive  deformation  leading  to  a  loss  of Serviceability 

  Wear and tribological damage 

  Ageing 

  Oxydation  for  material  sensitive  to  chemical deterioration with oxygen 

d.

The  propulsion  system  mechanical  design  shall  include  at  least  the following environmental aspects: 

1.

2.

3.

4.

5.

6.

pressure, 

temperature, 

vibration levels, 

humidity, 

corrosive environment, 

vacuum. 

e.  Minimum material properties for yield strength, ultimate tensile strength and  rupture  elongation,  defined  as  values  with  99  %  probability  to  be exceeded at 90 % confidence level, shall be used for strength justification i.e. departure from elastic behaviour (yielding), rupture, instability (plastic or elastic). 

Local yielding shall not be allowed unless all the following conditions are met: 

1.

2.

the material is ductile; 

no  detrimental  deformations  that  adversely  affect  the  component system function are present; 

the service life requirements are met. 

f.

3.

NOTE 1  Ductile material are defined on the basis of their notch sensitivity when performing a tensile test: Fnotch  >  or  equal  to  Fsmooth,  Fnotch  and Fsmooth being respectively the rupture load for a notched and a smooth tensile specimen of same minimum cross section. 

NOTE 2  For  pressure  vessel  submitted  to  a  temperature gradient across their wall ( for instance the wall of  the  regenerative  circuit  of  a  combustion chamber  or  the  wall  of  a  gas  generator  )  and made of a ductile material, the part of the stress due to the thermal gradient can be excluded from the  yield  margin  verification.  In  this  case  the justification is based on a life verification which includes  creep  and  ratcheting 

(progressive deformation). 

46 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 As  part  of  life  justification  of  a  propulsion  system,  the  absence  of  crack initiation shall be demonstrated by performing fatigue analysis. 

The  nominal  life  shall  be  established  with  the  internal  loads  which  are taken at the edge of the operational domain. 

The extreme envelope life shall be established with the extreme envelope internal loads. 

Crack propagation analysis shall be used in the following cases: 

1.

The  manufacturing  process  leads  to  the  presence  of  a  significant number of flaws. 

NOTE 

Example  of  manufacturing  process  affected  by the presence of a significant number of flaws are welds and castings. 

2.

The structure is submitted to loads which cannot be reproduced in ground tests. 

3.  Major parts of turbopump rotors. 

For cases identified in 9.6j ECSS‐E‐ST‐32‐01 shall apply. 

For parts defined in 9.6b safety factors used in the design process shall be listed in the propulsion system technical specification. 

For  propulsion  system  parts  other  than  parts  defined  in  9.6b  the  safety factors specified in ECSS‐E‐ST‐32‐10 shall be applied. 

For margin policy ECSS‐E‐ST‐10 shall apply. 

Project margins shall be accompanied by an action plan showing how they are reduced along the development. 

NOTE 

The  reduction  of  project  margins  relies  on  an enhanced  material  characterization,  component tests,  analysis  of  engine 

test examination. 

tests,  post 

A qualification by test shall be performed for the strength demonstration of critical parts. 

NOTE 

There is no detrimental yielding at the maximum design  load  multiplied  by  the  yield  coefficient and  no  failure  at  the  maximum  design  load multiplied by the ultimate safety coefficient, with a  temperature  correction,  a  material  correction and geometry correction. 

Dimensioning load cases shall be established by using a selection process of  all  load  case  combinations  during  the  whole  life  of  the  propulsion system. 

Internal  loads  used  for  strength  analysis,  designated  as  limit  load  in conformance with ECSS‐E‐ST‐32, shall be taken at the edge of the extreme envelope. 

Internal loads shall be derived from steady state and transient functional analysis of the propulsion system. 

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

s.

47 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 t.

u.

v.

External loads shall be derived from launch vehicle and stage specification using analytical model of the engine and propulsive system. 

Both  internal  and  external  load  cases  shall  be  used  when  establishing dimensioning load cases. 

It  shall  be  verified  that  all  functional  clearance  requirements  are  met  for the extreme envelope. 

w.  All pressurized connections and interfaces shall be designed such that they remain leak tight for all identified load cases. 

48 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Ground support equipmenta.

b.

c.

ECSS‐ST‐35 clause 4.6 shall apply. 

Relief  valves  shall  be  installed  on  all  pressurized  vessels  and  major portions of the lines 

The  GSE  design,  functioning  and  procedures  shall  ensure  that  fluids  are delivered to the launcher or spacecraft according to their specifications. NOTE 

of 

Examples 

contamination 

temperature. 

fluid 

level, 

specifications 

flow,  pressure 

are and 49 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Materialsa.

b.

c.

d.

e.

f.

g.

h.

ECSS‐Q‐ST‐70 clause 5 shall apply. 

The  material  characteristics  shall  be  determined  on  material  samples obtained by the same manufacturing process as the part themselves. 

NOTE   During the early phase of the development when the number of material test data is not sufficient, the use of a statistical distribution applicable to a similar  class  of  material  is  allowed  in  order  to define minimum properties. 

Hydrogen  embrittlement  effect  on  material  characteristic  shall  be determined for parts exposed to hydrogen rich gases. 

The possible adverse effect of vacuum shall be evaluated. 

NOTE 

example, 

For 

degassing. 

tribological 

deterioration, Risk of wear and tribological damage shall be considered when selecting material. 

Compatibility with oxidizer shall be examined with respect to the material potential to ignite. 

The material selection shall be compatible with the contained fluids. 

The material selection shall consider the possible galvanic effect between dissimilar materials. 

NOTE 

For  minimum  material 

“Mechanical design” 9.6e. 

characteristic 

see 50 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Verificationa.

b.

For verification ECSS‐E‐ST‐35 clause 4.8 shall apply. 

The qualification process of the propulsion system shall include testing in the following conditions: 

1.

four  times  the  nominal  life  (i.e.  four  main  life  cycles  in  term  of number of cycles and cumulated time) within the flight domain, at least one time the main life cycle within the extreme envelope. 2.

51 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Production and manufacturinga.

b.

c.

d.

e.

The  functional  parameters  used  to  ensure  the  reproducibility  of  the hardware shall be defined and compared to acceptance criteria. 

NOTE 

Examples  of  such  functional  parameters  are vibration  levels  for  turbopumps  and  ignition time. 

All  components  and  elements  that  are  sensitive  to  pollution  and contamination, and all components and elements that can create pollution and  contamination  in  sensitive  elements  shall  be  cleaned  purged  and dried. 

It shall be demonstrated that the components and elements that come into contact with reactive chemicals are cleaned. 

NOTE 

For example oxygen. 

After cleaning, purging and drying, the components and elements shall be sealed to avoid pollution and contamination. 

The adverse effect of storage environmental conditions shall be analysed. NOTE 

For example, creep, corrosion, oxidation. 

52 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 In-service- 14.1  General

a.

Leakage criteria and leakage budget shall be defined. 

NOTE   A  leakage  budget  is  defined  as  an  allowable leakage flow for each subsystem. 

b.

The liquid propulsion system shall be instrumented in such a way that in the case of a launch‐abort, the cause of the launch‐abort can be identified. - 14.2  Operation

a.

b.

c.

d.

the propulsion system reset to a safe condition; 

cryogenic propulsion systems drained and flushed. 

In case of launch abort, the following shall be performed: 

1.

2.

In  case  of  launch  abort,  procedures  shall  be  prepared,  qualified  and implemented to reset the propulsion system to a safe condition. 

The number of launch aborts the propulsion system can undergo shall be specified. 

After  having  performed  its  operational  mission,  each  propulsion  system shall be drained of the remaining propellants (passivation) in such a way that this does not lead to explosion or other hazardous situations. 

53 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 Deliverablesa.

For deliverables ECSS‐E‐ST‐35 requirement 4.11a. shall apply. 

54 ![Im0](images/Im0)

ECSS‐E‐ST‐35‐03C 13 May 2011 BibliographyECSS‐S‐ST‐00 

ECSS‐E‐ST‐33‐11 

ECSS‐M‐ST‐10 

ECSS‐Q‐ST‐20 

 

ECSS system – Description, implementation and general requirements 

Space engineering – Explosive systems and devices Space  project  management  ‐ Project   planning  and implementation 

Space project assurance – Quality assurance 55 ![Im0](images/Im0)

