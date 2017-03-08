ECSS-E-ST-20-20C15 April 2016Space engineering

Electrical design and interface

requirements for power supply

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016- Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry

- associations for the purpose of developing and maintaining common standards. Requirements in this

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be

- applied where they are effective, and for the structures and methods to evolve as necessary without

- rewriting the standards.

- This  Standard  has  been  prepared  by  the  ECSS-E-ST-20-20  Working  Group,  reviewed  by  the  ECSS

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

ESA Requirements ,Standards and Engineering Knowledge Office

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2016© by the European Space Agency for the members of ECSS

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS-E-ST-20-20C 15 April 2016</td>
		<td>First issue</td>
	</tr>
</table>

ECSS-E-ST-20-20C15 April 2016Table of contents- Change log ................................................................................................................. 3

- Introduction ................................................................................................................ 7

- 1 Scope ....................................................................................................................... 8

- 2 Normative references ............................................................................................. 9

- 3 Terms, definitions and abbreviated terms .......................................................... 10

- 3.1  Terms from other standards .................................................................................... 10

- 3.2  Terms specific to the present standard ................................................................... 10

- 3.3  Abbreviated terms................................................................................................... 19

- 3.4  Nomenclature ......................................................................................................... 19

- 4 Principles .............................................................................................................. 21

- 4.1  General ................................................................................................................... 21

- 4.2  Standard assumptions ............................................................................................ 21

- 5 Requirements ........................................................................................................ 22

- 5.1  Reference power bus specifications ....................................................................... 22

- 5.2  Functional/Source interface requirements ............................................................... 24

5.2.1

LCL/HLCL class ........................................................................................ 245.2.2  RLCL class ............................................................................................... 245.2.3  Current limitation section ........................................................................... 245.2.4

Trip-off section .......................................................................................... 255.2.5  UVP section .............................................................................................. 255.2.6

Telecommand section features ................................................................. 265.2.7  Conditions at start-up/ switch-off ............................................................... 265.2.8

Telemetry section ...................................................................................... 285.2.9

