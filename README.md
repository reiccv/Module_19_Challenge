# Module 19 Challenge

# Crypto Wallet

two Python files, both of which are contained in the starter folder.

The first file that you will use is called `fintech_finder.py`. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called `crypto_wallet.py`. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the `fintech_finder.py` file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.

## Imports

These are the libraries and dependecies needed to complete this challenge

![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/imports_crypto.PNG)


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/import_fin.PNG)


### Import Ethereum Transaction Functions into the Fintech Finder Application

import several functions from the `crypto_wallet.py` script into the file `fintech_finder.py`, which contains code for Fintech Finder’s customer interface, in order to add wallet operations to the application.


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/def_gen_account.PNG)


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/restof_crypto.PNG)

This is the code from `crypto_wallet.py` implemented and corrected into `fintech_finder.py` below

![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/streamfinder.PNG)

### Inspect the Transaction

To inspect the transaction we will run the file `fintech_finder.py` in our gitbash terminal
using streamlit

![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/tempsnip.png)

Our streamlit app is showing the correct wallet and shows it is connected with ganache

![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/fin_finder.PNG)


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/ganache_address.PNG)

The transaction goes through the blockchain, showing a block on ganache and updating our balance

![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/ganache_address.PNG)


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/ganache_block.PNG)


![](https://github.com/reiccv/Module_19_Challenge/blob/main/Images/ganache_block2.PNG)