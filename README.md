# AcadChain — Academic Data Bank Smart Contract

## Project Title

AcadChain — Academic Data Bank

## Project Description

AcadChain is a decentralized academic document verification and access platform built on Soroban and the Stellar blockchain. It enables authors to register academic works such as theses, dissertations, research papers, and technical reports with secure IPFS storage and blockchain-based verification.

The platform combines AI-powered plagiarism verification and decentralized human reviewer validation to ensure document quality and authenticity. Readers can pay XLM to access verified documents, while royalty payments are automatically distributed to authors, reviewers, and the platform treasury in a transparent and trustless manner.

## Project Vision

The vision of AcadChain is to create a secure, transparent, and decentralized academic ecosystem where scholarly works can be verified, protected, and monetized fairly without relying on centralized institutions.

By leveraging blockchain technology, AI verification, and peer review mechanisms, AcadChain aims to reduce plagiarism, increase trust in academic publishing, and provide fair incentives for authors and reviewers.

## Key Features

* **Academic Document Registration:** Authors can submit theses, dissertations, research papers, and technical reports.
* **AI Verification:** Documents undergo AI-based plagiarism and content validation before peer review.
* **Decentralized Peer Review:** Human reviewers stake XLM and review submitted documents.
* **Reviewer Reputation System:** Reviewer quality and activity contribute to a reputation score.
* **Royalty Distribution:** Automatic revenue split:

  * **70%** to document authors
  * **20%** to platform treasury
  * **10%** to reviewer rewards
* **Paid Access System:** Readers purchase temporary access to verified academic content using XLM.
* **IPFS Integration:** Academic files are securely stored off-chain with only metadata and hashes stored on-chain.
* **Access Control:** Admin-only moderation, reviewer restrictions, and author ownership protections.
* **Emergency Pause:** Platform can pause operations during emergencies or security incidents.
* **Immutable Records:** All submissions, reviews, and state transitions are transparently recorded on-chain.

## Usage Instructions

1. **Deploy Contract:** Deploy the smart contract on Soroban and initialize platform settings.
2. **Set Platform Configuration:** Configure admin, treasury wallet, XLM token contract, and minimum reviewer stake.
3. **Submit Document:** Authors upload document metadata and IPFS hash for verification.
4. **AI Verification:** Admin records AI plagiarism and content analysis results.
5. **Peer Review:** Registered reviewers stake XLM and review submitted documents.
6. **Publish Decision:** Approved documents are published automatically after reaching review quorum.
7. **Purchase Access:** Readers pay XLM to access published academic documents.
8. **Withdraw Earnings:** Authors and reviewers withdraw accumulated rewards securely.

## Future Scope

* **Advanced AI Moderation:** Integrate more advanced plagiarism detection and semantic content analysis.
* **Multi-Reviewer Matching:** Automatically assign reviewers based on expertise fields.
* **NFT Academic Certificates:** Issue proof-of-authorship certificates as NFTs.
* **University Integration:** Partner with universities for official thesis verification.
* **Encrypted Content Access:** Add advanced encryption for premium academic resources.
* **Scholar Reputation System:** Build academic credibility scores for authors and reviewers.
* **Cross-Chain Expansion:** Extend compatibility with multiple blockchain ecosystems.

## Technology Stack

* **Rust** for smart contract development.
* **Soroban SDK** for Stellar smart contract programming.
* **Stellar Blockchain** for decentralized and immutable execution.
* **IPFS** for decentralized document storage.
* **XLM Token System** for staking, rewards, and document access payments.

## Contribution

Community contributions are welcome from blockchain developers, academic researchers, and open-source contributors. Fork the repository and submit pull requests to help improve AcadChain.

## License

This project is licensed under the MIT License.

### Contract Detail

**Platform:** Soroban / Stellar Blockchain

**Smart Contract Type:** Academic Verification & Royalty Distribution System

**Features Included:**

* AI Verification
* Reviewer Staking
* Paid Academic Access
* Automatic Royalty Sharing
* Reviewer Reputation
* Emergency Pause Control

![Contract Architecture](image.png)
