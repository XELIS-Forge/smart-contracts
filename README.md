# XELIS Forge Smart Contracts

A collection of smart contracts powering the XELIS Forge DeFi suite, built on the XELIS blockchain using Silex smart contract language and the XELIS Virtual Machine (XVM).

## Overview

XELIS Forge is a comprehensive DeFi platform that leverages XELIS's unique features. This repository contains the core smart contracts that power the Forge ecosystem.

## Smart Contracts

### Forge Swap
The decentralized exchange (DEX) contract implementing an Automated Market Maker (AMM) for trustless token swapping on the XELIS network.

**Features:**
- Automated Market Maker with constant product formula
- Native support for all XELIS confidential assets
- Liquidity pool management
- Fee distribution to liquidity providers
- Slippage protection

### Token Launchpad
A fair launch platform for new tokens on the XELIS network, enabling projects to bootstrap liquidity and distribute tokens in a decentralized manner.

**Features:**
- Token launch and sale mechanisms
- Automated liquidity pool creation
- Fair distribution models
- Anti-rug pull protections
- Creator earnings

### Asset Locker
A time-locked vault contract for securing tokens and assets, commonly used for team allocations, vesting schedules, and liquidity locks.

**Features:**
- Time-locked token storage
- Flexible vesting schedules

### Fee Collector
Centralized fee management contract for collecting and distributing protocol fees across the Forge ecosystem.

**Features:**
- Protocol fee collection from all Forge contracts
- Multi-recipient distribution
- Fee rate management
- Treasury integration
- Transparent fee accounting

## Security Considerations

- XELIS's privacy features mean balances and amounts are encrypted when transferring between users, however private deposits are currently not a feature. Interacting with contracts is in the clear.
- The XVM sandbox provides security guarantees, but logical vulnerabilities must still be addressed
- Test extensively on testnet before mainnet deployment

## Resources

- [XELIS Website](https://xelis.io/)
- [XELIS Documentation](https://docs.xelis.io/)
- [XELIS Blockchain Repository](https://github.com/xelis-project/xelis-blockchain)
- [XELIS Virtual Machine](https://github.com/xelis-project/xelis-vm)
- [Silex Language Documentation](https://docs.xelis.io/)
- [XELIS Forge Platform](https://xelisforge.app/)

## License

All smart contracts in this repository are licensed under the GNU General Public License v3.0 (GPL-3.0).

## Disclaimer

These smart contracts are provided as-is. Always conduct thorough testing and audits before deploying to production. The XELIS Forge team is not responsible for any losses incurred through the use of these contracts.

## Contact & Community

- **Website:** [@XelisForge](https://xelisforge.app/)
- **Twitter:** [@XelisForge](https://x.com/XelisForge)
- **Discord:** [Xelis Forge](https://discord.gg/49fk8U64Qm)
- **GitHub:** [XELIS-Forge](https://github.com/XELIS-Forge)
- **XELIS Project:** [xelis-project](https://github.com/xelis-project)

---
