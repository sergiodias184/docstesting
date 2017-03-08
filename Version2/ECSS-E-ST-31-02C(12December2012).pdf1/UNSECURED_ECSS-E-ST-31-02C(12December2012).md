ECSS-E-ST-31-02C12 December 2012Space engineering

Two-phase heat transport

equipment

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012- Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry

- associations for the purpose of developing and maintaining common standards. Requirements in this

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be

- applied where they are effective, and for the structures and methods to evolve as necessary without

- rewriting the standards.

- This  Standard  has  been  prepared  by  the  ECSS-E-ST-31-02C  Working  Group,  reviewed  by  the  ECSS

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

- Published by:

- Copyright:

ESA Requirements and Standards Division

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2012© by the European Space Agency for the members of ECSS

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS-E-ST-31-02C 12 December 2012</td>
		<td>First issue</td>
	</tr>
</table>

ECSS-E-ST-31-02C12 December 2012Table of contents- Change log ................................................................................................................. 3

- Introduction ................................................................................................................ 7

- 1 Scope ....................................................................................................................... 8

- 2 Normative references ............................................................................................. 9

- 3 Terms, definitions and abbreviated terms .......................................................... 10

- 3.1  Terms defined in other standards ........................................................................... 10

- 3.2  Terms specific to the present standard ................................................................... 10

- 3.3  Abbreviated terms................................................................................................... 14

- 4 TPHTE qualification principles ............................................................................ 15

- 4.1  TPHTE categorization ............................................................................................. 15

- 4.2

Involved organizations ............................................................................................ 15- 4.3  Generic requirements in this standard .................................................................... 16

- 4.4  Processes, number of qualification units ................................................................. 17

- 4.5  Thermal and mechanical qualification ..................................................................... 17

4.5.1

Temperature range ................................................................................... 174.5.2  Mechanical qualification ............................................................................ 19- 5 Requirements ........................................................................................................ 21

- 5.1  Technical requirements specification (TS) .............................................................. 21

5.1.1  General ..................................................................................................... 215.1.2  Requirements to the TS ............................................................................ 215.1.3  Requirements for formulating technical requirements ................................ 22- 5.2  Materials, parts and processes ............................................................................... 23

- 5.3  General qualification requirements ......................................................................... 23

5.3.1  Qualification process ................................................................................. 23Supporting infrastructure – Tools and test equipment ............................... 235.3.2

- 5.4  Qualification process selection ............................................................................... 23

- 5.5  Qualification stage .................................................................................................. 25

