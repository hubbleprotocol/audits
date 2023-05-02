## Hubble Protocol Security Vulnerability Disclosure Program

### Reporting security problems to Hubble

**DO NOT CREATE AN ISSUE** to report a security problem. Instead, please send an
email to security@hubble.markets and provide your github username so we can add you to our repos if needed.

Expect a response as fast as possible, typically within 24 hours.

The Hubble Protocol bug bounty program is focused on the prevention of negative impacts to the Hubble ecosystem, primarily loss of funds, which currently covers our smart contracts, web UI and Hubble integrations.

### Security bug bounties

All web/app bug reports must come with a Proof of Concept in order to be considered for a reward. All smart contract and guardian node bug reports must come with log components, reproduction, and data about vulnerabilities to support learnings and bug fixes. This can be satisfied by providing relevant screenshots, docs, code, and steps to reproduce the issue.

We offer bounties for critical security issues. Please see below for more details.

| **Smart Contracts**  |               |
| ------------- | ------------- |
| Critical  | Up to USD $500,000  |
| High      | USD $100,000  |
| Medium    | USD $10,000  |
| Low       | USD $2,500  |

| **Websites and Applications**  |               |
| ------------- | ------------- |
| Critical  | Up to USD $50,000  |
| High      | USD $10,000  |
| Medium    | USD $5,000  |
| Low       | USD $500  |

#### Primary prevention focuses
* Exploits resulting in the locking, loss, or theft of any funds
* General forging of unverified data, or validation of forged messages
* Determinism bugs that could lead to inconsistent states
* Exposure of infrastructure private keys and/or PII
* Remote code execution
* Bugs that can facilitate attacks

#### Out of scope
* Any encrypted credentials, auth tokens, etc. checked into the repo
* Bugs in dependencies. Please take them upstream!
* Attacks that require social engineering

#### Eligibility
* Minor issues do not automatically qualify for a bug bounty
* The participant submitting the bug report shall follow the process outlined within this document
* Valid exploits can be eligible even if they are not successfully executed on the cluster
* Multiple submissions for the same class of exploit are still eligible for compensation, though may be compensated at a lower rate, however these will be assessed on a case-by-case basis
* Participants must complete KYC and sign the participation agreement here when the registrations are open `<our KYC URL>`. Security exploits will still be assessed and open for submission at all times. This needs only be done prior to distribution of tokens
* Participants must send a valid invoice for the payment to be made

#### Payment
* Payments for eligible bug reports are distributed monthly
* Bounties for all bug reports submitted in a given month are paid out in the middle of the
following month
* The HBB/USD conversion rate used for payments is the market price at the end of
  the last day of the month for the month in which the bug was submitted.
* The reference for this price is the Closing Price given by Coingecko.com on
  that date given here:
  https://www.coingecko.com/en/coins/hubble/historical_data#panel
* For example, for all bugs submitted in April 2022, the HBB/USD price for bug
  payouts is the Close price on 2022-04-30 of $1.87. This applies to all bugs
  submitted in April 2022, to be paid in mid-May 2022
