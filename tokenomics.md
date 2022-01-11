## Tokenomics

**WAV** is our Native Token, on Binance Smart Chain.

**WVP** (WAV Pool) is our Core LP, consisting of **WAV-ACS-BNB** in 6:2:2 ratio. It is a Balancer V2 LP, on the [Acsi.Finance](https://app.acsi.finance/#/pool/0x44a9ce69ef2a71a9630697ca5cab3f4adaf8f90d00010000000000000000001a) deployment, on Binance Smart Chain.

**TGW** is our Governance Vault, consisting of staked **WVP**.

The locked TGW governs the DAO, and also earns DAO revenue and emissions, which will be automatically compounded in the Vault.

Withdrawing from the Governance Vault incurs a withdrawal fee, which is shared among the remaining TGW holders.

* TGW withdrawal fee is set at 88% for the first 6 months after launch, reducing by 15% each month from months 6-12. Where it will be set at 18% thereafter.
* **This is in effect a lockup for TGW holders for the first 6 months of the project with a punitive 88% withdrawal fee.**


![WAV Token](https://raw.githubusercontent.com/acryptos/docs-thegreatwave/main/img/WAV-Token-Pie.svg "WAV Token Distribution")

![Governance Vault Fees Cut Schedule](https://raw.githubusercontent.com/acryptos/docs-thegreatwave/main/img/TGW-withdrawalfees-schedule.svg "Governance Vault Fees Cut Schedule")

### Emissions

3000 WAV per day will be emitted, reducing by 16.88% every 88 days to give a maximum supply of 1,979,869 WAV.

Emissions distribution:

* 60% to TGW
* 10% to Treasury
* 30% to Farms

#### Initial Farm allocations :

* [WVP](https://app.acsi.finance/#/pool/0x44a9ce69ef2a71a9630697ca5cab3f4adaf8f90d00010000000000000000001a) ACSI.finance 5X
* [WAV-BNB](https://pancakeswap.finance/add/BNB/0x888888883BF208d3b1AcD0052a88b9Fd07bA5851) PancakeSwap LP 1X
* [A2B2 WAV Pool](https://app.acryptos.com/wav/) 1X

![WAV Token Emission](https://raw.githubusercontent.com/acryptos/docs-thegreatwave/main/img/WAV-Token-Emission.svg "WAV Token Emission")

### Genesis

* [415,888 WAV](https://bscscan.com/tx/0x2fc52fbcb89abe63f8e14dfc0eda62363d19472daecb95be59af6c0e70cbf618) were minted, and pooled with $284,112 of liquidity provided by the Founding Team, giving WAV an initial value of $1, creating [$700,000 of WVP](https://bscscan.com/tx/0x6b9a83485552b0e3336ae0c05f55b98db60faf5ff4d74a9a5f2c26de38e83464).
* $280,000 WVP was staked into TGW and given to the Founding Team. (TBC)
* $378,000 WVP was staked into TGW and given to the Treasury. (TBC)
* $42,000 WVP was given to the Treasury. (TBC)

**Effectively 94% of WAV and WVP was locked into TGW which has a 90% withdrawal fee for the first 6 months of the project, reducing to 15% in months 6-12.**



### Farm Boost

[Similar to ACryptoS](https://docs.acryptos.com/acryptos-farms#farm-rewards-boost), TGW holders can boost their Farm returns by up to 2.5 times. 

Unlike in ACryptoS, TGW is transferable, and Farm boost will be calculated using a time-weighted average of users’ TGW holdings, including TGW staked in NFTs.

The amount of boost is determined using the same formula as in ACryptoS:

1.5 \* \[% user's share of Governance Vault] \* \[TVL in Farm]&#x20;

(up to a maximum of 2.5X of users’ holdings in Farm)



### Governance NFTs

TGW NFTs will be able to have TGW staked inside each NFT, which can be unstaked by burning the NFT, setting a base value for each NFT. TGW staked in users’ NFTs boost their Farm returns by up to 2.5 times.


### Notes

Liquidity is built into the Governance Vault, so there is no longer a need to separately incentivise liquidity.

It also means Governance Vault holders are expected to take on Impermanent Loss risk. 

The TGW withdrawal fee acts as a lock-in for the Founding Team and early investors. 
