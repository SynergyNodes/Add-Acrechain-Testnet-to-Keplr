# Add Acrechain Testnet to Keplr wallet

You can follow these steps in Google Chrome, Brave browser or any other browser which supports Keplr wallet extension. 

## 1) Open Keplr wallet, right click on it and click on ``Inspect``.

This will open ``DevTools`` window.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-01-min-01.png)

## 2) On the ``DevTools`` window, click on ``Console`` tab.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-02-min.png)

## 3) Copy the following code.

```
window.keplr.experimentalSuggestChain({
  	"chainId": "bamboo_9051-2",
  	"chainName": "Acrechain Testnet",
    "rpc": "https://rpc-testnet2-acre.synergynodes.com",
    "rest": "https://lcd-testnet2-acre.synergynodes.com",
  	"bip44": {
  		"coinType": 60
  	},
  	"coinType": 60,
  	"bech32Config": {
  		"bech32PrefixAccAddr": "acre",
  		"bech32PrefixAccPub": "acrepub",
  		"bech32PrefixValAddr": "acrevaloper",
  		"bech32PrefixValPub": "acrevaloperpub",
  		"bech32PrefixConsAddr": "acrevalcons",
  		"bech32PrefixConsPub": "acrevalconspub"
  	},
  	"currencies": [
  		{
  			"coinDenom": "acre",
  			"coinMinimalDenom": "uacre",
  			"coinDecimals": 18,
  			"coinGeckoId": "unknown"
  		}
  	],
  	"feeCurrencies": [
  		{
  			"coinDenom": "acre",
  			"coinMinimalDenom": "uacre",
  			"coinDecimals": 18,
  			"coinGeckoId": "unknown"
  		}
  	],
  	"stakeCurrency": {
  		"coinDenom": "acre",
  		"coinMinimalDenom": "uacre",
  		"coinDecimals": 18,
  		"coinGeckoId": "unknown"
  	},
  	"gasPriceStep": {
  		"low": 10000000000,
  		"average": 20000000000,
  		"high": 30000000000
  	},
  	"features": [
  		"ibc-transfer",
  		"ibc-go",
  		"eth-address-gen",
  		"eth-key-sign"
  	]  
});
```

## 4) Paste the code in ``Console`` tab.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-03-min.png)

## 5) Press ``Enter``.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-04-min.png)

## 6) Click on ``Approve`` button on Keplr Wallet window.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-05-min.png)

## 7) Close Keplr Wallet and re-open it.

## 8) Click on the networks present at top of Keplr Wallet, scroll down, and select ``Arable Testnet``.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-06-min.png)

## 9) The wallet is ready and you can copy the address.

NOTE: After adding Arable testnet to Keplr wallet, you can import any wallet using the backed up Mnemonic phrase.

![](https://www.synergynodes.com/images/arable-testnet-keplr/Arable-Testnet-Keplr-07-min.png)
