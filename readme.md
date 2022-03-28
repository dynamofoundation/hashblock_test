
# Hashblock Algo test binaries

These Windows binaries will allow users to test the performance of algorithms without having to connect to testnet.




## Installation

Download and unzip the installation file into a directory.

Edit test_algo.txt to your liking.  The miner will only test one card at a time.

- First line is platform id
- Second line is device id
- Third line is compute units
- Fourth line is work size
- Remaining lines are algo to test


## Usage/Examples

```
testminer -mode testgpu
```
The miner will output average raw hashrate every 10 seconds as a whole number.
