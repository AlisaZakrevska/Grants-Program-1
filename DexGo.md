# Polymesh  Grant Proposal

- **Project Name:** DexGo
- **Team Name:** DexStudios
- **Payment Address:** 2FShrUsQ365P7nEvPxLdJYDT1vfq4K36VgpZJTP2T41jVYP1 
- **Level:** 2

## Project Overview :page_facing_up:

### Overview

- **Project Name:** DexGo — Move-to-Earn AR Exploration Game 
- **Brief Description:** DexGo is a mobile AR platform that turns real-world walking routes into gamified quests—users discover and design personalized routes, earn token rewards and NFT wearables as they explore their cities.
- **Polymesh Integration:** We will leverage Polymesh’s NFT issuance module to mint and manage our route-based AR wearables, and use its on-chain identity framework to distribute tokens securely and compliantly.
- **Why Our Team:** We’re passionate about merging healthy-lifestyle incentives with Web3 gamification. Polymesh’s compliance-first, NFT-centric infrastructure aligns perfectly with DexGo’s vision of community-driven exploration and rewards.

### Project Details

The system is founded on three fundamental data models. The route is associated with the level of difficulty and the author. The user profile is linked to the blockchain and NFT-related assets. The quest is associated with a specific route and a set of AR-triggers. The full OpenAPI specification will be released with the primary application to facilitate seamless integration with third-party developers.

The technological stack includes Unity 3D with AR Foundation on the client, Node.js/Express-backend for storing and managing the user's data, and smart contracts in Solidity for NFT management. We are pleased to inform you that we have integrated Polymesh modules into our NFT and verification systems in accordance with the established regulatory requirements. Each stage of the development process will be meticulously documented, including architectural diagrams, Docker configurations, and automated tests.

In the closed beta test conducted in Q1 2024, we successfully validated the functionality of the primary mechanism. This mechanism has garnered over 980,000 views on TikTok and has generated sales of more than $20,000 in the early NFT market.

### Ecosystem Fit

DexGo sits at the intersection of AR gaming and on-chain asset issuance: by minting and managing our exploration wearables on Polymesh, we demonstrate how real-world experiences can be tokenized in a compliance-first environment. As players traverse mapped routes, Polymesh’s identity and NFT modules ensure that every collectible is both verifiable and tradable within the broader ecosystem.

Our primary audience comprises two groups: mobile game developers and AR designers looking for a turnkey NFT integration, and end-users—urban explorers and fitness enthusiasts—who seek gamified incentives for healthy activity. Wallet and UI developers can leverage our published OpenAPI spec to build complementary tools, while creators can publish their own Polymesh-backed quests.

DexGo meets a dual need: it drives user engagement by rewarding physical exploration, and it provides a clear use-case for Polymesh’s asset issuance and identity framework. By turning everyday routes into on-chain quests, we unlock new avenues for real-world utility and broaden NFT adoption beyond static collectibles.

There are very few AR-focused move-to-earn projects on Polymesh today. In related ecosystems, most “move-to-earn” apps rely solely on off-chain proofs or build on generalist chains without compliance guarantees. DexGo’s unique combination of AR quest design, user-generated routes and Polymesh’s regulated NFT issuance distinguishes it as the first fully on-chain, compliance-oriented exploration game.

## Team :busts_in_silhouette:

### Team members

Oleksii Vinogradov – Founder, serial entrepreneur and investor with 25 years of track record launching and scaling tech ventures. 

Oleg Bondar – CEO with 12 years’ experience in retail and product development, leading cross-functional teams. 

Eugene Luzgin – Technical lead and problem-solver with a diverse software background, including Unity and Web3 integrations. 

Inna Koliasnikova – QA & Business Development specialist, 4 years in product testing and go-to-market execution. 

Denis Leshinsky – Unity designer focused on 2D/3D character art production and AR UX. 

### Contact

- **Contact Name:** Alisa Zakrevska
- **Contact Email:** alisa@dexgo.club
- **Website:** https://dexgo.club/en

### Legal Structure

- **Registered Address:** 7950 NW 53rd Street, Suite 337, Miami, Florida 33166

- **Registered Legal Entity:** IXC Global
  
### Team's experience

Our founding team possesses a unique combination of domain expertise in both blockchain technology and game development, providing us with a deep understanding of the challenges and opportunities at the intersection of these fields. Additionally, our extensive network within the gaming and blockchain communities gives us access to valuable partnerships and resources, enhancing our ability to execute our vision effectively. This blend of expertise and connections creates a formidable advantage that would be challenging for another team to replicate.


### Team Code Repos

https://github.com/oleksiivinogradov/

### Team LinkedIn Profiles (if available)

- Oleksii Vinogradov – https://www.linkedin.com/in/oleksiivinogradov/
- Oleg Bondar – https://www.linkedin.com/in/oleg-bondar-820710246/
- Margaret Khil – https://www.linkedin.com/in/khilmargaret
- Eugene Luzgin – https://www.linkedin.com/in/luzgin/ 

## Development Status :open_book:

N/A

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 2 month
- **Full-Time Equivalent (FTE):** 3 FTE
- **Total Costs:** 30 000 USD

## Roadmap & Milestones

### Milestone 1 — Polymesh Identity & Asset Integration
- **Duration:** 1 month  
- **FTE:** 1.5  
- **Budget:** $15 000

| #   | Deliverable | Specification |
| --- | ----------- | ------------- |
| 0a. | **License** | Apache 2.0 |
| 0b. | **Documentation** | Inline code comments + “Polymesh Integration” tutorial |
| 0c. | **API spec** | OpenAPI definition for KYC & NFT-mint endpoints |
| 0d. | **Test suite** | Unit & integration tests (≥ 90 % coverage) |
| 1.  | **Feature: KYC flow** | DID-based KYC integration via Polymesh SDK |
| 2.  | **Feature: NFT issuance** | Smart contract to mint “AR checkpoint” NFTs as Polymesh assets |


### Milestone 2 — On-Chain Gameplay Logic & Indexer
- **Duration:** 1 month  
- **FTE:** 1.5  
- **Budget:** $15 000

| #   | Deliverable | Specification |
| --- | ----------- | ------------- |
| 0a. | **License** | (carried over) |
| 0b. | **Documentation** | “On-Chain Gameplay” tutorial + architecture diagrams |
| 0c. | **API spec** | GraphQL schema for checkpoint events & leaderboards |
| 0d. | **Test suite** | Automated integration tests (simulate 100 events) |
| 1.  | **Feature: Event logging** | Smart contract logs “checkpoint captured” & asset transfers |
| 2.  | **Feature: Indexer service** | GraphQL API exposing real-time leaderboard data |


## Future Plans
- **Enhancements:**  
  - Browser-native Polymesh wallet plugin  
  - Cross-chain support (EVM + Polymesh)  
- **Promotion & Support:**  
  - Publish blog series & host a community workshop  
  - Open-source repository with contribution guidelines  


## Additional Information
- **Discovery:** Found via Polymesh Twitter announcement  
- **Current status:** Live on mainnet
