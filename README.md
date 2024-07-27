# ERC Standards & Proposals Cheat-Sheets

1. ERC-20: Defines a standard interface for fungible tokens on Ethereum.
2. ERC-721: Establishes a standard for non-fungible tokens (NFTs) on Ethereum.
3. ERC-1155: Introduces a multi-token standard that can represent both fungible and non-fungible tokens.
4. ERC-165: Provides a standard method to detect and publish interface implementations.
5. ERC-223: Prevents accidental token loss when sending to contract addresses.
6. ERC-777: Advanced token standard improving on ERC-20 with hooks and operator support.
7. ERC-827: Extends ERC-20 to allow execution of calls in transfers and approvals.
8. ERC-1271: Defines a standard signature validation method for contracts.
9. ERC-1363: Implements a payable token interface for immediate token transfers and calls.
10. ERC-1400: Establishes a standard for security tokens with additional compliance features.
11. ERC-1404: Introduces a simple restricted token standard for regulatory compliance.
12. ERC-1620: Defines a standard for continuous payments through money streaming.
13. ERC-1822: Specifies the Universal Upgradeable Proxy Standard (UUPS) for contract upgrades.
14. ERC-2309: Provides a consecutive transfer extension for more efficient NFT minting.
15. ERC-2535: Defines the Diamond Standard for upgradeable contracts with multiple facets.
16. ERC-2612: Extends ERC-20 with permit function for gasless token approvals.
17. ERC-2771: Establishes a secure protocol for native meta transactions.
18. ERC-2981: Implements a standard for NFT royalty payments.
19. ERC-3156: Defines a standard interface for flash loans.
20. ERC-3643: Establishes a standard for permissioned tokens with transfer restrictions.
21. ERC-4337: Introduces account abstraction via alternative mempool for improved UX.
22. ERC-4626: Defines a tokenized vault standard for yield-bearing tokens.
23. ERC-4907: Implements a rental NFT standard with time-limited permissions.
24. ERC-5023: Establishes a standard for shareable non-fungible tokens.
25. ERC-5114: Defines a standard for soulbound tokens (non-transferrable NFTs).
26. ERC-5484: Introduces a standard for consensual soulbound tokens.
27. ERC-5192: Specifies a minimal soulbound NFT standard.
28. ERC-5528: Implements a standard for refundable NFTs.
29. ERC-6093: Extends ERC-20 with standardized error messages.
30. ERC-6551: Defines non-fungible token bound accounts, allowing NFTs to own assets.
31. ERC-6909: Specifies a minimal multi-token interface for efficient token management.
32. ERC-404: Introduces a new token standard combining fungible and non-fungible properties.
33. ERC-721A: Optimizes the ERC-721 standard for gas-efficient batch minting, developed by Azuki.
34. ERC-918: Mineable Token Standard (for Proof of Work tokens).
35. ERC-1202: Voting Standard for smart contract-based voting.
36. ERC-1410: Partially Fungible Token Standard.
37. ERC-1523: Insurance Policy Standard.
38. ERC-1594: Core Security Token Standard.
39. ERC-1812: Verifiable Claims Standard.
40. ERC-3643: On-Chain KYC/AML Standard.
41. ERC-5095: Principal Token Standard.
42. ERC-5501: Rentable NFT Standard.
43. ERC-5646: Token State Fingerprint.
44. ERC-6147: Guard of NFT/SBT.
45. ERC-6372: Contract Clock.

# EIP (Ethereum Improvement Proposals)

