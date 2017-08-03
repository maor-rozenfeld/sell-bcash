# A complete guide to sell your free BCash for Bitcoin

> **TAKE A DEEP BREATH**<br/>
> Your BCash doesn't go anywhere. <br/>
> As of 02/08 18:20 UTC, the known exchange sites to support BCash deposits are HitBTC and ViaBTC.

This guide assumes you had Bitcoins in possession prior the hard fork, and you know your private key for those Bitcoins.


## Step 1 - Secure your Bitcoins

***why?***

When you redeem your BCash, you'll possibly expose your seed or your private key. To make sure your Bitcoins don't get lost or stolen, it is extremely recommended to move them to a new Bitcoin wallet. 

Redeeming BCash will require you to install a BCash wallet. This wallet is relatively new, and may contain unknown bugs or other issues. By moving your Bitcoins to a new address, you no longer risk losing them. Simply put, you're going to empty both Bitcoin and BCash from the old address - Bitcoin first.

***how?***

If you're using a wallet like Electrum, **you must create a new seed**, keep it safe and don't share it with anyone. Once you have your new wallet up, send your bitcoins to the new wallet.

If all you have is a private key, you can import it to a wallt and send it to a new one via [the supported wallets](http://bitcoin.org/en/choose-your-wallet). 

For example, in the online [Blockchain Wallet](http://blockchain.info/wallet), you'll need to create an account, go to **Settings**, **Addresses**, and then **Import Addresses**. Paste your private key, and you'll then be able to **Spend** the address balance to a new one of your choice. *Note: Using Blockchain Wallet itself, with a seed, isn't considered the most secure by some, but here we're only importing an address and then spending it immediatly*.


## Step 2 - Install a BCash wallet and import your old Bitcoin address

***why?***

To send your BCash to an exchange site you'll have to use a wallet that supports the BCash network. You cannot do that with a regular Bitcoin wallet.

***how?***

>*Warning: Running both Electrom and Electron Cashe on the same machine is a bad idea* 

Support for BCash isn't huge. The most obvious way to do this currently is with [Electron Cash](http://electroncash.org/). Electron Cash isn't related to Electrum, and we can't be completely sure what's inside of those binaries. While there is no evidence that Electron Cash has any malicous code in it, it may be bugged or unstable, and we don't want to take that risk. It is therefore advised to run Electron Cash in a [Virtual Machine](https://www.howtogeek.com/196060/beginner-geek-how-to-create-and-use-virtual-machines/). 

Once you install the wallet, import your old Bitcoin address with the private key. If the wallet shows the transaction to the new Bitcoin address, it's probably listenning to the Bitcoin network instead of the BCash one. Go to **Tools**, **Network**, and you can see the servers sorted into 2 groups. These groups are the two chains. Right click on the group that includes `cascharia.com` and `criptolayer.com` and choose **Follow this branch**. You should then be able to spend your BCash.

### Hardware Wallets

* [Instructions for Ledger Blue and Nano S owners](http://support.ledgerwallet.com/knowledge_base/topics/bitcoin-cash)
* [Instructions for Trezor owners](https://blog.trezor.io/claim-bcash-bitcoin-cash-bch-bcc-trezor-wallet-f0a810d5864a)
* [Instructions for Digital Bitbox owners](https://digitalbitbox.com/faq)

### Doing it from source code

* Grab the source from https://github.com/Bitcoin-ABC/bitcoin-abc
* Compile it.   I followed this guide: https://gist.github.com/kostaz/19729e6d53adc5d1606c
* Import your now-empty wallet seed using the command "bitcoin-cli importprivkey <privkey>".   You can use this to get the WIF from your extended seed: http://bip32.org/, or this: airbitz.co/recovery.   You have to import all of them!
* Wait for the blockchain to sync (took me a day).   You will run into issues with peering.   Just restart from time to time.   Eventually it will sync up
* Use bitcoin-cli sendtoaddress to send your bitcoins to the exchange

## Step 3 - Send the BCash to an exchange of your choice

***why?***

There's no magic that transforms BCash into Bitcoin. You'll need to sell it in an exchange site.

***how?***

The following exchange sites are said to support BCash deposits.

* [HitBTC](https://hitbtc.com/) is accepting BCash deposits, without any customer verification process, and allow you to exchange it only after 2 confirmations.
* [ViaBTC](https://www.viabtc.com/) is accepting BCash deposits, and you can exchange it after 1 confirmation. But you need to wait for 20 confirmations to withdrawal the received Bitcoins. Name, mobile number and ID card number are requiered for verification.

>***Warning: we don't know if any of these exchange sites will actually let you withdraw your Bitcoins, it's on your own risk. I will update once we have proven reports***

You can check the blocks being mined on [BlockDozer](http://blockdozer.com/insight/blocks) or [Blockchair](https://blockchair.com/bitcoin-cash/blocks).


## Step 4 - Sell the BCash for Bitcoins

More detailed instructions will follow, but each exchange site has its own interface and it should be pretty straight-forward.


## Step 5 - Withdraw your free Bitcoins to your new Bitcoin address

***why?***

**Your Bitcoins aren't yours if you don't own the private keys.** You should only leave Bitcoin in an exchange site if you're actively trading it. If you're not, **do not leave it in the exchange site**. Exchange sites are being hacked day and night and people lose their Bitcoins because of this mistake.


***how?***

More detailed instructions will follow, but feel free to withdraw the free Bitcoin to the new address you've created on Step 1, or create another new address if you like.
