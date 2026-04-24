# Ticket 02 - Internal call test between extensions

## User Report

A user requested confirmation that internal extension calling was working correctly between users in the 3CX environment.

## Ticket Details

| Field | Value |
|---|---|
| Ticket Type | Service Request |
| Category | VoIP / Internal Calling |
| Priority | Low |
| Status | Resolved |
| Affected Service | 3CX Internal Calling |
| Test Users | 24010 and 24013 |

## Objective

The goal of this test was to confirm that extension-to-extension calling worked successfully between two users in the VoIP environment.

## Test Steps

### 1. Reviewed the Caller Endpoint

The calling endpoint was reviewed to confirm that the user was signed in and ready to place an internal call.

![Caller Ready](../screenshots/ticket-02-caller-ready.png)

### 2. Placed an Internal Call

An internal call was placed from one extension to another to test extension-to-extension communication.

![Call Ringing](../screenshots/ticket-02-call-ringing.png)

### 3. Confirmed the Call Was Connected

The receiving user answered the call, confirming that internal calling was working successfully between both extensions.

![Call Connected](../screenshots/ticket-02-call-connected.png)

### 4. Reviewed Call Activity

Call activity was reviewed after the test to confirm that the internal call had been completed successfully.

![Call History](../screenshots/ticket-02-call-history.png)

## Result

The internal call test was completed successfully, confirming that extension-to-extension calling was working correctly in the 3CX lab environment.
