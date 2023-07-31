
# Fintech Finder

Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. Customers are able to instantly pay the fintech professionals whom they hire with cryptocurrency.

## Application Functionality

- Creates a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

- Fetches and display the account balance associated with the Ethereum account address on Ganache.

- Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

- Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

## Technologies

The program is based on Python 3 and require the following libraries/packages to function

Ganache <br>
Ganache is a personal blockchain for rapid Ethereum and Filecoin distributed application development. You can use Ganache across the entire development cycle; enabling you to develop, deploy, and test your dApps in a safe and deterministic environment.

Stremlit <br>
Streamlit lets you turn data scripts into shareable web apps in minutes, not weeks. It’s all Python, open-source, and free! And once you’ve created an app you can use our Community Cloud platform to deploy, manage, and share your app.


## Installation Guide

The user of the application will have to download Python,Python package manager PIP and Git.

   - [How to install Python](https://www.python.org/downloads/) 
   - [How to install Streamlit](https://docs.streamlit.io/library/get-started/installation)
   - [How to install Ganache](https://trufflesuite.com/ganache/)

* To the run the app, do the following:

```bash
$ git clone https://github.com/devops4cloud/fintech_finder.git
$ cd fintech_finder
$ streamlit run fintech_finder.py

```

## Application Usage

* Fintech Finder Application User Interface <br>
    <img title="Application UI" alt="Alt text" src="/Images/fintech_ui.png"> <br>


* Fintech Finder Ganache Wallet balance changes <br>
    <img title="Ganache Wallets" alt="Alt text" src="/Images/fintech_wallets.png"> <br>


* Fintech Finder Ganache Transactions
    <img title="Ganache Transactions" alt="Alt text" src="/Images/fintech_transactions.png"> <br>