Status section ........................................................................................... 295.2.10  Repetitive overload ................................................................................... 295.2.11  Reverse current tolerance ......................................................................... 305.2.12  Parallel connection .................................................................................... 305.2.13  Switching options ...................................................................................... 31![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 20165.2.14  LCL Switch dissipative failure .................................................................... 325.2.15  Loss of LCL lines ...................................................................................... 335.2.16  Noise immunity ......................................................................................... 335.2.17  Output impedance envelope, when in limitation ........................................ 335.2.18  Noise immunity feature ............................................................................. 345.2.19  Output LCL load (Input load characteristic) ............................................... 34- 5.3  Functional/Load interface requirements .................................................................. 35

5.3.1  Nominal feature ......................................................................................... 355.3.2

Switch-on .................................................................................................. 35LCL switch dissipative failure .................................................................... 365.3.3

5.3.4

Load test condition .................................................................................... 365.3.5  User UVP at bus input side ....................................................................... 36- 5.4  Performance/Source interface requirements ........................................................... 37

5.4.1  Overall requirements ................................................................................. 375.4.2

Start-up/Switch-off requirements ............................................................... 385.4.3  UVP .......................................................................................................... 395.4.4

Switch-on capability .................................................................................. 40Voltage drop.............................................................................................. 415.4.5

5.4.6

Stability ..................................................................................................... 415.4.7  Current Telemetry, accuracy ..................................................................... 425.4.8  Current Telemetry, offset........................................................................... 425.4.9  Retrigger interval ....................................................................................... 435.4.10  dI/dt limit on retrigger ON edge ................................................................. 435.4.11  dI/dt limit on retrigger OFF edge ................................................................ 435.4.12  Status, accuracy ....................................................................................... 43- 5.5  Performance/Load interface requirements .............................................................. 44

Load reverse current ................................................................................. 44Load characteristic .................................................................................... 44Source-load characteristic ......................................................................... 45Start-up surge input current ....................................................................... 45Internal load Input current limitation .......................................................... 465.5.1

5.5.2

5.5.3

5.5.4

5.5.5

- Annex A (informative) Requirements mapping ..................................................... 47

- Bibliography ............................................................................................................. 61

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016- Figures

- Figure 3-1: LCL overload timing diagram (case 1) ................................................................ 13

- Figure 3-2: LCL overload timing diagram (case 2) ................................................................ 14

- Figure 3-3: Typical start-up current profile of a DC/DC converter attached to a LCL ............. 14

- Figure 3-4: RLCL overload timing diagram ........................................................................... 15

- Tables

- Table 3-1: LCL classes ......................................................................................................... 16

- Table 3-2: RLCL classes ...................................................................................................... 17

- Table 3-3: HLCL classes ...................................................................................................... 18

- Table 5-1: Reference Power Bus Specifications ................................................................... 23

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016IntroductionThis standard identifies the requirements needed to specify, procure or developa  space  power  distribution  based  on  Latching  Current  Limiters,  both  fromsource and load perspective.

For a reference architecture description, it is possible to refer to ECSS-E-HB-20-20.ECSS-E-HB-20-20  includes  a  clarification  of  the  principles  of  operation  of  apower distribution based on LCLs, identifies important issues related to LCLsand explains the requirements of the present standard.

Note that the present issue of the standard covers electrical design and interfacerequirements for power distribution based on Latching Current Limiters only.Future issues of the present standard will cover additional power interfaces.![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016ScopeThe target  applications covered  by this standard  are all missions traditionallyprovided  with  power  distribution  and  protection  by  LCLs/RLCLs  (science,earth  observation,  navigation)  with  exclusion  of  applications  for  which  thepower distribution and protection is provided by fuses (e.g. most of the GEOtelecom satellites).

The present standard applies to power distribution by LCLs/RLCLs for powersystems, and in general for satellites, required to be Single Point Failure Free.The  present  standard  document  applies  exclusively  to  the  main  bus  powerdistribution by LCLs/RLCLs to external satellite loads.

A particular case of LCLs (Heater LCLs, or HLCLs) is also treated. The HLCLsare the protections elements of the power distribution to the thermal heaters ina spacecraft.

Internal power system protections of LCLs/RLCLs are not covered.

Paralleling of LCLs to increase power supply line reliability is not covered bythe  present  standard,  since  this  choice  does  not  appreciably  change  thereliability of the overall function (i.e. LCL plus load).

In fact, a typical reliability figure of the LCL (limited to the loss of its switch-oncapability) is 20 FIT or less.

If the load to be connected to the LCL line has a substantial higher failure ratethan this, it is not necessary to duplicate the LCL to supply that load.

This standard may be tailored for the specific characteristic and constrains of aspace project in conformance with ECSS-S-ST-00.

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016Normative referencesThe  following  normative  documents  contain  provisions  which,  throughreference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  datedreferences, subsequent amendments to, or revision of any of these publicationsdo not apply. However, parties to agreements based on this ECSS Standard areencouraged to investigate the possibility of applying the more recent editions ofthe  normative  documents  indicated  below.  For  undated  references,  the  latestedition of the publication referred to applies.

ECSS-S-ST-00-01

ECSS-E-ST-20

ECSS system - Glossary of terms

Space engineering - Electrical and electronic

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016Terms, definitions and abbreviated terms- 3.1  Terms from other standards

a.

For the purpose of this Standard, the terms and definitions from ECSS-S-ST-00-01 apply, in particular for the following terms:

1.

2.

3.

4.

5.

6.

redundancy

active redundancy

hot redundancy

cold redundancy

fault

fault tolerance

- 3.2  Terms specific to the present standard

centralised

3.2.1

feature that serves a number of elementary functions in a system

current overshoot decay time

3.2.2

maximum  time  constant  decay  time  from  current  overshoot  peak  to  actuallimitation  current  after  an  overcurrent  event,  under  the  assumption  that  thedecay time is modelled by an exponential law

current overshoot recovery time

3.2.3

time needed for the to reduce from its maximum  value to ±10% of the excesscurrent, at the application of an overload to the LCL/RLCL/HLCL

NOTE 1  See Figure 3-1 and Figure 3-2.

NOTE 2  Excess  current  is  intended  as  overshoot  peak

minus actual limitation current value.

fault condition

3.2.4

internal failure of one of the following devices: LCL, RLCL or HLCL

NOTE

This  definition  is  aimed  at  clarifying  that  the

fault  condition  is  not  the  one  relevant  to  the

load.

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016fault current emission

3.2.5

maximum  current  emission  of  a  given  circuit  at  external  interface  underabnormal conditions

NOTE   Abnormal  in  this  context  can  cover  fault

condition or operator error.

fault current tolerance

3.2.6

minimum  abnormal  interface  current  that  a  circuit  can  sustain  without  beingdamaged

fault voltage emission

3.2.7

maximum  voltage  emission  of  a  given  circuit  at  external  interface  underabnormal conditions

NOTE   Abnormal  condition  can  cover  fault  condition

or operator error.

fault voltage tolerance

3.2.8

minimum  abnormal  interface  voltage  that  a  circuit  can  sustain  without  beingdamaged

feature

3.2.9

part of a function to which a specific requirement refers

3.2.10  heater latching current limiter (HLCL)

LCL  used  as  protection  element  in  a  power  distribution  to  satellite  thermalheaters

input filter charge time

3.2.11

time required for the LCL to charge the load input filter

NOTE

See Figure 3-3.

input overshoot charge

3.2.12

charge  requested  at  the  LCL/RLCL/HLCL  input  at  the  application  of  anoverload, for current in excess of the actual limitation current

NOTE

See Figure 3-1 and Figure 3-2.

latching current limiter (LCL)

3.2.13

switchable  and  latching  protection  placed  between  a  power  source  and  therelevant  load,  causing  a  trip-off  after  having  achieved  at  its  output  anovercurrent limitation for a definite trip-off time

3.2.14  LCL class

maximum allowable current that can flow through the LCL itself, under givenstandard conditions

NOTE

LCL classes are defined in Table 3-1.

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 20163.2.15  LCL switch dissipative failure

failure corresponding to an equivalent gate to drain short circuit on a MOSFETNOTE

The  voltage  across  is  approximately  4V  to  5V

maximum.

3.2.16  nominal condition

operative condition of the LCL/RLCL/HLCL, with no internal failure

repetitive overload

3.2.17

overcurrent event that repeats for a number of cycles or indefinitely

retriggerable latching current limiter (RLCL)

3.2.18

LCL  that  automatically  attempts  to  switch  ON  when  powered  or  after  aretrigger interval when a trip-off event occurred

retriggerability

3.2.19

characteristic  of  an  RLCL  protection  to  be  able  to  restart  automatically  afterbeing triggered

retrigger interval

3.2.20

time duration in high impedance state of a RLCL after a permanent overcurrentevent occurred and the relevant trip-off time elapsed

NOTE 1  See Figure 3-4.

NOTE 2  High  impedance  state  is  equivalent  to  OFF

condition.

3.2.21  RLCL class

maximum allowable current that can flow through the RLCL itself, under givenstandard conditions

NOTE

RLCL classes are defined in Table 3-2.

3.2.22  sub-feature

sub-part of a function to which a specific requirement refers

3.2.23  switch-on capability

See “Switch-on response time”.

3.2.24  switch-on response time

time  needed  to  enable  actual  ON  command  reception,  under  specifiedconditions

3.2.25  UVP switch-off response time

time  to  achieve  UVP  action  in  dynamical  conditions,  when  under  voltageexcitation is achieved under standard conditions

NOTE

The  UVP  action  is  the  OFF  of  the  relevant

function.

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016time to current overshoot

3.2.26

maximum  time  from  max  limitation  current  to  actual  current  overshoot  peakafter an overcurrent event

NOTE

See Figure 3-1 and Figure 3-2.

trip-off

3.2.27

event occurring when a current protection latch flips and opens the protecteddistribution line after an overcurrent condition

NOTE

To  open  a  distribution  line  means  to  set  the

distribution line in high impedance status.

trip-off time

3.2.28

time  in  between  LCL  crossing  actual  current  limitation  value  and  the  trip-offevent, in permanent overcurrent condition.

NOTE

See Figure 3-1 and Figure 3-2.

3.2.29  undervoltage protection (UVP)

protection that is triggered when the voltage provided to a function falls belowa predefined threshold

NOTE

LCL  and  RLCL  are  examples  of  functions  for

which UVP is activated.

Current Overshoot

Decay Time

Time to Current

Overshoot

overshoot

charge

Excess

Current

±10% of

Excess

Current

Current

Overshoot

- Limitation

- Current

Max

Actual

Min{

- Nominal LCL

- current (LCL Class)

maximum

overshoot

recovery time

Trip-off time

Figure 3-1: LCL overload timing diagram (case 1)

![Im0](images/Im0)

ECSS-E-ST-20-20C15 April 2016Current

Overshoot

Time to Current

Overshoot

overshoot

charge

Excess

Current

±10% of

Excess

Current

Limitation

Current

Max

Actual

Min{

Nominal LCL

current (LCL Class)

maximum

overshoot

recovery time

Trip-off time

Figure 3-2: LCL overload timing diagram (case 2)

NOTE

Figure 3-1 and Figure 3-2 show typical current

diagrams  expected  when  an  LCL/RLCL/HLCL

are  subject  to  an  overload.  They  can  represent

either  the  LCL/RLCL/HLCL  input  or  output

current.

- LCL Current

- Limitation

- Nominal load

- consumption

Input

Filter Charge time

- Figure 3-3: Typical start-up current profile of a DC/DC converter attached to a LCL

![Im3](images/Im3)

![Im0](images/Im0)

![Im1](images/Im1)

![Im2](images/Im2)

![Im0](images/Im0)

Current

Current

Overshoot

ECSS-E-ST-20-20C15 April 2016- Limitation

- Current

Max

Actual

Min{

- Nominal  LCL

- current (LCL  Class)

Trip-off  time

Retrigger  interval

Overload

Figure 3-4: RLCL overload timing diagram

TimeECSS-E-ST-20-20C15 April 2016![Im0](images/Im0)

