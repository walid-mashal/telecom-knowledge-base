## Introduction

This document provides key terminologies and concepts related to the telecommunications sector. It is intended as a reference guide for professionals working in the telecommunications industry or anyone interested in understanding the technical and operational elements that support mobile communications.

Please leave a ⭐ if you find this resource helpful. Feel free to submit a pull request if you spot an issue or would like to enhance the content.

## Table of Contents

- [Mobile Network Operator (MNO)](#mno-mobile-network-operator)  
- [Voucher Card (VC)](#voucher-card-vc)  
- [Short Message Service (SMS)](#short-message-service-sms)  
- [Short Message Service Center (SMSC)](#short-message-service-center-smsc)  
- [Multimedia Messaging Service (MMS)](#multimedia-messaging-service-mms) 
- [Electronic Voucher (EV)](#electronic-voucher-ev)  
- [Postpaid Virtual Card](#postpaid-virtual-card)
- [SIM (Subscriber Identity Module)](#sim-subscriber-identity-module)  
- [MS (Mobile Station)](#ms-mobile-station) 
- [MSISDN (Mobile Station International Subscriber Directory Number)](#msisdn-mobile-station-international-subscriber-directory-number)  
- [Value Added Services (VAS)](#value-added-services-vas)  
- [Short Code](#short-code)  
- [On-Net](#on-net)  
- [Off-Net](#off-net)  
- [Number Normalization](#number-normalization)  
- [CRBT (Caller Ring Back Tone)](#crbt-caller-ring-back-tone)  
- [EVD (Electronic Voucher Distribution)](#evd-electronic-voucher-distribution)  
- [Denomination](#denomination)  
- [CDR (Call Detail Record)](#cdr-call-detail-record)  
- [Rated CDR](#rated-cdr)  
- [XDR (eXtended Detail Record)](#xdr-extended-detail-record)  
- [EDR (Event Detail Record)](#edr-event-detail-record)
- [2G Networks](#2g-networks)
- [2.5G Networks / GPRS (General Packet Radio Service)](#25g-networks--gprs-general-packet-radio-service)
- [3G Networks / UMTS (Universal Mobile Telecommunications System)](#3g-networks--umts-universal-mobile-telecommunications-system)
- [4G Networks / LTE (Long-Term Evolution)](#4g-networks--lte-long-term-evolution)
- [5G Networks](#5g-networks)
- [RAT (Radio Access Technology)](#rat-radio-access-technology)
- [VoIP (Voice over Internet Protocol)](#voip-voice-over-internet-protocol)
- [HSPA+ (Evolved High-Speed Packet Access)](#hspa-evolved-high-speed-packet-access)
- [IMSI (International Mobile Subscriber Identity)](#imsi-international-mobile-subscriber-identity)  
- [Country Code vs Mobile Country Code](#country-code-vs-mobile-country-code)  
- [MNC (Mobile Network Code)](#mnc-mobile-network-code)  
- [MSIN (Mobile Subscriber Identification Number)](#msin-mobile-subscriber-identification-number)  
- [IVR (Interactive Voice Response)](#ivr-interactive-voice-response)  
- [NOC (Network Operation Center)](#noc-network-operation-center)  
- [Base Station](#base-station)  
- [Billing Pulse](#billing-pulse)  
- [IMEI (International Mobile Equipment Identity)](#imei-international-mobile-equipment-identity)
- [EIR (Equipment Identity Register)](#eir-equipment-identity-register))  
- [MNP (Mobile Number Portability)](#mnp-mobile-number-portability)  
- [IN (Intelligent Network)](#in-intelligent-network)  
- [SGSN (Serving GPRS Support Node)](#sgsn-serving-gprs-support-node)  
- [GGSN (Gateway GPRS Support Node)](#ggsn-gateway-gprs-support-node)  
- [SGW (Serving Gateway)](#sgw-serving-gateway)  
- [PGW (Packet Gateway)](#pgw-packet-gateway)  
- [3G vs 4G Core Comparison](#3g-vs-4g-core-comparison)  
- [IGW (International Gateway)](#igw-international-gateway)  
- [Interconnect DRs (Detailed Records)](#interconnect-drs-detailed-records)  
- [PBX (Private Branch Exchange)](#pbx-private-branch-exchange)  
- [BTS (Base Transceiver Station)](#bts-base-transceiver-station)  
- [Node B](#node-b)
- [eNodeB](#enodeb)
- [gNodeB](#gnodeb)
- [RNC (Radio Network Controller)](#rnc-radio-network-controller)
- [Unified Communications (UC)](#unified-communications-uc)  
- [CDMA (Code Division Multiple Access)](#cdma-code-division-multiple-access)  
- [GSM (Global System for Mobile Communications)](#gsm-global-system-for-mobile-communications)  
- [Inbound Roamer (Inroamer)](#inbound-roamer-inroamer))  
- [Outbound Roamer (Outroamer)](#outbound-roamer-outroamer)) 
- [MSRN (Mobile Station Roaming Number)](#msrn-mobile-station-roaming-number) 
- [TAP (Transferred Account Procedure) Files](#tap-transferred-account-procedure-files) 
- [RAP (Returned Account Procedure) Files](#rap-returned-account-procedure-files)
- [VLR (Visitor Location Register)](#vlr-visitor-location-register)    
- [MSC (Mobile Switching Center)](#msc-mobile-switching-center)  
- [Gateway Mobile Switching Center (GMSC)](#gateway-mobile-switching-center-gmsc)  
- [VOMS (Voucher Management System)](#voms-voucher-management-system)  
- [OCS (Online Charging System)](#ocs-online-charging-system)  
- [Reconciliation Types](#reconciliation-types)  
- [PCRF (Policy and Charging Rules Function)](#pcrf-policy-and-charging-rules-function)  
- [CRM (Customer Relationship Management)](#crm-customer-relationship-management)  
- [HLR (Home Location Register)](#hlr-home-location-register)  
- [HSS (Home Subscriber Server)](#hss-home-subscriber-server)
- [Key Differences between HLR and HSS](#key-differences-between-hlr-and-hss)
- [Churn Rate](#churn-rate)
- [E1](#e1)
- [T1](#t1)
- [CPaaS (Communications Platform as a Service)](#cpaas-communications-platform-as-a-service) 
- [EBU (Enterprise Business Unit)](#enterprise-business-unit-ebu)
- [CBU (Consumer Business Unit)](#consumer-business-unit-cbu)
- [Trunk](#trunk)
- [Trunk Group](#trunk-group)
- [SDR (Special Drawing Rights)](#sdr-special-drawing-rights)

## MNO (Mobile Network Operator)

A Mobile Network Operator (MNO) is a company that provides wireless communication services to users. It owns or controls the infrastructure (e.g., cell towers) and offers services like voice calls, SMS, and mobile internet.  

**Examples:** 
- Afghanistan: MTN, Roshan, Etisalat
- United States: Verizon, AT&T, T-Mobile
- India: Jio, Airtel, Vi (Vodafone Idea)


## Voucher Card (VC)

A prepaid card used to top up mobile account balances for services such as calls, data, and text messages. Common in prepaid mobile plans.


## Short Message Service (SMS)

SMS stands for Short Message Service, the standard text messaging service used in mobile networks. Each SMS can carry up to 160 characters (using GSM 7-bit encoding) or fewer characters if using other encodings like UCS-2 (for non-Latin scripts).


## Short Message Service Center (SMSC)

SMSC is a vital network component that stores, forwards, and redirects all SMS (Short Message Service) messages between mobile phones and the network. It acts as a central hub, ensuring messages reach their intended recipients, even if they are not immediately available. 


## Multimedia Messaging Service (MMS)

MMS is an extension of SMS that allows sending multimedia content such as pictures, audio, video clips, and longer text.


## Electronic Voucher (EV)

A digital code used to pay for services like airtime or data. Delivered via SMS, USSD, or apps. Replaces physical scratch cards.


## Postpaid Virtual Card

A digital payment card issued by a mobile operator for postpaid users. Charges are added to the monthly phone bill.


## SIM (Subscriber Identity Module)

A SIM or SIM card is a small chip inside a phone that identifies a subscribter to the mobile network using the IMSI and authentication keys. It securely stores subscriber info and limited data like contacts or SMS, allowing you to make calls, send messages, and use mobile data safely.


## MS (Mobile Station) 

A Mobile Station is the complete device a user uses to access a mobile network. It comprises of two components – a Mobile Phone and a SIM card.


## MSISDN (Mobile Station International Subscriber Directory Number)

A unique phone number assigned to a mobile subscriber.  
**Example:** `+93-70-123-****`  
- Country Code (CC): +93 → Afghanistan  
- National Destination Code (NDC): 70 → Operator (e.g., Roshan)  
- Subscriber Number: 123-****


## Value Added Services (VAS)

Non-core telecom services like mobile internet, entertainment (TV, games), financial services, and custom features like voicemail or ringback tones. These services enhance the basic offering and provide additional revenue for telecom operators. 

Summary: Non-core services like internet, games, financial services, voicemail, ringback tones.


## Short Code

A short code is a 3-6 digit number used for SMS/MMS services by businesses and organizations. It is commonly used for marketing, authentication (OTP), alerts, and customer support.

Short codes can be dedicated, shared, vanity, or random and are widely used for promotions, notifications, and emergency services.

Summary: A 3–6 digit number for SMS/MMS services, used for OTPs, alerts, marketing, support.


## On-Net

Communication between users on the same network.
**Example:** MTN user to MTN user call. Often cheaper or free.

## Off-Net

Communication between different networks.
**Example:** Roshan user to MTN user call in Afghanistan. Usually incurs higher charges.


## Number Normalization

Number normalization is the process of converting phone numbers into a standard, consistent format so that they can be processed correctly by telecom systems, regardless of how they were originally entered or dialed.

- **A Number:** Formats caller’s number (e.g., add country code).  
- **B Number:** Formats receiver’s number.

**Example:**  
- Raw A Number: `00937012*****` → Normalized: `+937012*****`  
- Raw B Number: `07012*****` → Normalized: `+937012*****`


## CRBT (Caller Ring Back Tone)

CRBT is a telecom service that lets users set a custom tone (like a song or message) that callers hear while waiting for the call to be answered.

Key Points:
- Replaces the default ringtone with music, voice, etc.
- Activated via USSD, IVR, app, or SMS.

Summary: Custom tone (song/message) heard by caller while waiting. Can be activated via USSD, IVR, app, or SMS.


## EVD (Electronic Voucher Distribution)

EVD is a system for digitally selling mobile airtime, data, and services without physical scratch cards. Retailers use a digital platform (like a POS, app, or web portal) to top up customer accounts in real time. It reduces costs, improves security, and enables real-time tracking of sales and inventory.

Summary: Digital platform for topping up mobile balances. Replaces scratch cards. Enables real-time recharge, security, and tracking.


## Denomination

Refers to the value of a prepaid recharge or service bundle. It represents fixed amounts like 50, 100, or 500 AFN used for mobile top-ups, data, SMS, or voice packs. Denominations are commonly used in scratch cards, digital recharges, and mobile apps.

Summary: Fixed recharge values like 50, 100, or 500 AFN used for mobile top-ups.


## CDR (Call Detail Record)

A CDR logs voice call or SMS details such as caller, receiver, duration, time, and call status.
CDR is used for: Billing, call tracking, and analytics.


## Rated CDR

Rated CDR is a type of Call Detail Record (CDR) that has been processed by a rating engine and contains the charges calculated for a specific communication event. Rated CDR contains billing information such as call costs, rates, taxes, and is used for billing and financial purposes.


## XDR (eXtended Detail Record)

An XDR records data and multimedia usage (e.g., internet, video streaming), offering more detail than a CDR.
XDR is used for billing complex services and data analytics.


## EDR (Event Detail Record)

An EDR logs any network events, such as logins, SMS, handovers, or policy changes.
EDR is used for: Network monitoring, security, and service assurance.


## 2G Networks

2G was the first digital generation of mobile networks, replacing analog systems. It introduced GSM, enabled encrypted voice calls, and brought text messaging to users. It also improved call quality, used radio spectrum (the range of frequencies used for wireless communication) more efficiently, and laid the foundation for 3G, 4G, and 5G Networks.


## 2.5G Networks / GPRS (General Packet Radio Service)

GPRS, also called 2.5G, is a mobile data standard built on 2G networks. It enabled packet-based data transfers at speeds around 56 to 114 Kbps. Operating on both 2G and 3G networks, GPRS powered early mobile internet services like:

- MMS (picture messaging)  
- Web browsing  
- Email  
- Basic apps (e.g., weather, news)  


## 3G Networks / UMTS (Universal Mobile Telecommunications System)

UMTS, known as 3G, brought faster internet and improved voice quality. It enabled:

- Better web browsing  
- Video calling  
- Music/video streaming  
- Support for more advanced mobile apps (e.g., Facebook, YouTube)  

Speeds were typically up to 384 Kbps, and up to 42 Mbps with later upgrades (like HSPA+).


## 4G Networks / LTE (Long-Term Evolution)

LTE, commonly referred to as 4G, is a wireless broadband standard based on 4th generation cellular technology. It delivers high-speed internet to smartphones, tablets, and other mobile devices.

LTE supports:

- HD video streaming  
- Online gaming  
- Smooth app usage  
- VoIP (e.g., WhatsApp, FaceTime)  

Typical speeds can reach 100+ Mbps, with some versions offering even more. LTE powers modern smartphone use including Netflix, cloud apps, social media, and more.


## 5G Networks

5G is the fifth generation of cellular networks. It offers ultra-fast speeds (up to 10 Gbps) and extremely low latency, enabling near-instant communication.

5G benefits applications that require high reliability and speed, such as:

- Self-driving cars  
- Advanced cloud gaming  
- Live-streaming media  
- Smart cities and IoT  


## RAT (Radio Access Technology)

RAT is the technology used for wireless communication between a device and a network. It defines how data and voice are transmitted over the air. Common RATs include 2G, 3G, 4G, and 5G. Modern networks often support multiple RATs simultaneously (multi-RAT), allowing devices to switch or hand over between technologies based on coverage and network conditions.


## VoIP (Voice over Internet Protocol)

VoIP allows voice and multimedia communication over IP networks (like the internet) instead of traditional phone lines. It is cost-effective, flexible, and supports services like voice calls, video calls, and messaging on various devices.

Examples: Skype, WhatsApp, etc.


## HSPA+ (Evolved High-Speed Packet Access) 

HSPA+ is an enhanced 3G (3.5G/3.75G) mobile broadband technology that offers faster data speeds (up to 42 Mbps download, 11.5 Mbps upload) and lower latency compared to standard 3G.

HSPA+ is backward compatible with older UMTS/3G networks and was widely used before LTE/4G became common.


## IMSI (International Mobile Subscriber Identity)

IMSI is a unique number stored on your SIM card that mobile networks use to identify and authenticate you.

**Example IMSI:** `412800734*****`  

- MCC (Mobile Country Code): 412 (Afghanistan)  
- MNC (Mobile Network Code): 80 (Salaam Telecom)  
- MSIN (Mobile Subscriber Identification Number): 0734***** (Subscriber ID)


## Country Code vs Mobile Country Code

The Country Code (like +93 or 0093) is used for making international phone calls to a specific country. For example, when dialing a number in Afghanistan from another country, you'd start with +93.
The Mobile Country Code (MCC) is used internally by mobile networks to identify the country of a mobile subscriber. For Afghanistan, the MCC is 412. It's part of the IMSI (International Mobile Subscriber Identity) stored on the SIM card and used by the network during registration and authentication.

- **Country Code:** Used for dialing (e.g., +93 for Afghanistan, +1 for the United States, +91 for India).  
- **MCC (Mobile Country Code):** Used by networks to identify country (e.g., 412 for Afghanistan, 310 for United States, 404 for India).


## MNC (Mobile Network Code)

A two or three-digit code that uniquely identifies a mobile network operator within a specific country. It is used in combination with MCC to distinguish between different carriers operating in the same country.

Example MNCs:

- 80 → Salaam Telecom (Afghanistan)
- 01 → AT&T (USA)
- 10 → Airtel (India)
- 01 → T-Mobile (Germany)

Note: The same MNC can exist in different countries but with different MCCs.


## MSIN (Mobile Subscriber Identification Number)

A unique number assigned to each mobile subscriber by their mobile network operator. It identifies the individual user within that operator’s network. The format and length may vary between operators but typically consists of 9–10 digits.

Example MSINs:

- 07341**** → a subscriber on Salaam Telecom
- 98765**** → a subscriber on Airtel India
- 123456**** → a subscriber on Verizon USA


## IVR (Interactive Voice Response)

IVR is a system that lets callers interact with automated voice menus using keypad input or speech. It’s used to route calls, provide information, or handle tasks like checking balances or recharging accounts without human agents.


## NOC (Network Operation Center)

Centralized location for monitoring and managing network operations.


## Base Station

A base station is a fixed communication location that enables wireless communication between a network and mobile devices. It sends and receives radio signals to/from mobile phones or other wireless devices. It consists of Antennas, transceivers, power supplies, and baseband units.

Examples: Cell towers in mobile phone networks (e.g., 4G, 5G).


## Billing Pulse

Billing Pulse refers to a fixed time unit (e.g., 60 seconds) used to calculate charges for telecom services such as voice calls. Users are billed in increments of this unit, regardless of whether the entire duration is used. 

Example: For a 60-second pulse rate, a 61-second call would be billed as 2 pulses.

Most common billing pulses durations are 1 second, 30 seconds and 60 seconds.

## IMEI (International Mobile Equipment Identity) 

IMEI is a unique 15-digit number that identifies a mobile device. It is used by networks for device authentication and security. It can also help track, block, or blacklist lost or stolen phones.

IMEI numbers are stored in a database called the EIR (Equipment Identity Register)


## EIR (Equipment Identity Register)

EIR is a database in mobile networks that stores lists of mobile device IMEIs, it helps MNOs identify and control devices by classifying them into three lists:

- White List: Allowed devices
- Black List: Blocked (e.g., stolen) devices
- Grey List: Suspicious devices (monitored but allowed)

EIR’s job is to check (using the IMEI number) that every phone call or SMS sent is from a mobile phone authorized to use a mobile network.

EIR helps prevent the use of stolen, faulty, or unauthorized devices on the network.


## MNP (Mobile Number Portability)

Mobile number portability enables mobile phone users to retain a mobile telephone number when changing the mobile network operator.


## IN (Intelligent Network)

A telecom architecture enabling advanced value-added services like call forwarding, toll-free numbers, voicemail, and IVR. It supports dynamic call routing, prepaid billing, and service customization by separating service logic from core infrastructure, simplifying updates and new service deployment.

Summary: Telecom architecture enabling services like call forwarding, toll-free numbers, and IVR.


## SGSN (Serving GPRS Support Node)

Manages delivery of data packets to/from mobile devices. Tracks location and manages mobility.

## GGSN (Gateway GPRS Support Node)

Interface between mobile network and external networks (like the internet). Manages IP allocation and data routing.


## SGW (Serving Gateway)

Routes user data between eNodeB and PGW. Handles mobility, QoS, and anchoring traffic in LTE.


## PGW (Packet Gateway)

Connects users to external networks. Manages IPs, QoS, billing. Evolves into UPF in 5G.

### 3G vs 4G Core Comparison

- **3G:**  
  - SGSN ≈ Mobility, routing  
  - GGSN ≈ Internet gateway  
- **4G:**  
  - SGW ≈ SGSN  
  - PGW ≈ GGSN


## IGW (International Gateway)

IGW is an exchange/switch that connects a local operator’s network to international carriers for voice, SMS, and data traffic.


## Interconnect DRs (Detailed Records)

Interconnect DRs are records generated for calls, messages, or data sessions that occur between different operator networks. They track usage details like duration, time, type of service, and destination to facilitate billing and revenue sharing between operators.

Key Points:

- Used for settlement and inter-operator charges.
- Ensure accuracy for costing and revenue assurance.
- Include fields like originating/terminating operator, timestamps, and usage metrics.

Summary: Usage records for inter-operator communication. Used for billing, reconciliation, and revenue assurance.


## PBX (Private Branch Exchange)

PBX is a private telephone network used by businesses for internal and external communication. It manages call routing, voicemail, conferencing, and integrations. PBX can be traditional (landlines), IP-based (VoIP), or cloud-hosted for more flexibility.

Summary: Private telephone network within organizations. Can be landline-based, VoIP, or cloud-hosted.


## BTS (Base Transceiver Station)

BTS is a key component in 2g mobile telecom networks, responsible for handling wireless communication between mobile devices and the network. 

It transmits and receives signals within a specific area (cell) and manages multiple calls or data sessions. BTS connects mobile devices to the broader telecom infrastructure, enabling communication.

Summary: Handles wireless communication between devices and the network.


## Node B  

Node B is the 3G counterpart of the BTS in 2G networks. It manages radio communication with mobile devices, transmitting and receiving signals within a cell. 

Unlike BTS, Node B connects to an RNC (Radio Network Controller) and supports higher data rates and advanced 3G services like mobile internet and video calls.


## eNodeB  

eNodeB (Evolved Node B) is the 4G LTE equivalent of Node B (3G) and BTS (2G). eNodeB is the 4G base station that replaces both Node B and its controller (RNC), enabling high-speed LTE communication with simpler, faster architecture.


## gNodeB

gNodeB (Next Generation Node B) is the 5G equivalent of eNodeB (4G). It manages radio communication between user devices and the 5G Core Network, supporting both high-speed data and ultra-low latency connections.


## RNC (Radio Network Controller)

RNC manages multiple 3G Node Bs, controlling radio resources, handovers between cells, performs load balancing, and mobility. It connects Node Bs to the core network and ensures smooth communication in 3G networks.


## Unified Communications (UC)

Integrates voice, video, messaging, email, and collaboration into one platform.


## CDMA (Code Division Multiple Access)

CDMA is a wireless communication technology used in mobile networks. It allows multiple users to share the same frequency channel by assigning each call a unique code. This makes communication more efficient and secure compared to older technologies like GSM. CDMA was widely used in 2G and 3G networks, especially in North America and some parts of Asia, before LTE and 5G became dominant.

Summary: Wireless tech allowing multiple users on one frequency via unique codes.


## GSM (Global System for Mobile Communications)

GSM is a standard for mobile networks that enables voice and data communication. It uses digital cellular technology with SIM cards for authentication and operates on multiple frequency bands. GSM supports features like SMS, international roaming, and secure encryption for calls.

Summary: Mobile network standard using SIM cards, supporting SMS, roaming, and encryption.


## Inbound Roamer (Inroamer)

An inbound roamer refers to a foreign subscriber who accesses and uses services on a local network while visiting from another country or operator.
In other words, the subscriber’s home network is abroad, but they temporarily connect to the local operator’s network through international roaming agreements.

**Example:** A Vodafone (Germany) subscriber utilizing network services on Airtel (India) while in India.


## Outbound Roamer (Outroamer)

An outbound roamer refers to a local subscriber who accesses and uses services on a foreign network while traveling outside their home country.
In this case, the subscriber’s home network is local, but they temporarily connect to a foreign operator’s network through roaming partnerships.

**Example:** An Airtel (India) subscriber utilizing network services on Vodafone (Germany) while in Germany.


## MSRN (Mobile Station Roaming Number) 

MSRN is a temporary telephone number assigned to a mobile station which roams into another numbering area (usually another country).


## TAP (Transferred Account Procedure) Files 

TAP files are standardized data files used between mobile operators for international roaming billing.
When you use your phone abroad, your visited network records your usage (calls, SMS, data). This data is packaged into a TAP file and sent to your home network for billing and settlement.


## RAP (Returned Account Procedure) Files

RAP files are used to dispute or correct TAP files. If the home network detects an error in a TAP file (e.g., wrong duration, duplicated record), it creates a RAP file and sends it back to the visited network.


## VLR (Visitor Location Register) 

VLR is a temporary database in mobile networks that stores subscriber information when a user is roaming. It works with the MSC to track the user's location, authenticate them, and help route calls and messages. The VLR gets data from the HLR and deletes it when the user leaves the area.


## MSC (Mobile Switching Center)

MSC is a key component in 2G/3G mobile networks that manages call switching, mobility, SMS routing, and subscriber authentication. It connects mobile users to other networks (like landlines or the internet).

- Call Switching: Connecting voice calls between users or networks.
- Mobility: Manages the user's location as they move across different cell areas and ensures seamless service continuity through handover between base stations.
- SMS Routing: Delivering text messages to the correct destination.


## Gateway Mobile Switching Center (GMSC)

A GMSC acts as the gateway to other networks, handling call routing between the home network and external ones like the Public Switched Telephone Network (PSTN), other mobile networks, or Voice over Internet Protocol (VoIP) networks.


## VOMS (Voucher Management System)

VOMS is a backend system used by telecom operators to create, manage, distribute, and validate prepaid recharge vouchers.

Key Points:
- Manages top-up PIN codes or electronic vouchers
- Tracks voucher activation and usage
- Integrates with: USSD/SMS systems, Retailer/dealer apps, Charging systems (like IN or OCS)
- Helps prevent fraud and supports audit/logging


## OCS (Online Charging System)

OCS is a real-time billing system used by telecom operators to charge customers instantly as they use services like Voice calls, Mobile data, SMS, Roaming and Value-added services.

Summary: Real-time billing system for charging services as they are used.


## Reconciliation Types

- **VOMS vs IN:** VOMS manages recharges; IN handles real-time charging. Reconciliation ensures recharge data matches between both systems to prevent revenue loss.  
- **EVD vs IN:** EVD manages electronic recharges; IN handles balance deductions. Reconciliation ensures all EVD top-ups reflect accurately in IN to avoid discrepancies.


## PCRF (Policy and Charging Rules Function)

PCRF manages real-time policy control and charging decisions. It defines how data is prioritized, billed, and accessed based on user profiles and service types. It works closely with the PGW and subscriber database to enforce network rules. PCRF is a core component in LTE networks.

Summary: Manages real-time data usage policies and charging in LTE networks.


## CRM (Customer Relationship Management)

CRM helps operators manage customer interactions, track data, and improve services. It handles sales, marketing, support, and billing, enabling personalized offers, support tracking, and better customer satisfaction. CRM systems also integrate with billing to monitor usage and charges.

Summary: Tracks customer interactions, billing, and support. Improves retention and satisfaction.


## HLR (Home Location Register)

HLR is a central database that stores subscriber info like profiles, subscriptions, and location data. It manages service access, tracks location for call routing, and supports services like call forwarding and voicemail. The HLR also handles authentication and call authorization.

Summary: Central database for subscriber info, location, and service access.


## HSS (Home Subscriber Server)

HSS is the central database in 4G and 5G networks that stores and manages user subscription data, authentication credentials, and mobility information. 

It supports IP-based services and is a key component of the IMS (IP Multimedia Subsystem).


## Key Differences between HLR and HSS

- HLR is used in 2G/3G; HSS is for 4G/5G.
- HSS supports IMS, Diameter protocol, and policy control.
- HSS provides a superset of HLR functions for modern networks.


## Churn Rate

The percentage of customers who stop using the service within a given period.


## E1

E1 is a European telecommunications standard that uses a dedicated physical/virtual line to carry multiple voice calls or data streams between network devices. It provides a total data rate of 2.048 Mbps and is commonly used in telecom and enterprise networks.


## T1

T1 is a North American telecommunications standard that uses a dedicated physical/virtual connection to link phone systems and data networks. It provides a total data rate of 1.544 Mbps and is mainly used in the U.S. and Japan.


## CPaaS (Communications Platform as a Service)

CPaas refers to cloud-based platforms that use APIs to let businesses integrate real-time communication features like voice, SMS, and video into their own applications. Popular CPaaS Providers include Twilio, Vonage (Nexmo), Sinch, and etc.


## Enterprise Business Unit (EBU)

The Enterprise Business Unit (EBU) is a division within a telecom company that serves enterprise and business clients, focusing on B2B revenue through voice, data, and ICT solutions tailored for organizations and government entities.


## Consumer Business Unit (CBU)

The Consumer Business Unit (CBU) is the division of a telecom company that focuses on retail customers (individual subscribers) who use mobile phones, home internet, and other personal communication services.


## Trunk

A trunk is a physical or logical communication link that carries multiple voice or data channels between switching centers (such as exchanges, PBXs, or MSCs in mobile networks). Trunks aggregate traffic instead of connecting individual users directly.


## Trunk Group

A trunk group is a set of trunks bundled together to handle large volumes of calls between two points (for example, between two exchanges or a PBX and the PSTN). The network can route calls over any available trunk in the group, improving capacity, efficiency, and redundancy.


## SDR (Special Drawing Rights)

SDR is used as a standard international value unit for setting spectrum fees, license charges, and regulatory penalties. SDR is created by the International Monetary Fund (IMF). SDR is not a currency and its value is derived from a basket of five major currencies such as the US dollar, Euro, Chinese renminbi, Japanese yen, and British pound sterling. The value of 1 SDR equals 1.42 USD at the time or writing this article.


