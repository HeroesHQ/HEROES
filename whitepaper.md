# **HEROES: A Non-Custodial & Compliant Smart Contract System for Decentralized Work Coordination on the Open Web**

## **Abstract**

This document presents a non-custodial bounty marketplace designed and implemented on the NEAR Protocol. Our platform aims to revolutionize task-based payments by ensuring trust, transparency, and seamless transactions through its smart contract-based escrow system. The architecture, security, and technical details of the platform are discussed, highlighting the benefits offered by blockchain technology.

## **Unleashing Your Inner Hero: Building in the Decentralized Frontier**

Imagine a universe teeming with heroes. Not the ones donning capes or swinging around skyscrapers, but real heroes. The ones who unleash their creativity, turning nothing into something, and ideas into reality. In this digital world, we're all adventurers on the infinite landscape of Web 3.0. Armed with the most powerful tool known to mankind - our creativity - we're changing the universe, one project at a time.

### **Heroes of the Frontier**

In this decentralized frontier, builders are the heroes. They’re the wizards conjuring codes, the smiths forging smart contracts, the architects shaping systems. Builders aren't just shaping their destiny; they’re shaping the future of work and play. It's not about filling a role; it's about fulfilling a purpose.

The advent of blockchain technology has revolutionized numerous sectors, particularly finance, with its immutable, decentralized, and secure nature. The NEAR protocol, with its unique Nightshade sharding approach and the robust proof-of-stake consensus mechanism, offers unparalleled scalability, flexibility, and security for developing decentralized applications.

Our Non-Custodial Bounty Marketplace aims to leverage these advantages to create a secure and transparent ecosystem for job seekers and job providers alike, eliminating the need for intermediaries and fostering an environment of trust and efficiency.

## **Ecosystem Design**

### **Bounty Contracts**

At the core of the marketplace are the escrow bounty contracts. These contracts hold the bounty reward in escrow until the completion of the assigned task. The contract is built with a predefined set of rules, and releases the payment when those conditions are met, ensuring a fair and transparent bounty distribution process.

### **Role of Parties**

#### **Job Providers**

Job providers can create bounties, specifying the task requirements and reward. They are also responsible for approving the completion of tasks and can interact with the bounty contract to release the reward.

#### **Job Seekers**

Job seekers can browse available bounties and apply for tasks that match their skills. Upon task completion, job seekers submit their work, which triggers a review process by the job provider.

#### **Investors**

Investors can view startup opportunities and harvest the HEROES army to boost their portfolio value adding services. The platform allows investors to sign-up to get leads are not just the benefactors; they're the co-creators. They’re not merely injecting funds but are providing the thrust needed to lift these ambitious projects off the ground. By backing these bounties, investors play a crucial role in the actualization of creative endeavours and technological breakthroughs.


![contracts_flow2](https://github.com/HeroesHQ/Kanban/assets/18598519/a81ed417-c375-41f2-a54c-12c800fb3d94)



## **Platform Implementation**

The non-custodial bounty marketplace is built on the NEAR protocol, leveraging its scalable and secure blockchain infrastructure. This section provides technical details of the platform's implementation, including the use of smart contracts and consensus mechanism.

## **Overview of Smart Contracts**

The Non-Custodial Bounty Marketplace is a complex ecosystem powered by several interlinked smart contracts. These contracts govern the platform's operations and ensure security, transparency, and efficiency in the marketplace.

### **Bounty Contract**

This escrow contract forms the core of the marketplace. It holds the bounty reward in escrow until the completion of the task. The contract's conditions are pre-set, ensuring a fair and transparent process of bounty distribution. It also allow to add other whitelist features native to HEROES whcih are not covered in the whitelist contract.

### **Whitelist Contract**

This contract maintains users' whitelist statuses in order to claim certain bounties. It allows bounty creator to specifiy that only users that has completed a KYC check can apply and/or claim a bounty. Theoretically, this contract could be utilized by other trusted partner tools built on NEAR, a concept similar to the KYC DAO approach.

### **Reputation Contract**

This contract fosters transparency within the platform by managing the on-chain reputation of all participants. Users' reputations are based on their marketplace performance and behavior, aiding other participants in making informed decisions.

### **Heroes Token Contract**

This contract manages the creation, distribution, and transactions of the platform's native "Heroes" tokens. These tokens serve as a utility payment method within the ecosystem, facilitating tasks, rewards, and service fees.

### **Dispute Resolution Contract**

This contract comes into play when disputes arise regarding task completion. It manages the dispute resolution process, allowing relevant experts to objectively evaluate the work done and decide on the release of funds from the Bounty Contract's escrow.

### **Service DAO Contract**

Service DAO Contract Built on the Sputnik DAO framework, the Service DAO Contract facilitates task delegation from bounty creators to a Service DAO, reflecting an agency-freelancer coordination model for enhanced efficiency in the open web workforce.

## **NEAR Protocol**

The NEAR protocol's unique sharding approach, Nightshade, enables the platform to efficiently handle large volumes of transactions, making it ideal for the marketplace. The platform's proof-of-stake consensus mechanism ensures security and robustness against potential attacks.

## **Security**

The highest level of security standards is paramount to our platform. We strongly encourage community contributions and peer reviews to ensure and enhance the platform's functuinality & security.

## **Conclusion**

By harnessing the potential of the Near protocol, our Non-Custodial Bounty Marketplace seeks to transform the landscape of task-based payments, ensuring security, fairness, and transparency. With its robust architecture, the platform opens the door for a wide range of potential applications and innovations in the decentralised space.
