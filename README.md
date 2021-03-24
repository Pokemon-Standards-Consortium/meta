# About PSC
The mission of the **Pokémon Standards Consortium** is to ensure the interoperability of information related to the Pokémon franchise between organizations by developing well-defined and clear methods. This is a semi-formal, community-driven initiative that will allow for more data portability across projects and organizations, working directly with those who hope to benefit from the Consortium's efforts to ensure rigid standards.

- [Communication](#communication)
- [Standards process](#standards-process)
  * [Proposal](#proposal)
  * [Early Draft](#early-draft)
  * [Working Draft](#working-draft)
  * [Publication Candidate](#publication-candidate)
  * [Finalized Standard](#finalized-standard)
- [Membership](#membership)
  * [List of members](#list-of-members)
    + [Board members](#board-members)
  * [Becoming a member](#becoming-a-member)
- [GitHub structure](#github-structure)
  * [standards](#standards)
  * [meta](#meta)

# Communication
Most formal communication should be done in the PSC GitHub for transparency and easy tracking. Issues should be created for all Proposals, as well as topics of discussion. Informal communication, as well as all voting, will be done in [the PSC Discord](https://discord.gg/f7jXyE2C4h).

# Standards process
The process for PSC standards documents is loosely based on processes used by the [IETF](https://www.ietf.org/), [W3C](https://www.w3.org/), and [ISO](https://www.iso.org/), as well as common software release life cycles.

There are five stages of a PSC standards document:
## Proposal
A Proposal can be created by anyone, regardless of membership in PSC. Proposals are fairly informal, as most of the work will be done in the Early Draft stage, but we ask that Proposals include a basic overview of the scope and desired outcome. Fu
## Early Draft
Once a Proposal gets sponsored by a member (if a member submitted a Proposal, they sponsor it by default) and seconded by another member (from a different organization if the sponsor is representing an organization), an Early Draft is created. A PSC ID is assigned at this point, to allow for easy tracking.
## Working Draft
Once an Early Draft reaches a point where the sponsor feels that the document is mostly complete, it becomes a Working Draft. Working Drafts are to be reviewed by all members to determine if any changes need to be made.
## Publication Candidate
On a biweekly basis, the list of Working Drafts will be reviewed by the Consortium, and each will be put up for vote to move to Publication Candidate. Two days (48 hours) will be given to vote, after which the decision will be made based on a plurality of voting members. Once a Publication Candidate, members are encouraged to communicate the documents to their organizations for review.
## Finalized Standard
On a biweekly basis, the list of Finalized Standards will be reviewed by the Consortium, and each will be put up for vote to move to Finalized Standard. Seven days (168 hours) will be given to vote, after which the decision will be made based on a plurality of voting members. Once a Finalized Standard, the document is considered finished and ready for use. Minor amendments may be proposed afterwards, starting as late in the process as Working Drafts (without assigning a new PSC ID).

# Membership
Organizations and individuals can become members of PSC to provide input throughout the standards process. You do not need to be a member to participate in discussion, create a Proposal, or (most importantly) utilize the standards documents. Voting and sponsoring/seconding a Proposal are the primary rights granted to members.
## List of members
The following are members of the Pokémon Standards Consortium. Members may be representatives of an organization or unaffiliated.
### Board members
The following are members of the PSC Management Board. The Board has few responsibilities, as the majority of PSC operations are driven by all members. Board responsibilities include moderation of the PSC Discord, administration of the GitHub (including approving pull requests), and the processing of member applications.
## Becoming a member
If you are interested in becoming a member, please [apply using this form](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAMAAK9gcItUMjBKQUQ0VVBaSzhRWlI4SldYRktJWUJYUi4u). Applications will be reviewed by a member of the Board and usually get approved within 48 hours. If there is an issue with an application, or in the extremely rare occasion where an application would be denied, a Board member will reach out to the applicant to discuss.

# GitHub structure
## standards
The standards repository is where all standards documents are stored. Final documents are published in the `final` directory, whereas documents at all working stages are in the `drafts` directory. Where applicable, this repository also includes formed JSON versions of the standards for ease of use.
## meta
The meta repository contains information on the Pokémon Standards Consortium itself, including the procedure for creating a standards document, a list of members, etc.
