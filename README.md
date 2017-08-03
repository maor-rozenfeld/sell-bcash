# A complete guide to selling your free BCash for Bitcoin

> As others have pointed out, it's your choice to decide whether to sell the BCash or hold it. I am not here to give trading advice. This guide is only meant to help people who have decided to sell their BCash for Bitcoin.
>
> If you don't want to sell, there's nothing you need to do really. You don't need to "claim" your BCash, you already have it.

This guide assumes you had Bitcoins in your possession prior to the hard fork, and you know the private key for those Bitcoins.


## Step 1 - Secure your Bitcoins

***why?***

When you redeem your BCash, you'll possibly expose your seed or your private key. To make sure your Bitcoins don't get lost or stolen, it is highly recommended to move them to a new Bitcoin wallet. 

Redeeming BCash will require you to install a BCash wallet. This wallet is relatively new, and may contain unknown bugs or other issues. By moving your Bitcoins to a new address, you no longer risk losing them. Simply put, you're going to empty both Bitcoin and BCash from the old address - Bitcoin first.

***how?***

If you're using a wallet like Electrum, **you must create a new seed**, keep it safe and don't share it with anyone. Once you have your new wallet, send your Bitcoins to the new wallet.

If all you have is a private key, you can import it to a wallet and send the Bitcoins to a new wallet via [the supported wallets](http://bitcoin.org/en/choose-your-wallet). 

For example, in the online [Blockchain Wallet](http://blockchain.info/wallet), you'll need to create an account, go to **Settings**, **Addresses**, and then **Import Addresses**. Paste your private key, and you'll then be able to **Spend** the address balance to a new one of your choice. *Note: Using Blockchain Wallet itself, with a seed, isn't considered the most secure by some, but here we're only importing an address and then spending it immediately*.


## Step 2 - Install a BCash wallet and import your old Bitcoin address

***why?***

To send your BCash to an exchange site you'll have to use a wallet that supports the BCash network. You cannot do that with a regular Bitcoin wallet.

***how?***

>*Warning: Running both Electrum and Electron Cash on the same machine is a bad idea* 

Support for BCash isn't huge. The most obvious way to do this currently is with [Electron Cash](http://electroncash.org/). Electron Cash isn't related to Electrum, and we can't be completely sure what's inside of those binaries. While there is no evidence that Electron Cash has any malicous code in it, it may be buggy or unstable, and we don't want to take that risk. It is therefore advised to run Electron Cash in a [Virtual Machine](https://www.howtogeek.com/196060/beginner-geek-how-to-create-and-use-virtual-machines/). 

Once you install the wallet, import your old Bitcoin address with the private key. If the wallet shows the transaction to the new Bitcoin address, it's probably listening to the Bitcoin network instead of the BCash one. Go to **Tools**, **Network**, and you can see the servers sorted into 2 groups. These groups are the two chains. Right click on the group that includes `cascharia.com` and `criptolayer.com` and choose **Follow this branch**. You should then be able to spend your BCash.

### Hardware Wallets

* [Instructions for Ledger Blue and Nano S owners](http://support.ledgerwallet.com/knowledge_base/topics/bitcoin-cash)
* [Instructions for Trezor owners](https://blog.trezor.io/claim-bcash-bitcoin-cash-bch-bcc-trezor-wallet-f0a810d5864a)
* [Instructions for Digital Bitbox owners](https://digitalbitbox.com/faq)


## Step 3 - Send the BCash to an exchange of your choice

***why?***

There's no magic that transforms BCash into Bitcoin. You'll need to sell it on an exchange site.

***how?***

The following exchange sites are said to support BCash deposits:

* [HitBTC](https://hitbtc.com/) is accepting BCash deposits, without any customer verification process, and allows you to exchange it only after 2 confirmations.
* [ViaBTC](https://www.viabtc.com/) is accepting BCash deposits, and you can exchange it after 1 confirmation. But you need to wait for 20 confirmations to withdraw the received Bitcoins. Name, mobile number and ID card number are required for verification.

HitBTC seems like the best option for now, with only 2 required confirmations and fast withdrawal of the Bitcoins. In HitBTC, simply register and go to ***Account***, find the ***BCC Bitcoin Cash*** row and click the plus icon ("Fund"). You'll receieve a BCash address and you'll need to send your BCash to that address. You can do that with Electron Cash.

Once you make the transaction you can see it at the bottom of the page (should be instant). After 2 confirmations, your balance will update. You can check the blocks being mined on [BlockDozer](http://blockdozer.com/insight/blocks) or [Blockchair](https://blockchair.com/bitcoin-cash/blocks).

Once your balance updates, make sure to move your BCash from the ***Main Account*** to the ***Trade Account***. This can be done in the same page, in the ***BCC Bitcoin Cash*** row.


## Step 4 - Sell the BCash for Bitcoins

Each exchange site has its own interface and it should be pretty straightforward.

In HitBTC, simply navigate to ***Exchange***, choose ***BCC*** on the table to the right ("Instruments"), and fill the fields under ***Sell BCC*** (Limit).

## Step 5 - Withdraw your free Bitcoins to your new Bitcoin address

***why?***

**Your Bitcoins aren't yours if you don't own the private keys.** You should only leave Bitcoin in an exchange site if you're actively trading it. If you're not, **do not leave it in the exchange site**. Exchange sites are being hacked day and night and people lose their Bitcoins because of this mistake.


***how?***

More detailed instructions will follow, but feel free to send the free Bitcoin to the new address you created in Step 1, or use another new address if you like.

