# Cryptocurrency Wallet

![Blockchain Image](./assets/images/wallet.png)

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## The Application

<!--Below is an image of the application in use. There is a form to record and submit the `Sender`, `Reciever` and `Amount` of the cryptocurrency. Below this we see a public ledger that along with the Genesis block, has recorded several other blocks for transactions. Below the ledger is a button to validate the chain. Once clicked, it will display `True` or `False` depending on the validity of the chain. In the image we see `True` in green text below the button, indicating that the chain is valid. On the left side of the application we see a slider to select the difficulty of tha chain's hash. Below this we have a dropdown to select a specific block from the chain ledger. And below that in green text we see the values of the block.-->

![Landing Page](./assets/images/landing.png)

## Transaction

### Making Transaction

![App In Use](./assets/images/app.png)

### Transaction on Ganache

Sender
![Sender](./assets/images/sender.png)
Transaction History
![Transaction History](./assets/images/transaction_history.png)
Transaction
![Transaction](./assets/images/transaction.png)
Reciever
![Reciever](./assets/images/reciever.png)

## Getting Started

### Prerequisites

Download Ganache [here](https://trufflesuite.com/ganache/)

![Ganache](./assets/images/ganache.png)

You must have Python 3 & Pip installed

```
$ python3 --version
Output: Python 3.10.8
$ pip --verison
Ouput: pip 22.2.2 from /Users/{#Username}/opt/anaconda3/lib/python3.9/site-packages/pip (python 3.9)
```

### Installing Dependencies

```
$ pip install streamlit
$ pip install python-dotenv
$ pip install datetime
$ pip install pandas
$ pip install typing
$ pip install dataclasses
$ pip install bip44
$ pip install mnemonic
$ pip install eth-tester
$ pip install web3
$ pip show protobuf
$ pip install --upgrade protobuf
```

### Clone Repository
```
$ git clone git@github.com:SZun/Cryptocurrency-Wallet.git
$ cd PyChain-Ledger
```

### Run The Application
```
$ streamlit run krypto_jobs.py
```

## Built With
[![Python 3.7.13](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]([https://www.python.org/downloads/release/python-3713/)
[![Python](https://img.shields.io/badge/Python-3.7.13-blue)](https://www.python.org/downloads/release/python-3713/) - *Programming Language* <br>
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/) - *Web app generation tool* <br>
[![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/docs/#) - *Data analysis library*

### Python Libraries
- [dataclasses](https://docs.python.org/3/library/dataclasses.html)
- [datetime](https://docs.python.org/3/library/datetime.html)
- [hashlib](https://docs.python.org/3/library/hashlib.html)
- [typing](https://docs.python.org/3/library/typing.html)

## Contributors
- **Sam G. Zun** - [LinkedIn](https://www.linkedin.com/in/szun/) | [GitHub](https://github.com/SZun)