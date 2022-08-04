# -Cryptocurrency-Wallet

# Homework_10_A_Yen_for_the_Future



## At a startup that I was tasked with building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.
The following code enables customers to send cryptocurrency payments to fintech professionals. ##
--------

## Technologies

```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import hashlib
from web3 import Web3
from web3 import Account, Web3
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
```

## Installation Guide

Before running the notebook, please install the dependencies:

```bash
pip install streamlit
pip install web3
From web Ganache
pip install requests
pip install dotenv
pip install os

```

---

## Observations

### The steps for this challenge are broken out into the following sections: ###

Import Ethereum Transaction Functions into the Fintech Finder Application
Sign and Execute a Payment Transaction
Inspect the Transaction on Ganache

Also note that in the end I also amended the code so that Lane had an account address that was from my current Ganache that was utilising my Ethereum account address. Therefore you will see in the code and the images that there is both a reduction in my wallet and the last transaction shows an increase in the wallet that I assigned to Lane.

![Lane_on_fintechfinder](Images/screenshots/fintech_finder.png)



![Price vs Trend](images/Price vs Trend.png)

![Noise](images/Noise.png)



![arma_fig](images/arma_fig.png)

![arima_fig](images/arima_fig.png)



![Composition_of_personal_savings](images/garch_fig.png)


# Conclusions


## Contributors

By: Roy Booker

---

## License

MIT
