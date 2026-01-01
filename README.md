# Help Desk & Systems Support Lab (Active Directory)

## Overview

This lab demonstrates foundational Active Directory administration skills aligned with real-world Help Desk and IT Support responsibilities. The environment simulates a small enterprise domain where user accounts, organizational units, group policies, and authentication workflows are managed using Microsoft Active Directory.

The goal of this lab is to show practical, job-ready experience with identity management, domain services, and policy enforcement rather than theoretical knowledge alone.

All actions are documented with screenshots, structured walkthroughs, and validation steps to reflect how work would be performed and verified in a production support environment.

## Lab Objectives

The objectives of this lab are to:

Establish a functional Active Directory domain environment
Install and configure Active Directory Domain Services
Promote a Windows Server to a Domain Controller
Design a logical Organizational Unit (OU) structure
Manage users, groups, and group membership
Apply and scope Group Policy Objects (GPOs)
Validate domain authentication and policy enforcement

## Environment Overview

The lab environment consists of:

A Windows Server configured as a Domain Controller
A Windows client joined to the domain
DNS configured for domain name resolution
Organizational Units structured by business function
User and group objects managed through ADUC
Group Policy applied at the OU level

This setup mirrors common Help Desk and Tier 1–2 support environments.

## Repository Structure

This repository is organized to clearly separate documentation, screenshots, and validation artifacts.

The screenshots directory contains step-by-step visual evidence of each lab phase.
Each major phase includes its own README explaining what was performed and why it matters.

The structure allows reviewers to quickly navigate from high-level understanding to detailed execution.

## Lab Walkthrough Sections

01 – Active Directory Domain Services Installation
Installation of the AD DS role and required management tools.

02 – Domain Promotion
Promotion of the server to a Domain Controller and creation of a new forest and domain.

03 – Organizational Unit Structure
Design and implementation of a business-aligned OU hierarchy.

04 – User Management
Creation, modification, disabling, and validation of domain user accounts and group membership.

05 – Group Policy Basics
Creation and linking of a Group Policy Object scoped to a specific OU with enforced settings.

99 – Proof and Validation
Verification of domain join, DNS resolution, authentication, and applied policies.

## Skills Demonstrated

Active Directory administration
Windows Server management
User and group lifecycle management
Organizational Unit design
Group Policy creation and scoping
DNS and domain authentication validation
Help Desk–level troubleshooting and verification

## Why This Lab Matters

Active Directory remains a core technology in enterprise environments.
Help Desk and IT Support professionals are expected to understand how users authenticate, how policies are applied, and how issues are validated.

This lab demonstrates the ability to:

Follow structured administrative processes
Document work clearly and professionally
Validate outcomes rather than assume success
Operate with the mindset expected in real support roles

## Intended Audience

This lab is intended for:

Help Desk and IT Support roles
Entry-level Systems Administration roles
Students learning enterprise Windows environments
Recruiters and hiring managers reviewing hands-on experience

## Next Steps

This lab serves as a foundation for future projects involving:

Ticketing system integration
Password reset and account lockout workflows
Security group-based access control
Advanced Group Policy enforcement
Incident response and troubleshooting scenarios