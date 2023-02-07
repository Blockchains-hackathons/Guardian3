# Guardian3

[ETHGlobal Hackthon Showcase](https://ethglobal.com/showcase/guardian3-dd1u8)

Guardian3 is a secure and anonymous communication platform for sources (whistleblowers) to share information with journalists. Inspired by The Guardian's SecureDrop service, Guardian3 uses FVM and blockchain technology to provide a user-friendly solution for whistleblowers to share important information with journalists in a secure and confidential manner. Guardian3 is dedicated to making the world a better place.

# Features
- Easy-to-use: Our frontend pages are built with Next.js, and all web3 integrations are supported by Ethers.js and RainbowKit.

- Secure: All communication and documents are encrypted and stored on-chain, providing a permanent and unalterable record. Whistleblowers can verify the authenticity of leaked information through cryptography technology.

- Anonymous: Sources can communicate with journalists anonymously, and the encrypted documents are stored on-chain for a specified duration and number of accesses.

- SBT (SoulBound Token): Journalists must mint our unique SBT in order to be listed on our journalists list and receive messages/documents from sources. SBT provides information about the journalist, including name, email, public wallet address, organization, and professional field.

- Document storage: Our service utilizes the LightHouse SDK to store documents, allowing for the establishment of a 1-of-2 multi-sig between the source and the target journalist's public address.

- Transparency: In our service, encrypted documents and communications are stored on-chain permanently and cannot be altered. Whistleblowers can trust the validity of any further investigative reporting by journalists, as the authenticity of the information can be verified through cryptography technology. This ensures the elimination of the risk of false reports and other unwanted outcomes.

# How it Works
Sources (whistleblowers) can communicate with journalists through two simple steps:

1. Choose a journalist from our journalists list.
2. Upload documents/files/messages and set the encryption algorithm, duration, and access count. The encrypted document/message will then be sent to the target journalist.

# Tech Stack
- Frontend: Next.js
- Web3 Integration: Ethers.js and RainbowKit
- Smart Contracts: Written in Solidity and deployed/tested on Hyperspace and Wallaby Testnet
- Document Storage: LightHouse SDK


