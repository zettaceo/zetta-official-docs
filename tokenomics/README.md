# ZETTA Token Economics — Official

> **Version 2.0 — July 2026.** This document supersedes the December 2024
> tokenomics (presale / transaction-fee / gradual-burn model). The values
> below are the **single official reference**, consistent with the
> institutional site, the public whitepaper and the print documents.

## Token Information

| Property | Value |
|----------|-------|
| **Name** | ZETTA WORD |
| **Symbol** | Z |
| **Network** | Binance Smart Chain (BSC) |
| **Standard** | BEP-20 |
| **Decimals** | 18 |
| **Contract** | `0x8AaCC38933007eC530c552007E210B4667749DF1` |
| **Initial Total Supply** | 1,000,000,000 Z |
| **Pre-Fair-Launch Burn** | 500,000,000 Z |
| **Final Supply** | 500,000,000 Z |

## Supply Structure

| Step | Amount | Event |
|------|--------|-------|
| 1 | 1,000,000,000 Z | Initial supply at deploy |
| 2 | −500,000,000 Z | **Pre-fair-launch burn** — executed before the fair launch begins, verifiable on-chain |
| 3 | 500,000,000 Z | Final official supply for the operational cycle |

No further burns are scheduled after the pre-fair-launch event.

## Distribution (over the final 500M supply)

| Category | Official % | Institutional guideline |
|----------|-----------|------------------------|
| Fair Launch + Liquidity (dynamic via AMM) | **45%** | Dynamic on-chain liquidity execution |
| Staking & Rewards | **20%** | Functional network incentives |
| Treasury | **13%** | Operational sustainability of the ecosystem |
| Marketing & Acquisition | **10%** | Adoption and operational expansion |
| Development | **10%** | Technical roadmap and continuous maintenance |
| Founders (long vesting) | **4%** | Allocation under extended vesting schedule |
| Advisors (vesting & restrictions) | **3%** | Allocation under institutional restrictions |

## Fair Launch Mechanics

- **Model:** Fair Launch AMM — **no hardcap, no fixed price**.
- **Softcap:** USD 6,000,000 (technical reference parameter for the launch phase).
- **Liquidity formation:** **51%** of proceeds → on-chain liquidity · **49%** → operational treasury.

## Fair Launch Participation Registry & Benefits

Participation in the fair launch is registered technically **on-chain** for
institutional transparency, regulatory predictability and historical
traceability.

1. **Fair Launch Participant Tier** — functional recognition of the
   participating wallet, badge and access to an exclusive ecosystem area.
2. **Executive Advisory Circle** — non-deliberative advisory structure with
   executive context access; no financial governance, no treasury powers.
3. **Priority Access to Future Modules/Products** — operational priority in
   future modules and activation queues.

> The participation registry is technical and transparency-oriented. It
> **does not create financial rights**, does not promise economic performance
> and does not change the utility nature of the Z token.

## Token Utility (functional)

- Activation of modules and service flows across the ecosystem.
- Technical integration with the ecosystem's staking/rewards mechanisms.
- Support for on-chain participation tracks and functional recognition.

> The Z token does not represent equity, does not constitute a security and
> does not imply any promise of financial performance.

## Contract Security

- **Audited:** Cyberscope (November 2024) — 0 critical, 0 medium findings.
- **KYC Verified:** team identity verified (December 2024).
- **No mint function:** supply cannot be increased.
- **Ownership:** OpenZeppelin `Ownable2Step`.
- **Fee limit:** maximum 25% hardcoded in the contract (see [contract](../contract/) for the fee system specification).

## Regulatory Posture

ZETTA acts as a modular digital infrastructure provider. It is **not a bank
and not a financial institution**; financial and digital-asset services are
operated through authorized/regulated partners, per applicable jurisdiction.

## Verification

- **BSCScan:** [View Contract](https://bscscan.com/token/0x8aacc38933007ec530c552007e210b4667749df1)
- **Audit:** [Cyberscope](https://www.cyberscope.io/audits/3-z)

---

*This document is informational and technical. It does not constitute an
offer of securities, financial advice or a promise of financial performance.*
