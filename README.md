# BCH Guru Smart Contracts

In this repository you can find the smart contracts used by Bch-Guru.

## Price Prediction Contracts

This folder contains the contracts for price predictions on [app.bch.guru](https://app.bch.guru), the contracts are different for BCH-Play and FURU-Play.

Price predictions happen in two stages, first there is the PvP offer, then when a 2nd player accepts, the PvP Game contract is used.
For FURU-Play there is the additional need for a 'depository' contract which holds the FURU tokens.

For the contracts, the CashScript source code is provided, the compiled artifacts and the CashRPC templates for CashConnect.