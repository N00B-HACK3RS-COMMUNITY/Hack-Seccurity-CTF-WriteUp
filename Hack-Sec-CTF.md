### BlockChain : 

## Hide & Seek 50 :

- Step 1: As one hint is given in challenge about the "Type of Network" so quickly open [```Ropsten Test Network```](https://ropsten.etherscan.io/).
- Step 2: Copy the address from challenge Address:```0xD1F1588598352C73E3797d3F28eAFeCb638700bB``` and paste in Ropsten network.
- Step 3: Ok it'll looks like as given in image, now you need to analyse each and every transactions one-by-one. (Instead of doing that There's an trick look for only those transaction which has been cancelled or failed.
- Step 4: Ok, there's total 9 failed transactions, now this's not a big task... "How to anaylse these transaction" Follow up these steps down!
  - 1. Click on any failed transaction suppose say I click on first one now you'll notice some information about the transaction.
  - 1. For looking over the data inside this transaction you need to scroll down and look for ```Click to see More``` click on that and input data would be there in the hex format simply view as ```UTF-8 in View as Input link```.
  - 1. Boom!! You've your flag! Wait a sec that's not real flag for real flag do follow these step on every failed transactions.
  - 1. Now you'll definetly get your flag at this  location [Real Flag](https://ropsten.etherscan.io/tx/0x1d9e846aff27ef177f0cbc072b04d0a4fbdc3439332f2d536e65e5a43c146789) Flag: HACSEC{h1d33N_4S_d474}.

## I WannaCry 50:

- Step 1: Now this time You need to switch your netwowrk from ```Ropsten --> [Blockchain](https://www.blockchain.com/btc/tx/)``` process is same but this time youe need to find the address of hacker through which the attack was happned or transaction were made. Iterate your addresses on this network you'llget u'r flag.
- Step 2: [Flag Location](https://www.blockchain.com/btc/tx/b4fb81c941ae859a4a21a6f5f5c825282a09d85eeb10f2448b2dcb0693792007). Flag: ```HACSEC{1BwibwNo9nNzyHyZ5bw9ziFAwcM6KKHUq1}```.

## Shards 100 :

- Step 1: this's quite tricky chall, now this time you need to make a transaction or verify it.
- Step 2: [Flag location](https://ropsten.etherscan.io/tx/0xdc9397c7bb1da65d538b7a4deace1ff50638d23d1229322c6aab20b0bbe9f296) [ABI data](https://www.paste.org/110133) you need to encode ABI in hex format then It'll accept it as "ABI-Encoded" try any online encoder like [try this:](https://abi.hashex.org/#) and copy paste Source code available on the flag location mentioned above and verify you'll get flag in failed transaction. Flag : ```HACSEC{Sm4R7_C0n7R4c7s_4r3_fuN}``` click on above flag location and move on state here scroll down click 2nd transaction details check out Storage (2nd) look flag as text format.
