-   [Change log](#change-log)
-   [Table of contents](#table-of-contents)
    -   [\
        Scope](#scope)
    -   [\
        Normative references](#normative-references)
        -   [Terms specific to the present
            standard](#terms-specific-to-the-present-standard)
        -   [Abbreviated terms](#abbreviated-terms)
        -   [Conventions](#conventions)
    -   [\
        Principles](#principles)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-50-51C(5February2010).docx1//media/image1.png){width="4.157638888888889in"
height="2.55in"}

Space engineering

SpaceWire protocol identification

**Foreword**

This Standard is one of the series of ECSS Standards intended to be
applied together for the management, engineering and product assurance
in space projects and applications. ECSS is a cooperative effort of the
European Space Agency, national space agencies and European industry
associations for the purpose of developing and maintaining common
standards. Requirements in this Standard are defined in terms of what
shall be accomplished, rather than in terms of how to organize and
perform the necessary work. This allows existing organizational
structures and methods to be applied where they are effective, and for
the structures and methods to evolve as necessary without rewriting the
standards.

This Standard has been prepared by the ECSS-E-ST-50-51 Working Group,
reviewed by the ECSS Executive Secretariat and approved by the ECSS
Technical Authority.

**Disclaimer**

ECSS does not provide any warranty whatsoever, whether expressed,
implied, or statutory, including, but not limited to, any warranty of
merchantability or fitness for a particular purpose or any warranty that
the contents of the item are error-free. In no respect shall ECSS incur
any liability for any damages, including, but not limited to, direct,
indirect, special, or consequential damages arising out of, resulting
from, or in any way connected to the use of this Standard, whether or
not based upon warranty, contract, tort, or otherwise; whether or not
injury was sustained by persons or property or otherwise; and whether or
not loss was sustained from, or arose out of, the results of, the item,
or any services that may be provided by ECSS.

Published by: ESA Requirements and Standards Division

ESTEC, P.O. Box 299,

2200 AG Noordwijk

The Netherlands

Copyright: 2010 © by the European Space Agency for the members of ECSS

 Change log

  ------------------ --------------
  ECSS-E-ST-50-51A   Never issued

  ECSS-E-ST-50-51B   Never issued

  ECSS-E-ST-50-51C   First issue
                     
  5 February 2010    
  ------------------ --------------

 Table of contents {#table-of-contents .Contents}

[Change log 3](#change-log)

[1 Scope 5](#scope)

[2 Normative references 6](#normative-references)

[3 Terms, definitions and abbreviated terms
7](#terms-definitions-and-abbreviated-terms)

[3.1 Terms defined in other standards
7](#terms-defined-in-other-standards)

[3.2 Terms specific to the present standard
7](#terms-specific-to-the-present-standard)

[3.3 Abbreviated terms 9](#abbreviated-terms)

[3.4 Conventions 9](#conventions)

[4 Principles 10](#principles)

[5 Requirements 11](#requirements)

[5.1 Overview 11](#overview)

[5.2 Protocol identification 11](#protocol-identification)

[5.2.1 Addressing 11](#addressing)

[5.2.2 Protocol Identifier 12](#protocol-identifier)

[5.2.3 Extended Protocol Identifier 12](#extended-protocol-identifier)

[5.2.4 Ignoring unknown protocols 13](#ignoring-unknown-protocols)

[5.2.5 Protocol Identifier and Extended Protocol Identifier Allocation
13](#protocol-identifier-and-extended-protocol-identifier-allocation)

[Bibliography 15](#bibliography)

Figures

[Figure 5‑1: Protocol Identifier position
12](#__RefHeading___Toc253409777)

[Figure 5‑2: Extended Protocol Identifier
13](#__RefHeading___Toc253409778)

Tables

[Table 5‑1: Protocol identifier allocation
14](#__RefHeading___Toc253409779)

\
Scope
=====

There is a number of communication protocols that can be used in
conjunction with the SpaceWire Standard (ECSS-E-ST-50-12), to provide a
comprehensive set of services for onboard user applications. These
protocols are covered by the ECSS-E-ST-50-5x series.

To distinguish between the various protocols a protocol identifier is
used. This Standard specifies this protocol identifier.

This standard may be tailored for the specific characteristic and
constrains of a space project in conformance with ECSS-S-ST-00.

\
Normative references
====================

The following normative documents contain provisions which, through
reference in this text, constitute provisions of this ECSS Standard. For
dated references, subsequent amendments to, or revision of any of these
publications do not apply. However, parties to agreements based on this
ECSS Standard are encouraged to investigate the possibility of applying
the more recent editions of the normative documents indicated below. For
undated references, the latest edition of the publication referred to
applies.

  ---------------------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------
  ECSS-S-ST-00-01                                                                                                  ECSS system - Glossary of terms
  ECSS-E-ST-50-12                                                                                                  Space engineering - SpaceWire - Links, nodes, routers and networks
  ECSS-E-ST-50-52                                                                                                  Space engineering - SpaceWire - Remote memory access protocol
  ECSS-E-ST-50-53                                                                                                  Space engineering - SpaceWire - CCSDS packet transfer protocol
  CCSDS 133.0-B-1                                                                                                  Space Packet Protocol, Blue Book
  [[[]{#OLE_LINK7 .anchor}]{#OLE_LINK8 .anchor}]{#_Hlk231116672 .anchor}SMCS-ASTD-PS-001 Issue 1.1, 24 July 2009   STUP SpaceWire Protocol - Protocol Specification, EADS Astrium ASE4
  417-R-RTP-0050 Version 2.1, 16 January 2008                                                                      Geostationary Operational Environmental Satellites (GOES), GOES-R Series, GOES-R Reliable Data Delivery Protocol (GRDDP), NASA Goddard Spaceflight Centre
  ---------------------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms defined in other standards
        --------------------------------

[]{#_Ref160615816 .anchor}For the purpose of this Standard, the terms
and definitions from ECSS-S-ST-00-01 apply.

Terms specific to the present standard
--------------------------------------

1.  byte

8-bits where bit 7 is the most-significant bit

1.  command

instruction to a SpaceWire node (target) to perform some action

1.  For example, write data to memory.

<!-- -->

1.  command packet

packet that contains a command

1.  confirmation

primitive passed from a service provider to a service user to indicate
the success or otherwise of a previous service request

1.  data character

SpaceWire symbol containing 8-bits of user information

1.  Error End of Packet marker (EEP)

control character indicating that the Packet was terminated prematurely

1.  End of Packet marker (EOP)

control character indicating the end of a packet

1.  extender protocol identifier

two data characters following a protocol identifier which has value 0x00
that identify a particular protocol being used for communication

1.  indication

primitive passed from a service provider to a service user to provide
information or status to the service user

1.  initiator

SpaceWire node that starts a transaction by sending a command to a
SpaceWire node

1.  initiator user application

application in an initiator that is using the SpaceWire protocol
services

1.  logical address

identifier of a initiator or target which can be used to route a Packet
to the target or, if path addressing is being used, to confirm that the
final target is the correct one i.e. that the logical address of the
target matches the logical address in the packet

1.  memory

addressable storage element including random access memory, registers,
FIFO, mailboxes

1.  packet

SpaceWire packet

1.  path address

sequence of one or more SpaceWire data characters that defines the route
to a target by specifying, for each router encountered on the way to the
target, the output port that a Packet is forwarded through

1.  protocol identifier

data character that identifies a particular protocol being used for
communication

1.  reply

response sent by a target to the initiator or some other node expecting
the reply to provide the required information or to indicate that some
commanded action has been completed by the target

1.  reply packet

packet containing a reply

1.  request

primitive passed from a service user to a service provider to request a
service

1.  response

primitive passed from a service user to a service provider in response
to an indication from the service provider

1.  target

SpaceWire node that responds to a command sent by an initiator

1.  target user application

application in a target that is using the SpaceWire protocol services

1.  transaction

interaction between an initiator and a target

1.  word

multiple bytes held in a single memory location

Abbreviated terms
-----------------

The following abbreviations are defined and used within this standard:

  -------------- -----------------------------------------------
  Abbreviation   Meaning
  CCSDS          Consultative Committee for Space Data Systems
  EEP            error end of packet
  EOP            end of packet
  FIFO           first in first out
  ID             identifier
  RMAP           remote memory access protocol
  VHSIC          very high speed integrated circuit
  -------------- -----------------------------------------------

Conventions
-----------

In this document hexadecimal numbers are written with the prefix 0x, for
example 0x34 and 0xDF15.

Binary numbers are written with the prefix 0b, for example 0b01001100
and 0b01.

Decimal numbers have no prefix.

\
Principles
==========

To distinguish between the various protocols that can be used in
conjunction with the SpaceWire protocol defined in ECSS-E-ST-50-12, a
protocol identifier is used. This standard specifies such a protocol
identifier. The protocols that operate over SpaceWire are then specified
in the ECSS-E-ST-50-5x series of standards.

Examples of these protocols are:

-   Remote Memory Access Protocol (RMAP)

The aim of RMAP is to support reading from and writing to memory in a
remote SpaceWire node. RMAP can be used to configure a SpaceWire
network, control SpaceWire nodes, and to transfer data to and from
SpaceWire nodes. RMAP is specified in ECSS-E-ST-50-52.

-   CCSDS Packet Transfer Protocol

The aim of the CCSDS Packet Transfer Protocol is to transfer CCSDS
Packets across a SpaceWire network. It does this by encapsulating the
CCSDS Packet in a SpaceWire packet, transferring it across the SpaceWire
network and then extracting the CCSDS Packet at the target. The CCSDS
Packet Transfer Protocol is specified in ECSS-E-ST-50-53.

1.  \
    Requirements
    ============

    1.  Overview
        --------

The protocol identification scheme enables many different protocols to
operate concurrently over a SpaceWire network without them interfering
with each other. To achieve this, an identifier is given to each
protocol. Nodes receiving packets process and respond to them according
to the protocol specified by the Protocol Identifier in the packet. If a
packet arrives with a particular Protocol Identifier that is not
supported by a node then it is ignored.

1.  Protocol identification
    -----------------------

    1.  ### Addressing

        a.  A packet containing a Protocol Identifier shall start with a
            single byte logical address when it arrives at the target.

<!-- -->

1.  1 See Figure Requirements-1.

2.  2 When sent by the initiator the packet can have one or more leading
    > path or logical address bytes which are stripped off (SpaceWire
    > Address) on the way through the SpaceWire network leaving the
    > single logical address byte when it arrives at the target.

    a.  The logical address 254 (0xFE) shall be used as a default value
        when the target does not have another value specified for its
        logical address.

<!-- -->

1.  When the initiator does not know the logical address of the target
    > the default logical address 254 (0xFE) can be used.

    a.  A target may choose to ignore packets with logical address 254
        (0xFE).

2.  If a packet with a logical address is ignored then the target can
    > record and make available a count of the number of packets it
    > received and ignored with logical address 254 (0xFE).

    a.  A target may accept packets with one or more different logical
        address values.

3.  For example, a node accepting packets with logical addresses 60, 61
    > or 254.

    1.  ### Protocol Identifier 

        a.  A Protocol Identifier shall comprise a single byte
            immediately following the logical address.

4.  See Figure Requirements-1.

    a.  A value of zero shall be used to identify an Extended Protocol
        Identifier.

5.  The value of zero in the Protocol Identifier byte is reserved for
    > extension of the Protocol Identifier, as specified in clause
    > 5.2.3.

    a.  A Protocol Identifier with a value of 255 (0xFF) shall not be
        used.

6.  It is reserved for future use.

[[[[]{#_1298288789 .anchor}]{#_1298289229 .anchor}]{#_1298289377
.anchor}]{#_1298289743 .anchor}

[[]{#_Ref86915060 .anchor}]{#__RefHeading___Toc253409777 .anchor}Figure
Chapter‑1: Protocol Identifier position

1.  ### Extended Protocol Identifier

    a.  If an Extended Protocol Identifier is supported, the following
        shall apply:

        1.  Protocol Identifier has the value zero (0x00).

        2.  The two bytes following the reserved Protocol Identifier
            (zero) form a 16-bit Extended Protocol Identifier.

<!-- -->

1.  1 This allows up to 65535 protocols to be carried over a SpaceWire
    > network.

2.  2 An Extended Protocol Identifier need not be implemented.

3.  3 See Figure Requirements-2.

    a.  If an Extended Protocol Identifier is not supported, then a
        packet with a Protocol Identifier with the value zero (reserved
        Protocol Identifier) shall be discarded when received.

<!-- -->

1.  If a target ignores the Extended Protocol Identifier then it can
    > record and make available a count of the number of packets it
    > received with an Extended Protocol Identifier.

    a.  Extended Protocol Identifiers with values in the range 0x0000 to
        0x00FF are reserved and shall not be used.

    b.  A packet with an Extended Protocol Identifier with a value in
        the range 0x0000 to 0x00FF shall be discarded when received.

2.  These values are reserved for future use.

[[[]{#_1298288829 .anchor}]{#_1298289332 .anchor}]{#_1298289983 .anchor}

[[]{#_Ref86915234 .anchor}]{#__RefHeading___Toc253409778 .anchor}Figure
Chapter‑2: Extended Protocol Identifier

1.  ### Ignoring unknown protocols

    a.  If a packet arrives with a Protocol Identifier or Extended
        Protocol Identifier that is not supported (unknown) by that
        target then the packet shall be discarded.

<!-- -->

1.  The target can count the number of packets that arrive at a target
    > with unknown Protocol Identifier or Extended Protocol Identifier
    > can be kept and made available by the target.

    1.  ### Protocol Identifier and Extended Protocol Identifier Allocation

        a.  Protocol Identifiers in the range 1 to 239 (0x01 to 0xEF)
            that shall be used are those listed in Table Requirements-1.

<!-- -->

1.  1 The identifiers in Table Requirements-1 have been assigned by the
    > SpaceWire working group. The protocols starting at number 1 and
    > working upwards as defined in this standard document define the
    > current set of approved SpaceWire protocols and their Protocol
    > Identifiers. The protocols starting at 239 and working downwards
    > are legacy protocols and are not covered by this standard
    > document.

2.  2 The reader is advised to consult the SpaceWire website
    > (http://www.spacewire.esa.int) for the latest Table defining the
    > Protocol Identifiers and Extended Protocol Identifier allocation.

    a.  Protocol Identifiers in the range 240 to 254 (0xF0 to 0xFE)
        shall be assigned by the project.

3.  1 Developers can use these Protocol Identifiers but it is important
    > to note that they can clash with protocols being developed by
    > other users. Concurrent operation of different protocols is only
    > assured for Protocol Identifiers in the range 1 to 239 (0x01 to
    > 0xEF).

4.  2 Proven protocols can be recommended for adoption by the SpaceWire
    > working group and then be included in future revisions or
    > extensions to this SpaceWire Protocols standard. Once adopted they
    > are given a unique Protocol Identifier in the range 1 to 239.

5.  3 No Extended Protocol Identifiers have been allocated.

[[]{#_Ref183316653 .anchor}]{#__RefHeading___Toc253409779 .anchor}Table
Chapter‑1: Protocol identifier allocation

  --------------------- ---------------------------------------- ---------------------------------------------
  Protocol Identifier   Protocol                                 Specified in
  0                     Extended Protocol Identifier             Clause 5
  1                     Remote Memory Access Protocol            ECSS-E-ST-50-52
  2                     CCSDS Packet Transfer Protocol           ECSS-E-ST-50-53
  238                   GOES-R Reliable Data Delivery Protocol   417-R-RTP-0050 Version 2.1, 16 January 2008
  239                   Serial Transfer Universal Protocol       SMCS-ASTD-PS-001 Issue 1.1, 24 July 2009
  --------------------- ---------------------------------------- ---------------------------------------------

 Bibliography

  ------------------------------ --------------------------------------------------------------------
  ECSS-ST-S-00                   ECSS system - Description, implementation and general requirements
  http://www.spacewire.esa.int   SpaceWire website
  ------------------------------ --------------------------------------------------------------------