5.5.1  General ..................................................................................................... 25![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 20125.5.2  Quality audits ............................................................................................ 265.5.3  Qualification methods ................................................................................ 265.5.4

Full and delta qualification programme ...................................................... 28Performance requirements ........................................................................ 285.5.5

- 5.6  Qualification test programme .................................................................................. 30

5.6.1  Number of qualification units ..................................................................... 30Test sequence .......................................................................................... 315.6.2

Test requirements ...................................................................................... 345.6.3

5.6.4

Physical properties measurement ............................................................. 37Proof pressure test .................................................................................... 385.6.5

Pressure cycle test .................................................................................... 385.6.6

5.6.7

Burst pressure test .................................................................................... 38Leak test ................................................................................................... 395.6.8

5.6.9

Thermal performance test ......................................................................... 405.6.10  Mechanical tests ....................................................................................... 425.6.11  Thermal cycle test ..................................................................................... 445.6.12  Aging and life tests .................................................................................... 445.6.13  Gas plug test ............................................................................................. 455.6.14  Reduced thermal performance test ............................................................. 45- 5.7  Operating procedures ............................................................................................. 46

- 5.8  Storage ................................................................................................................... 46

- 5.9  Documentation ....................................................................................................... 46

5.9.1  Documentation summary .......................................................................... 465.9.2

Specific documentation requirements........................................................ 46- Annex A (normative) Technical requirements specification (TS) – DRD ............ 49

- Annex B (normative) Verification plan (VP) – DRD ............................................... 52

- Annex C (normative) Review-of-design report (RRPT) - DRD .............................. 55

- Annex D (normative) Inspection report (IRPT) – DRD .......................................... 57

- Annex E (normative) Test specification (TSPE) – DRD ........................................ 59

- Annex F (normative) Test procedure (TPRO) – DRD ............................................ 62

- Annex G (normative) Test report (TRPT) – DRD ................................................... 65

- Annex H (normative) Verification report (VRPT) – DRD ....................................... 67

- Bibliography ............................................................................................................. 69

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012- Figures

- Figure 3-1: Tilt definition for HP ............................................................................................ 13

- Figure 3-2: Tilt definition for LHP .......................................................................................... 13

- Figure 4-1: Categories of TPHTE (two-phase heat transport equipment) ............................. 16

- Figure 4-2: Figure-of-merit (G) for some TPHTE fluids ......................................................... 18

- Figure 4-3: Definition of temperature and performance ranges for a HP ............................... 19

- Figure 5-1: Selection of qualification process ....................................................................... 25

- Figure 5-2: Qualification test sequence for HP ..................................................................... 32

- Figure 5-3: Qualification test sequence for CDL ................................................................... 33

- Tables

- Table 5-1: Categories of two-phase heat transport equipment according to heritage

(derived from ECSS-E-ST-10-02C, Table 5-1) ................................................... 24- Table 5-2: Allowable tolerances ............................................................................................ 35

- Table 5-3: Measurement accuracy ....................................................................................... 37

- Table 5-4: Equipment resonance search test levels ............................................................. 43

- Table 5-5: Sinusoidal vibration qualification test levels ......................................................... 43

- Table 5-6: Random vibration qualification test levels ............................................................ 44

- Table 5-7: TPHTE documentation ........................................................................................ 48

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012IntroductionThis  Standard  is  based  on  ESA  PSS-49,  Issue  2  “Heat  pipe  qualificationrequirements”,  written  1983,  when  the  need  for  heat  pipes  in  several  ESAprojects had been identified. At that time a number of European developmentactivities were initiated to provide qualified heat pipes for these programmes,which culminated in a first heat pipe application on a European spacecraft in1981  (MARECS,  BR-200,  ESA  Achievements  -  More  Than  Thirty  Years  ofPioneering Space Activity, ESA November 30, 2001), followed by a first majorapplication on a European communication satellite in 1987 (TV-SAT 1, GermanCommunication Satellites).

ESA PSS-49 was published at a time, when knowledge of heat pipe technologystarted  to  evolve  from  work  of  a  few  laboratories  in  Europe  (IKE,  UniversityStuttgart,  EURATOM  Research  Centre,  Ispra).  Several  wick  designs,  materialcombinations  and  heat  carrier  fluids  were  investigated  and  many  processrelated issues remained to be solved. From today’s view point the qualificationrequirements of ESA PSS-49 appear therefore very detailed, exhaustive and insome cases disproportionate in an effort to cover any not yet fully understoodphenomena. As examples  the specified number of  qualification units (14), thenumber of required thermal cycles (800) and the extensive  mechanical testing(50 g constant acceleration, high level sine and random vibration) can be cited.The present Standard takes advantage of valid requirements of ESA PSS-49, butreflects  at  the  same  time  today’s  advanced  knowledge  of  two-phase  coolingtechnology,  which  can  be  found  with  European  manufacturers.  This  includesexperience to select proven material combinations, reliable wick and containerdesigns,  to  apply  well-established  manufacturing  and  testing  processes,  anddevelop  reliable  analysis  tools  to  predict  in-orbit  performance  of  flighthardware.  The  experience  is  also  based  on  numerous  successful  two-phasecooling system application in European spacecraft over the last 20 years.

Besides stream-lining the ESA PSS-49, to arrive at today’s accepted set of heatpipe  qualification  requirements,  the  following  features  have  also  been  takeninto account:

Inclusion of qualification requirements for two-phase loops (CPL, LHP),•

•  Reference to applicable requirements in other ECSS documents,

•  Formatting  to  recent  ECSS  template  in  order  to  produce  a  document,which  can  be  used  in  business  agreements  between  customer  andsupplier.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Scopetransportationtwo-phase  heat

This  standard  defines  requirements  for

equipment (TPHTE), for use in spacecraft thermal control.

This standard is applicable to new hardware qualification activities.

Requirements for mechanical pump driven loops (MPDL) are not included inthe present version of this Standard.

This standard includes definitions, requirements and DRDs from ECSS-E-ST-10-02,  ECSS-E-ST-10-03,  and  ECSS-E-ST-10-06  applicable  to  TPHTE  qualification.Therefore,  these  three  standards  are  not  applicable  to  the  qualification  ofTPHTE.

This standard also includes definitions and part of the requirements of ECSS-E-ST-32-02  applicable  to  TPHTE  qualification.  ECSS-E-ST-32-02  is  thereforeapplicable to the qualification of TPHTE.

This standard does not include requirements for acceptance of TPHTE.

This standard may be tailored for the specific characteristic and constrains of aspace project in conformance with ECSS-S-ST-00.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Normative referencesThe  following  normative  documents  contain  provisions  which,  throughreference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  datedreferences, subsequent amendments to, or revision of any of these publicationsdo not apply. However, parties to agreements based on this ECSS Standard areencouraged to investigate the possibility of applying the more recent editions ofthe  normative  documents  indicated  below.  For  undated  references,  the  latestedition of the publication referred to applies.

ECSS-S-ST-00-01

ECSS-E-ST-31

ECSS-E-ST-32

ECSS-E-ST-32-01

ECSS-E-ST-32-02

ECSS-Q-ST-70

EN 9100:2009

ECSS system - Glossary of terms

Space engineering - Thermal control general

requirements

Space engineering - Structural general requirementsSpace engineering- Fracture control

Space engineering - Structural design and verificationof pressurized hardware

Space product assurance - Materials, mechanical partsand processes

Aerospace series - Quality management systems -

Requirements for Aviation, Space and Defense

Organizations

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Terms, definitions and abbreviated terms- 3.1  Terms defined in other standards

For the purpose of this Standard, the terms and definitions from ECSS-E-ST-00-01apply.

For  the  purpose  of  this  standard,  the  following  terms  and  definitions  fromECSS-E-ST-10-02 apply:

analysis

qualification stage

review-of-design (ROD)

For  the  purpose  of  this  standard,  the  following  terms  and  definitions  fromECSS-E-ST-32-02 apply:

burst pressure

differential pressure

external pressure

internal pressure

leak-before-burst (LBB)

pressure vessel (PV)

pressurized hardware (PH)

proof test

- 3.2  Terms specific to the present standard

capillary driven loop (CDL)

3.2.1

TPL,  in  which  fluid  circulation  is  accomplished  by  capillary  action  (capillarypump)

NOTE

See TPL definition in 3.2.21.

capillary pumped loop (CPL)

3.2.2

CDL  with  the  fluid  reservoir  separated  from  the  evaporator  and  without  acapillary link to the evaporator

NOTE

See CDL definition in 3.2.1.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012constant conductance heat pipe (CCHP)

3.2.3

heat pipe with a fixed thermal conductance between evaporator and condenserat a given saturation temperature

NOTE

See heat pipe definition in 3.2.7.

dry-out

3.2.4

depletion  of  liquid  in  the  evaporator  section  at  high  heat  input  when  thecapillary pressure gain becomes lower than the pressure drop in the circulatingfluid

effective length

3.2.5

heat  pipe  length  between  middle  of  evaporator  and  middle  of  condenser  forconfigurations with one evaporator and one condenser only

NOTE  Used  to  determine  the  heat  pipe  transport

capability (see 3.2.10).

exposure temperature range

3.2.6

maximum temperature range to which a TPHTE is exposed during its productlife cycle and which is relevant for thermo-mechanical qualification

NOTE 1  The internal pressure at the maximum temperature

of  this  range  defines  the  MDP  for  the  pressure

vessel qualification of a TPHTE.

NOTE 2  The  extreme  temperatures  of  this  range  can  be

below freezing and / or above critical temperatures

of the working fluid.

In other technical domains, this temperature range

is

temperature

range (see clause 4 for additional explanation).

typically  called  non-operating

NOTE 3

heat pipe (HP)

3.2.7

TPHTE  consisting  of  a  single  container  with  liquid  and  vapour  passagesarranged in such a way that the two fluid phases move in counter flow

NOTE 1  See TPHTE definition in 3.2.20.

NOTE 2  The capillary structure in a heat pipe extends over

the entire container length.

heat pipe diode (HPD)

3.2.8

heat pipe, which transports heat based on evaporation and condensation onlyin one direction

NOTE

See heat pipe definition in 3.2.7.

loop heat pipe (LHP)

3.2.9

CDL with the fluid reservoir as integral part of the evaporator

NOTE 1  See CDL definition in 3.2.1.

NOTE 2  The reservoir can be separated, but has a capillary

link to the evaporator.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 20123.2.10  heat transport capability

maximum  amount  of  heat,  which  can  be  transported  in  a  TPHTE  from  theevaporator to the condenser

NOTE

For  heat  pipes  it  is  the  maximum  heat  load

expressed in [Wm] (transported heat x effective

length).

3.2.11  maximum design pressure (MDP)

maximum allowed pressure inside a TPHTE during product life cycle

NOTE  The product life cycle starts after acceptance of

the product for flight.

3.2.12  mechanical pump driven loop (MPDL)

TPL, in which fluid circulation is accomplished by a mechanical pump

NOTE

See TPL definitions in 3.2.21.

3.2.13  product life cycle

product  life  starting  from  the  delivery  of  the  TPHTE  hardware  until  end  ofservice live

reflux mode

3.2.14

operational  mode,  where  the  liquid  is  returned  from  the  condenser  to  theevaporator by gravitational forces and not by capillary forces

3.2.15  start-up

operational  phase  starting  with  initial  supply  of  heat  to  the  evaporator  untilnominal operational conditions of the device are established

3.2.16  sub-cooling

temperature  difference  between  average  CDL  reservoir  temperature  and  thetemperature of the liquid line at the inlet to the reservoir

NOTE  The  average  CDL

temperature

represents the saturation temperature inside the

reservoir.

reservoir

thermal performance temperature range

3.2.17

temperature range for which a TPHTE is thermally qualified

NOTE

In the thermal performance temperature range

a thermal performance map exists.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012tilt for HP

3.2.18

height  of  the  evaporator  (highest  point)  above  the  condenser  (lowest  point)during ground testing

NOTE  This definition is valid for a configuration with

one  evaporator  and  one  condenser  (see  Figure

3-1).

condenser

Figure 3-1: Tilt definition for HP

evaporator

tilt for LHP

3.2.19

height  of  the  evaporator  (highest  point)  above  the  reservoir  (lowest  point)during ground testing

NOTE

See Figure 3-2.

Figure 3-2: Tilt definition for LHP

two-phase heat transport equipment (TPHTE)

3.2.20

hermetically closed system filled with a working fluid and transporting thermalenergy by a continuous evaporation/condensation process using the latent heatof the fluid

NOTE 1  A  fluid  evaporates

in

input  zone

(evaporator)  and  condenses  in  the  heat  output

zone (condenser).

the  heat

NOTE 2  This is in contrast to a single-phase loop where the

sensible  heat  of  a  liquid  is  transported  (a  liquid

heats up in the heat input zone and cools down in

the heat output zone).

two-phase loop (TPL)

3.2.21

TPHTE with physically separated vapour and liquid transport lines forming aclosed loop

NOTE

See TPHTE definition in 3.2.20.

![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

ECSS-E-ST-31-02C12 December 20123.2.22  variable conductance heat pipe (VCHP)

heat pipe with an additional non-condensable gas reservoir allowing a variablethermal conductance between evaporator and condenser

NOTE 1  See heat pipe definition in 3.2.7.

NOTE 2  The  variation in thermal conductance is generally

accomplished  by  regulating  the  volume  of  a  non-

condensable gas plug reaching into the condenser

zone, which in turn varies the effective condenser

length.

NOTE 3  The variation of the gas volume can be performed

by active or passive means.

- 3.3  Abbreviated terms

The following abbreviations are defined and used within this standard:

Abbreviation

CCHP

CDL

CPL

CTE

DRD

HP

HPD

LBB

LHP

MDP

MPDL

MSPE

NDI

PH

ROD

SPE

TCS

TPHTE

TPL

TS

VCHP

VP

Meaning

constant conductance heat pipe

capillary driven loop

capillary pumped loop

coefficient of thermal expansion

document requirements definition

heat pipe

heat pipe diode

leak before burst

loop heat pipe

maximum design pressure

mechanical pump driven loop

metallic special pressurized equipment

non-destructive inspection

pressurized hardware

review-of-design

special pressurized equipment

thermal control (sub)system

two-phase heat transport equipment

two-phase loop

technical requirement specification

variable conductance heat pipe

verification plan

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012TPHTE qualification principles- 4.1  TPHTE categorization

TPHTE  are  considered  special  pressurized  hardware,  as  defined  in  clause  3.Requirements of ECSS-E-ST-32-02 are included in this Standard for this reason.The  TPHTE  are  categorized  in  Figure  4-1  according  to  their  design  andfunctional principle.

Heat  pipes  consist  of  a  single  container  with  a  capillary  structure  extendingover  the  entire  container  length.  Liquid  and  vapour  passages  are  arranged  insuch a way that the two fluid phases move in counter flow.

Capillary driven loops (CDL) have separate evaporator and condenser sections,which  are  connected  by  dedicated  vapour  and  liquid  tubing.  At  least  onecapillary structure is located in the evaporator section, which serves as capillarypump to circulate the fluid in a true loop configuration.

The mechanically pumped two-phase loop (MPDL) has a configuration, whichis similar to the CDL, except that the circulation of the fluid is accomplished bya mechanical pump.

NOTE  Requirements for MPDL are not included in the

present version of this Standard.

- 4.2

Involved organizations

The  qualification  process  of  TPHTE  is  generally  carried  out  by  a  specializedequipment manufacturer (called in this document “supplier”) and controlled bythe qualification authority, which is called in this document the “customer”.The qualification activity is embedded in the supplier’s product assurance andquality organization and in most cases the supplier's quality assurance plan hasbeen  established  and  approved  for  space  activities  independently  from  theTPHTE  qualification  process  specified  in  this  document.  It  is  the  task  of  thesupplier’s  PA  authority  to  introduce  /  approve  adequate  product  assuranceprovisions  at  his  subcontractor(s).  The  existence  of  an  approved  PA  Plan  isprecondition for commencing qualification activities.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Figure 4-1: Categories of TPHTE (two-phase heat transport equipment)

- 4.3  Generic requirements in this standard

The  present  document  provides  generic,  i.e.  not  project  specific  requirementsfor formal qualification of TPHTE. It is therefore important to select overall andenveloping  qualification  requirements  in  order  to  support  a  maximum  ofspacecraft application without the need for delta qualification.

![Im0](images/Im0)

![Im1](images/Im1)

![Im0](images/Im0)

- 4.4  Processes, number of qualification units

ECSS-E-ST-31-02C12 December 2012The qualification of TPHTE is based on qualified manufacturing processes (e.g.cleaning, surface treatment, welding and leak testing) and covers in general thefollowing areas:

•

Performance over long operation time (compatibility between fluid andwall material, space radiation, leak tightness)

Mechanical performance (strength, pressurized hardware)

Thermal performance (e.g. heat transport capability, start-up behaviour,heat transfer coefficients)

•

•

In this context the number of TPHTE units to be produced for the qualificationprogram  are  evaluated  and  selected  by  the  supplier.  There  are  no  generalapplicable sources, which specify the minimum of units to be used to undergoidentical  qualification  testing  in  order  to  arrive  at  a  successful  qualifiedproduct.  The  question  to  be  answered  for  each  TPHTE  configuration  is:  Howmany  identical  units  need  to  be  built  and  tested  in  order  to  verify  thatproduction processes provide reproducible performance results.

The following are possible selection criteria:

•

•

•

Experience of the manufacturer in production of similar products,

Simplicity of the configuration,

TPHTE  design  features,  which  have  inherent  capability  for  goodrepeatability of the production processes (e.g. simple axial grooved heatpipes).

This  Standard  specifies  the  number  of  needed  units  submitted  to  thequalification  process  for  configurations,  which  are  currently  used  in  severalspacecraft  applications.  It  is  recommended  that  the  supplier  performs  theselection  for other  configurations  and  provide  argumentation  to  the  customerfor agreement of his choice.

Compared  to  full  qualification  of  a  new  product  the  number  of  units  can  bereduced for delta qualification of an existing but modified product.

- 4.5  Thermal and mechanical qualification

Temperature range

4.5.1

In contrast to most of electronic equipment the performance of a TPHTE varieswith its operating temperature, because properties of the used heat carrier aretemperature  dependent.  For  heat  pipes  as  an  example,  important  fluidproperties  can  be  grouped  into  a  figure-of-merit  (G),  which  is  the  product  ofsurface tension, heat of  vaporization and liquid density divided by the liquidviscosity (for more information see references in Bibliography). G is plotted forsome fluids over the temperature in Figure 4-2. The heat transport capability ofa capillary pumped loop is proportional to these curves.

ECSS-E-ST-31-02C12 December 2012Figure 4-2: Figure-of-merit (G) for some TPHTE fluids

Generally, the applicable temperature range of a TPHTE is subdivided into athermally and a mechanically relevant regime.

The  thermal  performance  temperature  range,  which  is  used  for  thermalqualification,  is  defined  within  the  theoretical  operating  temperature  range,confined by the freezing and the critical temperature of the used fluid. Lowerand upper temperature limits of the qualification range are selected in such away that a useful map of thermal performance data can be established. Withinthis  range  the  maximum  transport  capability  for  qualification  will  bedetermined.  For  a  specific  space  application  the  operating  temperature  range(within  the  thermal  performance  temperature  range)  and  the  maximumrequired heat transport capability are specified.

For thermo-mechanical qualification the temperature range is relevant, to whichthe  device  is  exposed  to  during  the  life  cycle.  In  most  cases  this  exposuretemperature  range  is  wider  than  the  above-mentioned  thermal  performancetemperature range. The minimum temperature of this range can be below thefreezing  temperature  of  the  used  heat  carrier  and  it  is  important  to  take  intoaccount possible damage caused by the freezing or thawing effects. The upperexposure  temperature  can  be  even  above  the  critical  temperature  of  the  heatcarrier. This temperature determines in general the maximum internal pressurefor design and qualification of the device.

![Im0](images/Im0)

![Im1](images/Im1)

![Im0](images/Im0)

The  mentioned  temperature  ranges  and  associated  heat  transport  capabilitiesare illustrated in Figure 4-3.

ECSS-E-ST-31-02C12 December 2012- Legend

Maximum transport capability for qualification

- Qmax,qual

- Qmax,acc

Maximum transport capability for acceptance (specified for a specific project)

- TF, TC

Freezing and critical temperature of a selected fluid

- T P, min, T P, max  Minimum and maximum performance temperature

- T Ac, min, T Ac, max  Minimum and maximum acceptance temperature (specified for a specific project)

- T P,min    T P,max  Performance temperature range

- T Ac,min    T Ac,max Acceptance temperature range (specified for a specific project)

Figure 4-3: Definition of temperature and performance ranges for a HP

4.5.2  Mechanical qualification

TPHTE  are  classified  as  pressurized  component  and  relevant  mechanicalrequirements  are  specified  in  ECSS-ST-E-32-02  and  are  applied  in  the  presentStandard for all TPHTE types.

For qualification of a TPHTE as pressurized component the main characteristicis the internal pressure, which varies in relation to the exposure temperature ofthe unit (temperature dependent saturation pressure of the heat carrier liquid).ECSS-ST-E-32-02 specifies qualification requirements for heat pipes (see figure4.12).  The  present  Standard  selects  qualification  requirements  for  TPHTE,which  have  seen  proof  pressure  tests  ≥  1,5  MDP.  Testing  is  the  preferredmethod rather than qualification by fracture control analysis.

![Im1](images/Im1)

ECSS-E-ST-31-02C12 December 2012Constant or static acceleration

Sine vibration

Random vibration

For  qualifying  a  TPHTE  with  respect  to  external  mechanical  environment  thefollowing mechanical tests are considered:

•

•

•

For  these  tests  the  qualification  unit  needs  to  be  rigidly  mounted  to  the  testequipment (vibration table). However, such mounting provisions can have onlyreduced similarity to real applications in spacecrafts and the meaningfulness ofsuch tests is, therefore, very often reason for discussion under experts. For heatpipes it is common understanding not to perform these tests on long heat pipeprofiles for the following reasons:

•

The length of the test heat pipe is adapted to the test equipment and istherefore shorter as in many realistic spacecraft applications.

The  application  of  heat  pipe  is  often  for  embedding  them  in  sandwichstructures. Mechanical loads for these applications are quite different ascan be simulated with a rigidly fixed single heat pipe profile.

Several  capillary  structures,  in  particular  axial  groove  heat  pipes,  arequite  insensitive  to  mechanical  loads  and  tests  as  suggested  in  existingprocedures can be unnecessary.

•

•

For many TPHTE  applications (in particular for devices with simple capillarystructures,  e.g.  axial  grooves)  the  formal  mechanical  qualification  can  betherefore performed with the first structural model on satellite level. In case therisk for such a late qualification is high, pre-qualification can be performed onunit or part level in particular for the following cases:

•

The TPHTE, in particular a heat pipe, has a capillary structure, which issensitive  towards  mechanical  loads,  e.g.  arterial  wick.  In  such  a  case  ashort piece of the heat pipe profile is selected for mechanical qualificationtesting (sine, random vibration).

An evaporator of a LHP or CPL can  be  separately tested (sine, randomvibration) to verify that mechanical requirements are met.

Equally this can be true for a two-phase loop condenser, in particular forconfigurations where the condenser tubing is embedded into a structuralpanel.

•

•

The  Standard  does  not  therefore  not  specify  at  which  model  level  vibrationtesting is to be performed. The supplier and customer are asked to agree on alogical qualification plan, which may include testing at higher than equipmentlevel.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012Requirements- 5.1  Technical requirements specification (TS)

5.1.1  General

a.

The  qualification  process  shall  be  based  on  a  technical  requirementsspecification, approved by the customer.

NOTE  Usually the technical specification evolves from

the  functional  requirements  of  the  customer

and  defines  the  technical  performances  for  the

proposed  solution  as  part  of  a  business

agreement.

b.

The  technical  requirements  specification  specified  in  5.1.1a  shall  bewritten in accordance with DRD in Annex A.

5.1.2

a.

2.

b.

c.

d.

e.

f.

Requirements to the TS

The specification shall be identifiable, referable and related to a TPHTEproduct.

The following entity shall be responsible for the TS:

1.

the supplier for a generic TPHTE specification, which is not relatedto a specific application;

the customer for a specific TPHTE specification, which is related toa specific application.

NOTE  A  delta  qualification  can  be  necessary,  if  the

generic  specification  does not  completely  meet

the requirements for a specific application.

Each technical requirement shall be separately stated.

Abbreviated terms used in requirements shall be defined in a dedicatedsection of the specification.

The technical requirements shall be consistent and not in conflict with theother requirements within the specification.

The  technical  requirements  shall  not  be

requirements contained in business agreement documents.

in  conflict  with  other![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012g.

h.

i.

The  specification  shall  be  complete  in  terms  of  applicable  technicalrequirements and reference to applicable documents.

The specification shall be under configuration management.

Quantity of units required for the qualification process shall be specifiedin the TS.

NOTE  TS exclude requirements such as cost, methods

of payment, time or place of delivery.

5.1.3

Requirements for formulating technical

requirements

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

k.

l.

m.

n.

Each technical requirement shall be described in quantifiable terms.

The technical requirements shall be unambiguous.

Each technical requirement shall be unique.

A unique identifier shall be assigned to each technical requirement.

Each technical requirement shall be separately stated.

A technical requirement shall be verifiable using one or more approvedverification methods.

The tolerance shall be specified for each parameter/variable.

NOTE  The  technical  requirement  tolerance  is  a  range

of  values  within  which  the  conformity  to  the

requirement is accepted.

Technical  requirements  should  be  stated  in  performance  or  “what-is-necessary” terms, as opposed to “how-to" perform a task, unless the exactsteps  in  performance  of  the  task  are  essential  to  ensure  the  properfunctioning of the product.

Technical  requirements  should  be  expressed  in  a  positive  way,  as  acomplete sentence (with a verb and a noun).

The  verbal  form  “shall”  shall  be  used  whenever  a  provision  is  arequirement.

The  verbal  form  “should”  shall  be  used  whenever  a  provision  is  arecommendation.

The  verbal  form  “may”  shall  be  used  whenever  a  provision  is  apermission.

The verbal form “can” shall be used to indicate possibility or capability.The  following  terms  shall  not  be  used  in  a  TS  requirement:  “and/or”,“etc”,  “goal”,  “shall  be  included  but  not  limited  to”,  “relevant”,“necessary”, “appropriate”, “as far as possible”, “optimize”, “minimize”,“maximize”,  “typical”,  “rapid”,  “user-friendly”,  “easy”,  “sufficient”,“enough”,  “suitable”,  “satisfactory”,  adequate”,  “quick”,  “first  rate”,“best possible”, “great”, “small”, “large”, and “state of the art”.

![Im0](images/Im0)

![Im0](images/Im0)

- 5.2  Materials, parts and processes

ECSS-E-ST-31-02C12 December 2012a.  Materials,  parts  and  processes  for  TPHTE  to  be  qualified  shall  bedocumented in the following lists (see Table 5-7):

1.

2.

3.

Declared materials list

Declared mechanical parts list

Declared processes list

- 5.3  General qualification requirements

5.3.1  Qualification process

a.

The qualification stage shall be completed before launch.

5.3.2

Supporting infrastructure – Tools and testequipment

a.

b.

c.

d.

e.

f.

Tools  to  be  used  to  support  the  qualification  process  shall  be  validatedfor their intended use.

The  validation  shall  be  performed  under  expected  environmentalconditions and operational constraints.

Compatibility  of  tools  and  test  equipment

qualification hardware shall be verified by test.

Calibration of laboratory equipment shall be verified prior to their use.Tools and test equipment that is modified and used in a new applicationshall be re-verified according to 5.3.2a to 5.3.2d.

Test  facilities,  tools  and  instrumentation  shall  be  designed  to  avoidadverse effects on the qualification objectives.

interfaces  with  flightNOTE  Examples  of  these  are:  Thermocouples,  strain

gauges,  heater  mounting,  cooling  devices,

support structures.

- 5.4  Qualification process selection

a.

b.

c.

The  scope  of  the  qualification  process  shall  be  adapted  to  thequalification heritage of the product.

For categorization of the heritage the product categories of Table 5-1 shallbe used.

The qualification process shall be structured according to Figure 5-1.

ECSS-E-ST-31-02C12 December 2012- Table 5-1: Categories of two-phase heat transport equipment according to heritage

![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td> y r o g e t a C</td>
		<td>Description</td>
		<td>Qualification programme</td>
		<td>Remarks related to the present Standard</td>
	</tr>
	<tr align="center">
		<td></td>
		<td>modifications and  The product is qualified to requirements at least as severe as those imposed by the actual technical specification The product is produced by the same manufacturer and using identical tools and manufacturing processes </td>
		<td>None</td>
		<td></td>
	</tr>
	<tr align="center">
		<td></td>
		<td>modifications. However:  The product is qualified to requirements less severe or different to those imposed by the actual technical specification Or  Or  The product is produced by a different manufacturer or using different tools and manufacturing processes The product has substitution parts and materials with equivalent reliability *)</td>
		<td>Delta qualification programme, decided on a case-by-case basis in agreement between the customer and the supplier</td>
		<td>This category relates for example to TPHTE hardware, which is identical to already qualified hardware but has been qualified to lower mechanical loads or narrower operating temperature ranges as required by an actual project. The category relates also to situations, where TPHTE manufacturing technology is transferred from a qualified supplier to a new manufacturer. *) Any substitution parts and materials fulfilling the same procurement specification does not require delta-qualification.</td>
	</tr>
	<tr align="center">
		<td></td>
		<td>modifications</td>
		<td>Delta or full qualification programme, decided on a case-by-case basis depending on the impact of the modification in agreement between the customer and the supplier</td>
		<td>Examples for category C are: Heat pipes with identical capillary structure but different diameters, smaller bent radius, CDL with different fluid line configurations or dimensions or different condenser configurations (radiator lay out).</td>
	</tr>
	<tr align="center">
		<td></td>
		<td></td>
		<td></td>
		<td>TPHTE, including existing systems with new capillary structures or material combinations.</td>
	</tr>
</table>

ECSS-E-ST-31-02C12 December 2012TPHTE to be

qualified

Review-of-design

(Clause 5.5.3.4)

Category A

equipment?

Yes

No qualification

programme required

No

Category B

equipment?

No

Category C

equipment?

No

Category D

equipment

Yes

Similarity analysis

(Clause 5.5.3.3.2)

Delta qualification

programme

(Clause 5.5.4.2)

Yes  Similarity analysis

(Clause 5.5.3.3.2)

Delta qualification

programme

(Clause 5.5.4.2)

or Full qualification

programme

(Clause 5.5.4.1)

Full qualification

programme

(Clause 5.5.4.1)

For category definition see Table 5-1.

Figure 5-1: Selection of qualification process

- 5.5  Qualification stage

5.5.1  General

a.

Qualification shall demonstrate that the design of the TPHTE meets therequirements of the technical specification.

NOTE  The  qualification  can  be  supported  by  in-orbit

demonstration  to  verify  requirements,  which

are affected by zero-g environment.

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012b.  When  a  requirement  is  verified  by  qualification  at  lower  level,  thetraceability to the lower level verification evidence shall be provided.NOTE  This concerns manufacturing processes as well

as parts, materials and sub-units of a TPHTE.

c.

Formal close-out of qualification at lower level shall be performed priorto close-out at higher level.

5.5.2  Quality audits

a.

The  supplier  shall  allow  quality  audits  in  support  to  the  qualificationprocess in accordance with EN 9100-2009 clause 4.6.4.2.

Quality audits shall be conducted such that the supplier’s know-how andproprietary data are protected.

b.

NOTE  As  a  general  rule  audits  should  be  performed

by quality assurance personnel of the customer

and not by experts in the field.

5.5.3  Qualification methods

5.5.3.1  Overview

a.

A verification plan (VP) shall be prepared in conformance with the DRDin Annex B and agreed with the customer.

The qualification of TPHTE shall be accomplished by one or more of thefollowing verification methods:

1.

2.

3.

4.

The selected qualification methods shall be defined in a verification planspecified in 5.5.3.1a.

Test (including demonstration), as specified in 5.5.3.2.

Analysis (including similarity), as specified in 5.5.3.3.

Review-of-design, as specified in 5.5.3.4.

Inspection, as specified in 5.5.3.5.

b.

c.

b.

c.

d.

5.5.3.2

a.

Test

Verification by test shall consist of measuring product performance andfunctions under representative simulated environments.

All safety critical functions shall be verified by test.

Qualification shall be carried out on hardware, which is representative ofthe end item in terms of design, materials, tooling and methods.

TPHTE  subject  to  qualification  test  shall  be  manufactured  applyingqualified processes.

![Im0](images/Im0)

![Im0](images/Im0)

5.5.3.3  Analysis

ECSS-E-ST-31-02C12 December 20125.5.3.3.1  General

a.

Verification  by  analysis  shall  consist  of  performing  theoretical  orempirical evaluation using techniques agreed with the customer.

Analysis shall be performed to predict specified performance parameterof the TPHTE.

Analytical  prediction  results  shall  be  correlated  with  qualification  testresults.

NOTE  Result  correlations

validation,  which

qualification processes.

lead

can

to  software

reduce

tool

follow-on

Discrepancies  between  analytical  prediction  and  test  results  shall  beanalysed in order to demonstrate that the objective of the qualification isnot compromised.

e.  Mechanical  and  thermal  performance  analysis  and  test  prediction  shallbe documented in a dedicated report in conformance with ECSS-E-ST-31,Annex C.

NOTE  Analysis and test prediction can be split in two

documents.

b.

c.

d.

b.

5.5.3.3.2  Similarity

a.

shall  be  performed

For  a  product  that  is  similar  to  already  qualified  products,  a  similarityanalysis

requiringto

complementary qualification activities.

Qualification by similarity shall not be performed on a product that hasbeen previously qualified by similarity.

identify  differences

5.5.3.4  Review-of-design (ROD)

a.

For  verification  by  ROD  existing  records  and  evidence  shall  be  used  todemonstrate that requirements are met.

NOTE  Existing  records  and  evidence  are  validated

design  documents,  approved  design  reports,

technical

and

description,

manufacturing drawings.

engineering

b.

Verification by ROD shall be documented in a Review-of-Design reportin conformance with the DRD in Annex C.

5.5.3.5

a.

Inspection

For  verification  by

characteristics shall be used to demonstrate that requirements are met.inspection  visual  determination  of  physicalNOTE  Physical  characteristics  include  constructional

features,  hardware  conformance  to  document

drawing  and  workmanship

requirements,

physical conditions.

ECSS-E-ST-31-02C12 December 2012b.

Verification by inspection shall be documented in an Inspection Report inconformance with the DRD in Annex D.

5.5.4

Full and delta qualification programme

5.5.4.1

a.

Full qualification programme

Equipment  for  which  a  full  qualification  programme  is  required  as  perTable 5-1 shall be qualified by test according to clause 5.5.3.2 and 5.6 andby analysis according to clause 5.5.3.3.

5.5.4.2  Delta qualification programme

a.

Equipment for which a delta qualification programme is required as perTable  5-1  shall  undergo  a  delta  qualification  programme,  which  is  asubset of the full qualification programme of clause 5.5.4.1.

The  delta  qualification  programme  shall  be  selected  on  a  case-by-casebasis and based on the modifications to existing qualified hardware.

The delta qualification programme shall be agreed with the customer.b.

c.

5.5.5

Performance requirements

5.5.5.1  Generic requirements

a.

The  following  generic  performance  characteristics  of  a  TPHTE  shall  bedetermined and verified against specified data:

1.

Ability  to  sustain  the  combination  of  the  predicted  worstmechanical loads:

(a)

(b)

External mechanical loads.

Internal  loads  due  to  the  saturation  pressure  of  the  heatcarrier fluid within the TPHTE exposure temperature range.Thermo-mechanical  loads  due  to  temperature  cycling  andCTE  mismatch  within  the  TPHTE  exposure  temperaturerange.

Loads imposed by  volume change due to freezing/thawingof the heat carrier within the TPHTE exposure temperaturerange.

(c)

(d)

2.

Safe life item and fatigue-life demonstration

(a)

Safe  life  item  demonstration,  performed  by  analysis  or  testor  both  in  conformance  with  ECSS-E-ST-32-01  for  TPHTEnot  submitted  to  a  proof  pressure  or  for  which  the  prooffactor used in the proof pressure test is less than 1,5.

Fatigue-life demonstration, performed by analysis or test orboth  in  conformance  with  ECSS-E-ST-32  for  TPHTE  for(b)

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012which  the  proof  factor  used  in  the  proof  pressure  test  isequal or larger than 1,5.

3.

Thermal parameters:

(a)  Minimum and maximum heat transport capability over theTPHTE thermal performance temperature range.

NOTE

For  heat  pipes  only

transport capability is of interest.

the  maximum  heat

(b)

Evaporator heat flux over  the TPHTE thermal performancetemperature range.

(c)  Heat transfer coefficient in the evaporator and condenser.(d)  Overall thermal resistance of the device.

Operational characteristics

(a)  Maximum  heat  load  applied  in  one  step  at  discretetemperatures over the specified range.

Start-up  behaviour  from  frozen  conditions,  if  the  exposuretemperature range includes freezing of the working fluid.For  cryogenic  TPHTE,  start-up  from  the  super-critical  stateof the working fluid.

4.

5.

6.

(b)

(c)

(b)

Leak-before-burst.

Lifetime performance:

(a)

Long-term compatibility between fluid and wetted materials(materials in contact with the fluid).

Space radiation effects in order to demonstrate that fluid de-composition  does  not  adversely  affect  specified  TPHTEperformance during the product life cycle.

5.5.5.2

a.

Specific requirements

For  CCHP  the  following  specific  performance  characteristics  shall  bedetermined and verified against specified data:

1.

Reduction of transport capability due to heat pipe bending at theminimum specified radius.

Reduction of transport capability due to tilt (see Figure 3-1).

NOTE  To  item  1:  The  minimum  bending  radius  is

2.

defined by the supplier.

b.

The characteristics specified in 5.5.5.2a,

For  VCHP,  the  following  specific  performance  characteristics  shall  bedetermined and verified against specified data:

1.

2.  Maximum transport capability in fully-on conditions,

Heat leak from condenser to evaporator in off-mode,

3.

4.

Thermal resistance between condenser and reservoir,

![Im0](images/Im0)

![Im0](images/Im0)

c.

d.

ECSS-E-ST-31-02C12 December 20125.

Ability  to  regulate  the  evaporator  temperature  with  passive  andactive methods.

NOTE  Passive  methods  include  devices  with  non-

heated  gas  reservoirs,  active  methods  include

devices with heated/cooled gas reservoirs.

The characteristics specified in 5.5.5.2a,

For HP Diode, the following specific performance characteristics shall bedetermined and verified against specified data.

1.

2.  Maximum heat transport capability in forward mode,

3.

4.

5.

For  CDL,  the  following  specific  performance  characteristics  shall  bedetermined and verified against specified data

1.  Minimum heat load applied under which start-up is possible overTime and energy to move from forward to reverse mode,

Time and energy to move from reverse to forward mode,

Heat leak from condenser to evaporator in reverse mode.

the specified temperature range,

Sensitivity  of  the  minimum  heat  load  in  relation  to  the  thermalmass attached to the evaporator,

3.  Minimum  heat  load  applied  under  which  nominal  operation  ispossible over the specified temperature range,

Sub-cooling conditions to guarantee specified performance,

Impact  on  performance  due  to  tilt  (see  Figure  3-2)  and  adverseelevation (evaporator above condenser),

Heat leak from condenser to evaporator in off-mode,

Ability  to  regulate  the  evaporator  temperature  with  passive  andactive methods.

2.

4.

5.

6.

7.

NOTE  Passive  methods  include  devices  with  passive

regulation  (by-pass)  valves  in  TPL.  Active

methods  include  devices  with  heated/cooled

liquid  reservoirs,  heated  regulation  valves  and

TPLs  with  thermo-electric  cooler  (TEC)  on  the

liquid reservoir.

- 5.6  Qualification test programme

5.6.1

a.

Number of qualification units

The  number  of  TPHTE  units  submitted  to  the  qualification  programmetest units shall be in accordance with Figure 5-2 and Figure 5-3.

![Im0](images/Im0)

Test sequence

ECSS-E-ST-31-02C12 December 20125.6.2

a.

Equipment  for  which  a  full  qualification  programme  is  required  as  perTable  5-1  shall  be  verified  by  qualification  testing  according  to  the  testsequence as defined in Figure 5-2 for HP and Figure 5-3 for CDL.

For an equipment where a delta qualification programme is required asper Table 5-1, the supplier shall derive from the test sequence of Figure5-2  for  HP  and  Figure  5-3  for  CDL  a  reduced  test  sequence  for  deltaqualification.

The delta qualification sequence shall be agreed with the customer.

b.

c.

ECSS-E-ST-31-02C12 December 2012Heat Pipe:

5 functional units

•

•

3 units straight configuration

2 units bent configuration

2 units for material compatibility testing

2 pressure samples

- n

- o

- i

- t

- a

- r

- a

- p

- e

- r

- p

- m

- e

- t

- i

- t

- s

- e

- T

Selection of test item

configuration and quantity

(5.6.1)

Manufacturing of qualification

hardware

according to documented processes

Reduced acceptance test of hardware

for qualification:

•  Physical property measurement (5.6.4)

•  Proof pressure test (5.6.5)

•  Leak test (5.6.8)

•  Gas plug test (5.6.13)

•  Reduced thermal performance test

(5.6.14.1 to 5.6.14.4)

Leak test

(5.6.8)

Test plan and Qualification

Test Readiness Review

(5.6.3.1)

Functional tests

(3 straight, 2 bent)

Material compatibility tests

(2 units) (2 HP)

Pressure tests

(2 samples)

Pressure cycle test

(5.6.6)

Leak test

(5.6.8)

Burst pressure test

(5.6.7)

Full thermal performance test

(5.6.9.1 to 5.6.9.4)

Reduced thermal

performance test

(5.6.14.1 to 5.6.14.4)

- e

- m

- m

- a

- r

- g

- o

- r

- p

- t

- s

- e

- t

- n

- o

- i

- t

- a

- c

- i

- f

- i

- l

- a

- u

- Q

Mechanical test

(5.6.10)

Thermal cycle test

(5.6.11)

Gas plug test

(5.6.13)

Reduced thermal performance

test (5.6.14.1 to 5.6.14.4)

Aging test

(5.6.12)

Full thermal performance test

(5.6.9.1 to 5.6.9.4)

Life test incl.  Gas plug test

(5.6.12 & 5.6.13)

Reduced thermal

performance test

(5.6.14.1 to 5.6.14.4)

Post Test Review

(5.6.3.1b)

Verification Report

(Table 5-7)

Figure 5-2: Qualification test sequence for HP

![Im0](images/Im0)

ECSS-E-ST-31-02C12 December 2012CDL:

1 functional unit

1 unit for material compatibility testing1 unit as pressure sample

Selection of test item configuration and

quantity

(5.6.1)

Manufacturing of qualification hardware

according to documented processes

Reduced acceptance test of hardware for

qualification:

●  Physical property measurement (5.6.4)

●  Proof test (5.6.5)

●  Leak test (5.6.8)

●  Reduced thermal performance test (5.6.14)

- n

- o

- i

- t

- a

- r

- a

- p

- e

- r

- p

- m

- e

- t

- i

- t

- s

- e

- T

Leak test

(5.6.8)

Test plan and Qualification

Test Readiness Review

(5.6.3.1)

Functional tests

(1 CDL)

Full thermal performance test

(5.6.9.1 & 5.6.9.5)

Mechanical test

(5.6.10)

Reduced thermal performance test

(5.6.14.1 & 5.6.14.5)

Material compatibility tests

(1 CDL)

Pressure tests

(1 sample)

Reduced thermal performance test

Pressure cycle test(5.6.14.1 & 5.6.14.5)

Life test

(5.6.12)

(5.6.6)

Leak test

(5.6.8)

Burst pressure test(5.6.7)

Thermal cycle test

(5.6.11)

Reduced thermal performance test

(5.6.14.1 & 5.6.14.5)

Full thermal performance test

5.6.9.1 & 5.6.9.5)

- e

- m

- m

- a

- r

- g

- o

- r

- p

- t

- s

- e

- t

- n

- o

- i

- t

- a

- c

- i

- f

- i

- l

- a

- u

- Q

Post Test Review

(5.6.3.1b)

Verification Report

(Table 5-7)

Figure 5-3: Qualification test sequence for CDL

![Im0](images/Im0)

![Im0](images/Im0)

5.6.3

Test requirements

ECSS-E-ST-31-02C12 December 2012Test specification and reviews

the  qualification

test  campaign

the

following5.6.3.1

a.

starting

Before

preconditions shall be met:

1.

2.

Establishing of a test specification in conformance with the DRD inAnnex E,

Establishing  of  test  procedures  in  conformance  with  the  DRD  inAnnex F, and

Conductance of test readiness review.

3.

At completion of the test sequence a post-test review shall be conducted.Test documentation shall be agreed with the customer.

5.6.3.2

Test conditions

5.6.3.2.1  Test tolerances

a.

The test tolerances specified in Table 5-2 shall be applied to the nominaltest values specified.

For  the  purpose  of  5.6.3.2.1a,  test  tolerances  shall

instrumentation accuracy.

include  testb.

c.

b.

NOTE  The  tolerances  specified  in  Table  5-2  are  the

test

allowable

parameters can vary. The values in the table are

inclusive of instrumentation accuracy.

ranges  within  which

the

ECSS-E-ST-31-02C12 December 2012![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Test parameters</td>
		<td>Tolerances</td>
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
		<td>2. Relative humidity</td>
		<td>± 10 %</td>
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
		<td>4. Acceleration</td>
		<td>-0 / +10 %</td>
	</tr>
	<tr align="center">
		<td>5. Static Load</td>
		<td>-0 / +10 %</td>
	</tr>
	<tr align="center">
	</tr>
	<tr align="center">
	</tr>
</table>

ECSS-E-ST-31-02C12 December 2012![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Test parameters</td>
		<td>Tolerances</td>
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
		<td>13. Test time</td>
		<td>-0/+10 %</td>
	</tr>
</table>

ECSS-E-ST-31-02C12 December 20125.6.3.2.2  Measurement accuracy

a.

The accuracy of test instrumentation shall be verified in accordance withapproved calibration procedures.

All test instrumentation shall be within the normal calibration period atthe time of the test.

b.

![Im0](images/Im0)

