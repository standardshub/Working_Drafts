## Community Specification Governance and Contribution Policy

This document provides the governance and contribution policy for specifications and other documents developed using the Community Specification process in a repository (each a “Working Group”).  Each Working Group and must adhere to the requirements in this document.

## Roles.

Each Working Group may include the following roles. Additional roles may be adopted and documented by the Working Group.

### Maintainer
“Maintainers” are responsible for organizing activities around developing, maintaining, and updating the specification(s) developed by the Working Group.  Maintainers are also responsible for determining consensus and coordinating appeals.  Each Working Group will designate one or more Maintainer for that Working Group.  A Working Group may select a new or additional Maintainer(s) upon Approval of the Working Group Participants.  

### Editor
“Editors” are responsible for ensuring that the contents of the document accurately reflect the decisions that have been made by the group, and that the specification adheres to formatting and content guidelines. Each Working Group will designate an Editor for that Working Group.  A Working Group may select a new Editor upon Approval of the Working Group Participants.

### Participants
“Participants” are those that have made contributions to the Working Group.

## Decision Making.

#### Consensus-Based Decision Making
Working Groups make decisions through a consensus process (“Approval” or “Approved”).  While the agreement of all participants is preferred, it is not required for consensus.  Rather, the Maintainer will determine consensus based on their good faith consideration of a number of factors, including the dominant view of the Working Group Participants and nature of support and objections.  The Maintainer will document Evidence of consensus in accordance with these requirements. 

#### Appeal Process
Decisions may be appealed be via a pull request or an issue, and that appeal will be considered by the Maintainer in good faith, who will respond in writing within a reasonable time.

## Requirements.  [Include file langauage from Getting Started document]

The following materials must be included in the repository.  

### Community Specification License

### Scope
Each Working Group must designate a defined scope, which must be included in the repositories Scope.md file. 

### Noticies.md file.

## Ways of Working.

Inspired by ANSI’s Essential Requirements for Due Process, Community Specification Working Groups must adhere to consensus-based due process requirements.  These requirements apply to activities related to the development of consensus for approval, revision, reaffirmation, and withdrawal of Community Specifications.  Due process means that any person (organization, company, government agency, individual, etc.) with a direct and material interest has a right to participate by: a) expressing a position and its basis, b) having that position considered, and c) having the right to appeal. Due process allows for equity and fair play. The following constitute the minimum acceptable due process requirements for the development of consensus.

### Openness
Participation shall be open to all persons who are directly and materially affected by the activity in question. There shall be no undue financial barriers to participation. Voting membership on the consensus body shall not be conditional upon membership in any organization, nor unreasonably restricted on the basis of technical qualifications or other such requirements.  Membership in a Working Group’s parent organization, if any, may be required.

### Lack of Dominance
The development process shall not be dominated by any single interest category, individual or organization. Dominance means a position or exercise of dominant authority, leadership, or influence by reason of superior leverage, strength, or representation to the exclusion of fair and equitable consideration of other viewpoints.

### Balance
The development process should have a balance of interests. Participants from diverse interest categories shall be sought with the objective of achieving balance.

### Coordination and Harmonization
Good faith efforts shall be made to resolve potential conflicts between and among deliverables developed under this Working Group and existing industry standards.

### Consideration of Views and Objections
Prompt consideration shall be given to the written views and objections of all Participants.

### Written procedures
This governance document and other materials documenting the Community Specification development process shall be available to any interested person.

### Specification Development Process.  

### Pre-Draft
Any Participant may submit a proposed initial draft document as a candidate Draft Deliverable of that Working Group.  The Maintainer will designate each submission as a “Pre-Draft” document.

### Draft
Each Pre-Draft document of a Working Group must first be Approved to become a” Draft Specification”.  Once the Working Group approves a document as a Draft Specification, the Draft Specification becomes the basis for all going forward work on that specification.

### Working Group Approval
Once a Working Group believes it has achieved the objectives for its specification as described in the Scope, it will Approve that Draft Specification and progrees it to “Approved Specification” status. 

### Publication and Submission
Upon the designation of a Draft Specification as an Approved Specification, the Maintainer will publish the Approved Specification in a manner agreed upon by the Working Group Participants (i.e., Working Group Participant only location, publicly available location, Working Group maintained website, Working Group member website, etc.).  The publication of an Approved Specification in a publicly accessible manner must include the terms under which the Approved Specification is being made available under.

