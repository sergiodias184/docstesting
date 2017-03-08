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
        -   [Protocol features](#protocol-features)
        -   [Services ](#services)
        -   [Guide to this document](#guide-to-this-document)
-   [Bibliography](#bibliography)

![](/home/sdias/Desktop/papper_docs/ecss/1-Active_ECSS/generated/ECSS-E-ST-50-53C(5February2010).docx1//media/image1.png){width="4.157638888888889in"
height="2.55in"}

Space engineering

SpaceWire - CCSDS packet transfer protocol

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

This Standard has been prepared by the ECSS-E-ST-50-53 Working Group,
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
  ECSS-E-ST-50-53A   Never issued

  ECSS-E-ST-50-53B   Never issued

  ECSS-E-ST-50-53C   First issue
                     
  5 February 2010    
  ------------------ --------------

 Table of contents {#table-of-contents .ListParagraph .Contents}

[Change log 3](#change-log)

[1 Scope 6](#scope)

[2 Normative references 7](#normative-references)

[3 Terms, definitions and abbreviated terms
8](#terms-definitions-and-abbreviated-terms)

[3.1 Terms defined in other standards
8](#terms-defined-in-other-standards)

[3.2 Terms specific to the present standard
8](#terms-specific-to-the-present-standard)

[3.3 Abbreviated terms 8](#abbreviated-terms)

[3.4 Conventions 8](#conventions)

[4 Principles 9](#principles)

[4.1 Purpose 9](#purpose)

[4.2 Protocol features 9](#protocol-features)

[4.3 Services 10](#services)

[4.4 Guide to this document 11](#guide-to-this-document)

[5 Requirements 12](#requirements)

[5.1 Service parameters 12](#service-parameters)

[5.1.1 CCSDS packet 12](#ccsds-packet)

[5.1.2 Packet length 12](#packet-length)

[5.1.3 Status code 12](#status-code)

[5.1.4 Target SpaceWire Address 12](#target-spacewire-address)

[5.1.5 Target Logical Address 13](#target-logical-address)

[5.1.6 User Application Value 13](#user-application-value)

[5.2 Service primitives 13](#service-primitives)

[5.2.1 CCSDS Packet Transfer Service 13](#ccsds-packet-transfer-service)

[5.2.2 CCSDS\_PACKET\_SEND.request 13](#ccsds_packet_send.request)

[5.2.3 CCSDS\_PACKET\_RECEIVED.indication
14](#ccsds_packet_received.indication)

[5.3 CCSDS Packet Transfer Protocol fields
15](#ccsds-packet-transfer-protocol-fields)

[5.3.1 Target SpaceWire Address field
15](#target-spacewire-address-field)

[5.3.2 Target Logical Address field 15](#target-logical-address-field)

[5.3.3 Protocol Identifier field 15](#protocol-identifier-field)

[5.3.4 Reserved field 15](#reserved-field)

[5.3.5 User Application field 15](#user-application-field)

[5.3.6 Packet field 16](#packet-field)

[5.4 CCSDS Packet Transfer Protocol format
16](#ccsds-packet-transfer-protocol-format)

[5.5 CCSDS Packet Transfer Protocol Action
17](#ccsds-packet-transfer-protocol-action)

[5.5.1 Overview 17](#overview)

[5.5.2 Send request 17](#send-request)

[5.5.3 Transfer packet 18](#transfer-packet)

[5.5.4 Receive indication 18](#receive-indication)

[Annex A (informative) Managed parameters
20](#__RefHeading___Toc253409315)

[Bibliography 21](#bibliography)

Figures

[Figure 4‑1: Protocol configuration 9](#__RefHeading___Toc253409317)

[Figure 5‑1: Encapsulated CCSDS Packet format
16](#__RefHeading___Toc253409318)

[Figure 5‑2: CCSDS Packet Transfer Protocol Packet Transfer
17](#__RefHeading___Toc253409319)

\
Scope
=====

There is a number of communication protocols that can be used in
conjunction with the SpaceWire Standard (ECSS-E-ST-50-12), to provide a
comprehensive set of services for onboard user applications. To
distinguish between the various protocols a protocol identifier is used,
as specified in ECSS-E-ST-50-51.

This Standard specifies the CCSDS packet transfer protocol, which is one
of these protocols that works over SpaceWire.

The aim of the CCSDS Packet Transfer Protocol is to transfer CCSDS
Packets across a SpaceWire network. It does this by encapsulating the
CCSDS Packet in a SpaceWire packet, transferring it across the SpaceWire
network and then extracting the CCSDS Packet at the target.

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

  ----------------- -------------------------------------------------------------------- --
  ECSS-S-ST-00-01   ECSS system - Glossary of terms
  ECSS-E-ST-50-12   Space engineering - SpaceWire - Links, nodes, routers and networks
  ECSS-E-ST-50-51   Space engineering - SpaceWire protocol identification
  CCSDS 133.0-B-1   Space Packet Protocol, Blue Book
  ----------------- -------------------------------------------------------------------- --

1.  \
    Terms, definitions and abbreviated terms
    ========================================

    1.  Terms defined in other standards
        --------------------------------

[]{#_Ref160615816 .anchor}For the purpose of this Standard, the terms
and definitions from ECSS-S-ST-00-01 and ECSS-E-ST-50-51 apply.

Terms specific to the present standard
--------------------------------------

None.

Abbreviated terms
-----------------

The following abbreviations are defined and used within this standard:

  -------------- -----------------------------------------------
  Abbreviation   Meaning
  CCSDS          Consultative Committee for Space Data Systems
  EEP            error end of packet
  EOP            end of packet
  SpW            SpaceWire
  -------------- -----------------------------------------------

Conventions
-----------

In this document hexadecimal numbers are written with the prefix 0x, for
example 0x34 and 0xDF15.

Binary numbers are written with the prefix 0b, for example 0b01001100
and 0b01.

Decimal numbers have no prefix.

1.  \
    Principles
    ==========

    1.  Purpose
        -------

The CCSDS Packet Transfer Protocol has been designed to encapsulate a
CCSDS Space Packet into a SpaceWire packet, transfer it from an
initiator to a target across a SpaceWire network, extract it from the
SpaceWire packet and pass it to a target user application. This protocol
does not provide any means for ensuring delivery of the packet nor is it
responsible for the contents of the packet being a CCSDS Space Packet.

The CCSDS Space Packet Protocol is defined in the following document:

CCSDS 133.0-B-1 Space Packet Protocol. Blue Book. Issue 1. September
2003 or a later issue

Figure Principles-1 illustrates the location of the CCSDS Space Packet
transfer Protocol in a typical onboard protocol stack. The CCSDS Space
Packet transfer Protocol provides a unidirectional data transfer service
from a single source user application to a single destination user
application through a SpaceWire network.

[[]{#_Ref205033844 .anchor}]{#__RefHeading___Toc253409317 .anchor}Figure
Chapter‑1: Protocol configuration

Protocol features
-----------------

The CCSDS Space Packet transfer Protocol provides the capability to
transfer CCSDS Space Packets between onboard users of a SpaceWire
network. The CCSDS space packets may be of variable length or fixed size
at the discretion of the user and may be submitted for transmission at
variable intervals. The composition of the CCSDS space packet is under
the responsibility of the user application and is not checked by the
CCSDS space packet transfer protocol.

Services 
---------

The CCSDS Space Packet Transfer Protocol provides users with data
transfer services. The point at which a service is provided by a
protocol entity to a user is called a Service Access Point. A Service
Access Point of the Space Packet Transfer Protocol is identified by a
SpaceWire address and each service user is also identified by a
SpaceWire Address.

Service data units submitted to a Service Access Point are processed in
the order of submission.

Implementations may be required to perform flow control at a Service
Access Point between the service user and the service provider. However,
this standard does not recommend a scheme for flow control between the
user and the provider.

The followings features are offered by the data transfer service defined
in this Standard:

-   Unidirectional (one way) data transfer service.

-   Asynchronous Service. There are no predefined timing rules for the
    transfer of service data units supplied by the service user. The
    user may request data transfer at any time it desires, but there may
    be restrictions imposed by the provider on the data generation rate.

-   Unconfirmed Service: the sending user does not receive confirmation
    from the receiving end that data has been received.

-   Incomplete Services. The services do not guarantee completeness, nor
    do they provide a retransmission mechanism.

-   SDU format: the service does not check the format of the submitted
    CCSDS Space packet.

-   Non sequence Preserving Service. The sequence of service data units
    supplied by the sending user may not be preserved through the
    underlying network

The end-to-end quality-of-service provided to service users is the one
that is provided by the underlying SpaceWire network. The Space Packet
Transfer Protocol does not provide any mechanisms for guaranteeing a
particular quality-of-service; it is the responsibility of implementing
organizations to ensure that the end-to-end performance of a particular
service instance meets the requirements of its users.

[[]{#OLE_LINK3 .anchor}]{#OLE_LINK4 .anchor}Sequence preservation of
packets in a SpaceWire network is dependent on the underlying network
topology and configuration. Topologies and configurations which allow
only a single route from the source to the destination, i.e.
configurations that are not using group adaptive routing, are sequence
preserving.

Guide to this document
----------------------

Clause 4 presents the purpose, protocol features and an overview of the
services the CCSDS packet transfer protocol offers.

Clause 5.1 defines the service parameters.

Clause 5.2 specifies the service primitives provided by the protocol.

Clause 5.3 defines the protocol fields used in the CCSDS packet transfer
protocol packets.

Clause 5.4 specifies the format of the packets used by the CCSDS packet
transfer protocol.

Clause 5.5 specified the action of the CCSDS packet transfer protocol.

Annex A lists the managed parameters associated with this protocol.

1.  \
    Requirements
    ============

    1.  Service parameters
        ------------------

        1.  ### CCSDS packet

            a.  The CCSDS packet parameter, intended as the service data
                unit transferred by the CCSDS packet transfer service,
                shall be the CCSDS Space Packet as defined in CCSDS
                133.0-B-1 Space Packet Protocol, Blue Book, Issue 1,
                September 2003.

        2.  ### Packet length

            a.  The value of the packet length shall be equal to at
                least 7 and at most 65542 octets.

            b.  Individual project organizations may establish the
                maximum length for a particular mission.

<!-- -->

1.  The length parameter defines the length of the Data Unit submitted
    > by the user.

    1.  ### Status code

        a.  The Status code parameter shall be used to indicate the
            validity of the packet to the receiving service user.

        b.  The Status code parameter shall take one of the following
            values:

            1.  0x00 indicates that the packet is ok

            2.  0x01 indicates packet arrived terminated by EEP

            3.  0x02 indicates reserved field was non-zero

    2.  ### Target SpaceWire Address

        a.  The Target SpaceWire Address parameter shall be used to
            define the path to the Target when SpaceWire path addressing
            is being used.

    3.  ### Target Logical Address

        a.  The Target Logical Address parameter shall be used to define
            the logical address of the Target that is to receive the
            CCSDS packet.

    4.  ### User Application Value

        a.  The User Application Value shall be an 8-bit value which is
            transferred along with the CCSDS packet to the Target.

2.  Its value and use is user specific.

    1.  Service primitives
        ------------------

        1.  ### CCSDS Packet Transfer Service

            a.  The service primitives associated with this service
                shall be the following

                1.  CCSDS\_PACKET\_SEND.request,

                2.  CCSDS\_PACKET\_RECEIVE.indication.

        2.  ### CCSDS\_PACKET\_SEND.request

            1.  #### Function 

                a.  At the initiator, the CCSDS Packet Transfer service
                    user shall pass a CCSDS\_PACKET\_SEND.request
                    primitive to the service provider to request that a
                    CCSDS Packet is transferred to the user at the
                    target across the SpaceWire network.

            2.  #### Semantics 

                a.  The CCSDS\_PACKET.request primitive shall provide
                    the following parameters:

                    1.  CCSDS\_PACKET\_SEND.request (CCSDS Packet,
                        Packet Length, Target SpaceWire Address, Target
                        Logical Address, User Application Value).

            3.  #### When Generated 

                a.  The CCSDS\_PACKET\_SEND.request primitive shall be
                    passed to the service provider to request it to send
                    the CCSDS Packet.

            4.  #### Effect On Receipt 

                a.  Receipt of the CCSDS\_PACKET\_SEND.request primitive
                    shall cause the service provider to transfer the
                    CCSDS Packet.

            5.  #### Additional Comments 

                a.  The CCSDS\_PACKET\_SEND.request primitive shall be
                    used to transfer CCSDS Packets across the SpaceWire
                    network along the route defined by the Target
                    SpaceWire Address and Target Logical Address
                    parameters.

        3.  ### CCSDS\_PACKET\_RECEIVED.indication 

            1.  #### Function 

                a.  At the target, the service provider shall pass a
                    CCSDS\_PACKET\_RECEIVED.indication to the CCSDS
                    Packet Service user to deliver a Packet.

            2.  #### Semantics 

                a.  []{#_Ref235591714 .anchor}The
                    CCSDS\_PACKET\_RECEIVED.indication primitive shall
                    provide parameters as follows:

                    1.  CCSDS\_PACKET\_RECEIVED.indication (CCSDS
                        Packet, User Application Value, Status)

                b.  If the packet arrived is terminated by EEP or the
                    Reserved field is non-zero the CCSDS Packet and the
                    User Application Value shall be null.

                c.  The Status parameter shall be one of the following
                    codes:

                    1.  0x00 indicates that the packet arrived with no
                        known error,

                    2.  0x01 indicates that the packet arrived
                        terminated by EEP,

                    3.  0x02 indicates that the Reserved field was
                        non-zero.

            3.  #### When Generated 

                a.  The CCSDS\_PACKET\_RECEIVED.indication primitive
                    shall be passed from the service provider to the
                    CCSDS Packet Service user at the target to deliver a
                    CCSDS Packet.

            4.  #### Effect On Receipt 

                a.  The effect of receipt of the
                    CCSDS\_PACKET\_RECEIVED.indication primitive by the
                    CCSDS Packet Service user shall be defined by the
                    user.

            5.  #### Additional Comments 

                a.  The CCSDS\_PACKET\_RECEIVED.indication primitive
                    shall be used to deliver CCSDS Packets to the CCSDS
                    Packet Service user at the target.

    2.  CCSDS Packet Transfer Protocol fields
        -------------------------------------

        1.  ### Target SpaceWire Address field

            a.  The Target SpaceWire Address field shall comprise zero
                or more data characters forming the SpaceWire address
                which is used to route the CCSDS Packet Transfer
                Protocol packet to the target.

3.  The Target SpaceWire Address is stripped off by the time the packet
    > reaches the target.

    a.  SpaceWire path addressing and regional addressing may be used.

    b.  The Target SpaceWire Address field shall not be used when a
        single logical address is being used for routing the CCSDS
        Packet Transfer Protocol packet to the target.

4.  In this case the CCSDS Packet Transfer Protocol packet is routed to
    > the target by the Target Logical Address contained in the Target
    > Logical Address field.

    1.  ### Target Logical Address field

        a.  Target Logical Address field shall be an 8-bit field that
            contains a logical address of the target.

<!-- -->

1.  1 The Target Logical Address field is normally set to a logical
    address recognised by the target.

2.  2 If the target does not have a specific logical address then the
    Target Logical Address field can be set to the default value 254
    (0xFE).

3.  3 A target can have more than one logical address.

    1.  ### Protocol Identifier field

        a.  The Protocol Identifier field shall be an 8-bit field that
            contains the Protocol Identifier.

        b.  The Protocol Identifier field shall be set to the value 2
            (0x02) which is the Protocol Identifier for the CCSDS Packet
            Encapsulation Protocol.

    2.  ### Reserved field

        a.  The Reserved shall be an 8-bit field that is set to 0x00.

    3.  ### User Application field

        a.  [[]{#OLE_LINK5 .anchor}]{#OLE_LINK6 .anchor}The User
            Application field shall be an 8-bit field which is
            transferred along with the CCSDS packet to the Target.

4.  [[]{#ole_link5 .anchor}]{#ole_link6 .anchor}1 Its value and use is
    user specific.

5.  2 If for example the target supports virtual channels, the User
    Application field can be set to a virtual channel number.

    1.  ### Packet field

        a.  The CCSDS Packet field shall be a variable length field that
            contains the CCSDS Packet.

        b.  The first byte of the CCSDS Packet field shall be the first
            byte of the CCSDS Packet.

        c.  The byte order of the CCSDS Packet field shall be the same
            as the CCSDS Packet.

    <!-- -->

    1.  CCSDS Packet Transfer Protocol format
        -------------------------------------

        1.  #### Fields

            a.  The CCSDS Packet Transfer Protocol packet shall contain
                the fields shown in Figure Requirements-2.

[]{#_1298290511 .anchor}

[[]{#_Ref195268226 .anchor}]{#__RefHeading___Toc253409318 .anchor}Figure
Chapter‑2: Encapsulated CCSDS Packet format

1.  #### Target SpaceWire Address field

    a.  The Target SpaceWire Address field shall be as defined in clause
        5.3.1.

2.  #### Target Logical Address field

    a.  The Target Logical Address field shall be as defined in clause
        5.3.2.

3.  #### Protocol Identifier field

    a.  The Protocol Identifier field shall be as defined in clause
        5.3.3.

4.  #### Reserved field

    a.  The Reserved field format shall be as defined in clause 5.3.4.

5.  #### User Application field

    a.  The User Application field format shall be as defined in clause
        5.3.5.

6.  #### CCSDS Packet field

    a.  The CCSDS Packet field format shall be as defined in clause
        5.3.6.

7.  #### EOP character

    a.  The end of the CCSDS Packet Transfer Protocol packet shall be
        indicated by an EOP character.

<!-- -->

1.  CCSDS Packet Transfer Protocol Action
    -------------------------------------

    1.  ### Overview 

The normal sequence of actions for a CCSDS Packet Transfer Protocol
packet transfer is illustrated in Figure Requirements-3.

[]{#_1300780575 .anchor}

[[]{#_Ref195268329 .anchor}]{#__RefHeading___Toc253409319 .anchor}Figure
Chapter‑3: CCSDS Packet Transfer Protocol Packet Transfer

1.  ### Send request

    a.  The CCSDS Packet Transfer Protocol packet transfer shall begin
        when an initiator user application requests to send a CCSDS
        Packet Transfer Protocol packet (Send Request).

    b.  The initiator user application shall pass the following
        information to the initiator:

        1.  Target SpaceWire Address

        2.  Target Logical Address

        3.  CCSDS Packet

        4.  Packet Length

        5.  User Application Value

    c.  If the Packet Length of the CCSDS Packet is greater than the
        maximum acceptable length, the following shall be done:

        1.  Reject the Send Request

        2.  Inform the initiator user application.

2.  ### Transfer packet

    a.  In response to the send request the initiator shall encapsulate
        the CCSSDS Space Packet into a SpaceWire packet as described in
        clause 5.4 and send it across the SpaceWire network to the
        target (Transfer Packet).

<!-- -->

1.  The Target SpaceWire Address and Target Logical Address are used to
    > route the command packet to the target.

    1.  ### Receive indication

        1.  #### Protocol identifier

            a.  When a SpaceWire packet is received at the target and
                the Protocol Identifier field is 0x02 the packet shall
                be regarded as a CCSDS Packet Transfer Protocol packet.

        2.  #### Reserved field zero

            a.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target with the Reserved field set to 0x00 and is
                terminated by an EOP, the CCSDS Packet shall be
                extracted from the SpaceWire packet and passed to the
                target user application.

            b.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target with the Reserved field set to 0x00 and is
                terminated by an EOP, the value of the User Application
                field shall be passed to the target user application.

        3.  #### Reserved field not zero

            a.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target with the Reserved field set to a non-zero
                value and is terminated by an EOP the CCSDS Packet
                Transfer Protocol packet shall be discarded,

            b.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target with the Reserved field set to a non-zero
                value and is terminated by an EOP, the target user
                application should be informed that an invalid CCSDS
                Packet Transfer Protocol packet has been received.

        4.  #### Error End of Packet

            a.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target terminated by an EEP, the CCSDS Packet
                Transfer Protocol packet shall be discarded.

            b.  If the CCSDS Packet Transfer Protocol packet arrives at
                the target terminated by an EEP, the target user
                application should be informed that an invalid CCSDS
                Packet Transfer Protocol packet has been received.

<!-- -->

A.  []{#_Ref205034379 .anchor} []{#__RefHeading___Toc253409315
    .anchor}(informative)\
    Managed parameters

In order to provide an optimised implementation, some parameters
associated with the CCSDS Packet Transfer service are handled by
management, rather than by inline communications protocol. The managed
parameters are those which tend to be static for long periods of time,
and whose change generally signifies a major reconfiguration of the
service provider associated with a particular mission. Through the use
of a management system, management conveys the required information to
the service provider.

The managed parameters used for the CCSDS Packet Transfer Service are
listed in Table 1.1. These parameters are defined in an abstract sense,
and are not intended to imply any particular implementation of a
management system.

The value of these parameters are defined for a specific mission
implementation.

1.  [[]{#_Ref206234394 .anchor}]{#_Ref245814373 .anchor}: Managed
    > parameters

  ------------------------------------------- ---------------
  Managed parameter                           Allowed value
  Minimum CCSDS Space packet length (bytes)   Integer
  Maximum CCSDS Space packet size (bytes)     Integer
  ------------------------------------------- ---------------

 Bibliography

  ------------------------------ --------------------------------------------------------------------
  ECSS-ST-S-00                   ECSS system - Description, implementation and general requirements
  http://www.spacewire.esa.int   SpaceWire website
  ------------------------------ --------------------------------------------------------------------
