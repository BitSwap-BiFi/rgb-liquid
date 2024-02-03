# RGB & Liquid 🌊 🔴🟢🔵

⚠️**Study proposal and PoC**

PoC for RGB and Liquid on DEX

Based on RGB Core v0.11

### How works

- Alice send for Bob token into Liquid to RGB using PSBT
- Both verify UTXOs between Liquid and RGB
- Later Bob receive USDT from Liquid and Alice USDT from RGB

*Obsevation*

*All script can be locked in a coveant script on Liquid side and then burn asset between Alice and Bob*

### What's necessary for this happen?

 - Centralized bridges and issuers allow verify UTXOs among parties
 - Liquidity constant to tokens of Liquid and RGB,which is powered by PSBT
 - Secondary issue assets from [RGB side](htps://github.com/RGB-WG/rgb-schemata/issues/20)
 - Run Liquid Node or if necessary become member of the Federation

## Disclaimer

This is only for study proposal in future integrations