### Submissions to Standards Bodies
No Draft Specification or Approved Specification may be submitted to another standards development organization without Working group Approval.  Upon reaching Approval, Maintainer will coordinate the submission of the applicable Draft Specification or Approved Specification to another standards development organization.  Working Group Participants that developed that Draft Specification or Approved Specification agree to grant the copyright rights necessary to make those submissions.

## Contribution Guidelines.

This Working Group accepts contributions via GitHub pull requests. The following section outlines the process for merging contributions to the spec.

### Issues
Issues are used as the primary method for tracking anything to do with this specification Working Group.

### Issue Types
There are three types of issues (each with their own corresponding label):

##### Discussion
These are support or functionality inquiries that we want to have a record of for future reference. Depending on the discussion, these can turn into "Spec Change" issues.

##### Proposal
Used for items that propose a new ideas or functionality that require a larger discussion. This allows for feedback from others before a specification change is actually written. All issues that are proposals should both have a label and an issue title of "Proposal: [the rest of the title]." A proposal can become a "Spec Change" and does not require a milestone.

##### Spec Change
These track specific spec changes and ideas until they are complete. They can evolve from "Proposal" and "Discussion" items, or can be submitted individually depending on the size. Each spec change should be placed into a milestone.

## Issue Lifecycle.

The issue lifecycle is mainly driven by the Maintainer. All issue types follow the same general lifecycle. Differences are noted below.

### Issue Creation

### Triage

* The Editor in charge of triaging will apply the proper labels for the issue. This includes labels for priority, type, and metadata.

* (If needed) Clean up the title to succinctly and clearly state the issue. Also ensure that proposals are prefaced with "Proposal".

### Discussion

* "Spec Change" issues should be connected to the PR that resolves it.

* Whoever is working on a "Spec Change" issue should either assign the issue to themselves or make a comment in the issue saying that they are taking it.

* "Proposal" and "Discussion" issues should stay open until resolved.

### Issue Closure

## How to Contribute a Patch.

The Working Group uses pull requests ("PRs") to track changes. To submit a change to the specification:

### Fork the Repo, modify the Specification to Address the Issue

## Submit a Pull Request

## PR Workflow.

The next section contains more information on the workflow followed for Pull Requests.

### PR Creation

* We welcome PRs that are currently in progress. They are a great way to keep track of important work that is in-flight, but useful for others to see. If a PR is a work in progress, it should be prefaced with "WIP: [title]". You should also add the wip label Once the PR is ready for review, remove "WIP" from the title and label.

* It is preferred, but not required, to have a PR tied to a specific issue. There can be circumstances where if it is a quick fix then an issue might be overkill. The details provided in the PR description would suffice in this case.

### Triage

* The Editor in charge of triaging will apply the proper labels for the issue. This should include at least a size label, a milestone, and awaiting review once all labels are applied. 

### Reviewing/Discussion

* All reviews will be completed using the GitHub review tool.

* A "Comment" review should be used when there are questions about the spec that should be answered, but that don't involve spec changes. This type of review does not count as approval.

* A "Changes Requested" review indicates that changes to the spec need to be made before they will be merged.

* Reviewers should update labels as needed (such as needs rebase).

* When a review is approved, the reviewer should add LGTM as a comment.

* Final approval is required by a designated Editor.  Merging is blocked without this final approval. Editors will factor reviews from all other reviewers into their approval process.

### Responsive
PR owner should try to be responsive to comments by answering questions or changing text. Once all comments have been addressed, the PR is ready to be merged.

### Merge or Close

* A PR should stay open until a Maintainer has marked the PR approved.

* PRs can be closed by the author without merging.

* PRs may be closed by a Maintainer if the decision is made that the PR is not going to be merged.

## Non-Confidential, Restricted Disclosure.

Information disclosed in connection with the any Working Group activity, including but not limited to meetings, Contributions, and submissions, is not confidential, regardless of any markings or statements to the contrary.  Notwithstanding the foregoing, if the Working Group is collaborating via a private repository, the participants will not make any public disclosures of that information contained in that private repository without the Approval of the Working Group.  
