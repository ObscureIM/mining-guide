# mining-guide

There are two ways to mine XSC, namely via the solo miner packaged in the main release or by usign XMR-Stak which is highly recommended.


Method 1: Solomining

First download the latest release package here: https://github.com/ObscureIM/ObscureIM/releases
Extract v0.Someversion-youros.zip anywhere on your computer.

To solomine, type this command , changing the parameters as needed:

```
/path/to/v0.SomeVersion-youros.zip/miner --address <address> //change address to your own address
```

Method 2: XMR-STAK

You will first need to download XMR-STAK. Download it from the official xmr-stak repositiory here: https://github.com/fireice-uk/xmr-stak/releases

Extract xmr-stak anywhere on your desktop.

You will need to join a mining pool. Luckily we have our own official mining pool. If you want to set up your own mining pool please go to this repository:

This is the link to our mining pool: https://pool.obscure.im

Open your command prompt and type in the following

```
/path/to/xmr-stak/bin/xmr-stak

//type this when prompted
Do you want to use the HTTP interface? //put 0 unless u want to have an API
Please enter the currency that you want to mine // type cryptonight_lite_v7
Pool Address //depending on your hardware specification, for example https://pool.obscure.im:3333
Username //your wallet address
Password //your password, empty is fine too
Rig identifier for pool-side statistics //l eave this empty, just press enter if you are using the official pool
Does this pool port support TLS/SSL? //Y
Do you want to use nicehash on this pool? //N , but it's up to you
- Do you want to use multiple pools?? //N , but it's up to you
```
