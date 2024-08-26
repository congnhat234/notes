- [Cyber security](#cyber-security)
  - [1. Introduction](#1-introduction)
  - [2. Social Engineering](#2-social-engineering)
    - [How do we train the people that we work with to kind of start thinking this way?](#how-do-we-train-the-people-that-we-work-with-to-kind-of-start-thinking-this-way)
  - [3. Example Employee Security Policy](#3-example-employee-security-policy)
  - [4. Common Attack Types](#4-common-attack-types)
  - [5. Servers vs. Managed Services](#5-servers-vs-managed-services)
  - [6. Network Segmentation](#6-network-segmentation)
  - [7. Basic Firewall Concepts](#7-basic-firewall-concepts)
  - [8. Honey Pots](#8-honey-pots)

# Cyber security

## 1. Introduction
- Following basic best practices is 90% of the battle
- Being a good administrator solves many issues
- Remove old accounts
- Don't allow users to install software
- Don't use a full admin account for day-to-day tasks
- Patches and updates are essential
- MFA

## 2. Social Engineering
- Social engineering is an attack on a computer system that uses social engineering tactics to trick people into giving them sensitive information.
- Humans trust, even when they shouldn't
- Humans want to help, even when they shouldn't
- Humans are busy!

### How do we train the people that we work with to kind of start thinking this way?
- Run Social Enginering penetration tests
  - Tailgater (tailgate somebody, see if you can gain access to the building, see how far you can get from there,...)
  - Exterminator (fake exterminator to access the building and plugging some device into our network)
  - Telecom worker
- Phishing, fake surveys,...
  - We need to discourage trust (not download anything, include source code from Github if you are not 100% confident)

## 3. Example Employee Security Policy

- bit.ly/3F62FRI

## 4. Common Attack Types

- DDoS:
  - attempt to make website or application unavailable
  - Tie up bandwitdth / other system resources
- SQL Injection:
  - Attempt to execute SQL queries
- Advanced Persistent Threats:
  - Attempt to gain access to a system

## 5. Servers vs. Managed Services
- Managed services are hosted by a service provider
- You are note responsible for patching or the OS
- Managed services are more secure
- Servers are less secure

## 6. Network Segmentation
Network traditional segmentation
- Using different segments for different security zones (VLAN)
- You can enforce rules on traffic BETWEEN segments, no within segments

Network micro segmentation

## 7. Basic Firewall Concepts
- Statteful Firewall
  - Allow all outbound traffic
  - Allow very little inbound traffic
- Rules are enforced in order
- Zero-trust model: default rule is Deny all traffic
- Layer 7 Firewall (AntiVirus Firewall)
- Firewall rules:
  - Only open the required tràaic for the required machines
  - Maintain Firewall rules
  - Strong change control required
- IDS (Intrusion Detection System) / IPS (Intrusion Prevention System)

## 8. Honey Pots

- Honeypots look valuable but are not.
- Certain countries may generate more attacks
- Misdirect attackers
- Analyze attack data
