# Cloud iNfrastructure Telco Taskforce Technical Release Process

## Table of Contents
* [Scope](#scope)
* [Release Model](#releasemodel)
* [Release Delivery Timeline](#timeline)
* [Events](#events)
* [Release Sign-off](#signoff)

<a name="scope"></a>
## Scope

The scope of this document is to define the release management and its process for planning, scheduling and controlling the build, in addition to proof reading and release deployment. This document defines the release model by organising the git branches and managing the code and other artefacts efficiently in well-structured format.
It should be considered a living document until it is agreed and signed by all the parties.

<a name="releasemodel"></a>
## Release Model

As a guiding principle, all the development occurs in “Master” branch. All the contribution for the milestone (especially M3) goes into ”Master”. After M4 (Proof Reading), at one point in the release candidate (for now maintain Release Candidate 0) for Baldy and based on experience we shall increase or limit what get into the final release. To make this happen, branch out from “Master”, create a delivery branch (“Baldy”, “Baraque”, etc). Developers can continue their next release branch work in “Master”. At the end of each release, artifacts are “tagged” in GitHub according to the guideline and principles defined.

To deliver a fixes into the latest release, simply apply the fixes on the "master" branch and then cherry pick technique will be applied for a particular PR which would agree jointly and tag it (4.0.1-Baldy). In case, if the "master" has evolved significantly then apply the fixes on the latest release branch directly. As shown in the below diagram.

<p align="center"><img src="../figures/proposedmodel.png" alt="Proposed Model" title="Proposed Release Model" width="80%"/></p>
<p align="center"><b>Figure 1:</b> Specimen Release Model</p>

During the development cycle when working with release branches, developers or architects should open up a “pull request” in GitHub so that team members can see what you are preparing to release.

<a name="timeline"></a>
## Release Delivery Timeline

The table below captured the list of events, long holidays only, release plan and sign off with corresponding dates. The release plan consists of all the milestones associated with the release candidate.

| Title | Feb/20 | Mar/20 | Apr/20 | May/20 | Jun/20 | Jul/20 | Aug/20 | Sep/20 | 
|------|-------|-------|--------|---------|-------|-------|--------|---------|
| Events | 
| ONES NA 2020 ||| 20/Apr to 23/Apr |
| ONES - Antwerp, Belgium (Proposed Release Name: **Baraque**) | | | | | | | | 29/Sep to 2/Oct | 
| Long Holidays |
| Easter (UK/US) |||10/Apr to 13/Apr | 
| Labour Day (China) | ||| 1/May to 5/May |
| Dragon Boat Festival (China) ||||| 25/Jun to 27/Jun |
| **Baldy (Proposed)** |
| M1 (Release Planning/Requirements) | 1/Feb |
| M2 (Issue Logging) | 21/Feb |
| M3 (Freeze Contributions) | ||~~03/Apr~~| 01/May |
| M4 (Freeze Proof Reading) | ||~~09/Apr~~| 07/May |
| Release Candidate | ||~~13/Apr~~| 11/May |
| Baldy Sign-Off | ||~~17/Apr~~| 15/May |
| **Baraque (Proposed)** |
| M1 (Release Planning/Requirements) | ||| 29/May | ~~17/Jun~~ |
| M2 (Issue Logging) | |||| 19/Jun | ~~01/Jul~~ |
| M3 (Freeze Contributions) | | | | | | | | 14/Sep |
| M4 (Freeze Proof Reading) | | | | | | | | 18/Sep |
| Release Candidate | | | | | | | | 21/Sep |
| Baldy Sign-Off | | | | | | | | 25/Sep |

<p align="center"><b>Figure 2:</b> 2020 Release Roadmap</p>

<a name="events"></a>
## Events

The list of events for the technical F2F planning captured from LGN events. <br>
•	~~ONES NA 2020 (Los Angeles, California) - April 20 & 21. Technical meetings April 22 & 23rd. <br>~~
•	~~LFN DDF (Seoul, South Korea) - June 1-4. <br>~~
•	ONES Europe 2020 (Antwerp, Belgium) - September 29 & 30. Technical meetings October 1 & 2.

<a name="signoff"></a>
## Release Sign-off

|   Name and Title of Approver   |   Decision       |    Reason for Rejection      |     Date     |
|--------------------------------|------------------|------------------------------|--------------|
|                                |                  |      &#9744; Approved <br> &#9744; Rejected  |              |
|                                |                  |      &#9744; Approved <br> &#9744; Rejected  |              |
|                                |                  |      &#9744; Approved <br> &#9744; Rejected  |              |
<p align="center"><b>Table 1:</b> Specimen Release Signoff</p>
