# Vyper - Scroll Level-Up Grant Application


## Project summary

Vyper is a pythonic programming language for smart contracts on the Ethereum Virtual Machine (EVM). We aim to become the most widely used smart contract programming language by offering superior developer experience, high-quality tooling,  readability, and maximum security.

## Project category

Other

## Project links

https://github.com/vyperlang/vyper

https://github.com/vyperlang/titanoboa

https://github.com/vyperlang/gaboon/tree/refactor

https://vyperlang.org/

https://twitter.com/vyperlang/

https://defillama.com/languages

https://try.vyperlang.org/

## Team description

Vyper is an open source project with a core team of 5 highly experienced web3 engineers, over 20 contributors, and many partners across the EVM toolchain, infrastructure and, security ecosystems.

For this particular project, the team will consist of 

- Charles (https://github.com/charles-cooper, https://x.com/big_tech_sux). Charles is the lead developer of Vyper and titanoboa (https://github.com/vyperlang/titanoboa). Charles also contributes to multiple Ethereum tooling projects (py-evm, pyrevm, eth-abi) and is the author of several EIPs.
- Harry (https://github.com/harkal, https://x.com/harkal). Harry has been working on Vyper's intermediate representation (Venom) since 2023. Harry has over 10 years of experience in embedded programming and computer graphics.

## What makes your project unique compared to your competitors out there? What is novel about your approach?

Vyper stands out in the smart contract programming landscape due to its unique focus on readability, security, and simplicity. Unlike its main competitors such as Solidity, Fe, and Yul, Vyper is specifically designed to make contracts maximally human-readable, even to non-programmers. We also strive to keep the language easy to learn and simple to use. A big part of this is done by focusing on providing better tooling for developers. Many of the historical contributors to Vyper and its developer tool suite are also engineers for DeFi protocols, ensuring that both the language and tooling are optimized to the needs of developers.
This approach has several advantages:

- Easier and cheaper to audit: According to auditors, Vyper's simplicity reduces the time required to audit a protocol, resulting in roughly 20% cheaper auditing costs.
- Safer: Common security footguns such as inline assembly, class inheritance or operator and function overloading are not available and prevent unforeseen vulnerabilities.
- Easy to onboard new developers: Vyper's Pythonic syntax is familiar to the many developers already working with Python (currently the most widely used programming language) and has a low learning curve for beginner programmers.
- Optimized:  Simplicity in the code translates to more optimized contracts, which have, on average 50% smaller bytecode and less gas costs than Solidity contracts.

## How will your project benefit the broader Scroll ecosystem?*

We want to help the Scroll ecosystem grow by offering a better developer experience and easy onboarding to new builders. Larger Vyper adoption on Scroll also increases language diversity and therefore the resilience of its whole ecosystem.

With its Pythonic, easy to learn syntax Vyper is uniquely positioned to attract new developers to Scroll, particularly those already familiar with Python. But Vyper's latest version and its convenient dev tool suite also appeal to established web3 developers, the majority of whom would prefer it to Solidity for their next project  (https://x.com/0xKoga/status/1805524364948893756). 

A big part of the increasing interest in Vyper among developers comes from more mature and accessible tooling. Tools like Titanoboa and the upcoming Gaboon enable faster testing, debugging, and deployment of smart contracts, as well as experimental and collaborative work through shared notebooks (https://try.vyperlang.org/).

We are committed to ensuring Scroll becomes a first-class citizen in the Vyper ecosystem. We want Vyper tooling to make deployment on Scroll easy and secure by better handling the chain's differences (opcodes, precompiled contracts) with Ethereum mainnet, making network management seamless and offering unmatched developer experience. 


## Is your project deployed on Scroll? 

Yes (probably? any vyper contracts deployed there?)


## Is your project deployed on other chains? 

Yes

## What are you hoping to accomplish with this grant? 

We are planning to use this grant to fund a developer to work on the development of two crucial Vyper developer tools: Titanoboa and Gaboon. These tools have proven essential in driving new Vyper adoption and their continued development will make smart contract development more accessible and productive.

Several smart contract development frameworks currently support Vyper but each come with significant drawbacks (Foundry is hard to set up, Brownie is deprecated, Ape is not suited for fuzzing) and its own UX issues. The grant would allow us to make Titanoboa and Gaboon the best available alternative with a particular focus on Scroll integration and cross-chain capacities. 

Titanoboa, as an interpreter, already makes running tests 100x faster than by using a simulated EVM like other frameworks and offers many other unique capacities (opcode patching, automatic fuzzing, custom precompiles). These advantages, however, can be hard to leverage for new developers. Other important features for UX such as wallet and network management, chain forking, ABI fetching are available but still rudimentary UX-wise. and interacting with third-party contracts in other languages is not always straightforward.

The grant would allow for the improvement of these features either directly in the Titanoboa codebase or through the new Gaboon framework. Gaboon would offer network management, deployment history and log management, integration with static analysis, fuzzing and symbolic testing tools, a CLI and REPL, and better support for non-Vyper languages.

## Milestone and roadmap

1. Better network management and enhance Titanoboa's EVM detection capacity to alert to differences in opcode availability or behavior and pre-compiled contracts between Scroll, other L2/alt-L1 chains, and mainnet (1 month)
2. Improve Titanoboa's integration of chain explorers like Scrollscan and associated API key management (1 week)
3. Add deployment history and log management features to Titanoboa (3 weeks)
4. Secure keystore and account management (1 month)
5. Project management in Gaboon with possibility to add and remove modules via CLI (1 month)
6. Integration with security tools in Gaboon: Halmos, Medusa (1 month)
7. Console in Gaboon to quickly load and interact with contracts (2 months)
8. Vyper REPL (2 months)
9. Improvements to Titanoboa documentation, Gaboon documentation and tutorial videos (2 months)

## Risks and Challenges

The main risks and challenges come from funding. Vyper is free and open source software and relies solely on grants.

## Total Budget Requested

$100,000

## Budget Breakdown

The whole budget will be allocated to pay the wages of the developers working on the project.

## Additional Funding

Vyper received a $920,000 grant from Curve in August 2023, a retroactive public good funding grant worth approximately $400,000 from Optimism in January 2024, and a $4,000 grant from Octant in August 2024.

## More Support

We would appreciate opportunities to demonstrate Vyper's capabilities in Scroll developer community events or to co-organize hackathons. We would also be happy to have a chance to be put in touch with new builders on Scroll and to onboard them to Vyper.

## Did anyone refer you to apply?

No
