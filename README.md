# MUE2.0
Apologies, repo is now located at
https://github.com/muecoin/MUE


Importing wallet balances from MUE 1.0.3 wallets into MUE 2.0 wallets
MUE has migrated to a completely new codebase, and as such, is no longer compatible with the previous network and blockchain used by the old 1.0.3 wallets. As part of the migration to the MUE 2.0 wallets and network, users can redeem their old wallet balances* into their new wallets. This process is simple, but if not done correctly could risk you losing all your coins. Please follow these simple steps

BACKUP your old MUE wallet (most critical is your wallet.dat file!)
Move that back up somewhere safe e.g USB drive, seperate computer.
Make a list of your wallet addresses (you may need to look in "coin control" for a full list)
For each wallet address (that you know has a balance of MUE) in debug console run "dumpprivkey enteryourmuewalletaddresshere"
Record the private key (securely & safely) that is printed there
As per item 2) Backup your old MUE wallet (just to be sure). Again, critical is your wallet.dat file
Uninstall your old MUE wallet IF you are installing the 2.0 wallet on the same machine (to avoid any conflicts)
Install the new MUE 2.0 wallet
In debug console run "importprivkey enteryourprivatekeyhere"
You should now see your old MUE balance re-instated into the new MUE 2.0 wallet. For security, we recommend you now send those coins to yourself to a newly generated receive address created in your own 2.0 wallet.

For support, please don't hesitate to join us in our chat platform at http://discord.gg/5PD3X7G

*Only transactions up to and including block 833658 will be processed
