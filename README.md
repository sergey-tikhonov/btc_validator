# Bitcoin address validator
* Supports new and old addresses
* Based on `pybtc` and `base58` packages
* Requires no dependencies 
* Fixes bugs in `pybtc` implementation

## Supported addresses
* Mainnet 
* Testnet 
* Segwit
* Legacy

## Installation
```
pip3 install git+https://github.com/sergey-tikhonov/btc_validator
```

## Usage 
```python
from btc_validator import is_valid_btc_address

is_valid_btc_address(
    'bc1qw508d6qejxtdg4y5r3zarvary0c5xw7kv8f3t4'
)
>>> True

is_valid_btc_address(
    'tb1qrp33g0q5c5txsp9arysrx4k6zdkfs4nce4xj0gdcccefvpysxf3q0sl5k7',
    testnet=True,
)
>>> True
```
 
