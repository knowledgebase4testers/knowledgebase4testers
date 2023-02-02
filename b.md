---
layout: default
title:  QA Glossary - Letter B
description: This is just Letter B
---

## Letter B

### Backlog refinement 
- the activity of creating and refining product backlog items, estimating and prioritizing them.

### Ballpark estimate 
- a ballpark estimate or figure is a number that is a guess, but one that you believe is near the correct number.
### Bash 
- command language and shell.

### basis test set: 
- A set of test cases derived from the code logic which ensure that \%
branch coverage is achieved.

### behavior: 
- The combination of input values and preconditions and the required response
for a function of a system. The full specification of a function would normally comprise one or more behaviors.

### beta testing:
- Operational testing at a site not otherwise involved with the software developers.
- Usually selected, committed users are invited.

### big-bang testing: 
- Integration testing where no incremental testing takes place prior to all the system's components being combined to form the system.

### black box testing:
* Specific knowledge of the application's code, internal structure and programming knowledge in general is not required.
* Real life: The tester is aware of what the software is supposed to do but is not aware of how it does it.
* Typical black-box test design techniques include:
    - Error guessing
    - Use case testing
    - User story testing

### bottom-up testing: 
* An approach to integration testing where the lowest level components are tested first, then used to facilitate the testing of higher level components. The process is repeated until the component at the top of the hierarchy is tested.

### branch: 
- A conditional transfer of control from any statement to any other statement in a component, or an unconditional transfer of control from any statement to any other statement in the component except the next statement, or when a component has more than one entry point, a transfer of control to an entry point of the component.
- every major Android release starts with creating a branch from master AB [as this is part of repo the repo is branched and hence its called branch]. Example, RVC,QT, SC etc. Every branch will have a dev and release branch ex sc-dev, sc-d1-release

### branch coverage: 
- The percentage of branches that have been exercised by a test case suite

### Browserstack 
- software to test mobile ("App Live") and web apps ("Live") remotely on real devices.

###  bug: 
- A manifestation of an error in software.
- a software bug is an error, flaw, or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways.

### Bug priority

| Priority        | Urgency         | Fixed/Downgrade |
|:-------------|:------------------|:------|
| P0 | Urgent Attention Required | [24 hours (ASAP) of P0 Priority to resolve or mitigate & downgrade  |
| P1 | Immediate Attention Required | 15 business days  |
| P2 | Attention Required | 60 business days |
| P3 | No Urgency / Deprioritized | 180 days  |
| P4 | Untriaged | N/A |


###  Bug seeding [error seeding]: 
- The process of intentionally adding known faults to those already in a computer program for the purpose of monitoring the rate of detection and removal, and estimating the number of faults remaining in the program. [IEEE]

###  Bug Status

| Issue status        | Description         |  |
|:-------------|:------------------|:------|
| New | The issue does not have a person assigned to it |   |
| Assigned | Issue has a person assigned to it. |  |
| Accepted | The assignee has acknowledged to assignment and has begun to work on the issue. |
| Fixed | The issue has been addrssed |   |
| Fixed(verified) | The correctness of the fix has been confirmed. |  |
| Won't fix(not repro) | Either not enough informatin or issue cannot be reproduced |  |
| Won't fix(intended behavior) | The issue describes expected behavior. |  |

### Bug template
for easy reading and efficiency the bugs need to be standarized. 

```
1. Summary
    Short description of the issue
    
2. Environment
    Mac/Linux/Windows
    Browser Version
    Apk, RC (Release Candidate) version
    
3. Steps to reproduce
    - what locales
    - what dimensions
    - what Testcase, test account
    - what surface
    - what query(queries)
    
4. Actual results
    - screenshot, video
    - Console logs (bugreport), 
    - logcat []https://developer.android.com/studio/debug/logcat]; 
    - Sherlog
    - Test account (white-listed or not)
        
5. Expected results

6. Additional Information
```



[back](./)