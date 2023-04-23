# Used in Project for MIT-Bitcoin Hackathon 2023

https://devpost.com/software/ckbsafe

## What we learned 

Throughout our research on the Nervos CKB blockchain, we gained valuable insights into its unique architecture. The UTXO model of the Nervos CKB blockchain is an enhanced version of Bitcoin's UTXO approach, offering improved security and scalability. Transactions create, update, or consume cells, and the model enables parallel processing, ensuring deterministic outcomes while providing better auditability and reducing the risk of double-spending.

Nervos CKB leverages the RISC-V instruction set to compile smart contracts from various languages into binary files, enabling a versatile development ecosystem. Rust stood out as a popular choice due to its strong safety guarantees, concurrency support, and high-performance capabilities.

Leveraging Rust's expressive type system and pattern matching, we successfully developed and deployed the CKBSafe multi-signature contract. By harnessing Rust's powerful capabilities, we were able to create a reliable and secure solution for managing transactions on the Nervos CKB blockchain.

## Challenges faced

During the development of CKBSafe, we faced several challenges, including limited resources and unfamiliarity with Rust. The Nervos CKB blockchain's architecture, being significantly different from the Ethereum ecosystem, posed a steep learning curve. 

CKB's unique design philosophy, consensus mechanism, and smart contract execution model required us to invest a considerable amount of time and effort into research and understanding the underlying architecture. CKB's distinct approach, such as the use of the UTXO model instead of account-based model and different smart contract languages, demanded that we rethink our development strategies and learn new paradigms.
