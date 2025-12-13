# Cyberscope Security Audit

## Audit Information

| Field | Value |
|-------|-------|
| **Auditor** | Cyberscope |
| **Date** | November 26, 2024 |
| **Network** | BSC (Binance Smart Chain) |
| **Contract** | 0x8AaCC38933007eC530c552007E210B4667749DF1 |
| **Compiler** | Solidity v0.8.25 |
| **Optimization** | 200 runs |

## Results Summary

### Critical Analysis

| Check | Description | Result |
|-------|-------------|--------|
| ST | Stops Transactions | **PASSED** |
| OTUT | Transfers User's Tokens | **PASSED** |
| ELFM | Exceeds Fees Limit | **PASSED** |
| MT | Mints Tokens | **PASSED** |
| BT | Burns Tokens | **PASSED** |
| BC | Blacklists Addresses | **PASSED** |

### Vulnerability Summary

| Severity | Count |
|----------|-------|
| Critical | 0 |
| Medium | 0 |
| Minor/Informative | 14 |

## About Minor/Informative Findings

All 14 findings are classified as **Minor/Informative**, meaning:
- Unlikely to be exploited
- Low to no impact on security
- Mostly code style and optimization suggestions

Each finding has been thoroughly analyzed and documented in our [Audit Responses](../audit-responses/).

## Audit Badge

ZETTA WORD is eligible for the Cyberscope audit badge, indicating compliance with security standards.

## Official Links

- **Cyberscope Audit Page:** https://www.cyberscope.io/audits/3-z
- **BSCScan Verified Contract:** https://bscscan.com/token/0x8aacc38933007ec530c552007e210b4667749df1

## Files

- `cyberscope-audit-nov2024.pdf` - Full audit report

---

*Cyberscope is a blockchain cybersecurity company that has secured tens of millions in investor funds across thousands of projects.*
