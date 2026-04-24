# VoIP Help Desk Support Lab

This project is a small VoIP support lab built around the kind of tasks that can come up in help desk and entry-level IT support work.

I used this lab to practice setting up users, connecting softphone clients, testing internal calls, and checking how call routing works in a small business 3CX environment.

## Project Overview

The lab started with the basic 3CX setup and then moved into a few support-style scenarios that felt more like real troubleshooting than just system configuration.

The main areas covered in this project include:

- creating users and extensions
- setting up the Windows softphone
- testing internal extension-to-extension calls
- creating and testing a ring group
- configuring a queue
- setting up an IVR / digital receptionist
- configuring office hours
- documenting support-style scenarios

## Skills Used

- User provisioning and extension management
- Softphone setup and configuration
- Internal call testing
- Call routing setup
- Ring group setup and validation
- IVR configuration
- Basic VoIP troubleshooting
- Technical documentation

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

The initial buildout of the lab is documented in [setup.md](setup.md). This includes user creation, softphone setup, ring group creation, queue setup, IVR configuration, and office hours.

### Support Scenarios

So far, I have documented these support-style scenarios:

- [Ticket 01 - Windows softphone not provisioned](tickets/ticket-01-softphone-provision.md)
- [Ticket 02 - Internal call test between extensions](tickets/ticket-02-internal-call.md)
- [Ticket 03 - Ring Group routing test](tickets/ticket-03-ring-group-test.md)

## What Was Configured

### User and Extension Setup
Created multiple users and internal extensions to build out the lab environment.

### Softphone Configuration
Connected the 3CX Windows softphone for test users and confirmed it was ready for use.

### Internal Calling
Tested internal calling between extensions to make sure communication between users was working correctly.

### Ring Group Configuration
Set up and tested a ring group for shared inbound call handling.

### Queue Configuration
Created a help desk queue to support basic call distribution across users.

### IVR / Digital Receptionist
Configured a simple menu to route callers to the right destination.

### Office Hours Configuration
Set business hours for the lab and reviewed how call handling could change based on time of day.

## Screenshots

Screenshots are organized in the `screenshots/` folder by setup stage and support scenario.

## Why I Built This Project

I wanted a project that was closer to the kind of work done in IT support than a purely technical phone-system build.

This lab gave me a way to practice basic VoIP setup, user-side support tasks, internal calling checks, and call routing in a format that I could document clearly on GitHub.
