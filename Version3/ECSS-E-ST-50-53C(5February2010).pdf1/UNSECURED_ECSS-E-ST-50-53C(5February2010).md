ECSS-E-ST-50-53C5 February 2010Space engineering

SpaceWire - CCSDS packet transferprotocol

 

ECSS SecretariatESA-ESTECRequirements & Standards DivisionNoordwijk, The Netherlands![Im1](images/Im1)

![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 - Foreword

- This  Standard  is  one  of  the  series  of  ECSS  Standards  intended  to  be  applied  together  for  the 

- management,  engineering  and  product  assurance  in  space  projects  and  applications.  ECSS  is  a 

- cooperative  effort  of  the  European  Space  Agency,  national  space  agencies  and  European  industry 

- associations for the purpose of developing and maintaining common standards. Requirements in this 

- Standard are defined in terms of what shall be accomplished, rather than in terms of how to organize 

- and  perform  the  necessary  work.  This  allows  existing  organizational  structures  and  methods  to  be 

- applied where they are effective, and for the structures and methods to evolve as necessary without 

- rewriting the standards. 

- This  Standard  has  been  prepared  by  the  ECSS‐E‐ST‐50‐53  Working  Group,  reviewed  by  the  ECSS 

- Executive Secretariat and approved by the ECSS Technical Authority. 

- Disclaimer

- ECSS does not provide any warranty whatsoever, whether expressed, implied, or statutory, including, 

- but not limited to, any warranty of merchantability or fitness for a particular purpose or any warranty 

- that  the  contents  of  the  item  are  error‐free.  In  no  respect  shall  ECSS  incur  any  liability  for  any 

- damages, including, but not limited to, direct, indirect, special, or consequential damages arising out 

- of, resulting from, or in any way connected to the use of this Standard, whether or not based upon 

- warranty, contract, tort, or otherwise; whether or not injury was sustained by persons or property or 

- otherwise; and whether or not loss was sustained from, or arose out of, the results of, the item, or any 

- services that may be provided by ECSS. 

- Published by:  

- Copyright:  

ESA Requirements and Standards Division 

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

2010 © by the European Space Agency for the members of ECSS 

2 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 Change log![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>ECSS‐E‐ST‐50‐53A </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐50‐53B </td>
		<td>Never issued </td>
	</tr>
	<tr align="center">
		<td>ECSS‐E‐ST‐50‐53C  5 February 2010 </td>
		<td>First issue </td>
	</tr>
</table>

3 ECSS‐E‐ST‐50‐53C 5 February 2010 Table of contents- Change log.................................................................................................................3

- 1 Scope.......................................................................................................................6

- 2 Normative references.............................................................................................7

- 3 Terms, definitions and abbreviated terms............................................................8

- 3.1  Terms defined in other standards...............................................................................8

- 3.2  Terms specific to the present standard ......................................................................8

- 3.3  Abbreviated terms ......................................................................................................8

- 3.4  Conventions ...............................................................................................................8

- 4 Principles ................................................................................................................9

- 4.1  Purpose ......................................................................................................................9

- 4.2  Protocol features ........................................................................................................9

- 4.3  Services....................................................................................................................10

- 4.4  Guide to this document ............................................................................................11

- 5 Requirements........................................................................................................12

- 5.1  Service parameters ..................................................................................................12

5.1.1  CCSDS packet ...........................................................................................12Packet length..............................................................................................125.1.2

Status code.................................................................................................125.1.3

5.1.4

Target SpaceWire Address ........................................................................125.1.5

Target Logical Address...............................................................................135.1.6  User Application Value ...............................................................................13- 5.2  Service primitives .....................................................................................................13

5.2.1  CCSDS Packet Transfer Service................................................................135.2.2  CCSDS_PACKET_SEND.request..............................................................135.2.3  CCSDS_PACKET_RECEIVED.indication ..................................................14- 5.3  CCSDS Packet Transfer Protocol fields...................................................................15

Target SpaceWire Address field.................................................................15Target Logical Address field.......................................................................155.3.1

5.3.2

4 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 5.3.3

Protocol Identifier field................................................................................155.3.4  Reserved field.............................................................................................155.3.5  User Application field..................................................................................155.3.6

Packet field.................................................................................................16- 5.4  CCSDS Packet Transfer Protocol format .................................................................16

- 5.5  CCSDS Packet Transfer Protocol Action .................................................................17

5.5.1  Overview.....................................................................................................175.5.2

Send request ..............................................................................................175.5.3

Transfer packet...........................................................................................185.5.4  Receive indication ......................................................................................18- Annex A (informative) Managed parameters.........................................................20

- Bibliography.............................................................................................................21

- Figures

- Figure 4-1: Protocol configuration ............................................................................................9

- Figure 5-1: Encapsulated CCSDS Packet format ..................................................................16

- Figure 5-2: CCSDS Packet Transfer Protocol Packet Transfer .............................................17

 

5 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 ScopeThere is a number of communication protocols that can be used in conjunction with  the  SpaceWire  Standard  (ECSS‐E‐ST‐50‐12),  to  provide  a  comprehensive set  of  services  for  onboard  user  applications.  To  distinguish  between  the various protocols a protocol identifier is used, as specified in ECSS‐E‐ST‐50‐51. This  Standard  specifies  the  CCSDS  packet  transfer  protocol,  which  is  one  of these protocols that works over SpaceWire. 

The  aim  of  the  CCSDS  Packet  Transfer  Protocol  is to  transfer  CCSDS Packets across a SpaceWire network. It does this by encapsulating the CCSDS Packet in a  SpaceWire  packet,  transferring  it  across  the  SpaceWire  network  and  then extracting the CCSDS Packet at the target.  

This standard may be tailored for the specific characteristic and constrains of a space project in conformance with ECSS‐S‐ST‐00. 

6 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 Normative referencesThe  following  normative  documents  contain  provisions  which,  through reference  in  this  text,  constitute  provisions  of  this  ECSS  Standard.  For  dated references, subsequent amendments to, or revision of any of these publications do not apply. However, parties to agreements based on this ECSS Standard are encouraged to investigate the possibility of applying the more recent editions of the  normative  documents  indicated  below.  For  undated  references,  the  latest edition of the publication referred to applies. 

 

ECSS‐S‐ST‐00‐01 

ECSS‐E‐ST‐50‐12 

ECSS‐E‐ST‐50‐51 

CCSDS 133.0‐B‐1 

 

ECSS system ‐ Glossary of terms 

Space engineering ‐ SpaceWire ‐ Links, nodes, routers and networks 

Space engineering ‐ SpaceWire protocol identification Space Packet Protocol, Blue Book 

7 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 Terms, definitions and abbreviated terms- 3.1  Terms defined in other standards

For the purpose of this Standard, the terms and definitions from ECSS‐S‐ST‐00‐01 and ECSS‐E‐ST‐50‐51 apply. 

- 3.2  Terms specific to the present standard

None. 

- 3.3  Abbreviated terms

The following abbreviations are defined and used within this standard: 

Abbreviation 

CCSDS 

EEP 

EOP 

SpW 

Meaning 

Consultative Committee for Space Data Systems 

error end of packet 

end of packet 

SpaceWire 

 

- 3.4  Conventions

In  this  document  hexadecimal  numbers  are  written  with  the  prefix  0x,  for example 0x34 and 0xDF15.  

Binary  numbers  are  written  with  the  prefix  0b,  for  example  0b01001100  and 0b01. 

Decimal numbers have no prefix. 

8 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 Principles- 4.1  Purpose

The  CCSDS  Packet  Transfer  Protocol  has  been  designed  to  encapsulate  a CCSDS Space Packet into a SpaceWire packet, transfer it from an initiator to a target  across  a  SpaceWire  network,  extract  it  from  the  SpaceWire  packet  and pass it to a target user application. This protocol does not provide any means for ensuring delivery of the packet nor is it responsible for the contents of the packet being a CCSDS Space Packet. 

The CCSDS Space Packet Protocol is defined in the following document: 

CCSDS  133.0‐B‐1  Space  Packet  Protocol.  Blue  Book.  Issue  1.  September 2003 or a later issue 

Figure 4‐1 illustrates the location of the CCSDS Space Packet transfer Protocol in a typical onboard protocol stack. The CCSDS Space Packet transfer Protocol provides  a  unidirectional  data  transfer  service  from  a  single  source  user application  to  a  single  destination  user  application  through  a  SpaceWire network.  

User Application

User Application

CCSDS Space packet

Transfer Protocol

CCSDS Space packet

Transfer Protocol

SpaceWire

Network

SpaceWire

Network

Figure 4‐1: Protocol configuration 

- 4.2  Protocol features

The  CCSDS  Space  Packet  transfer  Protocol  provides  the  capability  to  transfer CCSDS  Space  Packets  between  onboard  users  of  a  SpaceWire  network.  The CCSDS space packets may be of variable length or fixed size at the discretion of the  user  and  may  be  submitted  for  transmission  at  variable  intervals.  The 9 ![Im0](images/Im0)

![Im0](images/Im0)

composition of the CCSDS space packet is under the responsibility of the user application and is not checked by the CCSDS space packet transfer protocol.  ECSS‐E‐ST‐50‐53C 5 February 2010 - 4.3  Services

The  CCSDS  Space  Packet  Transfer  Protocol  provides  users  with  data  transfer services. The point at which a service is provided by a protocol entity to a user is  called  a  Service  Access  Point.  A  Service  Access  Point  of  the  Space  Packet Transfer Protocol is identified by a SpaceWire address and each service user is also identified by a SpaceWire Address.  

Service  data  units  submitted  to  a  Service  Access  Point  are  processed  in  the order of submission.  

Implementations may be required to perform flow control at a Service Access Point  between  the  service  user  and  the  service  provider.  However,  this standard does not recommend a scheme for flow control between the user and the provider.  

The followings features are offered by the data transfer service defined in this Standard:  





Unidirectional (one way) data transfer service. 

Asynchronous  Service.  There  are  no  predefined  timing  rules  for  the transfer of service data units supplied by the service user. The user may request data transfer at any time it desires, but there may be restrictions imposed by the provider on the data generation rate. 

Unconfirmed  Service:  the  sending  user  does  not  receive  confirmation from the receiving end that data has been received. 

Incomplete Services. The services do not guarantee completeness, nor do they provide a retransmission mechanism. 

SDU  format:  the  service  does  not  check  the  format  of  the  submitted CCSDS Space packet. 

Non  sequence  Preserving  Service.  The  sequence  of  service  data  units supplied  by  the  sending  user  may  not  be  preserved  through  the underlying network 









The  end‐to‐end  quality‐of‐service  provided  to  service  users  is  the  one  that  is provided  by  the  underlying  SpaceWire  network.  The  Space  Packet  Transfer Protocol  does  not  provide  any  mechanisms  for  guaranteeing  a  particular quality‐of‐service;  it  is  the  responsibility  of  implementing  organizations  to ensure that the end‐to‐end performance of a particular service instance meets the requirements of its users.  

Sequence preservation of packets in a SpaceWire network is dependent on the underlying network topology and configuration. Topologies and configurations which  allow  only  a  single  route  from  the  source  to  the  destination,  i.e. configurations  that  are  not  using  group  adaptive  routing,  are  sequence preserving.  

10 ![Im0](images/Im0)

- 4.4  Guide to this document

ECSS‐E‐ST‐50‐53C 5 February 2010 Clause  4  presents  the  purpose,  protocol  features  and  an  overview  of  the services the CCSDS packet transfer protocol offers. 

Clause 5.1 defines the service parameters. 

Clause 5.2 specifies the service primitives provided by the protocol. 

Clause  5.3  defines  the  protocol  fields  used  in  the  CCSDS  packet  transfer protocol packets. 

Clause  5.4  specifies  the  format  of  the  packets  used  by  the  CCSDS  packet transfer protocol. 

Clause 5.5 specified the action of the CCSDS packet transfer protocol. 

Annex A lists the managed parameters associated with this protocol. 

11 ECSS‐E‐ST‐50‐53C 5 February 2010 Requirements- 5.1  Service parameters

CCSDS packet

The  CCSDS  packet  parameter,  intended  as  the  service  data  unit transferred  by  the  CCSDS  packet  transfer  service,  shall  be  the  CCSDS Space Packet as defined in CCSDS 133.0‐B‐1 Space Packet Protocol, Blue Book, Issue 1, September 2003. 

Packet length

5.1.1

a.

5.1.2

a.

b.

5.1.3

a.

b.

5.1.4

a.

The  value  of  the  packet  length  shall  be  equal  to  at  least  7  and  at  most 65542 octets. 

Individual project organizations may establish the maximum length for a particular mission. 

NOTE

The length parameter defines the length of the 

Data Unit submitted by the user. 

Status code

The  Status  code  parameter  shall  be  used  to  indicate  the  validity  of  the packet to the receiving service user. 

The Status code parameter shall take one of the following values: 

1.

2.

3.

0x00 indicates that the packet is ok 

0x01 indicates packet arrived terminated by EEP 

0x02 indicates reserved field was non‐zero 

Target SpaceWire Address

The Target SpaceWire Address parameter shall be used to define the path to the Target when SpaceWire path addressing is being used. 

12 ![Im0](images/Im0)

![Im0](images/Im0)

5.1.5

a.

5.1.6

a.

5.2.1

a.

NOTE

Its value and use is user specific. 

- 5.2  Service primitives

Target Logical Address

ECSS‐E‐ST‐50‐53C 5 February 2010 The Target Logical Address parameter shall be used to define the logical address of the Target that is to receive the CCSDS packet. 

User Application Value

The User Application Value shall be an 8‐bit value which is transferred along with the CCSDS packet to the Target.  

CCSDS Packet Transfer Service

The service primitives associated with this service shall be the following  1.

2.

CCSDS_PACKET_SEND.request, 

CCSDS_PACKET_RECEIVE.indication. 

5.2.2

CCSDS_PACKET_SEND.request

Function

5.2.2.1

a.

At  the  initiator,  the  CCSDS  Packet  Transfer  service  user  shall  pass  a CCSDS_PACKET_SEND.request  primitive  to  the  service  provider  to request that a CCSDS Packet is transferred to the user at the target across the SpaceWire network. 

Semantics

5.2.2.2

a.

The  CCSDS_PACKET.request  primitive  shall  provide  the  following parameters:  

1.

CCSDS_PACKET_SEND.request  (CCSDS  Packet,  Packet  Length, Target  SpaceWire  Address,  Target  Logical  Address,  User Application Value). 

5.2.2.3  When Generated

a.

The  CCSDS_PACKET_SEND.request  primitive  shall  be  passed  to  the service provider to request it to send the CCSDS Packet.  

Effect On Receipt

5.2.2.4

a.

Receipt of the CCSDS_PACKET_SEND.request primitive shall cause the service provider to transfer the CCSDS Packet. 

13 ECSS‐E‐ST‐50‐53C 5 February 2010 5.2.2.5  Additional Comments

a.

The  CCSDS_PACKET_SEND.request  primitive  shall  be  used  to  transfer CCSDS Packets across the SpaceWire network along the route defined by the Target SpaceWire Address and Target Logical Address parameters. 5.2.3

CCSDS_PACKET_RECEIVED.indication

Function

the 

target, 

5.2.3.1

a.

At 

a CCSDS_PACKET_RECEIVED.indication  to  the  CCSDS  Packet  Service user to deliver a Packet.  

provider 

service 

the 

shall 

pass 

Semantics

5.2.3.2

a.

The  CCSDS_PACKET_RECEIVED.indication  primitive  shall  provide parameters as follows:  

1.

(CCSDS  Packet,  User CCSDS_PACKET_RECEIVED.indication 

Application Value, Status)  

b.

c.

If the packet arrived is terminated by EEP or the Reserved field is non‐zero the CCSDS Packet and the User Application Value shall be null. 

The Status parameter shall be one of the following codes: 

1.

2.

3.

0x00 indicates that the packet arrived with no known error, 

0x01 indicates that the packet arrived terminated by EEP, 

0x02 indicates that the Reserved field was non‐zero. 

5.2.3.3  When Generated

a.

The  CCSDS_PACKET_RECEIVED.indication  primitive  shall  be  passed from the service provider to the CCSDS Packet Service user at the target to deliver a CCSDS Packet. 

Effect On Receipt

5.2.3.4

a.

The  effect  of  receipt  of  the  CCSDS_PACKET_RECEIVED.indication primitive by the CCSDS Packet Service user shall be defined by the user.5.2.3.5  Additional Comments

a.

The  CCSDS_PACKET_RECEIVED.indication  primitive  shall  be  used  to deliver CCSDS Packets to the CCSDS Packet Service user at the target. 14 ![Im0](images/Im0)

![Im0](images/Im0)

- 5.3  CCSDS Packet Transfer Protocol fields

ECSS‐E‐ST‐50‐53C 5 February 2010 5.3.1

a.

Target SpaceWire Address field

The  Target  SpaceWire  Address  field  shall  comprise  zero  or  more  data characters  forming  the  SpaceWire  address  which  is  used  to  route  the CCSDS Packet Transfer Protocol packet to the target. 

NOTE

The  Target  SpaceWire  Address  is  stripped  off 

by the time the packet reaches the target. 

b.

c.

SpaceWire path addressing and regional addressing may be used. 

The  Target  SpaceWire  Address  field  shall  not  be  used  when  a  single logical  address  is  being  used  for  routing  the  CCSDS  Packet  Transfer Protocol packet to the target. 

NOTE

In this case the CCSDS Packet Transfer Protocol 

packet  is  routed  to  the  target  by  the  Target 

Logical Address contained in the Target Logical 

Address field. 

Target Logical Address field

Target Logical Address field shall be an 8‐bit field that contains a logical address of the target. 

NOTE 1  The Target Logical Address field is normally set to 

NOTE 2 

a logical address recognised by the target. 

If  the  target  does  not  have  a  specific  logical 

address then the Target Logical Address field can 

be set to the default value 254 (0xFE). 

NOTE 3  A target can have more than one logical address. 

Protocol Identifier field

5.3.2

a.

5.3.3

a.

b.

5.3.4

a.

5.3.5

a.

The  Protocol  Identifier  field  shall  be  an  8‐bit  field  that  contains  the Protocol Identifier. 

The Protocol Identifier field shall be set to the value 2 (0x02) which is the Protocol Identifier for the CCSDS Packet Encapsulation Protocol. 

Reserved field

The Reserved shall be an 8‐bit field that is set to 0x00. 

User Application field

The  User  Application  field  shall  be  an  8‐bit  field  which  is  transferred along with the CCSDS packet to the Target.  

NOTE 1 

Its value and use is user specific. 

15 ECSS‐E‐ST‐50‐53C 5 February 2010 NOTE 2 

If for example the target supports virtual channels, 

the  User  Application  field  can  be  set  to  a  virtual 

channel number. 

Packet field

The CCSDS Packet field shall be a variable length field that contains the CCSDS Packet. 

The  first  byte  of  the  CCSDS  Packet  field  shall  be  the  first  byte  of  the CCSDS Packet. 

The byte order of the CCSDS Packet field shall be the same as the CCSDS Packet. 

5.3.6

a.

b.

c.

- 5.4  CCSDS Packet Transfer Protocol format

Fields

5.4.1.1

a.

The  CCSDS  Packet  Transfer  Protocol  packet  shall  contain  the  fields shown in Figure 5‐1. 

First byte transmitted

Target SpW Address

Target Logical Address

Protocol Identifier

CCSDS Packet

(First Byte)

CCSDS Packet

CCSDS Packet

CCSDS Packet

...

CCSDS Packet

(Last Byte)

Last byte transmitted

EOP

….

Target SpW Address

Reserved = 0x00

CCSDS Packet

...

User Application

CCSDS Packet

CCSDS Packet

Figure 5‐1: Encapsulated CCSDS Packet format 

Target SpaceWire Address field

The Target SpaceWire Address field shall be as defined in clause 5.3.1. Target Logical Address field

The Target Logical Address field shall be as defined in clause 5.3.2.  

5.4.1.2

a.

5.4.1.3

a.

5.4.1.4

a.

Protocol Identifier field

The Protocol Identifier field shall be as defined in clause 5.3.3. 

5.4.1.5  Reserved field

a.

The Reserved field format shall be as defined in clause 5.3.4. 

16 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 5.4.1.6  User Application field

a.

The User Application field format shall be as defined in clause 5.3.5. 

5.4.1.7  CCSDS Packet field

a.

The CCSDS Packet field format shall be as defined in clause 5.3.6. 

EOP character

5.4.1.8

a.

The end of the CCSDS Packet Transfer Protocol packet shall be indicated by an EOP character. 

- 5.5  CCSDS Packet Transfer Protocol Action

5.5.1  Overview

The  normal  sequence  of actions  for a CCSDS  Packet  Transfer  Protocol  packet transfer is illustrated in Figure 5‐2. 

Initiator

Target

1. Send Request

2. Transfer

Packet

Figure 5‐2: CCSDS Packet Transfer Protocol Packet Transfer 

3. Receive Indication

5.5.2

a.

b.

Send request

The CCSDS Packet Transfer Protocol packet transfer shall begin when an initiator  user  application  requests  to  send  a  CCSDS  Packet  Transfer Protocol packet (Send Request).  

The initiator user application shall pass the following information to the initiator: 

1.

2.

3.

4.

5.

Target SpaceWire Address 

Target Logical Address 

CCSDS Packet 

Packet Length 

User Application Value 

17 ![Im0](images/Im0)

ECSS‐E‐ST‐50‐53C 5 February 2010 c.

If the Packet Length of the CCSDS Packet is greater than the maximum acceptable length, the following shall be done: 

1.

2.

Reject the Send Request 

Inform the initiator user application. 

Transfer packet

5.5.3

a.

In  response  to  the  send  request  the  initiator  shall  encapsulate  the CCSSDS Space Packet into a SpaceWire packet as described in clause 5.4 and send it across the SpaceWire network to the target (Transfer Packet). NOTE

The  Target  SpaceWire  Address  and  Target 

Logical  Address  are  used 

the 

command packet to the target. 

to  route 

5.5.4

Receive indication

Protocol identifier

5.5.4.1

a.  When  a  SpaceWire  packet  is  received  at  the  target  and  the  Protocol Identifier  field  is  0x02  the  packet  shall  be  regarded  as  a  CCSDS  Packet Transfer Protocol packet. 

5.5.4.2  Reserved field zero

a.

If the CCSDS Packet Transfer Protocol packet arrives at the target with the Reserved field set to 0x00 and is terminated by an EOP, the CCSDS Packet  shall  be  extracted  from  the  SpaceWire  packet  and  passed  to  the target user application. 

If the CCSDS Packet Transfer Protocol packet arrives at the target with the Reserved field set to 0x00 and is terminated by an EOP, the value of the User Application field shall be passed to the target user application. b.

b.

5.5.4.3  Reserved field not zero

a.

If the CCSDS Packet Transfer Protocol packet arrives at the target with the Reserved field set to a non‐zero value and is terminated by an EOP the CCSDS Packet Transfer Protocol packet shall be discarded,  

If the CCSDS Packet Transfer Protocol packet arrives at the target with the Reserved field set to a non‐zero value and is terminated by an EOP, the  target  user  application  should  be  informed  that  an  invalid  CCSDS Packet Transfer Protocol packet has been received. 

Error End of Packet

5.5.4.4

a.

If  the  CCSDS  Packet  Transfer  Protocol  packet  arrives  at  the  target terminated by an EEP, the CCSDS Packet Transfer Protocol packet shall be discarded. 

18 ![Im0](images/Im0)

![Im0](images/Im0)

b.

If  the  CCSDS  Packet  Transfer  Protocol  packet  arrives  at  the  target terminated  by  an  EEP,  the  target  user  application  should  be  informed that an invalid CCSDS Packet Transfer Protocol packet has been received. ECSS‐E‐ST‐50‐53C 5 February 2010 19 ECSS‐E‐ST‐50‐53C 5 February 2010 Annex A (informative)Managed parametersIn order to provide an optimised implementation, some parameters associated with  the  CCSDS  Packet  Transfer  service  are  handled  by  management,  rather than  by  inline  communications  protocol.  The  managed  parameters  are  those which tend to be static for long periods of time, and whose change generally signifies  a  major  reconfiguration  of  the  service  provider  associated  with  a particular  mission.  Through  the  use  of  a  management  system,  management conveys the required information to the service provider. 

The managed parameters used for the CCSDS Packet Transfer Service are listed in  Table  A‐1.  These  parameters  are  defined  in  an  abstract  sense,  and  are  not intended to imply any particular implementation of a management system.  The  value  of 

implementation. 

these  parameters  are  defined 

for  a  specific  mission ![Im0](images/Im0)

<table align="center">
	<tr align="center">
		<td>Managed parameter </td>
		<td>Allowed value </td>
	</tr>
	<tr align="center">
		<td>Minimum CCSDS Space packet length  (bytes) </td>
		<td>Integer </td>
	</tr>
	<tr align="center">
		<td>Maximum CCSDS Space packet size  (bytes) </td>
		<td>Integer </td>
	</tr>
</table>

 

20 ECSS‐E‐ST‐50‐53C 5 February 2010 BibliographyECSS‐ST‐S‐00 

ECSS system ‐ Description, implementation and general requirements 

http://www.spacewire.esa.int  SpaceWire website 

 

21 ![Im0](images/Im0)

