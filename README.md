# Unit-21-Token-Crowdsale

Project : Launch a crowdsale to convert their ether money to KaseiCoin.

## Step 1 - Create the KaseiCoin Token Contract

![step 1](/Evaluation%20Evidence/step_1.png)

---

## Step 2 - Create the KaseiCoin Crowdsale Contract

![](/Evaluation%20Evidence/step_2.png)

---

## Step 3 - Create the KaseiCoin Deployer Contract

![](/Evaluation%20Evidence/step_3.png)

---

## Step 4 - Deploy and Test the Crowdsale

1. Contract Setup

![](/Evaluation%20Evidence/step_4_contractSetup.gif)

2.  Purchase new KAI Tokens
```
1. check the balances of accounts(OxA8...0874 = beneficiary address)
2. review total supply of minted token (1000 KAI tokens)
3. amount of wei reaised (1000 wei)
```
![](/Evaluation%20Evidence/step_4_purchaseToken.gif)

---

## Step 5 - Deploy Crowdsale Contract of **Extended Features**

1. Send ether to the crowdsale from Account 2 , 3, 4 in **Matamask**, which are top 3 accounts in **Ganache**. Ether amount **50, 40, 30** respectively.

2. All ether raised to Wallet - **Account 5 in Matamask**, which is the **4th** account in **Ganache**. Final **Ether Balance** is expected to be `100+50+40+30 =Total 220 `

3. Extend Crowdsale COntract Features:
```
open time for crowdsale :  'now' , 
close time for crowdsale : 'now + 8 minutes'
min. amount of goal for KAI tokens : '100 ETH'
cap of KAI tokens raised: '200 ETH'
```
![](/Evaluation%20Evidence/deployContract_a.gif)

...continue from above

![](/Evaluation%20Evidence/deployContract_b.gif)

---

## Step 6 - Review tokens in MataMask

> **Press** `finalize` function to end the sale after close time (**8 minutes**) of deployment.- To stored tokens in **Crowdsale contract**.

> **Press** `withdrawTokens` function, set `beneficiary` address for Account 2 , 3, 4 in **Matamask**. - To transfer tokens to **Token contract**

```
Review tokens in MataMask
```
![](/Evaluation%20Evidence/final_token.gif)

---
