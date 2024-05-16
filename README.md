# Polkadot Tooling Collective

This document proposes to the Polkadot tokenholders the inception of a new System Collective: The Polkadot Tooling Collective (PoToC).

After a formation period to establish members and display effectiveness, the collective will request funds from the main treasury to support a salary structure and sub-treasury. These ideas are laid out in the `Phases` section.

## Context

The Polkadot Core Fellowship is currently the only System Collective for developers. This makes it the go-to spot for new developers who want to join Polkadot - regardless of the field in which they want to work.

The scope of the Core Fellowship is rather narrow, focusing primarily on implementations of the Polkadot Host and runtime code. But many developers are working on tools related to making Polkadot successful, both the maintenance and development of the core protocol and the libraries and abstractions for dApp developers. These developers often find that their contributions are not recognized within the mandate of the Core Fellowship.

But the system can host many collectives. The Core Fellowship should be just one of many Collectives that serve Polkadot in different ways. Each has its own set of members, scope, and expertise levels.

Having a narrow scope is critical for a Collective to ensure that it can fulfill its mission. Widening the scope leads to a softening of its direction and social cohesion and possibly a loss of vision.

The Polkadot Tooling Collective will serve Polkadot by recognizing and retaining developers who make significant contributions to tools and libraries that make Polkadot easier to maintain, use, and integrate.

## The Mission

The Polkadot Tooling Collective acts in the best interest of Polkadot. It tries to have a positive impact on developer success in the Polkadot Ecosystem and intends to do this by working towards two main goals:

- To maintain developer tools to build dApps on Polkadot (dApp Tooling)
- To maintain developer tools to build on Polkadot in general (General Tooling)

Since these definitions are not sufficiently precise, an exhaustive *Mission List* is provided by PoToC. This *Mission List* is the only source of truth about its mission.

Similar to the Core Fellowship, one of PoToC's goals is to recognize and retain developers who make substantial contributions to these areas. Specifically, the collective should focus on people who have contributed to the specification or implementation of Polkadot tooling. Having an on-chain body will provide a means for these developers to align and organize. 

PoToC may want to apply for treasury funding in the future; it is therefore clear that any infringement upon its mission statement must be treated as an attempt to exfiltrate governance funds.

## Mission List

The *Mission List* contains all projects and services that are maintained by PoToC.

It is divided into two sections, solely to keep the requirements of each section clearly defined; *dApp* and *General*. It can be updated through an on-chain 2/3-majority rank-weighted vote across all Members.

Some obvious cornerstones that must be upheld by all projects are:

- Must be FOSS (Free and Open-Source Software).
- Source code must be accessible without a login requirement.
- All members of PoToC must have permission to propose changes and raise issues.

The *Mission List* will be defined as part of the initial seeding.

### dApp Developer Tooling

This category contains all tools and libraries that help to build *on* Polkadot and are predominantly developed for this cause. Ideally, it should provide all pieces of software that are needed for a developer to build a dApp on Polkadot.

It specifically aims at developers - not end-users. Things like wallets, explorers, dashboards etc. are out of scope for this very cause.

We split this category into two layers:

#### Fundamentals

Software that lays the basis for a dApp project. They connect to the Polkadot network and offer rich possibilities to interact with it.  
Some examples would be: sending transactions, subscribing to block headers or decoding and storage. 

#### Extensions

Software in this tier depends on `Fundamentals` and extends their functionality. They may simplify and/or abstract certain functionality or tailor it to suite specific corner needs.

### General Polkadot Tooling

Projects that improve velocity and simplicity to develop on Polkadot. This category is not restricted to dApps, but can also include Parachains, node software or similar.

## Structure

The initial structure shall be as minimalistic as possible, to limit maintenance and social drama. This has the downside of being less resilient against foreign takeovers, but in the beginning, I think it is fine to rather focus on social cohesion.

There is no differentiation between maintainers of "Core Tooling" and "dApp Tooling". They both share the same set of members and rank structure. These terms are only used to clarify the mission goal.

### Rank 0 - Candidate

Developers who want to join can be inducted by any Member into this rank. A vote for promotion to rank 1 can be started not earlier than six months after being inducted.

They are expected to be a maintainer for one of the tools on the mission list.

- Voting weight: 0
- Salary mult: task-based bounties

### Rank 1 - Member

Members are expected to keep up the maintenance of at least one tool from the mission list. This includes extending them and creating new tools that are needed by the Polkadot developer community.

- Voting weight: 1
- Salary mult: 0.1 + task-based bounties

### Further Ranks

The initial member seeding will show how many ranks need to be created to arrive at the correct granularity. The requirement for adding new ranks is that they are *absolutely necessary*.

We do not want to end in a situation where ranks are purely added to show off.

## Salary Structure

There is no initial salary or bonus structure. In the future, after PoToC proves itself worthy, it is proposed to set up a bounty-centered pay structure.

Different tiers of bounties shall be defined, and a fairly low baseline salary will be paid to all members. This is done to provide an incentive for improving the tooling instead of sloth.

A member may apply for a specific bounty while providing evidence of fulfilling the bounty requirements. Granting of a bounty will be decided upon by a 50% on-chain vote. A cap on the monthly bounty payout should be established to prevent runaway spending and prioritize important changes. Bounty votes may only commence once per month to ease coordination between the Members.

The exact constants for the size of the bounties and baseline salary will be proposed through a secondary document in `Phase II`.

## Initial Members

There shall be a seeding repo that allows anyone to apply to a rank. Applications should include a list of tools and contributions that show their past commitment to Polkadot tooling development. The applicant must justify why they are a good fit to join PoToC.

Eventually, there needs to be a social consensus on the initial set of members. This set would then be proposed to the tokenholders, either as part of the PoToC proposal itself or as a separate referendum.

## Future

There are a lot of questions unanswered by this document. In the beginning, we will use the Core Fellowship as a guiding light for processes and ethics as much as possible. Eventually, PoToC would develop its sub-culture (pun intended) and show more of its own identity.

A rough mid-term plan could look like this:

### Phase I - Setup

This phase is for setting everything up and getting it enacted on-cain. It should take at most 6 months.

- 1.1 Contacting all stakeholders: Tokenholders, Seeding members, and The Fellowship.
- 1.2 Pitching the proposal to the community and incorporating feedback. 
- 2.1 Crafting a preliminary implementation to ensure that all important parameters are mentioned in the proposal.
- 2.2 Binding governance vote via Wish-For-Change track. This is treated as the final signal on whether to pursue it or not.
- 3.1 Final implementation and approval by The Fellowship.
- 3.2 Enactment on-chain and beginning of operations.

## Phase II - Probation Period

PoToC starts operating in a risk-reduced mode without governance funding. This phase will be used to evaluate the effectiveness and impact of PoToC.

Hopefully, the general public will deem it useful and approve of its future funding requests.

This phase should take from 6 months to 1 year.

## Phase III - Business As Usual

PoToC enacts its salary structure. The creation and granting of bounties starts and attracts new developer talent.

This will demonstrate that creating a System Collective can be done by anyone, and hopefully inspire the wider community to further its decentralization efforts in that direction.
