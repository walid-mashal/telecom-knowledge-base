## Introduction

This document provides key terminologies and concepts related to the telecommunications sector. It is intended as a reference guide for professionals working in the telecommunications industry or anyone interested in understanding the technical and operational elements that support mobile communications.

Please leave a ⭐ if you find this resource helpful. Feel free to submit a pull request if you spot an issue or would like to enhance the content.

## Table of Contents

- [Mobile Network Operator (MNO)](#mno-mobile-network-operator)  
- [Voucher Card (VC)](#voucher-card-vc)  
- [Electronic Voucher (EV)](#electronic-voucher-ev)  
- [Postpaid Virtual Card](#postpaid-virtual-card)  
- [MSISDN (Mobile Station International Subscriber Directory Number)](#msisdn-mobile-station-international-subscriber-directory-number)  
- [Value Added Services (VAS)](#value-added-services-vas)  
- [Short Code](#short-code)  
- [On-Net](#on-net)  
- [Off-Net](#off-net)  
- [Number Normalization](#number-normalization)  
- [CRBT (Caller Ring Back Tone)](#crbt-caller-ring-back-tone)  
- [EVD (Electronic Voucher Distribution)](#evd-electronic-voucher-distribution)  
- [Denomination](#denomination)  
- [IMSI (International Mobile Subscriber Identity)](#imsi-international-mobile-subscriber-identity)  
- [Country Code vs Mobile Country Code](#country-code-vs-mobile-country-code)  
- [MNC (Mobile Network Code)](#mnc-mobile-network-code)  
- [MSIN (Mobile Subscriber Identification Number)](#msin-mobile-subscriber-identification-number)  
- [IVR (Interactive Voice Response)](#ivr-interactive-voice-response)  
- [NOC (Network Operation Center)](#noc-network-operation-center)  
- [Base Station](#base-station)  
- [Billing Pulse](#billing-pulse)  
- [IMEI (International Mobile Equipment Identity)](#imei-international-mobile-equipment-identity)  
- [MNP (Mobile Number Portability)](#mnp-mobile-number-portability)  
- [IN (Intelligent Network)](#in-intelligent-network)  
- [SGSN (Serving GPRS Support Node)](#sgsn-serving-gprs-support-node)  
- [GGSN (Gateway GPRS Support Node)](#ggsn-gateway-gprs-support-node)  
- [SGW (Serving Gateway)](#sgw-serving-gateway)  
- [PGW (Packet Gateway)](#pgw-packet-gateway)  
- [3G vs 4G Core Comparison](#3g-vs-4g-core-comparison)  
- [Interconnect DRs (Detailed Records)](#interconnect-drs-detailed-records)  
- [PBX (Private Branch Exchange)](#pbx-private-branch-exchange)  
- [BTS (Base Transceiver Station)](#bts-base-transceiver-station)  
- [Unified Communications (UC)](#unified-communications-uc)  
- [CDMA (Code Division Multiple Access)](#cdma-code-division-multiple-access)  
- [GSM (Global System for Mobile Communications)](#gsm-global-system-for-mobile-communications)  
- [Inroamer](#inroamer)  
- [Outroamer](#outroamer) 
- [MSRN (Mobile Station Roaming Number)](#msrn-mobile-station-roaming-number)     
- [VLR (Visitor Location Register)](#vlr-visitor-location-register)    
- [MSC (Mobile Switching Center)](#msc-mobile-switching-center)  
- [VOMS (Voucher Management System)](#voms-voucher-management-system)  
- [OCS (Online Charging System)](#ocs-online-charging-system)  
- [Reconciliation Types](#reconciliation-types)  
- [PCRF (Policy and Charging Rules Function)](#pcrf-policy-and-charging-rules-function)  
- [CRM (Customer Relationship Management)](#crm-customer-relationship-management)  
- [HLR (Home Location Register)](#hlr-home-location-register)  
- [Churn Rate](#churn-rate)


## MNO (Mobile Network Operator)

A Mobile Network Operator (MNO) is a company that provides wireless communication services to users. It owns or controls the infrastructure (e.g., cell towers) and offers services like voice calls, SMS, and mobile internet.  

**Examples:** MTN, Roshan, Etisalat


## Voucher Card (VC)

A prepaid card used to top up mobile account balances for services such as calls, data, and text messages. Common in prepaid mobile plans.

## Electronic Voucher (EV)

A digital code used to pay for services like airtime or data. Delivered via SMS, USSD, or apps. Replaces physical scratch cards.


## Postpaid Virtual Card

A digital payment card issued by a mobile operator for postpaid users. Charges are added to the monthly phone bill.

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
**Example:** Roshan user to MTN user call. Usually incurs higher charges.


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


MSIN (Mobile Subscriber Identification Number)

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

IMEI numbers are stored in a database called the EIR (Equipment Identity Register), which contains information about all valid mobile phone equipment.

EIR’s job is to check (using the IMEI number) that every phone call or SMS sent is from a mobile phone authorized to use a mobile network.

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

BTS is a key component in mobile telecom networks, responsible for handling wireless communication between mobile devices and the network. It transmits and receives signals within a specific area (cell) and manages multiple calls or data sessions. BTS connects mobile devices to the broader telecom infrastructure, enabling communication.

Summary: Handles wireless communication between devices and the network.


## Unified Communications (UC)

Integrates voice, video, messaging, email, and collaboration into one platform.


## CDMA (Code Division Multiple Access)

CDMA is a wireless communication technology used in mobile networks. It allows multiple users to share the same frequency channel by assigning each call a unique code. This makes communication more efficient and secure compared to older technologies like GSM. CDMA was widely used in 2G and 3G networks, especially in North America and some parts of Asia, before LTE and 5G became dominant.

Summary: Wireless tech allowing multiple users on one frequency via unique codes.


## GSM (Global System for Mobile Communications)

GSM is a standard for mobile networks that enables voice and data communication. It uses digital cellular technology with SIM cards for authentication and operates on multiple frequency bands. GSM supports features like SMS, international roaming, and secure encryption for calls.

Summary: Mobile network standard using SIM cards, supporting SMS, roaming, and encryption.


## Inroamer

Foreign user roaming on a local network.  
**Example:** Vodafone (Germany) user on Airtel (India).

## Outroamer

Local subscriber roaming on a foreign network.  
**Example:** Airtel (India) user on Vodafone (Germany).


## MSRN (Mobile Station Roaming Number) 

MSRN is a temporary telephone number assigned to a mobile station which roams into another numbering area (usually another country).

## VLR (Visitor Location Register) 

VLR is a temporary database in mobile networks that stores subscriber information when a user is roaming. It works with the MSC to track the user's location, authenticate them, and help route calls and messages. The VLR gets data from the HLR and deletes it when the user leaves the area.

## MSC (Mobile Switching Center)

MSC is a key component in 2G/3G mobile networks that manages call switching, mobility, SMS routing, and subscriber authentication. It connects mobile users to other networks (like landlines or the internet).

- Call Switching: Connecting voice calls between users or networks.
- Mobility: Manages the user's location as they move across different cell areas and ensures seamless service continuity through handover between base stations.
- SMS Routing: Delivering text messages to the correct destination.

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


## Churn Rate

The percentage of customers who stop using the service within a given period.

