## Open Social Governance App by ODIN

A Project Proposal

### The Context

As a collaborating group of people having deep interest and experience with Cardano 
and the practices and dynamics of socially-governed organizations, we want to to share 
and spread knowledge, capabilities and supporting technology for orgs not operated 
in top-down, command-and-control style.  

We want to enable mechanisms for these organizations to start from where they are and 
what they already have, and to help them make the most out of it.

#### The Tension

Our shared experience shows us that small reward pools and informal methods of work 
planning have not been sufficient to create a context for impactful execution of even 
relatively small tasks and delivery of results, in the area of our purpose and mission.

We have talked about and agreed on activities that would help ODIN make progress on our 
journey to enablement of viable Teal organizations.  But in the absence of a mechanism 
of more concretely recognizing rewards and performing essential record-keeping, we have 
not been able to create, much less sustain, effective execution on a coherent shared purpose.

#### The Relevance

We've recognized the presence of a small pool of financial rewards; a far-more-valuable 
pool of knowledge, experience, and insight on Sociocracy; as well as know-how for creation 
of Cardano-based application software that can operate on-chain, creating accounting records 
and token-based forms of representing current- and future-value.

Our hypothesis is that by starting to create ***an application in which we can perform 
a few basic functions for starting to operate our own organization with some economic 
essentials and some record-keeping basics***, that it can provide a basis for resolving 
the essential dysfunctions that have previously interfered with organizational action.

Our hypothesis is that there will be further challenges that arise immediately after 
achieving that first goal, and that we can make further incremental steps to resolve 
those challenges as they arise.

#### The Requirement

We intend to create a simple application to start.

 - It should be able to mint ODIN tokens to serve as equity for our contributors.
 - It should be able to mint IOU.ADA tokens to serve as deferred compensation for 
   our participation.

We would want to be able to produce the most essential short-term results in around 
2 weeks of effort.

We would want to start issuing these tokens on the `preprod` network for safety at 
first, using `preprod` to directly account for contributions, and once we gain enough confidence, to 
replicate all of our accumulated value into a `mainnet` environment.

We would like to be able to grow the application further, fine-tuning and expanding its 
capabilities to facilitate decentralized organizations to meaningfully apply some of 
the most essential practices of Sociocracy/S3.

In particular, it should let us create the ODIN S3 Domain, with its expression of 
purpose (driver statement).

#### The impact

If it works, we will be able to evaluate the application, either deploying it to `preprod` 
or making key modifications before starting to use it ("potentially shippable").

If it works, we will be able to start issuing equity tokens and/or debt tokens - Cardano 
native assets that have no inherent cost (or value), but which are much more concrete 
representations of accounting for value delivered by our contributors.

If it works, we will be able to grow the application through additional small refinements 
through practices of Sociocracy and evolve product features that honor S3 principles, 
practices and workflow.

If it works, we will eventually be able to provide this software for use by any 
decentralized organization to manage the impactful, effective delivery of their purposes, 
and to use token-based mechanisms to helpx them with the financial facet of operating.

If it works, we will create real value for the ODIN tokens, start collecting revenues, 
and be able to pay out later on currently-issued debt and staked equity tokens, and/or 
enable our contributors to sell ODIN tokens at market.

### What has come before

#### Sprint 0

We made this proposal!

We can move key items from below up into here, in future proposals, if any, to extend this effort.

### The Proposal

#### Considerations

 - Make something small.
 - Make progress.
 - Address our most critical tensions ASAP.

#### What

Randall will build an initial version of an OSG app.

    - Can mint ODIN tokens to serve as equity for our contributors.
    - Can mint IOU.ADA tokens to serve as deferred compensation for our participation.
    - Nice to have: Can create the ODIN Domain with a primary Driver description.

#### How

Built using Stellar Contracts and Stellar Tokenomics, the OSG app will have a simple web-based 
UI for basic administration of the adopted functions.

If time permits, the application will allow the expression of one or more S3 Domains, with 
a basic structure aligned to the S3 practices, forming the most basic unit of S3 record-keeping 
to create shared meaning.

The frameworks include the ability to create separate policies controlling each type of 
data.  It allows the iterative deployment of updates to those policies.

##### Strategy for prioritizing future work 

We will use the core principles of S3 and the patterns that back those principles - see the 
(Common Sense Framework)[https://patterns.sociocracy30.org/csf.html] for some top candidates, 
focusing on those that we think will provide the most useful leverage for our needs. 

    - Be able record each organization's most essential "charter" type of information, 
      primarily to describe its primary driver.
    - Proposals and Consent process mechanisms
    - Agreements, Strategy and Backlogs
    - Organizational Principles and Values

Other non-S3 areas to also consider:
    - Be able to make a record of resources that we have, perhaps in one of the 8 forms of capital.
    - Debt- and equity-accounting: be able to clearly see what "debt tokens" are issued, as well 
      as how much equity is outstanding.
    - Market-based mechanisms 
    - Be able to support treasury-management workflows and contribution-accounting
    - Be able to create retroactive funding mechanisms, in which future financial contributors can 
      reward previous efforts

#####  Software Lifecycle strategy: Room to Grow

The software should be able to evolve:
    - Trade old data structures for new ones
    - Trade old on-chain policies for evolving policies
    - Add new capabilities as we grow 
    - Keep minting ODIN tokens, ideally with same policy-id over time.
    - Be able to mint other tokens for purposes we haven't yet predicted

