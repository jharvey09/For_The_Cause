## For The Cause
Your company has decided to crowdsale their PupperCoin token in order to help fund the network development. This network will be used to track the dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. You have already worked with the necessary legal bodies and have the green light on creating a crowdsale open to the public. However, you are required to enable refunds if the crowdsale is successful and the goal is met, and you are only allowed to raise a maximum of 300 Ether. The crowdsale will run for 24 weeks.

You will need to create an ERC20 token that will be minted through a Crowdsale contract that you can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will need to inherit Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.

You will conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.

ERC20 PupperCoin
You will need to simply use a standard ERC20Mintable and ERC20Detailed contract, hardcoding 18 as the decimals parameter, and leaving the initial_supply parameter alone.

You don't need to hardcode the decimals, however since most use-cases match Ethereum's default, you may do so.

Simply fill in the PupperCoin.sol file with this starter code, which contains the complete contract you'll need to work with in the Crowdsale.

PupperCoinCrowdsale
Leverage the Crowdsale starter code, saving the file in Remix as Crowdsale.sol.

You will need to bootstrap the contract by inheriting the following OpenZeppelin contracts:

Crowdsale

MintedCrowdsale

CappedCrowdsale

TimedCrowdsale

RefundablePostDeliveryCrowdsale

ERC20 PupperCoin
You will need to simply use a standard ERC20Mintable and ERC20Detailed contract, hardcoding 18 as the decimals parameter, and leaving the initial_supply parameter alone.

You don't need to hardcode the decimals, however since most use-cases match Ethereum's default, you may do so.

Simply fill in the PupperCoin.sol file with this starter code, which contains the complete contract you'll need to work with in the Crowdsale.

PupperCoinCrowdsale
Leverage the Crowdsale starter code, saving the file in Remix as Crowdsale.sol.

You will need to bootstrap the contract by inheriting the following OpenZeppelin contracts:

Crowdsale

MintedCrowdsale

CappedCrowdsale

TimedCrowdsale

### Images
*Compling and deploying contract*
![2021-11-06 (4)](https://user-images.githubusercontent.com/80294571/140630493-9e506e5d-f55b-421f-9eeb-404125da964f.png)

![2021-11-06 (6)](https://user-images.githubusercontent.com/80294571/140630511-7325fc79-b644-44dc-9cba-4a27aeec45fe.png)

![2021-11-06 (8)](https://user-images.githubusercontent.com/80294571/140630525-9938d281-bb37-46e5-9f35-e25f7186a51b.png)

![2021-11-06 (17)](https://user-images.githubusercontent.com/80294571/140631096-e9c19da9-f5e9-4b02-b8d9-1b7228baec05.png)

![2021-11-06 (18)](https://user-images.githubusercontent.com/80294571/140631121-f5e4ede2-6f36-47ed-b8e6-891a2e357fa4.png)

![2021-11-06 (19)](https://user-images.githubusercontent.com/80294571/140631135-8526f535-4864-444b-b47a-7c300e2560b3.png)

![2021-11-06 (20)](https://user-images.githubusercontent.com/80294571/140631158-c949d6d6-3fe9-43cf-9fc1-43d741a45d8a.png)

![2021-11-06 (21)](https://user-images.githubusercontent.com/80294571/140631187-ff9fc573-2ba1-453d-986a-ccabdd401235.png)

![2021-11-06 (22)](https://user-images.githubusercontent.com/80294571/140631206-a190a305-35b4-458e-9dee-130e2f3831c2.png)

![2021-11-06 (23)](https://user-images.githubusercontent.com/80294571/140631224-98150f85-6d8a-4042-989c-0cda745152bc.png)

![2021-11-06 (24)](https://user-images.githubusercontent.com/80294571/140631239-c85430b1-ad6a-4871-80b9-732d42b665f3.png)











