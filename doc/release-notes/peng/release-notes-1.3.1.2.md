1.3.1.2 Release notes
=====================

- Block Cryptopia wallet from sending transactions to preserve user funds until a suitable solution is found
- Update rewards table: cut rewards 50%, but have slower decline. 16,000,000,000 max supply with 2% inflation average over 30 years.
- Finalize rebrand to PENG: updated client name, graphics, copyright (& DATAFOLDER LOCATION & CONF FILE! SEE BELOW)
- Added checkpoints to ensure chain splits are no longer synced after bootstrap
- Updated ports to range of 3181 - 3188
- Add an extra timed check for mature coins (for staking)
- Push zPENG activation back another year (precautionary, until fix is found or disabled)
- Fix testnet (& it's stakemodifer)
- Update dependencies to a somewhat suitable selection (minor issues remain)
- Created a summary of PENG including project summary, (social) media links, masternode setup guide & blockchain specifications in git's README.md
- Update protocol to 70230
- Update version number to 1.3.1.2
- Disconnect all old nodes from block 525,601

### CHANGE OF BINARY NAMES, CONF FILE & DATAFOLDERS TO SUIT REBRAND
- Windows: peng-qt.exe, peng.conf datafolder PENG
- Linux: peng-qt, peng.conf & datafolder .peng
- Mac: peng-qt, peng.conf & datafolder PENG
- This means that for this update, you will need to update your binaries, change datafolder and peng.conf names & use the bootstrap when upgrading.

It is important everyone upgrades as soon as possible. Starting at block 525,601 old nodes are no longer valid.
The next update will disconnect ALL nodes that have not been updated!