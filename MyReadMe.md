# We are going to be making a stablecoin

1. (Relative Stability) Anchored or Pegged -> $1.00
    1. Chainlink Price Feed.
    2. Set a function to exchange ETH & BTC -> $$$
2. Stability Mechanism (Minting): Algorithmic (Decentralised)
    1. People can only mint the stablecoin with enough collateral (coded)
3. Collateral: Exogenous (Crypto)
    1. wETH ---> ERC20 version of ETH
    2. wBTC ---> ERC20 version of BTC

Fuzz testing: Supply random data to your system in an attempt to break it.

Invariant: Properties of our system that should always hold. i.e uint256 public shouldAlwaysBeZero = 0;

// Have our invariant aka properties

// What are our invariants?

// 1. The total supply of DSC should be less than the total value of collateral
// 2. Getter view functions should never revert <- evergreen invariant 

