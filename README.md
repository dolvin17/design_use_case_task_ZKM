**Complete this form to earn ZKM POINTS. POINTS can be used to unlock ZKM-exclusive opportunities. **
## 1. Define universal settlement?
Metaphorically speaking it’s finalising some kind of operation where all of the obligations between any of the involved parties are satisfied. Defining universal settlementIs, is the process of finalising a transaction, so we can say that transaction isn’t able to be reverted once it was executed. 

## 2. Why is Universal Settlement important and how is ZKM achieving this?
This is important because it acts as a guarantee that a transaction can't be reverted. ZKM is using entangled rollups in order to make this posible.

## 3. What is an Entangled Rollup? Describe its capabilities
It's a way to trustlessly pass messages from one chain to another using zkp. It can create/improve/allow interoperability. How? Sending assets/messages/funds across chains even if they are on incompatible chains. 

## 4. How Does the Analogy of Quantum Entanglement Relate to ZKM's Quantum Network?
In quantum mechanics, entangled particles share a unique connection. When you measure the state of one entangled particle, the other particle **instantly reflects the same state**, regardless of distance. ZKPs allows one party (prover) to convince another party (verifier) that a statement is true without revealing any additional information about the statement itself.  The Analogy is about in ZKM's Quantum Network, **messages maintain their properties regardless of their placement on different or incompatible blockchains.**

## 5. Elaborate on the Advantages that ZKM's Quantum Network offers.
- We must start mentioning interoperability: ZKM allows communication between incompatible or isolated blockchains no matter if they are EVM/MVM/SVM/NVM..  using ZK proofs.
- The other massive point is trustless: the quantum network doesn’t depend on any kind of external third-party validator, it has the capabilities of cross bridging without having to implement the architecture of an actual bridge.
- Also this Quantum Network can enable Native Liquidity across this incompatible chains, for example any funds that a user deposits into an L1 within the quantum network can also be used across all the L2 within this network and users can also withdraw to any other L1.
- 

** design_use_case_task_ZKM ** 
Here is my idea:

`ZKM-based KYC verification`

KYC processes are essential, we all know this, but they are too intrusive as you expose your personal data to a third party that you don't know if you can trust. Personally, this worries me since it puts my privacy at risk and sometimes discourages me from using certain protocols or services that ask me to do so.

That is why I thought we can create a KYC verification system in which people can prove their identity and comply with regulatory requirements without revealing a single personal data.

How ZKM-based KYC verification might works:

Registration: The customer registers on our platform and provides basic information such as their name and email address.

Identity verification: The customer uses their mobile device to capture an image of their identity document (for example, passport or driver's license). The image is processed locally on the client's device, extracting biometric characteristics and other relevant data.

ZKP Generation: The client device generates ZKP that proves that the captured image is valid and belongs to the client. The ZKP does not reveal any personal information, only identity verification.

Sending ZKP to the platform: The ZKP is securely sent to our platform. The platform verifies the ZKP using the ZKM system, confirming the authenticity of the customer's identity without accessing any personal data.

Regulatory Compliance: Our platform uses verified information to assess customer compliance with regulatory requirements. If the client complies, they are granted access.

Summarizing a lot: we can use ZKM to generate zkproofs that allow us to create more efficient KYC processes and that truly protect the security of users 1000%

Thank you for reading this. I think I will try on this if I have a chance in a hackathon. 🔥