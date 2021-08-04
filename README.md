# Blockchain-Python-hw-19

# 1. INSTALLATION AND PROJECT SETUP:

- Clone the hd-wallet-derive tool into the wallet folder and install it. Then, open terminal and perform the following steps, test that you can run the ./derive script properly and the output will be as shown in the images below

<img width="1435" alt="Screen Shot 2021-08-03 at 19 35 26" src="https://user-images.githubusercontent.com/78338890/128100157-1d750601-a119-42a8-84b2-a3594e93c350.png">
<img width="1429" alt="Screen Shot 2021-08-03 at 19 35 59" src="https://user-images.githubusercontent.com/78338890/128100221-cdafeeb3-2914-4558-a48f-b219cb1ae14d.png">

# 2. Setup wallet.py and constants as well as generate mnemonics:
After this, we create a file called wallet.py which will be our universal wallet script and in it we will import all constants. And in a separate file, constants.py, we will set the following constants:

BTC = 'btc'
ETH = 'eth'
BTCTEST = 'btc-test'

<img width="1436" alt="Screen Shot 2021-08-03 at 19 36 34" src="https://user-images.githubusercontent.com/78338890/128101298-4c5a048b-855c-40d2-a19f-4b12607bb784.png">


# 3. Derive the wallet keys

- Create a function called derive_wallets.
- Create a dictionary object called coins that uses the derive_wallets function to derive ETH and BTCTEST wallets.

<img width="1436" alt="Screen Shot 2021-08-03 at 19 36 34" src="https://user-images.githubusercontent.com/78338890/128101309-9c0c6072-3194-4581-9c38-a6b5b35a4436.png">
<img width="1430" alt="Screen Shot 2021-08-03 at 19 39 28" src="https://user-images.githubusercontent.com/78338890/128101360-9687fc9b-4529-457a-b406-cefe5920d411.png">

# 4. Transactions with Bitcoin Testnet:

There are three functions, which are described below:

priv_key_to_account: This reveals the public address based on the private key input.

create_tx: This prepares the transaction offline, with the inputs of: sender private key, recipient address, amount, and coin (currency). When this function runs succesfully, it prints out a string with the sender address. For the BTC testnet network the output of this function is ready to broadcast, while ethereum transactions need an extra step to approval.

send_tx: This function essentially broadcast the transaction to the corresponding cryptocurrency network. When this function runs succesfully, it prints out a message transaction successful along with the coin and the amount of the transaction.

create_tx: This prepares the transaction offline, with the inputs of: sender private key, recipient address, amount, and coin (currency). When this function runs succesfully, it prints out a string with the sender address. For the BTC testnet network the output of this function is ready to broadcast, while ethereum transactions need an extra step to approval.

<img width="878" alt="Screen Shot 2021-08-03 at 14 01 01" src="https://user-images.githubusercontent.com/78338890/128101595-36261e92-7bd4-42e7-a793-8a271c75b90f.png">

<img width="1363" alt="Screen Shot 2021-08-03 at 14 01 32" src="https://user-images.githubusercontent.com/78338890/128101604-09586406-225f-4539-ae92-b34acef7de82.png">

<img width="1359" alt="Screen Shot 2021-08-03 at 14 08 54" src="https://user-images.githubusercontent.com/78338890/128101617-811c73df-da4d-49e1-9fef-f2046eb97665.png">

# 5. Transactions in Local Ethereum Network:

<img width="1396" alt="Screen Shot 2021-08-03 at 20 10 59" src="https://user-images.githubusercontent.com/78338890/128101768-0f298ff3-022b-4648-bbfd-017cc0261736.png">






