# W3F Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Grants Program Process](https://github.com/w3f/Grants-Program/#pencil-process) on how to submit a proposal.

- **Project Name:** QRUCIAL DAO
- **Team Name:** QRUCIAL OÜ
- **Payment Address:** TBA - BTC, Ethereum (USDT/USDC/DAI) or Polkadot/Kusama (aUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))
- **Level:** 2

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful W3F grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview

Please provide the following:

- If the name of your project is not descriptive, a tag line (one sentence summary).
- A brief description of your project.
- An indication of how your project relates to / integrates into Substrate / Polkadot / Kusama.
- An indication of why your team is interested in creating this project.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- The high level overview can be found in the Litepaper: <TBA>
- Topology TBA
- Research and meeting notes to be added and their results
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
- What need(s) does your project meet?
- Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  - If so, how is your project different?
  - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

- Team Lead: six / David Pethes - CTO of QRUCIAL, Founder of CCTF, Polkadot Head Ambassador of Eastern Europe
- Chief Architect: ra33it0 / Sebastian Kraus - CEO of QRUCIAL, EFF member
- Runtime Developer: Wigy / - Senior Rust developer, Ex-Parity substrate core developer
- Full-stack Developer: Silur / Ábrahám Endre - Researcher at Hungarian Academy of Sciences (MTA), Ex-Ethereum Foundation developer
- DevOps Engineer: knockoff / Nico Selby - R&D team manager at QRUCIAL

### Contact

- **Contact Name:** Sebastian Kraus
- **Contact Email:** hello@qrucial.io
- **Website:** qrucial.io

### Legal Structure

- **Registered Address:** Harju maakond, Tallinn, Kesklinna linnaosa, Narva mnt 7-652, 10117
- **Registered Legal Entity:** QRUCIAL OÜ, Registration number: 16357543

### Team's experience

QRUCIAL OÜ is a web3 security company.

This is the first time we apply for a grant.

David is a web3 researcher and security expert and founded the largest crypto hacking competition in the world – CCTF – two years ago. He has more than 9 years experience in IT penetration testing and got several global certifications. Since 2021 he is Regional Head Ambassador for Eastern Europe of Polkadot. Since 2013 he is into blockchain and keeps improving his skills through related projects since then.

ra33it0 intro
wigy intro
silur intro
knockoff intro


### Team Code Repos

- https://github.com/Qrucial/QRUCIAL-DAO
- https://github.com/Qrucial/Hacking_Substrate_with_Chaos_Pallet
- https://github.com/Qrucial/SafuDot
- https://github.com/Qrucial/QRUCIAL_Audits

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/smilingSix
- https://github.com/Silur

### Team LinkedIn Profiles (if available)

- [https://www.linkedin.com/in/david-six-pethes/](https://www.linkedin.com/in/david-six-pethes/)
- [https://www.linkedin.com/in/sebastian-kraus-97a65a1a7/](https://www.linkedin.com/in/sebastian-kraus-97a65a1a7/)

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Implement Substrate Modules

- **Estimated duration:** 3 months
- **FTE:**  2
- **Costs:** 20,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. Docker images will also be prepared for the Exogenous tools. |
| 0e. | Article | We will publish **articles** and conduct workshop that explain QRUCIAL DAO. These will appear on QRUCIAL blog and the workshops will be conducted at Polkadot meetups (eg. Polkadot Hungary meetup and at hackerspaces).
| 1. | Substrate module: ExoSys | |  
| 2. | Substrate module: HackeRep | Reputation system for the manual auditors who verify the output recorded by ExoSys. |
| 3. | Substrate glue: ExoTools |  |  


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1
- **Costs:** 23,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.

- In the short term we'd like to have the grant so development goes faster. QRUCIAL as a company will keep funding the project until it becomes self-sustaining (meaning, the governance system keeps the DAO running on its own).
- CCTF (cryptoctf.org) is already a partner, helping to bring the best web3 hackers to the system.
- Elfz and Trollz is a marketing partner so we don't just develop a DAO, but also make it usable and visually acceptable to all audiences.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Personal recommendation from Achim Schneider and Jonan.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- We already have the litepaper: TBA link
- QRUCIAL OÜ is paying for the development already.
- This is the first time we request a grant.
