
As a general rule, it is considered a lot more secure to compile a software yourself, rather than download the already compiled binaries from the internet.

Follow the instructions to compile the full Bitcoin ABC wallet, which you can use to spend your BCash:

* Grab the source from [here](https://github.com/Bitcoin-ABC/bitcoin-abc)
* Compile it. You follow [this guide](https://gist.github.com/kostaz/19729e6d53adc5d1606c).
* Start the daemon: `bitcoind -daemon -disablesafemode`
* Import your now-empty wallet seed using the command `bitcoin-cli importprivkey <privkey>`. To get the WIF from your extended seed, use [bip32](http://bip32.org/) or [airbitz](airbitz.co/recovery). **You have to import all of them!**
* Wait for the blockchain to sync (might take a day). You will run into issues with peering. Just restart from time to time.   Eventually it will sync up
* Use `bitcoin-cli sendtoaddress` to send your bitcoins to the exchange
