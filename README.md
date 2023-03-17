# Blockchain decentralization measurement

## Goal of this repository

Blockchain decentralization is widely acknowledged as a core virtue of blockchains. Public blockchains, like *Bitcoin* and *Ethereum*, are based on cryptocurrencies distributed between blockchain participants. Cryptocurrencies play a significant role in the usage and development of blockchain ecosystems; therefore, wealth decentralization evaluation is very relevant. This repository provides data and results of analysis of wealth decentralization measurement for *Bitcoin* and *Ethereum* blockchain networks using various metrics.

## Metrics considered

For the blockchain wealth decentralization the following metrics considered:

- *Gini index,*
  
- *Shanon entropy*,
  
- *Nakamoto coefficient*,
  
- *Herfindahl-Hirschman index*,
  
- The proposed *block-based Herfindahl-Hirschman index*.
  

## Data sets and wealth decentralization calculations
Dataset are provide in the directory [Data](Data/)

We consider 10,000 addresses with the largest balances to evaluate wealth decentralization.

*Bitcoin* data of top balances can be accessed at [Whale Addresses - Bitcoin(BTC) - BTC.com Professional Data Service for Global Blockchain Enthusiasts](https://explorer.btc.com/btc/top-address). We provide a snippet of the dataset on *01.09.2022* and wealth decentralization calculations using the metrics mentioned above.

- [Bitcoin data 01.09.2022](Data/BTC-Top10000-balances-01.09.2022.xlsx)

*Ethereum* data of top balances can be accessed at [Ethereum Top Accounts by ETH Balance | Etherscan](https://etherscan.io/accounts). We provide two snippets of the dataset on *01.09.2022* (before PoS) and *31.01.2023* (after PoS) and wealth decentralization calculations using the metrics mentioned above.

- [Ethereum data 01.09.2022](Data/ETH-PoW-Top10000-balances-01.09.2022.xlsx)
- [Ethereum data 31.01.2023](Data/ETH-PoS-Top10000-balances-31.01.2023.xlsx)

## Contribution to this repository

We welcome contributions and corrections to this resource either way:

- **common way** - send us your comments, corrections or suggestions by email: [mindaugas.juodis@mif.vu.lt](mailto:mindaugas.juodis@mif.vu.lt), [ernestas.filatovas@mif.vu.lt](mailto:ernestas.filatovas@mif.vu.lt), [remigijus.paulavicius@mif.vu.lt](mailto:remigijus.paulavicius@mif.vu.lt).
  
- **modern way** - [fork](https://help.github.com/articles/fork-a-repo/) github repository, add new information & correct existing, then create a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) and we gratefully incorporate your contribution!
  

## Acknowledgment

- This research has received funding from the Research Council of Lithuania (LMTLT), agreement No. S-MIP-21-53.
