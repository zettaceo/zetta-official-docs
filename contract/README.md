# ZETTA WORD Smart Contract

## Contract Information

| Property | Value |
|----------|-------|
| **Name** | zetta_word |
| **Symbol** | Z |
| **Network** | Binance Smart Chain (BSC) |
| **Address** | `0x8AaCC38933007eC530c552007E210B4667749DF1` |
| **Standard** | BEP-20 |
| **Compiler** | Solidity v0.8.25 |
| **Optimization** | 200 runs |
| **Total Supply** | 1,000,000,000 Z |
| **Decimals** | 18 |

## Verified Source Code

The contract source code is verified on BSCScan:
- [View on BSCScan](https://bscscan.com/token/0x8aacc38933007ec530c552007e210b4667749df1#code)

## Contract Features

### Inherited Contracts (OpenZeppelin)

1. **ERC20** - Standard token implementation
2. **ERC20Burnable** - Token burning capability
3. **Ownable2Step** - Secure two-step ownership transfer
4. **Initializable** - Safe initialization pattern

### Custom Features

1. **Fee System**
   - Buy fees
   - Sell fees
   - Transfer fees
   - Maximum total fee: 25%

2. **Liquidity Management**
   - Automatic liquidity provision
   - Swap threshold configuration

3. **Tax Distribution**
   - Configurable tax wallet
   - Automatic distribution

4. **AMM Integration**
   - PancakeSwap V2 Router integration
   - Configurable AMM pairs

## Key Functions

### View Functions

```solidity
function decimals() public pure returns (uint8)
function getAllPending() public view returns (uint256)
function getSwapThresholdAmount() public view returns (uint256)
function isExcludedFromFees(address) public view returns (bool)
```

### Owner Functions

```solidity
function taxbuyAddressSetup(address _newAddress) public onlyOwner
function taxbuyFeesSetup(uint16 _buyFee, uint16 _sellFee, uint16 _transferFee) public onlyOwner
function liquidityFeesSetup(uint16 _buyFee, uint16 _sellFee, uint16 _transferFee) public onlyOwner
function excludeFromFees(address account, bool isExcluded) public onlyOwner
function updateSwapThreshold(uint16 _swapThresholdRatio) public onlyOwner
function setAMM(address pair, bool isPair) external onlyOwner
```

### Recovery Functions

```solidity
function recoverToken(uint256 amount) external onlyOwner
function recoverForeignERC20(address tokenAddress, uint256 amount) external onlyOwner
```

## Security Considerations

1. **No Mint Function**: Supply is fixed at deployment
2. **Fee Limits**: Maximum 25% total fees enforced
3. **Two-Step Ownership**: Prevents accidental ownership loss
4. **Anti-Bot**: Assembly-based caller verification

## Token Distribution

| Allocation | Percentage | Address |
|------------|------------|---------|
| Vesting Contract | 52% | 0x10b5...5774c |
| Main Wallet | 48% | 0x072c...1668a |

---

*Source code is verified and open for public review on BSCScan.*