1. EIP-1559: Introduces a new fee market to make gas fees more predictable.
2. EIP-3675: Specifies the upgrade from Proof of Work to Proof of Stake (The Merge).
3. EIP-4844: Proposes proto-danksharding for increased scalability.
4. EIP-1014: Implements CREATE2 opcode for deterministic contract addresses.
5. EIP-1167: Defines a minimal proxy contract for gas-efficient contract cloning.
6. EIP-1193: Standardizes the Ethereum Provider JavaScript API.
7. EIP-1474: Specifies a remote procedure call standard for Ethereum clients.
8. EIP-1967: Defines standard proxy storage slots for upgradeable contracts.
9. EIP-2098: Introduces a compact signature representation for efficiency.
10. EIP-2718: Implements a new transaction type allowing for future upgrades.
11. EIP-2929: Increases gas costs for state access opcodes to mitigate DoS attacks.
12. EIP-2930: Introduces optional access lists to optimize gas usage.
13. EIP-3074: Proposes AUTH and AUTHCALL opcodes for account abstraction.
14. EIP-3198: Adds BASEFEE opcode to access the current block's base fee.
15. EIP-3529: Reduces gas refunds to mitigate potential exploits.
16. EIP-3541: Rejects new contract code starting with the 0xEF byte for future upgrades.
17. EIP-3651: Introduces Warm COINBASE to reduce gas costs for certain operations.
18. EIP-3855: Adds PUSH0 instruction for gas optimization.
19. EIP-4399: Replaces DIFFICULTY opcode with PREVRANDAO for Proof of Stake.
20. EIP-4895: Implements beacon chain push withdrawals as operations.
21. EIP-1973: Proposes scalable rewards distribution on Ethereum.
22. EIP-86: Abstraction of transaction origin and signature.
23. EIP-150: Gas cost changes for IO-heavy operations.
24. EIP-158: State clearing.
25. EIP-160: EXP cost increase.
26. EIP-170: Contract code size limit.
27. EIP-196: Elliptic curve addition and scalar multiplication on alt_bn128.
28. EIP-197: Precompiled contracts for optimal Ate pairing check on the elliptic curve alt_bn128.
29. EIP-198: Big integer modular exponentiation.
30. EIP-211: New opcodes: RETURNDATASIZE and RETURNDATACOPY.
31. EIP-214: New opcode STATICCALL.
32. EIP-225: Clique proof-of-authority consensus protocol.
33. EIP-649: Metropolis difficulty bomb delay and block reward reduction.
34. EIP-658: Embedding transaction status code in receipts.
35. EIP-1052: EXTCODEHASH opcode.
36. EIP-1108: Reduce alt_bn128 precompile gas costs.
37. EIP-1234: Constantinople difficulty bomb delay and block reward adjustment.
38. EIP-1283: Net gas metering for SSTORE without dirty maps.
39. EIP-1344: ChainID opcode.
40. EIP-1884: Repricing for trie-size-dependent opcodes.
41. EIP-2028: Transaction data gas cost reduction.
42. EIP-2200: Structured definitions for net gas metering.
43. EIP-2315: Simple subroutines for the EVM.
44. EIP-2565: ModExp gas cost.
45. EIP-3554: Difficulty Bomb Delay.
46. EIP-3607: Reject transactions from senders with deployed code.
47. EIP-3860: Limit and meter initcode.
48. EIP-4345: Difficulty Bomb Delay to June 2022.
49. EIP-5133: Delaying Difficulty Bomb to mid-September 2022.

# Major Network Upgrades and Forks

1. Frontier: The initial Ethereum mainnet launch.
2. Homestead: The first planned upgrade to the Ethereum network.
3. DAO Fork: Contentious hard fork to address The DAO hack.
4. Tangerine Whistle (EIP-150 revisions): Addressed urgent network health issues.
5. Spurious Dragon (EIP-158, EIP-160, EIP-170): Addressed state bloat and gas price issues.
6. Byzantium: Part of the Metropolis upgrade, introduced zk-SNARKs and other improvements.
7. Constantinople + Petersburg: Combined upgrade addressing implementation issues and delaying difficulty bomb.
8. Istanbul: Implemented various EIPs for network optimization and Ethereum-Zcash interoperability.
9. Muir Glacier: Delayed the difficulty bomb.
10. Berlin: Implemented gas optimizations and new transaction types.
11. London: Implemented EIP-1559 and other significant changes to the fee market.
12. Arrow Glacier: Further delayed the difficulty bomb.
13. Gray Glacier: Another difficulty bomb delay.
14. Paris (The Merge): Transitioned Ethereum from Proof of Work to Proof of Stake.
15. Shanghai + Capella (Shapella): Enabled staked ETH withdrawals and implemented several EIPs for optimization.

