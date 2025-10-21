Skill Certs
Skill Certs is a decentralized skill certification protocol built on the Stacks blockchain using Clarity smart contracts.
It allows verified organizations to issue non-transferable NFT certificates that validate a user’s skills or achievements.

Features
Issue blockchain-based certificates as non-transferable NFTs
Only verified issuers can mint or revoke certificates
Transparent and verifiable ownership on-chain
Metadata includes skill name, level, and details
Event logs for traceability

Technical Overview
Language: Clarity
NFT Standard: SIP-009 with transfer restrictions (soulbound)
Core Functions:
register-issuer → Register verified institutions
issue-cert → Mint certificate to a user
revoke-cert → Remove certificate if invalidated
get-cert-data → Retrieve skill and metadata
get-owner → Get certificate holder

Installation & Usage
Clone the repository:
git clone https://github.com/your-repo/skill-certs.git
cd skill-certs
Deploy contract using Clarinet:
clarinet contract deploy skill-certs
Run tests:
clarinet test
