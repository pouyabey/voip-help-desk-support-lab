# VoIP Help Desk Support Lab

This project documents a hands-on VoIP support lab focused on common help desk and entry-level IT support tasks.

The lab covers user setup, softphone configuration, internal call testing, call routing, and basic troubleshooting in a small business VoIP environment.

## Project Overview

In this lab, I set up a small business VoIP environment and documented both the initial configuration process and selected support-style test scenarios.

The project focuses on tasks that are relevant to help desk, IT support, and systems support roles, including:

- user and extension setup
- Windows softphone configuration
- internal extension calling
- ring group configuration and validation
- queue configuration
- IVR / digital receptionist setup
- office hours configuration
- troubleshooting documentation

## Skills Used

- User provisioning and extension management
- Softphone setup and configuration
- Internal call testing and validation
- Call routing configuration
- Ring group setup and testing
- IVR configuration
- Basic VoIP troubleshooting
- Technical documentation
- End-user support simulation

## Lab Environment

- VoIP Platform: 3CX Hosted / SMB environment
- Client: 3CX Web Client
- Softphone: 3CX Windows App
- Mobile Endpoints: iOS and Android softphone clients
- Test Setup: Multiple internal user extensions
- Documentation Format: GitHub Markdown with screenshots

## Test Users and Extensions

- 101 - Reception
- 102 - Help Desk Agent
- 103 - Sales Agent
- 104 - Manager

## Project Documentation

### Initial Setup

The initial system setup, including user creation, softphone setup, ring group creation, queue creation, IVR setup, and office hours configuration, is documented in [setup.md](Setup.md).

### Support Scenarios

The following support-style scenarios have been documented so far:

- [Ticket 01 - Windows softphone not provisioned](tickets/ticket-01-softphone-provision.md)
- [Ticket 02 - Internal call test between extensions](tickets/ticket-02-internal-call.md)
- [Ticket 03 - Ring Group routing test](tickets/ticket-03-ring-group-test.md)

## Key Configurations Completed

### User and Extension Setup
Created multiple users and internal extensions for a small business VoIP support environment.

### Softphone Configuration
Set up and connected the 3CX Windows softphone for test users.

### Internal Calling
Tested extension-to-extension calling and confirmed basic internal communication between endpoints.

### Ring Group Configuration
Configured and tested a ring group to support shared inbound call handling.

### Queue Configuration
Built a help desk queue for support call distribution across users.

### IVR / Digital Receptionist
Configured menu-based call routing for different destinations within the VoIP environment.

### Office Hours Configuration
Set up business hours and related call-handling behavior for the lab environment.

## Screenshots

Project screenshots are organized in the `screenshots/` folder by setup stage and support scenario.

## Why This Project Matters

This project shows hands-on work related to:

- help desk support workflows
- VoIP user setup and support
- softphone configuration
- internal call validation
- call routing configuration
- troubleshooting and documentation

It was built around the kind of tasks that can come up in IT support, help desk, and systems support roles.
